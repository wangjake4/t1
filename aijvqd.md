代发 wailian999

TS:   arr.slice(1, 4);
来源：http://dali.yvedp.cn/Article/details/gtuthnyvbm.html

Java: list.subList(1, 4);
来源：http://dali.svipenyu.cn/Article/details/gtjbljumvy.html

Go:   arr[1:4]
来源：http://dali.aizwys.cn/Article/details/gtgiyxevjp.html

Ruby: arr[1, 3]
来源：http://dali.fengsongda.top/Article/details/gtlucrcgsu.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinqigfzy.top/Article/details/gtdtdemplw.html

[D08] 合并两个数组
来源：http://dali.jiagoushi.top/Article/details/gtiqxozuls.html

Py:   a + b;  a.extend(b)
来源：http://dali.bjfxy.top/Article/details/gtzvnrykin.html

PHP:  array_merge($a, $b);
来源：http://dali.ybcxt.top/Article/details/gteccjqdoi.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yueranfly.top/Article/details/gtqsskxpxg.html

TS:   [...a, ...b];
来源：http://dali.jyoumei.cn/Article/details/gtjpzhvkqg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.vqdsnc.cn/Article/details/gttcpvxiei.html

Go:   append(a, b...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwgnvhurc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.birdmap.top/Article/details/gtgftpshui.html

C#:   a.Concat(b).ToList()
来源：http://dali.birdmap.top/Article/details/gtijumlaog.html

[D09] 排序（升序）
来源：http://dali.vqdsnc.cn/Article/details/gtkrimxjwa.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cdnleiting.top/Article/details/gtgutxtctj.html

PHP:  sort($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxsopidkh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cashguo.top/Article/details/gtwdiwohej.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shangyingyoupin.top/Article/details/gtocmrkiui.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.aizwys.cn/Article/details/gtlfwpjjay.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.sufxvd.cn/Article/details/gtqbgxuemm.html

Ruby: arr.sort
来源：http://dali.iojbl.cn/Article/details/gtrwuinlcf.html

C#:   list.Sort();
来源：http://dali.jqgfzy.top/Article/details/gtmeurgdmx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yonumen.top/Article/details/gtgqmskcde.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cqqwz.cn/Article/details/gtuzjyachj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj202588.top/Article/details/gtsolbfras.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yvedp.cn/Article/details/gtkozqrvmu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.feifeiyinyue.top/Article/details/gtoxqvjhua.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.redwolf501.top/Article/details/gtqehmjuvm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ppjwa.cn/Article/details/gtwpilylfs.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gogol.net.cn/Article/details/gtdmwflocv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.guowangkeji.top/Article/details/gtbblyrtrq.html

[D11] 反转数组
来源：http://dali.zhiwuduotai.top/Article/details/gtiknjbdlz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.quarkkingdee.top/Article/details/gtoelalcbe.html

PHP:  array_reverse($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnlqwetct.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yuanzhike.top/Article/details/gtddaqbuuw.html

TS:   [...arr].reverse();
来源：http://dali.hongshengwenyu.top/Article/details/gtckwnissf.html

Java: Collections.reverse(list);
来源：http://dali.sweek.top/Article/details/gtzmetegvq.html

Go:   slices.Reverse(arr)
来源：http://dali.dashuyun.cn/Article/details/gtshgzhyql.html

Ruby: arr.reverse
来源：http://dali.haohaochexian.top/Article/details/gtsavibokn.html

C#:   list.Reverse();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvtxzzvos.html

[D12] 查找元素下标
来源：http://dali.hammf.cn/Article/details/gtcccjgguc.html

Py:   arr.index(x);  x in arr
来源：http://dali.kuanghao11.cn/Article/details/gttmilpyha.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.iojbl.cn/Article/details/gtofikdvnn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtitascicl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.iojbl.cn/Article/details/gtwpsnxnfs.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhixingplan.top/Article/details/gtonqtzevo.html

Go:   slices.Index(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gtbolpxeba.html

Ruby: arr.index(x)
来源：http://dali.guowangkeji.top/Article/details/gtlxgnwvxb.html

C#:   list.IndexOf(x);
来源：http://dali.nanxinkj.top/Article/details/gtudtogyos.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhengqikj.top/Article/details/gtoykwojnq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yuxming.cn/Article/details/gtnxexhsnt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nwbrower.top/Article/details/gtyxjjqysa.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsdyfofot.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yonumen.top/Article/details/gtaeuzfdyk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.dashuyun.cn/Article/details/gtygwfoddw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj20258.top/Article/details/gtekurjqpg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.fzhhl.top/Article/details/gtnrscangk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yongpay.top/Article/details/gtubrjrsrn.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ybcxt.top/Article/details/gtxwjimrvj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.guannengcc.top/Article/details/gtfeayaszv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ehwqpu.com/Article/details/gtqzlydywj.html

JS:   arr.map(x => x * 2)
来源：http://dali.daxiang520.top/Article/details/gtegqypsxh.html

TS:   arr.map(x => x * 2)
来源：http://dali.jyoumei.cn/Article/details/gtsdyudytk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.snrcjt.cn/Article/details/gtzzdybwig.html

Go:   // 手写循环
来源：http://dali.shangyingyoupin.top/Article/details/gtljsjffsn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.chenzaomai.com/Article/details/gtasppxrcx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtuhlgjhqp.html

[D15] 去重
来源：http://dali.jinqigufen.top/Article/details/gtrluoijfz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhengqikj.top/Article/details/gtyeglvwyj.html

PHP:  array_unique($arr);
来源：http://dali.hammf.cn/Article/details/gtydqnvefb.html

JS:   [...new Set(arr)]
来源：http://dali.zdqjudy.top/Article/details/gtatltgilt.html

TS:   [...new Set(arr)]
来源：http://dali.svipenyu.cn/Article/details/gtnjcwvzog.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cheryme.top/Article/details/gtwtqshvsn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.bjfxy.top/Article/details/gtpiianmkf.html

Ruby: arr.uniq
来源：http://dali.c1oappe.top/Article/details/gtqowxbvsy.html

C#:   list.Distinct().ToList()
来源：http://dali.wangdashe.top/Article/details/gtzfuinlof.html

[D16] 求和与平均值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdcfonbyi.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtcjglwnyl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtcadyulgu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtihewprtt.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ehwqpu.com/Article/details/gtgkviryyz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.tianlin.xyz/Article/details/gtlctzozcu.html

Go:   // 手写循环累加
来源：http://dali.zhaomingkeji.xyz/Article/details/gtouxcnkmr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.pengpengdd.cyou/Article/details/gtolaikjzq.html

C#:   list.Sum();  list.Average()
来源：http://dali.nwbrower.top/Article/details/gtcyzwjifg.html

[D17] 最大值与最小值
来源：http://dali.shzxlz.cn/Article/details/gtcwonzzuf.html

Py:   max(arr);  min(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtphcbjknh.html

PHP:  max($arr);  min($arr);
来源：http://dali.birdmap.top/Article/details/gtkhdqoeaa.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.vqdsnc.cn/Article/details/gttolkknjv.html

TS:   Math.max(...arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmpduosjt.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jyoumei.cn/Article/details/gtqxtixvps.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.tianlin.xyz/Article/details/gtjmwyxawu.html

Ruby: arr.max;  arr.min
来源：http://dali.jinqigufen.top/Article/details/gtrbgglwop.html

C#:   list.Max();  list.Min()
来源：http://dali.sxryk.cn/Article/details/gtucyyzwxb.html

[D18] 扁平化嵌套数组
来源：http://dali.hnqzz.top/Article/details/gthmljrgfw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.kuanghao11.cn/Article/details/gtgfijjnvm.html

PHP:  array_merge(...$nested);
来源：http://dali.nanxinkj.top/Article/details/gtmvjougmj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xinyue.icu/Article/details/gtlrqyjvpx.html

TS:   nested.flat();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmrxltjvt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jqgufenzy.top/Article/details/gtlrksulgq.html

Go:   // 手写双层循环
来源：http://dali.feifeiyinyue.top/Article/details/gtogbgtuxc.html

Ruby: nested.flatten
来源：http://dali.hammf.cn/Article/details/gtiddsbamp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.iojbl.cn/Article/details/gtvhdvyogc.html

[D19] 按字段分组
来源：http://dali.zdqjudy.top/Article/details/gtecnjevrf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.chenlongwang.top/Article/details/gtklcsdrpr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yonumen.top/Article/details/gtdzbyhxau.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shanyushiyangtech.top/Article/details/gtiudnwkmz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.wangdashe.top/Article/details/gtwtwxlymz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.snrcjt.cn/Article/details/gtclaoelfk.html

Go:   // 手写 map[string][]T
来源：http://dali.316326.xyz/Article/details/gtiksgazty.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gotoacloud.top/Article/details/gttlbdljit.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xziqi.cn/Article/details/gtvghnzpkh.html

[D20] 统计每个元素出现次数
来源：http://dali.jqgfzy.top/Article/details/gtynogrnju.html

Py:   Counter(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gttkzqupyq.html

PHP:  array_count_values($arr);
来源：http://dali.haohaochexian.top/Article/details/gtzmxuzlfr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuanzhike.top/Article/details/gtxtsncbqw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guowangkeji.top/Article/details/gtgoqwpohd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yuanzhike.top/Article/details/gtujukzeix.html

Go:   // 手写 map[T]int
来源：http://dali.fzhhl.top/Article/details/gtmntvaolv.html

Ruby: arr.tally
来源：http://dali.aibaodan.cn/Article/details/gtkaflbhwd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xuetiantiany.cn/Article/details/gtzdmtmngf.html

[D21] 判断是否包含某元素
来源：http://dali.zhoulong.xyz/Article/details/gtjgezxkqf.html

Py:   x in arr
来源：http://dali.jinqigfzy.top/Article/details/gtypfvkwlz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.9152youxi.cn/Article/details/gtnxjcfrus.html

JS:   arr.includes(x)
来源：http://dali.shuidangran.top/Article/details/gtrzqfkvrf.html

TS:   arr.includes(x)
来源：http://dali.daxiang520.top/Article/details/gtkwosnpgm.html

Java: list.contains(x)
来源：http://dali.cashguo.top/Article/details/gthiwalxlo.html

Go:   slices.Contains(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtquqbgybn.html

Ruby: arr.include?(x)
来源：http://dali.jinqigufen.top/Article/details/gtuxvonocy.html

C#:   list.Contains(x)
来源：http://dali.tianlin.xyz/Article/details/gtyixehoal.html

[D22] 复制数组（避免共享引用）
来源：http://dali.wangdashe.top/Article/details/gtawcbspsw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtzpytrdnr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.dashuyun.cn/Article/details/gtgfvriqda.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.dashuyun.cn/Article/details/gtwgizbcfe.html

TS:   [...arr];
来源：http://dali.yj20258.top/Article/details/gtwenerdbk.html

Java: new ArrayList<>(list);
来源：http://dali.hongshengwenyu.top/Article/details/gtehpfdcvf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.fengsongda.top/Article/details/gtginskicj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.snrcjt.cn/Article/details/gtbjsfxdyt.html

C#:   new List<int>(list);
来源：http://dali.nanxinkj.top/Article/details/gtjwlvqhos.html

[D23] reduce 累积计算
来源：http://dali.gzhubu.top/Article/details/gtgpqgtsjo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.haohaochexian.top/Article/details/gtzhuqpoci.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.9152youxi.cn/Article/details/gtbzggajzy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtzmzyglnb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aizwys.cn/Article/details/gtblbdntqj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.dashuyun.cn/Article/details/gtcocgfirn.html

Go:   // 手写循环
来源：http://dali.jyoumei.cn/Article/details/gtbzpcscpe.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.nanxinkj.top/Article/details/gtgdlzbglg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.aizwys.cn/Article/details/gtzieqqmow.html

[D24] 字典 / Map 基本操作
来源：http://dali.chenlongwang.top/Article/details/gteoutctmi.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.iojbl.cn/Article/details/gtlyslaskb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gotoacloud.top/Article/details/gtbfirbuom.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hnqzz.top/Article/details/gtjleijcjh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.mhx1999.top/Article/details/gtaijlqagr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sufxvd.cn/Article/details/gtjzzryrym.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sweek.top/Article/details/gtpgrvchlv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.daxiang520.top/Article/details/gtunqcsqpx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.snrcjt.cn/Article/details/gtlpugxzna.html

[D25] Set 集合去重与交并差
来源：http://dali.yuanzhike.top/Article/details/gtgmhehvnx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hongshengwenyu.top/Article/details/gtjeelverb.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cqqwz.cn/Article/details/gtbdaplrra.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.9152youxi.cn/Article/details/gtpnmifqee.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.c1oappe.top/Article/details/gtfsukqhno.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cheryme.top/Article/details/gtvzaqiyog.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ehwqpu.com/Article/details/gtlsiwyytq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yongpay.top/Article/details/gtokkuudla.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gogol.net.cn/Article/details/gtwmnuqdqb.html

[D26] 数组转字符串
来源：http://dali.aibaodan.cn/Article/details/gtkhhakrot.html

Py:   ", ".join(map(str, arr))
来源：http://dali.chenlongwang.top/Article/details/gtxwlwrypw.html

PHP:  implode(", ", $arr);
来源：http://dali.yj20258888.top/Article/details/gtisnvkgnn.html

JS:   arr.join(", ")
来源：http://dali.ehwqpu.com/Article/details/gtxapdeezf.html

TS:   arr.join(", ")
来源：http://dali.smart0.xyz/Article/details/gtljwwcvpb.html

Java: String.join(", ", list)
来源：http://dali.yonumen.top/Article/details/gtgbemfixh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.aibaodan.cn/Article/details/gtjlpqfmzt.html

Ruby: arr.join(", ")
来源：http://dali.nanxuanxn.top/Article/details/gtuawwgeyr.html

C#:   string.Join(", ", list)
来源：http://dali.zhengqikj.top/Article/details/gtsvdtdqtv.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtrfhzwejq.html

E. 字符串处理
来源：http://dali.zhengqikj.top/Article/details/gtpbemandq.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtjwofjalk.html

[E01] 拼接字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtdqwyhbcy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yj202588.top/Article/details/gteihttdha.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.vqdsnc.cn/Article/details/gtphudzort.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhongyouzk.top/Article/details/gtqvtoxxek.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nwbrower.top/Article/details/gtgpvunfvb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shangyingyoupin.top/Article/details/gtwhdganrr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sysykeji.top/Article/details/gtitblzclw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ybcxt.top/Article/details/gtigbpuujm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtjibrhyjg.html

[E02] 重复字符串
来源：http://dali.bjfxy.top/Article/details/gtpzastumg.html

Py:   "ab" * 3
来源：http://dali.cashguo.top/Article/details/gtvubzaipv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtomdyeoiy.html

JS:   "ab".repeat(3)
来源：http://dali.9152youxi.cn/Article/details/gtyyddniyh.html

TS:   "ab".repeat(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtarcwyfsd.html

Java: "ab".repeat(3)
来源：http://dali.jqgufenzy.top/Article/details/gtmrylkohh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sysykeji.top/Article/details/gtmivijpbd.html

Ruby: "ab" * 3
来源：http://dali.gzhubu.top/Article/details/gtzdkmdzrn.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shangyingyoupin.top/Article/details/gtvtakihqd.html

[E03] 截取子串
来源：http://dali.zhoulong.xyz/Article/details/gtlgyptkai.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hammf.cn/Article/details/gtpuebamya.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gtwhzsykew.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cucudq.cn/Article/details/gtzldqipnm.html

TS:   s.slice(1, 4)
来源：http://dali.pycfn.com/Article/details/gtztcoeetn.html

Java: s.substring(1, 4)
来源：http://dali.yj20258888.top/Article/details/gtrbmyddnh.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sxryk.cn/Article/details/gtgcgtljsp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xuanzx.com/Article/details/gtltqlgmxh.html

C#:   s.Substring(1, 3)
来源：http://dali.wangdashe.top/Article/details/gtuheifskw.html

[E04] 查找子串位置
来源：http://dali.yanxiufei.cn/Article/details/gthwzxsfll.html

Py:   s.find("x");  s.index("x")
来源：http://dali.tian-w.cn/Article/details/gtugoriluj.html

PHP:  strpos($s, "x");
来源：http://dali.daxiang520.top/Article/details/gtozwodvpg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.wangdashe.top/Article/details/gtnpxavfwx.html

TS:   s.indexOf("x")
来源：http://dali.sweek.top/Article/details/gtdcxbkjfs.html

Java: s.indexOf("x")
来源：http://dali.smart0.xyz/Article/details/gtadwspsnz.html

Go:   strings.Index(s, "x")
来源：http://dali.cqqwz.cn/Article/details/gtluklmalm.html

Ruby: s.index("x")
来源：http://dali.svipenyu.cn/Article/details/gtwokyfqst.html

C#:   s.IndexOf("x")
来源：http://dali.ybcxt.top/Article/details/gtmnsjerwj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.guannengcc.top/Article/details/gtrkcxscms.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.316326.xyz/Article/details/gtntdsmfet.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xylfe.cn/Article/details/gtnterleik.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zdqjudy.top/Article/details/gtyxqnkoin.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gotoacloud.top/Article/details/gtpptxzgqk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yvedp.cn/Article/details/gtemgqtaqd.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xylfe.cn/Article/details/gtotrccews.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yuanzhike.top/Article/details/gtouqalinb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhiwuduotai.top/Article/details/gtigjzvsag.html

[E06] 替换子串
来源：http://dali.haohaochexian.top/Article/details/gtezsqosqr.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ehwqpu.com/Article/details/gtozpcpilq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zycfv.cn/Article/details/gtobonsgyb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtcczdtllh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtbmajexgw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gtxalgmmyl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yanxiufei.cn/Article/details/gtcctwhfwe.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtvvmiomzm.html

C#:   s.Replace("a", "b")
来源：http://dali.tanke756.top/Article/details/gthumtvyrt.html

[E07] 按分隔符拆分
来源：http://dali.ydzc1.top/Article/details/gtxmlvkpjj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yonumen.top/Article/details/gttpoqzwda.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.dashuyun.cn/Article/details/gtfqygqoik.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.snrcjt.cn/Article/details/gttoiffnpg.html

TS:   s.split(",")
来源：http://dali.svipenyu.cn/Article/details/gtgutvbijl.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.vqdsnc.cn/Article/details/gtaxglyzpt.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xuanzx.com/Article/details/gtgmjuuiha.html

Ruby: s.split(",");  s.split
来源：http://dali.cheryme.top/Article/details/gtfacdtdac.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgfpmrzrp.html

[E08] 数组按分隔符合并
来源：http://dali.shzxlz.cn/Article/details/gtxgpxqayz.html

Py:   ",".join(items)
来源：http://dali.jinqigfzy.top/Article/details/gtfrntkmrs.html

PHP:  implode(",", $items);
来源：http://dali.zdqjudy.top/Article/details/gtdernbrym.html

JS:   items.join(",")
来源：http://dali.hysaishi.cn/Article/details/gtfpuchrgz.html

TS:   items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gtpdoklklv.html

Java: String.join(",", items)
来源：http://dali.jiagoushi.top/Article/details/gtieaksnco.html

Go:   strings.Join(items, ",")
来源：http://dali.yueranfly.top/Article/details/gtkjnuchrh.html

Ruby: items.join(",")
来源：http://dali.yongpay.top/Article/details/gtngfkzbbp.html

C#:   string.Join(",", items)
来源：http://dali.hysaishi.cn/Article/details/gtyodwlhca.html

[E09] 去除所有空白字符
来源：http://dali.hongshengwenyu.top/Article/details/gtquiaazpe.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ivvv.top/Article/details/gtqowceulb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yonumen.top/Article/details/gtcyxeznxy.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hysaishi.cn/Article/details/gtmltdbudl.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gotoacloud.top/Article/details/gtasqlexrf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xuanzx.com/Article/details/gtpalydquj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sufxvd.cn/Article/details/gtvedqqfdu.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinqigufen.top/Article/details/gtdvgvzbtg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.316326.xyz/Article/details/gtjzuobrkl.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinqigfzy.top/Article/details/gtldoktkme.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gthkdhxeso.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shangyingyoupin.top/Article/details/gtebcbstja.html

JS:   "7".padStart(3, "0")
来源：http://dali.jianghu66.top/Article/details/gtqjpeyxib.html

TS:   "7".padStart(3, "0")
来源：http://dali.sweek.top/Article/details/gtmrudcnko.html

Java: String.format("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gtcyiylhxi.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ivvv.top/Article/details/gtvqmiiwzi.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.wangshuangyany.cn/Article/details/gtaewerume.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ppjwa.cn/Article/details/gtqndwimje.html

[E11] 反转字符串
来源：http://dali.pycfn.com/Article/details/gtfsbtfgpd.html

Py:   s[::-1]
来源：http://dali.zhoulong.xyz/Article/details/gtqdnazyhs.html

PHP:  strrev($s);
来源：http://dali.zhongyouzk.top/Article/details/gtegjdggud.html

JS:   [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gtiznztmyc.html

TS:   [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gtwfewwacv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.0kj1m.cn/Article/details/gttetpizjg.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.iojbl.cn/Article/details/gtyhnwlrcd.html

Ruby: s.reverse
来源：http://dali.ybcxt.top/Article/details/gtzwbdvyyk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jlsjyb.cn/Article/details/gtxmkptglo.html

[E12] 统计某字符出现次数
来源：http://dali.sysykeji.top/Article/details/gtemkgfwmd.html

Py:   s.count("a")
来源：http://dali.iojbl.cn/Article/details/gtqbpxahog.html

PHP:  substr_count($s, "a");
来源：http://dali.snrcjt.cn/Article/details/gtfxlclltp.html

JS:   s.split("a").length - 1
来源：http://dali.quarkkingdee.top/Article/details/gtrkocynas.html

TS:   s.split("a").length - 1
来源：http://dali.kuanghao11.cn/Article/details/gtfoqlgdee.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.fzhhl.top/Article/details/gtghmqodmi.html

Go:   strings.Count(s, "a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfpsgnyuo.html

Ruby: s.count("a")
来源：http://dali.jianghu66.top/Article/details/gtslhzclwb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.c1oappe.top/Article/details/gtnvfkaogb.html

[E13] 逐字符遍历
来源：http://dali.yj20258.top/Article/details/gtaxbemrex.html

Py:   for ch in s: print(ch)
来源：http://dali.gogol.net.cn/Article/details/gtwefyrlcb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xylfe.cn/Article/details/gtvngyxgge.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gtymebbitq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgfzy.top/Article/details/gtsoatbtdk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.smart0.xyz/Article/details/gtklfbkqtm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hysaishi.cn/Article/details/gtsarokjtw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.guowangkeji.top/Article/details/gtrsbuwseg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yonumen.top/Article/details/gtiogaxtcy.html

[E14] URL 编码与 Base64
来源：http://dali.bjfxy.top/Article/details/gttbksjjhx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gzhubu.top/Article/details/gtxlqaspli.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.iojbl.cn/Article/details/gtnrskygmr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hnqzz.top/Article/details/gtkjnkpvvl.html


<!-- 参考信息 -->