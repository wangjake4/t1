代发 wailian999

C#:   list.GetRange(1, 3);
来源：http://dali.ydzc1.top/Article/details/gt2ppjnayoq.html

[D08] 合并两个数组
来源：http://dali.iojbl.cn/Article/details/gt2uypvkctu.html

Py:   a + b;  a.extend(b)
来源：http://dali.daria6918.cn/Article/details/gt2ipowwcom.html

PHP:  array_merge($a, $b);
来源：http://dali.jinqigufen.top/Article/details/gt2ehvbigfe.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ppjwa.cn/Article/details/gt2ujeqbfaq.html

TS:   [...a, ...b];
来源：http://dali.yangfankeji.com/Article/details/gt2qjwemhpx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.bjfxy.top/Article/details/gt2uwdfziye.html

Go:   append(a, b...)
来源：http://dali.jiagoushi.top/Article/details/gt2ckozpsae.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jqgufenzy.top/Article/details/gt2ghdphejn.html

C#:   a.Concat(b).ToList()
来源：http://dali.birdmap.top/Article/details/gt2kfsgvibj.html

[D09] 排序（升序）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ptubtizz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dashuyun.cn/Article/details/gt2fddhqttd.html

PHP:  sort($arr);
来源：http://dali.cashguo.top/Article/details/gt2vocxzwbo.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2rhyrbavu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.chenjidiqi.icu/Article/details/gt2gzkkuyxk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zdqjudy.top/Article/details/gt2ihidbsbk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.c1oappe.top/Article/details/gt2giwpxnuw.html

Ruby: arr.sort
来源：http://dali.nwbrower.top/Article/details/gt2jruxbdll.html

C#:   list.Sort();
来源：http://dali.nanxinkj.top/Article/details/gt2lkgmodnu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jlsjyb.cn/Article/details/gt2qwwktsxi.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ydzc1.top/Article/details/gt2qcuzubrq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gzhubu.top/Article/details/gt2gjtqmpkj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cheryme.top/Article/details/gt2dkuykwnz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dianchejie.cn/Article/details/gt2njvwicwu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.haohaochexian.top/Article/details/gt2fcxvqsri.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jlsjyb.cn/Article/details/gt2tjjhlxyx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.aizwys.cn/Article/details/gt2ufnbsyfj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hongshengwenyu.top/Article/details/gt2ekbwklqs.html

[D11] 反转数组
来源：http://dali.ppjwa.cn/Article/details/gt2mbsbelru.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.chenzaomai.com/Article/details/gt2zkijvinh.html

