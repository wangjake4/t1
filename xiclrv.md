代发 wailian999

Ruby: a + b;  a.concat(b)
来源：http://dali.hnqzz.top/Article/details/gtrzrstowk.html

C#:   a.Concat(b).ToList()
来源：http://dali.svipenyu.cn/Article/details/gttqpwbrqi.html

[D09] 排序（升序）
来源：http://dali.xylfe.cn/Article/details/gtoyufmjjo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ehwqpu.com/Article/details/gtinoqenwx.html

PHP:  sort($arr);
来源：http://dali.ybcxt.top/Article/details/gtwuphcxaf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.9152youxi.cn/Article/details/gteodeafwd.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinqigufen.top/Article/details/gtuujabgig.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jqgufenzy.top/Article/details/gttyrnzpoz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.birdmap.top/Article/details/gtekgdimpx.html

Ruby: arr.sort
来源：http://dali.yanxiufei.cn/Article/details/gtdoohxpmd.html

C#:   list.Sort();
来源：http://dali.daria6918.cn/Article/details/gtahrvsmqa.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.wangdashe.top/Article/details/gtynzwvecm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.birdmap.top/Article/details/gthpjetyum.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yonumen.top/Article/details/gtjkdbagih.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenlongwang.top/Article/details/gtgatmatuz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xylfe.cn/Article/details/gtrdgmvhui.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.mhx1999.top/Article/details/gttvbordre.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ybcxt.top/Article/details/gtbwmoeseh.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.wangdashe.top/Article/details/gtjwvsmxju.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sxryk.cn/Article/details/gtxjnpsgtj.html

[D11] 反转数组
来源：http://dali.yj20258888.top/Article/details/gtnctlclpy.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shuidangran.top/Article/details/gtlavvebgd.html

PHP:  array_reverse($arr);
来源：http://dali.hnqzz.top/Article/details/gtvkswcdun.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yuxming.cn/Article/details/gtmeyqamha.html

TS:   [...arr].reverse();
来源：http://dali.hammf.cn/Article/details/gtrzvyumgl.html

Java: Collections.reverse(list);
来源：http://dali.c1oappe.top/Article/details/gtejexahso.html

