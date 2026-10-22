代发 wailian999

C#:   list.GetRange(1, 3);
来源：http://dali.yuxming.cn/Article/details/gt2bggyshet.html

[D08] 合并两个数组
来源：http://dali.zycfv.cn/Article/details/gt2fxxfoott.html

Py:   a + b;  a.extend(b)
来源：http://dali.tianlin.xyz/Article/details/gt2upatydop.html

PHP:  array_merge($a, $b);
来源：http://dali.nanxinkj.top/Article/details/gt2rugzwclu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhengqikj.top/Article/details/gt2ixoffivc.html

TS:   [...a, ...b];
来源：http://dali.andypj.xyz/Article/details/gt2pobsjhkn.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2jkdkocbr.html

Go:   append(a, b...)
来源：http://dali.tianlin.xyz/Article/details/gt2chyuawvx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sysykeji.top/Article/details/gt2jlravoku.html

C#:   a.Concat(b).ToList()
来源：http://dali.tianlin.xyz/Article/details/gt2eowmgmgl.html

[D09] 排序（升序）
来源：http://dali.ehwqpu.com/Article/details/gt2ptouggtd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cashguo.top/Article/details/gt2obzwyyha.html

PHP:  sort($arr);
来源：http://dali.yangfankeji.com/Article/details/gt2ezerlrmo.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ydzc1.top/Article/details/gt2ahauwyam.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hfpthk.cn/Article/details/gt2bukrhrvn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.quarkkingdee.top/Article/details/gt2fqtohtnw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.smart0.xyz/Article/details/gt2hiwbjtay.html

Ruby: arr.sort
来源：http://dali.sweek.top/Article/details/gt2pvuaekcz.html

C#:   list.Sort();
来源：http://dali.dianchejie.cn/Article/details/gt2llsleekp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cheryme.top/Article/details/gt2ankvflas.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hywenlv.cn/Article/details/gt2gxbvlobu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.kuanghao11.cn/Article/details/gt2uolzdwbd.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.quarkkingdee.top/Article/details/gt2bwekrepw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.c1oappe.top/Article/details/gt2qltifakh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.guowangkeji.top/Article/details/gt2rcnmlqnk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.andypj.xyz/Article/details/gt2hfsygufg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cdnleiting.top/Article/details/gt2cxsgtkvj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shanyushiyangtech.top/Article/details/gt2svdhraoh.html

[D11] 反转数组
来源：http://dali.jqgufenzy.top/Article/details/gt2zhjbncxx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cheryme.top/Article/details/gt2emmrcmhr.html

PHP:  array_reverse($arr);
来源：http://dali.aibaodan.cn/Article/details/gt2zhblovto.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.havefunace.top/Article/details/gt2humofhrj.html

TS:   [...arr].reverse();
来源：http://dali.wangshuangyany.cn/Article/details/gt2dejdkdme.html

Java: Collections.reverse(list);
来源：http://dali.cqqwz.cn/Article/details/gt2ndkbeucz.html

Go:   slices.Reverse(arr)
来源：http://dali.xuanzx.com/Article/details/gt2wzhubkax.html

Ruby: arr.reverse
来源：http://dali.daxiang520.top/Article/details/gt2kejghlgy.html

C#:   list.Reverse();
来源：http://dali.chenzaomai.com/Article/details/gt2fygkpevl.html

[D12] 查找元素下标
来源：http://dali.andypj.xyz/Article/details/gt2xkfajtno.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhoulong.xyz/Article/details/gt2cpnusssp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yongpay.top/Article/details/gt2sngffedv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dashuyun.cn/Article/details/gt2igevprkq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tanke756.top/Article/details/gt2wjhsqtbw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cashguo.top/Article/details/gt2nwnppwrq.html

Go:   slices.Index(arr, x)
来源：http://dali.cheryme.top/Article/details/gt2owlhkjib.html

Ruby: arr.index(x)
来源：http://dali.ydzc1.top/Article/details/gt2rmmvijvt.html

