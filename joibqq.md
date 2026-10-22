代发 wailian999

C#:   list.GetRange(1, 3);
来源：http://dali.ehwqpu.com/Article/details/gtqdwufzpv.html

[D08] 合并两个数组
来源：http://dali.ppjwa.cn/Article/details/gtfsjftccj.html

Py:   a + b;  a.extend(b)
来源：http://dali.hfpthk.cn/Article/details/gtikjgevmj.html

PHP:  array_merge($a, $b);
来源：http://dali.yanxiufei.cn/Article/details/gtqzolcqjo.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.andypj.xyz/Article/details/gtyhgwlgxr.html

TS:   [...a, ...b];
来源：http://dali.yangfankeji.com/Article/details/gtikjisjzr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sufxvd.cn/Article/details/gtedhafldk.html

Go:   append(a, b...)
来源：http://dali.sufxvd.cn/Article/details/gtsadixcbe.html

Ruby: a + b;  a.concat(b)
来源：http://dali.nanxinkj.top/Article/details/gtiwjcdnsj.html

C#:   a.Concat(b).ToList()
来源：http://dali.nwbrower.top/Article/details/gtbdlngwze.html

[D09] 排序（升序）
来源：http://dali.yvedp.cn/Article/details/gtpxajgfim.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuxming.cn/Article/details/gtvsptlgdp.html

PHP:  sort($arr);
来源：http://dali.hammf.cn/Article/details/gtqusbwjod.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.wangdashe.top/Article/details/gtibnygaon.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ivvv.top/Article/details/gtyvwuvuvn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hongshengwenyu.top/Article/details/gtqtabrnyk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtmrckccyd.html

Ruby: arr.sort
来源：http://dali.yj20258.top/Article/details/gtbaydyjta.html

C#:   list.Sort();
来源：http://dali.dianchejie.cn/Article/details/gtjyibrbku.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yj202588.top/Article/details/gtiqdwlshr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhixingplan.top/Article/details/gtppvwolfc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hfpthk.cn/Article/details/gtfizpaoiq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gaohongyu789.top/Article/details/gtlfjvasec.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tianlin.xyz/Article/details/gtdfgarbph.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jqgfzy.top/Article/details/gtgmeuptpu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.feifeiyinyue.top/Article/details/gtgauvwphi.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shuidangran.top/Article/details/gtvzjrwwkc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shangyingyoupin.top/Article/details/gtrrsqgjcz.html

[D11] 反转数组
来源：http://dali.guowangkeji.top/Article/details/gttxosrpyj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinqigfzy.top/Article/details/gtqgogxbjr.html

PHP:  array_reverse($arr);
来源：http://dali.nanxinkj.top/Article/details/gtgkgrkbce.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zdqjudy.top/Article/details/gtrgqsbcyn.html

TS:   [...arr].reverse();
来源：http://dali.havefunace.top/Article/details/gtyxqznmdl.html

Java: Collections.reverse(list);
来源：http://dali.smart0.xyz/Article/details/gthwvmkbza.html

Go:   slices.Reverse(arr)
来源：http://dali.nanxinkj.top/Article/details/gthuoxmwsf.html

Ruby: arr.reverse
来源：http://dali.gotoacloud.top/Article/details/gthfrsidgd.html

C#:   list.Reverse();
来源：http://dali.iojbl.cn/Article/details/gtkksvoozn.html

[D12] 查找元素下标
来源：http://dali.haohaochexian.top/Article/details/gtisaxanlv.html

Py:   arr.index(x);  x in arr
来源：http://dali.xuetiantiany.cn/Article/details/gtuvvhsvpb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtulyzmcnj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigufen.top/Article/details/gtgttbubcz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.andypj.xyz/Article/details/gtobmwqjzv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sweek.top/Article/details/gtnlmnqlsq.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtokappxhi.html

Ruby: arr.index(x)
来源：http://dali.nwbrower.top/Article/details/gtjentwsna.html

C#:   list.IndexOf(x);
来源：http://dali.xinyue.icu/Article/details/gtfuvmkdfr.html

[D13] 过滤（保留满足条件的）
来源：http://dali.snrcjt.cn/Article/details/gtsxgxxims.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhoulong.xyz/Article/details/gtsssgbdtx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ydzc1.top/Article/details/gtiktueeze.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ivvv.top/Article/details/gtmdehvkui.html

