代发 wailian999

Java: list.size();
来源：http://dali.sysykeji.top/Article/details/gt2eeygxeuh.html

Go:   len(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2neunbbaf.html

Ruby: arr.length; arr.size
来源：http://dali.svipenyu.cn/Article/details/gt2grlkbjtk.html

C#:   list.Count;
来源：http://dali.ydzc1.top/Article/details/gt2nvzasryx.html

[D07] 切片 / 取子数组
来源：http://dali.jqgufenzy.top/Article/details/gt2dzocsylf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yanxiufei.cn/Article/details/gt2einmrxrx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.nwbrower.top/Article/details/gt2gzsdrovf.html

JS:   arr.slice(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gt2vhswscqq.html

TS:   arr.slice(1, 4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zigsluov.html

Java: list.subList(1, 4);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ytzuaofc.html

Go:   arr[1:4]
来源：http://dali.hnqzz.top/Article/details/gt2ldryczcl.html

Ruby: arr[1, 3]
来源：http://dali.hnxiangtu.top/Article/details/gt2wvaieurh.html

C#:   list.GetRange(1, 3);
来源：http://dali.jlsjyb.cn/Article/details/gt2rokehuac.html

[D08] 合并两个数组
来源：http://dali.iojbl.cn/Article/details/gt2bwjkbskp.html

Py:   a + b;  a.extend(b)
来源：http://dali.cheryme.top/Article/details/gt2vtjwbcpv.html

PHP:  array_merge($a, $b);
来源：http://dali.jqgfzy.top/Article/details/gt2cimrastk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cucudq.cn/Article/details/gt2ouowztjm.html

TS:   [...a, ...b];
来源：http://dali.daria6918.cn/Article/details/gt2unhczikd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.aibaodan.cn/Article/details/gt2tqrhgutt.html

Go:   append(a, b...)
来源：http://dali.jlsjyb.cn/Article/details/gt2kqjffsrz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jqgufenzy.top/Article/details/gt2shpukhze.html

C#:   a.Concat(b).ToList()
来源：http://dali.snrcjt.cn/Article/details/gt2nuzshixo.html

[D09] 排序（升序）
来源：http://dali.fengsongda.top/Article/details/gt2laugcwrl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gaohongyu789.top/Article/details/gt2odtakqzm.html

PHP:  sort($arr);
来源：http://dali.xylfe.cn/Article/details/gt2oodjexek.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hbtnaykq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.daria6918.cn/Article/details/gt2jrviwjof.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yvedp.cn/Article/details/gt2ylsvuxjd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2jiiizsam.html

Ruby: arr.sort
来源：http://dali.daria6918.cn/Article/details/gt2sjrfyung.html

C#:   list.Sort();
来源：http://dali.sysykeji.top/Article/details/gt2mrypzpsx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cheryme.top/Article/details/gt2vjbyslxh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hnqzz.top/Article/details/gt2rjvwfkbh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yangfankeji.com/Article/details/gt2wrpuanpt.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xtmvbsjx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnsfbvhs.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xylfe.cn/Article/details/gt2zegktmka.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.guowangkeji.top/Article/details/gt2jimfydor.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.chenzaomai.com/Article/details/gt2gzlthzhg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shangyingyoupin.top/Article/details/gt2kfymjoew.html

[D11] 反转数组
来源：http://dali.shzxlz.cn/Article/details/gt2dlcczspy.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.wangshuangyany.cn/Article/details/gt2wkxheggp.html

PHP:  array_reverse($arr);
来源：http://dali.snrcjt.cn/Article/details/gt2mkudrrhb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yueranfly.top/Article/details/gt2zrozrppr.html

TS:   [...arr].reverse();
来源：http://dali.mhx1999.top/Article/details/gt2bqtxviic.html

Java: Collections.reverse(list);
来源：http://dali.vqdsnc.cn/Article/details/gt2cbtkskzf.html

Go:   slices.Reverse(arr)
来源：http://dali.c1oappe.top/Article/details/gt2rbzfznqk.html

Ruby: arr.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yvvajrga.html

C#:   list.Reverse();
来源：http://dali.yanxiufei.cn/Article/details/gt2yukiunsc.html

[D12] 查找元素下标
来源：http://dali.nwbrower.top/Article/details/gt2hqoltzdn.html

Py:   arr.index(x);  x in arr
来源：http://dali.hammf.cn/Article/details/gt2qjogsbia.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zycfv.cn/Article/details/gt2ejmsjsds.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.kuanghao11.cn/Article/details/gt2lukzadnm.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhongyouzk.top/Article/details/gt2udepfyih.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ivvv.top/Article/details/gt2eumousoy.html

Go:   slices.Index(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tphbluzr.html

Ruby: arr.index(x)
来源：http://dali.jinqigufen.top/Article/details/gt2yamdvmzp.html

C#:   list.IndexOf(x);
来源：http://dali.ppjwa.cn/Article/details/gt2mwhhymto.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iblhztfo.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xuanzx.com/Article/details/gt2qegjypxv.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gzhubu.top/Article/details/gt2rjhxncyq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hnxiangtu.top/Article/details/gt2cqthlzdv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.wangdashe.top/Article/details/gt2atpbamvn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.wangdashe.top/Article/details/gt2pyfxtqhz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhengqikj.top/Article/details/gt2bodpxeac.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinqigfzy.top/Article/details/gt2aedebbqg.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj20258.top/Article/details/gt2ijtlyixl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhixingplan.top/Article/details/gt2vpjmhnwa.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yj20258888.top/Article/details/gt2xgypllfl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yonumen.top/Article/details/gt2xgerynzo.html

JS:   arr.map(x => x * 2)
来源：http://dali.c1oappe.top/Article/details/gt2zvmednbr.html

TS:   arr.map(x => x * 2)
来源：http://dali.gogol.net.cn/Article/details/gt2aqwclsfj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hammf.cn/Article/details/gt2icibkylf.html

Go:   // 手写循环
来源：http://dali.gotoacloud.top/Article/details/gt2vilwkyvk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2rtzdrqle.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.daxiang520.top/Article/details/gt2ellmvkxy.html

[D15] 去重
来源：http://dali.haohaochexian.top/Article/details/gt2lkxunsgd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gzhubu.top/Article/details/gt2qlzetmmv.html

PHP:  array_unique($arr);
来源：http://dali.havefunace.top/Article/details/gt2tiervrns.html

JS:   [...new Set(arr)]
来源：http://dali.nanxuanxn.top/Article/details/gt2nenjqorc.html

TS:   [...new Set(arr)]
来源：http://dali.aibaodan.cn/Article/details/gt2irbxhpsm.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.aizwys.cn/Article/details/gt2lofyhbnv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.0kj1m.cn/Article/details/gt2hmdzefde.html

Ruby: arr.uniq
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sexyjqwe.html

C#:   list.Distinct().ToList()
来源：http://dali.yangfankeji.com/Article/details/gt2svzatzqa.html

[D16] 求和与平均值
来源：http://dali.9152youxi.cn/Article/details/gt2yuifbldg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2lkfgaivk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.sufxvd.cn/Article/details/gt2vbnsdoov.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gt2mbqzfdtc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.iojbl.cn/Article/details/gt2jukmbdnu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhengqikj.top/Article/details/gt2zwfmdqjp.html

Go:   // 手写循环累加
来源：http://dali.hammf.cn/Article/details/gt2upbhyggd.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hfpthk.cn/Article/details/gt2qesnzyxj.html

C#:   list.Sum();  list.Average()
来源：http://dali.yuanzhike.top/Article/details/gt2dqohsybo.html

[D17] 最大值与最小值
来源：http://dali.zhongyouzk.top/Article/details/gt2ysejeywo.html

Py:   max(arr);  min(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2zvvomfsh.html

PHP:  max($arr);  min($arr);
来源：http://dali.hammf.cn/Article/details/gt2focpicbo.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hguljveq.html

TS:   Math.max(...arr);
来源：http://dali.chenlongwang.top/Article/details/gt2msxtsjnv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yj202588.top/Article/details/gt2irlywmtr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2tkrltees.html

Ruby: arr.max;  arr.min
来源：http://dali.tian-w.cn/Article/details/gt2svgsnqth.html

C#:   list.Max();  list.Min()
来源：http://dali.vqdsnc.cn/Article/details/gt2xcrjnttz.html

[D18] 扁平化嵌套数组
来源：http://dali.jlsjyb.cn/Article/details/gt2dzpcqmxm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sweek.top/Article/details/gt2csdzxodf.html

PHP:  array_merge(...$nested);
来源：http://dali.meibo888.top/Article/details/gt2usmbmtps.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zbzihwvn.html

TS:   nested.flat();
来源：http://dali.316326.xyz/Article/details/gt2avljmbcp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yj20258.top/Article/details/gt2bsrkhcbb.html

Go:   // 手写双层循环
来源：http://dali.smart0.xyz/Article/details/gt2jjjkxukp.html

Ruby: nested.flatten
来源：http://dali.daxiang520.top/Article/details/gt2dgghluhw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sufxvd.cn/Article/details/gt2qtpitrub.html

[D19] 按字段分组
来源：http://dali.dashuyun.cn/Article/details/gt2jmnwrsdm.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.mhx1999.top/Article/details/gt2dobpkcni.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hnxiangtu.top/Article/details/gt2lboitfwl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.0kj1m.cn/Article/details/gt2wazmgpes.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.birdmap.top/Article/details/gt2xcwckobj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.pycfn.com/Article/details/gt2tndgvegr.html

Go:   // 手写 map[string][]T
来源：http://dali.zhixingplan.top/Article/details/gt2ozjylfki.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cqqwz.cn/Article/details/gt2saqqtwrc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hongshengwenyu.top/Article/details/gt2klrbsihu.html

[D20] 统计每个元素出现次数
来源：http://dali.jqgfzy.top/Article/details/gt2nitfbwfi.html

Py:   Counter(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2exmrgemr.html

PHP:  array_count_values($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2ffpjisuu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.andypj.xyz/Article/details/gt2kgflzpvm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.smart0.xyz/Article/details/gt2ciffqdtk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.daxiang520.top/Article/details/gt2etygaehw.html

Go:   // 手写 map[T]int
来源：http://dali.andypj.xyz/Article/details/gt2ugjotysr.html

Ruby: arr.tally
来源：http://dali.smart0.xyz/Article/details/gt2edzkghhe.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uzpoovma.html

[D21] 判断是否包含某元素
来源：http://dali.yuxming.cn/Article/details/gt2bznpwymn.html

Py:   x in arr
来源：http://dali.guannengcc.top/Article/details/gt2kwgkrltx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xuanzx.com/Article/details/gt2jfxwwyxt.html

JS:   arr.includes(x)
来源：http://dali.tian-w.cn/Article/details/gt2plxciiid.html

TS:   arr.includes(x)
来源：http://dali.dianchejie.cn/Article/details/gt2utgyqxrj.html

Java: list.contains(x)
来源：http://dali.fengsongda.top/Article/details/gt2mjajlmyi.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gt2ldrkpnus.html

Ruby: arr.include?(x)
来源：http://dali.jqgfzy.top/Article/details/gt2zisxlqus.html

C#:   list.Contains(x)
来源：http://dali.chenlongwang.top/Article/details/gt2qkvmjvrh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.wangshuangyany.cn/Article/details/gt2aouctccp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yuxming.cn/Article/details/gt2bozdzpqe.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.aizwys.cn/Article/details/gt2szxsaidg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2znzkghzy.html

TS:   [...arr];
来源：http://dali.yanxiufei.cn/Article/details/gt2gyrtlryf.html

Java: new ArrayList<>(list);
来源：http://dali.hammf.cn/Article/details/gt2dbtzltfo.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.meibo888.top/Article/details/gt2suceywtx.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cucudq.cn/Article/details/gt2typqsnpx.html

C#:   new List<int>(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2djtinaeo.html

[D23] reduce 累积计算
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ikcjukcs.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mvbyrcre.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hywenlv.cn/Article/details/gt2wkqyhbyd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sxryk.cn/Article/details/gt2bqaisiaf.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.andypj.xyz/Article/details/gt2hetncrtz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pmyecibz.html

Go:   // 手写循环
来源：http://dali.redwolf501.top/Article/details/gt2romgukyo.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xziqi.cn/Article/details/gt2aspivybl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.daxiang520.top/Article/details/gt2udpzcsdx.html

[D24] 字典 / Map 基本操作
来源：http://dali.xuetiantiany.cn/Article/details/gt2gvbxtums.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.guowangkeji.top/Article/details/gt2egjdlrce.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ffyyjguh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hammf.cn/Article/details/gt2ckplufff.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gt2nmaagvjn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.guowangkeji.top/Article/details/gt2wcathxbb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.wangdashe.top/Article/details/gt2jeuurhft.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xuanzx.com/Article/details/gt2jcfzyzpq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jqgufenzy.top/Article/details/gt2jtbwztwp.html

[D25] Set 集合去重与交并差
来源：http://dali.tian-w.cn/Article/details/gt2vxwbycrs.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yongpay.top/Article/details/gt2gyccmauk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hammf.cn/Article/details/gt2akxipixi.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.redwolf501.top/Article/details/gt2qxomqykr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cqqwz.cn/Article/details/gt2nrpuwxpu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gogol.net.cn/Article/details/gt2ilhqcato.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.quarkkingdee.top/Article/details/gt2dfnivsvl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shuidangran.top/Article/details/gt2uldkdnmu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yonumen.top/Article/details/gt2vuphozmu.html

[D26] 数组转字符串
来源：http://dali.sysykeji.top/Article/details/gt2fgxbmhyt.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gaohongyu789.top/Article/details/gt2hemkqkcv.html

PHP:  implode(", ", $arr);
来源：http://dali.yangfankeji.com/Article/details/gt2krqlodpt.html

JS:   arr.join(", ")
来源：http://dali.9152youxi.cn/Article/details/gt2hqazyvul.html

TS:   arr.join(", ")
来源：http://dali.nanxuanxn.top/Article/details/gt2qlntamyg.html

Java: String.join(", ", list)
来源：http://dali.pycfn.com/Article/details/gt2xwkafcna.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhengqikj.top/Article/details/gt2wwrkwmnu.html

Ruby: arr.join(", ")
来源：http://dali.snrcjt.cn/Article/details/gt2lxmvaqqn.html

C#:   string.Join(", ", list)
来源：http://dali.zdqjudy.top/Article/details/gt2cuxpxynq.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2mbuooldp.html

E. 字符串处理
来源：http://dali.9152youxi.cn/Article/details/gt2cmhznnak.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2lbmkxelq.html

[E01] 拼接字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lboaqsph.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gogol.net.cn/Article/details/gt2irzmqcoj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ydzc1.top/Article/details/gt2ddubmbxo.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jiagoushi.top/Article/details/gt2qmuafupi.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qyourldb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gogol.net.cn/Article/details/gt2qnmugrha.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.mhx1999.top/Article/details/gt2lmepbrxx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sweek.top/Article/details/gt2wuzmhydu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gt2hdacdcue.html

[E02] 重复字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2baysfzcp.html

Py:   "ab" * 3
来源：http://dali.zhengqikj.top/Article/details/gt2cerbycba.html

PHP:  str_repeat("ab", 3);
来源：http://dali.tanke756.top/Article/details/gt2buiglbji.html

JS:   "ab".repeat(3)
来源：http://dali.yangfankeji.com/Article/details/gt2yvlwtthf.html

TS:   "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gt2uagwlhag.html

Java: "ab".repeat(3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2timvykcf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.svipenyu.cn/Article/details/gt2itafqmtm.html

Ruby: "ab" * 3
来源：http://dali.pengpengdd.cyou/Article/details/gt2vhvsnupt.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gotoacloud.top/Article/details/gt2jsobiggm.html

[E03] 截取子串
来源：http://dali.quarkkingdee.top/Article/details/gt2hqopeffs.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhoulong.xyz/Article/details/gt2zvscontu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gt2kaiosdcl.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jyoumei.cn/Article/details/gt2oteusyeu.html

TS:   s.slice(1, 4)
来源：http://dali.shuidangran.top/Article/details/gt2kmekxaug.html

Java: s.substring(1, 4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yqphlqji.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.nanxinkj.top/Article/details/gt2wfekypmk.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sufxvd.cn/Article/details/gt2inadgeof.html

C#:   s.Substring(1, 3)
来源：http://dali.yanxiufei.cn/Article/details/gt2kylejapp.html

[E04] 查找子串位置
来源：http://dali.zhoulong.xyz/Article/details/gt2vwivoafl.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hywenlv.cn/Article/details/gt2dkkupurt.html

PHP:  strpos($s, "x");
来源：http://dali.feifeiyinyue.top/Article/details/gt2hmrpuler.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.daxiang520.top/Article/details/gt2fauiulom.html

TS:   s.indexOf("x")
来源：http://dali.guannengcc.top/Article/details/gt2wiclvraz.html

Java: s.indexOf("x")
来源：http://dali.xuetiantiany.cn/Article/details/gt2uzlmjssw.html

Go:   strings.Index(s, "x")
来源：http://dali.aibaodan.cn/Article/details/gt2dopeodjm.html

Ruby: s.index("x")
来源：http://dali.jlsjyb.cn/Article/details/gt2hckwwtzh.html

C#:   s.IndexOf("x")
来源：http://dali.xuanzx.com/Article/details/gt2gwanxhtb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.feifeiyinyue.top/Article/details/gt2erpnyzik.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.nanxinkj.top/Article/details/gt2qjqadxwx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kqipqeaz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fzhhl.top/Article/details/gt2gawpveik.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.chenzaomai.com/Article/details/gt2uesoxtrg.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gt2xxtlqnqr.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.0kj1m.cn/Article/details/gt2jbvtgipn.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ujguypva.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xuanzx.com/Article/details/gt2jxftqvyc.html

[E06] 替换子串
来源：http://dali.yanxiufei.cn/Article/details/gt2ggclduui.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.birdmap.top/Article/details/gt2zfrozafk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gaohongyu789.top/Article/details/gt2rajboorm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gt2urthslhe.html

TS:   s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gt2qtadbssl.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gt2xzktavkc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hnqzz.top/Article/details/gt2bgutnega.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gt2yssllzhf.html

C#:   s.Replace("a", "b")
来源：http://dali.mhx1999.top/Article/details/gt2bvxmdviv.html

[E07] 按分隔符拆分
来源：http://dali.xziqi.cn/Article/details/gt2dxfchzfo.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yangfankeji.com/Article/details/gt2pxqvuirb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.havefunace.top/Article/details/gt2niwniuvo.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xinyue.icu/Article/details/gt2kqqbfmol.html

TS:   s.split(",")
来源：http://dali.svipenyu.cn/Article/details/gt2mlmwyemv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hywenlv.cn/Article/details/gt2scnjwyes.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hnqzz.top/Article/details/gt2qfihezxv.html

Ruby: s.split(",");  s.split
来源：http://dali.birdmap.top/Article/details/gt2hxrbtmts.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gfyzsxil.html

[E08] 数组按分隔符合并
来源：http://dali.xziqi.cn/Article/details/gt2lxtvfbgj.html

Py:   ",".join(items)
来源：http://dali.tian-w.cn/Article/details/gt2olppqofr.html

PHP:  implode(",", $items);
来源：http://dali.ppjwa.cn/Article/details/gt2rvewzxxk.html

JS:   items.join(",")
来源：http://dali.ivvv.top/Article/details/gt2cgcpshhv.html

TS:   items.join(",")
来源：http://dali.yueranfly.top/Article/details/gt2ubmopnho.html

Java: String.join(",", items)
来源：http://dali.hysaishi.cn/Article/details/gt2glbvdrtv.html

Go:   strings.Join(items, ",")
来源：http://dali.daria6918.cn/Article/details/gt2xybqacnr.html

Ruby: items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gt2raivafya.html

C#:   string.Join(",", items)
来源：http://dali.quarkkingdee.top/Article/details/gt2sahtugus.html

[E09] 去除所有空白字符
来源：http://dali.tanke756.top/Article/details/gt2aafsjnzl.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sweek.top/Article/details/gt2txcspype.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yvedp.cn/Article/details/gt2qndjitvy.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bpftpkmo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sufxvd.cn/Article/details/gt2tddzmcbh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gotoacloud.top/Article/details/gt2gimseqiy.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj202588.top/Article/details/gt2exzhozfa.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.316326.xyz/Article/details/gt2qogvkurp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cucudq.cn/Article/details/gt2ttvsxlit.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cheryme.top/Article/details/gt2odikecdn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gt2bvhxlykc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.316326.xyz/Article/details/gt2vhwcapgi.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gt2mdtmqouf.html

TS:   "7".padStart(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gt2wcxndrhm.html

Java: String.format("%03d", 7)
来源：http://dali.ivvv.top/Article/details/gt2soazfmmz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gt2ipqhkgrr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gt2trkkdsez.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sufxvd.cn/Article/details/gt2vnoitbjo.html

[E11] 反转字符串
来源：http://dali.xinyue.icu/Article/details/gt2tancuhzm.html

Py:   s[::-1]
来源：http://dali.gzhubu.top/Article/details/gt2zpgcqgin.html

PHP:  strrev($s);
来源：http://dali.9152youxi.cn/Article/details/gt2jjonqaiv.html

JS:   [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gt2otiehlfl.html

TS:   [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mrlyizme.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.guowangkeji.top/Article/details/gt2wetaspxv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xuetiantiany.cn/Article/details/gt2gzqeakbt.html

Ruby: s.reverse
来源：http://dali.shuidangran.top/Article/details/gt2vffuyqfw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hammf.cn/Article/details/gt2ppvvokwl.html

[E12] 统计某字符出现次数
来源：http://dali.hammf.cn/Article/details/gt2imwhydrz.html

Py:   s.count("a")
来源：http://dali.cucudq.cn/Article/details/gt2ozdibngz.html

PHP:  substr_count($s, "a");
来源：http://dali.redwolf501.top/Article/details/gt2iyqqvvcj.html

JS:   s.split("a").length - 1
来源：http://dali.tanke756.top/Article/details/gt2zhravkiz.html

TS:   s.split("a").length - 1
来源：http://dali.chenzaomai.com/Article/details/gt2lxvhutbr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yangfankeji.com/Article/details/gt2rnzohbcm.html

Go:   strings.Count(s, "a")
来源：http://dali.tianlin.xyz/Article/details/gt2rvqzdnpr.html

Ruby: s.count("a")
来源：http://dali.ehwqpu.com/Article/details/gt2cmerfrey.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gotoacloud.top/Article/details/gt2bovechlb.html

[E13] 逐字符遍历
来源：http://dali.smart0.xyz/Article/details/gt2sjufqnmg.html

Py:   for ch in s: print(ch)
来源：http://dali.cheryme.top/Article/details/gt2gmkmumrz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yuxming.cn/Article/details/gt2adamktmq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jiagoushi.top/Article/details/gt2hywzifve.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gt2vjfkfmzp.html


<!-- 参考信息 -->