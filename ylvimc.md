代发 wailian999

PHP:  sort($arr);
来源：http://dali.pycfn.com/Article/details/gt2tebjeliv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ppjwa.cn/Article/details/gt2zmamsffn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhixingplan.top/Article/details/gt2ekcteice.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.guowangkeji.top/Article/details/gt2lekonyto.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2siithhji.html

Ruby: arr.sort
来源：http://dali.feifeiyinyue.top/Article/details/gt2pobeakah.html

C#:   list.Sort();
来源：http://dali.xuetiantiany.cn/Article/details/gt2ktwlolom.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.pengpengdd.cyou/Article/details/gt2ofsvapcu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.tian-w.cn/Article/details/gt2eicadnrw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hysaishi.cn/Article/details/gt2dkjclulm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gaohongyu789.top/Article/details/gt2fgqunnoq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ydzc1.top/Article/details/gt2pjaywmgk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.tianlin.xyz/Article/details/gt2stimizwm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jianghu66.top/Article/details/gt2vipdcfxv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yj20258888.top/Article/details/gt2kzhyuggr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yueranfly.top/Article/details/gt2swqnwbgt.html

[D11] 反转数组
来源：http://dali.haohaochexian.top/Article/details/gt2wrsmjynb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.pycfn.com/Article/details/gt2sioqkcpf.html

PHP:  array_reverse($arr);
来源：http://dali.chenzaomai.com/Article/details/gt2vdjatccl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2huckuusw.html

TS:   [...arr].reverse();
来源：http://dali.iojbl.cn/Article/details/gt2upizuuoa.html

Java: Collections.reverse(list);
来源：http://dali.tianlin.xyz/Article/details/gt2ffgbyywr.html

Go:   slices.Reverse(arr)
来源：http://dali.ppjwa.cn/Article/details/gt2sjhqkgwy.html

Ruby: arr.reverse
来源：http://dali.ybcxt.top/Article/details/gt2bolbrggj.html

C#:   list.Reverse();
来源：http://dali.sufxvd.cn/Article/details/gt2rjhzfkkr.html

[D12] 查找元素下标
来源：http://dali.hysaishi.cn/Article/details/gt2hbpxddci.html

Py:   arr.index(x);  x in arr
来源：http://dali.nanxuanxn.top/Article/details/gt2ffdzlnqt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2odtcxxhu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhoulong.xyz/Article/details/gt2pcgrmwbc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zoysfwti.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhoulong.xyz/Article/details/gt2hibsexdk.html

Go:   slices.Index(arr, x)
来源：http://dali.tanke756.top/Article/details/gt2fosijxsv.html

Ruby: arr.index(x)
来源：http://dali.jqgfzy.top/Article/details/gt2azwdyktc.html

C#:   list.IndexOf(x);
来源：http://dali.sufxvd.cn/Article/details/gt2llnhzedb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ppjwa.cn/Article/details/gt2cxosruwa.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hongshengwenyu.top/Article/details/gt2baxhnzzj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yangfankeji.com/Article/details/gt2uzzikzkx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yj202588.top/Article/details/gt2ufvwmsvh.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nanxinkj.top/Article/details/gt2rjaipirv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jyoumei.cn/Article/details/gt2kkoujaws.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.feifeiyinyue.top/Article/details/gt2taiajftq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.dashuyun.cn/Article/details/gt2fvfejbzw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2qhfegmlj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gotoacloud.top/Article/details/gt2apkrbvgk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.0kj1m.cn/Article/details/gt2wfytaypc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2upaqrwen.html

JS:   arr.map(x => x * 2)
来源：http://dali.hywenlv.cn/Article/details/gt2zxqfupkc.html

TS:   arr.map(x => x * 2)
来源：http://dali.c1oappe.top/Article/details/gt2ugxutnkt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hywenlv.cn/Article/details/gt2mepjcqrp.html

Go:   // 手写循环
来源：http://dali.pengpengdd.cyou/Article/details/gt2gxntctnb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2hlfvyivn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cdnleiting.top/Article/details/gt2hvldapgu.html

