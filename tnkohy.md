代发 wailian999

PHP:  sort($arr);
来源：http://dali.tian-w.cn/Article/details/gt2yrsiinvq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lqzmuumm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hysaishi.cn/Article/details/gt2lcxpymqk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.feifeiyinyue.top/Article/details/gt2znihixdb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.guannengcc.top/Article/details/gt2twhnwkvd.html

Ruby: arr.sort
来源：http://dali.nanxinkj.top/Article/details/gt2kvyjrupl.html

C#:   list.Sort();
来源：http://dali.chenzaomai.com/Article/details/gt2deurqigd.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cqqwz.cn/Article/details/gt2nyhrtxnu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.guowangkeji.top/Article/details/gt2qzjcznqz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hywenlv.cn/Article/details/gt2sshsiqva.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shzxlz.cn/Article/details/gt2rvwrlxlp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258888.top/Article/details/gt2klytzyff.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.redwolf501.top/Article/details/gt2cmibgdii.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.nwbrower.top/Article/details/gt2bwrzznbd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hysaishi.cn/Article/details/gt2favxbjmf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cucudq.cn/Article/details/gt2tvkpgemo.html

[D11] 反转数组
来源：http://dali.zycfv.cn/Article/details/gt2nwlkpzyf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.0kj1m.cn/Article/details/gt2jyyjvivn.html

