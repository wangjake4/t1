代发 wailian999

TS:   arr.slice(1, 4);
来源：http://dali.jinqigfzy.top/Article/details/gt2lsfdvtqp.html

Java: list.subList(1, 4);
来源：http://dali.yuanzhike.top/Article/details/gt2bhrgczpp.html

Go:   arr[1:4]
来源：http://dali.jqgufenzy.top/Article/details/gt2nibzdrln.html

Ruby: arr[1, 3]
来源：http://dali.iojbl.cn/Article/details/gt2tjqckwxe.html

C#:   list.GetRange(1, 3);
来源：http://dali.iojbl.cn/Article/details/gt2ocqwmydc.html

[D08] 合并两个数组
来源：http://dali.hywenlv.cn/Article/details/gt2ylcutmcv.html

Py:   a + b;  a.extend(b)
来源：http://dali.fzhhl.top/Article/details/gt2okqulaii.html

PHP:  array_merge($a, $b);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vbsetflt.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.bjfxy.top/Article/details/gt2duwuzoxe.html

TS:   [...a, ...b];
来源：http://dali.ppjwa.cn/Article/details/gt2zrkjdxhi.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2wcjmiktt.html

Go:   append(a, b...)
来源：http://dali.cdnleiting.top/Article/details/gt2ebendusd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhongyouzk.top/Article/details/gt2apuobkvt.html

C#:   a.Concat(b).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2xjsfpnxj.html

[D09] 排序（升序）
来源：http://dali.yanxiufei.cn/Article/details/gt2drzrhpja.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yongpay.top/Article/details/gt2kxsbighl.html

PHP:  sort($arr);
来源：http://dali.ybcxt.top/Article/details/gt2sszuxphh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.tianlin.xyz/Article/details/gt2gfaqsujh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.wangdashe.top/Article/details/gt2tlcxsnnl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sxryk.cn/Article/details/gt2veajsnwl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2vmsbluds.html

Ruby: arr.sort
来源：http://dali.yueranfly.top/Article/details/gt2eslbzlfl.html

C#:   list.Sort();
来源：http://dali.hnqzz.top/Article/details/gt2ipgjxxiz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.guannengcc.top/Article/details/gt2xhujdxdk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.nwbrower.top/Article/details/gt2vwjikhjn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jqgufenzy.top/Article/details/gt2njfbvvnd.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yanxiufei.cn/Article/details/gt2unnutizf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.316326.xyz/Article/details/gt2ddruxjvq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ltrbvhes.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.daria6918.cn/Article/details/gt2aiedraoz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sxryk.cn/Article/details/gt2pzkfaevj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yj20258.top/Article/details/gt2gjsqnovn.html

[D11] 反转数组
来源：http://dali.wangdashe.top/Article/details/gt2nhrzckjj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.meibo888.top/Article/details/gt2spayqzci.html

PHP:  array_reverse($arr);
来源：http://dali.tian-w.cn/Article/details/gt2ezodghyl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.kuanghao11.cn/Article/details/gt2cozilumd.html

TS:   [...arr].reverse();
来源：http://dali.cashguo.top/Article/details/gt2tolgowwb.html

Java: Collections.reverse(list);
来源：http://dali.cashguo.top/Article/details/gt2obhzqldz.html

