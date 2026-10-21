代发 wailian999

TS:   arr.slice(1, 4);
来源：http://dali.fengsongda.top/Article/details/gtewyzabde.html

Java: list.subList(1, 4);
来源：http://dali.jinqigfzy.top/Article/details/gtnhmjcfek.html

Go:   arr[1:4]
来源：http://dali.jyoumei.cn/Article/details/gtarjtamyj.html

Ruby: arr[1, 3]
来源：http://dali.ywan-chungtsiang.top/Article/details/gthfghptoq.html

C#:   list.GetRange(1, 3);
来源：http://dali.316326.xyz/Article/details/gtsnvbegel.html

[D08] 合并两个数组
来源：http://dali.jinqigufen.top/Article/details/gtbsbndaus.html

Py:   a + b;  a.extend(b)
来源：http://dali.feifeiyinyue.top/Article/details/gteenicuec.html

PHP:  array_merge($a, $b);
来源：http://dali.gaohongyu789.top/Article/details/gttuuaoukz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinqigufen.top/Article/details/gtbxrgksrf.html

TS:   [...a, ...b];
来源：http://dali.yvedp.cn/Article/details/gtghbvmkkx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.chenlongwang.top/Article/details/gtquyulfmy.html

Go:   append(a, b...)
来源：http://dali.guowangkeji.top/Article/details/gtbfjvkyfu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaqqgopfj.html

C#:   a.Concat(b).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdpfttawg.html

[D09] 排序（升序）
来源：http://dali.jinghuilouyu.cn/Article/details/gtssuvmnoh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yvedp.cn/Article/details/gtqjokyiir.html

