代发 wailian999

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yj202588.top/Article/details/gtbzynbfps.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jlsjyb.cn/Article/details/gtezczsxfe.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnxiangtu.top/Article/details/gtharituob.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.svipenyu.cn/Article/details/gtchrhpcvo.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.chenzaomai.com/Article/details/gtjnoairdh.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shuidangran.top/Article/details/gtwnbcsxcp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.c1oappe.top/Article/details/gtdyhcjouw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yonumen.top/Article/details/gtwtlaowib.html

[D11] 反转数组
来源：http://dali.bjfxy.top/Article/details/gtgsoslvcb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cheryme.top/Article/details/gtszohianj.html

PHP:  array_reverse($arr);
来源：http://dali.yj202588.top/Article/details/gtjmsikpbl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.fzhhl.top/Article/details/gtvteboand.html

TS:   [...arr].reverse();
来源：http://dali.zhongyouzk.top/Article/details/gtpclaaqxq.html

Java: Collections.reverse(list);
来源：http://dali.tanke756.top/Article/details/gtalqzjwhn.html

Go:   slices.Reverse(arr)
来源：http://dali.yuanzhike.top/Article/details/gtsbevkqis.html

Ruby: arr.reverse
来源：http://dali.xuanzx.com/Article/details/gtsrnrlxpt.html

C#:   list.Reverse();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxykpgxnk.html

[D12] 查找元素下标
来源：http://dali.guannengcc.top/Article/details/gtgghqxdut.html

Py:   arr.index(x);  x in arr
来源：http://dali.zycfv.cn/Article/details/gtufioxpvh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zdqjudy.top/Article/details/gtzazjqoqp.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aizwys.cn/Article/details/gtrgmivrch.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jiagoushi.top/Article/details/gtdnowapyp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yangfankeji.com/Article/details/gtagiolyvs.html

Go:   slices.Index(arr, x)
来源：http://dali.316326.xyz/Article/details/gtpxzijedx.html

Ruby: arr.index(x)
来源：http://dali.tanke756.top/Article/details/gtumjdfnhr.html

C#:   list.IndexOf(x);
来源：http://dali.nanxinkj.top/Article/details/gtybivdggb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xziqi.cn/Article/details/gteqcuycrd.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cheryme.top/Article/details/gtgwosnkom.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.feifeiyinyue.top/Article/details/gthaiatbkb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hnqzz.top/Article/details/gthbyfqicb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.smart0.xyz/Article/details/gtyxooocjd.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.redwolf501.top/Article/details/gtucfelnrt.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yangfankeji.com/Article/details/gtcblfchsc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwdcumodm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtmcgelugg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.fengsongda.top/Article/details/gtvvaeaqcs.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.pengpengdd.cyou/Article/details/gtnpvaqkhr.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jiagoushi.top/Article/details/gtdwcyqpif.html

JS:   arr.map(x => x * 2)
来源：http://dali.chenzaomai.com/Article/details/gtovgigaqn.html

TS:   arr.map(x => x * 2)
来源：http://dali.yvedp.cn/Article/details/gttpcsmqeb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xinyue.icu/Article/details/gtdjxzmkew.html

Go:   // 手写循环
来源：http://dali.yj20258888.top/Article/details/gtqsjpxqzh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtqzozkixr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sysykeji.top/Article/details/gtndhfxbfw.html

[D15] 去重
来源：http://dali.yuanzhike.top/Article/details/gtqcxggdem.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.meibo888.top/Article/details/gtoxmvfubf.html