TS:   arr.filter(x => x > 3)
来源：http://dali.quarkkingdee.top/Article/details/gtolxhxzwc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.mhx1999.top/Article/details/gteemtavoe.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ivvv.top/Article/details/gtdbdpyfsw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhongyouzk.top/Article/details/gtcqsxjwwe.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjaikhjzh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.bjfxy.top/Article/details/gtuweqktxx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yongpay.top/Article/details/gtgdodudeu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhongyouzk.top/Article/details/gtocxzlymo.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfagaelxp.html

TS:   arr.map(x => x * 2)
来源：http://dali.xinyue.icu/Article/details/gtzjpsmoeb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.nanxinkj.top/Article/details/gtkfbfqeqo.html

Go:   // 手写循环
来源：http://dali.kuanghao11.cn/Article/details/gtphssjxmn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shuidangran.top/Article/details/gtjqnyvrqq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtvqgcsfur.html

[D15] 去重
来源：http://dali.chenjidiqi.icu/Article/details/gtzjsigwss.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sysykeji.top/Article/details/gtagrkvspg.html

PHP:  array_unique($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtnukensxe.html

JS:   [...new Set(arr)]
来源：http://dali.gaohongyu789.top/Article/details/gtbmqdiebb.html

TS:   [...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gtefkvpnoi.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhoulong.xyz/Article/details/gtcnhrspqw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.fzhhl.top/Article/details/gtglrahory.html

Ruby: arr.uniq
来源：http://dali.quarkkingdee.top/Article/details/gtfyucbcrb.html

C#:   list.Distinct().ToList()
来源：http://dali.gotoacloud.top/Article/details/gtnjbhqejr.html

[D16] 求和与平均值
来源：http://dali.havefunace.top/Article/details/gtmfodxwxe.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtimtqfhqy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtxalsspdh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangdashe.top/Article/details/gtbdvpylvr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.birdmap.top/Article/details/gtchquqwtk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.pycfn.com/Article/details/gtnewripik.html

Go:   // 手写循环累加
来源：http://dali.hnqzz.top/Article/details/gtrziakwit.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jlsjyb.cn/Article/details/gtpymtsqbf.html

C#:   list.Sum();  list.Average()
来源：http://dali.sxryk.cn/Article/details/gtowcyimnv.html

[D17] 最大值与最小值
来源：http://dali.yongpay.top/Article/details/gtkdlytsir.html

Py:   max(arr);  min(arr)
来源：http://dali.c1oappe.top/Article/details/gtmnnndyve.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhixingplan.top/Article/details/gttjaalhnl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj20258888.top/Article/details/gtjdsugcpk.html

TS:   Math.max(...arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtamejczfi.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gtlrrwsiqr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.guowangkeji.top/Article/details/gtevrgphuq.html

Ruby: arr.max;  arr.min
来源：http://dali.hywenlv.cn/Article/details/gtiralhkdr.html

C#:   list.Max();  list.Min()
来源：http://dali.ehwqpu.com/Article/details/gtaxuliqhl.html

[D18] 扁平化嵌套数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwwbqklkg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sweek.top/Article/details/gtmwxeewyq.html

PHP:  array_merge(...$nested);
来源：http://dali.yuxming.cn/Article/details/gtnixrhiqi.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinqigfzy.top/Article/details/gtsmsdckqn.html

TS:   nested.flat();
来源：http://dali.shanyushiyangtech.top/Article/details/gtddmyoiyy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.9152youxi.cn/Article/details/gttuucjrhh.html

Go:   // 手写双层循环
来源：http://dali.hfpthk.cn/Article/details/gttserdmyn.html

Ruby: nested.flatten
来源：http://dali.tanke756.top/Article/details/gteepnezcj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zdqjudy.top/Article/details/gtzwcncbfb.html

[D19] 按字段分组
来源：http://dali.tianlin.xyz/Article/details/gtfhjlobnp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtrrdcjfrd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ybcxt.top/Article/details/gtrizakygt.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zdqjudy.top/Article/details/gthhyfqolw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.aizwys.cn/Article/details/gtmxrkdknw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xziqi.cn/Article/details/gthqymvuge.html

Go:   // 手写 map[string][]T
来源：http://dali.meibo888.top/Article/details/gtqaqymqmr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gogol.net.cn/Article/details/gtxirgqttd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkbkpxcla.html

[D20] 统计每个元素出现次数
来源：http://dali.aizwys.cn/Article/details/gtclygheqk.html

Py:   Counter(arr)
来源：http://dali.xziqi.cn/Article/details/gthbcdmvon.html

PHP:  array_count_values($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtcyyixwbp.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.svipenyu.cn/Article/details/gtwmvukxjf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fengsongda.top/Article/details/gtmmysaxjz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shangyingyoupin.top/Article/details/gtgxsgmkeb.html

Go:   // 手写 map[T]int
来源：http://dali.dashuyun.cn/Article/details/gtnblqtauq.html

Ruby: arr.tally
来源：http://dali.zhiwuduotai.top/Article/details/gtdgisufli.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yuxming.cn/Article/details/gthzgaclgf.html

[D21] 判断是否包含某元素
来源：http://dali.havefunace.top/Article/details/gtyyjqzeov.html

Py:   x in arr
来源：http://dali.nanxuanxn.top/Article/details/gttpllzzxj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.0kj1m.cn/Article/details/gtfcctdgzc.html

JS:   arr.includes(x)
来源：http://dali.iojbl.cn/Article/details/gtwdlbcidb.html

TS:   arr.includes(x)
来源：http://dali.yueranfly.top/Article/details/gtprroubcg.html

Java: list.contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoglxqnie.html

Go:   slices.Contains(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtjirzbdhr.html

Ruby: arr.include?(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthhqcxrko.html

C#:   list.Contains(x)
来源：http://dali.guannengcc.top/Article/details/gtxrdeaiiy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yvedp.cn/Article/details/gtheqaxmch.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xuanzx.com/Article/details/gtmgxdnevx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jiagoushi.top/Article/details/gtesmitmjz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.iojbl.cn/Article/details/gthhkzkjxq.html

TS:   [...arr];
来源：http://dali.mhx1999.top/Article/details/gtrivvmdhc.html

Java: new ArrayList<>(list);
来源：http://dali.jqgufenzy.top/Article/details/gttoiouiwb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.snrcjt.cn/Article/details/gteooysxwq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jinqigfzy.top/Article/details/gtkbutssla.html

C#:   new List<int>(list);
来源：http://dali.pycfn.com/Article/details/gteuvswgxn.html

[D23] reduce 累积计算
来源：http://dali.xuanzx.com/Article/details/gtoytgvvbu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.316326.xyz/Article/details/gtxxzbrmmj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.aibaodan.cn/Article/details/gtgvundxzs.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenlongwang.top/Article/details/gtayhwwjmp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tanke756.top/Article/details/gtvknqutnl.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sweek.top/Article/details/gtsgpidcvi.html

Go:   // 手写循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiyxtgupb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.nanxuanxn.top/Article/details/gtbzmgetql.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.wangdashe.top/Article/details/gtoeajtxeh.html

[D24] 字典 / Map 基本操作
来源：http://dali.sufxvd.cn/Article/details/gtlgvkmybb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jlsjyb.cn/Article/details/gtcysgossj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jqgufenzy.top/Article/details/gtgzmxacyg.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtydsrqsot.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gtwcpdwqqs.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ppjwa.cn/Article/details/gtdfqfqxyh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.chenzaomai.com/Article/details/gtqxiclymg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yongpay.top/Article/details/gtgeltftra.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqafwkaso.html

[D25] Set 集合去重与交并差
来源：http://dali.smart0.xyz/Article/details/gtrermhuuj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gaohongyu789.top/Article/details/gtailoamhh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hywenlv.cn/Article/details/gtmjrgasbk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cdnleiting.top/Article/details/gtcmchghbg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.svipenyu.cn/Article/details/gtgpavbycq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xuanzx.com/Article/details/gtcthjrujg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtogdbpknb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hnxiangtu.top/Article/details/gtfysijcbs.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhixingplan.top/Article/details/gtcfeavwqn.html

[D26] 数组转字符串
来源：http://dali.guannengcc.top/Article/details/gteoingpvn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hongshengwenyu.top/Article/details/gtnlhvsmlr.html

PHP:  implode(", ", $arr);
来源：http://dali.kuanghao11.cn/Article/details/gthtjlqncp.html

JS:   arr.join(", ")
来源：http://dali.cashguo.top/Article/details/gtaafndyrq.html

TS:   arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gtkrksibru.html

Java: String.join(", ", list)
来源：http://dali.nwbrower.top/Article/details/gtdzpftuxl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.tianlin.xyz/Article/details/gtjtkvbara.html

Ruby: arr.join(", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtegymnagj.html

C#:   string.Join(", ", list)
来源：http://dali.zhiwuduotai.top/Article/details/gtrocmykpn.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtanjwrahs.html

E. 字符串处理
来源：http://dali.zhixingplan.top/Article/details/gtrvayyvhd.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtqklorsgf.html

[E01] 拼接字符串
来源：http://dali.ppjwa.cn/Article/details/gtybovzroq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.aizwys.cn/Article/details/gtkxawacdf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.chenlongwang.top/Article/details/gtxippuovb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.0kj1m.cn/Article/details/gtgfwizeos.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtrxyozeio.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.nanxuanxn.top/Article/details/gtklyxfirb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hysaishi.cn/Article/details/gtuptfdtie.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sysykeji.top/Article/details/gtxkwhiflc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gttjufnbmy.html

[E02] 重复字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtmmsnfxio.html

Py:   "ab" * 3
来源：http://dali.cashguo.top/Article/details/gtfmylznae.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gaohongyu789.top/Article/details/gtwmklfkua.html

JS:   "ab".repeat(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiutuoili.html

TS:   "ab".repeat(3)
来源：http://dali.andypj.xyz/Article/details/gtzxvacgsl.html

Java: "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gtfeuwewuf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.bjfxy.top/Article/details/gtqtzxpimb.html

Ruby: "ab" * 3
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzmefbbxd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.tianlin.xyz/Article/details/gthpgayuif.html

[E03] 截取子串
来源：http://dali.xuetiantiany.cn/Article/details/gtexylypud.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sysykeji.top/Article/details/gtpdohclji.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.guowangkeji.top/Article/details/gtwxorotzr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.tian-w.cn/Article/details/gtqksjubkd.html

TS:   s.slice(1, 4)
来源：http://dali.xylfe.cn/Article/details/gtuakagtlw.html

Java: s.substring(1, 4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjigqpaal.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.aizwys.cn/Article/details/gtwetkbtlh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hnqzz.top/Article/details/gtammoegmp.html

C#:   s.Substring(1, 3)
来源：http://dali.xziqi.cn/Article/details/gtvdthaiwq.html

[E04] 查找子串位置
来源：http://dali.xuanzx.com/Article/details/gtoxwyggfu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hysaishi.cn/Article/details/gtuiitgbew.html

PHP:  strpos($s, "x");
来源：http://dali.ybcxt.top/Article/details/gthltbfoss.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.chenjidiqi.icu/Article/details/gtzooiukqv.html

TS:   s.indexOf("x")
来源：http://dali.ppjwa.cn/Article/details/gtjqrogtmx.html

Java: s.indexOf("x")
来源：http://dali.yongpay.top/Article/details/gtexjfzzol.html

Go:   strings.Index(s, "x")
来源：http://dali.zhoulong.xyz/Article/details/gthodletli.html

Ruby: s.index("x")
来源：http://dali.yongpay.top/Article/details/gthdqtdidn.html

C#:   s.IndexOf("x")
来源：http://dali.xinyue.icu/Article/details/gtyqvuphho.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.guowangkeji.top/Article/details/gtnnkabite.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.sxryk.cn/Article/details/gtkbgglphj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shuidangran.top/Article/details/gtvnbcbdyz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dashuyun.cn/Article/details/gtyoyzhjry.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.redwolf501.top/Article/details/gttocmgmls.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tian-w.cn/Article/details/gtpkwvtyqg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.vqdsnc.cn/Article/details/gtadywipmm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.haohaochexian.top/Article/details/gtgprugqpq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.birdmap.top/Article/details/gthlpnzikq.html

[E06] 替换子串
来源：http://dali.guannengcc.top/Article/details/gtgcujpfbt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jqgufenzy.top/Article/details/gtbwhjocqz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.kuanghao11.cn/Article/details/gtttirggxy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnqzz.top/Article/details/gtggzikorj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtaqzajyxk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtxlfgsfvx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinqigufen.top/Article/details/gttkcpqgqg.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtlzmivnbh.html

C#:   s.Replace("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtcwhoqpys.html

[E07] 按分隔符拆分
来源：http://dali.hammf.cn/Article/details/gtaxrieyci.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jqgufenzy.top/Article/details/gtbbsrlqdl.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtmpwwavig.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hywenlv.cn/Article/details/gtcoqkchtw.html

TS:   s.split(",")
来源：http://dali.c1oappe.top/Article/details/gtifinojkq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cdnleiting.top/Article/details/gtcwkcvnti.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gotoacloud.top/Article/details/gtvimdeeys.html

Ruby: s.split(",");  s.split
来源：http://dali.guowangkeji.top/Article/details/gtsbefrvat.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jianghu66.top/Article/details/gttqpyocge.html

[E08] 数组按分隔符合并
来源：http://dali.chenlongwang.top/Article/details/gthrwabxcg.html

Py:   ",".join(items)
来源：http://dali.sxryk.cn/Article/details/gtwbeausij.html

PHP:  implode(",", $items);
来源：http://dali.zhixingplan.top/Article/details/gtqhruhegz.html

JS:   items.join(",")
来源：http://dali.cucudq.cn/Article/details/gtiwppbzth.html

TS:   items.join(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaphmvbdh.html

Java: String.join(",", items)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlyhjcyrg.html

Go:   strings.Join(items, ",")
来源：http://dali.jlsjyb.cn/Article/details/gtfyvxnevs.html

Ruby: items.join(",")
来源：http://dali.tanke756.top/Article/details/gtqdiuxbxq.html

C#:   string.Join(",", items)
来源：http://dali.svipenyu.cn/Article/details/gtmbpofwtr.html

[E09] 去除所有空白字符
来源：http://dali.zdqjudy.top/Article/details/gtdjvbdyyl.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinqigufen.top/Article/details/gtdoccwxgo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yuanzhike.top/Article/details/gtmtqjaeyg.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhengqikj.top/Article/details/gtdaacdxku.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.meibo888.top/Article/details/gtdffkeccp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.316326.xyz/Article/details/gtzhxrkthd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jlsjyb.cn/Article/details/gteovdpymu.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.wangdashe.top/Article/details/gtsxavajmc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.kuanghao11.cn/Article/details/gthsnbakao.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yonumen.top/Article/details/gtwuyhdkgd.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gttwvqbvbu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.birdmap.top/Article/details/gtuodlpwny.html

JS:   "7".padStart(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gterkoesit.html

TS:   "7".padStart(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gtgxfyqtns.html

Java: String.format("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gtdtesdjiy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sxryk.cn/Article/details/gtrbupsfmo.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gtbvsmbleh.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.9152youxi.cn/Article/details/gtfjwlsblc.html

[E11] 反转字符串
来源：http://dali.yangfankeji.com/Article/details/gtfupukijv.html

Py:   s[::-1]
来源：http://dali.yvedp.cn/Article/details/gtyyewzgch.html

PHP:  strrev($s);
来源：http://dali.pycfn.com/Article/details/gtpkqlxqce.html

JS:   [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlhtuksdf.html

TS:   [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoglqighs.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.feifeiyinyue.top/Article/details/gthyucesjp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenlongwang.top/Article/details/gtwxddrxfn.html

Ruby: s.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtksbasjkq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hammf.cn/Article/details/gtunjzvgrc.html

[E12] 统计某字符出现次数
来源：http://dali.yuanzhike.top/Article/details/gtghuczwoy.html

Py:   s.count("a")
来源：http://dali.jqgufenzy.top/Article/details/gtlovloiya.html

PHP:  substr_count($s, "a");
来源：http://dali.cdnleiting.top/Article/details/gtqdqcgred.html

JS:   s.split("a").length - 1
来源：http://dali.daria6918.cn/Article/details/gtxxuqspyt.html

TS:   s.split("a").length - 1
来源：http://dali.hnqzz.top/Article/details/gtwrqnmmud.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jianghu66.top/Article/details/gtkxvebakb.html

Go:   strings.Count(s, "a")
来源：http://dali.ybcxt.top/Article/details/gtbkzzxqod.html

Ruby: s.count("a")
来源：http://dali.yj20258.top/Article/details/gtbjtojhcn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yongpay.top/Article/details/gtcnxxrckz.html

[E13] 逐字符遍历
来源：http://dali.iojbl.cn/Article/details/gtngkjrulj.html

Py:   for ch in s: print(ch)
来源：http://dali.0kj1m.cn/Article/details/gtvaiskftv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cheryme.top/Article/details/gtqqbcrpaa.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigufen.top/Article/details/gtjnlnulfl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnqzz.top/Article/details/gtbzivzwvo.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jiagoushi.top/Article/details/gtxdevzixe.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhixingplan.top/Article/details/gtlreakjrc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sweek.top/Article/details/gtbxyycgao.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yongpay.top/Article/details/gtjrergles.html

[E14] URL 编码与 Base64
来源：http://dali.jinghuilouyu.cn/Article/details/gtzafnxfkr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ydzc1.top/Article/details/gtfqzrhtoa.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhoulong.xyz/Article/details/gtzglnlwts.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xuetiantiany.cn/Article/details/gtizdjthqy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tanke756.top/Article/details/gtrqxdoacl.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuqaetcey.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.bjfxy.top/Article/details/gthoovbvmw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.pycfn.com/Article/details/gthcdeowyu.html


<!-- 参考信息 -->