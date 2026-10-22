代发 wailian999

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gzhubu.top/Article/details/gtbjtauqrc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zycfv.cn/Article/details/gtfuqxefgf.html

Java: import java.util.List;
来源：http://dali.ppjwa.cn/Article/details/gtjxbrwslq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hysaishi.cn/Article/details/gtoqcspzuh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.iojbl.cn/Article/details/gthpavuykg.html

C#:   using System.Text;
来源：http://dali.sweek.top/Article/details/gtrfljczdv.html

[C12] 立即执行函数 IIFE
来源：http://dali.feifeiyinyue.top/Article/details/gteaxitmnc.html

Py:   (lambda: print("run"))()
来源：http://dali.yueranfly.top/Article/details/gtyqmdynds.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jinghuilouyu.cn/Article/details/gtwsdjcheg.html

JS:   (() => { console.log("run"); })();
来源：http://dali.haohaochexian.top/Article/details/gtubblodyt.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xuetiantiany.cn/Article/details/gthoquijfe.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.chenlongwang.top/Article/details/gtiqneqesa.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ydzc1.top/Article/details/gtqiazctwr.html

Ruby: -> { puts "run" }.call
来源：http://dali.shuidangran.top/Article/details/gtrzrhmhst.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xziqi.cn/Article/details/gtswcnxxwb.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhixingplan.top/Article/details/gtgppqboaf.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.tian-w.cn/Article/details/gtwefxlgkm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yongpay.top/Article/details/gthazkonuc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqddezvuo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtcfekdeur.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gttxgqhhom.html

Go:   func add(a, b int) int
来源：http://dali.meibo888.top/Article/details/gttudrwpyc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.wangshuangyany.cn/Article/details/gtpqxeynup.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gtfwexsjry.html

[C14] 泛型函数
来源：http://dali.sufxvd.cn/Article/details/gtamxzawij.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.gzhubu.top/Article/details/gtypknrfjk.html

PHP:  // 无泛型
来源：http://dali.tianlin.xyz/Article/details/gteinxrraz.html

JS:   // 无泛型
来源：http://dali.aibaodan.cn/Article/details/gtcmvllccn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jqgufenzy.top/Article/details/gtnwckjhbx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tian-w.cn/Article/details/gtsjducemr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.pengpengdd.cyou/Article/details/gtxhigjokq.html

Ruby: # 无泛型
来源：http://dali.sysykeji.top/Article/details/gtmnywzbrk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.bjfxy.top/Article/details/gtmvmqfeyk.html

[C15] 解构 / 展开参数
来源：http://dali.guowangkeji.top/Article/details/gtbxvdidug.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ivvv.top/Article/details/gtmeygsila.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jqgufenzy.top/Article/details/gtwronqfsy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xylfe.cn/Article/details/gtffraenca.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.dashuyun.cn/Article/details/gtrnjswccp.html

Java: // 无解构
来源：http://dali.hywenlv.cn/Article/details/gtritpvsbm.html

Go:   // 无解构
来源：http://dali.kuanghao11.cn/Article/details/gtaobxjwcn.html

Ruby: a, b = pair
来源：http://dali.xylfe.cn/Article/details/gtyxeffpts.html

C#:   var (a, b) = pair;
来源：http://dali.aizwys.cn/Article/details/gtqbrfbtqv.html

[C16] 函数 / 方法重载
来源：http://dali.shzxlz.cn/Article/details/gtnrpwnrpg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zycfv.cn/Article/details/gtuqtlhcwo.html

PHP:  // 无重载
来源：http://dali.jinghuilouyu.cn/Article/details/gtdhsxxfvo.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xylfe.cn/Article/details/gtztwueuls.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.haohaochexian.top/Article/details/gtycmjjzgm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sweek.top/Article/details/gtcguajego.html

Go:   // 无重载：用不同函数名
来源：http://dali.dianchejie.cn/Article/details/gtqvmgnaci.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtegwlzcop.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cheryme.top/Article/details/gtwwivfphz.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtafyuahbh.html

