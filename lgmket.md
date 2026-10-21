代发 wailian999

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gotoacloud.top/Article/details/gtguuxshuf.html

Ruby: arr.sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyzacrroz.html

C#:   list.Sort();
来源：http://dali.yj20258.top/Article/details/gtqfiicxul.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.chenzaomai.com/Article/details/gtcasdmobs.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.daria6918.cn/Article/details/gtvtixftsg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tianlin.xyz/Article/details/gtktqktlsy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinghuilouyu.cn/Article/details/gtoiynould.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hywenlv.cn/Article/details/gtmehefzol.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ppjwa.cn/Article/details/gtfamszsth.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cucudq.cn/Article/details/gtwxahrhio.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yonumen.top/Article/details/gtcdblyprf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.bjfxy.top/Article/details/gtknvjjevd.html

[D11] 反转数组
来源：http://dali.yongpay.top/Article/details/gtvhxzplco.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.vqdsnc.cn/Article/details/gtebhpcvaj.html

PHP:  array_reverse($arr);
来源：http://dali.chenzaomai.com/Article/details/gtrhvopnis.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yonumen.top/Article/details/gtglatxtjk.html

TS:   [...arr].reverse();
来源：http://dali.quarkkingdee.top/Article/details/gtpznjrfyx.html

Java: Collections.reverse(list);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtigpwmvwt.html

