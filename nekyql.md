代发 wailian999

Py:   len(arr)
来源：http://dali.iojbl.cn/Article/details/gtckekjntf.html

PHP:  count($arr);
来源：http://dali.yangfankeji.com/Article/details/gttckxcudr.html

JS:   arr.length
来源：http://dali.vqdsnc.cn/Article/details/gtfpukhsfy.html

TS:   arr.length
来源：http://dali.jqgfzy.top/Article/details/gtqeqyaqig.html

Java: list.size();
来源：http://dali.jiagoushi.top/Article/details/gtphxrgkwa.html

Go:   len(arr)
来源：http://dali.zhengqikj.top/Article/details/gtzkrnwmyb.html

Ruby: arr.length; arr.size
来源：http://dali.svipenyu.cn/Article/details/gtwmnhcdke.html

C#:   list.Count;
来源：http://dali.xinyue.icu/Article/details/gtcgsjsomr.html

[D07] 切片 / 取子数组
来源：http://dali.mhx1999.top/Article/details/gtogxmbttg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinqigufen.top/Article/details/gtnbsrlbhz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sxryk.cn/Article/details/gtboyvzwqo.html

JS:   arr.slice(1, 4);
来源：http://dali.yanxiufei.cn/Article/details/gtxmsxqedf.html

TS:   arr.slice(1, 4);
来源：http://dali.pengpengdd.cyou/Article/details/gthevoihwn.html

Java: list.subList(1, 4);
来源：http://dali.hnxiangtu.top/Article/details/gtodnmksfg.html

Go:   arr[1:4]
来源：http://dali.dashuyun.cn/Article/details/gtrbldjwhu.html

Ruby: arr[1, 3]
来源：http://dali.tianlin.xyz/Article/details/gtmnmtvxjy.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinqigufen.top/Article/details/gtokuzlgwp.html

[D08] 合并两个数组
来源：http://dali.hongshengwenyu.top/Article/details/gthnxenlat.html

Py:   a + b;  a.extend(b)
来源：http://dali.quarkkingdee.top/Article/details/gthvdumvdf.html

PHP:  array_merge($a, $b);
来源：http://dali.ehwqpu.com/Article/details/gtesrigche.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj20258.top/Article/details/gtrtytdkba.html

TS:   [...a, ...b];
来源：http://dali.ybcxt.top/Article/details/gtkgwrakey.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtytcopbsg.html

Go:   append(a, b...)
来源：http://dali.ivvv.top/Article/details/gtbdtpauzo.html

Ruby: a + b;  a.concat(b)
来源：http://dali.nanxuanxn.top/Article/details/gtruilixep.html

C#:   a.Concat(b).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtzolhhswl.html

[D09] 排序（升序）
来源：http://dali.jinqigfzy.top/Article/details/gtaflkggul.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shuidangran.top/Article/details/gtvuhvsnmp.html

PHP:  sort($arr);
来源：http://dali.shzxlz.cn/Article/details/gtxylxsmdl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cdnleiting.top/Article/details/gtxdkabyvo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jianghu66.top/Article/details/gtfkwgqgha.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.tianlin.xyz/Article/details/gtldwaccbd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cqqwz.cn/Article/details/gtqzvidrmw.html

Ruby: arr.sort
来源：http://dali.sysykeji.top/Article/details/gtkbhjyujp.html

C#:   list.Sort();
来源：http://dali.yj202588.top/Article/details/gtpobignub.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.316326.xyz/Article/details/gtuqqmwlmq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrbazjbew.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhiwuduotai.top/Article/details/gtllcyoras.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwwmwawuz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.haohaochexian.top/Article/details/gtzdkillkn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.0kj1m.cn/Article/details/gtoilznovy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jyoumei.cn/Article/details/gttgxmwccn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.c1oappe.top/Article/details/gtaebmmgam.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cucudq.cn/Article/details/gtdvejjbyr.html

[D11] 反转数组
来源：http://dali.dianchejie.cn/Article/details/gtugldnbzk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cashguo.top/Article/details/gtgnosrmsa.html

