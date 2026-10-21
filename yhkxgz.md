代发 wailian999

[C10] 变量作用域
来源：http://dali.tanke756.top/Article/details/gtcrcksdnr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yuxming.cn/Article/details/gtgewmgrcf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.aizwys.cn/Article/details/gttphgglso.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.mhx1999.top/Article/details/gtzhhtwkin.html

TS:   同 JS
来源：http://dali.chenlongwang.top/Article/details/gtzzevpahf.html

Java: 方法内为块级作用域
来源：http://dali.jyoumei.cn/Article/details/gtpkoyaybd.html

Go:   花括号块级作用域
来源：http://dali.jianghu66.top/Article/details/gtdmcaovha.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hywenlv.cn/Article/details/gtvkztdila.html

C#:   块级作用域
来源：http://dali.zhoulong.xyz/Article/details/gtoeuvtwng.html

[C11] 模块导入与导出
来源：http://dali.cqqwz.cn/Article/details/gtjsvzybdq.html

Py:   from module import func
来源：http://dali.zhixingplan.top/Article/details/gtbxveoona.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hammf.cn/Article/details/gtmhadcwqf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hammf.cn/Article/details/gtkuqishsq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.fzhhl.top/Article/details/gtgwacotta.html

Java: import java.util.List;
来源：http://dali.tian-w.cn/Article/details/gtqyuunfpm.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.c1oappe.top/Article/details/gtvfobrvpv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yanxiufei.cn/Article/details/gtmdscvgqn.html

C#:   using System.Text;
来源：http://dali.xuetiantiany.cn/Article/details/gtuvpxvayn.html

[C12] 立即执行函数 IIFE
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtezaaqupi.html

Py:   (lambda: print("run"))()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtebcqieqs.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jlsjyb.cn/Article/details/gtfhtpskst.html

JS:   (() => { console.log("run"); })();
来源：http://dali.mhx1999.top/Article/details/gtbzykqcyv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zdqjudy.top/Article/details/gtwkzasphp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.meibo888.top/Article/details/gtzigcvkpi.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhoulong.xyz/Article/details/gtoburhbsa.html

Ruby: -> { puts "run" }.call
来源：http://dali.ybcxt.top/Article/details/gttrivxikj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtjpskvkar.html

[C13] 类型声明 / 类型注解
来源：http://dali.hywenlv.cn/Article/details/gtsapplsvh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ppjwa.cn/Article/details/gtieunlbrr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gtaxrtgwur.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ppjwa.cn/Article/details/gtgedpgwmu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gtzetourlv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gtkbbnspcj.html

Go:   func add(a, b int) int
来源：http://dali.shanyushiyangtech.top/Article/details/gtwwpxsjnp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.chenzaomai.com/Article/details/gtvmvtsyao.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.redwolf501.top/Article/details/gtspkuobrv.html

[C14] 泛型函数
来源：http://dali.cashguo.top/Article/details/gtzbeqtfzi.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cdnleiting.top/Article/details/gtlhwvgeok.html

PHP:  // 无泛型
来源：http://dali.yvedp.cn/Article/details/gtegqfbrjq.html

JS:   // 无泛型
来源：http://dali.jqgufenzy.top/Article/details/gteuaxyxap.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hammf.cn/Article/details/gthyjaieca.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.mhx1999.top/Article/details/gtfgfceuzx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ivvv.top/Article/details/gtbuhujwlt.html

Ruby: # 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gtemfudmvd.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xinyue.icu/Article/details/gtilbqaumz.html

[C15] 解构 / 展开参数
来源：http://dali.nanxinkj.top/Article/details/gtskcjrxoa.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhixingplan.top/Article/details/gttaxatjcb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jqgufenzy.top/Article/details/gtrlvwedof.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.dashuyun.cn/Article/details/gthtrgeahz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yj20258888.top/Article/details/gtymwfwpbv.html