Go:   slices.Reverse(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtxctticys.html

Ruby: arr.reverse
来源：http://dali.cashguo.top/Article/details/gtyadowqiu.html

C#:   list.Reverse();
来源：http://dali.nanxuanxn.top/Article/details/gtnwmmfckw.html

[D12] 查找元素下标
来源：http://dali.jqgufenzy.top/Article/details/gthrovunig.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinqigfzy.top/Article/details/gtbtvkyweh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtdtvgyidu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuxming.cn/Article/details/gtjlzzikkb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cheryme.top/Article/details/gtviakkmjv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xuanzx.com/Article/details/gtyxybdegy.html

Go:   slices.Index(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gthrkevvoo.html

Ruby: arr.index(x)
来源：http://dali.jinqigfzy.top/Article/details/gtzuujtxuc.html

C#:   list.IndexOf(x);
来源：http://dali.cqqwz.cn/Article/details/gtvlwgikzt.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gzhubu.top/Article/details/gtqhxyqnag.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.nanxinkj.top/Article/details/gtrtrewcmc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaculedij.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaaomslde.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yanxiufei.cn/Article/details/gtvgumllno.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xuanzx.com/Article/details/gttujrdyrh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj202588.top/Article/details/gtkazcewkt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.316326.xyz/Article/details/gtnydmxqoj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cdnleiting.top/Article/details/gtzvyokqxe.html

[D14] 映射转换（每个元素变形）
来源：http://dali.havefunace.top/Article/details/gtnyppxixc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cashguo.top/Article/details/gtuapynacy.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gteaigqbbg.html

JS:   arr.map(x => x * 2)
来源：http://dali.tianlin.xyz/Article/details/gtyuagewpy.html

TS:   arr.map(x => x * 2)
来源：http://dali.hnqzz.top/Article/details/gtenzqhojb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hfpthk.cn/Article/details/gtiggsbvxb.html

Go:   // 手写循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttoosvlvu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yuanzhike.top/Article/details/gtqtwhfnrd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.0kj1m.cn/Article/details/gthunbdkga.html

[D15] 去重
来源：http://dali.zhoulong.xyz/Article/details/gtzgosugll.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvymnceah.html

PHP:  array_unique($arr);
来源：http://dali.jianghu66.top/Article/details/gtpcvteuwz.html

JS:   [...new Set(arr)]
来源：http://dali.tanke756.top/Article/details/gtddfnsyky.html

TS:   [...new Set(arr)]
来源：http://dali.ydzc1.top/Article/details/gthfrynkze.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sweek.top/Article/details/gtncvkdbsl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.0kj1m.cn/Article/details/gtjalpmlzw.html

Ruby: arr.uniq
来源：http://dali.smart0.xyz/Article/details/gtxkcbhycd.html

C#:   list.Distinct().ToList()
来源：http://dali.shzxlz.cn/Article/details/gtppcpzdto.html

[D16] 求和与平均值
来源：http://dali.wangshuangyany.cn/Article/details/gtdrunyirz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.aibaodan.cn/Article/details/gtijlncqpt.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtglxfyjzz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyvenihmf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.snrcjt.cn/Article/details/gtengovkdt.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ydzc1.top/Article/details/gtntjbxyjx.html

Go:   // 手写循环累加
来源：http://dali.xziqi.cn/Article/details/gtebdhlifq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.nanxinkj.top/Article/details/gtfsfdkfjy.html

C#:   list.Sum();  list.Average()
来源：http://dali.0kj1m.cn/Article/details/gtufpbnowe.html

[D17] 最大值与最小值
来源：http://dali.shangyingyoupin.top/Article/details/gtyuipyuaq.html

Py:   max(arr);  min(arr)
来源：http://dali.yj202588.top/Article/details/gtktgvwxhr.html

PHP:  max($arr);  min($arr);
来源：http://dali.jyoumei.cn/Article/details/gtkslwpgpj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yonumen.top/Article/details/gtwyizdjtr.html

TS:   Math.max(...arr);
来源：http://dali.gogol.net.cn/Article/details/gtdyasqcdk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.wangshuangyany.cn/Article/details/gtwuohepyo.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjxeinxoq.html

Ruby: arr.max;  arr.min
来源：http://dali.xinyue.icu/Article/details/gtoibxiufx.html

C#:   list.Max();  list.Min()
来源：http://dali.zdqjudy.top/Article/details/gtuaacfiyf.html

[D18] 扁平化嵌套数组
来源：http://dali.meibo888.top/Article/details/gtnmlzihri.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zycfv.cn/Article/details/gtbnbxjhfr.html

PHP:  array_merge(...$nested);
来源：http://dali.yvedp.cn/Article/details/gtchjdjdoc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.fzhhl.top/Article/details/gtjydtgopc.html

TS:   nested.flat();
来源：http://dali.jlsjyb.cn/Article/details/gtaybftxku.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.guannengcc.top/Article/details/gtruafngus.html

Go:   // 手写双层循环
来源：http://dali.yueranfly.top/Article/details/gttffcjxhc.html

Ruby: nested.flatten
来源：http://dali.hywenlv.cn/Article/details/gtlbpsmoyt.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtkteqfchz.html

[D19] 按字段分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzwfgdamx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.fzhhl.top/Article/details/gtfrsimxhr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.mhx1999.top/Article/details/gtbichwxsl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj20258888.top/Article/details/gtcsymqfjo.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyjszikyr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hysaishi.cn/Article/details/gtbypftrrj.html

Go:   // 手写 map[string][]T
来源：http://dali.0kj1m.cn/Article/details/gtjhohstqy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.redwolf501.top/Article/details/gtnouloxpj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yueranfly.top/Article/details/gtyzmqsxqy.html

[D20] 统计每个元素出现次数
来源：http://dali.guannengcc.top/Article/details/gttbjpbamz.html

Py:   Counter(arr)
来源：http://dali.sufxvd.cn/Article/details/gtgmkrmcgn.html

PHP:  array_count_values($arr);
来源：http://dali.dashuyun.cn/Article/details/gtsryrriwq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.bjfxy.top/Article/details/gtkstjucai.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fzhhl.top/Article/details/gtxthpsdhd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.redwolf501.top/Article/details/gtwfcajnun.html

Go:   // 手写 map[T]int
来源：http://dali.feifeiyinyue.top/Article/details/gtvvxeofib.html

Ruby: arr.tally
来源：http://dali.wangshuangyany.cn/Article/details/gtpnyxeaau.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinghuilouyu.cn/Article/details/gteaurxlrr.html

[D21] 判断是否包含某元素
来源：http://dali.jqgfzy.top/Article/details/gtfofigfme.html

Py:   x in arr
来源：http://dali.haohaochexian.top/Article/details/gtgjzvymrh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jlsjyb.cn/Article/details/gtsobwnwgm.html

JS:   arr.includes(x)
来源：http://dali.ybcxt.top/Article/details/gtrcsgtmas.html

TS:   arr.includes(x)
来源：http://dali.cdnleiting.top/Article/details/gtmiykpeiw.html

Java: list.contains(x)
来源：http://dali.meibo888.top/Article/details/gtmimvcqvs.html

Go:   slices.Contains(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtzihsxjcy.html

Ruby: arr.include?(x)
来源：http://dali.havefunace.top/Article/details/gtlvthbxws.html

C#:   list.Contains(x)
来源：http://dali.havefunace.top/Article/details/gtkurgeulw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jyoumei.cn/Article/details/gtsdqskadz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ydzc1.top/Article/details/gtxepdggha.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.iojbl.cn/Article/details/gtxkqzsvjd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cucudq.cn/Article/details/gtzeugrufk.html

TS:   [...arr];
来源：http://dali.ydzc1.top/Article/details/gtfcimsaua.html

Java: new ArrayList<>(list);
来源：http://dali.gogol.net.cn/Article/details/gtkytvuyem.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.pengpengdd.cyou/Article/details/gtdzataapa.html

Ruby: arr.dup;  arr.clone
来源：http://dali.mhx1999.top/Article/details/gtbnldtnxf.html

C#:   new List<int>(list);
来源：http://dali.hywenlv.cn/Article/details/gtoagjcyfp.html

[D23] reduce 累积计算
来源：http://dali.ybcxt.top/Article/details/gtdtxidhzb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhixingplan.top/Article/details/gtvmenidof.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.birdmap.top/Article/details/gtyajettit.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jyoumei.cn/Article/details/gthopiabpz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.havefunace.top/Article/details/gtuavymcxj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.svipenyu.cn/Article/details/gtuananeuf.html

Go:   // 手写循环
来源：http://dali.ybcxt.top/Article/details/gtpoibcwha.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shanyushiyangtech.top/Article/details/gtqsqrxohv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.pengpengdd.cyou/Article/details/gtztvxpvrh.html

[D24] 字典 / Map 基本操作
来源：http://dali.hywenlv.cn/Article/details/gtyyztrcrp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jqgfzy.top/Article/details/gtzqilorxf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbmiqzqyd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcuvcaduc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtnzhpsijs.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hnqzz.top/Article/details/gtzpalkpsm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.mhx1999.top/Article/details/gtbbjjcchw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.haohaochexian.top/Article/details/gtscaklllj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hammf.cn/Article/details/gtavvolzcw.html

[D25] Set 集合去重与交并差
来源：http://dali.9152youxi.cn/Article/details/gtdcbvlgnu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yongpay.top/Article/details/gtgziuhswg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yj20258888.top/Article/details/gtouyniion.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hywenlv.cn/Article/details/gtvthqmfrd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhoulong.xyz/Article/details/gtagqwsccw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xziqi.cn/Article/details/gtxecuqjgo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.snrcjt.cn/Article/details/gtqbhgwuow.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhoulong.xyz/Article/details/gtyzduozrw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jianghu66.top/Article/details/gtpekmzuod.html

[D26] 数组转字符串
来源：http://dali.ehwqpu.com/Article/details/gtwvzhauef.html

Py:   ", ".join(map(str, arr))
来源：http://dali.aizwys.cn/Article/details/gtctzezwka.html

PHP:  implode(", ", $arr);
来源：http://dali.haohaochexian.top/Article/details/gtqhqvtdgq.html

JS:   arr.join(", ")
来源：http://dali.zycfv.cn/Article/details/gtiqmlmlxy.html

TS:   arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gttniimhhp.html

Java: String.join(", ", list)
来源：http://dali.nanxinkj.top/Article/details/gtknigfprn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hywenlv.cn/Article/details/gtpeoychwb.html

Ruby: arr.join(", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsqpuhqxq.html

C#:   string.Join(", ", list)
来源：http://dali.yuxming.cn/Article/details/gtvndyxwyv.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtwgxkbzsg.html

E. 字符串处理
来源：http://dali.yj20258888.top/Article/details/gtoruvbrtc.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtndrptruz.html

[E01] 拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gtvlmrkplh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.chenjidiqi.icu/Article/details/gtkhrmikre.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jiagoushi.top/Article/details/gtrgqwlnex.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258888.top/Article/details/gtzpqeabgb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwelpgshw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.chenzaomai.com/Article/details/gtoxbyjnew.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sufxvd.cn/Article/details/gtsnykvnva.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoytbpfok.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtanbrclko.html

[E02] 重复字符串
来源：http://dali.jinqigufen.top/Article/details/gtlygmdmhn.html

Py:   "ab" * 3
来源：http://dali.yueranfly.top/Article/details/gtimroctqa.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthlmbncyn.html

JS:   "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gtulzyjsdg.html

TS:   "ab".repeat(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmnvpdhcq.html

Java: "ab".repeat(3)
来源：http://dali.jinqigufen.top/Article/details/gtbczfgpkg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hongshengwenyu.top/Article/details/gtssdtfsff.html

Ruby: "ab" * 3
来源：http://dali.kuanghao11.cn/Article/details/gtegmzpfkq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenjidiqi.icu/Article/details/gtzwsvwzvr.html

[E03] 截取子串
来源：http://dali.xziqi.cn/Article/details/gttinubusd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.c1oappe.top/Article/details/gtotphqeeo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gtgtwzmvse.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.sxryk.cn/Article/details/gtaswiyddb.html

TS:   s.slice(1, 4)
来源：http://dali.zhixingplan.top/Article/details/gtkdwohjkr.html

Java: s.substring(1, 4)
来源：http://dali.fengsongda.top/Article/details/gtzuwrgpnv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.quarkkingdee.top/Article/details/gtsbgercdp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cdnleiting.top/Article/details/gtbblfuuzk.html

C#:   s.Substring(1, 3)
来源：http://dali.hnqzz.top/Article/details/gtdkmnvurq.html

[E04] 查找子串位置
来源：http://dali.yj202588.top/Article/details/gtbsnotzmb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hfpthk.cn/Article/details/gthpvzuiwn.html

PHP:  strpos($s, "x");
来源：http://dali.xylfe.cn/Article/details/gtnjvrfsuq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hfpthk.cn/Article/details/gtxguxmnzi.html

TS:   s.indexOf("x")
来源：http://dali.smart0.xyz/Article/details/gthwtqzelv.html

Java: s.indexOf("x")
来源：http://dali.hywenlv.cn/Article/details/gttdjavmgs.html

Go:   strings.Index(s, "x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtluudxtpt.html

Ruby: s.index("x")
来源：http://dali.hysaishi.cn/Article/details/gtyfffdfwn.html

C#:   s.IndexOf("x")
来源：http://dali.zhiwuduotai.top/Article/details/gtzepcvlax.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzaqphcbb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gtgkwkrkdm.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.chenlongwang.top/Article/details/gtkhqrbyli.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gogol.net.cn/Article/details/gtbybjyele.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xziqi.cn/Article/details/gtlsezuznt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnxiangtu.top/Article/details/gtwicewjhz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.daxiang520.top/Article/details/gtyycxssby.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.meibo888.top/Article/details/gtvzogbvbq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gttsvuxbvh.html

[E06] 替换子串
来源：http://dali.zycfv.cn/Article/details/gtwhmzxtey.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.svipenyu.cn/Article/details/gthbsoapcd.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hfpthk.cn/Article/details/gtsptsknyk.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtsjeactwe.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtgsloddjm.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gttutoorqa.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.andypj.xyz/Article/details/gtwqodmaay.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cheryme.top/Article/details/gtxyulnbkn.html

C#:   s.Replace("a", "b")
来源：http://dali.birdmap.top/Article/details/gtfhsggjfm.html

[E07] 按分隔符拆分
来源：http://dali.yuanzhike.top/Article/details/gtntldbzbp.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.pengpengdd.cyou/Article/details/gtrfzrpgyx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tian-w.cn/Article/details/gttxfmmrnb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.gzhubu.top/Article/details/gtixocpaax.html

TS:   s.split(",")
来源：http://dali.ehwqpu.com/Article/details/gtihwvkgrx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yangfankeji.com/Article/details/gtqtbiponq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.guannengcc.top/Article/details/gtfkngsqpg.html

Ruby: s.split(",");  s.split
来源：http://dali.yj20258888.top/Article/details/gtjexgzscl.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.guowangkeji.top/Article/details/gtpomelfic.html

[E08] 数组按分隔符合并
来源：http://dali.hnxiangtu.top/Article/details/gtxdxwrvwn.html

Py:   ",".join(items)
来源：http://dali.guowangkeji.top/Article/details/gtlyjcakof.html

PHP:  implode(",", $items);
来源：http://dali.hnxiangtu.top/Article/details/gtgbpqgnhn.html

JS:   items.join(",")
来源：http://dali.snrcjt.cn/Article/details/gtqifzqmjv.html

TS:   items.join(",")
来源：http://dali.cheryme.top/Article/details/gthcydsqcl.html

Java: String.join(",", items)
来源：http://dali.fzhhl.top/Article/details/gtbhciyivn.html

Go:   strings.Join(items, ",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfqfmdwsc.html

Ruby: items.join(",")
来源：http://dali.cqqwz.cn/Article/details/gturnjtkpr.html

C#:   string.Join(",", items)
来源：http://dali.svipenyu.cn/Article/details/gtzaoxtafa.html

[E09] 去除所有空白字符
来源：http://dali.dianchejie.cn/Article/details/gtmwegdwvl.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtlfqojvoi.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zdqjudy.top/Article/details/gtjhteftko.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yonumen.top/Article/details/gtlkszxltj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jyoumei.cn/Article/details/gtqvvqkpwd.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.316326.xyz/Article/details/gtbleulzbj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.nanxinkj.top/Article/details/gtqzqpgwlw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jlsjyb.cn/Article/details/gthmrrcgpm.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hfpthk.cn/Article/details/gtgxdxkyhf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zycfv.cn/Article/details/gtzdworrbz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.svipenyu.cn/Article/details/gtdohymxny.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zycfv.cn/Article/details/gtycchpylx.html

JS:   "7".padStart(3, "0")
来源：http://dali.shuidangran.top/Article/details/gtlpccvvhr.html

TS:   "7".padStart(3, "0")
来源：http://dali.jqgufenzy.top/Article/details/gtfhcyjdhh.html

Java: String.format("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gtcnjfshnm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gtryfmvggu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.wangshuangyany.cn/Article/details/gtureanwej.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yangfankeji.com/Article/details/gthxxugyye.html

[E11] 反转字符串
来源：http://dali.fzhhl.top/Article/details/gtxupajuyj.html

Py:   s[::-1]
来源：http://dali.jianghu66.top/Article/details/gtqwdjhndd.html

PHP:  strrev($s);
来源：http://dali.cashguo.top/Article/details/gtdjmiwmpb.html

JS:   [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gtnwsaozwp.html

TS:   [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gtyzxupunu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj202588.top/Article/details/gtezvrfglo.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.feifeiyinyue.top/Article/details/gtjaqruvmw.html

Ruby: s.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gtajbdhgjf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinqigfzy.top/Article/details/gtiaiwgeri.html

[E12] 统计某字符出现次数
来源：http://dali.cashguo.top/Article/details/gthyyzkzag.html

Py:   s.count("a")
来源：http://dali.c1oappe.top/Article/details/gthpyrouay.html

PHP:  substr_count($s, "a");
来源：http://dali.haohaochexian.top/Article/details/gtznstrurz.html

JS:   s.split("a").length - 1
来源：http://dali.jianghu66.top/Article/details/gtichqzrxd.html

TS:   s.split("a").length - 1
来源：http://dali.sysykeji.top/Article/details/gtuwqgiign.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cucudq.cn/Article/details/gthmggcuwl.html

Go:   strings.Count(s, "a")
来源：http://dali.yangfankeji.com/Article/details/gtkskntisf.html

Ruby: s.count("a")
来源：http://dali.cheryme.top/Article/details/gtwpwczest.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yangfankeji.com/Article/details/gtsxjfooyg.html

[E13] 逐字符遍历
来源：http://dali.c1oappe.top/Article/details/gtrszkdowj.html

Py:   for ch in s: print(ch)
来源：http://dali.yj202588.top/Article/details/gtedjrtsai.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hongshengwenyu.top/Article/details/gtyxyxejal.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuxming.cn/Article/details/gtwwcdsohc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtjtukljxv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.fengsongda.top/Article/details/gtpdwyzurs.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.nanxinkj.top/Article/details/gtyrsgxwia.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jqgfzy.top/Article/details/gtycajesvo.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jinqigufen.top/Article/details/gtgbowrvqo.html

[E14] URL 编码与 Base64
来源：http://dali.fengsongda.top/Article/details/gtpuiirdqa.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinghuilouyu.cn/Article/details/gtxuejmjoc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.sysykeji.top/Article/details/gtuzazpyxt.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.meibo888.top/Article/details/gttpdyabxc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sysykeji.top/Article/details/gtiiprkzda.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jqgfzy.top/Article/details/gtqrptrfic.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.c1oappe.top/Article/details/gtcqwcfeno.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cucudq.cn/Article/details/gtktghqowy.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.kuanghao11.cn/Article/details/gtrtaahscf.html

[E15] HTML 转义 / 反转义
来源：http://dali.xuanzx.com/Article/details/gtziuhvkrl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shuidangran.top/Article/details/gtunebgftx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ehwqpu.com/Article/details/gtmwhhwygb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtyazolcjk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gzhubu.top/Article/details/gtdzgxzazu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.havefunace.top/Article/details/gtwfihahwc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hnqzz.top/Article/details/gtwuybmjqz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gtmudpwjqw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ydzc1.top/Article/details/gtzgdugnwf.html

[E16] 数字千分位
来源：http://dali.yj20258.top/Article/details/gtmpccnwrv.html

Py:   f"{1234567:,}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtqohuxyuv.html

PHP:  number_format(1234567);
来源：http://dali.gotoacloud.top/Article/details/gtzhsgdryd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxinkj.top/Article/details/gtzmapvmdi.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuxming.cn/Article/details/gtvqnxapdx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnucgcpbu.html


<!-- 参考信息 -->