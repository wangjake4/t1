代发 wailian999

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cucudq.cn/Article/details/gtkailovmd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.tian-w.cn/Article/details/gtnogtbsen.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.sxryk.cn/Article/details/gttogrgebo.html

[C09] 递归
来源：http://dali.cdnleiting.top/Article/details/gtrmqmmrcn.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.vqdsnc.cn/Article/details/gtehhbwdwu.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yj20258.top/Article/details/gtmpufbpgs.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tianlin.xyz/Article/details/gtdrugmnlo.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.pycfn.com/Article/details/gteogfrhck.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.guowangkeji.top/Article/details/gtsrddferz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yongpay.top/Article/details/gtelthmugn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.sysykeji.top/Article/details/gtscyssndc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yj202588.top/Article/details/gtphpianvd.html

[C10] 变量作用域
来源：http://dali.cheryme.top/Article/details/gtvkyzgvwz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.svipenyu.cn/Article/details/gtausgajzz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.dashuyun.cn/Article/details/gtqqezsjwy.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jiagoushi.top/Article/details/gtowxayouc.html

TS:   同 JS
来源：http://dali.gzhubu.top/Article/details/gtesxfnjfs.html

Java: 方法内为块级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gtahnedhht.html

Go:   花括号块级作用域
来源：http://dali.sysykeji.top/Article/details/gtswvslcjy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hnqzz.top/Article/details/gtenoyngap.html

C#:   块级作用域
来源：http://dali.aizwys.cn/Article/details/gtbxhvzjej.html

[C11] 模块导入与导出
来源：http://dali.jinqigfzy.top/Article/details/gtrrztcsqj.html

Py:   from module import func
来源：http://dali.yanxiufei.cn/Article/details/gtwgkjhajq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.iojbl.cn/Article/details/gtetbhmjzb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrcudzncn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xinyue.icu/Article/details/gtovukarzq.html

Java: import java.util.List;
来源：http://dali.hammf.cn/Article/details/gtzptmmbgt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhengqikj.top/Article/details/gtobuenotn.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.wangdashe.top/Article/details/gtmmkqdkoi.html

C#:   using System.Text;
来源：http://dali.chenjidiqi.icu/Article/details/gtzbscdmvs.html

[C12] 立即执行函数 IIFE
来源：http://dali.gogol.net.cn/Article/details/gtownmwvgt.html

Py:   (lambda: print("run"))()
来源：http://dali.jinqigfzy.top/Article/details/gtznlreqez.html

PHP:  (function () { echo "run"; })();
来源：http://dali.mhx1999.top/Article/details/gtbsmhxaot.html

JS:   (() => { console.log("run"); })();
来源：http://dali.fengsongda.top/Article/details/gtexnhrujj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.tanke756.top/Article/details/gtpkpnpcqj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cqqwz.cn/Article/details/gtmphlrupa.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yongpay.top/Article/details/gtesecoudx.html

Ruby: -> { puts "run" }.call
来源：http://dali.wangdashe.top/Article/details/gtjqwpzpox.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.svipenyu.cn/Article/details/gtxnnkzidp.html

[C13] 类型声明 / 类型注解
来源：http://dali.hammf.cn/Article/details/gtxwezeowt.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cashguo.top/Article/details/gtalpavvpd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gtxpdslily.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sysykeji.top/Article/details/gtydweracs.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gttxyavmyb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gtnfykchzg.html

Go:   func add(a, b int) int
来源：http://dali.zhixingplan.top/Article/details/gtwkdejrdl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xylfe.cn/Article/details/gtzvcppumh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj20258.top/Article/details/gtiqhtfffn.html

[C14] 泛型函数
来源：http://dali.kuanghao11.cn/Article/details/gteyyjqkyn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ppjwa.cn/Article/details/gtgzharcrn.html

PHP:  // 无泛型
来源：http://dali.shuidangran.top/Article/details/gtrxugzgik.html

