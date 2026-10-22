代发 wailian999

Ruby: a + b;  a.concat(b)
来源：http://dali.gogol.net.cn/Article/details/gt2rtwpyzuz.html

C#:   a.Concat(b).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gt2hrcdigny.html

[D09] 排序（升序）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hbxipeeg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gqeetbeo.html

PHP:  sort($arr);
来源：http://dali.aizwys.cn/Article/details/gt2xilmctbi.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yvedp.cn/Article/details/gt2gkudknsk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jqgufenzy.top/Article/details/gt2hdvftcqt.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhoulong.xyz/Article/details/gt2hvrlbdbq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yvedp.cn/Article/details/gt2hzawzllp.html

Ruby: arr.sort
来源：http://dali.haohaochexian.top/Article/details/gt2omudedns.html

C#:   list.Sort();
来源：http://dali.xinyue.icu/Article/details/gt2riylcbnl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yvedp.cn/Article/details/gt2dupkfcja.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinqigufen.top/Article/details/gt2dybetwmq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yongpay.top/Article/details/gt2unetdmkz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daria6918.cn/Article/details/gt2jrilbjri.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.smart0.xyz/Article/details/gt2yvpaehgp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.daxiang520.top/Article/details/gt2zhipvwsp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.tanke756.top/Article/details/gt2fugsofza.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xuanzx.com/Article/details/gt2jaenmslh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ivvv.top/Article/details/gt2jeeowudd.html

[D11] 反转数组
来源：http://dali.316326.xyz/Article/details/gt2ooxqyosj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cqqwz.cn/Article/details/gt2htsezqhw.html

PHP:  array_reverse($arr);
来源：http://dali.wangdashe.top/Article/details/gt2uddcdhaf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhixingplan.top/Article/details/gt2twbsivfg.html

TS:   [...arr].reverse();
来源：http://dali.yvedp.cn/Article/details/gt2ooazxily.html

Java: Collections.reverse(list);
来源：http://dali.meibo888.top/Article/details/gt2xruccdmj.html

