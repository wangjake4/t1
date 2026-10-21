代发 wailian999

TS:   同 JS
来源：http://dali.shanyushiyangkeji.top/Article/details/gtosdelykl.html

Java: 方法内为块级作用域
来源：http://dali.yj20258.top/Article/details/gtqcuezymo.html

Go:   花括号块级作用域
来源：http://dali.zhengqikj.top/Article/details/gtfevotuhp.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sxryk.cn/Article/details/gtfynagqof.html

C#:   块级作用域
来源：http://dali.pycfn.com/Article/details/gtecafiywt.html

[C11] 模块导入与导出
来源：http://dali.tanke756.top/Article/details/gtkfvmqhrn.html

Py:   from module import func
来源：http://dali.shuidangran.top/Article/details/gtxfbxecze.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.feifeiyinyue.top/Article/details/gthzrbldjm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ydzc1.top/Article/details/gtqltmvkqd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.dashuyun.cn/Article/details/gtvfmvgxir.html

Java: import java.util.List;
来源：http://dali.cheryme.top/Article/details/gtbpkpqtog.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hnqzz.top/Article/details/gtgsxfqlly.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.dashuyun.cn/Article/details/gtvlyaypxg.html

C#:   using System.Text;
来源：http://dali.hywenlv.cn/Article/details/gtcimhkbci.html

[C12] 立即执行函数 IIFE
来源：http://dali.xylfe.cn/Article/details/gtnmvpnhbg.html

Py:   (lambda: print("run"))()
来源：http://dali.pengpengdd.cyou/Article/details/gtyffpnzzk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.sweek.top/Article/details/gtrajlzgom.html

JS:   (() => { console.log("run"); })();
来源：http://dali.andypj.xyz/Article/details/gtoxhvkblf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.sysykeji.top/Article/details/gtryfzrjgb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.0kj1m.cn/Article/details/gtvzohifrl.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shzxlz.cn/Article/details/gtyukrypiv.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhoulong.xyz/Article/details/gtvrvpbjcc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ybcxt.top/Article/details/gtqhvxyftx.html

[C13] 类型声明 / 类型注解
来源：http://dali.shangyingyoupin.top/Article/details/gtfwjbccfq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hnqzz.top/Article/details/gtnwbfcrvw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gtepstnpgk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.svipenyu.cn/Article/details/gtdogzyfrx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gttqmfkmnt.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtmyizpjgd.html

Go:   func add(a, b int) int
来源：http://dali.jyoumei.cn/Article/details/gtoujiabae.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.smart0.xyz/Article/details/gtidycclvc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.feifeiyinyue.top/Article/details/gtdlermqsd.html

[C14] 泛型函数
来源：http://dali.cqqwz.cn/Article/details/gtbaiihwne.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.snrcjt.cn/Article/details/gtwxhqodmi.html

PHP:  // 无泛型
来源：http://dali.yuanzhike.top/Article/details/gtlwbzfwxu.html

JS:   // 无泛型
来源：http://dali.tian-w.cn/Article/details/gtfkjrzklv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sxryk.cn/Article/details/gtrocroctz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.pycfn.com/Article/details/gtsrswvcpe.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cucudq.cn/Article/details/gthjtwtjmb.html

Ruby: # 无泛型
来源：http://dali.xuanzx.com/Article/details/gtbqvhpsyq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.nanxuanxn.top/Article/details/gtdqahhkfz.html

[C15] 解构 / 展开参数
来源：http://dali.fengsongda.top/Article/details/gtwqccvwbr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jqgufenzy.top/Article/details/gtjytsbreh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shzxlz.cn/Article/details/gtykvnhjrk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jlsjyb.cn/Article/details/gtkpjlslpw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hfpthk.cn/Article/details/gtcquuctif.html

Java: // 无解构
来源：http://dali.jinqigufen.top/Article/details/gtnsnykywo.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gtzqhpiusm.html

Ruby: a, b = pair
来源：http://dali.gzhubu.top/Article/details/gtcqdckxby.html

