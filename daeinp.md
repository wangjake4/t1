代发 wailian999

TS:   arr.slice(1, 4);
来源：http://dali.yj202588.top/Article/details/gt2jorhpnkl.html

Java: list.subList(1, 4);
来源：http://dali.jlsjyb.cn/Article/details/gt2diquwwcb.html

Go:   arr[1:4]
来源：http://dali.xuanzx.com/Article/details/gt2nvktfmwq.html

Ruby: arr[1, 3]
来源：http://dali.xinyue.icu/Article/details/gt2fdmccblb.html

C#:   list.GetRange(1, 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2avwkajfh.html

[D08] 合并两个数组
来源：http://dali.nwbrower.top/Article/details/gt2lvcgxmhs.html

Py:   a + b;  a.extend(b)
来源：http://dali.zycfv.cn/Article/details/gt2ogoccipp.html

PHP:  array_merge($a, $b);
来源：http://dali.cucudq.cn/Article/details/gt2bpytlhgt.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.quarkkingdee.top/Article/details/gt2uwbjagtx.html

TS:   [...a, ...b];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bixqswue.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yueranfly.top/Article/details/gt2godsuuyw.html

Go:   append(a, b...)
来源：http://dali.iojbl.cn/Article/details/gt2pttcgfkt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.tanke756.top/Article/details/gt2mngfytyn.html

C#:   a.Concat(b).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2cgqsjuxe.html

[D09] 排序（升序）
来源：http://dali.guannengcc.top/Article/details/gt2bvoopwzu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuxming.cn/Article/details/gt2tqadhyua.html

PHP:  sort($arr);
来源：http://dali.chenzaomai.com/Article/details/gt2liudapgn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.wangshuangyany.cn/Article/details/gt2xjrqbwhj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pwtqyhxw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.aibaodan.cn/Article/details/gt2mmhliqpg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.sysykeji.top/Article/details/gt2hxezkusk.html

Ruby: arr.sort
来源：http://dali.316326.xyz/Article/details/gt2mbgoelav.html

C#:   list.Sort();
来源：http://dali.nwbrower.top/Article/details/gt2baehefkr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhongyouzk.top/Article/details/gt2gxtnvcmh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sxryk.cn/Article/details/gt2pubegrqw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jyoumei.cn/Article/details/gt2xixpcyou.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.wangdashe.top/Article/details/gt2tupvkkgj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.havefunace.top/Article/details/gt2ybogwjdb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.andypj.xyz/Article/details/gt2yelovzll.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinqigfzy.top/Article/details/gt2ttmtrels.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jyoumei.cn/Article/details/gt2xggrfqlc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.tanke756.top/Article/details/gt2nuxexyme.html

[D11] 反转数组
来源：http://dali.zhengqikj.top/Article/details/gt2yzqyngug.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yvedp.cn/Article/details/gt2lerflqpl.html

PHP:  array_reverse($arr);
来源：http://dali.jqgfzy.top/Article/details/gt2vwftxqew.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ydzc1.top/Article/details/gt2rdhautqo.html

TS:   [...arr].reverse();
来源：http://dali.gzhubu.top/Article/details/gt2eotxmtrn.html

Java: Collections.reverse(list);
来源：http://dali.nwbrower.top/Article/details/gt2eogmylhk.html

