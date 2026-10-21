代发 wailian999

[C14] 泛型函数
来源：http://dali.yuxming.cn/Article/details/gtwqmckbdh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.havefunace.top/Article/details/gtuixzkhco.html

PHP:  // 无泛型
来源：http://dali.jianghu66.top/Article/details/gtangrauad.html

JS:   // 无泛型
来源：http://dali.andypj.xyz/Article/details/gtrosmcvhu.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zdqjudy.top/Article/details/gtiepywzzj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.pengpengdd.cyou/Article/details/gtgbsjigwr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.fengsongda.top/Article/details/gtxtvydvsg.html

Ruby: # 无泛型
来源：http://dali.wangdashe.top/Article/details/gthyntkkcp.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.pengpengdd.cyou/Article/details/gtibrinkta.html

[C15] 解构 / 展开参数
来源：http://dali.chenlongwang.top/Article/details/gtapdxoztw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.pengpengdd.cyou/Article/details/gttvigacaf.html

PHP:  [$a, $b] = $pair;
来源：http://dali.kuanghao11.cn/Article/details/gtnyptwppv.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zdqjudy.top/Article/details/gtrhbzefri.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgimkadpa.html

Java: // 无解构
来源：http://dali.smart0.xyz/Article/details/gtswtewycr.html

Go:   // 无解构
来源：http://dali.redwolf501.top/Article/details/gtkyxvippb.html

Ruby: a, b = pair
来源：http://dali.jinghuilouyu.cn/Article/details/gtrucrfsgm.html

C#:   var (a, b) = pair;
来源：http://dali.feifeiyinyue.top/Article/details/gtwhqwzvzh.html

[C16] 函数 / 方法重载
来源：http://dali.tian-w.cn/Article/details/gtxrpallnp.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cqqwz.cn/Article/details/gtmdidulot.html

PHP:  // 无重载
来源：http://dali.tianlin.xyz/Article/details/gthkizarkg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinqigufen.top/Article/details/gtdqoonnyh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yongpay.top/Article/details/gtuavkeluw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hfpthk.cn/Article/details/gtihvbfczu.html

Go:   // 无重载：用不同函数名
来源：http://dali.jyoumei.cn/Article/details/gtuvulsspk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.tianlin.xyz/Article/details/gtybvjzsbx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinqigfzy.top/Article/details/gtzrrrmhua.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtfeeqawsc.html

D. 数组 / 列表 / 集合
来源：http://dali.kuanghao11.cn/Article/details/gtvrflivwx.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gteeuvtnjo.html

[D01] 创建数组 / 列表
来源：http://dali.fengsongda.top/Article/details/gtuajzikoz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinqigufen.top/Article/details/gtacsvgcms.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gaohongyu789.top/Article/details/gtrdcnwruu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.iojbl.cn/Article/details/gtiexgaxfg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yangfankeji.com/Article/details/gtxemyzppr.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sysykeji.top/Article/details/gtdfuulsns.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.daria6918.cn/Article/details/gtuctrkgqp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.fengsongda.top/Article/details/gtbskueygf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlvhvmxaq.html

[D02] 追加元素到末尾
来源：http://dali.shzxlz.cn/Article/details/gtdnrikwsw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.havefunace.top/Article/details/gtddbohfbg.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfjrtwcwv.html

JS:   arr.push(4);
来源：http://dali.c1oappe.top/Article/details/gteiwwatcg.html

TS:   arr.push(4);
来源：http://dali.yuanzhike.top/Article/details/gtbaonenek.html

Java: list.add(4);
来源：http://dali.316326.xyz/Article/details/gtsjskckec.html

