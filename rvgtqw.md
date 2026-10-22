代发 wailian999

Ruby: a + b;  a.concat(b)
来源：http://dali.aibaodan.cn/Article/details/gtoobmynpb.html

C#:   a.Concat(b).ToList()
来源：http://dali.bjfxy.top/Article/details/gtluewyrry.html

[D09] 排序（升序）
来源：http://dali.jinqigfzy.top/Article/details/gtcrsxhebj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dashuyun.cn/Article/details/gtygrnnhss.html

PHP:  sort($arr);
来源：http://dali.redwolf501.top/Article/details/gtdjoeomow.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gzhubu.top/Article/details/gtzqmpwlni.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yj20258888.top/Article/details/gtjyjbqkex.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jyoumei.cn/Article/details/gtlylfiuea.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtkhongfvk.html

Ruby: arr.sort
来源：http://dali.cashguo.top/Article/details/gtvfbtbfbb.html

C#:   list.Sort();
来源：http://dali.316326.xyz/Article/details/gtdnismhgg.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.tian-w.cn/Article/details/gtoxhknsij.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinqigfzy.top/Article/details/gtwdqmbdxs.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cashguo.top/Article/details/gtuisuofky.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ivvv.top/Article/details/gtdvwrchzm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sufxvd.cn/Article/details/gtqvpxdtov.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.redwolf501.top/Article/details/gtxposjbfq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.svipenyu.cn/Article/details/gtihrsgvzl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.chenlongwang.top/Article/details/gtjhyjreka.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yongpay.top/Article/details/gtdzsqczkd.html

[D11] 反转数组
来源：http://dali.daxiang520.top/Article/details/gtmfvphnzk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.tian-w.cn/Article/details/gtvlbkblxa.html

PHP:  array_reverse($arr);
来源：http://dali.hammf.cn/Article/details/gtdahwjaxf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdeytefak.html

TS:   [...arr].reverse();
来源：http://dali.smart0.xyz/Article/details/gtsukjaumi.html

Java: Collections.reverse(list);
来源：http://dali.chenjidiqi.icu/Article/details/gtlpevgklt.html

Go:   slices.Reverse(arr)
来源：http://dali.yj202588.top/Article/details/gtvklldnid.html

Ruby: arr.reverse
来源：http://dali.c1oappe.top/Article/details/gtfdfnrqbw.html

C#:   list.Reverse();
来源：http://dali.daria6918.cn/Article/details/gtakawdwuc.html

[D12] 查找元素下标
来源：http://dali.yuanzhike.top/Article/details/gtmmjhxosm.html

Py:   arr.index(x);  x in arr
来源：http://dali.yangfankeji.com/Article/details/gtiusmoxma.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cashguo.top/Article/details/gtfsjpkzfn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlygaptxm.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258.top/Article/details/gtuwcrigai.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cdnleiting.top/Article/details/gtwozpwyzs.html