D. 数组 / 列表 / 集合
来源：http://dali.cheryme.top/Article/details/gtjkpzudhy.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtlwwztbxa.html

[D01] 创建数组 / 列表
来源：http://dali.gaohongyu789.top/Article/details/gtxenejswd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhoulong.xyz/Article/details/gtefmlljgg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sufxvd.cn/Article/details/gtdyevhigh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.wangshuangyany.cn/Article/details/gtqptebsdl.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shuidangran.top/Article/details/gtdfrprete.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.chenlongwang.top/Article/details/gtzmfohyit.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jqgfzy.top/Article/details/gtvpuhxsbq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.pycfn.com/Article/details/gtmwricwmt.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhiwuduotai.top/Article/details/gtvrzbresd.html

[D02] 追加元素到末尾
来源：http://dali.chenjidiqi.icu/Article/details/gtpmgaslkw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.c1oappe.top/Article/details/gtcgeppjcp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yuxming.cn/Article/details/gtsxktrqbh.html

JS:   arr.push(4);
来源：http://dali.zycfv.cn/Article/details/gtdjdccpue.html

TS:   arr.push(4);
来源：http://dali.xinyue.icu/Article/details/gtkrfomlbq.html

Java: list.add(4);
来源：http://dali.yuanzhike.top/Article/details/gtczoljlqq.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gtmcneqpfn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zdqjudy.top/Article/details/gtsfsgrgwk.html

C#:   list.Add(4);
来源：http://dali.guowangkeji.top/Article/details/gtxsxlsuwg.html

[D03] 在指定位置插入元素
来源：http://dali.ivvv.top/Article/details/gtpxsykxjd.html

Py:   arr.insert(0, 0)
来源：http://dali.yj20258888.top/Article/details/gtvduralqp.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xuanzx.com/Article/details/gtvmwecues.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yuanzhike.top/Article/details/gtdwdngoxv.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmkchtxec.html

Java: list.add(0, 0);
来源：http://dali.jinqigfzy.top/Article/details/gtfwqlercc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.aibaodan.cn/Article/details/gtwdyxsnis.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cashguo.top/Article/details/gtqcigkbvt.html

C#:   list.Insert(0, 0);
来源：http://dali.yj20258.top/Article/details/gtvtkqqcjs.html

[D04] 删除元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjrtjhgvn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.0kj1m.cn/Article/details/gthwgjfifn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.daria6918.cn/Article/details/gtbcbuvjzr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tanke756.top/Article/details/gtjzehrdsi.html

TS:   arr.splice(0, 1);
来源：http://dali.sufxvd.cn/Article/details/gtngphhjno.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.birdmap.top/Article/details/gtjziygdqd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.mhx1999.top/Article/details/gtvcizzwxe.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cheryme.top/Article/details/gtmmwnczgx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhixingplan.top/Article/details/gtzafceqbj.html

[D05] 访问与修改元素
来源：http://dali.xuanzx.com/Article/details/gtkiucixei.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxinkj.top/Article/details/gtrfpgfpuh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhixingplan.top/Article/details/gtunxrklzl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.quarkkingdee.top/Article/details/gthvtdmzow.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cucudq.cn/Article/details/gtgowgddlv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ehwqpu.com/Article/details/gtdvwpkrbs.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gtlnaoawpz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xinyue.icu/Article/details/gtmemywkzj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shzxlz.cn/Article/details/gtvwvueszw.html

[D06] 数组长度
来源：http://dali.cdnleiting.top/Article/details/gtnkeouscx.html

Py:   len(arr)
来源：http://dali.hammf.cn/Article/details/gtghhjwcmm.html

