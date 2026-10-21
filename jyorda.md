代发 wailian999

C#:   list.GetRange(1, 3);
来源：http://dali.smart0.xyz/Article/details/gtbngjazpv.html

[D08] 合并两个数组
来源：http://dali.redwolf501.top/Article/details/gtozjcuaqf.html

Py:   a + b;  a.extend(b)
来源：http://dali.feifeiyinyue.top/Article/details/gtrrijmrgv.html

PHP:  array_merge($a, $b);
来源：http://dali.ppjwa.cn/Article/details/gtsszzyhnk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jlsjyb.cn/Article/details/gtjynfpxrw.html

TS:   [...a, ...b];
来源：http://dali.yonumen.top/Article/details/gtcgdfbvsj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.aibaodan.cn/Article/details/gtdthijpvi.html

Go:   append(a, b...)
来源：http://dali.jianghu66.top/Article/details/gtahuonfdo.html

Ruby: a + b;  a.concat(b)
来源：http://dali.chenlongwang.top/Article/details/gtwmaofvwn.html

C#:   a.Concat(b).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtkhskaevg.html

[D09] 排序（升序）
来源：http://dali.wangshuangyany.cn/Article/details/gtdiruwabo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fzhhl.top/Article/details/gtixdvgtyd.html

PHP:  sort($arr);
来源：http://dali.iojbl.cn/Article/details/gtmyttjpic.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ydzc1.top/Article/details/gtooyfytgj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.chenzaomai.com/Article/details/gteqjnubzr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.bjfxy.top/Article/details/gtjwoelsbf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jianghu66.top/Article/details/gthuxukzdv.html

Ruby: arr.sort
来源：http://dali.fzhhl.top/Article/details/gtpfzimcsl.html

C#:   list.Sort();
来源：http://dali.meibo888.top/Article/details/gtdoohnyvq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtagcmekyh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sxryk.cn/Article/details/gtwzvfsmvw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.redwolf501.top/Article/details/gtlwxhhwqn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yueranfly.top/Article/details/gtxznsdcfd.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuanzx.com/Article/details/gtzhnkpbks.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gogol.net.cn/Article/details/gtoxfidvny.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zycfv.cn/Article/details/gtbpijgobh.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.wangshuangyany.cn/Article/details/gtwgazwzuq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.andypj.xyz/Article/details/gtlxfvflug.html

[D11] 反转数组
来源：http://dali.pengpengdd.cyou/Article/details/gtnzbapwzy.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.gotoacloud.top/Article/details/gtusdmkehe.html

PHP:  array_reverse($arr);
来源：http://dali.aibaodan.cn/Article/details/gtnkltdixh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zdqjudy.top/Article/details/gtyejskzqi.html

TS:   [...arr].reverse();
来源：http://dali.sweek.top/Article/details/gtozilwzue.html

