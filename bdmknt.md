代发 wailian999

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.bjfxy.top/Article/details/gt2elhrekyz.html

TS:   [...a, ...b];
来源：http://dali.gotoacloud.top/Article/details/gt2wozvmoki.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jqgfzy.top/Article/details/gt2sehutwbr.html

Go:   append(a, b...)
来源：http://dali.mhx1999.top/Article/details/gt2rmwflfin.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jlsjyb.cn/Article/details/gt2qcipqasz.html

C#:   a.Concat(b).ToList()
来源：http://dali.hnqzz.top/Article/details/gt2ebonwzyy.html

[D09] 排序（升序）
来源：http://dali.cashguo.top/Article/details/gt2cjjzqwkz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnxiangtu.top/Article/details/gt2nxhmedfg.html

PHP:  sort($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2pdhkcfwj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinqigufen.top/Article/details/gt2nclormqz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yangfankeji.com/Article/details/gt2zsdrbqfs.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sxryk.cn/Article/details/gt2fftwchyj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2kxlopfjp.html

Ruby: arr.sort
来源：http://dali.sxryk.cn/Article/details/gt2xgnotnll.html

C#:   list.Sort();
来源：http://dali.gotoacloud.top/Article/details/gt2kpaklmze.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xuanzx.com/Article/details/gt2pxkwkfyu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hywenlv.cn/Article/details/gt2lmtanzfs.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.316326.xyz/Article/details/gt2rguhugtu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shzxlz.cn/Article/details/gt2mzazrbcw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yanxiufei.cn/Article/details/gt2iriapcsq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jlsjyb.cn/Article/details/gt2dgtbnqas.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sufxvd.cn/Article/details/gt2rdvjcbwu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.chenlongwang.top/Article/details/gt2qkhdgnil.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.kuanghao11.cn/Article/details/gt2axbifxyi.html

[D11] 反转数组
来源：http://dali.smart0.xyz/Article/details/gt2bxhizlqp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cdnleiting.top/Article/details/gt2eeeijxbc.html

PHP:  array_reverse($arr);
来源：http://dali.redwolf501.top/Article/details/gt2uxayjclv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.svipenyu.cn/Article/details/gt2oilqgqnj.html

TS:   [...arr].reverse();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vgjvdqpk.html

Java: Collections.reverse(list);
来源：http://dali.ydzc1.top/Article/details/gt2rhzafzwm.html

Go:   slices.Reverse(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2jsunnkjo.html

Ruby: arr.reverse
来源：http://dali.yanxiufei.cn/Article/details/gt2ztihylak.html

C#:   list.Reverse();
来源：http://dali.xylfe.cn/Article/details/gt2cguomcrr.html

[D12] 查找元素下标
来源：http://dali.birdmap.top/Article/details/gt2xofcgmye.html

Py:   arr.index(x);  x in arr
来源：http://dali.yj20258888.top/Article/details/gt2fpmpirsa.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.wangdashe.top/Article/details/gt2tefhwlrw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuxming.cn/Article/details/gt2umazgrsl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yonumen.top/Article/details/gt2faigossl.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yvedp.cn/Article/details/gt2tripnplm.html

Go:   slices.Index(arr, x)
来源：http://dali.yvedp.cn/Article/details/gt2jvnpmqie.html

Ruby: arr.index(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2lzeexhlu.html

C#:   list.IndexOf(x);
来源：http://dali.cheryme.top/Article/details/gt2zcexozou.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shangyingyoupin.top/Article/details/gt2hiychyhw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.gzhubu.top/Article/details/gt2alheugwm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.guowangkeji.top/Article/details/gt2rerrujxo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.iojbl.cn/Article/details/gt2fdgvwwli.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cucudq.cn/Article/details/gt2xcaqhaog.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yj20258888.top/Article/details/gt2jabegbuh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ivvv.top/Article/details/gt2cenzcpwq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yj20258.top/Article/details/gt2jhamhoir.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jiagoushi.top/Article/details/gt2ccozjghc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.snrcjt.cn/Article/details/gt2bocfhakk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2otapxbnv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.iojbl.cn/Article/details/gt2klqpcbwg.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2qsegbgof.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lgwbjyof.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yuanzhike.top/Article/details/gt2cfwbotix.html

Go:   // 手写循环
来源：http://dali.chenlongwang.top/Article/details/gt2stdtzrfo.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wwgvqfkk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.daria6918.cn/Article/details/gt2srqxnzfi.html

[D15] 去重
来源：http://dali.jinqigufen.top/Article/details/gt2fktqejlt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.c1oappe.top/Article/details/gt2vaksnmgp.html

PHP:  array_unique($arr);
来源：http://dali.jianghu66.top/Article/details/gt2pisovovo.html

JS:   [...new Set(arr)]
来源：http://dali.mhx1999.top/Article/details/gt2yldpynhg.html

TS:   [...new Set(arr)]
来源：http://dali.yueranfly.top/Article/details/gt2cytdsyju.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.guowangkeji.top/Article/details/gt2moctxdvb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.meibo888.top/Article/details/gt2svdawfcb.html

Ruby: arr.uniq
来源：http://dali.xuanzx.com/Article/details/gt2uqmbwwin.html

C#:   list.Distinct().ToList()
来源：http://dali.snrcjt.cn/Article/details/gt2jenvjhad.html

[D16] 求和与平均值
来源：http://dali.jinqigufen.top/Article/details/gt2uwfdaoba.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2oggynznh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cdnleiting.top/Article/details/gt2jjtdgaqb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2pvklzflj.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.birdmap.top/Article/details/gt2bswxbpai.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.tianlin.xyz/Article/details/gt2juyrhbub.html

Go:   // 手写循环累加
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2siyxjgjk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.smart0.xyz/Article/details/gt2bipzyymx.html

C#:   list.Sum();  list.Average()
来源：http://dali.9152youxi.cn/Article/details/gt2cwwigcgd.html

[D17] 最大值与最小值
来源：http://dali.birdmap.top/Article/details/gt2whpzpwet.html

Py:   max(arr);  min(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2blknuejn.html

PHP:  max($arr);  min($arr);
来源：http://dali.gogol.net.cn/Article/details/gt2azkmenot.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xziqi.cn/Article/details/gt2aobzojbo.html

TS:   Math.max(...arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2tdeezbrz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jqgufenzy.top/Article/details/gt2zdxvptxc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.haohaochexian.top/Article/details/gt2pblvmuhe.html

Ruby: arr.max;  arr.min
来源：http://dali.hammf.cn/Article/details/gt2xoxxqhhl.html

C#:   list.Max();  list.Min()
来源：http://dali.mhx1999.top/Article/details/gt2jxwsqtte.html

[D18] 扁平化嵌套数组
来源：http://dali.bjfxy.top/Article/details/gt2ruvmpuaj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.316326.xyz/Article/details/gt2pkprecen.html

PHP:  array_merge(...$nested);
来源：http://dali.dashuyun.cn/Article/details/gt2awnxksgf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.chenjidiqi.icu/Article/details/gt2cqbqvryz.html

TS:   nested.flat();
来源：http://dali.meibo888.top/Article/details/gt2zoxjywsi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zycfv.cn/Article/details/gt2enshdtsb.html

Go:   // 手写双层循环
来源：http://dali.yj20258.top/Article/details/gt2aymtnjmm.html

Ruby: nested.flatten
来源：http://dali.guannengcc.top/Article/details/gt2esncszho.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ehwqpu.com/Article/details/gt2yznkpagd.html

[D19] 按字段分组
来源：http://dali.guannengcc.top/Article/details/gt2jehgvvwq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yj20258.top/Article/details/gt2yzvuesrm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sxryk.cn/Article/details/gt2hukqlsnl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xgxcwuvl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xndhsuwl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.andypj.xyz/Article/details/gt2bfqyncwo.html

Go:   // 手写 map[string][]T
来源：http://dali.hongshengwenyu.top/Article/details/gt2oayfrldf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.tianlin.xyz/Article/details/gt2auojidsm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.chenjidiqi.icu/Article/details/gt2bmotssxh.html

[D20] 统计每个元素出现次数
来源：http://dali.xziqi.cn/Article/details/gt2ptgiingh.html

Py:   Counter(arr)
来源：http://dali.andypj.xyz/Article/details/gt2wbbzgvqa.html

PHP:  array_count_values($arr);
来源：http://dali.cashguo.top/Article/details/gt2bvpztbiz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ehwqpu.com/Article/details/gt2ygevfjvd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenlongwang.top/Article/details/gt2olbxypdt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.wangshuangyany.cn/Article/details/gt2kpxamchk.html

Go:   // 手写 map[T]int
来源：http://dali.hnxiangtu.top/Article/details/gt2gucyufze.html

Ruby: arr.tally
来源：http://dali.xuanzx.com/Article/details/gt2wrucegwg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cheryme.top/Article/details/gt2qipuzkxm.html

[D21] 判断是否包含某元素
来源：http://dali.zhengqikj.top/Article/details/gt2slumhrxq.html

Py:   x in arr
来源：http://dali.jinqigufen.top/Article/details/gt2ahdbbvnq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gzhubu.top/Article/details/gt2nayhnmfj.html

JS:   arr.includes(x)
来源：http://dali.jinqigufen.top/Article/details/gt2polvkhuv.html

TS:   arr.includes(x)
来源：http://dali.hammf.cn/Article/details/gt2cxuzwvgx.html

Java: list.contains(x)
来源：http://dali.sufxvd.cn/Article/details/gt2jxnojzvd.html

Go:   slices.Contains(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gt2sfcujhor.html

Ruby: arr.include?(x)
来源：http://dali.chenlongwang.top/Article/details/gt2cbauuane.html

C#:   list.Contains(x)
来源：http://dali.c1oappe.top/Article/details/gt2vvuhkblo.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yongpay.top/Article/details/gt2xsgwkejl.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2joeqpeds.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.daria6918.cn/Article/details/gt2esfiodor.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yueranfly.top/Article/details/gt2vnpxseyy.html

TS:   [...arr];
来源：http://dali.iojbl.cn/Article/details/gt2kqveuzem.html

Java: new ArrayList<>(list);
来源：http://dali.pengpengdd.cyou/Article/details/gt2cgyzzjnq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj20258888.top/Article/details/gt2undznvik.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jianghu66.top/Article/details/gt2aaltwkdm.html

C#:   new List<int>(list);
来源：http://dali.yj202588.top/Article/details/gt2obqpzttl.html

[D23] reduce 累积计算
来源：http://dali.svipenyu.cn/Article/details/gt2xhaxyhvk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.9152youxi.cn/Article/details/gt2cictzqrq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.fzhhl.top/Article/details/gt2drlczaaz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2njezrzdw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj202588.top/Article/details/gt2nxpjxyul.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ydzc1.top/Article/details/gt2wwgfukcm.html

Go:   // 手写循环
来源：http://dali.nwbrower.top/Article/details/gt2hqrctzxz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.fengsongda.top/Article/details/gt2rvniehqx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.birdmap.top/Article/details/gt2ssnwecza.html

[D24] 字典 / Map 基本操作
来源：http://dali.dashuyun.cn/Article/details/gt2mzqzkduw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinqigfzy.top/Article/details/gt2ddijeqcq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gaohongyu789.top/Article/details/gt2keydqygo.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.chenlongwang.top/Article/details/gt2udtbpatu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rjcejcne.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.nanxuanxn.top/Article/details/gt2ypsiwdoa.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tian-w.cn/Article/details/gt2xwxtefyu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.aibaodan.cn/Article/details/gt2kehuhvdy.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kcxdsovz.html

[D25] Set 集合去重与交并差
来源：http://dali.havefunace.top/Article/details/gt2ipwhyyoa.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gogol.net.cn/Article/details/gt2mhewqowu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.dianchejie.cn/Article/details/gt2tfhfxysc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shzxlz.cn/Article/details/gt2sqoarewq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.smart0.xyz/Article/details/gt2aefdrojo.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.birdmap.top/Article/details/gt2cgskazqf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.vqdsnc.cn/Article/details/gt2efwmbhwv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hammf.cn/Article/details/gt2aviyerph.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ovvthztk.html

[D26] 数组转字符串
来源：http://dali.tian-w.cn/Article/details/gt2dcvczfkf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shuidangran.top/Article/details/gt2qpcuucfv.html

PHP:  implode(", ", $arr);
来源：http://dali.jqgfzy.top/Article/details/gt2ceozrjng.html

JS:   arr.join(", ")
来源：http://dali.jianghu66.top/Article/details/gt2nakjkloz.html

TS:   arr.join(", ")
来源：http://dali.yuxming.cn/Article/details/gt2gzirefxn.html

Java: String.join(", ", list)
来源：http://dali.cdnleiting.top/Article/details/gt2djyqaxhl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sxryk.cn/Article/details/gt2kqrxorkd.html

Ruby: arr.join(", ")
来源：http://dali.hnqzz.top/Article/details/gt2vnjybdeo.html

C#:   string.Join(", ", list)
来源：http://dali.yanxiufei.cn/Article/details/gt2tffdlwbn.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2hxxjtdwa.html

E. 字符串处理
来源：http://dali.hnxiangtu.top/Article/details/gt2rsufvhbl.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2lygirqhd.html

[E01] 拼接字符串
来源：http://dali.sufxvd.cn/Article/details/gt2rgtkejyt.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hysaishi.cn/Article/details/gt2olvtkycw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xuetiantiany.cn/Article/details/gt2uanzierx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.9152youxi.cn/Article/details/gt2ltrjphpv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.quarkkingdee.top/Article/details/gt2xkraszmq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cucudq.cn/Article/details/gt2rsaihfqb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.guannengcc.top/Article/details/gt2acljyjfm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zdqjudy.top/Article/details/gt2eyaoosxq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ybcxt.top/Article/details/gt2rtkdbkxh.html

[E02] 重复字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2jqhxhczf.html

Py:   "ab" * 3
来源：http://dali.smart0.xyz/Article/details/gt2mwsizlvm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.daxiang520.top/Article/details/gt2vikswgkl.html

JS:   "ab".repeat(3)
来源：http://dali.yvedp.cn/Article/details/gt2rctoqczx.html

TS:   "ab".repeat(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vijbjxvl.html

Java: "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gt2wglpdtzd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.c1oappe.top/Article/details/gt2qboyabxg.html

Ruby: "ab" * 3
来源：http://dali.xinyue.icu/Article/details/gt2hhhedvkh.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zdqjudy.top/Article/details/gt2mzaidgix.html

[E03] 截取子串
来源：http://dali.cdnleiting.top/Article/details/gt2siwclvpt.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.svipenyu.cn/Article/details/gt2zttyamsq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gt2swlbupwn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.chenzaomai.com/Article/details/gt2cbblggxc.html

TS:   s.slice(1, 4)
来源：http://dali.zhixingplan.top/Article/details/gt2cjxbshnf.html

Java: s.substring(1, 4)
来源：http://dali.wangdashe.top/Article/details/gt2qedsrags.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gzhubu.top/Article/details/gt2dggmvrjs.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zdqjudy.top/Article/details/gt2mmeoqetd.html

C#:   s.Substring(1, 3)
来源：http://dali.hnqzz.top/Article/details/gt2ojjfsnbt.html

[E04] 查找子串位置
来源：http://dali.zhixingplan.top/Article/details/gt2jlbdofoh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.daxiang520.top/Article/details/gt2isethult.html

PHP:  strpos($s, "x");
来源：http://dali.jinqigufen.top/Article/details/gt2hkygmxcb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.quarkkingdee.top/Article/details/gt2cugctrhn.html

TS:   s.indexOf("x")
来源：http://dali.yvedp.cn/Article/details/gt2uilojrpc.html

Java: s.indexOf("x")
来源：http://dali.ehwqpu.com/Article/details/gt2lqerjopq.html

Go:   strings.Index(s, "x")
来源：http://dali.feifeiyinyue.top/Article/details/gt2tbidhqry.html

Ruby: s.index("x")
来源：http://dali.zhengqikj.top/Article/details/gt2uybabqmi.html

C#:   s.IndexOf("x")
来源：http://dali.yonumen.top/Article/details/gt2calzxksy.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.meibo888.top/Article/details/gt2npmpcuae.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.tanke756.top/Article/details/gt2cujyeohg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cashguo.top/Article/details/gt2dkmwbrxd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhoulong.xyz/Article/details/gt2ocxgeqwi.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ppjwa.cn/Article/details/gt2blspmtha.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zdqjudy.top/Article/details/gt2nnkqpaxi.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yanxiufei.cn/Article/details/gt2ntjagghc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yangfankeji.com/Article/details/gt2llruqttc.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.dashuyun.cn/Article/details/gt2bmcbnulv.html

[E06] 替换子串
来源：http://dali.cucudq.cn/Article/details/gt2ahvirpwx.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yj20258888.top/Article/details/gt2mshlfvuf.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.chenlongwang.top/Article/details/gt2qomjyxdf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gt2oxavbsnu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gt2weqkqnif.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gt2uveayrai.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2fufvybov.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.meibo888.top/Article/details/gt2kotwdvcw.html

C#:   s.Replace("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jlscsvhj.html

[E07] 按分隔符拆分
来源：http://dali.gotoacloud.top/Article/details/gt2ieoyvaam.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2nqygocri.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.svipenyu.cn/Article/details/gt2feitvfwe.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hfpthk.cn/Article/details/gt2lwjnwbrw.html

TS:   s.split(",")
来源：http://dali.yj20258888.top/Article/details/gt2ppkjsvfx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xuanzx.com/Article/details/gt2hgasdtqc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yuxming.cn/Article/details/gt2wpjekfyp.html

Ruby: s.split(",");  s.split
来源：http://dali.birdmap.top/Article/details/gt2ctyokftb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kipoaowr.html

[E08] 数组按分隔符合并
来源：http://dali.sxryk.cn/Article/details/gt2rmgzmuym.html

Py:   ",".join(items)
来源：http://dali.yongpay.top/Article/details/gt2bkgbdrdk.html

PHP:  implode(",", $items);
来源：http://dali.zhoulong.xyz/Article/details/gt2bodaorfh.html

JS:   items.join(",")
来源：http://dali.cashguo.top/Article/details/gt2uanknmaj.html

TS:   items.join(",")
来源：http://dali.zdqjudy.top/Article/details/gt2kixvlufr.html

Java: String.join(",", items)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iphrwhwc.html

Go:   strings.Join(items, ",")
来源：http://dali.aizwys.cn/Article/details/gt2mbhvobon.html

Ruby: items.join(",")
来源：http://dali.yuxming.cn/Article/details/gt2hwppbkdt.html

C#:   string.Join(",", items)
来源：http://dali.daxiang520.top/Article/details/gt2awafvrok.html

[E09] 去除所有空白字符
来源：http://dali.aibaodan.cn/Article/details/gt2cnolupyj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.tian-w.cn/Article/details/gt2jpkkcefl.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.guannengcc.top/Article/details/gt2euamtpii.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rfoepknq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.mhx1999.top/Article/details/gt2egqizqie.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.pengpengdd.cyou/Article/details/gt2pxgbwfxo.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.c1oappe.top/Article/details/gt2yisfsnhm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xuanzx.com/Article/details/gt2wsjvriea.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xylfe.cn/Article/details/gt2wkdianbu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.guannengcc.top/Article/details/gt2suxmwzct.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gt2uxmqslen.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jiagoushi.top/Article/details/gt2rykrrfpb.html

JS:   "7".padStart(3, "0")
来源：http://dali.nwbrower.top/Article/details/gt2rgtafmun.html

TS:   "7".padStart(3, "0")
来源：http://dali.yuanzhike.top/Article/details/gt2humzvtuu.html

Java: String.format("%03d", 7)
来源：http://dali.tianlin.xyz/Article/details/gt2ysjwuqvv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.fengsongda.top/Article/details/gt2cauzrejl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tmkudkbi.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.bjfxy.top/Article/details/gt2wicpvmpc.html

[E11] 反转字符串
来源：http://dali.nanxinkj.top/Article/details/gt2kpgwovik.html

Py:   s[::-1]
来源：http://dali.gaohongyu789.top/Article/details/gt2akykmfxk.html

PHP:  strrev($s);
来源：http://dali.jiagoushi.top/Article/details/gt2aeyztfoe.html

JS:   [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gt2znhzlopt.html

TS:   [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gt2xzbisbys.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xuanzx.com/Article/details/gt2rizzmpxl.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ppjwa.cn/Article/details/gt2appnfxnq.html

Ruby: s.reverse
来源：http://dali.hysaishi.cn/Article/details/gt2cxqznzie.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.vqdsnc.cn/Article/details/gt2tqtrhqzj.html

[E12] 统计某字符出现次数
来源：http://dali.ydzc1.top/Article/details/gt2ldgyvfdh.html

Py:   s.count("a")
来源：http://dali.aibaodan.cn/Article/details/gt2wparxzhm.html

PHP:  substr_count($s, "a");
来源：http://dali.gogol.net.cn/Article/details/gt2dxdnrfbv.html

JS:   s.split("a").length - 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eupijmog.html

TS:   s.split("a").length - 1
来源：http://dali.yangfankeji.com/Article/details/gt2jlupdudp.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.dashuyun.cn/Article/details/gt2zebgcdpw.html

Go:   strings.Count(s, "a")
来源：http://dali.vqdsnc.cn/Article/details/gt2kkepoyoh.html

Ruby: s.count("a")
来源：http://dali.xinyue.icu/Article/details/gt2bbhtsshp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shzxlz.cn/Article/details/gt2hayanjtf.html

[E13] 逐字符遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2puvnrtoj.html

Py:   for ch in s: print(ch)
来源：http://dali.jqgufenzy.top/Article/details/gt2yorihxze.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.tianlin.xyz/Article/details/gt2ermlvlif.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hfpthk.cn/Article/details/gt2kgzgfeji.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guannengcc.top/Article/details/gt2colmyppj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.tian-w.cn/Article/details/gt2nxklskwl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinqigfzy.top/Article/details/gt2xewpmkhy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yvedp.cn/Article/details/gt2sinybdiu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hywenlv.cn/Article/details/gt2bxcsucle.html

[E14] URL 编码与 Base64
来源：http://dali.guowangkeji.top/Article/details/gt2wbevzmrp.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.0kj1m.cn/Article/details/gt2oouwbmwq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gogol.net.cn/Article/details/gt2tmihnyym.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yvedp.cn/Article/details/gt2hkbmefqr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zdqjudy.top/Article/details/gt2uponbthj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.guowangkeji.top/Article/details/gt2ynsuvfry.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.0kj1m.cn/Article/details/gt2kaatshke.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jfrapzoc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.nanxinkj.top/Article/details/gt2eeforvpt.html

[E15] HTML 转义 / 反转义
来源：http://dali.jqgufenzy.top/Article/details/gt2gccsmeqa.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinqigufen.top/Article/details/gt2jlpubdpv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cheryme.top/Article/details/gt2vfqhnmla.html


<!-- 参考信息 -->