[D15] 去重
来源：http://dali.hongshengwenyu.top/Article/details/gt2rtvkbrpt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.wangshuangyany.cn/Article/details/gt2eqivkydw.html

PHP:  array_unique($arr);
来源：http://dali.andypj.xyz/Article/details/gt2qbguomho.html

JS:   [...new Set(arr)]
来源：http://dali.shzxlz.cn/Article/details/gt2noefpbgn.html

TS:   [...new Set(arr)]
来源：http://dali.hnxiangtu.top/Article/details/gt2obkzsptt.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cheryme.top/Article/details/gt2fxdmmwcs.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.kuanghao11.cn/Article/details/gt2dismxvzn.html

Ruby: arr.uniq
来源：http://dali.aibaodan.cn/Article/details/gt2znmoiljf.html

C#:   list.Distinct().ToList()
来源：http://dali.jinqigfzy.top/Article/details/gt2ujysrygi.html

[D16] 求和与平均值
来源：http://dali.fengsongda.top/Article/details/gt2mmwjujrm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbehyvjo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.chenlongwang.top/Article/details/gt2hxdrsexd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.smart0.xyz/Article/details/gt2bcdmaxyh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2zgtcgwma.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yuanzhike.top/Article/details/gt2ribdgvlx.html

Go:   // 手写循环累加
来源：http://dali.shangyingyoupin.top/Article/details/gt2ufltbxwa.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.vqdsnc.cn/Article/details/gt2nqrpbdqj.html

C#:   list.Sum();  list.Average()
来源：http://dali.quarkkingdee.top/Article/details/gt2gaodmczd.html

[D17] 最大值与最小值
来源：http://dali.gotoacloud.top/Article/details/gt2juctvvvs.html