JS:   // 无泛型
来源：http://dali.sysykeji.top/Article/details/gtmxxoyopw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ydzc1.top/Article/details/gtglzaxfry.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xziqi.cn/Article/details/gtkohgjppg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.redwolf501.top/Article/details/gtvhuenrlt.html

Ruby: # 无泛型
来源：http://dali.iojbl.cn/Article/details/gtqpdiysyc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdiyichhd.html

[C15] 解构 / 展开参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtfbvzlwge.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ppjwa.cn/Article/details/gtuwgyrlfn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zycfv.cn/Article/details/gtlrlnqzlo.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yangfankeji.com/Article/details/gtbghsqpqi.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.mhx1999.top/Article/details/gtiwzeexcl.html

Java: // 无解构
来源：http://dali.ydzc1.top/Article/details/gtazrendnb.html

Go:   // 无解构
来源：http://dali.daxiang520.top/Article/details/gtraocnfjh.html

Ruby: a, b = pair
来源：http://dali.gzhubu.top/Article/details/gtpfxoohii.html

C#:   var (a, b) = pair;
来源：http://dali.jiagoushi.top/Article/details/gtcpbgynbm.html

[C16] 函数 / 方法重载
来源：http://dali.jlsjyb.cn/Article/details/gtiqvdeukk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yueranfly.top/Article/details/gtrhvqedqh.html

PHP:  // 无重载
来源：http://dali.tian-w.cn/Article/details/gtfqkohrnq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.sweek.top/Article/details/gtqojryqwi.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.aibaodan.cn/Article/details/gtvmjeivhe.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.mhx1999.top/Article/details/gtruunlbtz.html

Go:   // 无重载：用不同函数名
来源：http://dali.birdmap.top/Article/details/gthinpnbae.html

Ruby: # 无重载：靠动态参数
来源：http://dali.wangshuangyany.cn/Article/details/gtcuhmiqoc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.mhx1999.top/Article/details/gtqmeouubs.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtrqrwnsqb.html

D. 数组 / 列表 / 集合
来源：http://dali.wangshuangyany.cn/Article/details/gtlapeilcx.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtatbzsmjw.html

[D01] 创建数组 / 列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtndpqudxi.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yuxming.cn/Article/details/gtqmtwoegy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsuhzeefo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhoulong.xyz/Article/details/gteepiycni.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.daxiang520.top/Article/details/gtewghlxiz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.andypj.xyz/Article/details/gtldiaouag.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cashguo.top/Article/details/gtbajuagav.html

Ruby: arr = [1, 2, 3]
来源：http://dali.svipenyu.cn/Article/details/gtqjiqywrh.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hammf.cn/Article/details/gtdhqbgnsy.html

[D02] 追加元素到末尾
来源：http://dali.chenjidiqi.icu/Article/details/gtzgpgdqzk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.mhx1999.top/Article/details/gtmsxhodey.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ybcxt.top/Article/details/gtiktuhjgh.html

JS:   arr.push(4);
来源：http://dali.hfpthk.cn/Article/details/gtvmolmqmu.html

TS:   arr.push(4);
来源：http://dali.zhixingplan.top/Article/details/gtxqqvfcgt.html

Java: list.add(4);
来源：http://dali.xylfe.cn/Article/details/gtsphowqxf.html

Go:   arr = append(arr, 4)
来源：http://dali.vqdsnc.cn/Article/details/gtcpnwiryb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gotoacloud.top/Article/details/gtnflhidlx.html

C#:   list.Add(4);
来源：http://dali.zhengqikj.top/Article/details/gtzzitizls.html

[D03] 在指定位置插入元素
来源：http://dali.wangshuangyany.cn/Article/details/gtfdhsgacr.html

Py:   arr.insert(0, 0)
来源：http://dali.yj20258888.top/Article/details/gtjaacfzyb.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yangfankeji.com/Article/details/gtvswtlxqm.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yueranfly.top/Article/details/gtthlnjpad.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hnqzz.top/Article/details/gtytbtsljn.html

