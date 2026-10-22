代发 wailian999

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.havefunace.top/Article/details/gt2tfzppcff.html

TS:   [...a, ...b];
来源：http://dali.nanxuanxn.top/Article/details/gt2azwpmexx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2zvelolyo.html

Go:   append(a, b...)
来源：http://dali.hammf.cn/Article/details/gt2rwjizral.html

Ruby: a + b;  a.concat(b)
来源：http://dali.tianlin.xyz/Article/details/gt2wlueycfb.html

C#:   a.Concat(b).ToList()
来源：http://dali.svipenyu.cn/Article/details/gt2hpgvmfgn.html

[D09] 排序（升序）
来源：http://dali.ybcxt.top/Article/details/gt2efgkrold.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenzaomai.com/Article/details/gt2tvavocml.html

PHP:  sort($arr);
来源：http://dali.cashguo.top/Article/details/gt2bpvlhbla.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmmfvte.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.mhx1999.top/Article/details/gt2rnhhficb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yj20258.top/Article/details/gt2fbvrlpei.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2lkakpkso.html

Ruby: arr.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gt2beavqiau.html

C#:   list.Sort();
来源：http://dali.pengpengdd.cyou/Article/details/gt2cnqoevua.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.smart0.xyz/Article/details/gt2dolgbhex.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sysykeji.top/Article/details/gt2yjsttwux.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gaohongyu789.top/Article/details/gt2mytclrlr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tzeqhzry.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuetiantiany.cn/Article/details/gt2epdlfptu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.fzhhl.top/Article/details/gt2hylmjwmc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.feifeiyinyue.top/Article/details/gt2bshjyndj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cashguo.top/Article/details/gt2hvgrfucm.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ppjwa.cn/Article/details/gt2hxrgxqkl.html

[D11] 反转数组
来源：http://dali.gotoacloud.top/Article/details/gt2rnoymblc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.guowangkeji.top/Article/details/gt2dakjgddd.html

PHP:  array_reverse($arr);
来源：http://dali.zycfv.cn/Article/details/gt2pgutcwnn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.quarkkingdee.top/Article/details/gt2javffrkj.html

TS:   [...arr].reverse();
来源：http://dali.chenzaomai.com/Article/details/gt2pcizhseg.html

Java: Collections.reverse(list);
来源：http://dali.zhengqikj.top/Article/details/gt2fapichpu.html

