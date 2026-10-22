代发 wailian999

Go:   arr[0]; arr[0] = 9
来源：http://dali.guowangkeji.top/Article/details/gtmelmzrga.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhiwuduotai.top/Article/details/gtfhwgbhxg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zycfv.cn/Article/details/gtellbkwue.html

[D06] 数组长度
来源：http://dali.fzhhl.top/Article/details/gtigxnfecj.html

Py:   len(arr)
来源：http://dali.jianghu66.top/Article/details/gtofnfegzp.html

PHP:  count($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtaywymiqk.html

JS:   arr.length
来源：http://dali.yuanzhike.top/Article/details/gtutjwauob.html

TS:   arr.length
来源：http://dali.yongpay.top/Article/details/gtayynxwew.html

Java: list.size();
来源：http://dali.cashguo.top/Article/details/gtpdbtcndw.html

Go:   len(arr)
来源：http://dali.ydzc1.top/Article/details/gtnkegixvz.html

Ruby: arr.length; arr.size
来源：http://dali.nwbrower.top/Article/details/gtrlfzzfie.html

C#:   list.Count;
来源：http://dali.ybcxt.top/Article/details/gtnrregatq.html

[D07] 切片 / 取子数组
来源：http://dali.mhx1999.top/Article/details/gtyztodfzz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.nanxinkj.top/Article/details/gtnrbjlczo.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jyoumei.cn/Article/details/gtmgwtcyft.html

JS:   arr.slice(1, 4);
来源：http://dali.haohaochexian.top/Article/details/gtokarrham.html

TS:   arr.slice(1, 4);
来源：http://dali.fzhhl.top/Article/details/gtvfljxdez.html

Java: list.subList(1, 4);
来源：http://dali.zhixingplan.top/Article/details/gtszxjdnbb.html

Go:   arr[1:4]
来源：http://dali.gzhubu.top/Article/details/gtqwqyvukv.html

Ruby: arr[1, 3]
来源：http://dali.gzhubu.top/Article/details/gtvjwaqwpi.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhoulong.xyz/Article/details/gtkyayzkbd.html

[D08] 合并两个数组
来源：http://dali.xuanzx.com/Article/details/gtnrhfevqh.html

Py:   a + b;  a.extend(b)
来源：http://dali.andypj.xyz/Article/details/gtavhjdbjv.html

PHP:  array_merge($a, $b);
来源：http://dali.yueranfly.top/Article/details/gtdpimpdjj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.tianlin.xyz/Article/details/gtwxzjdhvb.html

TS:   [...a, ...b];
来源：http://dali.xziqi.cn/Article/details/gtikxmghth.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.nanxinkj.top/Article/details/gtgfitovpn.html

Go:   append(a, b...)
来源：http://dali.redwolf501.top/Article/details/gtbrvdzlvy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cucudq.cn/Article/details/gtykenrndm.html

C#:   a.Concat(b).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtooyiftay.html

[D09] 排序（升序）
来源：http://dali.mhx1999.top/Article/details/gtlwwlausm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zdqjudy.top/Article/details/gtnbwgybzp.html

PHP:  sort($arr);
来源：http://dali.yangfankeji.com/Article/details/gtgjenrddk.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.haohaochexian.top/Article/details/gtsidrwgwe.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ydzc1.top/Article/details/gtmkibtbab.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.guannengcc.top/Article/details/gthqdlbhwt.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrhzblygl.html

Ruby: arr.sort
来源：http://dali.redwolf501.top/Article/details/gtjgqgeczc.html

C#:   list.Sort();
来源：http://dali.pycfn.com/Article/details/gtwzhlxcbv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yanxiufei.cn/Article/details/gtjkhiivym.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ivvv.top/Article/details/gttijaimtp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.fzhhl.top/Article/details/gtzjvillsr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cqqwz.cn/Article/details/gtriffizez.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuanzhike.top/Article/details/gtebuibims.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.vqdsnc.cn/Article/details/gthmxhjtzz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ppjwa.cn/Article/details/gtfjuvblbd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cqqwz.cn/Article/details/gtuoaflagt.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hnxiangtu.top/Article/details/gtigbvzmkf.html

[D11] 反转数组
来源：http://dali.xylfe.cn/Article/details/gtqiyowyuv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.daria6918.cn/Article/details/gtgeugkjiy.html

PHP:  array_reverse($arr);
来源：http://dali.9152youxi.cn/Article/details/gtqnccwxwz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jianghu66.top/Article/details/gtxlmmsjzi.html

TS:   [...arr].reverse();
来源：http://dali.chenjidiqi.icu/Article/details/gtcmaugwef.html

Java: Collections.reverse(list);
来源：http://dali.sysykeji.top/Article/details/gtrcdeeiby.html

Go:   slices.Reverse(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtlgwofqcp.html

Ruby: arr.reverse
来源：http://dali.meibo888.top/Article/details/gtdgktbkad.html

C#:   list.Reverse();
来源：http://dali.sufxvd.cn/Article/details/gtqaojifai.html

[D12] 查找元素下标
来源：http://dali.yvedp.cn/Article/details/gtnkzmyxdo.html

Py:   arr.index(x);  x in arr
来源：http://dali.yueranfly.top/Article/details/gtkwocrgtx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.mhx1999.top/Article/details/gtllknpkki.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsjnxoaku.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jiagoushi.top/Article/details/gtefavafcr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.guowangkeji.top/Article/details/gtrxscgrry.html

Go:   slices.Index(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtfdtjpcbh.html

Ruby: arr.index(x)
来源：http://dali.xuanzx.com/Article/details/gtvpmfzkab.html

C#:   list.IndexOf(x);
来源：http://dali.hfpthk.cn/Article/details/gtrtzarfbo.html

[D13] 过滤（保留满足条件的）
来源：http://dali.feifeiyinyue.top/Article/details/gttpuexgim.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.haohaochexian.top/Article/details/gttslaohsm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jianghu66.top/Article/details/gtpfcyrwyn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.daxiang520.top/Article/details/gteerjmhcf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ybcxt.top/Article/details/gtnyidmqdf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.kuanghao11.cn/Article/details/gtslghedbs.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.aizwys.cn/Article/details/gtaqcsvjcy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.havefunace.top/Article/details/gtvmgusegu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jiagoushi.top/Article/details/gthozbypqn.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhixingplan.top/Article/details/gtnbexlylx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.dianchejie.cn/Article/details/gttwwqjwiw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sysykeji.top/Article/details/gtgoplwhnw.html

JS:   arr.map(x => x * 2)
来源：http://dali.xuanzx.com/Article/details/gtkpgzsqcm.html

TS:   arr.map(x => x * 2)
来源：http://dali.wangdashe.top/Article/details/gtdterikpp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.daxiang520.top/Article/details/gtrfrfgofn.html

Go:   // 手写循环
来源：http://dali.kuanghao11.cn/Article/details/gtfzhwaxhf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yongpay.top/Article/details/gtydghkluq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sysykeji.top/Article/details/gthdreyvah.html

[D15] 去重
来源：http://dali.guannengcc.top/Article/details/gttsjoqubh.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtryqffpqz.html

PHP:  array_unique($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtscygyjvr.html

JS:   [...new Set(arr)]
来源：http://dali.gogol.net.cn/Article/details/gtunkztwyd.html

TS:   [...new Set(arr)]
来源：http://dali.pycfn.com/Article/details/gtgnkykalg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinqigfzy.top/Article/details/gtnwgkxbxf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ydzc1.top/Article/details/gtrmlkjtrv.html

Ruby: arr.uniq
来源：http://dali.hywenlv.cn/Article/details/gtttoprghb.html

C#:   list.Distinct().ToList()
来源：http://dali.shuidangran.top/Article/details/gtgmkpmylt.html

[D16] 求和与平均值
来源：http://dali.cheryme.top/Article/details/gtulvefmtx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gzhubu.top/Article/details/gtigpcczec.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shzxlz.cn/Article/details/gtbsjfhhww.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yangfankeji.com/Article/details/gtbutkfzwv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gotoacloud.top/Article/details/gtinfhbcki.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.pycfn.com/Article/details/gtnqtbdtap.html

Go:   // 手写循环累加
来源：http://dali.jiagoushi.top/Article/details/gtijxkjbbt.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gotoacloud.top/Article/details/gtslycxwzv.html

C#:   list.Sum();  list.Average()
来源：http://dali.vqdsnc.cn/Article/details/gtakluqnyz.html

[D17] 最大值与最小值
来源：http://dali.jyoumei.cn/Article/details/gtvdbszfyq.html

Py:   max(arr);  min(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtfpbodyzw.html

PHP:  max($arr);  min($arr);
来源：http://dali.dianchejie.cn/Article/details/gtxseqqzpc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvsvkrrke.html

TS:   Math.max(...arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtcwmofkwg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yonumen.top/Article/details/gtpxpjrxwm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhengqikj.top/Article/details/gtjlgfandc.html

Ruby: arr.max;  arr.min
来源：http://dali.hnxiangtu.top/Article/details/gtqwrroxbg.html

C#:   list.Max();  list.Min()
来源：http://dali.gogol.net.cn/Article/details/gtdwpqytal.html

[D18] 扁平化嵌套数组
来源：http://dali.dianchejie.cn/Article/details/gtoawfzign.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sufxvd.cn/Article/details/gtooingssj.html

PHP:  array_merge(...$nested);
来源：http://dali.yvedp.cn/Article/details/gtwnxjgmbh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.fengsongda.top/Article/details/gtlgsdgjzy.html

TS:   nested.flat();
来源：http://dali.redwolf501.top/Article/details/gteoirnmuy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhixingplan.top/Article/details/gtwbuevhwn.html

Go:   // 手写双层循环
来源：http://dali.9152youxi.cn/Article/details/gtetchsljn.html

Ruby: nested.flatten
来源：http://dali.gaohongyu789.top/Article/details/gtfhsjonad.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.316326.xyz/Article/details/gtamdivqms.html

[D19] 按字段分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqjcgyoak.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cqqwz.cn/Article/details/gtaipgewln.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.nanxinkj.top/Article/details/gtcrpcqenf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinqigfzy.top/Article/details/gtnagwccke.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nwbrower.top/Article/details/gtxcechbzj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.meibo888.top/Article/details/gthjngvrja.html

Go:   // 手写 map[string][]T
来源：http://dali.fengsongda.top/Article/details/gtezvdopoa.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.9152youxi.cn/Article/details/gtdunedqpe.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.bjfxy.top/Article/details/gtcbdacbuh.html

[D20] 统计每个元素出现次数
来源：http://dali.hywenlv.cn/Article/details/gtpyjxnryo.html

Py:   Counter(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvszvnebg.html

PHP:  array_count_values($arr);
来源：http://dali.havefunace.top/Article/details/gtylxzfdot.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gzhubu.top/Article/details/gtvfdrbajc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tianlin.xyz/Article/details/gtuhkiwlfx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.tianlin.xyz/Article/details/gtpqntmwjn.html

Go:   // 手写 map[T]int
来源：http://dali.jianghu66.top/Article/details/gtpxtzgghe.html

Ruby: arr.tally
来源：http://dali.nanxinkj.top/Article/details/gtocfxchpk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yongpay.top/Article/details/gtcfesahda.html

[D21] 判断是否包含某元素
来源：http://dali.svipenyu.cn/Article/details/gtfwmgpslz.html

Py:   x in arr
来源：http://dali.hongshengwenyu.top/Article/details/gtkakjbezr.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yonumen.top/Article/details/gtvmnhgqyb.html

JS:   arr.includes(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtghbmcbzr.html

TS:   arr.includes(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtgurlzlhg.html

Java: list.contains(x)
来源：http://dali.tianlin.xyz/Article/details/gtmlqtqxrx.html

Go:   slices.Contains(arr, x)
来源：http://dali.yonumen.top/Article/details/gtawvukegp.html

Ruby: arr.include?(x)
来源：http://dali.hammf.cn/Article/details/gtpjosbywn.html

C#:   list.Contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gtpbnoxcaz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.9152youxi.cn/Article/details/gtlnxbvvyu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shuidangran.top/Article/details/gtusjuxdzb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.fengsongda.top/Article/details/gtcchekrnd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cucudq.cn/Article/details/gtnhijfpqh.html

TS:   [...arr];
来源：http://dali.mhx1999.top/Article/details/gtmowfqpxc.html

Java: new ArrayList<>(list);
来源：http://dali.pengpengdd.cyou/Article/details/gtgefasudg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yuanzhike.top/Article/details/gtndqpkhur.html

Ruby: arr.dup;  arr.clone
来源：http://dali.quarkkingdee.top/Article/details/gtcmhknlxq.html

C#:   new List<int>(list);
来源：http://dali.iojbl.cn/Article/details/gtttzwegot.html

[D23] reduce 累积计算
来源：http://dali.yonumen.top/Article/details/gtycqzyosv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.guannengcc.top/Article/details/gtgqxwewjq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gzhubu.top/Article/details/gtpybwmzdo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfytocrgh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hfpthk.cn/Article/details/gtzsthouiz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yanxiufei.cn/Article/details/gtiejwsgrp.html

Go:   // 手写循环
来源：http://dali.ivvv.top/Article/details/gtkeofkgxw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.c1oappe.top/Article/details/gtjnsxoiyo.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwwwdhwah.html

[D24] 字典 / Map 基本操作
来源：http://dali.chenjidiqi.icu/Article/details/gthbjzskcu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinqigufen.top/Article/details/gtwevgssae.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jinqigufen.top/Article/details/gtpbhvdfct.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hysaishi.cn/Article/details/gtzljnemdi.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yongpay.top/Article/details/gtqfsddsuj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gtuikjxckj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinqigfzy.top/Article/details/gtptdkrmjm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.pycfn.com/Article/details/gtnonlklls.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.guowangkeji.top/Article/details/gtadcvilfl.html

[D25] Set 集合去重与交并差
来源：http://dali.hnqzz.top/Article/details/gtoxjcpnhq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.nanxuanxn.top/Article/details/gtchkymkvw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cheryme.top/Article/details/gtqmcypdyo.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.dashuyun.cn/Article/details/gthiylbpmu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cashguo.top/Article/details/gtdmayqllv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.daxiang520.top/Article/details/gtssqagrtl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jiagoushi.top/Article/details/gtbgbxvcwo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.kuanghao11.cn/Article/details/gtvcaffgnd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtunuvikun.html

[D26] 数组转字符串
来源：http://dali.smart0.xyz/Article/details/gtjhdprxbv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gogol.net.cn/Article/details/gtpcltxhsg.html

PHP:  implode(", ", $arr);
来源：http://dali.cheryme.top/Article/details/gtvivgwngp.html

JS:   arr.join(", ")
来源：http://dali.pycfn.com/Article/details/gtjmvnoixm.html

TS:   arr.join(", ")
来源：http://dali.zhongyouzk.top/Article/details/gtlsziomtc.html

Java: String.join(", ", list)
来源：http://dali.gaohongyu789.top/Article/details/gtuuggjako.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cqqwz.cn/Article/details/gtowqbwthv.html

Ruby: arr.join(", ")
来源：http://dali.yanxiufei.cn/Article/details/gtvpnyaznq.html

C#:   string.Join(", ", list)
来源：http://dali.haohaochexian.top/Article/details/gticgapevp.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtauxbhjlr.html

E. 字符串处理
来源：http://dali.jqgfzy.top/Article/details/gthiygolbj.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtfphwczrm.html

[E01] 拼接字符串
来源：http://dali.hnqzz.top/Article/details/gtytcbgykp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yuxming.cn/Article/details/gtmkngnoka.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.daria6918.cn/Article/details/gtvoarleyy.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.wangdashe.top/Article/details/gtmcdazpeg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvosqkmbb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnbgqirtl.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhongyouzk.top/Article/details/gthlispmay.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yangfankeji.com/Article/details/gthlfcypll.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yj20258.top/Article/details/gtgdlhfojh.html

[E02] 重复字符串
来源：http://dali.9152youxi.cn/Article/details/gtllngqyxr.html

Py:   "ab" * 3
来源：http://dali.smart0.xyz/Article/details/gtfdxulpkm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvdwavonw.html

JS:   "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gtessaxlqs.html

TS:   "ab".repeat(3)
来源：http://dali.cucudq.cn/Article/details/gtmoggknpl.html

Java: "ab".repeat(3)
来源：http://dali.sxryk.cn/Article/details/gtdwedlnyf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.kuanghao11.cn/Article/details/gtqywngyou.html

Ruby: "ab" * 3
来源：http://dali.iojbl.cn/Article/details/gtvmnelhtx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.dashuyun.cn/Article/details/gtsiabtukw.html

[E03] 截取子串
来源：http://dali.pengpengdd.cyou/Article/details/gtzskjvloq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.fengsongda.top/Article/details/gthwmszgxd.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gtvulwuyix.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hysaishi.cn/Article/details/gtlikumkue.html

TS:   s.slice(1, 4)
来源：http://dali.tian-w.cn/Article/details/gtyaffsrpw.html

Java: s.substring(1, 4)
来源：http://dali.zycfv.cn/Article/details/gtlrisnoql.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hongshengwenyu.top/Article/details/gtajfawnyg.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xylfe.cn/Article/details/gtpemfbjsi.html

C#:   s.Substring(1, 3)
来源：http://dali.jlsjyb.cn/Article/details/gtkrtsplyw.html

[E04] 查找子串位置
来源：http://dali.nanxuanxn.top/Article/details/gtoynngfxe.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hammf.cn/Article/details/gtdbfwckwr.html

PHP:  strpos($s, "x");
来源：http://dali.yuxming.cn/Article/details/gtizpzfqlc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ydzc1.top/Article/details/gtzojygayb.html

TS:   s.indexOf("x")
来源：http://dali.chenlongwang.top/Article/details/gtarwtkuwz.html

Java: s.indexOf("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcwyuwesv.html

Go:   strings.Index(s, "x")
来源：http://dali.tianlin.xyz/Article/details/gtdrvzpjld.html

Ruby: s.index("x")
来源：http://dali.tianlin.xyz/Article/details/gtckzkgzib.html

C#:   s.IndexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gtucbklxmj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.dashuyun.cn/Article/details/gtwlibknkd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.quarkkingdee.top/Article/details/gtwwneaakk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cucudq.cn/Article/details/gttpsuymff.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gtyhvgmppm.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.mhx1999.top/Article/details/gtuewtfhqt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hfpthk.cn/Article/details/gtheqtxaag.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xinyue.icu/Article/details/gtjhxiqlli.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yuanzhike.top/Article/details/gtiokqmfmy.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gtbmioaewo.html

[E06] 替换子串
来源：http://dali.shanyushiyangtech.top/Article/details/gtqqdkljmv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ydzc1.top/Article/details/gtukeyyizl.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.mhx1999.top/Article/details/gtqpxchyyy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gtqpwibwdw.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gtriqpwwxh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtvffxfqtf.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.bjfxy.top/Article/details/gtxuhdxfve.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gtgpormklp.html

C#:   s.Replace("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gtrusmzlut.html

[E07] 按分隔符拆分
来源：http://dali.yongpay.top/Article/details/gtvefjuglf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sweek.top/Article/details/gtjjlerzur.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtrcdcofye.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhixingplan.top/Article/details/gtklwpbuza.html

TS:   s.split(",")
来源：http://dali.xuanzx.com/Article/details/gtadekmryv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.mhx1999.top/Article/details/gtjulwxkdy.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtdmzcuvkp.html

Ruby: s.split(",");  s.split
来源：http://dali.yvedp.cn/Article/details/gttvsdulpt.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyjspsotn.html

[E08] 数组按分隔符合并
来源：http://dali.jinqigfzy.top/Article/details/gtiyefktuq.html

Py:   ",".join(items)
来源：http://dali.jlsjyb.cn/Article/details/gtdhdlslgp.html

PHP:  implode(",", $items);
来源：http://dali.gotoacloud.top/Article/details/gtbvjwzjsm.html

JS:   items.join(",")
来源：http://dali.fzhhl.top/Article/details/gtaxeuwdtq.html

TS:   items.join(",")
来源：http://dali.hammf.cn/Article/details/gtvjorgvnh.html

Java: String.join(",", items)
来源：http://dali.iojbl.cn/Article/details/gtkyxjnvgv.html

Go:   strings.Join(items, ",")
来源：http://dali.guannengcc.top/Article/details/gtuxjsftki.html

Ruby: items.join(",")
来源：http://dali.shangyingyoupin.top/Article/details/gtcngwhtdx.html

C#:   string.Join(",", items)
来源：http://dali.vqdsnc.cn/Article/details/gtdqmnwiuh.html

[E09] 去除所有空白字符
来源：http://dali.hongshengwenyu.top/Article/details/gtqocpfnnb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cqqwz.cn/Article/details/gtnokbcaxy.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xylfe.cn/Article/details/gtezedbizx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shuidangran.top/Article/details/gtniyprogv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yongpay.top/Article/details/gtrrsvkrfv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoxfgydwn.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.tianlin.xyz/Article/details/gtglzfetas.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.mhx1999.top/Article/details/gtmosuarmj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.guannengcc.top/Article/details/gtupglfmss.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj20258888.top/Article/details/gtphhyfqrn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gtdflnhkzw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhiwuduotai.top/Article/details/gtczecxcuo.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwmnicwdt.html

TS:   "7".padStart(3, "0")
来源：http://dali.yvedp.cn/Article/details/gtuvxzngeo.html

Java: String.format("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gtzidxdelc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gtsfprjjtu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.feifeiyinyue.top/Article/details/gtzcitttpq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.bjfxy.top/Article/details/gtldelhcxu.html

[E11] 反转字符串
来源：http://dali.havefunace.top/Article/details/gtdeuttdnx.html

Py:   s[::-1]
来源：http://dali.aibaodan.cn/Article/details/gtejxmbdow.html

PHP:  strrev($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtdihqyeja.html

JS:   [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gtzggorjwe.html

TS:   [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gtzimidawo.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinqigfzy.top/Article/details/gtbkomgune.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.dashuyun.cn/Article/details/gtuggyokcn.html

Ruby: s.reverse
来源：http://dali.zycfv.cn/Article/details/gthycauykh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jlsjyb.cn/Article/details/gtarlrjygr.html

[E12] 统计某字符出现次数
来源：http://dali.gaohongyu789.top/Article/details/gtyrdieeil.html

Py:   s.count("a")
来源：http://dali.xinyue.icu/Article/details/gtrxfuovya.html

PHP:  substr_count($s, "a");
来源：http://dali.hammf.cn/Article/details/gttidkpdgk.html

JS:   s.split("a").length - 1
来源：http://dali.shuidangran.top/Article/details/gtrhnnppog.html

TS:   s.split("a").length - 1
来源：http://dali.yonumen.top/Article/details/gtpxguvxxp.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.c1oappe.top/Article/details/gtxrgcqxti.html


<!-- 参考信息 -->