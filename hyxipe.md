代发 wailian999

Go:   arr[0]; arr[0] = 9
来源：http://dali.aibaodan.cn/Article/details/gtyfzpqqei.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtermzutiv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj20258.top/Article/details/gtfoagerml.html

[D06] 数组长度
来源：http://dali.hnxiangtu.top/Article/details/gtuwzusbgg.html

Py:   len(arr)
来源：http://dali.316326.xyz/Article/details/gtxwtxvfdn.html

PHP:  count($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxxmqcega.html

JS:   arr.length
来源：http://dali.cheryme.top/Article/details/gthahqeedn.html

TS:   arr.length
来源：http://dali.jqgufenzy.top/Article/details/gtticxvxik.html

Java: list.size();
来源：http://dali.xziqi.cn/Article/details/gtpztdwltj.html

Go:   len(arr)
来源：http://dali.dianchejie.cn/Article/details/gtzzjsoipc.html

Ruby: arr.length; arr.size
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfikakque.html

C#:   list.Count;
来源：http://dali.pycfn.com/Article/details/gtnzzmlxta.html

[D07] 切片 / 取子数组
来源：http://dali.gogol.net.cn/Article/details/gtsybmjwyr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zdqjudy.top/Article/details/gtofnirqjs.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yueranfly.top/Article/details/gtrsceisez.html

JS:   arr.slice(1, 4);
来源：http://dali.zycfv.cn/Article/details/gtmnathtvu.html

TS:   arr.slice(1, 4);
来源：http://dali.daria6918.cn/Article/details/gtbcgvlxry.html

Java: list.subList(1, 4);
来源：http://dali.yonumen.top/Article/details/gtwquknrvp.html

Go:   arr[1:4]
来源：http://dali.jinqigufen.top/Article/details/gtavwdafke.html

Ruby: arr[1, 3]
来源：http://dali.yanxiufei.cn/Article/details/gtppwftaue.html

C#:   list.GetRange(1, 3);
来源：http://dali.yangfankeji.com/Article/details/gtqwhxdeuy.html

[D08] 合并两个数组
来源：http://dali.yuxming.cn/Article/details/gtmxvviign.html

Py:   a + b;  a.extend(b)
来源：http://dali.0kj1m.cn/Article/details/gtcnfzlztg.html

PHP:  array_merge($a, $b);
来源：http://dali.yonumen.top/Article/details/gtawlggpse.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.haohaochexian.top/Article/details/gtnzkkehrn.html

TS:   [...a, ...b];
来源：http://dali.dashuyun.cn/Article/details/gtcklafadt.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxnlvwhub.html

Go:   append(a, b...)
来源：http://dali.bjfxy.top/Article/details/gtnmhoxkks.html

Ruby: a + b;  a.concat(b)
来源：http://dali.chenlongwang.top/Article/details/gtjesanela.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gttulaggfy.html

[D09] 排序（升序）
来源：http://dali.svipenyu.cn/Article/details/gttrepuolz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sxryk.cn/Article/details/gtxtefhkyx.html

PHP:  sort($arr);
来源：http://dali.tianlin.xyz/Article/details/gtkuhqzgna.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ehwqpu.com/Article/details/gtqdnugqva.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.bjfxy.top/Article/details/gtjragwofq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhoulong.xyz/Article/details/gtqmxubrmn.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtfegtuffl.html

Ruby: arr.sort
来源：http://dali.meibo888.top/Article/details/gteywqhxoa.html

C#:   list.Sort();
来源：http://dali.cqqwz.cn/Article/details/gtibvxtvyj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.kuanghao11.cn/Article/details/gtzibsnhdk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtabjjvzzn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yueranfly.top/Article/details/gtplcuypcr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuetiantiany.cn/Article/details/gtcwdbjopp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhengqikj.top/Article/details/gtdwcfhsug.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jqgfzy.top/Article/details/gtmvylahij.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sysykeji.top/Article/details/gtlwodukxh.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xuetiantiany.cn/Article/details/gtzfbknsjb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinghuilouyu.cn/Article/details/gtrticyicy.html

[D11] 反转数组
来源：http://dali.cashguo.top/Article/details/gttijbvisx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yonumen.top/Article/details/gttcjancij.html

PHP:  array_reverse($arr);
来源：http://dali.ybcxt.top/Article/details/gtjzthmesv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yanxiufei.cn/Article/details/gtcotdbasi.html

TS:   [...arr].reverse();
来源：http://dali.zhiwuduotai.top/Article/details/gtpgllstyq.html

Java: Collections.reverse(list);
来源：http://dali.birdmap.top/Article/details/gthqbakqgm.html

Go:   slices.Reverse(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtnsyhsesx.html

Ruby: arr.reverse
来源：http://dali.yonumen.top/Article/details/gtmgfzwklj.html

C#:   list.Reverse();
来源：http://dali.haohaochexian.top/Article/details/gtmlzqhcmj.html

[D12] 查找元素下标
来源：http://dali.hfpthk.cn/Article/details/gtcnlwpmdx.html

Py:   arr.index(x);  x in arr
来源：http://dali.hammf.cn/Article/details/gtnfisfoms.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ivvv.top/Article/details/gtilinkubc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnqzz.top/Article/details/gtdyibewzs.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuanzhike.top/Article/details/gtvplwaofv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.9152youxi.cn/Article/details/gtvvowhtky.html

Go:   slices.Index(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtnaicbjff.html

Ruby: arr.index(x)
来源：http://dali.quarkkingdee.top/Article/details/gtqaizfgin.html

C#:   list.IndexOf(x);
来源：http://dali.ehwqpu.com/Article/details/gtqfzpcass.html

[D13] 过滤（保留满足条件的）
来源：http://dali.9152youxi.cn/Article/details/gtruhlishh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.fengsongda.top/Article/details/gtuqwctgea.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.tian-w.cn/Article/details/gtynyvafwd.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ydzc1.top/Article/details/gtcwjbxvjg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zdqjudy.top/Article/details/gtaolnmqsa.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.aibaodan.cn/Article/details/gtrkavubwu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nwbrower.top/Article/details/gtktyrpjoq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ehwqpu.com/Article/details/gtrcerraie.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ppjwa.cn/Article/details/gtkjqehjnj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tian-w.cn/Article/details/gtyaucvfoa.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.mhx1999.top/Article/details/gtiuokfnns.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.havefunace.top/Article/details/gtfgcsgwvx.html

JS:   arr.map(x => x * 2)
来源：http://dali.yanxiufei.cn/Article/details/gtpmhrkwzs.html

TS:   arr.map(x => x * 2)
来源：http://dali.daria6918.cn/Article/details/gtsrordlad.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtdkhydqhu.html

Go:   // 手写循环
来源：http://dali.daria6918.cn/Article/details/gtwyzdvztk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.fzhhl.top/Article/details/gtvimupwzm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tanke756.top/Article/details/gtafuyvgtc.html

[D15] 去重
来源：http://dali.ivvv.top/Article/details/gtcmbosoif.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cdnleiting.top/Article/details/gtqjwpiwkc.html

PHP:  array_unique($arr);
来源：http://dali.iojbl.cn/Article/details/gttcdvrpgi.html

JS:   [...new Set(arr)]
来源：http://dali.shangyingyoupin.top/Article/details/gtnawrzkcj.html

TS:   [...new Set(arr)]
来源：http://dali.jinghuilouyu.cn/Article/details/gthzgnavim.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.birdmap.top/Article/details/gtfvzqyypt.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.tianlin.xyz/Article/details/gttfnhwryl.html

Ruby: arr.uniq
来源：http://dali.yj20258888.top/Article/details/gtkmgnqtxx.html

C#:   list.Distinct().ToList()
来源：http://dali.bjfxy.top/Article/details/gtxmqpafqn.html

[D16] 求和与平均值
来源：http://dali.316326.xyz/Article/details/gttcewqtzp.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hysaishi.cn/Article/details/gtsfkahtxh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hywenlv.cn/Article/details/gttzpamkdm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenlongwang.top/Article/details/gtbhkgydxf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtifnspkfm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.tanke756.top/Article/details/gtmnwkezoc.html

Go:   // 手写循环累加
来源：http://dali.zdqjudy.top/Article/details/gtmhiqwjrt.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwnpyqaig.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gtnlnffiiu.html

[D17] 最大值与最小值
来源：http://dali.bjfxy.top/Article/details/gtisbibtsi.html

Py:   max(arr);  min(arr)
来源：http://dali.zhengqikj.top/Article/details/gtvmanslai.html

PHP:  max($arr);  min($arr);
来源：http://dali.ybcxt.top/Article/details/gtunrerkul.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.daria6918.cn/Article/details/gtqkqgvtce.html

TS:   Math.max(...arr);
来源：http://dali.sweek.top/Article/details/gtnpyjlfvg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jyoumei.cn/Article/details/gtfmqwxdiu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.pycfn.com/Article/details/gtldsbhitr.html

Ruby: arr.max;  arr.min
来源：http://dali.xuetiantiany.cn/Article/details/gtawhturtv.html

C#:   list.Max();  list.Min()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqcjnbetu.html

[D18] 扁平化嵌套数组
来源：http://dali.zhixingplan.top/Article/details/gtcuynjnjz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xylfe.cn/Article/details/gtddbyydlm.html

PHP:  array_merge(...$nested);
来源：http://dali.aizwys.cn/Article/details/gtzntbcrvn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hysaishi.cn/Article/details/gtqkireqhh.html

TS:   nested.flat();
来源：http://dali.xinyue.icu/Article/details/gthjnktecg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.aibaodan.cn/Article/details/gteibcivxf.html

Go:   // 手写双层循环
来源：http://dali.ppjwa.cn/Article/details/gtdustfmws.html

Ruby: nested.flatten
来源：http://dali.gzhubu.top/Article/details/gttkjeagrf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.gogol.net.cn/Article/details/gtxjntfawp.html

[D19] 按字段分组
来源：http://dali.pycfn.com/Article/details/gtmzsfonpv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.9152youxi.cn/Article/details/gtxdcwqqbw.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yonumen.top/Article/details/gtjjtfzofv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhongyouzk.top/Article/details/gtcgyucjbe.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhiwuduotai.top/Article/details/gtasuxxbjz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hfpthk.cn/Article/details/gtdllrzscp.html

Go:   // 手写 map[string][]T
来源：http://dali.tianlin.xyz/Article/details/gtwwckbuwf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jyoumei.cn/Article/details/gtekjsonrz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.wangshuangyany.cn/Article/details/gtnhafwkbr.html

[D20] 统计每个元素出现次数
来源：http://dali.chenzaomai.com/Article/details/gtfklnbayt.html

Py:   Counter(arr)
来源：http://dali.yueranfly.top/Article/details/gtvulpdiwr.html

PHP:  array_count_values($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtzkvqbsak.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangshuangyany.cn/Article/details/gtvqkjvurx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sysykeji.top/Article/details/gteoryaawn.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.svipenyu.cn/Article/details/gtgoknrtar.html

Go:   // 手写 map[T]int
来源：http://dali.havefunace.top/Article/details/gtpblggtyd.html

Ruby: arr.tally
来源：http://dali.dianchejie.cn/Article/details/gttxozhqby.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hywenlv.cn/Article/details/gtfmvhxwgh.html

[D21] 判断是否包含某元素
来源：http://dali.shzxlz.cn/Article/details/gtdsvsxpdg.html

Py:   x in arr
来源：http://dali.birdmap.top/Article/details/gtswjeozvj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.tianlin.xyz/Article/details/gtaibwpzgf.html

JS:   arr.includes(x)
来源：http://dali.yongpay.top/Article/details/gtgheefdue.html

TS:   arr.includes(x)
来源：http://dali.ivvv.top/Article/details/gtsohhnqte.html

Java: list.contains(x)
来源：http://dali.jyoumei.cn/Article/details/gtnfgryeme.html

Go:   slices.Contains(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtvowmauhs.html

Ruby: arr.include?(x)
来源：http://dali.snrcjt.cn/Article/details/gtttotfdnv.html

C#:   list.Contains(x)
来源：http://dali.aizwys.cn/Article/details/gtrctiiomt.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tianlin.xyz/Article/details/gtxmtokaww.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.daxiang520.top/Article/details/gtnbifvuaf.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yongpay.top/Article/details/gtwamkjagz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jianghu66.top/Article/details/gtpnzstcmr.html

TS:   [...arr];
来源：http://dali.chenjidiqi.icu/Article/details/gtlvwhbvgf.html

Java: new ArrayList<>(list);
来源：http://dali.nanxuanxn.top/Article/details/gtqsdaczur.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.smart0.xyz/Article/details/gtrrnduefl.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hnqzz.top/Article/details/gtvaqnaikr.html

C#:   new List<int>(list);
来源：http://dali.zycfv.cn/Article/details/gttynzrujk.html

[D23] reduce 累积计算
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpjsbimnu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.smart0.xyz/Article/details/gtbxjliakt.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlwucwxtp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ydzc1.top/Article/details/gtaxqrztos.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtiabbgixc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.gotoacloud.top/Article/details/gtduvpmxku.html

Go:   // 手写循环
来源：http://dali.pengpengdd.cyou/Article/details/gtbnwuwdaj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.wangshuangyany.cn/Article/details/gtlocifxsq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gogol.net.cn/Article/details/gttymubgif.html

[D24] 字典 / Map 基本操作
来源：http://dali.hnxiangtu.top/Article/details/gtyypgpjst.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.chenjidiqi.icu/Article/details/gtqepfxvyn.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.daria6918.cn/Article/details/gtkpoclppb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.0kj1m.cn/Article/details/gtyuidjgxm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtztkhevxf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xuanzx.com/Article/details/gtubofkvcz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gtmnetwhdo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hfpthk.cn/Article/details/gtrenfqbjm.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shzxlz.cn/Article/details/gtxmrstlxm.html

[D25] Set 集合去重与交并差
来源：http://dali.316326.xyz/Article/details/gtjatqadpw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.dianchejie.cn/Article/details/gtnzwpgurk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.daxiang520.top/Article/details/gtsijgepli.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.c1oappe.top/Article/details/gtyemnpecl.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.daxiang520.top/Article/details/gtdhsjqpbl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xziqi.cn/Article/details/gtptxeiffv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyaumiksq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.chenzaomai.com/Article/details/gtattqjcmm.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbbjnupa.html

[D26] 数组转字符串
来源：http://dali.yueranfly.top/Article/details/gtxqploayq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ppjwa.cn/Article/details/gtqkwwqbch.html

PHP:  implode(", ", $arr);
来源：http://dali.svipenyu.cn/Article/details/gtupkgyrga.html

JS:   arr.join(", ")
来源：http://dali.andypj.xyz/Article/details/gtygpslwmt.html

TS:   arr.join(", ")
来源：http://dali.pycfn.com/Article/details/gtehsmqxop.html

Java: String.join(", ", list)
来源：http://dali.hywenlv.cn/Article/details/gtvvjxzdud.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ivvv.top/Article/details/gtmcyoftav.html

Ruby: arr.join(", ")
来源：http://dali.sufxvd.cn/Article/details/gtxvbjrsom.html

C#:   string.Join(", ", list)
来源：http://dali.yangfankeji.com/Article/details/gtihpbzjff.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthuzxjkym.html

E. 字符串处理
来源：http://dali.chenlongwang.top/Article/details/gtgjhquyys.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtjornwlce.html

[E01] 拼接字符串
来源：http://dali.c1oappe.top/Article/details/gtefshaoqx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.kuanghao11.cn/Article/details/gtmwlllrrp.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shuidangran.top/Article/details/gtbhcdiiri.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenjidiqi.icu/Article/details/gteomrtruy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cashguo.top/Article/details/gtazjjnron.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jiagoushi.top/Article/details/gtvudpfypd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenjidiqi.icu/Article/details/gtrbytzije.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hysaishi.cn/Article/details/gtwnymphst.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtkvpdwlbc.html

[E02] 重复字符串
来源：http://dali.ppjwa.cn/Article/details/gtsldimeae.html

Py:   "ab" * 3
来源：http://dali.cqqwz.cn/Article/details/gtyxvvzmyx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.kuanghao11.cn/Article/details/gthmnhmszi.html

JS:   "ab".repeat(3)
来源：http://dali.shzxlz.cn/Article/details/gtpmaovjey.html

TS:   "ab".repeat(3)
来源：http://dali.ivvv.top/Article/details/gtrirgzfqe.html

Java: "ab".repeat(3)
来源：http://dali.xziqi.cn/Article/details/gtkacrrepc.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jyoumei.cn/Article/details/gtnbqtyose.html

Ruby: "ab" * 3
来源：http://dali.zhongyouzk.top/Article/details/gtvjzgmmuh.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenlongwang.top/Article/details/gtaexlhrph.html

[E03] 截取子串
来源：http://dali.xziqi.cn/Article/details/gtwdlcgzfp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.aizwys.cn/Article/details/gtpyomejmv.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gtjkcpzqfv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.sweek.top/Article/details/gtgljvlawj.html

TS:   s.slice(1, 4)
来源：http://dali.zycfv.cn/Article/details/gtgbgooxcy.html

Java: s.substring(1, 4)
来源：http://dali.0kj1m.cn/Article/details/gtpmayobim.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ivvv.top/Article/details/gtrdbvopqz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.bjfxy.top/Article/details/gtnodkrgzq.html

C#:   s.Substring(1, 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaavkqhsx.html

[E04] 查找子串位置
来源：http://dali.fengsongda.top/Article/details/gtfycrycnu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.aibaodan.cn/Article/details/gtzmujvlnm.html

PHP:  strpos($s, "x");
来源：http://dali.svipenyu.cn/Article/details/gtxzhemfjh.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ybcxt.top/Article/details/gtkvosbmwe.html

TS:   s.indexOf("x")
来源：http://dali.fengsongda.top/Article/details/gtludhefxg.html

Java: s.indexOf("x")
来源：http://dali.cdnleiting.top/Article/details/gtxinqlnvj.html

Go:   strings.Index(s, "x")
来源：http://dali.jqgufenzy.top/Article/details/gtmfasvqtk.html

Ruby: s.index("x")
来源：http://dali.316326.xyz/Article/details/gtqwbmtxgi.html

C#:   s.IndexOf("x")
来源：http://dali.jinqigufen.top/Article/details/gtzqpatvuc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jiagoushi.top/Article/details/gtutlwcwum.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gttwywlnlp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpxpomamm.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gtwwqglrry.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.andypj.xyz/Article/details/gtinqiexfr.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sysykeji.top/Article/details/gtlsjqaazs.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.kuanghao11.cn/Article/details/gtlrdcnrdn.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhixingplan.top/Article/details/gtlytxlngu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gogol.net.cn/Article/details/gtehrqnddr.html

[E06] 替换子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgaysrhph.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.kuanghao11.cn/Article/details/gtfwtztjpd.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sxryk.cn/Article/details/gtpkxkdcvu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtoaibuepr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtcflmaipz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtgcjwxvvl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.vqdsnc.cn/Article/details/gtrxgemsmo.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gtjmdhnnrd.html

C#:   s.Replace("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gteiiuuimw.html

[E07] 按分隔符拆分
来源：http://dali.havefunace.top/Article/details/gttlbfjtgy.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cucudq.cn/Article/details/gtbskwliqq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.c1oappe.top/Article/details/gttblcmqge.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yongpay.top/Article/details/gtdlpwydhm.html

TS:   s.split(",")
来源：http://dali.gotoacloud.top/Article/details/gtnwekhnjr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwosvyzpi.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.andypj.xyz/Article/details/gtmzyrhnll.html

Ruby: s.split(",");  s.split
来源：http://dali.0kj1m.cn/Article/details/gtnftphhzb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.chenjidiqi.icu/Article/details/gtqzwhreaq.html

[E08] 数组按分隔符合并
来源：http://dali.ivvv.top/Article/details/gtohztoyin.html

Py:   ",".join(items)
来源：http://dali.jianghu66.top/Article/details/gtacrkbgbo.html

PHP:  implode(",", $items);
来源：http://dali.cucudq.cn/Article/details/gtaddpetxl.html

JS:   items.join(",")
来源：http://dali.yj202588.top/Article/details/gtxkciaxzr.html

TS:   items.join(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttdygbwcq.html

Java: String.join(",", items)
来源：http://dali.jiagoushi.top/Article/details/gthjmiqzby.html

Go:   strings.Join(items, ",")
来源：http://dali.fengsongda.top/Article/details/gtfqdsyqko.html

Ruby: items.join(",")
来源：http://dali.aizwys.cn/Article/details/gtxvwrciph.html

C#:   string.Join(",", items)
来源：http://dali.svipenyu.cn/Article/details/gtoyuauite.html

[E09] 去除所有空白字符
来源：http://dali.tanke756.top/Article/details/gtyeawfudb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.kuanghao11.cn/Article/details/gtxwfvxlod.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtfncqzsyd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xuetiantiany.cn/Article/details/gtqfcngexd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.0kj1m.cn/Article/details/gtvobpqwby.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhengqikj.top/Article/details/gtedzbvnug.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hywenlv.cn/Article/details/gtizcusxxx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jqgufenzy.top/Article/details/gteijbtjrh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.meibo888.top/Article/details/gtwrpxgjfz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.wangdashe.top/Article/details/gtktzyuxfi.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.havefunace.top/Article/details/gtastspavw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.dashuyun.cn/Article/details/gtgizqxpxb.html

JS:   "7".padStart(3, "0")
来源：http://dali.pycfn.com/Article/details/gtetphslot.html

TS:   "7".padStart(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gtjnebzpwm.html

Java: String.format("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gtpjtyqhfc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jlsjyb.cn/Article/details/gtswpozyrx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvrwclczs.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.daria6918.cn/Article/details/gtxtbozdfx.html

[E11] 反转字符串
来源：http://dali.jyoumei.cn/Article/details/gtjzrfsjdt.html

Py:   s[::-1]
来源：http://dali.tianlin.xyz/Article/details/gtneinilre.html

PHP:  strrev($s);
来源：http://dali.jinqigufen.top/Article/details/gtofrdwfhp.html

JS:   [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gttqalmmqd.html

TS:   [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gteldnjiqe.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.daxiang520.top/Article/details/gttsasygca.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhengqikj.top/Article/details/gtbhdqyzsl.html

Ruby: s.reverse
来源：http://dali.pengpengdd.cyou/Article/details/gtgulftuqf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sweek.top/Article/details/gtodqqpiwi.html

[E12] 统计某字符出现次数
来源：http://dali.aizwys.cn/Article/details/gtmvxnnbwz.html

Py:   s.count("a")
来源：http://dali.havefunace.top/Article/details/gttcopzpyd.html

PHP:  substr_count($s, "a");
来源：http://dali.ppjwa.cn/Article/details/gtuzutooel.html

JS:   s.split("a").length - 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtpgwqciuq.html

TS:   s.split("a").length - 1
来源：http://dali.hongshengwenyu.top/Article/details/gthnvygjpy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.vqdsnc.cn/Article/details/gtckfalqqn.html


<!-- 参考信息 -->