PHP:  array_reverse($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2drfqalpe.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhoulong.xyz/Article/details/gt2vwiylzmo.html

TS:   [...arr].reverse();
来源：http://dali.redwolf501.top/Article/details/gt2yhzewjfh.html

Java: Collections.reverse(list);
来源：http://dali.yvedp.cn/Article/details/gt2hkqgcgiv.html

Go:   slices.Reverse(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kfsxgveu.html

Ruby: arr.reverse
来源：http://dali.shzxlz.cn/Article/details/gt2nsvthgmw.html

C#:   list.Reverse();
来源：http://dali.redwolf501.top/Article/details/gt2bkriuimk.html

[D12] 查找元素下标
来源：http://dali.hammf.cn/Article/details/gt2xducnxca.html

Py:   arr.index(x);  x in arr
来源：http://dali.nwbrower.top/Article/details/gt2zrjvudav.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ivvv.top/Article/details/gt2refumjqf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hysaishi.cn/Article/details/gt2tgjnkbqp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gogol.net.cn/Article/details/gt2kgogdxcg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shzxlz.cn/Article/details/gt2telfizxw.html

Go:   slices.Index(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qyfgnhup.html

Ruby: arr.index(x)
来源：http://dali.sweek.top/Article/details/gt2usalvwva.html

C#:   list.IndexOf(x);
来源：http://dali.gogol.net.cn/Article/details/gt2jtlljulv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.snrcjt.cn/Article/details/gt2oyxgxdya.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.0kj1m.cn/Article/details/gt2cjlalbza.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xuanzx.com/Article/details/gt2gfxpjijg.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2socrmlqr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hywenlv.cn/Article/details/gt2ycipjipg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xinyue.icu/Article/details/gt2jjnrmhmm.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.tanke756.top/Article/details/gt2gnshcfxi.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jqgufenzy.top/Article/details/gt2nuhmdnjz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.daxiang520.top/Article/details/gt2hxoeryrw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gogol.net.cn/Article/details/gt2vwdccyle.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cucudq.cn/Article/details/gt2qrugluik.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhixingplan.top/Article/details/gt2pbxwxowb.html

JS:   arr.map(x => x * 2)
来源：http://dali.havefunace.top/Article/details/gt2ayrcnuoi.html

TS:   arr.map(x => x * 2)
来源：http://dali.316326.xyz/Article/details/gt2unzuurdn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jqgufenzy.top/Article/details/gt2awczvbjw.html

Go:   // 手写循环
来源：http://dali.sufxvd.cn/Article/details/gt2eruutami.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shuidangran.top/Article/details/gt2oedwlvyf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.pycfn.com/Article/details/gt2cimwbbao.html

[D15] 去重
来源：http://dali.cdnleiting.top/Article/details/gt2dsxjlibv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhixingplan.top/Article/details/gt2juvahxox.html

PHP:  array_unique($arr);
来源：http://dali.zhengqikj.top/Article/details/gt2wrbmvrbh.html

JS:   [...new Set(arr)]
来源：http://dali.pycfn.com/Article/details/gt2uahwwcev.html

TS:   [...new Set(arr)]
来源：http://dali.ybcxt.top/Article/details/gt2cnlxkiok.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hnqzz.top/Article/details/gt2gcjcajzu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.wangshuangyany.cn/Article/details/gt2iyvsrvpu.html

Ruby: arr.uniq
来源：http://dali.ppjwa.cn/Article/details/gt2stwjdrxk.html

C#:   list.Distinct().ToList()
来源：http://dali.nanxuanxn.top/Article/details/gt2nbuxkhag.html

[D16] 求和与平均值
来源：http://dali.tian-w.cn/Article/details/gt2rbpcwsdf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2nfasszks.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jianghu66.top/Article/details/gt2xszanefv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fengsongda.top/Article/details/gt2dtomlhbq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cdgyiebj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.aibaodan.cn/Article/details/gt2ckbatbjy.html

Go:   // 手写循环累加
来源：http://dali.ehwqpu.com/Article/details/gt2cjsamfiq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sysykeji.top/Article/details/gt2zawnafcp.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinqigufen.top/Article/details/gt2hqosnwua.html

[D17] 最大值与最小值
来源：http://dali.fengsongda.top/Article/details/gt2wrdymixf.html

Py:   max(arr);  min(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2ttserqwg.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2gctxcayu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2tzetadvf.html

TS:   Math.max(...arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jhoxezhh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gtnvtjad.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gzhubu.top/Article/details/gt2ggtlvpuq.html

Ruby: arr.max;  arr.min
来源：http://dali.yuanzhike.top/Article/details/gt2ddcjhvfc.html

C#:   list.Max();  list.Min()
来源：http://dali.sweek.top/Article/details/gt2ereoxfxc.html

[D18] 扁平化嵌套数组
来源：http://dali.xziqi.cn/Article/details/gt2rjhgrtkl.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shuidangran.top/Article/details/gt2rcivixbn.html

PHP:  array_merge(...$nested);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pktoiapa.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jyoumei.cn/Article/details/gt2rtetjiay.html

TS:   nested.flat();
来源：http://dali.tianlin.xyz/Article/details/gt2oxrkglcc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ufpnphqm.html

Go:   // 手写双层循环
来源：http://dali.redwolf501.top/Article/details/gt2qpymlukb.html

Ruby: nested.flatten
来源：http://dali.yj20258888.top/Article/details/gt2ybyzqcpj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xinyue.icu/Article/details/gt2duteyrnn.html

[D19] 按字段分组
来源：http://dali.ydzc1.top/Article/details/gt2lvxwdemq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uwdczjfs.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.haohaochexian.top/Article/details/gt2ulflyije.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sysykeji.top/Article/details/gt2jpjrxuos.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cqqwz.cn/Article/details/gt2ictcxqqx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.daxiang520.top/Article/details/gt2ikkdgxkq.html

Go:   // 手写 map[string][]T
来源：http://dali.xuanzx.com/Article/details/gt2sehutnky.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.pycfn.com/Article/details/gt2nqgvbhoh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shangyingyoupin.top/Article/details/gt2rbjzjmvy.html

[D20] 统计每个元素出现次数
来源：http://dali.zhengqikj.top/Article/details/gt2fwqiapqi.html

Py:   Counter(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2tofcljka.html

PHP:  array_count_values($arr);
来源：http://dali.cucudq.cn/Article/details/gt2baccgfbp.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuanzhike.top/Article/details/gt2aedeyhzu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pycfn.com/Article/details/gt2clfjlmgu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.316326.xyz/Article/details/gt2dmqfahxz.html

Go:   // 手写 map[T]int
来源：http://dali.aibaodan.cn/Article/details/gt2xzkflsum.html

Ruby: arr.tally
来源：http://dali.gzhubu.top/Article/details/gt2lmmynhbr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.aizwys.cn/Article/details/gt2rhxcdxot.html

[D21] 判断是否包含某元素
来源：http://dali.hnxiangtu.top/Article/details/gt2lnjjlqbu.html

Py:   x in arr
来源：http://dali.chenjidiqi.icu/Article/details/gt2jhanvolx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.fengsongda.top/Article/details/gt2auegumur.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2coqfcozf.html

TS:   arr.includes(x)
来源：http://dali.yuxming.cn/Article/details/gt2uqtssjgc.html

Java: list.contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2nfcslhoz.html

Go:   slices.Contains(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gt2xjvlmoon.html

Ruby: arr.include?(x)
来源：http://dali.meibo888.top/Article/details/gt2akoubvvh.html

C#:   list.Contains(x)
来源：http://dali.fengsongda.top/Article/details/gt2gpvhyftr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.fzhhl.top/Article/details/gt2wrlhjgfl.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2gxvxfqbn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ydzc1.top/Article/details/gt2dscphofy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.tanke756.top/Article/details/gt2bhnakkqj.html

TS:   [...arr];
来源：http://dali.c1oappe.top/Article/details/gt2hkbtyxdv.html

Java: new ArrayList<>(list);
来源：http://dali.shuidangran.top/Article/details/gt2mbdanbqy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jqgufenzy.top/Article/details/gt2esduhlic.html

Ruby: arr.dup;  arr.clone
来源：http://dali.quarkkingdee.top/Article/details/gt2hzycdovv.html

C#:   new List<int>(list);
来源：http://dali.snrcjt.cn/Article/details/gt2rimjzozo.html

[D23] reduce 累积计算
来源：http://dali.sufxvd.cn/Article/details/gt2uriebmxp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2zzlruztc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.bjfxy.top/Article/details/gt2auqgfbsc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cdnleiting.top/Article/details/gt2gvvnqdey.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenzaomai.com/Article/details/gt2zcumfebd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhoulong.xyz/Article/details/gt2qxfpzrjo.html

Go:   // 手写循环
来源：http://dali.sysykeji.top/Article/details/gt2sngfsenl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jxuiwrto.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.dashuyun.cn/Article/details/gt2hgnmsqmz.html

[D24] 字典 / Map 基本操作
来源：http://dali.jianghu66.top/Article/details/gt2edppoalz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jqgufenzy.top/Article/details/gt2zhvrdpcf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2opvvnnsk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.svipenyu.cn/Article/details/gt2flrcuhio.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gt2qdsqrgps.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jianghu66.top/Article/details/gt2aokpqmhz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sxryk.cn/Article/details/gt2gcgymgxe.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.redwolf501.top/Article/details/gt2gznvgkqw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jlsjyb.cn/Article/details/gt2belspvla.html

[D25] Set 集合去重与交并差
来源：http://dali.guannengcc.top/Article/details/gt2mcvislvs.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yvedp.cn/Article/details/gt2ndeauxee.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yonumen.top/Article/details/gt2qkwajdok.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2uersbfps.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tanke756.top/Article/details/gt2slijxrdw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jiagoushi.top/Article/details/gt2tbysgqzd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gogol.net.cn/Article/details/gt2iqdwlasv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sxryk.cn/Article/details/gt2zxuhemuk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2awtwlbvy.html

[D26] 数组转字符串
来源：http://dali.iojbl.cn/Article/details/gt2xrdkwpix.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yvedp.cn/Article/details/gt2foqawxmq.html

PHP:  implode(", ", $arr);
来源：http://dali.hnxiangtu.top/Article/details/gt2koypkrme.html

JS:   arr.join(", ")
来源：http://dali.zycfv.cn/Article/details/gt2etbrwsak.html

TS:   arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gt2zbljjmsr.html

Java: String.join(", ", list)
来源：http://dali.redwolf501.top/Article/details/gt2awizurzb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hysaishi.cn/Article/details/gt2wqhbkovs.html

Ruby: arr.join(", ")
来源：http://dali.mhx1999.top/Article/details/gt2xsoruovg.html

C#:   string.Join(", ", list)
来源：http://dali.cheryme.top/Article/details/gt2iizkzutd.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2ovyrwnrl.html

E. 字符串处理
来源：http://dali.sxryk.cn/Article/details/gt2jzqyagbu.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2cqwcggsj.html

[E01] 拼接字符串
来源：http://dali.chenlongwang.top/Article/details/gt2vbnshtdn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sysykeji.top/Article/details/gt2vlpfhsbp.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.aibaodan.cn/Article/details/gt2dxhpcrua.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.guannengcc.top/Article/details/gt2gsmjjxex.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.snrcjt.cn/Article/details/gt2grzeebxf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cdnleiting.top/Article/details/gt2fzzpjdtv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhixingplan.top/Article/details/gt2ngmqxuos.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sweek.top/Article/details/gt2iimdxnkh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gt2ocjcxwoa.html

[E02] 重复字符串
来源：http://dali.xziqi.cn/Article/details/gt2alhwxipi.html

Py:   "ab" * 3
来源：http://dali.nwbrower.top/Article/details/gt2kmytggyl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.birdmap.top/Article/details/gt2vdlhfpeh.html

JS:   "ab".repeat(3)
来源：http://dali.quarkkingdee.top/Article/details/gt2jukfnykk.html

TS:   "ab".repeat(3)
来源：http://dali.haohaochexian.top/Article/details/gt2euegapio.html

Java: "ab".repeat(3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2lqwfssny.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.316326.xyz/Article/details/gt2tdbhhmkg.html

Ruby: "ab" * 3
来源：http://dali.jyoumei.cn/Article/details/gt2evmmasoz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.dashuyun.cn/Article/details/gt2erkixxvn.html

[E03] 截取子串
来源：http://dali.bjfxy.top/Article/details/gt2nhrywdar.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.nanxuanxn.top/Article/details/gt2cgcexrmh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yj202588.top/Article/details/gt2zpxjjtai.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlbgayi.html

TS:   s.slice(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gt2vuxdjang.html

Java: s.substring(1, 4)
来源：http://dali.hammf.cn/Article/details/gt2lbxqkzsz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xylfe.cn/Article/details/gt2nvynaywd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinqigfzy.top/Article/details/gt2fiogxmlt.html

C#:   s.Substring(1, 3)
来源：http://dali.ydzc1.top/Article/details/gt2qvdqdvnc.html

[E04] 查找子串位置
来源：http://dali.mhx1999.top/Article/details/gt2jsgkngrd.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cdnleiting.top/Article/details/gt2rdomoqpu.html

PHP:  strpos($s, "x");
来源：http://dali.316326.xyz/Article/details/gt2mqolmjxc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.dashuyun.cn/Article/details/gt2fhhaxvkb.html

TS:   s.indexOf("x")
来源：http://dali.ivvv.top/Article/details/gt2sxxffikd.html

Java: s.indexOf("x")
来源：http://dali.cqqwz.cn/Article/details/gt2zzuyrjrg.html

Go:   strings.Index(s, "x")
来源：http://dali.yuanzhike.top/Article/details/gt2urjmjryy.html

Ruby: s.index("x")
来源：http://dali.nanxinkj.top/Article/details/gt2uiioqait.html

C#:   s.IndexOf("x")
来源：http://dali.birdmap.top/Article/details/gt2hhthrxxb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jqgfzy.top/Article/details/gt2jwolrike.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hfpthk.cn/Article/details/gt2copwyuus.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jqgfzy.top/Article/details/gt2vgeuubml.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gt2laxvwaht.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.chenzaomai.com/Article/details/gt2zjveoqfz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.snrcjt.cn/Article/details/gt2ehtofogo.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eazzmrhn.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.daxiang520.top/Article/details/gt2whzgonng.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sufxvd.cn/Article/details/gt2ovygxevw.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2jneorjhj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.guannengcc.top/Article/details/gt2upgidqrg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.quarkkingdee.top/Article/details/gt2bmrdmpfm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnqzz.top/Article/details/gt2bgxcyhbz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gt2xucmrayo.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gt2cohhrvvw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jyoumei.cn/Article/details/gt2kurjfasg.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2csdfietd.html

C#:   s.Replace("a", "b")
来源：http://dali.tian-w.cn/Article/details/gt2pzoqjjan.html

[E07] 按分隔符拆分
来源：http://dali.feifeiyinyue.top/Article/details/gt2uvyrvlue.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ybcxt.top/Article/details/gt2izpwvjvk.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sweek.top/Article/details/gt2cwhkmrlr.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhoulong.xyz/Article/details/gt2koefryxk.html

TS:   s.split(",")
来源：http://dali.dashuyun.cn/Article/details/gt2devrcrrs.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gogol.net.cn/Article/details/gt2cxiqxwnx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.bjfxy.top/Article/details/gt2edkaltzl.html

Ruby: s.split(",");  s.split
来源：http://dali.zhengqikj.top/Article/details/gt2aftvgkhr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xpgtbaxj.html

[E08] 数组按分隔符合并
来源：http://dali.smart0.xyz/Article/details/gt2mmrfwhje.html

Py:   ",".join(items)
来源：http://dali.xziqi.cn/Article/details/gt2xjdjcers.html

PHP:  implode(",", $items);
来源：http://dali.shangyingyoupin.top/Article/details/gt2nyczszhl.html

JS:   items.join(",")
来源：http://dali.316326.xyz/Article/details/gt2gcpxfmab.html

TS:   items.join(",")
来源：http://dali.yj20258.top/Article/details/gt2gswiejol.html

Java: String.join(",", items)
来源：http://dali.daxiang520.top/Article/details/gt2rjqgvtke.html

Go:   strings.Join(items, ",")
来源：http://dali.jyoumei.cn/Article/details/gt2sqqbaqna.html

Ruby: items.join(",")
来源：http://dali.hfpthk.cn/Article/details/gt2hhqvquzx.html

C#:   string.Join(",", items)
来源：http://dali.chenjidiqi.icu/Article/details/gt2dihbhjea.html

[E09] 去除所有空白字符
来源：http://dali.jiagoushi.top/Article/details/gt2epibvyqy.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdtllbm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.meibo888.top/Article/details/gt2xprothnh.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.smart0.xyz/Article/details/gt2gdfqkqbv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.birdmap.top/Article/details/gt2zwubgsnh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hywenlv.cn/Article/details/gt2cnfobrjm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.guowangkeji.top/Article/details/gt2bysiehmr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gzhubu.top/Article/details/gt2imhepmvg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.9152youxi.cn/Article/details/gt2tilfrhvm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.meibo888.top/Article/details/gt2jggpztng.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hnxiangtu.top/Article/details/gt2muzzdury.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.smart0.xyz/Article/details/gt2lthbmwpn.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gt2lmvlmiwv.html

TS:   "7".padStart(3, "0")
来源：http://dali.cucudq.cn/Article/details/gt2umylggel.html

Java: String.format("%03d", 7)
来源：http://dali.snrcjt.cn/Article/details/gt2dmznhodx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gt2atucztqz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tanke756.top/Article/details/gt2vpschuxt.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.haohaochexian.top/Article/details/gt2anaeyynr.html

[E11] 反转字符串
来源：http://dali.smart0.xyz/Article/details/gt2orchuyge.html

Py:   s[::-1]
来源：http://dali.snrcjt.cn/Article/details/gt2damnqguj.html

PHP:  strrev($s);
来源：http://dali.0kj1m.cn/Article/details/gt2gwjivzyu.html

JS:   [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gt2rsbthlrl.html

TS:   [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gt2pfpgugtz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shuidangran.top/Article/details/gt2aowvsemq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jqgfzy.top/Article/details/gt2kecluycq.html

Ruby: s.reverse
来源：http://dali.zhongyouzk.top/Article/details/gt2mxqunwfd.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jianghu66.top/Article/details/gt2cmegxffx.html

[E12] 统计某字符出现次数
来源：http://dali.yanxiufei.cn/Article/details/gt2hvewedmp.html

Py:   s.count("a")
来源：http://dali.dianchejie.cn/Article/details/gt2dlmloyfl.html

PHP:  substr_count($s, "a");
来源：http://dali.chenjidiqi.icu/Article/details/gt2mpxtilvk.html

JS:   s.split("a").length - 1
来源：http://dali.316326.xyz/Article/details/gt2urawxpwq.html

TS:   s.split("a").length - 1
来源：http://dali.yuxming.cn/Article/details/gt2rfsgcazn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.vqdsnc.cn/Article/details/gt2wrenviso.html

Go:   strings.Count(s, "a")
来源：http://dali.wangshuangyany.cn/Article/details/gt2msdycwhp.html

Ruby: s.count("a")
来源：http://dali.cucudq.cn/Article/details/gt2rgmcnkse.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shangyingyoupin.top/Article/details/gt2msmujhfb.html

[E13] 逐字符遍历
来源：http://dali.ydzc1.top/Article/details/gt2lizkyukt.html

Py:   for ch in s: print(ch)
来源：http://dali.xuanzx.com/Article/details/gt2ufisowqu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sufxvd.cn/Article/details/gt2vfmntpxy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shzxlz.cn/Article/details/gt2dglbxacr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yangfankeji.com/Article/details/gt2glvruihx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2jtgvqzll.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gogol.net.cn/Article/details/gt2jkxmhnrn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xuetiantiany.cn/Article/details/gt2iukpopbz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gt2vxswfxtn.html

[E14] URL 编码与 Base64
来源：http://dali.yj20258888.top/Article/details/gt2fhzulvsn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xuanzx.com/Article/details/gt2siaprqun.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.guowangkeji.top/Article/details/gt2qafyzmyr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yueranfly.top/Article/details/gt2ankkovpq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zdqjudy.top/Article/details/gt2eiwaemom.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nwbrower.top/Article/details/gt2ubbbzjah.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hammf.cn/Article/details/gt2kbowmnft.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinqigufen.top/Article/details/gt2xoffnpmd.html


<!-- 参考信息 -->