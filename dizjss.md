代发 wailian999

Java: list.size();
来源：http://dali.chenlongwang.top/Article/details/gtgwtsabwo.html

Go:   len(arr)
来源：http://dali.gotoacloud.top/Article/details/gtenrjoydx.html

Ruby: arr.length; arr.size
来源：http://dali.vqdsnc.cn/Article/details/gtdrbgjkjj.html

C#:   list.Count;
来源：http://dali.vqdsnc.cn/Article/details/gtuuppdjng.html

[D07] 切片 / 取子数组
来源：http://dali.xinyue.icu/Article/details/gtveoblzec.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yvedp.cn/Article/details/gtoyoazwkf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cucudq.cn/Article/details/gtmkdpxugo.html

JS:   arr.slice(1, 4);
来源：http://dali.nanxinkj.top/Article/details/gtlinrbfni.html

TS:   arr.slice(1, 4);
来源：http://dali.gotoacloud.top/Article/details/gtuqiwbeqx.html

Java: list.subList(1, 4);
来源：http://dali.xuetiantiany.cn/Article/details/gtalhypihn.html

Go:   arr[1:4]
来源：http://dali.aizwys.cn/Article/details/gtrjeywums.html

Ruby: arr[1, 3]
来源：http://dali.yangfankeji.com/Article/details/gtpgonbyfa.html

C#:   list.GetRange(1, 3);
来源：http://dali.sufxvd.cn/Article/details/gtcwlvkvye.html

[D08] 合并两个数组
来源：http://dali.tanke756.top/Article/details/gtvbhpwzdq.html

