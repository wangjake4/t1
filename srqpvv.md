代发 wailian999

[D07] 切片 / 取子数组
来源：http://dali.daxiang520.top/Article/details/gt2fytqgctp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hammf.cn/Article/details/gt2kidgahgo.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yuxming.cn/Article/details/gt2xwezfdyc.html

JS:   arr.slice(1, 4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dthymbri.html

TS:   arr.slice(1, 4);
来源：http://dali.daxiang520.top/Article/details/gt2sjnjvhac.html

Java: list.subList(1, 4);
来源：http://dali.xziqi.cn/Article/details/gt2dlirdfxh.html

Go:   arr[1:4]
来源：http://dali.sysykeji.top/Article/details/gt2vbkmegqs.html

Ruby: arr[1, 3]
来源：http://dali.smart0.xyz/Article/details/gt2vaxjxoge.html

C#:   list.GetRange(1, 3);
来源：http://dali.cqqwz.cn/Article/details/gt2mujwryty.html

[D08] 合并两个数组
来源：http://dali.yuanzhike.top/Article/details/gt2rlxsahpv.html

Py:   a + b;  a.extend(b)
来源：http://dali.jlsjyb.cn/Article/details/gt2ltfyxiap.html

PHP:  array_merge($a, $b);
来源：http://dali.yanxiufei.cn/Article/details/gt2umcinokm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sweek.top/Article/details/gt2xfczczab.html

TS:   [...a, ...b];
来源：http://dali.redwolf501.top/Article/details/gt2wymigygk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bxnckqmd.html

Go:   append(a, b...)
来源：http://dali.tanke756.top/Article/details/gt2nlyaijfk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.316326.xyz/Article/details/gt2fsjnwhgk.html

C#:   a.Concat(b).ToList()
来源：http://dali.dashuyun.cn/Article/details/gt2nipbglne.html

[D09] 排序（升序）
来源：http://dali.tanke756.top/Article/details/gt2psnshhyy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.mhx1999.top/Article/details/gt2penrvjkf.html

PHP:  sort($arr);
来源：http://dali.jianghu66.top/Article/details/gt2kyscipcm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yj20258.top/Article/details/gt2yfaghelo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.vqdsnc.cn/Article/details/gt2yhhnihmj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhengqikj.top/Article/details/gt2hpdydhkr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tylfgfho.html

Ruby: arr.sort
来源：http://dali.sxryk.cn/Article/details/gt2hlntlopu.html

C#:   list.Sort();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2megqjxgv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hnqzz.top/Article/details/gt2cabjqvva.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.guowangkeji.top/Article/details/gt2yhsgwsqy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenlongwang.top/Article/details/gt2cxruvptx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zdqjudy.top/Article/details/gt2rwdcdedl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.0kj1m.cn/Article/details/gt2fgafhzqu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2htlwmodo.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shzxlz.cn/Article/details/gt2nbxutssk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.tianlin.xyz/Article/details/gt2bqduckjs.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.aibaodan.cn/Article/details/gt2azfxbwsv.html

[D11] 反转数组
来源：http://dali.zhongyouzk.top/Article/details/gt2kvzjembc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinqigfzy.top/Article/details/gt2gpmwlipk.html

PHP:  array_reverse($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qdrkwfxe.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gogol.net.cn/Article/details/gt2soxtucez.html

TS:   [...arr].reverse();
来源：http://dali.aibaodan.cn/Article/details/gt2dtiyppoy.html

Java: Collections.reverse(list);
来源：http://dali.ivvv.top/Article/details/gt2rcjpwknj.html

Go:   slices.Reverse(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2oxuftvlh.html

Ruby: arr.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tyramtpl.html

C#:   list.Reverse();
来源：http://dali.dashuyun.cn/Article/details/gt2jprgysli.html

[D12] 查找元素下标
来源：http://dali.jyoumei.cn/Article/details/gt2ctiqshnj.html

Py:   arr.index(x);  x in arr
来源：http://dali.hongshengwenyu.top/Article/details/gt2ieyvukvs.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2thpnlzjn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxinkj.top/Article/details/gt2gjmqbwca.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuxming.cn/Article/details/gt2rzkcgobd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yueranfly.top/Article/details/gt2lusglhpq.html

Go:   slices.Index(arr, x)
来源：http://dali.mhx1999.top/Article/details/gt2wiizdsbx.html

Ruby: arr.index(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rtaagmqx.html

C#:   list.IndexOf(x);
来源：http://dali.havefunace.top/Article/details/gt2udadsqhz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.andypj.xyz/Article/details/gt2mhdzmyls.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cdnleiting.top/Article/details/gt2faeezlyo.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yj20258888.top/Article/details/gt2wvlaqgdo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zmqeacki.html

TS:   arr.filter(x => x > 3)
来源：http://dali.chenlongwang.top/Article/details/gt2fhulxfoa.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2zzndnklh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yongpay.top/Article/details/gt2porgtfdo.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mjgmwjxe.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gt2maoyqmew.html

[D14] 映射转换（每个元素变形）
来源：http://dali.kuanghao11.cn/Article/details/gt2gppsabyo.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hnxiangtu.top/Article/details/gt2ahzdvnhi.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jyoumei.cn/Article/details/gt2sjstjhpm.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2yyfrqsgy.html

TS:   arr.map(x => x * 2)
来源：http://dali.nanxinkj.top/Article/details/gt2iskzkvbg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.nanxuanxn.top/Article/details/gt2fskpboao.html

Go:   // 手写循环
来源：http://dali.zycfv.cn/Article/details/gt2irrxzdeb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2iewajmej.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yitsgcrd.html

[D15] 去重
来源：http://dali.sysykeji.top/Article/details/gt2mnylqmvy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.chenzaomai.com/Article/details/gt2zwoguxem.html

PHP:  array_unique($arr);
来源：http://dali.yuanzhike.top/Article/details/gt2yottohqo.html

JS:   [...new Set(arr)]
来源：http://dali.xinyue.icu/Article/details/gt2qixdzwdq.html

TS:   [...new Set(arr)]
来源：http://dali.mhx1999.top/Article/details/gt2qyaytslg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.svipenyu.cn/Article/details/gt2ixcooorl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hammf.cn/Article/details/gt2qywalxmx.html

Ruby: arr.uniq
来源：http://dali.smart0.xyz/Article/details/gt2nqtohlrd.html

C#:   list.Distinct().ToList()
来源：http://dali.tanke756.top/Article/details/gt2tvuchplf.html

[D16] 求和与平均值
来源：http://dali.yvedp.cn/Article/details/gt2ezesrquh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xylfe.cn/Article/details/gt2zvhhhmmj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2zqbezmgm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gt2parzkirg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daria6918.cn/Article/details/gt2lsgvaywi.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.redwolf501.top/Article/details/gt2zrqyxdom.html

Go:   // 手写循环累加
来源：http://dali.gzhubu.top/Article/details/gt2odvldsqp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.guannengcc.top/Article/details/gt2cknyxrzv.html

C#:   list.Sum();  list.Average()
来源：http://dali.zycfv.cn/Article/details/gt2uxbaamap.html

[D17] 最大值与最小值
来源：http://dali.ehwqpu.com/Article/details/gt2fwbeyhoz.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fthylfyq.html

PHP:  max($arr);  min($arr);
来源：http://dali.ivvv.top/Article/details/gt2prqvxdsj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.snrcjt.cn/Article/details/gt2duafayio.html

TS:   Math.max(...arr);
来源：http://dali.316326.xyz/Article/details/gt2ewfrnngz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinqigufen.top/Article/details/gt2zaddlufr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yonumen.top/Article/details/gt2mycrypka.html

Ruby: arr.max;  arr.min
来源：http://dali.0kj1m.cn/Article/details/gt2npyxwcjb.html

C#:   list.Max();  list.Min()
来源：http://dali.shzxlz.cn/Article/details/gt2skabwmgx.html

[D18] 扁平化嵌套数组
来源：http://dali.zhiwuduotai.top/Article/details/gt2bexwkykx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yvedp.cn/Article/details/gt2nlmkqwax.html

PHP:  array_merge(...$nested);
来源：http://dali.cdnleiting.top/Article/details/gt2lkqkubwp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.316326.xyz/Article/details/gt2fsxcndhf.html

TS:   nested.flat();
来源：http://dali.nanxinkj.top/Article/details/gt2pbkrhmkl.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.haohaochexian.top/Article/details/gt2ownahtwc.html

Go:   // 手写双层循环
来源：http://dali.dianchejie.cn/Article/details/gt2cquxdruc.html

Ruby: nested.flatten
来源：http://dali.sweek.top/Article/details/gt2eyafckus.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xinyue.icu/Article/details/gt2qgusjhwp.html

[D19] 按字段分组
来源：http://dali.svipenyu.cn/Article/details/gt2wcpznkix.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cashguo.top/Article/details/gt2mjufhppi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ivvv.top/Article/details/gt2kqartzrz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.fzhhl.top/Article/details/gt2sfwrejfl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yanxiufei.cn/Article/details/gt2kbqaalyq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.kuanghao11.cn/Article/details/gt2xzncrawj.html

Go:   // 手写 map[string][]T
来源：http://dali.zhixingplan.top/Article/details/gt2fmodrfjq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.svipenyu.cn/Article/details/gt2cavsvtpk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.wangdashe.top/Article/details/gt2kjhegyca.html

[D20] 统计每个元素出现次数
来源：http://dali.xziqi.cn/Article/details/gt2saoicfna.html

Py:   Counter(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2teftmmgk.html

PHP:  array_count_values($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2smhkcbco.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hysaishi.cn/Article/details/gt2ulwlxope.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jianghu66.top/Article/details/gt2dtbwmkfy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2drxrgyzp.html

Go:   // 手写 map[T]int
来源：http://dali.zhongyouzk.top/Article/details/gt2mxzkwxrh.html

Ruby: arr.tally
来源：http://dali.hammf.cn/Article/details/gt2dtcermlh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shzxlz.cn/Article/details/gt2aogycplu.html

[D21] 判断是否包含某元素
来源：http://dali.havefunace.top/Article/details/gt2qxkskbmv.html

Py:   x in arr
来源：http://dali.ydzc1.top/Article/details/gt2esfcgemz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.havefunace.top/Article/details/gt2oddqlbgk.html

JS:   arr.includes(x)
来源：http://dali.chenlongwang.top/Article/details/gt2ygqgjvgj.html

TS:   arr.includes(x)
来源：http://dali.jinqigufen.top/Article/details/gt2mttexfkn.html

Java: list.contains(x)
来源：http://dali.yonumen.top/Article/details/gt2qzjxmafm.html

Go:   slices.Contains(arr, x)
来源：http://dali.xinyue.icu/Article/details/gt2yfxqwolo.html

Ruby: arr.include?(x)
来源：http://dali.9152youxi.cn/Article/details/gt2kzszrmrd.html

C#:   list.Contains(x)
来源：http://dali.cdnleiting.top/Article/details/gt2hlcgpuap.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tianlin.xyz/Article/details/gt2jgnxbhct.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.meibo888.top/Article/details/gt2gdvtcgvq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cheryme.top/Article/details/gt2jfwtzncd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.daxiang520.top/Article/details/gt2tcrfukka.html

TS:   [...arr];
来源：http://dali.guannengcc.top/Article/details/gt2zvjdcddr.html

Java: new ArrayList<>(list);
来源：http://dali.birdmap.top/Article/details/gt2khtyppsg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj20258.top/Article/details/gt2oetokkje.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhiwuduotai.top/Article/details/gt2duxwekrh.html

C#:   new List<int>(list);
来源：http://dali.bjfxy.top/Article/details/gt2ijbgztel.html

[D23] reduce 累积计算
来源：http://dali.havefunace.top/Article/details/gt2owvkggac.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.c1oappe.top/Article/details/gt2dnwmgbju.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sweek.top/Article/details/gt2nxwdbjjp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guowangkeji.top/Article/details/gt2fmoyxxjg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guowangkeji.top/Article/details/gt2tauqejhu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hnxiangtu.top/Article/details/gt2rumhhzbf.html

Go:   // 手写循环
来源：http://dali.jyoumei.cn/Article/details/gt2jofpnulx.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.snrcjt.cn/Article/details/gt2wlecsbzq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yangfankeji.com/Article/details/gt2sqjyhzxy.html

[D24] 字典 / Map 基本操作
来源：http://dali.wangdashe.top/Article/details/gt2bjtgiwuy.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cqqwz.cn/Article/details/gt2cgbqxgkb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.haohaochexian.top/Article/details/gt2fidauohx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.sufxvd.cn/Article/details/gt2fcffgkbq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xinyue.icu/Article/details/gt2hoyreuzf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.havefunace.top/Article/details/gt2yufnexcl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gaohongyu789.top/Article/details/gt2auywlmwk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.316326.xyz/Article/details/gt2gbnieblp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ehwqpu.com/Article/details/gt2xarjfwfv.html

[D25] Set 集合去重与交并差
来源：http://dali.sysykeji.top/Article/details/gt2zzimtmub.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.snrcjt.cn/Article/details/gt2aryxiqby.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.dashuyun.cn/Article/details/gt2trehwwsw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rddsulxa.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xylfe.cn/Article/details/gt2orqxwvof.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hfpthk.cn/Article/details/gt2mdhdwsus.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cdnleiting.top/Article/details/gt2pekslolw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yvedp.cn/Article/details/gt2wcfrewdz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.nwbrower.top/Article/details/gt2ciwpmldr.html

[D26] 数组转字符串
来源：http://dali.jyoumei.cn/Article/details/gt2wboblgzw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jqgfzy.top/Article/details/gt2lmgjnuxn.html

PHP:  implode(", ", $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2yfomawql.html

JS:   arr.join(", ")
来源：http://dali.gogol.net.cn/Article/details/gt2fabdtjgn.html

TS:   arr.join(", ")
来源：http://dali.cqqwz.cn/Article/details/gt2rpwttxts.html

Java: String.join(", ", list)
来源：http://dali.316326.xyz/Article/details/gt2yauksopc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.pengpengdd.cyou/Article/details/gt2czzcglwy.html

Ruby: arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gt2ocndzskm.html

C#:   string.Join(", ", list)
来源：http://dali.hnqzz.top/Article/details/gt2bnrkhpui.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2psouwolr.html

E. 字符串处理
来源：http://dali.dianchejie.cn/Article/details/gt2yuznogrb.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2mdtblcqh.html

[E01] 拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hjjkvckq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ydzc1.top/Article/details/gt2fsdcqnug.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhengqikj.top/Article/details/gt2ghdzhdkz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cashguo.top/Article/details/gt2nesfhvyx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tanke756.top/Article/details/gt2muobbgcg.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.havefunace.top/Article/details/gt2wryktpvj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhixingplan.top/Article/details/gt2ozjcvdju.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.dashuyun.cn/Article/details/gt2nwttdebt.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ycloukyl.html

[E02] 重复字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2jjnjpjye.html

Py:   "ab" * 3
来源：http://dali.jyoumei.cn/Article/details/gt2gulgercx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.tianlin.xyz/Article/details/gt2drcwcukp.html

JS:   "ab".repeat(3)
来源：http://dali.hnxiangtu.top/Article/details/gt2lclynvjx.html

TS:   "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gt2kgjrcdbq.html

Java: "ab".repeat(3)
来源：http://dali.vqdsnc.cn/Article/details/gt2xaojbnmj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhoulong.xyz/Article/details/gt2hglqflny.html

Ruby: "ab" * 3
来源：http://dali.snrcjt.cn/Article/details/gt2ihmitzjt.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.mhx1999.top/Article/details/gt2krxudexq.html

[E03] 截取子串
来源：http://dali.sysykeji.top/Article/details/gt2bdzxtjoh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ydzc1.top/Article/details/gt2rnindenq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gt2syulrzmi.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.kuanghao11.cn/Article/details/gt2anohsgxs.html

TS:   s.slice(1, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iuptyewg.html

Java: s.substring(1, 4)
来源：http://dali.316326.xyz/Article/details/gt2rfajvkzl.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hywenlv.cn/Article/details/gt2fqblbjcv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shangyingyoupin.top/Article/details/gt2dmtgjfba.html

C#:   s.Substring(1, 3)
来源：http://dali.c1oappe.top/Article/details/gt2ytlxbdxy.html

[E04] 查找子串位置
来源：http://dali.ehwqpu.com/Article/details/gt2aypuzfmt.html

Py:   s.find("x");  s.index("x")
来源：http://dali.birdmap.top/Article/details/gt2ndhtjqad.html

PHP:  strpos($s, "x");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rldhfbzq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cdnleiting.top/Article/details/gt2lmcfoqhl.html

TS:   s.indexOf("x")
来源：http://dali.316326.xyz/Article/details/gt2iwmrrdkb.html

Java: s.indexOf("x")
来源：http://dali.kuanghao11.cn/Article/details/gt2xwvjsuhf.html

Go:   strings.Index(s, "x")
来源：http://dali.ehwqpu.com/Article/details/gt2vfvynfgs.html

Ruby: s.index("x")
来源：http://dali.yanxiufei.cn/Article/details/gt2jpsmgtxd.html

C#:   s.IndexOf("x")
来源：http://dali.yj20258.top/Article/details/gt2urwlvqwu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yj202588.top/Article/details/gt2tiljykyk.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yvedp.cn/Article/details/gt2vztfvckm.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wzgrcpyj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gt2cevzpurf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.andypj.xyz/Article/details/gt2zvqcjlas.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.pycfn.com/Article/details/gt2ypsvcogv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shuidangran.top/Article/details/gt2lgzswgfe.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sweek.top/Article/details/gt2zbkbguid.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gt2mclvbtpg.html

[E06] 替换子串
来源：http://dali.feifeiyinyue.top/Article/details/gt2ycbqblao.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxtcjva.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sufxvd.cn/Article/details/gt2bnodrvkz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gt2jmcweesc.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gt2dbycslbm.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qgcykrqe.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.fengsongda.top/Article/details/gt2bsanyqqu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.havefunace.top/Article/details/gt2wiwddxcn.html

C#:   s.Replace("a", "b")
来源：http://dali.bjfxy.top/Article/details/gt2atvlgzmy.html

[E07] 按分隔符拆分
来源：http://dali.ppjwa.cn/Article/details/gt2opmlchhx.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yj202588.top/Article/details/gt2vurlmlyy.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinqigufen.top/Article/details/gt2gvgmpsse.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zycfv.cn/Article/details/gt2wdsxywzb.html

TS:   s.split(",")
来源：http://dali.hysaishi.cn/Article/details/gt2reiwoxzq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yvedp.cn/Article/details/gt2fztrpkgh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jqgfzy.top/Article/details/gt2ngmdnuxr.html

Ruby: s.split(",");  s.split
来源：http://dali.zhixingplan.top/Article/details/gt2eugsbkwj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zycfv.cn/Article/details/gt2yrdjocla.html

[E08] 数组按分隔符合并
来源：http://dali.cucudq.cn/Article/details/gt2dhpcxpov.html

Py:   ",".join(items)
来源：http://dali.quarkkingdee.top/Article/details/gt2tflmqnrf.html

PHP:  implode(",", $items);
来源：http://dali.andypj.xyz/Article/details/gt2vsqmvptb.html

JS:   items.join(",")
来源：http://dali.ybcxt.top/Article/details/gt2axdwpskw.html

TS:   items.join(",")
来源：http://dali.andypj.xyz/Article/details/gt2umkvwuxa.html

Java: String.join(",", items)
来源：http://dali.yj202588.top/Article/details/gt2revyelku.html

Go:   strings.Join(items, ",")
来源：http://dali.hammf.cn/Article/details/gt2uimhqnng.html

Ruby: items.join(",")
来源：http://dali.zhoulong.xyz/Article/details/gt2rslagezg.html

C#:   string.Join(",", items)
来源：http://dali.haohaochexian.top/Article/details/gt2keqdahty.html

[E09] 去除所有空白字符
来源：http://dali.tian-w.cn/Article/details/gt2paxolyix.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dedavdks.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ivvv.top/Article/details/gt2qectzgrq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sxryk.cn/Article/details/gt2rjhopadr.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hammf.cn/Article/details/gt2mefsycwn.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cqffmrfh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ziodunmh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zdqjudy.top/Article/details/gt2weavmitb.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yangfankeji.com/Article/details/gt2hbvmzjmo.html

[E10] 左侧补零 / 定长填充
来源：http://dali.aizwys.cn/Article/details/gt2xtylsymv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.nwbrower.top/Article/details/gt2hznfjjxe.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jiagoushi.top/Article/details/gt2ozghvakc.html

JS:   "7".padStart(3, "0")
来源：http://dali.zdqjudy.top/Article/details/gt2lesddorc.html

TS:   "7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gt2zxjlpiqw.html

Java: String.format("%03d", 7)
来源：http://dali.hysaishi.cn/Article/details/gt2vedblznw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhixingplan.top/Article/details/gt2oflzeenf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yangfankeji.com/Article/details/gt2xejrclyd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.guannengcc.top/Article/details/gt2xuudbjcn.html

[E11] 反转字符串
来源：http://dali.jyoumei.cn/Article/details/gt2ugmaqtfo.html

Py:   s[::-1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cejwvpna.html

PHP:  strrev($s);
来源：http://dali.zhengqikj.top/Article/details/gt2iwksoicf.html

JS:   [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gt2jcdenroq.html

TS:   [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gt2btinxrog.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.snrcjt.cn/Article/details/gt2olwfoyto.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kblzbhux.html

Ruby: s.reverse
来源：http://dali.iojbl.cn/Article/details/gt2lylddatl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xziqi.cn/Article/details/gt2jeeosztk.html

[E12] 统计某字符出现次数
来源：http://dali.pengpengdd.cyou/Article/details/gt2fkpoxoiy.html

Py:   s.count("a")
来源：http://dali.zycfv.cn/Article/details/gt2jeknxbbg.html

PHP:  substr_count($s, "a");
来源：http://dali.xinyue.icu/Article/details/gt2jrmnfqcy.html

JS:   s.split("a").length - 1
来源：http://dali.dianchejie.cn/Article/details/gt2pxbkfdoj.html

TS:   s.split("a").length - 1
来源：http://dali.gaohongyu789.top/Article/details/gt2bcrefqxk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.svipenyu.cn/Article/details/gt2arufdasc.html

Go:   strings.Count(s, "a")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fpaqlxcd.html

Ruby: s.count("a")
来源：http://dali.9152youxi.cn/Article/details/gt2yqimejbg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hfpthk.cn/Article/details/gt2euatwupo.html

[E13] 逐字符遍历
来源：http://dali.fzhhl.top/Article/details/gt2kfcpzrnk.html

Py:   for ch in s: print(ch)
来源：http://dali.dashuyun.cn/Article/details/gt2hzdmqdnf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ehwqpu.com/Article/details/gt2bdcwpyjf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gt2xyfrgbme.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daxiang520.top/Article/details/gt2tqvsulub.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hysaishi.cn/Article/details/gt2mvwjbesh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ehwqpu.com/Article/details/gt2pqrpmhrn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zycfv.cn/Article/details/gt2uaogsjxn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.svipenyu.cn/Article/details/gt2xfknullf.html


<!-- 参考信息 -->