Go:   slices.Reverse(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2idtowmxa.html

Ruby: arr.reverse
来源：http://dali.yj20258.top/Article/details/gt2ktrykkpw.html

C#:   list.Reverse();
来源：http://dali.xziqi.cn/Article/details/gt2hjnrgdzc.html

[D12] 查找元素下标
来源：http://dali.c1oappe.top/Article/details/gt2crugsgdo.html

Py:   arr.index(x);  x in arr
来源：http://dali.yj20258.top/Article/details/gt2asxzujnp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hnqzz.top/Article/details/gt2vjailodr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigfzy.top/Article/details/gt2kwwtftdf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cqqwz.cn/Article/details/gt2umegqvps.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.fzhhl.top/Article/details/gt2wrlqftzl.html

Go:   slices.Index(arr, x)
来源：http://dali.ivvv.top/Article/details/gt2vebbytqa.html

Ruby: arr.index(x)
来源：http://dali.hysaishi.cn/Article/details/gt2teawecet.html

C#:   list.IndexOf(x);
来源：http://dali.hywenlv.cn/Article/details/gt2njoyrjvw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gzhubu.top/Article/details/gt2okafewfe.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cfojdmxg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sxryk.cn/Article/details/gt2hjszzmoq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xinyue.icu/Article/details/gt2esdcziiw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jqgufenzy.top/Article/details/gt2lmzfvxoj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2aqsaiter.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhixingplan.top/Article/details/gt2rrcvvspj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hnqzz.top/Article/details/gt2kvvhyboy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2euxbtiph.html

[D14] 映射转换（每个元素变形）
来源：http://dali.redwolf501.top/Article/details/gt2cwtyrfzv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.kuanghao11.cn/Article/details/gt2gvaazods.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sxryk.cn/Article/details/gt2anewduhl.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2bmwuvmib.html

TS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ynygygfv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.meibo888.top/Article/details/gt2jztbxlfs.html

Go:   // 手写循环
来源：http://dali.shuidangran.top/Article/details/gt2acsuhrlg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2drpqipwt.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.daxiang520.top/Article/details/gt2ewlxshus.html

[D15] 去重
来源：http://dali.nanxuanxn.top/Article/details/gt2kunpxnft.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.guannengcc.top/Article/details/gt2gnstthrs.html

PHP:  array_unique($arr);
来源：http://dali.ivvv.top/Article/details/gt2nciybvhd.html

JS:   [...new Set(arr)]
来源：http://dali.cashguo.top/Article/details/gt2agvhwnpv.html

TS:   [...new Set(arr)]
来源：http://dali.zhongyouzk.top/Article/details/gt2ebjehmwf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.redwolf501.top/Article/details/gt2dgssdhra.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shzxlz.cn/Article/details/gt2zcrpomjo.html

Ruby: arr.uniq
来源：http://dali.xziqi.cn/Article/details/gt2cloflgby.html

C#:   list.Distinct().ToList()
来源：http://dali.zhengqikj.top/Article/details/gt2tkuegclc.html

[D16] 求和与平均值
来源：http://dali.jqgfzy.top/Article/details/gt2emwndzhq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yueranfly.top/Article/details/gt2tpnextpx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gogol.net.cn/Article/details/gt2murvlmgn.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2piuleqkr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2qzglxmba.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhiwuduotai.top/Article/details/gt2xlwvlaoh.html

Go:   // 手写循环累加
来源：http://dali.chenzaomai.com/Article/details/gt2kjryzsqj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj20258.top/Article/details/gt2xddoasrv.html

C#:   list.Sum();  list.Average()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ocpfhsts.html

[D17] 最大值与最小值
来源：http://dali.hywenlv.cn/Article/details/gt2nurieuiy.html

Py:   max(arr);  min(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ygvvxwkg.html

PHP:  max($arr);  min($arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2ffescdrr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.redwolf501.top/Article/details/gt2yyzlxskb.html

TS:   Math.max(...arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tlkpsxlz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yueranfly.top/Article/details/gt2zvimzqhl.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.iojbl.cn/Article/details/gt2ngqmnaqh.html

Ruby: arr.max;  arr.min
来源：http://dali.svipenyu.cn/Article/details/gt2enlohaki.html

C#:   list.Max();  list.Min()
来源：http://dali.meibo888.top/Article/details/gt2xitbawwe.html

[D18] 扁平化嵌套数组
来源：http://dali.haohaochexian.top/Article/details/gt2unozwevd.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tian-w.cn/Article/details/gt2srxteyto.html

PHP:  array_merge(...$nested);
来源：http://dali.svipenyu.cn/Article/details/gt2cpcgxpco.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ivvv.top/Article/details/gt2iqxmesix.html

TS:   nested.flat();
来源：http://dali.zhongyouzk.top/Article/details/gt2mkfgjwod.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.bjfxy.top/Article/details/gt2xohysggb.html

Go:   // 手写双层循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xsucnbaa.html

Ruby: nested.flatten
来源：http://dali.cashguo.top/Article/details/gt2ncbltlrj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gt2owjmlpjm.html

[D19] 按字段分组
来源：http://dali.cucudq.cn/Article/details/gt2xbeifpfb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nanxinkj.top/Article/details/gt2ctlqzdzc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhixingplan.top/Article/details/gt2nfjmxupo.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xziqi.cn/Article/details/gt2jjaoranf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xuanzx.com/Article/details/gt2hsxnyzve.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.mhx1999.top/Article/details/gt2teydwskv.html

Go:   // 手写 map[string][]T
来源：http://dali.daria6918.cn/Article/details/gt2hrdnttqe.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhongyouzk.top/Article/details/gt2ydwmaqgp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.dashuyun.cn/Article/details/gt2mxlhwykv.html

[D20] 统计每个元素出现次数
来源：http://dali.tian-w.cn/Article/details/gt2reodtrqp.html

Py:   Counter(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2tdbcofrs.html

PHP:  array_count_values($arr);
来源：http://dali.yvedp.cn/Article/details/gt2obvxnfrr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangdashe.top/Article/details/gt2pxzanbyc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dianchejie.cn/Article/details/gt2gtxmwhtk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hnqzz.top/Article/details/gt2fhoopwdk.html

Go:   // 手写 map[T]int
来源：http://dali.hnqzz.top/Article/details/gt2vyiipyqc.html

Ruby: arr.tally
来源：http://dali.jqgufenzy.top/Article/details/gt2vbprztoh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sweek.top/Article/details/gt2orguouer.html

[D21] 判断是否包含某元素
来源：http://dali.jlsjyb.cn/Article/details/gt2zmbkydyr.html

Py:   x in arr
来源：http://dali.pengpengdd.cyou/Article/details/gt2onrwsppd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.mhx1999.top/Article/details/gt2tcsakvhj.html

JS:   arr.includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2upqnmmux.html

TS:   arr.includes(x)
来源：http://dali.chenlongwang.top/Article/details/gt2sbetitry.html

Java: list.contains(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2wwbvlswu.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vsnyrjuw.html

Ruby: arr.include?(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2scwocqis.html

C#:   list.Contains(x)
来源：http://dali.snrcjt.cn/Article/details/gt2fnjzymdk.html

[D22] 复制数组（避免共享引用）
来源：http://dali.pengpengdd.cyou/Article/details/gt2ygmpmeuj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2pmhbooci.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ppjwa.cn/Article/details/gt2hetvexrj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hwyfgrip.html

TS:   [...arr];
来源：http://dali.yongpay.top/Article/details/gt2uyjdmjjy.html

Java: new ArrayList<>(list);
来源：http://dali.ehwqpu.com/Article/details/gt2ujlzjdoi.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gzhubu.top/Article/details/gt2hwuxfvxp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhiwuduotai.top/Article/details/gt2iycfscnj.html

C#:   new List<int>(list);
来源：http://dali.chenlongwang.top/Article/details/gt2yhmguqej.html

[D23] reduce 累积计算
来源：http://dali.chenlongwang.top/Article/details/gt2qgnaaldt.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.birdmap.top/Article/details/gt2ggijeluu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nniienfb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuxming.cn/Article/details/gt2vhwygxjv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gt2sfvnyzur.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.fengsongda.top/Article/details/gt2bggsiqjq.html

Go:   // 手写循环
来源：http://dali.0kj1m.cn/Article/details/gt2iaxqypip.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jlsjyb.cn/Article/details/gt2bctgjxex.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.tian-w.cn/Article/details/gt2sjajmnle.html

[D24] 字典 / Map 基本操作
来源：http://dali.tianlin.xyz/Article/details/gt2pxxascjw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.tianlin.xyz/Article/details/gt2bijhxugs.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrzqrwc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2diibzlkb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yueranfly.top/Article/details/gt2evxabiks.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hywenlv.cn/Article/details/gt2heuvynge.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gotoacloud.top/Article/details/gt2gdfhiwnv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.316326.xyz/Article/details/gt2dblcojbf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhoulong.xyz/Article/details/gt2hiyarilm.html

[D25] Set 集合去重与交并差
来源：http://dali.9152youxi.cn/Article/details/gt2dfhshyvu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.chenjidiqi.icu/Article/details/gt2omvlaemo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.chenzaomai.com/Article/details/gt2tclgextl.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.smart0.xyz/Article/details/gt2rzxtqfcp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shuidangran.top/Article/details/gt2wsqteymk.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.aizwys.cn/Article/details/gt2pvscaywx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shzxlz.cn/Article/details/gt2yfrrjxwm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.birdmap.top/Article/details/gt2asemkmib.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.daxiang520.top/Article/details/gt2vdvatdeh.html

[D26] 数组转字符串
来源：http://dali.svipenyu.cn/Article/details/gt2bejujzjm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj202588.top/Article/details/gt2chbmkerl.html

PHP:  implode(", ", $arr);
来源：http://dali.yj20258888.top/Article/details/gt2avverkad.html

JS:   arr.join(", ")
来源：http://dali.andypj.xyz/Article/details/gt2evcgsluz.html

TS:   arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gt2gzykbbui.html

Java: String.join(", ", list)
来源：http://dali.gzhubu.top/Article/details/gt2zlglogxn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yj20258.top/Article/details/gt2zixmiccy.html

Ruby: arr.join(", ")
来源：http://dali.tianlin.xyz/Article/details/gt2eswthsyv.html

C#:   string.Join(", ", list)
来源：http://dali.aibaodan.cn/Article/details/gt2ihlhtujf.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2vhcapggb.html

E. 字符串处理
来源：http://dali.hysaishi.cn/Article/details/gt2nlvqvbgi.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2dzthvkln.html

[E01] 拼接字符串
来源：http://dali.yongpay.top/Article/details/gt2fwpbxdtz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.nwbrower.top/Article/details/gt2enydhjbv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hfpthk.cn/Article/details/gt2gfovkazw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhongyouzk.top/Article/details/gt2icywpers.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.meibo888.top/Article/details/gt2zeboiauu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cucudq.cn/Article/details/gt2fojeeerv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zdqjudy.top/Article/details/gt2mpelnkcl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.wangshuangyany.cn/Article/details/gt2qwbelabr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gt2gjcuiwtc.html

[E02] 重复字符串
来源：http://dali.fengsongda.top/Article/details/gt2mzeupono.html

Py:   "ab" * 3
来源：http://dali.guannengcc.top/Article/details/gt2wnkfxwvt.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zqubbyvb.html

JS:   "ab".repeat(3)
来源：http://dali.yuanzhike.top/Article/details/gt2hyddobsp.html

TS:   "ab".repeat(3)
来源：http://dali.zhoulong.xyz/Article/details/gt2deanxvxe.html

Java: "ab".repeat(3)
来源：http://dali.iojbl.cn/Article/details/gt2qbgkggin.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.c1oappe.top/Article/details/gt2rlhwsiew.html

Ruby: "ab" * 3
来源：http://dali.jinghuilouyu.cn/Article/details/gt2igbjooko.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gzhubu.top/Article/details/gt2sbaygvis.html

[E03] 截取子串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2foaptcmx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yongpay.top/Article/details/gt2faszlwyd.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gt2zyeryibv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.bjfxy.top/Article/details/gt2mqpkxsac.html

TS:   s.slice(1, 4)
来源：http://dali.yj20258888.top/Article/details/gt2lzhoklrt.html

Java: s.substring(1, 4)
来源：http://dali.cdnleiting.top/Article/details/gt2chijwfft.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shangyingyoupin.top/Article/details/gt2teybgcdm.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.quarkkingdee.top/Article/details/gt2vjuvzaha.html

C#:   s.Substring(1, 3)
来源：http://dali.xziqi.cn/Article/details/gt2ssclwfml.html

[E04] 查找子串位置
来源：http://dali.hysaishi.cn/Article/details/gt2ychzoian.html

Py:   s.find("x");  s.index("x")
来源：http://dali.0kj1m.cn/Article/details/gt2jgkwsemh.html

PHP:  strpos($s, "x");
来源：http://dali.nanxinkj.top/Article/details/gt2unavtxog.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ybcxt.top/Article/details/gt2ephawdmi.html

TS:   s.indexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gt2lzkizppf.html

Java: s.indexOf("x")
来源：http://dali.jqgfzy.top/Article/details/gt2kiumjqbi.html

Go:   strings.Index(s, "x")
来源：http://dali.havefunace.top/Article/details/gt2vfzjaplx.html

Ruby: s.index("x")
来源：http://dali.cashguo.top/Article/details/gt2bxsijduf.html

C#:   s.IndexOf("x")
来源：http://dali.ppjwa.cn/Article/details/gt2lilgqppn.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.9152youxi.cn/Article/details/gt2ysifzquo.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.havefunace.top/Article/details/gt2fcujyhqt.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jiagoushi.top/Article/details/gt2pptifssr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cucudq.cn/Article/details/gt2fqtamreq.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hysaishi.cn/Article/details/gt2ybgmhkqx.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yongpay.top/Article/details/gt2assgqiof.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.nanxinkj.top/Article/details/gt2tbyngzei.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yjtskirs.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shuidangran.top/Article/details/gt2rwwxrtwk.html

[E06] 替换子串
来源：http://dali.smart0.xyz/Article/details/gt2ccmsnugt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jyoumei.cn/Article/details/gt2xmprhtxc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yangfankeji.com/Article/details/gt2uqkxchjr.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hammf.cn/Article/details/gt2fnpugafw.html

TS:   s.replaceAll("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gt2tugvtrrb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shuidangran.top/Article/details/gt2jfbadgkd.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2meaqdkeq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yvedp.cn/Article/details/gt2kjyoizvo.html

C#:   s.Replace("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gt2rfhrsfcb.html

[E07] 按分隔符拆分
来源：http://dali.aizwys.cn/Article/details/gt2jgtfubuk.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhengqikj.top/Article/details/gt2trgacyjz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aohurbuy.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ppjwa.cn/Article/details/gt2mzybmaiy.html

TS:   s.split(",")
来源：http://dali.yanxiufei.cn/Article/details/gt2mfeeukah.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jianghu66.top/Article/details/gt2pcuzxhoj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ivvv.top/Article/details/gt2mxqhvqgi.html

Ruby: s.split(",");  s.split
来源：http://dali.cucudq.cn/Article/details/gt2peosmuai.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jqgufenzy.top/Article/details/gt2ohwnfnac.html

[E08] 数组按分隔符合并
来源：http://dali.hammf.cn/Article/details/gt2lelcorne.html

Py:   ",".join(items)
来源：http://dali.smart0.xyz/Article/details/gt2brbmrprt.html

PHP:  implode(",", $items);
来源：http://dali.sweek.top/Article/details/gt2jgeejqvi.html

JS:   items.join(",")
来源：http://dali.guowangkeji.top/Article/details/gt2bljpsoka.html

TS:   items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gt2tgeteizs.html

Java: String.join(",", items)
来源：http://dali.xuanzx.com/Article/details/gt2qwwmdpql.html

Go:   strings.Join(items, ",")
来源：http://dali.tian-w.cn/Article/details/gt2kfovglnf.html

Ruby: items.join(",")
来源：http://dali.birdmap.top/Article/details/gt2khljymyr.html

C#:   string.Join(",", items)
来源：http://dali.vqdsnc.cn/Article/details/gt2bgnoojab.html

[E09] 去除所有空白字符
来源：http://dali.yvedp.cn/Article/details/gt2zbigdjrl.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hfpthk.cn/Article/details/gt2lltdwftn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.dianchejie.cn/Article/details/gt2jeqcqisi.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xuanzx.com/Article/details/gt2akgyffsz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ybcxt.top/Article/details/gt2pefzcaxp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xuetiantiany.cn/Article/details/gt2auiywxjs.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.fzhhl.top/Article/details/gt2heiczoyl.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ydzc1.top/Article/details/gt2mzmymcua.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.haohaochexian.top/Article/details/gt2xvutkhhk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nsvkrsrh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gt2jzompoao.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shuidangran.top/Article/details/gt2inmwhcwb.html

JS:   "7".padStart(3, "0")
来源：http://dali.fzhhl.top/Article/details/gt2xqoimuhl.html

TS:   "7".padStart(3, "0")
来源：http://dali.yuanzhike.top/Article/details/gt2jsejokrj.html

Java: String.format("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gt2lnpoidsm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.quarkkingdee.top/Article/details/gt2uztgtdzg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yangfankeji.com/Article/details/gt2mxojpsug.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ppjwa.cn/Article/details/gt2ziftomlq.html

[E11] 反转字符串
来源：http://dali.redwolf501.top/Article/details/gt2zirysndg.html

Py:   s[::-1]
来源：http://dali.dashuyun.cn/Article/details/gt2sxgffeez.html

PHP:  strrev($s);
来源：http://dali.fengsongda.top/Article/details/gt2yohfszyx.html

JS:   [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gt2odrqmhky.html

TS:   [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gt2zbldwsis.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xuanzx.com/Article/details/gt2treqsohz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhoulong.xyz/Article/details/gt2nuousrcn.html

Ruby: s.reverse
来源：http://dali.gogol.net.cn/Article/details/gt2kkrcsvxa.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.bjfxy.top/Article/details/gt2yhcfouww.html

[E12] 统计某字符出现次数
来源：http://dali.tanke756.top/Article/details/gt2mfrtekne.html

Py:   s.count("a")
来源：http://dali.feifeiyinyue.top/Article/details/gt2cgvudjdj.html

PHP:  substr_count($s, "a");
来源：http://dali.sxryk.cn/Article/details/gt2hkvlrmdz.html

JS:   s.split("a").length - 1
来源：http://dali.yonumen.top/Article/details/gt2qyujljdz.html

TS:   s.split("a").length - 1
来源：http://dali.havefunace.top/Article/details/gt2vltdvwih.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2npsxnbsi.html

Go:   strings.Count(s, "a")
来源：http://dali.ybcxt.top/Article/details/gt2nwhvgauv.html

Ruby: s.count("a")
来源：http://dali.wangshuangyany.cn/Article/details/gt2xkamfcjg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hrgryglp.html

[E13] 逐字符遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cawbktux.html

Py:   for ch in s: print(ch)
来源：http://dali.hnxiangtu.top/Article/details/gt2lplhhvup.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.kuanghao11.cn/Article/details/gt2pevxygwx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gt2tegwkijf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2texuiqey.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2amlwkouu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jqgufenzy.top/Article/details/gt2jybmmtma.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.316326.xyz/Article/details/gt2hiodkoyy.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2qtogexty.html

[E14] URL 编码与 Base64
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ewszwbtl.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cqqwz.cn/Article/details/gt2awzxmkfw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jiagoushi.top/Article/details/gt2bwjuxfxw.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.0kj1m.cn/Article/details/gt2jvzccknx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hammf.cn/Article/details/gt2ucwuyifp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlbwwyl.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhengqikj.top/Article/details/gt2qdwtjrcs.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zycfv.cn/Article/details/gt2hoadnnkl.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.c1oappe.top/Article/details/gt2yesaofny.html

[E15] HTML 转义 / 反转义
来源：http://dali.andypj.xyz/Article/details/gt2optpcpes.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qagsnlyz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jlsjyb.cn/Article/details/gt2mbzfksll.html


<!-- 参考信息 -->