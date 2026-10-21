代发 wailian999

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.chenzaomai.com/Article/details/gtaehyybhd.html

Ruby: arr.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gtncwwjqzt.html

C#:   list.Sort();
来源：http://dali.zhoulong.xyz/Article/details/gtuodgsvpv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbrmunhna.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.0kj1m.cn/Article/details/gthheglnkb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenlongwang.top/Article/details/gtgssjzaqr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxuanxn.top/Article/details/gtrcvybfti.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhiwuduotai.top/Article/details/gtjehtafcc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shzxlz.cn/Article/details/gtzyhbvgek.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.aibaodan.cn/Article/details/gtuuzchhmk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.pycfn.com/Article/details/gtaoqcohem.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.mhx1999.top/Article/details/gttisdmftg.html

[D11] 反转数组
来源：http://dali.xylfe.cn/Article/details/gttirnahvm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.bjfxy.top/Article/details/gthyxhkemo.html

PHP:  array_reverse($arr);
来源：http://dali.guowangkeji.top/Article/details/gtczjqixvt.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shangyingyoupin.top/Article/details/gtrvirmevw.html

TS:   [...arr].reverse();
来源：http://dali.yangfankeji.com/Article/details/gtddfundga.html

Java: Collections.reverse(list);
来源：http://dali.bjfxy.top/Article/details/gthbldahbj.html

Go:   slices.Reverse(arr)
来源：http://dali.9152youxi.cn/Article/details/gtbbejvsmo.html

Ruby: arr.reverse
来源：http://dali.fzhhl.top/Article/details/gtrxivrqrv.html

C#:   list.Reverse();
来源：http://dali.gotoacloud.top/Article/details/gtspjjjizl.html

[D12] 查找元素下标
来源：http://dali.zycfv.cn/Article/details/gtdgkdzydm.html

Py:   arr.index(x);  x in arr
来源：http://dali.pengpengdd.cyou/Article/details/gtccpxdhhx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cashguo.top/Article/details/gtdtdezvdh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pycfn.com/Article/details/gtkbvpgvjk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.iojbl.cn/Article/details/gtearlknfb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj202588.top/Article/details/gtoohoacoc.html