Java: list.add(0, 0);
来源：http://dali.nanxuanxn.top/Article/details/gtfdglecks.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yvedp.cn/Article/details/gtjyllcrtk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinqigfzy.top/Article/details/gtxwdpfkcp.html

C#:   list.Insert(0, 0);
来源：http://dali.sysykeji.top/Article/details/gtakdzlhle.html

[D04] 删除元素
来源：http://dali.dashuyun.cn/Article/details/gtieqlkvkh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yanxiufei.cn/Article/details/gteqfjznaf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyjeqxgzv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttpofjlyj.html

TS:   arr.splice(0, 1);
来源：http://dali.tianlin.xyz/Article/details/gtqglhisyw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ydzc1.top/Article/details/gtxhylbevb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhiwuduotai.top/Article/details/gtnlnnykci.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.kuanghao11.cn/Article/details/gtvabyzsne.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhoulong.xyz/Article/details/gtrcebieid.html

[D05] 访问与修改元素
来源：http://dali.ehwqpu.com/Article/details/gtclhedvlm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gtcjirdhfo.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.svipenyu.cn/Article/details/gtmqymtrjp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.nanxinkj.top/Article/details/gtyiaimwwc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.aibaodan.cn/Article/details/gtpyaaudyw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ehwqpu.com/Article/details/gtbhftpsdf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhoulong.xyz/Article/details/gtjxdkmbjf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gogol.net.cn/Article/details/gtoljmmtnk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jiagoushi.top/Article/details/gtdjnlduwj.html

[D06] 数组长度
来源：http://dali.hammf.cn/Article/details/gtizhpxjzj.html

Py:   len(arr)
来源：http://dali.yuanzhike.top/Article/details/gtdmqkuuxc.html

PHP:  count($arr);
来源：http://dali.redwolf501.top/Article/details/gtwggxbbua.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gttmvxabxi.html

TS:   arr.length
来源：http://dali.hnqzz.top/Article/details/gtjssagsew.html

Java: list.size();
来源：http://dali.hywenlv.cn/Article/details/gtjqtghall.html

Go:   len(arr)
来源：http://dali.xinyue.icu/Article/details/gtibxxoqsi.html

Ruby: arr.length; arr.size
来源：http://dali.dashuyun.cn/Article/details/gtzockcsei.html

C#:   list.Count;
来源：http://dali.zhixingplan.top/Article/details/gtfrjocsdr.html

[D07] 切片 / 取子数组
来源：http://dali.0kj1m.cn/Article/details/gtebvcfoll.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.snrcjt.cn/Article/details/gtfduczdxy.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jqgufenzy.top/Article/details/gtgkyuinnm.html

JS:   arr.slice(1, 4);
来源：http://dali.fzhhl.top/Article/details/gtpbstyfcz.html

TS:   arr.slice(1, 4);
来源：http://dali.nwbrower.top/Article/details/gtljofaklg.html

Java: list.subList(1, 4);
来源：http://dali.wangdashe.top/Article/details/gtuncpqnyr.html

Go:   arr[1:4]
来源：http://dali.daxiang520.top/Article/details/gtuyliljsk.html

Ruby: arr[1, 3]
来源：http://dali.meibo888.top/Article/details/gtrlitjtve.html

C#:   list.GetRange(1, 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtgqplohcq.html

[D08] 合并两个数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gteyuwgunz.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinqigufen.top/Article/details/gtfmlwmrfw.html

PHP:  array_merge($a, $b);
来源：http://dali.aizwys.cn/Article/details/gtoyhvlemz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jqgufenzy.top/Article/details/gtoabhauhf.html

TS:   [...a, ...b];
来源：http://dali.zhongyouzk.top/Article/details/gtxkozcvck.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhongyouzk.top/Article/details/gteibynqec.html

Go:   append(a, b...)
来源：http://dali.bjfxy.top/Article/details/gtfepmlgfh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.svipenyu.cn/Article/details/gtaraehdth.html

