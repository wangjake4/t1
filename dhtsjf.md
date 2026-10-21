代发 wailian999

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvcrgzbnp.html

TS:   [...a, ...b];
来源：http://dali.c1oappe.top/Article/details/gtpqkgdcnj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hnqzz.top/Article/details/gtpvbrnulv.html

Go:   append(a, b...)
来源：http://dali.fzhhl.top/Article/details/gtrspeaqmy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jqgufenzy.top/Article/details/gtjxnyegil.html

C#:   a.Concat(b).ToList()
来源：http://dali.birdmap.top/Article/details/gtgwpmwjhc.html

[D09] 排序（升序）
来源：http://dali.jlsjyb.cn/Article/details/gtkvoszdgj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhiwuduotai.top/Article/details/gttgboragk.html

PHP:  sort($arr);
来源：http://dali.xinyue.icu/Article/details/gtamtbvbsv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.redwolf501.top/Article/details/gtjyvrjzbk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.mhx1999.top/Article/details/gtmaipltxx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hywenlv.cn/Article/details/gthwkvnixq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jianghu66.top/Article/details/gtbhedzteb.html

Ruby: arr.sort
来源：http://dali.zhoulong.xyz/Article/details/gtobyfnnmg.html

C#:   list.Sort();
来源：http://dali.316326.xyz/Article/details/gtugullitk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jlsjyb.cn/Article/details/gtitbxampk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhoulong.xyz/Article/details/gtrrgymmzn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hnqzz.top/Article/details/gtkjfxmbqy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xziqi.cn/Article/details/gtomzjucjf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ppjwa.cn/Article/details/gtwbjdadbu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ybcxt.top/Article/details/gthpsgrubr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hnxiangtu.top/Article/details/gtheewbczt.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinqigfzy.top/Article/details/gtdpncvjxo.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ppjwa.cn/Article/details/gtfctfmdkj.html

[D11] 反转数组
来源：http://dali.chenlongwang.top/Article/details/gtevdcjrec.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.tian-w.cn/Article/details/gtahekvngc.html

PHP:  array_reverse($arr);
来源：http://dali.gogol.net.cn/Article/details/gtjuumthlr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gotoacloud.top/Article/details/gtdvicwrsn.html

TS:   [...arr].reverse();
来源：http://dali.yj20258.top/Article/details/gtiwygwzpr.html

Java: Collections.reverse(list);
来源：http://dali.yueranfly.top/Article/details/gtvehycqts.html

Go:   slices.Reverse(arr)
来源：http://dali.gzhubu.top/Article/details/gtdhatoeqv.html

Ruby: arr.reverse
来源：http://dali.daxiang520.top/Article/details/gthctdnflx.html

C#:   list.Reverse();
来源：http://dali.guowangkeji.top/Article/details/gtjepgycma.html

[D12] 查找元素下标
来源：http://dali.zhengqikj.top/Article/details/gtlujhdfsj.html

Py:   arr.index(x);  x in arr
来源：http://dali.mhx1999.top/Article/details/gtxomamrix.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jlsjyb.cn/Article/details/gtybhofenq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dashuyun.cn/Article/details/gttwwydwba.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jlsjyb.cn/Article/details/gtkeurokkt.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.wangdashe.top/Article/details/gtvhymzhtk.html