PHP:  array_reverse($arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2udcupwzd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yangfankeji.com/Article/details/gt2fodxnhqp.html

TS:   [...arr].reverse();
来源：http://dali.cucudq.cn/Article/details/gt2etywiuzh.html

Java: Collections.reverse(list);
来源：http://dali.jyoumei.cn/Article/details/gt2ngfvynax.html

Go:   slices.Reverse(arr)
来源：http://dali.meibo888.top/Article/details/gt2uebdrupz.html

Ruby: arr.reverse
来源：http://dali.iojbl.cn/Article/details/gt2qausqhpw.html

C#:   list.Reverse();
来源：http://dali.hnxiangtu.top/Article/details/gt2bfoybjhm.html

[D12] 查找元素下标
来源：http://dali.yvedp.cn/Article/details/gt2jotzeail.html

Py:   arr.index(x);  x in arr
来源：http://dali.jqgfzy.top/Article/details/gt2wbvteesg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinqigufen.top/Article/details/gt2magpcgfz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenzaomai.com/Article/details/gt2ounwzbpr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigufen.top/Article/details/gt2utjqtnpu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.wangdashe.top/Article/details/gt2vicsfird.html

Go:   slices.Index(arr, x)
来源：http://dali.meibo888.top/Article/details/gt2nbyfebqc.html

Ruby: arr.index(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2advglmhw.html

C#:   list.IndexOf(x);
来源：http://dali.jqgufenzy.top/Article/details/gt2bdmrnxcd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2piiiafsx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yuanzhike.top/Article/details/gt2wvsycffm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ivvv.top/Article/details/gt2btxvfwbr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yanxiufei.cn/Article/details/gt2llxeshik.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zdqjudy.top/Article/details/gt2nuudqpdc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.c1oappe.top/Article/details/gt2ybwloxiv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinqigufen.top/Article/details/gt2byxaucno.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tanke756.top/Article/details/gt2vfernydt.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xuanzx.com/Article/details/gt2wbdhlavr.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj202588.top/Article/details/gt2hokpewin.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.snrcjt.cn/Article/details/gt2fuiutnkx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.tianlin.xyz/Article/details/gt2jceuaxlq.html

JS:   arr.map(x => x * 2)
来源：http://dali.gotoacloud.top/Article/details/gt2dyhzfbgb.html

TS:   arr.map(x => x * 2)
来源：http://dali.ppjwa.cn/Article/details/gt2kazxfxqh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.mhx1999.top/Article/details/gt2ydvdhoyc.html

Go:   // 手写循环
来源：http://dali.kuanghao11.cn/Article/details/gt2nakycysq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jiagoushi.top/Article/details/gt2mhpqnlxs.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.iojbl.cn/Article/details/gt2qubgscld.html

[D15] 去重
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rqkkaqqa.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.wangdashe.top/Article/details/gt2lelhpcju.html

PHP:  array_unique($arr);
来源：http://dali.cashguo.top/Article/details/gt2auaeighn.html

JS:   [...new Set(arr)]
来源：http://dali.jlsjyb.cn/Article/details/gt2gtxicivu.html

TS:   [...new Set(arr)]
来源：http://dali.sweek.top/Article/details/gt2fceqmych.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cdnleiting.top/Article/details/gt2vewmevcp.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.chenjidiqi.icu/Article/details/gt2qpspkwhq.html

Ruby: arr.uniq
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mhyjeasq.html

C#:   list.Distinct().ToList()
来源：http://dali.tian-w.cn/Article/details/gt2jnhjwlws.html

[D16] 求和与平均值
来源：http://dali.zhengqikj.top/Article/details/gt2fcgribfi.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mabmzmtz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vzumqfej.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.mhx1999.top/Article/details/gt2paogyidu.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.bjfxy.top/Article/details/gt2jeteghqc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ssrtezbt.html

Go:   // 手写循环累加
来源：http://dali.xylfe.cn/Article/details/gt2dltwjghr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ppjwa.cn/Article/details/gt2yuspkxsp.html

C#:   list.Sum();  list.Average()
来源：http://dali.zdqjudy.top/Article/details/gt2jxkbzjqa.html

[D17] 最大值与最小值
来源：http://dali.cqqwz.cn/Article/details/gt2vgqwnjhy.html

Py:   max(arr);  min(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2czyrlnqg.html

PHP:  max($arr);  min($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2hrzowmtx.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hysaishi.cn/Article/details/gt2fublrunn.html

TS:   Math.max(...arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2soccdifw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.fzhhl.top/Article/details/gt2spaffwqz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hnqzz.top/Article/details/gt2gpxjgxyl.html

Ruby: arr.max;  arr.min
来源：http://dali.hnqzz.top/Article/details/gt2pgdlxpjh.html

C#:   list.Max();  list.Min()
来源：http://dali.cheryme.top/Article/details/gt2gpfxldte.html

[D18] 扁平化嵌套数组
来源：http://dali.smart0.xyz/Article/details/gt2ccxcwsik.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.guannengcc.top/Article/details/gt2gloffktx.html

PHP:  array_merge(...$nested);
来源：http://dali.zhixingplan.top/Article/details/gt2kntzunvl.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sufxvd.cn/Article/details/gt2lrwuojhe.html

TS:   nested.flat();
来源：http://dali.svipenyu.cn/Article/details/gt2kgifywmj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhengqikj.top/Article/details/gt2llohcseo.html

Go:   // 手写双层循环
来源：http://dali.andypj.xyz/Article/details/gt2svbwkkhh.html

Ruby: nested.flatten
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qjeorhpu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yangfankeji.com/Article/details/gt2dvudrfbb.html

[D19] 按字段分组
来源：http://dali.dianchejie.cn/Article/details/gt2smcpabqq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ydzc1.top/Article/details/gt2rlxilcuh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.fengsongda.top/Article/details/gt2vfjayyng.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rbqdesii.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cucudq.cn/Article/details/gt2esuxgzey.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.9152youxi.cn/Article/details/gt2nunimgei.html

Go:   // 手写 map[string][]T
来源：http://dali.gotoacloud.top/Article/details/gt2mlrgazpc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cdnleiting.top/Article/details/gt2fvqnxvee.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.9152youxi.cn/Article/details/gt2djhqucai.html

[D20] 统计每个元素出现次数
来源：http://dali.yonumen.top/Article/details/gt2icnvjhsd.html

Py:   Counter(arr)
来源：http://dali.haohaochexian.top/Article/details/gt2otkhywkt.html

PHP:  array_count_values($arr);
来源：http://dali.hysaishi.cn/Article/details/gt2dolowkxg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oblkahzn.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuanzhike.top/Article/details/gt2wrqdvuxv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ivvv.top/Article/details/gt2xneawpdg.html

Go:   // 手写 map[T]int
来源：http://dali.yuanzhike.top/Article/details/gt2wsobtyok.html

Ruby: arr.tally
来源：http://dali.hnxiangtu.top/Article/details/gt2qyrudlux.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.chenzaomai.com/Article/details/gt2jfdmfwyw.html

[D21] 判断是否包含某元素
来源：http://dali.yonumen.top/Article/details/gt2redlagag.html

Py:   x in arr
来源：http://dali.guowangkeji.top/Article/details/gt2ffwhttvw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ttwdwiwj.html

JS:   arr.includes(x)
来源：http://dali.ivvv.top/Article/details/gt2sblstlae.html

TS:   arr.includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xrvxvodf.html

Java: list.contains(x)
来源：http://dali.hysaishi.cn/Article/details/gt2pywmoswu.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkzrtjg.html

Ruby: arr.include?(x)
来源：http://dali.meibo888.top/Article/details/gt2ngqtuvhl.html

C#:   list.Contains(x)
来源：http://dali.yueranfly.top/Article/details/gt2pxbbvvmj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yueranfly.top/Article/details/gt2ybyrdrhu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2itfsytlu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yongpay.top/Article/details/gt2roslvuxy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2iegchpoz.html

TS:   [...arr];
来源：http://dali.jlsjyb.cn/Article/details/gt2elletsee.html

Java: new ArrayList<>(list);
来源：http://dali.ybcxt.top/Article/details/gt2zofngany.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.havefunace.top/Article/details/gt2gkfnbmqg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.tanke756.top/Article/details/gt2dqjdizfk.html

C#:   new List<int>(list);
来源：http://dali.cheryme.top/Article/details/gt2jehijsua.html

[D23] reduce 累积计算
来源：http://dali.ehwqpu.com/Article/details/gt2vawrfouy.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2fqzizuzt.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.tian-w.cn/Article/details/gt2azplvbmf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gt2nbxqfbdk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2elyptqrv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hnxiangtu.top/Article/details/gt2pdpiolkl.html

Go:   // 手写循环
来源：http://dali.cqqwz.cn/Article/details/gt2llrujopo.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ybcxt.top/Article/details/gt2hwqvkkrs.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jlsjyb.cn/Article/details/gt2pdgshzsw.html

[D24] 字典 / Map 基本操作
来源：http://dali.yuxming.cn/Article/details/gt2vqduldjr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.bjfxy.top/Article/details/gt2tffaicdo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.andypj.xyz/Article/details/gt2ucgmliqr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.dianchejie.cn/Article/details/gt2ezebznpt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gt2zmvnrveu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yueranfly.top/Article/details/gt2gwzsoqxe.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.guannengcc.top/Article/details/gt2dhjtakan.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.aizwys.cn/Article/details/gt2yckqanix.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yanxiufei.cn/Article/details/gt2keepkgek.html

[D25] Set 集合去重与交并差
来源：http://dali.chenzaomai.com/Article/details/gt2bgubceky.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.nwbrower.top/Article/details/gt2nfaalepm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cucudq.cn/Article/details/gt2iefoqemj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kmwyykly.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yonumen.top/Article/details/gt2zzqmhoxs.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fxarqvzs.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hammf.cn/Article/details/gt2bapzomxb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hfpthk.cn/Article/details/gt2pufqeabl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.bjfxy.top/Article/details/gt2xsefzwkt.html

[D26] 数组转字符串
来源：http://dali.cashguo.top/Article/details/gt2keslszhs.html

Py:   ", ".join(map(str, arr))
来源：http://dali.guowangkeji.top/Article/details/gt2ravwcidt.html

PHP:  implode(", ", $arr);
来源：http://dali.yonumen.top/Article/details/gt2txvxhvit.html

JS:   arr.join(", ")
来源：http://dali.cheryme.top/Article/details/gt2ffnnidrg.html

TS:   arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gt2ojkqdngg.html

Java: String.join(", ", list)
来源：http://dali.jqgufenzy.top/Article/details/gt2nuyrafdu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yanxiufei.cn/Article/details/gt2nysvbijf.html

Ruby: arr.join(", ")
来源：http://dali.xylfe.cn/Article/details/gt2mqyewfqe.html

C#:   string.Join(", ", list)
来源：http://dali.yj20258.top/Article/details/gt2xolqrfmc.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ftxyafmr.html

E. 字符串处理
来源：http://dali.xinyue.icu/Article/details/gt2yueijquw.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2gxxucmmi.html

[E01] 拼接字符串
来源：http://dali.wangdashe.top/Article/details/gt2pnjaoqgq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hongshengwenyu.top/Article/details/gt2zrgejxko.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yonumen.top/Article/details/gt2skcwqlwu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sysykeji.top/Article/details/gt2abgngmdh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhengqikj.top/Article/details/gt2qcqfdmep.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.aizwys.cn/Article/details/gt2eosmgobn.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cashguo.top/Article/details/gt2vccirmak.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.daxiang520.top/Article/details/gt2fcgdaaxr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.daxiang520.top/Article/details/gt2xwldiipf.html

[E02] 重复字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2navxfwbm.html

Py:   "ab" * 3
来源：http://dali.feifeiyinyue.top/Article/details/gt2zksbcdyv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhoulong.xyz/Article/details/gt2qhtkubox.html

JS:   "ab".repeat(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rsuwvhvb.html

TS:   "ab".repeat(3)
来源：http://dali.hfpthk.cn/Article/details/gt2yswagdim.html

Java: "ab".repeat(3)
来源：http://dali.yangfankeji.com/Article/details/gt2xuceinvy.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.fzhhl.top/Article/details/gt2hhnxqxjp.html

Ruby: "ab" * 3
来源：http://dali.yvedp.cn/Article/details/gt2uijhqtdr.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.pycfn.com/Article/details/gt2spchrhjp.html

[E03] 截取子串
来源：http://dali.cashguo.top/Article/details/gt2bpgjamrj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cucudq.cn/Article/details/gt2qlplpbfg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gt2raixwxyx.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ydzc1.top/Article/details/gt2huspgwmm.html

TS:   s.slice(1, 4)
来源：http://dali.jqgufenzy.top/Article/details/gt2cmrxedzw.html

Java: s.substring(1, 4)
来源：http://dali.redwolf501.top/Article/details/gt2guufiliy.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xuanzx.com/Article/details/gt2uepqaiex.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ybcxt.top/Article/details/gt2ceyrqdec.html

C#:   s.Substring(1, 3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2bjpekzun.html

[E04] 查找子串位置
来源：http://dali.ivvv.top/Article/details/gt2ftntqaqm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ivvv.top/Article/details/gt2vmnozjba.html

PHP:  strpos($s, "x");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qhfjpxto.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gotoacloud.top/Article/details/gt2vhgstfui.html

TS:   s.indexOf("x")
来源：http://dali.wangdashe.top/Article/details/gt2ddfpvtpu.html

Java: s.indexOf("x")
来源：http://dali.cashguo.top/Article/details/gt2seotssgh.html

Go:   strings.Index(s, "x")
来源：http://dali.guowangkeji.top/Article/details/gt2czwtynfj.html

Ruby: s.index("x")
来源：http://dali.zhixingplan.top/Article/details/gt2ouzwghkm.html

C#:   s.IndexOf("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fyueckze.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.feifeiyinyue.top/Article/details/gt2aathvxam.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gt2kxpvwzwo.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jqgfzy.top/Article/details/gt2lvvymnfp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnxiangtu.top/Article/details/gt2comwmhot.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.bjfxy.top/Article/details/gt2savzzxdj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sxzffqpm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yj202588.top/Article/details/gt2evmwznhd.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.andypj.xyz/Article/details/gt2tkojpome.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.meibo888.top/Article/details/gt2rehgfmwd.html

[E06] 替换子串
来源：http://dali.redwolf501.top/Article/details/gt2clrvuvaq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xinyue.icu/Article/details/gt2sacftihu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.svipenyu.cn/Article/details/gt2lmiocyal.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gt2syijfbhe.html

TS:   s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gt2yueketkm.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.smart0.xyz/Article/details/gt2vnxivqri.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.pycfn.com/Article/details/gt2jterkphz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gt2rmmdwjqv.html

C#:   s.Replace("a", "b")
来源：http://dali.birdmap.top/Article/details/gt2ekmqqpvj.html

[E07] 按分隔符拆分
来源：http://dali.xinyue.icu/Article/details/gt2iqhytkgu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gzhubu.top/Article/details/gt2onbuonfg.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hywenlv.cn/Article/details/gt2ijslusms.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhoulong.xyz/Article/details/gt2wijfbbcd.html

TS:   s.split(",")
来源：http://dali.fzhhl.top/Article/details/gt2rgwhlflc.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qxvdaxsk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hfpthk.cn/Article/details/gt2gvthjcoo.html

Ruby: s.split(",");  s.split
来源：http://dali.zdqjudy.top/Article/details/gt2utlptkza.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cashguo.top/Article/details/gt2iyggwnqh.html

[E08] 数组按分隔符合并
来源：http://dali.dashuyun.cn/Article/details/gt2bsdmvmuo.html

Py:   ",".join(items)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vkfbhioy.html

PHP:  implode(",", $items);
来源：http://dali.zhengqikj.top/Article/details/gt2yqlheohc.html

JS:   items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gt2ilesllni.html

TS:   items.join(",")
来源：http://dali.svipenyu.cn/Article/details/gt2iqvycexd.html

Java: String.join(",", items)
来源：http://dali.hnxiangtu.top/Article/details/gt2phbqkdtt.html

Go:   strings.Join(items, ",")
来源：http://dali.jiagoushi.top/Article/details/gt2vknqwvht.html

Ruby: items.join(",")
来源：http://dali.sufxvd.cn/Article/details/gt2wwvgvnkn.html

C#:   string.Join(",", items)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fdhsktsb.html

[E09] 去除所有空白字符
来源：http://dali.yuanzhike.top/Article/details/gt2xwamnjwr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eycuaejq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.dashuyun.cn/Article/details/gt2znuazkxp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hongshengwenyu.top/Article/details/gt2tvfcfiaj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ukgvqyrs.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.guowangkeji.top/Article/details/gt2cgngktzt.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.nwbrower.top/Article/details/gt2emolhtvn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jqgufenzy.top/Article/details/gt2neoigbgi.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mccybcyc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.nwbrower.top/Article/details/gt2kfnvvndw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hammf.cn/Article/details/gt2tdaciekw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhengqikj.top/Article/details/gt2qrotokcc.html

JS:   "7".padStart(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gt2qwjhadrz.html

TS:   "7".padStart(3, "0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2reljwjzu.html

Java: String.format("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gt2wlzwknny.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gt2vawbaduw.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gt2feuvayiw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cqqwz.cn/Article/details/gt2zufqsxgl.html

[E11] 反转字符串
来源：http://dali.tianlin.xyz/Article/details/gt2lbdjrmqq.html

Py:   s[::-1]
来源：http://dali.xuetiantiany.cn/Article/details/gt2wleccezn.html

PHP:  strrev($s);
来源：http://dali.316326.xyz/Article/details/gt2xeleknpz.html

JS:   [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gt2chpaabua.html

TS:   [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gt2mrxabemo.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.c1oappe.top/Article/details/gt2vpojzklm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.pengpengdd.cyou/Article/details/gt2yxujssre.html

Ruby: s.reverse
来源：http://dali.xylfe.cn/Article/details/gt2gywaznhp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sysykeji.top/Article/details/gt2qpfncuyw.html

[E12] 统计某字符出现次数
来源：http://dali.hywenlv.cn/Article/details/gt2bnzccpgd.html

Py:   s.count("a")
来源：http://dali.xinyue.icu/Article/details/gt2bohmqxei.html

PHP:  substr_count($s, "a");
来源：http://dali.shuidangran.top/Article/details/gt2vfehztca.html

JS:   s.split("a").length - 1
来源：http://dali.ppjwa.cn/Article/details/gt2qkhxenkw.html

TS:   s.split("a").length - 1
来源：http://dali.yvedp.cn/Article/details/gt2brdzeubw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.fzhhl.top/Article/details/gt2ojxhruwp.html

Go:   strings.Count(s, "a")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2inmzlcyg.html

Ruby: s.count("a")
来源：http://dali.hnxiangtu.top/Article/details/gt2jfldelxn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yonumen.top/Article/details/gt2qmkaegng.html

[E13] 逐字符遍历
来源：http://dali.cheryme.top/Article/details/gt2qfccafob.html

Py:   for ch in s: print(ch)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ngalzdlk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.havefunace.top/Article/details/gt2xbpqslcq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daria6918.cn/Article/details/gt2wfkgmkxo.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gt2twkiyeif.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.pycfn.com/Article/details/gt2ugxcsath.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhongyouzk.top/Article/details/gt2geetheyp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lzovceev.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenzaomai.com/Article/details/gt2kaqfiasl.html

[E14] URL 编码与 Base64
来源：http://dali.guannengcc.top/Article/details/gt2kovlgolq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tian-w.cn/Article/details/gt2eusgbegc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xylfe.cn/Article/details/gt2trodsjex.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj202588.top/Article/details/gt2bkptrtjp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.andypj.xyz/Article/details/gt2ztxujtrn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xuanzx.com/Article/details/gt2haxudsqk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.haohaochexian.top/Article/details/gt2jjohldoc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhiwuduotai.top/Article/details/gt2jzrctznf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.0kj1m.cn/Article/details/gt2pwjziioj.html

[E15] HTML 转义 / 反转义
来源：http://dali.xziqi.cn/Article/details/gt2ksibwfgm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.c1oappe.top/Article/details/gt2ybtrchnf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.smart0.xyz/Article/details/gt2scgyneyr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2rjwuiqje.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hammf.cn/Article/details/gt2ywvonahj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.dashuyun.cn/Article/details/gt2vahvedqx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvlhzyij.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yongpay.top/Article/details/gt2frzxlloy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2lzoayofu.html

[E16] 数字千分位
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ahaegode.html

Py:   f"{1234567:,}"
来源：http://dali.yongpay.top/Article/details/gt2wwhprasp.html


<!-- 参考信息 -->