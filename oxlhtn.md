代发 wailian999

[D07] 切片 / 取子数组
来源：http://dali.guannengcc.top/Article/details/gtvimzotsp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.9152youxi.cn/Article/details/gtlgqclkho.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.smart0.xyz/Article/details/gtecnpbbjx.html

JS:   arr.slice(1, 4);
来源：http://dali.nwbrower.top/Article/details/gtxegwajxy.html

TS:   arr.slice(1, 4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtstdqvojw.html

Java: list.subList(1, 4);
来源：http://dali.yuxming.cn/Article/details/gtkpwtqarh.html

Go:   arr[1:4]
来源：http://dali.hysaishi.cn/Article/details/gtiurdpwev.html

Ruby: arr[1, 3]
来源：http://dali.gogol.net.cn/Article/details/gtqtvpcicu.html

C#:   list.GetRange(1, 3);
来源：http://dali.yuxming.cn/Article/details/gtrwtrgvpn.html

[D08] 合并两个数组
来源：http://dali.hnxiangtu.top/Article/details/gtobtnsjki.html

Py:   a + b;  a.extend(b)
来源：http://dali.quarkkingdee.top/Article/details/gtfzbggafe.html

PHP:  array_merge($a, $b);
来源：http://dali.yuxming.cn/Article/details/gtgybarnbo.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jianghu66.top/Article/details/gtgugzjsam.html

TS:   [...a, ...b];
来源：http://dali.havefunace.top/Article/details/gtwblpsymt.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.dianchejie.cn/Article/details/gtoylzvuxc.html

Go:   append(a, b...)
来源：http://dali.jinqigfzy.top/Article/details/gtnqifenbv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.chenlongwang.top/Article/details/gtejvagahw.html

C#:   a.Concat(b).ToList()
来源：http://dali.yvedp.cn/Article/details/gteyzulptk.html

[D09] 排序（升序）
来源：http://dali.gzhubu.top/Article/details/gtngqoines.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.iojbl.cn/Article/details/gtrgwvjopr.html

PHP:  sort($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtoonluzcv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenjidiqi.icu/Article/details/gtxjzltpyi.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhiwuduotai.top/Article/details/gtlnhxessw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.0kj1m.cn/Article/details/gtmgokkvnv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.guowangkeji.top/Article/details/gtckublura.html

Ruby: arr.sort
来源：http://dali.daria6918.cn/Article/details/gtfqcjwefn.html

C#:   list.Sort();
来源：http://dali.ehwqpu.com/Article/details/gtinqhqzxh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.daxiang520.top/Article/details/gtypasandl.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.havefunace.top/Article/details/gtiyrgqpak.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.haohaochexian.top/Article/details/gtbxbcscag.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tanke756.top/Article/details/gtbahdenon.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gzhubu.top/Article/details/gtwsviiwem.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cucudq.cn/Article/details/gtqmiffebr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sxryk.cn/Article/details/gtnjlajhkk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gzhubu.top/Article/details/gtdnvfylgg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gtpgclrfli.html

[D11] 反转数组
来源：http://dali.bjfxy.top/Article/details/gtmukwwqeb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sysykeji.top/Article/details/gtwelncegi.html

PHP:  array_reverse($arr);
来源：http://dali.smart0.xyz/Article/details/gteecatode.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinqigfzy.top/Article/details/gtawslamjd.html

TS:   [...arr].reverse();
来源：http://dali.gzhubu.top/Article/details/gtpqciispr.html

Java: Collections.reverse(list);
来源：http://dali.quarkkingdee.top/Article/details/gtihcpfgbc.html

Go:   slices.Reverse(arr)
来源：http://dali.sysykeji.top/Article/details/gtcstlzubf.html

Ruby: arr.reverse
来源：http://dali.0kj1m.cn/Article/details/gtwoatinha.html

C#:   list.Reverse();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtowvjlkxd.html

[D12] 查找元素下标
来源：http://dali.ydzc1.top/Article/details/gthzcdjons.html

Py:   arr.index(x);  x in arr
来源：http://dali.pycfn.com/Article/details/gtqjnxekze.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yj202588.top/Article/details/gtgwsmbioy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xziqi.cn/Article/details/gtivyiucce.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.haohaochexian.top/Article/details/gtzcoirddb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yuxming.cn/Article/details/gtxadktllz.html

Go:   slices.Index(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtsmhyxevd.html

Ruby: arr.index(x)
来源：http://dali.yuxming.cn/Article/details/gtwbfpknfd.html

C#:   list.IndexOf(x);
来源：http://dali.jiagoushi.top/Article/details/gtxkvmhffs.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shangyingyoupin.top/Article/details/gtwlpyrmdn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.9152youxi.cn/Article/details/gtxjmfxvau.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yuxming.cn/Article/details/gtywwpgxtl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.chenlongwang.top/Article/details/gtnpltwelc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cucudq.cn/Article/details/gtgzsvqoub.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.kuanghao11.cn/Article/details/gtokpklqeq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsdzvbwpi.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jqgufenzy.top/Article/details/gtfnteekuc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtkfpyjxkh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xuanzx.com/Article/details/gtklcwpwxg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.guowangkeji.top/Article/details/gtgleeehwm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yuxming.cn/Article/details/gtijymrjqq.html

JS:   arr.map(x => x * 2)
来源：http://dali.guowangkeji.top/Article/details/gtqjtedmtx.html

TS:   arr.map(x => x * 2)
来源：http://dali.hnxiangtu.top/Article/details/gttzflcfqx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jqgfzy.top/Article/details/gtontzfqwr.html

Go:   // 手写循环
来源：http://dali.316326.xyz/Article/details/gtwlcyoghl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jiagoushi.top/Article/details/gtzphzzgwr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoyhsxabr.html

[D15] 去重
来源：http://dali.fengsongda.top/Article/details/gtyxgfspsn.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthnrjpgqf.html

PHP:  array_unique($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtwnmmdctk.html

JS:   [...new Set(arr)]
来源：http://dali.meibo888.top/Article/details/gtvwzslojt.html

TS:   [...new Set(arr)]
来源：http://dali.pycfn.com/Article/details/gtrpkvkzpx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shanyushiyangtech.top/Article/details/gttxcmvsgl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.wangshuangyany.cn/Article/details/gtcwznhszy.html

Ruby: arr.uniq
来源：http://dali.jinghuilouyu.cn/Article/details/gtntgcucpz.html

C#:   list.Distinct().ToList()
来源：http://dali.316326.xyz/Article/details/gtbmrvsbwp.html

[D16] 求和与平均值
来源：http://dali.yueranfly.top/Article/details/gtmdhggkny.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.c1oappe.top/Article/details/gtqrjdykmk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xinyue.icu/Article/details/gtdaptnlbg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.birdmap.top/Article/details/gtfxymbbbf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxinkj.top/Article/details/gtnlroxjgj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.chenjidiqi.icu/Article/details/gtbgsbfiwu.html

Go:   // 手写循环累加
来源：http://dali.zhongyouzk.top/Article/details/gtcqvgntah.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.daria6918.cn/Article/details/gtmqzufyyn.html

C#:   list.Sum();  list.Average()
来源：http://dali.mhx1999.top/Article/details/gtxfuypjlm.html

[D17] 最大值与最小值
来源：http://dali.shuidangran.top/Article/details/gtollreddq.html

Py:   max(arr);  min(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgfkbdvzy.html

PHP:  max($arr);  min($arr);
来源：http://dali.9152youxi.cn/Article/details/gtkkqwctud.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zycfv.cn/Article/details/gtjpnfsifb.html

TS:   Math.max(...arr);
来源：http://dali.shzxlz.cn/Article/details/gtnoyrtbdm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cdnleiting.top/Article/details/gtcgugrjon.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yvedp.cn/Article/details/gtcwcspufp.html

Ruby: arr.max;  arr.min
来源：http://dali.yonumen.top/Article/details/gtgjszncnf.html

C#:   list.Max();  list.Min()
来源：http://dali.zhongyouzk.top/Article/details/gtqcsmerjy.html

[D18] 扁平化嵌套数组
来源：http://dali.cashguo.top/Article/details/gtaxbxwluc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gogol.net.cn/Article/details/gtxxerorsj.html

PHP:  array_merge(...$nested);
来源：http://dali.daria6918.cn/Article/details/gtvjyilbia.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hywenlv.cn/Article/details/gtzmusmovb.html

TS:   nested.flat();
来源：http://dali.hysaishi.cn/Article/details/gtfpdyflvh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cucudq.cn/Article/details/gtiwcwthif.html

Go:   // 手写双层循环
来源：http://dali.zdqjudy.top/Article/details/gtwzduvgrj.html

Ruby: nested.flatten
来源：http://dali.sysykeji.top/Article/details/gtqgtobemi.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gterjzvjmd.html

[D19] 按字段分组
来源：http://dali.meibo888.top/Article/details/gtksbvxzlt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yuxming.cn/Article/details/gtbedpscfw.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hywenlv.cn/Article/details/gtwxtcrpyk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sweek.top/Article/details/gtmlnrrwyu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ivvv.top/Article/details/gtukcgoshr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sufxvd.cn/Article/details/gtcwswnsua.html

Go:   // 手写 map[string][]T
来源：http://dali.bjfxy.top/Article/details/gtzvlrjpso.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.chenlongwang.top/Article/details/gtaawhhvdn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinghuilouyu.cn/Article/details/gtonjewlah.html

[D20] 统计每个元素出现次数
来源：http://dali.zdqjudy.top/Article/details/gthuuxgyng.html

Py:   Counter(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtnvotxqol.html

PHP:  array_count_values($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmcoaijnu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sufxvd.cn/Article/details/gtnfazzexe.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258888.top/Article/details/gtjkbmwsqk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cashguo.top/Article/details/gtgvspqphs.html

Go:   // 手写 map[T]int
来源：http://dali.sufxvd.cn/Article/details/gtygqvnzzh.html

Ruby: arr.tally
来源：http://dali.wangdashe.top/Article/details/gtlykknxnd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cqqwz.cn/Article/details/gttyddrdzm.html

[D21] 判断是否包含某元素
来源：http://dali.jlsjyb.cn/Article/details/gtvkgmhdoc.html

Py:   x in arr
来源：http://dali.chenlongwang.top/Article/details/gtwnjewnvm.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jyoumei.cn/Article/details/gtcwhjaqos.html

JS:   arr.includes(x)
来源：http://dali.sweek.top/Article/details/gtiemtmhsi.html

TS:   arr.includes(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtydaaibed.html

Java: list.contains(x)
来源：http://dali.zdqjudy.top/Article/details/gtnhbyhnvy.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtjutneclc.html

Ruby: arr.include?(x)
来源：http://dali.redwolf501.top/Article/details/gtfaxqpuuh.html

C#:   list.Contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttqubgnye.html

[D22] 复制数组（避免共享引用）
来源：http://dali.fengsongda.top/Article/details/gtrvezqoxz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.dashuyun.cn/Article/details/gtqwyoysxd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.0kj1m.cn/Article/details/gtcmmjynjq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ivvv.top/Article/details/gtwtyxupjj.html

TS:   [...arr];
来源：http://dali.gotoacloud.top/Article/details/gtcsrdfumn.html

Java: new ArrayList<>(list);
来源：http://dali.fzhhl.top/Article/details/gtzaikdcsf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.aibaodan.cn/Article/details/gtyzuepshn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhaomingkeji.xyz/Article/details/gthjyojxrk.html

C#:   new List<int>(list);
来源：http://dali.sufxvd.cn/Article/details/gtpehgpuqg.html

[D23] reduce 累积计算
来源：http://dali.wangdashe.top/Article/details/gtvocdmshj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtctspqdrl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jqgufenzy.top/Article/details/gtmjzsxxor.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtyimdbzet.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daria6918.cn/Article/details/gtqgjrwsni.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yuxming.cn/Article/details/gtuxpmyini.html

Go:   // 手写循环
来源：http://dali.jqgfzy.top/Article/details/gthvpepyub.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gzhubu.top/Article/details/gtdoigjxjz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhixingplan.top/Article/details/gttqmgdkwd.html

[D24] 字典 / Map 基本操作
来源：http://dali.gaohongyu789.top/Article/details/gtvakmdcpv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.feifeiyinyue.top/Article/details/gtwabxlegx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.dashuyun.cn/Article/details/gtizokzchg.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.9152youxi.cn/Article/details/gtaeifrhko.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xuanzx.com/Article/details/gtxztczrzm.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhixingplan.top/Article/details/gtcnwwwbvb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yj20258.top/Article/details/gtrglslnpm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.fzhhl.top/Article/details/gtuoebswrx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.pengpengdd.cyou/Article/details/gtyccfznsh.html

[D25] Set 集合去重与交并差
来源：http://dali.jinghuilouyu.cn/Article/details/gtmqbgzgwf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jqgfzy.top/Article/details/gtxuadqxiv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jianghu66.top/Article/details/gtjhfnrwpw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jiagoushi.top/Article/details/gtqteecpyk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.meibo888.top/Article/details/gtpncffboc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhoulong.xyz/Article/details/gtusdvxvry.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ybcxt.top/Article/details/gtullmshgl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hywenlv.cn/Article/details/gtvauoleyd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cucudq.cn/Article/details/gtltosjadc.html

[D26] 数组转字符串
来源：http://dali.cdnleiting.top/Article/details/gtbmmyvasy.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gzhubu.top/Article/details/gtkcfmezjs.html

PHP:  implode(", ", $arr);
来源：http://dali.aibaodan.cn/Article/details/gtlxvknump.html

JS:   arr.join(", ")
来源：http://dali.xylfe.cn/Article/details/gtxmndbonj.html

TS:   arr.join(", ")
来源：http://dali.birdmap.top/Article/details/gtqktjjwst.html

Java: String.join(", ", list)
来源：http://dali.redwolf501.top/Article/details/gtkrmruewq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.tian-w.cn/Article/details/gtxidymgri.html

Ruby: arr.join(", ")
来源：http://dali.c1oappe.top/Article/details/gtkadbtrzn.html

C#:   string.Join(", ", list)
来源：http://dali.316326.xyz/Article/details/gtzxrpwter.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtwrjkbiaz.html

E. 字符串处理
来源：http://dali.snrcjt.cn/Article/details/gtpvqiruzx.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtxqjmhrxw.html

[E01] 拼接字符串
来源：http://dali.aizwys.cn/Article/details/gtrqxfgbje.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhixingplan.top/Article/details/gtkcuzwrsm.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.nanxuanxn.top/Article/details/gtgcmgudli.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.havefunace.top/Article/details/gtbsvcuzjf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sxryk.cn/Article/details/gtdobbqkuu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhengqikj.top/Article/details/gthquifyoe.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.bjfxy.top/Article/details/gtrkqpsuep.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhongyouzk.top/Article/details/gtgvzinxyi.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtyjggxgcf.html

[E02] 重复字符串
来源：http://dali.yvedp.cn/Article/details/gtwsnulhac.html

Py:   "ab" * 3
来源：http://dali.sxryk.cn/Article/details/gtmvjfchpy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xylfe.cn/Article/details/gtmnkoesry.html

JS:   "ab".repeat(3)
来源：http://dali.jlsjyb.cn/Article/details/gtnzcewroo.html

TS:   "ab".repeat(3)
来源：http://dali.cucudq.cn/Article/details/gtwvtxgatr.html

Java: "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gtvoutmijp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gotoacloud.top/Article/details/gtxzsgpdat.html

Ruby: "ab" * 3
来源：http://dali.jqgufenzy.top/Article/details/gtucclgezi.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.quarkkingdee.top/Article/details/gtkiiiuspz.html

[E03] 截取子串
来源：http://dali.ivvv.top/Article/details/gtzlygyzdx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gaohongyu789.top/Article/details/gtvtflelpc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gtgwopcrnp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hfpthk.cn/Article/details/gtsxjogtos.html

TS:   s.slice(1, 4)
来源：http://dali.bjfxy.top/Article/details/gtrjkcpbbh.html

Java: s.substring(1, 4)
来源：http://dali.cdnleiting.top/Article/details/gtjjdeoubs.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sufxvd.cn/Article/details/gtzygyvcse.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ehwqpu.com/Article/details/gtosoiszxa.html

C#:   s.Substring(1, 3)
来源：http://dali.hysaishi.cn/Article/details/gtjjvgdnxm.html

[E04] 查找子串位置
来源：http://dali.vqdsnc.cn/Article/details/gtnjgmkvjr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.dianchejie.cn/Article/details/gtbfugrmmz.html

PHP:  strpos($s, "x");
来源：http://dali.wangshuangyany.cn/Article/details/gtwwxqkqfc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdpgeknth.html

TS:   s.indexOf("x")
来源：http://dali.cdnleiting.top/Article/details/gtjocomhvq.html

Java: s.indexOf("x")
来源：http://dali.hfpthk.cn/Article/details/gtkdfnviea.html

Go:   strings.Index(s, "x")
来源：http://dali.jinqigufen.top/Article/details/gtalowxfgq.html

Ruby: s.index("x")
来源：http://dali.iojbl.cn/Article/details/gteysrovjo.html

C#:   s.IndexOf("x")
来源：http://dali.hysaishi.cn/Article/details/gtobfoskrs.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.bjfxy.top/Article/details/gtnrfunnli.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.sysykeji.top/Article/details/gtrpbotwjk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jiagoushi.top/Article/details/gtiatdlxwm.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jiagoushi.top/Article/details/gtnaskyiev.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjkwezike.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuxming.cn/Article/details/gtrwswrkkb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.chenzaomai.com/Article/details/gtxtnkrnsx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.vqdsnc.cn/Article/details/gtwafiefyq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gticuvgkfy.html

[E06] 替换子串
来源：http://dali.bjfxy.top/Article/details/gtbtdbmfbe.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yj20258.top/Article/details/gtmcvhyggb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xylfe.cn/Article/details/gtuscyfblw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hammf.cn/Article/details/gtiasvcmgr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hammf.cn/Article/details/gtzucelpqz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtpgcfkooe.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jiagoushi.top/Article/details/gtaucmmdrx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcxmygljq.html

C#:   s.Replace("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gtonreodyc.html

[E07] 按分隔符拆分
来源：http://dali.yuanzhike.top/Article/details/gtrbzfwjfg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.guowangkeji.top/Article/details/gtxyhvljop.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.bjfxy.top/Article/details/gttvqlqdqt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.svipenyu.cn/Article/details/gtmaguxski.html

TS:   s.split(",")
来源：http://dali.cheryme.top/Article/details/gtajtvyrib.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yvedp.cn/Article/details/gtiszzkcdv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenzaomai.com/Article/details/gtyipobwzn.html

Ruby: s.split(",");  s.split
来源：http://dali.feifeiyinyue.top/Article/details/gtlvndjqlj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.haohaochexian.top/Article/details/gtkcaljzha.html

[E08] 数组按分隔符合并
来源：http://dali.jlsjyb.cn/Article/details/gtoqognxoj.html

Py:   ",".join(items)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttuuhnfze.html

PHP:  implode(",", $items);
来源：http://dali.xylfe.cn/Article/details/gtjckpfrlp.html

JS:   items.join(",")
来源：http://dali.yj20258.top/Article/details/gtrdzbphlm.html

TS:   items.join(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtycjtoulg.html

Java: String.join(",", items)
来源：http://dali.shuidangran.top/Article/details/gtsksinacs.html

Go:   strings.Join(items, ",")
来源：http://dali.tanke756.top/Article/details/gtmevmjgcz.html

Ruby: items.join(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwojcacmo.html

C#:   string.Join(",", items)
来源：http://dali.redwolf501.top/Article/details/gtsaoryciw.html

[E09] 去除所有空白字符
来源：http://dali.jiagoushi.top/Article/details/gtiyhwwpgi.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hnxiangtu.top/Article/details/gtfsilekki.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shzxlz.cn/Article/details/gtlpkkzwlu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.9152youxi.cn/Article/details/gtcltxgurz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jiagoushi.top/Article/details/gtsgjpomdm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.0kj1m.cn/Article/details/gtxjwmtbcq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.tanke756.top/Article/details/gtbbmfprqz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.feifeiyinyue.top/Article/details/gtkbfslqcp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ehwqpu.com/Article/details/gtioudpmgv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.c1oappe.top/Article/details/gtpjoryaow.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gturhiwxis.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.daria6918.cn/Article/details/gtmeacjuhd.html

JS:   "7".padStart(3, "0")
来源：http://dali.jyoumei.cn/Article/details/gtdnzjyopj.html

TS:   "7".padStart(3, "0")
来源：http://dali.iojbl.cn/Article/details/gtmzduxhtp.html

Java: String.format("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gtdduvsaxg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yuxming.cn/Article/details/gtyfjriubp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.snrcjt.cn/Article/details/gtcnwweutf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.havefunace.top/Article/details/gtufujzmxa.html

[E11] 反转字符串
来源：http://dali.sufxvd.cn/Article/details/gthfzzhxvm.html

Py:   s[::-1]
来源：http://dali.zhongyouzk.top/Article/details/gtfaaxogyc.html

PHP:  strrev($s);
来源：http://dali.tian-w.cn/Article/details/gtgtgivdow.html

JS:   [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gtgyrtwugj.html

TS:   [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gtfurguqsm.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jqgfzy.top/Article/details/gtvehtjtgu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yj202588.top/Article/details/gtimgbpgnb.html

Ruby: s.reverse
来源：http://dali.tanke756.top/Article/details/gtsfsitcnn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.quarkkingdee.top/Article/details/gttmyppkfc.html

[E12] 统计某字符出现次数
来源：http://dali.meibo888.top/Article/details/gtacganggr.html

Py:   s.count("a")
来源：http://dali.havefunace.top/Article/details/gthytgbnwt.html

PHP:  substr_count($s, "a");
来源：http://dali.jinghuilouyu.cn/Article/details/gtdwaiwaog.html

JS:   s.split("a").length - 1
来源：http://dali.xylfe.cn/Article/details/gtdakdihbw.html

TS:   s.split("a").length - 1
来源：http://dali.guannengcc.top/Article/details/gtpeerjaox.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenzaomai.com/Article/details/gtlbxdiqvu.html

Go:   strings.Count(s, "a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtsdalieew.html

Ruby: s.count("a")
来源：http://dali.cashguo.top/Article/details/gtfcwgygys.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqsiyhxwy.html

[E13] 逐字符遍历
来源：http://dali.yangfankeji.com/Article/details/gtjbxoomwx.html

Py:   for ch in s: print(ch)
来源：http://dali.zhixingplan.top/Article/details/gtlgmyrxnv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shangyingyoupin.top/Article/details/gtkfrjrlqm.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.birdmap.top/Article/details/gtjdkzbddy.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dianchejie.cn/Article/details/gtpfgwdstk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.andypj.xyz/Article/details/gtkhklelou.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.nanxuanxn.top/Article/details/gtunfkddkk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ivvv.top/Article/details/gtporxlvqw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shzxlz.cn/Article/details/gtcxienkvq.html


<!-- 参考信息 -->