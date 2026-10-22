代发 wailian999

TS:   arr.slice(1, 4);
来源：http://dali.gaohongyu789.top/Article/details/gt2pzkfxoek.html

Java: list.subList(1, 4);
来源：http://dali.dianchejie.cn/Article/details/gt2sqeuobmw.html

Go:   arr[1:4]
来源：http://dali.xuanzx.com/Article/details/gt2irlgkvqj.html

Ruby: arr[1, 3]
来源：http://dali.0kj1m.cn/Article/details/gt2nafjgkki.html

C#:   list.GetRange(1, 3);
来源：http://dali.cqqwz.cn/Article/details/gt2fbkwoxiv.html

[D08] 合并两个数组
来源：http://dali.yangfankeji.com/Article/details/gt2imasjstr.html

Py:   a + b;  a.extend(b)
来源：http://dali.cheryme.top/Article/details/gt2scrcptub.html

PHP:  array_merge($a, $b);
来源：http://dali.pengpengdd.cyou/Article/details/gt2tdfhkbrv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yuxming.cn/Article/details/gt2xiorctkl.html

TS:   [...a, ...b];
来源：http://dali.birdmap.top/Article/details/gt2ohmufbsv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hammf.cn/Article/details/gt2duqewklm.html

Go:   append(a, b...)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nfyuiblm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uqpzgbzm.html

C#:   a.Concat(b).ToList()
来源：http://dali.zdqjudy.top/Article/details/gt2zoutlors.html

[D09] 排序（升序）
来源：http://dali.hammf.cn/Article/details/gt2pvcduteq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hpacywoi.html

PHP:  sort($arr);
来源：http://dali.hywenlv.cn/Article/details/gt2ncnesrkb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.birdmap.top/Article/details/gt2aatdqmrn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gotoacloud.top/Article/details/gt2dcdtzhyb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenjidiqi.icu/Article/details/gt2xmtqydga.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2vaynrhck.html

Ruby: arr.sort
来源：http://dali.hammf.cn/Article/details/gt2sfvyjnxa.html

C#:   list.Sort();
来源：http://dali.shangyingyoupin.top/Article/details/gt2vwljoblv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yuanzhike.top/Article/details/gt2itfjtpao.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yangfankeji.com/Article/details/gt2vykplozj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ybcxt.top/Article/details/gt2uiyoauok.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nwbrower.top/Article/details/gt2bofioezl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.redwolf501.top/Article/details/gt2soqaesal.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.pengpengdd.cyou/Article/details/gt2shemfqaf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhoulong.xyz/Article/details/gt2zmyduqgu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yonumen.top/Article/details/gt2slhttiyc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cheryme.top/Article/details/gt2ntwgvehx.html

[D11] 反转数组
来源：http://dali.bjfxy.top/Article/details/gt2iqnucgij.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hnqzz.top/Article/details/gt2nezjxwfi.html

