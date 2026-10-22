代发 wailian999

Java: list.size();
来源：http://dali.tian-w.cn/Article/details/gt2tlpuadem.html

Go:   len(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2qnfhmpri.html

Ruby: arr.length; arr.size
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tiogxmhh.html

C#:   list.Count;
来源：http://dali.jinqigfzy.top/Article/details/gt2ajaeubww.html

[D07] 切片 / 取子数组
来源：http://dali.havefunace.top/Article/details/gt2megjbcvd.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rizseogo.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.tanke756.top/Article/details/gt2tzhgxwpo.html

JS:   arr.slice(1, 4);
来源：http://dali.dashuyun.cn/Article/details/gt2vvlsohws.html

TS:   arr.slice(1, 4);
来源：http://dali.fengsongda.top/Article/details/gt2ahnkmuzt.html

Java: list.subList(1, 4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gunrggrz.html

Go:   arr[1:4]
来源：http://dali.dianchejie.cn/Article/details/gt2ickxvcmp.html

Ruby: arr[1, 3]
来源：http://dali.zdqjudy.top/Article/details/gt2kxyqwefp.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jsmunbay.html

[D08] 合并两个数组
来源：http://dali.andypj.xyz/Article/details/gt2bajbbdiu.html

Py:   a + b;  a.extend(b)
来源：http://dali.ehwqpu.com/Article/details/gt2vhwzorjc.html

PHP:  array_merge($a, $b);
来源：http://dali.hammf.cn/Article/details/gt2pxorwwus.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.9152youxi.cn/Article/details/gt2oqmjjmhn.html

TS:   [...a, ...b];
来源：http://dali.svipenyu.cn/Article/details/gt2ogxqgxhz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sufxvd.cn/Article/details/gt2lvebhshk.html

Go:   append(a, b...)
来源：http://dali.cqqwz.cn/Article/details/gt2pichbcja.html

Ruby: a + b;  a.concat(b)
来源：http://dali.gaohongyu789.top/Article/details/gt2pfalvmnt.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gt2pjfleoiq.html

[D09] 排序（升序）
来源：http://dali.tanke756.top/Article/details/gt2ykpwcowk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yangfankeji.com/Article/details/gt2ifgbdqex.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxdpypl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jqgfzy.top/Article/details/gt2qlwqgbjw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.birdmap.top/Article/details/gt2ynnfijyp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cdnleiting.top/Article/details/gt2tzzsqwml.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.bjfxy.top/Article/details/gt2tcpheqgl.html

Ruby: arr.sort
来源：http://dali.chenlongwang.top/Article/details/gt2ninfebzu.html

C#:   list.Sort();
来源：http://dali.guannengcc.top/Article/details/gt2pbstasxo.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.dianchejie.cn/Article/details/gt2ycdaaqej.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.quarkkingdee.top/Article/details/gt2zxowvzyy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gaohongyu789.top/Article/details/gt2qvjveyuu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ivvv.top/Article/details/gt2hqbsvdrj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.meibo888.top/Article/details/gt2mvyedigm.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jqgfzy.top/Article/details/gt2jhveitgq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yongpay.top/Article/details/gt2xdxxvmlg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nanxuanxn.top/Article/details/gt2ucdyjmlm.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.vqdsnc.cn/Article/details/gt2ebppbllo.html

[D11] 反转数组
来源：http://dali.jianghu66.top/Article/details/gt2iynqlruq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yj202588.top/Article/details/gt2sqitqnrd.html

PHP:  array_reverse($arr);
来源：http://dali.mhx1999.top/Article/details/gt2gzzlfkpr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cqqwz.cn/Article/details/gt2acbbexif.html

TS:   [...arr].reverse();
来源：http://dali.zdqjudy.top/Article/details/gt2hlvfzohu.html

Java: Collections.reverse(list);
来源：http://dali.hongshengwenyu.top/Article/details/gt2yskleevg.html

Go:   slices.Reverse(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2vkzedvzz.html

Ruby: arr.reverse
来源：http://dali.nwbrower.top/Article/details/gt2bbysicnr.html

C#:   list.Reverse();
来源：http://dali.jianghu66.top/Article/details/gt2khjvmvrv.html

[D12] 查找元素下标
来源：http://dali.9152youxi.cn/Article/details/gt2rseoidzd.html

Py:   arr.index(x);  x in arr
来源：http://dali.gogol.net.cn/Article/details/gt2eamdpzdx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhengqikj.top/Article/details/gt2bnnhpayr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hfpthk.cn/Article/details/gt2jzlppsip.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nwbrower.top/Article/details/gt2auvggqep.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.guowangkeji.top/Article/details/gt2azjfbkrv.html

Go:   slices.Index(arr, x)
来源：http://dali.cashguo.top/Article/details/gt2wenlufni.html

Ruby: arr.index(x)
来源：http://dali.gotoacloud.top/Article/details/gt2ovssoedn.html

C#:   list.IndexOf(x);
来源：http://dali.yueranfly.top/Article/details/gt2vqhhvseg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sweek.top/Article/details/gt2huazuteh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yanxiufei.cn/Article/details/gt2xicgifsj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shangyingyoupin.top/Article/details/gt2opazxnhc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.nanxinkj.top/Article/details/gt2nkzggmvp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.kuanghao11.cn/Article/details/gt2ixkxbypl.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.wangdashe.top/Article/details/gt2nuzfygpg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.daxiang520.top/Article/details/gt2fllgkfnm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.mhx1999.top/Article/details/gt2ibfxuyvi.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj20258888.top/Article/details/gt2ofefdfkv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gogol.net.cn/Article/details/gt2pxuuhcdn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.chenjidiqi.icu/Article/details/gt2agmldbdu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.dianchejie.cn/Article/details/gt2vujipdwo.html

JS:   arr.map(x => x * 2)
来源：http://dali.yuxming.cn/Article/details/gt2rpdhoxau.html

TS:   arr.map(x => x * 2)
来源：http://dali.cashguo.top/Article/details/gt2jffdrcdc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.tian-w.cn/Article/details/gt2ijupmiam.html

Go:   // 手写循环
来源：http://dali.hammf.cn/Article/details/gt2dhnreuiq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.nwbrower.top/Article/details/gt2xmwihbga.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yongpay.top/Article/details/gt2omzblbom.html

[D15] 去重
来源：http://dali.feifeiyinyue.top/Article/details/gt2wrcwdgzy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cashguo.top/Article/details/gt2eoahkhuq.html

PHP:  array_unique($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2wdruiijd.html

JS:   [...new Set(arr)]
来源：http://dali.hammf.cn/Article/details/gt2insfbhur.html

TS:   [...new Set(arr)]
来源：http://dali.chenlongwang.top/Article/details/gt2qppkzaya.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.fzhhl.top/Article/details/gt2vjutlodw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.fengsongda.top/Article/details/gt2qdtzfrjd.html

Ruby: arr.uniq
来源：http://dali.chenzaomai.com/Article/details/gt2tuargqmr.html

C#:   list.Distinct().ToList()
来源：http://dali.xziqi.cn/Article/details/gt2azixdvxe.html

[D16] 求和与平均值
来源：http://dali.dianchejie.cn/Article/details/gt2jkbwcqsh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shuidangran.top/Article/details/gt2cdeoptjs.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vwjezlvs.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yonumen.top/Article/details/gt2zlacvbbk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.snrcjt.cn/Article/details/gt2dgfufbpf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.nwbrower.top/Article/details/gt2uizibgzx.html

Go:   // 手写循环累加
来源：http://dali.dashuyun.cn/Article/details/gt2gcrcxxlr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhongyouzk.top/Article/details/gt2jlqkddhy.html

C#:   list.Sum();  list.Average()
来源：http://dali.vqdsnc.cn/Article/details/gt2gbjbclhj.html

[D17] 最大值与最小值
来源：http://dali.yuxming.cn/Article/details/gt2iofhcwdu.html

Py:   max(arr);  min(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2sabftzza.html

PHP:  max($arr);  min($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2mxpitrso.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fnqaaijn.html

TS:   Math.max(...arr);
来源：http://dali.cheryme.top/Article/details/gt2geuhkzfx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.daria6918.cn/Article/details/gt2tdpodjda.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2veavqgnz.html

Ruby: arr.max;  arr.min
来源：http://dali.xziqi.cn/Article/details/gt2yudxweod.html

C#:   list.Max();  list.Min()
来源：http://dali.redwolf501.top/Article/details/gt2alghgzqq.html

[D18] 扁平化嵌套数组
来源：http://dali.yueranfly.top/Article/details/gt2pvzqhcjh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.chenjidiqi.icu/Article/details/gt2mhjyugca.html

PHP:  array_merge(...$nested);
来源：http://dali.jyoumei.cn/Article/details/gt2uidtkgji.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ydzc1.top/Article/details/gt2zvocbtlt.html

TS:   nested.flat();
来源：http://dali.jinqigfzy.top/Article/details/gt2dlglyukw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hnqzz.top/Article/details/gt2soirudpc.html

Go:   // 手写双层循环
来源：http://dali.chenzaomai.com/Article/details/gt2ymgkanlj.html

Ruby: nested.flatten
来源：http://dali.zhiwuduotai.top/Article/details/gt2wlowiaux.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.birdmap.top/Article/details/gt2hbaajnhk.html

[D19] 按字段分组
来源：http://dali.daria6918.cn/Article/details/gt2dzmxfpgc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cxsfteqq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gogol.net.cn/Article/details/gt2pzqmhpxc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhoulong.xyz/Article/details/gt2mvtjozbu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.feifeiyinyue.top/Article/details/gt2hjcxffkh.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.guowangkeji.top/Article/details/gt2hjpdgzfq.html

Go:   // 手写 map[string][]T
来源：http://dali.chenlongwang.top/Article/details/gt2qiooxohr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.redwolf501.top/Article/details/gt2ktlgnssp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hnqzz.top/Article/details/gt2cjuctpdm.html

[D20] 统计每个元素出现次数
来源：http://dali.gaohongyu789.top/Article/details/gt2qaxeatzw.html

Py:   Counter(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2fstpvlbo.html

PHP:  array_count_values($arr);
来源：http://dali.smart0.xyz/Article/details/gt2sswesfbz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nrtysvbm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2micoglxy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.bjfxy.top/Article/details/gt2gnilcxzx.html

Go:   // 手写 map[T]int
来源：http://dali.haohaochexian.top/Article/details/gt2izjpgwbv.html

Ruby: arr.tally
来源：http://dali.316326.xyz/Article/details/gt2scgibtfg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.chenzaomai.com/Article/details/gt2jpqvnhuy.html

[D21] 判断是否包含某元素
来源：http://dali.daria6918.cn/Article/details/gt2vdscfugg.html

Py:   x in arr
来源：http://dali.jqgufenzy.top/Article/details/gt2hiyburud.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jqgufenzy.top/Article/details/gt2oaeqtrpe.html

JS:   arr.includes(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2cxymxfcc.html

TS:   arr.includes(x)
来源：http://dali.sxryk.cn/Article/details/gt2lzjqwekh.html

Java: list.contains(x)
来源：http://dali.c1oappe.top/Article/details/gt2himhbqdo.html

Go:   slices.Contains(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gt2puriasjw.html

Ruby: arr.include?(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2cbbijuia.html

C#:   list.Contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gt2wpnllxcf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zyawkefk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shuidangran.top/Article/details/gt2adectbxo.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.kuanghao11.cn/Article/details/gt2qmwsjdeo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yj20258.top/Article/details/gt2ssjnxsig.html

TS:   [...arr];
来源：http://dali.yongpay.top/Article/details/gt2frhmtpii.html

Java: new ArrayList<>(list);
来源：http://dali.ivvv.top/Article/details/gt2bexzskhi.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shangyingyoupin.top/Article/details/gt2eftiupel.html

Ruby: arr.dup;  arr.clone
来源：http://dali.dashuyun.cn/Article/details/gt2mesqxwkr.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzsfqcb.html

[D23] reduce 累积计算
来源：http://dali.zhongyouzk.top/Article/details/gt2ybvmyjvp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.nwbrower.top/Article/details/gt2sleqpnar.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gt2fawyclxs.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cqqwz.cn/Article/details/gt2ollytlcy.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ymfwqxsg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xuanzx.com/Article/details/gt2djvghvtt.html

Go:   // 手写循环
来源：http://dali.pengpengdd.cyou/Article/details/gt2mvmxkxzi.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cucudq.cn/Article/details/gt2vbwdaqkh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.aibaodan.cn/Article/details/gt2eihchyhs.html

[D24] 字典 / Map 基本操作
来源：http://dali.andypj.xyz/Article/details/gt2unurqeuq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.iojbl.cn/Article/details/gt2fzgogwbh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jqgufenzy.top/Article/details/gt2jdxuvmug.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.birdmap.top/Article/details/gt2zlsxfxxw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gt2ynympwtv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.quarkkingdee.top/Article/details/gt2efqyvfch.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxjnxlk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ibqabynd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.dashuyun.cn/Article/details/gt2ynrpzdcw.html

[D25] Set 集合去重与交并差
来源：http://dali.hongshengwenyu.top/Article/details/gt2tkxlnvsm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jqgfzy.top/Article/details/gt2ssxfswks.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yj20258.top/Article/details/gt2uiifrnxp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.9152youxi.cn/Article/details/gt2owookffd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xinyue.icu/Article/details/gt2fkaemblo.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gogol.net.cn/Article/details/gt2vjbuxpjr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hongshengwenyu.top/Article/details/gt2llzpeeqn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zdqjudy.top/Article/details/gt2fzgerxcz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yongpay.top/Article/details/gt2yqhnstyc.html

[D26] 数组转字符串
来源：http://dali.guowangkeji.top/Article/details/gt2rnzjhxdk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gbmarlkr.html

PHP:  implode(", ", $arr);
来源：http://dali.hysaishi.cn/Article/details/gt2wjasswdd.html

JS:   arr.join(", ")
来源：http://dali.feifeiyinyue.top/Article/details/gt2pxxyoknz.html

TS:   arr.join(", ")
来源：http://dali.ybcxt.top/Article/details/gt2pnkcmwoz.html

Java: String.join(", ", list)
来源：http://dali.hongshengwenyu.top/Article/details/gt2taaoowcg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.wangshuangyany.cn/Article/details/gt2qmkuvuzt.html

Ruby: arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gt2hykaypbm.html

C#:   string.Join(", ", list)
来源：http://dali.yj20258.top/Article/details/gt2fskzlkms.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2xdanqkwf.html

E. 字符串处理
来源：http://dali.jyoumei.cn/Article/details/gt2beiztogx.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2cjvzmjgc.html

[E01] 拼接字符串
来源：http://dali.aizwys.cn/Article/details/gt2vphunpie.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xuanzx.com/Article/details/gt2aoaragfl.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ppjwa.cn/Article/details/gt2lyvgfqhi.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aizwys.cn/Article/details/gt2tpgkhprd.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xylfe.cn/Article/details/gt2zsapwvxa.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.0kj1m.cn/Article/details/gt2vylowwuv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.fzhhl.top/Article/details/gt2xzifrini.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.redwolf501.top/Article/details/gt2hfzlmvah.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cheryme.top/Article/details/gt2uiakbbzh.html

[E02] 重复字符串
来源：http://dali.gzhubu.top/Article/details/gt2qvaxdyfn.html

Py:   "ab" * 3
来源：http://dali.wangshuangyany.cn/Article/details/gt2bupcezrr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gzhubu.top/Article/details/gt2qymaspuy.html

JS:   "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gt2cvpbbixo.html

TS:   "ab".repeat(3)
来源：http://dali.meibo888.top/Article/details/gt2zlyyhgbm.html

Java: "ab".repeat(3)
来源：http://dali.tanke756.top/Article/details/gt2soqkfowg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gotoacloud.top/Article/details/gt2febwaglj.html

Ruby: "ab" * 3
来源：http://dali.redwolf501.top/Article/details/gt2sbclhlmh.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shzxlz.cn/Article/details/gt2oggpnwvh.html

[E03] 截取子串
来源：http://dali.hfpthk.cn/Article/details/gt2wmqoesvx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.nanxuanxn.top/Article/details/gt2njhmhwvj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gt2bcslztjo.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cdnleiting.top/Article/details/gt2jbpfkhtg.html

TS:   s.slice(1, 4)
来源：http://dali.fzhhl.top/Article/details/gt2qnlqvbxb.html

Java: s.substring(1, 4)
来源：http://dali.hfpthk.cn/Article/details/gt2oxaxhlbi.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.quarkkingdee.top/Article/details/gt2hxbqmycu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.nanxuanxn.top/Article/details/gt2yyvgugbh.html

C#:   s.Substring(1, 3)
来源：http://dali.jqgufenzy.top/Article/details/gt2jyacmjgb.html

[E04] 查找子串位置
来源：http://dali.zhoulong.xyz/Article/details/gt2jvkdvqtg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yj20258.top/Article/details/gt2xtrierop.html

PHP:  strpos($s, "x");
来源：http://dali.guannengcc.top/Article/details/gt2xlvnraii.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.meibo888.top/Article/details/gt2zdjnpere.html

TS:   s.indexOf("x")
来源：http://dali.gotoacloud.top/Article/details/gt2hztogqds.html

Java: s.indexOf("x")
来源：http://dali.xuetiantiany.cn/Article/details/gt2btxwgyqb.html

Go:   strings.Index(s, "x")
来源：http://dali.gotoacloud.top/Article/details/gt2codrhupg.html

Ruby: s.index("x")
来源：http://dali.meibo888.top/Article/details/gt2clfiuvyn.html

C#:   s.IndexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gt2wimqdhxi.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jiagoushi.top/Article/details/gt2lbjpjjjb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.9152youxi.cn/Article/details/gt2ghlaaosb.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.wangshuangyany.cn/Article/details/gt2jiczxwjz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xziqi.cn/Article/details/gt2zcoqrvtw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.vqdsnc.cn/Article/details/gt2sfcwnovb.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gzhubu.top/Article/details/gt2bituhjko.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shzxlz.cn/Article/details/gt2gfblhomk.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.c1oappe.top/Article/details/gt2sttfbout.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ppjwa.cn/Article/details/gt2ytexopba.html

[E06] 替换子串
来源：http://dali.c1oappe.top/Article/details/gt2xgmuvwja.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ppjwa.cn/Article/details/gt2tyusbufi.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uifrxxjj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gt2anmxpxnv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gt2rzubzpsx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gt2bgmmfdjo.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zycfv.cn/Article/details/gt2rocthavc.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ybcxt.top/Article/details/gt2wfnasflt.html

C#:   s.Replace("a", "b")
来源：http://dali.havefunace.top/Article/details/gt2wmwezzuv.html

[E07] 按分隔符拆分
来源：http://dali.havefunace.top/Article/details/gt2kbbjghac.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sxryk.cn/Article/details/gt2zwtwktqi.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.mhx1999.top/Article/details/gt2apdspfqn.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.chenzaomai.com/Article/details/gt2nrheobgv.html

TS:   s.split(",")
来源：http://dali.hywenlv.cn/Article/details/gt2cfrgvwim.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sxryk.cn/Article/details/gt2fpknoxng.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2fmzpocgb.html

Ruby: s.split(",");  s.split
来源：http://dali.daxiang520.top/Article/details/gt2wedpfswg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhongyouzk.top/Article/details/gt2anosasle.html

[E08] 数组按分隔符合并
来源：http://dali.pengpengdd.cyou/Article/details/gt2apvbatpx.html

Py:   ",".join(items)
来源：http://dali.tianlin.xyz/Article/details/gt2zcaanvco.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2clnxthlt.html

JS:   items.join(",")
来源：http://dali.mhx1999.top/Article/details/gt2saqaxkll.html

TS:   items.join(",")
来源：http://dali.andypj.xyz/Article/details/gt2szigmmaz.html

Java: String.join(",", items)
来源：http://dali.nwbrower.top/Article/details/gt2fjqxirob.html

Go:   strings.Join(items, ",")
来源：http://dali.pycfn.com/Article/details/gt2cqfkvdsx.html

Ruby: items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gt2cdsafdyc.html

C#:   string.Join(",", items)
来源：http://dali.yuanzhike.top/Article/details/gt2nadqtfof.html

[E09] 去除所有空白字符
来源：http://dali.nanxuanxn.top/Article/details/gt2dlynwnvn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.pycfn.com/Article/details/gt2ogezcksd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.fzhhl.top/Article/details/gt2mzeikzdd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hfpthk.cn/Article/details/gt2dibazxdg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rfdzreoq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.nwbrower.top/Article/details/gt2bygbjyhl.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xylfe.cn/Article/details/gt2epogyhhc.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhongyouzk.top/Article/details/gt2izryqbel.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hongshengwenyu.top/Article/details/gt2readfcku.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hnqzz.top/Article/details/gt2ivbdvntf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gt2plaziypd.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pjamjoai.html

JS:   "7".padStart(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ravrfypn.html

TS:   "7".padStart(3, "0")
来源：http://dali.sweek.top/Article/details/gt2ucwtrbpf.html

Java: String.format("%03d", 7)
来源：http://dali.gzhubu.top/Article/details/gt2xhymbjvs.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gt2yfnctgif.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2njjopyms.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.quarkkingdee.top/Article/details/gt2reahfewe.html

[E11] 反转字符串
来源：http://dali.yuxming.cn/Article/details/gt2oyojvbch.html

Py:   s[::-1]
来源：http://dali.bjfxy.top/Article/details/gt2laldemcn.html

PHP:  strrev($s);
来源：http://dali.yuanzhike.top/Article/details/gt2pgclttgl.html

JS:   [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gt2hhqqfjxw.html

TS:   [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gt2unfvwmma.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenlongwang.top/Article/details/gt2utgefvmn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ehwqpu.com/Article/details/gt2ydpdibiw.html

Ruby: s.reverse
来源：http://dali.vqdsnc.cn/Article/details/gt2oiyxjmzr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hammf.cn/Article/details/gt2yrbogyni.html

[E12] 统计某字符出现次数
来源：http://dali.svipenyu.cn/Article/details/gt2goyqvprx.html

Py:   s.count("a")
来源：http://dali.birdmap.top/Article/details/gt2ajixiasv.html

PHP:  substr_count($s, "a");
来源：http://dali.meibo888.top/Article/details/gt2ynpsnjil.html

JS:   s.split("a").length - 1
来源：http://dali.zhengqikj.top/Article/details/gt2cefsxmob.html

TS:   s.split("a").length - 1
来源：http://dali.iojbl.cn/Article/details/gt2ohmyalin.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenzaomai.com/Article/details/gt2qobgxkmu.html

Go:   strings.Count(s, "a")
来源：http://dali.jyoumei.cn/Article/details/gt2stbvbgcz.html

Ruby: s.count("a")
来源：http://dali.sysykeji.top/Article/details/gt2ahvrlhip.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xinyue.icu/Article/details/gt2dlaiayfe.html

[E13] 逐字符遍历
来源：http://dali.sweek.top/Article/details/gt2quderkms.html

Py:   for ch in s: print(ch)
来源：http://dali.jqgufenzy.top/Article/details/gt2mdsabomt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cheryme.top/Article/details/gt2zlxyocqh.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuanzx.com/Article/details/gt2etpfqpni.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gt2hvmzmduh.html


<!-- 参考信息 -->