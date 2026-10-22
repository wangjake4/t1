代发 wailian999

Ruby: a + b;  a.concat(b)
来源：http://dali.nwbrower.top/Article/details/gt2hqqdmmxg.html

C#:   a.Concat(b).ToList()
来源：http://dali.sweek.top/Article/details/gt2dzvabiny.html

[D09] 排序（升序）
来源：http://dali.dianchejie.cn/Article/details/gt2noeovwua.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ppjwa.cn/Article/details/gt2wimnmjgg.html

PHP:  sort($arr);
来源：http://dali.tanke756.top/Article/details/gt2rkxthjvl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yuxming.cn/Article/details/gt2algfuizb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.c1oappe.top/Article/details/gt2afasdxun.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.nwbrower.top/Article/details/gt2tmhzakky.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2rgsbndry.html

Ruby: arr.sort
来源：http://dali.iojbl.cn/Article/details/gt2zrbopawm.html

C#:   list.Sort();
来源：http://dali.pycfn.com/Article/details/gt2vronkhfq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yangfankeji.com/Article/details/gt2flcfhhyx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ghganied.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.9152youxi.cn/Article/details/gt2rttqcvse.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zngownpq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuetiantiany.cn/Article/details/gt2keyuejrb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhiwuduotai.top/Article/details/gt2joyeqhvi.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yongpay.top/Article/details/gt2nfbffoog.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.fengsongda.top/Article/details/gt2lwlvsoio.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yj202588.top/Article/details/gt2qqyhxolk.html

[D11] 反转数组
来源：http://dali.ehwqpu.com/Article/details/gt2facruquv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.meibo888.top/Article/details/gt2qjkwrkbp.html

PHP:  array_reverse($arr);
来源：http://dali.cashguo.top/Article/details/gt2ybykxmrs.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.feifeiyinyue.top/Article/details/gt2edanijcm.html

TS:   [...arr].reverse();
来源：http://dali.tanke756.top/Article/details/gt2jippxqxu.html

Java: Collections.reverse(list);
来源：http://dali.smart0.xyz/Article/details/gt2ypwrwaak.html