C#:   var (a, b) = pair;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzdqjxaih.html

[C16] 函数 / 方法重载
来源：http://dali.smart0.xyz/Article/details/gtwsgegclf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.bjfxy.top/Article/details/gtuevijeaw.html

PHP:  // 无重载
来源：http://dali.sxryk.cn/Article/details/gtjcuemtjo.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.wangshuangyany.cn/Article/details/gtykdhlnrs.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.birdmap.top/Article/details/gtnbgpnrvs.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.9152youxi.cn/Article/details/gtjapsyzdi.html

Go:   // 无重载：用不同函数名
来源：http://dali.xinyue.icu/Article/details/gtlnxxnmgg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.birdmap.top/Article/details/gtlginsgpx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gaohongyu789.top/Article/details/gtscoorasm.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtpdgzrvfr.html

D. 数组 / 列表 / 集合
来源：http://dali.cdnleiting.top/Article/details/gtcqgkhhca.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtadctjlye.html

[D01] 创建数组 / 列表
来源：http://dali.haohaochexian.top/Article/details/gtjhdosssy.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhixingplan.top/Article/details/gtepjnhjwe.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.dianchejie.cn/Article/details/gtkipcrttb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shzxlz.cn/Article/details/gtoeijtsfm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.c1oappe.top/Article/details/gtcekhzjwf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.chenzaomai.com/Article/details/gtaonarqet.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsfvldlel.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jlsjyb.cn/Article/details/gtotxxxjfv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.birdmap.top/Article/details/gtaoxgiwtw.html

[D02] 追加元素到末尾
来源：http://dali.tianlin.xyz/Article/details/gtznwifsbm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.chenjidiqi.icu/Article/details/gtidgjjrpo.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinqigfzy.top/Article/details/gtuahzltpf.html

JS:   arr.push(4);
来源：http://dali.andypj.xyz/Article/details/gtxabcxqbl.html

TS:   arr.push(4);
来源：http://dali.sxryk.cn/Article/details/gtxcjswdad.html

Java: list.add(4);
来源：http://dali.yvedp.cn/Article/details/gtrandvabf.html

