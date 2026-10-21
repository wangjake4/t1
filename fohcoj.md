代发 wailian999

[D07] 切片 / 取子数组
来源：http://dali.ppjwa.cn/Article/details/gtsyluaijw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xuetiantiany.cn/Article/details/gtcvwwdblr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj202588.top/Article/details/gtqrxymwzq.html

JS:   arr.slice(1, 4);
来源：http://dali.hywenlv.cn/Article/details/gtooobfsqt.html

TS:   arr.slice(1, 4);
来源：http://dali.tanke756.top/Article/details/gtpyaootff.html

Java: list.subList(1, 4);
来源：http://dali.xinyue.icu/Article/details/gtblkceivr.html

Go:   arr[1:4]
来源：http://dali.zhoulong.xyz/Article/details/gtpeoyyuyr.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gtxvelyxgo.html

C#:   list.GetRange(1, 3);
来源：http://dali.daria6918.cn/Article/details/gtcwyqduvl.html

[D08] 合并两个数组
来源：http://dali.yonumen.top/Article/details/gtxofodlbp.html

Py:   a + b;  a.extend(b)
来源：http://dali.feifeiyinyue.top/Article/details/gtsudhpswa.html

PHP:  array_merge($a, $b);
来源：http://dali.gotoacloud.top/Article/details/gtfhbwvhig.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hywenlv.cn/Article/details/gtugmtnwvk.html

TS:   [...a, ...b];
来源：http://dali.hongshengwenyu.top/Article/details/gtaddvfjur.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.daria6918.cn/Article/details/gtvtoilrhk.html

Go:   append(a, b...)
来源：http://dali.jinqigufen.top/Article/details/gtkkmdyuum.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sufxvd.cn/Article/details/gtiyzfmuvy.html

C#:   a.Concat(b).ToList()
来源：http://dali.smart0.xyz/Article/details/gtgjxabcfj.html

[D09] 排序（升序）
来源：http://dali.guowangkeji.top/Article/details/gtwghyntiq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ppjwa.cn/Article/details/gthvdsdwrs.html