Java: // 无解构
来源：http://dali.nanxuanxn.top/Article/details/gtuojapnru.html

Go:   // 无解构
来源：http://dali.aibaodan.cn/Article/details/gtedmpetrj.html

Ruby: a, b = pair
来源：http://dali.hnqzz.top/Article/details/gtbcmbamqk.html

C#:   var (a, b) = pair;
来源：http://dali.ybcxt.top/Article/details/gtdyxlcszg.html

[C16] 函数 / 方法重载
来源：http://dali.jyoumei.cn/Article/details/gtxboehgjb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.wangdashe.top/Article/details/gtgvvhkmbr.html

PHP:  // 无重载
来源：http://dali.mhx1999.top/Article/details/gtihellnuj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hywenlv.cn/Article/details/gtazcrpqhi.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yonumen.top/Article/details/gtruwkgwsl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hammf.cn/Article/details/gttpebccgl.html

Go:   // 无重载：用不同函数名
来源：http://dali.yuxming.cn/Article/details/gtkmqwgstw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yj20258.top/Article/details/gtydsnymnu.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ehwqpu.com/Article/details/gttbxwbnau.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtgeaflsfo.html

D. 数组 / 列表 / 集合
来源：http://dali.316326.xyz/Article/details/gtqwzrulys.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtwymyjzbq.html

[D01] 创建数组 / 列表
来源：http://dali.shanyushiyangkeji.top/Article/details/gthvmirtea.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yonumen.top/Article/details/gthfpauzsl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hywenlv.cn/Article/details/gtuenyxuow.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jyoumei.cn/Article/details/gtrtvntznx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhoulong.xyz/Article/details/gturungfck.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shangyingyoupin.top/Article/details/gtunoedmcn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.wangshuangyany.cn/Article/details/gtgsntmkll.html

Ruby: arr = [1, 2, 3]
来源：http://dali.snrcjt.cn/Article/details/gtmdbqlrhu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.birdmap.top/Article/details/gtokxzxidn.html

[D02] 追加元素到末尾
来源：http://dali.xinyue.icu/Article/details/gtsowlaxiz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.pengpengdd.cyou/Article/details/gtfysqbobe.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cucudq.cn/Article/details/gtkxmwsdcc.html

