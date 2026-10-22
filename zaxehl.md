代发 wailian999

Py:   len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttirqzwqd.html

PHP:  count($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gthvjyegql.html

JS:   arr.length
来源：http://dali.9152youxi.cn/Article/details/gtknbjgrha.html

TS:   arr.length
来源：http://dali.pycfn.com/Article/details/gtszvvjjwu.html

Java: list.size();
来源：http://dali.haohaochexian.top/Article/details/gtdmbnrctc.html

Go:   len(arr)
来源：http://dali.cheryme.top/Article/details/gttzygvqnv.html

Ruby: arr.length; arr.size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvsowfshy.html

C#:   list.Count;
来源：http://dali.sufxvd.cn/Article/details/gtakgombgy.html

[D07] 切片 / 取子数组
来源：http://dali.hywenlv.cn/Article/details/gtsrxexcea.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.pycfn.com/Article/details/gthtbthfbl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.havefunace.top/Article/details/gtqzywxdpi.html

JS:   arr.slice(1, 4);
来源：http://dali.daria6918.cn/Article/details/gtksmueyhb.html

TS:   arr.slice(1, 4);
来源：http://dali.cheryme.top/Article/details/gtyxcdczvs.html

Java: list.subList(1, 4);
来源：http://dali.dashuyun.cn/Article/details/gtzydrqsnt.html

Go:   arr[1:4]
来源：http://dali.hammf.cn/Article/details/gtdcudevof.html

Ruby: arr[1, 3]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxjnaexpp.html

C#:   list.GetRange(1, 3);
来源：http://dali.wangdashe.top/Article/details/gtswdkxbjn.html

[D08] 合并两个数组
来源：http://dali.hfpthk.cn/Article/details/gtfymkgern.html

Py:   a + b;  a.extend(b)
来源：http://dali.snrcjt.cn/Article/details/gtrighravu.html

PHP:  array_merge($a, $b);
来源：http://dali.jqgfzy.top/Article/details/gtyjdhmkws.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cheryme.top/Article/details/gtiaxndyqy.html

TS:   [...a, ...b];
来源：http://dali.mhx1999.top/Article/details/gtkricsnut.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hysaishi.cn/Article/details/gtcjdyajgq.html

Go:   append(a, b...)
来源：http://dali.chenzaomai.com/Article/details/gtmibxtfri.html

Ruby: a + b;  a.concat(b)
来源：http://dali.nwbrower.top/Article/details/gtdwnzzuyw.html

C#:   a.Concat(b).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtydcwwwrw.html

[D09] 排序（升序）
来源：http://dali.ehwqpu.com/Article/details/gtylmmjczt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pengpengdd.cyou/Article/details/gtcxnfljom.html

PHP:  sort($arr);
来源：http://dali.meibo888.top/Article/details/gtinwuyrpa.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.haohaochexian.top/Article/details/gtcxipeioy.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xinyue.icu/Article/details/gtjnxechhh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.meibo888.top/Article/details/gtygndwfpt.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cdnleiting.top/Article/details/gtyfpvmmei.html

Ruby: arr.sort
来源：http://dali.guannengcc.top/Article/details/gtvsjrpvzp.html

C#:   list.Sort();
来源：http://dali.ehwqpu.com/Article/details/gtvcrvgopy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yongpay.top/Article/details/gtvjdjsstc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jyoumei.cn/Article/details/gtfuibienm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hnxiangtu.top/Article/details/gtdqiskcef.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xinyue.icu/Article/details/gtqcmwgvjk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cashguo.top/Article/details/gtxewdlyds.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.dianchejie.cn/Article/details/gtpgfvzbrj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhixingplan.top/Article/details/gtyrepmaal.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jiagoushi.top/Article/details/gtwfcpejfb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.redwolf501.top/Article/details/gtvocmphlg.html

[D11] 反转数组
来源：http://dali.wangshuangyany.cn/Article/details/gtskczwdev.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.wangdashe.top/Article/details/gtijqrayos.html

PHP:  array_reverse($arr);
来源：http://dali.ybcxt.top/Article/details/gtqiwgkbac.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cashguo.top/Article/details/gtijzldhba.html

TS:   [...arr].reverse();
来源：http://dali.zycfv.cn/Article/details/gtnshkwlbb.html

Java: Collections.reverse(list);
来源：http://dali.pycfn.com/Article/details/gtvgeuoqyj.html

Go:   slices.Reverse(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtbwfgswuv.html

Ruby: arr.reverse
来源：http://dali.mhx1999.top/Article/details/gtjrjaadnp.html

C#:   list.Reverse();
来源：http://dali.tianlin.xyz/Article/details/gtlgqrhast.html

[D12] 查找元素下标
来源：http://dali.ybcxt.top/Article/details/gthzwsvnld.html

Py:   arr.index(x);  x in arr
来源：http://dali.hysaishi.cn/Article/details/gtfdmannkh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cheryme.top/Article/details/gtbfsybpec.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gtconvxdne.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.9152youxi.cn/Article/details/gtvezbpwxo.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shzxlz.cn/Article/details/gtyupmjwlj.html

Go:   slices.Index(arr, x)
来源：http://dali.cucudq.cn/Article/details/gttqqwkjru.html

Ruby: arr.index(x)
来源：http://dali.daxiang520.top/Article/details/gtgejyvrnd.html

C#:   list.IndexOf(x);
来源：http://dali.tianlin.xyz/Article/details/gtxfpfozkt.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xinyue.icu/Article/details/gtdekgrrpa.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenzaomai.com/Article/details/gtdmpdogdm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.9152youxi.cn/Article/details/gtrduxruhx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.svipenyu.cn/Article/details/gtmvimulrl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gzhubu.top/Article/details/gtwjkwinbp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nanxinkj.top/Article/details/gtlkzseucy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.daxiang520.top/Article/details/gtjhsetvja.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hnqzz.top/Article/details/gtvzzvbqal.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtydkypvwd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shuidangran.top/Article/details/gtnsrazvtf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.tianlin.xyz/Article/details/gtcnjejyuu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yuxming.cn/Article/details/gtfqxtjgsq.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgioqbqez.html

TS:   arr.map(x => x * 2)
来源：http://dali.xuanzx.com/Article/details/gttjpogtlc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.meibo888.top/Article/details/gteupqmijk.html

Go:   // 手写循环
来源：http://dali.andypj.xyz/Article/details/gtnlyxdiui.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xinyue.icu/Article/details/gtyftoujvd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.birdmap.top/Article/details/gtoluzepph.html

[D15] 去重
来源：http://dali.sxryk.cn/Article/details/gtgrcpvypo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ppjwa.cn/Article/details/gtoqvbsjyj.html

PHP:  array_unique($arr);
来源：http://dali.yongpay.top/Article/details/gtanechgwb.html

JS:   [...new Set(arr)]
来源：http://dali.jlsjyb.cn/Article/details/gtdxbzqona.html

TS:   [...new Set(arr)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtutraoweg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yonumen.top/Article/details/gtvoqdbces.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.daria6918.cn/Article/details/gtgdljwvas.html

Ruby: arr.uniq
来源：http://dali.jianghu66.top/Article/details/gtgrzsdigl.html

C#:   list.Distinct().ToList()
来源：http://dali.guannengcc.top/Article/details/gtnwkxsask.html

[D16] 求和与平均值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwgfimncx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yanxiufei.cn/Article/details/gttnrotfwc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhengqikj.top/Article/details/gtiglmsecc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daria6918.cn/Article/details/gtndomhxoa.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.havefunace.top/Article/details/gtjagjqzrv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.iojbl.cn/Article/details/gtlknjjilb.html

Go:   // 手写循环累加
来源：http://dali.pycfn.com/Article/details/gtzeycgbgt.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.chenjidiqi.icu/Article/details/gtvioqbkza.html

C#:   list.Sum();  list.Average()
来源：http://dali.cheryme.top/Article/details/gtzlrffqbu.html

[D17] 最大值与最小值
来源：http://dali.yj20258888.top/Article/details/gthacbxsre.html

Py:   max(arr);  min(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtbmjlsegq.html

PHP:  max($arr);  min($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtdqcuyytq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpicqmhnw.html

TS:   Math.max(...arr);
来源：http://dali.dianchejie.cn/Article/details/gtoklyninj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhongyouzk.top/Article/details/gtaulcwwqb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtqzlhyity.html

Ruby: arr.max;  arr.min
来源：http://dali.shanyushiyangtech.top/Article/details/gtzjmvypbs.html

C#:   list.Max();  list.Min()
来源：http://dali.smart0.xyz/Article/details/gtnbayxahv.html

[D18] 扁平化嵌套数组
来源：http://dali.shuidangran.top/Article/details/gtolemhbbz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.nanxinkj.top/Article/details/gtnnvtjinq.html

PHP:  array_merge(...$nested);
来源：http://dali.yj202588.top/Article/details/gtmgiztsio.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ehwqpu.com/Article/details/gtxxgyvbny.html

TS:   nested.flat();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbnwtlklc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.dianchejie.cn/Article/details/gtpxqkrjrz.html

Go:   // 手写双层循环
来源：http://dali.ybcxt.top/Article/details/gtwxhjctkx.html

Ruby: nested.flatten
来源：http://dali.c1oappe.top/Article/details/gtlezscikf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtheswvhgm.html

[D19] 按字段分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtenfbnhpn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.guowangkeji.top/Article/details/gttflcswvq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.fzhhl.top/Article/details/gtlxzkaqts.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.wangdashe.top/Article/details/gtawhlfpwg.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinqigfzy.top/Article/details/gtqrramobb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.haohaochexian.top/Article/details/gtibhjmnkz.html

Go:   // 手写 map[string][]T
来源：http://dali.redwolf501.top/Article/details/gtkwuqbskh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.meibo888.top/Article/details/gtralwdeef.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jyoumei.cn/Article/details/gtrmzvvyty.html

[D20] 统计每个元素出现次数
来源：http://dali.gotoacloud.top/Article/details/gtcpkutntj.html

Py:   Counter(arr)
来源：http://dali.yongpay.top/Article/details/gtkwycaesi.html

PHP:  array_count_values($arr);
来源：http://dali.smart0.xyz/Article/details/gtziumrmep.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zycfv.cn/Article/details/gtuevxxztx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jiagoushi.top/Article/details/gtczsklwqg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.316326.xyz/Article/details/gtnttndjcy.html

Go:   // 手写 map[T]int
来源：http://dali.xylfe.cn/Article/details/gtlkqlbfdz.html

Ruby: arr.tally
来源：http://dali.yuanzhike.top/Article/details/gtoxuceyzv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hywenlv.cn/Article/details/gtvuuvgpod.html

[D21] 判断是否包含某元素
来源：http://dali.shuidangran.top/Article/details/gtkukqrvoy.html

Py:   x in arr
来源：http://dali.hnxiangtu.top/Article/details/gtrpqlflxj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.smart0.xyz/Article/details/gtgsvcefcm.html

JS:   arr.includes(x)
来源：http://dali.316326.xyz/Article/details/gthdcffwhw.html

TS:   arr.includes(x)
来源：http://dali.zhixingplan.top/Article/details/gtmzlnnctk.html

Java: list.contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtffqeeqio.html

Go:   slices.Contains(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gthqujamyl.html

Ruby: arr.include?(x)
来源：http://dali.chenlongwang.top/Article/details/gtzvvklbix.html

C#:   list.Contains(x)
来源：http://dali.sxryk.cn/Article/details/gtitpmmdsr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.feifeiyinyue.top/Article/details/gtysxiyzec.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yvedp.cn/Article/details/gteqolfobt.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sysykeji.top/Article/details/gtscfhpcbq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtoudkklho.html

TS:   [...arr];
来源：http://dali.xziqi.cn/Article/details/gtkfrnljlq.html

Java: new ArrayList<>(list);
来源：http://dali.hywenlv.cn/Article/details/gtngoducbz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.aibaodan.cn/Article/details/gtntizmgch.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hammf.cn/Article/details/gthlmqdwrv.html

C#:   new List<int>(list);
来源：http://dali.meibo888.top/Article/details/gtfsyvvyrw.html

[D23] reduce 累积计算
来源：http://dali.iojbl.cn/Article/details/gtabpygvup.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.gogol.net.cn/Article/details/gtigvgeuug.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xylfe.cn/Article/details/gthqbdtoqr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.andypj.xyz/Article/details/gtrflnobqe.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtymzmuekn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yj202588.top/Article/details/gtsajubtbk.html

Go:   // 手写循环
来源：http://dali.tianlin.xyz/Article/details/gtwrrvejcz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.feifeiyinyue.top/Article/details/gtbiuolani.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jianghu66.top/Article/details/gtnupciyav.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlihrxaca.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jyoumei.cn/Article/details/gtwwunlbqs.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.birdmap.top/Article/details/gtroujfltb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ppjwa.cn/Article/details/gtoljufywc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtvfnetbsw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.wangdashe.top/Article/details/gtfjeoswcs.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.haohaochexian.top/Article/details/gtbkizyuwv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gzhubu.top/Article/details/gtxwwriyuo.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.tianlin.xyz/Article/details/gtqutoeyfc.html

[D25] Set 集合去重与交并差
来源：http://dali.ivvv.top/Article/details/gtxphkaqlv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yj202588.top/Article/details/gtsttdkmfb.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.0kj1m.cn/Article/details/gtqzelorgf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtqxylcyhv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtswqjgneg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zdqjudy.top/Article/details/gtuqaplrkb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cucudq.cn/Article/details/gtucwxszvk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cdnleiting.top/Article/details/gtewhykyob.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.nanxinkj.top/Article/details/gtqzgvzqtm.html

[D26] 数组转字符串
来源：http://dali.yuanzhike.top/Article/details/gtaowknecj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhiwuduotai.top/Article/details/gttzxrxegr.html

PHP:  implode(", ", $arr);
来源：http://dali.ydzc1.top/Article/details/gtnrjghgqq.html

JS:   arr.join(", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttgpawlns.html

TS:   arr.join(", ")
来源：http://dali.9152youxi.cn/Article/details/gtbgkztdxm.html

Java: String.join(", ", list)
来源：http://dali.feifeiyinyue.top/Article/details/gtnztobzwl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.bjfxy.top/Article/details/gtxqgcrmvs.html

Ruby: arr.join(", ")
来源：http://dali.vqdsnc.cn/Article/details/gtixwewqwj.html

C#:   string.Join(", ", list)
来源：http://dali.zhengqikj.top/Article/details/gtqnyluwhz.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtogcbzpzu.html

E. 字符串处理
来源：http://dali.tian-w.cn/Article/details/gtepkapsgz.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtggajvccl.html

[E01] 拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gtodnyqqws.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.andypj.xyz/Article/details/gtirjwaovj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhoulong.xyz/Article/details/gtxvegkvel.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtspynxqay.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.iojbl.cn/Article/details/gtbelpxoog.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.nwbrower.top/Article/details/gttrzyuyzg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenzaomai.com/Article/details/gtlvmpadle.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.mhx1999.top/Article/details/gtpfvtkeyw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtgjhzynrc.html

[E02] 重复字符串
来源：http://dali.yuxming.cn/Article/details/gthdzrbxdd.html

Py:   "ab" * 3
来源：http://dali.dianchejie.cn/Article/details/gtygkwxwek.html

PHP:  str_repeat("ab", 3);
来源：http://dali.smart0.xyz/Article/details/gtqcssxuqt.html

JS:   "ab".repeat(3)
来源：http://dali.sweek.top/Article/details/gtfujsegfk.html

TS:   "ab".repeat(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqukzkhjr.html

Java: "ab".repeat(3)
来源：http://dali.bjfxy.top/Article/details/gtyhprtolo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.nwbrower.top/Article/details/gtrdkejhnp.html

Ruby: "ab" * 3
来源：http://dali.nanxuanxn.top/Article/details/gtnylnxiyr.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.daria6918.cn/Article/details/gtebseynfz.html

[E03] 截取子串
来源：http://dali.c1oappe.top/Article/details/gtwgxdzspf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jiagoushi.top/Article/details/gtwvdbltgr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwxzpbcri.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hammf.cn/Article/details/gtddslulno.html

TS:   s.slice(1, 4)
来源：http://dali.nanxuanxn.top/Article/details/gtfsiuwjyq.html

Java: s.substring(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gtftyjbgqe.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.nwbrower.top/Article/details/gtrqbzcceq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ybcxt.top/Article/details/gtcdvnrtpv.html

C#:   s.Substring(1, 3)
来源：http://dali.yuxming.cn/Article/details/gtydpvslam.html

[E04] 查找子串位置
来源：http://dali.yangfankeji.com/Article/details/gthgxibrss.html

Py:   s.find("x");  s.index("x")
来源：http://dali.quarkkingdee.top/Article/details/gteussbrrq.html

PHP:  strpos($s, "x");
来源：http://dali.yanxiufei.cn/Article/details/gtaordolof.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.9152youxi.cn/Article/details/gtqagmwujv.html

TS:   s.indexOf("x")
来源：http://dali.dianchejie.cn/Article/details/gtoscrwjos.html

Java: s.indexOf("x")
来源：http://dali.cheryme.top/Article/details/gtatnjpdfq.html

Go:   strings.Index(s, "x")
来源：http://dali.ehwqpu.com/Article/details/gtboonijll.html

Ruby: s.index("x")
来源：http://dali.birdmap.top/Article/details/gtuopdtrtw.html

C#:   s.IndexOf("x")
来源：http://dali.svipenyu.cn/Article/details/gtvszizaao.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.snrcjt.cn/Article/details/gtblilragy.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhoulong.xyz/Article/details/gtgnrrogrg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.iojbl.cn/Article/details/gtxahjwjir.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgfzy.top/Article/details/gtlyhqwysr.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yangfankeji.com/Article/details/gtbmkanpkk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.316326.xyz/Article/details/gtoqfakrzy.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.fzhhl.top/Article/details/gtpurwwtke.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xziqi.cn/Article/details/gtjszevris.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmllkkhkr.html

[E06] 替换子串
来源：http://dali.yj20258888.top/Article/details/gtgqwrcusn.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gaohongyu789.top/Article/details/gtoidfglln.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.andypj.xyz/Article/details/gtdtcsidpi.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtcjuffmin.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtjksnkuzh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtdwwvudey.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ydzc1.top/Article/details/gtpugvuuse.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtquctprko.html

C#:   s.Replace("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtignnvwxb.html

[E07] 按分隔符拆分
来源：http://dali.yuxming.cn/Article/details/gtjsmgypxc.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ppjwa.cn/Article/details/gtaljwjnso.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.havefunace.top/Article/details/gtpxldspcf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.redwolf501.top/Article/details/gttitdngbb.html

TS:   s.split(",")
来源：http://dali.gzhubu.top/Article/details/gtsxryblro.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.iojbl.cn/Article/details/gteqyiqqxi.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yj20258888.top/Article/details/gtzhmyryuc.html

Ruby: s.split(",");  s.split
来源：http://dali.xuetiantiany.cn/Article/details/gtypiuedru.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shuidangran.top/Article/details/gtqfftkuju.html

[E08] 数组按分隔符合并
来源：http://dali.hongshengwenyu.top/Article/details/gtpnvehgyf.html

Py:   ",".join(items)
来源：http://dali.guowangkeji.top/Article/details/gtfmvhjeai.html

PHP:  implode(",", $items);
来源：http://dali.zdqjudy.top/Article/details/gtcxgpmtbi.html

JS:   items.join(",")
来源：http://dali.shangyingyoupin.top/Article/details/gthzrnqpra.html

TS:   items.join(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzijgahth.html

Java: String.join(",", items)
来源：http://dali.ybcxt.top/Article/details/gtqctbknal.html

Go:   strings.Join(items, ",")
来源：http://dali.xziqi.cn/Article/details/gtzjselvdm.html

Ruby: items.join(",")
来源：http://dali.316326.xyz/Article/details/gtkwakkmja.html

C#:   string.Join(",", items)
来源：http://dali.zhiwuduotai.top/Article/details/gtonjdixyk.html

[E09] 去除所有空白字符
来源：http://dali.zhixingplan.top/Article/details/gtxdpsbzll.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yanxiufei.cn/Article/details/gtucwvqlav.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gzhubu.top/Article/details/gtxgibclfx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cashguo.top/Article/details/gtqafhvphg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xziqi.cn/Article/details/gttrpgdonl.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtibdghlfe.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhengqikj.top/Article/details/gtfsbiwwlu.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.nanxinkj.top/Article/details/gtwouumavw.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.dianchejie.cn/Article/details/gtutfadnld.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gtoygqhasa.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gtjyydfhdr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.daria6918.cn/Article/details/gtbvnvkvoi.html

JS:   "7".padStart(3, "0")
来源：http://dali.xinyue.icu/Article/details/gtydjxwuzg.html

TS:   "7".padStart(3, "0")
来源：http://dali.iojbl.cn/Article/details/gtakvihuab.html

Java: String.format("%03d", 7)
来源：http://dali.aizwys.cn/Article/details/gtstqhhyki.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.smart0.xyz/Article/details/gtfthaanqb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gtilkarfwu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinghuilouyu.cn/Article/details/gtqxtgksuj.html

[E11] 反转字符串
来源：http://dali.haohaochexian.top/Article/details/gtptpxjbre.html

Py:   s[::-1]
来源：http://dali.c1oappe.top/Article/details/gtaufrmumn.html

PHP:  strrev($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwltqslz.html

JS:   [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcssstqej.html

TS:   [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gtffrkzegp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyxjyrkfx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.quarkkingdee.top/Article/details/gtfxmlemyh.html

Ruby: s.reverse
来源：http://dali.dashuyun.cn/Article/details/gtjqftlyzy.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hywenlv.cn/Article/details/gtqluxazpt.html

[E12] 统计某字符出现次数
来源：http://dali.quarkkingdee.top/Article/details/gtrpqqhmbw.html

Py:   s.count("a")
来源：http://dali.birdmap.top/Article/details/gtqipxmizk.html

PHP:  substr_count($s, "a");
来源：http://dali.c1oappe.top/Article/details/gtsfwsaavg.html

JS:   s.split("a").length - 1
来源：http://dali.gzhubu.top/Article/details/gtptynuiym.html

TS:   s.split("a").length - 1
来源：http://dali.zhengqikj.top/Article/details/gtkdisewkt.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hongshengwenyu.top/Article/details/gtlyevdmfw.html

Go:   strings.Count(s, "a")
来源：http://dali.snrcjt.cn/Article/details/gtlhymobso.html

Ruby: s.count("a")
来源：http://dali.yongpay.top/Article/details/gtiyzymgly.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shangyingyoupin.top/Article/details/gtjgjrresd.html

[E13] 逐字符遍历
来源：http://dali.bjfxy.top/Article/details/gtwusvnwea.html


<!-- 参考信息 -->