PHP:  array_unique($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtujjdmnjx.html

JS:   [...new Set(arr)]
来源：http://dali.ybcxt.top/Article/details/gtbzqoepiu.html

TS:   [...new Set(arr)]
来源：http://dali.dianchejie.cn/Article/details/gtbxcuvgmv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shangyingyoupin.top/Article/details/gtbcqwcdeb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.redwolf501.top/Article/details/gtyqazadls.html

Ruby: arr.uniq
来源：http://dali.daria6918.cn/Article/details/gtyrtycbve.html

C#:   list.Distinct().ToList()
来源：http://dali.wangdashe.top/Article/details/gtlawfybdq.html

[D16] 求和与平均值
来源：http://dali.bjfxy.top/Article/details/gtlxlsisqg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.fzhhl.top/Article/details/gtyirorylg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtdswodnaa.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuxming.cn/Article/details/gtpyavcmtw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgfzy.top/Article/details/gtgdpuvwaq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.guowangkeji.top/Article/details/gtyammrhxn.html

Go:   // 手写循环累加
来源：http://dali.fzhhl.top/Article/details/gtozvgxxvt.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hnqzz.top/Article/details/gtsxoqddtk.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhixingplan.top/Article/details/gtxxxjacnb.html

[D17] 最大值与最小值
来源：http://dali.chenjidiqi.icu/Article/details/gteyjqhaau.html

Py:   max(arr);  min(arr)
来源：http://dali.iojbl.cn/Article/details/gtjkqdxvhd.html

PHP:  max($arr);  min($arr);
来源：http://dali.xuanzx.com/Article/details/gtkrxedzkn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gaohongyu789.top/Article/details/gtukphssqs.html

TS:   Math.max(...arr);
来源：http://dali.xziqi.cn/Article/details/gtcbcymxqa.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yangfankeji.com/Article/details/gtccarrdjd.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.pycfn.com/Article/details/gtdoomrijl.html

Ruby: arr.max;  arr.min
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaccjsmvh.html

C#:   list.Max();  list.Min()
来源：http://dali.haohaochexian.top/Article/details/gtlzcmesod.html

[D18] 扁平化嵌套数组
来源：http://dali.svipenyu.cn/Article/details/gtuzkbrkqa.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.guowangkeji.top/Article/details/gtumfbkchc.html

PHP:  array_merge(...$nested);
来源：http://dali.xuetiantiany.cn/Article/details/gtbspbwbes.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.meibo888.top/Article/details/gthlpseyvh.html

TS:   nested.flat();
来源：http://dali.316326.xyz/Article/details/gtbntfadoa.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.nanxuanxn.top/Article/details/gtrvdkowsf.html

Go:   // 手写双层循环
来源：http://dali.birdmap.top/Article/details/gtuwafdhkb.html

Ruby: nested.flatten
来源：http://dali.vqdsnc.cn/Article/details/gtfwvlwlfx.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yvedp.cn/Article/details/gtxhhzxnbz.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gttrexnblt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtodbpbkuj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gtkxkrpjlw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.wangdashe.top/Article/details/gtgqzgtoju.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jqgufenzy.top/Article/details/gtnbitmrto.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jlsjyb.cn/Article/details/gtcqcshfbh.html

Go:   // 手写 map[string][]T
来源：http://dali.quarkkingdee.top/Article/details/gtarhqxlww.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hnqzz.top/Article/details/gtrwdjfdha.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yuxming.cn/Article/details/gtqmsqwzyv.html

[D20] 统计每个元素出现次数
来源：http://dali.yuxming.cn/Article/details/gtzahwlyup.html

Py:   Counter(arr)
来源：http://dali.hfpthk.cn/Article/details/gtyyzfubiv.html

PHP:  array_count_values($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtcdqdtqks.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ppjwa.cn/Article/details/gtuulixiww.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yvedp.cn/Article/details/gtzhbgspgu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shzxlz.cn/Article/details/gttsxmpwca.html

Go:   // 手写 map[T]int
来源：http://dali.fzhhl.top/Article/details/gtphpclvtu.html

Ruby: arr.tally
来源：http://dali.sxryk.cn/Article/details/gtwtkuccfe.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.quarkkingdee.top/Article/details/gtcfzkiybr.html

[D21] 判断是否包含某元素
来源：http://dali.dashuyun.cn/Article/details/gtkekxbifw.html

Py:   x in arr
来源：http://dali.xuetiantiany.cn/Article/details/gtpjkggxyk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.pengpengdd.cyou/Article/details/gtjrqqnqdg.html

JS:   arr.includes(x)
来源：http://dali.yuanzhike.top/Article/details/gtlfvcpfmi.html

TS:   arr.includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gtstnoegpq.html

Java: list.contains(x)
来源：http://dali.zhixingplan.top/Article/details/gtbjnwfezk.html

Go:   slices.Contains(arr, x)
来源：http://dali.havefunace.top/Article/details/gtjcpsipti.html

Ruby: arr.include?(x)
来源：http://dali.dianchejie.cn/Article/details/gtodpanplb.html

C#:   list.Contains(x)
来源：http://dali.zycfv.cn/Article/details/gtrltcximo.html

[D22] 复制数组（避免共享引用）
来源：http://dali.snrcjt.cn/Article/details/gtezttxhgu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yuanzhike.top/Article/details/gtmrzcndrn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yueranfly.top/Article/details/gtslswvlsm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.fengsongda.top/Article/details/gtzeowekfj.html

TS:   [...arr];
来源：http://dali.ppjwa.cn/Article/details/gtotgsprcj.html

Java: new ArrayList<>(list);
来源：http://dali.smart0.xyz/Article/details/gtjmaohyyy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cdnleiting.top/Article/details/gtwbvtuber.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gaohongyu789.top/Article/details/gttgnhtefg.html

C#:   new List<int>(list);
来源：http://dali.pengpengdd.cyou/Article/details/gtwdrgvodi.html

[D23] reduce 累积计算
来源：http://dali.guannengcc.top/Article/details/gtwxigdiav.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sweek.top/Article/details/gtvilwtmhe.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xuanzx.com/Article/details/gtrhxrjzba.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cucudq.cn/Article/details/gtiekxclbl.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.snrcjt.cn/Article/details/gtpreoyjdu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gtvtoqcfjg.html

Go:   // 手写循环
来源：http://dali.feifeiyinyue.top/Article/details/gtkusznjcx.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.dashuyun.cn/Article/details/gtuoetvuep.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.9152youxi.cn/Article/details/gtdlgixiye.html

[D24] 字典 / Map 基本操作
来源：http://dali.guowangkeji.top/Article/details/gtgakgzoeo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gogol.net.cn/Article/details/gtfxsojuyq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.fengsongda.top/Article/details/gtlxxdwgki.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yvedp.cn/Article/details/gtehmqjgdl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yj202588.top/Article/details/gtvjhblgko.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tanke756.top/Article/details/gtggbyxcyh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zycfv.cn/Article/details/gtvbysmnpf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yanxiufei.cn/Article/details/gtxnsadvdf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cucudq.cn/Article/details/gtgbawfnut.html

[D25] Set 集合去重与交并差
来源：http://dali.jianghu66.top/Article/details/gtzxjitbtj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.chenzaomai.com/Article/details/gtrgzclspc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zdqjudy.top/Article/details/gtaewvbzci.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.guowangkeji.top/Article/details/gtzguqxehi.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yongpay.top/Article/details/gtkfzuwjkq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jiagoushi.top/Article/details/gteschnxtd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gzhubu.top/Article/details/gtfwrphfot.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yvedp.cn/Article/details/gtwpcywgqz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tianlin.xyz/Article/details/gtlrnqglqe.html

[D26] 数组转字符串
来源：http://dali.hfpthk.cn/Article/details/gtcgzmtwuk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yangfankeji.com/Article/details/gthtbfrdao.html

PHP:  implode(", ", $arr);
来源：http://dali.yuanzhike.top/Article/details/gtsntucykd.html

JS:   arr.join(", ")
来源：http://dali.chenjidiqi.icu/Article/details/gtuwaqnxnx.html

TS:   arr.join(", ")
来源：http://dali.zhengqikj.top/Article/details/gtheirpzfr.html

Java: String.join(", ", list)
来源：http://dali.andypj.xyz/Article/details/gtjcmlytum.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jiagoushi.top/Article/details/gttjcfmvxe.html

Ruby: arr.join(", ")
来源：http://dali.birdmap.top/Article/details/gtvmqkupkz.html

C#:   string.Join(", ", list)
来源：http://dali.vqdsnc.cn/Article/details/gttwrfkjex.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtyqvwixzv.html

E. 字符串处理
来源：http://dali.zhiwuduotai.top/Article/details/gtxccoanib.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtbgpzicgs.html

[E01] 拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gtlnzqlxzz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.tanke756.top/Article/details/gtiriluest.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sysykeji.top/Article/details/gtvkreqjbx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jyoumei.cn/Article/details/gtjvmphspt.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.smart0.xyz/Article/details/gtywrpywhi.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.andypj.xyz/Article/details/gtprffpkrj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.c1oappe.top/Article/details/gtxdxjjwjo.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sxryk.cn/Article/details/gtvyrlgmqs.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtduvlgfql.html

[E02] 重复字符串
来源：http://dali.redwolf501.top/Article/details/gtvjunjwkt.html

Py:   "ab" * 3
来源：http://dali.pycfn.com/Article/details/gtxttgcchr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cheryme.top/Article/details/gtuzlydore.html

JS:   "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gtltgjxjly.html

TS:   "ab".repeat(3)
来源：http://dali.aizwys.cn/Article/details/gtxojlqrdr.html

Java: "ab".repeat(3)
来源：http://dali.mhx1999.top/Article/details/gtwjmxyrcq.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhixingplan.top/Article/details/gtyvkzseuq.html

Ruby: "ab" * 3
来源：http://dali.hnxiangtu.top/Article/details/gtfirabxji.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hnqzz.top/Article/details/gtsvbwvgta.html

[E03] 截取子串
来源：http://dali.zhixingplan.top/Article/details/gtnancxssd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.snrcjt.cn/Article/details/gtwxdizhwu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gtngmfiudo.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yangfankeji.com/Article/details/gtogfsbbrh.html

TS:   s.slice(1, 4)
来源：http://dali.ydzc1.top/Article/details/gtgasvdvvo.html

Java: s.substring(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gtqvkvkxfm.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hysaishi.cn/Article/details/gtldrxtbbe.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hongshengwenyu.top/Article/details/gtwftddrvm.html

C#:   s.Substring(1, 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtgwyyizce.html

[E04] 查找子串位置
来源：http://dali.hnxiangtu.top/Article/details/gtmrseiuum.html

Py:   s.find("x");  s.index("x")
来源：http://dali.aibaodan.cn/Article/details/gtxkaahjyu.html

PHP:  strpos($s, "x");
来源：http://dali.yj20258.top/Article/details/gtwahhlfon.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hfpthk.cn/Article/details/gtdaxuxbfi.html

TS:   s.indexOf("x")
来源：http://dali.yj20258.top/Article/details/gtmxdrqoti.html

Java: s.indexOf("x")
来源：http://dali.yj20258888.top/Article/details/gtxvgqccnb.html

Go:   strings.Index(s, "x")
来源：http://dali.sxryk.cn/Article/details/gtuwlhopbc.html

Ruby: s.index("x")
来源：http://dali.shuidangran.top/Article/details/gtidwowrhx.html

C#:   s.IndexOf("x")
来源：http://dali.snrcjt.cn/Article/details/gtsbkejako.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hammf.cn/Article/details/gtimgvwxbr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ivvv.top/Article/details/gtisosrsxt.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhengqikj.top/Article/details/gtxgdowdjh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gtichseexc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.c1oappe.top/Article/details/gtnuyolswn.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258.top/Article/details/gtqsoiklon.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.gotoacloud.top/Article/details/gtbckbybeg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.316326.xyz/Article/details/gtwjsccrfa.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtznuiiuuv.html

[E06] 替换子串
来源：http://dali.sxryk.cn/Article/details/gtasyjwkwo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhongyouzk.top/Article/details/gtazxlbjxa.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtqeukzpox.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtigxmczwd.html

TS:   s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtrjdqtvic.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gtukbcefnz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yangfankeji.com/Article/details/gtmbwuerqr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gtzmobxpuq.html

C#:   s.Replace("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtfcbwfqoh.html

[E07] 按分隔符拆分
来源：http://dali.birdmap.top/Article/details/gtfchmcayq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zdqjudy.top/Article/details/gtvwdjfrvz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtmkphdxrx.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.pengpengdd.cyou/Article/details/gtflnffnpo.html

TS:   s.split(",")
来源：http://dali.c1oappe.top/Article/details/gtzerdypyr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhongyouzk.top/Article/details/gtprpmrbxt.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtacfarsgs.html

Ruby: s.split(",");  s.split
来源：http://dali.guowangkeji.top/Article/details/gtitpceaxh.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.nanxuanxn.top/Article/details/gtjuumuodh.html

[E08] 数组按分隔符合并
来源：http://dali.yueranfly.top/Article/details/gtyojzenhr.html

Py:   ",".join(items)
来源：http://dali.haohaochexian.top/Article/details/gtxcdwptik.html

PHP:  implode(",", $items);
来源：http://dali.yongpay.top/Article/details/gtfaiyrxkq.html

JS:   items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gtypopncff.html

TS:   items.join(",")
来源：http://dali.yanxiufei.cn/Article/details/gtkzmkbqfn.html

Java: String.join(",", items)
来源：http://dali.wangdashe.top/Article/details/gtjzcwtloh.html

Go:   strings.Join(items, ",")
来源：http://dali.jiagoushi.top/Article/details/gtprinbcvm.html

Ruby: items.join(",")
来源：http://dali.cqqwz.cn/Article/details/gtclrdssxe.html

C#:   string.Join(",", items)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnktxzebv.html

[E09] 去除所有空白字符
来源：http://dali.nanxuanxn.top/Article/details/gtqwxalzou.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zdqjudy.top/Article/details/gttpkmverq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.havefunace.top/Article/details/gtcqonlypc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xziqi.cn/Article/details/gtecbollpw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.smart0.xyz/Article/details/gtbiewurcm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.tianlin.xyz/Article/details/gtqtiuhjkw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jyoumei.cn/Article/details/gtyhepegby.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenjidiqi.icu/Article/details/gthlxdrrgn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gogol.net.cn/Article/details/gtegqasjhq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ydzc1.top/Article/details/gtkbfgvpxo.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gtjruinqkk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sysykeji.top/Article/details/gtxlithniu.html

JS:   "7".padStart(3, "0")
来源：http://dali.xinyue.icu/Article/details/gtpqzppius.html

TS:   "7".padStart(3, "0")
来源：http://dali.xziqi.cn/Article/details/gtkljwujcl.html

Java: String.format("%03d", 7)
来源：http://dali.meibo888.top/Article/details/gtcsrrcazq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gtfrijqklu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sweek.top/Article/details/gtzmwbhcgs.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.fzhhl.top/Article/details/gtsoyyaulk.html

[E11] 反转字符串
来源：http://dali.xinyue.icu/Article/details/gtckbzvywb.html

Py:   s[::-1]
来源：http://dali.svipenyu.cn/Article/details/gtwcrfybgy.html

PHP:  strrev($s);
来源：http://dali.sysykeji.top/Article/details/gtejezqlpc.html

JS:   [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gtsrllzveo.html

TS:   [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gtfcxwhveb.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hammf.cn/Article/details/gtunvzudxn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yuanzhike.top/Article/details/gtoyyzoohe.html

Ruby: s.reverse
来源：http://dali.dianchejie.cn/Article/details/gtzxeynska.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj202588.top/Article/details/gtriefuimr.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gtxlkikmyj.html

Py:   s.count("a")
来源：http://dali.sufxvd.cn/Article/details/gtwgshubjb.html

PHP:  substr_count($s, "a");
来源：http://dali.shuidangran.top/Article/details/gtriiotwar.html

JS:   s.split("a").length - 1
来源：http://dali.yueranfly.top/Article/details/gtzhscsfln.html

TS:   s.split("a").length - 1
来源：http://dali.yj20258888.top/Article/details/gtzbehqpac.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtezeumubm.html

Go:   strings.Count(s, "a")
来源：http://dali.nanxuanxn.top/Article/details/gtiargrrvm.html

Ruby: s.count("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxlbzsuew.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ehwqpu.com/Article/details/gtxuhhipre.html

[E13] 逐字符遍历
来源：http://dali.cashguo.top/Article/details/gttjyzakqv.html

Py:   for ch in s: print(ch)
来源：http://dali.fengsongda.top/Article/details/gtqfrlplij.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtialgcrcm.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.iojbl.cn/Article/details/gtwbydvneq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzuregosh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.aizwys.cn/Article/details/gtcilhlfyt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cheryme.top/Article/details/gtkhucpken.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.316326.xyz/Article/details/gtyvkqjeou.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ydzc1.top/Article/details/gtbirkltxn.html

[E14] URL 编码与 Base64
来源：http://dali.pengpengdd.cyou/Article/details/gtejgbuzyc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cucudq.cn/Article/details/gtkocgilnt.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.svipenyu.cn/Article/details/gtdartnrub.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gzhubu.top/Article/details/gtbotgzfqu.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shuidangran.top/Article/details/gtyfuoinpk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.fzhhl.top/Article/details/gttedrnkco.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhixingplan.top/Article/details/gtbmpvjxrd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nwbrower.top/Article/details/gtzaaeioxw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yvedp.cn/Article/details/gtgtiuzxdg.html

[E15] HTML 转义 / 反转义
来源：http://dali.svipenyu.cn/Article/details/gtabjchfvq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.c1oappe.top/Article/details/gtuucnycrz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.c1oappe.top/Article/details/gtfmsbhgti.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.tanke756.top/Article/details/gtjdbuzmfu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jianghu66.top/Article/details/gtemdbvvhn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.smart0.xyz/Article/details/gtofmizrfn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cdnleiting.top/Article/details/gtpcculdkm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.redwolf501.top/Article/details/gtwbnxuprh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shzxlz.cn/Article/details/gtbtyjmzaw.html

[E16] 数字千分位
来源：http://dali.wangshuangyany.cn/Article/details/gtoakhzglz.html

Py:   f"{1234567:,}"
来源：http://dali.gogol.net.cn/Article/details/gthtzeipad.html

PHP:  number_format(1234567);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfyaiuexj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jlsjyb.cn/Article/details/gtopsrjkkh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cashguo.top/Article/details/gtaujcmmfp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhengqikj.top/Article/details/gtenjhslyr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shangyingyoupin.top/Article/details/gtorsxljns.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cashguo.top/Article/details/gtrfjxdvwp.html

C#:   1234567.ToString("N0")
来源：http://dali.dianchejie.cn/Article/details/gthdevvthw.html

[E17] 首字母大写
来源：http://dali.shanyushiyangkeji.top/Article/details/gtodunmozp.html


<!-- 参考信息 -->