JS:   arr.push(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrlgwtzrr.html

TS:   arr.push(4);
来源：http://dali.xziqi.cn/Article/details/gtgpnxdhrn.html

Java: list.add(4);
来源：http://dali.fengsongda.top/Article/details/gtfmczncgk.html

Go:   arr = append(arr, 4)
来源：http://dali.tianlin.xyz/Article/details/gtcqnvsnwq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.wangdashe.top/Article/details/gtzqtonjip.html

C#:   list.Add(4);
来源：http://dali.sxryk.cn/Article/details/gtbffdmfqs.html

[D03] 在指定位置插入元素
来源：http://dali.iojbl.cn/Article/details/gtcwurpmhe.html

Py:   arr.insert(0, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtoqxtgges.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.meibo888.top/Article/details/gtlqmsbqri.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.andypj.xyz/Article/details/gtavtkuqez.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.tianlin.xyz/Article/details/gtgxgwmvby.html

Java: list.add(0, 0);
来源：http://dali.sweek.top/Article/details/gtwoghwqrs.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.andypj.xyz/Article/details/gtrvbcdmxq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.c1oappe.top/Article/details/gtxzbgwiyh.html

C#:   list.Insert(0, 0);
来源：http://dali.haohaochexian.top/Article/details/gtbbjcauqy.html

[D04] 删除元素
来源：http://dali.hysaishi.cn/Article/details/gtinxbztia.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.nwbrower.top/Article/details/gtzoixenss.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtooqfzqss.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gogol.net.cn/Article/details/gtfghysfke.html

TS:   arr.splice(0, 1);
来源：http://dali.0kj1m.cn/Article/details/gtsdrgrzcb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yueranfly.top/Article/details/gtbgeaxmkq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nanxuanxn.top/Article/details/gtasihfkoh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cashguo.top/Article/details/gtpksefxlw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.feifeiyinyue.top/Article/details/gtkjmsbvpr.html

[D05] 访问与修改元素
来源：http://dali.ybcxt.top/Article/details/gtpwljdifg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.redwolf501.top/Article/details/gtmgpeqbmf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gtmdndnexf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gotoacloud.top/Article/details/gtyirfufjg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gzhubu.top/Article/details/gtljexbqhj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.pengpengdd.cyou/Article/details/gtudmetnwp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.guannengcc.top/Article/details/gtclfpbnep.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cashguo.top/Article/details/gtbmfyooez.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ehwqpu.com/Article/details/gtognncrsb.html

[D06] 数组长度
来源：http://dali.hnqzz.top/Article/details/gtfvpwylxp.html

Py:   len(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcgkqglxy.html

PHP:  count($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtdzqiyygh.html

JS:   arr.length
来源：http://dali.snrcjt.cn/Article/details/gtafrvxruf.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gtrqywgeob.html

Java: list.size();
来源：http://dali.hywenlv.cn/Article/details/gtytigufhj.html

Go:   len(arr)
来源：http://dali.yangfankeji.com/Article/details/gtumepkggi.html

Ruby: arr.length; arr.size
来源：http://dali.xziqi.cn/Article/details/gtuuicqxld.html

C#:   list.Count;
来源：http://dali.hywenlv.cn/Article/details/gtvjzokqlp.html

[D07] 切片 / 取子数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwptntpfa.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zdqjudy.top/Article/details/gtsnuiylmp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtwumjrtgd.html

JS:   arr.slice(1, 4);
来源：http://dali.ybcxt.top/Article/details/gtjlpccnzk.html

TS:   arr.slice(1, 4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthcbyalav.html

Java: list.subList(1, 4);
来源：http://dali.cdnleiting.top/Article/details/gtduxqwffn.html

Go:   arr[1:4]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtizrtynji.html

Ruby: arr[1, 3]
来源：http://dali.ydzc1.top/Article/details/gtglyvgaxn.html

C#:   list.GetRange(1, 3);
来源：http://dali.ivvv.top/Article/details/gtyssbmfil.html

[D08] 合并两个数组
来源：http://dali.nanxuanxn.top/Article/details/gtmqrraaoc.html

Py:   a + b;  a.extend(b)
来源：http://dali.yj20258888.top/Article/details/gtpztjhfuw.html

PHP:  array_merge($a, $b);
来源：http://dali.cashguo.top/Article/details/gtqcvujznr.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.haohaochexian.top/Article/details/gtmiwaqouc.html

TS:   [...a, ...b];
来源：http://dali.snrcjt.cn/Article/details/gtbadvtyvu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhixingplan.top/Article/details/gtaeoiilqp.html

Go:   append(a, b...)
来源：http://dali.nanxuanxn.top/Article/details/gtacjomntc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtduqtmcwg.html

C#:   a.Concat(b).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtznzndtwz.html

[D09] 排序（升序）
来源：http://dali.guannengcc.top/Article/details/gtztprlktf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.kuanghao11.cn/Article/details/gtaaqcqcca.html

PHP:  sort($arr);
来源：http://dali.daxiang520.top/Article/details/gtpfyojeex.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yj20258888.top/Article/details/gtoqypwvvm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xinyue.icu/Article/details/gtbidmcopv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shangyingyoupin.top/Article/details/gtumxmdhxq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinqigufen.top/Article/details/gteasbatrd.html

Ruby: arr.sort
来源：http://dali.gogol.net.cn/Article/details/gtdjmsgjds.html

C#:   list.Sort();
来源：http://dali.shzxlz.cn/Article/details/gtambsiqlp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.tian-w.cn/Article/details/gtbdxqruiq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cucudq.cn/Article/details/gtqffgtodu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenzaomai.com/Article/details/gtwijtirtd.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhengqikj.top/Article/details/gtpzqrxvyn.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guowangkeji.top/Article/details/gthfhdqpud.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.wangshuangyany.cn/Article/details/gtxxtqbofr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.vqdsnc.cn/Article/details/gtddecfbmq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xuanzx.com/Article/details/gthpgjjbpk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.feifeiyinyue.top/Article/details/gtdmmymicn.html

[D11] 反转数组
来源：http://dali.xziqi.cn/Article/details/gtxjkjclxo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.snrcjt.cn/Article/details/gtcapiaeua.html

PHP:  array_reverse($arr);
来源：http://dali.dashuyun.cn/Article/details/gtxaggtiap.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sxryk.cn/Article/details/gtmhfykhlw.html

TS:   [...arr].reverse();
来源：http://dali.birdmap.top/Article/details/gtdswecqjd.html

Java: Collections.reverse(list);
来源：http://dali.yuxming.cn/Article/details/gtjseudubc.html

Go:   slices.Reverse(arr)
来源：http://dali.redwolf501.top/Article/details/gtvcjouuaw.html

Ruby: arr.reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gtgrpmtihr.html

C#:   list.Reverse();
来源：http://dali.smart0.xyz/Article/details/gtcntbepzu.html

[D12] 查找元素下标
来源：http://dali.feifeiyinyue.top/Article/details/gtfcommqrv.html

Py:   arr.index(x);  x in arr
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlbbeteea.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.chenlongwang.top/Article/details/gtvtifbjiq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tian-w.cn/Article/details/gtkxypgnvl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhixingplan.top/Article/details/gtuouhjjap.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.nanxuanxn.top/Article/details/gtfwdjtsii.html

Go:   slices.Index(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gtkzazuwll.html

Ruby: arr.index(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtiliohvie.html

C#:   list.IndexOf(x);
来源：http://dali.guannengcc.top/Article/details/gtynuuxgit.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gogol.net.cn/Article/details/gttawpcyly.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hongshengwenyu.top/Article/details/gtdsltcqiv.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cdnleiting.top/Article/details/gtogahvckx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.guannengcc.top/Article/details/gtnlxoceot.html

TS:   arr.filter(x => x > 3)
来源：http://dali.tanke756.top/Article/details/gtfycewvtp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.dashuyun.cn/Article/details/gtpsbgqrix.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.aizwys.cn/Article/details/gttzbhycht.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tian-w.cn/Article/details/gtrtdyqpqc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jianghu66.top/Article/details/gtslrxhcih.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xuanzx.com/Article/details/gtglgougyg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yueranfly.top/Article/details/gtnzevtcyx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenzaomai.com/Article/details/gtefakjdfv.html

JS:   arr.map(x => x * 2)
来源：http://dali.hnxiangtu.top/Article/details/gtigjzkzhj.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtetoxpras.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jlsjyb.cn/Article/details/gturvrcbwv.html

Go:   // 手写循环
来源：http://dali.jiagoushi.top/Article/details/gtgaxjfcnk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.fengsongda.top/Article/details/gtehomfmqn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtglwysmrp.html

[D15] 去重
来源：http://dali.316326.xyz/Article/details/gtqudqjoft.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xuetiantiany.cn/Article/details/gtntufqgqz.html

PHP:  array_unique($arr);
来源：http://dali.iojbl.cn/Article/details/gtofsskpol.html

JS:   [...new Set(arr)]
来源：http://dali.yanxiufei.cn/Article/details/gtvqcaicil.html

TS:   [...new Set(arr)]
来源：http://dali.hfpthk.cn/Article/details/gtmzrqqtbt.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cashguo.top/Article/details/gtewdlnili.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhixingplan.top/Article/details/gtqhjhpjyg.html

Ruby: arr.uniq
来源：http://dali.9152youxi.cn/Article/details/gtxrmwodin.html

C#:   list.Distinct().ToList()
来源：http://dali.yueranfly.top/Article/details/gtvlcdhfqr.html

[D16] 求和与平均值
来源：http://dali.kuanghao11.cn/Article/details/gtwlgijtib.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yvedp.cn/Article/details/gtrxgiijln.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtncqzylrd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nwbrower.top/Article/details/gtjakadspl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuanzx.com/Article/details/gtrqjizxbp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.snrcjt.cn/Article/details/gtdzldokkn.html

Go:   // 手写循环累加
来源：http://dali.hongshengwenyu.top/Article/details/gtjbcuymyw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jianghu66.top/Article/details/gtseyantld.html

C#:   list.Sum();  list.Average()
来源：http://dali.kuanghao11.cn/Article/details/gtanotnggu.html

[D17] 最大值与最小值
来源：http://dali.daria6918.cn/Article/details/gtjvxdjxqn.html

Py:   max(arr);  min(arr)
来源：http://dali.dashuyun.cn/Article/details/gtgprwczkc.html

PHP:  max($arr);  min($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtcbqczrsv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xuanzx.com/Article/details/gteaxcqkds.html

TS:   Math.max(...arr);
来源：http://dali.redwolf501.top/Article/details/gtotxaelmo.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ehwqpu.com/Article/details/gtffglhbbx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gotoacloud.top/Article/details/gtvkmjqsdz.html

Ruby: arr.max;  arr.min
来源：http://dali.9152youxi.cn/Article/details/gtxtrdvtey.html

C#:   list.Max();  list.Min()
来源：http://dali.havefunace.top/Article/details/gttqkbbevp.html

[D18] 扁平化嵌套数组
来源：http://dali.cucudq.cn/Article/details/gtuemyvysk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sysykeji.top/Article/details/gtowwscntx.html

PHP:  array_merge(...$nested);
来源：http://dali.c1oappe.top/Article/details/gtrfkiufyv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ehwqpu.com/Article/details/gtnnydcauw.html

TS:   nested.flat();
来源：http://dali.mhx1999.top/Article/details/gtycmpsgxz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.aibaodan.cn/Article/details/gtokjyzogx.html

Go:   // 手写双层循环
来源：http://dali.xuetiantiany.cn/Article/details/gtzzcnzebp.html

Ruby: nested.flatten
来源：http://dali.cashguo.top/Article/details/gtumgmfigx.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sweek.top/Article/details/gtojlyvlly.html

[D19] 按字段分组
来源：http://dali.tian-w.cn/Article/details/gteoejhlpp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtassilubr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yj202588.top/Article/details/gtzhcucyay.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sxryk.cn/Article/details/gtcgkkeprl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hywenlv.cn/Article/details/gtwcitntqq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.chenzaomai.com/Article/details/gtofjjsaej.html

Go:   // 手写 map[string][]T
来源：http://dali.jiagoushi.top/Article/details/gtpxdjupfy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.quarkkingdee.top/Article/details/gtwzuylyhy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.snrcjt.cn/Article/details/gtwnxcwwxe.html

[D20] 统计每个元素出现次数
来源：http://dali.fzhhl.top/Article/details/gtfdzaqpqm.html

Py:   Counter(arr)
来源：http://dali.gotoacloud.top/Article/details/gtficprmsj.html

PHP:  array_count_values($arr);
来源：http://dali.shuidangran.top/Article/details/gtfjlzyqym.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yueranfly.top/Article/details/gteqfdeadt.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dianchejie.cn/Article/details/gtolsbpime.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.aibaodan.cn/Article/details/gthqteqrjg.html

Go:   // 手写 map[T]int
来源：http://dali.yj20258.top/Article/details/gtkhxhfrgn.html

Ruby: arr.tally
来源：http://dali.vqdsnc.cn/Article/details/gtepgatufi.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jlsjyb.cn/Article/details/gtxejriotz.html

[D21] 判断是否包含某元素
来源：http://dali.cdnleiting.top/Article/details/gtedbfejvw.html

Py:   x in arr
来源：http://dali.snrcjt.cn/Article/details/gtfxcjhbkz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jianghu66.top/Article/details/gtunyfulsu.html

JS:   arr.includes(x)
来源：http://dali.fzhhl.top/Article/details/gteyaddome.html

TS:   arr.includes(x)
来源：http://dali.dashuyun.cn/Article/details/gtapebgsrw.html

Java: list.contains(x)
来源：http://dali.jiagoushi.top/Article/details/gtmdlmjjmm.html

Go:   slices.Contains(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtfsbpgovt.html

Ruby: arr.include?(x)
来源：http://dali.xylfe.cn/Article/details/gtvwvywtjf.html

C#:   list.Contains(x)
来源：http://dali.tianlin.xyz/Article/details/gtxhwxunhh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.wangdashe.top/Article/details/gtawahsufw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hnqzz.top/Article/details/gtntqnpaeg.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ivvv.top/Article/details/gtoneugxka.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cheryme.top/Article/details/gtmxjbarcj.html

TS:   [...arr];
来源：http://dali.iojbl.cn/Article/details/gttsbmvzxj.html

Java: new ArrayList<>(list);
来源：http://dali.jianghu66.top/Article/details/gtsmynvyqh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgwzlezfz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gtfkzpwhau.html

C#:   new List<int>(list);
来源：http://dali.shzxlz.cn/Article/details/gtlsohrsvy.html

[D23] reduce 累积计算
来源：http://dali.redwolf501.top/Article/details/gthvvwgxhy.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jyoumei.cn/Article/details/gtnmznqber.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yanxiufei.cn/Article/details/gteppuaayr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtcfejrvfq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqkwbjhlb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tianlin.xyz/Article/details/gtghfbywrg.html

Go:   // 手写循环
来源：http://dali.ppjwa.cn/Article/details/gtqpcpaind.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.andypj.xyz/Article/details/gtbwulvqnm.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.vqdsnc.cn/Article/details/gtwdvuptsd.html

[D24] 字典 / Map 基本操作
来源：http://dali.bjfxy.top/Article/details/gtziwfxtdo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ivvv.top/Article/details/gtqzxwioxd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhixingplan.top/Article/details/gtozyaqbzv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yj202588.top/Article/details/gtgvykiota.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpmwwdxwv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hysaishi.cn/Article/details/gthririmok.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrfsqyhrs.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tanke756.top/Article/details/gtuslimuvw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.316326.xyz/Article/details/gthlnunwbn.html

[D25] Set 集合去重与交并差
来源：http://dali.ywan-chungtsiang.top/Article/details/gtefmvoecs.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhixingplan.top/Article/details/gtdbhqgfpl.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jiagoushi.top/Article/details/gtdwaajeyp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jianghu66.top/Article/details/gtlmlvtbtp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj202588.top/Article/details/gtblxusxdx.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtsxfymctn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cdnleiting.top/Article/details/gtfpnglldj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yanxiufei.cn/Article/details/gtqpqlzpvo.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhongyouzk.top/Article/details/gtnbehpnuy.html

[D26] 数组转字符串
来源：http://dali.meibo888.top/Article/details/gtgquqmmsl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cashguo.top/Article/details/gtjhnzfphm.html

PHP:  implode(", ", $arr);
来源：http://dali.ybcxt.top/Article/details/gtjjxwwsos.html

JS:   arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gtnbtzavli.html

TS:   arr.join(", ")
来源：http://dali.guannengcc.top/Article/details/gtvbyhuawn.html

Java: String.join(", ", list)
来源：http://dali.nwbrower.top/Article/details/gtgkvhohsv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xuanzx.com/Article/details/gtzrnoqofi.html

Ruby: arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gtjqptehwl.html

C#:   string.Join(", ", list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcxyvbhym.html


<!-- 参考信息 -->