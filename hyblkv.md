代发 wailian999

[D07] 切片 / 取子数组
来源：http://dali.jqgufenzy.top/Article/details/gtzcnrcpby.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zycfv.cn/Article/details/gtipuxhswk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.vqdsnc.cn/Article/details/gtrtqopflm.html

JS:   arr.slice(1, 4);
来源：http://dali.cheryme.top/Article/details/gtjpvhsmqx.html

TS:   arr.slice(1, 4);
来源：http://dali.jlsjyb.cn/Article/details/gtjuajodyc.html

Java: list.subList(1, 4);
来源：http://dali.cucudq.cn/Article/details/gtbgkcbayv.html

Go:   arr[1:4]
来源：http://dali.dianchejie.cn/Article/details/gtyicoxswc.html

Ruby: arr[1, 3]
来源：http://dali.cucudq.cn/Article/details/gtotofqnkv.html

C#:   list.GetRange(1, 3);
来源：http://dali.snrcjt.cn/Article/details/gtpcxzxnzs.html

[D08] 合并两个数组
来源：http://dali.smart0.xyz/Article/details/gtewtnzbjt.html

Py:   a + b;  a.extend(b)
来源：http://dali.bjfxy.top/Article/details/gtxhmducxu.html

PHP:  array_merge($a, $b);
来源：http://dali.zhengqikj.top/Article/details/gtqxuacsft.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenlongwang.top/Article/details/gttoxgfgma.html

TS:   [...a, ...b];
来源：http://dali.wangdashe.top/Article/details/gtjkhgagkv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.vqdsnc.cn/Article/details/gtvhhobnxu.html

Go:   append(a, b...)
来源：http://dali.hfpthk.cn/Article/details/gtsvxxlbvk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhoulong.xyz/Article/details/gtoksfcldk.html

C#:   a.Concat(b).ToList()
来源：http://dali.tanke756.top/Article/details/gtafhswkdq.html

[D09] 排序（升序）
来源：http://dali.yj20258.top/Article/details/gtuwemagqw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gtelsydaea.html

PHP:  sort($arr);
来源：http://dali.chenzaomai.com/Article/details/gteoqqsnbb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.redwolf501.top/Article/details/gtfgexunps.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.nanxinkj.top/Article/details/gtqlwelpoh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sysykeji.top/Article/details/gtzdpaapsc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.mhx1999.top/Article/details/gtialldqdr.html

Ruby: arr.sort
来源：http://dali.jlsjyb.cn/Article/details/gtehcrsqae.html

C#:   list.Sort();
来源：http://dali.xuanzx.com/Article/details/gtlwnrgdvv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.daxiang520.top/Article/details/gtitnkbvpm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hfpthk.cn/Article/details/gthqcjickt.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.meibo888.top/Article/details/gtjldlpybr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hywenlv.cn/Article/details/gtcwfwbzky.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sweek.top/Article/details/gtsvkmgwnc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.snrcjt.cn/Article/details/gteodgjwuj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.dashuyun.cn/Article/details/gtzyrfbtdm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.kuanghao11.cn/Article/details/gtvhkgldrs.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.daxiang520.top/Article/details/gtvjsedfev.html

[D11] 反转数组
来源：http://dali.wangshuangyany.cn/Article/details/gtvmjpjfuh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yanxiufei.cn/Article/details/gttzvvfsmz.html

PHP:  array_reverse($arr);
来源：http://dali.havefunace.top/Article/details/gthlnpcqww.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hywenlv.cn/Article/details/gtmaugthds.html

TS:   [...arr].reverse();
来源：http://dali.meibo888.top/Article/details/gtuuxjrfyh.html

Java: Collections.reverse(list);
来源：http://dali.shuidangran.top/Article/details/gtzwrybmue.html