Go:   slices.Reverse(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtsmrmhqnd.html

Ruby: arr.reverse
来源：http://dali.daxiang520.top/Article/details/gtydncapkl.html

C#:   list.Reverse();
来源：http://dali.jqgufenzy.top/Article/details/gtawnndpwu.html

[D12] 查找元素下标
来源：http://dali.svipenyu.cn/Article/details/gtzueekuct.html

Py:   arr.index(x);  x in arr
来源：http://dali.cdnleiting.top/Article/details/gtjublebyb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sysykeji.top/Article/details/gtjiqqhroa.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xziqi.cn/Article/details/gtivruyeno.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.smart0.xyz/Article/details/gtjfqopdza.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jiagoushi.top/Article/details/gtaayxmqyi.html

Go:   slices.Index(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtmdzvbkat.html

Ruby: arr.index(x)
来源：http://dali.hnqzz.top/Article/details/gtqyygepoa.html

C#:   list.IndexOf(x);
来源：http://dali.jinqigufen.top/Article/details/gtetdpcmdd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzzgraqx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jlsjyb.cn/Article/details/gtdbqhtall.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.andypj.xyz/Article/details/gtlhufdcwf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jyoumei.cn/Article/details/gtjsncaaqa.html

TS:   arr.filter(x => x > 3)
来源：http://dali.iojbl.cn/Article/details/gtjpjotaiu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cdnleiting.top/Article/details/gtidoktifk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gzhubu.top/Article/details/gtvmfieeiw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.quarkkingdee.top/Article/details/gthibishph.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.0kj1m.cn/Article/details/gtrmmkzshq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.smart0.xyz/Article/details/gtyjmhthxs.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinqigfzy.top/Article/details/gtdqelbyqs.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.nwbrower.top/Article/details/gtnnfpbrus.html

JS:   arr.map(x => x * 2)
来源：http://dali.xinyue.icu/Article/details/gtourlveeq.html

TS:   arr.map(x => x * 2)
来源：http://dali.yj20258.top/Article/details/gthigvrtve.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gzhubu.top/Article/details/gtglhdjlcp.html

Go:   // 手写循环
来源：http://dali.c1oappe.top/Article/details/gtmobcvgjw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.tanke756.top/Article/details/gtxxclveer.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.wangdashe.top/Article/details/gthklpyfyc.html

[D15] 去重
来源：http://dali.zhoulong.xyz/Article/details/gthwbprmqz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shuidangran.top/Article/details/gtcuuhrxwl.html

PHP:  array_unique($arr);
来源：http://dali.ehwqpu.com/Article/details/gtbocgvcmv.html

JS:   [...new Set(arr)]
来源：http://dali.xuanzx.com/Article/details/gtdhxmzoru.html

TS:   [...new Set(arr)]
来源：http://dali.chenzaomai.com/Article/details/gtpihukunj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yj20258888.top/Article/details/gtdvgxigmg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shzxlz.cn/Article/details/gtsamathyr.html

Ruby: arr.uniq
来源：http://dali.kuanghao11.cn/Article/details/gtlpqbjmia.html

C#:   list.Distinct().ToList()
来源：http://dali.ehwqpu.com/Article/details/gtfftkjmhb.html

[D16] 求和与平均值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtintvqpno.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cqqwz.cn/Article/details/gtcspnuygf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.svipenyu.cn/Article/details/gtddyejxfs.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzufjctik.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgishdtlh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhixingplan.top/Article/details/gtpgiegypr.html

Go:   // 手写循环累加
来源：http://dali.gogol.net.cn/Article/details/gtxbyopmdv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jianghu66.top/Article/details/gtlvjhnvai.html

C#:   list.Sum();  list.Average()
来源：http://dali.xuetiantiany.cn/Article/details/gtlrffjfbf.html

[D17] 最大值与最小值
来源：http://dali.tanke756.top/Article/details/gtblwlvpuw.html

Py:   max(arr);  min(arr)
来源：http://dali.zycfv.cn/Article/details/gtawyxlxyg.html

PHP:  max($arr);  min($arr);
来源：http://dali.mhx1999.top/Article/details/gtqdslhpni.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.iojbl.cn/Article/details/gtxemhldpt.html

TS:   Math.max(...arr);
来源：http://dali.hammf.cn/Article/details/gtdesnjsux.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.fzhhl.top/Article/details/gtwyynbswg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shuidangran.top/Article/details/gtyztbuybe.html

Ruby: arr.max;  arr.min
来源：http://dali.guannengcc.top/Article/details/gtwwrrttwn.html

C#:   list.Max();  list.Min()
来源：http://dali.jlsjyb.cn/Article/details/gtzonbvyqk.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gtqycppkgv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.guannengcc.top/Article/details/gtoiyzpphe.html

PHP:  array_merge(...$nested);
来源：http://dali.bjfxy.top/Article/details/gtlpsepxgc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shuidangran.top/Article/details/gtgvofcbus.html

TS:   nested.flat();
来源：http://dali.chenzaomai.com/Article/details/gtcttcerhy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.bjfxy.top/Article/details/gtxhelxros.html

Go:   // 手写双层循环
来源：http://dali.zhoulong.xyz/Article/details/gtxydltjjj.html

Ruby: nested.flatten
来源：http://dali.ehwqpu.com/Article/details/gtprtkanep.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yonumen.top/Article/details/gtycziqevf.html

[D19] 按字段分组
来源：http://dali.xuanzx.com/Article/details/gtmsjkwaeh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hnxiangtu.top/Article/details/gtaisuobct.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yj20258888.top/Article/details/gtkogwqxyq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.andypj.xyz/Article/details/gthwwvyult.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.9152youxi.cn/Article/details/gtkaberyqw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhengqikj.top/Article/details/gtuwqdpdmi.html

Go:   // 手写 map[string][]T
来源：http://dali.hammf.cn/Article/details/gtzqmmahyt.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinghuilouyu.cn/Article/details/gthmkkipcs.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shangyingyoupin.top/Article/details/gtdkuliseo.html

[D20] 统计每个元素出现次数
来源：http://dali.yonumen.top/Article/details/gtjkgpcflu.html

Py:   Counter(arr)
来源：http://dali.nanxinkj.top/Article/details/gtefwqcbmt.html

PHP:  array_count_values($arr);
来源：http://dali.wangdashe.top/Article/details/gtcjjrtffs.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangshuangyany.cn/Article/details/gtvsbsflok.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.0kj1m.cn/Article/details/gtsopgdvxh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.redwolf501.top/Article/details/gtwuxxvxwl.html

Go:   // 手写 map[T]int
来源：http://dali.sweek.top/Article/details/gtkfitgqjn.html

Ruby: arr.tally
来源：http://dali.yj20258.top/Article/details/gtfdtighlg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.aizwys.cn/Article/details/gtoxstnaaz.html

[D21] 判断是否包含某元素
来源：http://dali.hongshengwenyu.top/Article/details/gtufygudci.html

Py:   x in arr
来源：http://dali.hysaishi.cn/Article/details/gtnudckyvc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.havefunace.top/Article/details/gtphyzgwbr.html

JS:   arr.includes(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtbjeyvysl.html

TS:   arr.includes(x)
来源：http://dali.snrcjt.cn/Article/details/gtgygtexfr.html

Java: list.contains(x)
来源：http://dali.zdqjudy.top/Article/details/gtvtdysbkf.html

Go:   slices.Contains(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtapfvyoki.html

Ruby: arr.include?(x)
来源：http://dali.c1oappe.top/Article/details/gtmaonfvsy.html

C#:   list.Contains(x)
来源：http://dali.pycfn.com/Article/details/gtwqznlldc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.wangshuangyany.cn/Article/details/gtpoeahccy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yuxming.cn/Article/details/gtfwlpdeyx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ywan-chungtsiang.top/Article/details/gtopojnmer.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zycfv.cn/Article/details/gtatdqetbt.html

TS:   [...arr];
来源：http://dali.yj20258.top/Article/details/gtevknrvla.html

Java: new ArrayList<>(list);
来源：http://dali.gogol.net.cn/Article/details/gtgajicyey.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xuetiantiany.cn/Article/details/gtuudhyjqu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yueranfly.top/Article/details/gtapyyupam.html

C#:   new List<int>(list);
来源：http://dali.zhiwuduotai.top/Article/details/gtsjeawlcj.html

[D23] reduce 累积计算
来源：http://dali.gogol.net.cn/Article/details/gtafgtdljs.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtliwcdmbh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtojzlszhy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fzhhl.top/Article/details/gtwsnuzycv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gogol.net.cn/Article/details/gtjgzwkfon.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cucudq.cn/Article/details/gtgzqudxon.html

Go:   // 手写循环
来源：http://dali.quarkkingdee.top/Article/details/gtudsbqteg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj202588.top/Article/details/gtxiygyodj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.nwbrower.top/Article/details/gtzkvkvwax.html

[D24] 字典 / Map 基本操作
来源：http://dali.quarkkingdee.top/Article/details/gtmxykhexy.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.pycfn.com/Article/details/gtgyeryyrt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tian-w.cn/Article/details/gtooxlxpwv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cheryme.top/Article/details/gtqtxjdfkf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.c1oappe.top/Article/details/gtmrlxnpbc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdefgvytv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhongyouzk.top/Article/details/gtkecwuyzd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.0kj1m.cn/Article/details/gtbjqzhwnq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.aizwys.cn/Article/details/gtmyucjmhm.html

[D25] Set 集合去重与交并差
来源：http://dali.chenzaomai.com/Article/details/gttpuoeugu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jqgfzy.top/Article/details/gtcpswxhhz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xziqi.cn/Article/details/gtfkygyepw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yuanzhike.top/Article/details/gtschvgdby.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yangfankeji.com/Article/details/gtuwdugpaq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jinqigufen.top/Article/details/gtoxvzbubf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.daria6918.cn/Article/details/gtcmzmcdrm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sysykeji.top/Article/details/gtcdfdlrhg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtdgzihisc.html

[D26] 数组转字符串
来源：http://dali.cucudq.cn/Article/details/gtydegnjgu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.chenlongwang.top/Article/details/gtyxmqiptg.html

PHP:  implode(", ", $arr);
来源：http://dali.hnqzz.top/Article/details/gtmogbqrih.html

JS:   arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gtxrbymllt.html

TS:   arr.join(", ")
来源：http://dali.feifeiyinyue.top/Article/details/gtjzwybbqg.html

Java: String.join(", ", list)
来源：http://dali.zdqjudy.top/Article/details/gtqntksmur.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jlsjyb.cn/Article/details/gtowfcqxcc.html

Ruby: arr.join(", ")
来源：http://dali.ydzc1.top/Article/details/gtfdwgahfl.html

C#:   string.Join(", ", list)
来源：http://dali.mhx1999.top/Article/details/gtqpidxdgh.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtpauggnap.html

E. 字符串处理
来源：http://dali.jqgfzy.top/Article/details/gtdslwlfsg.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtedpsnasf.html

[E01] 拼接字符串
来源：http://dali.iojbl.cn/Article/details/gtlpsakejq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gogol.net.cn/Article/details/gtdekfjjpx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.chenzaomai.com/Article/details/gtxmgutwus.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daxiang520.top/Article/details/gtrgtirzqn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ybcxt.top/Article/details/gtaqbgjbxp.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.daria6918.cn/Article/details/gtbwxwmjjv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.kuanghao11.cn/Article/details/gtagtiropj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yangfankeji.com/Article/details/gtrissjnif.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtlzdmtbjv.html

[E02] 重复字符串
来源：http://dali.aibaodan.cn/Article/details/gthprknzfx.html

Py:   "ab" * 3
来源：http://dali.9152youxi.cn/Article/details/gtvfmagnwy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yanxiufei.cn/Article/details/gtvuhuifon.html

JS:   "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gtrojpyomj.html

TS:   "ab".repeat(3)
来源：http://dali.zhoulong.xyz/Article/details/gtcklmvnir.html

Java: "ab".repeat(3)
来源：http://dali.yuxming.cn/Article/details/gttunzusiz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.guowangkeji.top/Article/details/gtkzwqvbdg.html

Ruby: "ab" * 3
来源：http://dali.yj20258.top/Article/details/gtqyveypvk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.c1oappe.top/Article/details/gttssaende.html

[E03] 截取子串
来源：http://dali.yongpay.top/Article/details/gtsvytxbcx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yueranfly.top/Article/details/gtqmqmimto.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gtzlrwknzh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.tanke756.top/Article/details/gtxwdtgguq.html

TS:   s.slice(1, 4)
来源：http://dali.dianchejie.cn/Article/details/gtqjxhnhre.html

Java: s.substring(1, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gtmczzskou.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.kuanghao11.cn/Article/details/gtsbdpjbco.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.pengpengdd.cyou/Article/details/gtzgzcwacx.html

C#:   s.Substring(1, 3)
来源：http://dali.sxryk.cn/Article/details/gtouysxhqf.html

[E04] 查找子串位置
来源：http://dali.cdnleiting.top/Article/details/gtnafebmtv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hammf.cn/Article/details/gtnqfhzqlp.html

PHP:  strpos($s, "x");
来源：http://dali.xziqi.cn/Article/details/gtumxfmeeq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zdqjudy.top/Article/details/gtgtzuqcpi.html

TS:   s.indexOf("x")
来源：http://dali.zdqjudy.top/Article/details/gtovcynrem.html

Java: s.indexOf("x")
来源：http://dali.meibo888.top/Article/details/gtfnenorzj.html

Go:   strings.Index(s, "x")
来源：http://dali.yangfankeji.com/Article/details/gtvrxnbwvm.html

Ruby: s.index("x")
来源：http://dali.yanxiufei.cn/Article/details/gttwpndwek.html

C#:   s.IndexOf("x")
来源：http://dali.xylfe.cn/Article/details/gtysizpove.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhongyouzk.top/Article/details/gtrpzsnpub.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jlsjyb.cn/Article/details/gtvfgixxci.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yvedp.cn/Article/details/gtsjyqwxhx.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xylfe.cn/Article/details/gtmzbohzyx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gogol.net.cn/Article/details/gthxdsbjin.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.guowangkeji.top/Article/details/gtitcfemfe.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yvedp.cn/Article/details/gtjuifnguz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.tanke756.top/Article/details/gtzcbokpks.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gtczutksac.html

[E06] 替换子串
来源：http://dali.ivvv.top/Article/details/gtruueoieg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.bjfxy.top/Article/details/gtpokclcrm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ybcxt.top/Article/details/gttkusnevu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gtfuzvfwtx.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtqtrgfftw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtubesfwnb.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hywenlv.cn/Article/details/gtctcphjgh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtjteulzxf.html

C#:   s.Replace("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtofdviixj.html

[E07] 按分隔符拆分
来源：http://dali.0kj1m.cn/Article/details/gtpikgitmz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.haohaochexian.top/Article/details/gtgwrrnnmq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.redwolf501.top/Article/details/gtownzlopv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.snrcjt.cn/Article/details/gtaaoysfqq.html

TS:   s.split(",")
来源：http://dali.jiagoushi.top/Article/details/gtphxynlgu.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hammf.cn/Article/details/gtbhitearw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrplsdgbb.html

Ruby: s.split(",");  s.split
来源：http://dali.tianlin.xyz/Article/details/gtcdybicvn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cheryme.top/Article/details/gtqtnpyuxi.html

[E08] 数组按分隔符合并
来源：http://dali.jianghu66.top/Article/details/gtzljhtgzi.html

Py:   ",".join(items)
来源：http://dali.yj20258888.top/Article/details/gttjwugkgr.html

PHP:  implode(",", $items);
来源：http://dali.cqqwz.cn/Article/details/gtrucoiibf.html

JS:   items.join(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtiqyuysek.html

TS:   items.join(",")
来源：http://dali.fzhhl.top/Article/details/gtvvnwiyum.html

Java: String.join(",", items)
来源：http://dali.iojbl.cn/Article/details/gtkhrkphku.html

Go:   strings.Join(items, ",")
来源：http://dali.hywenlv.cn/Article/details/gtmqqfzwny.html

Ruby: items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gtuxyeljdt.html

C#:   string.Join(",", items)
来源：http://dali.ivvv.top/Article/details/gtaryposuc.html

[E09] 去除所有空白字符
来源：http://dali.jianghu66.top/Article/details/gtpmhqphpt.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.snrcjt.cn/Article/details/gtvqxklklh.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hammf.cn/Article/details/gtresqrorc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.guowangkeji.top/Article/details/gtiqaewhpw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.daria6918.cn/Article/details/gtbslouwhv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhoulong.xyz/Article/details/gtnrcehttn.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhongyouzk.top/Article/details/gtuqyzmbvz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.feifeiyinyue.top/Article/details/gtvngoslnz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.dashuyun.cn/Article/details/gtkgoltceu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jqgfzy.top/Article/details/gtkhqwuwih.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yvedp.cn/Article/details/gtecrvxptu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.aibaodan.cn/Article/details/gtrzpgneuu.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gtzzwvzpgl.html

TS:   "7".padStart(3, "0")
来源：http://dali.gogol.net.cn/Article/details/gtmuepmfbh.html

Java: String.format("%03d", 7)
来源：http://dali.yj20258888.top/Article/details/gtszmasngk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.tanke756.top/Article/details/gtvqofknbt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jlsjyb.cn/Article/details/gtwtdkhlfy.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj202588.top/Article/details/gtmzzoedhm.html

[E11] 反转字符串
来源：http://dali.zhoulong.xyz/Article/details/gtrmagjydt.html

Py:   s[::-1]
来源：http://dali.dianchejie.cn/Article/details/gtwkmoiefg.html

PHP:  strrev($s);
来源：http://dali.hammf.cn/Article/details/gtdpqcpuxc.html

JS:   [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gtuduqpols.html

TS:   [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gtmtevcuzf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shzxlz.cn/Article/details/gtpcocvfsy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.wangshuangyany.cn/Article/details/gthexgqvga.html

Ruby: s.reverse
来源：http://dali.yuxming.cn/Article/details/gtmlfzohxj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hammf.cn/Article/details/gtxiatutfx.html

[E12] 统计某字符出现次数
来源：http://dali.yuanzhike.top/Article/details/gtumngwbsb.html

Py:   s.count("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtemwexlzp.html

PHP:  substr_count($s, "a");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtavcrkpqx.html

JS:   s.split("a").length - 1
来源：http://dali.pycfn.com/Article/details/gtpfqfodpl.html

TS:   s.split("a").length - 1
来源：http://dali.cheryme.top/Article/details/gtkqqoymcq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.fzhhl.top/Article/details/gtgupproso.html

Go:   strings.Count(s, "a")
来源：http://dali.sxryk.cn/Article/details/gtdrjyprop.html

Ruby: s.count("a")
来源：http://dali.jinqigufen.top/Article/details/gtenbqcpej.html

C#:   s.Count(c => c == 'a')
来源：http://dali.0kj1m.cn/Article/details/gtrcdgxfuq.html

[E13] 逐字符遍历
来源：http://dali.jinqigufen.top/Article/details/gtjchxfxsl.html

Py:   for ch in s: print(ch)
来源：http://dali.daxiang520.top/Article/details/gtrnqlkiqi.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.birdmap.top/Article/details/gtoasmvcre.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guowangkeji.top/Article/details/gtteyvtuhd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tianlin.xyz/Article/details/gtnnvxdvoc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shzxlz.cn/Article/details/gttlkazvbn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtjkondcax.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hywenlv.cn/Article/details/gtweuyphyk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xuanzx.com/Article/details/gtyamohqlw.html

[E14] URL 编码与 Base64
来源：http://dali.sxryk.cn/Article/details/gthsxikjom.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ivvv.top/Article/details/gtynzwhhhn.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenzaomai.com/Article/details/gthceulhwb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shangyingyoupin.top/Article/details/gtxbwzpwzk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yuxming.cn/Article/details/gtzmplklvh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.andypj.xyz/Article/details/gtzgncdcro.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sufxvd.cn/Article/details/gtapnblric.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.dashuyun.cn/Article/details/gtxilieyvn.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.dashuyun.cn/Article/details/gtwbwrpvvs.html

[E15] HTML 转义 / 反转义
来源：http://dali.tianlin.xyz/Article/details/gtvvgzyvvk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yongpay.top/Article/details/gtwxfjjsat.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhongyouzk.top/Article/details/gtzfpwowwa.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zycfv.cn/Article/details/gtqwwgotpp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hywenlv.cn/Article/details/gtoxwqwzgz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cqqwz.cn/Article/details/gtjfjrvgzs.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.daria6918.cn/Article/details/gtzspcpymi.html


<!-- 参考信息 -->