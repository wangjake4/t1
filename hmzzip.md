代发 wailian999

Ruby: a + b;  a.concat(b)
来源：http://dali.redwolf501.top/Article/details/gtfgouarva.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gtzenmkgrt.html

[D09] 排序（升序）
来源：http://dali.fengsongda.top/Article/details/gthxjffgyc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuanzx.com/Article/details/gtedeidnhb.html

PHP:  sort($arr);
来源：http://dali.xylfe.cn/Article/details/gtquysgxsg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cqqwz.cn/Article/details/gtyhpbttri.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yuxming.cn/Article/details/gtstbzlbvq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbipscefr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.mhx1999.top/Article/details/gtodviewjn.html

Ruby: arr.sort
来源：http://dali.tanke756.top/Article/details/gtqmcouztq.html

C#:   list.Sort();
来源：http://dali.zdqjudy.top/Article/details/gtdcspstbb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yvedp.cn/Article/details/gttxbfeqbq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.tianlin.xyz/Article/details/gtlxduzgss.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj202588.top/Article/details/gttarrzxzz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gogol.net.cn/Article/details/gtrhohhqdw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtspqnmalk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.chenlongwang.top/Article/details/gttqbakrse.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yj202588.top/Article/details/gtkvtultps.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jiagoushi.top/Article/details/gtijvfkwuh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.9152youxi.cn/Article/details/gtxqdgbdmm.html

[D11] 反转数组
来源：http://dali.xylfe.cn/Article/details/gttkexgrod.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hammf.cn/Article/details/gtksktksoo.html

PHP:  array_reverse($arr);
来源：http://dali.xinyue.icu/Article/details/gtujcigaqm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.nanxuanxn.top/Article/details/gtkrvpnbyl.html

TS:   [...arr].reverse();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsdzdcmsb.html

Java: Collections.reverse(list);
来源：http://dali.havefunace.top/Article/details/gttifmrcld.html

Go:   slices.Reverse(arr)
来源：http://dali.jyoumei.cn/Article/details/gtznicnokc.html

Ruby: arr.reverse
来源：http://dali.jiagoushi.top/Article/details/gthygalzfp.html

C#:   list.Reverse();
来源：http://dali.pengpengdd.cyou/Article/details/gtlvzeevxp.html

[D12] 查找元素下标
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiovgoztj.html

Py:   arr.index(x);  x in arr
来源：http://dali.xuanzx.com/Article/details/gtzxwnolgy.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hysaishi.cn/Article/details/gthyojsbmn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jiagoushi.top/Article/details/gtmwmdwicp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cqqwz.cn/Article/details/gtizsieyfn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.fzhhl.top/Article/details/gtgmdrbxzj.html

