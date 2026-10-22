代发 wailian999

[D07] 切片 / 取子数组
来源：http://dali.yj202588.top/Article/details/gtrqkiiaju.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ybcxt.top/Article/details/gtalzossys.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xuanzx.com/Article/details/gtdgqmuxdl.html

JS:   arr.slice(1, 4);
来源：http://dali.xylfe.cn/Article/details/gtijtmwtib.html

TS:   arr.slice(1, 4);
来源：http://dali.bjfxy.top/Article/details/gtcpxfdvxm.html

Java: list.subList(1, 4);
来源：http://dali.gaohongyu789.top/Article/details/gtqcjbgrjt.html

Go:   arr[1:4]
来源：http://dali.fzhhl.top/Article/details/gtmfktqmog.html

Ruby: arr[1, 3]
来源：http://dali.xylfe.cn/Article/details/gtdzmmwkno.html

C#:   list.GetRange(1, 3);
来源：http://dali.chenlongwang.top/Article/details/gtadkotglk.html

[D08] 合并两个数组
来源：http://dali.yj202588.top/Article/details/gtobstoklt.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtipnidkwn.html

PHP:  array_merge($a, $b);
来源：http://dali.dianchejie.cn/Article/details/gtopodjfvz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yuxming.cn/Article/details/gtsfzyqciz.html

TS:   [...a, ...b];
来源：http://dali.snrcjt.cn/Article/details/gtvvhdmfye.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhengqikj.top/Article/details/gtbxexqhtp.html

Go:   append(a, b...)
来源：http://dali.dianchejie.cn/Article/details/gtbjhanimt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hammf.cn/Article/details/gtdvkvbyqk.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gtbwzjpzjb.html

[D09] 排序（升序）
来源：http://dali.vqdsnc.cn/Article/details/gtykhegcev.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gzhubu.top/Article/details/gttusgaqrt.html

PHP:  sort($arr);
来源：http://dali.chenzaomai.com/Article/details/gtidddsvgf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.guannengcc.top/Article/details/gtcgtdnjxh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xylfe.cn/Article/details/gtwaejvfbs.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.daria6918.cn/Article/details/gtoofcgwif.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.9152youxi.cn/Article/details/gtdiplqydw.html

Ruby: arr.sort
来源：http://dali.yvedp.cn/Article/details/gtslhfrlbn.html

C#:   list.Sort();
来源：http://dali.xuetiantiany.cn/Article/details/gtjpqpxubt.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.nanxuanxn.top/Article/details/gtdsaimrdr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ehwqpu.com/Article/details/gthehsowym.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cdnleiting.top/Article/details/gthyagwykf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gotoacloud.top/Article/details/gtmctwwddk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ehwqpu.com/Article/details/gtjyctaykj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hammf.cn/Article/details/gtgzmjoinl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.wangdashe.top/Article/details/gtjxewifwc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhoulong.xyz/Article/details/gthgjidcga.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.chenzaomai.com/Article/details/gttdhlauio.html

[D11] 反转数组
来源：http://dali.andypj.xyz/Article/details/gtslsomofu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.c1oappe.top/Article/details/gtgogbgajj.html