C#:   list.IndexOf(x);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dnasrlfx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.vqdsnc.cn/Article/details/gt2vkfgqppu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yvedp.cn/Article/details/gt2fwfddqgc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bcfbqaak.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhengqikj.top/Article/details/gt2awgxmsqh.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hfpthk.cn/Article/details/gt2umsbojqe.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.aizwys.cn/Article/details/gt2fvwyromj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.aibaodan.cn/Article/details/gt2mgnckgai.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.chenlongwang.top/Article/details/gt2hxaoogdc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ydzc1.top/Article/details/gt2uevgvpfo.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cashguo.top/Article/details/gt2vkqoczmu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zbycpouh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.gzhubu.top/Article/details/gt2ofjleqdk.html

JS:   arr.map(x => x * 2)
来源：http://dali.tianlin.xyz/Article/details/gt2lxxsfehu.html

TS:   arr.map(x => x * 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2winkhfnz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jlsjyb.cn/Article/details/gt2rspyzsiq.html

Go:   // 手写循环
来源：http://dali.316326.xyz/Article/details/gt2xxzyxlaw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.iojbl.cn/Article/details/gt2zcqvhexk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2gdptnbzb.html

[D15] 去重
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lbudkbkx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ppjwa.cn/Article/details/gt2ylhlsyqs.html

PHP:  array_unique($arr);
来源：http://dali.xuanzx.com/Article/details/gt2xdgryzlb.html

JS:   [...new Set(arr)]
来源：http://dali.bjfxy.top/Article/details/gt2phzpiwvo.html

TS:   [...new Set(arr)]
来源：http://dali.quarkkingdee.top/Article/details/gt2plcnqsaw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.c1oappe.top/Article/details/gt2nogpvonm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.havefunace.top/Article/details/gt2xipzxvnh.html

Ruby: arr.uniq
来源：http://dali.yonumen.top/Article/details/gt2dhmfutfv.html

C#:   list.Distinct().ToList()
来源：http://dali.yanxiufei.cn/Article/details/gt2cxesbyyj.html

[D16] 求和与平均值
来源：http://dali.jianghu66.top/Article/details/gt2sjukdbnc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2vklcxbiw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.smart0.xyz/Article/details/gt2iztgkvks.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hlxuvmef.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ybcxt.top/Article/details/gt2jrckqsxv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gotoacloud.top/Article/details/gt2zntqizua.html

Go:   // 手写循环累加
来源：http://dali.kuanghao11.cn/Article/details/gt2jyzkrhoo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yangfankeji.com/Article/details/gt2kjqhqcli.html

C#:   list.Sum();  list.Average()
来源：http://dali.yanxiufei.cn/Article/details/gt2eaoioroz.html

[D17] 最大值与最小值
来源：http://dali.yj20258888.top/Article/details/gt2emnkhpjx.html

Py:   max(arr);  min(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2tcexrlap.html

PHP:  max($arr);  min($arr);
来源：http://dali.0kj1m.cn/Article/details/gt2ummhzdrq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.andypj.xyz/Article/details/gt2hpgfcgtw.html

TS:   Math.max(...arr);
来源：http://dali.daxiang520.top/Article/details/gt2jfcpmjlq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yuanzhike.top/Article/details/gt2okvyjdjo.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2xrezwdnq.html

Ruby: arr.max;  arr.min
来源：http://dali.gogol.net.cn/Article/details/gt2henwafkf.html

C#:   list.Max();  list.Min()
来源：http://dali.pengpengdd.cyou/Article/details/gt2bciskxvc.html

[D18] 扁平化嵌套数组
来源：http://dali.jinghuilouyu.cn/Article/details/gt2juwlpopn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jiagoushi.top/Article/details/gt2zmzwovhc.html

PHP:  array_merge(...$nested);
来源：http://dali.yj202588.top/Article/details/gt2vtpfhpov.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xuanzx.com/Article/details/gt2qnlvnukz.html

TS:   nested.flat();
来源：http://dali.smart0.xyz/Article/details/gt2tdaracqn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ehwqpu.com/Article/details/gt2wiwshmwd.html

Go:   // 手写双层循环
来源：http://dali.quarkkingdee.top/Article/details/gt2qfbwnbzm.html

Ruby: nested.flatten
来源：http://dali.iojbl.cn/Article/details/gt2vpjegzam.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.guannengcc.top/Article/details/gt2bwjvwnkv.html

[D19] 按字段分组
来源：http://dali.shzxlz.cn/Article/details/gt2asywpvym.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2dyrwqyyg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.andypj.xyz/Article/details/gt2eholsbgw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.smart0.xyz/Article/details/gt2fnvsnvez.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.daria6918.cn/Article/details/gt2jyodfzxq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lgknioug.html

Go:   // 手写 map[string][]T
来源：http://dali.quarkkingdee.top/Article/details/gt2zluwhmlc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ehwqpu.com/Article/details/gt2afbningh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sweek.top/Article/details/gt2yilwbest.html

[D20] 统计每个元素出现次数
来源：http://dali.smart0.xyz/Article/details/gt2nvkvmcal.html

Py:   Counter(arr)
来源：http://dali.wangdashe.top/Article/details/gt2cgtjrrnt.html

PHP:  array_count_values($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2zrgdmwfo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangdashe.top/Article/details/gt2copmbymb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.redwolf501.top/Article/details/gt2dmznivge.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ldqwbmtd.html

Go:   // 手写 map[T]int
来源：http://dali.shanyushiyangtech.top/Article/details/gt2euermotp.html

Ruby: arr.tally
来源：http://dali.dashuyun.cn/Article/details/gt2dmadihnp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jiagoushi.top/Article/details/gt2fcdrqmos.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nideeihf.html

Py:   x in arr
来源：http://dali.yonumen.top/Article/details/gt2jlkxgvdb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.quarkkingdee.top/Article/details/gt2bxikgftj.html

JS:   arr.includes(x)
来源：http://dali.pycfn.com/Article/details/gt2lbcmzswm.html

TS:   arr.includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bdrgvfjk.html

Java: list.contains(x)
来源：http://dali.zhengqikj.top/Article/details/gt2xyscxdea.html

Go:   slices.Contains(arr, x)
来源：http://dali.ydzc1.top/Article/details/gt2ilrlscxl.html

Ruby: arr.include?(x)
来源：http://dali.havefunace.top/Article/details/gt2ufeysbnw.html

C#:   list.Contains(x)
来源：http://dali.birdmap.top/Article/details/gt2fsntrqit.html

[D22] 复制数组（避免共享引用）
来源：http://dali.0kj1m.cn/Article/details/gt2hgyplpzu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.316326.xyz/Article/details/gt2eiyvodfn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.316326.xyz/Article/details/gt2hlcenvwx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2kpdwwuky.html

TS:   [...arr];
来源：http://dali.snrcjt.cn/Article/details/gt2hdufjqpb.html

Java: new ArrayList<>(list);
来源：http://dali.guannengcc.top/Article/details/gt2rmqbffnj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yonumen.top/Article/details/gt2ozjagvxl.html

Ruby: arr.dup;  arr.clone
来源：http://dali.dianchejie.cn/Article/details/gt2phmgvfte.html

C#:   new List<int>(list);
来源：http://dali.zycfv.cn/Article/details/gt2firzmmil.html

[D23] reduce 累积计算
来源：http://dali.tian-w.cn/Article/details/gt2eukoguhv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2sjetdotg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.chenlongwang.top/Article/details/gt2kbzpzokh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2cxsyxfox.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iloeasea.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.birdmap.top/Article/details/gt2rvzneuoe.html

Go:   // 手写循环
来源：http://dali.havefunace.top/Article/details/gt2ykdxhqrc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.0kj1m.cn/Article/details/gt2gqipdlpm.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hysaishi.cn/Article/details/gt2qjcftibz.html

[D24] 字典 / Map 基本操作
来源：http://dali.sweek.top/Article/details/gt2cftoqaay.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kdypcudm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xylfe.cn/Article/details/gt2phvaihsv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yueranfly.top/Article/details/gt2ptojchyc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xuanzx.com/Article/details/gt2ioljapfv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinqigfzy.top/Article/details/gt2ntymdtah.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jyoumei.cn/Article/details/gt2rtpjvtvd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.quarkkingdee.top/Article/details/gt2irrcmhxh.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xylfe.cn/Article/details/gt2zfoelyit.html

[D25] Set 集合去重与交并差
来源：http://dali.xuanzx.com/Article/details/gt2oovqvhad.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shangyingyoupin.top/Article/details/gt2dmbgvqsh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hammf.cn/Article/details/gt2ymnorpyu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sweek.top/Article/details/gt2najxmvcl.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.kuanghao11.cn/Article/details/gt2tiecczqd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sufxvd.cn/Article/details/gt2kymxgrmp.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.9152youxi.cn/Article/details/gt2dfkyysqb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ppjwa.cn/Article/details/gt2yrrpzuvd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.chenlongwang.top/Article/details/gt2tbwgcyqz.html

[D26] 数组转字符串
来源：http://dali.shzxlz.cn/Article/details/gt2dbqfsajt.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jqgfzy.top/Article/details/gt2uhecgblw.html

PHP:  implode(", ", $arr);
来源：http://dali.ehwqpu.com/Article/details/gt2ohfnrdax.html

JS:   arr.join(", ")
来源：http://dali.yuanzhike.top/Article/details/gt2okilbvyh.html

TS:   arr.join(", ")
来源：http://dali.hammf.cn/Article/details/gt2nvzlqmzs.html

Java: String.join(", ", list)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zhnrzpwn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.birdmap.top/Article/details/gt2rzpmnfdi.html

Ruby: arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gt2kobtcnog.html

C#:   string.Join(", ", list)
来源：http://dali.cdnleiting.top/Article/details/gt2vvskyiyf.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2hlrpvmrk.html

E. 字符串处理
来源：http://dali.jlsjyb.cn/Article/details/gt2gupwbpjg.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2srskfdgr.html

[E01] 拼接字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dxznilsp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hfpthk.cn/Article/details/gt2nkzrkzwc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.aibaodan.cn/Article/details/gt2gumfueqq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vpcfpgpg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nwbrower.top/Article/details/gt2ndqpteka.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.fzhhl.top/Article/details/gt2matpkgwk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinqigufen.top/Article/details/gt2stxnathr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hysaishi.cn/Article/details/gt2yaawhynh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gzhubu.top/Article/details/gt2hesvnqew.html

[E02] 重复字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2bclahowh.html

Py:   "ab" * 3
来源：http://dali.jlsjyb.cn/Article/details/gt2kwpledow.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xuetiantiany.cn/Article/details/gt2mifkfoey.html

JS:   "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gt2hnmydmck.html

TS:   "ab".repeat(3)
来源：http://dali.andypj.xyz/Article/details/gt2myaintyz.html

Java: "ab".repeat(3)
来源：http://dali.yvedp.cn/Article/details/gt2shjkveuu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yanxiufei.cn/Article/details/gt2ahnnvraz.html

Ruby: "ab" * 3
来源：http://dali.yuxming.cn/Article/details/gt2ozbsftue.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.aibaodan.cn/Article/details/gt2tpydjcva.html

[E03] 截取子串
来源：http://dali.tianlin.xyz/Article/details/gt2xacnxgiv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zycfv.cn/Article/details/gt2pfwopnlf.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yj20258.top/Article/details/gt2fmfeepop.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zbrapjww.html

TS:   s.slice(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gt2cnelvmcl.html

Java: s.substring(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gt2lmnsherv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xinyue.icu/Article/details/gt2gelahymd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cqqwz.cn/Article/details/gt2ihdlyavz.html

C#:   s.Substring(1, 3)
来源：http://dali.svipenyu.cn/Article/details/gt2njsbaxsp.html

[E04] 查找子串位置
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dsiiburn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.fzhhl.top/Article/details/gt2ehtkzmiv.html

PHP:  strpos($s, "x");
来源：http://dali.ehwqpu.com/Article/details/gt2lrtbgypi.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ebgdgevx.html

TS:   s.indexOf("x")
来源：http://dali.iojbl.cn/Article/details/gt2sbzeshnu.html

Java: s.indexOf("x")
来源：http://dali.nanxinkj.top/Article/details/gt2nwczhdkl.html

Go:   strings.Index(s, "x")
来源：http://dali.andypj.xyz/Article/details/gt2kjyvyvuy.html

Ruby: s.index("x")
来源：http://dali.zhoulong.xyz/Article/details/gt2qrklxlzp.html

C#:   s.IndexOf("x")
来源：http://dali.cheryme.top/Article/details/gt2iwkzesrm.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sufxvd.cn/Article/details/gt2jzdndphu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.pycfn.com/Article/details/gt2gannjiam.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.chenjidiqi.icu/Article/details/gt2epwiqqvz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuxming.cn/Article/details/gt2vcxvrypj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jinqigfzy.top/Article/details/gt2yikuztjj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.0kj1m.cn/Article/details/gt2nkvvkscz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.nanxinkj.top/Article/details/gt2pyibdmth.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.wangshuangyany.cn/Article/details/gt2wblszwpj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gt2qevneeeb.html

[E06] 替换子串
来源：http://dali.pengpengdd.cyou/Article/details/gt2wrcsvbob.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nwbrower.top/Article/details/gt2abthuvhi.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ybcxt.top/Article/details/gt2hcpjdnyc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gt2sanqrklk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sysykeji.top/Article/details/gt2saxddbke.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gt2vjedtzgc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhengqikj.top/Article/details/gt2kuojvqaj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gt2llvjjfzu.html

C#:   s.Replace("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gt2izrvnmaj.html

[E07] 按分隔符拆分
来源：http://dali.snrcjt.cn/Article/details/gt2jkzpecjv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.wangdashe.top/Article/details/gt2citbpaqk.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tanke756.top/Article/details/gt2qvllhsts.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.mhx1999.top/Article/details/gt2mmvzbnti.html

TS:   s.split(",")
来源：http://dali.meibo888.top/Article/details/gt2lziaxuas.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jqgufenzy.top/Article/details/gt2pzvqsqjf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shuidangran.top/Article/details/gt2nxkmgwso.html

Ruby: s.split(",");  s.split
来源：http://dali.guannengcc.top/Article/details/gt2bbszscdt.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yj20258888.top/Article/details/gt2xhttrmoe.html

[E08] 数组按分隔符合并
来源：http://dali.aizwys.cn/Article/details/gt2femarefu.html

Py:   ",".join(items)
来源：http://dali.ehwqpu.com/Article/details/gt2zrwuwljq.html

PHP:  implode(",", $items);
来源：http://dali.smart0.xyz/Article/details/gt2nbspxran.html

JS:   items.join(",")
来源：http://dali.yongpay.top/Article/details/gt2mpemrkxw.html

TS:   items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2omxmotnh.html

Java: String.join(",", items)
来源：http://dali.hammf.cn/Article/details/gt2crffycsb.html

Go:   strings.Join(items, ",")
来源：http://dali.aizwys.cn/Article/details/gt2uhcdhqlv.html

Ruby: items.join(",")
来源：http://dali.xinyue.icu/Article/details/gt2hkonjkyv.html

C#:   string.Join(",", items)
来源：http://dali.ppjwa.cn/Article/details/gt2adznfptq.html

[E09] 去除所有空白字符
来源：http://dali.svipenyu.cn/Article/details/gt2ymuucicp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gotoacloud.top/Article/details/gt2zemimust.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhixingplan.top/Article/details/gt2hsoslgpw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kwgbkhxy.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vkikspnh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sxryk.cn/Article/details/gt2vmxhmwwv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.tanke756.top/Article/details/gt2rkyjhrjq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.aibaodan.cn/Article/details/gt2pjdejvll.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhengqikj.top/Article/details/gt2uoxcupdw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhengqikj.top/Article/details/gt2hnqnituv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gt2llambvsb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2trqikimg.html

JS:   "7".padStart(3, "0")
来源：http://dali.xylfe.cn/Article/details/gt2nltnecys.html

TS:   "7".padStart(3, "0")
来源：http://dali.dianchejie.cn/Article/details/gt2nzrwdzag.html

Java: String.format("%03d", 7)
来源：http://dali.chenzaomai.com/Article/details/gt2fqnjwckb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lvsigkss.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gt2knrbhxpz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.redwolf501.top/Article/details/gt2xgvuntxo.html

[E11] 反转字符串
来源：http://dali.fzhhl.top/Article/details/gt2swrwzcef.html

Py:   s[::-1]
来源：http://dali.kuanghao11.cn/Article/details/gt2emthsnsh.html

PHP:  strrev($s);
来源：http://dali.quarkkingdee.top/Article/details/gt2zypasktp.html

JS:   [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gt2lvzkenaq.html

TS:   [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gt2qxxriick.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vhyiycnn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.nanxinkj.top/Article/details/gt2ikxmjsaa.html

Ruby: s.reverse
来源：http://dali.ehwqpu.com/Article/details/gt2oeppgokk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shangyingyoupin.top/Article/details/gt2hngmwcgz.html

[E12] 统计某字符出现次数
来源：http://dali.hysaishi.cn/Article/details/gt2ffntvvzj.html

Py:   s.count("a")
来源：http://dali.birdmap.top/Article/details/gt2iavbaqvh.html

PHP:  substr_count($s, "a");
来源：http://dali.aizwys.cn/Article/details/gt2ixjkuifz.html

JS:   s.split("a").length - 1
来源：http://dali.yvedp.cn/Article/details/gt2thzznwbr.html

TS:   s.split("a").length - 1
来源：http://dali.quarkkingdee.top/Article/details/gt2zfackkls.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sufxvd.cn/Article/details/gt2hchrbdvh.html

Go:   strings.Count(s, "a")
来源：http://dali.chenzaomai.com/Article/details/gt2amujjszx.html

Ruby: s.count("a")
来源：http://dali.sysykeji.top/Article/details/gt2zvhnhkjo.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj20258.top/Article/details/gt2dyghrsos.html

[E13] 逐字符遍历
来源：http://dali.cheryme.top/Article/details/gt2npavfdnu.html

Py:   for ch in s: print(ch)
来源：http://dali.smart0.xyz/Article/details/gt2yveckfeo.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2optwooqo.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.haohaochexian.top/Article/details/gt2fcgussgd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgfzy.top/Article/details/gt2wkeyqzvt.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yongpay.top/Article/details/gt2xsyadrce.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.316326.xyz/Article/details/gt2eecnwxeh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.feifeiyinyue.top/Article/details/gt2gmieczfc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yj20258888.top/Article/details/gt2jmcralil.html

[E14] URL 编码与 Base64
来源：http://dali.shzxlz.cn/Article/details/gt2tivxelys.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gaohongyu789.top/Article/details/gt2qnrkvirx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.guannengcc.top/Article/details/gt2nmchhjkc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shangyingyoupin.top/Article/details/gt2knuvpkfk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tianlin.xyz/Article/details/gt2xjxanahy.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gt2nmiltvwy.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yj20258888.top/Article/details/gt2plpphfrm.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.tian-w.cn/Article/details/gt2zediplox.html


<!-- 参考信息 -->