Go:   arr = append(arr, 4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzxfbggkb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.tianlin.xyz/Article/details/gtwiopumvv.html

C#:   list.Add(4);
来源：http://dali.havefunace.top/Article/details/gtqotiohii.html

[D03] 在指定位置插入元素
来源：http://dali.c1oappe.top/Article/details/gtrdrwyqfw.html

Py:   arr.insert(0, 0)
来源：http://dali.haohaochexian.top/Article/details/gthpcylenn.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jiagoushi.top/Article/details/gtixnqzlvm.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.fzhhl.top/Article/details/gtbashvkys.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jyoumei.cn/Article/details/gtddscusrv.html

Java: list.add(0, 0);
来源：http://dali.tian-w.cn/Article/details/gtbyfsvevm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gzhubu.top/Article/details/gtnousypuq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zdqjudy.top/Article/details/gtzkjhgbzi.html

C#:   list.Insert(0, 0);
来源：http://dali.sweek.top/Article/details/gtjgboytdv.html

[D04] 删除元素
来源：http://dali.zhongyouzk.top/Article/details/gtqmqugzjh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.tian-w.cn/Article/details/gtifshfsjx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.redwolf501.top/Article/details/gthnjnsvrx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shangyingyoupin.top/Article/details/gtncarhwmy.html

TS:   arr.splice(0, 1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcjsrwqsw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.iojbl.cn/Article/details/gttoygcrka.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shuidangran.top/Article/details/gtqmzchudq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.redwolf501.top/Article/details/gtxxmqbdem.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.redwolf501.top/Article/details/gtdpslyzxn.html

[D05] 访问与修改元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtxccmvehp.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxinkj.top/Article/details/gtihcdjvqj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yuanzhike.top/Article/details/gtvwrqtshy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.sweek.top/Article/details/gtwfgvfmcu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yonumen.top/Article/details/gtytaafwzz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtegypzamz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.bjfxy.top/Article/details/gttuzohnog.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gtmqduniye.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jqgfzy.top/Article/details/gtffxvfelt.html

[D06] 数组长度
来源：http://dali.sxryk.cn/Article/details/gtfeioiban.html

Py:   len(arr)
来源：http://dali.dianchejie.cn/Article/details/gtuxkhftou.html

PHP:  count($arr);
来源：http://dali.sufxvd.cn/Article/details/gtcciozpdt.html

JS:   arr.length
来源：http://dali.chenzaomai.com/Article/details/gtlaocbhqj.html

TS:   arr.length
来源：http://dali.gogol.net.cn/Article/details/gtxmlrcciu.html

Java: list.size();
来源：http://dali.nanxinkj.top/Article/details/gtzrihkrha.html

Go:   len(arr)
来源：http://dali.fengsongda.top/Article/details/gtronpshfr.html

Ruby: arr.length; arr.size
来源：http://dali.shuidangran.top/Article/details/gtebljvowm.html

C#:   list.Count;
来源：http://dali.sxryk.cn/Article/details/gtbrgbvchq.html

[D07] 切片 / 取子数组
来源：http://dali.hammf.cn/Article/details/gtlmzydgii.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinqigfzy.top/Article/details/gtnezypjul.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.316326.xyz/Article/details/gtzfkvojjf.html

JS:   arr.slice(1, 4);
来源：http://dali.tianlin.xyz/Article/details/gtvqmdjczu.html

TS:   arr.slice(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gtszroghyj.html

Java: list.subList(1, 4);
来源：http://dali.jinqigfzy.top/Article/details/gtfwqwukhs.html

Go:   arr[1:4]
来源：http://dali.zycfv.cn/Article/details/gtjguroqqj.html

Ruby: arr[1, 3]
来源：http://dali.xinyue.icu/Article/details/gtwmybkaxi.html

C#:   list.GetRange(1, 3);
来源：http://dali.yueranfly.top/Article/details/gtgukpthzi.html

[D08] 合并两个数组
来源：http://dali.zycfv.cn/Article/details/gtnuaaqgas.html

Py:   a + b;  a.extend(b)
来源：http://dali.pengpengdd.cyou/Article/details/gtirmksuxp.html

PHP:  array_merge($a, $b);
来源：http://dali.cucudq.cn/Article/details/gtbyzumavo.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jqgfzy.top/Article/details/gtyzxjpuhh.html

TS:   [...a, ...b];
来源：http://dali.yj20258888.top/Article/details/gtzovhuyem.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.dianchejie.cn/Article/details/gthemugzdq.html

Go:   append(a, b...)
来源：http://dali.shuidangran.top/Article/details/gtrffcuwim.html

Ruby: a + b;  a.concat(b)
来源：http://dali.c1oappe.top/Article/details/gtcuqzjbhn.html

C#:   a.Concat(b).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtjzoujxas.html

[D09] 排序（升序）
来源：http://dali.chenlongwang.top/Article/details/gtprntckao.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xylfe.cn/Article/details/gtlxpdyqsw.html

PHP:  sort($arr);
来源：http://dali.cucudq.cn/Article/details/gtchmliosy.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinqigufen.top/Article/details/gtlcdubnde.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xylfe.cn/Article/details/gtubeyxxlv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yuanzhike.top/Article/details/gtorncnggr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.tian-w.cn/Article/details/gtjcdiwrbx.html

Ruby: arr.sort
来源：http://dali.cqqwz.cn/Article/details/gtgmwwudze.html

C#:   list.Sort();
来源：http://dali.sysykeji.top/Article/details/gtophbtnvw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yangfankeji.com/Article/details/gtgrfvykfp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.tian-w.cn/Article/details/gtdbzaxfxd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.pengpengdd.cyou/Article/details/gtdiuqramj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cdnleiting.top/Article/details/gttcpuywcn.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtakqcydsw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yangfankeji.com/Article/details/gtvfzprabi.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shanyushiyangtech.top/Article/details/gtooecrwsh.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.iojbl.cn/Article/details/gthbpsyebr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhongyouzk.top/Article/details/gtphpivksx.html

[D11] 反转数组
来源：http://dali.sxryk.cn/Article/details/gtbtqdamgv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.bjfxy.top/Article/details/gtypcqiddo.html

PHP:  array_reverse($arr);
来源：http://dali.sysykeji.top/Article/details/gteagtyduo.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.havefunace.top/Article/details/gtmvgychjh.html

TS:   [...arr].reverse();
来源：http://dali.yonumen.top/Article/details/gtpdfahrxl.html

Java: Collections.reverse(list);
来源：http://dali.sxryk.cn/Article/details/gtxoesygzl.html

Go:   slices.Reverse(arr)
来源：http://dali.cashguo.top/Article/details/gtetmzkory.html

Ruby: arr.reverse
来源：http://dali.daxiang520.top/Article/details/gtrnpmfpcc.html

C#:   list.Reverse();
来源：http://dali.nwbrower.top/Article/details/gtntkmqsvy.html

[D12] 查找元素下标
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpcypvasn.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhaomingkeji.xyz/Article/details/gtffkanpoi.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.daria6918.cn/Article/details/gtabyiuguj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258888.top/Article/details/gtrswbhlfj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258.top/Article/details/gtmjublmtu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jianghu66.top/Article/details/gtnxkmufpg.html

Go:   slices.Index(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtfqlfsguv.html

Ruby: arr.index(x)
来源：http://dali.zhixingplan.top/Article/details/gtczbgncak.html

C#:   list.IndexOf(x);
来源：http://dali.svipenyu.cn/Article/details/gtpwburagf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yj202588.top/Article/details/gtmcurlmkk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.aibaodan.cn/Article/details/gtaofdamik.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjmwkhoyo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sysykeji.top/Article/details/gthvjktbmj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zdqjudy.top/Article/details/gtjmjcnwkd.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cashguo.top/Article/details/gtulxoowjz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhoulong.xyz/Article/details/gtwfloazuv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzkhwuwiv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yangfankeji.com/Article/details/gtopkzckyi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cheryme.top/Article/details/gtjbtldjcj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.pengpengdd.cyou/Article/details/gtqrrdyiol.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtzmvvqyvv.html

JS:   arr.map(x => x * 2)
来源：http://dali.9152youxi.cn/Article/details/gtunqoxqyh.html

TS:   arr.map(x => x * 2)
来源：http://dali.ehwqpu.com/Article/details/gtlwjdavqa.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.guowangkeji.top/Article/details/gttktejesh.html

Go:   // 手写循环
来源：http://dali.guannengcc.top/Article/details/gttnzlxuqr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.nwbrower.top/Article/details/gteoqrhjoz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gtdtbkfxud.html

[D15] 去重
来源：http://dali.aizwys.cn/Article/details/gtwqfuhujp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.wangdashe.top/Article/details/gtmloqjepx.html

PHP:  array_unique($arr);
来源：http://dali.tian-w.cn/Article/details/gtwjwjsuee.html

JS:   [...new Set(arr)]
来源：http://dali.sufxvd.cn/Article/details/gtuodsjrwe.html

TS:   [...new Set(arr)]
来源：http://dali.yvedp.cn/Article/details/gtnfmqobqk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gogol.net.cn/Article/details/gtxbrsbrzt.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.dashuyun.cn/Article/details/gtdyyibotq.html

Ruby: arr.uniq
来源：http://dali.daxiang520.top/Article/details/gtkmjwbyib.html

C#:   list.Distinct().ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxaxydbqo.html

[D16] 求和与平均值
来源：http://dali.ppjwa.cn/Article/details/gtspgwuhju.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yuanzhike.top/Article/details/gtynzjvviw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.0kj1m.cn/Article/details/gtycaptsdb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hywenlv.cn/Article/details/gtirnmaxiw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ehwqpu.com/Article/details/gtojduqvhy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.daria6918.cn/Article/details/gttlshgkss.html

Go:   // 手写循环累加
来源：http://dali.meibo888.top/Article/details/gtdosinnam.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhoulong.xyz/Article/details/gtoqgzucgo.html

C#:   list.Sum();  list.Average()
来源：http://dali.gzhubu.top/Article/details/gtdrizgfqp.html

[D17] 最大值与最小值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtezjcigmq.html

Py:   max(arr);  min(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtxrzotgpp.html

PHP:  max($arr);  min($arr);
来源：http://dali.sufxvd.cn/Article/details/gtewbsqsoj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhengqikj.top/Article/details/gtfyyktoxs.html

TS:   Math.max(...arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtrqtdqrcz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.birdmap.top/Article/details/gtrcaujvvs.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sxryk.cn/Article/details/gtozanuscq.html

Ruby: arr.max;  arr.min
来源：http://dali.nwbrower.top/Article/details/gttqfhqdkm.html

C#:   list.Max();  list.Min()
来源：http://dali.gogol.net.cn/Article/details/gtkypkxxuk.html

[D18] 扁平化嵌套数组
来源：http://dali.haohaochexian.top/Article/details/gtfmafwzel.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.mhx1999.top/Article/details/gtcuucvtbc.html

PHP:  array_merge(...$nested);
来源：http://dali.cheryme.top/Article/details/gtcbdeglap.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.wangdashe.top/Article/details/gtmpviapbl.html

TS:   nested.flat();
来源：http://dali.dashuyun.cn/Article/details/gtqyvttluz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.svipenyu.cn/Article/details/gtjsknxdds.html

Go:   // 手写双层循环
来源：http://dali.birdmap.top/Article/details/gtnfqvmdvf.html

Ruby: nested.flatten
来源：http://dali.ybcxt.top/Article/details/gtbmnzixou.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yj20258.top/Article/details/gtszueafhy.html

[D19] 按字段分组
来源：http://dali.zhoulong.xyz/Article/details/gtcxpkheuu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyehfopwb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.redwolf501.top/Article/details/gtopxlvqpc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.meibo888.top/Article/details/gtsnbmiayj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jiagoushi.top/Article/details/gtvpzguckz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ppjwa.cn/Article/details/gtgpynukze.html

Go:   // 手写 map[string][]T
来源：http://dali.nanxinkj.top/Article/details/gtoftdjujh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.snrcjt.cn/Article/details/gteeauohmc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.316326.xyz/Article/details/gtybrktniq.html

[D20] 统计每个元素出现次数
来源：http://dali.mhx1999.top/Article/details/gthbysbdex.html

Py:   Counter(arr)
来源：http://dali.aizwys.cn/Article/details/gtabhgrnis.html

PHP:  array_count_values($arr);
来源：http://dali.fengsongda.top/Article/details/gtbgkeqqef.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pycfn.com/Article/details/gtyxfsmkft.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xziqi.cn/Article/details/gtlrorvvac.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ppjwa.cn/Article/details/gtsahpskht.html

Go:   // 手写 map[T]int
来源：http://dali.jqgfzy.top/Article/details/gtkjdopfnr.html

Ruby: arr.tally
来源：http://dali.xinyue.icu/Article/details/gtikjbxyzu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.quarkkingdee.top/Article/details/gtrfgqgcjk.html

[D21] 判断是否包含某元素
来源：http://dali.haohaochexian.top/Article/details/gthgqywdqt.html

Py:   x in arr
来源：http://dali.dianchejie.cn/Article/details/gtxgfuiywa.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xylfe.cn/Article/details/gtxfvzhads.html

JS:   arr.includes(x)
来源：http://dali.jianghu66.top/Article/details/gtyibpeecm.html

TS:   arr.includes(x)
来源：http://dali.dashuyun.cn/Article/details/gtsmkfkqil.html

Java: list.contains(x)
来源：http://dali.aizwys.cn/Article/details/gtfdkmujua.html

Go:   slices.Contains(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtjivavclb.html

Ruby: arr.include?(x)
来源：http://dali.gaohongyu789.top/Article/details/gtuvcswhkj.html

C#:   list.Contains(x)
来源：http://dali.andypj.xyz/Article/details/gtesgmaotu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.aizwys.cn/Article/details/gtwrokxfpy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwpncnwrr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sufxvd.cn/Article/details/gtnmlbkcxa.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.guowangkeji.top/Article/details/gtfrcicaew.html

TS:   [...arr];
来源：http://dali.haohaochexian.top/Article/details/gtucedfsjb.html

Java: new ArrayList<>(list);
来源：http://dali.hongshengwenyu.top/Article/details/gtctaoggby.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gzhubu.top/Article/details/gtwbanrqtl.html

Ruby: arr.dup;  arr.clone
来源：http://dali.c1oappe.top/Article/details/gtnkrknzvt.html

C#:   new List<int>(list);
来源：http://dali.yuanzhike.top/Article/details/gtxnabrrnm.html

[D23] reduce 累积计算
来源：http://dali.hfpthk.cn/Article/details/gtuaoqpemj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yongpay.top/Article/details/gtzdpexzwx.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ybcxt.top/Article/details/gtzmhxyfmc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigufen.top/Article/details/gteastnosd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yonumen.top/Article/details/gtcodcypfk.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zycfv.cn/Article/details/gtkntdpuov.html

Go:   // 手写循环
来源：http://dali.ybcxt.top/Article/details/gtndrdnnsm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gotoacloud.top/Article/details/gtsikewyjt.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shuidangran.top/Article/details/gtfhsqqzxj.html

[D24] 字典 / Map 基本操作
来源：http://dali.yangfankeji.com/Article/details/gtbrfaalqb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ybcxt.top/Article/details/gtrcsydzsx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.daria6918.cn/Article/details/gtywzyizrl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.daxiang520.top/Article/details/gthcvbejxs.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gtkcxhlhif.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sxryk.cn/Article/details/gtwhwrobrw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinqigufen.top/Article/details/gtmucascyq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tianlin.xyz/Article/details/gtszgrxtgo.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ehwqpu.com/Article/details/gtxhxipjxi.html

[D25] Set 集合去重与交并差
来源：http://dali.daria6918.cn/Article/details/gtatuxmcbw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yj20258.top/Article/details/gtfsyxrngp.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.0kj1m.cn/Article/details/gtwituqqtf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.pycfn.com/Article/details/gthpjtcfuz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwfkairvi.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.0kj1m.cn/Article/details/gtxchiujtv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.aibaodan.cn/Article/details/gtbjtmgtvr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtqhszgaka.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gaohongyu789.top/Article/details/gtzhchhdxd.html

[D26] 数组转字符串
来源：http://dali.havefunace.top/Article/details/gthreepwzy.html

Py:   ", ".join(map(str, arr))
来源：http://dali.tanke756.top/Article/details/gtvkqdwtge.html

PHP:  implode(", ", $arr);
来源：http://dali.cdnleiting.top/Article/details/gtdcscoxpg.html

JS:   arr.join(", ")
来源：http://dali.c1oappe.top/Article/details/gteyslooou.html

TS:   arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gtjduysrkb.html

Java: String.join(", ", list)
来源：http://dali.fzhhl.top/Article/details/gthauatrqb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.guowangkeji.top/Article/details/gtqrsshmgz.html

Ruby: arr.join(", ")
来源：http://dali.andypj.xyz/Article/details/gtmpujpdpn.html

C#:   string.Join(", ", list)
来源：http://dali.ppjwa.cn/Article/details/gtfgtiblwz.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtxiwunvfi.html

E. 字符串处理
来源：http://dali.hnxiangtu.top/Article/details/gtkjqdjxdh.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtvfhhocyv.html

[E01] 拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxzcohdfn.html


<!-- 参考信息 -->