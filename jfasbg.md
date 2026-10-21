代发 wailian999

TS:   arr.slice(1, 4);
来源：http://dali.aizwys.cn/Article/details/gtocxnkwgl.html

Java: list.subList(1, 4);
来源：http://dali.sweek.top/Article/details/gtzcqefiuo.html

Go:   arr[1:4]
来源：http://dali.jinghuilouyu.cn/Article/details/gtffvmjwvi.html

Ruby: arr[1, 3]
来源：http://dali.xuetiantiany.cn/Article/details/gtnajbisva.html

C#:   list.GetRange(1, 3);
来源：http://dali.quarkkingdee.top/Article/details/gthllqozjy.html

[D08] 合并两个数组
来源：http://dali.jianghu66.top/Article/details/gtxszdpazb.html

Py:   a + b;  a.extend(b)
来源：http://dali.yj202588.top/Article/details/gttwongaty.html

PHP:  array_merge($a, $b);
来源：http://dali.0kj1m.cn/Article/details/gtghcufdhg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.pengpengdd.cyou/Article/details/gtxamjsydc.html

TS:   [...a, ...b];
来源：http://dali.0kj1m.cn/Article/details/gtzteqsavm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hammf.cn/Article/details/gtqichnmoc.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gtzypnenex.html

Ruby: a + b;  a.concat(b)
来源：http://dali.chenjidiqi.icu/Article/details/gthzxiaaoc.html

C#:   a.Concat(b).ToList()
来源：http://dali.c1oappe.top/Article/details/gtdwqgkoto.html

[D09] 排序（升序）
来源：http://dali.ehwqpu.com/Article/details/gtnuvrknac.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtncgjqcky.html

