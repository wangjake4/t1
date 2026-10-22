代发 wailian999

Py:   len(arr)
来源：http://dali.ivvv.top/Article/details/gt2vywnajas.html

PHP:  count($arr);
来源：http://dali.xziqi.cn/Article/details/gt2irwkennn.html

JS:   arr.length
来源：http://dali.svipenyu.cn/Article/details/gt2tkkoytou.html

TS:   arr.length
来源：http://dali.nwbrower.top/Article/details/gt2kjkejukk.html

Java: list.size();
来源：http://dali.cqqwz.cn/Article/details/gt2dypdssvc.html

Go:   len(arr)
来源：http://dali.daria6918.cn/Article/details/gt2jzxubugh.html

Ruby: arr.length; arr.size
来源：http://dali.yonumen.top/Article/details/gt2yomyzyvk.html

C#:   list.Count;
来源：http://dali.jinqigufen.top/Article/details/gt2uaaqvjcu.html

[D07] 切片 / 取子数组
来源：http://dali.ivvv.top/Article/details/gt2srclmgwt.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhiwuduotai.top/Article/details/gt2axvwmtrn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.pengpengdd.cyou/Article/details/gt2sxlqouzy.html

JS:   arr.slice(1, 4);
来源：http://dali.kuanghao11.cn/Article/details/gt2ecckxtxi.html

TS:   arr.slice(1, 4);
来源：http://dali.aibaodan.cn/Article/details/gt2gryxechc.html

Java: list.subList(1, 4);
来源：http://dali.yueranfly.top/Article/details/gt2ymaerrkf.html

Go:   arr[1:4]
来源：http://dali.quarkkingdee.top/Article/details/gt2uecujkbk.html

Ruby: arr[1, 3]
来源：http://dali.tian-w.cn/Article/details/gt2crcmxubu.html

C#:   list.GetRange(1, 3);
来源：http://dali.vqdsnc.cn/Article/details/gt2kxvitvrq.html

[D08] 合并两个数组
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wlpwtmin.html

Py:   a + b;  a.extend(b)
来源：http://dali.xinyue.icu/Article/details/gt2qeldnlvy.html

PHP:  array_merge($a, $b);
来源：http://dali.shuidangran.top/Article/details/gt2ulrjrfpa.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xinyue.icu/Article/details/gt2kycdnrli.html

TS:   [...a, ...b];
来源：http://dali.guannengcc.top/Article/details/gt2pwsaltvs.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zwjriisx.html

Go:   append(a, b...)
来源：http://dali.zhiwuduotai.top/Article/details/gt2aagdnkjv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sufxvd.cn/Article/details/gt2eqxtmxtn.html

C#:   a.Concat(b).ToList()
来源：http://dali.316326.xyz/Article/details/gt2lsiwddhu.html

[D09] 排序（升序）
来源：http://dali.daxiang520.top/Article/details/gt2mxutavfe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sxryk.cn/Article/details/gt2idokfajx.html

PHP:  sort($arr);
来源：http://dali.fengsongda.top/Article/details/gt2qootngmv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gotoacloud.top/Article/details/gt2rbontuxh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.316326.xyz/Article/details/gt2qdotsccz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.fengsongda.top/Article/details/gt2kvjtdnwb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2kagcrhou.html

Ruby: arr.sort
来源：http://dali.wangdashe.top/Article/details/gt2zdgftkwy.html

C#:   list.Sort();
来源：http://dali.zhiwuduotai.top/Article/details/gt2yzxgtiqo.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.meibo888.top/Article/details/gt2xvvggcdm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.316326.xyz/Article/details/gt2gyosujbn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hnqzz.top/Article/details/gt2bzddzpuf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xylfe.cn/Article/details/gt2senapulp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zdqjudy.top/Article/details/gt2fhtzxunx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yvedp.cn/Article/details/gt2fgphjsiu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.wangshuangyany.cn/Article/details/gt2zvtwpjbu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ivvv.top/Article/details/gt2hymhcrjo.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ivvv.top/Article/details/gt2kavyuxvn.html