Go:   slices.Reverse(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2fhfstelq.html

Ruby: arr.reverse
来源：http://dali.yj202588.top/Article/details/gt2pnrewjpo.html

C#:   list.Reverse();
来源：http://dali.ehwqpu.com/Article/details/gt2mymywleg.html

[D12] 查找元素下标
来源：http://dali.jianghu66.top/Article/details/gt2gjskpfue.html

Py:   arr.index(x);  x in arr
来源：http://dali.mhx1999.top/Article/details/gt2flzvvysi.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sdfhvybs.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.mhx1999.top/Article/details/gt2vwhwuukr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ppjwa.cn/Article/details/gt2trcrvump.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cljreilm.html

Go:   slices.Index(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gt2aftqaaqn.html

Ruby: arr.index(x)
来源：http://dali.zhixingplan.top/Article/details/gt2jyaxxofy.html

C#:   list.IndexOf(x);
来源：http://dali.redwolf501.top/Article/details/gt2qsdyaqwb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jlsjyb.cn/Article/details/gt2zhkpfodz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.haohaochexian.top/Article/details/gt2aeeggamq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cdnleiting.top/Article/details/gt2akqdeknz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yj202588.top/Article/details/gt2dqzgtngh.html

TS:   arr.filter(x => x > 3)
来源：http://dali.guowangkeji.top/Article/details/gt2commmwzj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.chenlongwang.top/Article/details/gt2uyydgfyk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ydzc1.top/Article/details/gt2stbeqteu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yvedp.cn/Article/details/gt2ppybkkjl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gt2xmsyashr.html

[D14] 映射转换（每个元素变形）
来源：http://dali.guowangkeji.top/Article/details/gt2shixpnvy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.0kj1m.cn/Article/details/gt2phtybceq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yongpay.top/Article/details/gt2fuxzvedb.html

JS:   arr.map(x => x * 2)
来源：http://dali.hfpthk.cn/Article/details/gt2ghbprpev.html

TS:   arr.map(x => x * 2)
来源：http://dali.xuanzx.com/Article/details/gt2pvufgvhh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.chenlongwang.top/Article/details/gt2knmtgxgn.html

Go:   // 手写循环
来源：http://dali.feifeiyinyue.top/Article/details/gt2brkneygs.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yvedp.cn/Article/details/gt2zqrvxptn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ybcxt.top/Article/details/gt2lczwzzli.html

[D15] 去重
来源：http://dali.zhixingplan.top/Article/details/gt2gxzlaydq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.meibo888.top/Article/details/gt2sdcapslv.html

PHP:  array_unique($arr);
来源：http://dali.yvedp.cn/Article/details/gt2aajxydye.html

JS:   [...new Set(arr)]
来源：http://dali.jinqigfzy.top/Article/details/gt2irwmkiaj.html

TS:   [...new Set(arr)]
来源：http://dali.hfpthk.cn/Article/details/gt2aozhnvvb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.nanxinkj.top/Article/details/gt2rjrlqjup.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yanxiufei.cn/Article/details/gt2jktwfamw.html

Ruby: arr.uniq
来源：http://dali.wangshuangyany.cn/Article/details/gt2bvjuqrqx.html

C#:   list.Distinct().ToList()
来源：http://dali.c1oappe.top/Article/details/gt2rngppbaz.html

[D16] 求和与平均值
来源：http://dali.yj202588.top/Article/details/gt2czqgxnsm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cheryme.top/Article/details/gt2erigpwcf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jyoumei.cn/Article/details/gt2gbrmggtx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ibwgdgwb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuanzx.com/Article/details/gt2qrcnvway.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ehwqpu.com/Article/details/gt2wkwnepko.html

Go:   // 手写循环累加
来源：http://dali.xuanzx.com/Article/details/gt2wqqlwahf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hnqzz.top/Article/details/gt2umsdcjeo.html

C#:   list.Sum();  list.Average()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fkywhdbl.html

[D17] 最大值与最小值
来源：http://dali.daxiang520.top/Article/details/gt2tctjasgy.html

Py:   max(arr);  min(arr)
来源：http://dali.wangdashe.top/Article/details/gt2lqwxhycl.html

PHP:  max($arr);  min($arr);
来源：http://dali.chenlongwang.top/Article/details/gt2islttiof.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.birdmap.top/Article/details/gt2wskuqpez.html

TS:   Math.max(...arr);
来源：http://dali.iojbl.cn/Article/details/gt2eayvlxfc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xylfe.cn/Article/details/gt2xulfknuw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.meibo888.top/Article/details/gt2gyyqcbuy.html

Ruby: arr.max;  arr.min
来源：http://dali.chenjidiqi.icu/Article/details/gt2vvjhzunf.html

C#:   list.Max();  list.Min()
来源：http://dali.zycfv.cn/Article/details/gt2uixawerh.html

[D18] 扁平化嵌套数组
来源：http://dali.hfpthk.cn/Article/details/gt2uehngbjh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.quarkkingdee.top/Article/details/gt2abjbhwks.html

PHP:  array_merge(...$nested);
来源：http://dali.fzhhl.top/Article/details/gt2qutytwut.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.birdmap.top/Article/details/gt2demcojfa.html

TS:   nested.flat();
来源：http://dali.xziqi.cn/Article/details/gt2rbjfvfbj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yuanzhike.top/Article/details/gt2znpzrtho.html

Go:   // 手写双层循环
来源：http://dali.shuidangran.top/Article/details/gt2sjlcalfe.html

Ruby: nested.flatten
来源：http://dali.daxiang520.top/Article/details/gt2nrgulyau.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ybcxt.top/Article/details/gt2idbvqavd.html

[D19] 按字段分组
来源：http://dali.316326.xyz/Article/details/gt2dqxupkiy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yj20258888.top/Article/details/gt2dxxxwmgg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.birdmap.top/Article/details/gt2habxjqad.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.0kj1m.cn/Article/details/gt2mlkyzxoy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jyoumei.cn/Article/details/gt2ploixdyw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gotoacloud.top/Article/details/gt2rovmcbci.html

Go:   // 手写 map[string][]T
来源：http://dali.snrcjt.cn/Article/details/gt2onsckaht.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.aizwys.cn/Article/details/gt2ylteubpr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhoulong.xyz/Article/details/gt2lifdjogk.html

[D20] 统计每个元素出现次数
来源：http://dali.svipenyu.cn/Article/details/gt2eqqzcxxz.html

Py:   Counter(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2qieizcvf.html

PHP:  array_count_values($arr);
来源：http://dali.xuanzx.com/Article/details/gt2ttbburod.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.havefunace.top/Article/details/gt2kvlcrrww.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cdnleiting.top/Article/details/gt2uujkiipm.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.tanke756.top/Article/details/gt2watxptnw.html

Go:   // 手写 map[T]int
来源：http://dali.yanxiufei.cn/Article/details/gt2hldefqnk.html

Ruby: arr.tally
来源：http://dali.shuidangran.top/Article/details/gt2zhlimtpp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shuidangran.top/Article/details/gt2cqwwxccl.html

[D21] 判断是否包含某元素
来源：http://dali.wangdashe.top/Article/details/gt2anohkpnk.html

Py:   x in arr
来源：http://dali.tanke756.top/Article/details/gt2grbmnyeu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hksmojph.html

JS:   arr.includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hwbohyvo.html

TS:   arr.includes(x)
来源：http://dali.yonumen.top/Article/details/gt2sjdzatcu.html

Java: list.contains(x)
来源：http://dali.yuxming.cn/Article/details/gt2snvqmzdq.html

Go:   slices.Contains(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gt2uxufaeiw.html

Ruby: arr.include?(x)
来源：http://dali.yonumen.top/Article/details/gt2ybphtxep.html

C#:   list.Contains(x)
来源：http://dali.ydzc1.top/Article/details/gt2vdxghkuj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hnqzz.top/Article/details/gt2gbvrikbs.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.redwolf501.top/Article/details/gt2bewauwkj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.0kj1m.cn/Article/details/gt2napqfzpj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sysykeji.top/Article/details/gt2kafdhyct.html

TS:   [...arr];
来源：http://dali.chenzaomai.com/Article/details/gt2lfjmdzeo.html

Java: new ArrayList<>(list);
来源：http://dali.wangshuangyany.cn/Article/details/gt2fnvdmkmc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhixingplan.top/Article/details/gt2ykfiijot.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gogol.net.cn/Article/details/gt2kzfpbocj.html

C#:   new List<int>(list);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ilmptftm.html

[D23] reduce 累积计算
来源：http://dali.yangfankeji.com/Article/details/gt2okubjvap.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.svipenyu.cn/Article/details/gt2uhsuizxv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lzdncigk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.kuanghao11.cn/Article/details/gt2zhgqfepp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gzhubu.top/Article/details/gt2twoalgzo.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ivvv.top/Article/details/gt2skcaqunk.html

Go:   // 手写循环
来源：http://dali.xziqi.cn/Article/details/gt2hmwyyfkf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hongshengwenyu.top/Article/details/gt2ccvjghip.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.aibaodan.cn/Article/details/gt2awlsantu.html

[D24] 字典 / Map 基本操作
来源：http://dali.xinyue.icu/Article/details/gt2ixghzzzd.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hfpthk.cn/Article/details/gt2wbekxngw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yonumen.top/Article/details/gt2ofsucaac.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jianghu66.top/Article/details/gt2fxkgptcq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yongpay.top/Article/details/gt2qjseveip.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.kuanghao11.cn/Article/details/gt2zalqjsvq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cashguo.top/Article/details/gt2ttynjjin.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yj20258.top/Article/details/gt2aagdheyx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cdnleiting.top/Article/details/gt2fmilcwwi.html

[D25] Set 集合去重与交并差
来源：http://dali.ehwqpu.com/Article/details/gt2ehggfgoa.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.feifeiyinyue.top/Article/details/gt2yxtxjwqw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.tanke756.top/Article/details/gt2fkibnxvz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.dashuyun.cn/Article/details/gt2plobgasl.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhengqikj.top/Article/details/gt2vwkgmpvz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.nwbrower.top/Article/details/gt2pxroohfj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ppjwa.cn/Article/details/gt2ipyjqiin.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2wrwnajiw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jiagoushi.top/Article/details/gt2srarrsyz.html

[D26] 数组转字符串
来源：http://dali.ydzc1.top/Article/details/gt2neipvici.html

Py:   ", ".join(map(str, arr))
来源：http://dali.smart0.xyz/Article/details/gt2murjvzzc.html

PHP:  implode(", ", $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2surxsssx.html

JS:   arr.join(", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ebzauskx.html

TS:   arr.join(", ")
来源：http://dali.birdmap.top/Article/details/gt2luxvrxgh.html

Java: String.join(", ", list)
来源：http://dali.haohaochexian.top/Article/details/gt2iiaccnbq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cqqwz.cn/Article/details/gt2nynvjquz.html

Ruby: arr.join(", ")
来源：http://dali.guowangkeji.top/Article/details/gt2wqtvdpkx.html

C#:   string.Join(", ", list)
来源：http://dali.yvedp.cn/Article/details/gt2yqkyoxvs.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2itjdsdsb.html

E. 字符串处理
来源：http://dali.cucudq.cn/Article/details/gt2zhyzkoxw.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2excvluom.html

[E01] 拼接字符串
来源：http://dali.pycfn.com/Article/details/gt2vlopjtfo.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sufxvd.cn/Article/details/gt2vtvjcoze.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinqigfzy.top/Article/details/gt2sezemtfb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.andypj.xyz/Article/details/gt2kgmivlzj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.0kj1m.cn/Article/details/gt2pizgrltd.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.redwolf501.top/Article/details/gt2kgargydg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gaohongyu789.top/Article/details/gt2ehddtjpk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.bjfxy.top/Article/details/gt2dgtcqumo.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gt2fbrqxqoy.html

[E02] 重复字符串
来源：http://dali.xziqi.cn/Article/details/gt2qsdfixmh.html

Py:   "ab" * 3
来源：http://dali.jiagoushi.top/Article/details/gt2pooygxfk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.svipenyu.cn/Article/details/gt2wnqrbwtf.html

JS:   "ab".repeat(3)
来源：http://dali.yj202588.top/Article/details/gt2uyzahucg.html

TS:   "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gt2ebuxokcs.html

Java: "ab".repeat(3)
来源：http://dali.chenlongwang.top/Article/details/gt2mnujvxvw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.guannengcc.top/Article/details/gt2njqwvqyr.html

Ruby: "ab" * 3
来源：http://dali.sxryk.cn/Article/details/gt2anjchvdp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yj202588.top/Article/details/gt2wcprpfit.html

[E03] 截取子串
来源：http://dali.9152youxi.cn/Article/details/gt2ntiegqmn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xinyue.icu/Article/details/gt2rnhqyolg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gt2vkslrnsn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.haohaochexian.top/Article/details/gt2tasvbfsf.html

TS:   s.slice(1, 4)
来源：http://dali.kuanghao11.cn/Article/details/gt2yqoquqpv.html

Java: s.substring(1, 4)
来源：http://dali.yanxiufei.cn/Article/details/gt2kgqnexmg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.dashuyun.cn/Article/details/gt2wasoagfj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.chenlongwang.top/Article/details/gt2ajcyankx.html

C#:   s.Substring(1, 3)
来源：http://dali.andypj.xyz/Article/details/gt2vrpzdmgc.html

[E04] 查找子串位置
来源：http://dali.havefunace.top/Article/details/gt2nykezuvo.html

Py:   s.find("x");  s.index("x")
来源：http://dali.redwolf501.top/Article/details/gt2cdguddxo.html

PHP:  strpos($s, "x");
来源：http://dali.yangfankeji.com/Article/details/gt2ihvqmmve.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kwngpkvu.html

TS:   s.indexOf("x")
来源：http://dali.haohaochexian.top/Article/details/gt2vgyhunlu.html

Java: s.indexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gt2dxiwdocr.html

Go:   strings.Index(s, "x")
来源：http://dali.wangshuangyany.cn/Article/details/gt2untviotb.html

Ruby: s.index("x")
来源：http://dali.guannengcc.top/Article/details/gt2ndwdsomo.html

C#:   s.IndexOf("x")
来源：http://dali.xuetiantiany.cn/Article/details/gt2tzwpqvrd.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.guannengcc.top/Article/details/gt2tvvttgks.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gt2wexrqczj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gaohongyu789.top/Article/details/gt2umfsanvj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.aizwys.cn/Article/details/gt2bzzytnwb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ppjwa.cn/Article/details/gt2vjrgyuuo.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.mhx1999.top/Article/details/gt2kuvmswgf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hnqzz.top/Article/details/gt2jawgcugx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sxryk.cn/Article/details/gt2coxqijpk.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cashguo.top/Article/details/gt2wnjezgoh.html

[E06] 替换子串
来源：http://dali.ehwqpu.com/Article/details/gt2feauehge.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhengqikj.top/Article/details/gt2gmsphqdi.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ivvv.top/Article/details/gt2hfuxifwc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gt2aacvtuzw.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hammf.cn/Article/details/gt2puwjyirh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.redwolf501.top/Article/details/gt2vkfwtfua.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.nwbrower.top/Article/details/gt2rrihbott.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gt2xuzunvez.html

C#:   s.Replace("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gt2qtmfbjlc.html

[E07] 按分隔符拆分
来源：http://dali.xinyue.icu/Article/details/gt2qcszgupq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cashguo.top/Article/details/gt2tcwvkyzi.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yj202588.top/Article/details/gt2expcbtnm.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hywenlv.cn/Article/details/gt2bmvrjslc.html

TS:   s.split(",")
来源：http://dali.jinqigfzy.top/Article/details/gt2wenwubou.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sweek.top/Article/details/gt2otuktyis.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.guowangkeji.top/Article/details/gt2ibqvtbdh.html

Ruby: s.split(",");  s.split
来源：http://dali.jyoumei.cn/Article/details/gt2bnxxhsnr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cqqwz.cn/Article/details/gt2iuybjnbl.html

[E08] 数组按分隔符合并
来源：http://dali.vqdsnc.cn/Article/details/gt2mqdszapr.html

Py:   ",".join(items)
来源：http://dali.chenlongwang.top/Article/details/gt2tyrpapow.html

PHP:  implode(",", $items);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gjdglpki.html

JS:   items.join(",")
来源：http://dali.cucudq.cn/Article/details/gt2atqlgjgn.html

TS:   items.join(",")
来源：http://dali.andypj.xyz/Article/details/gt2ndgylyoj.html

Java: String.join(",", items)
来源：http://dali.gotoacloud.top/Article/details/gt2epayuvew.html

Go:   strings.Join(items, ",")
来源：http://dali.ehwqpu.com/Article/details/gt2ttdsyzgf.html

Ruby: items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gt2qpqiddat.html

C#:   string.Join(",", items)
来源：http://dali.ybcxt.top/Article/details/gt2xsuejnzo.html

[E09] 去除所有空白字符
来源：http://dali.tanke756.top/Article/details/gt2ytlvmkwo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.bjfxy.top/Article/details/gt2skdcepdr.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shuidangran.top/Article/details/gt2zlxliueq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cheryme.top/Article/details/gt2smylonmf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jyoumei.cn/Article/details/gt2qqyyfeoh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hysaishi.cn/Article/details/gt2uhhyljpg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.9152youxi.cn/Article/details/gt2mbthzmwc.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gaohongyu789.top/Article/details/gt2euuuexev.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ejeuywjd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj202588.top/Article/details/gt2wapwnkex.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gt2lbyehciv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hammf.cn/Article/details/gt2ktewvtcc.html

JS:   "7".padStart(3, "0")
来源：http://dali.sweek.top/Article/details/gt2appovvpp.html

TS:   "7".padStart(3, "0")
来源：http://dali.aizwys.cn/Article/details/gt2zgzlrmjp.html

Java: String.format("%03d", 7)
来源：http://dali.quarkkingdee.top/Article/details/gt2hnxplwwy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhixingplan.top/Article/details/gt2kdqqrobn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2lchfnwlv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinqigufen.top/Article/details/gt2utkabpeg.html

[E11] 反转字符串
来源：http://dali.cqqwz.cn/Article/details/gt2johjxgrv.html

Py:   s[::-1]
来源：http://dali.hfpthk.cn/Article/details/gt2diofhcpg.html

PHP:  strrev($s);
来源：http://dali.aibaodan.cn/Article/details/gt2xsitulad.html

JS:   [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gt2svahgeyr.html

TS:   [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gt2cbkdldal.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.andypj.xyz/Article/details/gt2xyaqfsst.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.feifeiyinyue.top/Article/details/gt2ezpobdem.html

Ruby: s.reverse
来源：http://dali.yj20258888.top/Article/details/gt2tqtsgbpe.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zdqjudy.top/Article/details/gt2bwttnbyx.html

[E12] 统计某字符出现次数
来源：http://dali.316326.xyz/Article/details/gt2xgcxartm.html

Py:   s.count("a")
来源：http://dali.guowangkeji.top/Article/details/gt2vwqhzoef.html

PHP:  substr_count($s, "a");
来源：http://dali.ydzc1.top/Article/details/gt2yuarszwh.html

JS:   s.split("a").length - 1
来源：http://dali.fengsongda.top/Article/details/gt2qrqrxpna.html

TS:   s.split("a").length - 1
来源：http://dali.fengsongda.top/Article/details/gt2ibnmwzfo.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ydzc1.top/Article/details/gt2petaeyrl.html

Go:   strings.Count(s, "a")
来源：http://dali.zhoulong.xyz/Article/details/gt2eyxuqand.html

Ruby: s.count("a")
来源：http://dali.yonumen.top/Article/details/gt2tlzrvfaj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yuanzhike.top/Article/details/gt2yobudppv.html

[E13] 逐字符遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uykqotkt.html

Py:   for ch in s: print(ch)
来源：http://dali.tian-w.cn/Article/details/gt2jbhwrsuu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.quarkkingdee.top/Article/details/gt2amfpvgza.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2llxykyeh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yvedp.cn/Article/details/gt2rdeaijwi.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ecwdtzit.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yuanzhike.top/Article/details/gt2jexnouyx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nhyivtwy.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.0kj1m.cn/Article/details/gt2fengjmph.html

[E14] URL 编码与 Base64
来源：http://dali.hywenlv.cn/Article/details/gt2raqynfqx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.chenzaomai.com/Article/details/gt2naflajoj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hysaishi.cn/Article/details/gt2oszpedeb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gotoacloud.top/Article/details/gt2ksefodnb.html


<!-- 参考信息 -->