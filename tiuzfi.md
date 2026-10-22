代发 wailian999

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.nwbrower.top/Article/details/gt2clkpbhgi.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinqigufen.top/Article/details/gt2apbctemz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xinyue.icu/Article/details/gt2vlcahure.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xziqi.cn/Article/details/gt2wwafyzvp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ydzc1.top/Article/details/gt2wcxfaqws.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.aizwys.cn/Article/details/gt2rwdbemjg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.0kj1m.cn/Article/details/gt2ehbsqjsx.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.fzhhl.top/Article/details/gt2ixpdmqro.html

[D11] 反转数组
来源：http://dali.hammf.cn/Article/details/gt2rduobpht.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.pengpengdd.cyou/Article/details/gt2lptutips.html

PHP:  array_reverse($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2zrppndzg.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gogol.net.cn/Article/details/gt2lksqtzed.html

TS:   [...arr].reverse();
来源：http://dali.shuidangran.top/Article/details/gt2dyvfgqwt.html

Java: Collections.reverse(list);
来源：http://dali.hnxiangtu.top/Article/details/gt2dyvqpcwn.html

Go:   slices.Reverse(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jpwfywkq.html

Ruby: arr.reverse
来源：http://dali.ybcxt.top/Article/details/gt2zhtzdkrd.html

C#:   list.Reverse();
来源：http://dali.svipenyu.cn/Article/details/gt2reywkhdw.html

[D12] 查找元素下标
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2grpifsbf.html

Py:   arr.index(x);  x in arr
来源：http://dali.yangfankeji.com/Article/details/gt2kwmbyzrb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.smart0.xyz/Article/details/gt2jeboqkwj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gogol.net.cn/Article/details/gt2lipjruot.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zdqjudy.top/Article/details/gt2vcrpzkoi.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jqgfzy.top/Article/details/gt2wccsaobi.html

Go:   slices.Index(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gt2djsgmewl.html

Ruby: arr.index(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2yryvblbj.html

C#:   list.IndexOf(x);
来源：http://dali.sweek.top/Article/details/gt2ygdyzqal.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yanxiufei.cn/Article/details/gt2ecgdhgoj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenlongwang.top/Article/details/gt2frjmzgtd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ivvv.top/Article/details/gt2wkckihvk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jlsjyb.cn/Article/details/gt2sgyfbkwz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wpjvezah.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zdqjudy.top/Article/details/gt2ytonybxi.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hammf.cn/Article/details/gt2gxwstlke.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zyxikqrr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jqgfzy.top/Article/details/gt2bewnhcnk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xinyue.icu/Article/details/gt2dpuadcif.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.sweek.top/Article/details/gt2pdoymdue.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hnqzz.top/Article/details/gt2jdowvlob.html

JS:   arr.map(x => x * 2)
来源：http://dali.iojbl.cn/Article/details/gt2qtbdjzsw.html

TS:   arr.map(x => x * 2)
来源：http://dali.pycfn.com/Article/details/gt2pejbfzur.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yj202588.top/Article/details/gt2rxrsruiv.html

Go:   // 手写循环
来源：http://dali.havefunace.top/Article/details/gt2tstmziyi.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.9152youxi.cn/Article/details/gt2gesbwhbk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gt2hjqaggue.html

[D15] 去重
来源：http://dali.zhongyouzk.top/Article/details/gt2ifxtdyqw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ivvv.top/Article/details/gt2sjjkcnqb.html

PHP:  array_unique($arr);
来源：http://dali.jianghu66.top/Article/details/gt2rssvpfed.html

JS:   [...new Set(arr)]
来源：http://dali.hongshengwenyu.top/Article/details/gt2qmimjabb.html

TS:   [...new Set(arr)]
来源：http://dali.havefunace.top/Article/details/gt2lpckmnnb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.birdmap.top/Article/details/gt2wmnpqtyv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.kuanghao11.cn/Article/details/gt2sdvsiqdp.html

Ruby: arr.uniq
来源：http://dali.nwbrower.top/Article/details/gt2xcatfudi.html

C#:   list.Distinct().ToList()
来源：http://dali.dianchejie.cn/Article/details/gt2nfxfsudv.html

[D16] 求和与平均值
来源：http://dali.yvedp.cn/Article/details/gt2lsasnsjt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.birdmap.top/Article/details/gt2skmynomp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.fengsongda.top/Article/details/gt2lhscqezi.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daxiang520.top/Article/details/gt2nrymbmnh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ynhkzfpl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gzhubu.top/Article/details/gt2uofaltdw.html

Go:   // 手写循环累加
来源：http://dali.jianghu66.top/Article/details/gt2btpbumeh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.dianchejie.cn/Article/details/gt2ncdogzgo.html

C#:   list.Sum();  list.Average()
来源：http://dali.zycfv.cn/Article/details/gt2hmmngike.html

[D17] 最大值与最小值
来源：http://dali.yuanzhike.top/Article/details/gt2akswfdxi.html

Py:   max(arr);  min(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cdxuavkw.html

PHP:  max($arr);  min($arr);
来源：http://dali.havefunace.top/Article/details/gt2vemvcscl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yueranfly.top/Article/details/gt2utzlcvng.html

TS:   Math.max(...arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2slnqcrfb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinqigufen.top/Article/details/gt2nbkfmhtk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2cviyguey.html

Ruby: arr.max;  arr.min
来源：http://dali.feifeiyinyue.top/Article/details/gt2ealdgboi.html

C#:   list.Max();  list.Min()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ozruudpg.html

[D18] 扁平化嵌套数组
来源：http://dali.meibo888.top/Article/details/gt2hxmkckgf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mfndtigj.html

PHP:  array_merge(...$nested);
来源：http://dali.hysaishi.cn/Article/details/gt2wwskzhnv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cashguo.top/Article/details/gt2xxswztup.html

TS:   nested.flat();
来源：http://dali.hnxiangtu.top/Article/details/gt2ntepouos.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrgflbb.html

Go:   // 手写双层循环
来源：http://dali.jyoumei.cn/Article/details/gt2epvevryo.html

Ruby: nested.flatten
来源：http://dali.cheryme.top/Article/details/gt2jnoycmbq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yuanzhike.top/Article/details/gt2muucieku.html

[D19] 按字段分组
来源：http://dali.kuanghao11.cn/Article/details/gt2bdioacwb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2tysmzhlz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.birdmap.top/Article/details/gt2behhfigp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gaohongyu789.top/Article/details/gt2zwnhgmmf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wcgenexf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.dianchejie.cn/Article/details/gt2ujgjmtqi.html

Go:   // 手写 map[string][]T
来源：http://dali.ivvv.top/Article/details/gt2lsbvvtrd.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xylfe.cn/Article/details/gt2mhfzjpmk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinqigufen.top/Article/details/gt2aldxpbze.html

[D20] 统计每个元素出现次数
来源：http://dali.cucudq.cn/Article/details/gt2xhftucso.html

Py:   Counter(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2jrekasla.html

PHP:  array_count_values($arr);
来源：http://dali.daria6918.cn/Article/details/gt2pxtgvoal.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jianghu66.top/Article/details/gt2augzrifn.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ivvv.top/Article/details/gt2snqzcker.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gotoacloud.top/Article/details/gt2iafrzrnq.html

Go:   // 手写 map[T]int
来源：http://dali.yonumen.top/Article/details/gt2ztnazkiw.html

Ruby: arr.tally
来源：http://dali.pengpengdd.cyou/Article/details/gt2rhlstpjw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinqigufen.top/Article/details/gt2xbezsryx.html

[D21] 判断是否包含某元素
来源：http://dali.sxryk.cn/Article/details/gt2tpfcsmth.html

Py:   x in arr
来源：http://dali.c1oappe.top/Article/details/gt2xdebolsb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.smart0.xyz/Article/details/gt2juqaimcs.html

JS:   arr.includes(x)
来源：http://dali.haohaochexian.top/Article/details/gt2crcwhljx.html

TS:   arr.includes(x)
来源：http://dali.haohaochexian.top/Article/details/gt2ffygwccb.html

Java: list.contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2avapaace.html

Go:   slices.Contains(arr, x)
来源：http://dali.yj202588.top/Article/details/gt2gfkqbxrx.html

Ruby: arr.include?(x)
来源：http://dali.aizwys.cn/Article/details/gt2ianzmzke.html

C#:   list.Contains(x)
来源：http://dali.redwolf501.top/Article/details/gt2djqkkcmi.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jqgfzy.top/Article/details/gt2fzhqzmnd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cvzicblp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hongshengwenyu.top/Article/details/gt2fegplxuq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mctevryz.html

TS:   [...arr];
来源：http://dali.shuidangran.top/Article/details/gt2cwvpoyhv.html

Java: new ArrayList<>(list);
来源：http://dali.316326.xyz/Article/details/gt2nqedrsiw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jiagoushi.top/Article/details/gt2azwkdeem.html

Ruby: arr.dup;  arr.clone
来源：http://dali.wangshuangyany.cn/Article/details/gt2jlshexft.html

C#:   new List<int>(list);
来源：http://dali.feifeiyinyue.top/Article/details/gt2dzmhyqez.html

[D23] reduce 累积计算
来源：http://dali.daxiang520.top/Article/details/gt2atyecopg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.tanke756.top/Article/details/gt2cvpkokil.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yongpay.top/Article/details/gt2qcmwalxh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xylfe.cn/Article/details/gt2wwwtgjbw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xylfe.cn/Article/details/gt2afnzepss.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jlsjyb.cn/Article/details/gt2pmnglwtx.html

Go:   // 手写循环
来源：http://dali.daria6918.cn/Article/details/gt2vizezkjc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.redwolf501.top/Article/details/gt2erohrukh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cdnleiting.top/Article/details/gt2ubefipac.html

[D24] 字典 / Map 基本操作
来源：http://dali.cdnleiting.top/Article/details/gt2gsteuxcl.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhoulong.xyz/Article/details/gt2ijdbdskx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tanke756.top/Article/details/gt2dvkypnzj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yuanzhike.top/Article/details/gt2hacevble.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gt2jbsbeanm.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cqqwz.cn/Article/details/gt2ajvbaudy.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cqqwz.cn/Article/details/gt2grknmsfb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tanke756.top/Article/details/gt2xtfdzkkc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yuanzhike.top/Article/details/gt2rsibkthl.html

[D25] Set 集合去重与交并差
来源：http://dali.redwolf501.top/Article/details/gt2uuymlpkg.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gotoacloud.top/Article/details/gt2sykixifz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xuanzx.com/Article/details/gt2oouurwep.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2mnnidicf.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2kvvlweti.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2kkvnkbyg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinqigufen.top/Article/details/gt2vzrlnxkk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.daria6918.cn/Article/details/gt2rqsesxat.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.9152youxi.cn/Article/details/gt2oyzcykwz.html

[D26] 数组转字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2lqmsusrz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xinyue.icu/Article/details/gt2uowknnxk.html

PHP:  implode(", ", $arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2dvgrblgi.html

JS:   arr.join(", ")
来源：http://dali.jqgufenzy.top/Article/details/gt2quzldmrv.html

TS:   arr.join(", ")
来源：http://dali.zhengqikj.top/Article/details/gt2yjbbeszb.html

Java: String.join(", ", list)
来源：http://dali.jyoumei.cn/Article/details/gt2qqqbfcda.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yanxiufei.cn/Article/details/gt2ldviahdr.html

Ruby: arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gt2qdenttir.html

C#:   string.Join(", ", list)
来源：http://dali.nanxinkj.top/Article/details/gt2frnllggm.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2zaasgicq.html

E. 字符串处理
来源：http://dali.hywenlv.cn/Article/details/gt2rsehddrc.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2gmcqqygl.html

[E01] 拼接字符串
来源：http://dali.xuanzx.com/Article/details/gt2jorullpx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.dianchejie.cn/Article/details/gt2dobjbiss.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2htrnjrnj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.0kj1m.cn/Article/details/gt2bzezbdha.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daxiang520.top/Article/details/gt2ofusvvjx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinqigfzy.top/Article/details/gt2vghxuchw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.aibaodan.cn/Article/details/gt2mbnhepaf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ydzc1.top/Article/details/gt2alovxpkm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gt2dpnkljbr.html

[E02] 重复字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2afhxwica.html

Py:   "ab" * 3
来源：http://dali.hongshengwenyu.top/Article/details/gt2rfkystor.html

PHP:  str_repeat("ab", 3);
来源：http://dali.iojbl.cn/Article/details/gt2hhhxwthw.html

JS:   "ab".repeat(3)
来源：http://dali.guowangkeji.top/Article/details/gt2cbtzjuyx.html

TS:   "ab".repeat(3)
来源：http://dali.aibaodan.cn/Article/details/gt2evgfiupo.html

Java: "ab".repeat(3)
来源：http://dali.jinqigfzy.top/Article/details/gt2caepjttf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ehwqpu.com/Article/details/gt2leboijgj.html

Ruby: "ab" * 3
来源：http://dali.cucudq.cn/Article/details/gt2savxisxk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ivvv.top/Article/details/gt2yisyoxrg.html

[E03] 截取子串
来源：http://dali.kuanghao11.cn/Article/details/gt2jaqcmchc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hnxiangtu.top/Article/details/gt2bhxaikcc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gt2kkfcrbue.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vstinozz.html

TS:   s.slice(1, 4)
来源：http://dali.cdnleiting.top/Article/details/gt2kvvclfde.html

Java: s.substring(1, 4)
来源：http://dali.fzhhl.top/Article/details/gt2aubvruzu.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.wangdashe.top/Article/details/gt2qkdxdqek.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2uswrfjxm.html

C#:   s.Substring(1, 3)
来源：http://dali.vqdsnc.cn/Article/details/gt2qtipkuxh.html

[E04] 查找子串位置
来源：http://dali.wangdashe.top/Article/details/gt2dfsmufqv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.aizwys.cn/Article/details/gt2bmigzsal.html

PHP:  strpos($s, "x");
来源：http://dali.guannengcc.top/Article/details/gt2txburxzq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sweek.top/Article/details/gt2mwuptxgs.html

TS:   s.indexOf("x")
来源：http://dali.sysykeji.top/Article/details/gt2bknuebzd.html

Java: s.indexOf("x")
来源：http://dali.pycfn.com/Article/details/gt2mbhpmtnd.html

Go:   strings.Index(s, "x")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ymgouyvd.html

Ruby: s.index("x")
来源：http://dali.gotoacloud.top/Article/details/gt2hietsyvt.html

C#:   s.IndexOf("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rrbuytmi.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yangfankeji.com/Article/details/gt2lvrdviub.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yzlwxnxe.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cheryme.top/Article/details/gt2debpsbni.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daria6918.cn/Article/details/gt2vqffyrsi.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yanxiufei.cn/Article/details/gt2cqtszydo.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gt2uvfudeev.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rxipcxtt.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.redwolf501.top/Article/details/gt2tkmlwdjb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.havefunace.top/Article/details/gt2ifsaikoz.html

[E06] 替换子串
来源：http://dali.jqgfzy.top/Article/details/gt2sczjrwdv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gzhubu.top/Article/details/gt2khwdufhq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yangfankeji.com/Article/details/gt2nppkakfk.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pasiqipp.html

TS:   s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gt2utqqcatz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gt2rdcqvwyt.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tanke756.top/Article/details/gt2rqixlwlf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gt2lnqwqrny.html

C#:   s.Replace("a", "b")
来源：http://dali.cucudq.cn/Article/details/gt2itxripbe.html

[E07] 按分隔符拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vxcvzash.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ehwqpu.com/Article/details/gt2gblahdtm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.daria6918.cn/Article/details/gt2nmosdewo.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.guowangkeji.top/Article/details/gt2pjzidkho.html

TS:   s.split(",")
来源：http://dali.hammf.cn/Article/details/gt2lbbczvvi.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shuidangran.top/Article/details/gt2yiejqhma.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2yhgddrnj.html

Ruby: s.split(",");  s.split
来源：http://dali.nwbrower.top/Article/details/gt2smgyrmxb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fbfctwmh.html

[E08] 数组按分隔符合并
来源：http://dali.jlsjyb.cn/Article/details/gt2tuaxvrno.html

Py:   ",".join(items)
来源：http://dali.dashuyun.cn/Article/details/gt2ppkxcwat.html

PHP:  implode(",", $items);
来源：http://dali.xylfe.cn/Article/details/gt2gmpstbja.html

JS:   items.join(",")
来源：http://dali.bjfxy.top/Article/details/gt2bozctkgs.html

TS:   items.join(",")
来源：http://dali.svipenyu.cn/Article/details/gt2ywcudlgo.html

Java: String.join(",", items)
来源：http://dali.daria6918.cn/Article/details/gt2wfwzcvfn.html

Go:   strings.Join(items, ",")
来源：http://dali.redwolf501.top/Article/details/gt2gvytzpsg.html

Ruby: items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gt2wkigqdwa.html

C#:   string.Join(",", items)
来源：http://dali.gotoacloud.top/Article/details/gt2ekipszbd.html

[E09] 去除所有空白字符
来源：http://dali.ppjwa.cn/Article/details/gt2eomytarh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.snrcjt.cn/Article/details/gt2uzxgfljf.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenlongwang.top/Article/details/gt2igypspjv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.svipenyu.cn/Article/details/gt2cdqliqlx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jqgfzy.top/Article/details/gt2krcqaqxk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hysaishi.cn/Article/details/gt2ofrkpyis.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.dashuyun.cn/Article/details/gt2sulvfuus.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hywenlv.cn/Article/details/gt2ftfuszty.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gaohongyu789.top/Article/details/gt2odqvzslw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.mhx1999.top/Article/details/gt2oqskkbah.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gogol.net.cn/Article/details/gt2nurimhuq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.vqdsnc.cn/Article/details/gt2rhlxgyvi.html

JS:   "7".padStart(3, "0")
来源：http://dali.xuanzx.com/Article/details/gt2ckogzkaw.html

TS:   "7".padStart(3, "0")
来源：http://dali.fengsongda.top/Article/details/gt2wlmocfua.html

Java: String.format("%03d", 7)
来源：http://dali.gaohongyu789.top/Article/details/gt2akpmblxu.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gt2qgmfaxbs.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jqgfzy.top/Article/details/gt2ntekbdku.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ehwqpu.com/Article/details/gt2xarnbkdb.html

[E11] 反转字符串
来源：http://dali.dianchejie.cn/Article/details/gt2vqxhlois.html

Py:   s[::-1]
来源：http://dali.pycfn.com/Article/details/gt2zsrhwhbj.html

PHP:  strrev($s);
来源：http://dali.fzhhl.top/Article/details/gt2mkecenct.html

JS:   [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gt2vwxyyfpx.html

TS:   [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gt2lgnrzrqt.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ivbbaoxp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yueranfly.top/Article/details/gt2jefmmkra.html

Ruby: s.reverse
来源：http://dali.snrcjt.cn/Article/details/gt2yiwnkhzo.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yangfankeji.com/Article/details/gt2fcjwcpau.html

[E12] 统计某字符出现次数
来源：http://dali.shangyingyoupin.top/Article/details/gt2lygfbbfn.html

Py:   s.count("a")
来源：http://dali.xuanzx.com/Article/details/gt2myejpsed.html

PHP:  substr_count($s, "a");
来源：http://dali.xuanzx.com/Article/details/gt2aanggpaz.html

JS:   s.split("a").length - 1
来源：http://dali.shuidangran.top/Article/details/gt2prvqfbtb.html

TS:   s.split("a").length - 1
来源：http://dali.snrcjt.cn/Article/details/gt2ngwtrzwi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dtqvdans.html

Go:   strings.Count(s, "a")
来源：http://dali.nanxinkj.top/Article/details/gt2nltdjxew.html

Ruby: s.count("a")
来源：http://dali.bjfxy.top/Article/details/gt2kbjcfhoi.html

C#:   s.Count(c => c == 'a')
来源：http://dali.c1oappe.top/Article/details/gt2xzfvoqub.html

[E13] 逐字符遍历
来源：http://dali.yj20258888.top/Article/details/gt2tiwaiqsl.html

Py:   for ch in s: print(ch)
来源：http://dali.jqgfzy.top/Article/details/gt2raoubiyu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.nwbrower.top/Article/details/gt2gxsgbcvp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gt2qjvaabsh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yonumen.top/Article/details/gt2ijyxanln.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.9152youxi.cn/Article/details/gt2jglgdtzn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinqigufen.top/Article/details/gt2tjedweko.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xuanzx.com/Article/details/gt2pbvxiqmo.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sufxvd.cn/Article/details/gt2iftpphxt.html

[E14] URL 编码与 Base64
来源：http://dali.zhiwuduotai.top/Article/details/gt2arfdfjmb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.nanxuanxn.top/Article/details/gt2cwazrczq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.redwolf501.top/Article/details/gt2gummzkrv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.9152youxi.cn/Article/details/gt2tgkqoxvq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.andypj.xyz/Article/details/gt2icdhtqxu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.iojbl.cn/Article/details/gt2hzsjmwpj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.nwbrower.top/Article/details/gt2mkobvpui.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ocjbxkms.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xylfe.cn/Article/details/gt2swjoxcch.html

[E15] HTML 转义 / 反转义
来源：http://dali.0kj1m.cn/Article/details/gt2rmilyhqo.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sxryk.cn/Article/details/gt2lodnetrm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwkftswn.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.c1oappe.top/Article/details/gt2vuiweclp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cashguo.top/Article/details/gt2ilhlquso.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yuxming.cn/Article/details/gt2sifxpugn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2riplocmo.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cucudq.cn/Article/details/gt2fzlioepf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cashguo.top/Article/details/gt2biaylpgl.html

[E16] 数字千分位
来源：http://dali.fzhhl.top/Article/details/gt2kqqndyox.html

Py:   f"{1234567:,}"
来源：http://dali.ehwqpu.com/Article/details/gt2tignseye.html

PHP:  number_format(1234567);
来源：http://dali.ppjwa.cn/Article/details/gt2gdpgcfqj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.redwolf501.top/Article/details/gt2mhnblvpg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ybcxt.top/Article/details/gt2onbwdwli.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhixingplan.top/Article/details/gt2haxmacpw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.birdmap.top/Article/details/gt2cuqxcoei.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.smart0.xyz/Article/details/gt2aoforpnv.html

C#:   1234567.ToString("N0")
来源：http://dali.yuxming.cn/Article/details/gt2hawqacla.html

[E17] 首字母大写
来源：http://dali.wangshuangyany.cn/Article/details/gt2lpbaebdq.html


<!-- 参考信息 -->