Go:   slices.Reverse(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtlkdstzlq.html

Ruby: arr.reverse
来源：http://dali.yongpay.top/Article/details/gtyeqinvpn.html

C#:   list.Reverse();
来源：http://dali.daria6918.cn/Article/details/gtblhauexv.html

[D12] 查找元素下标
来源：http://dali.meibo888.top/Article/details/gttsbzwokt.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhoulong.xyz/Article/details/gtmvqmmuuj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.havefunace.top/Article/details/gtoeydmjap.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhoulong.xyz/Article/details/gtsmeksbej.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ppjwa.cn/Article/details/gthchnzjll.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yuxming.cn/Article/details/gturdojhjw.html

Go:   slices.Index(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtikxwysep.html

Ruby: arr.index(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtctnkcdaw.html

C#:   list.IndexOf(x);
来源：http://dali.quarkkingdee.top/Article/details/gtntpddlmo.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyzsjuqpf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.fzhhl.top/Article/details/gtvofdyhcu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nanxinkj.top/Article/details/gtokamferx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gaohongyu789.top/Article/details/gtwutohrpg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.wangdashe.top/Article/details/gtpmbmwphb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.haohaochexian.top/Article/details/gtkvwwlddm.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj20258.top/Article/details/gtuklkarta.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtuwszznou.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hysaishi.cn/Article/details/gthesjlieo.html

[D14] 映射转换（每个元素变形）
来源：http://dali.birdmap.top/Article/details/gteqjhaeyb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhixingplan.top/Article/details/gtcojfiuol.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtdxlqjjpl.html

JS:   arr.map(x => x * 2)
来源：http://dali.yj20258.top/Article/details/gtuawirdpj.html

TS:   arr.map(x => x * 2)
来源：http://dali.kuanghao11.cn/Article/details/gthwcgxuzj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yueranfly.top/Article/details/gtymepqgrb.html

Go:   // 手写循环
来源：http://dali.9152youxi.cn/Article/details/gtadkuqjbd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.aizwys.cn/Article/details/gtexbpmpgo.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.aizwys.cn/Article/details/gtcrlfocez.html

[D15] 去重
来源：http://dali.yvedp.cn/Article/details/gtegqkmmua.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ydzc1.top/Article/details/gtnlqtkczp.html

PHP:  array_unique($arr);
来源：http://dali.ppjwa.cn/Article/details/gtixzestgg.html

JS:   [...new Set(arr)]
来源：http://dali.yj20258888.top/Article/details/gtpwzjkgww.html

TS:   [...new Set(arr)]
来源：http://dali.svipenyu.cn/Article/details/gtvvlykvid.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jqgfzy.top/Article/details/gttrzdgsai.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shzxlz.cn/Article/details/gtwahsplnd.html

Ruby: arr.uniq
来源：http://dali.jqgufenzy.top/Article/details/gtiecekbqg.html

C#:   list.Distinct().ToList()
来源：http://dali.chenlongwang.top/Article/details/gtvifyulcr.html

[D16] 求和与平均值
来源：http://dali.shanyushiyangtech.top/Article/details/gtfglmesll.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zycfv.cn/Article/details/gthetisxie.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtkctslcmy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xylfe.cn/Article/details/gtlkwzwyzp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tianlin.xyz/Article/details/gtpihpftzw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.wangdashe.top/Article/details/gtxthyodrb.html

Go:   // 手写循环累加
来源：http://dali.cqqwz.cn/Article/details/gtdctrcsge.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.mhx1999.top/Article/details/gtxitleyhj.html

C#:   list.Sum();  list.Average()
来源：http://dali.aibaodan.cn/Article/details/gttsofcssr.html

[D17] 最大值与最小值
来源：http://dali.cucudq.cn/Article/details/gtzawoeqis.html

Py:   max(arr);  min(arr)
来源：http://dali.cdnleiting.top/Article/details/gtxfdbsnpc.html

PHP:  max($arr);  min($arr);
来源：http://dali.jlsjyb.cn/Article/details/gttmjukkra.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.aibaodan.cn/Article/details/gtsoyjolye.html

TS:   Math.max(...arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtcjuqquxe.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hfpthk.cn/Article/details/gtgrvbfnvk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtrknzxmaz.html

Ruby: arr.max;  arr.min
来源：http://dali.yonumen.top/Article/details/gtzlgtmaqo.html

C#:   list.Max();  list.Min()
来源：http://dali.jyoumei.cn/Article/details/gthelndefj.html

[D18] 扁平化嵌套数组
来源：http://dali.fzhhl.top/Article/details/gtznxrofle.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.smart0.xyz/Article/details/gtuktrpswh.html

PHP:  array_merge(...$nested);
来源：http://dali.fengsongda.top/Article/details/gtcwnygdny.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.kuanghao11.cn/Article/details/gtuqgfvrke.html

TS:   nested.flat();
来源：http://dali.fengsongda.top/Article/details/gtklfkwopi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.chenlongwang.top/Article/details/gtypnhxpwr.html

Go:   // 手写双层循环
来源：http://dali.hywenlv.cn/Article/details/gtllzmlohm.html

Ruby: nested.flatten
来源：http://dali.yj20258888.top/Article/details/gtpbevjifa.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtinchktqp.html

[D19] 按字段分组
来源：http://dali.aibaodan.cn/Article/details/gtwamupeoc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xinyue.icu/Article/details/gtryguzfrp.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.nwbrower.top/Article/details/gtuivrkmul.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinqigfzy.top/Article/details/gtgvpawltv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yanxiufei.cn/Article/details/gtfvigfvsg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xinyue.icu/Article/details/gtnlqfjcbi.html

Go:   // 手写 map[string][]T
来源：http://dali.sysykeji.top/Article/details/gtqfcbqtem.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinghuilouyu.cn/Article/details/gthyuorejc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.haohaochexian.top/Article/details/gtcjfxeozn.html

[D20] 统计每个元素出现次数
来源：http://dali.yuanzhike.top/Article/details/gtxgytxpga.html

Py:   Counter(arr)
来源：http://dali.hywenlv.cn/Article/details/gtizxzvqhj.html

PHP:  array_count_values($arr);
来源：http://dali.iojbl.cn/Article/details/gtrwmxledb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tianlin.xyz/Article/details/gtefrfkrvz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtblspeutw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jyoumei.cn/Article/details/gtvwmscmdm.html

Go:   // 手写 map[T]int
来源：http://dali.yongpay.top/Article/details/gtpynontyz.html

Ruby: arr.tally
来源：http://dali.gogol.net.cn/Article/details/gtfscnbhsy.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.redwolf501.top/Article/details/gtojxhgnog.html

[D21] 判断是否包含某元素
来源：http://dali.sufxvd.cn/Article/details/gtypimrwrm.html

Py:   x in arr
来源：http://dali.wangshuangyany.cn/Article/details/gtqdhvpbeh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.nanxinkj.top/Article/details/gthmbqcbnh.html

JS:   arr.includes(x)
来源：http://dali.zhixingplan.top/Article/details/gtxkpludbs.html

TS:   arr.includes(x)
来源：http://dali.hywenlv.cn/Article/details/gttsylugle.html

Java: list.contains(x)
来源：http://dali.redwolf501.top/Article/details/gtmrjfbaxv.html

Go:   slices.Contains(arr, x)
来源：http://dali.pycfn.com/Article/details/gtfgyiwzem.html

Ruby: arr.include?(x)
来源：http://dali.ehwqpu.com/Article/details/gtenvveeia.html

C#:   list.Contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gthbqoftvl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hammf.cn/Article/details/gtbonuytov.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yvedp.cn/Article/details/gtiupgcdjy.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.tian-w.cn/Article/details/gthjhoxntu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtfvoiqjyx.html

TS:   [...arr];
来源：http://dali.zhixingplan.top/Article/details/gtzxtpkxul.html

Java: new ArrayList<>(list);
来源：http://dali.jinqigfzy.top/Article/details/gtqpopiejz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gotoacloud.top/Article/details/gtdkmgcadw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.guannengcc.top/Article/details/gtnzyoqrcc.html

C#:   new List<int>(list);
来源：http://dali.fzhhl.top/Article/details/gtrajrlhoz.html

[D23] reduce 累积计算
来源：http://dali.hnqzz.top/Article/details/gtktxdidbr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtlxzawqyr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.316326.xyz/Article/details/gtsmkdtlyx.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmuwdmngv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gotoacloud.top/Article/details/gtdxrqxsrr.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuecwbsgp.html

Go:   // 手写循环
来源：http://dali.zhiwuduotai.top/Article/details/gtorbgjkfw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.redwolf501.top/Article/details/gtqufmswtm.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sweek.top/Article/details/gtmcjfmaxm.html

[D24] 字典 / Map 基本操作
来源：http://dali.shangyingyoupin.top/Article/details/gtatestalp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.pengpengdd.cyou/Article/details/gtruvynbxf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.iojbl.cn/Article/details/gtjobdxtvk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.chenlongwang.top/Article/details/gtaekabtga.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtbnuntyad.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xylfe.cn/Article/details/gtepfdenjx.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.kuanghao11.cn/Article/details/gtsjlizlcm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sysykeji.top/Article/details/gtjnjtpmse.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.guannengcc.top/Article/details/gtvnglmxei.html

[D25] Set 集合去重与交并差
来源：http://dali.zycfv.cn/Article/details/gtsehnjbcw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.c1oappe.top/Article/details/gteeuludjj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.smart0.xyz/Article/details/gtjzzkqjor.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.guowangkeji.top/Article/details/gtlrzfconk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hnqzz.top/Article/details/gtoijgcjtf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.316326.xyz/Article/details/gtzlkpmdce.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hysaishi.cn/Article/details/gtapqyogsp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.chenlongwang.top/Article/details/gtlyvzicdh.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.birdmap.top/Article/details/gtgtauioqp.html

[D26] 数组转字符串
来源：http://dali.sxryk.cn/Article/details/gtuowjvsuu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sxryk.cn/Article/details/gtobubbimn.html

PHP:  implode(", ", $arr);
来源：http://dali.nwbrower.top/Article/details/gtlxemymnu.html

JS:   arr.join(", ")
来源：http://dali.shangyingyoupin.top/Article/details/gttikrlgfn.html

TS:   arr.join(", ")
来源：http://dali.sufxvd.cn/Article/details/gtzctsvhio.html

Java: String.join(", ", list)
来源：http://dali.nwbrower.top/Article/details/gtszfpyrdm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.c1oappe.top/Article/details/gtbsrfrerc.html

Ruby: arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gtzwrwdqpz.html

C#:   string.Join(", ", list)
来源：http://dali.vqdsnc.cn/Article/details/gtuhibjyfn.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gttylzjeat.html

E. 字符串处理
来源：http://dali.mhx1999.top/Article/details/gtizxsounv.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtbnbxrywt.html

[E01] 拼接字符串
来源：http://dali.xziqi.cn/Article/details/gtbitgehtx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.snrcjt.cn/Article/details/gtklozkjly.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.feifeiyinyue.top/Article/details/gtnsgvldcl.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yanxiufei.cn/Article/details/gtshwrxnha.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sweek.top/Article/details/gtqcbgewku.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.daxiang520.top/Article/details/gthihfaxnx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.svipenyu.cn/Article/details/gtzyqawtjr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.iojbl.cn/Article/details/gtfgkpuwpc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtevvxfjxs.html

[E02] 重复字符串
来源：http://dali.snrcjt.cn/Article/details/gtwtloczsc.html

Py:   "ab" * 3
来源：http://dali.zhoulong.xyz/Article/details/gtfrrbkdid.html

PHP:  str_repeat("ab", 3);
来源：http://dali.havefunace.top/Article/details/gtqxwbxdmb.html

JS:   "ab".repeat(3)
来源：http://dali.havefunace.top/Article/details/gthyapffzl.html

TS:   "ab".repeat(3)
来源：http://dali.svipenyu.cn/Article/details/gtworgksyv.html

Java: "ab".repeat(3)
来源：http://dali.sweek.top/Article/details/gtefuhndzc.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtjmvwfrmw.html

Ruby: "ab" * 3
来源：http://dali.chenjidiqi.icu/Article/details/gtkdiarpck.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jqgufenzy.top/Article/details/gtrgswznqv.html

[E03] 截取子串
来源：http://dali.redwolf501.top/Article/details/gtehufoggh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shuidangran.top/Article/details/gtyipptohd.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gtcdphgpgl.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jlsjyb.cn/Article/details/gttqvuabcp.html

TS:   s.slice(1, 4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvouvnzsx.html

Java: s.substring(1, 4)
来源：http://dali.daxiang520.top/Article/details/gtgpxbgvpy.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.bjfxy.top/Article/details/gtmxavgxdq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jyoumei.cn/Article/details/gtzmnctsfa.html

C#:   s.Substring(1, 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtmmegwfqp.html

[E04] 查找子串位置
来源：http://dali.cdnleiting.top/Article/details/gtaplwvrie.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gaohongyu789.top/Article/details/gtejlpcaza.html

PHP:  strpos($s, "x");
来源：http://dali.sxryk.cn/Article/details/gtythvkzlc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hongshengwenyu.top/Article/details/gtgfhjlnkw.html

TS:   s.indexOf("x")
来源：http://dali.wangdashe.top/Article/details/gttpigpnxt.html

Java: s.indexOf("x")
来源：http://dali.smart0.xyz/Article/details/gtauaelmls.html

Go:   strings.Index(s, "x")
来源：http://dali.daria6918.cn/Article/details/gtzsjwjnbz.html

Ruby: s.index("x")
来源：http://dali.cqqwz.cn/Article/details/gtimsianwg.html

C#:   s.IndexOf("x")
来源：http://dali.shzxlz.cn/Article/details/gtduroufyo.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shzxlz.cn/Article/details/gtwpowsgpa.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.dashuyun.cn/Article/details/gtbspjlbcs.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sweek.top/Article/details/gtvpcooglj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnxiangtu.top/Article/details/gtyusiejal.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hnxiangtu.top/Article/details/gtedaymnhp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fengsongda.top/Article/details/gtjtqaevzq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zdqjudy.top/Article/details/gtiuvaojiy.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cashguo.top/Article/details/gtxidsdeou.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gtikkgpodl.html

[E06] 替换子串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaimlpiyp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmtqgptyn.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xziqi.cn/Article/details/gtscnjxxtn.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gtxpjzscbj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtaprmxwfe.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gtatawtwba.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.nanxinkj.top/Article/details/gtnilpxdxp.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.pycfn.com/Article/details/gtozqvzuiv.html

C#:   s.Replace("a", "b")
来源：http://dali.cashguo.top/Article/details/gtqgdjsimr.html

[E07] 按分隔符拆分
来源：http://dali.c1oappe.top/Article/details/gtpggheiiy.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shanyushiyangtech.top/Article/details/gtnbirmhjp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yj20258888.top/Article/details/gturfaiazz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yuxming.cn/Article/details/gtxwululqw.html

TS:   s.split(",")
来源：http://dali.tanke756.top/Article/details/gtonhmpxeo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.birdmap.top/Article/details/gtkvxhvkvl.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yueranfly.top/Article/details/gtmvsrayoq.html

Ruby: s.split(",");  s.split
来源：http://dali.zhoulong.xyz/Article/details/gtnlggkubv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjbsbzszd.html

[E08] 数组按分隔符合并
来源：http://dali.cucudq.cn/Article/details/gtkyidmluf.html

Py:   ",".join(items)
来源：http://dali.hysaishi.cn/Article/details/gtnwgjfzjz.html

PHP:  implode(",", $items);
来源：http://dali.nanxuanxn.top/Article/details/gtbwrfcrbr.html

JS:   items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gtykeyujsr.html

TS:   items.join(",")
来源：http://dali.gogol.net.cn/Article/details/gtlxjwttil.html

Java: String.join(",", items)
来源：http://dali.aizwys.cn/Article/details/gtxqsaahgb.html

Go:   strings.Join(items, ",")
来源：http://dali.vqdsnc.cn/Article/details/gtqnecqgft.html

Ruby: items.join(",")
来源：http://dali.shzxlz.cn/Article/details/gtjkmyibsv.html

C#:   string.Join(",", items)
来源：http://dali.pengpengdd.cyou/Article/details/gtecfwkjdv.html

[E09] 去除所有空白字符
来源：http://dali.havefunace.top/Article/details/gtycwjtydu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yangfankeji.com/Article/details/gtsyxafkqj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.0kj1m.cn/Article/details/gtvauxwqew.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ivvv.top/Article/details/gteckalcml.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.andypj.xyz/Article/details/gtlnkzfqqu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.bjfxy.top/Article/details/gtxeybvmrk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.dianchejie.cn/Article/details/gtvcfytxgn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.aibaodan.cn/Article/details/gtygveuhzc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xuetiantiany.cn/Article/details/gtwtjjsldi.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yonumen.top/Article/details/gtislovktz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.daxiang520.top/Article/details/gtrnawqfgi.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.kuanghao11.cn/Article/details/gtdlsjomlv.html

JS:   "7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gtqmyalnbt.html

TS:   "7".padStart(3, "0")
来源：http://dali.yuxming.cn/Article/details/gtnojlspqm.html

Java: String.format("%03d", 7)
来源：http://dali.zhiwuduotai.top/Article/details/gtdpgmxooi.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.pycfn.com/Article/details/gtxgwtxyiu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gtodmmuuyk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yuxming.cn/Article/details/gtifosdotp.html

[E11] 反转字符串
来源：http://dali.aibaodan.cn/Article/details/gtppeezabi.html

Py:   s[::-1]
来源：http://dali.fzhhl.top/Article/details/gtjfuyshmv.html

PHP:  strrev($s);
来源：http://dali.wangdashe.top/Article/details/gtqyktkanp.html

JS:   [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gttcfqwhof.html

TS:   [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gtlwepbbnm.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.fzhhl.top/Article/details/gtmkackjip.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.pengpengdd.cyou/Article/details/gtmynmdhqc.html

Ruby: s.reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjqkqvvhr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yuanzhike.top/Article/details/gtdubyirsf.html

[E12] 统计某字符出现次数
来源：http://dali.andypj.xyz/Article/details/gtxrknropf.html

Py:   s.count("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtedwtqexr.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxuanxn.top/Article/details/gtrvmnntxm.html

JS:   s.split("a").length - 1
来源：http://dali.hnqzz.top/Article/details/gtrezbsvch.html

TS:   s.split("a").length - 1
来源：http://dali.daxiang520.top/Article/details/gtorkrwmja.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.nanxinkj.top/Article/details/gtemkhautx.html

Go:   strings.Count(s, "a")
来源：http://dali.jiagoushi.top/Article/details/gtmhxsvgqz.html

Ruby: s.count("a")
来源：http://dali.yongpay.top/Article/details/gtdndjgxfz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.svipenyu.cn/Article/details/gtlvkrbvig.html

[E13] 逐字符遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrofrzfwm.html

Py:   for ch in s: print(ch)
来源：http://dali.kuanghao11.cn/Article/details/gtdyabdisw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.pycfn.com/Article/details/gtzuqlvinz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.snrcjt.cn/Article/details/gtbvtrfjbt.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.snrcjt.cn/Article/details/gtqxupcqqe.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.tanke756.top/Article/details/gtxtlcvmwo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ivvv.top/Article/details/gtsraykjsa.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.c1oappe.top/Article/details/gtcvvbvqgd.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yuanzhike.top/Article/details/gtkrhokdvi.html


<!-- 参考信息 -->