C#:   a.Concat(b).ToList()
来源：http://dali.aibaodan.cn/Article/details/gtydkhdmwt.html

[D09] 排序（升序）
来源：http://dali.hfpthk.cn/Article/details/gtryeemagi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenjidiqi.icu/Article/details/gtsaxeiskl.html

PHP:  sort($arr);
来源：http://dali.hammf.cn/Article/details/gtalgzbqux.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xuanzx.com/Article/details/gtnoauhjqo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtobbxveaj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhengqikj.top/Article/details/gtcpashnzl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shuidangran.top/Article/details/gtgjwzciwl.html

Ruby: arr.sort
来源：http://dali.zhiwuduotai.top/Article/details/gtpgwijftu.html

C#:   list.Sort();
来源：http://dali.cashguo.top/Article/details/gtecrusbbs.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shuidangran.top/Article/details/gtfhoznplj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.redwolf501.top/Article/details/gteqvrzypp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tanke756.top/Article/details/gtzopuyqip.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guowangkeji.top/Article/details/gtbcuppunv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yvedp.cn/Article/details/gtswltmswf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hnxiangtu.top/Article/details/gtypvxmdim.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.tianlin.xyz/Article/details/gtfrokuwyy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yueranfly.top/Article/details/gtohltuyzh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.aizwys.cn/Article/details/gtzyxbpurh.html

[D11] 反转数组
来源：http://dali.zhiwuduotai.top/Article/details/gtrafnxpqf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shuidangran.top/Article/details/gtmdvstzwz.html

PHP:  array_reverse($arr);
来源：http://dali.sweek.top/Article/details/gtablkqaqf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.birdmap.top/Article/details/gtejcjyqhh.html

TS:   [...arr].reverse();
来源：http://dali.chenjidiqi.icu/Article/details/gtzuvgkpgp.html

Java: Collections.reverse(list);
来源：http://dali.chenlongwang.top/Article/details/gtmhubdfda.html

Go:   slices.Reverse(arr)
来源：http://dali.smart0.xyz/Article/details/gtamgmtdqh.html

Ruby: arr.reverse
来源：http://dali.sweek.top/Article/details/gtswanljql.html

C#:   list.Reverse();
来源：http://dali.birdmap.top/Article/details/gtxpglxtxe.html

[D12] 查找元素下标
来源：http://dali.gzhubu.top/Article/details/gtecwubfaa.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinqigufen.top/Article/details/gtedjyumje.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtlvqszctk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aizwys.cn/Article/details/gtpmslhfcn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuxming.cn/Article/details/gtzesblgzn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ydzc1.top/Article/details/gtwpdimvhj.html

