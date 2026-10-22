代发 wailian999

C#:   list.GetRange(1, 3);
来源：http://dali.zycfv.cn/Article/details/gt2qkkdjnqp.html

[D08] 合并两个数组
来源：http://dali.pengpengdd.cyou/Article/details/gt2ahqvvybr.html

Py:   a + b;  a.extend(b)
来源：http://dali.sweek.top/Article/details/gt2oexrxfvf.html

PHP:  array_merge($a, $b);
来源：http://dali.iojbl.cn/Article/details/gt2dqqpbjlv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj202588.top/Article/details/gt2yctwaywx.html

TS:   [...a, ...b];
来源：http://dali.yanxiufei.cn/Article/details/gt2iaeyndlo.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.tianlin.xyz/Article/details/gt2mctniabs.html

Go:   append(a, b...)
来源：http://dali.jqgfzy.top/Article/details/gt2dzdyhglf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.svipenyu.cn/Article/details/gt2brmsocer.html

C#:   a.Concat(b).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gt2vzyzzgrp.html

[D09] 排序（升序）
来源：http://dali.fzhhl.top/Article/details/gt2dztbrczb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ipyfuslk.html

PHP:  sort($arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2woyjwqeg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yonumen.top/Article/details/gt2ebrbqlor.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sweek.top/Article/details/gt2iixqqcuy.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cqqwz.cn/Article/details/gt2xxyqveda.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2flphwult.html

Ruby: arr.sort
来源：http://dali.yueranfly.top/Article/details/gt2fzvqblrb.html

C#:   list.Sort();
来源：http://dali.jqgfzy.top/Article/details/gt2ncjujxpr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sxryk.cn/Article/details/gt2aittraxu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.pycfn.com/Article/details/gt2bujaiyja.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.kuanghao11.cn/Article/details/gt2nlkylvwu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sweek.top/Article/details/gt2kwraqxjl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nwbrower.top/Article/details/gt2epdwluol.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.havefunace.top/Article/details/gt2didjvboi.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenzaomai.com/Article/details/gt2schlgnqp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aghwyviy.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jqgufenzy.top/Article/details/gt2mtudruvf.html

[D11] 反转数组
来源：http://dali.wangshuangyany.cn/Article/details/gt2ifmcuvir.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cheryme.top/Article/details/gt2whuuugji.html

PHP:  array_reverse($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oziqrbeq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhengqikj.top/Article/details/gt2uapmyvol.html

TS:   [...arr].reverse();
来源：http://dali.hongshengwenyu.top/Article/details/gt2vnoknehh.html

Java: Collections.reverse(list);
来源：http://dali.meibo888.top/Article/details/gt2vyycihch.html

Go:   slices.Reverse(arr)
来源：http://dali.yj20258888.top/Article/details/gt2afprrftk.html

Ruby: arr.reverse
来源：http://dali.cqqwz.cn/Article/details/gt2wgmxqanm.html

C#:   list.Reverse();
来源：http://dali.ppjwa.cn/Article/details/gt2gimpnxny.html

[D12] 查找元素下标
来源：http://dali.shzxlz.cn/Article/details/gt2zcnzivgg.html

Py:   arr.index(x);  x in arr
来源：http://dali.xylfe.cn/Article/details/gt2vmviayvw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yvedp.cn/Article/details/gt2ibgsenqj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kphfvupy.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sysykeji.top/Article/details/gt2jtdyrfok.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pvauvdwi.html

Go:   slices.Index(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gt2yeowfelc.html

Ruby: arr.index(x)
来源：http://dali.daxiang520.top/Article/details/gt2btzjzgdb.html

C#:   list.IndexOf(x);
来源：http://dali.tianlin.xyz/Article/details/gt2dgmpbnua.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tanke756.top/Article/details/gt2vrmokhdk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.pycfn.com/Article/details/gt2vjqpnmvl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.9152youxi.cn/Article/details/gt2pvfpoena.html

JS:   arr.filter(x => x > 3)
来源：http://dali.mhx1999.top/Article/details/gt2qwbdlfbt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jqgufenzy.top/Article/details/gt2asdgbwal.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gotoacloud.top/Article/details/gt2xbxrfpyo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.tianlin.xyz/Article/details/gt2xqeupowg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2tnsesoex.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hfpthk.cn/Article/details/gt2mitcvgbh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj202588.top/Article/details/gt2qmfimqci.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ybcxt.top/Article/details/gt2ghopcqty.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.svipenyu.cn/Article/details/gt2dlejlopj.html

JS:   arr.map(x => x * 2)
来源：http://dali.hammf.cn/Article/details/gt2gmxelyxo.html

TS:   arr.map(x => x * 2)
来源：http://dali.ivvv.top/Article/details/gt2vnrltflk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cefdszxq.html

Go:   // 手写循环
来源：http://dali.hysaishi.cn/Article/details/gt2hxbiebzl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gt2uatjqaoi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.snrcjt.cn/Article/details/gt2bojjmpzp.html

[D15] 去重
来源：http://dali.yongpay.top/Article/details/gt2gnahldjh.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jianghu66.top/Article/details/gt2wtjubfti.html

PHP:  array_unique($arr);
来源：http://dali.ehwqpu.com/Article/details/gt2ssgjvlrl.html

JS:   [...new Set(arr)]
来源：http://dali.zhongyouzk.top/Article/details/gt2ewpmpbnk.html

TS:   [...new Set(arr)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jptjlqjo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ykxnixpb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.quarkkingdee.top/Article/details/gt2cnewftzh.html

Ruby: arr.uniq
来源：http://dali.ppjwa.cn/Article/details/gt2phsjuvrl.html

C#:   list.Distinct().ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2twtepbny.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjjfdyq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2rbaotnny.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.dashuyun.cn/Article/details/gt2sgzszhth.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zdqjudy.top/Article/details/gt2xyhqaqcf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xziqi.cn/Article/details/gt2cghqnfci.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cucudq.cn/Article/details/gt2cgdooxzt.html

Go:   // 手写循环累加
来源：http://dali.gzhubu.top/Article/details/gt2ugbfclra.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dydwmfxk.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2flefelha.html

[D17] 最大值与最小值
来源：http://dali.jqgufenzy.top/Article/details/gt2ekomfyai.html

Py:   max(arr);  min(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2ekwjjsem.html

PHP:  max($arr);  min($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2mdsufhka.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ybcxt.top/Article/details/gt2gkjxynxn.html

TS:   Math.max(...arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2rtgobdrs.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yuanzhike.top/Article/details/gt2gnfyosgv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xinyue.icu/Article/details/gt2vyypeque.html

Ruby: arr.max;  arr.min
来源：http://dali.cucudq.cn/Article/details/gt2nkkshyzn.html

C#:   list.Max();  list.Min()
来源：http://dali.svipenyu.cn/Article/details/gt2oaihdplg.html

[D18] 扁平化嵌套数组
来源：http://dali.guowangkeji.top/Article/details/gt2iyhycixp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.daxiang520.top/Article/details/gt2mwqllonu.html

PHP:  array_merge(...$nested);
来源：http://dali.wangdashe.top/Article/details/gt2bkqnuxgz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sysykeji.top/Article/details/gt2qdkpedqa.html

TS:   nested.flat();
来源：http://dali.aizwys.cn/Article/details/gt2rtaridve.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.pycfn.com/Article/details/gt2kswhoqwf.html

Go:   // 手写双层循环
来源：http://dali.ybcxt.top/Article/details/gt2jstszzwa.html

Ruby: nested.flatten
来源：http://dali.jlsjyb.cn/Article/details/gt2dfznwptt.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yuxming.cn/Article/details/gt2bvobenco.html

[D19] 按字段分组
来源：http://dali.tianlin.xyz/Article/details/gt2yllsccuz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.aizwys.cn/Article/details/gt2kklxzvxd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zycfv.cn/Article/details/gt2skpxhhst.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.0kj1m.cn/Article/details/gt2mgjkhent.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hnxiangtu.top/Article/details/gt2tlmkpara.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.0kj1m.cn/Article/details/gt2zhjnbtjt.html

Go:   // 手写 map[string][]T
来源：http://dali.cucudq.cn/Article/details/gt2skheqbrx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jqgufenzy.top/Article/details/gt2bulhkikd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jqgufenzy.top/Article/details/gt2yjncyaft.html

[D20] 统计每个元素出现次数
来源：http://dali.jqgfzy.top/Article/details/gt2rptnjhfi.html

Py:   Counter(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2vibhthxx.html

PHP:  array_count_values($arr);
来源：http://dali.hnqzz.top/Article/details/gt2okycufda.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.316326.xyz/Article/details/gt2klusumcx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.iojbl.cn/Article/details/gt2gttdvdmw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2verevals.html

Go:   // 手写 map[T]int
来源：http://dali.jqgfzy.top/Article/details/gt2umabevyu.html

Ruby: arr.tally
来源：http://dali.pengpengdd.cyou/Article/details/gt2xodlibfa.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cheryme.top/Article/details/gt2bpnelmqi.html

[D21] 判断是否包含某元素
来源：http://dali.yuxming.cn/Article/details/gt2zuepjouc.html

Py:   x in arr
来源：http://dali.xinyue.icu/Article/details/gt2pylnwnls.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gzhubu.top/Article/details/gt2zyrugcwj.html

JS:   arr.includes(x)
来源：http://dali.cdnleiting.top/Article/details/gt2mjlywkrq.html

TS:   arr.includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2sykbhelj.html

Java: list.contains(x)
来源：http://dali.haohaochexian.top/Article/details/gt2dwhldjnu.html

Go:   slices.Contains(arr, x)
来源：http://dali.yj20258888.top/Article/details/gt2pgeethqq.html

Ruby: arr.include?(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2ghrgydjb.html

C#:   list.Contains(x)
来源：http://dali.tanke756.top/Article/details/gt2lezntufv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xuetiantiany.cn/Article/details/gt2lytujtis.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.aizwys.cn/Article/details/gt2ccbubmbp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.c1oappe.top/Article/details/gt2twkefkdx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2zwagqvhd.html

TS:   [...arr];
来源：http://dali.sufxvd.cn/Article/details/gt2djzntxll.html

Java: new ArrayList<>(list);
来源：http://dali.smart0.xyz/Article/details/gt2uzgaagju.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cucudq.cn/Article/details/gt2vdlqgdsi.html

Ruby: arr.dup;  arr.clone
来源：http://dali.nwbrower.top/Article/details/gt2rtkcbiaf.html

C#:   new List<int>(list);
来源：http://dali.hysaishi.cn/Article/details/gt2wlfgpxjd.html

[D23] reduce 累积计算
来源：http://dali.xziqi.cn/Article/details/gt2epyfigxl.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sdzcxevp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yonumen.top/Article/details/gt2dbrtmadw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zdqjudy.top/Article/details/gt2ckirzlqd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.andypj.xyz/Article/details/gt2btkczins.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenjidiqi.icu/Article/details/gt2dyuwzlgd.html

Go:   // 手写循环
来源：http://dali.wangdashe.top/Article/details/gt2btxrkggn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj20258888.top/Article/details/gt2ipcoyydg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jiagoushi.top/Article/details/gt2cjxdvztp.html

[D24] 字典 / Map 基本操作
来源：http://dali.yj20258888.top/Article/details/gt2mtnjyyhv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xinyue.icu/Article/details/gt2ponmewkc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gaohongyu789.top/Article/details/gt2yxewsvxc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zdqjudy.top/Article/details/gt2bqdsxhvj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.fzhhl.top/Article/details/gt2uncdhtjh.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yueranfly.top/Article/details/gt2sijcnvnm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kxmedseo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xuetiantiany.cn/Article/details/gt2gyimzewa.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.redwolf501.top/Article/details/gt2nxtxgopn.html

[D25] Set 集合去重与交并差
来源：http://dali.svipenyu.cn/Article/details/gt2pxcrumla.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cashguo.top/Article/details/gt2myspmneo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.smart0.xyz/Article/details/gt2bjkojzzw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2dqifkvue.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tanke756.top/Article/details/gt2psryetha.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.snrcjt.cn/Article/details/gt2kqkimoah.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shzxlz.cn/Article/details/gt2epxzvozu.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2xzzfaygh.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yvedp.cn/Article/details/gt2dkncehsy.html

[D26] 数组转字符串
来源：http://dali.svipenyu.cn/Article/details/gt2cyitfssd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.tanke756.top/Article/details/gt2ckfufnff.html

PHP:  implode(", ", $arr);
来源：http://dali.xinyue.icu/Article/details/gt2lnpdsnta.html

JS:   arr.join(", ")
来源：http://dali.jqgufenzy.top/Article/details/gt2fpvcuurk.html

TS:   arr.join(", ")
来源：http://dali.zhixingplan.top/Article/details/gt2feqnnfgx.html

Java: String.join(", ", list)
来源：http://dali.zhongyouzk.top/Article/details/gt2zuewexxz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.tianlin.xyz/Article/details/gt2swjlypun.html

Ruby: arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gt2yvkfaemq.html

C#:   string.Join(", ", list)
来源：http://dali.kuanghao11.cn/Article/details/gt2jnuuszkv.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2gfohlxqt.html

E. 字符串处理
来源：http://dali.haohaochexian.top/Article/details/gt2jribbfpk.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2eunditff.html

[E01] 拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2mtcrvfhf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.dashuyun.cn/Article/details/gt2onzbevur.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.nanxuanxn.top/Article/details/gt2awofystj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnxiangtu.top/Article/details/gt2fjhdkgfb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nwbrower.top/Article/details/gt2zhblugno.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jtippyhl.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.tianlin.xyz/Article/details/gt2whltahnj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2suwyecfc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gt2zkhkavwe.html

[E02] 重复字符串
来源：http://dali.havefunace.top/Article/details/gt2zcacfopc.html

Py:   "ab" * 3
来源：http://dali.shzxlz.cn/Article/details/gt2bwkaemin.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xinyue.icu/Article/details/gt2mxpwrbki.html

JS:   "ab".repeat(3)
来源：http://dali.sweek.top/Article/details/gt2njqegnac.html

TS:   "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gt2ppdygrka.html

Java: "ab".repeat(3)
来源：http://dali.svipenyu.cn/Article/details/gt2jkxlbwhm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.andypj.xyz/Article/details/gt2qqixbosh.html

Ruby: "ab" * 3
来源：http://dali.wangshuangyany.cn/Article/details/gt2zdxgsdic.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xuetiantiany.cn/Article/details/gt2apgethgk.html

[E03] 截取子串
来源：http://dali.tian-w.cn/Article/details/gt2glwkbnns.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.vqdsnc.cn/Article/details/gt2hwpcnhyn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jxpexucw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jianghu66.top/Article/details/gt2ihkvhyhx.html

TS:   s.slice(1, 4)
来源：http://dali.yvedp.cn/Article/details/gt2kqaznohw.html

Java: s.substring(1, 4)
来源：http://dali.kuanghao11.cn/Article/details/gt2tqqevewo.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yangfankeji.com/Article/details/gt2lyzexysn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yueranfly.top/Article/details/gt2givlvkfy.html

C#:   s.Substring(1, 3)
来源：http://dali.redwolf501.top/Article/details/gt2oafiymza.html

[E04] 查找子串位置
来源：http://dali.dashuyun.cn/Article/details/gt2bbcwwjhe.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2unuvxhyj.html

PHP:  strpos($s, "x");
来源：http://dali.tian-w.cn/Article/details/gt2igtghzwy.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.quarkkingdee.top/Article/details/gt2pyzmnrjs.html

TS:   s.indexOf("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jptxeoic.html

Java: s.indexOf("x")
来源：http://dali.shzxlz.cn/Article/details/gt2nciutgkv.html

Go:   strings.Index(s, "x")
来源：http://dali.hnxiangtu.top/Article/details/gt2ritdoenf.html

Ruby: s.index("x")
来源：http://dali.9152youxi.cn/Article/details/gt2gokpkthq.html

C#:   s.IndexOf("x")
来源：http://dali.shangyingyoupin.top/Article/details/gt2phickdmz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hnxiangtu.top/Article/details/gt2bdlrhowy.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.sweek.top/Article/details/gt2uafhqmmj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cashguo.top/Article/details/gt2tsjtzmlc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yongpay.top/Article/details/gt2qdumqjaz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hywenlv.cn/Article/details/gt2bkicuqcd.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gt2yfuxxxqc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shangyingyoupin.top/Article/details/gt2iuluynoy.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hongshengwenyu.top/Article/details/gt2otnxaxzi.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yueranfly.top/Article/details/gt2fhwfretn.html

[E06] 替换子串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ejhrqevz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cucudq.cn/Article/details/gt2xkkdcbuq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2rgpulniq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gt2actmndjr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.smart0.xyz/Article/details/gt2sqpceulw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gt2gfepzzxd.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.svipenyu.cn/Article/details/gt2onnktyug.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yueranfly.top/Article/details/gt2yjwlpnty.html

C#:   s.Replace("a", "b")
来源：http://dali.xylfe.cn/Article/details/gt2srrqybaj.html

[E07] 按分隔符拆分
来源：http://dali.wangdashe.top/Article/details/gt2qvxkexfq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hongshengwenyu.top/Article/details/gt2lozexftw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.pycfn.com/Article/details/gt2magdynbl.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.birdmap.top/Article/details/gt2nekwjnew.html

TS:   s.split(",")
来源：http://dali.jiagoushi.top/Article/details/gt2sncmhwgm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.smart0.xyz/Article/details/gt2jclpltlp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.fengsongda.top/Article/details/gt2htiyvcds.html

Ruby: s.split(",");  s.split
来源：http://dali.ivvv.top/Article/details/gt2sihtipmx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.aizwys.cn/Article/details/gt2gecfhnwc.html

[E08] 数组按分隔符合并
来源：http://dali.redwolf501.top/Article/details/gt2dmynnapd.html

Py:   ",".join(items)
来源：http://dali.xziqi.cn/Article/details/gt2rgxcjwvk.html

PHP:  implode(",", $items);
来源：http://dali.chenjidiqi.icu/Article/details/gt2vqmidgmx.html

JS:   items.join(",")
来源：http://dali.hongshengwenyu.top/Article/details/gt2azmpqlil.html

TS:   items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gt2qzlrtzec.html

Java: String.join(",", items)
来源：http://dali.cdnleiting.top/Article/details/gt2ndhtbgxj.html

Go:   strings.Join(items, ",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ksdiqjfe.html

Ruby: items.join(",")
来源：http://dali.gzhubu.top/Article/details/gt2wmbffgxc.html

C#:   string.Join(",", items)
来源：http://dali.aizwys.cn/Article/details/gt2gavubtza.html

[E09] 去除所有空白字符
来源：http://dali.ivvv.top/Article/details/gt2akpltyml.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.guowangkeji.top/Article/details/gt2mknpvtfg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cqqwz.cn/Article/details/gt2byumaetr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.wangdashe.top/Article/details/gt2dkwmrapd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.mhx1999.top/Article/details/gt2jjnuvqfv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.svipenyu.cn/Article/details/gt2pavbefid.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zdqjudy.top/Article/details/gt2lqqrmpmh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.havefunace.top/Article/details/gt2apvjmjik.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yanxiufei.cn/Article/details/gt2grvonrwu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.9152youxi.cn/Article/details/gt2cgwufqrh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shuidangran.top/Article/details/gt2lkeltrsg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jlsjyb.cn/Article/details/gt2bmfjzbzr.html

JS:   "7".padStart(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gt2vsyrokar.html

TS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2symzdhnm.html

Java: String.format("%03d", 7)
来源：http://dali.chenlongwang.top/Article/details/gt2fdupbxwn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mruebhch.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gt2juaclxqg.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhoulong.xyz/Article/details/gt2zbgzvxfz.html

[E11] 反转字符串
来源：http://dali.chenzaomai.com/Article/details/gt2ktxjozif.html

Py:   s[::-1]
来源：http://dali.dashuyun.cn/Article/details/gt2nxalpygw.html

PHP:  strrev($s);
来源：http://dali.zhengqikj.top/Article/details/gt2aokhotde.html

JS:   [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gt2likjslme.html

TS:   [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qexpmfyi.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.andypj.xyz/Article/details/gt2iuoccxod.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.316326.xyz/Article/details/gt2hxwwdkxx.html

Ruby: s.reverse
来源：http://dali.chenlongwang.top/Article/details/gt2hyteybay.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.aibaodan.cn/Article/details/gt2daenmcvn.html

[E12] 统计某字符出现次数
来源：http://dali.tian-w.cn/Article/details/gt2folsgftf.html

Py:   s.count("a")
来源：http://dali.chenlongwang.top/Article/details/gt2ggdpduym.html

PHP:  substr_count($s, "a");
来源：http://dali.haohaochexian.top/Article/details/gt2ouddekmx.html

JS:   s.split("a").length - 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2bpsszvjm.html

TS:   s.split("a").length - 1
来源：http://dali.ppjwa.cn/Article/details/gt2epmkpdnk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ybcxt.top/Article/details/gt2fcwdbgqw.html

Go:   strings.Count(s, "a")
来源：http://dali.tanke756.top/Article/details/gt2reiwxkzw.html

Ruby: s.count("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mwkextvi.html

C#:   s.Count(c => c == 'a')
来源：http://dali.chenlongwang.top/Article/details/gt2zwmzfhnw.html

[E13] 逐字符遍历
来源：http://dali.daxiang520.top/Article/details/gt2ophmdrik.html

Py:   for ch in s: print(ch)
来源：http://dali.316326.xyz/Article/details/gt2roulmtez.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hysaishi.cn/Article/details/gt2irnbudki.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ivvv.top/Article/details/gt2mrhicdzz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.svipenyu.cn/Article/details/gt2umyyvjps.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hywenlv.cn/Article/details/gt2vgbckrme.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.nanxinkj.top/Article/details/gt2bvozdmsy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shzxlz.cn/Article/details/gt2wjnliepp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hysaishi.cn/Article/details/gt2peeivfdq.html

[E14] URL 编码与 Base64
来源：http://dali.yanxiufei.cn/Article/details/gt2shgqzssl.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ppniwewa.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.wangdashe.top/Article/details/gt2iesdmwzk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.smart0.xyz/Article/details/gt2rhuvbtxb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.aizwys.cn/Article/details/gt2ztnfynpl.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.bjfxy.top/Article/details/gt2xkixaotg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ivvv.top/Article/details/gt2xdljebrj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nanxinkj.top/Article/details/gt2lwigjxns.html


<!-- 参考信息 -->