PHP:  sort($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtvztqnunc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.tianlin.xyz/Article/details/gtcuxkgknx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yj20258.top/Article/details/gtnacbsyae.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shuidangran.top/Article/details/gtijgqoneq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.dianchejie.cn/Article/details/gtavxdbwcc.html

Ruby: arr.sort
来源：http://dali.wangdashe.top/Article/details/gtsyurmene.html

C#:   list.Sort();
来源：http://dali.hnxiangtu.top/Article/details/gtfvuuxdze.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhongyouzk.top/Article/details/gtikmqazxm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sweek.top/Article/details/gtpvzukjns.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ehwqpu.com/Article/details/gtbetpdzjk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xinyue.icu/Article/details/gtsrtdynhj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tianlin.xyz/Article/details/gtiwzhfkrd.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinghuilouyu.cn/Article/details/gtimunjllc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yj20258888.top/Article/details/gtbdeqfxtl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.wangdashe.top/Article/details/gtbemieyof.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jianghu66.top/Article/details/gtlcmfdcfb.html

[D11] 反转数组
来源：http://dali.hywenlv.cn/Article/details/gtegloczfk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cucudq.cn/Article/details/gtpediebkx.html

PHP:  array_reverse($arr);
来源：http://dali.shzxlz.cn/Article/details/gtavjfqxcx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yueranfly.top/Article/details/gtkwkiyfpd.html

TS:   [...arr].reverse();
来源：http://dali.cashguo.top/Article/details/gtlviuilci.html

Java: Collections.reverse(list);
来源：http://dali.kuanghao11.cn/Article/details/gtkklxzssd.html

Go:   slices.Reverse(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtmttkarop.html

Ruby: arr.reverse
来源：http://dali.nanxuanxn.top/Article/details/gtonhqcteq.html

C#:   list.Reverse();
来源：http://dali.hysaishi.cn/Article/details/gtxsqhncbv.html

[D12] 查找元素下标
来源：http://dali.hysaishi.cn/Article/details/gtiwgfchgx.html

Py:   arr.index(x);  x in arr
来源：http://dali.fzhhl.top/Article/details/gtdpstytbo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yangfankeji.com/Article/details/gtrfikihqt.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cheryme.top/Article/details/gtnhcyagat.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.kuanghao11.cn/Article/details/gtdwvpihaj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jqgfzy.top/Article/details/gtvrudisne.html

Go:   slices.Index(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtlmeoajdc.html

Ruby: arr.index(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlahgkhhi.html

C#:   list.IndexOf(x);
来源：http://dali.pengpengdd.cyou/Article/details/gtxbqpeveg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yj20258.top/Article/details/gtgynbspwi.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.andypj.xyz/Article/details/gtpbjukwlu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shzxlz.cn/Article/details/gtxdcgnepu.html

JS:   arr.filter(x => x > 3)
来源：http://dali.snrcjt.cn/Article/details/gtgguquhwa.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shuidangran.top/Article/details/gtcwqzmrnt.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sysykeji.top/Article/details/gthsaxagyf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.havefunace.top/Article/details/gtidqtnlqc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yvedp.cn/Article/details/gtzvgpsyja.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtrlcepdjk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hfpthk.cn/Article/details/gthhpoxigf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinqigufen.top/Article/details/gtoguwybgc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhongyouzk.top/Article/details/gtzgghqtfb.html

JS:   arr.map(x => x * 2)
来源：http://dali.yangfankeji.com/Article/details/gtboclfhje.html

TS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqcbdekhr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ydzc1.top/Article/details/gttrmqpctc.html

Go:   // 手写循环
来源：http://dali.nwbrower.top/Article/details/gtesyatgxn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xziqi.cn/Article/details/gtixcenyhu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yangfankeji.com/Article/details/gtmjctyhrk.html

[D15] 去重
来源：http://dali.mhx1999.top/Article/details/gtkdmjhkfo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.dianchejie.cn/Article/details/gtflvuxzyk.html

PHP:  array_unique($arr);
来源：http://dali.cdnleiting.top/Article/details/gtwaylwpzy.html

JS:   [...new Set(arr)]
来源：http://dali.ppjwa.cn/Article/details/gtmmdfaehn.html

TS:   [...new Set(arr)]
来源：http://dali.kuanghao11.cn/Article/details/gtmfvumymc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhaomingkeji.xyz/Article/details/gthczmtpkj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzcxxicbt.html

Ruby: arr.uniq
来源：http://dali.andypj.xyz/Article/details/gtrpxiuzse.html

C#:   list.Distinct().ToList()
来源：http://dali.ivvv.top/Article/details/gtiwhpnroi.html

[D16] 求和与平均值
来源：http://dali.yuanzhike.top/Article/details/gtllwtgsro.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenzaomai.com/Article/details/gtcllbuvos.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cashguo.top/Article/details/gtgnghqssz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhixingplan.top/Article/details/gtrgqjxfvk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtzzxlmuyd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.feifeiyinyue.top/Article/details/gtfsvnyjrk.html

Go:   // 手写循环累加
来源：http://dali.daria6918.cn/Article/details/gtjtpxglfy.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.quarkkingdee.top/Article/details/gtpdixtxbm.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenlongwang.top/Article/details/gtoiomxbrz.html

[D17] 最大值与最小值
来源：http://dali.pycfn.com/Article/details/gtihmddhpo.html

Py:   max(arr);  min(arr)
来源：http://dali.birdmap.top/Article/details/gtvjlwrswj.html

PHP:  max($arr);  min($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtokekllgl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.meibo888.top/Article/details/gtlmwpcktv.html

TS:   Math.max(...arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjnseages.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ydzc1.top/Article/details/gtmefmvdtm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.guannengcc.top/Article/details/gthkjxtttt.html

Ruby: arr.max;  arr.min
来源：http://dali.yj20258888.top/Article/details/gtfkeqznxb.html

C#:   list.Max();  list.Min()
来源：http://dali.aibaodan.cn/Article/details/gtifxalnhj.html

[D18] 扁平化嵌套数组
来源：http://dali.nanxuanxn.top/Article/details/gtdizqdsqt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hysaishi.cn/Article/details/gthtlwdnmu.html

PHP:  array_merge(...$nested);
来源：http://dali.zhengqikj.top/Article/details/gtvvgntuyz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yj20258888.top/Article/details/gtmivjmjzu.html

TS:   nested.flat();
来源：http://dali.yuanzhike.top/Article/details/gtowomksaq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.aibaodan.cn/Article/details/gtslsktocp.html

Go:   // 手写双层循环
来源：http://dali.hywenlv.cn/Article/details/gtwtjrfwon.html

Ruby: nested.flatten
来源：http://dali.yj202588.top/Article/details/gtjwtyrdwe.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtehvwcrhl.html

[D19] 按字段分组
来源：http://dali.gogol.net.cn/Article/details/gtfxectlqv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hysaishi.cn/Article/details/gtaxfxgljs.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gzhubu.top/Article/details/gtewlulxhw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.wangdashe.top/Article/details/gtjculhomu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xinyue.icu/Article/details/gtbgepxtfv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.pengpengdd.cyou/Article/details/gtjwdtodrc.html

Go:   // 手写 map[string][]T
来源：http://dali.guannengcc.top/Article/details/gtsfvbkrty.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hnxiangtu.top/Article/details/gtheizpbgm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ehwqpu.com/Article/details/gtogjyqipw.html

[D20] 统计每个元素出现次数
来源：http://dali.xinyue.icu/Article/details/gtkbncxjmm.html

Py:   Counter(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtxdnldppw.html

PHP:  array_count_values($arr);
来源：http://dali.c1oappe.top/Article/details/gtkxfoaxpc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgfzy.top/Article/details/gtocjnsklp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.havefunace.top/Article/details/gttgxmnfak.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cucudq.cn/Article/details/gtbvngvkkb.html

Go:   // 手写 map[T]int
来源：http://dali.ivvv.top/Article/details/gtungetrsg.html

Ruby: arr.tally
来源：http://dali.yuxming.cn/Article/details/gtefsiigzv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhongyouzk.top/Article/details/gtfjnpfhji.html

[D21] 判断是否包含某元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmerddwoc.html

Py:   x in arr
来源：http://dali.svipenyu.cn/Article/details/gtxaootmhr.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthlfrnyvn.html

JS:   arr.includes(x)
来源：http://dali.aizwys.cn/Article/details/gtrmbvlajr.html

TS:   arr.includes(x)
来源：http://dali.tanke756.top/Article/details/gtenehjxei.html

Java: list.contains(x)
来源：http://dali.316326.xyz/Article/details/gtawaznmhq.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gteurzjavu.html

Ruby: arr.include?(x)
来源：http://dali.tian-w.cn/Article/details/gtfzoqgetw.html

C#:   list.Contains(x)
来源：http://dali.snrcjt.cn/Article/details/gtvmpzyeap.html

[D22] 复制数组（避免共享引用）
来源：http://dali.aibaodan.cn/Article/details/gtytutnetd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.meibo888.top/Article/details/gticnofmsh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.pengpengdd.cyou/Article/details/gtleejsqig.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.andypj.xyz/Article/details/gtxrabansk.html

TS:   [...arr];
来源：http://dali.birdmap.top/Article/details/gtkiokzvyq.html

Java: new ArrayList<>(list);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbqmxpaax.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gteekiipkd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.wangshuangyany.cn/Article/details/gtqevlkgdq.html

C#:   new List<int>(list);
来源：http://dali.shangyingyoupin.top/Article/details/gtnjnalczy.html

[D23] reduce 累积计算
来源：http://dali.hnxiangtu.top/Article/details/gtulvnhsnp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhoulong.xyz/Article/details/gthlpmpqsp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hywenlv.cn/Article/details/gtlfjhpsnf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cucudq.cn/Article/details/gthgkfubde.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shuidangran.top/Article/details/gtsnaumsxt.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.pycfn.com/Article/details/gtftlxwftf.html

Go:   // 手写循环
来源：http://dali.zhongyouzk.top/Article/details/gthzdkpszz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.chenjidiqi.icu/Article/details/gtyvsewqml.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhengqikj.top/Article/details/gttgsnmwwg.html

[D24] 字典 / Map 基本操作
来源：http://dali.yueranfly.top/Article/details/gtxhzcohyj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.nanxinkj.top/Article/details/gtlbdzhjum.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.vqdsnc.cn/Article/details/gtjqsbkmnz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.guannengcc.top/Article/details/gtpximmaic.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yj20258888.top/Article/details/gtintijrbq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvblypukg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.fengsongda.top/Article/details/gtmfvjcxvm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.dashuyun.cn/Article/details/gtgwtcvnim.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.guannengcc.top/Article/details/gtrozyzvzw.html

[D25] Set 集合去重与交并差
来源：http://dali.hysaishi.cn/Article/details/gtmvjtbkry.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tanke756.top/Article/details/gtibblkdgi.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinghuilouyu.cn/Article/details/gtibdbkxks.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jyoumei.cn/Article/details/gtylpngdvu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.birdmap.top/Article/details/gtzygkaibr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tian-w.cn/Article/details/gtvjfoqfsf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jqgfzy.top/Article/details/gtnojpijjs.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.aizwys.cn/Article/details/gtnpabjksb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtyvmfldnk.html

[D26] 数组转字符串
来源：http://dali.gaohongyu789.top/Article/details/gtikkuwmtf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.dianchejie.cn/Article/details/gtslghsgma.html

PHP:  implode(", ", $arr);
来源：http://dali.jqgufenzy.top/Article/details/gtoockunlm.html

JS:   arr.join(", ")
来源：http://dali.0kj1m.cn/Article/details/gtcjxfutqe.html

TS:   arr.join(", ")
来源：http://dali.guowangkeji.top/Article/details/gtuuayxahs.html

Java: String.join(", ", list)
来源：http://dali.jlsjyb.cn/Article/details/gtaaeyrppa.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hfpthk.cn/Article/details/gtvcdphuys.html

Ruby: arr.join(", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttmxlcmxv.html

C#:   string.Join(", ", list)
来源：http://dali.nanxuanxn.top/Article/details/gtigsnsrpi.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtocsptryv.html

E. 字符串处理
来源：http://dali.cucudq.cn/Article/details/gtjmeakbzv.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtmazphrgp.html

[E01] 拼接字符串
来源：http://dali.smart0.xyz/Article/details/gtuvksyyib.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.kuanghao11.cn/Article/details/gtmiywfvck.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sweek.top/Article/details/gtadsujplr.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hammf.cn/Article/details/gtdcojrsgg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gogol.net.cn/Article/details/gtkjnhwdqt.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jyoumei.cn/Article/details/gthvdxoxzv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenjidiqi.icu/Article/details/gtdwwnyebl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cheryme.top/Article/details/gtcrjhztmf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gticeutpsz.html

[E02] 重复字符串
来源：http://dali.aibaodan.cn/Article/details/gtodnkjxvo.html

Py:   "ab" * 3
来源：http://dali.sxryk.cn/Article/details/gtbkahxcjf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zycfv.cn/Article/details/gtzhgectsg.html

JS:   "ab".repeat(3)
来源：http://dali.tianlin.xyz/Article/details/gtioknqhno.html

TS:   "ab".repeat(3)
来源：http://dali.jlsjyb.cn/Article/details/gtmaghlcui.html

Java: "ab".repeat(3)
来源：http://dali.xuanzx.com/Article/details/gthwgdmtji.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ehwqpu.com/Article/details/gtvhcyuytw.html

Ruby: "ab" * 3
来源：http://dali.xylfe.cn/Article/details/gtshcbsmrs.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.feifeiyinyue.top/Article/details/gtcniejipq.html

[E03] 截取子串
来源：http://dali.kuanghao11.cn/Article/details/gtxhrnwydk.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmnhpszhx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gteblwfeaq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.vqdsnc.cn/Article/details/gtrkgyddei.html

TS:   s.slice(1, 4)
来源：http://dali.cheryme.top/Article/details/gtjytiafdu.html

Java: s.substring(1, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdsdxsigy.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ywan-chungtsiang.top/Article/details/gteothsrfi.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.vqdsnc.cn/Article/details/gtcrjrcmow.html

C#:   s.Substring(1, 3)
来源：http://dali.iojbl.cn/Article/details/gttaserbld.html

[E04] 查找子串位置
来源：http://dali.hfpthk.cn/Article/details/gtdzjnekye.html

Py:   s.find("x");  s.index("x")
来源：http://dali.quarkkingdee.top/Article/details/gtzlfaonys.html

PHP:  strpos($s, "x");
来源：http://dali.gogol.net.cn/Article/details/gtxytduesf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.iojbl.cn/Article/details/gtohoaqpkg.html

TS:   s.indexOf("x")
来源：http://dali.haohaochexian.top/Article/details/gtuagxsqzt.html

Java: s.indexOf("x")
来源：http://dali.xinyue.icu/Article/details/gtjpadfskh.html

Go:   strings.Index(s, "x")
来源：http://dali.gaohongyu789.top/Article/details/gtwxeaefjz.html

Ruby: s.index("x")
来源：http://dali.gogol.net.cn/Article/details/gttmbnkrpu.html

C#:   s.IndexOf("x")
来源：http://dali.shangyingyoupin.top/Article/details/gtjdivtyaf.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hywenlv.cn/Article/details/gtdterfmna.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jyoumei.cn/Article/details/gtiaeymodk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jqgfzy.top/Article/details/gtqmjymnfd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cucudq.cn/Article/details/gtmctqomdg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ybcxt.top/Article/details/gtkvtozzeh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtekjnqnry.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cheryme.top/Article/details/gtqbqaaklz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.guannengcc.top/Article/details/gthpdmxrwg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yonumen.top/Article/details/gtydwlxfda.html

[E06] 替换子串
来源：http://dali.quarkkingdee.top/Article/details/gtzfsfoich.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhixingplan.top/Article/details/gtaqasbaai.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj20258888.top/Article/details/gtxuovtnzv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtxegmvjdk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtldigwfiu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtamiqoioe.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtugyyebcx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtdewlydhp.html

C#:   s.Replace("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtzionlohp.html

[E07] 按分隔符拆分
来源：http://dali.jqgfzy.top/Article/details/gtncnbjnul.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jqgfzy.top/Article/details/gttlpliwca.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tian-w.cn/Article/details/gtforlkqjn.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ehwqpu.com/Article/details/gtyndrvnxk.html

TS:   s.split(",")
来源：http://dali.svipenyu.cn/Article/details/gtplwvdnnv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ybcxt.top/Article/details/gtfryhxxhk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ivvv.top/Article/details/gtjfawaylv.html

Ruby: s.split(",");  s.split
来源：http://dali.pycfn.com/Article/details/gtckhdutde.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmnjytktq.html

[E08] 数组按分隔符合并
来源：http://dali.svipenyu.cn/Article/details/gtteuenzkn.html

Py:   ",".join(items)
来源：http://dali.zhongyouzk.top/Article/details/gtztxgdydk.html

PHP:  implode(",", $items);
来源：http://dali.dianchejie.cn/Article/details/gteszgujhr.html

JS:   items.join(",")
来源：http://dali.shangyingyoupin.top/Article/details/gtdzejtawv.html

TS:   items.join(",")
来源：http://dali.birdmap.top/Article/details/gtyfimgram.html

Java: String.join(",", items)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjnopwlep.html

Go:   strings.Join(items, ",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmsbjbdxk.html

Ruby: items.join(",")
来源：http://dali.jianghu66.top/Article/details/gtsravlkwv.html

C#:   string.Join(",", items)
来源：http://dali.aizwys.cn/Article/details/gtmxkbeybp.html

[E09] 去除所有空白字符
来源：http://dali.gzhubu.top/Article/details/gtbjfvdfrs.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sufxvd.cn/Article/details/gtrtrzcibn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cdnleiting.top/Article/details/gtwspnupaz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.iojbl.cn/Article/details/gtxhuwjvtz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tianlin.xyz/Article/details/gtjwihhwnd.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jiagoushi.top/Article/details/gttvrawold.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpyjmvhdl.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ivvv.top/Article/details/gtueooxejt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.chenlongwang.top/Article/details/gtrqcjhzkg.html

[E10] 左侧补零 / 定长填充
来源：http://dali.vqdsnc.cn/Article/details/gtrxhdwwsl.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hnqzz.top/Article/details/gtxfbuaheq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.9152youxi.cn/Article/details/gtbodvrdzn.html

JS:   "7".padStart(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gtlunapuzb.html

TS:   "7".padStart(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gtapumwqxr.html

Java: String.format("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gtjqfqaegb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gtsethgwiy.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttvbiurnf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yvedp.cn/Article/details/gtdnftwiwe.html

[E11] 反转字符串
来源：http://dali.sufxvd.cn/Article/details/gtpfyetngx.html

Py:   s[::-1]
来源：http://dali.pengpengdd.cyou/Article/details/gtxzmvrqtu.html

PHP:  strrev($s);
来源：http://dali.zdqjudy.top/Article/details/gtpmiulayc.html

JS:   [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gtefywuefc.html

TS:   [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gtkycqnwbn.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.svipenyu.cn/Article/details/gtdwuxebhn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ydzc1.top/Article/details/gtvqpobcuk.html

Ruby: s.reverse
来源：http://dali.jqgfzy.top/Article/details/gtqjsyxrhr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cqqwz.cn/Article/details/gtuvgnvycx.html

[E12] 统计某字符出现次数
来源：http://dali.svipenyu.cn/Article/details/gtodnvesap.html

Py:   s.count("a")
来源：http://dali.chenlongwang.top/Article/details/gtzzwhradw.html

PHP:  substr_count($s, "a");
来源：http://dali.zycfv.cn/Article/details/gtpeyzszgp.html

JS:   s.split("a").length - 1
来源：http://dali.mhx1999.top/Article/details/gtzhalpelz.html

TS:   s.split("a").length - 1
来源：http://dali.iojbl.cn/Article/details/gtbfcljxve.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yonumen.top/Article/details/gtnmxdcgjz.html

Go:   strings.Count(s, "a")
来源：http://dali.zhiwuduotai.top/Article/details/gtldvdofwu.html

Ruby: s.count("a")
来源：http://dali.hnxiangtu.top/Article/details/gttuxiaidj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hammf.cn/Article/details/gtbluhppac.html

[E13] 逐字符遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtfblfderg.html

Py:   for ch in s: print(ch)
来源：http://dali.chenjidiqi.icu/Article/details/gteqhadlqs.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cqqwz.cn/Article/details/gtzgvbrnko.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangdashe.top/Article/details/gtecktyreq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigufen.top/Article/details/gtkcxhjlwd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gtadtusjqd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenlongwang.top/Article/details/gtrqexbxyb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvwmxbbtf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hywenlv.cn/Article/details/gtijeyjlna.html

[E14] URL 编码与 Base64
来源：http://dali.cdnleiting.top/Article/details/gtexonbvlq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinqigfzy.top/Article/details/gtestqzdwq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nwbrower.top/Article/details/gteqreiiff.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.vqdsnc.cn/Article/details/gtgfsidsvq.html


<!-- 参考信息 -->