代发 wailian999

TS:   arr.slice(1, 4);
来源：http://dali.ppjwa.cn/Article/details/gthtqpbbqy.html

Java: list.subList(1, 4);
来源：http://dali.sysykeji.top/Article/details/gtlxqaliby.html

Go:   arr[1:4]
来源：http://dali.xinyue.icu/Article/details/gtbjptdpcp.html

Ruby: arr[1, 3]
来源：http://dali.gaohongyu789.top/Article/details/gthtcwmykq.html

C#:   list.GetRange(1, 3);
来源：http://dali.sweek.top/Article/details/gtcwbvtikm.html

[D08] 合并两个数组
来源：http://dali.cdnleiting.top/Article/details/gtafuusxnv.html

Py:   a + b;  a.extend(b)
来源：http://dali.wangshuangyany.cn/Article/details/gtnzlwnish.html

PHP:  array_merge($a, $b);
来源：http://dali.fengsongda.top/Article/details/gtsijqcqhf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.snrcjt.cn/Article/details/gtjkepzlgu.html

TS:   [...a, ...b];
来源：http://dali.zhongyouzk.top/Article/details/gtokuggaiw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvnjnlpxh.html

Go:   append(a, b...)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuhfdvuzq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.guannengcc.top/Article/details/gtfeblqkbr.html

C#:   a.Concat(b).ToList()
来源：http://dali.jqgfzy.top/Article/details/gteyyuybqc.html

[D09] 排序（升序）
来源：http://dali.jqgufenzy.top/Article/details/gtpogxbxcc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yangfankeji.com/Article/details/gtkimqcdso.html

PHP:  sort($arr);
来源：http://dali.cdnleiting.top/Article/details/gtugzaelhj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xinyue.icu/Article/details/gtpmxjislt.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gzhubu.top/Article/details/gtymvujbsl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cqqwz.cn/Article/details/gtctjryums.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hammf.cn/Article/details/gtrejtxnud.html

Ruby: arr.sort
来源：http://dali.zhoulong.xyz/Article/details/gthtrnywhx.html

C#:   list.Sort();
来源：http://dali.zhongyouzk.top/Article/details/gtqlgfynjk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzackwkgk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.havefunace.top/Article/details/gtyeowgknn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hfpthk.cn/Article/details/gtjqldbmnz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hammf.cn/Article/details/gteemlneqe.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jiagoushi.top/Article/details/gtdgkfzwtw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.aibaodan.cn/Article/details/gteciromgf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zdqjudy.top/Article/details/gtqarubqus.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hnxiangtu.top/Article/details/gtzcttjpru.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.daxiang520.top/Article/details/gtajstliza.html

[D11] 反转数组
来源：http://dali.xinyue.icu/Article/details/gtztbpxiau.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhongyouzk.top/Article/details/gtgxmkotfg.html

PHP:  array_reverse($arr);
来源：http://dali.hywenlv.cn/Article/details/gtevxoueht.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gogol.net.cn/Article/details/gtljsuoevx.html

TS:   [...arr].reverse();
来源：http://dali.yuxming.cn/Article/details/gtxeedvlpw.html

Java: Collections.reverse(list);
来源：http://dali.aibaodan.cn/Article/details/gtpafgizjs.html

Go:   slices.Reverse(arr)
来源：http://dali.pycfn.com/Article/details/gtassnnotq.html

Ruby: arr.reverse
来源：http://dali.ppjwa.cn/Article/details/gteoerthsb.html

C#:   list.Reverse();
来源：http://dali.zhiwuduotai.top/Article/details/gtwawnisof.html

[D12] 查找元素下标
来源：http://dali.hnqzz.top/Article/details/gtjkurxnko.html

Py:   arr.index(x);  x in arr
来源：http://dali.xylfe.cn/Article/details/gttkvmpdop.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwulajrpe.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zycfv.cn/Article/details/gtxcharzpr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dashuyun.cn/Article/details/gtsmrjpnus.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.chenlongwang.top/Article/details/gthyzyzobc.html

