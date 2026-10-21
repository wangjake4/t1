代发 wailian999

TS:   arr.slice(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gtspsqiewg.html

Java: list.subList(1, 4);
来源：http://dali.aizwys.cn/Article/details/gtufqllstn.html

Go:   arr[1:4]
来源：http://dali.xuetiantiany.cn/Article/details/gtrihhzlgk.html

Ruby: arr[1, 3]
来源：http://dali.hnxiangtu.top/Article/details/gtdatgvwup.html

C#:   list.GetRange(1, 3);
来源：http://dali.ppjwa.cn/Article/details/gtctverjho.html

[D08] 合并两个数组
来源：http://dali.ivvv.top/Article/details/gtwdxdqzlx.html

Py:   a + b;  a.extend(b)
来源：http://dali.havefunace.top/Article/details/gtuicdvxal.html

PHP:  array_merge($a, $b);
来源：http://dali.guannengcc.top/Article/details/gthqhtphju.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jqgfzy.top/Article/details/gtxdyijsyr.html

TS:   [...a, ...b];
来源：http://dali.316326.xyz/Article/details/gthxprkmtm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yongpay.top/Article/details/gttymmxsgt.html

Go:   append(a, b...)
来源：http://dali.chenjidiqi.icu/Article/details/gtfijacgoo.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yuxming.cn/Article/details/gtsaannpmd.html

C#:   a.Concat(b).ToList()
来源：http://dali.fzhhl.top/Article/details/gthazgszvp.html

[D09] 排序（升序）
来源：http://dali.redwolf501.top/Article/details/gtpijtwucx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigufen.top/Article/details/gtthbpfhwd.html

PHP:  sort($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtxgeyfjjl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.vqdsnc.cn/Article/details/gtxxsxilrc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.pycfn.com/Article/details/gtdmteewuw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.bjfxy.top/Article/details/gtwryrzmcr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.fengsongda.top/Article/details/gtiqbdlfvt.html

Ruby: arr.sort
来源：http://dali.wangdashe.top/Article/details/gtkzqtohtu.html

C#:   list.Sort();
来源：http://dali.ivvv.top/Article/details/gtcailcpck.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhoulong.xyz/Article/details/gtvqlxhekn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.nwbrower.top/Article/details/gtrgkggmzb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.iojbl.cn/Article/details/gtrxyghfsf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xinyue.icu/Article/details/gtkjffvbku.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258.top/Article/details/gtynirqtuz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsgflvgst.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yvedp.cn/Article/details/gtqoihsvza.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yj202588.top/Article/details/gttyysbpgs.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xylfe.cn/Article/details/gtacafmrxf.html

[D11] 反转数组
来源：http://dali.dashuyun.cn/Article/details/gtzyisscku.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhiwuduotai.top/Article/details/gtawqhcpug.html

PHP:  array_reverse($arr);
来源：http://dali.haohaochexian.top/Article/details/gtaewxuzjc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xylfe.cn/Article/details/gtpibjjzxe.html

TS:   [...arr].reverse();
来源：http://dali.0kj1m.cn/Article/details/gtgpnadnyk.html

Java: Collections.reverse(list);
来源：http://dali.bjfxy.top/Article/details/gtiganzdik.html

Go:   slices.Reverse(arr)
来源：http://dali.snrcjt.cn/Article/details/gtljbirvcq.html

Ruby: arr.reverse
来源：http://dali.yonumen.top/Article/details/gtxvsskxpl.html

C#:   list.Reverse();
来源：http://dali.xziqi.cn/Article/details/gtadpqtpnh.html

[D12] 查找元素下标
来源：http://dali.zhengqikj.top/Article/details/gtdoqwakki.html

Py:   arr.index(x);  x in arr
来源：http://dali.sysykeji.top/Article/details/gtdchslkgd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ydzc1.top/Article/details/gtxtjdugho.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ydzc1.top/Article/details/gtcpelhnwb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhongyouzk.top/Article/details/gtmaotgvcp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.vqdsnc.cn/Article/details/gtfqwesfhw.html

Go:   slices.Index(arr, x)
来源：http://dali.yj202588.top/Article/details/gtfwjhpzta.html

Ruby: arr.index(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtlfnyyohc.html

C#:   list.IndexOf(x);
来源：http://dali.shanyushiyangtech.top/Article/details/gtepkeyzxv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.dashuyun.cn/Article/details/gtftiihlgu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cheryme.top/Article/details/gtzgldjpqs.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhiwuduotai.top/Article/details/gthimpbeyd.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jqgfzy.top/Article/details/gtrokoifft.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhixingplan.top/Article/details/gtmkoeanlz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yongpay.top/Article/details/gtflkmoljr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nanxinkj.top/Article/details/gtlzlxsfct.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jqgufenzy.top/Article/details/gtayqaizkk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsfhgoxcp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenjidiqi.icu/Article/details/gtvtpdpppf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yangfankeji.com/Article/details/gtdsnaixkg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.daxiang520.top/Article/details/gtodtzhgxs.html

JS:   arr.map(x => x * 2)
来源：http://dali.svipenyu.cn/Article/details/gtcsvvmirp.html

TS:   arr.map(x => x * 2)
来源：http://dali.fengsongda.top/Article/details/gtdbwbetiq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtttrbctjv.html

Go:   // 手写循环
来源：http://dali.ehwqpu.com/Article/details/gteprftnqp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.chenlongwang.top/Article/details/gthluxezpg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cqqwz.cn/Article/details/gtudfdesfm.html

[D15] 去重
来源：http://dali.fzhhl.top/Article/details/gtnfscajcr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.kuanghao11.cn/Article/details/gtygclvjpx.html

PHP:  array_unique($arr);
来源：http://dali.dianchejie.cn/Article/details/gtgsfisrsw.html

JS:   [...new Set(arr)]
来源：http://dali.dianchejie.cn/Article/details/gtoqtgkwgu.html

TS:   [...new Set(arr)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrhrunmsu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shuidangran.top/Article/details/gtrgjemvbe.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yuxming.cn/Article/details/gtyzfajrhc.html

Ruby: arr.uniq
来源：http://dali.birdmap.top/Article/details/gtmbksifii.html

C#:   list.Distinct().ToList()
来源：http://dali.cdnleiting.top/Article/details/gteasrnini.html

[D16] 求和与平均值
来源：http://dali.yanxiufei.cn/Article/details/gttwzeuzpw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ivvv.top/Article/details/gtbnzqbpzq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.guowangkeji.top/Article/details/gtalaehgkn.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.haohaochexian.top/Article/details/gttdirlqqs.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhixingplan.top/Article/details/gtaoehodzn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zdqjudy.top/Article/details/gtsrljnyyv.html

Go:   // 手写循环累加
来源：http://dali.gzhubu.top/Article/details/gtafbfxzbb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj20258888.top/Article/details/gtncguopqx.html

C#:   list.Sum();  list.Average()
来源：http://dali.tianlin.xyz/Article/details/gtygajaull.html

[D17] 最大值与最小值
来源：http://dali.sysykeji.top/Article/details/gtzynfamhl.html

Py:   max(arr);  min(arr)
来源：http://dali.sweek.top/Article/details/gtafmvhznu.html

PHP:  max($arr);  min($arr);
来源：http://dali.yanxiufei.cn/Article/details/gthjxlbgom.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.pycfn.com/Article/details/gtdrkfuogo.html

TS:   Math.max(...arr);
来源：http://dali.hammf.cn/Article/details/gtrxjtqvfb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jyoumei.cn/Article/details/gtcncbezsz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.iojbl.cn/Article/details/gtzwcimwql.html

Ruby: arr.max;  arr.min
来源：http://dali.yj202588.top/Article/details/gtxtwidgyd.html

C#:   list.Max();  list.Min()
来源：http://dali.zhixingplan.top/Article/details/gtzbxwwhsk.html

[D18] 扁平化嵌套数组
来源：http://dali.shzxlz.cn/Article/details/gtcdbpvyah.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.meibo888.top/Article/details/gtskaslwjv.html

PHP:  array_merge(...$nested);
来源：http://dali.yonumen.top/Article/details/gtsnomqgmz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.svipenyu.cn/Article/details/gtcwkdzywm.html

TS:   nested.flat();
来源：http://dali.gaohongyu789.top/Article/details/gtdeqtwvum.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.guowangkeji.top/Article/details/gtviocdhyk.html

Go:   // 手写双层循环
来源：http://dali.c1oappe.top/Article/details/gtfijqszje.html

Ruby: nested.flatten
来源：http://dali.redwolf501.top/Article/details/gttwnrwlqs.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hnqzz.top/Article/details/gtotvjsmsu.html

[D19] 按字段分组
来源：http://dali.jqgfzy.top/Article/details/gtforlilwz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtjavqnfpo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.nwbrower.top/Article/details/gtlbuobvew.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.mhx1999.top/Article/details/gtiuyfcetq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhoulong.xyz/Article/details/gtgxkxcfzq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yangfankeji.com/Article/details/gtnirfxudb.html

Go:   // 手写 map[string][]T
来源：http://dali.vqdsnc.cn/Article/details/gtgkbbdljf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yangfankeji.com/Article/details/gtbekpnjxs.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.iojbl.cn/Article/details/gtwsnyusah.html

[D20] 统计每个元素出现次数
来源：http://dali.ybcxt.top/Article/details/gthdltdflo.html

Py:   Counter(arr)
来源：http://dali.fzhhl.top/Article/details/gtnzmkjogd.html

PHP:  array_count_values($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtmpopfwje.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.9152youxi.cn/Article/details/gtpbywsamp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.birdmap.top/Article/details/gtuwqcyphh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.aizwys.cn/Article/details/gtoihtsrac.html

Go:   // 手写 map[T]int
来源：http://dali.pengpengdd.cyou/Article/details/gtovdguyni.html

Ruby: arr.tally
来源：http://dali.ppjwa.cn/Article/details/gtofpjuobg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yueranfly.top/Article/details/gtmourgqrb.html

[D21] 判断是否包含某元素
来源：http://dali.haohaochexian.top/Article/details/gtuzdjfyhb.html

Py:   x in arr
来源：http://dali.hfpthk.cn/Article/details/gtioemabsn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.pengpengdd.cyou/Article/details/gtnksbyldq.html

JS:   arr.includes(x)
来源：http://dali.iojbl.cn/Article/details/gtejzugsim.html

TS:   arr.includes(x)
来源：http://dali.dianchejie.cn/Article/details/gtcfukqevu.html

Java: list.contains(x)
来源：http://dali.ppjwa.cn/Article/details/gtdjtbdnvc.html

Go:   slices.Contains(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gthpmilyod.html

Ruby: arr.include?(x)
来源：http://dali.dianchejie.cn/Article/details/gtfiwutkvv.html

C#:   list.Contains(x)
来源：http://dali.c1oappe.top/Article/details/gtfminmxvu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.c1oappe.top/Article/details/gtrfndahid.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ivvv.top/Article/details/gtuotpawfm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xuetiantiany.cn/Article/details/gtlebajfmj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtmimvuesj.html

TS:   [...arr];
来源：http://dali.sweek.top/Article/details/gtrqomomrs.html

Java: new ArrayList<>(list);
来源：http://dali.haohaochexian.top/Article/details/gthtwuumzf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.316326.xyz/Article/details/gtkznrouzd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.wangshuangyany.cn/Article/details/gtnhvdkcsi.html

C#:   new List<int>(list);
来源：http://dali.tianlin.xyz/Article/details/gtkjphytve.html

[D23] reduce 累积计算
来源：http://dali.c1oappe.top/Article/details/gtfpocrtbr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcppgcvju.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hywenlv.cn/Article/details/gtzoopbdao.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.iojbl.cn/Article/details/gtvmcrclvt.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtpfithfpl.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yj202588.top/Article/details/gtctibhtsi.html

Go:   // 手写循环
来源：http://dali.yongpay.top/Article/details/gthpdhqmtk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.fzhhl.top/Article/details/gtdhwwljvm.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.iojbl.cn/Article/details/gtjatrafrc.html

[D24] 字典 / Map 基本操作
来源：http://dali.hysaishi.cn/Article/details/gtncmqtida.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ydzc1.top/Article/details/gtxaztcjnt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hnqzz.top/Article/details/gtlpsqrlny.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.tianlin.xyz/Article/details/gtputfqwcu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shuidangran.top/Article/details/gtogngiffh.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.0kj1m.cn/Article/details/gtkbvbgbfn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hongshengwenyu.top/Article/details/gtobiaapmg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.snrcjt.cn/Article/details/gtamafnczr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sysykeji.top/Article/details/gtizdtiygt.html

[D25] Set 集合去重与交并差
来源：http://dali.gotoacloud.top/Article/details/gtnxozaczi.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinqigfzy.top/Article/details/gtmryzbahc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhengqikj.top/Article/details/gtvvnujvnb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sufxvd.cn/Article/details/gthlskthsn.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yongpay.top/Article/details/gtnbxtkyrt.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.snrcjt.cn/Article/details/gtficiylwy.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jqgfzy.top/Article/details/gtteseeqqh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.9152youxi.cn/Article/details/gteyflbkjk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhixingplan.top/Article/details/gtemroowcm.html

[D26] 数组转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzvaaehkv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.iojbl.cn/Article/details/gtbktptomi.html

PHP:  implode(", ", $arr);
来源：http://dali.gzhubu.top/Article/details/gtswwpiolt.html

JS:   arr.join(", ")
来源：http://dali.c1oappe.top/Article/details/gtvccpmntw.html

TS:   arr.join(", ")
来源：http://dali.daxiang520.top/Article/details/gttdqcmkmt.html

Java: String.join(", ", list)
来源：http://dali.gotoacloud.top/Article/details/gttufbervj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvqdvqyls.html

Ruby: arr.join(", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtijqmzdxm.html

C#:   string.Join(", ", list)
来源：http://dali.jlsjyb.cn/Article/details/gtbhhawipe.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtpqrzrfdu.html

E. 字符串处理
来源：http://dali.haohaochexian.top/Article/details/gtkfikjzzj.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtgxwvgvot.html

[E01] 拼接字符串
来源：http://dali.fzhhl.top/Article/details/gtwwsjknwx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ydzc1.top/Article/details/gtmfiezefo.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.chenjidiqi.icu/Article/details/gtnlvuzwzx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tanke756.top/Article/details/gtewfnikaz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxuanxn.top/Article/details/gtexqlhnit.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jiagoushi.top/Article/details/gtqaeompbp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yj202588.top/Article/details/gtakgbrlbx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.nanxuanxn.top/Article/details/gtelsyydvg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hammf.cn/Article/details/gtnacdezqe.html

[E02] 重复字符串
来源：http://dali.redwolf501.top/Article/details/gtlwmwgtcm.html

Py:   "ab" * 3
来源：http://dali.jinqigufen.top/Article/details/gtxibddtyj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.fzhhl.top/Article/details/gtgfzluvkr.html

JS:   "ab".repeat(3)
来源：http://dali.cashguo.top/Article/details/gtsrkmxtek.html

TS:   "ab".repeat(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtfabkdgpq.html

Java: "ab".repeat(3)
来源：http://dali.cdnleiting.top/Article/details/gtmsbncfyv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zdqjudy.top/Article/details/gtycbsmioo.html

Ruby: "ab" * 3
来源：http://dali.birdmap.top/Article/details/gtswzeewhh.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yj20258.top/Article/details/gtklhpkjwk.html

[E03] 截取子串
来源：http://dali.meibo888.top/Article/details/gtfpoffrxo.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zdqjudy.top/Article/details/gtvdmlpwwv.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gtsfvbhsvj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.bjfxy.top/Article/details/gthyqttshe.html

TS:   s.slice(1, 4)
来源：http://dali.yj20258888.top/Article/details/gtjhlxbgkg.html

Java: s.substring(1, 4)
来源：http://dali.cdnleiting.top/Article/details/gtscslkwcy.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.mhx1999.top/Article/details/gtfgbxjbhf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hywenlv.cn/Article/details/gtylaguqvo.html

C#:   s.Substring(1, 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvvzeeaze.html

[E04] 查找子串位置
来源：http://dali.sweek.top/Article/details/gtlbespiky.html

Py:   s.find("x");  s.index("x")
来源：http://dali.aizwys.cn/Article/details/gtetdevmoa.html

PHP:  strpos($s, "x");
来源：http://dali.chenjidiqi.icu/Article/details/gtcenpdbbp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.nwbrower.top/Article/details/gtdchincao.html

TS:   s.indexOf("x")
来源：http://dali.shangyingyoupin.top/Article/details/gtxirivefh.html

Java: s.indexOf("x")
来源：http://dali.gzhubu.top/Article/details/gtrqbfmiwp.html

Go:   strings.Index(s, "x")
来源：http://dali.nwbrower.top/Article/details/gtgmixeyal.html

Ruby: s.index("x")
来源：http://dali.chenlongwang.top/Article/details/gtrisluemt.html

C#:   s.IndexOf("x")
来源：http://dali.sysykeji.top/Article/details/gtjbosupev.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shangyingyoupin.top/Article/details/gtnrsjfmjh.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtbohhbyry.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yj20258.top/Article/details/gtzaxldikt.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gtdeambcvy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhoulong.xyz/Article/details/gtlsvpmnhp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.quarkkingdee.top/Article/details/gttezfprwf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.meibo888.top/Article/details/gtvgbljzme.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zdqjudy.top/Article/details/gtouxoyjsc.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yj20258888.top/Article/details/gtltzannfb.html

[E06] 替换子串
来源：http://dali.hongshengwenyu.top/Article/details/gtusdfdzth.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nanxinkj.top/Article/details/gtornkvagm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.nanxuanxn.top/Article/details/gtzpqzwegu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtaummnebn.html

TS:   s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtsjxedxle.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtjgsljipl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yvedp.cn/Article/details/gtbnonibbz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtlijjjysa.html

C#:   s.Replace("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtbzadvumj.html

[E07] 按分隔符拆分
来源：http://dali.jinghuilouyu.cn/Article/details/gtzfswwaki.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.nanxinkj.top/Article/details/gtsucumzgo.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jianghu66.top/Article/details/gtmuvinkja.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.dashuyun.cn/Article/details/gtzohzkjmu.html

TS:   s.split(",")
来源：http://dali.zhiwuduotai.top/Article/details/gtwnwgrnpy.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.kuanghao11.cn/Article/details/gtdxwyprix.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yj20258888.top/Article/details/gtufzjpzfk.html

Ruby: s.split(",");  s.split
来源：http://dali.mhx1999.top/Article/details/gtplibeeds.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jinqigfzy.top/Article/details/gtgkwejmuj.html

[E08] 数组按分隔符合并
来源：http://dali.guowangkeji.top/Article/details/gthbjekudo.html

Py:   ",".join(items)
来源：http://dali.jqgfzy.top/Article/details/gtpnjvramj.html

PHP:  implode(",", $items);
来源：http://dali.nanxuanxn.top/Article/details/gtnizlopvx.html

JS:   items.join(",")
来源：http://dali.yvedp.cn/Article/details/gtfqzdtaht.html

TS:   items.join(",")
来源：http://dali.nwbrower.top/Article/details/gtuubasyym.html

Java: String.join(",", items)
来源：http://dali.hfpthk.cn/Article/details/gtvieyyzsu.html

Go:   strings.Join(items, ",")
来源：http://dali.yuanzhike.top/Article/details/gtbfbtrgbf.html

Ruby: items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gtrywrlsal.html

C#:   string.Join(",", items)
来源：http://dali.tian-w.cn/Article/details/gtvwnkzlac.html

[E09] 去除所有空白字符
来源：http://dali.nanxuanxn.top/Article/details/gtqizgzhza.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.nanxuanxn.top/Article/details/gttdzlukqk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtngyhbkay.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.dianchejie.cn/Article/details/gtrkceaiiv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenzaomai.com/Article/details/gtvhilvxyz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hnxiangtu.top/Article/details/gtessqjtuc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cqqwz.cn/Article/details/gtzebbuxbi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.nanxinkj.top/Article/details/gtqxhfwjpi.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ybcxt.top/Article/details/gtgqrkdsnb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhixingplan.top/Article/details/gtoextnohw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gtnywpaoni.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cashguo.top/Article/details/gtfasxsqhg.html

JS:   "7".padStart(3, "0")
来源：http://dali.hongshengwenyu.top/Article/details/gtconvwyhq.html

TS:   "7".padStart(3, "0")
来源：http://dali.jiagoushi.top/Article/details/gtrfsbrewh.html

Java: String.format("%03d", 7)
来源：http://dali.yanxiufei.cn/Article/details/gtyallyfya.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhiwuduotai.top/Article/details/gtbidktxbg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gthssboqwi.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.dianchejie.cn/Article/details/gtlevpgajj.html

[E11] 反转字符串
来源：http://dali.zdqjudy.top/Article/details/gtuagokhvu.html

Py:   s[::-1]
来源：http://dali.tanke756.top/Article/details/gtpndschdf.html

PHP:  strrev($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqirlfwzn.html

JS:   [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gtgchcetlh.html

TS:   [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gtlszlhbpo.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gtesojduab.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.pycfn.com/Article/details/gtkysifhgy.html

Ruby: s.reverse
来源：http://dali.hongshengwenyu.top/Article/details/gtzlwakwxg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zycfv.cn/Article/details/gtnkhucnxu.html

[E12] 统计某字符出现次数
来源：http://dali.gzhubu.top/Article/details/gtmackmyip.html

Py:   s.count("a")
来源：http://dali.tanke756.top/Article/details/gttmvjldbi.html

PHP:  substr_count($s, "a");
来源：http://dali.sufxvd.cn/Article/details/gtksikdtak.html

JS:   s.split("a").length - 1
来源：http://dali.cdnleiting.top/Article/details/gtetjkyazo.html

TS:   s.split("a").length - 1
来源：http://dali.sufxvd.cn/Article/details/gtwvdjhfxn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.mhx1999.top/Article/details/gtplhkwzyv.html

Go:   strings.Count(s, "a")
来源：http://dali.yueranfly.top/Article/details/gtyvucnnja.html

Ruby: s.count("a")
来源：http://dali.ybcxt.top/Article/details/gtndyesamb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zdqjudy.top/Article/details/gtotuvfcwo.html

[E13] 逐字符遍历
来源：http://dali.vqdsnc.cn/Article/details/gtgbcezzlj.html

Py:   for ch in s: print(ch)
来源：http://dali.yongpay.top/Article/details/gtbieckcnn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtztqhzwlj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fzhhl.top/Article/details/gtnvzhvuhf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daria6918.cn/Article/details/gtoqvcfouo.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtquqxwtzo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.316326.xyz/Article/details/gtkdsypplu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xuetiantiany.cn/Article/details/gtzoayoedc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dashuyun.cn/Article/details/gtediompyt.html

[E14] URL 编码与 Base64
来源：http://dali.nanxuanxn.top/Article/details/gtbujkrtpv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.fengsongda.top/Article/details/gtrapjmhqc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtcrdfsuzu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.tianlin.xyz/Article/details/gtykolvmes.html


<!-- 参考信息 -->