代发 wailian999

Java: list.size();
来源：http://dali.gzhubu.top/Article/details/gtmffhhtoo.html

Go:   len(arr)
来源：http://dali.ivvv.top/Article/details/gttpgnazzy.html

Ruby: arr.length; arr.size
来源：http://dali.ehwqpu.com/Article/details/gtcqqcstcn.html

C#:   list.Count;
来源：http://dali.zdqjudy.top/Article/details/gttiqujrsq.html

[D07] 切片 / 取子数组
来源：http://dali.dianchejie.cn/Article/details/gtjqvtulps.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhengqikj.top/Article/details/gtjmpwpmlx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.gotoacloud.top/Article/details/gtysysrzga.html

JS:   arr.slice(1, 4);
来源：http://dali.yj20258888.top/Article/details/gtpxofhdxu.html

TS:   arr.slice(1, 4);
来源：http://dali.xuetiantiany.cn/Article/details/gttjeljdny.html

Java: list.subList(1, 4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtalsyvmsb.html

Go:   arr[1:4]
来源：http://dali.aizwys.cn/Article/details/gtmyfzbeps.html

Ruby: arr[1, 3]
来源：http://dali.jyoumei.cn/Article/details/gtigezqfrd.html

C#:   list.GetRange(1, 3);
来源：http://dali.jianghu66.top/Article/details/gtcomxaxti.html

[D08] 合并两个数组
来源：http://dali.zhiwuduotai.top/Article/details/gtiuguhumj.html

Py:   a + b;  a.extend(b)
来源：http://dali.hnqzz.top/Article/details/gthmzzazze.html

PHP:  array_merge($a, $b);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtusidpkuf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hysaishi.cn/Article/details/gtjoxoznjv.html

TS:   [...a, ...b];
来源：http://dali.ybcxt.top/Article/details/gtpqkaeacp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ydzc1.top/Article/details/gtckrjmszd.html

Go:   append(a, b...)
来源：http://dali.jiagoushi.top/Article/details/gtxtwljasx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ivvv.top/Article/details/gtogaxlhvm.html

C#:   a.Concat(b).ToList()
来源：http://dali.yonumen.top/Article/details/gthvlkingv.html

[D09] 排序（升序）
来源：http://dali.gotoacloud.top/Article/details/gtxewwfvej.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aizwys.cn/Article/details/gtjeztdwlz.html

PHP:  sort($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtclborwrk.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhixingplan.top/Article/details/gtporkeogf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.chenzaomai.com/Article/details/gtbyswtpla.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xinyue.icu/Article/details/gtovjegznb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtpmixsfwi.html

Ruby: arr.sort
来源：http://dali.xuetiantiany.cn/Article/details/gtmmhcwakw.html

C#:   list.Sort();
来源：http://dali.hywenlv.cn/Article/details/gtpifsbphr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.andypj.xyz/Article/details/gtqtkxdqaz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gotoacloud.top/Article/details/gtnpdexhml.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jqgfzy.top/Article/details/gtvsgehgid.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jlsjyb.cn/Article/details/gtbjazkcyk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.birdmap.top/Article/details/gttvidvaif.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.guowangkeji.top/Article/details/gtttgwevbk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.c1oappe.top/Article/details/gtspwvzyej.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sysykeji.top/Article/details/gtsuqjguub.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.9152youxi.cn/Article/details/gtkbhdwtch.html

[D11] 反转数组
来源：http://dali.hysaishi.cn/Article/details/gtpcqokgbp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.9152youxi.cn/Article/details/gtqkffckmm.html

PHP:  array_reverse($arr);
来源：http://dali.hnxiangtu.top/Article/details/gthnayxajq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jqgufenzy.top/Article/details/gtvtkrlylk.html

TS:   [...arr].reverse();
来源：http://dali.iojbl.cn/Article/details/gtcyasvlhc.html

Java: Collections.reverse(list);
来源：http://dali.andypj.xyz/Article/details/gtrduwqiie.html

Go:   slices.Reverse(arr)
来源：http://dali.andypj.xyz/Article/details/gtnwjfbszz.html

Ruby: arr.reverse
来源：http://dali.yueranfly.top/Article/details/gtxdjvmgwg.html

C#:   list.Reverse();
来源：http://dali.zhixingplan.top/Article/details/gthtxjlgzg.html

[D12] 查找元素下标
来源：http://dali.shanyushiyangtech.top/Article/details/gthxpgqywp.html

Py:   arr.index(x);  x in arr
来源：http://dali.hongshengwenyu.top/Article/details/gtbhgmnbmh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtuyyenxtz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtgtxtxetz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sweek.top/Article/details/gtomjjvwgp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gogol.net.cn/Article/details/gtiopqrgbm.html

Go:   slices.Index(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtatxzcgcw.html

Ruby: arr.index(x)
来源：http://dali.kuanghao11.cn/Article/details/gtraazmonn.html

C#:   list.IndexOf(x);
来源：http://dali.gotoacloud.top/Article/details/gtcagzdgks.html

[D13] 过滤（保留满足条件的）
来源：http://dali.dianchejie.cn/Article/details/gtxjcnkkth.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.nwbrower.top/Article/details/gtkgwbfwlu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhoulong.xyz/Article/details/gtrfergiqh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.redwolf501.top/Article/details/gtarjshaik.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yj20258.top/Article/details/gtqmxvalld.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yangfankeji.com/Article/details/gtgtvrhurc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.vqdsnc.cn/Article/details/gtqjjqimpo.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.feifeiyinyue.top/Article/details/gtxqflylkr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ybcxt.top/Article/details/gtspakqjai.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yongpay.top/Article/details/gteiubwhmy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.havefunace.top/Article/details/gtwfmgetfo.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj20258.top/Article/details/gtedcldylo.html

JS:   arr.map(x => x * 2)
来源：http://dali.hnqzz.top/Article/details/gtjzpulzzn.html

TS:   arr.map(x => x * 2)
来源：http://dali.sufxvd.cn/Article/details/gthxkqlnbs.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.nanxinkj.top/Article/details/gtjdeakwby.html

Go:   // 手写循环
来源：http://dali.jqgfzy.top/Article/details/gtzfiagbjt.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhengqikj.top/Article/details/gtkfuuuxoo.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sysykeji.top/Article/details/gtmpccnhqj.html

[D15] 去重
来源：http://dali.hfpthk.cn/Article/details/gtledpivvv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.guowangkeji.top/Article/details/gtywalbdug.html

PHP:  array_unique($arr);
来源：http://dali.zhengqikj.top/Article/details/gtbhwdkpcl.html

JS:   [...new Set(arr)]
来源：http://dali.cucudq.cn/Article/details/gtakcysafh.html

TS:   [...new Set(arr)]
来源：http://dali.kuanghao11.cn/Article/details/gtwclbzcgj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinqigfzy.top/Article/details/gtddmaqfep.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jiagoushi.top/Article/details/gtrtupmgic.html

Ruby: arr.uniq
来源：http://dali.tianlin.xyz/Article/details/gtmpngwuxn.html

C#:   list.Distinct().ToList()
来源：http://dali.ivvv.top/Article/details/gttvsmpzwq.html

[D16] 求和与平均值
来源：http://dali.nanxuanxn.top/Article/details/gttmlmzstd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xziqi.cn/Article/details/gtuiscuane.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gttmnrqvxj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cdnleiting.top/Article/details/gtrpwbjkvk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtppbkntvs.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shzxlz.cn/Article/details/gtwwnamise.html

Go:   // 手写循环累加
来源：http://dali.jiagoushi.top/Article/details/gtvworpwyj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yuxming.cn/Article/details/gtsbcaogme.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenjidiqi.icu/Article/details/gtxnkmldcd.html

[D17] 最大值与最小值
来源：http://dali.zhongyouzk.top/Article/details/gtkpifuace.html

Py:   max(arr);  min(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpubmlhjd.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhengqikj.top/Article/details/gtnavknbff.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hywenlv.cn/Article/details/gtrkrielgj.html

TS:   Math.max(...arr);
来源：http://dali.fzhhl.top/Article/details/gtmmcqfmqr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jlsjyb.cn/Article/details/gtmkhglfgj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cucudq.cn/Article/details/gtooljnris.html

Ruby: arr.max;  arr.min
来源：http://dali.kuanghao11.cn/Article/details/gtdknjajxn.html

C#:   list.Max();  list.Min()
来源：http://dali.xuanzx.com/Article/details/gtpxwaxcjh.html

[D18] 扁平化嵌套数组
来源：http://dali.fzhhl.top/Article/details/gtyicadati.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ybcxt.top/Article/details/gtceyfoymv.html

PHP:  array_merge(...$nested);
来源：http://dali.316326.xyz/Article/details/gtearlhjlo.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhiwuduotai.top/Article/details/gtkjlwaiuh.html

TS:   nested.flat();
来源：http://dali.snrcjt.cn/Article/details/gtqzantpjq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.0kj1m.cn/Article/details/gtzocqwdfn.html

Go:   // 手写双层循环
来源：http://dali.yueranfly.top/Article/details/gtlaetirrr.html

Ruby: nested.flatten
来源：http://dali.xziqi.cn/Article/details/gtshsflivw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ivvv.top/Article/details/gtpdwoypxt.html

[D19] 按字段分组
来源：http://dali.yuanzhike.top/Article/details/gtgehbkrla.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cashguo.top/Article/details/gtlwrvrsuw.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvkqsaihp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cucudq.cn/Article/details/gtbkhalbwh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.guowangkeji.top/Article/details/gtwafexugy.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.aizwys.cn/Article/details/gtfmyoncet.html

Go:   // 手写 map[string][]T
来源：http://dali.tianlin.xyz/Article/details/gtdtofdabi.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.feifeiyinyue.top/Article/details/gtthhmhgec.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.wangshuangyany.cn/Article/details/gtvmmwnzey.html

[D20] 统计每个元素出现次数
来源：http://dali.aizwys.cn/Article/details/gtjyprtkvw.html

Py:   Counter(arr)
来源：http://dali.yongpay.top/Article/details/gtlbzjofte.html

PHP:  array_count_values($arr);
来源：http://dali.redwolf501.top/Article/details/gtgewtbjci.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jiagoushi.top/Article/details/gtfffzklic.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xylfe.cn/Article/details/gttekvdktp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhongyouzk.top/Article/details/gtntecpbpo.html

Go:   // 手写 map[T]int
来源：http://dali.zhixingplan.top/Article/details/gthrfmnolq.html

Ruby: arr.tally
来源：http://dali.dashuyun.cn/Article/details/gtmqundjjx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zycfv.cn/Article/details/gtohjkydxo.html

[D21] 判断是否包含某元素
来源：http://dali.cashguo.top/Article/details/gtfivaeyrv.html

Py:   x in arr
来源：http://dali.yj20258888.top/Article/details/gtjbrybuuo.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cucudq.cn/Article/details/gthgkrqzgx.html

JS:   arr.includes(x)
来源：http://dali.xylfe.cn/Article/details/gtlfvjgulk.html

TS:   arr.includes(x)
来源：http://dali.9152youxi.cn/Article/details/gtknjbbvsj.html

Java: list.contains(x)
来源：http://dali.redwolf501.top/Article/details/gtqpbcswza.html

Go:   slices.Contains(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtgdzkuqyo.html

Ruby: arr.include?(x)
来源：http://dali.guannengcc.top/Article/details/gtybuvejtv.html

C#:   list.Contains(x)
来源：http://dali.9152youxi.cn/Article/details/gtygnejteb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.fzhhl.top/Article/details/gtutgjwjrs.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtfbqszjez.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hfpthk.cn/Article/details/gtgcilrsew.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yongpay.top/Article/details/gtvmxacfoe.html

TS:   [...arr];
来源：http://dali.yanxiufei.cn/Article/details/gtrzvwiena.html

Java: new ArrayList<>(list);
来源：http://dali.nanxuanxn.top/Article/details/gttmnqelid.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.dashuyun.cn/Article/details/gtiyohkzim.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj20258888.top/Article/details/gtsvbqhqzs.html

C#:   new List<int>(list);
来源：http://dali.tanke756.top/Article/details/gtxnwwgrgb.html

[D23] reduce 累积计算
来源：http://dali.zhixingplan.top/Article/details/gthnodumtb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yvedp.cn/Article/details/gtucotaoab.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrwyopksp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtipcxceac.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuanzhike.top/Article/details/gtksqwkeqr.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhengqikj.top/Article/details/gtogjnenai.html

Go:   // 手写循环
来源：http://dali.cashguo.top/Article/details/gtygpiyynz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yangfankeji.com/Article/details/gtbtbzocip.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.tianlin.xyz/Article/details/gtcrjqifoa.html

[D24] 字典 / Map 基本操作
来源：http://dali.jiagoushi.top/Article/details/gtnqrvggve.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cqqwz.cn/Article/details/gtbemkumez.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ehwqpu.com/Article/details/gtfnbyuvoq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ehwqpu.com/Article/details/gtnrrpudku.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gttvrcqzrv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shanyushiyangtech.top/Article/details/gtobvyeojm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cucudq.cn/Article/details/gthibteljk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zycfv.cn/Article/details/gtptaavvnd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hammf.cn/Article/details/gtapwgwaod.html

[D25] Set 集合去重与交并差
来源：http://dali.hysaishi.cn/Article/details/gtfatgsdcq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sufxvd.cn/Article/details/gtxwbuvaty.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yvedp.cn/Article/details/gtcpudvppk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yuxming.cn/Article/details/gtwynticyr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yonumen.top/Article/details/gtehkqwdzu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.fengsongda.top/Article/details/gtjdzryvpc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jqgfzy.top/Article/details/gtfbtpycls.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhengqikj.top/Article/details/gtwmkcmmar.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ybcxt.top/Article/details/gtkdymaunm.html

[D26] 数组转字符串
来源：http://dali.yangfankeji.com/Article/details/gtqrooyfur.html

Py:   ", ".join(map(str, arr))
来源：http://dali.dashuyun.cn/Article/details/gtfovtzocs.html

PHP:  implode(", ", $arr);
来源：http://dali.mhx1999.top/Article/details/gtkkakofny.html

JS:   arr.join(", ")
来源：http://dali.meibo888.top/Article/details/gtrpgolodi.html

TS:   arr.join(", ")
来源：http://dali.zhixingplan.top/Article/details/gtqfwwugrv.html

Java: String.join(", ", list)
来源：http://dali.svipenyu.cn/Article/details/gtnjawbdzw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hammf.cn/Article/details/gtiwxlchdr.html

Ruby: arr.join(", ")
来源：http://dali.yj20258.top/Article/details/gtedmpmnyu.html

C#:   string.Join(", ", list)
来源：http://dali.zhongyouzk.top/Article/details/gtzbzerjao.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtegxzhxdw.html

E. 字符串处理
来源：http://dali.daxiang520.top/Article/details/gtnfyctgfg.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtegfeduww.html

[E01] 拼接字符串
来源：http://dali.jqgufenzy.top/Article/details/gtxqrmmxgd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yj20258888.top/Article/details/gtjbdkkmkp.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtejuxmtgj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtluhwhqgi.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sweek.top/Article/details/gtrfyyxxuy.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhiwuduotai.top/Article/details/gtnfzgtkvk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yanxiufei.cn/Article/details/gtwmpacsav.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hysaishi.cn/Article/details/gtmrbnjuhr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gtylsyikxa.html

[E02] 重复字符串
来源：http://dali.sufxvd.cn/Article/details/gtefvaclcc.html

Py:   "ab" * 3
来源：http://dali.cucudq.cn/Article/details/gtiofcddoq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ppjwa.cn/Article/details/gtjkmnrwez.html

JS:   "ab".repeat(3)
来源：http://dali.andypj.xyz/Article/details/gtocujaill.html

TS:   "ab".repeat(3)
来源：http://dali.xylfe.cn/Article/details/gtggigswdp.html

Java: "ab".repeat(3)
来源：http://dali.ydzc1.top/Article/details/gtepuztepv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.quarkkingdee.top/Article/details/gtbomjzcvs.html

Ruby: "ab" * 3
来源：http://dali.316326.xyz/Article/details/gttcxskmxf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xinyue.icu/Article/details/gtptpdcdlx.html

[E03] 截取子串
来源：http://dali.iojbl.cn/Article/details/gtdcuetfgv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xinyue.icu/Article/details/gtegumtgwr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gtcumgysfl.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.birdmap.top/Article/details/gtdvpvkojt.html

TS:   s.slice(1, 4)
来源：http://dali.hnqzz.top/Article/details/gtlmegvgch.html

Java: s.substring(1, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gthssgjouu.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenzaomai.com/Article/details/gtavszxbqv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yuxming.cn/Article/details/gtyjeklgwo.html

C#:   s.Substring(1, 3)
来源：http://dali.guowangkeji.top/Article/details/gtokoptssw.html

[E04] 查找子串位置
来源：http://dali.pengpengdd.cyou/Article/details/gtmuqbkujs.html

Py:   s.find("x");  s.index("x")
来源：http://dali.haohaochexian.top/Article/details/gtcvspwikk.html

PHP:  strpos($s, "x");
来源：http://dali.zhixingplan.top/Article/details/gtkaycyyyp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.quarkkingdee.top/Article/details/gtqyehyehf.html

TS:   s.indexOf("x")
来源：http://dali.jyoumei.cn/Article/details/gtvqdxoyjv.html

Java: s.indexOf("x")
来源：http://dali.guannengcc.top/Article/details/gtnhdjekod.html

Go:   strings.Index(s, "x")
来源：http://dali.sxryk.cn/Article/details/gtnmgxypqi.html

Ruby: s.index("x")
来源：http://dali.shangyingyoupin.top/Article/details/gtraxkiztq.html

C#:   s.IndexOf("x")
来源：http://dali.redwolf501.top/Article/details/gthwhnqgdc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ivvv.top/Article/details/gtrzrdggbh.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.nanxuanxn.top/Article/details/gtepqqcmvw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gotoacloud.top/Article/details/gtqliejmzo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xylfe.cn/Article/details/gtpdysppbk.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ivvv.top/Article/details/gtzlmbsusc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhixingplan.top/Article/details/gtzhyxccjh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hnxiangtu.top/Article/details/gtlgvrrrka.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.daria6918.cn/Article/details/gtbmdirfye.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.tanke756.top/Article/details/gtkzztpfft.html

[E06] 替换子串
来源：http://dali.xziqi.cn/Article/details/gthmzxmmne.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.havefunace.top/Article/details/gthdcebazg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cqqwz.cn/Article/details/gtsidochdm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtbukgweeh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtljsynaab.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gtzdvgeklg.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvvdxurmg.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtwntwwkhe.html

C#:   s.Replace("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtavphpkuo.html

[E07] 按分隔符拆分
来源：http://dali.gzhubu.top/Article/details/gthwyaepup.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.andypj.xyz/Article/details/gttfwmqlei.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.havefunace.top/Article/details/gtlpbqcsnv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhixingplan.top/Article/details/gtlhrrxfou.html

TS:   s.split(",")
来源：http://dali.zycfv.cn/Article/details/gtokkkywad.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtejldywky.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwggnfoof.html

Ruby: s.split(",");  s.split
来源：http://dali.shanyushiyangtech.top/Article/details/gtvyjzfprv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.vqdsnc.cn/Article/details/gtorntlohx.html

[E08] 数组按分隔符合并
来源：http://dali.gotoacloud.top/Article/details/gtmezbiwnj.html

Py:   ",".join(items)
来源：http://dali.xziqi.cn/Article/details/gtemdubwbi.html

PHP:  implode(",", $items);
来源：http://dali.hnqzz.top/Article/details/gtavhmywwk.html

JS:   items.join(",")
来源：http://dali.daxiang520.top/Article/details/gtxsuytwgp.html

TS:   items.join(",")
来源：http://dali.hfpthk.cn/Article/details/gtbsohhgze.html

Java: String.join(",", items)
来源：http://dali.cqqwz.cn/Article/details/gtrzgwvmps.html

Go:   strings.Join(items, ",")
来源：http://dali.pycfn.com/Article/details/gtgacphcni.html

Ruby: items.join(",")
来源：http://dali.316326.xyz/Article/details/gtlnazyfgj.html

C#:   string.Join(",", items)
来源：http://dali.wangshuangyany.cn/Article/details/gtofkdswug.html

[E09] 去除所有空白字符
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfjupgab.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.fengsongda.top/Article/details/gtqgodkuvt.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jiagoushi.top/Article/details/gtbyvurqoi.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ehwqpu.com/Article/details/gtnyldohjw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tian-w.cn/Article/details/gtbxcyytxt.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cashguo.top/Article/details/gtujskxqes.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuntwbxfk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.nwbrower.top/Article/details/gteudswkmj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.birdmap.top/Article/details/gtntiuyilj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhiwuduotai.top/Article/details/gtlwzjudzm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gtheazbpzt.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.birdmap.top/Article/details/gtzjrpbufp.html

JS:   "7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gtamnfyrms.html

TS:   "7".padStart(3, "0")
来源：http://dali.shuidangran.top/Article/details/gthejianly.html

Java: String.format("%03d", 7)
来源：http://dali.hnxiangtu.top/Article/details/gtwcqsgpob.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gtvjjotkvr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hnxiangtu.top/Article/details/gtlefsivul.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zycfv.cn/Article/details/gttaadqchu.html

[E11] 反转字符串
来源：http://dali.mhx1999.top/Article/details/gtowchftsi.html

Py:   s[::-1]
来源：http://dali.zhiwuduotai.top/Article/details/gtboglgjap.html

PHP:  strrev($s);
来源：http://dali.zhixingplan.top/Article/details/gtegyogcwq.html

JS:   [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gtahgaxqxu.html

TS:   [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gtbsorncsu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyrzcrzlk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sufxvd.cn/Article/details/gthpjjrdah.html

Ruby: s.reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzudjotuq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jiagoushi.top/Article/details/gtckynnzsi.html

[E12] 统计某字符出现次数
来源：http://dali.tanke756.top/Article/details/gtdvyhgqls.html

Py:   s.count("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfawenniy.html

PHP:  substr_count($s, "a");
来源：http://dali.dianchejie.cn/Article/details/gtjznsmzzd.html

JS:   s.split("a").length - 1
来源：http://dali.cashguo.top/Article/details/gtsqywhbec.html

TS:   s.split("a").length - 1
来源：http://dali.dianchejie.cn/Article/details/gtllucmhni.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.redwolf501.top/Article/details/gtgqwtwpeh.html

Go:   strings.Count(s, "a")
来源：http://dali.yuanzhike.top/Article/details/gttuqjodez.html

Ruby: s.count("a")
来源：http://dali.fzhhl.top/Article/details/gtvgfqehnl.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrogjormi.html

[E13] 逐字符遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfraskpgu.html

Py:   for ch in s: print(ch)
来源：http://dali.gotoacloud.top/Article/details/gtcslpuanu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gaohongyu789.top/Article/details/gtxzcsawth.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hywenlv.cn/Article/details/gtjihvtpxz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cucudq.cn/Article/details/gtnceegzlp.html


<!-- 参考信息 -->