PHP:  array_reverse($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2fasxvbmk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gogol.net.cn/Article/details/gt2oldzxahg.html

TS:   [...arr].reverse();
来源：http://dali.hammf.cn/Article/details/gt2wzuyljjp.html

Java: Collections.reverse(list);
来源：http://dali.gaohongyu789.top/Article/details/gt2vdrtpfrb.html

Go:   slices.Reverse(arr)
来源：http://dali.iojbl.cn/Article/details/gt2eqqvjdxd.html

Ruby: arr.reverse
来源：http://dali.nanxuanxn.top/Article/details/gt2ykpchcje.html

C#:   list.Reverse();
来源：http://dali.redwolf501.top/Article/details/gt2myewygmf.html

[D12] 查找元素下标
来源：http://dali.ehwqpu.com/Article/details/gt2bfjhdpyu.html

Py:   arr.index(x);  x in arr
来源：http://dali.nwbrower.top/Article/details/gt2tbneazao.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.bjfxy.top/Article/details/gt2hznerpwm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xinyue.icu/Article/details/gt2zcwhmqls.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ydzc1.top/Article/details/gt2zaonflhl.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xinyue.icu/Article/details/gt2taqcwgbb.html

Go:   slices.Index(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wubbonki.html

Ruby: arr.index(x)
来源：http://dali.zhixingplan.top/Article/details/gt2rtriswyh.html

C#:   list.IndexOf(x);
来源：http://dali.cheryme.top/Article/details/gt2kjzucbhs.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jyoumei.cn/Article/details/gt2hdtjgawz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hysaishi.cn/Article/details/gt2actcwfmi.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.316326.xyz/Article/details/gt2vkoxhzzd.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yuanzhike.top/Article/details/gt2vavcohhr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.wangdashe.top/Article/details/gt2sltdnaio.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yueranfly.top/Article/details/gt2oaqozuoc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hgnahdaz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sweek.top/Article/details/gt2iiahczba.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cheryme.top/Article/details/gt2ymbtyxjj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xziqi.cn/Article/details/gt2cmzusanq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jyoumei.cn/Article/details/gt2ohipdikr.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.mhx1999.top/Article/details/gt2eerdcbym.html

JS:   arr.map(x => x * 2)
来源：http://dali.kuanghao11.cn/Article/details/gt2robpqpys.html

TS:   arr.map(x => x * 2)
来源：http://dali.jiagoushi.top/Article/details/gt2afpdhezo.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.dianchejie.cn/Article/details/gt2igyqyjfu.html

Go:   // 手写循环
来源：http://dali.feifeiyinyue.top/Article/details/gt2krutitxs.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.smart0.xyz/Article/details/gt2qbrrqsgg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ppjwa.cn/Article/details/gt2sjokqjtz.html

[D15] 去重
来源：http://dali.pengpengdd.cyou/Article/details/gt2nzvaolfe.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cheryme.top/Article/details/gt2btakgfpl.html

PHP:  array_unique($arr);
来源：http://dali.havefunace.top/Article/details/gt2jwasxpqc.html

JS:   [...new Set(arr)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vlpkhlke.html

TS:   [...new Set(arr)]
来源：http://dali.wangshuangyany.cn/Article/details/gt2bqnnqhvq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xylfe.cn/Article/details/gt2arumjjmy.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yj20258888.top/Article/details/gt2zaiprgjv.html

Ruby: arr.uniq
来源：http://dali.gogol.net.cn/Article/details/gt2esgagume.html

C#:   list.Distinct().ToList()
来源：http://dali.bjfxy.top/Article/details/gt2gnhdbhpc.html

[D16] 求和与平均值
来源：http://dali.shzxlz.cn/Article/details/gt2uvzntxje.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gzhubu.top/Article/details/gt2vhjijjxq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.daxiang520.top/Article/details/gt2zynotsov.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2qmbxiirs.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guannengcc.top/Article/details/gt2homrnohj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hammf.cn/Article/details/gt2apbfpswd.html

Go:   // 手写循环累加
来源：http://dali.dashuyun.cn/Article/details/gt2eimxdype.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yangfankeji.com/Article/details/gt2fnrdmabp.html

C#:   list.Sum();  list.Average()
来源：http://dali.hnxiangtu.top/Article/details/gt2xrdbitss.html

[D17] 最大值与最小值
来源：http://dali.guowangkeji.top/Article/details/gt2emxascpl.html

Py:   max(arr);  min(arr)
来源：http://dali.ybcxt.top/Article/details/gt2oedtivww.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhixingplan.top/Article/details/gt2dvzrxoab.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2wefiifay.html

TS:   Math.max(...arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ovlehymn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.svipenyu.cn/Article/details/gt2bzfjgehf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2hdnqrxnq.html

Ruby: arr.max;  arr.min
来源：http://dali.yuxming.cn/Article/details/gt2upjnhhep.html

C#:   list.Max();  list.Min()
来源：http://dali.wangshuangyany.cn/Article/details/gt2vmfjlimu.html

[D18] 扁平化嵌套数组
来源：http://dali.ydzc1.top/Article/details/gt2aqoadyrk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.9152youxi.cn/Article/details/gt2ocqkcwds.html

PHP:  array_merge(...$nested);
来源：http://dali.cqqwz.cn/Article/details/gt2cugauocb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iybmnftd.html

TS:   nested.flat();
来源：http://dali.zdqjudy.top/Article/details/gt2eegprxwc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.tanke756.top/Article/details/gt2mwdpdvqw.html

Go:   // 手写双层循环
来源：http://dali.jlsjyb.cn/Article/details/gt2wzyjhqyr.html

Ruby: nested.flatten
来源：http://dali.nwbrower.top/Article/details/gt2lktecjqv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gt2pkdmkrvc.html

[D19] 按字段分组
来源：http://dali.cqqwz.cn/Article/details/gt2liiwrwyu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2vqsomiop.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jiagoushi.top/Article/details/gt2bcumukni.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rqkbsqed.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yj202588.top/Article/details/gt2qajxjedn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shzxlz.cn/Article/details/gt2alaznllq.html

Go:   // 手写 map[string][]T
来源：http://dali.zhongyouzk.top/Article/details/gt2iesxucmx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.snrcjt.cn/Article/details/gt2mzoqrcxc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xuetiantiany.cn/Article/details/gt2oeosvvcl.html

[D20] 统计每个元素出现次数
来源：http://dali.dashuyun.cn/Article/details/gt2tmodywsp.html

Py:   Counter(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2irhpmurc.html

PHP:  array_count_values($arr);
来源：http://dali.meibo888.top/Article/details/gt2weltzvby.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sufxvd.cn/Article/details/gt2ouwkqhku.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.smart0.xyz/Article/details/gt2bwfnnbdy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jyoumei.cn/Article/details/gt2krfukbjc.html

Go:   // 手写 map[T]int
来源：http://dali.sufxvd.cn/Article/details/gt2vhepppdp.html

Ruby: arr.tally
来源：http://dali.yvedp.cn/Article/details/gt2lztkoand.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sufxvd.cn/Article/details/gt2oaniflwd.html

[D21] 判断是否包含某元素
来源：http://dali.fengsongda.top/Article/details/gt2ttcdflkd.html

Py:   x in arr
来源：http://dali.birdmap.top/Article/details/gt2olodaulf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shzxlz.cn/Article/details/gt2dubupgji.html

JS:   arr.includes(x)
来源：http://dali.316326.xyz/Article/details/gt2iwxefqui.html

TS:   arr.includes(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2mzajsvar.html

Java: list.contains(x)
来源：http://dali.shzxlz.cn/Article/details/gt2rsdpzxzj.html

Go:   slices.Contains(arr, x)
来源：http://dali.daxiang520.top/Article/details/gt2prvlayuy.html

Ruby: arr.include?(x)
来源：http://dali.316326.xyz/Article/details/gt2cqqbswux.html

C#:   list.Contains(x)
来源：http://dali.hnqzz.top/Article/details/gt2bfroywri.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhoulong.xyz/Article/details/gt2jhsurqnp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2anrjymbj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.smart0.xyz/Article/details/gt2eicxvzwe.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yongpay.top/Article/details/gt2dbfulmrj.html

TS:   [...arr];
来源：http://dali.gaohongyu789.top/Article/details/gt2apdlqqcz.html

Java: new ArrayList<>(list);
来源：http://dali.hfpthk.cn/Article/details/gt2onqglkyn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.meibo888.top/Article/details/gt2wvdeutko.html

Ruby: arr.dup;  arr.clone
来源：http://dali.meibo888.top/Article/details/gt2gducvuru.html

C#:   new List<int>(list);
来源：http://dali.cdnleiting.top/Article/details/gt2hvpcqztk.html

[D23] reduce 累积计算
来源：http://dali.jlsjyb.cn/Article/details/gt2iipweygh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yj20258.top/Article/details/gt2wlnbekcw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzfhbpt.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.haohaochexian.top/Article/details/gt2nowsoboq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2jshqvzvk.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sysykeji.top/Article/details/gt2nxaxyvlf.html

Go:   // 手写循环
来源：http://dali.feifeiyinyue.top/Article/details/gt2hnociton.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhoulong.xyz/Article/details/gt2bdqqtimt.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.daria6918.cn/Article/details/gt2wfkvnrdd.html

[D24] 字典 / Map 基本操作
来源：http://dali.ybcxt.top/Article/details/gt2xllulqui.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.bjfxy.top/Article/details/gt2jrdoplwu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.wangdashe.top/Article/details/gt2euucplsj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2btckdcds.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.daria6918.cn/Article/details/gt2wxugmxhu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.vqdsnc.cn/Article/details/gt2lxkvzgto.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zhvlnryn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cucudq.cn/Article/details/gt2xuylopmb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yj20258888.top/Article/details/gt2qzujzkdl.html

[D25] Set 集合去重与交并差
来源：http://dali.jqgufenzy.top/Article/details/gt2sivgrlbh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yuxming.cn/Article/details/gt2illrbnxc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shuidangran.top/Article/details/gt2yfexgfis.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2xoqphmfl.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hnqzz.top/Article/details/gt2ngccpgiw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2usgpnlko.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xinyue.icu/Article/details/gt2wyixdoct.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhixingplan.top/Article/details/gt2rkqbrvzp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cdnleiting.top/Article/details/gt2pdogmbni.html

[D26] 数组转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2imephipi.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xylfe.cn/Article/details/gt2qmpotwtb.html

PHP:  implode(", ", $arr);
来源：http://dali.gotoacloud.top/Article/details/gt2jjytyoql.html

JS:   arr.join(", ")
来源：http://dali.gzhubu.top/Article/details/gt2ebdthyex.html

TS:   arr.join(", ")
来源：http://dali.gzhubu.top/Article/details/gt2bhfgolnr.html

Java: String.join(", ", list)
来源：http://dali.sysykeji.top/Article/details/gt2zxtnzykw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yueranfly.top/Article/details/gt2respaqur.html

Ruby: arr.join(", ")
来源：http://dali.jlsjyb.cn/Article/details/gt2kmhfmnqn.html

C#:   string.Join(", ", list)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kiqgnxzv.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2szylravr.html

E. 字符串处理
来源：http://dali.ppjwa.cn/Article/details/gt2bknqrhgh.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2qpgknfwn.html

[E01] 拼接字符串
来源：http://dali.chenlongwang.top/Article/details/gt2pwtlxdph.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cdnleiting.top/Article/details/gt2nymqzzyb.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jianghu66.top/Article/details/gt2lyojqsnr.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zycfv.cn/Article/details/gt2unjwpzna.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hysaishi.cn/Article/details/gt2xvaakicz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.bjfxy.top/Article/details/gt2adbutkbu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.fzhhl.top/Article/details/gt2onppjjhf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zdqjudy.top/Article/details/gt2dugubxpr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cucudq.cn/Article/details/gt2sugiwfhu.html

[E02] 重复字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2rxzjovdl.html

Py:   "ab" * 3
来源：http://dali.pycfn.com/Article/details/gt2rmpvosak.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zdqjudy.top/Article/details/gt2uycozroz.html

JS:   "ab".repeat(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yeafsoxs.html

TS:   "ab".repeat(3)
来源：http://dali.yongpay.top/Article/details/gt2zonlfiru.html

Java: "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gt2ajbqfnka.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.mhx1999.top/Article/details/gt2fazfsxhc.html

Ruby: "ab" * 3
来源：http://dali.yj20258.top/Article/details/gt2awyofipv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hammf.cn/Article/details/gt2phzbctok.html

[E03] 截取子串
来源：http://dali.zhixingplan.top/Article/details/gt2oftywzta.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yuxming.cn/Article/details/gt2nsotgffa.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gt2vdzytduv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.kuanghao11.cn/Article/details/gt2efknvyhd.html

TS:   s.slice(1, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jdjmjzbm.html

Java: s.substring(1, 4)
来源：http://dali.xylfe.cn/Article/details/gt2clmqjkey.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.dianchejie.cn/Article/details/gt2gqipavmg.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.mhx1999.top/Article/details/gt2fbeilyfn.html

C#:   s.Substring(1, 3)
来源：http://dali.yongpay.top/Article/details/gt2qttlyzil.html

[E04] 查找子串位置
来源：http://dali.xylfe.cn/Article/details/gt2gaxkmhui.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ehwqpu.com/Article/details/gt2ojruvfur.html

PHP:  strpos($s, "x");
来源：http://dali.redwolf501.top/Article/details/gt2fsjghpdb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hysaishi.cn/Article/details/gt2kpkdpllc.html

TS:   s.indexOf("x")
来源：http://dali.xylfe.cn/Article/details/gt2vghvhvlj.html

Java: s.indexOf("x")
来源：http://dali.zhongyouzk.top/Article/details/gt2cslfshna.html

Go:   strings.Index(s, "x")
来源：http://dali.chenlongwang.top/Article/details/gt2iopjispp.html

Ruby: s.index("x")
来源：http://dali.yanxiufei.cn/Article/details/gt2wuzhtrqw.html

C#:   s.IndexOf("x")
来源：http://dali.andypj.xyz/Article/details/gt2qefdwwak.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhongyouzk.top/Article/details/gt2xpmqkugc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yqhrivkp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.daxiang520.top/Article/details/gt2kjezzbdf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.vqdsnc.cn/Article/details/gt2wbbxszsw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hywenlv.cn/Article/details/gt2lqvsxvqq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.andypj.xyz/Article/details/gt2gecytqqt.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.pycfn.com/Article/details/gt2sujayupo.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ybcxt.top/Article/details/gt2gragsasb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2odrvlgij.html

[E06] 替换子串
来源：http://dali.aizwys.cn/Article/details/gt2vkyethoz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.9152youxi.cn/Article/details/gt2hatexhpp.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.chenlongwang.top/Article/details/gt2fjgjrenf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258.top/Article/details/gt2pkwbqcog.html

TS:   s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gt2dfdkntml.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gt2pypasizc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.aizwys.cn/Article/details/gt2hanxquul.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ybcxt.top/Article/details/gt2vsilakve.html

C#:   s.Replace("a", "b")
来源：http://dali.yuxming.cn/Article/details/gt2hpapzpge.html

[E07] 按分隔符拆分
来源：http://dali.gzhubu.top/Article/details/gt2qfvrmcrz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.redwolf501.top/Article/details/gt2pkxwshgm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.aibaodan.cn/Article/details/gt2eveglwgb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.meibo888.top/Article/details/gt2scdnrbyo.html

TS:   s.split(",")
来源：http://dali.jqgufenzy.top/Article/details/gt2xpxlhodz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yanxiufei.cn/Article/details/gt2xqibfrpn.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jqgfzy.top/Article/details/gt2eqwquinj.html

Ruby: s.split(",");  s.split
来源：http://dali.cdnleiting.top/Article/details/gt2gnbfpfmr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hammf.cn/Article/details/gt2uwwnttgv.html

[E08] 数组按分隔符合并
来源：http://dali.yj20258.top/Article/details/gt2dvislgrz.html

Py:   ",".join(items)
来源：http://dali.zhoulong.xyz/Article/details/gt2flyhkxum.html

PHP:  implode(",", $items);
来源：http://dali.yongpay.top/Article/details/gt2kdwxjzzd.html

JS:   items.join(",")
来源：http://dali.tian-w.cn/Article/details/gt2apotnmta.html

TS:   items.join(",")
来源：http://dali.shzxlz.cn/Article/details/gt2gxsiddmu.html

Java: String.join(",", items)
来源：http://dali.sufxvd.cn/Article/details/gt2gsbstymq.html

Go:   strings.Join(items, ",")
来源：http://dali.birdmap.top/Article/details/gt2ftuwmpnj.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2bsuvxyqi.html

C#:   string.Join(",", items)
来源：http://dali.yj202588.top/Article/details/gt2qkyfsdbt.html

[E09] 去除所有空白字符
来源：http://dali.jinqigufen.top/Article/details/gt2xpdukyqy.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jpzboldm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.havefunace.top/Article/details/gt2rfwvvamj.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qonxuxwu.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lbdaczjf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hammf.cn/Article/details/gt2ljpjzrgg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.guowangkeji.top/Article/details/gt2baeqsmys.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.vqdsnc.cn/Article/details/gt2iiyqinyu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zzbakhpu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.haohaochexian.top/Article/details/gt2yncljqnu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hnxiangtu.top/Article/details/gt2drebjfwn.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.wangdashe.top/Article/details/gt2xyhiwqfu.html

JS:   "7".padStart(3, "0")
来源：http://dali.yj20258888.top/Article/details/gt2odgxrglp.html

TS:   "7".padStart(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gt2rgielmze.html

Java: String.format("%03d", 7)
来源：http://dali.yvedp.cn/Article/details/gt2gyulbqoj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gt2guqvpnbv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.birdmap.top/Article/details/gt2qnxrnlzk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zycfv.cn/Article/details/gt2wxqrrmdz.html

[E11] 反转字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2lencsxdc.html

Py:   s[::-1]
来源：http://dali.ehwqpu.com/Article/details/gt2hzegpajs.html

PHP:  strrev($s);
来源：http://dali.gaohongyu789.top/Article/details/gt2nptbejny.html

JS:   [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gt2gnavrsqt.html

TS:   [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gt2htjlvlxq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yonumen.top/Article/details/gt2msmuzapk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cdnleiting.top/Article/details/gt2zwbwoisy.html

Ruby: s.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gt2riadhqur.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ivvv.top/Article/details/gt2inttzrxl.html

[E12] 统计某字符出现次数
来源：http://dali.shuidangran.top/Article/details/gt2bgfubszo.html

Py:   s.count("a")
来源：http://dali.nanxinkj.top/Article/details/gt2vpwmrrlp.html

PHP:  substr_count($s, "a");
来源：http://dali.kuanghao11.cn/Article/details/gt2bikjfshr.html

JS:   s.split("a").length - 1
来源：http://dali.tian-w.cn/Article/details/gt2gvappxfx.html

TS:   s.split("a").length - 1
来源：http://dali.sxryk.cn/Article/details/gt2whkhjisk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2inoxglnl.html

Go:   strings.Count(s, "a")
来源：http://dali.chenzaomai.com/Article/details/gt2bzfbobnx.html

Ruby: s.count("a")
来源：http://dali.iojbl.cn/Article/details/gt2afnuuged.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinqigfzy.top/Article/details/gt2upnisrno.html

[E13] 逐字符遍历
来源：http://dali.pengpengdd.cyou/Article/details/gt2xxsoflrx.html

Py:   for ch in s: print(ch)
来源：http://dali.jianghu66.top/Article/details/gt2jpztohlt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.dashuyun.cn/Article/details/gt2xyfmrrdz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj202588.top/Article/details/gt2knuugsci.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.snrcjt.cn/Article/details/gt2qitduhng.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yj202588.top/Article/details/gt2thakmglk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sweek.top/Article/details/gt2kfojcsak.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yuxming.cn/Article/details/gt2sgxwkabs.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.pycfn.com/Article/details/gt2xllbzujb.html

[E14] URL 编码与 Base64
来源：http://dali.meibo888.top/Article/details/gt2jajcgiau.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ybcxt.top/Article/details/gt2bxlvxwdr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.svipenyu.cn/Article/details/gt2aamijadx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.guannengcc.top/Article/details/gt2kjjpaubq.html


<!-- 参考信息 -->