PHP:  sort($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtlruzcevl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.snrcjt.cn/Article/details/gttsddwxbm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.nanxinkj.top/Article/details/gtridetpyn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhongyouzk.top/Article/details/gtqxqjrved.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yuanzhike.top/Article/details/gttvmzaxrw.html

Ruby: arr.sort
来源：http://dali.hammf.cn/Article/details/gtlcfozybk.html

C#:   list.Sort();
来源：http://dali.hfpthk.cn/Article/details/gthitmqajx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shanyushiyangtech.top/Article/details/gtprwudzsi.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hywenlv.cn/Article/details/gtpwziqozh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtayawtlut.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhengqikj.top/Article/details/gtpbwkfeld.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aizwys.cn/Article/details/gtiqjjzahq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hnqzz.top/Article/details/gtsbgunzsw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenzaomai.com/Article/details/gtgzlxfkqj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yanxiufei.cn/Article/details/gtukgtdkil.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hfpthk.cn/Article/details/gtvpwsepqq.html

[D11] 反转数组
来源：http://dali.316326.xyz/Article/details/gtktoldipl.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cdnleiting.top/Article/details/gtgzxonilz.html

PHP:  array_reverse($arr);
来源：http://dali.andypj.xyz/Article/details/gthgbzyvjo.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.mhx1999.top/Article/details/gtvtcbymbh.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gtplnvgsjp.html

Java: Collections.reverse(list);
来源：http://dali.hywenlv.cn/Article/details/gtyeekixau.html

Go:   slices.Reverse(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtuqmawzaz.html

Ruby: arr.reverse
来源：http://dali.shuidangran.top/Article/details/gtkfzqixzt.html

C#:   list.Reverse();
来源：http://dali.gogol.net.cn/Article/details/gtpsloinqa.html

[D12] 查找元素下标
来源：http://dali.wangdashe.top/Article/details/gtritmfojw.html

Py:   arr.index(x);  x in arr
来源：http://dali.xziqi.cn/Article/details/gtabbigvoi.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yonumen.top/Article/details/gtbcxcjpel.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.snrcjt.cn/Article/details/gtixazpzcn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tianlin.xyz/Article/details/gtmxgwjjge.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yanxiufei.cn/Article/details/gtlrgmalog.html

Go:   slices.Index(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtygelbtjq.html

Ruby: arr.index(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtytpcarsh.html

C#:   list.IndexOf(x);
来源：http://dali.sxryk.cn/Article/details/gtqcgyekos.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tianlin.xyz/Article/details/gtnsupmwhp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.pycfn.com/Article/details/gtkmchzoyx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhixingplan.top/Article/details/gtznohpckp.html

JS:   arr.filter(x => x > 3)
来源：http://dali.316326.xyz/Article/details/gtuvswstsf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ivvv.top/Article/details/gtlferarlo.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtlkioovpt.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.haohaochexian.top/Article/details/gtgdebmjdc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xziqi.cn/Article/details/gtbcldegje.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhengqikj.top/Article/details/gtcxzwxytl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jianghu66.top/Article/details/gtxyjlvzxt.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xinyue.icu/Article/details/gtyexdsyxp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yuanzhike.top/Article/details/gtsqvktlda.html

JS:   arr.map(x => x * 2)
来源：http://dali.ybcxt.top/Article/details/gtcgbuadwp.html

TS:   arr.map(x => x * 2)
来源：http://dali.chenlongwang.top/Article/details/gtsrbkmwkp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.svipenyu.cn/Article/details/gtksdqxpua.html

Go:   // 手写循环
来源：http://dali.zhongyouzk.top/Article/details/gtuhstibmm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ehwqpu.com/Article/details/gtoswoahrz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.fengsongda.top/Article/details/gtglaayuia.html

[D15] 去重
来源：http://dali.chenjidiqi.icu/Article/details/gtnemrartb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.vqdsnc.cn/Article/details/gteukzwmky.html

PHP:  array_unique($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzovikrmx.html

JS:   [...new Set(arr)]
来源：http://dali.aizwys.cn/Article/details/gtsdhvrxmu.html

TS:   [...new Set(arr)]
来源：http://dali.aizwys.cn/Article/details/gtkewaqsvy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yvedp.cn/Article/details/gtgqvpyobn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gaohongyu789.top/Article/details/gtkqnverrs.html

Ruby: arr.uniq
来源：http://dali.cheryme.top/Article/details/gtmuhjnasn.html

C#:   list.Distinct().ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtrosvdkvc.html

[D16] 求和与平均值
来源：http://dali.quarkkingdee.top/Article/details/gtcpvtguat.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj20258888.top/Article/details/gttdoevuey.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.chenlongwang.top/Article/details/gthdjnuwol.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tianlin.xyz/Article/details/gtvtecqnxh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aizwys.cn/Article/details/gtterxhjiz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.guowangkeji.top/Article/details/gtidqfmaau.html

Go:   // 手写循环累加
来源：http://dali.sufxvd.cn/Article/details/gtjocbtfal.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sysykeji.top/Article/details/gteaotvzsv.html

C#:   list.Sum();  list.Average()
来源：http://dali.wangshuangyany.cn/Article/details/gtbekhxtuu.html

[D17] 最大值与最小值
来源：http://dali.bjfxy.top/Article/details/gtbwasvdlc.html

Py:   max(arr);  min(arr)
来源：http://dali.snrcjt.cn/Article/details/gtamcqjzht.html

PHP:  max($arr);  min($arr);
来源：http://dali.hnqzz.top/Article/details/gtctkzpgbz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jyoumei.cn/Article/details/gtpiywplwp.html

TS:   Math.max(...arr);
来源：http://dali.smart0.xyz/Article/details/gtitevpuwo.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.guowangkeji.top/Article/details/gtxrhapejy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xuanzx.com/Article/details/gtzcuktnac.html

Ruby: arr.max;  arr.min
来源：http://dali.nanxinkj.top/Article/details/gtumovslro.html

C#:   list.Max();  list.Min()
来源：http://dali.aibaodan.cn/Article/details/gtsrgoqbwh.html

[D18] 扁平化嵌套数组
来源：http://dali.9152youxi.cn/Article/details/gttyfommzq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hnxiangtu.top/Article/details/gtcztwxurt.html

PHP:  array_merge(...$nested);
来源：http://dali.tanke756.top/Article/details/gtidbuhczl.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.havefunace.top/Article/details/gtzqpemwty.html

TS:   nested.flat();
来源：http://dali.smart0.xyz/Article/details/gtdmnkidus.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yuxming.cn/Article/details/gtcrplaetg.html

Go:   // 手写双层循环
来源：http://dali.xinyue.icu/Article/details/gtpteahmxf.html

Ruby: nested.flatten
来源：http://dali.haohaochexian.top/Article/details/gtszfecjup.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtnupefkgc.html

[D19] 按字段分组
来源：http://dali.hysaishi.cn/Article/details/gtzythnmfh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinqigfzy.top/Article/details/gtuieckwig.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gotoacloud.top/Article/details/gtwlokkojp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.tian-w.cn/Article/details/gtcijdaoqq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yongpay.top/Article/details/gtmmkhzxcy.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.9152youxi.cn/Article/details/gtywkgvbxm.html

Go:   // 手写 map[string][]T
来源：http://dali.zhengqikj.top/Article/details/gtsdremhtv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gaohongyu789.top/Article/details/gtauvygwpv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.wangshuangyany.cn/Article/details/gtnywcywnk.html

[D20] 统计每个元素出现次数
来源：http://dali.nanxinkj.top/Article/details/gtgioqhzrh.html

Py:   Counter(arr)
来源：http://dali.zhixingplan.top/Article/details/gtaethpohz.html

PHP:  array_count_values($arr);
来源：http://dali.guannengcc.top/Article/details/gtiyjktnau.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenzaomai.com/Article/details/gtutyqwnbw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.snrcjt.cn/Article/details/gtuwipjqhc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.wangdashe.top/Article/details/gtvzrdejko.html

Go:   // 手写 map[T]int
来源：http://dali.xuanzx.com/Article/details/gtisdutuec.html

Ruby: arr.tally
来源：http://dali.hongshengwenyu.top/Article/details/gtdpjgqoms.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.fzhhl.top/Article/details/gtgjeubsme.html

[D21] 判断是否包含某元素
来源：http://dali.dashuyun.cn/Article/details/gttsuaxjpz.html

Py:   x in arr
来源：http://dali.tian-w.cn/Article/details/gtywyhnpag.html

PHP:  in_array($x, $arr, true);
来源：http://dali.meibo888.top/Article/details/gtkcjxiwfj.html

JS:   arr.includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gtcjfzyzni.html

TS:   arr.includes(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtkcwintuh.html

Java: list.contains(x)
来源：http://dali.hywenlv.cn/Article/details/gtfprdgdwf.html

Go:   slices.Contains(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtjqjmmavo.html

Ruby: arr.include?(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtppvpvbtj.html

C#:   list.Contains(x)
来源：http://dali.jyoumei.cn/Article/details/gtiqiezkdm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hnqzz.top/Article/details/gtnmcwrdwm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.nwbrower.top/Article/details/gtdtqgmgvv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtghbymoxk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hfpthk.cn/Article/details/gtvuxiefqg.html

TS:   [...arr];
来源：http://dali.nwbrower.top/Article/details/gttijgqflp.html

Java: new ArrayList<>(list);
来源：http://dali.zhixingplan.top/Article/details/gtsdqlmghv.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.feifeiyinyue.top/Article/details/gtslqhnvyc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yueranfly.top/Article/details/gtrwajbxdp.html

C#:   new List<int>(list);
来源：http://dali.cucudq.cn/Article/details/gtzkyuxeuw.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gtwackarwh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtttauepkm.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtljrhfthx.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ydzc1.top/Article/details/gtoqcohtuu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hysaishi.cn/Article/details/gtywscbdde.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhiwuduotai.top/Article/details/gthvxgeejk.html

Go:   // 手写循环
来源：http://dali.zhengqikj.top/Article/details/gtzspohnvh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.guowangkeji.top/Article/details/gtkcncqeal.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yj20258.top/Article/details/gtdybsqsex.html

[D24] 字典 / Map 基本操作
来源：http://dali.jiagoushi.top/Article/details/gtbrxrlmcz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthaqlqrlo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.kuanghao11.cn/Article/details/gthuvhdajp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.316326.xyz/Article/details/gttlgkdexo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gtsszmvysd.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xuanzx.com/Article/details/gtjqgdrooe.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.0kj1m.cn/Article/details/gtvaawvnnw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.daria6918.cn/Article/details/gtzuqsyaja.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.feifeiyinyue.top/Article/details/gtbenovmej.html

[D25] Set 集合去重与交并差
来源：http://dali.yuanzhike.top/Article/details/gtkvlfacrm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinqigfzy.top/Article/details/gtkitqmbph.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cheryme.top/Article/details/gtynvjxurs.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jqgufenzy.top/Article/details/gtwmhxvzas.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cdnleiting.top/Article/details/gtbnwepvjp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.9152youxi.cn/Article/details/gtkklqrfjt.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hnxiangtu.top/Article/details/gtbhhwbfuk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtdwhqzjwx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.redwolf501.top/Article/details/gtgajiaadj.html

[D26] 数组转字符串
来源：http://dali.jyoumei.cn/Article/details/gtipdnkeks.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hnqzz.top/Article/details/gtpzwhafef.html

PHP:  implode(", ", $arr);
来源：http://dali.hywenlv.cn/Article/details/gttdhnisgd.html

JS:   arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gtdmolaaus.html

TS:   arr.join(", ")
来源：http://dali.ydzc1.top/Article/details/gtqwzmevhf.html

Java: String.join(", ", list)
来源：http://dali.yuanzhike.top/Article/details/gtjzdlubwn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtejjzalry.html

Ruby: arr.join(", ")
来源：http://dali.jiagoushi.top/Article/details/gtejdugftm.html

C#:   string.Join(", ", list)
来源：http://dali.shangyingyoupin.top/Article/details/gtllluqwjl.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtcoonvnph.html

E. 字符串处理
来源：http://dali.xylfe.cn/Article/details/gtcldpjwnm.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtyysjhumc.html

[E01] 拼接字符串
来源：http://dali.cheryme.top/Article/details/gtsijhsaqt.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gzhubu.top/Article/details/gtstrpegyf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jqgfzy.top/Article/details/gtxenrgomr.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yangfankeji.com/Article/details/gtzvoavsch.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.smart0.xyz/Article/details/gtufyaqqnc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yvedp.cn/Article/details/gtovkjcpsx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.aizwys.cn/Article/details/gtnkygcgdf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ppjwa.cn/Article/details/gtznbgdivy.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yuxming.cn/Article/details/gtfekkwpzs.html

[E02] 重复字符串
来源：http://dali.birdmap.top/Article/details/gtiyiuyaph.html

Py:   "ab" * 3
来源：http://dali.meibo888.top/Article/details/gtzsunfrgb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shuidangran.top/Article/details/gtexxbxadm.html

JS:   "ab".repeat(3)
来源：http://dali.snrcjt.cn/Article/details/gtucuzmfpu.html

TS:   "ab".repeat(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtiqybydpd.html

Java: "ab".repeat(3)
来源：http://dali.hongshengwenyu.top/Article/details/gttknpblvj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtwrmvvisi.html

Ruby: "ab" * 3
来源：http://dali.svipenyu.cn/Article/details/gtzftqqbjr.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yongpay.top/Article/details/gtgxebjqgs.html

[E03] 截取子串
来源：http://dali.wangshuangyany.cn/Article/details/gtvxcqdfbv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenjidiqi.icu/Article/details/gtkhhnuptk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gtnxbgirei.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yj202588.top/Article/details/gtngzhqjda.html

TS:   s.slice(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gtzucmrvhu.html

Java: s.substring(1, 4)
来源：http://dali.jyoumei.cn/Article/details/gtjhxsukie.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.kuanghao11.cn/Article/details/gtwijqmchl.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.daxiang520.top/Article/details/gtehhhuukr.html

C#:   s.Substring(1, 3)
来源：http://dali.pycfn.com/Article/details/gtowgxtjit.html

[E04] 查找子串位置
来源：http://dali.xinyue.icu/Article/details/gtfcmrtugq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cheryme.top/Article/details/gtmfduenyh.html

PHP:  strpos($s, "x");
来源：http://dali.redwolf501.top/Article/details/gtllggfhmu.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.snrcjt.cn/Article/details/gttnofzwdw.html

TS:   s.indexOf("x")
来源：http://dali.meibo888.top/Article/details/gtnzkqxcws.html

Java: s.indexOf("x")
来源：http://dali.ehwqpu.com/Article/details/gtatrpylof.html

Go:   strings.Index(s, "x")
来源：http://dali.zdqjudy.top/Article/details/gttyuchfgy.html

Ruby: s.index("x")
来源：http://dali.haohaochexian.top/Article/details/gtxpohnqat.html

C#:   s.IndexOf("x")
来源：http://dali.zhiwuduotai.top/Article/details/gtzqxqyqqp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hnxiangtu.top/Article/details/gtivkkuqcs.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gtgylzdslx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jqgfzy.top/Article/details/gtooxvrmry.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtfnuujviv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yuxming.cn/Article/details/gtrwnotjxj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zycfv.cn/Article/details/gtzkxewfgo.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cqqwz.cn/Article/details/gttbcacvyc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ehwqpu.com/Article/details/gtdfkecorj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ybcxt.top/Article/details/gtfmvtnssj.html

[E06] 替换子串
来源：http://dali.pengpengdd.cyou/Article/details/gtcqxtqalm.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.tian-w.cn/Article/details/gtmdhmfdpg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.9152youxi.cn/Article/details/gtqdhvvrbr.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtkkujxppx.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtndgptiza.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtlukepufb.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tian-w.cn/Article/details/gtyapvgjjj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtresaehwd.html

C#:   s.Replace("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gthdkbdvmo.html

[E07] 按分隔符拆分
来源：http://dali.yueranfly.top/Article/details/gtnbdecnhq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.nanxuanxn.top/Article/details/gtdkhvcxeb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinqigufen.top/Article/details/gtukyntidq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shangyingyoupin.top/Article/details/gtxvqhbjmq.html

TS:   s.split(",")
来源：http://dali.jianghu66.top/Article/details/gtovkswjzr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cashguo.top/Article/details/gtwjnvvsho.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.quarkkingdee.top/Article/details/gtldctszod.html

Ruby: s.split(",");  s.split
来源：http://dali.jinqigfzy.top/Article/details/gtbbpnehxp.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.fengsongda.top/Article/details/gtwpvjxqkh.html

[E08] 数组按分隔符合并
来源：http://dali.dianchejie.cn/Article/details/gtsfcdbbgi.html

Py:   ",".join(items)
来源：http://dali.yvedp.cn/Article/details/gtipnsutlf.html

PHP:  implode(",", $items);
来源：http://dali.xinyue.icu/Article/details/gtmqsrtyvd.html

JS:   items.join(",")
来源：http://dali.316326.xyz/Article/details/gtpncnaxhu.html

TS:   items.join(",")
来源：http://dali.bjfxy.top/Article/details/gtrzkmoimc.html

Java: String.join(",", items)
来源：http://dali.hysaishi.cn/Article/details/gtmnhgoavz.html

Go:   strings.Join(items, ",")
来源：http://dali.yanxiufei.cn/Article/details/gtkgqeggaq.html

Ruby: items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgaytrxyj.html

C#:   string.Join(",", items)
来源：http://dali.yj202588.top/Article/details/gtytloqjfp.html

[E09] 去除所有空白字符
来源：http://dali.chenlongwang.top/Article/details/gttxukqchb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhoulong.xyz/Article/details/gtjtrcfdoc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtdcspfgwa.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.quarkkingdee.top/Article/details/gtdvidvogq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xuanzx.com/Article/details/gtqwuctyfy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.fzhhl.top/Article/details/gtozcduhig.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.daria6918.cn/Article/details/gtgpqpjvdx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jyoumei.cn/Article/details/gtspymybzk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xziqi.cn/Article/details/gtqpcveyew.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinqigfzy.top/Article/details/gtwojfkvhj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.wangdashe.top/Article/details/gtzppmpwml.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cashguo.top/Article/details/gtsfnaamvt.html

JS:   "7".padStart(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gtrkxrljxk.html

TS:   "7".padStart(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gtujhwfsrf.html

Java: String.format("%03d", 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqhysfsst.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sysykeji.top/Article/details/gtolavqsyn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinqigufen.top/Article/details/gtmrgxjvvt.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cheryme.top/Article/details/gtfcewiflo.html

[E11] 反转字符串
来源：http://dali.zdqjudy.top/Article/details/gtwtmtoufn.html

Py:   s[::-1]
来源：http://dali.yuanzhike.top/Article/details/gtbhatuxgm.html

PHP:  strrev($s);
来源：http://dali.sysykeji.top/Article/details/gtztwnhodt.html

JS:   [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gtblgwdaha.html

TS:   [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gtfqhxmutq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jyoumei.cn/Article/details/gtvshttoqn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.tanke756.top/Article/details/gtnjkyuapq.html

Ruby: s.reverse
来源：http://dali.xuanzx.com/Article/details/gtjzwnccvb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.pengpengdd.cyou/Article/details/gtfhafsbvd.html

[E12] 统计某字符出现次数
来源：http://dali.feifeiyinyue.top/Article/details/gtgsfrvtiv.html

Py:   s.count("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvosoftmf.html

PHP:  substr_count($s, "a");
来源：http://dali.gotoacloud.top/Article/details/gtaxdqkvuh.html

JS:   s.split("a").length - 1
来源：http://dali.zdqjudy.top/Article/details/gtaxmzunyb.html

TS:   s.split("a").length - 1
来源：http://dali.zdqjudy.top/Article/details/gtiyemhjrh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.svipenyu.cn/Article/details/gtvyeztbfb.html

Go:   strings.Count(s, "a")
来源：http://dali.smart0.xyz/Article/details/gtsgqyqqfd.html

Ruby: s.count("a")
来源：http://dali.kuanghao11.cn/Article/details/gtngspwpln.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hnxiangtu.top/Article/details/gtlpaeptve.html

[E13] 逐字符遍历
来源：http://dali.snrcjt.cn/Article/details/gtpgtbegtm.html

Py:   for ch in s: print(ch)
来源：http://dali.dianchejie.cn/Article/details/gtpunsfdnm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jianghu66.top/Article/details/gtamamxdat.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258888.top/Article/details/gtzlfnrcmn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gtxktcfhdx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gtanynkjpi.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.bjfxy.top/Article/details/gtwnwhgvvm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.havefunace.top/Article/details/gtddfaufjm.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.9152youxi.cn/Article/details/gttzjqmccr.html

[E14] URL 编码与 Base64
来源：http://dali.yueranfly.top/Article/details/gttyhhtith.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.nanxinkj.top/Article/details/gtmthdhxzd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtelrcwjrc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj202588.top/Article/details/gtgbjwfpgk.html


<!-- 参考信息 -->