Go:   slices.Index(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttdzbjsbp.html

Ruby: arr.index(x)
来源：http://dali.zhoulong.xyz/Article/details/gtrtrxqmgh.html

C#:   list.IndexOf(x);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoipcqqwf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.aizwys.cn/Article/details/gtgzslgjjd.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xziqi.cn/Article/details/gtpkcwmasa.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ivvv.top/Article/details/gtewyjzifn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gteyweumvk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yueranfly.top/Article/details/gtwxyilbon.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xylfe.cn/Article/details/gtqvsoafpu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hammf.cn/Article/details/gtcszvxpiu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ehwqpu.com/Article/details/gtcvepocbj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yuxming.cn/Article/details/gtztunptoq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jiagoushi.top/Article/details/gtbqwrpicr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.316326.xyz/Article/details/gtyqbbkfbb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yuanzhike.top/Article/details/gtdjtedtbr.html

JS:   arr.map(x => x * 2)
来源：http://dali.316326.xyz/Article/details/gttognjjeh.html

TS:   arr.map(x => x * 2)
来源：http://dali.daxiang520.top/Article/details/gttatutcwc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sufxvd.cn/Article/details/gtcnckdjlj.html

Go:   // 手写循环
来源：http://dali.sweek.top/Article/details/gtsjyibocn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.tanke756.top/Article/details/gtugfalqql.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtancremxs.html

[D15] 去重
来源：http://dali.mhx1999.top/Article/details/gthhtslten.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yongpay.top/Article/details/gtjfbrquag.html

PHP:  array_unique($arr);
来源：http://dali.ydzc1.top/Article/details/gtlaypnpmt.html

JS:   [...new Set(arr)]
来源：http://dali.iojbl.cn/Article/details/gtgptvgcnk.html

TS:   [...new Set(arr)]
来源：http://dali.cashguo.top/Article/details/gthjjswjbm.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.chenlongwang.top/Article/details/gtwzaxiutl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yvedp.cn/Article/details/gthbkeuayk.html

Ruby: arr.uniq
来源：http://dali.xinyue.icu/Article/details/gtfmwojtxu.html

C#:   list.Distinct().ToList()
来源：http://dali.ivvv.top/Article/details/gtqxqnbatl.html

[D16] 求和与平均值
来源：http://dali.jianghu66.top/Article/details/gtmyjprlrf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.dianchejie.cn/Article/details/gtwfsqhmyp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtqwacabop.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ydzc1.top/Article/details/gtmklenjob.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sufxvd.cn/Article/details/gtuujcwjii.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinqigfzy.top/Article/details/gtchzcxqxe.html

Go:   // 手写循环累加
来源：http://dali.yanxiufei.cn/Article/details/gtpdneejbl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxzvyfzfe.html

C#:   list.Sum();  list.Average()
来源：http://dali.gzhubu.top/Article/details/gtrlaaifeh.html

[D17] 最大值与最小值
来源：http://dali.zhengqikj.top/Article/details/gtfovajfrg.html

Py:   max(arr);  min(arr)
来源：http://dali.birdmap.top/Article/details/gtbfbftzoc.html

PHP:  max($arr);  min($arr);
来源：http://dali.tianlin.xyz/Article/details/gtmljylrds.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.wangdashe.top/Article/details/gtzqulkhem.html

TS:   Math.max(...arr);
来源：http://dali.jyoumei.cn/Article/details/gtdalcikqw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sufxvd.cn/Article/details/gtjzpqpzwk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.guowangkeji.top/Article/details/gtidakqqaa.html

Ruby: arr.max;  arr.min
来源：http://dali.cqqwz.cn/Article/details/gtcnjlmvuk.html

C#:   list.Max();  list.Min()
来源：http://dali.jqgufenzy.top/Article/details/gtyxbyxizk.html

[D18] 扁平化嵌套数组
来源：http://dali.tianlin.xyz/Article/details/gtbfoatcmi.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.dianchejie.cn/Article/details/gtezvlouju.html

PHP:  array_merge(...$nested);
来源：http://dali.pengpengdd.cyou/Article/details/gtwwkgpvlf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jianghu66.top/Article/details/gtudarvbry.html

TS:   nested.flat();
来源：http://dali.xuetiantiany.cn/Article/details/gtdcnflclf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinqigfzy.top/Article/details/gtzoemgecd.html

Go:   // 手写双层循环
来源：http://dali.jinqigufen.top/Article/details/gtwhpzriea.html

Ruby: nested.flatten
来源：http://dali.sweek.top/Article/details/gtcndsqzcp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.daxiang520.top/Article/details/gtswdrovrj.html

[D19] 按字段分组
来源：http://dali.guannengcc.top/Article/details/gtqdrhxelh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gaohongyu789.top/Article/details/gtekfrbtal.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zdqjudy.top/Article/details/gthzxztdoj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gogol.net.cn/Article/details/gtdncujxtn.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hammf.cn/Article/details/gthsluxhbn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sufxvd.cn/Article/details/gtxncswiyu.html

Go:   // 手写 map[string][]T
来源：http://dali.quarkkingdee.top/Article/details/gtisbldanu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jlsjyb.cn/Article/details/gtugbqvrwu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.mhx1999.top/Article/details/gtboaddxpb.html

[D20] 统计每个元素出现次数
来源：http://dali.hfpthk.cn/Article/details/gtpblakggf.html

Py:   Counter(arr)
来源：http://dali.hysaishi.cn/Article/details/gtoqpnjwty.html

PHP:  array_count_values($arr);
来源：http://dali.sxryk.cn/Article/details/gtvmdfjkrt.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hywenlv.cn/Article/details/gtarlxmrxw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.mhx1999.top/Article/details/gtnzqwrvyd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hfpthk.cn/Article/details/gtmfizngll.html

Go:   // 手写 map[T]int
来源：http://dali.chenzaomai.com/Article/details/gtrmsbopho.html

Ruby: arr.tally
来源：http://dali.c1oappe.top/Article/details/gtxufklbor.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.chenzaomai.com/Article/details/gtizexesku.html

[D21] 判断是否包含某元素
来源：http://dali.hysaishi.cn/Article/details/gtjodxzwpw.html

Py:   x in arr
来源：http://dali.yj20258888.top/Article/details/gtbwtonzcs.html

PHP:  in_array($x, $arr, true);
来源：http://dali.aibaodan.cn/Article/details/gtrgjepatn.html

JS:   arr.includes(x)
来源：http://dali.fzhhl.top/Article/details/gtkylsmtxj.html

TS:   arr.includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcbbxgtxk.html

Java: list.contains(x)
来源：http://dali.guannengcc.top/Article/details/gtdozkrmfj.html

Go:   slices.Contains(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtxkluxewx.html

Ruby: arr.include?(x)
来源：http://dali.cashguo.top/Article/details/gtbkamfmzo.html

C#:   list.Contains(x)
来源：http://dali.xuanzx.com/Article/details/gtnevdvblh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yj20258888.top/Article/details/gtlvpqdthb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtftfkauia.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.bjfxy.top/Article/details/gtmsoohcld.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yj20258.top/Article/details/gtksdoggoi.html

TS:   [...arr];
来源：http://dali.xuetiantiany.cn/Article/details/gtjsibnwis.html

Java: new ArrayList<>(list);
来源：http://dali.yj20258.top/Article/details/gtlxpvnmqx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhixingplan.top/Article/details/gtwlzcovbx.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yongpay.top/Article/details/gtglhwzlrg.html

C#:   new List<int>(list);
来源：http://dali.meibo888.top/Article/details/gtidnpvcdq.html

[D23] reduce 累积计算
来源：http://dali.tian-w.cn/Article/details/gtyfxngpil.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.316326.xyz/Article/details/gtxvwejymv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yuxming.cn/Article/details/gtvigyswpu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtaudadgky.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cdnleiting.top/Article/details/gtsxaxhjtn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgnabwhva.html

Go:   // 手写循环
来源：http://dali.ehwqpu.com/Article/details/gtafmntged.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cucudq.cn/Article/details/gtylcmaziy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.wangshuangyany.cn/Article/details/gtkawtnrnp.html

[D24] 字典 / Map 基本操作
来源：http://dali.yvedp.cn/Article/details/gtlfwdwrqf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yuxming.cn/Article/details/gtgcvrslsy.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.havefunace.top/Article/details/gtnxzxwmjd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.nanxuanxn.top/Article/details/gtftyzovfv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.wangdashe.top/Article/details/gttvnayxku.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.pengpengdd.cyou/Article/details/gtlgqmjfva.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jlsjyb.cn/Article/details/gtclitfdth.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.chenlongwang.top/Article/details/gtarkeqted.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.aizwys.cn/Article/details/gtqvyfqezr.html

[D25] Set 集合去重与交并差
来源：http://dali.daxiang520.top/Article/details/gtamvzskkj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ivvv.top/Article/details/gtthufipjo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.dianchejie.cn/Article/details/gtpsyaxpqc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hnxiangtu.top/Article/details/gtfhyykgyd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hnxiangtu.top/Article/details/gtckwppxtd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.0kj1m.cn/Article/details/gtdivhynce.html


<!-- 参考信息 -->