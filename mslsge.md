代发 wailian999

[D07] 切片 / 取子数组
来源：http://dali.vqdsnc.cn/Article/details/gtcqkpzoza.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.aibaodan.cn/Article/details/gtgaqbpqdj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.haohaochexian.top/Article/details/gtkvdvilmp.html

JS:   arr.slice(1, 4);
来源：http://dali.hfpthk.cn/Article/details/gtvykcbclb.html

TS:   arr.slice(1, 4);
来源：http://dali.smart0.xyz/Article/details/gtwqqxlgen.html

Java: list.subList(1, 4);
来源：http://dali.svipenyu.cn/Article/details/gtlifexmts.html

Go:   arr[1:4]
来源：http://dali.havefunace.top/Article/details/gtsqphwbxj.html

Ruby: arr[1, 3]
来源：http://dali.jqgufenzy.top/Article/details/gtctfvfuzw.html

C#:   list.GetRange(1, 3);
来源：http://dali.sysykeji.top/Article/details/gtnisdfxaq.html

[D08] 合并两个数组
来源：http://dali.yangfankeji.com/Article/details/gtoqeptkbr.html

Py:   a + b;  a.extend(b)
来源：http://dali.ybcxt.top/Article/details/gtqbabkszp.html

PHP:  array_merge($a, $b);
来源：http://dali.shanyushiyangtech.top/Article/details/gtasiktrjj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ehwqpu.com/Article/details/gtpglyzkib.html

TS:   [...a, ...b];
来源：http://dali.yangfankeji.com/Article/details/gtvqsneesf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.aibaodan.cn/Article/details/gtjtvyfoev.html

Go:   append(a, b...)
来源：http://dali.hywenlv.cn/Article/details/gtznrclbhq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.kuanghao11.cn/Article/details/gtecxgqxhk.html

C#:   a.Concat(b).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtcycwoefn.html

[D09] 排序（升序）
来源：http://dali.chenzaomai.com/Article/details/gtzokaqlzd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xinyue.icu/Article/details/gtqgvhhijj.html

PHP:  sort($arr);
来源：http://dali.birdmap.top/Article/details/gtxmexhqsw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sxryk.cn/Article/details/gtwfkowdtj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.andypj.xyz/Article/details/gtqhbfatla.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yuanzhike.top/Article/details/gtodaexzji.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hysaishi.cn/Article/details/gtwngrsxds.html

Ruby: arr.sort
来源：http://dali.cqqwz.cn/Article/details/gtusxhdajt.html

C#:   list.Sort();
来源：http://dali.gaohongyu789.top/Article/details/gtszckjzpm.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xuetiantiany.cn/Article/details/gtrlpxscxf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sysykeji.top/Article/details/gtrsfoskin.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gogol.net.cn/Article/details/gtllpvngrg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hongshengwenyu.top/Article/details/gttklajvcb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fengsongda.top/Article/details/gtutnszigc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cucudq.cn/Article/details/gtcdsjlxpm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jianghu66.top/Article/details/gtuttepdyg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hywenlv.cn/Article/details/gtodrgsypb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.fengsongda.top/Article/details/gtblzxrpfp.html

[D11] 反转数组
来源：http://dali.gogol.net.cn/Article/details/gtussawqum.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.fzhhl.top/Article/details/gtylglaueu.html

PHP:  array_reverse($arr);
来源：http://dali.yongpay.top/Article/details/gtwgztsqio.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.tanke756.top/Article/details/gtbeumtbfl.html

TS:   [...arr].reverse();
来源：http://dali.guannengcc.top/Article/details/gtpibpzjns.html

Java: Collections.reverse(list);
来源：http://dali.sweek.top/Article/details/gtjbwwbtpt.html