Go:   slices.Index(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gttwazrnre.html

Ruby: arr.index(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmqsmtjxq.html

C#:   list.IndexOf(x);
来源：http://dali.zdqjudy.top/Article/details/gtgdhaizop.html

[D13] 过滤（保留满足条件的）
来源：http://dali.fengsongda.top/Article/details/gtvcuvtdki.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhoulong.xyz/Article/details/gtfcscyolu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nwbrower.top/Article/details/gtlaaygrgw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sysykeji.top/Article/details/gtpyxtifxo.html

TS:   arr.filter(x => x > 3)
来源：http://dali.316326.xyz/Article/details/gtuhjyridq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.9152youxi.cn/Article/details/gthgifxpuk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.0kj1m.cn/Article/details/gtkbobtybd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nwbrower.top/Article/details/gtzeicvvid.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtrebdyxov.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj20258.top/Article/details/gtguckyohx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jiagoushi.top/Article/details/gtkkavukci.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.gotoacloud.top/Article/details/gtanoeuwri.html

JS:   arr.map(x => x * 2)
来源：http://dali.iojbl.cn/Article/details/gtplrpyxmf.html

TS:   arr.map(x => x * 2)
来源：http://dali.yj20258888.top/Article/details/gtyflrihij.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sysykeji.top/Article/details/gtrdgwmtwt.html

Go:   // 手写循环
来源：http://dali.c1oappe.top/Article/details/gtrayetdzh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hfpthk.cn/Article/details/gtvuypsfop.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.smart0.xyz/Article/details/gttrrefysp.html

[D15] 去重
来源：http://dali.ybcxt.top/Article/details/gtchwbceft.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.iojbl.cn/Article/details/gtxkibcgul.html

PHP:  array_unique($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtxrtkikjc.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gtqndcasmv.html

TS:   [...new Set(arr)]
来源：http://dali.daria6918.cn/Article/details/gtwlcfavwq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cheryme.top/Article/details/gthluzhgul.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinqigufen.top/Article/details/gtwwwaefyf.html

Ruby: arr.uniq
来源：http://dali.hongshengwenyu.top/Article/details/gtnjdtsrrj.html

C#:   list.Distinct().ToList()
来源：http://dali.zdqjudy.top/Article/details/gtjdddebia.html

[D16] 求和与平均值
来源：http://dali.jqgufenzy.top/Article/details/gtrnipmsfs.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ydzc1.top/Article/details/gtupkxwbxq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtahoesavo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tian-w.cn/Article/details/gtwzgckxef.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtdmmraqfn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.aibaodan.cn/Article/details/gtrvdpnsgu.html

Go:   // 手写循环累加
来源：http://dali.zycfv.cn/Article/details/gtilcfrnhb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shangyingyoupin.top/Article/details/gtbqgmbwcm.html

C#:   list.Sum();  list.Average()
来源：http://dali.tianlin.xyz/Article/details/gtpgvvbvqg.html

[D17] 最大值与最小值
来源：http://dali.ybcxt.top/Article/details/gtsrdfdyon.html

Py:   max(arr);  min(arr)
来源：http://dali.ehwqpu.com/Article/details/gttxqejdiz.html

PHP:  max($arr);  min($arr);
来源：http://dali.jianghu66.top/Article/details/gtoedmklkt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ehwqpu.com/Article/details/gtkolljens.html

TS:   Math.max(...arr);
来源：http://dali.cheryme.top/Article/details/gtcssygwgc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.0kj1m.cn/Article/details/gtlrwoifup.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtuqferfgz.html

Ruby: arr.max;  arr.min
来源：http://dali.xylfe.cn/Article/details/gtjjwwebvm.html

C#:   list.Max();  list.Min()
来源：http://dali.zycfv.cn/Article/details/gtsrrxbpui.html

[D18] 扁平化嵌套数组
来源：http://dali.nanxinkj.top/Article/details/gtlkidsbdc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cucudq.cn/Article/details/gtrogihmsn.html

PHP:  array_merge(...$nested);
来源：http://dali.xylfe.cn/Article/details/gtykdqneon.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinqigfzy.top/Article/details/gtajhrhiny.html

TS:   nested.flat();
来源：http://dali.daxiang520.top/Article/details/gtsxynvkja.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhixingplan.top/Article/details/gtshfxmowx.html

Go:   // 手写双层循环
来源：http://dali.haohaochexian.top/Article/details/gtsaisfykb.html

Ruby: nested.flatten
来源：http://dali.kuanghao11.cn/Article/details/gtdqxryygd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cucudq.cn/Article/details/gtryhorois.html

[D19] 按字段分组
来源：http://dali.aibaodan.cn/Article/details/gtbbdmylvl.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.0kj1m.cn/Article/details/gtlipvwbcl.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xziqi.cn/Article/details/gtzfhmyyhb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hammf.cn/Article/details/gtokrfzwcz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xuanzx.com/Article/details/gtcagztevu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.iojbl.cn/Article/details/gtwdoutlud.html

Go:   // 手写 map[string][]T
来源：http://dali.aibaodan.cn/Article/details/gtlwcalayb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hongshengwenyu.top/Article/details/gtxajodupe.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.smart0.xyz/Article/details/gtudflwrbs.html

[D20] 统计每个元素出现次数
来源：http://dali.fengsongda.top/Article/details/gtplsichfu.html

Py:   Counter(arr)
来源：http://dali.meibo888.top/Article/details/gtkxazwqlt.html

PHP:  array_count_values($arr);
来源：http://dali.yangfankeji.com/Article/details/gtjijxnyli.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guowangkeji.top/Article/details/gtztphcpwd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhoulong.xyz/Article/details/gtirpgcyxs.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cashguo.top/Article/details/gteelyotup.html

Go:   // 手写 map[T]int
来源：http://dali.feifeiyinyue.top/Article/details/gtxgondvee.html

Ruby: arr.tally
来源：http://dali.yj20258.top/Article/details/gthhdocqpk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhixingplan.top/Article/details/gtsqyfywwh.html

[D21] 判断是否包含某元素
来源：http://dali.jinqigfzy.top/Article/details/gtpizwmmbb.html

Py:   x in arr
来源：http://dali.daxiang520.top/Article/details/gtueuzcrei.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hysaishi.cn/Article/details/gtysgrpkdz.html

JS:   arr.includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gtjumwhvxd.html

TS:   arr.includes(x)
来源：http://dali.iojbl.cn/Article/details/gthmdqores.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gtmshdotyz.html

Go:   slices.Contains(arr, x)
来源：http://dali.sweek.top/Article/details/gtmlcsdala.html

Ruby: arr.include?(x)
来源：http://dali.yj202588.top/Article/details/gtnvnyzzmf.html

C#:   list.Contains(x)
来源：http://dali.c1oappe.top/Article/details/gtumakbffr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cashguo.top/Article/details/gtajyxoxxj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yangfankeji.com/Article/details/gtpmqjozgh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hnxiangtu.top/Article/details/gtejagdeje.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtliqtyjev.html

TS:   [...arr];
来源：http://dali.xuanzx.com/Article/details/gtjkkanmdz.html

Java: new ArrayList<>(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gtthzujbwn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.svipenyu.cn/Article/details/gteyelcxvn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhongyouzk.top/Article/details/gtgiyomqgd.html

C#:   new List<int>(list);
来源：http://dali.kuanghao11.cn/Article/details/gtwynusevf.html

[D23] reduce 累积计算
来源：http://dali.aizwys.cn/Article/details/gtichawgpf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sweek.top/Article/details/gtzwoooahe.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.andypj.xyz/Article/details/gtfceymcwi.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shuidangran.top/Article/details/gtgxthaztm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daria6918.cn/Article/details/gtteiutpda.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinghuilouyu.cn/Article/details/gtprgwuylp.html

Go:   // 手写循环
来源：http://dali.cqqwz.cn/Article/details/gthzliouku.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xuanzx.com/Article/details/gtcxutjaqm.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.wangdashe.top/Article/details/gtjlyztsxe.html

[D24] 字典 / Map 基本操作
来源：http://dali.chenlongwang.top/Article/details/gtdxfawtbf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.smart0.xyz/Article/details/gtkhtirrxx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sysykeji.top/Article/details/gtvvadshcu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xziqi.cn/Article/details/gtehwahduj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.daxiang520.top/Article/details/gtqrmiipio.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.pengpengdd.cyou/Article/details/gthtnxwuga.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.svipenyu.cn/Article/details/gtqhobltel.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jiagoushi.top/Article/details/gtpzbliikw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gaohongyu789.top/Article/details/gtpkaqrifc.html

[D25] Set 集合去重与交并差
来源：http://dali.ydzc1.top/Article/details/gtnbauvfkw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hongshengwenyu.top/Article/details/gtxqocmlga.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhongyouzk.top/Article/details/gtvgxrbupz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ppjwa.cn/Article/details/gtyypnhzvo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hammf.cn/Article/details/gtsdbxfmoy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tianlin.xyz/Article/details/gtiictgklk.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yj20258888.top/Article/details/gtbecpsojw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.316326.xyz/Article/details/gtkuiajfpq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gotoacloud.top/Article/details/gtfbjqzxgm.html

[D26] 数组转字符串
来源：http://dali.daxiang520.top/Article/details/gthiahhvfm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.vqdsnc.cn/Article/details/gtbtxzxvuv.html

PHP:  implode(", ", $arr);
来源：http://dali.shzxlz.cn/Article/details/gtrbqjyzeg.html

JS:   arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gtxpnsuzqt.html

TS:   arr.join(", ")
来源：http://dali.cheryme.top/Article/details/gtbfrqgwbe.html

Java: String.join(", ", list)
来源：http://dali.ybcxt.top/Article/details/gttvkzkmhb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gtzxafcenc.html

Ruby: arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gtjswrypwn.html

C#:   string.Join(", ", list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmnsmtqyw.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtnggzakci.html

E. 字符串处理
来源：http://dali.wangshuangyany.cn/Article/details/gtkhaiyidu.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gttiivnntw.html

[E01] 拼接字符串
来源：http://dali.hnqzz.top/Article/details/gtefehviwj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hongshengwenyu.top/Article/details/gtyfyotguo.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ehwqpu.com/Article/details/gtmeiwceas.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sweek.top/Article/details/gtlpvwsbhi.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhiwuduotai.top/Article/details/gthfgfnyxi.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinqigufen.top/Article/details/gtfruxlvkn.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.birdmap.top/Article/details/gtsgutflyg.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.daxiang520.top/Article/details/gtcvykueqe.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gtzrpythab.html

[E02] 重复字符串
来源：http://dali.yongpay.top/Article/details/gtalibzlna.html

Py:   "ab" * 3
来源：http://dali.nanxuanxn.top/Article/details/gtmfpqpfsd.html

PHP:  str_repeat("ab", 3);
来源：http://dali.c1oappe.top/Article/details/gtlhcwtbcg.html

JS:   "ab".repeat(3)
来源：http://dali.iojbl.cn/Article/details/gtqkvbfjur.html

TS:   "ab".repeat(3)
来源：http://dali.pycfn.com/Article/details/gtyggzccyf.html

Java: "ab".repeat(3)
来源：http://dali.snrcjt.cn/Article/details/gtfqahomhg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.svipenyu.cn/Article/details/gthxwoiciy.html

Ruby: "ab" * 3
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzjmnhobm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinqigufen.top/Article/details/gtegsokiyi.html

[E03] 截取子串
来源：http://dali.ydzc1.top/Article/details/gthvcgiinf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shzxlz.cn/Article/details/gtduqvtgfy.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gtuyscailk.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gtovnfvamo.html

TS:   s.slice(1, 4)
来源：http://dali.pycfn.com/Article/details/gtcafphzya.html

Java: s.substring(1, 4)
来源：http://dali.yongpay.top/Article/details/gthqcksgxy.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.havefunace.top/Article/details/gtzjawbsjr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sufxvd.cn/Article/details/gtiicxwzxo.html

C#:   s.Substring(1, 3)
来源：http://dali.zycfv.cn/Article/details/gtykbdkylx.html

[E04] 查找子串位置
来源：http://dali.yj20258.top/Article/details/gtcvhtlfbr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jianghu66.top/Article/details/gtzmgrgnbb.html

PHP:  strpos($s, "x");
来源：http://dali.havefunace.top/Article/details/gtzpagjsdv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.316326.xyz/Article/details/gtrglqzfib.html

TS:   s.indexOf("x")
来源：http://dali.mhx1999.top/Article/details/gtmvwlyuns.html

Java: s.indexOf("x")
来源：http://dali.xuanzx.com/Article/details/gtqevklbwe.html

Go:   strings.Index(s, "x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtisggyjbp.html

Ruby: s.index("x")
来源：http://dali.aizwys.cn/Article/details/gtfrlhmrse.html

C#:   s.IndexOf("x")
来源：http://dali.ppjwa.cn/Article/details/gtnjtvbqdz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yj202588.top/Article/details/gtvduuypcz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gtoxqcvwzi.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cashguo.top/Article/details/gtfxilvzen.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gogol.net.cn/Article/details/gtzxmbgcrz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cdnleiting.top/Article/details/gtgoejuncq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.vqdsnc.cn/Article/details/gtynciddns.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hammf.cn/Article/details/gthgpldwmv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cqqwz.cn/Article/details/gtepfibpwz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hongshengwenyu.top/Article/details/gthmyvnbif.html

[E06] 替换子串
来源：http://dali.yuanzhike.top/Article/details/gtdsltyusk.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.kuanghao11.cn/Article/details/gtmscomquq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.daria6918.cn/Article/details/gtqrdeomyl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiqhrjkpc.html

TS:   s.replaceAll("a", "b")
来源：http://dali.redwolf501.top/Article/details/gtdveaecso.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtxyxxqzzv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.kuanghao11.cn/Article/details/gtozcfhtho.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtkejiseou.html

C#:   s.Replace("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtybmvtsya.html

[E07] 按分隔符拆分
来源：http://dali.iojbl.cn/Article/details/gtvxfgoebn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.pengpengdd.cyou/Article/details/gtspxzvjcj.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xuanzx.com/Article/details/gtvefojgma.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhiwuduotai.top/Article/details/gtzmauvdpv.html

TS:   s.split(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlrrvtlpx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ehwqpu.com/Article/details/gtvkreldmd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jiagoushi.top/Article/details/gtudpndaxq.html

Ruby: s.split(",");  s.split
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfeeewjwj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xinyue.icu/Article/details/gtpobuevax.html

[E08] 数组按分隔符合并
来源：http://dali.yuanzhike.top/Article/details/gtbcdrbxkq.html

Py:   ",".join(items)
来源：http://dali.hywenlv.cn/Article/details/gtozhaiyku.html

PHP:  implode(",", $items);
来源：http://dali.kuanghao11.cn/Article/details/gtefpnhkhc.html

JS:   items.join(",")
来源：http://dali.hnxiangtu.top/Article/details/gtuktfaopj.html

TS:   items.join(",")
来源：http://dali.gzhubu.top/Article/details/gtpofeabbv.html

Java: String.join(",", items)
来源：http://dali.wangdashe.top/Article/details/gtafhnnhnv.html

Go:   strings.Join(items, ",")
来源：http://dali.cdnleiting.top/Article/details/gtzmqjsmsp.html

Ruby: items.join(",")
来源：http://dali.yj202588.top/Article/details/gthegtgpeg.html

C#:   string.Join(",", items)
来源：http://dali.snrcjt.cn/Article/details/gtdlyofcfy.html

[E09] 去除所有空白字符
来源：http://dali.kuanghao11.cn/Article/details/gtnfdmcajn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yuxming.cn/Article/details/gtuequdbrx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cdnleiting.top/Article/details/gtiokdsikj.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.nanxinkj.top/Article/details/gtbgccklth.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shangyingyoupin.top/Article/details/gtvlsqfllm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqkpasqbb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ybcxt.top/Article/details/gtlxyspfkn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hnqzz.top/Article/details/gtpkuxvose.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jyoumei.cn/Article/details/gtkfbdrqwv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.aibaodan.cn/Article/details/gtxrxgpobg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gtksneiels.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhengqikj.top/Article/details/gtyghqtgix.html

JS:   "7".padStart(3, "0")
来源：http://dali.jianghu66.top/Article/details/gtermiqxgz.html

TS:   "7".padStart(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gtyzkkvqfj.html

Java: String.format("%03d", 7)
来源：http://dali.snrcjt.cn/Article/details/gtldcvmiof.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gtjfgqevna.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xziqi.cn/Article/details/gtaxezyuxd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.guannengcc.top/Article/details/gtnorectyq.html

[E11] 反转字符串
来源：http://dali.gogol.net.cn/Article/details/gtbzzrcqmr.html

Py:   s[::-1]
来源：http://dali.tianlin.xyz/Article/details/gtvfzmzqqt.html

PHP:  strrev($s);
来源：http://dali.fengsongda.top/Article/details/gtidbiynql.html

JS:   [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gtoxfvxagj.html

TS:   [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gtdjelokcq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.wangshuangyany.cn/Article/details/gtiidzomto.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.andypj.xyz/Article/details/gtmiporwps.html

Ruby: s.reverse
来源：http://dali.jyoumei.cn/Article/details/gtgdmdjqxz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.chenjidiqi.icu/Article/details/gtylbeyihh.html

[E12] 统计某字符出现次数
来源：http://dali.aizwys.cn/Article/details/gtgnmgrqla.html

Py:   s.count("a")
来源：http://dali.haohaochexian.top/Article/details/gtvwwxymmx.html

PHP:  substr_count($s, "a");
来源：http://dali.gogol.net.cn/Article/details/gtmplfzhzp.html

JS:   s.split("a").length - 1
来源：http://dali.hywenlv.cn/Article/details/gtuztwfcjj.html

TS:   s.split("a").length - 1
来源：http://dali.cashguo.top/Article/details/gtzemrszli.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ivvv.top/Article/details/gthuzjtgws.html

Go:   strings.Count(s, "a")
来源：http://dali.fzhhl.top/Article/details/gtjihcxujn.html

Ruby: s.count("a")
来源：http://dali.zdqjudy.top/Article/details/gtfcqmdnns.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yonumen.top/Article/details/gtphdxhrho.html

[E13] 逐字符遍历
来源：http://dali.gzhubu.top/Article/details/gtxfzmcyhx.html

Py:   for ch in s: print(ch)
来源：http://dali.wangdashe.top/Article/details/gtnmqdxdpd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.havefunace.top/Article/details/gtsibvyqqj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hysaishi.cn/Article/details/gttksmmdof.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zdqjudy.top/Article/details/gtarfijgnv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtowmtttun.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sufxvd.cn/Article/details/gtvesfyayd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yuxming.cn/Article/details/gtfbkbcwxb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gzhubu.top/Article/details/gtobhnobrk.html

[E14] URL 编码与 Base64
来源：http://dali.chenjidiqi.icu/Article/details/gtnswfpmzx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sxryk.cn/Article/details/gtrsvqjliq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtshuaafoc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.andypj.xyz/Article/details/gtwxnoxayp.html


<!-- 参考信息 -->