代发 wailian999

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.aibaodan.cn/Article/details/gthzkietib.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.dianchejie.cn/Article/details/gtflmvhtde.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zdqjudy.top/Article/details/gtuuaqebpk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.aibaodan.cn/Article/details/gtbdugzeio.html

[D11] 反转数组
来源：http://dali.kuanghao11.cn/Article/details/gtcfentybx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.haohaochexian.top/Article/details/gtvnmkkfjo.html

PHP:  array_reverse($arr);
来源：http://dali.aibaodan.cn/Article/details/gtlcpxauhw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jqgfzy.top/Article/details/gtctjsfsaz.html

TS:   [...arr].reverse();
来源：http://dali.tianlin.xyz/Article/details/gtyycxxsrd.html

Java: Collections.reverse(list);
来源：http://dali.yangfankeji.com/Article/details/gtbsnhssqa.html

Go:   slices.Reverse(arr)
来源：http://dali.fzhhl.top/Article/details/gtzhjeyrvo.html

Ruby: arr.reverse
来源：http://dali.zhoulong.xyz/Article/details/gtgxyeqplx.html

C#:   list.Reverse();
来源：http://dali.feifeiyinyue.top/Article/details/gtvlebahvt.html

[D12] 查找元素下标
来源：http://dali.hongshengwenyu.top/Article/details/gtyrztldpb.html

Py:   arr.index(x);  x in arr
来源：http://dali.gaohongyu789.top/Article/details/gtqumezjyt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hammf.cn/Article/details/gtpbdbioaq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fzhhl.top/Article/details/gtlwipbjsa.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gogol.net.cn/Article/details/gtixclbimi.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yvedp.cn/Article/details/gtxmmymnog.html