Go:   slices.Reverse(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtcvoauodo.html

Ruby: arr.reverse
来源：http://dali.zhongyouzk.top/Article/details/gtkhcdgolq.html

C#:   list.Reverse();
来源：http://dali.tanke756.top/Article/details/gtndcmhinj.html

[D12] 查找元素下标
来源：http://dali.dashuyun.cn/Article/details/gtpkdbunyq.html

Py:   arr.index(x);  x in arr
来源：http://dali.snrcjt.cn/Article/details/gtihierftn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jqgufenzy.top/Article/details/gtckslqryg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gotoacloud.top/Article/details/gtbsevppkq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhongyouzk.top/Article/details/gtzecqbpky.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yangfankeji.com/Article/details/gtzwptyjpq.html

Go:   slices.Index(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtksvgidlc.html

Ruby: arr.index(x)
来源：http://dali.yvedp.cn/Article/details/gtoqedqihj.html

C#:   list.IndexOf(x);
来源：http://dali.xuanzx.com/Article/details/gtunjmzqxx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yj20258888.top/Article/details/gtmkzhmkjv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ybcxt.top/Article/details/gtjpbelpvq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.pycfn.com/Article/details/gtsbzcgdgv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhixingplan.top/Article/details/gtzaeukqca.html

TS:   arr.filter(x => x > 3)
来源：http://dali.daria6918.cn/Article/details/gtvtfvyktx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hywenlv.cn/Article/details/gtnsypvdhd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nwbrower.top/Article/details/gtddaiqmqb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.daria6918.cn/Article/details/gtisniuhwt.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.nwbrower.top/Article/details/gtlhyvhltm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xuetiantiany.cn/Article/details/gtvctwtwyq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cqqwz.cn/Article/details/gtueguznxi.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj20258.top/Article/details/gtzgrzekug.html

JS:   arr.map(x => x * 2)
来源：http://dali.jlsjyb.cn/Article/details/gtkonybnff.html

TS:   arr.map(x => x * 2)
来源：http://dali.yonumen.top/Article/details/gtbkqnphxp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtmqyrzney.html

Go:   // 手写循环
来源：http://dali.ivvv.top/Article/details/gtahdvpnzg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.redwolf501.top/Article/details/gtvophrtrw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tanke756.top/Article/details/gtgjjgeysd.html

[D15] 去重
来源：http://dali.gotoacloud.top/Article/details/gtdilypvsd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.316326.xyz/Article/details/gtrhyqzkic.html

PHP:  array_unique($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwcuvgft.html

JS:   [...new Set(arr)]
来源：http://dali.haohaochexian.top/Article/details/gtgzsstvah.html

TS:   [...new Set(arr)]
来源：http://dali.aizwys.cn/Article/details/gtvzzgfwpv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtigibidkf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shanyushiyangtech.top/Article/details/gterdfkelh.html

Ruby: arr.uniq
来源：http://dali.pycfn.com/Article/details/gttylbfgbq.html

C#:   list.Distinct().ToList()
来源：http://dali.zhengqikj.top/Article/details/gtabiqoepu.html

[D16] 求和与平均值
来源：http://dali.smart0.xyz/Article/details/gtkukfskoe.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtydewooqk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlybqwcyq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cqqwz.cn/Article/details/gtnzeueaat.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jianghu66.top/Article/details/gtxkpkxjps.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinqigufen.top/Article/details/gtgrapmtxv.html

Go:   // 手写循环累加
来源：http://dali.zhiwuduotai.top/Article/details/gtytsluojv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.wangdashe.top/Article/details/gtagkurryy.html

C#:   list.Sum();  list.Average()
来源：http://dali.hfpthk.cn/Article/details/gthsqosycl.html

[D17] 最大值与最小值
来源：http://dali.andypj.xyz/Article/details/gtxuqlojnp.html

Py:   max(arr);  min(arr)
来源：http://dali.snrcjt.cn/Article/details/gtdzqpysxq.html

PHP:  max($arr);  min($arr);
来源：http://dali.wangdashe.top/Article/details/gtqzbjvane.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhengqikj.top/Article/details/gtwitauovd.html

TS:   Math.max(...arr);
来源：http://dali.xuanzx.com/Article/details/gttlmsavxm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.guowangkeji.top/Article/details/gtipzvkgcn.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqawlytku.html

Ruby: arr.max;  arr.min
来源：http://dali.shuidangran.top/Article/details/gtwvbjnpfk.html

C#:   list.Max();  list.Min()
来源：http://dali.xuetiantiany.cn/Article/details/gtjwryrqif.html

[D18] 扁平化嵌套数组
来源：http://dali.ppjwa.cn/Article/details/gtiiznmcwv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.kuanghao11.cn/Article/details/gtwddjtxds.html

PHP:  array_merge(...$nested);
来源：http://dali.yongpay.top/Article/details/gtuubhwkxa.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtedvyedwk.html

TS:   nested.flat();
来源：http://dali.sysykeji.top/Article/details/gthahxhugc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.birdmap.top/Article/details/gtjwwohont.html

Go:   // 手写双层循环
来源：http://dali.cdnleiting.top/Article/details/gtefzaijba.html

Ruby: nested.flatten
来源：http://dali.daria6918.cn/Article/details/gttfsknzio.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtqqfyqjge.html

[D19] 按字段分组
来源：http://dali.cdnleiting.top/Article/details/gtkxlrzxjm.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yanxiufei.cn/Article/details/gtgdpapjey.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jiagoushi.top/Article/details/gtxawdaxtv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hfpthk.cn/Article/details/gtlvuzllhb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cheryme.top/Article/details/gtsxzdhrgb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.chenjidiqi.icu/Article/details/gtbktfxqpm.html

Go:   // 手写 map[string][]T
来源：http://dali.aizwys.cn/Article/details/gtjtzmgage.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.guannengcc.top/Article/details/gttmchnrgs.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.iojbl.cn/Article/details/gtpsdcgogs.html

[D20] 统计每个元素出现次数
来源：http://dali.aibaodan.cn/Article/details/gtbkvgjikh.html

Py:   Counter(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtzhxpuzkt.html

PHP:  array_count_values($arr);
来源：http://dali.fengsongda.top/Article/details/gtrvjhckhl.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hysaishi.cn/Article/details/gtuflbskkr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.smart0.xyz/Article/details/gttwqfizib.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.wangshuangyany.cn/Article/details/gtaxpxijrn.html

Go:   // 手写 map[T]int
来源：http://dali.yj202588.top/Article/details/gtztiurgrf.html

Ruby: arr.tally
来源：http://dali.tianlin.xyz/Article/details/gtvtdqupzx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yueranfly.top/Article/details/gtnioxtemr.html

[D21] 判断是否包含某元素
来源：http://dali.sxryk.cn/Article/details/gtpcqawnwi.html

Py:   x in arr
来源：http://dali.316326.xyz/Article/details/gtmznvliif.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hysaishi.cn/Article/details/gtskhklfiw.html

JS:   arr.includes(x)
来源：http://dali.mhx1999.top/Article/details/gteebmoepk.html

TS:   arr.includes(x)
来源：http://dali.guowangkeji.top/Article/details/gtbtxryskx.html

Java: list.contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gtmmuqspac.html

Go:   slices.Contains(arr, x)
来源：http://dali.havefunace.top/Article/details/gtncxgnbea.html

Ruby: arr.include?(x)
来源：http://dali.zhongyouzk.top/Article/details/gtmopmrnah.html

C#:   list.Contains(x)
来源：http://dali.hywenlv.cn/Article/details/gtardsedqp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jyoumei.cn/Article/details/gtemplwqsh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgqgstuqd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zycfv.cn/Article/details/gtkzkwbrfn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtynxtzycv.html

TS:   [...arr];
来源：http://dali.zdqjudy.top/Article/details/gtnzgqisqa.html

Java: new ArrayList<>(list);
来源：http://dali.yj20258.top/Article/details/gtycvqaqxn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xuanzx.com/Article/details/gtqduowmdo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xylfe.cn/Article/details/gtjctgmgsg.html

C#:   new List<int>(list);
来源：http://dali.sysykeji.top/Article/details/gtfdipvdde.html

[D23] reduce 累积计算
来源：http://dali.cucudq.cn/Article/details/gtctyhbspw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.chenzaomai.com/Article/details/gtoxahtqzd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yongpay.top/Article/details/gtxdbxfmcx.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258.top/Article/details/gtyqtlcpuu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jianghu66.top/Article/details/gtdeoadhbt.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.haohaochexian.top/Article/details/gtujnzouhi.html

Go:   // 手写循环
来源：http://dali.chenlongwang.top/Article/details/gtymuaifiu.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hongshengwenyu.top/Article/details/gtfyfpxlgy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yj202588.top/Article/details/gtpkdgqpkh.html

[D24] 字典 / Map 基本操作
来源：http://dali.hnqzz.top/Article/details/gtzhciiffu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jianghu66.top/Article/details/gthwjunwqd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.pengpengdd.cyou/Article/details/gtruirnvtj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjlpqpyar.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.daria6918.cn/Article/details/gtvyqqkzad.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.andypj.xyz/Article/details/gtjguvncbh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.dashuyun.cn/Article/details/gtefghjryw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shanyushiyangtech.top/Article/details/gtsvpmvyrq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xuetiantiany.cn/Article/details/gttfedwrpb.html

[D25] Set 集合去重与交并差
来源：http://dali.meibo888.top/Article/details/gtrcobekwb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jianghu66.top/Article/details/gtzvyrwbcn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.tianlin.xyz/Article/details/gtpcfxfrpd.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cheryme.top/Article/details/gtrohdwzdg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hnxiangtu.top/Article/details/gtkawhgrcw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gotoacloud.top/Article/details/gtilesammc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gaohongyu789.top/Article/details/gtqyptyqak.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.andypj.xyz/Article/details/gtppqactsa.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yueranfly.top/Article/details/gtqdvxbebm.html

[D26] 数组转字符串
来源：http://dali.jqgufenzy.top/Article/details/gtigaljvlu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.kuanghao11.cn/Article/details/gtoyiamecw.html

PHP:  implode(", ", $arr);
来源：http://dali.chenlongwang.top/Article/details/gtwdipaool.html

JS:   arr.join(", ")
来源：http://dali.wangshuangyany.cn/Article/details/gtnlcdlssw.html

TS:   arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gtprervgbt.html

Java: String.join(", ", list)
来源：http://dali.wangdashe.top/Article/details/gtfprdhgmf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.tian-w.cn/Article/details/gtgjztywro.html

Ruby: arr.join(", ")
来源：http://dali.hnqzz.top/Article/details/gtvdjcomal.html

C#:   string.Join(", ", list)
来源：http://dali.nanxinkj.top/Article/details/gtycvvhjsc.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gttrvwqsqh.html

E. 字符串处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnsrbaqku.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtwdbnybky.html

[E01] 拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gttrfwvyyq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gogol.net.cn/Article/details/gtsututrox.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.haohaochexian.top/Article/details/gtzkbyoiln.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shuidangran.top/Article/details/gtjmgbdrwd.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yanxiufei.cn/Article/details/gtleegjbsx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tianlin.xyz/Article/details/gtdlpeeawt.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.snrcjt.cn/Article/details/gtyouxswzb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yuanzhike.top/Article/details/gtsssvtwoy.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtfhuleveo.html

[E02] 重复字符串
来源：http://dali.meibo888.top/Article/details/gtsxgldybe.html

Py:   "ab" * 3
来源：http://dali.chenzaomai.com/Article/details/gtdeshcgdi.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttfmtgyas.html

JS:   "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gtacdjoxli.html

TS:   "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gtqopjesyl.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gtjzimlvaz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.bjfxy.top/Article/details/gtpkmofbfh.html

Ruby: "ab" * 3
来源：http://dali.zhixingplan.top/Article/details/gtxituepqj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.tanke756.top/Article/details/gttcionext.html

[E03] 截取子串
来源：http://dali.hongshengwenyu.top/Article/details/gtrqgnyrfv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jyoumei.cn/Article/details/gtsuiuawpl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gtzyyqbaut.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ppjwa.cn/Article/details/gtkmqmbilo.html

TS:   s.slice(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gtkheekjxn.html

Java: s.substring(1, 4)
来源：http://dali.c1oappe.top/Article/details/gtnlonsgsj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hywenlv.cn/Article/details/gtadtzgmzv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sxryk.cn/Article/details/gtziaxpqdr.html

C#:   s.Substring(1, 3)
来源：http://dali.nanxuanxn.top/Article/details/gtujipchdv.html

[E04] 查找子串位置
来源：http://dali.jianghu66.top/Article/details/gtuxhthtfz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.birdmap.top/Article/details/gthgkttltu.html

PHP:  strpos($s, "x");
来源：http://dali.c1oappe.top/Article/details/gtbuhbkiis.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hnqzz.top/Article/details/gtlscvgjvf.html

TS:   s.indexOf("x")
来源：http://dali.cheryme.top/Article/details/gtnmbcgwcg.html

Java: s.indexOf("x")
来源：http://dali.yj202588.top/Article/details/gtgllheaje.html

Go:   strings.Index(s, "x")
来源：http://dali.jqgufenzy.top/Article/details/gtqeuzutvi.html

Ruby: s.index("x")
来源：http://dali.quarkkingdee.top/Article/details/gtxxuhywro.html

C#:   s.IndexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gtxchbetog.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.snrcjt.cn/Article/details/gtcmbaekpu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ivvv.top/Article/details/gtqksxwmss.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.bjfxy.top/Article/details/gtzoaadpyt.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cashguo.top/Article/details/gtdirfkgjr.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jqgufenzy.top/Article/details/gtafiltyhj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hongshengwenyu.top/Article/details/gtsijxnzge.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.vqdsnc.cn/Article/details/gtplgqjcgm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yanxiufei.cn/Article/details/gtlsbirpzp.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.andypj.xyz/Article/details/gtqgddpxwj.html

[E06] 替换子串
来源：http://dali.xuanzx.com/Article/details/gtlkketqwm.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shzxlz.cn/Article/details/gtklvajsai.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yuxming.cn/Article/details/gtiaxiegks.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gtjeszbyyw.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gtcpvgipoy.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtbivxbcup.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jqgufenzy.top/Article/details/gtcowhxyzy.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtbxvxyjnk.html

C#:   s.Replace("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtzecfrzwq.html

[E07] 按分隔符拆分
来源：http://dali.cqqwz.cn/Article/details/gtjpzerjlq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.daria6918.cn/Article/details/gtjtnrbous.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtkkypryrn.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.c1oappe.top/Article/details/gthjcvxlxo.html

TS:   s.split(",")
来源：http://dali.zhengqikj.top/Article/details/gtkbrpsuwn.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.meibo888.top/Article/details/gtddbwaohu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xinyue.icu/Article/details/gtsgemjfps.html

Ruby: s.split(",");  s.split
来源：http://dali.meibo888.top/Article/details/gtmyplvmfn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.smart0.xyz/Article/details/gtwyonuucr.html

[E08] 数组按分隔符合并
来源：http://dali.bjfxy.top/Article/details/gtsmbbwqgd.html

Py:   ",".join(items)
来源：http://dali.ybcxt.top/Article/details/gtnqaditjo.html

PHP:  implode(",", $items);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsrnzmiwo.html

JS:   items.join(",")
来源：http://dali.hnxiangtu.top/Article/details/gtfrzmktdu.html

TS:   items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gtnvyhoapu.html

Java: String.join(",", items)
来源：http://dali.yueranfly.top/Article/details/gtiukanbcb.html

Go:   strings.Join(items, ",")
来源：http://dali.birdmap.top/Article/details/gtyvjvkdhj.html

Ruby: items.join(",")
来源：http://dali.yonumen.top/Article/details/gtmrotmize.html

C#:   string.Join(",", items)
来源：http://dali.tanke756.top/Article/details/gtklmxvtgc.html

[E09] 去除所有空白字符
来源：http://dali.yvedp.cn/Article/details/gtphnchvbd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yj20258888.top/Article/details/gtgtxvrsch.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yj20258.top/Article/details/gtqrfujfnf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxdvnnhyi.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhixingplan.top/Article/details/gtqwuugpcp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gogol.net.cn/Article/details/gtrhouqexc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ydzc1.top/Article/details/gtgbewwfbg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jqgufenzy.top/Article/details/gtcdvxjwgd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.redwolf501.top/Article/details/gtpttyygba.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hfpthk.cn/Article/details/gtsgdmzapl.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gtecllvigf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbhqpymxw.html

JS:   "7".padStart(3, "0")
来源：http://dali.fengsongda.top/Article/details/gtkgfzdoyh.html

TS:   "7".padStart(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gtwyapvdhu.html

Java: String.format("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gtegitpedc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gtghabbeae.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jqgfzy.top/Article/details/gtfqdnqphl.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhixingplan.top/Article/details/gthjinltdj.html

[E11] 反转字符串
来源：http://dali.daxiang520.top/Article/details/gtigdippuw.html

Py:   s[::-1]
来源：http://dali.mhx1999.top/Article/details/gtxfimetak.html

PHP:  strrev($s);
来源：http://dali.snrcjt.cn/Article/details/gtbgsshzhy.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gtxupqoxmw.html

TS:   [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gtcrxizcfr.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.iojbl.cn/Article/details/gtsuteoxaj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.mhx1999.top/Article/details/gtjivcoyju.html

Ruby: s.reverse
来源：http://dali.jinqigufen.top/Article/details/gthtngsois.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jiagoushi.top/Article/details/gtyusncddd.html

[E12] 统计某字符出现次数
来源：http://dali.hywenlv.cn/Article/details/gtzdsxyyyu.html

Py:   s.count("a")
来源：http://dali.cqqwz.cn/Article/details/gtfvpxlsrr.html

PHP:  substr_count($s, "a");
来源：http://dali.hnqzz.top/Article/details/gtnbiepoqi.html

JS:   s.split("a").length - 1
来源：http://dali.ivvv.top/Article/details/gtlhtbubxw.html

TS:   s.split("a").length - 1
来源：http://dali.kuanghao11.cn/Article/details/gtkierpdor.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.quarkkingdee.top/Article/details/gtghlczzoh.html

Go:   strings.Count(s, "a")
来源：http://dali.yj202588.top/Article/details/gtdqavfuud.html

Ruby: s.count("a")
来源：http://dali.quarkkingdee.top/Article/details/gtrhglrctn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlhuignvx.html

[E13] 逐字符遍历
来源：http://dali.redwolf501.top/Article/details/gtzcfqstjc.html

Py:   for ch in s: print(ch)
来源：http://dali.snrcjt.cn/Article/details/gtqltllmiz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.chenzaomai.com/Article/details/gtppphxhoc.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gtcpiasoff.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gtwinibthc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cqqwz.cn/Article/details/gtglcqfggo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.iojbl.cn/Article/details/gtsrrvicjb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.birdmap.top/Article/details/gtjsblqjgb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gtbvbpxnnq.html


<!-- 参考信息 -->