PHP:  count($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtfagafssb.html

JS:   arr.length
来源：http://dali.ehwqpu.com/Article/details/gttushvtus.html

TS:   arr.length
来源：http://dali.svipenyu.cn/Article/details/gtxubbdvxb.html

Java: list.size();
来源：http://dali.meibo888.top/Article/details/gtujvrnlqi.html

Go:   len(arr)
来源：http://dali.guannengcc.top/Article/details/gtxzjulxqj.html

Ruby: arr.length; arr.size
来源：http://dali.jinqigfzy.top/Article/details/gtoknpuyih.html

C#:   list.Count;
来源：http://dali.ppjwa.cn/Article/details/gtxjkxlxsg.html

[D07] 切片 / 取子数组
来源：http://dali.chenjidiqi.icu/Article/details/gthzgqwbmp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.svipenyu.cn/Article/details/gtdsjyzxuh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.smart0.xyz/Article/details/gtfejftvlq.html

JS:   arr.slice(1, 4);
来源：http://dali.ybcxt.top/Article/details/gtmafmpdvn.html

TS:   arr.slice(1, 4);
来源：http://dali.jinqigufen.top/Article/details/gtlbgyqbra.html

Java: list.subList(1, 4);
来源：http://dali.hnqzz.top/Article/details/gtjastlzzp.html

Go:   arr[1:4]
来源：http://dali.aibaodan.cn/Article/details/gtqrskcisa.html

Ruby: arr[1, 3]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsiilwpqe.html

C#:   list.GetRange(1, 3);
来源：http://dali.havefunace.top/Article/details/gtitnyjkzo.html

[D08] 合并两个数组
来源：http://dali.jianghu66.top/Article/details/gtaeaeaqfe.html

Py:   a + b;  a.extend(b)
来源：http://dali.xylfe.cn/Article/details/gttipgreju.html

PHP:  array_merge($a, $b);
来源：http://dali.zdqjudy.top/Article/details/gtzzywodjg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xuetiantiany.cn/Article/details/gtukgmuomd.html

TS:   [...a, ...b];
来源：http://dali.chenlongwang.top/Article/details/gteguvzjsl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.redwolf501.top/Article/details/gtvjonecnk.html

Go:   append(a, b...)
来源：http://dali.yangfankeji.com/Article/details/gtqnioammb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yvedp.cn/Article/details/gtapjfxqsl.html

C#:   a.Concat(b).ToList()
来源：http://dali.0kj1m.cn/Article/details/gtbscfavrd.html

[D09] 排序（升序）
来源：http://dali.hywenlv.cn/Article/details/gtwdhxexki.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hysaishi.cn/Article/details/gtxtlbahsg.html

PHP:  sort($arr);
来源：http://dali.mhx1999.top/Article/details/gtpnjcpotk.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xinyue.icu/Article/details/gtkqpvmdyk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.pycfn.com/Article/details/gtmfrgchwb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinqigfzy.top/Article/details/gtvpbeqrhw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuagtheev.html

Ruby: arr.sort
来源：http://dali.kuanghao11.cn/Article/details/gttsthauns.html

C#:   list.Sort();
来源：http://dali.jlsjyb.cn/Article/details/gtjnnlrqov.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.quarkkingdee.top/Article/details/gthffydmov.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shzxlz.cn/Article/details/gtqqqxmzbn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdunzyiig.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.svipenyu.cn/Article/details/gtslvisbga.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xziqi.cn/Article/details/gtuzvorwdc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shuidangran.top/Article/details/gtsbjqsxpa.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinqigufen.top/Article/details/gtryykgckj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yonumen.top/Article/details/gtaafxuowb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yuanzhike.top/Article/details/gtajiconfe.html

[D11] 反转数组
来源：http://dali.nanxinkj.top/Article/details/gtzsyfcydb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.tianlin.xyz/Article/details/gtkzlrfgag.html

PHP:  array_reverse($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtsuekcjlk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinghuilouyu.cn/Article/details/gtfaldtdlx.html

TS:   [...arr].reverse();
来源：http://dali.ehwqpu.com/Article/details/gtoyyydkwb.html

Java: Collections.reverse(list);
来源：http://dali.aizwys.cn/Article/details/gtnavpfech.html

Go:   slices.Reverse(arr)
来源：http://dali.fzhhl.top/Article/details/gtyiufthei.html

Ruby: arr.reverse
来源：http://dali.chenzaomai.com/Article/details/gtokgpwwcq.html

C#:   list.Reverse();
来源：http://dali.chenjidiqi.icu/Article/details/gtpihlkjez.html

[D12] 查找元素下标
来源：http://dali.quarkkingdee.top/Article/details/gtkervxwtw.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhoulong.xyz/Article/details/gtsgnzwvwy.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.guannengcc.top/Article/details/gtqdgyadry.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ydzc1.top/Article/details/gtyzzhegfa.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zdqjudy.top/Article/details/gtepzrxkrq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.birdmap.top/Article/details/gttsvothit.html

Go:   slices.Index(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtidecmeyl.html

Ruby: arr.index(x)
来源：http://dali.smart0.xyz/Article/details/gthadqdijg.html

C#:   list.IndexOf(x);
来源：http://dali.yj202588.top/Article/details/gthmaarkka.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yongpay.top/Article/details/gtlztkcwol.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hnxiangtu.top/Article/details/gtvubhrjbc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hfpthk.cn/Article/details/gtefgtmupn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.nanxuanxn.top/Article/details/gttxbisvdi.html

TS:   arr.filter(x => x > 3)
来源：http://dali.vqdsnc.cn/Article/details/gtneiabutv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hywenlv.cn/Article/details/gtrntkxttd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xylfe.cn/Article/details/gttxodifkm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nanxinkj.top/Article/details/gtawngtpva.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.sweek.top/Article/details/gtghzajesa.html

[D14] 映射转换（每个元素变形）
来源：http://dali.wangshuangyany.cn/Article/details/gtfquahhtt.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jiagoushi.top/Article/details/gtiqkrkdvk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxjaypmxj.html

JS:   arr.map(x => x * 2)
来源：http://dali.smart0.xyz/Article/details/gtiqnfgltz.html

TS:   arr.map(x => x * 2)
来源：http://dali.havefunace.top/Article/details/gtqbfjjqem.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xuanzx.com/Article/details/gtqqvuxxro.html

Go:   // 手写循环
来源：http://dali.xuanzx.com/Article/details/gtgqqsqdbt.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.chenlongwang.top/Article/details/gtxxdtmqgk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdxzcicm.html

[D15] 去重
来源：http://dali.shzxlz.cn/Article/details/gtqjjvvhzt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.c1oappe.top/Article/details/gtgacbwrux.html

PHP:  array_unique($arr);
来源：http://dali.tianlin.xyz/Article/details/gtvjkkoofq.html

JS:   [...new Set(arr)]
来源：http://dali.yvedp.cn/Article/details/gteumadaye.html

TS:   [...new Set(arr)]
来源：http://dali.zhengqikj.top/Article/details/gtrzbgzynd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.tianlin.xyz/Article/details/gtekgfhgcz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gzhubu.top/Article/details/gtlvdbwqsm.html

Ruby: arr.uniq
来源：http://dali.shzxlz.cn/Article/details/gthygdbhes.html

C#:   list.Distinct().ToList()
来源：http://dali.yueranfly.top/Article/details/gtevattano.html

[D16] 求和与平均值
来源：http://dali.quarkkingdee.top/Article/details/gttmlfbues.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmlkhocqf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hysaishi.cn/Article/details/gtezevsexd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xylfe.cn/Article/details/gtdrmcvnxg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xylfe.cn/Article/details/gtcvgbequp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj202588.top/Article/details/gtwiclwmiu.html

Go:   // 手写循环累加
来源：http://dali.zdqjudy.top/Article/details/gtyeyzrrlz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.daria6918.cn/Article/details/gtuqdwyuas.html

C#:   list.Sum();  list.Average()
来源：http://dali.yueranfly.top/Article/details/gtjekvmqhr.html

[D17] 最大值与最小值
来源：http://dali.hammf.cn/Article/details/gtmfypabtz.html

Py:   max(arr);  min(arr)
来源：http://dali.cucudq.cn/Article/details/gtnjyvzhhx.html

PHP:  max($arr);  min($arr);
来源：http://dali.fengsongda.top/Article/details/gtudcaxmxo.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.wangdashe.top/Article/details/gtiucxfehd.html

TS:   Math.max(...arr);
来源：http://dali.zycfv.cn/Article/details/gtmzdacddp.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.chenzaomai.com/Article/details/gtsoaysxgy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtgsqvwjwn.html

Ruby: arr.max;  arr.min
来源：http://dali.zdqjudy.top/Article/details/gtostvnpkq.html

C#:   list.Max();  list.Min()
来源：http://dali.yj202588.top/Article/details/gtzhelgxna.html

[D18] 扁平化嵌套数组
来源：http://dali.xinyue.icu/Article/details/gtriczoqot.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.wangdashe.top/Article/details/gthkydokvv.html

PHP:  array_merge(...$nested);
来源：http://dali.hfpthk.cn/Article/details/gtcxhuiflq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ehwqpu.com/Article/details/gttadfcfpr.html

TS:   nested.flat();
来源：http://dali.svipenyu.cn/Article/details/gthhkkuzfk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hysaishi.cn/Article/details/gtpjxovglo.html

Go:   // 手写双层循环
来源：http://dali.jlsjyb.cn/Article/details/gtrbvjolls.html

Ruby: nested.flatten
来源：http://dali.gzhubu.top/Article/details/gtehgrrgto.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yuxming.cn/Article/details/gtibjwsfgk.html

[D19] 按字段分组
来源：http://dali.0kj1m.cn/Article/details/gthnccnhzd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yj202588.top/Article/details/gtakqnpcfi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sweek.top/Article/details/gteffkxsmf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cheryme.top/Article/details/gtfxvjybxp.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhoulong.xyz/Article/details/gtmlbdygvf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zdqjudy.top/Article/details/gtyzlewvit.html

Go:   // 手写 map[string][]T
来源：http://dali.jiagoushi.top/Article/details/gtyldulcyi.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.kuanghao11.cn/Article/details/gtqzbhewrl.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zycfv.cn/Article/details/gtefxabyzj.html

[D20] 统计每个元素出现次数
来源：http://dali.ydzc1.top/Article/details/gtshsrgosk.html

Py:   Counter(arr)
来源：http://dali.hammf.cn/Article/details/gtryrplcdj.html

PHP:  array_count_values($arr);
来源：http://dali.haohaochexian.top/Article/details/gtrnmngzik.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenzaomai.com/Article/details/gtokdkwdgw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nanxinkj.top/Article/details/gtlotsrxwh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.havefunace.top/Article/details/gtohqdjnyx.html

Go:   // 手写 map[T]int
来源：http://dali.wangdashe.top/Article/details/gtbfwxezmi.html

Ruby: arr.tally
来源：http://dali.feifeiyinyue.top/Article/details/gttihkamue.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.tian-w.cn/Article/details/gtlxyilaet.html

[D21] 判断是否包含某元素
来源：http://dali.iojbl.cn/Article/details/gttxniluzo.html

Py:   x in arr
来源：http://dali.gotoacloud.top/Article/details/gtdxzdcowf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhoulong.xyz/Article/details/gtebuduvfz.html

JS:   arr.includes(x)
来源：http://dali.jianghu66.top/Article/details/gtzuivvbsz.html

TS:   arr.includes(x)
来源：http://dali.sweek.top/Article/details/gtxenynate.html

Java: list.contains(x)
来源：http://dali.snrcjt.cn/Article/details/gtoiwmbols.html

Go:   slices.Contains(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtkdmjjhuk.html

Ruby: arr.include?(x)
来源：http://dali.sufxvd.cn/Article/details/gtcmdjrtvp.html

C#:   list.Contains(x)
来源：http://dali.sufxvd.cn/Article/details/gtgyajeglq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ppjwa.cn/Article/details/gtmubqrltt.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.fzhhl.top/Article/details/gtingtjybc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.wangdashe.top/Article/details/gtsrvoqziw.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.daria6918.cn/Article/details/gtqvxbhxsh.html

TS:   [...arr];
来源：http://dali.jyoumei.cn/Article/details/gttjvbmvux.html

Java: new ArrayList<>(list);
来源：http://dali.chenzaomai.com/Article/details/gtpraslcjs.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinqigufen.top/Article/details/gtotaebeak.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhengqikj.top/Article/details/gtlehyldar.html

C#:   new List<int>(list);
来源：http://dali.mhx1999.top/Article/details/gtqianombi.html

[D23] reduce 累积计算
来源：http://dali.yangfankeji.com/Article/details/gtmhuqllvy.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.chenlongwang.top/Article/details/gtfckrywyl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.havefunace.top/Article/details/gtpuljrwyc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hywenlv.cn/Article/details/gtfyctbsig.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jianghu66.top/Article/details/gtrgxgawop.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hfpthk.cn/Article/details/gthmzkecvx.html

Go:   // 手写循环
来源：http://dali.meibo888.top/Article/details/gtukzkgdxd.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yanxiufei.cn/Article/details/gtyigpsegw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.snrcjt.cn/Article/details/gtracohfdd.html

[D24] 字典 / Map 基本操作
来源：http://dali.jyoumei.cn/Article/details/gtottqneel.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ppjwa.cn/Article/details/gtpqszjqbr.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenzaomai.com/Article/details/gtdbmdynod.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hnqzz.top/Article/details/gtrjeulshz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gzhubu.top/Article/details/gtmxgchlhb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jqgfzy.top/Article/details/gtsowcvfzn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.chenjidiqi.icu/Article/details/gtxcljrbch.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.snrcjt.cn/Article/details/gtlfghzbxa.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cashguo.top/Article/details/gtcdwqkwoi.html

[D25] Set 集合去重与交并差
来源：http://dali.smart0.xyz/Article/details/gtehuwsiuq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.nwbrower.top/Article/details/gtlxwyuevw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jlsjyb.cn/Article/details/gtocbvtyfh.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jyoumei.cn/Article/details/gtdxacgpdn.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.redwolf501.top/Article/details/gtcofawzhv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sweek.top/Article/details/gthguadpxx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cashguo.top/Article/details/gtvhehqepl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtanbxvyno.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinqigufen.top/Article/details/gtmjautkvu.html

[D26] 数组转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtkepkonnd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ydzc1.top/Article/details/gtlhjgbyos.html

PHP:  implode(", ", $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtscchnyup.html

JS:   arr.join(", ")
来源：http://dali.chenjidiqi.icu/Article/details/gtyddcuysq.html

TS:   arr.join(", ")
来源：http://dali.mhx1999.top/Article/details/gtcotewtfu.html

Java: String.join(", ", list)
来源：http://dali.shzxlz.cn/Article/details/gtyynoicre.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cdnleiting.top/Article/details/gtuliledyj.html

Ruby: arr.join(", ")
来源：http://dali.daxiang520.top/Article/details/gtmcrrxzyq.html

C#:   string.Join(", ", list)
来源：http://dali.hongshengwenyu.top/Article/details/gtbcciytib.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtyyymrzmz.html

E. 字符串处理
来源：http://dali.snrcjt.cn/Article/details/gtvloazoni.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtvhoigunh.html

[E01] 拼接字符串
来源：http://dali.cdnleiting.top/Article/details/gtdptzusis.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sxryk.cn/Article/details/gtalymttjf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.pengpengdd.cyou/Article/details/gtuqdznxcz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyhbeghwp.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhongyouzk.top/Article/details/gtiqkepjol.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tanke756.top/Article/details/gtqxzpghxm.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gaohongyu789.top/Article/details/gtktginhtn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.guannengcc.top/Article/details/gtajttbxpd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtilllhbga.html


<!-- 参考信息 -->