PHP:  array_reverse($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtigsaspjr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hnqzz.top/Article/details/gtjasjisif.html

TS:   [...arr].reverse();
来源：http://dali.cqqwz.cn/Article/details/gtgcdgwgno.html

Java: Collections.reverse(list);
来源：http://dali.shangyingyoupin.top/Article/details/gtifjodxmo.html

Go:   slices.Reverse(arr)
来源：http://dali.jyoumei.cn/Article/details/gtgivbawwr.html

Ruby: arr.reverse
来源：http://dali.cdnleiting.top/Article/details/gtnxwhcoqg.html

C#:   list.Reverse();
来源：http://dali.c1oappe.top/Article/details/gtmwsqkvdw.html

[D12] 查找元素下标
来源：http://dali.andypj.xyz/Article/details/gtatskfqes.html

Py:   arr.index(x);  x in arr
来源：http://dali.yueranfly.top/Article/details/gtbkuaqhbf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jqgufenzy.top/Article/details/gtrgbwgdxa.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.birdmap.top/Article/details/gtondxadpz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sufxvd.cn/Article/details/gtwhtfaggp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.andypj.xyz/Article/details/gtqtthibba.html

Go:   slices.Index(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtwroachwp.html

Ruby: arr.index(x)
来源：http://dali.snrcjt.cn/Article/details/gtzdknemwz.html

C#:   list.IndexOf(x);
来源：http://dali.daria6918.cn/Article/details/gtvegisahj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yanxiufei.cn/Article/details/gtrhuhrapf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhiwuduotai.top/Article/details/gtzuqlgbio.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zycfv.cn/Article/details/gtgziempgm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gotoacloud.top/Article/details/gtzbngrrls.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmtvnxlyv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yanxiufei.cn/Article/details/gteyaklgtj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hnxiangtu.top/Article/details/gtdtqqctta.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yanxiufei.cn/Article/details/gtfomaeorn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cashguo.top/Article/details/gtlbvrghgc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinghuilouyu.cn/Article/details/gtdkouidwf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.nwbrower.top/Article/details/gtobvzailc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj20258.top/Article/details/gtdtkavvft.html

JS:   arr.map(x => x * 2)
来源：http://dali.nanxuanxn.top/Article/details/gtleoowroj.html

TS:   arr.map(x => x * 2)
来源：http://dali.vqdsnc.cn/Article/details/gtqpmbeggw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yvedp.cn/Article/details/gtrupsucuw.html

Go:   // 手写循环
来源：http://dali.pengpengdd.cyou/Article/details/gtmohxksxk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.mhx1999.top/Article/details/gticcyvhqc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cucudq.cn/Article/details/gtojmzdbkb.html

[D15] 去重
来源：http://dali.jqgfzy.top/Article/details/gthmgzhrpk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hongshengwenyu.top/Article/details/gtyfqjgghf.html

PHP:  array_unique($arr);
来源：http://dali.yueranfly.top/Article/details/gtikdvsuec.html

JS:   [...new Set(arr)]
来源：http://dali.guowangkeji.top/Article/details/gtfpgpxyrm.html

TS:   [...new Set(arr)]
来源：http://dali.yj202588.top/Article/details/gtgbtnzgbx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.redwolf501.top/Article/details/gtvicqcgab.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.chenlongwang.top/Article/details/gtnkoxzfqc.html

Ruby: arr.uniq
来源：http://dali.c1oappe.top/Article/details/gtjzqxibom.html

C#:   list.Distinct().ToList()
来源：http://dali.yangfankeji.com/Article/details/gtogmnhxmg.html

[D16] 求和与平均值
来源：http://dali.shzxlz.cn/Article/details/gtuezenvql.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.birdmap.top/Article/details/gtryinevml.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xinyue.icu/Article/details/gtjbtefubr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yvedp.cn/Article/details/gtsefqhivu.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtwxceqbvp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shangyingyoupin.top/Article/details/gtjlszogyh.html

Go:   // 手写循环累加
来源：http://dali.ehwqpu.com/Article/details/gtnjwpypwl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shzxlz.cn/Article/details/gtniejyror.html

C#:   list.Sum();  list.Average()
来源：http://dali.smart0.xyz/Article/details/gtuyeeyqzz.html

[D17] 最大值与最小值
来源：http://dali.bjfxy.top/Article/details/gtkzdayent.html

Py:   max(arr);  min(arr)
来源：http://dali.jianghu66.top/Article/details/gtxykkfcpd.html

PHP:  max($arr);  min($arr);
来源：http://dali.cashguo.top/Article/details/gtkiaiypgk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.tanke756.top/Article/details/gtzprrdvpl.html

TS:   Math.max(...arr);
来源：http://dali.xinyue.icu/Article/details/gtzxcxaqxe.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hywenlv.cn/Article/details/gtxmdwgeun.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtmxktxtmu.html

Ruby: arr.max;  arr.min
来源：http://dali.316326.xyz/Article/details/gtbuwmonht.html

C#:   list.Max();  list.Min()
来源：http://dali.xinyue.icu/Article/details/gtswepawky.html

[D18] 扁平化嵌套数组
来源：http://dali.chenzaomai.com/Article/details/gtfgiistvi.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ivvv.top/Article/details/gtcoiwsdub.html

PHP:  array_merge(...$nested);
来源：http://dali.meibo888.top/Article/details/gtybdkixhg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jqgufenzy.top/Article/details/gtmgadjihd.html

TS:   nested.flat();
来源：http://dali.pycfn.com/Article/details/gtsfisncob.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hnxiangtu.top/Article/details/gtgescvgnd.html

Go:   // 手写双层循环
来源：http://dali.iojbl.cn/Article/details/gtpzetqbsw.html

Ruby: nested.flatten
来源：http://dali.cqqwz.cn/Article/details/gtkzkxogpp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.aibaodan.cn/Article/details/gtbmeprffc.html

[D19] 按字段分组
来源：http://dali.hnqzz.top/Article/details/gtwhglwskq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhongyouzk.top/Article/details/gtmlatvrji.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhixingplan.top/Article/details/gtwnfcooie.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gtnfqthkyc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.tianlin.xyz/Article/details/gtbbmdclxw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gogol.net.cn/Article/details/gtjzyjzxxy.html

Go:   // 手写 map[string][]T
来源：http://dali.tian-w.cn/Article/details/gtmppjehhs.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gogol.net.cn/Article/details/gtzvqvlfxs.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.meibo888.top/Article/details/gtijihggtu.html

[D20] 统计每个元素出现次数
来源：http://dali.jianghu66.top/Article/details/gtqlesjzci.html

Py:   Counter(arr)
来源：http://dali.jyoumei.cn/Article/details/gtzmneviiz.html

PHP:  array_count_values($arr);
来源：http://dali.0kj1m.cn/Article/details/gtlctwvxve.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hywenlv.cn/Article/details/gtvvnkfmah.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gzhubu.top/Article/details/gtimvhiiii.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhengqikj.top/Article/details/gttvyshntg.html

Go:   // 手写 map[T]int
来源：http://dali.hammf.cn/Article/details/gtvebgcbig.html

Ruby: arr.tally
来源：http://dali.gaohongyu789.top/Article/details/gtyrfmyedr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ybcxt.top/Article/details/gtthhowxdz.html

[D21] 判断是否包含某元素
来源：http://dali.cheryme.top/Article/details/gtkzgjcggg.html

Py:   x in arr
来源：http://dali.dianchejie.cn/Article/details/gtudlzrtzq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hnxiangtu.top/Article/details/gtiujycibl.html

JS:   arr.includes(x)
来源：http://dali.smart0.xyz/Article/details/gttlxpysqy.html

TS:   arr.includes(x)
来源：http://dali.daxiang520.top/Article/details/gtnvhbxicf.html

Java: list.contains(x)
来源：http://dali.zycfv.cn/Article/details/gttscviamo.html

Go:   slices.Contains(arr, x)
来源：http://dali.pycfn.com/Article/details/gtjbjitdga.html

Ruby: arr.include?(x)
来源：http://dali.gotoacloud.top/Article/details/gtgcmkfzsy.html

C#:   list.Contains(x)
来源：http://dali.jinqigufen.top/Article/details/gtiwymtmnz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yonumen.top/Article/details/gtpznrevwh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.guannengcc.top/Article/details/gtllsoxfan.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jqgfzy.top/Article/details/gtqatbgdam.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtlzqlkone.html

TS:   [...arr];
来源：http://dali.fengsongda.top/Article/details/gtpdgfwteo.html

Java: new ArrayList<>(list);
来源：http://dali.sweek.top/Article/details/gtmhmrhmem.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zdqjudy.top/Article/details/gttrwlhlhe.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yonumen.top/Article/details/gtpxmrpifx.html

C#:   new List<int>(list);
来源：http://dali.jqgufenzy.top/Article/details/gthbgklpgq.html

[D23] reduce 累积计算
来源：http://dali.jinyuanbaomall.cn/Article/details/gtttbacbod.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ydzc1.top/Article/details/gtygjecfoi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.tanke756.top/Article/details/gtanbbvfij.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258.top/Article/details/gttvkcnlxh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigufen.top/Article/details/gtkrhupvqf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinqigufen.top/Article/details/gtkabayznl.html

Go:   // 手写循环
来源：http://dali.yueranfly.top/Article/details/gtjjanloig.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shzxlz.cn/Article/details/gtnvsnaohu.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhoulong.xyz/Article/details/gtlwvndodm.html

[D24] 字典 / Map 基本操作
来源：http://dali.cucudq.cn/Article/details/gtyxazsytd.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hnxiangtu.top/Article/details/gtqvtejzpi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yvedp.cn/Article/details/gtdakmhynh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gttggwfrrb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtbaocbkjf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xinyue.icu/Article/details/gtxoxasdlj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhiwuduotai.top/Article/details/gtxdjzgmoz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xylfe.cn/Article/details/gtqnocxhcc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sweek.top/Article/details/gtbhcysmcz.html

[D25] Set 集合去重与交并差
来源：http://dali.shanyushiyangkeji.top/Article/details/gtetxeenol.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinqigfzy.top/Article/details/gtimixpzeo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.316326.xyz/Article/details/gtopfvdill.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjrfxfgyy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.iojbl.cn/Article/details/gtookxjtgg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zdqjudy.top/Article/details/gtfvkzvpfi.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhongyouzk.top/Article/details/gtmcngzjrr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cucudq.cn/Article/details/gtehhbvxcw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jianghu66.top/Article/details/gtfmatjuka.html

[D26] 数组转字符串
来源：http://dali.aibaodan.cn/Article/details/gtwpeqkgsu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.fzhhl.top/Article/details/gtykmfpyuj.html

PHP:  implode(", ", $arr);
来源：http://dali.zhengqikj.top/Article/details/gtucthweoa.html

JS:   arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gtqiyjapcw.html

TS:   arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gtcbwpnflo.html

Java: String.join(", ", list)
来源：http://dali.jinqigufen.top/Article/details/gtjttdsxui.html

Go:   strings.Join(strs, ", ")
来源：http://dali.316326.xyz/Article/details/gtqepsmihz.html

Ruby: arr.join(", ")
来源：http://dali.yj202588.top/Article/details/gtqlnpkwnz.html

C#:   string.Join(", ", list)
来源：http://dali.pengpengdd.cyou/Article/details/gtyrbzwrht.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtpwczbgiv.html

E. 字符串处理
来源：http://dali.cheryme.top/Article/details/gtjeonyvpl.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtdxfkzwjb.html

[E01] 拼接字符串
来源：http://dali.guannengcc.top/Article/details/gtfhcfwwag.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hywenlv.cn/Article/details/gtkzqncmcu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.9152youxi.cn/Article/details/gtdfqmbvlv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.birdmap.top/Article/details/gtuucwkncu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxuanxn.top/Article/details/gtbbccwlwf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.quarkkingdee.top/Article/details/gtrartavtw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shzxlz.cn/Article/details/gtvucodcdn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hfpthk.cn/Article/details/gttfxliicy.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gtwtqgeqoq.html

[E02] 重复字符串
来源：http://dali.jiagoushi.top/Article/details/gtqjbrwply.html

Py:   "ab" * 3
来源：http://dali.wangdashe.top/Article/details/gtupduatbn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sysykeji.top/Article/details/gtybkterzj.html

JS:   "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gtlmwiwdxb.html

TS:   "ab".repeat(3)
来源：http://dali.yuanzhike.top/Article/details/gteovqzrkf.html

Java: "ab".repeat(3)
来源：http://dali.cashguo.top/Article/details/gtdzfoqnka.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hnqzz.top/Article/details/gtaupasdch.html

Ruby: "ab" * 3
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttjledeso.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.aizwys.cn/Article/details/gtyjwkqvfq.html

[E03] 截取子串
来源：http://dali.yvedp.cn/Article/details/gtrjrzlewl.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.nwbrower.top/Article/details/gtkrjfrifj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.tanke756.top/Article/details/gtdjvzhvvw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yvedp.cn/Article/details/gthvcbrkdz.html

TS:   s.slice(1, 4)
来源：http://dali.zhoulong.xyz/Article/details/gtvfvwskma.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gthtmbonte.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhiwuduotai.top/Article/details/gtvzfvpxvi.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.guannengcc.top/Article/details/gtftvphtcu.html

C#:   s.Substring(1, 3)
来源：http://dali.yangfankeji.com/Article/details/gtcbwxywov.html

[E04] 查找子串位置
来源：http://dali.nanxuanxn.top/Article/details/gtzvxvnlhc.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinqigfzy.top/Article/details/gteawyrtek.html

PHP:  strpos($s, "x");
来源：http://dali.feifeiyinyue.top/Article/details/gttlkieplb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xuetiantiany.cn/Article/details/gtkfimrzmq.html

TS:   s.indexOf("x")
来源：http://dali.xuetiantiany.cn/Article/details/gtqqnclctj.html

Java: s.indexOf("x")
来源：http://dali.yangfankeji.com/Article/details/gtrelzxoqt.html

Go:   strings.Index(s, "x")
来源：http://dali.yanxiufei.cn/Article/details/gtwlfawgre.html

Ruby: s.index("x")
来源：http://dali.xylfe.cn/Article/details/gtwvyjbcjj.html

C#:   s.IndexOf("x")
来源：http://dali.pycfn.com/Article/details/gtrddufyuz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.tanke756.top/Article/details/gtzhbutpbw.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ehwqpu.com/Article/details/gtucixnhys.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ivvv.top/Article/details/gtojhwobhe.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuanzx.com/Article/details/gtgcsmxbbp.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jlsjyb.cn/Article/details/gtkuvygmds.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hongshengwenyu.top/Article/details/gtpijynwkn.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cheryme.top/Article/details/gtxdmytcgn.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.chenzaomai.com/Article/details/gtgjlgujvz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.aizwys.cn/Article/details/gtavncyljn.html

[E06] 替换子串
来源：http://dali.shzxlz.cn/Article/details/gtzsnncbqn.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.9152youxi.cn/Article/details/gtuaygkobo.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.quarkkingdee.top/Article/details/gtfetyoamv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtxadhuexv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtyazchdtd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtpzdikvpc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gtcendkydq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtydpcipwy.html

C#:   s.Replace("a", "b")
来源：http://dali.yonumen.top/Article/details/gtsapueaxt.html

[E07] 按分隔符拆分
来源：http://dali.0kj1m.cn/Article/details/gtypafpbbw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yueranfly.top/Article/details/gttgzctxfu.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.smart0.xyz/Article/details/gtixnjlfwb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xuetiantiany.cn/Article/details/gtrljdvlei.html

TS:   s.split(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgklzlikb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhongyouzk.top/Article/details/gtwtkxdmxt.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.nanxuanxn.top/Article/details/gtcebhtwxq.html

Ruby: s.split(",");  s.split
来源：http://dali.iojbl.cn/Article/details/gtrayottez.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.meibo888.top/Article/details/gtofeaukix.html

[E08] 数组按分隔符合并
来源：http://dali.ybcxt.top/Article/details/gtftidjvoz.html

Py:   ",".join(items)
来源：http://dali.fzhhl.top/Article/details/gtkvoympap.html

PHP:  implode(",", $items);
来源：http://dali.nanxuanxn.top/Article/details/gtptjxtcjx.html

JS:   items.join(",")
来源：http://dali.birdmap.top/Article/details/gtpdynawum.html

TS:   items.join(",")
来源：http://dali.jinqigfzy.top/Article/details/gtmyfqhmyb.html

Java: String.join(",", items)
来源：http://dali.jinghuilouyu.cn/Article/details/gtidbuyoak.html

Go:   strings.Join(items, ",")
来源：http://dali.zhongyouzk.top/Article/details/gtctdndepg.html

Ruby: items.join(",")
来源：http://dali.zhixingplan.top/Article/details/gtpsiakzwb.html

C#:   string.Join(",", items)
来源：http://dali.nanxuanxn.top/Article/details/gtzhyllnvl.html

[E09] 去除所有空白字符
来源：http://dali.xuetiantiany.cn/Article/details/gtxipxcqmu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cashguo.top/Article/details/gthovgwfmu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.havefunace.top/Article/details/gthnemayvn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hnxiangtu.top/Article/details/gtsfbyxqvh.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.wangdashe.top/Article/details/gtuwgqzavu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.chenzaomai.com/Article/details/gtwadlrpru.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gzhubu.top/Article/details/gtryrvgbod.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yonumen.top/Article/details/gtbfoxzmdi.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yangfankeji.com/Article/details/gthfcjhief.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gotoacloud.top/Article/details/gthaqzyxvb.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jqgfzy.top/Article/details/gtmvthvgvo.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jqgfzy.top/Article/details/gtcfmjkyms.html

JS:   "7".padStart(3, "0")
来源：http://dali.yuanzhike.top/Article/details/gtxjfoqmvo.html

TS:   "7".padStart(3, "0")
来源：http://dali.yj20258888.top/Article/details/gtphjzjbft.html

Java: String.format("%03d", 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvnlhiiqc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gtvahzgajn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shzxlz.cn/Article/details/gtjzcwxfzy.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gaohongyu789.top/Article/details/gtijlgmeza.html

[E11] 反转字符串
来源：http://dali.yvedp.cn/Article/details/gtbkesbert.html

Py:   s[::-1]
来源：http://dali.iojbl.cn/Article/details/gtonnkrrnp.html

PHP:  strrev($s);
来源：http://dali.zdqjudy.top/Article/details/gtmmovgzwj.html

JS:   [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gtyvmpwctc.html

TS:   [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gtrybrapsk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.mhx1999.top/Article/details/gtcqyxpdxl.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhixingplan.top/Article/details/gtjizxokkw.html

Ruby: s.reverse
来源：http://dali.0kj1m.cn/Article/details/gtedywntkv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sweek.top/Article/details/gtqlklsqde.html

[E12] 统计某字符出现次数
来源：http://dali.bjfxy.top/Article/details/gtaatgorwm.html

Py:   s.count("a")
来源：http://dali.yuanzhike.top/Article/details/gthpgnyavr.html

PHP:  substr_count($s, "a");
来源：http://dali.aibaodan.cn/Article/details/gttymuyjxq.html

JS:   s.split("a").length - 1
来源：http://dali.iojbl.cn/Article/details/gtafgswfdj.html

TS:   s.split("a").length - 1
来源：http://dali.bjfxy.top/Article/details/gtdptgelwj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.meibo888.top/Article/details/gtetrvqwmm.html

Go:   strings.Count(s, "a")
来源：http://dali.gzhubu.top/Article/details/gtnebkapcv.html

Ruby: s.count("a")
来源：http://dali.aibaodan.cn/Article/details/gtxhrnhawy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhongyouzk.top/Article/details/gttxejrojd.html

[E13] 逐字符遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtvlkgwgqd.html


<!-- 参考信息 -->