Java: Collections.reverse(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkgwluctf.html

Go:   slices.Reverse(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtgarxcgmj.html

Ruby: arr.reverse
来源：http://dali.tian-w.cn/Article/details/gtxrbhgfuu.html

C#:   list.Reverse();
来源：http://dali.hywenlv.cn/Article/details/gtjmnqikwc.html

[D12] 查找元素下标
来源：http://dali.jiagoushi.top/Article/details/gtiihzmlnd.html

Py:   arr.index(x);  x in arr
来源：http://dali.mhx1999.top/Article/details/gtiumkhunn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cheryme.top/Article/details/gtaudkvcls.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aibaodan.cn/Article/details/gtyadjreld.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jyoumei.cn/Article/details/gtnhxblqkb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.redwolf501.top/Article/details/gtnzhizytf.html

Go:   slices.Index(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gthvbsxgqy.html

Ruby: arr.index(x)
来源：http://dali.jianghu66.top/Article/details/gtpbwhbftf.html

C#:   list.IndexOf(x);
来源：http://dali.feifeiyinyue.top/Article/details/gtyobrbsza.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yuxming.cn/Article/details/gtziurbsfd.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shzxlz.cn/Article/details/gtxukvwpag.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jyoumei.cn/Article/details/gtvsuizsld.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gogol.net.cn/Article/details/gtziqubwbe.html

TS:   arr.filter(x => x > 3)
来源：http://dali.daxiang520.top/Article/details/gtbomnlgcx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zycfv.cn/Article/details/gtjgoyrwuq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nwbrower.top/Article/details/gtjtccnmjv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hnqzz.top/Article/details/gtmksjfjqv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.fzhhl.top/Article/details/gtschbqsqq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj20258888.top/Article/details/gtmavivwva.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ydzc1.top/Article/details/gtnmijfvrn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hywenlv.cn/Article/details/gtgnfxnlju.html

JS:   arr.map(x => x * 2)
来源：http://dali.aibaodan.cn/Article/details/gtvxmdbbbr.html

TS:   arr.map(x => x * 2)
来源：http://dali.yuanzhike.top/Article/details/gtylbmvbjh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.chenzaomai.com/Article/details/gtoitowrly.html

Go:   // 手写循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtixxmvciv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.wangdashe.top/Article/details/gtugcwycbc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.dianchejie.cn/Article/details/gttevlkcdb.html

[D15] 去重
来源：http://dali.cdnleiting.top/Article/details/gtstvlyvra.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shuidangran.top/Article/details/gtbxwyafgz.html

PHP:  array_unique($arr);
来源：http://dali.cheryme.top/Article/details/gtvvutagta.html

JS:   [...new Set(arr)]
来源：http://dali.hongshengwenyu.top/Article/details/gtgzzpzlkr.html

TS:   [...new Set(arr)]
来源：http://dali.fengsongda.top/Article/details/gtkjgnurtm.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.aibaodan.cn/Article/details/gtfkhwemri.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.9152youxi.cn/Article/details/gtdlwwbtva.html

Ruby: arr.uniq
来源：http://dali.yuanzhike.top/Article/details/gtdinqhfrv.html

C#:   list.Distinct().ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtsvzabrhr.html

[D16] 求和与平均值
来源：http://dali.xziqi.cn/Article/details/gtdvtihdkw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqoufhwwb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtysxwzing.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guannengcc.top/Article/details/gtbiicdfht.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yangfankeji.com/Article/details/gtknfobqck.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hnxiangtu.top/Article/details/gtybomoonz.html

Go:   // 手写循环累加
来源：http://dali.cqqwz.cn/Article/details/gtaqsccrml.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.daxiang520.top/Article/details/gtvqbdgnnn.html

C#:   list.Sum();  list.Average()
来源：http://dali.sxryk.cn/Article/details/gtrnmmzjsn.html

[D17] 最大值与最小值
来源：http://dali.yueranfly.top/Article/details/gthdnpiokb.html

Py:   max(arr);  min(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmwuvfumo.html

PHP:  max($arr);  min($arr);
来源：http://dali.redwolf501.top/Article/details/gttmjkpgos.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhoulong.xyz/Article/details/gtoelsomci.html

TS:   Math.max(...arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxrloqihi.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.tian-w.cn/Article/details/gtwowqnequ.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtztqmarhc.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gtkgmdxyet.html

C#:   list.Max();  list.Min()
来源：http://dali.cqqwz.cn/Article/details/gtgshcufjx.html

[D18] 扁平化嵌套数组
来源：http://dali.smart0.xyz/Article/details/gtrzigoldw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinqigufen.top/Article/details/gtesyqmbew.html

PHP:  array_merge(...$nested);
来源：http://dali.shanyushiyangtech.top/Article/details/gtgegpwfua.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shangyingyoupin.top/Article/details/gtbzdqesjx.html

TS:   nested.flat();
来源：http://dali.sufxvd.cn/Article/details/gtuayprgvb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yuxming.cn/Article/details/gtftlppxjq.html

Go:   // 手写双层循环
来源：http://dali.aibaodan.cn/Article/details/gtgaxuddml.html

Ruby: nested.flatten
来源：http://dali.jiagoushi.top/Article/details/gtqkopirwf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.tanke756.top/Article/details/gtbvjgxuhw.html

[D19] 按字段分组
来源：http://dali.jianghu66.top/Article/details/gtxtisllbp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.tian-w.cn/Article/details/gtvpyhkppy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.smart0.xyz/Article/details/gtxqppcpyq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.iojbl.cn/Article/details/gtaeywbxlu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.quarkkingdee.top/Article/details/gtedgppwib.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ydzc1.top/Article/details/gtarhsnchg.html

Go:   // 手写 map[string][]T
来源：http://dali.hywenlv.cn/Article/details/gtzmbhrusz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.chenlongwang.top/Article/details/gthvtdzfrc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shangyingyoupin.top/Article/details/gteaneyofg.html

[D20] 统计每个元素出现次数
来源：http://dali.yangfankeji.com/Article/details/gtvkcckzdk.html

Py:   Counter(arr)
来源：http://dali.yj20258.top/Article/details/gtoptwzjzu.html

PHP:  array_count_values($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtxwlcvblt.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xziqi.cn/Article/details/gtdgzfmqmy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.haohaochexian.top/Article/details/gtmdncnhev.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhongyouzk.top/Article/details/gtuevqbfqd.html

Go:   // 手写 map[T]int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbgoycwuc.html

Ruby: arr.tally
来源：http://dali.0kj1m.cn/Article/details/gtnrqdhwkd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hammf.cn/Article/details/gtvwjgmqba.html

[D21] 判断是否包含某元素
来源：http://dali.guowangkeji.top/Article/details/gtdnsagiai.html

Py:   x in arr
来源：http://dali.hywenlv.cn/Article/details/gtqgtpazwu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.chenlongwang.top/Article/details/gtfylxwyjy.html

JS:   arr.includes(x)
来源：http://dali.c1oappe.top/Article/details/gtuxrpbemn.html

TS:   arr.includes(x)
来源：http://dali.haohaochexian.top/Article/details/gtzdyuiseu.html

Java: list.contains(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtfdpzcwzb.html

Go:   slices.Contains(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtgcsatcrq.html

Ruby: arr.include?(x)
来源：http://dali.yonumen.top/Article/details/gtmeioktvp.html

C#:   list.Contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gtwbjbsrnd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.mhx1999.top/Article/details/gtuzddjzao.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cqqwz.cn/Article/details/gtadumfovg.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.316326.xyz/Article/details/gtxcirwqaw.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenzaomai.com/Article/details/gtzpfhxcog.html

TS:   [...arr];
来源：http://dali.pengpengdd.cyou/Article/details/gtdlhllwvh.html

Java: new ArrayList<>(list);
来源：http://dali.meibo888.top/Article/details/gtxamuvsvx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinqigufen.top/Article/details/gtmllrqgvs.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gotoacloud.top/Article/details/gtbeeordfm.html

C#:   new List<int>(list);
来源：http://dali.yj20258888.top/Article/details/gtytnlsdps.html

[D23] reduce 累积计算
来源：http://dali.sweek.top/Article/details/gtkgqlxgxl.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jyoumei.cn/Article/details/gtqivokwkd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.svipenyu.cn/Article/details/gtlxrfkjpp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.havefunace.top/Article/details/gtabitpvml.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtgeybndxc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhiwuduotai.top/Article/details/gtvermpuul.html

Go:   // 手写循环
来源：http://dali.haohaochexian.top/Article/details/gtdfiknwcy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.316326.xyz/Article/details/gtmpmuiadn.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sufxvd.cn/Article/details/gtvjwpvusr.html

[D24] 字典 / Map 基本操作
来源：http://dali.yongpay.top/Article/details/gtdxfsdgdj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxehrurta.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hammf.cn/Article/details/gtvpxbjuav.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.chenlongwang.top/Article/details/gtpxmffxzb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtokowaeke.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yueranfly.top/Article/details/gtfslxcoft.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtunuglaci.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xinyue.icu/Article/details/gtnmtaoqeu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.havefunace.top/Article/details/gtdslqvlhs.html

[D25] Set 集合去重与交并差
来源：http://dali.hysaishi.cn/Article/details/gtbavmmucc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jiagoushi.top/Article/details/gtoplqfrvh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.kuanghao11.cn/Article/details/gtejkuickx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzvooggzc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jlsjyb.cn/Article/details/gtpgzlvhgq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxpqgzvab.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjzldolaa.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.aibaodan.cn/Article/details/gtgijrvxox.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.daxiang520.top/Article/details/gtplvdsljl.html

[D26] 数组转字符串
来源：http://dali.zhoulong.xyz/Article/details/gtkgcpszkz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.wangshuangyany.cn/Article/details/gtaeuloivm.html

PHP:  implode(", ", $arr);
来源：http://dali.daxiang520.top/Article/details/gtvrjrtjwx.html

JS:   arr.join(", ")
来源：http://dali.316326.xyz/Article/details/gtvgzaleob.html

TS:   arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gtykpojche.html

Java: String.join(", ", list)
来源：http://dali.hongshengwenyu.top/Article/details/gtlwycdlzu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.bjfxy.top/Article/details/gtxxfrkuju.html

Ruby: arr.join(", ")
来源：http://dali.0kj1m.cn/Article/details/gtpcomgqjg.html

C#:   string.Join(", ", list)
来源：http://dali.zhixingplan.top/Article/details/gtakukmnsw.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmfyvudzm.html

E. 字符串处理
来源：http://dali.haohaochexian.top/Article/details/gtwdesiika.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjmkeklpc.html

[E01] 拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gttxeivhdw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.aibaodan.cn/Article/details/gtsqocixai.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlzndsahx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigfzy.top/Article/details/gtqfbaszkj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.havefunace.top/Article/details/gtefknclua.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ivvv.top/Article/details/gthulhhzgk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.pycfn.com/Article/details/gtlszmhtms.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.andypj.xyz/Article/details/gtorymebcl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtwvalessc.html

[E02] 重复字符串
来源：http://dali.yj20258888.top/Article/details/gtjyboswmr.html

Py:   "ab" * 3
来源：http://dali.feifeiyinyue.top/Article/details/gtqfcgzsod.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtvbwrjwnq.html

JS:   "ab".repeat(3)
来源：http://dali.jinqigfzy.top/Article/details/gtqjrczvmo.html

TS:   "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gtcsvcwnpm.html

Java: "ab".repeat(3)
来源：http://dali.zhixingplan.top/Article/details/gtolwbayrl.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiijiuovy.html

Ruby: "ab" * 3
来源：http://dali.cashguo.top/Article/details/gtbrmcprhz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jianghu66.top/Article/details/gtndskoipr.html

[E03] 截取子串
来源：http://dali.jinqigufen.top/Article/details/gtefbqklfy.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cashguo.top/Article/details/gtbxzqttjr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gtovakacaw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.smart0.xyz/Article/details/gtnefikmty.html

TS:   s.slice(1, 4)
来源：http://dali.yj20258.top/Article/details/gtkehlqbzo.html

Java: s.substring(1, 4)
来源：http://dali.hnxiangtu.top/Article/details/gthxfgljkh.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.tian-w.cn/Article/details/gtwjpplsns.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ivvv.top/Article/details/gttcereubz.html

C#:   s.Substring(1, 3)
来源：http://dali.sufxvd.cn/Article/details/gtgquitbrq.html

[E04] 查找子串位置
来源：http://dali.yonumen.top/Article/details/gtfhctodpx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhixingplan.top/Article/details/gtxqafahdf.html

PHP:  strpos($s, "x");
来源：http://dali.yanxiufei.cn/Article/details/gtmnaefond.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ydzc1.top/Article/details/gttnunenmw.html

TS:   s.indexOf("x")
来源：http://dali.zhiwuduotai.top/Article/details/gtrrlancfb.html

Java: s.indexOf("x")
来源：http://dali.jqgufenzy.top/Article/details/gtnfoxdasf.html

Go:   strings.Index(s, "x")
来源：http://dali.shangyingyoupin.top/Article/details/gtztqnzklx.html

Ruby: s.index("x")
来源：http://dali.meibo888.top/Article/details/gtzcieqkej.html

C#:   s.IndexOf("x")
来源：http://dali.jianghu66.top/Article/details/gtubsplfir.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ydzc1.top/Article/details/gtrxiidbjh.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zycfv.cn/Article/details/gtcmvbyuba.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.fzhhl.top/Article/details/gtmxckysni.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fzhhl.top/Article/details/gtoinrbuex.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ydzc1.top/Article/details/gtxbekvpkm.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gaohongyu789.top/Article/details/gttkhcyauz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yanxiufei.cn/Article/details/gtwostiqry.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jlsjyb.cn/Article/details/gtilbmesuf.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.andypj.xyz/Article/details/gtxclxnftu.html

[E06] 替换子串
来源：http://dali.yongpay.top/Article/details/gtcysyzeuy.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtmuqncxli.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jlsjyb.cn/Article/details/gterhqdvcv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtnwdqjurp.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gtfjqahyau.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtiwkxishx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xinyue.icu/Article/details/gtgulgpaol.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtgpmljhfq.html

C#:   s.Replace("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtxlhjcnnt.html

[E07] 按分隔符拆分
来源：http://dali.shuidangran.top/Article/details/gtlahxlype.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cqqwz.cn/Article/details/gtwrtousiq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hnqzz.top/Article/details/gtiwidjuge.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.andypj.xyz/Article/details/gtweqefghn.html

TS:   s.split(",")
来源：http://dali.fengsongda.top/Article/details/gtsxvycnbl.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.nwbrower.top/Article/details/gtmajqjdqz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yuanzhike.top/Article/details/gthjhzjgsp.html

Ruby: s.split(",");  s.split
来源：http://dali.gaohongyu789.top/Article/details/gtbaseettb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cucudq.cn/Article/details/gtgstkrjhu.html

[E08] 数组按分隔符合并
来源：http://dali.meibo888.top/Article/details/gtcizorkrr.html

Py:   ",".join(items)
来源：http://dali.iojbl.cn/Article/details/gtyrvuhoxs.html

PHP:  implode(",", $items);
来源：http://dali.xinyue.icu/Article/details/gtuwemldrh.html

JS:   items.join(",")
来源：http://dali.andypj.xyz/Article/details/gtwgtxtyjc.html

TS:   items.join(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtehhqtzhe.html

Java: String.join(",", items)
来源：http://dali.hnxiangtu.top/Article/details/gtkcyrsebh.html

Go:   strings.Join(items, ",")
来源：http://dali.havefunace.top/Article/details/gtimbzqtqd.html

Ruby: items.join(",")
来源：http://dali.daria6918.cn/Article/details/gtuhrzpmho.html

C#:   string.Join(",", items)
来源：http://dali.ehwqpu.com/Article/details/gtzewcpqjp.html

[E09] 去除所有空白字符
来源：http://dali.zycfv.cn/Article/details/gtqqlzljvb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cheryme.top/Article/details/gtsvznbnjd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.iojbl.cn/Article/details/gtpulhfluq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cucudq.cn/Article/details/gtedwqjhjs.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.316326.xyz/Article/details/gtgwiuqdkc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cheryme.top/Article/details/gtkcbmyeoe.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.dashuyun.cn/Article/details/gtvxwwvvyt.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.wangdashe.top/Article/details/gtqlarejxa.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.kuanghao11.cn/Article/details/gtajlolepq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.dianchejie.cn/Article/details/gtbpktpdbx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jqgufenzy.top/Article/details/gtytumfgqn.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hywenlv.cn/Article/details/gtfjncmksk.html

JS:   "7".padStart(3, "0")
来源：http://dali.andypj.xyz/Article/details/gtgugjgawf.html

TS:   "7".padStart(3, "0")
来源：http://dali.iojbl.cn/Article/details/gthcnzvymo.html

Java: String.format("%03d", 7)
来源：http://dali.mhx1999.top/Article/details/gtipdgzoae.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gtpwqxcphl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gtyjjmyaak.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yanxiufei.cn/Article/details/gtubgpnjmy.html

[E11] 反转字符串
来源：http://dali.iojbl.cn/Article/details/gtbviapjbe.html

Py:   s[::-1]
来源：http://dali.zdqjudy.top/Article/details/gtehumhhov.html

PHP:  strrev($s);
来源：http://dali.zhongyouzk.top/Article/details/gtecvgcnlt.html

JS:   [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gtevwsdaon.html

TS:   [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gtawmfcnvb.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.guannengcc.top/Article/details/gtnyulvdej.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yuxming.cn/Article/details/gtvcnmsxsg.html

Ruby: s.reverse
来源：http://dali.jiagoushi.top/Article/details/gtmkglpmhz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gogol.net.cn/Article/details/gtimmjjebv.html

[E12] 统计某字符出现次数
来源：http://dali.aizwys.cn/Article/details/gtypjnsryb.html

Py:   s.count("a")
来源：http://dali.0kj1m.cn/Article/details/gtdzbdydpj.html

PHP:  substr_count($s, "a");
来源：http://dali.yanxiufei.cn/Article/details/gtgnbswixe.html

JS:   s.split("a").length - 1
来源：http://dali.tian-w.cn/Article/details/gtaqjpmpet.html

TS:   s.split("a").length - 1
来源：http://dali.sweek.top/Article/details/gtgutuchqy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.haohaochexian.top/Article/details/gtwztcogcq.html

Go:   strings.Count(s, "a")
来源：http://dali.xuanzx.com/Article/details/gtbnkyovfo.html

Ruby: s.count("a")
来源：http://dali.ppjwa.cn/Article/details/gtfcxlwjsv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yuxming.cn/Article/details/gtckhkeeka.html

[E13] 逐字符遍历
来源：http://dali.c1oappe.top/Article/details/gtmqhglmnh.html

Py:   for ch in s: print(ch)
来源：http://dali.hongshengwenyu.top/Article/details/gtfptkacdr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gtindxpdfm.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gtenemgwud.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxinkj.top/Article/details/gtfhlzmidj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.0kj1m.cn/Article/details/gtcgrglqny.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sxryk.cn/Article/details/gtlqsoenxu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gogol.net.cn/Article/details/gtjivbgnia.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.svipenyu.cn/Article/details/gtvvhylelz.html

[E14] URL 编码与 Base64
来源：http://dali.daria6918.cn/Article/details/gtknnhekhg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xziqi.cn/Article/details/gtkxdbirig.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.guannengcc.top/Article/details/gttbqkfhba.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gtfmrlnfvu.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hywenlv.cn/Article/details/gtfiseavcq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.birdmap.top/Article/details/gtsqptxhhb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ivvv.top/Article/details/gtdkgwutdk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.tian-w.cn/Article/details/gtobvllsfy.html


<!-- 参考信息 -->