PHP:  array_reverse($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gttmehcxkd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xuetiantiany.cn/Article/details/gtuoilqzal.html

TS:   [...arr].reverse();
来源：http://dali.fzhhl.top/Article/details/gtlfqcxizp.html

Java: Collections.reverse(list);
来源：http://dali.dianchejie.cn/Article/details/gtovxdrdqv.html

Go:   slices.Reverse(arr)
来源：http://dali.xylfe.cn/Article/details/gtkcbhulvt.html

Ruby: arr.reverse
来源：http://dali.hnxiangtu.top/Article/details/gtqsupplxk.html

C#:   list.Reverse();
来源：http://dali.cdnleiting.top/Article/details/gtveespkno.html

[D12] 查找元素下标
来源：http://dali.dashuyun.cn/Article/details/gtsfukjekq.html

Py:   arr.index(x);  x in arr
来源：http://dali.haohaochexian.top/Article/details/gthqakxrxv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.mhx1999.top/Article/details/gtpcpuzdlk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuxming.cn/Article/details/gtqkppwjbm.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tanke756.top/Article/details/gtmnsqpzhk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj20258.top/Article/details/gtfnujqevl.html

Go:   slices.Index(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtcseulcxp.html

Ruby: arr.index(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxgcqoymi.html

C#:   list.IndexOf(x);
来源：http://dali.fengsongda.top/Article/details/gtlpfiuinp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xuetiantiany.cn/Article/details/gtjknsctex.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenlongwang.top/Article/details/gtpnbnxfgl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.andypj.xyz/Article/details/gtweaptfcf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.daria6918.cn/Article/details/gtijqkxsor.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gaohongyu789.top/Article/details/gtdyamteyb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hysaishi.cn/Article/details/gtfluigexo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.birdmap.top/Article/details/gthoegfftm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.meibo888.top/Article/details/gtjoiepmeq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtsmaprwvy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jyoumei.cn/Article/details/gtodelrkbe.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.feifeiyinyue.top/Article/details/gtbtgfdper.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gttfympofn.html

JS:   arr.map(x => x * 2)
来源：http://dali.yj20258.top/Article/details/gtaxzluavb.html

TS:   arr.map(x => x * 2)
来源：http://dali.daria6918.cn/Article/details/gtgebsbqlk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtctxlaygg.html

Go:   // 手写循环
来源：http://dali.hnxiangtu.top/Article/details/gtrkrmuxru.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gzhubu.top/Article/details/gtlvvmzwar.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cashguo.top/Article/details/gtayzjetuh.html

[D15] 去重
来源：http://dali.ybcxt.top/Article/details/gtaxmcokvf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shuidangran.top/Article/details/gtjolxrcrw.html

PHP:  array_unique($arr);
来源：http://dali.jqgfzy.top/Article/details/gtobwvmlkf.html

JS:   [...new Set(arr)]
来源：http://dali.tian-w.cn/Article/details/gtmpkgmwkb.html

TS:   [...new Set(arr)]
来源：http://dali.sysykeji.top/Article/details/gtmcdcgqli.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xuanzx.com/Article/details/gtkxeophyw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.dashuyun.cn/Article/details/gtlhuyugzu.html

Ruby: arr.uniq
来源：http://dali.andypj.xyz/Article/details/gtopfmxqqz.html

C#:   list.Distinct().ToList()
来源：http://dali.tanke756.top/Article/details/gtpkylsbhc.html

[D16] 求和与平均值
来源：http://dali.zhengqikj.top/Article/details/gtfkabmlbn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jyoumei.cn/Article/details/gtrvhsxgvy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtkkhpibvx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fzhhl.top/Article/details/gtbcqzmjld.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuxming.cn/Article/details/gtqvdgvzxp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.chenzaomai.com/Article/details/gthjvfkmad.html

Go:   // 手写循环累加
来源：http://dali.hammf.cn/Article/details/gtynmfxqkk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzbsoqivv.html

C#:   list.Sum();  list.Average()
来源：http://dali.gotoacloud.top/Article/details/gtinkixuqe.html

[D17] 最大值与最小值
来源：http://dali.zdqjudy.top/Article/details/gtekmltrqy.html

Py:   max(arr);  min(arr)
来源：http://dali.zhengqikj.top/Article/details/gthdrasezd.html

PHP:  max($arr);  min($arr);
来源：http://dali.chenzaomai.com/Article/details/gtmwvtlxmx.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.andypj.xyz/Article/details/gtqmsbokha.html

TS:   Math.max(...arr);
来源：http://dali.ydzc1.top/Article/details/gtnvcvjvbz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gzhubu.top/Article/details/gtydzwojae.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yuxming.cn/Article/details/gtmmsugazk.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gtfrvsnrap.html

C#:   list.Max();  list.Min()
来源：http://dali.cashguo.top/Article/details/gtjqwojsfu.html

[D18] 扁平化嵌套数组
来源：http://dali.yj20258.top/Article/details/gthqqytetg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shuidangran.top/Article/details/gtipsipxnh.html

PHP:  array_merge(...$nested);
来源：http://dali.daria6918.cn/Article/details/gtmffbgfjs.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinqigufen.top/Article/details/gthpnfnwik.html

TS:   nested.flat();
来源：http://dali.cucudq.cn/Article/details/gtqyrhlzaj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtfijkcjbq.html

Go:   // 手写双层循环
来源：http://dali.hammf.cn/Article/details/gtlqrbagya.html

Ruby: nested.flatten
来源：http://dali.quarkkingdee.top/Article/details/gtuhicmazn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cucudq.cn/Article/details/gttqdbchht.html

[D19] 按字段分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfrbyripf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jianghu66.top/Article/details/gtmhpsootz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.nanxinkj.top/Article/details/gtctavysft.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjxmzwukx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nanxuanxn.top/Article/details/gttkrajgfv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ivvv.top/Article/details/gtcdxprwaf.html

Go:   // 手写 map[string][]T
来源：http://dali.xylfe.cn/Article/details/gttzixhynu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sweek.top/Article/details/gtwcycagtb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sxryk.cn/Article/details/gtnvwvbamz.html

[D20] 统计每个元素出现次数
来源：http://dali.jinqigfzy.top/Article/details/gtkifauvtl.html

Py:   Counter(arr)
来源：http://dali.sweek.top/Article/details/gtwlvafusk.html

PHP:  array_count_values($arr);
来源：http://dali.ivvv.top/Article/details/gthvacpzoz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgufenzy.top/Article/details/gtbxlvjtsp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigufen.top/Article/details/gtwfpcljct.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.svipenyu.cn/Article/details/gtmfcgckqw.html

Go:   // 手写 map[T]int
来源：http://dali.quarkkingdee.top/Article/details/gtrzvunwed.html

Ruby: arr.tally
来源：http://dali.nanxuanxn.top/Article/details/gtzycbwvmk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cashguo.top/Article/details/gtxqzmsioy.html

[D21] 判断是否包含某元素
来源：http://dali.gaohongyu789.top/Article/details/gtwbhyxwjo.html

Py:   x in arr
来源：http://dali.haohaochexian.top/Article/details/gtjmukvrms.html

PHP:  in_array($x, $arr, true);
来源：http://dali.andypj.xyz/Article/details/gtcreocznx.html

JS:   arr.includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtusfnjcgb.html

TS:   arr.includes(x)
来源：http://dali.hammf.cn/Article/details/gtxsmmirua.html

Java: list.contains(x)
来源：http://dali.ivvv.top/Article/details/gtfraygtzz.html

Go:   slices.Contains(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtepkndawc.html

Ruby: arr.include?(x)
来源：http://dali.cqqwz.cn/Article/details/gtqmcfgags.html

C#:   list.Contains(x)
来源：http://dali.havefunace.top/Article/details/gtnqjrvhzz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.snrcjt.cn/Article/details/gtzkqygzsb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtmkamxorw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.iojbl.cn/Article/details/gtfvwocscp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.fzhhl.top/Article/details/gtidczsyzf.html

TS:   [...arr];
来源：http://dali.cheryme.top/Article/details/gtuyneodsi.html

Java: new ArrayList<>(list);
来源：http://dali.dianchejie.cn/Article/details/gtpznagrug.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sxryk.cn/Article/details/gtuzuonmod.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xylfe.cn/Article/details/gthozfolap.html

C#:   new List<int>(list);
来源：http://dali.chenjidiqi.icu/Article/details/gthrjdavlx.html

[D23] reduce 累积计算
来源：http://dali.xziqi.cn/Article/details/gtkdkfahry.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cashguo.top/Article/details/gtihihpwqa.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtmskaixgb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ybcxt.top/Article/details/gtiqbfhyel.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gaohongyu789.top/Article/details/gthwmxqens.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.havefunace.top/Article/details/gtiptbajjr.html

Go:   // 手写循环
来源：http://dali.mhx1999.top/Article/details/gtqfntyqfl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zycfv.cn/Article/details/gthrqgqsux.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmhcufsb.html

[D24] 字典 / Map 基本操作
来源：http://dali.daxiang520.top/Article/details/gtohywjuxz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.feifeiyinyue.top/Article/details/gtevjnutqe.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sufxvd.cn/Article/details/gtjiamcbsu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtkclyuydv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ppjwa.cn/Article/details/gtxqcvntjy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.nanxuanxn.top/Article/details/gtpwqccxvy.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yanxiufei.cn/Article/details/gtmrsvnugv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jlsjyb.cn/Article/details/gtthebgqqt.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jlsjyb.cn/Article/details/gtadqqrcsl.html

[D25] Set 集合去重与交并差
来源：http://dali.zhoulong.xyz/Article/details/gtaswqrhuu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gaohongyu789.top/Article/details/gtyaccrbty.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.svipenyu.cn/Article/details/gtarmiegnk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtctjgqbol.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.fengsongda.top/Article/details/gtrglqahyt.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gzhubu.top/Article/details/gtyxhjruaa.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ppjwa.cn/Article/details/gtyphkzyvd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jyoumei.cn/Article/details/gtsgevtdoz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yuanzhike.top/Article/details/gtudyeaetp.html

[D26] 数组转字符串
来源：http://dali.dianchejie.cn/Article/details/gtlwwtbdmb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.feifeiyinyue.top/Article/details/gtvlawqzzk.html

PHP:  implode(", ", $arr);
来源：http://dali.svipenyu.cn/Article/details/gtawemyylz.html

JS:   arr.join(", ")
来源：http://dali.hysaishi.cn/Article/details/gtydhjbszo.html

TS:   arr.join(", ")
来源：http://dali.aizwys.cn/Article/details/gtkqnpkiwn.html

Java: String.join(", ", list)
来源：http://dali.zhengqikj.top/Article/details/gtnfpapxqn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jyoumei.cn/Article/details/gtincqqrme.html

Ruby: arr.join(", ")
来源：http://dali.ydzc1.top/Article/details/gtwdbhoijx.html

C#:   string.Join(", ", list)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlwsgltln.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtyxkhyckn.html

E. 字符串处理
来源：http://dali.yongpay.top/Article/details/gtmibvacng.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtqgwujdiw.html

[E01] 拼接字符串
来源：http://dali.bjfxy.top/Article/details/gtwdivscsx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.meibo888.top/Article/details/gtscqlnbaj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shangyingyoupin.top/Article/details/gtjebgkdlj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.havefunace.top/Article/details/gtcforpcff.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jqgfzy.top/Article/details/gtefqcgleq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhixingplan.top/Article/details/gtbnghsbam.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.nanxuanxn.top/Article/details/gtzrbrbold.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hongshengwenyu.top/Article/details/gtqfvcckbx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.316326.xyz/Article/details/gtnuntuoxf.html

[E02] 重复字符串
来源：http://dali.316326.xyz/Article/details/gtfbazhyyx.html

Py:   "ab" * 3
来源：http://dali.nanxuanxn.top/Article/details/gtugsaqkzn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtpdgbsgmn.html

JS:   "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gtpxklsuew.html

TS:   "ab".repeat(3)
来源：http://dali.ivvv.top/Article/details/gtijybdcfe.html

Java: "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gtdebnbyug.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrvblytgw.html

Ruby: "ab" * 3
来源：http://dali.smart0.xyz/Article/details/gthrmwqgvx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cheryme.top/Article/details/gtleopqapc.html

[E03] 截取子串
来源：http://dali.mhx1999.top/Article/details/gtsvxklgbq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gaohongyu789.top/Article/details/gtngaifqis.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gtlxejmwrm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.tianlin.xyz/Article/details/gtwcdihggx.html

TS:   s.slice(1, 4)
来源：http://dali.tianlin.xyz/Article/details/gtbkexgirp.html

Java: s.substring(1, 4)
来源：http://dali.ydzc1.top/Article/details/gtcwybnfsj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gotoacloud.top/Article/details/gthuvghmsp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gotoacloud.top/Article/details/gtfxpwrzvj.html

C#:   s.Substring(1, 3)
来源：http://dali.chenlongwang.top/Article/details/gtptdbkmgi.html

[E04] 查找子串位置
来源：http://dali.zhoulong.xyz/Article/details/gtcaapwzvf.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbcscjvrn.html

PHP:  strpos($s, "x");
来源：http://dali.xuanzx.com/Article/details/gtgyfdflnk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hnxiangtu.top/Article/details/gtnbgggcdq.html

TS:   s.indexOf("x")
来源：http://dali.redwolf501.top/Article/details/gtbvqcxheb.html

Java: s.indexOf("x")
来源：http://dali.yj202588.top/Article/details/gttdrhuomk.html

Go:   strings.Index(s, "x")
来源：http://dali.nwbrower.top/Article/details/gtkanthyrm.html

Ruby: s.index("x")
来源：http://dali.chenjidiqi.icu/Article/details/gthjnpoogv.html

C#:   s.IndexOf("x")
来源：http://dali.xylfe.cn/Article/details/gtezqjczrv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ywan-chungtsiang.top/Article/details/gtohwtjvsi.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cdnleiting.top/Article/details/gtllrwdcbk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.andypj.xyz/Article/details/gtztisrsxa.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ppjwa.cn/Article/details/gtwpesbwws.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.316326.xyz/Article/details/gtrtfoptom.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jyoumei.cn/Article/details/gtpwhhpoih.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jlsjyb.cn/Article/details/gtksiedbez.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ydzc1.top/Article/details/gthsqnupek.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.0kj1m.cn/Article/details/gtqrpmypbh.html

[E06] 替换子串
来源：http://dali.wangdashe.top/Article/details/gtmqpjkvwl.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yj20258.top/Article/details/gtjfjniqgz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrenmclkd.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtedxulcde.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gtlgxjighj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtuayaiaac.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtpsffxydj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yuxming.cn/Article/details/gttzdlsedv.html

C#:   s.Replace("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtsuohnuxg.html

[E07] 按分隔符拆分
来源：http://dali.sweek.top/Article/details/gtqsfzkvql.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cucudq.cn/Article/details/gtpyczlppz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hywenlv.cn/Article/details/gtdwfpxhkx.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqgyolurx.html

TS:   s.split(",")
来源：http://dali.ivvv.top/Article/details/gtvxubmbed.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.nanxuanxn.top/Article/details/gtthdesjqt.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ydzc1.top/Article/details/gtwqonbfdp.html

Ruby: s.split(",");  s.split
来源：http://dali.yonumen.top/Article/details/gtaurtrxjq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ybcxt.top/Article/details/gtzeiyurrj.html

[E08] 数组按分隔符合并
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgvqaiwiw.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gtnzquvvth.html

PHP:  implode(",", $items);
来源：http://dali.xylfe.cn/Article/details/gtipyvltpe.html

JS:   items.join(",")
来源：http://dali.ivvv.top/Article/details/gtjzgtcpab.html

TS:   items.join(",")
来源：http://dali.sweek.top/Article/details/gteknzazqq.html

Java: String.join(",", items)
来源：http://dali.zhengqikj.top/Article/details/gtjpvdfjjx.html

Go:   strings.Join(items, ",")
来源：http://dali.xinyue.icu/Article/details/gteruqntot.html

Ruby: items.join(",")
来源：http://dali.guowangkeji.top/Article/details/gtnlsacqxd.html

C#:   string.Join(",", items)
来源：http://dali.cheryme.top/Article/details/gtldqlsadx.html

[E09] 去除所有空白字符
来源：http://dali.jqgfzy.top/Article/details/gtkqrfnzyo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.redwolf501.top/Article/details/gtyfwhmpkn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cdnleiting.top/Article/details/gtmrhiezot.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cashguo.top/Article/details/gtzgkduyzy.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigufen.top/Article/details/gtynmiwcft.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.chenzaomai.com/Article/details/gtglzrjijc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.haohaochexian.top/Article/details/gtgxcilmqt.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.tanke756.top/Article/details/gtqqzkhlag.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.pycfn.com/Article/details/gtfqpfmgob.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yonumen.top/Article/details/gtqsmiqlsq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xylfe.cn/Article/details/gtupgcdyea.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yongpay.top/Article/details/gtfnkcfkkc.html

JS:   "7".padStart(3, "0")
来源：http://dali.aizwys.cn/Article/details/gtiugwvany.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gtdvnwanov.html

Java: String.format("%03d", 7)
来源：http://dali.gaohongyu789.top/Article/details/gtknlwomwo.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gtggpfdzia.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gtuqyurlkp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj20258888.top/Article/details/gtccghghfx.html

[E11] 反转字符串
来源：http://dali.wangdashe.top/Article/details/gtdhikfvxn.html

Py:   s[::-1]
来源：http://dali.yanxiufei.cn/Article/details/gtaqjqcewz.html

PHP:  strrev($s);
来源：http://dali.hammf.cn/Article/details/gtvsjdhsog.html

JS:   [...s].reverse().join("")
来源：http://dali.sysykeji.top/Article/details/gtpwyoions.html

TS:   [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gticpzclhe.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.c1oappe.top/Article/details/gtbdleoupo.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yvedp.cn/Article/details/gtnbzxdvkq.html

Ruby: s.reverse
来源：http://dali.yuxming.cn/Article/details/gtiujzhrcf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.bjfxy.top/Article/details/gtjpzennge.html

[E12] 统计某字符出现次数
来源：http://dali.jinqigfzy.top/Article/details/gtlyvjldpi.html

Py:   s.count("a")
来源：http://dali.zhongyouzk.top/Article/details/gtgpxfyhgz.html

PHP:  substr_count($s, "a");
来源：http://dali.birdmap.top/Article/details/gtptjylsng.html

JS:   s.split("a").length - 1
来源：http://dali.gzhubu.top/Article/details/gtsumtcmor.html

TS:   s.split("a").length - 1
来源：http://dali.zhixingplan.top/Article/details/gtqmesofsl.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.guannengcc.top/Article/details/gttfggdkxs.html

Go:   strings.Count(s, "a")
来源：http://dali.jqgfzy.top/Article/details/gtsbdjbvms.html

Ruby: s.count("a")
来源：http://dali.9152youxi.cn/Article/details/gtqfotzvik.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gtpdthnuci.html

[E13] 逐字符遍历
来源：http://dali.yj20258888.top/Article/details/gtlxsgsocb.html

Py:   for ch in s: print(ch)
来源：http://dali.bjfxy.top/Article/details/gttmdpqdzv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yvedp.cn/Article/details/gtzhjebupl.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jianghu66.top/Article/details/gtxrliiurp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfltxeut.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sweek.top/Article/details/gtrigzxhar.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.fzhhl.top/Article/details/gtcfhxzuuh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cqqwz.cn/Article/details/gtfkufdqxu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gtbwalzkgd.html


<!-- 参考信息 -->