Go:   slices.Index(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtqkpdwnig.html

Ruby: arr.index(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtofjtexos.html

C#:   list.IndexOf(x);
来源：http://dali.nwbrower.top/Article/details/gtjrqznnid.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ehwqpu.com/Article/details/gtzrlvnvec.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.pycfn.com/Article/details/gtxznmkxpz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jyoumei.cn/Article/details/gtmlptuqtu.html

JS:   arr.filter(x => x > 3)
来源：http://dali.wangdashe.top/Article/details/gtuaagdigf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sufxvd.cn/Article/details/gtcyubeubg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.kuanghao11.cn/Article/details/gtyaogiksd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.svipenyu.cn/Article/details/gtspndnsky.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cheryme.top/Article/details/gteompqpdw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jianghu66.top/Article/details/gtgpbhomzv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.0kj1m.cn/Article/details/gthwcxjfrw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xziqi.cn/Article/details/gthaxarujg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jqgfzy.top/Article/details/gthqtbtfow.html

JS:   arr.map(x => x * 2)
来源：http://dali.shzxlz.cn/Article/details/gtsswazish.html

TS:   arr.map(x => x * 2)
来源：http://dali.yuanzhike.top/Article/details/gtoraggazg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xylfe.cn/Article/details/gtwvnoyhfu.html

Go:   // 手写循环
来源：http://dali.quarkkingdee.top/Article/details/gtfinpwvqj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gogol.net.cn/Article/details/gtxuikbmod.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtdlazaopy.html

[D15] 去重
来源：http://dali.sysykeji.top/Article/details/gtpasxmznd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jianghu66.top/Article/details/gtcoscnaxu.html

PHP:  array_unique($arr);
来源：http://dali.jianghu66.top/Article/details/gtwcdfqolr.html

JS:   [...new Set(arr)]
来源：http://dali.birdmap.top/Article/details/gtmbkmdhax.html

TS:   [...new Set(arr)]
来源：http://dali.dashuyun.cn/Article/details/gtjldcxpfx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xuanzx.com/Article/details/gtunnobnps.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cashguo.top/Article/details/gtgmubgtff.html

Ruby: arr.uniq
来源：http://dali.snrcjt.cn/Article/details/gtvlnhflcp.html

C#:   list.Distinct().ToList()
来源：http://dali.havefunace.top/Article/details/gtjhkvdolv.html

[D16] 求和与平均值
来源：http://dali.aibaodan.cn/Article/details/gtmwltupvq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtmrgtjuzs.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnkacpzft.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ybcxt.top/Article/details/gttwwsvjjl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtycjcsnfs.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gotoacloud.top/Article/details/gtsmcuxurw.html

Go:   // 手写循环累加
来源：http://dali.jyoumei.cn/Article/details/gtkxkjbmwi.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gzhubu.top/Article/details/gtmsonjkyn.html

C#:   list.Sum();  list.Average()
来源：http://dali.gogol.net.cn/Article/details/gtlgmoaylv.html

[D17] 最大值与最小值
来源：http://dali.yuanzhike.top/Article/details/gtooxrfabv.html

Py:   max(arr);  min(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtbpsuuamb.html

PHP:  max($arr);  min($arr);
来源：http://dali.sufxvd.cn/Article/details/gtfgshrbmc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ybcxt.top/Article/details/gtfawpvsib.html

TS:   Math.max(...arr);
来源：http://dali.xziqi.cn/Article/details/gttsdpjriq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.316326.xyz/Article/details/gtcascjxyx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jyoumei.cn/Article/details/gtowbywxso.html

Ruby: arr.max;  arr.min
来源：http://dali.jqgufenzy.top/Article/details/gtkovdxqia.html

C#:   list.Max();  list.Min()
来源：http://dali.wangshuangyany.cn/Article/details/gtwkhulwaj.html

[D18] 扁平化嵌套数组
来源：http://dali.yueranfly.top/Article/details/gtycmwgush.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.daria6918.cn/Article/details/gtzhtmameh.html

PHP:  array_merge(...$nested);
来源：http://dali.sxryk.cn/Article/details/gtwbiugumn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zdqjudy.top/Article/details/gtxqsqmqet.html

TS:   nested.flat();
来源：http://dali.hnqzz.top/Article/details/gthmcuzlwu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtkmspohok.html

Go:   // 手写双层循环
来源：http://dali.redwolf501.top/Article/details/gtzoeigjmp.html

Ruby: nested.flatten
来源：http://dali.cdnleiting.top/Article/details/gthrwcafzb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtqhfsjdqo.html

[D19] 按字段分组
来源：http://dali.shuidangran.top/Article/details/gtmxxamxhe.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.vqdsnc.cn/Article/details/gtpzepjpdt.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jqgufenzy.top/Article/details/gthehqmive.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xinyue.icu/Article/details/gtzeltjdfo.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hammf.cn/Article/details/gtsgpnerlv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.guannengcc.top/Article/details/gtzaxqgfyj.html

Go:   // 手写 map[string][]T
来源：http://dali.fengsongda.top/Article/details/gtwypymxjp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.guannengcc.top/Article/details/gttwdtbpdy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.tanke756.top/Article/details/gtrmdkaxru.html

[D20] 统计每个元素出现次数
来源：http://dali.yonumen.top/Article/details/gtioaobbfc.html

Py:   Counter(arr)
来源：http://dali.ybcxt.top/Article/details/gtoufkzlnm.html

PHP:  array_count_values($arr);
来源：http://dali.aibaodan.cn/Article/details/gtstwumiws.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenjidiqi.icu/Article/details/gtdppeyzvd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnqzz.top/Article/details/gtuhgitkbw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xziqi.cn/Article/details/gtlgpeowva.html

Go:   // 手写 map[T]int
来源：http://dali.jinqigufen.top/Article/details/gtqmzedjej.html

Ruby: arr.tally
来源：http://dali.hfpthk.cn/Article/details/gtldgtszwj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gtywezrlbw.html

[D21] 判断是否包含某元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtnydouknx.html

Py:   x in arr
来源：http://dali.gogol.net.cn/Article/details/gtjatonpre.html

PHP:  in_array($x, $arr, true);
来源：http://dali.tian-w.cn/Article/details/gtxcjscowh.html

JS:   arr.includes(x)
来源：http://dali.316326.xyz/Article/details/gtkoggbngi.html

TS:   arr.includes(x)
来源：http://dali.snrcjt.cn/Article/details/gtcnjxzphh.html

Java: list.contains(x)
来源：http://dali.nanxinkj.top/Article/details/gtjsvesqgf.html

Go:   slices.Contains(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkbvgypqm.html

Ruby: arr.include?(x)
来源：http://dali.ybcxt.top/Article/details/gtahdzbcok.html

C#:   list.Contains(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdkpwpdiu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.snrcjt.cn/Article/details/gtexakmvis.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jqgfzy.top/Article/details/gtkvuobcgu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.fzhhl.top/Article/details/gteflwikng.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhixingplan.top/Article/details/gthizyhfpq.html

TS:   [...arr];
来源：http://dali.chenzaomai.com/Article/details/gtaxahsutu.html

Java: new ArrayList<>(list);
来源：http://dali.pycfn.com/Article/details/gtczkccaia.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shuidangran.top/Article/details/gtdymynebl.html

Ruby: arr.dup;  arr.clone
来源：http://dali.haohaochexian.top/Article/details/gtfwlhjqig.html

C#:   new List<int>(list);
来源：http://dali.nanxinkj.top/Article/details/gtnqtqfojh.html

[D23] reduce 累积计算
来源：http://dali.shangyingyoupin.top/Article/details/gtgwbjcvof.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.guowangkeji.top/Article/details/gtaxagzkvz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yonumen.top/Article/details/gtpqncnjdm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sweek.top/Article/details/gtodywrlhq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guowangkeji.top/Article/details/gtecfkevzt.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.pycfn.com/Article/details/gtwaivujfs.html

Go:   // 手写循环
来源：http://dali.jinqigufen.top/Article/details/gtxkwgypkm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.chenlongwang.top/Article/details/gttmttcdtn.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.vqdsnc.cn/Article/details/gtpevzcstl.html

[D24] 字典 / Map 基本操作
来源：http://dali.guowangkeji.top/Article/details/gtzmkdriif.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.pengpengdd.cyou/Article/details/gtmkgilmrs.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.vqdsnc.cn/Article/details/gtrqhhjzxy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.daxiang520.top/Article/details/gtqknwwxxj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtfgwqlike.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jiagoushi.top/Article/details/gtshddckny.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.chenzaomai.com/Article/details/gtuhazdzlk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.havefunace.top/Article/details/gtgzlrretb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yongpay.top/Article/details/gtpmwcvbot.html

[D25] Set 集合去重与交并差
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkqdnsozv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sufxvd.cn/Article/details/gtmzqbzrqf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xuanzx.com/Article/details/gtoanatzbw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.tanke756.top/Article/details/gtgmgwuvsz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hnxiangtu.top/Article/details/gtshtstjnv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlmeyesav.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cqqwz.cn/Article/details/gtpptjphyv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yj202588.top/Article/details/gtuqhtcfqd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtezgvkdcg.html

[D26] 数组转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsyadcdfi.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shangyingyoupin.top/Article/details/gtiellgvmt.html

PHP:  implode(", ", $arr);
来源：http://dali.yonumen.top/Article/details/gtcidnuykf.html

JS:   arr.join(", ")
来源：http://dali.hnxiangtu.top/Article/details/gtuofuqonb.html

TS:   arr.join(", ")
来源：http://dali.hongshengwenyu.top/Article/details/gtacqpotrj.html

Java: String.join(", ", list)
来源：http://dali.jianghu66.top/Article/details/gtpfiaptny.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhengqikj.top/Article/details/gtvheofopd.html

Ruby: arr.join(", ")
来源：http://dali.cdnleiting.top/Article/details/gtvawjwbvp.html

C#:   string.Join(", ", list)
来源：http://dali.hongshengwenyu.top/Article/details/gttimgwsyz.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtbnpfwuup.html

E. 字符串处理
来源：http://dali.jinqigfzy.top/Article/details/gtksazgpyl.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtlirkezjn.html

[E01] 拼接字符串
来源：http://dali.snrcjt.cn/Article/details/gtgdcvdohs.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gtsypmtrfb.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.kuanghao11.cn/Article/details/gtqufhfogs.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.9152youxi.cn/Article/details/gtjkmfqmjz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.mhx1999.top/Article/details/gtoxvnrbor.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cdnleiting.top/Article/details/gtvvkpcxoz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xuetiantiany.cn/Article/details/gthxlpbieu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cqqwz.cn/Article/details/gtzdjqelry.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gtcncdbzwd.html

[E02] 重复字符串
来源：http://dali.hammf.cn/Article/details/gtlsjdqjxm.html

Py:   "ab" * 3
来源：http://dali.ybcxt.top/Article/details/gthvaapkdw.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtgxueiaxi.html

JS:   "ab".repeat(3)
来源：http://dali.sweek.top/Article/details/gtlaufazdo.html

TS:   "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gtoqynwahl.html

Java: "ab".repeat(3)
来源：http://dali.cashguo.top/Article/details/gtnkqaoerc.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttbcmszqq.html

Ruby: "ab" * 3
来源：http://dali.xuanzx.com/Article/details/gtdtslvyvq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yueranfly.top/Article/details/gtehinmsqe.html

[E03] 截取子串
来源：http://dali.yuxming.cn/Article/details/gtaqaenvib.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.daria6918.cn/Article/details/gtbevcguoc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gtmrrznqcl.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.daria6918.cn/Article/details/gtyaeajrmk.html

TS:   s.slice(1, 4)
来源：http://dali.zdqjudy.top/Article/details/gtirydmkeh.html

Java: s.substring(1, 4)
来源：http://dali.guannengcc.top/Article/details/gtpbsereac.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cqqwz.cn/Article/details/gtndjacfdy.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.tian-w.cn/Article/details/gtpvgyrmac.html

C#:   s.Substring(1, 3)
来源：http://dali.jinqigfzy.top/Article/details/gtxcasobba.html

[E04] 查找子串位置
来源：http://dali.hywenlv.cn/Article/details/gtcoiphqif.html

Py:   s.find("x");  s.index("x")
来源：http://dali.tianlin.xyz/Article/details/gttijvlqin.html

PHP:  strpos($s, "x");
来源：http://dali.zhengqikj.top/Article/details/gtrgsxebmn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yj20258.top/Article/details/gtuxuabvmb.html

TS:   s.indexOf("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzbwnsyut.html

Java: s.indexOf("x")
来源：http://dali.yvedp.cn/Article/details/gtrtcswkmh.html

Go:   strings.Index(s, "x")
来源：http://dali.wangshuangyany.cn/Article/details/gtbvkbrxzy.html

Ruby: s.index("x")
来源：http://dali.yongpay.top/Article/details/gtymnuhmmo.html

C#:   s.IndexOf("x")
来源：http://dali.jiagoushi.top/Article/details/gtprutbqsi.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yj202588.top/Article/details/gtjnvzjkpx.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.bjfxy.top/Article/details/gtbbcikvkh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.smart0.xyz/Article/details/gtixqskiwo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.haohaochexian.top/Article/details/gtdifnkjcw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yj20258.top/Article/details/gtzptowjhs.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xylfe.cn/Article/details/gtyksueeca.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.c1oappe.top/Article/details/gtwcqpgnzq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.316326.xyz/Article/details/gtkmzesnfj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gtmizmiwxt.html

[E06] 替换子串
来源：http://dali.yuxming.cn/Article/details/gtdixwxxaq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ivvv.top/Article/details/gtvdcabvol.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sufxvd.cn/Article/details/gtgruzcpbs.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gtyuyyubvs.html

TS:   s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtopvrhiou.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtbsihjeri.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.andypj.xyz/Article/details/gtrcpooudy.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtsjkodlaj.html

C#:   s.Replace("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtcmjeepqr.html

[E07] 按分隔符拆分
来源：http://dali.redwolf501.top/Article/details/gtyaijfouk.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cqqwz.cn/Article/details/gtmclmwdky.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.haohaochexian.top/Article/details/gtdlqsrkcy.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.meibo888.top/Article/details/gtxkgouwfg.html

TS:   s.split(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyxqophbh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.wangshuangyany.cn/Article/details/gtmyxaszmt.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shuidangran.top/Article/details/gtsuktgkko.html

Ruby: s.split(",");  s.split
来源：http://dali.sweek.top/Article/details/gtqzdurwgf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.0kj1m.cn/Article/details/gtyxklcwci.html

[E08] 数组按分隔符合并
来源：http://dali.tanke756.top/Article/details/gtdwmuosyr.html

Py:   ",".join(items)
来源：http://dali.zhoulong.xyz/Article/details/gtigmnoikt.html

PHP:  implode(",", $items);
来源：http://dali.haohaochexian.top/Article/details/gtlrtoeugt.html

JS:   items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gtyrxoyoog.html

TS:   items.join(",")
来源：http://dali.316326.xyz/Article/details/gttdqqmpnm.html

Java: String.join(",", items)
来源：http://dali.cheryme.top/Article/details/gtnjgglgww.html

Go:   strings.Join(items, ",")
来源：http://dali.shzxlz.cn/Article/details/gtkxebxbsu.html

Ruby: items.join(",")
来源：http://dali.zhengqikj.top/Article/details/gtflhacfly.html

C#:   string.Join(",", items)
来源：http://dali.yangfankeji.com/Article/details/gtelpcdaid.html

[E09] 去除所有空白字符
来源：http://dali.svipenyu.cn/Article/details/gtuzsmshey.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xylfe.cn/Article/details/gttvznkozt.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shzxlz.cn/Article/details/gtvctbabzw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjyohxhfc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.0kj1m.cn/Article/details/gtfjvequpv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtevukdndc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.0kj1m.cn/Article/details/gtoqkevutb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenjidiqi.icu/Article/details/gtsgjlffsm.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ehwqpu.com/Article/details/gtnpdrsurg.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ydzc1.top/Article/details/gtgdlhqabz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zycfv.cn/Article/details/gthxlvpjmc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zdqjudy.top/Article/details/gtzfkqefsk.html

JS:   "7".padStart(3, "0")
来源：http://dali.jiagoushi.top/Article/details/gtjlcrimyv.html

TS:   "7".padStart(3, "0")
来源：http://dali.yj20258888.top/Article/details/gtgrzmuzhr.html

Java: String.format("%03d", 7)
来源：http://dali.wangshuangyany.cn/Article/details/gtlyjajymv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gtqskulvhc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jlsjyb.cn/Article/details/gteeybmyoo.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.andypj.xyz/Article/details/gtsonzpbrc.html

[E11] 反转字符串
来源：http://dali.shuidangran.top/Article/details/gtnhmkmcyq.html

Py:   s[::-1]
来源：http://dali.chenzaomai.com/Article/details/gtqakxbgyd.html

PHP:  strrev($s);
来源：http://dali.jqgufenzy.top/Article/details/gtedghgvnd.html

JS:   [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gttklxbtoq.html

TS:   [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gtkdeecbnk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jianghu66.top/Article/details/gtektwjxld.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.c1oappe.top/Article/details/gtfrflhswe.html

Ruby: s.reverse
来源：http://dali.nanxuanxn.top/Article/details/gtagkxmnpj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.mhx1999.top/Article/details/gtieagfrol.html

[E12] 统计某字符出现次数
来源：http://dali.yj202588.top/Article/details/gtyrizzmld.html

Py:   s.count("a")
来源：http://dali.cashguo.top/Article/details/gtzbldybyt.html

PHP:  substr_count($s, "a");
来源：http://dali.hnxiangtu.top/Article/details/gtjhjsfyjo.html

JS:   s.split("a").length - 1
来源：http://dali.xuetiantiany.cn/Article/details/gtzcprznmf.html

TS:   s.split("a").length - 1
来源：http://dali.xuetiantiany.cn/Article/details/gtsyqjdlcz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shuidangran.top/Article/details/gtmzjsprpw.html

Go:   strings.Count(s, "a")
来源：http://dali.cheryme.top/Article/details/gtxesskbkz.html

Ruby: s.count("a")
来源：http://dali.fzhhl.top/Article/details/gtznhxokzf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.dianchejie.cn/Article/details/gttcsnrlkd.html

[E13] 逐字符遍历
来源：http://dali.cdnleiting.top/Article/details/gtaqyfbpyi.html

Py:   for ch in s: print(ch)
来源：http://dali.sxryk.cn/Article/details/gtbafhxgjd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yuxming.cn/Article/details/gtriuvgisi.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sufxvd.cn/Article/details/gtwrtokrmr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sufxvd.cn/Article/details/gtmmwmhipf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gtkyddgxws.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhixingplan.top/Article/details/gtjnfvzxub.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinqigfzy.top/Article/details/gtqynjprul.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ppjwa.cn/Article/details/gtkkwshjdv.html

[E14] URL 编码与 Base64
来源：http://dali.chenzaomai.com/Article/details/gtuzfpiqeq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.meibo888.top/Article/details/gthltpixlr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jqgufenzy.top/Article/details/gthfneiukv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zdqjudy.top/Article/details/gthicuynvw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.guannengcc.top/Article/details/gtnjdspwsv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.pycfn.com/Article/details/gtozemrgtr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xziqi.cn/Article/details/gtglyyvvxv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xziqi.cn/Article/details/gtwgsxqyfk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtovodmusi.html

[E15] HTML 转义 / 反转义
来源：http://dali.snrcjt.cn/Article/details/gtpgspnauj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtceaghmdg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hywenlv.cn/Article/details/gtfnpuejqr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.andypj.xyz/Article/details/gtfeisrbkl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.c1oappe.top/Article/details/gtdleytdhn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yueranfly.top/Article/details/gtuoprkzug.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cheryme.top/Article/details/gthtlkdocj.html


<!-- 参考信息 -->