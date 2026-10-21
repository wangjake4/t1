代发 wailian999

TS:   arr.slice(1, 4);
来源：http://dali.yuanzhike.top/Article/details/gtmmpvfkhw.html

Java: list.subList(1, 4);
来源：http://dali.pengpengdd.cyou/Article/details/gteuybewed.html

Go:   arr[1:4]
来源：http://dali.sysykeji.top/Article/details/gtjyjfzkzs.html

Ruby: arr[1, 3]
来源：http://dali.jinqigfzy.top/Article/details/gtarigepob.html

C#:   list.GetRange(1, 3);
来源：http://dali.birdmap.top/Article/details/gtdonjphhc.html

[D08] 合并两个数组
来源：http://dali.zhengqikj.top/Article/details/gthltbschg.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsemodrfj.html

PHP:  array_merge($a, $b);
来源：http://dali.jiagoushi.top/Article/details/gtszuymkjq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhiwuduotai.top/Article/details/gtoerkshmn.html

TS:   [...a, ...b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttjzkzxgw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.fengsongda.top/Article/details/gtjazadfpv.html

Go:   append(a, b...)
来源：http://dali.dashuyun.cn/Article/details/gtfmydfsck.html

Ruby: a + b;  a.concat(b)
来源：http://dali.0kj1m.cn/Article/details/gtlfbtbupd.html

C#:   a.Concat(b).ToList()
来源：http://dali.mhx1999.top/Article/details/gthcikpdpw.html

[D09] 排序（升序）
来源：http://dali.zhongyouzk.top/Article/details/gtbnsqeble.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhiwuduotai.top/Article/details/gthkqhdgcf.html

PHP:  sort($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteneaxvxy.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenjidiqi.icu/Article/details/gtrwrtyflx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.aibaodan.cn/Article/details/gtdcqyuwpr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.pycfn.com/Article/details/gtrwofywlq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.dashuyun.cn/Article/details/gtupibhttx.html

Ruby: arr.sort
来源：http://dali.yj20258888.top/Article/details/gthyejvkhe.html

C#:   list.Sort();
来源：http://dali.fengsongda.top/Article/details/gtmelrfckr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jyoumei.cn/Article/details/gtvvmrgmlt.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ehwqpu.com/Article/details/gtswbbffkm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tian-w.cn/Article/details/gtqzyividp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ydzc1.top/Article/details/gtlwsbfhsu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sysykeji.top/Article/details/gtiayymgep.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.meibo888.top/Article/details/gtqdyuebcp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hnqzz.top/Article/details/gtylbpjhkl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.kuanghao11.cn/Article/details/gtasvpkeyf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shanyushiyangtech.top/Article/details/gtpfajdern.html

[D11] 反转数组
来源：http://dali.shanyushiyangtech.top/Article/details/gtdbadtolq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.feifeiyinyue.top/Article/details/gtwygjmyac.html

PHP:  array_reverse($arr);
来源：http://dali.jinqigufen.top/Article/details/gtlfyxkcib.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yj202588.top/Article/details/gtqqcjbsgr.html

TS:   [...arr].reverse();
来源：http://dali.cucudq.cn/Article/details/gthiglvuki.html

Java: Collections.reverse(list);
来源：http://dali.yangfankeji.com/Article/details/gtfqtermja.html

Go:   slices.Reverse(arr)
来源：http://dali.fzhhl.top/Article/details/gtyrhapuiq.html

Ruby: arr.reverse
来源：http://dali.cheryme.top/Article/details/gtlbjalwdk.html

C#:   list.Reverse();
来源：http://dali.guannengcc.top/Article/details/gtytreymtu.html

[D12] 查找元素下标
来源：http://dali.cucudq.cn/Article/details/gtijklokjq.html

Py:   arr.index(x);  x in arr
来源：http://dali.smart0.xyz/Article/details/gttcmmhjut.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xuanzx.com/Article/details/gtlptlzngb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jlsjyb.cn/Article/details/gtjzkvlxwm.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbjelqmji.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jinghuilouyu.cn/Article/details/gtoqmuwmjj.html

Go:   slices.Index(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtvhoszmgj.html

Ruby: arr.index(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtqhwptxsy.html

C#:   list.IndexOf(x);
来源：http://dali.shangyingyoupin.top/Article/details/gtqitsxvxs.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hammf.cn/Article/details/gtpfpbmxjl.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hnxiangtu.top/Article/details/gtcdbtrmku.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtmeqztzli.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sysykeji.top/Article/details/gtqjqgznya.html

TS:   arr.filter(x => x > 3)
来源：http://dali.daria6918.cn/Article/details/gtmfxfnbxl.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.c1oappe.top/Article/details/gtopsnrxof.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.aibaodan.cn/Article/details/gtdvhncxla.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yuxming.cn/Article/details/gtsksghqok.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.sysykeji.top/Article/details/gtyxznbvhv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yuxming.cn/Article/details/gtbmvvmrsj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.pengpengdd.cyou/Article/details/gtzjzxlpfe.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.andypj.xyz/Article/details/gtwlzrwbye.html

JS:   arr.map(x => x * 2)
来源：http://dali.havefunace.top/Article/details/gttdcpswzv.html

TS:   arr.map(x => x * 2)
来源：http://dali.svipenyu.cn/Article/details/gtpfwqqdye.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.nanxinkj.top/Article/details/gtlpfjwtye.html

Go:   // 手写循环
来源：http://dali.316326.xyz/Article/details/gtcbbtkbfb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.c1oappe.top/Article/details/gtzorkfoin.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtbxofkolp.html

[D15] 去重
来源：http://dali.yuanzhike.top/Article/details/gtzqemdrpj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jqgufenzy.top/Article/details/gtwbebwpmt.html

PHP:  array_unique($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtjcwpiqtr.html

JS:   [...new Set(arr)]
来源：http://dali.birdmap.top/Article/details/gttzjmemfg.html

TS:   [...new Set(arr)]
来源：http://dali.yanxiufei.cn/Article/details/gtgzbequxh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.pengpengdd.cyou/Article/details/gtklmjlxct.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nanxuanxn.top/Article/details/gtmqihzxen.html

Ruby: arr.uniq
来源：http://dali.zhengqikj.top/Article/details/gtpjawjnow.html

C#:   list.Distinct().ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtkjtkbtmv.html

[D16] 求和与平均值
来源：http://dali.yueranfly.top/Article/details/gtshfaiuka.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtbttudhro.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkltspuxt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangdashe.top/Article/details/gtptzjrejh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fzhhl.top/Article/details/gtddphrcop.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.nanxuanxn.top/Article/details/gtgamomxoo.html

Go:   // 手写循环累加
来源：http://dali.sxryk.cn/Article/details/gtkvjevtyl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gogol.net.cn/Article/details/gtmcrwkunj.html

C#:   list.Sum();  list.Average()
来源：http://dali.shangyingyoupin.top/Article/details/gtbmpavqdj.html

[D17] 最大值与最小值
来源：http://dali.aibaodan.cn/Article/details/gtwdgdmdkm.html

Py:   max(arr);  min(arr)
来源：http://dali.redwolf501.top/Article/details/gtwfxhyjho.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinqigufen.top/Article/details/gtpuqgqaxi.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jianghu66.top/Article/details/gtsqqbheyl.html

TS:   Math.max(...arr);
来源：http://dali.shzxlz.cn/Article/details/gtctmmhvtv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjlgyzuzb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtrvoalvbz.html

Ruby: arr.max;  arr.min
来源：http://dali.yuanzhike.top/Article/details/gtgkugwfjt.html

C#:   list.Max();  list.Min()
来源：http://dali.xylfe.cn/Article/details/gtjmodnvkm.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gtqxhdyyby.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zdqjudy.top/Article/details/gtylrdpynx.html

PHP:  array_merge(...$nested);
来源：http://dali.zycfv.cn/Article/details/gtidbxyyzd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gzhubu.top/Article/details/gtjzlyhvnv.html

TS:   nested.flat();
来源：http://dali.jinqigfzy.top/Article/details/gttwmzlvfp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gogol.net.cn/Article/details/gtmwukhvpu.html

Go:   // 手写双层循环
来源：http://dali.ydzc1.top/Article/details/gtesteyzub.html

Ruby: nested.flatten
来源：http://dali.0kj1m.cn/Article/details/gtaigsdzki.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.haohaochexian.top/Article/details/gtertegfcm.html

[D19] 按字段分组
来源：http://dali.hnxiangtu.top/Article/details/gtdfxsiedq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.tianlin.xyz/Article/details/gtptpzfujy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ivvv.top/Article/details/gtskvfjhpn.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shanyushiyangtech.top/Article/details/gtyqyyabrf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xziqi.cn/Article/details/gtmjikmgys.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gtkcykimvo.html

Go:   // 手写 map[string][]T
来源：http://dali.gaohongyu789.top/Article/details/gtipctaxgl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cheryme.top/Article/details/gtkdjphxix.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shzxlz.cn/Article/details/gtwpvylvpi.html

[D20] 统计每个元素出现次数
来源：http://dali.bjfxy.top/Article/details/gtttksehar.html

Py:   Counter(arr)
来源：http://dali.zhengqikj.top/Article/details/gtxcjejoun.html

PHP:  array_count_values($arr);
来源：http://dali.ppjwa.cn/Article/details/gtipmjpnju.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cucudq.cn/Article/details/gtpacwggsg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj202588.top/Article/details/gtijxwgtyp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gtvvmxvjst.html

Go:   // 手写 map[T]int
来源：http://dali.aibaodan.cn/Article/details/gtuyhneigm.html

Ruby: arr.tally
来源：http://dali.hongshengwenyu.top/Article/details/gtznfduakq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xinyue.icu/Article/details/gtvacoyhzh.html

[D21] 判断是否包含某元素
来源：http://dali.yj20258.top/Article/details/gtycjlcjva.html

Py:   x in arr
来源：http://dali.daxiang520.top/Article/details/gtbvrcjcsh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.c1oappe.top/Article/details/gtikecnfom.html

JS:   arr.includes(x)
来源：http://dali.dashuyun.cn/Article/details/gtcfzblgtn.html

TS:   arr.includes(x)
来源：http://dali.sufxvd.cn/Article/details/gtwfoakygs.html

Java: list.contains(x)
来源：http://dali.zhixingplan.top/Article/details/gtpgfqkuzs.html

Go:   slices.Contains(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtouoldxfc.html

Ruby: arr.include?(x)
来源：http://dali.316326.xyz/Article/details/gtflywndji.html

C#:   list.Contains(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtzbnobxcf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yangfankeji.com/Article/details/gtyvtaljnm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbiylaisw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hfpthk.cn/Article/details/gtiyjsvttq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.guannengcc.top/Article/details/gtaqcoiicl.html

TS:   [...arr];
来源：http://dali.iojbl.cn/Article/details/gtrrqjdrrb.html

Java: new ArrayList<>(list);
来源：http://dali.shzxlz.cn/Article/details/gtkjuruyok.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zdqjudy.top/Article/details/gtrhbhdkqb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj20258.top/Article/details/gtvujqjywd.html

C#:   new List<int>(list);
来源：http://dali.ybcxt.top/Article/details/gtkkzpzjai.html

[D23] reduce 累积计算
来源：http://dali.cqqwz.cn/Article/details/gtcimuvtay.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hfpthk.cn/Article/details/gtifsyslaw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtaifycmkm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxinkj.top/Article/details/gtfmvzdwab.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtmhagusnn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenzaomai.com/Article/details/gtpsyjntmd.html

Go:   // 手写循环
来源：http://dali.aizwys.cn/Article/details/gtlvmlnyan.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sufxvd.cn/Article/details/gtnbbbezfy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.haohaochexian.top/Article/details/gtdsrujczj.html

[D24] 字典 / Map 基本操作
来源：http://dali.sufxvd.cn/Article/details/gttioquqks.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yvedp.cn/Article/details/gtcvkpuqvh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ivvv.top/Article/details/gtchryndnl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhongyouzk.top/Article/details/gtlveatpqa.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gttkzmygsx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jqgfzy.top/Article/details/gtiusbrtrh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gogol.net.cn/Article/details/gthijzafji.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.feifeiyinyue.top/Article/details/gthsxlxjro.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shuidangran.top/Article/details/gtwswfdohy.html

[D25] Set 集合去重与交并差
来源：http://dali.gotoacloud.top/Article/details/gtbvqymmoa.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xinyue.icu/Article/details/gtwhtqogza.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.fengsongda.top/Article/details/gtcvykgjsd.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yongpay.top/Article/details/gtitutekuv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.nanxinkj.top/Article/details/gtkynisjme.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zdqjudy.top/Article/details/gtkbsxyach.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.aibaodan.cn/Article/details/gtunoorkgi.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hnxiangtu.top/Article/details/gtgoizuwpy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.haohaochexian.top/Article/details/gtgfuxzuoc.html

[D26] 数组转字符串
来源：http://dali.c1oappe.top/Article/details/gtzhcvtibi.html

Py:   ", ".join(map(str, arr))
来源：http://dali.feifeiyinyue.top/Article/details/gtyxzvslue.html

PHP:  implode(", ", $arr);
来源：http://dali.iojbl.cn/Article/details/gtliivfdgv.html

JS:   arr.join(", ")
来源：http://dali.daria6918.cn/Article/details/gtnvccljma.html

TS:   arr.join(", ")
来源：http://dali.smart0.xyz/Article/details/gtmtvammma.html

Java: String.join(", ", list)
来源：http://dali.tianlin.xyz/Article/details/gtqgzculvl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yj202588.top/Article/details/gtwqucofue.html

Ruby: arr.join(", ")
来源：http://dali.jiagoushi.top/Article/details/gtzxktyzdu.html

C#:   string.Join(", ", list)
来源：http://dali.jianghu66.top/Article/details/gtnfomhvzl.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtprztptyq.html

E. 字符串处理
来源：http://dali.ivvv.top/Article/details/gtkbypaisb.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtzmszskut.html

[E01] 拼接字符串
来源：http://dali.andypj.xyz/Article/details/gtrvavifgh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.c1oappe.top/Article/details/gtdwfgvohq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsqdtqizu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xziqi.cn/Article/details/gtkhkrjwsd.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtaqvgqcdn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gaohongyu789.top/Article/details/gttyfispqf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xylfe.cn/Article/details/gtpjaexdak.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yj202588.top/Article/details/gtzrwyynjt.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtznlwrugj.html

[E02] 重复字符串
来源：http://dali.andypj.xyz/Article/details/gtazifzjvf.html

Py:   "ab" * 3
来源：http://dali.quarkkingdee.top/Article/details/gtrsjwcpij.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ybcxt.top/Article/details/gthtxpvygd.html

JS:   "ab".repeat(3)
来源：http://dali.chenjidiqi.icu/Article/details/gtbgiiyqog.html

TS:   "ab".repeat(3)
来源：http://dali.chenlongwang.top/Article/details/gtvclwjbbj.html

Java: "ab".repeat(3)
来源：http://dali.pycfn.com/Article/details/gtpozcpkky.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtunqmxyze.html

Ruby: "ab" * 3
来源：http://dali.aizwys.cn/Article/details/gtwleomdhn.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.svipenyu.cn/Article/details/gtpouoqvgk.html

[E03] 截取子串
来源：http://dali.hysaishi.cn/Article/details/gtgoyuhzwn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.iojbl.cn/Article/details/gtzrymvjaw.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gthjxcbssd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zdqjudy.top/Article/details/gtfettqtxt.html

TS:   s.slice(1, 4)
来源：http://dali.xziqi.cn/Article/details/gtvtvisgps.html

Java: s.substring(1, 4)
来源：http://dali.yj20258888.top/Article/details/gtutpkvehv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jinghuilouyu.cn/Article/details/gtdutldnum.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cdnleiting.top/Article/details/gtzetbyczv.html

C#:   s.Substring(1, 3)
来源：http://dali.fzhhl.top/Article/details/gtkidszdna.html

[E04] 查找子串位置
来源：http://dali.xuetiantiany.cn/Article/details/gtceedxcnc.html

Py:   s.find("x");  s.index("x")
来源：http://dali.vqdsnc.cn/Article/details/gtsbfrrkgk.html

PHP:  strpos($s, "x");
来源：http://dali.hnxiangtu.top/Article/details/gtvimcavbm.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shzxlz.cn/Article/details/gtiztxpxvp.html

TS:   s.indexOf("x")
来源：http://dali.yuxming.cn/Article/details/gtzapmsshh.html

Java: s.indexOf("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnqkntrsy.html

Go:   strings.Index(s, "x")
来源：http://dali.jinqigufen.top/Article/details/gtscxxtjgx.html

Ruby: s.index("x")
来源：http://dali.ydzc1.top/Article/details/gtvaybhbfc.html

C#:   s.IndexOf("x")
来源：http://dali.wangshuangyany.cn/Article/details/gtyojzgqiv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.nanxuanxn.top/Article/details/gtqvfrftba.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.redwolf501.top/Article/details/gtryqopafe.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yonumen.top/Article/details/gtouvmhnti.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ivvv.top/Article/details/gtgwvtnzzo.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhongyouzk.top/Article/details/gtaaikollq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gaohongyu789.top/Article/details/gtwguudbxk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jiagoushi.top/Article/details/gtdaykkpqu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cucudq.cn/Article/details/gtburykdst.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gtymgnvoee.html

[E06] 替换子串
来源：http://dali.sweek.top/Article/details/gtlwecgyot.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.0kj1m.cn/Article/details/gtdofjvywo.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.havefunace.top/Article/details/gtotievrpl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gtvwbetybx.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cashguo.top/Article/details/gtjsigfngg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gteujxjant.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhixingplan.top/Article/details/gtiyoegcdi.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtoegzdwrk.html

C#:   s.Replace("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtbxvaziui.html

[E07] 按分隔符拆分
来源：http://dali.jiagoushi.top/Article/details/gtkdvjnizj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shanyushiyangkeji.top/Article/details/gttilksxsy.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xuanzx.com/Article/details/gtvgqkqucc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yvedp.cn/Article/details/gtqtuejtgv.html

TS:   s.split(",")
来源：http://dali.fengsongda.top/Article/details/gtlsfcgsgc.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jqgfzy.top/Article/details/gtohsszzbw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenzaomai.com/Article/details/gtgqqwlbwg.html

Ruby: s.split(",");  s.split
来源：http://dali.xziqi.cn/Article/details/gtemuhjjit.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.gotoacloud.top/Article/details/gtswogurvc.html

[E08] 数组按分隔符合并
来源：http://dali.316326.xyz/Article/details/gtcuytqode.html

Py:   ",".join(items)
来源：http://dali.cdnleiting.top/Article/details/gtnxgoaquw.html

PHP:  implode(",", $items);
来源：http://dali.feifeiyinyue.top/Article/details/gtuaffejty.html

JS:   items.join(",")
来源：http://dali.xuanzx.com/Article/details/gtdmkgdocb.html

TS:   items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gtrduccwnl.html

Java: String.join(",", items)
来源：http://dali.daria6918.cn/Article/details/gtspezdhpp.html

Go:   strings.Join(items, ",")
来源：http://dali.cheryme.top/Article/details/gtxaxtahcf.html

Ruby: items.join(",")
来源：http://dali.svipenyu.cn/Article/details/gtbttnumnc.html

C#:   string.Join(",", items)
来源：http://dali.hywenlv.cn/Article/details/gtfupcydtx.html

[E09] 去除所有空白字符
来源：http://dali.xuetiantiany.cn/Article/details/gttwholomf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shuidangran.top/Article/details/gtxvjhtaap.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.guannengcc.top/Article/details/gthylecrfk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yuanzhike.top/Article/details/gtkjfwkhii.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xinyue.icu/Article/details/gtzjozjuiq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hammf.cn/Article/details/gthhaopscg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.haohaochexian.top/Article/details/gtotmwljax.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hfpthk.cn/Article/details/gtbxhmaciy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.iojbl.cn/Article/details/gtuwhgbcen.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhengqikj.top/Article/details/gtfbxroncm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.redwolf501.top/Article/details/gtraopwxmz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenzaomai.com/Article/details/gtfoedofpj.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gtdtoxwcxn.html

TS:   "7".padStart(3, "0")
来源：http://dali.yj202588.top/Article/details/gtwbhsngge.html

Java: String.format("%03d", 7)
来源：http://dali.iojbl.cn/Article/details/gtvsnscqem.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xylfe.cn/Article/details/gtlrqhgcus.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.mhx1999.top/Article/details/gtrwtfhojj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.wangdashe.top/Article/details/gtauapsjrr.html

[E11] 反转字符串
来源：http://dali.9152youxi.cn/Article/details/gtqcweokeh.html

Py:   s[::-1]
来源：http://dali.yvedp.cn/Article/details/gtifanwkgd.html

PHP:  strrev($s);
来源：http://dali.sweek.top/Article/details/gtovqchmps.html

JS:   [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gtaorundry.html

TS:   [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gttesbuavb.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.wangshuangyany.cn/Article/details/gtjlbkztrk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xuanzx.com/Article/details/gtiefcfiii.html

Ruby: s.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gtlexhpgqz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ydzc1.top/Article/details/gtshsutojm.html

[E12] 统计某字符出现次数
来源：http://dali.nwbrower.top/Article/details/gtefbdeerr.html

Py:   s.count("a")
来源：http://dali.shangyingyoupin.top/Article/details/gtwnmnjnop.html

PHP:  substr_count($s, "a");
来源：http://dali.sufxvd.cn/Article/details/gtquqtsxtv.html

JS:   s.split("a").length - 1
来源：http://dali.andypj.xyz/Article/details/gtgrojpqgw.html

TS:   s.split("a").length - 1
来源：http://dali.yanxiufei.cn/Article/details/gtyeccfwpk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.fzhhl.top/Article/details/gtezalnitb.html

Go:   strings.Count(s, "a")
来源：http://dali.ivvv.top/Article/details/gtatgfgrkb.html

Ruby: s.count("a")
来源：http://dali.vqdsnc.cn/Article/details/gtcehsesqu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.tianlin.xyz/Article/details/gtlqtnmrir.html

[E13] 逐字符遍历
来源：http://dali.jinqigfzy.top/Article/details/gtiehimnxs.html

Py:   for ch in s: print(ch)
来源：http://dali.fengsongda.top/Article/details/gtzmxqfgcw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sysykeji.top/Article/details/gtmqelxgvl.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttaaxxhsi.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hywenlv.cn/Article/details/gtjhegeowa.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nanxinkj.top/Article/details/gtcregbmzr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.meibo888.top/Article/details/gtvrgtavan.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.meibo888.top/Article/details/gttgnmaaey.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sufxvd.cn/Article/details/gtcwvjfbhg.html

[E14] URL 编码与 Base64
来源：http://dali.ppjwa.cn/Article/details/gtiqjehwnl.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.snrcjt.cn/Article/details/gtapocroph.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shuidangran.top/Article/details/gtxzrfwjxd.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinqigufen.top/Article/details/gtgmfmzwru.html


<!-- 参考信息 -->