Go:   slices.Reverse(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2sbxtqppl.html

Ruby: arr.reverse
来源：http://dali.sweek.top/Article/details/gt2ibkakmwf.html

C#:   list.Reverse();
来源：http://dali.xuetiantiany.cn/Article/details/gt2amjttlng.html

[D12] 查找元素下标
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2byevzwyd.html

Py:   arr.index(x);  x in arr
来源：http://dali.cdnleiting.top/Article/details/gt2xhkzgnwo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.dianchejie.cn/Article/details/gt2ihrjjmie.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guowangkeji.top/Article/details/gt2uhommjix.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yongpay.top/Article/details/gt2iuufzwdb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj202588.top/Article/details/gt2wticsehr.html

Go:   slices.Index(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gt2dparxgzj.html

Ruby: arr.index(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2bkvhgrjo.html

C#:   list.IndexOf(x);
来源：http://dali.nanxinkj.top/Article/details/gt2hzdswkzi.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vfpwnoma.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yj202588.top/Article/details/gt2msgllfon.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.smart0.xyz/Article/details/gt2jzohdtgy.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yj202588.top/Article/details/gt2ibgpzjbu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.dashuyun.cn/Article/details/gt2ulrxesvg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ulqmbqgn.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gaohongyu789.top/Article/details/gt2zpglgrcl.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tian-w.cn/Article/details/gt2lmkabhgw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xuanzx.com/Article/details/gt2mqfcoqqc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zycfv.cn/Article/details/gt2vpjnjyvu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.iojbl.cn/Article/details/gt2wxcfuqhm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2gigyanij.html

JS:   arr.map(x => x * 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2afwygawr.html

TS:   arr.map(x => x * 2)
来源：http://dali.xinyue.icu/Article/details/gt2hhxdpyft.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.svipenyu.cn/Article/details/gt2zshunhcp.html

Go:   // 手写循环
来源：http://dali.bjfxy.top/Article/details/gt2zkrxbocp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.kuanghao11.cn/Article/details/gt2evbijepp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gt2ehmimuwc.html

[D15] 去重
来源：http://dali.aizwys.cn/Article/details/gt2eysctwzs.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.tian-w.cn/Article/details/gt2bbvidadt.html

PHP:  array_unique($arr);
来源：http://dali.sxryk.cn/Article/details/gt2iwmnsyvp.html

JS:   [...new Set(arr)]
来源：http://dali.feifeiyinyue.top/Article/details/gt2bjhzuiod.html

TS:   [...new Set(arr)]
来源：http://dali.mhx1999.top/Article/details/gt2qcrdzvdx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hammf.cn/Article/details/gt2fekcuymk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.smart0.xyz/Article/details/gt2tpfbaylo.html

Ruby: arr.uniq
来源：http://dali.zhixingplan.top/Article/details/gt2avbrpsfm.html

C#:   list.Distinct().ToList()
来源：http://dali.redwolf501.top/Article/details/gt2uaykpzdm.html

[D16] 求和与平均值
来源：http://dali.xylfe.cn/Article/details/gt2pkmigozg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fuuojhbp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2qpzvvevg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gt2nxqsgtkk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.meibo888.top/Article/details/gt2rtdbbstq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zycfv.cn/Article/details/gt2qydeypdi.html

Go:   // 手写循环累加
来源：http://dali.gotoacloud.top/Article/details/gt2sndygynn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cucudq.cn/Article/details/gt2ujihfreb.html

C#:   list.Sum();  list.Average()
来源：http://dali.guowangkeji.top/Article/details/gt2mqkkylco.html

[D17] 最大值与最小值
来源：http://dali.cqqwz.cn/Article/details/gt2vbjnvazi.html

Py:   max(arr);  min(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2mfatotug.html

PHP:  max($arr);  min($arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2zjhzihzu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2kcqoljzf.html

TS:   Math.max(...arr);
来源：http://dali.ydzc1.top/Article/details/gt2lkfodjub.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ivvv.top/Article/details/gt2ewlpuuee.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yueranfly.top/Article/details/gt2qglsejfq.html

Ruby: arr.max;  arr.min
来源：http://dali.yj20258.top/Article/details/gt2mqsgtwam.html

C#:   list.Max();  list.Min()
来源：http://dali.gzhubu.top/Article/details/gt2xmltwlpg.html

[D18] 扁平化嵌套数组
来源：http://dali.zhiwuduotai.top/Article/details/gt2swkxpurs.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.dianchejie.cn/Article/details/gt2krtjhfor.html

PHP:  array_merge(...$nested);
来源：http://dali.ybcxt.top/Article/details/gt2qtqdocdn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cucudq.cn/Article/details/gt2wtkhcjkz.html

TS:   nested.flat();
来源：http://dali.xinyue.icu/Article/details/gt2rtxvgcpn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinqigufen.top/Article/details/gt2cnfdnola.html

Go:   // 手写双层循环
来源：http://dali.shanyushiyangtech.top/Article/details/gt2szvkurhq.html

Ruby: nested.flatten
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xrjybhwu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.aizwys.cn/Article/details/gt2imotaacn.html

[D19] 按字段分组
来源：http://dali.hywenlv.cn/Article/details/gt2gpxxloeq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2ogmqgelz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.chenjidiqi.icu/Article/details/gt2cfvomtzn.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.c1oappe.top/Article/details/gt2zzeosoph.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.kuanghao11.cn/Article/details/gt2eqqpqwgo.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yanxiufei.cn/Article/details/gt2dynzbbpt.html

Go:   // 手写 map[string][]T
来源：http://dali.c1oappe.top/Article/details/gt2wedarzmb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jianghu66.top/Article/details/gt2qbvyaaxu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.guowangkeji.top/Article/details/gt2boxhbbjm.html

[D20] 统计每个元素出现次数
来源：http://dali.svipenyu.cn/Article/details/gt2abpqotcw.html

Py:   Counter(arr)
来源：http://dali.ppjwa.cn/Article/details/gt2nmcpaarj.html

PHP:  array_count_values($arr);
来源：http://dali.pycfn.com/Article/details/gt2xvbbsxkz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hfpthk.cn/Article/details/gt2fwcljisq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nanxuanxn.top/Article/details/gt2qdblobov.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hfpthk.cn/Article/details/gt2jmqlahbn.html

Go:   // 手写 map[T]int
来源：http://dali.9152youxi.cn/Article/details/gt2kzhyqatk.html

Ruby: arr.tally
来源：http://dali.yangfankeji.com/Article/details/gt2hcxuovhu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.316326.xyz/Article/details/gt2bcggwwvx.html

[D21] 判断是否包含某元素
来源：http://dali.gotoacloud.top/Article/details/gt2zogbepyb.html

Py:   x in arr
来源：http://dali.nwbrower.top/Article/details/gt2xovoxydx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xylfe.cn/Article/details/gt2uoleqqlx.html

JS:   arr.includes(x)
来源：http://dali.shuidangran.top/Article/details/gt2aeyuwass.html

TS:   arr.includes(x)
来源：http://dali.yj20258888.top/Article/details/gt2gwfpetgg.html

Java: list.contains(x)
来源：http://dali.9152youxi.cn/Article/details/gt2ueqxpraf.html

Go:   slices.Contains(arr, x)
来源：http://dali.redwolf501.top/Article/details/gt2sewwhtsk.html

Ruby: arr.include?(x)
来源：http://dali.wangdashe.top/Article/details/gt2xwwrabhz.html

C#:   list.Contains(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dvkokemd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hywenlv.cn/Article/details/gt2nwxedjoh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2eoeuwibr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yonumen.top/Article/details/gt2iveifzho.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2bgeydqhl.html

TS:   [...arr];
来源：http://dali.jianghu66.top/Article/details/gt2xotxcdlj.html

Java: new ArrayList<>(list);
来源：http://dali.shzxlz.cn/Article/details/gt2wfgwjsmb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.guannengcc.top/Article/details/gt2vigcwxew.html

Ruby: arr.dup;  arr.clone
来源：http://dali.dashuyun.cn/Article/details/gt2frouskuj.html

C#:   new List<int>(list);
来源：http://dali.hnxiangtu.top/Article/details/gt2ahefhscp.html

[D23] reduce 累积计算
来源：http://dali.yj202588.top/Article/details/gt2cskrvuzs.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sxryk.cn/Article/details/gt2rrjiezuz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yuanzhike.top/Article/details/gt2vqmwwask.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhixingplan.top/Article/details/gt2zlpynosz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.pycfn.com/Article/details/gt2etbtcngy.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ybvxxcpd.html

Go:   // 手写循环
来源：http://dali.yangfankeji.com/Article/details/gt2pzmmhvil.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.nanxuanxn.top/Article/details/gt2rjwoihyh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jiagoushi.top/Article/details/gt2vmrkgkpk.html

[D24] 字典 / Map 基本操作
来源：http://dali.cucudq.cn/Article/details/gt2pujkhwmj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ivvv.top/Article/details/gt2wnekwluv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cucudq.cn/Article/details/gt2jczpqsty.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ybcxt.top/Article/details/gt2adptbmkc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gt2lxhtqbed.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.smart0.xyz/Article/details/gt2igcavfob.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.feifeiyinyue.top/Article/details/gt2agkhggir.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xylfe.cn/Article/details/gt2danfzmjf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jyoumei.cn/Article/details/gt2bvaqotyu.html

[D25] Set 集合去重与交并差
来源：http://dali.c1oappe.top/Article/details/gt2zwlbhore.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.9152youxi.cn/Article/details/gt2xyruejqx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.quarkkingdee.top/Article/details/gt2symhkeki.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2eauqiszc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.mhx1999.top/Article/details/gt2okporbxf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ehwqpu.com/Article/details/gt2fvqsrgwc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gaohongyu789.top/Article/details/gt2bfnzmwpv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shuidangran.top/Article/details/gt2bilryptz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yuanzhike.top/Article/details/gt2aqrhrobv.html

[D26] 数组转字符串
来源：http://dali.haohaochexian.top/Article/details/gt2xscajvif.html

Py:   ", ".join(map(str, arr))
来源：http://dali.nwbrower.top/Article/details/gt2tnnjvkbr.html

PHP:  implode(", ", $arr);
来源：http://dali.haohaochexian.top/Article/details/gt2uwfszmsp.html

JS:   arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gt2jdtevved.html

TS:   arr.join(", ")
来源：http://dali.xuetiantiany.cn/Article/details/gt2pkpyfmhj.html

Java: String.join(", ", list)
来源：http://dali.sysykeji.top/Article/details/gt2xjjveggl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yj202588.top/Article/details/gt2lewtbgus.html

Ruby: arr.join(", ")
来源：http://dali.c1oappe.top/Article/details/gt2njotyhfi.html

C#:   string.Join(", ", list)
来源：http://dali.havefunace.top/Article/details/gt2euggemmo.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2jjofcemn.html

E. 字符串处理
来源：http://dali.jinqigfzy.top/Article/details/gt2tvgocgth.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2reermubq.html

[E01] 拼接字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uywllqle.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xinyue.icu/Article/details/gt2fxvsamrd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.gotoacloud.top/Article/details/gt2yupbtrkb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ichlysni.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yvedp.cn/Article/details/gt2nohxwauk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhongyouzk.top/Article/details/gt2kfducyga.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.svipenyu.cn/Article/details/gt2whvzclum.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.guowangkeji.top/Article/details/gt2aiuvgyoe.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gt2esvjvmem.html

[E02] 重复字符串
来源：http://dali.zdqjudy.top/Article/details/gt2puehpxmz.html

Py:   "ab" * 3
来源：http://dali.gotoacloud.top/Article/details/gt2eebisqap.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gotoacloud.top/Article/details/gt2ybfgszcl.html

JS:   "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gt2ekitkvhs.html

TS:   "ab".repeat(3)
来源：http://dali.jinqigufen.top/Article/details/gt2ibinhvmg.html

Java: "ab".repeat(3)
来源：http://dali.hfpthk.cn/Article/details/gt2ckaaczqh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2icecjiqx.html

Ruby: "ab" * 3
来源：http://dali.tian-w.cn/Article/details/gt2wtgdywvs.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zycfv.cn/Article/details/gt2xcpdabkb.html

[E03] 截取子串
来源：http://dali.xziqi.cn/Article/details/gt2gpytovwp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jqgfzy.top/Article/details/gt2ogzsfcpo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gt2dcrqtenx.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.nwbrower.top/Article/details/gt2rajctutc.html

TS:   s.slice(1, 4)
来源：http://dali.sysykeji.top/Article/details/gt2fhuaaycr.html

Java: s.substring(1, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iwqlwswn.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.redwolf501.top/Article/details/gt2brunwfqg.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hammf.cn/Article/details/gt2jfvspyan.html

C#:   s.Substring(1, 3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2camueniu.html

[E04] 查找子串位置
来源：http://dali.hammf.cn/Article/details/gt2bizlsnie.html

Py:   s.find("x");  s.index("x")
来源：http://dali.9152youxi.cn/Article/details/gt2mrmoocdx.html

PHP:  strpos($s, "x");
来源：http://dali.yongpay.top/Article/details/gt2tmxjoocq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.kuanghao11.cn/Article/details/gt2enecavdj.html

TS:   s.indexOf("x")
来源：http://dali.sysykeji.top/Article/details/gt2xuzfypmg.html

Java: s.indexOf("x")
来源：http://dali.birdmap.top/Article/details/gt2eyccscos.html

Go:   strings.Index(s, "x")
来源：http://dali.zhongyouzk.top/Article/details/gt2cokwxtrh.html

Ruby: s.index("x")
来源：http://dali.hfpthk.cn/Article/details/gt2fcnpjmgq.html

C#:   s.IndexOf("x")
来源：http://dali.hysaishi.cn/Article/details/gt2ldmttbuz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yuanzhike.top/Article/details/gt2wzaydmoi.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yangfankeji.com/Article/details/gt2gpohrgfz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.vqdsnc.cn/Article/details/gt2fozqxwfp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sweek.top/Article/details/gt2uofcfclj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zycfv.cn/Article/details/gt2ouerowtp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wotzskhv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jiagoushi.top/Article/details/gt2xqiynhgh.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yuanzhike.top/Article/details/gt2yvvykdqi.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2chxwtbpn.html

[E06] 替换子串
来源：http://dali.cdnleiting.top/Article/details/gt2ndqxuoqj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yj20258888.top/Article/details/gt2vvijphvu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xuanzx.com/Article/details/gt2nubwkgfw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cashguo.top/Article/details/gt2jiehdmxv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gt2wgoyucda.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gt2lbyyzdrp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hnqzz.top/Article/details/gt2nyoflipr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ydzc1.top/Article/details/gt2bozbdush.html

C#:   s.Replace("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gt2aieaposk.html

[E07] 按分隔符拆分
来源：http://dali.svipenyu.cn/Article/details/gt2vscufqwx.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.bjfxy.top/Article/details/gt2riogjlvo.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhengqikj.top/Article/details/gt2uhvgnlpe.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jqgufenzy.top/Article/details/gt2iropthin.html

TS:   s.split(",")
来源：http://dali.tianlin.xyz/Article/details/gt2itbuynla.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.smart0.xyz/Article/details/gt2rxdrbxfz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2nnthsqrf.html

Ruby: s.split(",");  s.split
来源：http://dali.xylfe.cn/Article/details/gt2dvzlabnu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ivvv.top/Article/details/gt2injsskan.html

[E08] 数组按分隔符合并
来源：http://dali.ydzc1.top/Article/details/gt2okxhacmp.html

Py:   ",".join(items)
来源：http://dali.tianlin.xyz/Article/details/gt2rtzkqifl.html

PHP:  implode(",", $items);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2axdwzddw.html

JS:   items.join(",")
来源：http://dali.jianghu66.top/Article/details/gt2ujwizsxr.html

TS:   items.join(",")
来源：http://dali.gaohongyu789.top/Article/details/gt2eucsharj.html

Java: String.join(",", items)
来源：http://dali.xziqi.cn/Article/details/gt2lhvsdsry.html

Go:   strings.Join(items, ",")
来源：http://dali.hfpthk.cn/Article/details/gt2wbiznpsq.html

Ruby: items.join(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2viznwwwe.html

C#:   string.Join(",", items)
来源：http://dali.cqqwz.cn/Article/details/gt2arfaywpp.html

[E09] 去除所有空白字符
来源：http://dali.nanxuanxn.top/Article/details/gt2btzpeqsp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xvojuesv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hnxiangtu.top/Article/details/gt2nzhdduzv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.fengsongda.top/Article/details/gt2powawjcz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.redwolf501.top/Article/details/gt2xufuorvk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.andypj.xyz/Article/details/gt2vzzgezlr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.feifeiyinyue.top/Article/details/gt2niuogkfm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sxryk.cn/Article/details/gt2irrftprh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shangyingyoupin.top/Article/details/gt2jzmlxmai.html

[E10] 左侧补零 / 定长填充
来源：http://dali.fengsongda.top/Article/details/gt2qpnsordd.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gt2oqtovveb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhiwuduotai.top/Article/details/gt2lowqzozm.html

JS:   "7".padStart(3, "0")
来源：http://dali.jyoumei.cn/Article/details/gt2somwbpyf.html

TS:   "7".padStart(3, "0")
来源：http://dali.jqgufenzy.top/Article/details/gt2fyfmeuot.html

Java: String.format("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gt2hqrczbeq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nwbrower.top/Article/details/gt2iynfaokk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gt2souylfrw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cqqwz.cn/Article/details/gt2uuvvnpjq.html

[E11] 反转字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2pdefhymt.html

Py:   s[::-1]
来源：http://dali.jinqigufen.top/Article/details/gt2iuzdvsed.html

PHP:  strrev($s);
来源：http://dali.jqgfzy.top/Article/details/gt2qgsmfzse.html

JS:   [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gt2csiiodnb.html

TS:   [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gt2nfvxzrhe.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.quarkkingdee.top/Article/details/gt2zhwplpcb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cucudq.cn/Article/details/gt2xmcilyqb.html

Ruby: s.reverse
来源：http://dali.snrcjt.cn/Article/details/gt2bkjjyawy.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.0kj1m.cn/Article/details/gt2amhzvdbh.html

[E12] 统计某字符出现次数
来源：http://dali.shzxlz.cn/Article/details/gt2sxmizigp.html

Py:   s.count("a")
来源：http://dali.pengpengdd.cyou/Article/details/gt2dfurxoka.html

PHP:  substr_count($s, "a");
来源：http://dali.yj20258888.top/Article/details/gt2wmhhvaxo.html

JS:   s.split("a").length - 1
来源：http://dali.kuanghao11.cn/Article/details/gt2hrxffezz.html

TS:   s.split("a").length - 1
来源：http://dali.yvedp.cn/Article/details/gt2stbddcum.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.tanke756.top/Article/details/gt2cdtwxzoj.html

Go:   strings.Count(s, "a")
来源：http://dali.jqgufenzy.top/Article/details/gt2gurpyeal.html

Ruby: s.count("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jznzomvw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yongpay.top/Article/details/gt2ivqeltsd.html

[E13] 逐字符遍历
来源：http://dali.chenlongwang.top/Article/details/gt2bwjxilma.html

Py:   for ch in s: print(ch)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2veeqicco.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinqigufen.top/Article/details/gt2baupbpiq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnqzz.top/Article/details/gt2qxtzpajt.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jyoumei.cn/Article/details/gt2aubfsigr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2xekbgmqf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gt2palmoyzn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ydzc1.top/Article/details/gt2xbllshqu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shzxlz.cn/Article/details/gt2pifsblmw.html

[E14] URL 编码与 Base64
来源：http://dali.bjfxy.top/Article/details/gt2jqumccek.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.chenjidiqi.icu/Article/details/gt2idmpezup.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jqgufenzy.top/Article/details/gt2glpcsylb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj202588.top/Article/details/gt2ikorskty.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xinyue.icu/Article/details/gt2jvvdmjnk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zdqjudy.top/Article/details/gt2fqsltqbw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hammf.cn/Article/details/gt2srmrcuhw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zycfv.cn/Article/details/gt2bzqcizpn.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.daria6918.cn/Article/details/gt2utjtnmwr.html

[E15] HTML 转义 / 反转义
来源：http://dali.ybcxt.top/Article/details/gt2xxuvtxov.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.wangdashe.top/Article/details/gt2aqiqbfbu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhengqikj.top/Article/details/gt2sozczdxr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cqqwz.cn/Article/details/gt2hypppbbt.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.wangshuangyany.cn/Article/details/gt2shldyrby.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.tian-w.cn/Article/details/gt2prvusayx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.redwolf501.top/Article/details/gt2etmslgia.html


<!-- 参考信息 -->