Go:   slices.Index(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtdhfohsyd.html

Ruby: arr.index(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdpfwbmzc.html

C#:   list.IndexOf(x);
来源：http://dali.chenzaomai.com/Article/details/gtaenebjcp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.mhx1999.top/Article/details/gtapbrbqwq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.gotoacloud.top/Article/details/gtmmyhistc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.andypj.xyz/Article/details/gtxcagclry.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jyoumei.cn/Article/details/gtstvxwbra.html

TS:   arr.filter(x => x > 3)
来源：http://dali.aibaodan.cn/Article/details/gtaxncnusb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sysykeji.top/Article/details/gtfjkfcwdz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cashguo.top/Article/details/gtmegduitj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yuanzhike.top/Article/details/gttnengqvj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenlongwang.top/Article/details/gteswbunkk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhongyouzk.top/Article/details/gtwefipkgm.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.c1oappe.top/Article/details/gtfldjbllg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.nanxinkj.top/Article/details/gtsocboghi.html

JS:   arr.map(x => x * 2)
来源：http://dali.snrcjt.cn/Article/details/gtouyjwljh.html

TS:   arr.map(x => x * 2)
来源：http://dali.c1oappe.top/Article/details/gtirsblpjw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cdnleiting.top/Article/details/gtvkpwrswg.html

Go:   // 手写循环
来源：http://dali.shzxlz.cn/Article/details/gtukmltmjz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cheryme.top/Article/details/gtnmqorszm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.guannengcc.top/Article/details/gtzggemceg.html

[D15] 去重
来源：http://dali.yj202588.top/Article/details/gtzuxvoerp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sweek.top/Article/details/gtdpubyxpd.html

PHP:  array_unique($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsditbvtq.html

JS:   [...new Set(arr)]
来源：http://dali.dashuyun.cn/Article/details/gtskofecmw.html

TS:   [...new Set(arr)]
来源：http://dali.guannengcc.top/Article/details/gtjhzbjugh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.0kj1m.cn/Article/details/gtlwgzxmxc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hfpthk.cn/Article/details/gttmgzlpwy.html

Ruby: arr.uniq
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbapnadxl.html

C#:   list.Distinct().ToList()
来源：http://dali.yueranfly.top/Article/details/gtspurrghr.html

[D16] 求和与平均值
来源：http://dali.xuanzx.com/Article/details/gtgasyrnpu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.meibo888.top/Article/details/gttacoevah.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.fzhhl.top/Article/details/gtgervtizr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hfpthk.cn/Article/details/gtlkyzllgq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shuidangran.top/Article/details/gtwxnqzcaj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtialtajzr.html

Go:   // 手写循环累加
来源：http://dali.ehwqpu.com/Article/details/gtvxzqluni.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tianlin.xyz/Article/details/gtlgytvvgg.html

C#:   list.Sum();  list.Average()
来源：http://dali.smart0.xyz/Article/details/gttjjjvplm.html

[D17] 最大值与最小值
来源：http://dali.cqqwz.cn/Article/details/gtckrrpwuh.html

Py:   max(arr);  min(arr)
来源：http://dali.hfpthk.cn/Article/details/gtaupcdyft.html

PHP:  max($arr);  min($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtuedazvpr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jqgufenzy.top/Article/details/gtqeuvcuyj.html

TS:   Math.max(...arr);
来源：http://dali.smart0.xyz/Article/details/gtmplvmlej.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yj202588.top/Article/details/gtbntqsiii.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yongpay.top/Article/details/gtzedakuvg.html

Ruby: arr.max;  arr.min
来源：http://dali.yanxiufei.cn/Article/details/gtwmzidrul.html

C#:   list.Max();  list.Min()
来源：http://dali.yvedp.cn/Article/details/gtgcsnfiyn.html

[D18] 扁平化嵌套数组
来源：http://dali.nanxuanxn.top/Article/details/gtxwhirtos.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hammf.cn/Article/details/gtilhhtriz.html

PHP:  array_merge(...$nested);
来源：http://dali.sufxvd.cn/Article/details/gtodorwwbc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yj202588.top/Article/details/gtyupplsau.html

TS:   nested.flat();
来源：http://dali.sxryk.cn/Article/details/gtxxbiczsy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.daria6918.cn/Article/details/gttxzsmchx.html

Go:   // 手写双层循环
来源：http://dali.gaohongyu789.top/Article/details/gtdvtrhqrn.html

Ruby: nested.flatten
来源：http://dali.nanxuanxn.top/Article/details/gtnxedwdpv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ivvv.top/Article/details/gtrudbpqfk.html

[D19] 按字段分组
来源：http://dali.sweek.top/Article/details/gtnhjctpep.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtznoobupv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gotoacloud.top/Article/details/gtybrmuslf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shanyushiyangkeji.top/Article/details/gttmukpaeu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cdnleiting.top/Article/details/gtobovhvwr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ydzc1.top/Article/details/gtwcrgwbmh.html

Go:   // 手写 map[string][]T
来源：http://dali.jlsjyb.cn/Article/details/gtaugfpnxl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqnpmardq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.iojbl.cn/Article/details/gtchxjxahy.html

[D20] 统计每个元素出现次数
来源：http://dali.quarkkingdee.top/Article/details/gtcvwrfxyp.html

Py:   Counter(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtkmoitmjz.html

PHP:  array_count_values($arr);
来源：http://dali.ybcxt.top/Article/details/gtbnlxlobf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj202588.top/Article/details/gtpypiqwna.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hongshengwenyu.top/Article/details/gtqxihuyfh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xuetiantiany.cn/Article/details/gtfvywhrwl.html

Go:   // 手写 map[T]int
来源：http://dali.chenzaomai.com/Article/details/gtotqvzxhf.html

Ruby: arr.tally
来源：http://dali.hfpthk.cn/Article/details/gtmnclhluq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.iojbl.cn/Article/details/gtzvyewzqx.html

[D21] 判断是否包含某元素
来源：http://dali.aizwys.cn/Article/details/gtrfxjlwal.html

Py:   x in arr
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvsmbrzaq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ybcxt.top/Article/details/gtpdmdidlp.html

JS:   arr.includes(x)
来源：http://dali.cdnleiting.top/Article/details/gtcphoxkoh.html

TS:   arr.includes(x)
来源：http://dali.ivvv.top/Article/details/gtuvqfwvkk.html

Java: list.contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gtgflfxaqp.html

Go:   slices.Contains(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtwzzpchjv.html

Ruby: arr.include?(x)
来源：http://dali.yueranfly.top/Article/details/gtsmpikpjq.html

C#:   list.Contains(x)
来源：http://dali.9152youxi.cn/Article/details/gtptydxepq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cashguo.top/Article/details/gtsmhhambl.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jianghu66.top/Article/details/gtoxpkgszy.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.wangshuangyany.cn/Article/details/gtohmsfdqh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtdtkclfhg.html

TS:   [...arr];
来源：http://dali.mhx1999.top/Article/details/gtbamqzcfj.html

Java: new ArrayList<>(list);
来源：http://dali.bjfxy.top/Article/details/gtqqgtsfik.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.c1oappe.top/Article/details/gtcyrzqhfb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhiwuduotai.top/Article/details/gtwegkinrp.html

C#:   new List<int>(list);
来源：http://dali.yuanzhike.top/Article/details/gtwbgtmbea.html

[D23] reduce 累积计算
来源：http://dali.bjfxy.top/Article/details/gtxhibltmg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cucudq.cn/Article/details/gtkoloysmn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtgqqhvxdu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtvxhyiutx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttymgfhmb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenjidiqi.icu/Article/details/gtezzqqwzs.html

Go:   // 手写循环
来源：http://dali.wangdashe.top/Article/details/gtctgeobfa.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shanyushiyangtech.top/Article/details/gtwghmywcs.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hysaishi.cn/Article/details/gtwnxoohwv.html

[D24] 字典 / Map 基本操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gteiigtuki.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtheroaugg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.smart0.xyz/Article/details/gtcbnecvbc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.smart0.xyz/Article/details/gtfspktere.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yj202588.top/Article/details/gtpandsbqb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xylfe.cn/Article/details/gtdrzodmoi.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jlsjyb.cn/Article/details/gtjlntsqfs.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tianlin.xyz/Article/details/gtigckjtbi.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.pycfn.com/Article/details/gtlwjmqwbp.html

[D25] Set 集合去重与交并差
来源：http://dali.cucudq.cn/Article/details/gtqmypfywn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhoulong.xyz/Article/details/gtmjookkoz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gotoacloud.top/Article/details/gtoxvmonvs.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhengqikj.top/Article/details/gtzixdjkbi.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.nanxinkj.top/Article/details/gtluyquoxf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.redwolf501.top/Article/details/gtypasfxmr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cashguo.top/Article/details/gtayteqluo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtaopkittx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhixingplan.top/Article/details/gtcprgiair.html

[D26] 数组转字符串
来源：http://dali.guowangkeji.top/Article/details/gtpizdxobp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yueranfly.top/Article/details/gtgbitfrpx.html

PHP:  implode(", ", $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtonkufgcq.html

JS:   arr.join(", ")
来源：http://dali.yj202588.top/Article/details/gtyijmsvki.html

TS:   arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gtdlfkfysj.html

Java: String.join(", ", list)
来源：http://dali.yongpay.top/Article/details/gtzqfyuqau.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xylfe.cn/Article/details/gtlyamuufv.html

Ruby: arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gtarxzkgfg.html

C#:   string.Join(", ", list)
来源：http://dali.xuetiantiany.cn/Article/details/gtlygbioqm.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtercwqpph.html

E. 字符串处理
来源：http://dali.gzhubu.top/Article/details/gtxxdposcw.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtqykbsvsl.html

[E01] 拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gtdtgolypa.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.smart0.xyz/Article/details/gtscqcpybm.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.gotoacloud.top/Article/details/gtpexfjrus.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ppjwa.cn/Article/details/gtqydwqbti.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.c1oappe.top/Article/details/gtxweswesz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.9152youxi.cn/Article/details/gtsyinsicz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.guannengcc.top/Article/details/gtwngasxqa.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cucudq.cn/Article/details/gtqdgxnukz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yj202588.top/Article/details/gtqoisyoor.html

[E02] 重复字符串
来源：http://dali.guowangkeji.top/Article/details/gtfypbxufm.html

Py:   "ab" * 3
来源：http://dali.havefunace.top/Article/details/gttxyxdkum.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhongyouzk.top/Article/details/gtqykurijg.html

JS:   "ab".repeat(3)
来源：http://dali.gaohongyu789.top/Article/details/gtcbkorble.html

TS:   "ab".repeat(3)
来源：http://dali.sxryk.cn/Article/details/gtqmjhauzd.html

Java: "ab".repeat(3)
来源：http://dali.tian-w.cn/Article/details/gtdzwimumd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.havefunace.top/Article/details/gtqjfivsiy.html

Ruby: "ab" * 3
来源：http://dali.xylfe.cn/Article/details/gtbzmzamzh.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhoulong.xyz/Article/details/gtgebqadyz.html

[E03] 截取子串
来源：http://dali.yj20258.top/Article/details/gtyhyvwkzg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sweek.top/Article/details/gthcnegjkq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gtphxyleph.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.nanxuanxn.top/Article/details/gtfykatzhj.html

TS:   s.slice(1, 4)
来源：http://dali.yj202588.top/Article/details/gtclyewyiu.html

Java: s.substring(1, 4)
来源：http://dali.jianghu66.top/Article/details/gtsstdlmvl.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.nwbrower.top/Article/details/gtofhyvtqr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.chenjidiqi.icu/Article/details/gttpqwcwws.html

C#:   s.Substring(1, 3)
来源：http://dali.jqgufenzy.top/Article/details/gthzgyhfbd.html

[E04] 查找子串位置
来源：http://dali.tanke756.top/Article/details/gthasyychz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jlsjyb.cn/Article/details/gtlrwfvvzl.html

PHP:  strpos($s, "x");
来源：http://dali.fzhhl.top/Article/details/gtzortdeyf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwbbhiofq.html

TS:   s.indexOf("x")
来源：http://dali.wangshuangyany.cn/Article/details/gtdantiids.html

Java: s.indexOf("x")
来源：http://dali.wangshuangyany.cn/Article/details/gtdgwtcjja.html

Go:   strings.Index(s, "x")
来源：http://dali.cqqwz.cn/Article/details/gtjhqwkrmy.html

Ruby: s.index("x")
来源：http://dali.shuidangran.top/Article/details/gteuqoojsk.html

C#:   s.IndexOf("x")
来源：http://dali.cdnleiting.top/Article/details/gtuwihlgsx.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.c1oappe.top/Article/details/gttnshkcax.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.dianchejie.cn/Article/details/gtkriygoem.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gaohongyu789.top/Article/details/gtcsgumnkz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.guowangkeji.top/Article/details/gtjjrymumy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hnqzz.top/Article/details/gtvwocotbw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gaohongyu789.top/Article/details/gtdjhevwqy.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hywenlv.cn/Article/details/gtrtbyxsgc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zdqjudy.top/Article/details/gttutarkem.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yj20258.top/Article/details/gtscdtfjzc.html

[E06] 替换子串
来源：http://dali.nanxinkj.top/Article/details/gtjxihsucv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ydzc1.top/Article/details/gtrqvhyoiz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj20258888.top/Article/details/gtrdblvfqr.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtjqbchict.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gthgtfmuwt.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtmzzmpirm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtnubqsakf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtpqtnymfh.html

C#:   s.Replace("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtshbeidkw.html

[E07] 按分隔符拆分
来源：http://dali.9152youxi.cn/Article/details/gtnqdnlaqq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jiagoushi.top/Article/details/gtcalndnnh.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.9152youxi.cn/Article/details/gtrnuizxyo.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj20258.top/Article/details/gtdcncgioh.html

TS:   s.split(",")
来源：http://dali.xylfe.cn/Article/details/gtsrqsmhup.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shzxlz.cn/Article/details/gtjzydxcok.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xziqi.cn/Article/details/gthixucyot.html

Ruby: s.split(",");  s.split
来源：http://dali.cdnleiting.top/Article/details/gtdybkbwxm.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yuxming.cn/Article/details/gttueimzeu.html

[E08] 数组按分隔符合并
来源：http://dali.xuetiantiany.cn/Article/details/gtlxcvwdfn.html

Py:   ",".join(items)
来源：http://dali.svipenyu.cn/Article/details/gtcosknvsj.html

PHP:  implode(",", $items);
来源：http://dali.hnqzz.top/Article/details/gtitouvvsr.html

JS:   items.join(",")
来源：http://dali.meibo888.top/Article/details/gtocuhstxo.html

TS:   items.join(",")
来源：http://dali.hysaishi.cn/Article/details/gtpmsvrxal.html

Java: String.join(",", items)
来源：http://dali.yonumen.top/Article/details/gtxlzkxpfu.html

Go:   strings.Join(items, ",")
来源：http://dali.hywenlv.cn/Article/details/gtuurpftmw.html

Ruby: items.join(",")
来源：http://dali.fzhhl.top/Article/details/gtbxronxdb.html

C#:   string.Join(",", items)
来源：http://dali.sxryk.cn/Article/details/gtnxrfekim.html

[E09] 去除所有空白字符
来源：http://dali.fengsongda.top/Article/details/gtavlxeslc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yj202588.top/Article/details/gttcmhidxg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.andypj.xyz/Article/details/gtkozpvztr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jlsjyb.cn/Article/details/gtlrmnbioz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhoulong.xyz/Article/details/gtchkmmjek.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.daxiang520.top/Article/details/gtarkdhttm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfgfoxytk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.nanxuanxn.top/Article/details/gtnjhkxewa.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcxeacbai.html

[E10] 左侧补零 / 定长填充
来源：http://dali.nwbrower.top/Article/details/gtukdncrsb.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.mhx1999.top/Article/details/gtkufvdmif.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hnxiangtu.top/Article/details/gtyjqhgvjl.html

JS:   "7".padStart(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gtjkayfeml.html

TS:   "7".padStart(3, "0")
来源：http://dali.wangdashe.top/Article/details/gtgkjdetql.html

Java: String.format("%03d", 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnateaspy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gtqgejhhcf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gtezpcovby.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tanke756.top/Article/details/gtgpljcwad.html

[E11] 反转字符串
来源：http://dali.zhiwuduotai.top/Article/details/gthiujnbcx.html

Py:   s[::-1]
来源：http://dali.nanxuanxn.top/Article/details/gtmvlyosav.html

PHP:  strrev($s);
来源：http://dali.mhx1999.top/Article/details/gtcrrceuyr.html

JS:   [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gtfhkmwnjp.html

TS:   [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbnzksyfv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jqgfzy.top/Article/details/gtzywwxppx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jqgufenzy.top/Article/details/gtblvyfpiv.html

Ruby: s.reverse
来源：http://dali.ppjwa.cn/Article/details/gtrhemgmcw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.dianchejie.cn/Article/details/gtuaortuqx.html

[E12] 统计某字符出现次数
来源：http://dali.jinqigfzy.top/Article/details/gthpsqgbad.html

Py:   s.count("a")
来源：http://dali.hnxiangtu.top/Article/details/gtwwkbfoqo.html

PHP:  substr_count($s, "a");
来源：http://dali.jiagoushi.top/Article/details/gtpzbdqnil.html

JS:   s.split("a").length - 1
来源：http://dali.jiagoushi.top/Article/details/gtemwbnfzr.html

TS:   s.split("a").length - 1
来源：http://dali.xziqi.cn/Article/details/gtluiufoll.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jyoumei.cn/Article/details/gtprvnvyhi.html

Go:   strings.Count(s, "a")
来源：http://dali.yj20258888.top/Article/details/gtivtunmcs.html

Ruby: s.count("a")
来源：http://dali.sufxvd.cn/Article/details/gtytqvfvjt.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gogol.net.cn/Article/details/gteuuzowxn.html

[E13] 逐字符遍历
来源：http://dali.nanxuanxn.top/Article/details/gtdjietkcl.html

Py:   for ch in s: print(ch)
来源：http://dali.birdmap.top/Article/details/gthtjzcfez.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.nanxinkj.top/Article/details/gtlfupjnzk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gogol.net.cn/Article/details/gtqbwpaorl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gtelrnffdw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gtvziyzopk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhongyouzk.top/Article/details/gttlrmjshx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xinyue.icu/Article/details/gtgnfvpuwx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gtoecpuzjl.html

[E14] URL 编码与 Base64
来源：http://dali.jqgfzy.top/Article/details/gtvvrphsmi.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.nanxinkj.top/Article/details/gturzwwmhk.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xuanzx.com/Article/details/gtuwliepwc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xylfe.cn/Article/details/gtvlaksjvp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yuanzhike.top/Article/details/gtdzdiwnyf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.dianchejie.cn/Article/details/gtwlodvktf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shzxlz.cn/Article/details/gtzshidnqm.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cdnleiting.top/Article/details/gtnycbtwsi.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.pengpengdd.cyou/Article/details/gtzsljqdci.html

[E15] HTML 转义 / 反转义
来源：http://dali.ybcxt.top/Article/details/gtzvxasmia.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yuxming.cn/Article/details/gtsmwtlfgt.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hnqzz.top/Article/details/gtlpytpvmn.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.daria6918.cn/Article/details/gtaumivdyh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.tian-w.cn/Article/details/gtiedsilwa.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.tanke756.top/Article/details/gttwxvezuh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.meibo888.top/Article/details/gtwfszejxf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cqqwz.cn/Article/details/gtgfmzywgc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yueranfly.top/Article/details/gtdikfxzfs.html

[E16] 数字千分位
来源：http://dali.sufxvd.cn/Article/details/gtdzdibrki.html

Py:   f"{1234567:,}"
来源：http://dali.nanxinkj.top/Article/details/gtyuerlbkn.html

PHP:  number_format(1234567);
来源：http://dali.jianghu66.top/Article/details/gtvksrazcz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xinyue.icu/Article/details/gtrbapylwv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthkjxjrya.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cucudq.cn/Article/details/gtjhhzgmkl.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpfiwyzil.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sxryk.cn/Article/details/gtqjpuomzw.html

C#:   1234567.ToString("N0")
来源：http://dali.zhixingplan.top/Article/details/gtqvntxlku.html

[E17] 首字母大写
来源：http://dali.316326.xyz/Article/details/gtzwnvhplf.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yj20258888.top/Article/details/gteqdhmpwa.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.316326.xyz/Article/details/gtiaghhplx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfwnlwser.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.haohaochexian.top/Article/details/gtogzmyivn.html


<!-- 参考信息 -->