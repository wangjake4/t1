代发 wailian999

[D07] 切片 / 取子数组
来源：http://dali.yuxming.cn/Article/details/gt2xusqtfey.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yuanzhike.top/Article/details/gt2nffcnecd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sweek.top/Article/details/gt2mecomzeg.html

JS:   arr.slice(1, 4);
来源：http://dali.shuidangran.top/Article/details/gt2nwvjxzzp.html

TS:   arr.slice(1, 4);
来源：http://dali.ppjwa.cn/Article/details/gt2wslamiag.html

Java: list.subList(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gt2yvqggflm.html

Go:   arr[1:4]
来源：http://dali.cucudq.cn/Article/details/gt2fhrofhbr.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2padveuiv.html

C#:   list.GetRange(1, 3);
来源：http://dali.aizwys.cn/Article/details/gt2rfppaoof.html

[D08] 合并两个数组
来源：http://dali.yongpay.top/Article/details/gt2furatshe.html

Py:   a + b;  a.extend(b)
来源：http://dali.hammf.cn/Article/details/gt2qctwajlk.html

PHP:  array_merge($a, $b);
来源：http://dali.hongshengwenyu.top/Article/details/gt2akiwbppb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.daxiang520.top/Article/details/gt2lanslkqb.html

TS:   [...a, ...b];
来源：http://dali.ppjwa.cn/Article/details/gt2slbwjzsr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xylfe.cn/Article/details/gt2qhgttvjg.html

Go:   append(a, b...)
来源：http://dali.chenjidiqi.icu/Article/details/gt2asjndlnj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fnuomsgy.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhengqikj.top/Article/details/gt2wxfjgwkf.html

[D09] 排序（升序）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aalnjllb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhongyouzk.top/Article/details/gt2mjejymlw.html

PHP:  sort($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2gaaqrfqs.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.pycfn.com/Article/details/gt2fmngqnrb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.dianchejie.cn/Article/details/gt2wdhnqwau.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ajxlitfb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2igxundpd.html

Ruby: arr.sort
来源：http://dali.aizwys.cn/Article/details/gt2jwzvsmmr.html

C#:   list.Sort();
来源：http://dali.9152youxi.cn/Article/details/gt2tjhfdqzr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xuanzx.com/Article/details/gt2ghtmtesd.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yanxiufei.cn/Article/details/gt2wmntdymq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gotoacloud.top/Article/details/gt2zrwuqxpv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fengsongda.top/Article/details/gt2hbjaqijw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258.top/Article/details/gt2nqpluxfl.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cdnleiting.top/Article/details/gt2kubaeuwd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhongyouzk.top/Article/details/gt2gwykczky.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.meibo888.top/Article/details/gt2ulxordov.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yonumen.top/Article/details/gt2zmohfrzh.html

[D11] 反转数组
来源：http://dali.sxryk.cn/Article/details/gt2splagtzj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shangyingyoupin.top/Article/details/gt2nipxbbhl.html

PHP:  array_reverse($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2rtusdmaw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.daxiang520.top/Article/details/gt2toqoghvv.html

TS:   [...arr].reverse();
来源：http://dali.fengsongda.top/Article/details/gt2stwvccnv.html

Java: Collections.reverse(list);
来源：http://dali.mhx1999.top/Article/details/gt2vwogedfs.html

Go:   slices.Reverse(arr)
来源：http://dali.fengsongda.top/Article/details/gt2durbonaf.html

Ruby: arr.reverse
来源：http://dali.dianchejie.cn/Article/details/gt2sdyqyjaz.html

C#:   list.Reverse();
来源：http://dali.hywenlv.cn/Article/details/gt2symihhmi.html

[D12] 查找元素下标
来源：http://dali.meibo888.top/Article/details/gt2kfntvuzd.html

Py:   arr.index(x);  x in arr
来源：http://dali.0kj1m.cn/Article/details/gt2owzuzwxi.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hammf.cn/Article/details/gt2zjmfdxkz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bhoytige.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shuidangran.top/Article/details/gt2pdjxtflh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yangfankeji.com/Article/details/gt2oncrfupx.html

Go:   slices.Index(arr, x)
来源：http://dali.birdmap.top/Article/details/gt2lnupivfd.html

Ruby: arr.index(x)
来源：http://dali.yuxming.cn/Article/details/gt2umpftaga.html

C#:   list.IndexOf(x);
来源：http://dali.cqqwz.cn/Article/details/gt2wxneosdv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.aizwys.cn/Article/details/gt2wrzvtsco.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.aibaodan.cn/Article/details/gt2innudldt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinqigfzy.top/Article/details/gt2mcxvxzku.html

JS:   arr.filter(x => x > 3)
来源：http://dali.pycfn.com/Article/details/gt2shaufukv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.guannengcc.top/Article/details/gt2hljfwcxm.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.kuanghao11.cn/Article/details/gt2ghbgkkuh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.meibo888.top/Article/details/gt2bzfgdnib.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hywenlv.cn/Article/details/gt2nylmvsmp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2lddstdmz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xuanzx.com/Article/details/gt2ficbndhl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.tian-w.cn/Article/details/gt2axirwued.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.9152youxi.cn/Article/details/gt2wapqeuvg.html

JS:   arr.map(x => x * 2)
来源：http://dali.hywenlv.cn/Article/details/gt2dnvepaih.html

TS:   arr.map(x => x * 2)
来源：http://dali.hnxiangtu.top/Article/details/gt2cppqajxq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yvedp.cn/Article/details/gt2ftloulxb.html

Go:   // 手写循环
来源：http://dali.gaohongyu789.top/Article/details/gt2fsnsqwoi.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yongpay.top/Article/details/gt2vidmbvdg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.havefunace.top/Article/details/gt2hcvxqtuo.html

[D15] 去重
来源：http://dali.tianlin.xyz/Article/details/gt2gjnadqtj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yangfankeji.com/Article/details/gt2qpfjdkln.html

PHP:  array_unique($arr);
来源：http://dali.gotoacloud.top/Article/details/gt2nrteylik.html

JS:   [...new Set(arr)]
来源：http://dali.zhixingplan.top/Article/details/gt2xfmsgbki.html

TS:   [...new Set(arr)]
来源：http://dali.gotoacloud.top/Article/details/gt2bsivjcjy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xziqi.cn/Article/details/gt2jjoicgbf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.aibaodan.cn/Article/details/gt2mguadola.html

Ruby: arr.uniq
来源：http://dali.hysaishi.cn/Article/details/gt2wwnwipdr.html

C#:   list.Distinct().ToList()
来源：http://dali.yangfankeji.com/Article/details/gt2hwjtqnxz.html

[D16] 求和与平均值
来源：http://dali.dashuyun.cn/Article/details/gt2yhtpoejx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zdqjudy.top/Article/details/gt2jdeakkgf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.aibaodan.cn/Article/details/gt2atljrkze.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangdashe.top/Article/details/gt2ixufyiln.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.redwolf501.top/Article/details/gt2tuzctpkb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zdqjudy.top/Article/details/gt2xmdgmfdj.html

Go:   // 手写循环累加
来源：http://dali.0kj1m.cn/Article/details/gt2mqaysohu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hongshengwenyu.top/Article/details/gt2rtigxuhs.html

C#:   list.Sum();  list.Average()
来源：http://dali.xuetiantiany.cn/Article/details/gt2spqeexrj.html

[D17] 最大值与最小值
来源：http://dali.pycfn.com/Article/details/gt2oscrinqf.html

Py:   max(arr);  min(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ykwwhqwu.html

PHP:  max($arr);  min($arr);
来源：http://dali.ydzc1.top/Article/details/gt2dgcjlvek.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.pycfn.com/Article/details/gt2duqghyfm.html

TS:   Math.max(...arr);
来源：http://dali.cqqwz.cn/Article/details/gt2zhxptzck.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qvauvkki.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yj20258888.top/Article/details/gt2znloseao.html

Ruby: arr.max;  arr.min
来源：http://dali.sweek.top/Article/details/gt2thtlfvod.html

C#:   list.Max();  list.Min()
来源：http://dali.guowangkeji.top/Article/details/gt2nmbkiqvj.html

[D18] 扁平化嵌套数组
来源：http://dali.gzhubu.top/Article/details/gt2xhtljozw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tian-w.cn/Article/details/gt2mzjqvbho.html

PHP:  array_merge(...$nested);
来源：http://dali.xuetiantiany.cn/Article/details/gt2cgthrdqg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.guowangkeji.top/Article/details/gt2cnafwjra.html

TS:   nested.flat();
来源：http://dali.smart0.xyz/Article/details/gt2wsliqhaz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sxryk.cn/Article/details/gt2dtjlwyfq.html

Go:   // 手写双层循环
来源：http://dali.snrcjt.cn/Article/details/gt2lyrkvhqn.html

Ruby: nested.flatten
来源：http://dali.bjfxy.top/Article/details/gt2fwlvqmfk.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.guowangkeji.top/Article/details/gt2jsatoeht.html

[D19] 按字段分组
来源：http://dali.xuetiantiany.cn/Article/details/gt2yrocekxl.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2gjbrmieq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hysaishi.cn/Article/details/gt2ehdxnvpd.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yuxming.cn/Article/details/gt2nprezuti.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.chenzaomai.com/Article/details/gt2ivtaitsb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.316326.xyz/Article/details/gt2yyedydly.html

Go:   // 手写 map[string][]T
来源：http://dali.jqgufenzy.top/Article/details/gt2sjubumht.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yongpay.top/Article/details/gt2xaefhytr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shuidangran.top/Article/details/gt2dhziqeal.html

[D20] 统计每个元素出现次数
来源：http://dali.nanxinkj.top/Article/details/gt2itvfekps.html

Py:   Counter(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2cswkxscq.html

PHP:  array_count_values($arr);
来源：http://dali.sxryk.cn/Article/details/gt2dttfapdm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tanke756.top/Article/details/gt2uvhcxnpx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhixingplan.top/Article/details/gt2hvcvclwp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.daria6918.cn/Article/details/gt2persbfwe.html

Go:   // 手写 map[T]int
来源：http://dali.meibo888.top/Article/details/gt2tjokfwvd.html

Ruby: arr.tally
来源：http://dali.redwolf501.top/Article/details/gt2dqcrubsa.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hnxiangtu.top/Article/details/gt2mjnajkfz.html

[D21] 判断是否包含某元素
来源：http://dali.fzhhl.top/Article/details/gt2oboaavqb.html

Py:   x in arr
来源：http://dali.cheryme.top/Article/details/gt2amptzmrd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.andypj.xyz/Article/details/gt2vhlgodgs.html

JS:   arr.includes(x)
来源：http://dali.fzhhl.top/Article/details/gt2parzvayd.html

TS:   arr.includes(x)
来源：http://dali.yuxming.cn/Article/details/gt2ypyrofec.html

Java: list.contains(x)
来源：http://dali.redwolf501.top/Article/details/gt2zhwvdxrm.html

Go:   slices.Contains(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2grjsjsmd.html

Ruby: arr.include?(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2qbmulkaj.html

C#:   list.Contains(x)
来源：http://dali.meibo888.top/Article/details/gt2ckvpvcbc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.nwbrower.top/Article/details/gt2dmfahggp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yvedp.cn/Article/details/gt2sotwnssa.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.meibo888.top/Article/details/gt2eqhgsald.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkslytr.html

TS:   [...arr];
来源：http://dali.dashuyun.cn/Article/details/gt2hzzxjmuf.html

Java: new ArrayList<>(list);
来源：http://dali.shzxlz.cn/Article/details/gt2djdfwknm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jiagoushi.top/Article/details/gt2nlvvxjed.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gogol.net.cn/Article/details/gt2ufbkfqff.html

C#:   new List<int>(list);
来源：http://dali.sweek.top/Article/details/gt2jhtbjqpu.html

[D23] reduce 累积计算
来源：http://dali.daria6918.cn/Article/details/gt2jiveypif.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.daxiang520.top/Article/details/gt2ftchtqgm.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.daria6918.cn/Article/details/gt2mjhtqqkd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuanzhike.top/Article/details/gt2tavgrqlq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ibndytss.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yuanzhike.top/Article/details/gt2gbyplsil.html

Go:   // 手写循环
来源：http://dali.aibaodan.cn/Article/details/gt2wmjgcocd.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.havefunace.top/Article/details/gt2gyqeankh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.wangdashe.top/Article/details/gt2kjxpidjk.html

[D24] 字典 / Map 基本操作
来源：http://dali.feifeiyinyue.top/Article/details/gt2grdyxths.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yongpay.top/Article/details/gt2ppiaaosz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhixingplan.top/Article/details/gt2nfelnuxs.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.c1oappe.top/Article/details/gt2hyfsxazw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gt2alolalth.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yuanzhike.top/Article/details/gt2xkvgghis.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.nanxinkj.top/Article/details/gt2zjexizqy.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.aibaodan.cn/Article/details/gt2urmoinfa.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.nanxuanxn.top/Article/details/gt2gppeyjwo.html

[D25] Set 集合去重与交并差
来源：http://dali.zycfv.cn/Article/details/gt2wxdvqkwn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhiwuduotai.top/Article/details/gt2mclwrghf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gogol.net.cn/Article/details/gt2hjakapic.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.bjfxy.top/Article/details/gt2hkxwtwip.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.0kj1m.cn/Article/details/gt2mpoyrrhu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tanke756.top/Article/details/gt2mpendlkv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.mhx1999.top/Article/details/gt2xxwparfm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xkzxpkih.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rcqugalx.html

[D26] 数组转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ssslmqoq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yuanzhike.top/Article/details/gt2rsymifvh.html

PHP:  implode(", ", $arr);
来源：http://dali.xinyue.icu/Article/details/gt2lflkxmpk.html

JS:   arr.join(", ")
来源：http://dali.shzxlz.cn/Article/details/gt2jokwqjfr.html

TS:   arr.join(", ")
来源：http://dali.yuxming.cn/Article/details/gt2tzuzleil.html

Java: String.join(", ", list)
来源：http://dali.haohaochexian.top/Article/details/gt2nhtztloj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.nanxuanxn.top/Article/details/gt2kleodvub.html

Ruby: arr.join(", ")
来源：http://dali.jianghu66.top/Article/details/gt2zlqkbkqi.html

C#:   string.Join(", ", list)
来源：http://dali.zhengqikj.top/Article/details/gt2rfprzurs.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2zlpqxbln.html

E. 字符串处理
来源：http://dali.chenjidiqi.icu/Article/details/gt2xpnhzhal.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2wvzwbbhr.html

[E01] 拼接字符串
来源：http://dali.cqqwz.cn/Article/details/gt2mkutldah.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jqgfzy.top/Article/details/gt2bhmbjzjz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jianghu66.top/Article/details/gt2wkryqfti.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ntmybzuq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258888.top/Article/details/gt2hvfpsjyb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.pycfn.com/Article/details/gt2iozoyujo.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cheryme.top/Article/details/gt2kfvkfrxv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yvedp.cn/Article/details/gt2zeuaaahi.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gt2zmwjzyhq.html

[E02] 重复字符串
来源：http://dali.jinqigufen.top/Article/details/gt2ooimmlcd.html

Py:   "ab" * 3
来源：http://dali.jyoumei.cn/Article/details/gt2luqhsfsp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.redwolf501.top/Article/details/gt2cbmqotpm.html

JS:   "ab".repeat(3)
来源：http://dali.yuanzhike.top/Article/details/gt2hqnjsilr.html

TS:   "ab".repeat(3)
来源：http://dali.xinyue.icu/Article/details/gt2wdwigvxg.html

Java: "ab".repeat(3)
来源：http://dali.aizwys.cn/Article/details/gt2xnvvhtpc.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinqigfzy.top/Article/details/gt2tbgdmixz.html

Ruby: "ab" * 3
来源：http://dali.cucudq.cn/Article/details/gt2rnyqoghx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ydzc1.top/Article/details/gt2ocohglnq.html

[E03] 截取子串
来源：http://dali.fzhhl.top/Article/details/gt2gxueytnz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.meibo888.top/Article/details/gt2zubvzgxb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sweek.top/Article/details/gt2tgrnpzcv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.andypj.xyz/Article/details/gt2aylxegyr.html

TS:   s.slice(1, 4)
来源：http://dali.shuidangran.top/Article/details/gt2jwnuyqni.html

Java: s.substring(1, 4)
来源：http://dali.guannengcc.top/Article/details/gt2mmdzpxvq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shanyushiyangtech.top/Article/details/gt2brjmbcxh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yj20258888.top/Article/details/gt2zxzhzrgw.html

C#:   s.Substring(1, 3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2pwjcftnv.html

[E04] 查找子串位置
来源：http://dali.vqdsnc.cn/Article/details/gt2fvdvnsqk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.fzhhl.top/Article/details/gt2shvjsbpu.html

PHP:  strpos($s, "x");
来源：http://dali.kuanghao11.cn/Article/details/gt2hondquwv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2opvvqydk.html

TS:   s.indexOf("x")
来源：http://dali.c1oappe.top/Article/details/gt2wieaaszk.html

Java: s.indexOf("x")
来源：http://dali.hnxiangtu.top/Article/details/gt2qijnktfu.html

Go:   strings.Index(s, "x")
来源：http://dali.zhongyouzk.top/Article/details/gt2opnyuxxu.html

Ruby: s.index("x")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ionavurd.html

C#:   s.IndexOf("x")
来源：http://dali.redwolf501.top/Article/details/gt2zciryyjd.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hbkffjhg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2jajaktrq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.fengsongda.top/Article/details/gt2hslscgpl.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2glrsntgd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xinyue.icu/Article/details/gt2kexsmsbo.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cashguo.top/Article/details/gt2nzhjvscq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.c1oappe.top/Article/details/gt2vbwzwnru.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.meibo888.top/Article/details/gt2gggdwrrb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jlsjyb.cn/Article/details/gt2ikedzdgo.html

[E06] 替换子串
来源：http://dali.mhx1999.top/Article/details/gt2iqbjzxtd.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.kuanghao11.cn/Article/details/gt2orsxdfhg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.birdmap.top/Article/details/gt2haaocfys.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gt2tnxcjaur.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gt2ygroxfyc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gt2hzctiees.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.sufxvd.cn/Article/details/gt2xlnzbspe.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gt2ehyiwsau.html

C#:   s.Replace("a", "b")
来源：http://dali.yongpay.top/Article/details/gt2oleymtyh.html

[E07] 按分隔符拆分
来源：http://dali.ehwqpu.com/Article/details/gt2rxlrnjem.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.wangshuangyany.cn/Article/details/gt2nuqpqkuk.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gt2teygzwxu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cheryme.top/Article/details/gt2fbiarraf.html

TS:   s.split(",")
来源：http://dali.ydzc1.top/Article/details/gt2xwwsuzyn.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yonumen.top/Article/details/gt2jvhejijx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yj20258888.top/Article/details/gt2giqosbsb.html

Ruby: s.split(",");  s.split
来源：http://dali.redwolf501.top/Article/details/gt2jlgyaahu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.birdmap.top/Article/details/gt2shdixphq.html

[E08] 数组按分隔符合并
来源：http://dali.yongpay.top/Article/details/gt2mraxietx.html

Py:   ",".join(items)
来源：http://dali.nwbrower.top/Article/details/gt2innqxnoe.html

PHP:  implode(",", $items);
来源：http://dali.zhoulong.xyz/Article/details/gt2efslkzdp.html

JS:   items.join(",")
来源：http://dali.yuanzhike.top/Article/details/gt2zhgohwka.html

TS:   items.join(",")
来源：http://dali.yueranfly.top/Article/details/gt2duofyfbt.html

Java: String.join(",", items)
来源：http://dali.zhongyouzk.top/Article/details/gt2csvohpya.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjlfvpa.html

Ruby: items.join(",")
来源：http://dali.hnxiangtu.top/Article/details/gt2vilbgygn.html

C#:   string.Join(",", items)
来源：http://dali.xylfe.cn/Article/details/gt2ftwqhuvx.html

[E09] 去除所有空白字符
来源：http://dali.hammf.cn/Article/details/gt2cjjjnjcf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.tianlin.xyz/Article/details/gt2yqwrdojw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lsedbyhi.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ejgtaibv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zycfv.cn/Article/details/gt2qpprnfbn.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yuxming.cn/Article/details/gt2besqcgbw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shuidangran.top/Article/details/gt2sqgnfpti.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yangfankeji.com/Article/details/gt2ktunsnlh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yuanzhike.top/Article/details/gt2hblqpbhz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.redwolf501.top/Article/details/gt2ahjfclia.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yanxiufei.cn/Article/details/gt2uacwhckw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.bjfxy.top/Article/details/gt2crqjqtww.html

JS:   "7".padStart(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gt2fkgnxofi.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2slqjwedq.html

Java: String.format("%03d", 7)
来源：http://dali.yanxiufei.cn/Article/details/gt2lzjlubdy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2imkeresp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jyoumei.cn/Article/details/gt2rhllgtdy.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.316326.xyz/Article/details/gt2zrultpog.html

[E11] 反转字符串
来源：http://dali.meibo888.top/Article/details/gt2iqfrynpz.html

Py:   s[::-1]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dnwpcsfh.html

PHP:  strrev($s);
来源：http://dali.jianghu66.top/Article/details/gt2njepwctu.html

JS:   [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gt2mkcwmedx.html

TS:   [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gt2tgoqffid.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.nwbrower.top/Article/details/gt2yxcnfxld.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gogol.net.cn/Article/details/gt2rsytfnww.html

Ruby: s.reverse
来源：http://dali.jlsjyb.cn/Article/details/gt2byquqfov.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.wangdashe.top/Article/details/gt2uzxlfiap.html

[E12] 统计某字符出现次数
来源：http://dali.zhixingplan.top/Article/details/gt2twmumwgq.html

Py:   s.count("a")
来源：http://dali.nanxinkj.top/Article/details/gt2rmjuqztr.html

PHP:  substr_count($s, "a");
来源：http://dali.yj20258888.top/Article/details/gt2etcvogun.html

JS:   s.split("a").length - 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vxzydnfg.html

TS:   s.split("a").length - 1
来源：http://dali.nanxuanxn.top/Article/details/gt2ununstja.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenzaomai.com/Article/details/gt2dqmihcsh.html

Go:   strings.Count(s, "a")
来源：http://dali.shzxlz.cn/Article/details/gt2xkceuqyi.html

Ruby: s.count("a")
来源：http://dali.xylfe.cn/Article/details/gt2wdrrhzun.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yanxiufei.cn/Article/details/gt2ijbkxvat.html

[E13] 逐字符遍历
来源：http://dali.hnxiangtu.top/Article/details/gt2ccseldcu.html

Py:   for ch in s: print(ch)
来源：http://dali.iojbl.cn/Article/details/gt2jenfqpgw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.316326.xyz/Article/details/gt2paouqjxe.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.havefunace.top/Article/details/gt2tmgjdpmi.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ztpuzcyg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2zxrafdms.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yvedp.cn/Article/details/gt2bvzxgngo.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jlsjyb.cn/Article/details/gt2rdwhmjcg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cqqwz.cn/Article/details/gt2rgjjzlkr.html


<!-- 参考信息 -->