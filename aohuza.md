代发 wailian999

Java: list.size();
来源：http://dali.chenzaomai.com/Article/details/gt2twtjydyp.html

Go:   len(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2xubudrjp.html

Ruby: arr.length; arr.size
来源：http://dali.hfpthk.cn/Article/details/gt2wedewufp.html

C#:   list.Count;
来源：http://dali.jinqigufen.top/Article/details/gt2fsxtlpzq.html

[D07] 切片 / 取子数组
来源：http://dali.aibaodan.cn/Article/details/gt2pyivzzgb.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.wangshuangyany.cn/Article/details/gt2spgojsrj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.vqdsnc.cn/Article/details/gt2dfzhevyx.html

JS:   arr.slice(1, 4);
来源：http://dali.meibo888.top/Article/details/gt2agshldrz.html

TS:   arr.slice(1, 4);
来源：http://dali.xinyue.icu/Article/details/gt2agoucsvv.html

Java: list.subList(1, 4);
来源：http://dali.fengsongda.top/Article/details/gt2uostjblb.html

Go:   arr[1:4]
来源：http://dali.gogol.net.cn/Article/details/gt2ufchoxbw.html

Ruby: arr[1, 3]
来源：http://dali.pycfn.com/Article/details/gt2miigltoh.html

C#:   list.GetRange(1, 3);
来源：http://dali.hysaishi.cn/Article/details/gt2rudwkymz.html

[D08] 合并两个数组
来源：http://dali.shuidangran.top/Article/details/gt2wvtnfidn.html

Py:   a + b;  a.extend(b)
来源：http://dali.cashguo.top/Article/details/gt2okfoyjgx.html

PHP:  array_merge($a, $b);
来源：http://dali.xziqi.cn/Article/details/gt2ghatzlew.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.wangshuangyany.cn/Article/details/gt2qrntxqpg.html

TS:   [...a, ...b];
来源：http://dali.xziqi.cn/Article/details/gt2gbnmmngs.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sufxvd.cn/Article/details/gt2ngkcdsoe.html

Go:   append(a, b...)
来源：http://dali.birdmap.top/Article/details/gt2cthrpdgu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2fduyouvz.html

C#:   a.Concat(b).ToList()
来源：http://dali.fengsongda.top/Article/details/gt2gnoiktwd.html

[D09] 排序（升序）
来源：http://dali.dianchejie.cn/Article/details/gt2ggcbnhyq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zycfv.cn/Article/details/gt2rmddyysr.html

PHP:  sort($arr);
来源：http://dali.chenlongwang.top/Article/details/gt2biumriif.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinqigfzy.top/Article/details/gt2ohwvkgye.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.birdmap.top/Article/details/gt2svzvaloq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.guannengcc.top/Article/details/gt2jiplevjs.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yvedp.cn/Article/details/gt2kdvpshar.html

Ruby: arr.sort
来源：http://dali.daria6918.cn/Article/details/gt2kndiukrk.html

C#:   list.Sort();
来源：http://dali.zycfv.cn/Article/details/gt2qergdgte.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yj202588.top/Article/details/gt2kbvvhmye.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhixingplan.top/Article/details/gt2igyxvlyc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.wangdashe.top/Article/details/gt2vvqtkmut.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ybcxt.top/Article/details/gt2ryjgczhp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgufenzy.top/Article/details/gt2bplfatdy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zycfv.cn/Article/details/gt2igiuvdwm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.fengsongda.top/Article/details/gt2xdulhdfn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hongshengwenyu.top/Article/details/gt2jabnyzfr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hammf.cn/Article/details/gt2fakifwop.html

[D11] 反转数组
来源：http://dali.yanxiufei.cn/Article/details/gt2eavrwofq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.havefunace.top/Article/details/gt2lnrfxdhp.html

PHP:  array_reverse($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2pblzxiit.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhixingplan.top/Article/details/gt2gecucuzl.html

TS:   [...arr].reverse();
来源：http://dali.fengsongda.top/Article/details/gt2geumkcra.html

Java: Collections.reverse(list);
来源：http://dali.shangyingyoupin.top/Article/details/gt2zgpkvcht.html

Go:   slices.Reverse(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2sorjnivd.html

Ruby: arr.reverse
来源：http://dali.guowangkeji.top/Article/details/gt2fbwadyqj.html

C#:   list.Reverse();
来源：http://dali.tian-w.cn/Article/details/gt2fgbjpwav.html

[D12] 查找元素下标
来源：http://dali.jyoumei.cn/Article/details/gt2mjvvonpx.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinqigfzy.top/Article/details/gt2lhfdtdty.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ivvv.top/Article/details/gt2bziefzvs.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.redwolf501.top/Article/details/gt2slcnzkxv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cdnleiting.top/Article/details/gt2pcjydrdm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhixingplan.top/Article/details/gt2lguqbsuq.html

Go:   slices.Index(arr, x)
来源：http://dali.tian-w.cn/Article/details/gt2gijwqzor.html

Ruby: arr.index(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ejfhbvdr.html

C#:   list.IndexOf(x);
来源：http://dali.hywenlv.cn/Article/details/gt2aivxgfie.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sysykeji.top/Article/details/gt2aqefnmfu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jqgfzy.top/Article/details/gt2igdkczpn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.guannengcc.top/Article/details/gt2lzhmjdfc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2dfnvsetc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hnqzz.top/Article/details/gt2wbdvdcvk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yj202588.top/Article/details/gt2foxoxtcn.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yuxming.cn/Article/details/gt2cymwxuhm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yuanzhike.top/Article/details/gt2wnirkllu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cqqwz.cn/Article/details/gt2fgbyutvk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.wangshuangyany.cn/Article/details/gt2sshlcbeu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hywenlv.cn/Article/details/gt2dvyszore.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.iojbl.cn/Article/details/gt2lwrybruz.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinqigufen.top/Article/details/gt2bjxciaup.html

TS:   arr.map(x => x * 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2pzbdjthg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cvrshssi.html

Go:   // 手写循环
来源：http://dali.iojbl.cn/Article/details/gt2ljiucyse.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yuanzhike.top/Article/details/gt2qarpvexq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hysaishi.cn/Article/details/gt2zpsfdgvo.html

[D15] 去重
来源：http://dali.yangfankeji.com/Article/details/gt2pckocyin.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xuetiantiany.cn/Article/details/gt2wwfkcdem.html

PHP:  array_unique($arr);
来源：http://dali.jqgfzy.top/Article/details/gt2kwlreugm.html

JS:   [...new Set(arr)]
来源：http://dali.yj20258.top/Article/details/gt2pfhexfaa.html

TS:   [...new Set(arr)]
来源：http://dali.dashuyun.cn/Article/details/gt2vhgtyhkk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.andypj.xyz/Article/details/gt2bzirudyf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hywenlv.cn/Article/details/gt2wsodhfux.html

Ruby: arr.uniq
来源：http://dali.birdmap.top/Article/details/gt2nawutzcf.html

C#:   list.Distinct().ToList()
来源：http://dali.hfpthk.cn/Article/details/gt2niffvasc.html

[D16] 求和与平均值
来源：http://dali.ppjwa.cn/Article/details/gt2zqnipkxe.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zycfv.cn/Article/details/gt2yqyplflo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zycfv.cn/Article/details/gt2wvkbzhcw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.svipenyu.cn/Article/details/gt2ghtfsvhb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jiagoushi.top/Article/details/gt2xmmfptyp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yuanzhike.top/Article/details/gt2jncvgepm.html

Go:   // 手写循环累加
来源：http://dali.jiagoushi.top/Article/details/gt2cgdrgahb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.fengsongda.top/Article/details/gt2dazviuem.html

C#:   list.Sum();  list.Average()
来源：http://dali.hysaishi.cn/Article/details/gt2qsfizdri.html

[D17] 最大值与最小值
来源：http://dali.yj20258.top/Article/details/gt2qesqmrne.html

Py:   max(arr);  min(arr)
来源：http://dali.yj20258.top/Article/details/gt2delobhtx.html

PHP:  max($arr);  min($arr);
来源：http://dali.yangfankeji.com/Article/details/gt2yntmzxdq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cheryme.top/Article/details/gt2yiumorhe.html

TS:   Math.max(...arr);
来源：http://dali.ivvv.top/Article/details/gt2qwsfhbhc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.mhx1999.top/Article/details/gt2ukbmplvc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2yiwghygm.html

Ruby: arr.max;  arr.min
来源：http://dali.hysaishi.cn/Article/details/gt2uhxiwvtl.html

C#:   list.Max();  list.Min()
来源：http://dali.gogol.net.cn/Article/details/gt2ilrbfsac.html

[D18] 扁平化嵌套数组
来源：http://dali.vqdsnc.cn/Article/details/gt2odlvdevg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.havefunace.top/Article/details/gt2ccrrarhi.html

PHP:  array_merge(...$nested);
来源：http://dali.havefunace.top/Article/details/gt2xzouanyc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xylfe.cn/Article/details/gt2oangrsad.html

TS:   nested.flat();
来源：http://dali.ivvv.top/Article/details/gt2zeeudbnt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cucudq.cn/Article/details/gt2lwehjwbt.html

Go:   // 手写双层循环
来源：http://dali.zhoulong.xyz/Article/details/gt2ntcssyel.html

Ruby: nested.flatten
来源：http://dali.hywenlv.cn/Article/details/gt2dmsddkzu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ydzc1.top/Article/details/gt2hzubbdnt.html

[D19] 按字段分组
来源：http://dali.0kj1m.cn/Article/details/gt2ttqddyty.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yanxiufei.cn/Article/details/gt2oefrhovq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtkdyih.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.kuanghao11.cn/Article/details/gt2euiatxxl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.guannengcc.top/Article/details/gt2svpdrzmn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cucudq.cn/Article/details/gt2hewqgkkq.html

Go:   // 手写 map[string][]T
来源：http://dali.chenjidiqi.icu/Article/details/gt2unxeskkw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hnxiangtu.top/Article/details/gt2tupwyfkn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.tianlin.xyz/Article/details/gt2ghvikdcn.html

[D20] 统计每个元素出现次数
来源：http://dali.nanxuanxn.top/Article/details/gt2iawwtcfy.html

Py:   Counter(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2wodxnmbi.html

PHP:  array_count_values($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2owtbjvmc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigfzy.top/Article/details/gt2gbcybluf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258.top/Article/details/gt2nabutiqd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.havefunace.top/Article/details/gt2wrneoepc.html

Go:   // 手写 map[T]int
来源：http://dali.yanxiufei.cn/Article/details/gt2dnbgrmuz.html

Ruby: arr.tally
来源：http://dali.sxryk.cn/Article/details/gt2rvuqhzsc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yhkgtqhn.html

[D21] 判断是否包含某元素
来源：http://dali.smart0.xyz/Article/details/gt2lqtythsk.html

Py:   x in arr
来源：http://dali.yj202588.top/Article/details/gt2ojvdazkk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xuanzx.com/Article/details/gt2vpffkxor.html

JS:   arr.includes(x)
来源：http://dali.ydzc1.top/Article/details/gt2xjpmblpy.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqiqwxo.html

Java: list.contains(x)
来源：http://dali.9152youxi.cn/Article/details/gt2vkbwmmds.html

Go:   slices.Contains(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gt2moufnzre.html

Ruby: arr.include?(x)
来源：http://dali.dianchejie.cn/Article/details/gt2vlzhwlqc.html

C#:   list.Contains(x)
来源：http://dali.ydzc1.top/Article/details/gt2pmhjqvxh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sweek.top/Article/details/gt2aexiyptx.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ppisbcgv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cheryme.top/Article/details/gt2iaszhbot.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2hmprstit.html

TS:   [...arr];
来源：http://dali.meibo888.top/Article/details/gt2stctkvtg.html

Java: new ArrayList<>(list);
来源：http://dali.iojbl.cn/Article/details/gt2fxsbagnk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj202588.top/Article/details/gt2ibltxoti.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sweek.top/Article/details/gt2jalfijma.html

C#:   new List<int>(list);
来源：http://dali.meibo888.top/Article/details/gt2ouqtgvlb.html

[D23] reduce 累积计算
来源：http://dali.wangshuangyany.cn/Article/details/gt2obtyfkrs.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2ngheirwg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xuanzx.com/Article/details/gt2ikzqjbpo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xszhlfpp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fzhhl.top/Article/details/gt2cneejbbi.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tian-w.cn/Article/details/gt2mosskxmp.html

Go:   // 手写循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fzmanbxz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.snrcjt.cn/Article/details/gt2rnpubxlp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.meibo888.top/Article/details/gt2ttmgewpn.html

[D24] 字典 / Map 基本操作
来源：http://dali.9152youxi.cn/Article/details/gt2aosaajrt.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.fzhhl.top/Article/details/gt2mrglagdx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yongpay.top/Article/details/gt2egmuguzx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinqigfzy.top/Article/details/gt2dtsdsiop.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yj202588.top/Article/details/gt2kvyjrcfe.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zycfv.cn/Article/details/gt2wptlayap.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yj202588.top/Article/details/gt2xhqfdmjg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.wangshuangyany.cn/Article/details/gt2yrwkrqbe.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xuanzx.com/Article/details/gt2hjzsglxh.html

[D25] Set 集合去重与交并差
来源：http://dali.yj202588.top/Article/details/gt2achylyam.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cheryme.top/Article/details/gt2gdzuaudg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.tianlin.xyz/Article/details/gt2qxbfkbuj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenlongwang.top/Article/details/gt2roxatpwx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hammf.cn/Article/details/gt2kgzueeju.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.aizwys.cn/Article/details/gt2fejtncnf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.birdmap.top/Article/details/gt2ymfbdzij.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yfvvbrxi.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yj202588.top/Article/details/gt2urcptydo.html

[D26] 数组转字符串
来源：http://dali.sysykeji.top/Article/details/gt2wkiolxna.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jqgufenzy.top/Article/details/gt2uayxrikq.html

PHP:  implode(", ", $arr);
来源：http://dali.yangfankeji.com/Article/details/gt2jsqeexxa.html

JS:   arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gt2qqekzlnu.html

TS:   arr.join(", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mbamrpsl.html

Java: String.join(", ", list)
来源：http://dali.hywenlv.cn/Article/details/gt2yuzvbpyt.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shuidangran.top/Article/details/gt2hvekofoe.html

Ruby: arr.join(", ")
来源：http://dali.bjfxy.top/Article/details/gt2gxygjnkr.html

C#:   string.Join(", ", list)
来源：http://dali.c1oappe.top/Article/details/gt2irebexdl.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2esrdptwn.html

E. 字符串处理
来源：http://dali.birdmap.top/Article/details/gt2texgavbb.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2egwqdcqy.html

[E01] 拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gt2rvcpxked.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinqigfzy.top/Article/details/gt2mfaaevrk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sysykeji.top/Article/details/gt2pqyepzdg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.mhx1999.top/Article/details/gt2kymydany.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jiagoushi.top/Article/details/gt2hwtermgw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tianlin.xyz/Article/details/gt2xhkxrhbu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cdnleiting.top/Article/details/gt2ggbxdium.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.meibo888.top/Article/details/gt2rvfpeqnc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gt2rwdhnvzf.html

[E02] 重复字符串
来源：http://dali.ydzc1.top/Article/details/gt2cggfjmqr.html

Py:   "ab" * 3
来源：http://dali.xuanzx.com/Article/details/gt2skayiurm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jqgufenzy.top/Article/details/gt2eedyapkc.html

JS:   "ab".repeat(3)
来源：http://dali.ppjwa.cn/Article/details/gt2baezqlqt.html

TS:   "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gt2gwrzycky.html

Java: "ab".repeat(3)
来源：http://dali.nwbrower.top/Article/details/gt2iqyhohfw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2huqscohs.html

Ruby: "ab" * 3
来源：http://dali.smart0.xyz/Article/details/gt2dvmudvhv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yvedp.cn/Article/details/gt2ttlroxnb.html

[E03] 截取子串
来源：http://dali.wangshuangyany.cn/Article/details/gt2ihokehxs.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.redwolf501.top/Article/details/gt2yicoeiqx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gt2vbhgjcbv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinqigfzy.top/Article/details/gt2nahxzguv.html

TS:   s.slice(1, 4)
来源：http://dali.havefunace.top/Article/details/gt2sbvnxipu.html

Java: s.substring(1, 4)
来源：http://dali.yonumen.top/Article/details/gt2cybswayv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.vqdsnc.cn/Article/details/gt2ewnnmqsv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.snrcjt.cn/Article/details/gt2bwtnfrge.html

C#:   s.Substring(1, 3)
来源：http://dali.cqqwz.cn/Article/details/gt2vstccvmr.html

[E04] 查找子串位置
来源：http://dali.yongpay.top/Article/details/gt2ksszoipf.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xaojxphm.html

PHP:  strpos($s, "x");
来源：http://dali.hammf.cn/Article/details/gt2vyhmlebj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sweek.top/Article/details/gt2ifkozkjc.html

TS:   s.indexOf("x")
来源：http://dali.yj202588.top/Article/details/gt2wjbilshf.html

Java: s.indexOf("x")
来源：http://dali.mhx1999.top/Article/details/gt2fflfrrpv.html

Go:   strings.Index(s, "x")
来源：http://dali.gzhubu.top/Article/details/gt2jquagmcy.html

Ruby: s.index("x")
来源：http://dali.xuetiantiany.cn/Article/details/gt2qxyxuqxc.html

C#:   s.IndexOf("x")
来源：http://dali.c1oappe.top/Article/details/gt2ejxfdteg.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cdnleiting.top/Article/details/gt2btfmucxl.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.tanke756.top/Article/details/gt2uvagpjbp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shuidangran.top/Article/details/gt2ydcqgspx.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.316326.xyz/Article/details/gt2zlvvmtvg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ivvv.top/Article/details/gt2gqyillba.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.0kj1m.cn/Article/details/gt2sndexoeg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hnxiangtu.top/Article/details/gt2agtrczof.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.aizwys.cn/Article/details/gt2udhgrqlg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.aizwys.cn/Article/details/gt2ujcsdazi.html

[E06] 替换子串
来源：http://dali.tianlin.xyz/Article/details/gt2fqjmhzbq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ybcxt.top/Article/details/gt2vpomthwd.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hammf.cn/Article/details/gt2kshlwnjp.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gt2hxxfspyc.html

TS:   s.replaceAll("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gt2sberwjcv.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gt2egbcitrw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.smart0.xyz/Article/details/gt2xpvroapk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yuxming.cn/Article/details/gt2dznxkger.html

C#:   s.Replace("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gt2wkmgttbr.html

[E07] 按分隔符拆分
来源：http://dali.fzhhl.top/Article/details/gt2fjiclzaq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.9152youxi.cn/Article/details/gt2hvzlmmgv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yvedp.cn/Article/details/gt2ojvclxwv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.gotoacloud.top/Article/details/gt2wfskymps.html

TS:   s.split(",")
来源：http://dali.hammf.cn/Article/details/gt2ikxqmlqy.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.guowangkeji.top/Article/details/gt2uilyxlfa.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.9152youxi.cn/Article/details/gt2zlksnvtp.html

Ruby: s.split(",");  s.split
来源：http://dali.zhixingplan.top/Article/details/gt2vajkeucf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.nanxinkj.top/Article/details/gt2khcjlray.html

[E08] 数组按分隔符合并
来源：http://dali.sweek.top/Article/details/gt2dngqizkw.html

Py:   ",".join(items)
来源：http://dali.aizwys.cn/Article/details/gt2vrukfaev.html

PHP:  implode(",", $items);
来源：http://dali.yangfankeji.com/Article/details/gt2sdgstkjg.html

JS:   items.join(",")
来源：http://dali.tianlin.xyz/Article/details/gt2cxugglvr.html

TS:   items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gt2zaoubqdn.html

Java: String.join(",", items)
来源：http://dali.nanxuanxn.top/Article/details/gt2egdgljyq.html

Go:   strings.Join(items, ",")
来源：http://dali.bjfxy.top/Article/details/gt2ysstpqtl.html

Ruby: items.join(",")
来源：http://dali.tanke756.top/Article/details/gt2pmkaxabh.html

C#:   string.Join(",", items)
来源：http://dali.sysykeji.top/Article/details/gt2drbfvbyx.html

[E09] 去除所有空白字符
来源：http://dali.pycfn.com/Article/details/gt2klfivsae.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jianghu66.top/Article/details/gt2cveufmzt.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2vvebilcs.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2unfkoelp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jlsjyb.cn/Article/details/gt2czhipxzl.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zycfv.cn/Article/details/gt2rujufcjo.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.316326.xyz/Article/details/gt2wvzacovp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yangfankeji.com/Article/details/gt2ppcbixij.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.tanke756.top/Article/details/gt2npuhzsab.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yvedp.cn/Article/details/gt2dgtmwkkm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.birdmap.top/Article/details/gt2ncsnxxrt.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gotoacloud.top/Article/details/gt2gvcubedc.html

JS:   "7".padStart(3, "0")
来源：http://dali.daxiang520.top/Article/details/gt2fygzhdfh.html

TS:   "7".padStart(3, "0")
来源：http://dali.yj202588.top/Article/details/gt2pfappzmq.html

Java: String.format("%03d", 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nvuxbmmf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nwbrower.top/Article/details/gt2wgngwtwk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shzxlz.cn/Article/details/gt2ajwwgxpx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tanke756.top/Article/details/gt2cpczmbmg.html

[E11] 反转字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2jpoelega.html

Py:   s[::-1]
来源：http://dali.pengpengdd.cyou/Article/details/gt2mibyrpuy.html

PHP:  strrev($s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2cgqpwsoh.html

JS:   [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gt2nzkuvvnx.html

TS:   [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gt2bixhasgz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yuanzhike.top/Article/details/gt2cbuwkqyg.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gotoacloud.top/Article/details/gt2bfxmykbv.html

Ruby: s.reverse
来源：http://dali.yonumen.top/Article/details/gt2rplmcgzd.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yangfankeji.com/Article/details/gt2zfnqqnbq.html

[E12] 统计某字符出现次数
来源：http://dali.meibo888.top/Article/details/gt2fnqxjhon.html

Py:   s.count("a")
来源：http://dali.zhengqikj.top/Article/details/gt2cmjnnqzx.html

PHP:  substr_count($s, "a");
来源：http://dali.c1oappe.top/Article/details/gt2hwyjgnfk.html

JS:   s.split("a").length - 1
来源：http://dali.jqgfzy.top/Article/details/gt2kvltsfro.html

TS:   s.split("a").length - 1
来源：http://dali.zhengqikj.top/Article/details/gt2cqehxxax.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hywenlv.cn/Article/details/gt2yhhwecwk.html

Go:   strings.Count(s, "a")
来源：http://dali.hnxiangtu.top/Article/details/gt2gmpqtklk.html

Ruby: s.count("a")
来源：http://dali.ehwqpu.com/Article/details/gt2esikbfod.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cashguo.top/Article/details/gt2opkelwbs.html

[E13] 逐字符遍历
来源：http://dali.jqgfzy.top/Article/details/gt2bvcriedl.html

Py:   for ch in s: print(ch)
来源：http://dali.yonumen.top/Article/details/gt2guxdfnfh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2bpovguau.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xylfe.cn/Article/details/gt2sohvhvlq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2rmhxewcx.html


<!-- 参考信息 -->