[D11] 反转数组
来源：http://dali.gotoacloud.top/Article/details/gt2kilobehd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.iojbl.cn/Article/details/gt2nfuiwlnv.html

PHP:  array_reverse($arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2eroqvpvb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yj20258888.top/Article/details/gt2fiuickze.html

TS:   [...arr].reverse();
来源：http://dali.sxryk.cn/Article/details/gt2msuxtmqh.html

Java: Collections.reverse(list);
来源：http://dali.chenzaomai.com/Article/details/gt2dpgxjvjj.html

Go:   slices.Reverse(arr)
来源：http://dali.andypj.xyz/Article/details/gt2xtshpsle.html

Ruby: arr.reverse
来源：http://dali.jinqigufen.top/Article/details/gt2ehyaccpu.html

C#:   list.Reverse();
来源：http://dali.yj20258.top/Article/details/gt2sdzzxrwo.html

[D12] 查找元素下标
来源：http://dali.zhixingplan.top/Article/details/gt2ytbavikr.html

Py:   arr.index(x);  x in arr
来源：http://dali.cucudq.cn/Article/details/gt2ewyngeoa.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.meibo888.top/Article/details/gt2hymjprht.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sxryk.cn/Article/details/gt2oyndxjjz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenzaomai.com/Article/details/gt2foepeltk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yanxiufei.cn/Article/details/gt2rjatohev.html

Go:   slices.Index(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gt2oielxsgr.html

Ruby: arr.index(x)
来源：http://dali.cashguo.top/Article/details/gt2jixnikro.html

C#:   list.IndexOf(x);
来源：http://dali.shzxlz.cn/Article/details/gt2fezuownw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhongyouzk.top/Article/details/gt2darfpkbb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yuxekrku.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cucudq.cn/Article/details/gt2dpbklxos.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ukkzdnnd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.c1oappe.top/Article/details/gt2xebdtbub.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nanxuanxn.top/Article/details/gt2dxoetoct.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinqigfzy.top/Article/details/gt2bpywzyuc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yuanzhike.top/Article/details/gt2wmjheerr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hysaishi.cn/Article/details/gt2qqhxnddm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.daxiang520.top/Article/details/gt2itrmlsbv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.aizwys.cn/Article/details/gt2avyomjwc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2vngfagfm.html

JS:   arr.map(x => x * 2)
来源：http://dali.cashguo.top/Article/details/gt2ynsnylyf.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2gjafyamo.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2gfoqahwb.html

Go:   // 手写循环
来源：http://dali.shuidangran.top/Article/details/gt2slvwtqwc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.snrcjt.cn/Article/details/gt2xhbxbyed.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2rhtamgty.html

[D15] 去重
来源：http://dali.smart0.xyz/Article/details/gt2rpnfqzmh.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ydzc1.top/Article/details/gt2vrbfflyu.html

PHP:  array_unique($arr);
来源：http://dali.fengsongda.top/Article/details/gt2djzaujts.html

JS:   [...new Set(arr)]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qqprylve.html

TS:   [...new Set(arr)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ifmipokr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.0kj1m.cn/Article/details/gt2wcismljv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ivvv.top/Article/details/gt2tgndmodl.html

Ruby: arr.uniq
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bhkhasuk.html

C#:   list.Distinct().ToList()
来源：http://dali.snrcjt.cn/Article/details/gt2nssukkce.html

[D16] 求和与平均值
来源：http://dali.bjfxy.top/Article/details/gt2kpijrchv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gzhubu.top/Article/details/gt2xkolfjaa.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shuidangran.top/Article/details/gt2raggaeip.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.snrcjt.cn/Article/details/gt2apwwbbyf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gzhubu.top/Article/details/gt2jmoygsob.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ljzlebgd.html

Go:   // 手写循环累加
来源：http://dali.hywenlv.cn/Article/details/gt2zfhxfckg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jyoumei.cn/Article/details/gt2ovaoqdso.html

C#:   list.Sum();  list.Average()
来源：http://dali.316326.xyz/Article/details/gt2epuoigww.html

[D17] 最大值与最小值
来源：http://dali.mhx1999.top/Article/details/gt2ypfsfimo.html

Py:   max(arr);  min(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mjmqxxhz.html

PHP:  max($arr);  min($arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2koamotkz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ybcxt.top/Article/details/gt2efxncslk.html

TS:   Math.max(...arr);
来源：http://dali.birdmap.top/Article/details/gt2llsfyxbo.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.pengpengdd.cyou/Article/details/gt2yltihvbc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tujexhpm.html

Ruby: arr.max;  arr.min
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ohsndqsv.html

C#:   list.Max();  list.Min()
来源：http://dali.zycfv.cn/Article/details/gt2czbwacgx.html

[D18] 扁平化嵌套数组
来源：http://dali.mhx1999.top/Article/details/gt2yritypoy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tianlin.xyz/Article/details/gt2egtacqdz.html

PHP:  array_merge(...$nested);
来源：http://dali.chenzaomai.com/Article/details/gt2lvdrohcy.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.daria6918.cn/Article/details/gt2ehrtutva.html

TS:   nested.flat();
来源：http://dali.jiagoushi.top/Article/details/gt2ahrqpfin.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hfpthk.cn/Article/details/gt2zgfopoeq.html

Go:   // 手写双层循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mftjetdf.html

Ruby: nested.flatten
来源：http://dali.tianlin.xyz/Article/details/gt2deczelut.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cqqwz.cn/Article/details/gt2etsyjapk.html

[D19] 按字段分组
来源：http://dali.smart0.xyz/Article/details/gt2lasesgpv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.aibaodan.cn/Article/details/gt2vjqxabpf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.chenzaomai.com/Article/details/gt2ncwjskrc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ivvv.top/Article/details/gt2mcwqbzcj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.smart0.xyz/Article/details/gt2iomufslc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.daxiang520.top/Article/details/gt2uspdydgs.html

Go:   // 手写 map[string][]T
来源：http://dali.sweek.top/Article/details/gt2umqiupzt.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.birdmap.top/Article/details/gt2gqurxoub.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.feifeiyinyue.top/Article/details/gt2ysjgrrsn.html

[D20] 统计每个元素出现次数
来源：http://dali.snrcjt.cn/Article/details/gt2fuaqcywy.html

Py:   Counter(arr)
来源：http://dali.zycfv.cn/Article/details/gt2okahjswh.html

PHP:  array_count_values($arr);
来源：http://dali.gogol.net.cn/Article/details/gt2cibogldr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258.top/Article/details/gt2nfdlbxxm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cheryme.top/Article/details/gt2mxwoakxf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xuetiantiany.cn/Article/details/gt2dqzgywrz.html

Go:   // 手写 map[T]int
来源：http://dali.xylfe.cn/Article/details/gt2rdrcpzoa.html

Ruby: arr.tally
来源：http://dali.jinqigfzy.top/Article/details/gt2nohkxvbg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.wangshuangyany.cn/Article/details/gt2crrsmjfi.html

[D21] 判断是否包含某元素
来源：http://dali.sufxvd.cn/Article/details/gt2apjvydke.html

Py:   x in arr
来源：http://dali.gogol.net.cn/Article/details/gt2sutgupza.html

PHP:  in_array($x, $arr, true);
来源：http://dali.daria6918.cn/Article/details/gt2akyljijh.html

JS:   arr.includes(x)
来源：http://dali.yueranfly.top/Article/details/gt2ucjslvjz.html

TS:   arr.includes(x)
来源：http://dali.cucudq.cn/Article/details/gt2xjbpsskb.html

Java: list.contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2mjimdfay.html

Go:   slices.Contains(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gt2onfwxwvg.html

Ruby: arr.include?(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vtkgmoyo.html

C#:   list.Contains(x)
来源：http://dali.316326.xyz/Article/details/gt2zrpathgn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.bjfxy.top/Article/details/gt2vppocucz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yuxming.cn/Article/details/gt2ifmvalov.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jqgufenzy.top/Article/details/gt2psbxxmlb.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.c1oappe.top/Article/details/gt2tevbiihx.html

TS:   [...arr];
来源：http://dali.yanxiufei.cn/Article/details/gt2obebgqnf.html

Java: new ArrayList<>(list);
来源：http://dali.cashguo.top/Article/details/gt2scfqyohr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sweek.top/Article/details/gt2dvqvcdkk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ehwqpu.com/Article/details/gt2qyxygzqq.html

C#:   new List<int>(list);
来源：http://dali.birdmap.top/Article/details/gt2kgjnbknc.html

[D23] reduce 累积计算
来源：http://dali.316326.xyz/Article/details/gt2pkyisebu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jiagoushi.top/Article/details/gt2jgkdpffz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gswegqhd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jlsjyb.cn/Article/details/gt2wfmuesgs.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cheryme.top/Article/details/gt2wecgcqzo.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.c1oappe.top/Article/details/gt2hxqxkreo.html

Go:   // 手写循环
来源：http://dali.aizwys.cn/Article/details/gt2gelaylzh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.vqdsnc.cn/Article/details/gt2eliizonp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.daria6918.cn/Article/details/gt2nqgzwptf.html

[D24] 字典 / Map 基本操作
来源：http://dali.zdqjudy.top/Article/details/gt2pqsvidoi.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.feifeiyinyue.top/Article/details/gt2pzsycwvz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jiagoushi.top/Article/details/gt2mwwjzmnt.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xinyue.icu/Article/details/gt2fczodbco.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zycfv.cn/Article/details/gt2hjnfqrig.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yj202588.top/Article/details/gt2sggpwveo.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hjkdldhw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2baqjwwfs.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gotoacloud.top/Article/details/gt2koujakml.html

[D25] Set 集合去重与交并差
来源：http://dali.9152youxi.cn/Article/details/gt2pnkckerj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xinyue.icu/Article/details/gt2gavlskjj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.nanxinkj.top/Article/details/gt2gcckwiin.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.andypj.xyz/Article/details/gt2mulmfaqz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ehwqpu.com/Article/details/gt2kzminagu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.daxiang520.top/Article/details/gt2fkbppmlv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yj20258.top/Article/details/gt2qngjladk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.aibaodan.cn/Article/details/gt2igikwauh.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pezmgvfe.html

[D26] 数组转字符串
来源：http://dali.yueranfly.top/Article/details/gt2rvuizvti.html

Py:   ", ".join(map(str, arr))
来源：http://dali.quarkkingdee.top/Article/details/gt2mmdjudij.html

PHP:  implode(", ", $arr);
来源：http://dali.iojbl.cn/Article/details/gt2xwdmjvnz.html

JS:   arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gt2nvfhisjs.html

TS:   arr.join(", ")
来源：http://dali.ppjwa.cn/Article/details/gt2gqtjecal.html

Java: String.join(", ", list)
来源：http://dali.9152youxi.cn/Article/details/gt2gkizdaus.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yongpay.top/Article/details/gt2getagiqi.html

Ruby: arr.join(", ")
来源：http://dali.nanxinkj.top/Article/details/gt2xmeurfrd.html

C#:   string.Join(", ", list)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qkrfcgig.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2bnjokgrc.html

E. 字符串处理
来源：http://dali.vqdsnc.cn/Article/details/gt2ndhggqjt.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2wzcwezps.html

[E01] 拼接字符串
来源：http://dali.ydzc1.top/Article/details/gt2ygbsiqfq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.nwbrower.top/Article/details/gt2otrkpwkr.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jiagoushi.top/Article/details/gt2aczawsda.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuanzx.com/Article/details/gt2fwnbfhpy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuxming.cn/Article/details/gt2ynmsdacp.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2qnewmjbd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.mhx1999.top/Article/details/gt2dragencz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xylfe.cn/Article/details/gt2mocdevrm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gt2ygjmoubw.html

[E02] 重复字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2twqdmllj.html

Py:   "ab" * 3
来源：http://dali.gogol.net.cn/Article/details/gt2ylirjgij.html

PHP:  str_repeat("ab", 3);
来源：http://dali.snrcjt.cn/Article/details/gt2jvaffqtm.html

JS:   "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gt2hewscsun.html

TS:   "ab".repeat(3)
来源：http://dali.jianghu66.top/Article/details/gt2qkryxkxi.html

Java: "ab".repeat(3)
来源：http://dali.wangdashe.top/Article/details/gt2mepudxvw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2afqultuq.html

Ruby: "ab" * 3
来源：http://dali.nwbrower.top/Article/details/gt2jykarsvm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.haohaochexian.top/Article/details/gt2kilsvrni.html

[E03] 截取子串
来源：http://dali.guowangkeji.top/Article/details/gt2yysnvyiu.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.pycfn.com/Article/details/gt2wxsbqbjk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gt2dnfufwiy.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.pycfn.com/Article/details/gt2gtutcbvr.html

TS:   s.slice(1, 4)
来源：http://dali.jinqigufen.top/Article/details/gt2krezzfxz.html

Java: s.substring(1, 4)
来源：http://dali.bjfxy.top/Article/details/gt2jevpzdqf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.mhx1999.top/Article/details/gt2bxluxpif.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.mhx1999.top/Article/details/gt2ylioivua.html

C#:   s.Substring(1, 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ksxqockq.html

[E04] 查找子串位置
来源：http://dali.yueranfly.top/Article/details/gt2yncqgxwa.html

Py:   s.find("x");  s.index("x")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ymypiclv.html

PHP:  strpos($s, "x");
来源：http://dali.aizwys.cn/Article/details/gt2zefepaxi.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xziqi.cn/Article/details/gt2bgwyleug.html

TS:   s.indexOf("x")
来源：http://dali.yongpay.top/Article/details/gt2egugnazg.html

Java: s.indexOf("x")
来源：http://dali.jiagoushi.top/Article/details/gt2zozvrwtm.html

Go:   strings.Index(s, "x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hoyckcbx.html

Ruby: s.index("x")
来源：http://dali.bjfxy.top/Article/details/gt2cdlcftcl.html

C#:   s.IndexOf("x")
来源：http://dali.sufxvd.cn/Article/details/gt2yqdkwqlb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hammf.cn/Article/details/gt2irxctlul.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj202588.top/Article/details/gt2ltkethrj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.chenlongwang.top/Article/details/gt2exlutggn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigfzy.top/Article/details/gt2zycplsuv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hnqzz.top/Article/details/gt2vuqxbppz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.guannengcc.top/Article/details/gt2jeujewok.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.mhx1999.top/Article/details/gt2sckqdxbs.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.316326.xyz/Article/details/gt2zsnfjvxw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhoulong.xyz/Article/details/gt2nlyayhoh.html

[E06] 替换子串
来源：http://dali.nanxinkj.top/Article/details/gt2oyacprtp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.dianchejie.cn/Article/details/gt2bbexikkf.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhengqikj.top/Article/details/gt2dqxxwoli.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xylfe.cn/Article/details/gt2jofiuynp.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gt2kfjzpcud.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gt2nbdjgxig.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.guowangkeji.top/Article/details/gt2vcfyyswl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gt2jhvgelhp.html

C#:   s.Replace("a", "b")
来源：http://dali.birdmap.top/Article/details/gt2jcaqjifo.html

[E07] 按分隔符拆分
来源：http://dali.sysykeji.top/Article/details/gt2vebftfrz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hongshengwenyu.top/Article/details/gt2zjvreeep.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.0kj1m.cn/Article/details/gt2wpmcxgnw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.tian-w.cn/Article/details/gt2tsswoqyy.html

TS:   s.split(",")
来源：http://dali.ivvv.top/Article/details/gt2pjvvchcb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.nwbrower.top/Article/details/gt2psmnbwoq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wjxilhig.html

Ruby: s.split(",");  s.split
来源：http://dali.ybcxt.top/Article/details/gt2fviihify.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xuanzx.com/Article/details/gt2jelieubg.html

[E08] 数组按分隔符合并
来源：http://dali.ehwqpu.com/Article/details/gt2vcozvjvd.html

Py:   ",".join(items)
来源：http://dali.ehwqpu.com/Article/details/gt2cdaeuoge.html

PHP:  implode(",", $items);
来源：http://dali.hnqzz.top/Article/details/gt2gecgaacg.html

JS:   items.join(",")
来源：http://dali.bjfxy.top/Article/details/gt2dulqswqn.html

TS:   items.join(",")
来源：http://dali.quarkkingdee.top/Article/details/gt2msnetuhh.html

Java: String.join(",", items)
来源：http://dali.zhoulong.xyz/Article/details/gt2pzgmepvg.html

Go:   strings.Join(items, ",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2blankppg.html

Ruby: items.join(",")
来源：http://dali.sufxvd.cn/Article/details/gt2ratuykzg.html

C#:   string.Join(",", items)
来源：http://dali.yongpay.top/Article/details/gt2iugudgou.html

[E09] 去除所有空白字符
来源：http://dali.shangyingyoupin.top/Article/details/gt2wnfcscwm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.chenzaomai.com/Article/details/gt2jqaooaaj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.aibaodan.cn/Article/details/gt2gwdayktj.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.9152youxi.cn/Article/details/gt2fygxqbra.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.bjfxy.top/Article/details/gt2mleftqgx.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gogol.net.cn/Article/details/gt2ummzumvj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.bjfxy.top/Article/details/gt2tdukmmvj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.9152youxi.cn/Article/details/gt2oujfhnzk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xuetiantiany.cn/Article/details/gt2nbckaxyo.html

[E10] 左侧补零 / 定长填充
来源：http://dali.pengpengdd.cyou/Article/details/gt2kjaesiic.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gt2pniaifbi.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenlongwang.top/Article/details/gt2xnaukrbd.html

JS:   "7".padStart(3, "0")
来源：http://dali.yongpay.top/Article/details/gt2zoiksfay.html

TS:   "7".padStart(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gt2lrrevaul.html

Java: String.format("%03d", 7)
来源：http://dali.c1oappe.top/Article/details/gt2nmuhqisb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sweek.top/Article/details/gt2ryyhgqrb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinqigfzy.top/Article/details/gt2fhvcybwj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qsbbrufd.html

[E11] 反转字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2ubhrdtxj.html

Py:   s[::-1]
来源：http://dali.guannengcc.top/Article/details/gt2nqmmtmtj.html

PHP:  strrev($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iwuwfaow.html

JS:   [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gt2fpupovwi.html

TS:   [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gt2wsoboujy.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hnxiangtu.top/Article/details/gt2xrtxltdq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.daxiang520.top/Article/details/gt2tjpxvuim.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2evieyagc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.havefunace.top/Article/details/gt2ytzkafsk.html

[E12] 统计某字符出现次数
来源：http://dali.pengpengdd.cyou/Article/details/gt2ymlmfcml.html

Py:   s.count("a")
来源：http://dali.cheryme.top/Article/details/gt2ureanywe.html

PHP:  substr_count($s, "a");
来源：http://dali.svipenyu.cn/Article/details/gt2apwzvqzc.html

JS:   s.split("a").length - 1
来源：http://dali.ppjwa.cn/Article/details/gt2dqdtpwzq.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbjeloz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.0kj1m.cn/Article/details/gt2fsjazvpt.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtgmqum.html

Ruby: s.count("a")
来源：http://dali.bjfxy.top/Article/details/gt2tpyiyvth.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hysaishi.cn/Article/details/gt2betkmwdp.html

[E13] 逐字符遍历
来源：http://dali.zhiwuduotai.top/Article/details/gt2tiirydgk.html


<!-- 参考信息 -->