Go:   slices.Index(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtewzzpeji.html

Ruby: arr.index(x)
来源：http://dali.yvedp.cn/Article/details/gteqekqeuh.html

C#:   list.IndexOf(x);
来源：http://dali.zdqjudy.top/Article/details/gthuxqlvkb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sxryk.cn/Article/details/gtpjdmqsmf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.quarkkingdee.top/Article/details/gtohvubgwx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ybcxt.top/Article/details/gtfbphpcvl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthbguzexu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gzhubu.top/Article/details/gteobfwpxv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.guannengcc.top/Article/details/gtpapotylm.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ehwqpu.com/Article/details/gtazzkrycj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmhhtftre.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ybcxt.top/Article/details/gtbpdohcfo.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yueranfly.top/Article/details/gtlmpbszfi.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xziqi.cn/Article/details/gtvbujzatl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.kuanghao11.cn/Article/details/gtndvnmxzc.html

JS:   arr.map(x => x * 2)
来源：http://dali.tianlin.xyz/Article/details/gtphkwwsef.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhixingplan.top/Article/details/gtuhnhlgxu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yuxming.cn/Article/details/gttzhawenb.html

Go:   // 手写循环
来源：http://dali.yanxiufei.cn/Article/details/gtamckfwfx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.chenzaomai.com/Article/details/gtersruqpv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtmzxitrrp.html

[D15] 去重
来源：http://dali.ppjwa.cn/Article/details/gtogsvtzvt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cucudq.cn/Article/details/gtqoetltnq.html

PHP:  array_unique($arr);
来源：http://dali.nwbrower.top/Article/details/gtajvmrhmg.html

JS:   [...new Set(arr)]
来源：http://dali.jlsjyb.cn/Article/details/gtoglpronm.html

TS:   [...new Set(arr)]
来源：http://dali.andypj.xyz/Article/details/gtaejdbboq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.birdmap.top/Article/details/gtxpqisyml.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.guannengcc.top/Article/details/gtfpgjhzla.html

Ruby: arr.uniq
来源：http://dali.zdqjudy.top/Article/details/gtgnwlfeuu.html

C#:   list.Distinct().ToList()
来源：http://dali.yueranfly.top/Article/details/gtksduqrii.html

[D16] 求和与平均值
来源：http://dali.zhoulong.xyz/Article/details/gtsloblwvo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.meibo888.top/Article/details/gtsdlsettb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gzhubu.top/Article/details/gtrzzjdeio.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtfwtifcgh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shzxlz.cn/Article/details/gtcpipngan.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yuxming.cn/Article/details/gtmbctnryh.html

Go:   // 手写循环累加
来源：http://dali.cheryme.top/Article/details/gtxdpgnhqv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.chenjidiqi.icu/Article/details/gtvchwepef.html

C#:   list.Sum();  list.Average()
来源：http://dali.hysaishi.cn/Article/details/gtpqymizou.html

[D17] 最大值与最小值
来源：http://dali.ybcxt.top/Article/details/gteuotvlka.html

Py:   max(arr);  min(arr)
来源：http://dali.ivvv.top/Article/details/gtqzyytreh.html

PHP:  max($arr);  min($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtrkmolkcf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ydzc1.top/Article/details/gtbfnuhnbs.html

TS:   Math.max(...arr);
来源：http://dali.9152youxi.cn/Article/details/gtaoyhgmiq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinqigufen.top/Article/details/gtqghvvmhr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xuanzx.com/Article/details/gtgcdnuarn.html

Ruby: arr.max;  arr.min
来源：http://dali.ivvv.top/Article/details/gtnznzifma.html

C#:   list.Max();  list.Min()
来源：http://dali.jlsjyb.cn/Article/details/gtcxwhjpvo.html

[D18] 扁平化嵌套数组
来源：http://dali.snrcjt.cn/Article/details/gtadowggzu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.c1oappe.top/Article/details/gtnpyychrd.html

PHP:  array_merge(...$nested);
来源：http://dali.hnxiangtu.top/Article/details/gtfxpmzcci.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ybcxt.top/Article/details/gttcmdntqd.html

TS:   nested.flat();
来源：http://dali.yanxiufei.cn/Article/details/gtgkettttz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtvpjhrvcj.html

Go:   // 手写双层循环
来源：http://dali.zhongyouzk.top/Article/details/gtbesiplou.html

Ruby: nested.flatten
来源：http://dali.havefunace.top/Article/details/gtxognxfga.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cucudq.cn/Article/details/gthiaxyueg.html

[D19] 按字段分组
来源：http://dali.cucudq.cn/Article/details/gtijjjdauc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.meibo888.top/Article/details/gthhiwpeep.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hnxiangtu.top/Article/details/gtxoewziih.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.c1oappe.top/Article/details/gtctjeqfzz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxvvmrpqs.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.snrcjt.cn/Article/details/gttlapeuml.html

Go:   // 手写 map[string][]T
来源：http://dali.aizwys.cn/Article/details/gtzxufxqje.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.tian-w.cn/Article/details/gtzvzqqjol.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shanyushiyangtech.top/Article/details/gtwyujxkei.html

[D20] 统计每个元素出现次数
来源：http://dali.sysykeji.top/Article/details/gtsuakkjvp.html

Py:   Counter(arr)
来源：http://dali.daria6918.cn/Article/details/gtrgrsxrtc.html

PHP:  array_count_values($arr);
来源：http://dali.ppjwa.cn/Article/details/gtsrvvokjw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aizwys.cn/Article/details/gtpswtixyp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwrvruhpn.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gogol.net.cn/Article/details/gtwpuazzuu.html

Go:   // 手写 map[T]int
来源：http://dali.zhongyouzk.top/Article/details/gtkjikpxqv.html

Ruby: arr.tally
来源：http://dali.jqgfzy.top/Article/details/gtmnjpvtho.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gzhubu.top/Article/details/gtihgbzjii.html

[D21] 判断是否包含某元素
来源：http://dali.yangfankeji.com/Article/details/gtheisxqfq.html

Py:   x in arr
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlwsbcgne.html

PHP:  in_array($x, $arr, true);
来源：http://dali.fzhhl.top/Article/details/gtldqouioj.html

JS:   arr.includes(x)
来源：http://dali.cucudq.cn/Article/details/gtlofrqysr.html

TS:   arr.includes(x)
来源：http://dali.tanke756.top/Article/details/gtsowmgibm.html

Java: list.contains(x)
来源：http://dali.smart0.xyz/Article/details/gtjjgqjgdc.html

Go:   slices.Contains(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtuyomtefw.html

Ruby: arr.include?(x)
来源：http://dali.zycfv.cn/Article/details/gthcyjindo.html

C#:   list.Contains(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtagyaflju.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yuxming.cn/Article/details/gtrudcbmtp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xylfe.cn/Article/details/gtfqtwdkku.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhongyouzk.top/Article/details/gtalmhjaoa.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenlongwang.top/Article/details/gtavvknwbb.html

TS:   [...arr];
来源：http://dali.nwbrower.top/Article/details/gtbtknzmlp.html

Java: new ArrayList<>(list);
来源：http://dali.havefunace.top/Article/details/gtgjjyishe.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hfpthk.cn/Article/details/gtmymoakgs.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jqgufenzy.top/Article/details/gtcwtropve.html

C#:   new List<int>(list);
来源：http://dali.jyoumei.cn/Article/details/gtejvvosvy.html

[D23] reduce 累积计算
来源：http://dali.dianchejie.cn/Article/details/gtbxjimdcf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yonumen.top/Article/details/gtzfmoilos.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtgzgzrmtm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dianchejie.cn/Article/details/gtsixjbhmn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtaunnylad.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cashguo.top/Article/details/gtgfernjcr.html

Go:   // 手写循环
来源：http://dali.316326.xyz/Article/details/gtytzopwyx.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.chenzaomai.com/Article/details/gtgijalcga.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yj20258888.top/Article/details/gtsftdyymj.html

[D24] 字典 / Map 基本操作
来源：http://dali.jiagoushi.top/Article/details/gtjipblkja.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yangfankeji.com/Article/details/gtqrurcqpc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenlongwang.top/Article/details/gtpadwwbzw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jyoumei.cn/Article/details/gtjrneyvfw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtlschxudy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfcmkwhhq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hammf.cn/Article/details/gtneywzjdb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.316326.xyz/Article/details/gtxkzwvkgz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuefrkqqk.html

[D25] Set 集合去重与交并差
来源：http://dali.snrcjt.cn/Article/details/gtqbskfdmk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.nanxinkj.top/Article/details/gtuiuhfeod.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.redwolf501.top/Article/details/gtuhmpjkpb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhoulong.xyz/Article/details/gtgyqtyipd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.aizwys.cn/Article/details/gtlfipszir.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yuanzhike.top/Article/details/gthbbmawkr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yvedp.cn/Article/details/gtclpfwpka.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.quarkkingdee.top/Article/details/gtvjaizpwt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gaohongyu789.top/Article/details/gtymtutjbh.html

[D26] 数组转字符串
来源：http://dali.cdnleiting.top/Article/details/gtkybhfneg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhixingplan.top/Article/details/gtcxiqanqr.html

PHP:  implode(", ", $arr);
来源：http://dali.zhoulong.xyz/Article/details/gtiyydbsdc.html

JS:   arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gtnklltscl.html

TS:   arr.join(", ")
来源：http://dali.pycfn.com/Article/details/gtmwmzyuny.html

Java: String.join(", ", list)
来源：http://dali.guowangkeji.top/Article/details/gtkgzukbxa.html

Go:   strings.Join(strs, ", ")
来源：http://dali.fengsongda.top/Article/details/gtcztazhcd.html

Ruby: arr.join(", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gtujgrifng.html

C#:   string.Join(", ", list)
来源：http://dali.ybcxt.top/Article/details/gtgqmkofod.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtovqfgwze.html

E. 字符串处理
来源：http://dali.yj20258.top/Article/details/gteeboknpv.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtplpyloja.html

[E01] 拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gtqqycfibs.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ydzc1.top/Article/details/gtjgmhzrhv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hammf.cn/Article/details/gtreavxymn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pycfn.com/Article/details/gtajgcmxwk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258.top/Article/details/gtlzqhkteb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.9152youxi.cn/Article/details/gtsqldiwvb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jqgfzy.top/Article/details/gtjjtycudp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.svipenyu.cn/Article/details/gtogqzwxnv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yuxming.cn/Article/details/gtiwthqsdz.html

[E02] 重复字符串
来源：http://dali.jinqigufen.top/Article/details/gtbbhlcjkz.html

Py:   "ab" * 3
来源：http://dali.yvedp.cn/Article/details/gtybzfhodj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinqigufen.top/Article/details/gtmkrxyzcm.html

JS:   "ab".repeat(3)
来源：http://dali.aibaodan.cn/Article/details/gtzqlmzduz.html

TS:   "ab".repeat(3)
来源：http://dali.hnxiangtu.top/Article/details/gtblkuovwb.html

Java: "ab".repeat(3)
来源：http://dali.yueranfly.top/Article/details/gtnngrxrdb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhixingplan.top/Article/details/gtmiywtybz.html

Ruby: "ab" * 3
来源：http://dali.yongpay.top/Article/details/gtfxrcbnnv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrkfwlxpb.html

[E03] 截取子串
来源：http://dali.dashuyun.cn/Article/details/gtqigdcwas.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shanyushiyangtech.top/Article/details/gtfpoyoqyl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gtqixerexa.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.chenjidiqi.icu/Article/details/gtvhvxrhyj.html

TS:   s.slice(1, 4)
来源：http://dali.sysykeji.top/Article/details/gtkurboepp.html

Java: s.substring(1, 4)
来源：http://dali.jyoumei.cn/Article/details/gtspvugfti.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hammf.cn/Article/details/gtqwkoicns.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sxryk.cn/Article/details/gtdkaqqnsv.html

C#:   s.Substring(1, 3)
来源：http://dali.yonumen.top/Article/details/gtvxileopb.html

[E04] 查找子串位置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqdfidlsm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jyoumei.cn/Article/details/gtnnyfwxdf.html

PHP:  strpos($s, "x");
来源：http://dali.hnxiangtu.top/Article/details/gtbyigqfes.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhiwuduotai.top/Article/details/gtsifoecbf.html

TS:   s.indexOf("x")
来源：http://dali.hysaishi.cn/Article/details/gtraqflfun.html

Java: s.indexOf("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtptpjxdux.html

Go:   strings.Index(s, "x")
来源：http://dali.jinqigfzy.top/Article/details/gtjzhmfqfj.html

Ruby: s.index("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcvbsfebo.html

C#:   s.IndexOf("x")
来源：http://dali.haohaochexian.top/Article/details/gtctkmuebq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xziqi.cn/Article/details/gthglnojnn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.sweek.top/Article/details/gtccbsiskg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.quarkkingdee.top/Article/details/gtfhuhkbrj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yangfankeji.com/Article/details/gtwkiwttem.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.tian-w.cn/Article/details/gtyjmljznq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dashuyun.cn/Article/details/gtywghhjfu.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.mhx1999.top/Article/details/gthgussckv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvdzdowfn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hnxiangtu.top/Article/details/gtbrlwhmqz.html

[E06] 替换子串
来源：http://dali.ybcxt.top/Article/details/gtnljggdcd.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjdveuqpq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jiagoushi.top/Article/details/gtgrojbxsk.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gtrozgludb.html

TS:   s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtsmmhvjld.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnqzz.top/Article/details/gtumwcgmjt.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttjqfmcjj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtopkclpya.html

C#:   s.Replace("a", "b")
来源：http://dali.birdmap.top/Article/details/gtarxfmisk.html

[E07] 按分隔符拆分
来源：http://dali.jinqigufen.top/Article/details/gtwaecagww.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ivvv.top/Article/details/gtmoygvhpl.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.nanxinkj.top/Article/details/gtwhorftky.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhixingplan.top/Article/details/gtyyowyydo.html

TS:   s.split(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgcvcjgll.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shangyingyoupin.top/Article/details/gtzawigysi.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sufxvd.cn/Article/details/gtjjmagyug.html

Ruby: s.split(",");  s.split
来源：http://dali.xylfe.cn/Article/details/gtrokxzjpq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.chenzaomai.com/Article/details/gtqmmhowbr.html

[E08] 数组按分隔符合并
来源：http://dali.pycfn.com/Article/details/gtrfcntknh.html

Py:   ",".join(items)
来源：http://dali.hnqzz.top/Article/details/gtbreujoza.html

PHP:  implode(",", $items);
来源：http://dali.tanke756.top/Article/details/gtpyrfzpng.html

JS:   items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gtblcgmagb.html

TS:   items.join(",")
来源：http://dali.jianghu66.top/Article/details/gtpanwurjb.html

Java: String.join(",", items)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlblgrfft.html

Go:   strings.Join(items, ",")
来源：http://dali.shanyushiyangtech.top/Article/details/gtaxdlttwd.html

Ruby: items.join(",")
来源：http://dali.ivvv.top/Article/details/gtthirmrfp.html

C#:   string.Join(",", items)
来源：http://dali.jinqigufen.top/Article/details/gtzukoqnus.html

[E09] 去除所有空白字符
来源：http://dali.chenjidiqi.icu/Article/details/gtbqlktjax.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yueranfly.top/Article/details/gtxufpyzyu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cqqwz.cn/Article/details/gtxwkepgyc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.pengpengdd.cyou/Article/details/gtdoonczmo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tian-w.cn/Article/details/gtqumvyprk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shanyushiyangtech.top/Article/details/gttfrznzsk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hammf.cn/Article/details/gtbuffdpnk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenjidiqi.icu/Article/details/gtemvftuxr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gaohongyu789.top/Article/details/gtauoqhciz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yuxming.cn/Article/details/gtsynpzuqc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gtaaymllhq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gaohongyu789.top/Article/details/gtpmazojml.html

JS:   "7".padStart(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gtxkwszlfn.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gtlosbchxi.html

Java: String.format("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gtrdrscqjg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.9152youxi.cn/Article/details/gtfltmcfbo.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hywenlv.cn/Article/details/gtphzslrvp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.birdmap.top/Article/details/gtypmqvpxf.html

[E11] 反转字符串
来源：http://dali.ivvv.top/Article/details/gthezppaam.html

Py:   s[::-1]
来源：http://dali.tanke756.top/Article/details/gtwfsbelux.html

PHP:  strrev($s);
来源：http://dali.wangdashe.top/Article/details/gtdzfrsjbk.html

JS:   [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gtnfwfmmkd.html

TS:   [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gtuqmwowhf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.nanxinkj.top/Article/details/gtivmicnyv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ybcxt.top/Article/details/gtcmdeljgn.html

Ruby: s.reverse
来源：http://dali.nanxuanxn.top/Article/details/gtjdtmhkzp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmvqeunea.html

[E12] 统计某字符出现次数
来源：http://dali.sysykeji.top/Article/details/gtmsejprui.html

Py:   s.count("a")
来源：http://dali.0kj1m.cn/Article/details/gtyzudbbyq.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxuanxn.top/Article/details/gtvmkxaftq.html

JS:   s.split("a").length - 1
来源：http://dali.chenlongwang.top/Article/details/gtymviiogi.html

TS:   s.split("a").length - 1
来源：http://dali.cheryme.top/Article/details/gtzzzkymhx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.fzhhl.top/Article/details/gtaznczcog.html

Go:   strings.Count(s, "a")
来源：http://dali.smart0.xyz/Article/details/gttcqbhgxd.html

Ruby: s.count("a")
来源：http://dali.iojbl.cn/Article/details/gtamhucryw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsxnfawmt.html

[E13] 逐字符遍历
来源：http://dali.jlsjyb.cn/Article/details/gtiizwwwan.html

Py:   for ch in s: print(ch)
来源：http://dali.gotoacloud.top/Article/details/gtsshlwels.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhoulong.xyz/Article/details/gtmpbrxlsi.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtatmyiegi.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xinyue.icu/Article/details/gtpvqufmej.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.fzhhl.top/Article/details/gttjwlxcis.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.pengpengdd.cyou/Article/details/gthykyxnuy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.316326.xyz/Article/details/gtkzafavbj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yj20258888.top/Article/details/gtvpeyzkyp.html

[E14] URL 编码与 Base64
来源：http://dali.tianlin.xyz/Article/details/gteubefxjk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinghuilouyu.cn/Article/details/gtbspkymyq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ppjwa.cn/Article/details/gtrrrhkuhz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xinyue.icu/Article/details/gturqskjjg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.daxiang520.top/Article/details/gtvzhqtxzf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gtnfrrriqw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.tian-w.cn/Article/details/gtftpentte.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hammf.cn/Article/details/gtvvqzmgce.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hywenlv.cn/Article/details/gtrvhsbxbb.html

[E15] HTML 转义 / 反转义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtapofbztl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jqgfzy.top/Article/details/gtwuaroalp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.redwolf501.top/Article/details/gtcuwruwqv.html


<!-- 参考信息 -->