Py:   max(arr);  min(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2rqjkkxqg.html

PHP:  max($arr);  min($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2pshbzvhk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tozkmzum.html

TS:   Math.max(...arr);
来源：http://dali.iojbl.cn/Article/details/gt2zqznsogr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hysaishi.cn/Article/details/gt2gvehyfvh.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zycfv.cn/Article/details/gt2tccfsqrn.html

Ruby: arr.max;  arr.min
来源：http://dali.nanxuanxn.top/Article/details/gt2zglwsubv.html

C#:   list.Max();  list.Min()
来源：http://dali.9152youxi.cn/Article/details/gt2iwvgwpdr.html

[D18] 扁平化嵌套数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vcmknsuv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.aizwys.cn/Article/details/gt2bssysmnf.html

PHP:  array_merge(...$nested);
来源：http://dali.vqdsnc.cn/Article/details/gt2vjqasthy.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.meibo888.top/Article/details/gt2bktfqxvd.html

TS:   nested.flat();
来源：http://dali.jyoumei.cn/Article/details/gt2iforepbi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sxryk.cn/Article/details/gt2pydmpdyk.html

Go:   // 手写双层循环
来源：http://dali.bjfxy.top/Article/details/gt2izppdwxw.html

Ruby: nested.flatten
来源：http://dali.smart0.xyz/Article/details/gt2zkphbdjw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yonumen.top/Article/details/gt2zwxmziqz.html

[D19] 按字段分组
来源：http://dali.hysaishi.cn/Article/details/gt2nuycilqa.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aekcbylh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gotoacloud.top/Article/details/gt2ysnknpfr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yueranfly.top/Article/details/gt2zgccxrxo.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.daria6918.cn/Article/details/gt2zehtbexy.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yj202588.top/Article/details/gt2qqwexwhh.html

Go:   // 手写 map[string][]T
来源：http://dali.vqdsnc.cn/Article/details/gt2rtdeycdu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hfpthk.cn/Article/details/gt2imuooeae.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhoulong.xyz/Article/details/gt2zfgoowhs.html

[D20] 统计每个元素出现次数
来源：http://dali.sxryk.cn/Article/details/gt2obespffm.html

Py:   Counter(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2byycgxmu.html

PHP:  array_count_values($arr);
来源：http://dali.fzhhl.top/Article/details/gt2cipqnyqh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zdqjudy.top/Article/details/gt2efydgqzv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgfzy.top/Article/details/gt2pvswirlg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yonumen.top/Article/details/gt2ghkoqfdj.html

Go:   // 手写 map[T]int
来源：http://dali.c1oappe.top/Article/details/gt2gwnjlkih.html

Ruby: arr.tally
来源：http://dali.birdmap.top/Article/details/gt2yeaxcuoe.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yuxming.cn/Article/details/gt2vtktviql.html

[D21] 判断是否包含某元素
来源：http://dali.chenjidiqi.icu/Article/details/gt2skvqiyke.html

Py:   x in arr
来源：http://dali.yueranfly.top/Article/details/gt2iutkdhbm.html

PHP:  in_array($x, $arr, true);
来源：http://dali.iojbl.cn/Article/details/gt2wrjkgpen.html

JS:   arr.includes(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jixvomid.html

TS:   arr.includes(x)
来源：http://dali.xinyue.icu/Article/details/gt2gokxgkeo.html

Java: list.contains(x)
来源：http://dali.meibo888.top/Article/details/gt2hhvhdmfq.html

Go:   slices.Contains(arr, x)
来源：http://dali.cheryme.top/Article/details/gt2mhthasgm.html

Ruby: arr.include?(x)
来源：http://dali.snrcjt.cn/Article/details/gt2huvincct.html

C#:   list.Contains(x)
来源：http://dali.c1oappe.top/Article/details/gt2ihhqafto.html

[D22] 复制数组（避免共享引用）
来源：http://dali.guowangkeji.top/Article/details/gt2nfshpyrm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.bjfxy.top/Article/details/gt2cdxqxcnk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.0kj1m.cn/Article/details/gt2ulrvxxlz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zryzexom.html

TS:   [...arr];
来源：http://dali.zhiwuduotai.top/Article/details/gt2bsiycmkw.html

Java: new ArrayList<>(list);
来源：http://dali.gogol.net.cn/Article/details/gt2wrthsrnx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cucudq.cn/Article/details/gt2eyrjcztf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.tianlin.xyz/Article/details/gt2pkvsaipd.html

C#:   new List<int>(list);
来源：http://dali.ybcxt.top/Article/details/gt2kjvbnxfg.html

[D23] reduce 累积计算
来源：http://dali.xuanzx.com/Article/details/gt2twcevviv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gt2aynkvwxz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.meibo888.top/Article/details/gt2npervjsw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.kuanghao11.cn/Article/details/gt2eriaupbd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2rxamyzjt.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ybcxt.top/Article/details/gt2frdxwmcj.html

Go:   // 手写循环
来源：http://dali.yueranfly.top/Article/details/gt2pskashwd.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhoulong.xyz/Article/details/gt2wsfmqxto.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenlongwang.top/Article/details/gt2xnteoqze.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pbcgdogy.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sysykeji.top/Article/details/gt2tdxflpil.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.dianchejie.cn/Article/details/gt2buyhjqcn.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.9152youxi.cn/Article/details/gt2bochstea.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sysykeji.top/Article/details/gt2lsrmciio.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ehwqpu.com/Article/details/gt2geqibimi.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.nwbrower.top/Article/details/gt2lpjwkemg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.aibaodan.cn/Article/details/gt2ddahwqht.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2soqwvspv.html

[D25] Set 集合去重与交并差
来源：http://dali.kuanghao11.cn/Article/details/gt2eiaywtlg.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yuxming.cn/Article/details/gt2eujlywdo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yj20258.top/Article/details/gt2uofzqwne.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jyoumei.cn/Article/details/gt2wqhpkmlw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zdqjudy.top/Article/details/gt2jbhwtuvs.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ppjwa.cn/Article/details/gt2jrlrlrmq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shzxlz.cn/Article/details/gt2hdvtsotw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hysaishi.cn/Article/details/gt2hdcygmqm.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xdjxxawn.html

[D26] 数组转字符串
来源：http://dali.cucudq.cn/Article/details/gt2suqndfdn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gaohongyu789.top/Article/details/gt2trnkycla.html

PHP:  implode(", ", $arr);
来源：http://dali.0kj1m.cn/Article/details/gt2aihtbepn.html

JS:   arr.join(", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nhozaxey.html

TS:   arr.join(", ")
来源：http://dali.guannengcc.top/Article/details/gt2sguwnhxn.html

Java: String.join(", ", list)
来源：http://dali.gzhubu.top/Article/details/gt2nohwdstw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gotoacloud.top/Article/details/gt2khrjipmz.html

Ruby: arr.join(", ")
来源：http://dali.nanxinkj.top/Article/details/gt2odqgqxng.html

C#:   string.Join(", ", list)
来源：http://dali.jinqigfzy.top/Article/details/gt2lzwayvrv.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2hdgwfdgn.html

E. 字符串处理
来源：http://dali.kuanghao11.cn/Article/details/gt2umgkxpmm.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2milwvaws.html

[E01] 拼接字符串
来源：http://dali.cucudq.cn/Article/details/gt2malgvdkg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shzxlz.cn/Article/details/gt2veeqvrvu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.bjfxy.top/Article/details/gt2flnskznx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tianlin.xyz/Article/details/gt2iozgodns.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.havefunace.top/Article/details/gt2okugrxam.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xziqi.cn/Article/details/gt2uusdigby.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.aizwys.cn/Article/details/gt2vwbxalgq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.daxiang520.top/Article/details/gt2pwlpzzos.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gt2mxwymwwi.html

[E02] 重复字符串
来源：http://dali.daxiang520.top/Article/details/gt2espxocau.html

Py:   "ab" * 3
来源：http://dali.shanyushiyangtech.top/Article/details/gt2clkoimyy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.dashuyun.cn/Article/details/gt2erifyypg.html

JS:   "ab".repeat(3)
来源：http://dali.cqqwz.cn/Article/details/gt2plyuwsir.html

TS:   "ab".repeat(3)
来源：http://dali.jyoumei.cn/Article/details/gt2wfsspeif.html

Java: "ab".repeat(3)
来源：http://dali.bjfxy.top/Article/details/gt2kdtjicwu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhoulong.xyz/Article/details/gt2ldphkalx.html

Ruby: "ab" * 3
来源：http://dali.cdnleiting.top/Article/details/gt2divmavmz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ivvv.top/Article/details/gt2wwiqcngh.html

[E03] 截取子串
来源：http://dali.snrcjt.cn/Article/details/gt2fuwxetlz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ybcxt.top/Article/details/gt2amjjpjyp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gt2bncdxbwc.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gzhubu.top/Article/details/gt2pswgxcsp.html

TS:   s.slice(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gt2yttugglu.html

Java: s.substring(1, 4)
来源：http://dali.gogol.net.cn/Article/details/gt2mwqgforw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cucudq.cn/Article/details/gt2ytqzwcvo.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.dianchejie.cn/Article/details/gt2atvlxduq.html

C#:   s.Substring(1, 3)
来源：http://dali.yonumen.top/Article/details/gt2jpdqdqiz.html

[E04] 查找子串位置
来源：http://dali.pengpengdd.cyou/Article/details/gt2besgecux.html

Py:   s.find("x");  s.index("x")
来源：http://dali.wangshuangyany.cn/Article/details/gt2wkodkqoc.html

PHP:  strpos($s, "x");
来源：http://dali.kuanghao11.cn/Article/details/gt2ttfuzokr.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.birdmap.top/Article/details/gt2khiehjcd.html

TS:   s.indexOf("x")
来源：http://dali.hfpthk.cn/Article/details/gt2hhqwmaby.html

Java: s.indexOf("x")
来源：http://dali.smart0.xyz/Article/details/gt2kdggmxhn.html

Go:   strings.Index(s, "x")
来源：http://dali.0kj1m.cn/Article/details/gt2hpbjpdfs.html

Ruby: s.index("x")
来源：http://dali.jianghu66.top/Article/details/gt2oxbsovge.html

C#:   s.IndexOf("x")
来源：http://dali.ehwqpu.com/Article/details/gt2rmxzmjwb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.wangdashe.top/Article/details/gt2zjzlmhrz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xinyue.icu/Article/details/gt2desqsynh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.birdmap.top/Article/details/gt2gncznayc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gt2glvpunqg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jinqigufen.top/Article/details/gt2wgggblsf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nwbrower.top/Article/details/gt2xcdkcclo.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.iojbl.cn/Article/details/gt2vgvzddho.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.gotoacloud.top/Article/details/gt2ynwauwfm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.iojbl.cn/Article/details/gt2qymoxepy.html

[E06] 替换子串
来源：http://dali.jianghu66.top/Article/details/gt2xhkivntx.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zdqjudy.top/Article/details/gt2ugxtkvoz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hnxiangtu.top/Article/details/gt2lrsuhgfb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gt2ejxisldq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.iojbl.cn/Article/details/gt2znkklpmx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gt2ndmhgcaw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.smart0.xyz/Article/details/gt2hdwcztgb.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ivvv.top/Article/details/gt2nrxmxsbd.html

C#:   s.Replace("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gt2dyifqdcc.html

[E07] 按分隔符拆分
来源：http://dali.feifeiyinyue.top/Article/details/gt2gcotakrr.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bfcrvtuz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xspjugip.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.bjfxy.top/Article/details/gt2uqvvegkf.html

TS:   s.split(",")
来源：http://dali.vqdsnc.cn/Article/details/gt2scpnvish.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.chenlongwang.top/Article/details/gt2ypuehqno.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.c1oappe.top/Article/details/gt2glajtkhv.html

Ruby: s.split(",");  s.split
来源：http://dali.pengpengdd.cyou/Article/details/gt2jpcjrkne.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ehwqpu.com/Article/details/gt2tjsydjkp.html

[E08] 数组按分隔符合并
来源：http://dali.dashuyun.cn/Article/details/gt2swrkqofb.html

Py:   ",".join(items)
来源：http://dali.9152youxi.cn/Article/details/gt2mgoeawum.html

PHP:  implode(",", $items);
来源：http://dali.yongpay.top/Article/details/gt2ddshkaak.html

JS:   items.join(",")
来源：http://dali.yonumen.top/Article/details/gt2amblkbzs.html

TS:   items.join(",")
来源：http://dali.smart0.xyz/Article/details/gt2xdmjyyoa.html

Java: String.join(",", items)
来源：http://dali.yuxming.cn/Article/details/gt2fsxexeue.html

Go:   strings.Join(items, ",")
来源：http://dali.zycfv.cn/Article/details/gt2wdecovvh.html

Ruby: items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gt2pkdapshr.html

C#:   string.Join(",", items)
来源：http://dali.daria6918.cn/Article/details/gt2mjhdolve.html

[E09] 去除所有空白字符
来源：http://dali.xuanzx.com/Article/details/gt2zxkmznpw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ppjwa.cn/Article/details/gt2uihjhflk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tian-w.cn/Article/details/gt2bfctxdkl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.svipenyu.cn/Article/details/gt2aottvwnq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gaohongyu789.top/Article/details/gt2cvsetlgz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.tianlin.xyz/Article/details/gt2lmbeipyk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sweek.top/Article/details/gt2gjfbvrvw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.aizwys.cn/Article/details/gt2swtjwjou.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.9152youxi.cn/Article/details/gt2bnqmsuyh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yvedp.cn/Article/details/gt2ezgvwsmr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.c1oappe.top/Article/details/gt2njgyrizd.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gogol.net.cn/Article/details/gt2kandorpg.html

JS:   "7".padStart(3, "0")
来源：http://dali.xylfe.cn/Article/details/gt2tiiccxwy.html

TS:   "7".padStart(3, "0")
来源：http://dali.shuidangran.top/Article/details/gt2zygneqdy.html

Java: String.format("%03d", 7)
来源：http://dali.dashuyun.cn/Article/details/gt2oubyvnky.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oqoirrku.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.smart0.xyz/Article/details/gt2ebsdahww.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhongyouzk.top/Article/details/gt2gowzwvdo.html

[E11] 反转字符串
来源：http://dali.redwolf501.top/Article/details/gt2jddgznhw.html

Py:   s[::-1]
来源：http://dali.zhongyouzk.top/Article/details/gt2fkfvwmps.html

PHP:  strrev($s);
来源：http://dali.shzxlz.cn/Article/details/gt2kmhaefgi.html

JS:   [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gt2ssdjodpr.html

TS:   [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gt2oprbqmcl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cucudq.cn/Article/details/gt2sywtnhyg.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yuanzhike.top/Article/details/gt2cmwowpex.html

Ruby: s.reverse
来源：http://dali.cdnleiting.top/Article/details/gt2tqezfini.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nanxuanxn.top/Article/details/gt2pcscywgp.html

[E12] 统计某字符出现次数
来源：http://dali.yuanzhike.top/Article/details/gt2wbeeyzvj.html

Py:   s.count("a")
来源：http://dali.hfpthk.cn/Article/details/gt2kcevoxky.html

PHP:  substr_count($s, "a");
来源：http://dali.sweek.top/Article/details/gt2ubgncsoa.html

JS:   s.split("a").length - 1
来源：http://dali.ydzc1.top/Article/details/gt2tnqqonod.html

TS:   s.split("a").length - 1
来源：http://dali.nwbrower.top/Article/details/gt2turylszy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.mhx1999.top/Article/details/gt2rgyesyyk.html

Go:   strings.Count(s, "a")
来源：http://dali.hfpthk.cn/Article/details/gt2etdfxywx.html

Ruby: s.count("a")
来源：http://dali.yj202588.top/Article/details/gt2niqolrru.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sysykeji.top/Article/details/gt2edrdwekv.html

[E13] 逐字符遍历
来源：http://dali.smart0.xyz/Article/details/gt2xgpdbplw.html

Py:   for ch in s: print(ch)
来源：http://dali.svipenyu.cn/Article/details/gt2nxmebroj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jqgufenzy.top/Article/details/gt2njwvabge.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ehwqpu.com/Article/details/gt2qpomtqjd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hfpthk.cn/Article/details/gt2mpqfqiub.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hnqzz.top/Article/details/gt2ofqhagqq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yj202588.top/Article/details/gt2lygtzlcm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xinyue.icu/Article/details/gt2omcpkclr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.havefunace.top/Article/details/gt2nnhokhdy.html

[E14] URL 编码与 Base64
来源：http://dali.ydzc1.top/Article/details/gt2pcsjlipz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jqgufenzy.top/Article/details/gt2gcyvimlk.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gaohongyu789.top/Article/details/gt2pqjwwfdg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gogol.net.cn/Article/details/gt2nnppzdjc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.smart0.xyz/Article/details/gt2setesjfh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.havefunace.top/Article/details/gt2jggwbuqp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hfpthk.cn/Article/details/gt2ixwqtwei.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.aibaodan.cn/Article/details/gt2vpyzkdnb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gt2judbumsv.html

[E15] HTML 转义 / 反转义
来源：http://dali.ybcxt.top/Article/details/gt2nfcvpnrp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.bjfxy.top/Article/details/gt2ojdlgbys.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.316326.xyz/Article/details/gt2wotzptva.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2adrcjksi.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yongpay.top/Article/details/gt2ucxuldoe.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.guowangkeji.top/Article/details/gt2uswdclxs.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.aibaodan.cn/Article/details/gt2hvpcxgks.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gotoacloud.top/Article/details/gt2fmzvnfsw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shzxlz.cn/Article/details/gt2cqjpxjwq.html

[E16] 数字千分位
来源：http://dali.tian-w.cn/Article/details/gt2zqomsufo.html

Py:   f"{1234567:,}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lvfatfud.html


<!-- 参考信息 -->