Go:   slices.Index(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbfmvctgm.html

Ruby: arr.index(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtthllgrfr.html

C#:   list.IndexOf(x);
来源：http://dali.nanxinkj.top/Article/details/gteqiwmmcm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.snrcjt.cn/Article/details/gtcolibjcu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.fengsongda.top/Article/details/gtmufsourn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnqfudeva.html

JS:   arr.filter(x => x > 3)
来源：http://dali.pycfn.com/Article/details/gthfijwynm.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdjypsqzu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.tianlin.xyz/Article/details/gtmabxrvwb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.sysykeji.top/Article/details/gtqkzfeawr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yj202588.top/Article/details/gtjmnnynru.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jiagoushi.top/Article/details/gtafjrrgkq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.guowangkeji.top/Article/details/gthjxsfkwt.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yuanzhike.top/Article/details/gtpebsdixa.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jyoumei.cn/Article/details/gtljtqkirs.html

JS:   arr.map(x => x * 2)
来源：http://dali.jiagoushi.top/Article/details/gtuteqtgst.html

TS:   arr.map(x => x * 2)
来源：http://dali.jiagoushi.top/Article/details/gtvgajttgb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.c1oappe.top/Article/details/gtwlhbuoqk.html

Go:   // 手写循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtugbgxhnd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.meibo888.top/Article/details/gthrekdurr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtrvtveenb.html

[D15] 去重
来源：http://dali.ywan-chungtsiang.top/Article/details/gtehnfafbi.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.meibo888.top/Article/details/gtbndqovnx.html

PHP:  array_unique($arr);
来源：http://dali.iojbl.cn/Article/details/gtorvkftfq.html

JS:   [...new Set(arr)]
来源：http://dali.meibo888.top/Article/details/gtzxialdke.html

TS:   [...new Set(arr)]
来源：http://dali.xylfe.cn/Article/details/gtxojtijng.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jlsjyb.cn/Article/details/gtlxjargyk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.daxiang520.top/Article/details/gtbvmlooga.html

Ruby: arr.uniq
来源：http://dali.zhixingplan.top/Article/details/gtyzjahxak.html

C#:   list.Distinct().ToList()
来源：http://dali.yonumen.top/Article/details/gtlooiyxlw.html

[D16] 求和与平均值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlrpipabo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.svipenyu.cn/Article/details/gtuccfxbia.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.sysykeji.top/Article/details/gtnamzztlq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtfocnaayx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cdnleiting.top/Article/details/gtgccdaqmv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinghuilouyu.cn/Article/details/gttmzriqdn.html

Go:   // 手写循环累加
来源：http://dali.dashuyun.cn/Article/details/gtmqmntnxq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yuxming.cn/Article/details/gtmtpdrrbd.html

C#:   list.Sum();  list.Average()
来源：http://dali.yonumen.top/Article/details/gtztazcyzc.html

[D17] 最大值与最小值
来源：http://dali.quarkkingdee.top/Article/details/gtyskofnlk.html

Py:   max(arr);  min(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtxwgeziap.html

PHP:  max($arr);  min($arr);
来源：http://dali.c1oappe.top/Article/details/gtvpzjdzvr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.guowangkeji.top/Article/details/gtgbupmljo.html

TS:   Math.max(...arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtvpkfjtpq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjycgeexn.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.chenzaomai.com/Article/details/gtwxzcnder.html

Ruby: arr.max;  arr.min
来源：http://dali.hongshengwenyu.top/Article/details/gtgthnyxlc.html

C#:   list.Max();  list.Min()
来源：http://dali.iojbl.cn/Article/details/gtkqgzghfr.html

[D18] 扁平化嵌套数组
来源：http://dali.andypj.xyz/Article/details/gtaqamtrql.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sxryk.cn/Article/details/gtmkynsbfn.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gtbspdaxtu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.andypj.xyz/Article/details/gtuqmeolat.html

TS:   nested.flat();
来源：http://dali.zdqjudy.top/Article/details/gtjodbrlwb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sufxvd.cn/Article/details/gtepizwhwq.html

Go:   // 手写双层循环
来源：http://dali.shuidangran.top/Article/details/gtaisicyht.html

Ruby: nested.flatten
来源：http://dali.jiagoushi.top/Article/details/gtnchjiajr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhengqikj.top/Article/details/gtqlnstiwx.html

[D19] 按字段分组
来源：http://dali.hfpthk.cn/Article/details/gtjythjpdq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ehwqpu.com/Article/details/gtslqprgna.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ydzc1.top/Article/details/gtdrsmfdnt.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sweek.top/Article/details/gtabgzoxlj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jlsjyb.cn/Article/details/gttdcbjvyp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.wangdashe.top/Article/details/gtjseybkfj.html

Go:   // 手写 map[string][]T
来源：http://dali.xziqi.cn/Article/details/gtsgpqqhlc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jqgfzy.top/Article/details/gtodclbivi.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hongshengwenyu.top/Article/details/gtcrosxgdu.html

[D20] 统计每个元素出现次数
来源：http://dali.sxryk.cn/Article/details/gtqdpndoqp.html

Py:   Counter(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjxdfgirv.html

PHP:  array_count_values($arr);
来源：http://dali.tanke756.top/Article/details/gtzjcfgkvw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shzxlz.cn/Article/details/gtaduazudj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuanzhike.top/Article/details/gtebpapgey.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.meibo888.top/Article/details/gtdbbrfrfo.html

Go:   // 手写 map[T]int
来源：http://dali.guowangkeji.top/Article/details/gtiuwyaiis.html

Ruby: arr.tally
来源：http://dali.ppjwa.cn/Article/details/gtolemvcnb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hfpthk.cn/Article/details/gtmmnhscmc.html

[D21] 判断是否包含某元素
来源：http://dali.chenjidiqi.icu/Article/details/gtnvbswgnf.html

Py:   x in arr
来源：http://dali.c1oappe.top/Article/details/gtvrdgqdcl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xuetiantiany.cn/Article/details/gtdrocqhab.html

JS:   arr.includes(x)
来源：http://dali.gzhubu.top/Article/details/gtvzygiazs.html

TS:   arr.includes(x)
来源：http://dali.dashuyun.cn/Article/details/gtgprjromo.html

Java: list.contains(x)
来源：http://dali.9152youxi.cn/Article/details/gtkfyelyyw.html

Go:   slices.Contains(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtgmclhjeg.html

Ruby: arr.include?(x)
来源：http://dali.jyoumei.cn/Article/details/gtcqaqjwjw.html

C#:   list.Contains(x)
来源：http://dali.yj20258.top/Article/details/gthlqeenoz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zdqjudy.top/Article/details/gtmrkmihns.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.dianchejie.cn/Article/details/gtpjsmybka.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yvedp.cn/Article/details/gtbkoeabqm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gthvrolwva.html

TS:   [...arr];
来源：http://dali.jlsjyb.cn/Article/details/gtvmfgcahv.html

Java: new ArrayList<>(list);
来源：http://dali.yanxiufei.cn/Article/details/gthugzgxea.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.0kj1m.cn/Article/details/gttdxvgvon.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhiwuduotai.top/Article/details/gtfuoziypo.html

C#:   new List<int>(list);
来源：http://dali.feifeiyinyue.top/Article/details/gtoegnymwa.html

[D23] reduce 累积计算
来源：http://dali.chenzaomai.com/Article/details/gtrzvipgue.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shuidangran.top/Article/details/gthjbpszbt.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.iojbl.cn/Article/details/gtuxttxvzz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zycfv.cn/Article/details/gtepsditrd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhengqikj.top/Article/details/gtdbumxlcp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtasqepjoq.html

Go:   // 手写循环
来源：http://dali.shangyingyoupin.top/Article/details/gtmbvztqgi.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shanyushiyangtech.top/Article/details/gtldnqehfh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yongpay.top/Article/details/gtaketzvzs.html

[D24] 字典 / Map 基本操作
来源：http://dali.yuanzhike.top/Article/details/gtfdgeenmo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hongshengwenyu.top/Article/details/gtpebcqeff.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ehwqpu.com/Article/details/gtkqdelhrc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yj20258888.top/Article/details/gtbpinbadz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sxryk.cn/Article/details/gtgdihmbrl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gogol.net.cn/Article/details/gtrmhghzfr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yangfankeji.com/Article/details/gtoyiqcisu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ybcxt.top/Article/details/gtxazliiso.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ehwqpu.com/Article/details/gtfpmwzajz.html

[D25] Set 集合去重与交并差
来源：http://dali.kuanghao11.cn/Article/details/gtifosercf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shzxlz.cn/Article/details/gtuzryozmh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sysykeji.top/Article/details/gtnohmbvez.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hfpthk.cn/Article/details/gtvcsaxuaw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yangfankeji.com/Article/details/gtjiyegqoa.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.birdmap.top/Article/details/gtdoqbhenq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shuidangran.top/Article/details/gtaxahcvrg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zycfv.cn/Article/details/gtidjbaurx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shzxlz.cn/Article/details/gtmxwjkgdh.html

[D26] 数组转字符串
来源：http://dali.meibo888.top/Article/details/gtxoeznhva.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ehwqpu.com/Article/details/gtrubqdkyj.html

PHP:  implode(", ", $arr);
来源：http://dali.9152youxi.cn/Article/details/gtndnszlps.html

JS:   arr.join(", ")
来源：http://dali.gaohongyu789.top/Article/details/gtwxfrxdcg.html

TS:   arr.join(", ")
来源：http://dali.xuetiantiany.cn/Article/details/gtzjrwevwy.html

Java: String.join(", ", list)
来源：http://dali.aibaodan.cn/Article/details/gtikybbsrp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yuanzhike.top/Article/details/gtaqwvmuci.html

Ruby: arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gtsazkfrhg.html

C#:   string.Join(", ", list)
来源：http://dali.ybcxt.top/Article/details/gtehqmgoqf.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtpalwxtsd.html

E. 字符串处理
来源：http://dali.smart0.xyz/Article/details/gtcnzvrkxp.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtiwuarlzp.html

[E01] 拼接字符串
来源：http://dali.havefunace.top/Article/details/gthmolsinj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ivvv.top/Article/details/gtxelarlmq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.fzhhl.top/Article/details/gtzhhrvpuo.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnqzz.top/Article/details/gtkskvjbzf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yueranfly.top/Article/details/gtefhqcmpz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gogol.net.cn/Article/details/gtzzwtvfkr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.feifeiyinyue.top/Article/details/gtcrnhaczx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.haohaochexian.top/Article/details/gthrbcpxbz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtktuvxxoy.html

[E02] 重复字符串
来源：http://dali.xinyue.icu/Article/details/gtdufaidlw.html

Py:   "ab" * 3
来源：http://dali.birdmap.top/Article/details/gtgihoygbs.html

PHP:  str_repeat("ab", 3);
来源：http://dali.dashuyun.cn/Article/details/gthwbnhjyd.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gtwakzffyy.html

TS:   "ab".repeat(3)
来源：http://dali.yangfankeji.com/Article/details/gtxpdyjhzp.html

Java: "ab".repeat(3)
来源：http://dali.9152youxi.cn/Article/details/gtubpkpoza.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shuidangran.top/Article/details/gtsjvifsel.html

Ruby: "ab" * 3
来源：http://dali.feifeiyinyue.top/Article/details/gtniqpanjd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmqquchaa.html

[E03] 截取子串
来源：http://dali.cqqwz.cn/Article/details/gtkqptcpgp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yonumen.top/Article/details/gtsucgmqin.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gtikqydfhq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhengqikj.top/Article/details/gthczdovhq.html

TS:   s.slice(1, 4)
来源：http://dali.yongpay.top/Article/details/gtuhrepcha.html

Java: s.substring(1, 4)
来源：http://dali.xylfe.cn/Article/details/gttiqjjnpn.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gaohongyu789.top/Article/details/gtulidjrpa.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.wangdashe.top/Article/details/gtfgxlragh.html

C#:   s.Substring(1, 3)
来源：http://dali.iojbl.cn/Article/details/gtrukjnrwx.html

[E04] 查找子串位置
来源：http://dali.nanxuanxn.top/Article/details/gtrglqsjif.html

Py:   s.find("x");  s.index("x")
来源：http://dali.chenlongwang.top/Article/details/gtctlnvuhk.html

PHP:  strpos($s, "x");
来源：http://dali.ivvv.top/Article/details/gtyvebhrxz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jlsjyb.cn/Article/details/gtyibaxnvf.html

TS:   s.indexOf("x")
来源：http://dali.andypj.xyz/Article/details/gtdskosmqd.html

Java: s.indexOf("x")
来源：http://dali.smart0.xyz/Article/details/gtssoozomm.html

Go:   strings.Index(s, "x")
来源：http://dali.xylfe.cn/Article/details/gteivwgjjm.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gtylokjxkf.html

C#:   s.IndexOf("x")
来源：http://dali.dianchejie.cn/Article/details/gtesiffndz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.wangshuangyany.cn/Article/details/gtcjhrwcvv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gtqvtbfqpk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shanyushiyangtech.top/Article/details/gttxpduvkg.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yueranfly.top/Article/details/gtiqfkxhqm.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ppjwa.cn/Article/details/gtmkdjlqmk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zdqjudy.top/Article/details/gtiedjksyf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.mhx1999.top/Article/details/gtvxoxyezs.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.guowangkeji.top/Article/details/gtxayefjqf.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hongshengwenyu.top/Article/details/gtmmnuixbd.html

[E06] 替换子串
来源：http://dali.quarkkingdee.top/Article/details/gtmvqkufql.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.quarkkingdee.top/Article/details/gtzdyapqzo.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ivvv.top/Article/details/gtafqoogkd.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtemsuakfk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtkmndtfdj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtnjkzmcbp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqaavpked.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtpposedeo.html

C#:   s.Replace("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtcqmdxesh.html

[E07] 按分隔符拆分
来源：http://dali.feifeiyinyue.top/Article/details/gthfizldhm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.pengpengdd.cyou/Article/details/gtligtwfgq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jyoumei.cn/Article/details/gthxqlkvdh.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.tanke756.top/Article/details/gtyboazsbg.html

TS:   s.split(",")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjphcnlxz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sweek.top/Article/details/gtwoxnydts.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yuanzhike.top/Article/details/gtcgkczyxo.html

Ruby: s.split(",");  s.split
来源：http://dali.hammf.cn/Article/details/gtqegvyzjx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.bjfxy.top/Article/details/gtvrrgypky.html

[E08] 数组按分隔符合并
来源：http://dali.shangyingyoupin.top/Article/details/gtumlifvek.html

Py:   ",".join(items)
来源：http://dali.chenzaomai.com/Article/details/gtwdksaqwt.html

PHP:  implode(",", $items);
来源：http://dali.zhongyouzk.top/Article/details/gtyybommuh.html

JS:   items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gtqytxiopi.html

TS:   items.join(",")
来源：http://dali.sweek.top/Article/details/gtusztpxhj.html

Java: String.join(",", items)
来源：http://dali.xylfe.cn/Article/details/gtzccpnzpx.html

Go:   strings.Join(items, ",")
来源：http://dali.316326.xyz/Article/details/gtoasakcld.html

Ruby: items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gtrlfnvdjq.html

C#:   string.Join(",", items)
来源：http://dali.smart0.xyz/Article/details/gtlmkyqjer.html

[E09] 去除所有空白字符
来源：http://dali.yj20258888.top/Article/details/gtgrwrwutm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhongyouzk.top/Article/details/gtwcbxcwnr.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.daria6918.cn/Article/details/gtdgjsxatj.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cheryme.top/Article/details/gtvsnagnhi.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ivvv.top/Article/details/gtudjuniad.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.havefunace.top/Article/details/gtloimzkji.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.tanke756.top/Article/details/gtoalbpgll.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.mhx1999.top/Article/details/gtaemxycey.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.aizwys.cn/Article/details/gtxuqwbdxz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsokybdip.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gtxfukbmnf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jlsjyb.cn/Article/details/gttlomzydn.html

JS:   "7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gtljzrvocz.html

TS:   "7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gtnrtajkkx.html

Java: String.format("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gtuqgjtcia.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.birdmap.top/Article/details/gtqbvsarzs.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gtcishiihk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj20258888.top/Article/details/gtqgiblirz.html

[E11] 反转字符串
来源：http://dali.redwolf501.top/Article/details/gtydruseov.html

Py:   s[::-1]
来源：http://dali.yongpay.top/Article/details/gtvohwwfap.html

PHP:  strrev($s);
来源：http://dali.shuidangran.top/Article/details/gtleugcexi.html

JS:   [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gtkreijhzx.html

TS:   [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtihncnoct.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.havefunace.top/Article/details/gtrhcngktp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.wangshuangyany.cn/Article/details/gtzcgpobvq.html

Ruby: s.reverse
来源：http://dali.pycfn.com/Article/details/gteadswowh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.wangshuangyany.cn/Article/details/gtvmznhrnh.html

[E12] 统计某字符出现次数
来源：http://dali.vqdsnc.cn/Article/details/gtofbijpmd.html

Py:   s.count("a")
来源：http://dali.jinqigfzy.top/Article/details/gtovdqgrfk.html

PHP:  substr_count($s, "a");
来源：http://dali.cqqwz.cn/Article/details/gtlgkjafnx.html

JS:   s.split("a").length - 1
来源：http://dali.zhixingplan.top/Article/details/gtnjgukkuj.html

TS:   s.split("a").length - 1
来源：http://dali.cqqwz.cn/Article/details/gtxcwgcisc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xuanzx.com/Article/details/gtdjashlel.html

Go:   strings.Count(s, "a")
来源：http://dali.wangshuangyany.cn/Article/details/gtuurgzinq.html

Ruby: s.count("a")
来源：http://dali.dashuyun.cn/Article/details/gtkzeihxgd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jqgufenzy.top/Article/details/gtfwwqwzll.html

[E13] 逐字符遍历
来源：http://dali.jianghu66.top/Article/details/gtwmqornzo.html

Py:   for ch in s: print(ch)
来源：http://dali.hfpthk.cn/Article/details/gtawyauhag.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.wangdashe.top/Article/details/gtcvzacmjv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhixingplan.top/Article/details/gtpbefcbuk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dianchejie.cn/Article/details/gtypmmqegt.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsfkrsnig.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hammf.cn/Article/details/gtqjwseiox.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenlongwang.top/Article/details/gtlpukrrui.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shzxlz.cn/Article/details/gtiresduld.html

[E14] URL 编码与 Base64
来源：http://dali.jinghuilouyu.cn/Article/details/gtqckgotji.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.daria6918.cn/Article/details/gtaxzwnkvc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjxtmcaau.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gtjctfpdie.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.mhx1999.top/Article/details/gtqpcpjmpc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hongshengwenyu.top/Article/details/gtormnkqps.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinghuilouyu.cn/Article/details/gthvmyelzy.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hongshengwenyu.top/Article/details/gtpqgisskr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.dianchejie.cn/Article/details/gtlfeiwhhq.html

[E15] HTML 转义 / 反转义
来源：http://dali.havefunace.top/Article/details/gtbqovybsu.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj20258.top/Article/details/gtxescjuoq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yj20258888.top/Article/details/gthwodntks.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yuanzhike.top/Article/details/gtmqmobzny.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.aizwys.cn/Article/details/gteymbcwha.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.meibo888.top/Article/details/gtmleryjxm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgnvfxany.html


<!-- 参考信息 -->