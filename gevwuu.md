代发 wailian999

Java: list.size();
来源：http://dali.yangfankeji.com/Article/details/gt2vldlozzr.html

Go:   len(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2spiacjax.html

Ruby: arr.length; arr.size
来源：http://dali.kuanghao11.cn/Article/details/gt2pmqntdau.html

C#:   list.Count;
来源：http://dali.guannengcc.top/Article/details/gt2ccpiguiv.html

[D07] 切片 / 取子数组
来源：http://dali.hongshengwenyu.top/Article/details/gt2eeotssbk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.meibo888.top/Article/details/gt2wrdqnycf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hongshengwenyu.top/Article/details/gt2cpkxfkcu.html

JS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xgdrkegx.html

TS:   arr.slice(1, 4);
来源：http://dali.sxryk.cn/Article/details/gt2biyrfoyw.html

Java: list.subList(1, 4);
来源：http://dali.ppjwa.cn/Article/details/gt2xrzlbsom.html

Go:   arr[1:4]
来源：http://dali.sweek.top/Article/details/gt2uuaoqjwh.html

Ruby: arr[1, 3]
来源：http://dali.hysaishi.cn/Article/details/gt2ltutkdpl.html

C#:   list.GetRange(1, 3);
来源：http://dali.sxryk.cn/Article/details/gt2bwijtnem.html

[D08] 合并两个数组
来源：http://dali.tanke756.top/Article/details/gt2usdbtekx.html

Py:   a + b;  a.extend(b)
来源：http://dali.tanke756.top/Article/details/gt2qkmnyqbi.html

PHP:  array_merge($a, $b);
来源：http://dali.jqgfzy.top/Article/details/gt2rmkmecgi.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.fzhhl.top/Article/details/gt2phuuwdls.html

TS:   [...a, ...b];
来源：http://dali.bjfxy.top/Article/details/gt2xhulvbrn.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zdqjudy.top/Article/details/gt2tsmzdkdf.html

Go:   append(a, b...)
来源：http://dali.nwbrower.top/Article/details/gt2ghektyba.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mnrpedqa.html

C#:   a.Concat(b).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2cwkjweqi.html

[D09] 排序（升序）
来源：http://dali.hnxiangtu.top/Article/details/gt2hxvdoghs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.iojbl.cn/Article/details/gt2qzjumvyc.html

PHP:  sort($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2kcaifnoh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.pengpengdd.cyou/Article/details/gt2nqmxssky.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.tian-w.cn/Article/details/gt2dxcpwxac.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.tian-w.cn/Article/details/gt2awzlwjbl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.meibo888.top/Article/details/gt2gwwtnqbb.html

Ruby: arr.sort
来源：http://dali.nwbrower.top/Article/details/gt2sguaotnx.html

C#:   list.Sort();
来源：http://dali.yonumen.top/Article/details/gt2iigmmrwa.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hongshengwenyu.top/Article/details/gt2maerxnxl.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.andypj.xyz/Article/details/gt2mqosaycv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hnqzz.top/Article/details/gt2xvtcqwrd.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xziqi.cn/Article/details/gt2fvjyaobn.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhiwuduotai.top/Article/details/gt2akpcgqld.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shuidangran.top/Article/details/gt2ghhymekz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.tian-w.cn/Article/details/gt2vwvtevno.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qezmtpbc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nomcybpb.html

[D11] 反转数组
来源：http://dali.sxryk.cn/Article/details/gt2rnhixokt.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.gogol.net.cn/Article/details/gt2tnsbgwfk.html

PHP:  array_reverse($arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2usgarayn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xuanzx.com/Article/details/gt2ecgpguqh.html

TS:   [...arr].reverse();
来源：http://dali.aibaodan.cn/Article/details/gt2wkjlbmuh.html

Java: Collections.reverse(list);
来源：http://dali.nanxuanxn.top/Article/details/gt2mahhliyc.html

Go:   slices.Reverse(arr)
来源：http://dali.yueranfly.top/Article/details/gt2boizsrnu.html

Ruby: arr.reverse
来源：http://dali.nwbrower.top/Article/details/gt2qvoaksxa.html

C#:   list.Reverse();
来源：http://dali.yj202588.top/Article/details/gt2acogqooi.html

[D12] 查找元素下标
来源：http://dali.yvedp.cn/Article/details/gt2kcgkjgtm.html

Py:   arr.index(x);  x in arr
来源：http://dali.cashguo.top/Article/details/gt2roqubyty.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.nwbrower.top/Article/details/gt2glrxqfgn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sweek.top/Article/details/gt2juqzdunb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.mhx1999.top/Article/details/gt2bhgvqrgm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sweek.top/Article/details/gt2dpsyhrdr.html

Go:   slices.Index(arr, x)
来源：http://dali.havefunace.top/Article/details/gt2qrscizvv.html

Ruby: arr.index(x)
来源：http://dali.dashuyun.cn/Article/details/gt2xdajqtjs.html

C#:   list.IndexOf(x);
来源：http://dali.sxryk.cn/Article/details/gt2mfdjopuv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zycfv.cn/Article/details/gt2qxietilm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fojqqjoe.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.mhx1999.top/Article/details/gt2wnmponog.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gogol.net.cn/Article/details/gt2rmfejuvh.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ybcxt.top/Article/details/gt2gdypktjx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yj20258888.top/Article/details/gt2hlmklfaw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.quarkkingdee.top/Article/details/gt2rjriidvg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.dianchejie.cn/Article/details/gt2cotykycr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.sufxvd.cn/Article/details/gt2fzyytgie.html

[D14] 映射转换（每个元素变形）
来源：http://dali.pycfn.com/Article/details/gt2cnnuunhb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.tanke756.top/Article/details/gt2sbuxdlbr.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinqigufen.top/Article/details/gt2plezipem.html

JS:   arr.map(x => x * 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gsxunjwc.html

TS:   arr.map(x => x * 2)
来源：http://dali.gogol.net.cn/Article/details/gt2dsypqziy.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.nwbrower.top/Article/details/gt2myowcjwv.html

Go:   // 手写循环
来源：http://dali.xuanzx.com/Article/details/gt2pxclwdrm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gt2wibjkmwq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2oajoczkw.html

[D15] 去重
来源：http://dali.9152youxi.cn/Article/details/gt2hpuzgtsi.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jianghu66.top/Article/details/gt2rrpztcsy.html

PHP:  array_unique($arr);
来源：http://dali.nanxinkj.top/Article/details/gt2rrditrdi.html

JS:   [...new Set(arr)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ohoertjv.html

TS:   [...new Set(arr)]
来源：http://dali.yangfankeji.com/Article/details/gt2nykaaeuk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.tian-w.cn/Article/details/gt2dkrnirbh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yangfankeji.com/Article/details/gt2lkvetdoq.html

Ruby: arr.uniq
来源：http://dali.jianghu66.top/Article/details/gt2wmlggfvc.html

C#:   list.Distinct().ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wctnmzdz.html

[D16] 求和与平均值
来源：http://dali.fzhhl.top/Article/details/gt2lipzimlm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xziqi.cn/Article/details/gt2kbqswgib.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gzhubu.top/Article/details/gt2drvofsgu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.haohaochexian.top/Article/details/gt2qqlvpkqg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnxiangtu.top/Article/details/gt2gowcgaqf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cheryme.top/Article/details/gt2kfrxwzbh.html

Go:   // 手写循环累加
来源：http://dali.sufxvd.cn/Article/details/gt2humogvpb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qyepmhjk.html

C#:   list.Sum();  list.Average()
来源：http://dali.redwolf501.top/Article/details/gt2ducdcuxg.html

[D17] 最大值与最小值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2flykikuv.html

Py:   max(arr);  min(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2jbaufwgu.html

PHP:  max($arr);  min($arr);
来源：http://dali.jiagoushi.top/Article/details/gt2fgzilopl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ybcxt.top/Article/details/gt2izuarsvh.html

TS:   Math.max(...arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2ewgpqsco.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.svipenyu.cn/Article/details/gt2enxlxmup.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tuevxrcl.html

Ruby: arr.max;  arr.min
来源：http://dali.fzhhl.top/Article/details/gt2bbavmtit.html

C#:   list.Max();  list.Min()
来源：http://dali.hywenlv.cn/Article/details/gt2aytlrhwo.html

[D18] 扁平化嵌套数组
来源：http://dali.hnqzz.top/Article/details/gt2nvtyjssp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gjzmbxzr.html

PHP:  array_merge(...$nested);
来源：http://dali.gogol.net.cn/Article/details/gt2kdpvwinz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gogol.net.cn/Article/details/gt2yrkinjkq.html

TS:   nested.flat();
来源：http://dali.9152youxi.cn/Article/details/gt2hzdqhsah.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.mhx1999.top/Article/details/gt2fynmgizg.html

Go:   // 手写双层循环
来源：http://dali.yj20258888.top/Article/details/gt2wiinlwrt.html

Ruby: nested.flatten
来源：http://dali.meibo888.top/Article/details/gt2fothsvia.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.fengsongda.top/Article/details/gt2uazkqhof.html

[D19] 按字段分组
来源：http://dali.chenzaomai.com/Article/details/gt2kjsnphso.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cucudq.cn/Article/details/gt2qblzxgpp.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhiwuduotai.top/Article/details/gt2tvjdhgol.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.snrcjt.cn/Article/details/gt2irfvllqy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shzxlz.cn/Article/details/gt2cyuxevvs.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pwrwmbnk.html

Go:   // 手写 map[string][]T
来源：http://dali.cucudq.cn/Article/details/gt2otcpladx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.guannengcc.top/Article/details/gt2rrmedtmc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhiwuduotai.top/Article/details/gt2rrexqgxe.html

[D20] 统计每个元素出现次数
来源：http://dali.9152youxi.cn/Article/details/gt2fmydxhpo.html

Py:   Counter(arr)
来源：http://dali.zdqjudy.top/Article/details/gt2xvmvptjl.html

PHP:  array_count_values($arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2drkydjwq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258888.top/Article/details/gt2jbmektqy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gogol.net.cn/Article/details/gt2tlqdtvee.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shuidangran.top/Article/details/gt2pxoiklwf.html

Go:   // 手写 map[T]int
来源：http://dali.cashguo.top/Article/details/gt2ikpkseco.html

Ruby: arr.tally
来源：http://dali.aizwys.cn/Article/details/gt2zgaozwdj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhongyouzk.top/Article/details/gt2ducxaoxp.html

[D21] 判断是否包含某元素
来源：http://dali.yvedp.cn/Article/details/gt2bcolfbit.html

Py:   x in arr
来源：http://dali.xylfe.cn/Article/details/gt2gpswkffk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.guannengcc.top/Article/details/gt2dpferiqe.html

JS:   arr.includes(x)
来源：http://dali.c1oappe.top/Article/details/gt2txkdcsde.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgpaxxgz.html

Java: list.contains(x)
来源：http://dali.xziqi.cn/Article/details/gt2gonypmjm.html

Go:   slices.Contains(arr, x)
来源：http://dali.daxiang520.top/Article/details/gt2xbacerlu.html

Ruby: arr.include?(x)
来源：http://dali.snrcjt.cn/Article/details/gt2qebtthyq.html

C#:   list.Contains(x)
来源：http://dali.zhixingplan.top/Article/details/gt2imzxwaci.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xinyue.icu/Article/details/gt2fvgagrrc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jwcxrbfd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.iojbl.cn/Article/details/gt2xczbbojl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2pmsscikl.html

TS:   [...arr];
来源：http://dali.ybcxt.top/Article/details/gt2jakuibpf.html

Java: new ArrayList<>(list);
来源：http://dali.zdqjudy.top/Article/details/gt2ocnyeqol.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yuanzhike.top/Article/details/gt2zqudvnwx.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sweek.top/Article/details/gt2fnewoena.html

C#:   new List<int>(list);
来源：http://dali.tianlin.xyz/Article/details/gt2tljvbyqk.html

[D23] reduce 累积计算
来源：http://dali.nanxuanxn.top/Article/details/gt2znzcwthi.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sysykeji.top/Article/details/gt2kojovshp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2skehmmwb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gt2nsdtpowe.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dkdptbko.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.daria6918.cn/Article/details/gt2wkkbcjra.html

Go:   // 手写循环
来源：http://dali.yj20258888.top/Article/details/gt2efgzpkjk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ijznjhoj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.andypj.xyz/Article/details/gt2bfsurjbs.html

[D24] 字典 / Map 基本操作
来源：http://dali.xziqi.cn/Article/details/gt2ytzabjly.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hnqzz.top/Article/details/gt2bdrmpgsb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.quarkkingdee.top/Article/details/gt2fjfkioyr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xylfe.cn/Article/details/gt2oojrvafo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.daxiang520.top/Article/details/gt2bixnumcw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.0kj1m.cn/Article/details/gt2jljksluo.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sysykeji.top/Article/details/gt2swwkkdgp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.aibaodan.cn/Article/details/gt2qotazvuh.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenzaomai.com/Article/details/gt2cvphyozs.html

[D25] Set 集合去重与交并差
来源：http://dali.jqgfzy.top/Article/details/gt2hhglgehf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.chenzaomai.com/Article/details/gt2dbfopaxd.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zdqjudy.top/Article/details/gt2kuyaxnnk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gotoacloud.top/Article/details/gt2atpgmtjg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.svipenyu.cn/Article/details/gt2xuaegdsl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ydzc1.top/Article/details/gt2ejhnrsyo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.pengpengdd.cyou/Article/details/gt2bvgegaiw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ppjwa.cn/Article/details/gt2qgquowvl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shuidangran.top/Article/details/gt2dynycqnp.html

[D26] 数组转字符串
来源：http://dali.cucudq.cn/Article/details/gt2ocwvjlcy.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhiwuduotai.top/Article/details/gt2hwxyaxxv.html

PHP:  implode(", ", $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2knrpcliq.html

JS:   arr.join(", ")
来源：http://dali.dianchejie.cn/Article/details/gt2qbukyohj.html

TS:   arr.join(", ")
来源：http://dali.andypj.xyz/Article/details/gt2plhsutuv.html

Java: String.join(", ", list)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mnbgzdre.html

Go:   strings.Join(strs, ", ")
来源：http://dali.meibo888.top/Article/details/gt2qusklttb.html

Ruby: arr.join(", ")
来源：http://dali.daria6918.cn/Article/details/gt2yvxrmuko.html

C#:   string.Join(", ", list)
来源：http://dali.zhixingplan.top/Article/details/gt2mqjsjudr.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2nlsfprcz.html

E. 字符串处理
来源：http://dali.sysykeji.top/Article/details/gt2qigdsfpe.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2quvxnrbz.html

[E01] 拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gt2ngmdkefp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.dianchejie.cn/Article/details/gt2emtogcsd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sxryk.cn/Article/details/gt2wdprrgfq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dashuyun.cn/Article/details/gt2mdwjdycn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.0kj1m.cn/Article/details/gt2orggitma.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jqgufenzy.top/Article/details/gt2jnzdatul.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhoulong.xyz/Article/details/gt2pdaymgoq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shanyushiyangtech.top/Article/details/gt2miqauqgw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gt2kxnjqvze.html

[E02] 重复字符串
来源：http://dali.zhengqikj.top/Article/details/gt2nyoiiijz.html

Py:   "ab" * 3
来源：http://dali.dashuyun.cn/Article/details/gt2nusyjbwp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenlongwang.top/Article/details/gt2tfyrigdk.html

JS:   "ab".repeat(3)
来源：http://dali.9152youxi.cn/Article/details/gt2cribqzbk.html

TS:   "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gt2jpgfpjyj.html

Java: "ab".repeat(3)
来源：http://dali.snrcjt.cn/Article/details/gt2bldvcolg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yangfankeji.com/Article/details/gt2dtdwgctb.html

Ruby: "ab" * 3
来源：http://dali.jianghu66.top/Article/details/gt2vgfjatnq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhongyouzk.top/Article/details/gt2spliorvq.html

[E03] 截取子串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zaivspog.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yj202588.top/Article/details/gt2dlgmcyjw.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gt2axflayrg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cucudq.cn/Article/details/gt2oihhjtnq.html

TS:   s.slice(1, 4)
来源：http://dali.jlsjyb.cn/Article/details/gt2iassezrt.html

Java: s.substring(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gt2pzaejlqs.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenjidiqi.icu/Article/details/gt2dgqitiwv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sxryk.cn/Article/details/gt2vfxzvrsi.html

C#:   s.Substring(1, 3)
来源：http://dali.zhixingplan.top/Article/details/gt2fwzvpocu.html

[E04] 查找子串位置
来源：http://dali.hywenlv.cn/Article/details/gt2wiesrimm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xziqi.cn/Article/details/gt2lxrrlsfl.html

PHP:  strpos($s, "x");
来源：http://dali.gaohongyu789.top/Article/details/gt2gbaupwbj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zdqjudy.top/Article/details/gt2ofesbrps.html

TS:   s.indexOf("x")
来源：http://dali.hongshengwenyu.top/Article/details/gt2gahodjyy.html

Java: s.indexOf("x")
来源：http://dali.bjfxy.top/Article/details/gt2jaepraji.html

Go:   strings.Index(s, "x")
来源：http://dali.ybcxt.top/Article/details/gt2nroaxytz.html

Ruby: s.index("x")
来源：http://dali.havefunace.top/Article/details/gt2xkcecqvs.html

C#:   s.IndexOf("x")
来源：http://dali.ybcxt.top/Article/details/gt2nxzyimzo.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gzhubu.top/Article/details/gt2ghhucnss.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xinyue.icu/Article/details/gt2dovpsirt.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2konfgovu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgfzy.top/Article/details/gt2aarbaiwl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.nanxuanxn.top/Article/details/gt2dwgkujjd.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ppjwa.cn/Article/details/gt2ejftucfg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ivvv.top/Article/details/gt2nsdzyqdu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yangfankeji.com/Article/details/gt2lkqidsat.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shuidangran.top/Article/details/gt2emriwabf.html

[E06] 替换子串
来源：http://dali.jinqigufen.top/Article/details/gt2geriaeho.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cashguo.top/Article/details/gt2qujnygvx.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhengqikj.top/Article/details/gt2qgyirxnf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gt2gbkxhjok.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gt2gaxqcxic.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gt2rdyodlis.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qhntvbin.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cheryme.top/Article/details/gt2evgbuvzs.html

C#:   s.Replace("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gt2hofaslgd.html

[E07] 按分隔符拆分
来源：http://dali.zhoulong.xyz/Article/details/gt2vgtizihh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.daria6918.cn/Article/details/gt2jdfengpv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yuxming.cn/Article/details/gt2ubbaurch.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.wangdashe.top/Article/details/gt2upfhenxl.html

TS:   s.split(",")
来源：http://dali.dianchejie.cn/Article/details/gt2vrfjkrub.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.pengpengdd.cyou/Article/details/gt2kjsdlwui.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.nwbrower.top/Article/details/gt2zeiaifov.html

Ruby: s.split(",");  s.split
来源：http://dali.xuetiantiany.cn/Article/details/gt2csdzsgfs.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.aizwys.cn/Article/details/gt2rydfgmjd.html

[E08] 数组按分隔符合并
来源：http://dali.xziqi.cn/Article/details/gt2ojekuudf.html

Py:   ",".join(items)
来源：http://dali.tianlin.xyz/Article/details/gt2tjrsfrlo.html

PHP:  implode(",", $items);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qlerxjew.html

JS:   items.join(",")
来源：http://dali.guannengcc.top/Article/details/gt2drshlgmm.html

TS:   items.join(",")
来源：http://dali.mhx1999.top/Article/details/gt2hjtedpcp.html

Java: String.join(",", items)
来源：http://dali.birdmap.top/Article/details/gt2lufoiqni.html

Go:   strings.Join(items, ",")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ymsbtrpo.html

Ruby: items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gt2tszlmfui.html

C#:   string.Join(",", items)
来源：http://dali.yj20258888.top/Article/details/gt2oelafihc.html

[E09] 去除所有空白字符
来源：http://dali.hnqzz.top/Article/details/gt2npkphghc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gogol.net.cn/Article/details/gt2mugeqoqr.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenzaomai.com/Article/details/gt2ukdomzku.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shuidangran.top/Article/details/gt2yrsrwmbc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xinyue.icu/Article/details/gt2cdsflxiw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhoulong.xyz/Article/details/gt2kvaouhiz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hywenlv.cn/Article/details/gt2qmzczzcw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.nanxinkj.top/Article/details/gt2elauvkaf.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jyoumei.cn/Article/details/gt2vhdcaseu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cheryme.top/Article/details/gt2niljpwlm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.pycfn.com/Article/details/gt2vvmjsily.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.havefunace.top/Article/details/gt2qcjyqkvw.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pasehvam.html

TS:   "7".padStart(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gt2ersedhcs.html

Java: String.format("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2olcjvcoq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gt2kafbiqne.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gt2ceapuljk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shuidangran.top/Article/details/gt2pzpocvil.html

[E11] 反转字符串
来源：http://dali.cucudq.cn/Article/details/gt2tjlqxkwc.html

Py:   s[::-1]
来源：http://dali.tian-w.cn/Article/details/gt2faeygtaf.html

PHP:  strrev($s);
来源：http://dali.ehwqpu.com/Article/details/gt2twhybgmx.html

JS:   [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gt2qtrkwujl.html

TS:   [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gt2nztiwadg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yueranfly.top/Article/details/gt2dlkiyuig.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.redwolf501.top/Article/details/gt2ktoaocbe.html

Ruby: s.reverse
来源：http://dali.nwbrower.top/Article/details/gt2limxvqmr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.c1oappe.top/Article/details/gt2bzsapmpn.html

[E12] 统计某字符出现次数
来源：http://dali.nwbrower.top/Article/details/gt2ampddumi.html

Py:   s.count("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2owdczsgj.html

PHP:  substr_count($s, "a");
来源：http://dali.xuanzx.com/Article/details/gt2uavdakjs.html

JS:   s.split("a").length - 1
来源：http://dali.zhoulong.xyz/Article/details/gt2ysdbsenz.html

TS:   s.split("a").length - 1
来源：http://dali.zycfv.cn/Article/details/gt2xaniwoni.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jqgfzy.top/Article/details/gt2aupokilu.html

Go:   strings.Count(s, "a")
来源：http://dali.kuanghao11.cn/Article/details/gt2ddchxctf.html

Ruby: s.count("a")
来源：http://dali.kuanghao11.cn/Article/details/gt2sitqdtsx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.dianchejie.cn/Article/details/gt2lhahndyu.html

[E13] 逐字符遍历
来源：http://dali.sxryk.cn/Article/details/gt2lpzuuodb.html

Py:   for ch in s: print(ch)
来源：http://dali.yangfankeji.com/Article/details/gt2xjipuncy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jianghu66.top/Article/details/gt2dcvuvbak.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hywenlv.cn/Article/details/gt2btvfyzrl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2skzxfkex.html


<!-- 参考信息 -->