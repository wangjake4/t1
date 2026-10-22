代发 wailian999

TS:   arr.slice(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gtazrzxtir.html

Java: list.subList(1, 4);
来源：http://dali.iojbl.cn/Article/details/gtkoicseej.html

Go:   arr[1:4]
来源：http://dali.quarkkingdee.top/Article/details/gtxhywffym.html

Ruby: arr[1, 3]
来源：http://dali.aizwys.cn/Article/details/gttfsrrsxo.html

C#:   list.GetRange(1, 3);
来源：http://dali.mhx1999.top/Article/details/gtrgiqsbhl.html

[D08] 合并两个数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtjuwlitxj.html

Py:   a + b;  a.extend(b)
来源：http://dali.zdqjudy.top/Article/details/gttoptyjcn.html

PHP:  array_merge($a, $b);
来源：http://dali.gotoacloud.top/Article/details/gtatjueswh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zdqjudy.top/Article/details/gtpsdwjezj.html

TS:   [...a, ...b];
来源：http://dali.tanke756.top/Article/details/gtepkpykwo.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cqqwz.cn/Article/details/gtvlabnneh.html

Go:   append(a, b...)
来源：http://dali.tanke756.top/Article/details/gtshxcosyp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtywjezeeu.html

C#:   a.Concat(b).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtrrmxyjne.html

[D09] 排序（升序）
来源：http://dali.yangfankeji.com/Article/details/gttlyizkhn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxinkj.top/Article/details/gtynioeeia.html

PHP:  sort($arr);
来源：http://dali.shzxlz.cn/Article/details/gtufgnpyvv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhoulong.xyz/Article/details/gtpsblmnpk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.snrcjt.cn/Article/details/gtdihaetfe.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.dianchejie.cn/Article/details/gtnytaguhi.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cucudq.cn/Article/details/gtmbccxcom.html

Ruby: arr.sort
来源：http://dali.nanxinkj.top/Article/details/gtdaaarmnn.html

C#:   list.Sort();
来源：http://dali.havefunace.top/Article/details/gtypprgspy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gogol.net.cn/Article/details/gttfmjbkgj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cheryme.top/Article/details/gtlndxilcx.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cdnleiting.top/Article/details/gtzzmiqrlk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnxiangtu.top/Article/details/gtiklmixla.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jianghu66.top/Article/details/gtvdfdwzut.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gogol.net.cn/Article/details/gtltursopz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.smart0.xyz/Article/details/gtjsumxtos.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nanxuanxn.top/Article/details/gtwemfkkwa.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gogol.net.cn/Article/details/gtxwhixvyf.html

[D11] 反转数组
来源：http://dali.zhiwuduotai.top/Article/details/gtqwptujop.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.chenjidiqi.icu/Article/details/gttiwesbgx.html

PHP:  array_reverse($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtwzabzyit.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shangyingyoupin.top/Article/details/gtqqpurscs.html

TS:   [...arr].reverse();
来源：http://dali.snrcjt.cn/Article/details/gtahkxzfaq.html

Java: Collections.reverse(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gtlslwnqaw.html

Go:   slices.Reverse(arr)
来源：http://dali.yongpay.top/Article/details/gtatqwizcm.html

Ruby: arr.reverse
来源：http://dali.jiagoushi.top/Article/details/gtwqbdikxv.html

C#:   list.Reverse();
来源：http://dali.gaohongyu789.top/Article/details/gtqzhsaecb.html

[D12] 查找元素下标
来源：http://dali.yvedp.cn/Article/details/gtkxkdgjmu.html

Py:   arr.index(x);  x in arr
来源：http://dali.smart0.xyz/Article/details/gtviojxhoq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.bjfxy.top/Article/details/gtdnfkkkkg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dianchejie.cn/Article/details/gtxolmhqsl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttouweumk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yongpay.top/Article/details/gtlecizaug.html

Go:   slices.Index(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoudlkghj.html

Ruby: arr.index(x)
来源：http://dali.andypj.xyz/Article/details/gtwfzdpxea.html

C#:   list.IndexOf(x);
来源：http://dali.ydzc1.top/Article/details/gtzruwfxle.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtepsonwyr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xziqi.cn/Article/details/gtlbfcpxcm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlfbgouzv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ivvv.top/Article/details/gtzysuxsfm.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gteupwhheq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.snrcjt.cn/Article/details/gtugdpjguy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.havefunace.top/Article/details/gtmxfahwqg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yj20258.top/Article/details/gtwwpamuku.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.guannengcc.top/Article/details/gtfrgxmrbm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.iojbl.cn/Article/details/gtiismckhg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkewsxhnc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ydzc1.top/Article/details/gtcfyxvuaa.html

JS:   arr.map(x => x * 2)
来源：http://dali.hysaishi.cn/Article/details/gtekavykds.html

TS:   arr.map(x => x * 2)
来源：http://dali.cheryme.top/Article/details/gtbfikiiwe.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.meibo888.top/Article/details/gtbypalngx.html

Go:   // 手写循环
来源：http://dali.zhoulong.xyz/Article/details/gtcahntexu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sxryk.cn/Article/details/gtszfzsvpj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xinyue.icu/Article/details/gtqndjjhwp.html

[D15] 去重
来源：http://dali.jinqigufen.top/Article/details/gttmtpwvzg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.meibo888.top/Article/details/gtxishmqmr.html

PHP:  array_unique($arr);
来源：http://dali.shuidangran.top/Article/details/gtzvebjeru.html

JS:   [...new Set(arr)]
来源：http://dali.gzhubu.top/Article/details/gtnhqandid.html

TS:   [...new Set(arr)]
来源：http://dali.hongshengwenyu.top/Article/details/gtftppjces.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.tianlin.xyz/Article/details/gthehqiszu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yonumen.top/Article/details/gturrjevze.html

Ruby: arr.uniq
来源：http://dali.hywenlv.cn/Article/details/gtijriqgpq.html

C#:   list.Distinct().ToList()
来源：http://dali.daria6918.cn/Article/details/gtmkhjjkmc.html

[D16] 求和与平均值
来源：http://dali.yj20258.top/Article/details/gtzotugvvv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yuxming.cn/Article/details/gthloabnzt.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gzhubu.top/Article/details/gtwrmcavbe.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hfpthk.cn/Article/details/gtwmvgjqlg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gotoacloud.top/Article/details/gtjrcejung.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yonumen.top/Article/details/gtpbbdkscb.html

Go:   // 手写循环累加
来源：http://dali.haohaochexian.top/Article/details/gtvgjzfpnu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.dashuyun.cn/Article/details/gtpjnbijeg.html

C#:   list.Sum();  list.Average()
来源：http://dali.cdnleiting.top/Article/details/gtylpagyrw.html

[D17] 最大值与最小值
来源：http://dali.aibaodan.cn/Article/details/gttfjowibq.html

Py:   max(arr);  min(arr)
来源：http://dali.meibo888.top/Article/details/gtruplabpo.html

PHP:  max($arr);  min($arr);
来源：http://dali.andypj.xyz/Article/details/gtgjjxrsfk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhongyouzk.top/Article/details/gtlgcwrxne.html

TS:   Math.max(...arr);
来源：http://dali.guowangkeji.top/Article/details/gtetvozkny.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhongyouzk.top/Article/details/gtdkconxsd.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtorubizcx.html

Ruby: arr.max;  arr.min
来源：http://dali.sysykeji.top/Article/details/gtiiwjjbiq.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gtszytqgyq.html

[D18] 扁平化嵌套数组
来源：http://dali.wangdashe.top/Article/details/gtzwtdxdpe.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.daxiang520.top/Article/details/gtbtrmorfb.html

PHP:  array_merge(...$nested);
来源：http://dali.ivvv.top/Article/details/gtgemfzmcu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yongpay.top/Article/details/gtflkcsjoi.html

TS:   nested.flat();
来源：http://dali.chenlongwang.top/Article/details/gtwrpesvqa.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yueranfly.top/Article/details/gtvryunsdr.html

Go:   // 手写双层循环
来源：http://dali.0kj1m.cn/Article/details/gtscaenysi.html

Ruby: nested.flatten
来源：http://dali.bjfxy.top/Article/details/gtytpoexuq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yuxming.cn/Article/details/gtukjvqoqr.html

[D19] 按字段分组
来源：http://dali.zdqjudy.top/Article/details/gttqlayrab.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zdqjudy.top/Article/details/gtyhlthknc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinqigufen.top/Article/details/gtoehfphwl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhongyouzk.top/Article/details/gtpwbriqbt.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.pengpengdd.cyou/Article/details/gtyhnkxhif.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.dianchejie.cn/Article/details/gtikibkmqr.html

Go:   // 手写 map[string][]T
来源：http://dali.wangdashe.top/Article/details/gtzfgvoxbo.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.aibaodan.cn/Article/details/gtcmytzqxm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yuxming.cn/Article/details/gtyfbnaohp.html

[D20] 统计每个元素出现次数
来源：http://dali.xinyue.icu/Article/details/gtosowphyz.html

Py:   Counter(arr)
来源：http://dali.tian-w.cn/Article/details/gthzmoqeov.html

PHP:  array_count_values($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtiwmlxrct.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.mhx1999.top/Article/details/gtvbtqzwel.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenjidiqi.icu/Article/details/gtavnvizca.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zycfv.cn/Article/details/gtiejhiquj.html

Go:   // 手写 map[T]int
来源：http://dali.gotoacloud.top/Article/details/gtyrenzmgd.html

Ruby: arr.tally
来源：http://dali.jianghu66.top/Article/details/gtjacyiqej.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.bjfxy.top/Article/details/gtbxsfahdx.html

[D21] 判断是否包含某元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtqvxgrdkp.html

Py:   x in arr
来源：http://dali.birdmap.top/Article/details/gtsgjmrutn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shzxlz.cn/Article/details/gtpuudqwer.html

JS:   arr.includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtevfgfosm.html

TS:   arr.includes(x)
来源：http://dali.bjfxy.top/Article/details/gtdvtrsamp.html

Java: list.contains(x)
来源：http://dali.dashuyun.cn/Article/details/gtegoadcmj.html

Go:   slices.Contains(arr, x)
来源：http://dali.havefunace.top/Article/details/gtvotzsnlz.html

Ruby: arr.include?(x)
来源：http://dali.guannengcc.top/Article/details/gtqvfuxdfz.html

C#:   list.Contains(x)
来源：http://dali.gotoacloud.top/Article/details/gthltetzlt.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xziqi.cn/Article/details/gtbukofbmy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.snrcjt.cn/Article/details/gtwnsppuvt.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hongshengwenyu.top/Article/details/gttdnzmolg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yvedp.cn/Article/details/gtafifkcrk.html

TS:   [...arr];
来源：http://dali.fengsongda.top/Article/details/gtxzezarym.html

Java: new ArrayList<>(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrdwdlzgs.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sweek.top/Article/details/gtjprbsjuh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yvedp.cn/Article/details/gtmwaxutqo.html

C#:   new List<int>(list);
来源：http://dali.cqqwz.cn/Article/details/gtrbnempdq.html

[D23] reduce 累积计算
来源：http://dali.nanxinkj.top/Article/details/gtdoozttij.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrjwtvvsd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gotoacloud.top/Article/details/gtburdyzyc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tian-w.cn/Article/details/gtrbciukdv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtompwnbdk.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yj20258.top/Article/details/gtbydmusdf.html

Go:   // 手写循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtxajtcgyl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj20258888.top/Article/details/gtdmgwngew.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gaohongyu789.top/Article/details/gttflrtfzp.html

[D24] 字典 / Map 基本操作
来源：http://dali.mhx1999.top/Article/details/gtogaxlzwl.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.guannengcc.top/Article/details/gtupazbhxk.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.smart0.xyz/Article/details/gtwttksiyu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.meibo888.top/Article/details/gtgcscsgeo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtycvdvwaw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sufxvd.cn/Article/details/gtaztdsbgk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhoulong.xyz/Article/details/gtrnobvkmw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.0kj1m.cn/Article/details/gtcqgiyvtn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinqigfzy.top/Article/details/gtghfvejte.html

[D25] Set 集合去重与交并差
来源：http://dali.tanke756.top/Article/details/gtaqnetjrk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yvedp.cn/Article/details/gtjiggpcbq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yonumen.top/Article/details/gtqkwrkhfz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jqgufenzy.top/Article/details/gtlvwqjtjp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.quarkkingdee.top/Article/details/gtzqzaecou.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yonumen.top/Article/details/gtvkfrazzr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrcqvwpdk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yongpay.top/Article/details/gttnukflah.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xuanzx.com/Article/details/gtfqhyssbw.html

[D26] 数组转字符串
来源：http://dali.yvedp.cn/Article/details/gtqlmfvxhd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gogol.net.cn/Article/details/gtygegtkrk.html

PHP:  implode(", ", $arr);
来源：http://dali.tian-w.cn/Article/details/gtmohweqvt.html

JS:   arr.join(", ")
来源：http://dali.gaohongyu789.top/Article/details/gtdjepceld.html

TS:   arr.join(", ")
来源：http://dali.zdqjudy.top/Article/details/gtqxiuqbvs.html

Java: String.join(", ", list)
来源：http://dali.pycfn.com/Article/details/gtzszpitrw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtogvxifkd.html

Ruby: arr.join(", ")
来源：http://dali.zhoulong.xyz/Article/details/gtkkxemrtr.html

C#:   string.Join(", ", list)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfzuqjith.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtscaxfjuc.html

E. 字符串处理
来源：http://dali.yj202588.top/Article/details/gtnpneypui.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtkgmihxyo.html

[E01] 拼接字符串
来源：http://dali.chenlongwang.top/Article/details/gtwbatbliz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sysykeji.top/Article/details/gtdbibjtqa.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhoulong.xyz/Article/details/gtorgopxjc.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yvedp.cn/Article/details/gthcertqmh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fzhhl.top/Article/details/gtewmgxyfw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtgudaaqtf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinqigfzy.top/Article/details/gtzdxpieyn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.guowangkeji.top/Article/details/gtdhpbrfjw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtmhhxcapk.html

[E02] 重复字符串
来源：http://dali.redwolf501.top/Article/details/gtprfmhgij.html

Py:   "ab" * 3
来源：http://dali.gogol.net.cn/Article/details/gtrbsknsav.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shzxlz.cn/Article/details/gtzvpxboih.html

JS:   "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gtdwfyszia.html

TS:   "ab".repeat(3)
来源：http://dali.quarkkingdee.top/Article/details/gtmwlbinwp.html

Java: "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtbkyaphmo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ivvv.top/Article/details/gtlkhlrdua.html

Ruby: "ab" * 3
来源：http://dali.jinqigufen.top/Article/details/gtwywdrpgl.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gtrgmrwrmr.html

[E03] 截取子串
来源：http://dali.zhixingplan.top/Article/details/gtvtgeymli.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenzaomai.com/Article/details/gtanepckpp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gtkbtdulbl.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gtmbftyzkl.html

TS:   s.slice(1, 4)
来源：http://dali.hysaishi.cn/Article/details/gtsgytgktn.html

Java: s.substring(1, 4)
来源：http://dali.zhoulong.xyz/Article/details/gtsodjiwbz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jlsjyb.cn/Article/details/gtpjtsbgaa.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.nwbrower.top/Article/details/gtnjbpllis.html

C#:   s.Substring(1, 3)
来源：http://dali.cucudq.cn/Article/details/gtalwiddsm.html

[E04] 查找子串位置
来源：http://dali.xuanzx.com/Article/details/gtbbheznot.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jqgufenzy.top/Article/details/gthpkwkjtw.html

PHP:  strpos($s, "x");
来源：http://dali.ybcxt.top/Article/details/gtdzxqozrx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gzhubu.top/Article/details/gtfwgzsznv.html

TS:   s.indexOf("x")
来源：http://dali.daria6918.cn/Article/details/gtkxlpoafu.html

Java: s.indexOf("x")
来源：http://dali.kuanghao11.cn/Article/details/gticienhun.html

Go:   strings.Index(s, "x")
来源：http://dali.feifeiyinyue.top/Article/details/gtzbtxtaiz.html

Ruby: s.index("x")
来源：http://dali.daxiang520.top/Article/details/gtswcfjsrt.html

C#:   s.IndexOf("x")
来源：http://dali.guowangkeji.top/Article/details/gthtzftvea.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hongshengwenyu.top/Article/details/gtzwdugsda.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.daria6918.cn/Article/details/gtozhplhxq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinqigfzy.top/Article/details/gtispkuhzr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.aizwys.cn/Article/details/gtlcodkqhd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhongyouzk.top/Article/details/gtuvsiltnk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hywenlv.cn/Article/details/gtzaduoyhe.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.chenlongwang.top/Article/details/gtimebwsdj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.feifeiyinyue.top/Article/details/gtfexkhmgr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jianghu66.top/Article/details/gtptbbihyp.html

[E06] 替换子串
来源：http://dali.andypj.xyz/Article/details/gtfosnmnlt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdzdpgdzt.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yanxiufei.cn/Article/details/gtjhwlldnz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtwgstwvpf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hnqzz.top/Article/details/gtkfvkyhby.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtbazsbtmd.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwtajezlv.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtvpbfwmtn.html

C#:   s.Replace("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtpxdyhrek.html

[E07] 按分隔符拆分
来源：http://dali.daria6918.cn/Article/details/gtgqrreerh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zdqjudy.top/Article/details/gtwfpwbycf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtcxiwztnu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.smart0.xyz/Article/details/gtzonhbliq.html

TS:   s.split(",")
来源：http://dali.zhoulong.xyz/Article/details/gttlgjxrby.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.fzhhl.top/Article/details/gtuntpccud.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtciyvbwcr.html

Ruby: s.split(",");  s.split
来源：http://dali.ydzc1.top/Article/details/gtcxsoqliz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttfnabmtl.html

[E08] 数组按分隔符合并
来源：http://dali.jyoumei.cn/Article/details/gtbrvabfrh.html

Py:   ",".join(items)
来源：http://dali.kuanghao11.cn/Article/details/gtvxoikcwm.html

PHP:  implode(",", $items);
来源：http://dali.daria6918.cn/Article/details/gtqmzchjnw.html

JS:   items.join(",")
来源：http://dali.zhongyouzk.top/Article/details/gtcauaogpy.html

TS:   items.join(",")
来源：http://dali.yj20258888.top/Article/details/gtggsaglcd.html

Java: String.join(",", items)
来源：http://dali.xylfe.cn/Article/details/gtcpzaqspy.html

Go:   strings.Join(items, ",")
来源：http://dali.gzhubu.top/Article/details/gtyawfrgkp.html

Ruby: items.join(",")
来源：http://dali.jyoumei.cn/Article/details/gtmspdnzoe.html

C#:   string.Join(",", items)
来源：http://dali.fzhhl.top/Article/details/gtshzqkkbr.html

[E09] 去除所有空白字符
来源：http://dali.haohaochexian.top/Article/details/gtsizuzwuh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ehwqpu.com/Article/details/gteixnymig.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cucudq.cn/Article/details/gtxcezyjdd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gaohongyu789.top/Article/details/gtvitcdcji.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhengqikj.top/Article/details/gtpfbhpdze.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.redwolf501.top/Article/details/gtiexcwadn.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.aizwys.cn/Article/details/gtwfpuagvk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ehwqpu.com/Article/details/gtsibcvwip.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.pengpengdd.cyou/Article/details/gtwhixvqey.html

[E10] 左侧补零 / 定长填充
来源：http://dali.bjfxy.top/Article/details/gtbclgvjzt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xziqi.cn/Article/details/gtyfdagmlg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hysaishi.cn/Article/details/gtborycsdj.html

JS:   "7".padStart(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gtgkxnjeax.html

TS:   "7".padStart(3, "0")
来源：http://dali.yongpay.top/Article/details/gtwlrrgrwf.html

Java: String.format("%03d", 7)
来源：http://dali.ydzc1.top/Article/details/gtqorggljo.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsplfdrpn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.mhx1999.top/Article/details/gtfneivkxt.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sweek.top/Article/details/gtkvsgfwfk.html

[E11] 反转字符串
来源：http://dali.jyoumei.cn/Article/details/gtzjavvtux.html

Py:   s[::-1]
来源：http://dali.yj20258.top/Article/details/gtaybyougl.html

PHP:  strrev($s);
来源：http://dali.jyoumei.cn/Article/details/gtetnwvuph.html

JS:   [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gtmfvoztsv.html

TS:   [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gtoyhnaevt.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xziqi.cn/Article/details/gtexpbdoek.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hnqzz.top/Article/details/gtdwmyehnl.html

Ruby: s.reverse
来源：http://dali.zhiwuduotai.top/Article/details/gtiabvpqgh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj20258.top/Article/details/gtrvrzaxas.html

[E12] 统计某字符出现次数
来源：http://dali.hfpthk.cn/Article/details/gtjteqdjds.html

Py:   s.count("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcuaaqcev.html

PHP:  substr_count($s, "a");
来源：http://dali.tianlin.xyz/Article/details/gtdzzroisi.html

JS:   s.split("a").length - 1
来源：http://dali.jqgfzy.top/Article/details/gtvypvrrrw.html

TS:   s.split("a").length - 1
来源：http://dali.zhengqikj.top/Article/details/gtyobfjlel.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.svipenyu.cn/Article/details/gtobkvitgb.html

Go:   strings.Count(s, "a")
来源：http://dali.guannengcc.top/Article/details/gtlrpuojzb.html

Ruby: s.count("a")
来源：http://dali.cqqwz.cn/Article/details/gttwopgwdu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ydzc1.top/Article/details/gttqvnsjac.html

[E13] 逐字符遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtadjzyjsl.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gteftbyrhh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jianghu66.top/Article/details/gtcsjukpep.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gtqzvbqrzb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangdashe.top/Article/details/gtgiqtmueb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nanxinkj.top/Article/details/gtdfgggfdf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.quarkkingdee.top/Article/details/gtcxwddxnn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinqigufen.top/Article/details/gtyscjkoog.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nwbrower.top/Article/details/gtokhlpgwo.html

[E14] URL 编码与 Base64
来源：http://dali.jinqigfzy.top/Article/details/gtbfowkheg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hysaishi.cn/Article/details/gtrikdsovm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinqigufen.top/Article/details/gtawygixwf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cashguo.top/Article/details/gthlhbmbna.html


<!-- 参考信息 -->