Go:   slices.Reverse(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2uxfoelaj.html

Ruby: arr.reverse
来源：http://dali.ivvv.top/Article/details/gt2eeotqwjo.html

C#:   list.Reverse();
来源：http://dali.zhoulong.xyz/Article/details/gt2tkvhprpx.html

[D12] 查找元素下标
来源：http://dali.hywenlv.cn/Article/details/gt2cdbdudaj.html

Py:   arr.index(x);  x in arr
来源：http://dali.cucudq.cn/Article/details/gt2gyueodcm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.c1oappe.top/Article/details/gt2yuafrqwz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yanxiufei.cn/Article/details/gt2aiqtsqyn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxinkj.top/Article/details/gt2ajfntwtc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shangyingyoupin.top/Article/details/gt2vuajxnsl.html

Go:   slices.Index(arr, x)
来源：http://dali.zycfv.cn/Article/details/gt2xniicayb.html

Ruby: arr.index(x)
来源：http://dali.sxryk.cn/Article/details/gt2sbxkalsa.html

C#:   list.IndexOf(x);
来源：http://dali.zdqjudy.top/Article/details/gt2jpmtqhdn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ahcfmwvr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ydzc1.top/Article/details/gt2fkwplrnp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yongpay.top/Article/details/gt2neurbeko.html

JS:   arr.filter(x => x > 3)
来源：http://dali.c1oappe.top/Article/details/gt2tybkydiq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.pycfn.com/Article/details/gt2utucxiln.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.wangdashe.top/Article/details/gt2jdyomado.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aqntcrgx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xinyue.icu/Article/details/gt2dcjxilyk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.birdmap.top/Article/details/gt2lvwdrekc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yanxiufei.cn/Article/details/gt2tosvfvqs.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kwopbjfu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.daxiang520.top/Article/details/gt2nedooqvm.html

JS:   arr.map(x => x * 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2ulqixpta.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2ionodvxt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gaohongyu789.top/Article/details/gt2crzfebja.html

Go:   // 手写循环
来源：http://dali.sweek.top/Article/details/gt2hmgyblce.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hnqzz.top/Article/details/gt2gagcgiln.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.daxiang520.top/Article/details/gt2dkauipxc.html

[D15] 去重
来源：http://dali.cashguo.top/Article/details/gt2jluazkjx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.meibo888.top/Article/details/gt2tpqpnvcy.html

PHP:  array_unique($arr);
来源：http://dali.birdmap.top/Article/details/gt2okndeuez.html

JS:   [...new Set(arr)]
来源：http://dali.zhixingplan.top/Article/details/gt2udvqttkh.html

TS:   [...new Set(arr)]
来源：http://dali.tianlin.xyz/Article/details/gt2bvugrncy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sxryk.cn/Article/details/gt2voecqmuf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.wangshuangyany.cn/Article/details/gt2yxyaprjo.html

Ruby: arr.uniq
来源：http://dali.bjfxy.top/Article/details/gt2bddqkypt.html

C#:   list.Distinct().ToList()
来源：http://dali.svipenyu.cn/Article/details/gt2nozmncsf.html

[D16] 求和与平均值
来源：http://dali.jqgufenzy.top/Article/details/gt2qshymsny.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.wangdashe.top/Article/details/gt2nivbhaxx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.316326.xyz/Article/details/gt2mlpnnpcp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ybcxt.top/Article/details/gt2naxmzeec.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guowangkeji.top/Article/details/gt2qkbyjeos.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhongyouzk.top/Article/details/gt2cdnlirie.html

Go:   // 手写循环累加
来源：http://dali.ppjwa.cn/Article/details/gt2lyoybeul.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.wangdashe.top/Article/details/gt2topsgmzp.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhiwuduotai.top/Article/details/gt2hymtnjwz.html

[D17] 最大值与最小值
来源：http://dali.yvedp.cn/Article/details/gt2xmpgzaco.html

Py:   max(arr);  min(arr)
来源：http://dali.haohaochexian.top/Article/details/gt2nxljedda.html

PHP:  max($arr);  min($arr);
来源：http://dali.iojbl.cn/Article/details/gt2dlrzajst.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2znrnwutb.html

TS:   Math.max(...arr);
来源：http://dali.ppjwa.cn/Article/details/gt2vlctxkdw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.redwolf501.top/Article/details/gt2wlxavupm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zocvazor.html

Ruby: arr.max;  arr.min
来源：http://dali.shanyushiyangtech.top/Article/details/gt2agfevqdw.html

C#:   list.Max();  list.Min()
来源：http://dali.fzhhl.top/Article/details/gt2pbnttbsz.html

[D18] 扁平化嵌套数组
来源：http://dali.jlsjyb.cn/Article/details/gt2gwlakffd.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xylfe.cn/Article/details/gt2kuekaecn.html

PHP:  array_merge(...$nested);
来源：http://dali.tanke756.top/Article/details/gt2clghgnsp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yangfankeji.com/Article/details/gt2qswnqpxg.html

TS:   nested.flat();
来源：http://dali.chenjidiqi.icu/Article/details/gt2atizokks.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2bkwgdshi.html

Go:   // 手写双层循环
来源：http://dali.c1oappe.top/Article/details/gt2szklsxql.html

Ruby: nested.flatten
来源：http://dali.yanxiufei.cn/Article/details/gt2aerfrvig.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.tian-w.cn/Article/details/gt2eebuvfmk.html

[D19] 按字段分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lqtrboqv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.aizwys.cn/Article/details/gt2rakzpdaa.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ybcxt.top/Article/details/gt2craticza.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yvedp.cn/Article/details/gt2jopnxorg.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.vqdsnc.cn/Article/details/gt2ihhiyjja.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yvedp.cn/Article/details/gt2nikwwezv.html

Go:   // 手写 map[string][]T
来源：http://dali.svipenyu.cn/Article/details/gt2uiisynvj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yj20258888.top/Article/details/gt2oucscpbv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.316326.xyz/Article/details/gt2kcedmmqb.html

[D20] 统计每个元素出现次数
来源：http://dali.xuetiantiany.cn/Article/details/gt2zeqluvjy.html

Py:   Counter(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2miovmcwv.html

PHP:  array_count_values($arr);
来源：http://dali.cucudq.cn/Article/details/gt2wjvisprs.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgfzy.top/Article/details/gt2fdiywdcg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yongpay.top/Article/details/gt2ultyjjzj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shangyingyoupin.top/Article/details/gt2irzttemc.html

Go:   // 手写 map[T]int
来源：http://dali.havefunace.top/Article/details/gt2ywhmctzu.html

Ruby: arr.tally
来源：http://dali.smart0.xyz/Article/details/gt2lzvmygud.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.9152youxi.cn/Article/details/gt2ysbpvxta.html

[D21] 判断是否包含某元素
来源：http://dali.yvedp.cn/Article/details/gt2entpswlf.html

Py:   x in arr
来源：http://dali.cashguo.top/Article/details/gt2itzykihu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ajgaxkno.html

JS:   arr.includes(x)
来源：http://dali.mhx1999.top/Article/details/gt2rfotsfnf.html

TS:   arr.includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jszakdee.html

Java: list.contains(x)
来源：http://dali.gzhubu.top/Article/details/gt2rnipvtzl.html

Go:   slices.Contains(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gt2oceidjlo.html

Ruby: arr.include?(x)
来源：http://dali.cqqwz.cn/Article/details/gt2vfbytoym.html

C#:   list.Contains(x)
来源：http://dali.guowangkeji.top/Article/details/gt2dsaetlei.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinqigfzy.top/Article/details/gt2ejfbmxmw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2uokjerdr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.fzhhl.top/Article/details/gt2hnnywpnw.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sxryk.cn/Article/details/gt2ilpyhbvj.html

TS:   [...arr];
来源：http://dali.chenjidiqi.icu/Article/details/gt2qyypzqda.html

Java: new ArrayList<>(list);
来源：http://dali.hfpthk.cn/Article/details/gt2knkdmafe.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xylfe.cn/Article/details/gt2uvmzogbk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shuidangran.top/Article/details/gt2dyonalaa.html

C#:   new List<int>(list);
来源：http://dali.nanxuanxn.top/Article/details/gt2zrupgckz.html

[D23] reduce 累积计算
来源：http://dali.hammf.cn/Article/details/gt2tflbesal.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.meibo888.top/Article/details/gt2noboqmwg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zycfv.cn/Article/details/gt2pfsberql.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sxryk.cn/Article/details/gt2zhhyzwhj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuxming.cn/Article/details/gt2hcnhupdn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.9152youxi.cn/Article/details/gt2lkzgqugw.html

Go:   // 手写循环
来源：http://dali.haohaochexian.top/Article/details/gt2xtmokzev.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.meibo888.top/Article/details/gt2igntmrvj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.iojbl.cn/Article/details/gt2egtxcuaj.html

[D24] 字典 / Map 基本操作
来源：http://dali.xziqi.cn/Article/details/gt2oqngktxi.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.fzhhl.top/Article/details/gt2yfghetqr.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.havefunace.top/Article/details/gt2gbzwhkui.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ppjwa.cn/Article/details/gt2ivxkmmmx.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gt2gvnskdkl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.dashuyun.cn/Article/details/gt2lrvtvuyg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.daria6918.cn/Article/details/gt2jwupeaao.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yanxiufei.cn/Article/details/gt2ekbodheq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yvedp.cn/Article/details/gt2bcgcyvcw.html

[D25] Set 集合去重与交并差
来源：http://dali.daxiang520.top/Article/details/gt2kpatbcmo.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.bjfxy.top/Article/details/gt2xhxdtdrm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hnxiangtu.top/Article/details/gt2fnheopek.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hnqzz.top/Article/details/gt2kakiqhop.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dvifigqr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jiagoushi.top/Article/details/gt2vngwskec.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gotoacloud.top/Article/details/gt2fqbkvooh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yueranfly.top/Article/details/gt2wktynhfa.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zdqjudy.top/Article/details/gt2vtezkfqo.html

[D26] 数组转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2ondovndh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.bjfxy.top/Article/details/gt2nsnbdagb.html

PHP:  implode(", ", $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tnbgfqmm.html

JS:   arr.join(", ")
来源：http://dali.redwolf501.top/Article/details/gt2cqtoouvv.html

TS:   arr.join(", ")
来源：http://dali.ybcxt.top/Article/details/gt2pzjclrvr.html

Java: String.join(", ", list)
来源：http://dali.jiagoushi.top/Article/details/gt2nihqbfxi.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yuanzhike.top/Article/details/gt2uhtgvcfa.html

Ruby: arr.join(", ")
来源：http://dali.jlsjyb.cn/Article/details/gt2cpytqeco.html

C#:   string.Join(", ", list)
来源：http://dali.cqqwz.cn/Article/details/gt2xwsezdrt.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2djibclbe.html

E. 字符串处理
来源：http://dali.jlsjyb.cn/Article/details/gt2mlriejcb.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2ivmnzlag.html

[E01] 拼接字符串
来源：http://dali.smart0.xyz/Article/details/gt2nggrxuws.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.316326.xyz/Article/details/gt2slqqevjo.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.gzhubu.top/Article/details/gt2nmkvdzie.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nwbrower.top/Article/details/gt2spgvegkd.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhiwuduotai.top/Article/details/gt2nrebbpbw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fdiwfqyz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sntrfjcj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.birdmap.top/Article/details/gt2ypsoqmag.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xziqi.cn/Article/details/gt2rmxqnelk.html

[E02] 重复字符串
来源：http://dali.ybcxt.top/Article/details/gt2jcviagrv.html

Py:   "ab" * 3
来源：http://dali.hongshengwenyu.top/Article/details/gt2hziifujv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hysaishi.cn/Article/details/gt2qanzsclx.html

JS:   "ab".repeat(3)
来源：http://dali.cheryme.top/Article/details/gt2ymyrhnri.html

TS:   "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gt2bkrybrwl.html

Java: "ab".repeat(3)
来源：http://dali.sweek.top/Article/details/gt2nqzjdykv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.316326.xyz/Article/details/gt2sblfqepr.html

Ruby: "ab" * 3
来源：http://dali.kuanghao11.cn/Article/details/gt2hiaxpuju.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sxryk.cn/Article/details/gt2mbvpvhjv.html

[E03] 截取子串
来源：http://dali.xuanzx.com/Article/details/gt2qvbjlgwb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jyoumei.cn/Article/details/gt2yqyiwckm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gt2qsdhvxuu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gt2bvktpjzy.html

TS:   s.slice(1, 4)
来源：http://dali.zycfv.cn/Article/details/gt2wichdeor.html

Java: s.substring(1, 4)
来源：http://dali.ivvv.top/Article/details/gt2addbjigw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.316326.xyz/Article/details/gt2unudsqxs.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bjzdoskg.html

C#:   s.Substring(1, 3)
来源：http://dali.guannengcc.top/Article/details/gt2rzpyixgj.html

[E04] 查找子串位置
来源：http://dali.hongshengwenyu.top/Article/details/gt2iomynoep.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinqigfzy.top/Article/details/gt2vhxktpqf.html

PHP:  strpos($s, "x");
来源：http://dali.chenzaomai.com/Article/details/gt2kkupuvux.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yongpay.top/Article/details/gt2rnaluxya.html

TS:   s.indexOf("x")
来源：http://dali.chenlongwang.top/Article/details/gt2pdnmdomh.html

Java: s.indexOf("x")
来源：http://dali.redwolf501.top/Article/details/gt2cspcuoxu.html

Go:   strings.Index(s, "x")
来源：http://dali.svipenyu.cn/Article/details/gt2ttimvluq.html

Ruby: s.index("x")
来源：http://dali.hywenlv.cn/Article/details/gt2haqkzsxt.html

C#:   s.IndexOf("x")
来源：http://dali.ybcxt.top/Article/details/gt2lfvvnmnh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yqwllbnn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gt2xjiadlra.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.vqdsnc.cn/Article/details/gt2avgrtnan.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gt2circpauh.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.chenlongwang.top/Article/details/gt2cvtxtlrw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hywenlv.cn/Article/details/gt2zxxatnpq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yj20258.top/Article/details/gt2ydcriyun.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.9152youxi.cn/Article/details/gt2htmbywrj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yj202588.top/Article/details/gt2ohkzjqtp.html

[E06] 替换子串
来源：http://dali.shangyingyoupin.top/Article/details/gt2wqsoshze.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2pplzimpd.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.dashuyun.cn/Article/details/gt2flejtwsm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gt2oujvacrc.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gt2ekassihs.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gt2ribcdacm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.guannengcc.top/Article/details/gt2jwlwbkhv.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gt2qistmmti.html

C#:   s.Replace("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gt2gyylthik.html

[E07] 按分隔符拆分
来源：http://dali.xylfe.cn/Article/details/gt2ufdglgzv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cucudq.cn/Article/details/gt2ouetuovc.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gt2dnyzzdlx.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.gotoacloud.top/Article/details/gt2xqsqpdpe.html

TS:   s.split(",")
来源：http://dali.haohaochexian.top/Article/details/gt2zxdumsuz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.fengsongda.top/Article/details/gt2vzcqmolc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ppjwa.cn/Article/details/gt2axbvzidp.html

Ruby: s.split(",");  s.split
来源：http://dali.zhongyouzk.top/Article/details/gt2buzonnxn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jqgfzy.top/Article/details/gt2apylvrur.html

[E08] 数组按分隔符合并
来源：http://dali.fzhhl.top/Article/details/gt2ohulbxpj.html

Py:   ",".join(items)
来源：http://dali.redwolf501.top/Article/details/gt2fhugrpjf.html

PHP:  implode(",", $items);
来源：http://dali.zycfv.cn/Article/details/gt2eowkwkgs.html

JS:   items.join(",")
来源：http://dali.yanxiufei.cn/Article/details/gt2ohwqipfh.html

TS:   items.join(",")
来源：http://dali.cashguo.top/Article/details/gt2zulzcidr.html

Java: String.join(",", items)
来源：http://dali.zycfv.cn/Article/details/gt2dboxqztd.html

Go:   strings.Join(items, ",")
来源：http://dali.zhiwuduotai.top/Article/details/gt2iddbkkry.html

Ruby: items.join(",")
来源：http://dali.yj202588.top/Article/details/gt2pdugvkao.html

C#:   string.Join(",", items)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ojcyqekc.html

[E09] 去除所有空白字符
来源：http://dali.nanxinkj.top/Article/details/gt2kffgxdud.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yvedp.cn/Article/details/gt2kmvrsgjn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yonumen.top/Article/details/gt2fmunzurr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gogol.net.cn/Article/details/gt2dxweeclp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.wangdashe.top/Article/details/gt2ysclupcs.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj202588.top/Article/details/gt2bxfufphl.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ydzc1.top/Article/details/gt2kwjlbuqu.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.guannengcc.top/Article/details/gt2zrschrcp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.bjfxy.top/Article/details/gt2ujehcmud.html

[E10] 左侧补零 / 定长填充
来源：http://dali.smart0.xyz/Article/details/gt2gokpsxze.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yongpay.top/Article/details/gt2womoxdje.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.nwbrower.top/Article/details/gt2wnjedcsq.html

JS:   "7".padStart(3, "0")
来源：http://dali.yuxming.cn/Article/details/gt2mgywcaeu.html

TS:   "7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gt2ofannrel.html

Java: String.format("%03d", 7)
来源：http://dali.havefunace.top/Article/details/gt2cvshrcaj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jqgufenzy.top/Article/details/gt2rsckugwe.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kwizorgs.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.dianchejie.cn/Article/details/gt2lptopbmh.html

[E11] 反转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2whlkqpxo.html

Py:   s[::-1]
来源：http://dali.hywenlv.cn/Article/details/gt2rfczfkra.html

PHP:  strrev($s);
来源：http://dali.sxryk.cn/Article/details/gt2zxvblrbn.html

JS:   [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gt2oxrksbwd.html

TS:   [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gt2qbgavrvt.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.bjfxy.top/Article/details/gt2xpfsnguv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.aibaodan.cn/Article/details/gt2fnqlctqs.html

Ruby: s.reverse
来源：http://dali.c1oappe.top/Article/details/gt2uxtiewlf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhoulong.xyz/Article/details/gt2gefztsbf.html

[E12] 统计某字符出现次数
来源：http://dali.hysaishi.cn/Article/details/gt2ctjcxxzl.html

Py:   s.count("a")
来源：http://dali.yj202588.top/Article/details/gt2joonzhie.html

PHP:  substr_count($s, "a");
来源：http://dali.hysaishi.cn/Article/details/gt2fcxubcie.html

JS:   s.split("a").length - 1
来源：http://dali.c1oappe.top/Article/details/gt2hjcdnnvc.html

TS:   s.split("a").length - 1
来源：http://dali.zdqjudy.top/Article/details/gt2frapcohr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ugbdnscn.html

Go:   strings.Count(s, "a")
来源：http://dali.jlsjyb.cn/Article/details/gt2jfkzwwmb.html

Ruby: s.count("a")
来源：http://dali.ppjwa.cn/Article/details/gt2ebbtckbl.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj20258.top/Article/details/gt2srwwexvz.html

[E13] 逐字符遍历
来源：http://dali.iojbl.cn/Article/details/gt2gednygmd.html

Py:   for ch in s: print(ch)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ugooqqwh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.c1oappe.top/Article/details/gt2regsdmde.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ivvv.top/Article/details/gt2lbgemcyv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jianghu66.top/Article/details/gt2bzdntycy.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ppjwa.cn/Article/details/gt2cszjjuuw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yuxming.cn/Article/details/gt2ilybsvlp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2trlwbumb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sweek.top/Article/details/gt2erfqsghm.html

[E14] URL 编码与 Base64
来源：http://dali.yuxming.cn/Article/details/gt2fsnztzii.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cheryme.top/Article/details/gt2onpkxlhb.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.snrcjt.cn/Article/details/gt2slgilmue.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yonumen.top/Article/details/gt2fxbgehye.html


<!-- 参考信息 -->