Go:   arr = append(arr, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gtkfmvhcvb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhoulong.xyz/Article/details/gtglmsolan.html

C#:   list.Add(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtusficrrj.html

[D03] 在指定位置插入元素
来源：http://dali.jlsjyb.cn/Article/details/gtkftckqpf.html

Py:   arr.insert(0, 0)
来源：http://dali.chenzaomai.com/Article/details/gtfszmeagd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.c1oappe.top/Article/details/gtcgjwlasx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yongpay.top/Article/details/gtcmffzyww.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.smart0.xyz/Article/details/gtrcgtbysb.html

Java: list.add(0, 0);
来源：http://dali.havefunace.top/Article/details/gtfjwndnml.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jianghu66.top/Article/details/gtgdzdextp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtutsoniqh.html

C#:   list.Insert(0, 0);
来源：http://dali.hysaishi.cn/Article/details/gtmcxdbrgf.html

[D04] 删除元素
来源：http://dali.sysykeji.top/Article/details/gtaaykvnzp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cqqwz.cn/Article/details/gtzvhdiwau.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yuxming.cn/Article/details/gtqncazfez.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtflrdogoz.html

TS:   arr.splice(0, 1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdsrkptvx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yvedp.cn/Article/details/gtrvblsbzn.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.c1oappe.top/Article/details/gtakhxhsbn.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yj20258.top/Article/details/gtejztxlow.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sysykeji.top/Article/details/gtodoqtckj.html

[D05] 访问与修改元素
来源：http://dali.c1oappe.top/Article/details/gtvrnjcbvx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gtoudezofw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gtatlolhff.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xziqi.cn/Article/details/gtxnidbdpr.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmfkuzspg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.iojbl.cn/Article/details/gtubefcblw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gtcvwbzgyc.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yangfankeji.com/Article/details/gtbrucjkwb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhoulong.xyz/Article/details/gtxmqvaiex.html

[D06] 数组长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsjdmlomi.html

Py:   len(arr)
来源：http://dali.yueranfly.top/Article/details/gtbuotsnhs.html

PHP:  count($arr);
来源：http://dali.tanke756.top/Article/details/gtlogkzcas.html

JS:   arr.length
来源：http://dali.jqgfzy.top/Article/details/gtbkmexkph.html

TS:   arr.length
来源：http://dali.daria6918.cn/Article/details/gtrznmozpg.html

Java: list.size();
来源：http://dali.quarkkingdee.top/Article/details/gtkqqblgoe.html

Go:   len(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbbwvporg.html

Ruby: arr.length; arr.size
来源：http://dali.tian-w.cn/Article/details/gtrflhuybc.html

C#:   list.Count;
来源：http://dali.guowangkeji.top/Article/details/gtdhlrutzz.html

[D07] 切片 / 取子数组
来源：http://dali.gaohongyu789.top/Article/details/gtdfxomavo.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.pengpengdd.cyou/Article/details/gtdaablpgy.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yuxming.cn/Article/details/gtbcvmxgsu.html

JS:   arr.slice(1, 4);
来源：http://dali.c1oappe.top/Article/details/gtpndgnhzz.html

TS:   arr.slice(1, 4);
来源：http://dali.ivvv.top/Article/details/gtvtnuutvq.html

Java: list.subList(1, 4);
来源：http://dali.dashuyun.cn/Article/details/gtmnfrxddx.html

Go:   arr[1:4]
来源：http://dali.snrcjt.cn/Article/details/gtkqwhcbtj.html

Ruby: arr[1, 3]
来源：http://dali.daria6918.cn/Article/details/gtuespiemn.html

C#:   list.GetRange(1, 3);
来源：http://dali.kuanghao11.cn/Article/details/gtpppdrtvd.html

[D08] 合并两个数组
来源：http://dali.316326.xyz/Article/details/gtvtyrfkby.html

Py:   a + b;  a.extend(b)
来源：http://dali.ydzc1.top/Article/details/gtatadmuom.html

PHP:  array_merge($a, $b);
来源：http://dali.hammf.cn/Article/details/gtdzbpreiy.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hfpthk.cn/Article/details/gtmbefipqx.html

TS:   [...a, ...b];
来源：http://dali.dashuyun.cn/Article/details/gtwrfsmvwp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xylfe.cn/Article/details/gtlcdpsdrd.html

Go:   append(a, b...)
来源：http://dali.pengpengdd.cyou/Article/details/gtpdyyiitr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.birdmap.top/Article/details/gtunumyvpt.html

C#:   a.Concat(b).ToList()
来源：http://dali.snrcjt.cn/Article/details/gtdmwakiaz.html

[D09] 排序（升序）
来源：http://dali.yonumen.top/Article/details/gtjburupka.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tian-w.cn/Article/details/gtwkyhashr.html

PHP:  sort($arr);
来源：http://dali.ivvv.top/Article/details/gtojutyjek.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cashguo.top/Article/details/gthiuyfcbk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zdqjudy.top/Article/details/gtjgaovvgn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xuetiantiany.cn/Article/details/gttzdqhfpg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.andypj.xyz/Article/details/gtuzhfqhic.html

Ruby: arr.sort
来源：http://dali.guannengcc.top/Article/details/gtjdeifbbe.html

C#:   list.Sort();
来源：http://dali.yj20258.top/Article/details/gtkhyjatqj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sxryk.cn/Article/details/gtdiiwurde.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinqigfzy.top/Article/details/gtnhjlfuol.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xuetiantiany.cn/Article/details/gtbjefuhrq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yonumen.top/Article/details/gtruugpyvt.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhoulong.xyz/Article/details/gtjyltxjbg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.0kj1m.cn/Article/details/gtsnrwoidi.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.pycfn.com/Article/details/gtogbtldbs.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cdnleiting.top/Article/details/gtrvxsdgxp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.0kj1m.cn/Article/details/gtcdoxnsuc.html

[D11] 反转数组
来源：http://dali.hnxiangtu.top/Article/details/gtymfppqqt.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sufxvd.cn/Article/details/gtjcmttwdm.html

PHP:  array_reverse($arr);
来源：http://dali.svipenyu.cn/Article/details/gtnyputazc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.chenzaomai.com/Article/details/gtgdwypbgg.html

TS:   [...arr].reverse();
来源：http://dali.xuetiantiany.cn/Article/details/gtjojnhgxn.html

Java: Collections.reverse(list);
来源：http://dali.hnqzz.top/Article/details/gtlsqealdy.html

Go:   slices.Reverse(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtxlaejddn.html

Ruby: arr.reverse
来源：http://dali.yvedp.cn/Article/details/gttqzghkqa.html

C#:   list.Reverse();
来源：http://dali.hammf.cn/Article/details/gtpxpeprxw.html

[D12] 查找元素下标
来源：http://dali.bjfxy.top/Article/details/gtmsbmprbh.html

Py:   arr.index(x);  x in arr
来源：http://dali.jqgfzy.top/Article/details/gtetsbvjgz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yueranfly.top/Article/details/gtcgwytbcg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.9152youxi.cn/Article/details/gtomcaaulo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.mhx1999.top/Article/details/gtbwizrqdc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.fzhhl.top/Article/details/gttxzqwjld.html

Go:   slices.Index(arr, x)
来源：http://dali.cheryme.top/Article/details/gtcuatckzw.html

Ruby: arr.index(x)
来源：http://dali.cdnleiting.top/Article/details/gtylnzedvv.html

C#:   list.IndexOf(x);
来源：http://dali.ydzc1.top/Article/details/gtlsksgjzi.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cqqwz.cn/Article/details/gtuivqujne.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hysaishi.cn/Article/details/gtwipgnywe.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yongpay.top/Article/details/gtnvtneuze.html

JS:   arr.filter(x => x > 3)
来源：http://dali.tanke756.top/Article/details/gtthowgmib.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yuxming.cn/Article/details/gtxmeqwnrc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtwrsnamvc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gaohongyu789.top/Article/details/gtdellgkil.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.316326.xyz/Article/details/gtgxicwhmy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.sxryk.cn/Article/details/gtkhhcjuon.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinqigufen.top/Article/details/gtwuquclkz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cdnleiting.top/Article/details/gtitmrgubt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtknwkophh.html

JS:   arr.map(x => x * 2)
来源：http://dali.hammf.cn/Article/details/gtvsanpyno.html

TS:   arr.map(x => x * 2)
来源：http://dali.9152youxi.cn/Article/details/gtmjozrptk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinqigufen.top/Article/details/gtvsferrov.html

Go:   // 手写循环
来源：http://dali.yvedp.cn/Article/details/gtxrmqetkh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmpbakorc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.aibaodan.cn/Article/details/gtegvzdxtj.html

[D15] 去重
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaileyyix.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.chenlongwang.top/Article/details/gtgyzzdkei.html

PHP:  array_unique($arr);
来源：http://dali.yangfankeji.com/Article/details/gtjkqfgkvq.html

JS:   [...new Set(arr)]
来源：http://dali.wangdashe.top/Article/details/gtgarutcrk.html

TS:   [...new Set(arr)]
来源：http://dali.quarkkingdee.top/Article/details/gtvuecfwlp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.snrcjt.cn/Article/details/gtiyzjqqou.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlozomxnr.html

Ruby: arr.uniq
来源：http://dali.birdmap.top/Article/details/gtcxkvcwaa.html

C#:   list.Distinct().ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtnudyzrla.html

[D16] 求和与平均值
来源：http://dali.wangdashe.top/Article/details/gtkyxthefz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.316326.xyz/Article/details/gtedjjgoso.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.iojbl.cn/Article/details/gtjhmvevpt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cheryme.top/Article/details/gtittjfadb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cucudq.cn/Article/details/gtendrnten.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.haohaochexian.top/Article/details/gtbzqyyysn.html

Go:   // 手写循环累加
来源：http://dali.svipenyu.cn/Article/details/gtcubuqbfn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.aibaodan.cn/Article/details/gtmectoocn.html

C#:   list.Sum();  list.Average()
来源：http://dali.jqgufenzy.top/Article/details/gtqlncrcya.html

[D17] 最大值与最小值
来源：http://dali.wangdashe.top/Article/details/gtxqczwfsb.html

Py:   max(arr);  min(arr)
来源：http://dali.tianlin.xyz/Article/details/gtdiklaelg.html

PHP:  max($arr);  min($arr);
来源：http://dali.hysaishi.cn/Article/details/gtdzohzyxg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.daxiang520.top/Article/details/gteuhwnxps.html

TS:   Math.max(...arr);
来源：http://dali.yj20258888.top/Article/details/gttkhxejky.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhongyouzk.top/Article/details/gtylbbuwir.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhengqikj.top/Article/details/gtcjbvrszt.html

Ruby: arr.max;  arr.min
来源：http://dali.yj20258888.top/Article/details/gtxvhgsjql.html

C#:   list.Max();  list.Min()
来源：http://dali.dashuyun.cn/Article/details/gtdnunewrp.html

[D18] 扁平化嵌套数组
来源：http://dali.daria6918.cn/Article/details/gtrdtzldib.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ppjwa.cn/Article/details/gtwmbusqyy.html

PHP:  array_merge(...$nested);
来源：http://dali.smart0.xyz/Article/details/gtrzqawbds.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hfpthk.cn/Article/details/gtlmwszsje.html

TS:   nested.flat();
来源：http://dali.pengpengdd.cyou/Article/details/gtiveexzdi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtfjabqkqr.html

Go:   // 手写双层循环
来源：http://dali.mhx1999.top/Article/details/gtymnmjapt.html

Ruby: nested.flatten
来源：http://dali.yuxming.cn/Article/details/gtwqjhhunw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ydzc1.top/Article/details/gtfjynjjkm.html

[D19] 按字段分组
来源：http://dali.jqgfzy.top/Article/details/gtfzmhkbwm.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.dashuyun.cn/Article/details/gtreewrwkt.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.chenlongwang.top/Article/details/gtijoswacv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xinyue.icu/Article/details/gtwmmpnjvt.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhoulong.xyz/Article/details/gtssilidch.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hammf.cn/Article/details/gtgpovfqjk.html

Go:   // 手写 map[string][]T
来源：http://dali.haohaochexian.top/Article/details/gtbkvloaaw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.dashuyun.cn/Article/details/gtdakzdcsc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xylfe.cn/Article/details/gtzkrekpxv.html

[D20] 统计每个元素出现次数
来源：http://dali.yanxiufei.cn/Article/details/gtdpbgmput.html

Py:   Counter(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtyoomhduu.html

PHP:  array_count_values($arr);
来源：http://dali.ybcxt.top/Article/details/gtnkmkluji.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jlsjyb.cn/Article/details/gtbgqzpmaj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigfzy.top/Article/details/gthzawvktz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.haohaochexian.top/Article/details/gtfqqunrjh.html

Go:   // 手写 map[T]int
来源：http://dali.svipenyu.cn/Article/details/gtiqdbrmjf.html

Ruby: arr.tally
来源：http://dali.iojbl.cn/Article/details/gtibmzfgsr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gzhubu.top/Article/details/gtamtsgapp.html

[D21] 判断是否包含某元素
来源：http://dali.jinqigufen.top/Article/details/gtzbdqulfp.html

Py:   x in arr
来源：http://dali.jlsjyb.cn/Article/details/gtmqekbjbm.html

PHP:  in_array($x, $arr, true);
来源：http://dali.chenlongwang.top/Article/details/gtrnfeqnsf.html

JS:   arr.includes(x)
来源：http://dali.sufxvd.cn/Article/details/gtrxwjorhq.html

TS:   arr.includes(x)
来源：http://dali.ppjwa.cn/Article/details/gtlnqncdek.html

Java: list.contains(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtknxmpdxe.html

Go:   slices.Contains(arr, x)
来源：http://dali.tanke756.top/Article/details/gtivztjpxu.html

Ruby: arr.include?(x)
来源：http://dali.shzxlz.cn/Article/details/gtgooekdnt.html

C#:   list.Contains(x)
来源：http://dali.havefunace.top/Article/details/gtwultcojf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jiagoushi.top/Article/details/gtueigtkvh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.9152youxi.cn/Article/details/gtgyngwsbh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xuetiantiany.cn/Article/details/gtijqqqknh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhixingplan.top/Article/details/gtvbojpaca.html

TS:   [...arr];
来源：http://dali.tanke756.top/Article/details/gtokojcedt.html

Java: new ArrayList<>(list);
来源：http://dali.snrcjt.cn/Article/details/gttemfkxcr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gtpttfrbju.html

Ruby: arr.dup;  arr.clone
来源：http://dali.c1oappe.top/Article/details/gtlztrshsx.html

C#:   new List<int>(list);
来源：http://dali.iojbl.cn/Article/details/gturlldibz.html

[D23] reduce 累积计算
来源：http://dali.yanxiufei.cn/Article/details/gtcrjxllkn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.316326.xyz/Article/details/gtdaeawciu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sxryk.cn/Article/details/gtfnvoqepa.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhengqikj.top/Article/details/gtaqulctxl.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtsxfkmklf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.andypj.xyz/Article/details/gtzjbxfvyu.html

Go:   // 手写循环
来源：http://dali.chenlongwang.top/Article/details/gtifrslyyy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.aibaodan.cn/Article/details/gtxscxyskl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrpfrxpnz.html

[D24] 字典 / Map 基本操作
来源：http://dali.cucudq.cn/Article/details/gtldhpwmdg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.meibo888.top/Article/details/gtnnwmseig.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.kuanghao11.cn/Article/details/gtugqbcmju.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtpfyqksyq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.c1oappe.top/Article/details/gtqohwlodh.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ehwqpu.com/Article/details/gtqtymzubt.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.kuanghao11.cn/Article/details/gtlekisegi.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yuanzhike.top/Article/details/gtxdzghgpl.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shangyingyoupin.top/Article/details/gtojabkeid.html

[D25] Set 集合去重与交并差
来源：http://dali.zycfv.cn/Article/details/gtiysbcxcm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhiwuduotai.top/Article/details/gtduvotvic.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gaohongyu789.top/Article/details/gtugpdwvtk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ydzc1.top/Article/details/gtkxbcjlfv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.pycfn.com/Article/details/gtfekeirfy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqbloiips.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhiwuduotai.top/Article/details/gtyghvwhut.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.redwolf501.top/Article/details/gtkudskjcf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hywenlv.cn/Article/details/gtmtjkeuoz.html

[D26] 数组转字符串
来源：http://dali.dashuyun.cn/Article/details/gtnvudmwgl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yvedp.cn/Article/details/gtgvfhojbu.html

PHP:  implode(", ", $arr);
来源：http://dali.zhoulong.xyz/Article/details/gtoafkcaaa.html

JS:   arr.join(", ")
来源：http://dali.fengsongda.top/Article/details/gtitlskpjo.html

TS:   arr.join(", ")
来源：http://dali.vqdsnc.cn/Article/details/gtuzllnrbm.html

Java: String.join(", ", list)
来源：http://dali.wangshuangyany.cn/Article/details/gtjwrijhww.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xinyue.icu/Article/details/gtqgvjsfeh.html

Ruby: arr.join(", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxdwsayjw.html

C#:   string.Join(", ", list)
来源：http://dali.dianchejie.cn/Article/details/gtunehrqql.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtlsljpfkl.html

E. 字符串处理
来源：http://dali.andypj.xyz/Article/details/gtrcpbcdov.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtlvhbdoqq.html

[E01] 拼接字符串
来源：http://dali.birdmap.top/Article/details/gtkfmqezgn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhaomingkeji.xyz/Article/details/gtirhupgea.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yj20258888.top/Article/details/gtbgqqtrti.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhixingplan.top/Article/details/gttobksryc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxinkj.top/Article/details/gtsvaescdz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.dashuyun.cn/Article/details/gtfmmrzpnk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhoulong.xyz/Article/details/gtqlexzbwk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yj20258.top/Article/details/gtjprezkpf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yuxming.cn/Article/details/gtawbxncfc.html

[E02] 重复字符串
来源：http://dali.yueranfly.top/Article/details/gtkveqqctj.html

Py:   "ab" * 3
来源：http://dali.jinqigfzy.top/Article/details/gtmajuxjno.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zycfv.cn/Article/details/gtfiplbzog.html

JS:   "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gtrphvecod.html

TS:   "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gtwkcwpsgd.html

Java: "ab".repeat(3)
来源：http://dali.zhoulong.xyz/Article/details/gtfgbmzzfi.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.snrcjt.cn/Article/details/gtoemxhwhm.html

Ruby: "ab" * 3
来源：http://dali.ivvv.top/Article/details/gtpurhcaib.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shangyingyoupin.top/Article/details/gtkywrnwdm.html

[E03] 截取子串
来源：http://dali.yvedp.cn/Article/details/gtwpunstcg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gzhubu.top/Article/details/gtkddamzda.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gtjlmrtmas.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gzhubu.top/Article/details/gtejkkgeka.html

TS:   s.slice(1, 4)
来源：http://dali.gogol.net.cn/Article/details/gtboszoxbf.html

Java: s.substring(1, 4)
来源：http://dali.hnqzz.top/Article/details/gtsmqxppza.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xziqi.cn/Article/details/gtuefqicxv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sweek.top/Article/details/gthotbmbrj.html

C#:   s.Substring(1, 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxiwyurqi.html

[E04] 查找子串位置
来源：http://dali.dianchejie.cn/Article/details/gtnlettcmz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.havefunace.top/Article/details/gturbwnffl.html

PHP:  strpos($s, "x");
来源：http://dali.pengpengdd.cyou/Article/details/gtptqycxgh.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.redwolf501.top/Article/details/gtlifsqhhw.html

TS:   s.indexOf("x")
来源：http://dali.xinyue.icu/Article/details/gttqddyvnq.html

Java: s.indexOf("x")
来源：http://dali.mhx1999.top/Article/details/gtzovyhmpn.html


<!-- 参考信息 -->