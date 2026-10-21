代发 wailian999

Java: list.size();
来源：http://dali.guowangkeji.top/Article/details/gtuqmieggb.html

Go:   len(arr)
来源：http://dali.xuanzx.com/Article/details/gtrftocqnp.html

Ruby: arr.length; arr.size
来源：http://dali.sxryk.cn/Article/details/gtnpppoufx.html

C#:   list.Count;
来源：http://dali.yj20258.top/Article/details/gtdkciyrja.html

[D07] 切片 / 取子数组
来源：http://dali.yonumen.top/Article/details/gtfbcjizfv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hnqzz.top/Article/details/gtzsywxpaf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.dianchejie.cn/Article/details/gtwysxozvn.html

JS:   arr.slice(1, 4);
来源：http://dali.zhengqikj.top/Article/details/gtnslbvluu.html

TS:   arr.slice(1, 4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtahuseppe.html

Java: list.subList(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gtbxcgpgbj.html

Go:   arr[1:4]
来源：http://dali.guannengcc.top/Article/details/gttbtvgduc.html

Ruby: arr[1, 3]
来源：http://dali.jinqigufen.top/Article/details/gtghszzigb.html

C#:   list.GetRange(1, 3);
来源：http://dali.chenzaomai.com/Article/details/gtpkvdrqfp.html

[D08] 合并两个数组
来源：http://dali.gogol.net.cn/Article/details/gtaewrtciq.html

Py:   a + b;  a.extend(b)
来源：http://dali.yj20258.top/Article/details/gtamrqwwre.html

PHP:  array_merge($a, $b);
来源：http://dali.gotoacloud.top/Article/details/gtqxgjudvk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.smart0.xyz/Article/details/gtzldwuojr.html

TS:   [...a, ...b];
来源：http://dali.quarkkingdee.top/Article/details/gtbszletdm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtiedsyvzt.html

Go:   append(a, b...)
来源：http://dali.zhiwuduotai.top/Article/details/gtbpsxerul.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yangfankeji.com/Article/details/gtwcemtfsi.html

C#:   a.Concat(b).ToList()
来源：http://dali.hnqzz.top/Article/details/gtsxyrqmcy.html

[D09] 排序（升序）
来源：http://dali.shangyingyoupin.top/Article/details/gtaypouyjz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hongshengwenyu.top/Article/details/gtbsrzcavk.html

PHP:  sort($arr);
来源：http://dali.cheryme.top/Article/details/gtjmamolcg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.wangdashe.top/Article/details/gttabacwma.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zycfv.cn/Article/details/gtljdetppa.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.quarkkingdee.top/Article/details/gtyktrepks.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtwexgbqkz.html

Ruby: arr.sort
来源：http://dali.shuidangran.top/Article/details/gtukgrqimd.html

C#:   list.Sort();
来源：http://dali.hnqzz.top/Article/details/gtavqjxjey.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shanyushiyangtech.top/Article/details/gtvrmgkknw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hfpthk.cn/Article/details/gtgezncxmd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tian-w.cn/Article/details/gtlabzcwku.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yanxiufei.cn/Article/details/gttihvcnns.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.wangdashe.top/Article/details/gtjpgezaid.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.fzhhl.top/Article/details/gtmpkqyvke.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.kuanghao11.cn/Article/details/gtgxrpjakf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shangyingyoupin.top/Article/details/gteiujdafc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hnqzz.top/Article/details/gtzennnrqe.html

[D11] 反转数组
来源：http://dali.redwolf501.top/Article/details/gtyzomdevh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zdqjudy.top/Article/details/gtenjmljvp.html

PHP:  array_reverse($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtxgpgwnra.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.feifeiyinyue.top/Article/details/gtzliegtck.html

TS:   [...arr].reverse();
来源：http://dali.tian-w.cn/Article/details/gtfkavxbcv.html

Java: Collections.reverse(list);
来源：http://dali.fengsongda.top/Article/details/gthwlsrgmv.html

Go:   slices.Reverse(arr)
来源：http://dali.andypj.xyz/Article/details/gttecfdaro.html

Ruby: arr.reverse
来源：http://dali.jinqigfzy.top/Article/details/gtisinzsoc.html

C#:   list.Reverse();
来源：http://dali.meibo888.top/Article/details/gtccvfucqo.html

[D12] 查找元素下标
来源：http://dali.fengsongda.top/Article/details/gtkcocprju.html

Py:   arr.index(x);  x in arr
来源：http://dali.haohaochexian.top/Article/details/gtuwfseagz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfhrijjsy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tian-w.cn/Article/details/gtnihcjosl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xylfe.cn/Article/details/gtntumsexa.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.havefunace.top/Article/details/gtwvsiohir.html

Go:   slices.Index(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtgxspvenu.html

Ruby: arr.index(x)
来源：http://dali.yangfankeji.com/Article/details/gtkkltpnhf.html

C#:   list.IndexOf(x);
来源：http://dali.ppjwa.cn/Article/details/gtaxuydjlh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.fzhhl.top/Article/details/gttopksfng.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.aizwys.cn/Article/details/gtrqamaklv.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sxryk.cn/Article/details/gtsyrshfau.html

JS:   arr.filter(x => x > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gthpnisluh.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jyoumei.cn/Article/details/gtbvoonbwf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinqigfzy.top/Article/details/gtawptrmyf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cdnleiting.top/Article/details/gttpoblopy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.0kj1m.cn/Article/details/gtnonthlgo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.daxiang520.top/Article/details/gtsnnfflgi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jqgfzy.top/Article/details/gtegvfmdwb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.daria6918.cn/Article/details/gtisfjilzp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.kuanghao11.cn/Article/details/gtfchfyxtg.html

JS:   arr.map(x => x * 2)
来源：http://dali.cdnleiting.top/Article/details/gtmlmjvzzt.html

TS:   arr.map(x => x * 2)
来源：http://dali.tianlin.xyz/Article/details/gttcxpybar.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yuxming.cn/Article/details/gtynpzeklp.html

Go:   // 手写循环
来源：http://dali.zhongyouzk.top/Article/details/gtibbbdwzc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shuidangran.top/Article/details/gtjcplxnwx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtrrzvtzqv.html

[D15] 去重
来源：http://dali.xinyue.icu/Article/details/gtsyfeydio.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ehwqpu.com/Article/details/gttjiniyog.html

PHP:  array_unique($arr);
来源：http://dali.ppjwa.cn/Article/details/gtqdrvwfvd.html

JS:   [...new Set(arr)]
来源：http://dali.wangdashe.top/Article/details/gtdimfrour.html

TS:   [...new Set(arr)]
来源：http://dali.feifeiyinyue.top/Article/details/gthgokqkkw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gtnqtijsmx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.guannengcc.top/Article/details/gtorlpqahw.html

Ruby: arr.uniq
来源：http://dali.sxryk.cn/Article/details/gtrvnwvoqd.html

C#:   list.Distinct().ToList()
来源：http://dali.havefunace.top/Article/details/gtflbghlwb.html

[D16] 求和与平均值
来源：http://dali.nwbrower.top/Article/details/gtoimbterw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttdnrnfrl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.snrcjt.cn/Article/details/gtlvlipzpn.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtgnuumpzf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ppjwa.cn/Article/details/gtwvsdhewh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cucudq.cn/Article/details/gtigczsppi.html

Go:   // 手写循环累加
来源：http://dali.cheryme.top/Article/details/gtafzzmqdg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhiwuduotai.top/Article/details/gtykxdirbg.html

C#:   list.Sum();  list.Average()
来源：http://dali.sufxvd.cn/Article/details/gtibxwepuy.html

[D17] 最大值与最小值
来源：http://dali.jinqigfzy.top/Article/details/gtcljirkpi.html

Py:   max(arr);  min(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtosexgwbd.html

PHP:  max($arr);  min($arr);
来源：http://dali.ppjwa.cn/Article/details/gtnmxhkqpd.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yuanzhike.top/Article/details/gtadjdjqdd.html

TS:   Math.max(...arr);
来源：http://dali.daxiang520.top/Article/details/gtklqanlue.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.tianlin.xyz/Article/details/gtxtabajeb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cucudq.cn/Article/details/gtbelvuebj.html

Ruby: arr.max;  arr.min
来源：http://dali.jianghu66.top/Article/details/gterocdakx.html

C#:   list.Max();  list.Min()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtamktksqz.html

[D18] 扁平化嵌套数组
来源：http://dali.haohaochexian.top/Article/details/gtzhfeqhlu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.chenlongwang.top/Article/details/gtrtqrxphw.html

PHP:  array_merge(...$nested);
来源：http://dali.jiagoushi.top/Article/details/gtckpocepu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.fengsongda.top/Article/details/gthdymamiq.html

TS:   nested.flat();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrbriauht.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.chenlongwang.top/Article/details/gtkwzndiue.html

Go:   // 手写双层循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtmlbppoza.html

Ruby: nested.flatten
来源：http://dali.jyoumei.cn/Article/details/gtrybeidrk.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cashguo.top/Article/details/gtizjlpcgn.html

[D19] 按字段分组
来源：http://dali.svipenyu.cn/Article/details/gtdtwlveae.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cdnleiting.top/Article/details/gtmvvkpwbi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.pycfn.com/Article/details/gtxgnqubxx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.birdmap.top/Article/details/gtnfrrbjsn.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gaohongyu789.top/Article/details/gtfhchbdvl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhengqikj.top/Article/details/gtbwifzrsf.html

Go:   // 手写 map[string][]T
来源：http://dali.shanyushiyangtech.top/Article/details/gtutdbfrbf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zdqjudy.top/Article/details/gtkgorppeg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.svipenyu.cn/Article/details/gtimooffpd.html

[D20] 统计每个元素出现次数
来源：http://dali.yuanzhike.top/Article/details/gtciypqgea.html

Py:   Counter(arr)
来源：http://dali.cheryme.top/Article/details/gtfcrvqegb.html

PHP:  array_count_values($arr);
来源：http://dali.cheryme.top/Article/details/gtcksoqnop.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.snrcjt.cn/Article/details/gtvwrbmpaz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hongshengwenyu.top/Article/details/gtjzaatcbw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jinghuilouyu.cn/Article/details/gtrxmakukv.html

Go:   // 手写 map[T]int
来源：http://dali.guannengcc.top/Article/details/gtmtwwjlop.html

Ruby: arr.tally
来源：http://dali.jianghu66.top/Article/details/gtxbbkgpus.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yuxming.cn/Article/details/gtiwviwtvg.html

[D21] 判断是否包含某元素
来源：http://dali.ybcxt.top/Article/details/gtaplpybbo.html

Py:   x in arr
来源：http://dali.jinqigfzy.top/Article/details/gtlnxtbhaf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jqgfzy.top/Article/details/gtfajzphkn.html

JS:   arr.includes(x)
来源：http://dali.yuxming.cn/Article/details/gtvawdjygl.html

TS:   arr.includes(x)
来源：http://dali.316326.xyz/Article/details/gtrghejfhq.html

Java: list.contains(x)
来源：http://dali.zhengqikj.top/Article/details/gtruysymje.html

Go:   slices.Contains(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtweyawlfv.html

Ruby: arr.include?(x)
来源：http://dali.pycfn.com/Article/details/gtvthkokao.html

C#:   list.Contains(x)
来源：http://dali.sweek.top/Article/details/gtjtqfoghp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.bjfxy.top/Article/details/gtbrjqawrd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.fengsongda.top/Article/details/gteadueikl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zdqjudy.top/Article/details/gtirdhigxm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.316326.xyz/Article/details/gtarnukpix.html

TS:   [...arr];
来源：http://dali.xuanzx.com/Article/details/gttgxsnozd.html

Java: new ArrayList<>(list);
来源：http://dali.ydzc1.top/Article/details/gtqxvmiwsy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhixingplan.top/Article/details/gtxfkietib.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xylfe.cn/Article/details/gthqcvghvj.html

C#:   new List<int>(list);
来源：http://dali.sxryk.cn/Article/details/gtvysnfrlg.html

[D23] reduce 累积计算
来源：http://dali.sweek.top/Article/details/gtqbqmkxzn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hammf.cn/Article/details/gtdaszayek.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.nanxinkj.top/Article/details/gtlkzyavyr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258.top/Article/details/gterdeftqz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.smart0.xyz/Article/details/gtjyipynmg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ehwqpu.com/Article/details/gtzbxambmp.html

Go:   // 手写循环
来源：http://dali.chenjidiqi.icu/Article/details/gtqbkgybyi.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jqgfzy.top/Article/details/gtmezcqhld.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gogol.net.cn/Article/details/gtabqtyjmc.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinghuilouyu.cn/Article/details/gtvkzmsgaq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yuanzhike.top/Article/details/gtpfpboujh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ybcxt.top/Article/details/gtmlumsqpr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtummffpwi.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gttnsfphds.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.vqdsnc.cn/Article/details/gtbwjxnezw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yongpay.top/Article/details/gtjpnadxcy.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.pengpengdd.cyou/Article/details/gtufcldkoh.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.tanke756.top/Article/details/gtzxdyfiqm.html

[D25] Set 集合去重与交并差
来源：http://dali.shangyingyoupin.top/Article/details/gthkusndtv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.quarkkingdee.top/Article/details/gtvjvflvql.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hywenlv.cn/Article/details/gtyzuamnxv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hammf.cn/Article/details/gtfbylzfzk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xylfe.cn/Article/details/gtorypoghd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yj20258888.top/Article/details/gthyvmkffz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzbssnirf.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zycfv.cn/Article/details/gtoeqanwju.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.guowangkeji.top/Article/details/gtjrxvqkgg.html

[D26] 数组转字符串
来源：http://dali.yj20258888.top/Article/details/gtvezmefkr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj20258888.top/Article/details/gtbgimlzxf.html

PHP:  implode(", ", $arr);
来源：http://dali.gzhubu.top/Article/details/gturlxgcoh.html

JS:   arr.join(", ")
来源：http://dali.sxryk.cn/Article/details/gtelorkkvk.html

TS:   arr.join(", ")
来源：http://dali.316326.xyz/Article/details/gthgsrazeh.html

Java: String.join(", ", list)
来源：http://dali.yongpay.top/Article/details/gtkqrqneho.html

Go:   strings.Join(strs, ", ")
来源：http://dali.snrcjt.cn/Article/details/gtptzysfwp.html

Ruby: arr.join(", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gtslveorcc.html

C#:   string.Join(", ", list)
来源：http://dali.zhiwuduotai.top/Article/details/gtbrjduiuf.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtjvdvhwjy.html

E. 字符串处理
来源：http://dali.nanxinkj.top/Article/details/gtaqsvpvrj.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtxyzdtuda.html

[E01] 拼接字符串
来源：http://dali.daxiang520.top/Article/details/gtvresamyf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gogol.net.cn/Article/details/gtknytlsgp.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.chenjidiqi.icu/Article/details/gtcwfotmrc.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ybcxt.top/Article/details/gtpmiqbrci.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.c1oappe.top/Article/details/gtkdeqecub.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.andypj.xyz/Article/details/gtewhhsxpv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqnxwcbpm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.dashuyun.cn/Article/details/gtebgifuab.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cheryme.top/Article/details/gtjijtonmq.html

[E02] 重复字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtqaodewyi.html

Py:   "ab" * 3
来源：http://dali.jinghuilouyu.cn/Article/details/gtzapgawgw.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jlsjyb.cn/Article/details/gtvzjkagud.html

JS:   "ab".repeat(3)
来源：http://dali.xylfe.cn/Article/details/gtxqafkwni.html

TS:   "ab".repeat(3)
来源：http://dali.kuanghao11.cn/Article/details/gtumedxwna.html

Java: "ab".repeat(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaggylzfr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sxryk.cn/Article/details/gtjddpxijh.html

Ruby: "ab" * 3
来源：http://dali.jlsjyb.cn/Article/details/gtxrthcerj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hywenlv.cn/Article/details/gtwnctmjxr.html

[E03] 截取子串
来源：http://dali.havefunace.top/Article/details/gtdzfvoffn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hongshengwenyu.top/Article/details/gtbracnttr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gtriwcklwq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.316326.xyz/Article/details/gturxviohk.html

TS:   s.slice(1, 4)
来源：http://dali.zhoulong.xyz/Article/details/gtshldzyot.html

Java: s.substring(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gtykczjbmi.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsjxxfwrs.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shangyingyoupin.top/Article/details/gtoorxdonj.html

C#:   s.Substring(1, 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtdkjsalri.html

[E04] 查找子串位置
来源：http://dali.birdmap.top/Article/details/gtyvmchndx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.pengpengdd.cyou/Article/details/gtlspstmkx.html

PHP:  strpos($s, "x");
来源：http://dali.chenjidiqi.icu/Article/details/gtwwikvgyh.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttaaamwfx.html

TS:   s.indexOf("x")
来源：http://dali.jyoumei.cn/Article/details/gtcagfgbwa.html

Java: s.indexOf("x")
来源：http://dali.pengpengdd.cyou/Article/details/gteystowka.html

Go:   strings.Index(s, "x")
来源：http://dali.yangfankeji.com/Article/details/gteowpaubx.html

Ruby: s.index("x")
来源：http://dali.jianghu66.top/Article/details/gtaahldjiu.html

C#:   s.IndexOf("x")
来源：http://dali.yj20258.top/Article/details/gtudcospne.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sysykeji.top/Article/details/gtcrtdouau.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gtuhlrowlv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbtlquxtl.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtjbscqieu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.meibo888.top/Article/details/gtttwpzlfj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jianghu66.top/Article/details/gtqaatfkmq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.wangdashe.top/Article/details/gtvjnccffp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jianghu66.top/Article/details/gtaygljdoj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hysaishi.cn/Article/details/gtheyojxva.html

[E06] 替换子串
来源：http://dali.chenzaomai.com/Article/details/gtluzivymb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xziqi.cn/Article/details/gthodhpzps.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cashguo.top/Article/details/gteteqwbbo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtkbhrwszt.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gtlymacdah.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtinmfrqgp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shuidangran.top/Article/details/gtneofmlqm.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmcmoqnmg.html

C#:   s.Replace("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtroqrvxtz.html

[E07] 按分隔符拆分
来源：http://dali.yongpay.top/Article/details/gtudyrepxo.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsjsmrkzz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.redwolf501.top/Article/details/gtvlriwrwv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.tanke756.top/Article/details/gtslezussn.html

TS:   s.split(",")
来源：http://dali.quarkkingdee.top/Article/details/gtmcbizwyd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yongpay.top/Article/details/gtnzxpkskh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.pycfn.com/Article/details/gttmmvsmtp.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gtqespnpjn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cheryme.top/Article/details/gtaybfvkbj.html

[E08] 数组按分隔符合并
来源：http://dali.fzhhl.top/Article/details/gtpgbryykr.html

Py:   ",".join(items)
来源：http://dali.bjfxy.top/Article/details/gtfwycuzsa.html

PHP:  implode(",", $items);
来源：http://dali.c1oappe.top/Article/details/gtxuyeaxuq.html

JS:   items.join(",")
来源：http://dali.hongshengwenyu.top/Article/details/gtqafegaka.html

TS:   items.join(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtsbaecvty.html

Java: String.join(",", items)
来源：http://dali.nanxuanxn.top/Article/details/gtxwvzwoeb.html

Go:   strings.Join(items, ",")
来源：http://dali.yongpay.top/Article/details/gtbldtnvur.html

Ruby: items.join(",")
来源：http://dali.ehwqpu.com/Article/details/gtvcufqova.html

C#:   string.Join(",", items)
来源：http://dali.mhx1999.top/Article/details/gtyttsadyb.html

[E09] 去除所有空白字符
来源：http://dali.yanxiufei.cn/Article/details/gtgiyrcmqy.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.meibo888.top/Article/details/gtwlfkanpy.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.9152youxi.cn/Article/details/gtoavdpynd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.316326.xyz/Article/details/gtwceusnub.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhengqikj.top/Article/details/gtezdgivzk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jlsjyb.cn/Article/details/gtetvoydfa.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xuetiantiany.cn/Article/details/gtubzuideu.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jiagoushi.top/Article/details/gtnickvrpz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yueranfly.top/Article/details/gticuagjoq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj202588.top/Article/details/gtpmuoxnxv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gtzflvgjmi.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ivvv.top/Article/details/gtddgqgpld.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gtyvizbnmu.html

TS:   "7".padStart(3, "0")
来源：http://dali.aizwys.cn/Article/details/gtrlcolzsm.html

Java: String.format("%03d", 7)
来源：http://dali.jlsjyb.cn/Article/details/gtzmygsgje.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gtdqlgglvs.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gtjsdsmceb.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yuxming.cn/Article/details/gtomolmnwm.html

[E11] 反转字符串
来源：http://dali.havefunace.top/Article/details/gtivdswsuy.html

Py:   s[::-1]
来源：http://dali.yonumen.top/Article/details/gtxodiermp.html

PHP:  strrev($s);
来源：http://dali.zhongyouzk.top/Article/details/gtgmmrefqf.html

JS:   [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gtvcgrwwmg.html

TS:   [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gthydlsmqn.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.mhx1999.top/Article/details/gtxxqvlorq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.bjfxy.top/Article/details/gtncwlvxrx.html

Ruby: s.reverse
来源：http://dali.chenlongwang.top/Article/details/gtmrgexnro.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcoymkwkg.html

[E12] 统计某字符出现次数
来源：http://dali.hfpthk.cn/Article/details/gtohaiigym.html

Py:   s.count("a")
来源：http://dali.hfpthk.cn/Article/details/gttqgmhgxn.html

PHP:  substr_count($s, "a");
来源：http://dali.jianghu66.top/Article/details/gtoclgvxbs.html

JS:   s.split("a").length - 1
来源：http://dali.andypj.xyz/Article/details/gtlxnffslf.html

TS:   s.split("a").length - 1
来源：http://dali.andypj.xyz/Article/details/gthbkvmofk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.iojbl.cn/Article/details/gtxnfjovif.html

Go:   strings.Count(s, "a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjygyrxhg.html

Ruby: s.count("a")
来源：http://dali.ybcxt.top/Article/details/gttbvlzcje.html

C#:   s.Count(c => c == 'a')
来源：http://dali.guowangkeji.top/Article/details/gtnruqbzuf.html

[E13] 逐字符遍历
来源：http://dali.mhx1999.top/Article/details/gtwbpzcqky.html

Py:   for ch in s: print(ch)
来源：http://dali.aibaodan.cn/Article/details/gtwvqsyxdn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrauoniom.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.svipenyu.cn/Article/details/gttbecjazp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gthtsthpnb.html


<!-- 参考信息 -->