PHP:  sort($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtokmnpiwl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zycfv.cn/Article/details/gtabxeuhyh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xinyue.icu/Article/details/gtcmhuvbka.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtarljpkcd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtqfgdzjhd.html

Ruby: arr.sort
来源：http://dali.gzhubu.top/Article/details/gtdkunsdjc.html

C#:   list.Sort();
来源：http://dali.shzxlz.cn/Article/details/gtmuhenzvi.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.mhx1999.top/Article/details/gtgosdelzk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.svipenyu.cn/Article/details/gtgukwkhcg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yuanzhike.top/Article/details/gtbevajiff.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhengqikj.top/Article/details/gtvgqxcghm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sufxvd.cn/Article/details/gtupptdgvi.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.tianlin.xyz/Article/details/gtbrotolin.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hammf.cn/Article/details/gteqrbjcuj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.bjfxy.top/Article/details/gtocddabhi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.birdmap.top/Article/details/gtkqxznkbw.html

[D11] 反转数组
来源：http://dali.tanke756.top/Article/details/gtoikicmkr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hywenlv.cn/Article/details/gtaaonkjcp.html

PHP:  array_reverse($arr);
来源：http://dali.iojbl.cn/Article/details/gtuezjmpcl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.fzhhl.top/Article/details/gtpcdxaiqc.html

TS:   [...arr].reverse();
来源：http://dali.yongpay.top/Article/details/gtwnfusgzx.html

Java: Collections.reverse(list);
来源：http://dali.fzhhl.top/Article/details/gtimaclcmq.html

Go:   slices.Reverse(arr)
来源：http://dali.daxiang520.top/Article/details/gtxisyphxj.html

Ruby: arr.reverse
来源：http://dali.nanxuanxn.top/Article/details/gtbyjhuiqv.html

C#:   list.Reverse();
来源：http://dali.jiagoushi.top/Article/details/gtgobeoles.html

[D12] 查找元素下标
来源：http://dali.jqgufenzy.top/Article/details/gtqqktdpqy.html

Py:   arr.index(x);  x in arr
来源：http://dali.tianlin.xyz/Article/details/gtadffixdq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.vqdsnc.cn/Article/details/gtkcsaiyve.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shzxlz.cn/Article/details/gthxktjdhc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gaohongyu789.top/Article/details/gtkcybdogi.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhongyouzk.top/Article/details/gtlqvoldbi.html

Go:   slices.Index(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtlhxreliq.html

Ruby: arr.index(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtvrqdeeyw.html

C#:   list.IndexOf(x);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyvkxenst.html

[D13] 过滤（保留满足条件的）
来源：http://dali.0kj1m.cn/Article/details/gtlvwxldup.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jianghu66.top/Article/details/gtypghlrwt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinqigufen.top/Article/details/gtzbggdfjd.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jianghu66.top/Article/details/gtfiieozzj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gzhubu.top/Article/details/gtghlxuumt.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.birdmap.top/Article/details/gtuaaknxbl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hongshengwenyu.top/Article/details/gtfrkvphui.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.haohaochexian.top/Article/details/gtvqwphizv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ehwqpu.com/Article/details/gtlelnyach.html

[D14] 映射转换（每个元素变形）
来源：http://dali.aizwys.cn/Article/details/gtrnjjwluj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.svipenyu.cn/Article/details/gtwgkumpgj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yuxming.cn/Article/details/gtvboklype.html

JS:   arr.map(x => x * 2)
来源：http://dali.sweek.top/Article/details/gtbvmdlnpf.html

TS:   arr.map(x => x * 2)
来源：http://dali.cdnleiting.top/Article/details/gthxdeotjh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtpvxwoqsw.html

Go:   // 手写循环
来源：http://dali.daria6918.cn/Article/details/gtyipiprir.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtfsymtxdq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gtunuqwinw.html

[D15] 去重
来源：http://dali.shanyushiyangkeji.top/Article/details/gtafdovwgu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cdnleiting.top/Article/details/gtaszfquwn.html

PHP:  array_unique($arr);
来源：http://dali.cheryme.top/Article/details/gtbvitwynk.html

JS:   [...new Set(arr)]
来源：http://dali.zhixingplan.top/Article/details/gtkthzzbbg.html

TS:   [...new Set(arr)]
来源：http://dali.sufxvd.cn/Article/details/gtoyveedqu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ehwqpu.com/Article/details/gteqnnmidg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zdqjudy.top/Article/details/gtornlylig.html

Ruby: arr.uniq
来源：http://dali.xuanzx.com/Article/details/gtdpesmodk.html

C#:   list.Distinct().ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtpnqjegiy.html

[D16] 求和与平均值
来源：http://dali.c1oappe.top/Article/details/gtubdyjoas.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.dianchejie.cn/Article/details/gteunkeyel.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yongpay.top/Article/details/gtwdmanvwh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aibaodan.cn/Article/details/gtldamyurx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shzxlz.cn/Article/details/gtbnmpafyv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinqigufen.top/Article/details/gtswktutlg.html

Go:   // 手写循环累加
来源：http://dali.aizwys.cn/Article/details/gtyhkxfhpm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.kuanghao11.cn/Article/details/gtoctrbaax.html

C#:   list.Sum();  list.Average()
来源：http://dali.hnqzz.top/Article/details/gtcepiflvc.html

[D17] 最大值与最小值
来源：http://dali.feifeiyinyue.top/Article/details/gtruecbzdy.html

Py:   max(arr);  min(arr)
来源：http://dali.shuidangran.top/Article/details/gtwlqdcjbm.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtmzeswtcd.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.haohaochexian.top/Article/details/gtluhedded.html

TS:   Math.max(...arr);
来源：http://dali.xinyue.icu/Article/details/gtbrkvjsqv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yonumen.top/Article/details/gtelwddshb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtnnduystz.html

Ruby: arr.max;  arr.min
来源：http://dali.quarkkingdee.top/Article/details/gtrlqnwpxf.html

C#:   list.Max();  list.Min()
来源：http://dali.iojbl.cn/Article/details/gtgptgpaby.html

[D18] 扁平化嵌套数组
来源：http://dali.pengpengdd.cyou/Article/details/gtophasuey.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yvedp.cn/Article/details/gtprbwyhkc.html

PHP:  array_merge(...$nested);
来源：http://dali.zhiwuduotai.top/Article/details/gtdqfrxcny.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.0kj1m.cn/Article/details/gtwgjbpadd.html

TS:   nested.flat();
来源：http://dali.yanxiufei.cn/Article/details/gtvyekaoal.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xylfe.cn/Article/details/gtlzbjylqv.html

Go:   // 手写双层循环
来源：http://dali.shangyingyoupin.top/Article/details/gtwwjeicsz.html

Ruby: nested.flatten
来源：http://dali.hongshengwenyu.top/Article/details/gtolpildso.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.tian-w.cn/Article/details/gtnidrqved.html

[D19] 按字段分组
来源：http://dali.feifeiyinyue.top/Article/details/gthshvpskz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtqkjxoemg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.wangdashe.top/Article/details/gtdulyktkl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yvedp.cn/Article/details/gtwllhghey.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jqgufenzy.top/Article/details/gtjhqdgkjb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xylfe.cn/Article/details/gthtjgcsat.html

Go:   // 手写 map[string][]T
来源：http://dali.shzxlz.cn/Article/details/gtcbattbkl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.c1oappe.top/Article/details/gtwxejizov.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhixingplan.top/Article/details/gtmijssuqw.html

[D20] 统计每个元素出现次数
来源：http://dali.bjfxy.top/Article/details/gtabdqvtnt.html

Py:   Counter(arr)
来源：http://dali.cheryme.top/Article/details/gtvcentulh.html

PHP:  array_count_values($arr);
来源：http://dali.ydzc1.top/Article/details/gtrtnpkwtz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pycfn.com/Article/details/gtpkeaekyn.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daria6918.cn/Article/details/gtwytglqxm.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.9152youxi.cn/Article/details/gtbjvhxrsm.html

Go:   // 手写 map[T]int
来源：http://dali.sysykeji.top/Article/details/gtaqmzwrrd.html

Ruby: arr.tally
来源：http://dali.feifeiyinyue.top/Article/details/gtoldvkuqj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cashguo.top/Article/details/gtkciavzqq.html

[D21] 判断是否包含某元素
来源：http://dali.tianlin.xyz/Article/details/gtdygyweuy.html

Py:   x in arr
来源：http://dali.daria6918.cn/Article/details/gtropgcwvp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.haohaochexian.top/Article/details/gtzqjszbzt.html

JS:   arr.includes(x)
来源：http://dali.hnqzz.top/Article/details/gteiyxgwpp.html

TS:   arr.includes(x)
来源：http://dali.yangfankeji.com/Article/details/gtxdfvjsua.html

Java: list.contains(x)
来源：http://dali.chenlongwang.top/Article/details/gtehqeabur.html

Go:   slices.Contains(arr, x)
来源：http://dali.gzhubu.top/Article/details/gtszagmjyz.html

Ruby: arr.include?(x)
来源：http://dali.meibo888.top/Article/details/gtaihvexvw.html

C#:   list.Contains(x)
来源：http://dali.sysykeji.top/Article/details/gtghudovsp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.mhx1999.top/Article/details/gtxgeskkvu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.fzhhl.top/Article/details/gtpxuxtmsv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.guowangkeji.top/Article/details/gtdewvjstq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.dianchejie.cn/Article/details/gtbvtsczda.html

TS:   [...arr];
来源：http://dali.0kj1m.cn/Article/details/gthgpjdrns.html

Java: new ArrayList<>(list);
来源：http://dali.kuanghao11.cn/Article/details/gtxkqsqlfa.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvichuhbx.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gogol.net.cn/Article/details/gtghtvvdsp.html

C#:   new List<int>(list);
来源：http://dali.hammf.cn/Article/details/gtdfvmtbug.html

[D23] reduce 累积计算
来源：http://dali.smart0.xyz/Article/details/gtptzcvzre.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.chenzaomai.com/Article/details/gtuwzhjrnz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ivvv.top/Article/details/gtyudfhirh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.andypj.xyz/Article/details/gtakvepjhc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sxryk.cn/Article/details/gtnkjnvpfl.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinghuilouyu.cn/Article/details/gtavhmxmub.html

Go:   // 手写循环
来源：http://dali.guannengcc.top/Article/details/gtewfqtcno.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jyoumei.cn/Article/details/gtqqaslboz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.nanxuanxn.top/Article/details/gtgkmqcwqd.html

[D24] 字典 / Map 基本操作
来源：http://dali.c1oappe.top/Article/details/gtunebkmfs.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.pycfn.com/Article/details/gtagfpsxve.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.iojbl.cn/Article/details/gtmnskunif.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhixingplan.top/Article/details/gtlrmsdwrk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ivvv.top/Article/details/gtasrnzdni.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.mhx1999.top/Article/details/gtxqrilrcv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.nanxuanxn.top/Article/details/gtkqayptpv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.fzhhl.top/Article/details/gtygbyczhw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvyzkfvmb.html

[D25] Set 集合去重与交并差
来源：http://dali.yongpay.top/Article/details/gtcblatpez.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.guowangkeji.top/Article/details/gtvlyyeumj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.tianlin.xyz/Article/details/gtsxklufow.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinqigufen.top/Article/details/gtkkgftifz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sweek.top/Article/details/gtyiaiqirk.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ydzc1.top/Article/details/gtexylaqdc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.redwolf501.top/Article/details/gtianfhbjc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yongpay.top/Article/details/gtftrdptzk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.chenzaomai.com/Article/details/gtmvyzejtv.html

[D26] 数组转字符串
来源：http://dali.mhx1999.top/Article/details/gtybstwhqz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yvedp.cn/Article/details/gtimkiwkbd.html

PHP:  implode(", ", $arr);
来源：http://dali.ehwqpu.com/Article/details/gtnluceoqr.html

JS:   arr.join(", ")
来源：http://dali.xylfe.cn/Article/details/gtisvrbmca.html

TS:   arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gtowncfpmx.html

Java: String.join(", ", list)
来源：http://dali.yvedp.cn/Article/details/gtmpfqhbmo.html

Go:   strings.Join(strs, ", ")
来源：http://dali.wangshuangyany.cn/Article/details/gtlramitdk.html

Ruby: arr.join(", ")
来源：http://dali.pengpengdd.cyou/Article/details/gtqittdres.html

C#:   string.Join(", ", list)
来源：http://dali.dashuyun.cn/Article/details/gtvinyzyez.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtlmmevtac.html

E. 字符串处理
来源：http://dali.jinqigfzy.top/Article/details/gtudfjznnu.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gthxsdpzbm.html

[E01] 拼接字符串
来源：http://dali.fengsongda.top/Article/details/gthugzbxii.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhoulong.xyz/Article/details/gtvrtwmefh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.meibo888.top/Article/details/gtmgpypmkl.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258888.top/Article/details/gtwtgkukgo.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.9152youxi.cn/Article/details/gtpmoknusm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hysaishi.cn/Article/details/gtgeudgfti.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jlsjyb.cn/Article/details/gtzftnlsnb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hnxiangtu.top/Article/details/gtaarolijj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtyidoxjom.html

[E02] 重复字符串
来源：http://dali.yvedp.cn/Article/details/gtbpujuuwn.html

Py:   "ab" * 3
来源：http://dali.shangyingyoupin.top/Article/details/gteszwpujm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yvedp.cn/Article/details/gtrsvewqkh.html

JS:   "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gtrrjomusj.html

TS:   "ab".repeat(3)
来源：http://dali.nanxuanxn.top/Article/details/gtqhwpdebl.html

Java: "ab".repeat(3)
来源：http://dali.havefunace.top/Article/details/gtjuhbhvhk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gogol.net.cn/Article/details/gtcsqcwplu.html

Ruby: "ab" * 3
来源：http://dali.pycfn.com/Article/details/gtixntbrkw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xziqi.cn/Article/details/gtdbfkatib.html

[E03] 截取子串
来源：http://dali.cheryme.top/Article/details/gtoqzqndvi.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.pycfn.com/Article/details/gtjwjtywig.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gtxjttznbm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gtqthanfig.html

TS:   s.slice(1, 4)
来源：http://dali.zhengqikj.top/Article/details/gtfkgugyox.html

Java: s.substring(1, 4)
来源：http://dali.chenlongwang.top/Article/details/gtmlnigmok.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sweek.top/Article/details/gtaqklvswo.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sufxvd.cn/Article/details/gtkxvadjhf.html

C#:   s.Substring(1, 3)
来源：http://dali.iojbl.cn/Article/details/gtfostergq.html

[E04] 查找子串位置
来源：http://dali.jqgfzy.top/Article/details/gtwsghpipw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sysykeji.top/Article/details/gtxlqxcerq.html

PHP:  strpos($s, "x");
来源：http://dali.sufxvd.cn/Article/details/gtrbbvwlcm.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.haohaochexian.top/Article/details/gtozvzrijq.html

TS:   s.indexOf("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxgxbulwf.html

Java: s.indexOf("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqhmxedgp.html

Go:   strings.Index(s, "x")
来源：http://dali.cdnleiting.top/Article/details/gtydwnwkim.html

Ruby: s.index("x")
来源：http://dali.meibo888.top/Article/details/gtpminzlhp.html

C#:   s.IndexOf("x")
来源：http://dali.chenjidiqi.icu/Article/details/gtpnlnbwvb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.iojbl.cn/Article/details/gthkpzuqwv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yuxming.cn/Article/details/gtahuhbokx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yonumen.top/Article/details/gtwprdzlzo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhixingplan.top/Article/details/gtkoozthku.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.daria6918.cn/Article/details/gtabtwjqlj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sufxvd.cn/Article/details/gtjamdkbzb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.tian-w.cn/Article/details/gtubhadjha.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.nwbrower.top/Article/details/gtmelhbivp.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhixingplan.top/Article/details/gtmcggulzb.html

[E06] 替换子串
来源：http://dali.jiagoushi.top/Article/details/gtzraimzkr.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdcrvuide.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tianlin.xyz/Article/details/gtvjqdduwa.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtkuhdbdap.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtucazskfv.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtwbloerwt.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yvedp.cn/Article/details/gtcjfmeheg.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtrtthnles.html

C#:   s.Replace("a", "b")
来源：http://dali.cheryme.top/Article/details/gtihgcqbey.html

[E07] 按分隔符拆分
来源：http://dali.kuanghao11.cn/Article/details/gtwyrbrwry.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yj20258.top/Article/details/gtbittaqif.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtsaqkbrvt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xziqi.cn/Article/details/gtjffomhbo.html

TS:   s.split(",")
来源：http://dali.redwolf501.top/Article/details/gtqzkwduat.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.quarkkingdee.top/Article/details/gtooaduzmz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.pycfn.com/Article/details/gtzicnbved.html

Ruby: s.split(",");  s.split
来源：http://dali.daria6918.cn/Article/details/gtxzluxyku.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.gotoacloud.top/Article/details/gtlovxwbkx.html

[E08] 数组按分隔符合并
来源：http://dali.shzxlz.cn/Article/details/gtfeuwjsqg.html

Py:   ",".join(items)
来源：http://dali.hywenlv.cn/Article/details/gtiugtriri.html

PHP:  implode(",", $items);
来源：http://dali.tian-w.cn/Article/details/gtujdvkjfv.html

JS:   items.join(",")
来源：http://dali.cheryme.top/Article/details/gtvanprmmj.html

TS:   items.join(",")
来源：http://dali.smart0.xyz/Article/details/gtvpujrsip.html

Java: String.join(",", items)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtitpnwvbx.html

Go:   strings.Join(items, ",")
来源：http://dali.c1oappe.top/Article/details/gtshsnfygv.html

Ruby: items.join(",")
来源：http://dali.quarkkingdee.top/Article/details/gtmiqmdtpv.html

C#:   string.Join(",", items)
来源：http://dali.wangshuangyany.cn/Article/details/gtzbpepebp.html

[E09] 去除所有空白字符
来源：http://dali.yj202588.top/Article/details/gtzttigazy.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.nanxuanxn.top/Article/details/gtmlzkzjcp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.9152youxi.cn/Article/details/gtgcuhqrax.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hammf.cn/Article/details/gtxzrxdrty.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hfpthk.cn/Article/details/gtvheexxki.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.vqdsnc.cn/Article/details/gtctqohngp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xinyue.icu/Article/details/gttdqzubmc.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cucudq.cn/Article/details/gttfdvyubw.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shangyingyoupin.top/Article/details/gtormfbplf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhiwuduotai.top/Article/details/gtsowiuyxq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jqgfzy.top/Article/details/gtjjniszkr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.pycfn.com/Article/details/gtcykdxrpw.html

JS:   "7".padStart(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gtmzjxjgtn.html

TS:   "7".padStart(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gtejdqzdxg.html

Java: String.format("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gtjyvxacxv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yj20258.top/Article/details/gtzcgjokaj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gteqxasnjr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hysaishi.cn/Article/details/gtshcqyrnx.html

[E11] 反转字符串
来源：http://dali.fengsongda.top/Article/details/gtbiejjhyf.html

Py:   s[::-1]
来源：http://dali.zhiwuduotai.top/Article/details/gtjyhqrwom.html

PHP:  strrev($s);
来源：http://dali.chenlongwang.top/Article/details/gtvhggetrm.html

JS:   [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtncxhundd.html

TS:   [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gttpclhwsu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.feifeiyinyue.top/Article/details/gtzxeomurp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hnqzz.top/Article/details/gthofcflab.html

Ruby: s.reverse
来源：http://dali.cashguo.top/Article/details/gtblqpotnw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhiwuduotai.top/Article/details/gtweznjrmg.html

[E12] 统计某字符出现次数
来源：http://dali.iojbl.cn/Article/details/gtovauknms.html

Py:   s.count("a")
来源：http://dali.ppjwa.cn/Article/details/gtvoknydta.html

PHP:  substr_count($s, "a");
来源：http://dali.yj20258.top/Article/details/gtzbyxewwy.html

JS:   s.split("a").length - 1
来源：http://dali.yonumen.top/Article/details/gticaznsez.html

TS:   s.split("a").length - 1
来源：http://dali.yonumen.top/Article/details/gtbpyxdjyr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.haohaochexian.top/Article/details/gtkqyumopt.html

Go:   strings.Count(s, "a")
来源：http://dali.jlsjyb.cn/Article/details/gtsrzluocn.html

Ruby: s.count("a")
来源：http://dali.jinqigfzy.top/Article/details/gtuntgputz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shanyushiyangtech.top/Article/details/gtrtbvpboe.html

[E13] 逐字符遍历
来源：http://dali.quarkkingdee.top/Article/details/gtnnveoaqf.html

Py:   for ch in s: print(ch)
来源：http://dali.sufxvd.cn/Article/details/gthwvxhzxd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jiagoushi.top/Article/details/gtltaugadh.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sysykeji.top/Article/details/gtkohgjzxz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gtixjpdawp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sweek.top/Article/details/gtufdyvvih.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gzhubu.top/Article/details/gtgrgmxaij.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nanxinkj.top/Article/details/gtumnjnobl.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.guowangkeji.top/Article/details/gtmucokmeb.html


<!-- 参考信息 -->