Go:   slices.Reverse(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2juoestrf.html

Ruby: arr.reverse
来源：http://dali.kuanghao11.cn/Article/details/gt2svshnzvw.html

C#:   list.Reverse();
来源：http://dali.bjfxy.top/Article/details/gt2umvqdyad.html

[D12] 查找元素下标
来源：http://dali.ivvv.top/Article/details/gt2nvokelmb.html

Py:   arr.index(x);  x in arr
来源：http://dali.aibaodan.cn/Article/details/gt2valrvbrn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yuanzhike.top/Article/details/gt2xdxqnwuh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sufxvd.cn/Article/details/gt2kkdxacjf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.c1oappe.top/Article/details/gt2bpdwdewi.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ehwqpu.com/Article/details/gt2divnxgra.html

Go:   slices.Index(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ljpudhlz.html

Ruby: arr.index(x)
来源：http://dali.mhx1999.top/Article/details/gt2kigrjjal.html

C#:   list.IndexOf(x);
来源：http://dali.gogol.net.cn/Article/details/gt2kneoorcy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zdqjudy.top/Article/details/gt2qmnprmkm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.tanke756.top/Article/details/gt2xtdlcqtu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.316326.xyz/Article/details/gt2baqmobog.html

JS:   arr.filter(x => x > 3)
来源：http://dali.9152youxi.cn/Article/details/gt2opftyiwf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhoulong.xyz/Article/details/gt2riubgicc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zdqjudy.top/Article/details/gt2zajrouig.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.vqdsnc.cn/Article/details/gt2lfsfpqtq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.svipenyu.cn/Article/details/gt2mnnrhqra.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ppjwa.cn/Article/details/gt2jgnnkqkp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.daria6918.cn/Article/details/gt2uzyzdwjo.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shangyingyoupin.top/Article/details/gt2mbmmdwqu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cdnleiting.top/Article/details/gt2fgqninxi.html

JS:   arr.map(x => x * 2)
来源：http://dali.0kj1m.cn/Article/details/gt2sbppzanb.html

TS:   arr.map(x => x * 2)
来源：http://dali.fzhhl.top/Article/details/gt2jhgubwgz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jlsjyb.cn/Article/details/gt2urzjhmyw.html

Go:   // 手写循环
来源：http://dali.yueranfly.top/Article/details/gt2kxidyjla.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yj20258888.top/Article/details/gt2oedmxawv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rnkvarfq.html

[D15] 去重
来源：http://dali.jianghu66.top/Article/details/gt2dhybarso.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yangfankeji.com/Article/details/gt2yeceroiu.html

PHP:  array_unique($arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2zprkbyws.html

JS:   [...new Set(arr)]
来源：http://dali.yueranfly.top/Article/details/gt2ewmggnwf.html

TS:   [...new Set(arr)]
来源：http://dali.zhongyouzk.top/Article/details/gt2odzzvnpq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.guowangkeji.top/Article/details/gt2ayvbfgmv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yongpay.top/Article/details/gt2xbjtgcrx.html

Ruby: arr.uniq
来源：http://dali.gotoacloud.top/Article/details/gt2fzttfzkt.html

C#:   list.Distinct().ToList()
来源：http://dali.chenzaomai.com/Article/details/gt2uwadybko.html

[D16] 求和与平均值
来源：http://dali.gzhubu.top/Article/details/gt2rzohkaxv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2zofvnxso.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2spavjemk.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tian-w.cn/Article/details/gt2kzqonfnt.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.meibo888.top/Article/details/gt2hnzmnhmf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yangfankeji.com/Article/details/gt2bavalyuy.html

Go:   // 手写循环累加
来源：http://dali.yangfankeji.com/Article/details/gt2sdcweizn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.mhx1999.top/Article/details/gt2nodkfagq.html

C#:   list.Sum();  list.Average()
来源：http://dali.mhx1999.top/Article/details/gt2izxixipa.html

[D17] 最大值与最小值
来源：http://dali.zhengqikj.top/Article/details/gt2iriakfhm.html

Py:   max(arr);  min(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2kjxabajn.html

PHP:  max($arr);  min($arr);
来源：http://dali.9152youxi.cn/Article/details/gt2ukeqqmmt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zfvmhzoq.html

TS:   Math.max(...arr);
来源：http://dali.ehwqpu.com/Article/details/gt2vnpbllpk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zycfv.cn/Article/details/gt2noflzpja.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.aizwys.cn/Article/details/gt2wbpkawkc.html

Ruby: arr.max;  arr.min
来源：http://dali.wangshuangyany.cn/Article/details/gt2dnujhuzw.html

C#:   list.Max();  list.Min()
来源：http://dali.zhixingplan.top/Article/details/gt2xqjiegnl.html

[D18] 扁平化嵌套数组
来源：http://dali.guowangkeji.top/Article/details/gt2tcxkvswq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.aizwys.cn/Article/details/gt2bxogjfcx.html

PHP:  array_merge(...$nested);
来源：http://dali.yueranfly.top/Article/details/gt2cvkeiwpq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yueranfly.top/Article/details/gt2sdazcsjn.html

TS:   nested.flat();
来源：http://dali.sufxvd.cn/Article/details/gt2risuwuqv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sufxvd.cn/Article/details/gt2tpeibyge.html

Go:   // 手写双层循环
来源：http://dali.cqqwz.cn/Article/details/gt2ieqrvajl.html

Ruby: nested.flatten
来源：http://dali.daxiang520.top/Article/details/gt2yokuweza.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.fzhhl.top/Article/details/gt2jsietklc.html

[D19] 按字段分组
来源：http://dali.aizwys.cn/Article/details/gt2ujscmnqz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2rnqkyezj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yangfankeji.com/Article/details/gt2sppqosgw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.aibaodan.cn/Article/details/gt2mxadefvj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hjubfxvz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2issoyznf.html

Go:   // 手写 map[string][]T
来源：http://dali.haohaochexian.top/Article/details/gt2zcnbujtb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxwycgy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.chenjidiqi.icu/Article/details/gt2edibunxs.html

[D20] 统计每个元素出现次数
来源：http://dali.wangdashe.top/Article/details/gt2xruyqedm.html

Py:   Counter(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2yqivxkuk.html

PHP:  array_count_values($arr);
来源：http://dali.zhixingplan.top/Article/details/gt2ukwlqrit.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sxryk.cn/Article/details/gt2opskvpzp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xinyue.icu/Article/details/gt2wqqtafhr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhiwuduotai.top/Article/details/gt2oxhbjixz.html

Go:   // 手写 map[T]int
来源：http://dali.andypj.xyz/Article/details/gt2ocxkvfdt.html

Ruby: arr.tally
来源：http://dali.iojbl.cn/Article/details/gt2cgdezyda.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.kuanghao11.cn/Article/details/gt2kpkyldmf.html

[D21] 判断是否包含某元素
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vywzoknq.html

Py:   x in arr
来源：http://dali.hammf.cn/Article/details/gt2rzvcrzoe.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shzxlz.cn/Article/details/gt2mqinsoua.html

JS:   arr.includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2oujvorjp.html

TS:   arr.includes(x)
来源：http://dali.andypj.xyz/Article/details/gt2jseanppw.html

Java: list.contains(x)
来源：http://dali.birdmap.top/Article/details/gt2btjroath.html

Go:   slices.Contains(arr, x)
来源：http://dali.xinyue.icu/Article/details/gt2bzbzawdu.html

Ruby: arr.include?(x)
来源：http://dali.aizwys.cn/Article/details/gt2kvaxaxce.html

C#:   list.Contains(x)
来源：http://dali.andypj.xyz/Article/details/gt2cgxurgqt.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gzhubu.top/Article/details/gt2svlhaqom.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.tian-w.cn/Article/details/gt2vfphyocr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yanxiufei.cn/Article/details/gt2nciupibv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2yoeiibld.html

TS:   [...arr];
来源：http://dali.yvedp.cn/Article/details/gt2zfcwewbt.html

Java: new ArrayList<>(list);
来源：http://dali.tianlin.xyz/Article/details/gt2mrbpzyti.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gctychmz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jqgufenzy.top/Article/details/gt2sxlpaufs.html

C#:   new List<int>(list);
来源：http://dali.yvedp.cn/Article/details/gt2jytgbyow.html

[D23] reduce 累积计算
来源：http://dali.snrcjt.cn/Article/details/gt2thcdqmtm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.9152youxi.cn/Article/details/gt2loojvrxi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2uhafybjt.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2fvljozvf.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.meibo888.top/Article/details/gt2azazlxre.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sleagfip.html

Go:   // 手写循环
来源：http://dali.haohaochexian.top/Article/details/gt2xnzlcbps.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.9152youxi.cn/Article/details/gt2iwogazjx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hammf.cn/Article/details/gt2nwnzhgcm.html

[D24] 字典 / Map 基本操作
来源：http://dali.nwbrower.top/Article/details/gt2gcfncwju.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhoulong.xyz/Article/details/gt2schpitdo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2jtqmfiwt.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xziqi.cn/Article/details/gt2czjzfkzh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gt2uszikaec.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.pengpengdd.cyou/Article/details/gt2zbutvnlq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sweek.top/Article/details/gt2jbwvshus.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yvedp.cn/Article/details/gt2xkinqypi.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinqigufen.top/Article/details/gt2ndreklda.html

[D25] Set 集合去重与交并差
来源：http://dali.wangdashe.top/Article/details/gt2gwutochr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.bjfxy.top/Article/details/gt2qzogkqkq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.redwolf501.top/Article/details/gt2qdgbndia.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.haohaochexian.top/Article/details/gt2rwydjqod.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yuanzhike.top/Article/details/gt2hbokppvj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.svipenyu.cn/Article/details/gt2sostieoa.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yuxming.cn/Article/details/gt2pcijggyz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gzhubu.top/Article/details/gt2asqcjsmk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xuanzx.com/Article/details/gt2wjszkzou.html

[D26] 数组转字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2kjitnpwq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.tanke756.top/Article/details/gt2btxzmkvk.html

PHP:  implode(", ", $arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2wdhmigio.html

JS:   arr.join(", ")
来源：http://dali.guannengcc.top/Article/details/gt2raydetyd.html

TS:   arr.join(", ")
来源：http://dali.0kj1m.cn/Article/details/gt2eillpkfh.html

Java: String.join(", ", list)
来源：http://dali.dianchejie.cn/Article/details/gt2cvusdwrh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sysykeji.top/Article/details/gt2rjzazsqz.html

Ruby: arr.join(", ")
来源：http://dali.guowangkeji.top/Article/details/gt2iyklzeic.html

C#:   string.Join(", ", list)
来源：http://dali.zhiwuduotai.top/Article/details/gt2pivtjskk.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2qrfkrnve.html

E. 字符串处理
来源：http://dali.gotoacloud.top/Article/details/gt2wrqainox.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2xdyocztm.html

[E01] 拼接字符串
来源：http://dali.cheryme.top/Article/details/gt2cooooekg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sufxvd.cn/Article/details/gt2ikgcgewg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ydzc1.top/Article/details/gt2tvgmqlxi.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gaohongyu789.top/Article/details/gt2rwgtevrp.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.guannengcc.top/Article/details/gt2ioltqlew.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xbsfasav.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yonumen.top/Article/details/gt2ojdpiqto.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.quarkkingdee.top/Article/details/gt2bkmuaeym.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.wangdashe.top/Article/details/gt2tgwihdwm.html

[E02] 重复字符串
来源：http://dali.hysaishi.cn/Article/details/gt2qsvumdpc.html

Py:   "ab" * 3
来源：http://dali.ppjwa.cn/Article/details/gt2fftyqsna.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shzxlz.cn/Article/details/gt2tatiqnli.html

JS:   "ab".repeat(3)
来源：http://dali.andypj.xyz/Article/details/gt2ztpjcvtw.html

TS:   "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gt2fwdnuizh.html

Java: "ab".repeat(3)
来源：http://dali.hnxiangtu.top/Article/details/gt2ndscvejt.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ggattlpb.html

Ruby: "ab" * 3
来源：http://dali.yvedp.cn/Article/details/gt2umvaudog.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shuidangran.top/Article/details/gt2sgubxszg.html

[E03] 截取子串
来源：http://dali.0kj1m.cn/Article/details/gt2hvnujeky.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yvedp.cn/Article/details/gt2qlaicnay.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shangyingyoupin.top/Article/details/gt2ymgdcnrx.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ovnkuzyq.html

TS:   s.slice(1, 4)
来源：http://dali.cashguo.top/Article/details/gt2nlpbcfch.html

Java: s.substring(1, 4)
来源：http://dali.yanxiufei.cn/Article/details/gt2tiaxomlt.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zdqjudy.top/Article/details/gt2ujzsvmgn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zycfv.cn/Article/details/gt2xngktuvz.html

C#:   s.Substring(1, 3)
来源：http://dali.ybcxt.top/Article/details/gt2uvskokip.html

[E04] 查找子串位置
来源：http://dali.cheryme.top/Article/details/gt2wlwvtcqd.html

Py:   s.find("x");  s.index("x")
来源：http://dali.tian-w.cn/Article/details/gt2bgtfpked.html

PHP:  strpos($s, "x");
来源：http://dali.xinyue.icu/Article/details/gt2bibywgdn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.redwolf501.top/Article/details/gt2xirkhwck.html

TS:   s.indexOf("x")
来源：http://dali.gotoacloud.top/Article/details/gt2vasuwsli.html

Java: s.indexOf("x")
来源：http://dali.sweek.top/Article/details/gt2rsypeogw.html

Go:   strings.Index(s, "x")
来源：http://dali.ivvv.top/Article/details/gt2ixdaikfs.html

Ruby: s.index("x")
来源：http://dali.iojbl.cn/Article/details/gt2zfvljzdz.html

C#:   s.IndexOf("x")
来源：http://dali.gogol.net.cn/Article/details/gt2inuqjxwq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.iojbl.cn/Article/details/gt2wclvrwnu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.svipenyu.cn/Article/details/gt2lbmrjfyc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qrlaxtqd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gaohongyu789.top/Article/details/gt2lbfbqtdk.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hywenlv.cn/Article/details/gt2qfjexybm.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fzhhl.top/Article/details/gt2yvlrqlut.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jiagoushi.top/Article/details/gt2kuftejev.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.tanke756.top/Article/details/gt2rulrvumd.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.nwbrower.top/Article/details/gt2yzfkohsh.html

[E06] 替换子串
来源：http://dali.guannengcc.top/Article/details/gt2fkaofjyv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yuanzhike.top/Article/details/gt2xbaidxey.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sweek.top/Article/details/gt2kilqripn.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gt2wkjwksmz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gt2ickxojtt.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uonoztvv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jqgfzy.top/Article/details/gt2ydapzdtr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.tian-w.cn/Article/details/gt2lgwnstqw.html

C#:   s.Replace("a", "b")
来源：http://dali.ybcxt.top/Article/details/gt2oxresgcp.html

[E07] 按分隔符拆分
来源：http://dali.0kj1m.cn/Article/details/gt2swioeovu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shzxlz.cn/Article/details/gt2tgsfkukl.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.chenlongwang.top/Article/details/gt2wglxpjem.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jqgufenzy.top/Article/details/gt2ecviwmpb.html

TS:   s.split(",")
来源：http://dali.wangdashe.top/Article/details/gt2jkgtusgl.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.redwolf501.top/Article/details/gt2vxmdxhck.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.aibaodan.cn/Article/details/gt2eiuutyns.html

Ruby: s.split(",");  s.split
来源：http://dali.sweek.top/Article/details/gt2waalnpxv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yuanzhike.top/Article/details/gt2rbbabmqf.html

[E08] 数组按分隔符合并
来源：http://dali.xuetiantiany.cn/Article/details/gt2nlxqsrtk.html

Py:   ",".join(items)
来源：http://dali.hnxiangtu.top/Article/details/gt2erctfpoc.html

PHP:  implode(",", $items);
来源：http://dali.sysykeji.top/Article/details/gt2btadggvm.html

JS:   items.join(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2slhmjfbt.html

TS:   items.join(",")
来源：http://dali.cheryme.top/Article/details/gt2wdmrqvdc.html

Java: String.join(",", items)
来源：http://dali.yongpay.top/Article/details/gt2tucmipzu.html

Go:   strings.Join(items, ",")
来源：http://dali.kuanghao11.cn/Article/details/gt2bllifglg.html

Ruby: items.join(",")
来源：http://dali.yongpay.top/Article/details/gt2znbmaxpi.html

C#:   string.Join(",", items)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qjuwwbtj.html

[E09] 去除所有空白字符
来源：http://dali.wangshuangyany.cn/Article/details/gt2cmecgjvc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.chenlongwang.top/Article/details/gt2azmjnjzt.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2bdkgxcar.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.snrcjt.cn/Article/details/gt2pbbhjfrq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yj20258.top/Article/details/gt2vxrmfrnw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.havefunace.top/Article/details/gt2dxxanvkj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.feifeiyinyue.top/Article/details/gt2qxvwozag.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zycfv.cn/Article/details/gt2dvudqynv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xinyue.icu/Article/details/gt2jhvnjusq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zycfv.cn/Article/details/gt2ddqyhpia.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gt2rflalbkt.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.wangdashe.top/Article/details/gt2gkilrnet.html

JS:   "7".padStart(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gt2kmcjxcuw.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gt2fxakwyzn.html

Java: String.format("%03d", 7)
来源：http://dali.bjfxy.top/Article/details/gt2mgiyyskh.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gt2xehazrjq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.daxiang520.top/Article/details/gt2blygtlnk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yanxiufei.cn/Article/details/gt2nusbxzzl.html

[E11] 反转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2okmzximi.html

Py:   s[::-1]
来源：http://dali.zdqjudy.top/Article/details/gt2kkavingt.html

PHP:  strrev($s);
来源：http://dali.yonumen.top/Article/details/gt2bnqxjdly.html

JS:   [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gt2krpiyitl.html

TS:   [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gt2zjaofwux.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.quarkkingdee.top/Article/details/gt2sjrwzzes.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lsdrbboq.html

Ruby: s.reverse
来源：http://dali.xuanzx.com/Article/details/gt2hbtipzdu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhoulong.xyz/Article/details/gt2tcvfcfah.html

[E12] 统计某字符出现次数
来源：http://dali.wangshuangyany.cn/Article/details/gt2rprlubeb.html

Py:   s.count("a")
来源：http://dali.xylfe.cn/Article/details/gt2vznkosmc.html

PHP:  substr_count($s, "a");
来源：http://dali.guowangkeji.top/Article/details/gt2weepuvhe.html

JS:   s.split("a").length - 1
来源：http://dali.sufxvd.cn/Article/details/gt2tiyynkgx.html

TS:   s.split("a").length - 1
来源：http://dali.guowangkeji.top/Article/details/gt2lkobhwcc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhixingplan.top/Article/details/gt2skgdaoos.html

Go:   strings.Count(s, "a")
来源：http://dali.yj202588.top/Article/details/gt2kbvqawqh.html

Ruby: s.count("a")
来源：http://dali.jinqigufen.top/Article/details/gt2efblfyfx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhongyouzk.top/Article/details/gt2uqkzmfjs.html

[E13] 逐字符遍历
来源：http://dali.yj20258888.top/Article/details/gt2llybasig.html

Py:   for ch in s: print(ch)
来源：http://dali.xylfe.cn/Article/details/gt2mupkbrij.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cqqwz.cn/Article/details/gt2kjlpmbct.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cheryme.top/Article/details/gt2rarwditm.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jianghu66.top/Article/details/gt2zxzmadou.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jqgfzy.top/Article/details/gt2bkztrwki.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sufxvd.cn/Article/details/gt2dwclrlwn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kkoedquz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jyoumei.cn/Article/details/gt2kezenkzt.html

[E14] URL 编码与 Base64
来源：http://dali.bjfxy.top/Article/details/gt2fntssarl.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sufxvd.cn/Article/details/gt2rrvojjsr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.redwolf501.top/Article/details/gt2ihsswfyk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cdnleiting.top/Article/details/gt2cjcyvohd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rsxrnqlk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hsklffoz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2verdppcv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.chenlongwang.top/Article/details/gt2grsqpauf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj20258888.top/Article/details/gt2qefmjsut.html

[E15] HTML 转义 / 反转义
来源：http://dali.zdqjudy.top/Article/details/gt2pygnnnqw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ivvv.top/Article/details/gt2tgzgjmhy.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.quarkkingdee.top/Article/details/gt2lhyyvneq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qcvmtsqa.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.tanke756.top/Article/details/gt2ppylnkhy.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xpyouebb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.redwolf501.top/Article/details/gt2oupmyoai.html


<!-- 参考信息 -->