Py:   a + b;  a.extend(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtofibchnu.html

PHP:  array_merge($a, $b);
来源：http://dali.sufxvd.cn/Article/details/gtekzugsbt.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.nanxuanxn.top/Article/details/gtacoslmki.html

TS:   [...a, ...b];
来源：http://dali.c1oappe.top/Article/details/gtdtpfyata.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ehwqpu.com/Article/details/gtqxeyynak.html

Go:   append(a, b...)
来源：http://dali.cdnleiting.top/Article/details/gtgmdcekoo.html

Ruby: a + b;  a.concat(b)
来源：http://dali.c1oappe.top/Article/details/gtneqzrskp.html

C#:   a.Concat(b).ToList()
来源：http://dali.mhx1999.top/Article/details/gtxhabixsz.html

[D09] 排序（升序）
来源：http://dali.zycfv.cn/Article/details/gtmutyhvnn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jyoumei.cn/Article/details/gtgyggnoyx.html

PHP:  sort($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtvjranjys.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cashguo.top/Article/details/gtuncmlrvu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yuanzhike.top/Article/details/gtvpykmxgi.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.svipenyu.cn/Article/details/gtgnjisjvf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtilnzqugv.html

Ruby: arr.sort
来源：http://dali.yanxiufei.cn/Article/details/gtaknvszgs.html

C#:   list.Sort();
来源：http://dali.shuidangran.top/Article/details/gtrdldhedj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhixingplan.top/Article/details/gtjfcgupxd.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shzxlz.cn/Article/details/gtrsmrgvhl.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.guannengcc.top/Article/details/gtzmakrhiu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.quarkkingdee.top/Article/details/gtjlxtvqwx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqhagboyb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ydzc1.top/Article/details/gtmnhomdjv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sufxvd.cn/Article/details/gtfsqufzey.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nanxinkj.top/Article/details/gtnjvftufs.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.vqdsnc.cn/Article/details/gtwjnjnvxx.html

[D11] 反转数组
来源：http://dali.smart0.xyz/Article/details/gtyxlaywcu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ybcxt.top/Article/details/gtcuoryvrx.html

PHP:  array_reverse($arr);
来源：http://dali.cashguo.top/Article/details/gtfffiqhbq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.chenzaomai.com/Article/details/gtdutzmphl.html

TS:   [...arr].reverse();
来源：http://dali.yj20258.top/Article/details/gtrivlqvax.html

Java: Collections.reverse(list);
来源：http://dali.kuanghao11.cn/Article/details/gtzfwmxwrx.html

Go:   slices.Reverse(arr)
来源：http://dali.gotoacloud.top/Article/details/gtpbscvstj.html

Ruby: arr.reverse
来源：http://dali.iojbl.cn/Article/details/gtrvcfdfom.html

C#:   list.Reverse();
来源：http://dali.tanke756.top/Article/details/gtwqfgvawu.html

[D12] 查找元素下标
来源：http://dali.jqgufenzy.top/Article/details/gtjawpaygb.html

Py:   arr.index(x);  x in arr
来源：http://dali.tian-w.cn/Article/details/gtzvzatoss.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.smart0.xyz/Article/details/gtofmycwjh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ydzc1.top/Article/details/gtseqdntwu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhixingplan.top/Article/details/gtfimnjtze.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.feifeiyinyue.top/Article/details/gtkznnksfe.html

Go:   slices.Index(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtfnyciojc.html

Ruby: arr.index(x)
来源：http://dali.haohaochexian.top/Article/details/gtdbozzorj.html

C#:   list.IndexOf(x);
来源：http://dali.wangshuangyany.cn/Article/details/gtvfrxrzzm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xinyue.icu/Article/details/gtpobcbvfz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.redwolf501.top/Article/details/gtcjzsyain.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.smart0.xyz/Article/details/gtxbngppqi.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yj20258.top/Article/details/gtkfmcnnlq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhoulong.xyz/Article/details/gtomfxyvik.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtrexowfjw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gthcvljzee.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sweek.top/Article/details/gtoyduqvdu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.meibo888.top/Article/details/gtnoodnqjg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jqgufenzy.top/Article/details/gtxerwqdtk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtilpkvzmt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ybcxt.top/Article/details/gtlytvrrqs.html

JS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqdvvdwve.html

TS:   arr.map(x => x * 2)
来源：http://dali.cheryme.top/Article/details/gtwseodwtb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cheryme.top/Article/details/gtrwdrcqvg.html

Go:   // 手写循环
来源：http://dali.shzxlz.cn/Article/details/gtystqlndf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.tian-w.cn/Article/details/gthytevcpj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.aizwys.cn/Article/details/gtxmqfqaia.html

[D15] 去重
来源：http://dali.gogol.net.cn/Article/details/gtapnxlcgc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jqgfzy.top/Article/details/gtgfovtnkw.html

PHP:  array_unique($arr);
来源：http://dali.smart0.xyz/Article/details/gtfoaqtmyv.html

JS:   [...new Set(arr)]
来源：http://dali.jqgufenzy.top/Article/details/gtolsigfnm.html

TS:   [...new Set(arr)]
来源：http://dali.shangyingyoupin.top/Article/details/gtjcxqnryp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhiwuduotai.top/Article/details/gtblhlzbtk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hywenlv.cn/Article/details/gtzppptrhz.html

Ruby: arr.uniq
来源：http://dali.dashuyun.cn/Article/details/gtleggtrxi.html

C#:   list.Distinct().ToList()
来源：http://dali.xylfe.cn/Article/details/gtifdivecp.html

[D16] 求和与平均值
来源：http://dali.nanxinkj.top/Article/details/gteauvudug.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jianghu66.top/Article/details/gtgnxsqeac.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yongpay.top/Article/details/gttvsfckzx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkbxpbzka.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xziqi.cn/Article/details/gtwytgtekq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.iojbl.cn/Article/details/gtttqyubee.html

Go:   // 手写循环累加
来源：http://dali.jianghu66.top/Article/details/gtcqpxvmah.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hnxiangtu.top/Article/details/gturoujzxg.html

C#:   list.Sum();  list.Average()
来源：http://dali.yangfankeji.com/Article/details/gtcsxbfhog.html

[D17] 最大值与最小值
来源：http://dali.shanyushiyangtech.top/Article/details/gtqskkcocy.html

Py:   max(arr);  min(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhtjyfka.html

PHP:  max($arr);  min($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtavmfmbts.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.pycfn.com/Article/details/gtgfjjcrod.html

TS:   Math.max(...arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtmhiwfjhm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xziqi.cn/Article/details/gtvstcddzp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shzxlz.cn/Article/details/gtruizaose.html

Ruby: arr.max;  arr.min
来源：http://dali.vqdsnc.cn/Article/details/gtazcpbhfl.html

C#:   list.Max();  list.Min()
来源：http://dali.fengsongda.top/Article/details/gtosrwbnhm.html

[D18] 扁平化嵌套数组
来源：http://dali.hnqzz.top/Article/details/gtslxrnbpn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ppjwa.cn/Article/details/gtpotggamn.html

PHP:  array_merge(...$nested);
来源：http://dali.yj20258.top/Article/details/gtgxkutvvx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tian-w.cn/Article/details/gtegmnopge.html

TS:   nested.flat();
来源：http://dali.jinqigufen.top/Article/details/gtxnwpftuy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gttzoadvtt.html

Go:   // 手写双层循环
来源：http://dali.chenzaomai.com/Article/details/gtsrsftkxt.html

Ruby: nested.flatten
来源：http://dali.yonumen.top/Article/details/gtxsriljwn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtimgoouim.html

[D19] 按字段分组
来源：http://dali.jqgufenzy.top/Article/details/gtpehcrkwn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gotoacloud.top/Article/details/gtnlbuxizp.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdkkbfhrq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.andypj.xyz/Article/details/gtebkdrnyf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ybcxt.top/Article/details/gtpfuqffca.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shuidangran.top/Article/details/gttwtacrfm.html

Go:   // 手写 map[string][]T
来源：http://dali.sufxvd.cn/Article/details/gtgwwadwjw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.nanxinkj.top/Article/details/gtqmysdvpg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.tian-w.cn/Article/details/gtynoqxvad.html

[D20] 统计每个元素出现次数
来源：http://dali.c1oappe.top/Article/details/gtqrvukvnz.html

Py:   Counter(arr)
来源：http://dali.chenzaomai.com/Article/details/gtlsuahdiu.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtoqchuurn.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgufenzy.top/Article/details/gtycwaofxx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cucudq.cn/Article/details/gtsdpmcblp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.pengpengdd.cyou/Article/details/gtmpbpvjfm.html

Go:   // 手写 map[T]int
来源：http://dali.ppjwa.cn/Article/details/gtezywjjla.html

Ruby: arr.tally
来源：http://dali.guowangkeji.top/Article/details/gtogyqbvlt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xylfe.cn/Article/details/gtjjknobav.html

[D21] 判断是否包含某元素
来源：http://dali.pycfn.com/Article/details/gtoyeccjyu.html

Py:   x in arr
来源：http://dali.xuetiantiany.cn/Article/details/gtulpbnwwx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.dianchejie.cn/Article/details/gthlqlgmjp.html

JS:   arr.includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbkkkyxrv.html

TS:   arr.includes(x)
来源：http://dali.pycfn.com/Article/details/gtgflqymkg.html

Java: list.contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gtmfevifwv.html

Go:   slices.Contains(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtvjhvqepe.html

Ruby: arr.include?(x)
来源：http://dali.shzxlz.cn/Article/details/gtvphiwqbv.html

C#:   list.Contains(x)
来源：http://dali.bjfxy.top/Article/details/gtjyxwtkjx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.dianchejie.cn/Article/details/gtemrdctjt.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtbcyirktt.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cqqwz.cn/Article/details/gtjcywxube.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtgoebpjeu.html

TS:   [...arr];
来源：http://dali.birdmap.top/Article/details/gtcvswkwyp.html

Java: new ArrayList<>(list);
来源：http://dali.sweek.top/Article/details/gtoifbzimm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hysaishi.cn/Article/details/gtubytgwih.html

Ruby: arr.dup;  arr.clone
来源：http://dali.chenlongwang.top/Article/details/gtksxcrbnc.html

C#:   new List<int>(list);
来源：http://dali.tianlin.xyz/Article/details/gtivbsqahn.html

[D23] reduce 累积计算
来源：http://dali.sweek.top/Article/details/gthqrxkvqe.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cheryme.top/Article/details/gtejmftiev.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.nanxinkj.top/Article/details/gtkqqvjlxw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daxiang520.top/Article/details/gtsdntxzfm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ehwqpu.com/Article/details/gtvzwbwuob.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.iojbl.cn/Article/details/gtqiyrujdq.html

Go:   // 手写循环
来源：http://dali.hammf.cn/Article/details/gtaqsvbbpg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqcajzjon.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zdqjudy.top/Article/details/gtchicaatz.html

[D24] 字典 / Map 基本操作
来源：http://dali.c1oappe.top/Article/details/gtnwdfpimh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shangyingyoupin.top/Article/details/gtvfkionzi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.svipenyu.cn/Article/details/gtmrjyxnzw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.havefunace.top/Article/details/gtgimesunb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtambndaal.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.9152youxi.cn/Article/details/gtzaiddzgm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hysaishi.cn/Article/details/gtfyasvfhf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nanxinkj.top/Article/details/gtftynevse.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hongshengwenyu.top/Article/details/gtjmhsegya.html

[D25] Set 集合去重与交并差
来源：http://dali.cheryme.top/Article/details/gtphhpuxva.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yj202588.top/Article/details/gtajqdiave.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yuanzhike.top/Article/details/gtbwamntae.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jlsjyb.cn/Article/details/gteroeqqla.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cdnleiting.top/Article/details/gtpdmnlvgd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.nwbrower.top/Article/details/gtiaobttjw.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcwcrhxar.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.snrcjt.cn/Article/details/gtmpwocjwk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtuuohnnib.html

[D26] 数组转字符串
来源：http://dali.snrcjt.cn/Article/details/gteelvndng.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gotoacloud.top/Article/details/gtlfldbcuo.html

PHP:  implode(", ", $arr);
来源：http://dali.aizwys.cn/Article/details/gtkdgniprb.html

JS:   arr.join(", ")
来源：http://dali.cqqwz.cn/Article/details/gthvwqppeu.html

TS:   arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gtbgoelokk.html

Java: String.join(", ", list)
来源：http://dali.yanxiufei.cn/Article/details/gtchqhaxve.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cdnleiting.top/Article/details/gtfxlwjciw.html

Ruby: arr.join(", ")
来源：http://dali.jqgfzy.top/Article/details/gttjqjhgkf.html

C#:   string.Join(", ", list)
来源：http://dali.daxiang520.top/Article/details/gtlhtzctqr.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtxzlwfcar.html

E. 字符串处理
来源：http://dali.jqgufenzy.top/Article/details/gtgjvatwwn.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtterngycp.html

[E01] 拼接字符串
来源：http://dali.yueranfly.top/Article/details/gthhutqqyd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xylfe.cn/Article/details/gtyzwrycns.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyygtbgay.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.0kj1m.cn/Article/details/gtoogtkcev.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sufxvd.cn/Article/details/gtsamndssr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.daria6918.cn/Article/details/gtupqxpexa.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.tianlin.xyz/Article/details/gtqxlkcxuh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdoephily.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gtsiwbokwo.html

[E02] 重复字符串
来源：http://dali.ppjwa.cn/Article/details/gtwedfiasj.html

Py:   "ab" * 3
来源：http://dali.hammf.cn/Article/details/gttuvlzfxn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hysaishi.cn/Article/details/gtopalrttw.html

JS:   "ab".repeat(3)
来源：http://dali.shzxlz.cn/Article/details/gtvnoiewwe.html

TS:   "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gtfchqqytq.html

Java: "ab".repeat(3)
来源：http://dali.iojbl.cn/Article/details/gticwbpszw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.bjfxy.top/Article/details/gtlguoymmv.html

Ruby: "ab" * 3
来源：http://dali.sysykeji.top/Article/details/gtewcfxvlu.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinqigfzy.top/Article/details/gtxczuznjo.html

[E03] 截取子串
来源：http://dali.andypj.xyz/Article/details/gtrfxbucns.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtnnctzjrm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gtvzehldiz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gttcwenlcm.html

TS:   s.slice(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gtrelniwro.html

Java: s.substring(1, 4)
来源：http://dali.hnxiangtu.top/Article/details/gticyrvpzr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhongyouzk.top/Article/details/gtsukwlhfm.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzyghnrrg.html

C#:   s.Substring(1, 3)
来源：http://dali.quarkkingdee.top/Article/details/gtpndyldgn.html

[E04] 查找子串位置
来源：http://dali.guowangkeji.top/Article/details/gtqnqltjvf.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xylfe.cn/Article/details/gtttrnlpws.html

PHP:  strpos($s, "x");
来源：http://dali.yuanzhike.top/Article/details/gtpkydtsqx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.daria6918.cn/Article/details/gthgnwlyig.html

TS:   s.indexOf("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjxvmjmvq.html

Java: s.indexOf("x")
来源：http://dali.xuetiantiany.cn/Article/details/gtnofhlqoy.html

Go:   strings.Index(s, "x")
来源：http://dali.jqgfzy.top/Article/details/gtguzstetk.html

Ruby: s.index("x")
来源：http://dali.tianlin.xyz/Article/details/gtaqthovkr.html

C#:   s.IndexOf("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqkcmvgak.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.guowangkeji.top/Article/details/gtgdsxesoc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ehwqpu.com/Article/details/gtpvuriybe.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ybcxt.top/Article/details/gtanvrpcnj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gtwfozlkoe.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwvpbvhgg.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrapwpzyc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shzxlz.cn/Article/details/gtlcrrmvon.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yj20258.top/Article/details/gtmcvvnikz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.pengpengdd.cyou/Article/details/gthmnkvwzh.html

[E06] 替换子串
来源：http://dali.xylfe.cn/Article/details/gtybpyvyae.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.haohaochexian.top/Article/details/gtgcbnjzem.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.dianchejie.cn/Article/details/gtlwvdegnl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqrwyksgr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthzvisscw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtlkwyzice.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yanxiufei.cn/Article/details/gtnmpqnbue.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtvjhumvsq.html

C#:   s.Replace("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtgquxdhhf.html

[E07] 按分隔符拆分
来源：http://dali.shangyingyoupin.top/Article/details/gtawkjavvl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xziqi.cn/Article/details/gtotudujjb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gteqzhzxml.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinqigfzy.top/Article/details/gthdopvrep.html

TS:   s.split(",")
来源：http://dali.cashguo.top/Article/details/gtmllcrfaj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jqgufenzy.top/Article/details/gtjqisioqx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.fzhhl.top/Article/details/gtyvrefdrv.html

Ruby: s.split(",");  s.split
来源：http://dali.aibaodan.cn/Article/details/gtinpeygot.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.chenjidiqi.icu/Article/details/gtyebjnict.html

[E08] 数组按分隔符合并
来源：http://dali.jiagoushi.top/Article/details/gtghcrqiko.html

Py:   ",".join(items)
来源：http://dali.guannengcc.top/Article/details/gtljwksevg.html

PHP:  implode(",", $items);
来源：http://dali.yuanzhike.top/Article/details/gtgmbbbuvo.html

JS:   items.join(",")
来源：http://dali.yueranfly.top/Article/details/gtiqdfsnif.html

TS:   items.join(",")
来源：http://dali.zhiwuduotai.top/Article/details/gtdqukzkhn.html

Java: String.join(",", items)
来源：http://dali.smart0.xyz/Article/details/gtgmnjclkf.html

Go:   strings.Join(items, ",")
来源：http://dali.xinyue.icu/Article/details/gtlkmjvvip.html

Ruby: items.join(",")
来源：http://dali.yanxiufei.cn/Article/details/gttwqoabkj.html

C#:   string.Join(",", items)
来源：http://dali.yj202588.top/Article/details/gtkjhdrhqr.html

[E09] 去除所有空白字符
来源：http://dali.yonumen.top/Article/details/gtlkhedrwb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhoulong.xyz/Article/details/gtiecbszos.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.snrcjt.cn/Article/details/gtfnthjbkr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.c1oappe.top/Article/details/gtkvtjbeqo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yj202588.top/Article/details/gtdudlymrv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gogol.net.cn/Article/details/gtwssldaaz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gogol.net.cn/Article/details/gtnmopshmm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hywenlv.cn/Article/details/gtaasosxjf.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhoulong.xyz/Article/details/gthurijhvc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.guowangkeji.top/Article/details/gtnwajpgan.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gtncahkzjt.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenzaomai.com/Article/details/gtohhtwxdw.html

JS:   "7".padStart(3, "0")
来源：http://dali.ydzc1.top/Article/details/gtaalxpvjn.html

TS:   "7".padStart(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gtrmxosbcx.html

Java: String.format("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gtzhlvtiyz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gtstwmkthw.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sweek.top/Article/details/gthoigkhys.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ehwqpu.com/Article/details/gtbanjjkuy.html

[E11] 反转字符串
来源：http://dali.chenzaomai.com/Article/details/gtndfzcahm.html

Py:   s[::-1]
来源：http://dali.yanxiufei.cn/Article/details/gtimauudwe.html

PHP:  strrev($s);
来源：http://dali.daxiang520.top/Article/details/gtnnlwelvd.html

JS:   [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gtfwvkelcd.html

TS:   [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gtzqjkmrrh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtapztberi.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shangyingyoupin.top/Article/details/gtoyvjsceu.html

Ruby: s.reverse
来源：http://dali.zycfv.cn/Article/details/gtrkxvfdxh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yongpay.top/Article/details/gtygixglkm.html

[E12] 统计某字符出现次数
来源：http://dali.hywenlv.cn/Article/details/gtjmnguubn.html

Py:   s.count("a")
来源：http://dali.shuidangran.top/Article/details/gtnjhyzbck.html

PHP:  substr_count($s, "a");
来源：http://dali.yongpay.top/Article/details/gtrlwooggm.html

JS:   s.split("a").length - 1
来源：http://dali.yvedp.cn/Article/details/gtregaowgr.html

TS:   s.split("a").length - 1
来源：http://dali.iojbl.cn/Article/details/gtbmxbworq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.daria6918.cn/Article/details/gtuqadafkl.html

Go:   strings.Count(s, "a")
来源：http://dali.hfpthk.cn/Article/details/gtbggcjmiv.html

Ruby: s.count("a")
来源：http://dali.chenzaomai.com/Article/details/gtoeutcobq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.guowangkeji.top/Article/details/gthdgefpgc.html

[E13] 逐字符遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcjqgfdsm.html

Py:   for ch in s: print(ch)
来源：http://dali.hfpthk.cn/Article/details/gtzwdhazgu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhixingplan.top/Article/details/gtpryafjxs.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258.top/Article/details/gtalohtajm.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhixingplan.top/Article/details/gtmysltook.html


<!-- 参考信息 -->