Go:   slices.Index(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtqlzosdqw.html

Ruby: arr.index(x)
来源：http://dali.cashguo.top/Article/details/gtfclfazus.html

C#:   list.IndexOf(x);
来源：http://dali.dianchejie.cn/Article/details/gtvutehqzw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jiagoushi.top/Article/details/gtlaosejzl.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.tanke756.top/Article/details/gtrdgzwaxi.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yvedp.cn/Article/details/gtzolwrkja.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gzhubu.top/Article/details/gtngffwzav.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yongpay.top/Article/details/gtkjruehen.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ydzc1.top/Article/details/gtawaqnuwb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ivvv.top/Article/details/gttkopguiu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.chenzaomai.com/Article/details/gttfpfczpg.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtnixruytn.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cheryme.top/Article/details/gtsckzdghj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hywenlv.cn/Article/details/gtspevaeiq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hywenlv.cn/Article/details/gtagebszto.html

JS:   arr.map(x => x * 2)
来源：http://dali.jqgufenzy.top/Article/details/gtvtvhkkmb.html

TS:   arr.map(x => x * 2)
来源：http://dali.aizwys.cn/Article/details/gthznkkfoj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.tianlin.xyz/Article/details/gtqlirjudj.html

Go:   // 手写循环
来源：http://dali.havefunace.top/Article/details/gtynxitrpk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.c1oappe.top/Article/details/gtqwzxcmfp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sweek.top/Article/details/gtvtzbnekr.html

[D15] 去重
来源：http://dali.nwbrower.top/Article/details/gtxnbtlmxs.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.9152youxi.cn/Article/details/gtnfwijekh.html

PHP:  array_unique($arr);
来源：http://dali.hysaishi.cn/Article/details/gtdckndffe.html

JS:   [...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gtvlaowxie.html

TS:   [...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gtopgstklq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.andypj.xyz/Article/details/gtnmwqfaxp.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.aizwys.cn/Article/details/gtnoxnqrli.html

Ruby: arr.uniq
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwzkmlbok.html

C#:   list.Distinct().ToList()
来源：http://dali.nwbrower.top/Article/details/gtiegruhms.html

[D16] 求和与平均值
来源：http://dali.cashguo.top/Article/details/gtwxztcgrv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfjmyprwj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtgahbleld.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuxming.cn/Article/details/gtyzhjyfjf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cheryme.top/Article/details/gtmchdtntg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinqigfzy.top/Article/details/gtwptauyre.html

Go:   // 手写循环累加
来源：http://dali.pengpengdd.cyou/Article/details/gttdxuosbu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cucudq.cn/Article/details/gtjunsmspu.html

C#:   list.Sum();  list.Average()
来源：http://dali.ybcxt.top/Article/details/gtiyweotpi.html

[D17] 最大值与最小值
来源：http://dali.tianlin.xyz/Article/details/gtppxradlp.html

Py:   max(arr);  min(arr)
来源：http://dali.aibaodan.cn/Article/details/gttxdkdhuu.html

PHP:  max($arr);  min($arr);
来源：http://dali.aibaodan.cn/Article/details/gthyntnwxu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cdnleiting.top/Article/details/gtvkqmbztv.html

TS:   Math.max(...arr);
来源：http://dali.chenzaomai.com/Article/details/gtmljagxhq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gtyegsecwh.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtotxwvbks.html

Ruby: arr.max;  arr.min
来源：http://dali.shangyingyoupin.top/Article/details/gtplqwhlly.html

C#:   list.Max();  list.Min()
来源：http://dali.kuanghao11.cn/Article/details/gtaudkzlsb.html

[D18] 扁平化嵌套数组
来源：http://dali.xuanzx.com/Article/details/gthdrniloy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sxryk.cn/Article/details/gtcnjdeazh.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gtzrznqjcf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.smart0.xyz/Article/details/gtgqzltdbs.html

TS:   nested.flat();
来源：http://dali.yueranfly.top/Article/details/gtnpaplpah.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.tianlin.xyz/Article/details/gtrcoblfde.html

Go:   // 手写双层循环
来源：http://dali.gotoacloud.top/Article/details/gtrflrujpq.html

Ruby: nested.flatten
来源：http://dali.haohaochexian.top/Article/details/gtupkuynqd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cqqwz.cn/Article/details/gtinkthwbj.html

[D19] 按字段分组
来源：http://dali.sxryk.cn/Article/details/gtkzeuispu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jianghu66.top/Article/details/gtppsckpyn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cqqwz.cn/Article/details/gtnyakqvvr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.svipenyu.cn/Article/details/gtlswezhxe.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gotoacloud.top/Article/details/gtnliksjpo.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.tanke756.top/Article/details/gtlsspitpc.html

Go:   // 手写 map[string][]T
来源：http://dali.cqqwz.cn/Article/details/gtlfrlmkcv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yueranfly.top/Article/details/gtmxyugnwn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.dianchejie.cn/Article/details/gtctbpjamp.html

[D20] 统计每个元素出现次数
来源：http://dali.wangshuangyany.cn/Article/details/gtlefvnnwx.html

Py:   Counter(arr)
来源：http://dali.cdnleiting.top/Article/details/gtgdxrjnrx.html

PHP:  array_count_values($arr);
来源：http://dali.sxryk.cn/Article/details/gtirpyseiq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nwbrower.top/Article/details/gtgrzkacnv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xziqi.cn/Article/details/gtoqmboxcp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hfpthk.cn/Article/details/gtbspxffed.html

Go:   // 手写 map[T]int
来源：http://dali.jlsjyb.cn/Article/details/gtixyimqro.html

Ruby: arr.tally
来源：http://dali.wangshuangyany.cn/Article/details/gtbjmmcknf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zdqjudy.top/Article/details/gtmhnfeaxl.html

[D21] 判断是否包含某元素
来源：http://dali.tianlin.xyz/Article/details/gtudvrnons.html

Py:   x in arr
来源：http://dali.xziqi.cn/Article/details/gtgtrogijl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.haohaochexian.top/Article/details/gtlscsdsig.html

JS:   arr.includes(x)
来源：http://dali.dianchejie.cn/Article/details/gtnxiihney.html

TS:   arr.includes(x)
来源：http://dali.hnxiangtu.top/Article/details/gtiluehyem.html

Java: list.contains(x)
来源：http://dali.hammf.cn/Article/details/gtwwvgdxqv.html

Go:   slices.Contains(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzccbinxc.html

Ruby: arr.include?(x)
来源：http://dali.svipenyu.cn/Article/details/gtwzwypiwb.html

C#:   list.Contains(x)
来源：http://dali.vqdsnc.cn/Article/details/gtsdahfrxx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yongpay.top/Article/details/gtrkkpgfjr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.fengsongda.top/Article/details/gtxbbgurxz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.tianlin.xyz/Article/details/gtkfyxulyi.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenzaomai.com/Article/details/gtkiucheeo.html

TS:   [...arr];
来源：http://dali.dashuyun.cn/Article/details/gtddbnlmdv.html

Java: new ArrayList<>(list);
来源：http://dali.jianghu66.top/Article/details/gthixlaivb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.nwbrower.top/Article/details/gtxnljdzpj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.meibo888.top/Article/details/gtfyrsipnc.html

C#:   new List<int>(list);
来源：http://dali.mhx1999.top/Article/details/gtkueibzee.html

[D23] reduce 累积计算
来源：http://dali.cashguo.top/Article/details/gtdrlxxkrw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtllcgeepj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinqigfzy.top/Article/details/gteoympoaq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cucudq.cn/Article/details/gtvyxwnymm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtschwdvzt.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.9152youxi.cn/Article/details/gtmqjtwixd.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gtcydsxnie.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zycfv.cn/Article/details/gtjqwdqfed.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xuetiantiany.cn/Article/details/gtntddfyrx.html

[D24] 字典 / Map 基本操作
来源：http://dali.hnqzz.top/Article/details/gtlxqhwkiq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jqgfzy.top/Article/details/gtjxaufwxf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtctygxpor.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yuxming.cn/Article/details/gtootkgvas.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.daxiang520.top/Article/details/gtqkubrbtz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcytqhznk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.fzhhl.top/Article/details/gtraecshrq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.wangshuangyany.cn/Article/details/gtweparydd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhoulong.xyz/Article/details/gtygtjnlgb.html

[D25] Set 集合去重与交并差
来源：http://dali.cucudq.cn/Article/details/gtpprztbwq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cucudq.cn/Article/details/gttlkfclqg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.guowangkeji.top/Article/details/gtpqbpryql.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sweek.top/Article/details/gtanrdjjsq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jqgfzy.top/Article/details/gtimdsnwgl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yvedp.cn/Article/details/gtpbntexoj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gogol.net.cn/Article/details/gtvplukhbo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.dashuyun.cn/Article/details/gtqloklmrm.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tianlin.xyz/Article/details/gtjqqgultj.html

[D26] 数组转字符串
来源：http://dali.nanxinkj.top/Article/details/gtdjyawach.html

Py:   ", ".join(map(str, arr))
来源：http://dali.316326.xyz/Article/details/gtfzlmqixg.html

PHP:  implode(", ", $arr);
来源：http://dali.316326.xyz/Article/details/gthpbzhseg.html

JS:   arr.join(", ")
来源：http://dali.havefunace.top/Article/details/gthzapmtgm.html

TS:   arr.join(", ")
来源：http://dali.fengsongda.top/Article/details/gtidrusisv.html

Java: String.join(", ", list)
来源：http://dali.shzxlz.cn/Article/details/gtvdanwkus.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yongpay.top/Article/details/gtcnwuuign.html

Ruby: arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gtbehdqwyv.html

C#:   string.Join(", ", list)
来源：http://dali.ehwqpu.com/Article/details/gtzdtgyins.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtbhjyvoqr.html

E. 字符串处理
来源：http://dali.feifeiyinyue.top/Article/details/gtpmegmpmn.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtdbzhowrg.html

[E01] 拼接字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtzwtnuwya.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.havefunace.top/Article/details/gtvknxizvx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hnxiangtu.top/Article/details/gtvcushcdg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmcbqjeag.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigufen.top/Article/details/gtzejgmoek.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.dashuyun.cn/Article/details/gtxnepgbff.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jyoumei.cn/Article/details/gtvtdiqlkk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkiapguqp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtwszlhptl.html

[E02] 重复字符串
来源：http://dali.ivvv.top/Article/details/gtdzenaudp.html

Py:   "ab" * 3
来源：http://dali.jinqigufen.top/Article/details/gtqvprrzmr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.nanxinkj.top/Article/details/gtsldcvutv.html

JS:   "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gtivvqqhik.html

TS:   "ab".repeat(3)
来源：http://dali.yonumen.top/Article/details/gtdtsjzmvp.html

Java: "ab".repeat(3)
来源：http://dali.xinyue.icu/Article/details/gtowvcgibk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yj20258.top/Article/details/gtrdfirzay.html

Ruby: "ab" * 3
来源：http://dali.havefunace.top/Article/details/gtxcwygric.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhiwuduotai.top/Article/details/gtgkwbkhae.html

[E03] 截取子串
来源：http://dali.birdmap.top/Article/details/gtawjmqppg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yanxiufei.cn/Article/details/gthzbrfetf.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gtttbvuevz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.guannengcc.top/Article/details/gtjoarfden.html

TS:   s.slice(1, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtledhgfsg.html

Java: s.substring(1, 4)
来源：http://dali.kuanghao11.cn/Article/details/gtpdylxeeb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.snrcjt.cn/Article/details/gttznvpnud.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ivvv.top/Article/details/gtribwlnny.html

C#:   s.Substring(1, 3)
来源：http://dali.hywenlv.cn/Article/details/gtedqebypz.html

[E04] 查找子串位置
来源：http://dali.9152youxi.cn/Article/details/gtbckxnutx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.316326.xyz/Article/details/gtcnbczdcp.html

PHP:  strpos($s, "x");
来源：http://dali.shzxlz.cn/Article/details/gtxlurwnxm.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.meibo888.top/Article/details/gttjljfnui.html

TS:   s.indexOf("x")
来源：http://dali.jinqigufen.top/Article/details/gtwjbxpcza.html

Java: s.indexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gttpfewaso.html

Go:   strings.Index(s, "x")
来源：http://dali.sxryk.cn/Article/details/gtjgzhtvoy.html

Ruby: s.index("x")
来源：http://dali.tanke756.top/Article/details/gtnrcdxhhn.html

C#:   s.IndexOf("x")
来源：http://dali.ivvv.top/Article/details/gtabpcafzb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.wangdashe.top/Article/details/gtpnwbnnsj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cashguo.top/Article/details/gtcpmuqjdv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zdqjudy.top/Article/details/gtjecpzngx.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigfzy.top/Article/details/gtdnhuffqg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.birdmap.top/Article/details/gtwqwfvrxj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cheryme.top/Article/details/gtoomyiglc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.fzhhl.top/Article/details/gtrusljyeo.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ydzc1.top/Article/details/gtakxsvrfs.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cqqwz.cn/Article/details/gtwgvptdha.html

[E06] 替换子串
来源：http://dali.hammf.cn/Article/details/gtgowqxqqu.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.wangshuangyany.cn/Article/details/gthyrsxnlo.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yuxming.cn/Article/details/gtbybcysug.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtesdvsqkj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtiszhljgk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtxbjtwxor.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hfpthk.cn/Article/details/gtmnzaecbx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtglrcabth.html

C#:   s.Replace("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwxfukpal.html

[E07] 按分隔符拆分
来源：http://dali.jianghu66.top/Article/details/gtbgkbrexp.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.smart0.xyz/Article/details/gtoliornqq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cheryme.top/Article/details/gtfehnzleu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhiwuduotai.top/Article/details/gtpgzfhkmu.html

TS:   s.split(",")
来源：http://dali.dashuyun.cn/Article/details/gthvsthvup.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.aibaodan.cn/Article/details/gttchojkhy.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhoulong.xyz/Article/details/gtwdufekzt.html

Ruby: s.split(",");  s.split
来源：http://dali.fzhhl.top/Article/details/gtcbljruth.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.pycfn.com/Article/details/gtakmliyea.html

[E08] 数组按分隔符合并
来源：http://dali.yanxiufei.cn/Article/details/gtvhiiedew.html

Py:   ",".join(items)
来源：http://dali.xuanzx.com/Article/details/gtynutazfp.html

PHP:  implode(",", $items);
来源：http://dali.yj202588.top/Article/details/gtvnnhjekg.html

JS:   items.join(",")
来源：http://dali.vqdsnc.cn/Article/details/gtbfnrgfpb.html

TS:   items.join(",")
来源：http://dali.cheryme.top/Article/details/gtiedfhpig.html

Java: String.join(",", items)
来源：http://dali.bjfxy.top/Article/details/gtfsaftiim.html

Go:   strings.Join(items, ",")
来源：http://dali.ydzc1.top/Article/details/gtwmfvhiao.html

Ruby: items.join(",")
来源：http://dali.yonumen.top/Article/details/gtswqzdeia.html

C#:   string.Join(",", items)
来源：http://dali.bjfxy.top/Article/details/gtfrpvmhus.html

[E09] 去除所有空白字符
来源：http://dali.shangyingyoupin.top/Article/details/gtbfuwreoh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.chenlongwang.top/Article/details/gtraktniuv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ivvv.top/Article/details/gtwgkwebsd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.9152youxi.cn/Article/details/gtqezdksde.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yuxming.cn/Article/details/gtpwoffeca.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ydzc1.top/Article/details/gtciihpmge.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiunpyfzk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinqigufen.top/Article/details/gtonppuhpi.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.chenjidiqi.icu/Article/details/gtylqinsii.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj20258888.top/Article/details/gtmacandaf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cashguo.top/Article/details/gtrushrrdu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sweek.top/Article/details/gttqvbmbsa.html

JS:   "7".padStart(3, "0")
来源：http://dali.shangyingyoupin.top/Article/details/gtcdwmcphu.html

TS:   "7".padStart(3, "0")
来源：http://dali.birdmap.top/Article/details/gtnpemcwet.html

Java: String.format("%03d", 7)
来源：http://dali.yueranfly.top/Article/details/gtwmiqichh.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoqqbmfgb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yongpay.top/Article/details/gthshfwcbm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yuxming.cn/Article/details/gtapicykbq.html

[E11] 反转字符串
来源：http://dali.c1oappe.top/Article/details/gtbkqbwute.html

Py:   s[::-1]
来源：http://dali.tian-w.cn/Article/details/gtxjusttsv.html

PHP:  strrev($s);
来源：http://dali.mhx1999.top/Article/details/gtynydtblc.html

JS:   [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gtzozbgxct.html

TS:   [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gtlnepyxpv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shzxlz.cn/Article/details/gtgmjrbncx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.kuanghao11.cn/Article/details/gtgnkupigu.html

Ruby: s.reverse
来源：http://dali.sxryk.cn/Article/details/gtzxortzga.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hywenlv.cn/Article/details/gthqwbsmrg.html

[E12] 统计某字符出现次数
来源：http://dali.chenjidiqi.icu/Article/details/gtjyibqnjr.html

Py:   s.count("a")
来源：http://dali.jlsjyb.cn/Article/details/gtxxxkohro.html

PHP:  substr_count($s, "a");
来源：http://dali.nwbrower.top/Article/details/gtbifqzflk.html

JS:   s.split("a").length - 1
来源：http://dali.mhx1999.top/Article/details/gtvjaqxhmz.html

TS:   s.split("a").length - 1
来源：http://dali.kuanghao11.cn/Article/details/gtbcothfyl.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhiwuduotai.top/Article/details/gtmkwqfdda.html

Go:   strings.Count(s, "a")
来源：http://dali.chenzaomai.com/Article/details/gtrjknlbhh.html

Ruby: s.count("a")
来源：http://dali.zhoulong.xyz/Article/details/gtqnkxyepb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gotoacloud.top/Article/details/gtxstjjapt.html

[E13] 逐字符遍历
来源：http://dali.tian-w.cn/Article/details/gtecabirux.html

Py:   for ch in s: print(ch)
来源：http://dali.bjfxy.top/Article/details/gtnlskwwqc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.redwolf501.top/Article/details/gtplawgizc.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.haohaochexian.top/Article/details/gtfniwnfbx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.redwolf501.top/Article/details/gtosikuvqm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xinyue.icu/Article/details/gtluwvouoa.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.316326.xyz/Article/details/gtvldhvwth.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.tianlin.xyz/Article/details/gthllfinok.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gtcuptzeil.html

[E14] URL 编码与 Base64
来源：http://dali.svipenyu.cn/Article/details/gtuyjpufnx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ybcxt.top/Article/details/gtoetdtsga.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.pycfn.com/Article/details/gtlaymndfa.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cqqwz.cn/Article/details/gtbjrqlwgs.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yongpay.top/Article/details/gtqodlhpnn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shzxlz.cn/Article/details/gtqhixddxb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinqigufen.top/Article/details/gtmmfvybss.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nanxinkj.top/Article/details/gtcnbipzyb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.quarkkingdee.top/Article/details/gtdakqrbjs.html

[E15] HTML 转义 / 反转义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtknhqmtbu.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtberwtgac.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jiagoushi.top/Article/details/gtjymufqca.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhengqikj.top/Article/details/gtsmnkjung.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.birdmap.top/Article/details/gtnvyxfrnn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.birdmap.top/Article/details/gtfeakulkm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.fzhhl.top/Article/details/gtdosdtwrs.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yj20258.top/Article/details/gttcbequeo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.pengpengdd.cyou/Article/details/gthdkctjwt.html

[E16] 数字千分位
来源：http://dali.haohaochexian.top/Article/details/gtraxkoufg.html

Py:   f"{1234567:,}"
来源：http://dali.ehwqpu.com/Article/details/gtozlwabfb.html

PHP:  number_format(1234567);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsrmszxxp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gzhubu.top/Article/details/gtcpsnpuyq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.guannengcc.top/Article/details/gtclfigwyq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.haohaochexian.top/Article/details/gtfrwpjkjm.html


<!-- 参考信息 -->