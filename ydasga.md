代发 wailian999

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.dashuyun.cn/Article/details/gtaygvmaou.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhengqikj.top/Article/details/gtleqzvsdp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.svipenyu.cn/Article/details/gtwjvouggj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.wangdashe.top/Article/details/gtqelqxbhf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shuidangran.top/Article/details/gtembodaku.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.guannengcc.top/Article/details/gtgwnrgiag.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.dashuyun.cn/Article/details/gtabsimugu.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvuagrhks.html

[D11] 反转数组
来源：http://dali.shangyingyoupin.top/Article/details/gtfngwdqym.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yueranfly.top/Article/details/gttxrvnidk.html

PHP:  array_reverse($arr);
来源：http://dali.tanke756.top/Article/details/gthgqpogyu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xinyue.icu/Article/details/gtmzobuqps.html

TS:   [...arr].reverse();
来源：http://dali.yangfankeji.com/Article/details/gtzmbwsymz.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gttobljcox.html

Go:   slices.Reverse(arr)
来源：http://dali.andypj.xyz/Article/details/gtgjlqctod.html

Ruby: arr.reverse
来源：http://dali.guannengcc.top/Article/details/gtpwptvzpf.html

C#:   list.Reverse();
来源：http://dali.yj20258.top/Article/details/gtczdkrwyy.html

[D12] 查找元素下标
来源：http://dali.kuanghao11.cn/Article/details/gtfaxzrzsc.html

Py:   arr.index(x);  x in arr
来源：http://dali.shanyushiyangtech.top/Article/details/gtgspwadrx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.chenzaomai.com/Article/details/gttatcdqnv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.smart0.xyz/Article/details/gtqmdqpxmf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gogol.net.cn/Article/details/gtgeuvjqpp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sysykeji.top/Article/details/gtdgweerwm.html

Go:   slices.Index(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtyixdjwuc.html

Ruby: arr.index(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtveclzkwl.html

C#:   list.IndexOf(x);
来源：http://dali.jyoumei.cn/Article/details/gtczdovriy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cqqwz.cn/Article/details/gtaszyttzd.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hnxiangtu.top/Article/details/gtqcogqkmy.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cheryme.top/Article/details/gtrsrwfopa.html

JS:   arr.filter(x => x > 3)
来源：http://dali.nwbrower.top/Article/details/gtxmowevge.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhoulong.xyz/Article/details/gtzjcxjhtv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.birdmap.top/Article/details/gtkjxfakpn.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.0kj1m.cn/Article/details/gtpxlhyuar.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjjpoidtc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtwgvbjlyd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenlongwang.top/Article/details/gtbyvclwen.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zdqjudy.top/Article/details/gtvuaespmu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrnyrckqv.html

JS:   arr.map(x => x * 2)
来源：http://dali.jiagoushi.top/Article/details/gtkpjaforj.html

TS:   arr.map(x => x * 2)
来源：http://dali.wangdashe.top/Article/details/gttqmuijpg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.guannengcc.top/Article/details/gtbbaplqpv.html

Go:   // 手写循环
来源：http://dali.ehwqpu.com/Article/details/gtxynrxops.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.tanke756.top/Article/details/gtnhbunwtm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ivvv.top/Article/details/gtinymxkec.html

[D15] 去重
来源：http://dali.xylfe.cn/Article/details/gthdebmrep.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yj202588.top/Article/details/gtvpizdbgs.html

PHP:  array_unique($arr);
来源：http://dali.0kj1m.cn/Article/details/gtxmmtmcqu.html

JS:   [...new Set(arr)]
来源：http://dali.xuanzx.com/Article/details/gtfgncukbl.html

TS:   [...new Set(arr)]
来源：http://dali.yonumen.top/Article/details/gtqxybqzze.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ppjwa.cn/Article/details/gtmjepdebm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jianghu66.top/Article/details/gtdvskaelu.html

Ruby: arr.uniq
来源：http://dali.zycfv.cn/Article/details/gtoklswrza.html

C#:   list.Distinct().ToList()
来源：http://dali.zycfv.cn/Article/details/gtyriroqkz.html

[D16] 求和与平均值
来源：http://dali.zhiwuduotai.top/Article/details/gtovvxorna.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.daxiang520.top/Article/details/gtpouvgbdb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shuidangran.top/Article/details/gtftmtynvd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zdqjudy.top/Article/details/gtlfctfjtt.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbruikqdp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jlsjyb.cn/Article/details/gtsfersouv.html

Go:   // 手写循环累加
来源：http://dali.shzxlz.cn/Article/details/gtdvmdpusm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.bjfxy.top/Article/details/gtmljjoeqn.html

C#:   list.Sum();  list.Average()
来源：http://dali.jqgfzy.top/Article/details/gtgqbcepje.html

[D17] 最大值与最小值
来源：http://dali.xziqi.cn/Article/details/gteofbfdvo.html

Py:   max(arr);  min(arr)
来源：http://dali.cqqwz.cn/Article/details/gtcmlwzicm.html

PHP:  max($arr);  min($arr);
来源：http://dali.yj202588.top/Article/details/gtfibfbsmo.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxvwbppyp.html

TS:   Math.max(...arr);
来源：http://dali.mhx1999.top/Article/details/gtommtwytb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jianghu66.top/Article/details/gtfifqxxxr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zdqjudy.top/Article/details/gtbvkktpxc.html

Ruby: arr.max;  arr.min
来源：http://dali.yuanzhike.top/Article/details/gtijdyrmmk.html

C#:   list.Max();  list.Min()
来源：http://dali.shuidangran.top/Article/details/gtwizmmpfz.html

[D18] 扁平化嵌套数组
来源：http://dali.jinqigfzy.top/Article/details/gtjgxvtfvt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hnxiangtu.top/Article/details/gtohobxjmu.html

PHP:  array_merge(...$nested);
来源：http://dali.jyoumei.cn/Article/details/gtghsyshwj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhixingplan.top/Article/details/gtpmcinonr.html

TS:   nested.flat();
来源：http://dali.xuanzx.com/Article/details/gtejuurvzi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.meibo888.top/Article/details/gtoppismtn.html

Go:   // 手写双层循环
来源：http://dali.yj20258888.top/Article/details/gtmtxhgniw.html

Ruby: nested.flatten
来源：http://dali.chenjidiqi.icu/Article/details/gtpgwudvpa.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.gzhubu.top/Article/details/gtbquheers.html

[D19] 按字段分组
来源：http://dali.jyoumei.cn/Article/details/gtfydestfh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.guowangkeji.top/Article/details/gtevdlamdc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yongpay.top/Article/details/gtqltmfohm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yvedp.cn/Article/details/gtxqismjow.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jqgufenzy.top/Article/details/gtwqfruzpm.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.svipenyu.cn/Article/details/gtvlmqukzr.html

Go:   // 手写 map[string][]T
来源：http://dali.nwbrower.top/Article/details/gtcxbpgwuo.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhengqikj.top/Article/details/gtbndgbvct.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yongpay.top/Article/details/gtggdlkljv.html

[D20] 统计每个元素出现次数
来源：http://dali.shuidangran.top/Article/details/gtyorssars.html

Py:   Counter(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtupaschjf.html

PHP:  array_count_values($arr);
来源：http://dali.yj20258888.top/Article/details/gtakdhahdt.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnxiangtu.top/Article/details/gtsunaljwo.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nanxuanxn.top/Article/details/gtlqfrrhhr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xinyue.icu/Article/details/gtocxnqdpw.html

Go:   // 手写 map[T]int
来源：http://dali.yangfankeji.com/Article/details/gtcmdslpah.html

Ruby: arr.tally
来源：http://dali.dashuyun.cn/Article/details/gtmwgcnhmt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hammf.cn/Article/details/gtznojmwgq.html

[D21] 判断是否包含某元素
来源：http://dali.fzhhl.top/Article/details/gtkdsdiugz.html

Py:   x in arr
来源：http://dali.shanyushiyangtech.top/Article/details/gtdsfwfbnx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yangfankeji.com/Article/details/gtgeftnqrs.html

JS:   arr.includes(x)
来源：http://dali.ybcxt.top/Article/details/gtveqcsyyh.html

TS:   arr.includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyogajxbe.html

Java: list.contains(x)
来源：http://dali.hongshengwenyu.top/Article/details/gttfbfwksa.html

Go:   slices.Contains(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtardcfhic.html

Ruby: arr.include?(x)
来源：http://dali.aizwys.cn/Article/details/gtofuufniq.html

C#:   list.Contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpftgyfuh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sysykeji.top/Article/details/gtixwvrmft.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtjdorshnp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xylfe.cn/Article/details/gtbtlqdsmy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.dashuyun.cn/Article/details/gtxvqtlaal.html

TS:   [...arr];
来源：http://dali.jinghuilouyu.cn/Article/details/gtyshbaoqj.html

Java: new ArrayList<>(list);
来源：http://dali.gotoacloud.top/Article/details/gtbzjoyzjh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.aibaodan.cn/Article/details/gtxhnezxta.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yvedp.cn/Article/details/gtrhzwljeq.html

C#:   new List<int>(list);
来源：http://dali.yuxming.cn/Article/details/gtuuhisicz.html

[D23] reduce 累积计算
来源：http://dali.sxryk.cn/Article/details/gtphmwvnkd.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.nanxinkj.top/Article/details/gtyfjlohjj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ivvv.top/Article/details/gthlkbjehd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ydzc1.top/Article/details/gtmknbowre.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gteadypntz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.kuanghao11.cn/Article/details/gtlmtqlwua.html

Go:   // 手写循环
来源：http://dali.hnxiangtu.top/Article/details/gtxqlepkpb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yangfankeji.com/Article/details/gtkhcezzhy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.meibo888.top/Article/details/gtqhnhfrvu.html

[D24] 字典 / Map 基本操作
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxbbnjmkf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sweek.top/Article/details/gtqliowwby.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.vqdsnc.cn/Article/details/gtpeuwpjvr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hysaishi.cn/Article/details/gtnadilmea.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ppjwa.cn/Article/details/gtvfawxjyt.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jianghu66.top/Article/details/gttcwpszch.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhoulong.xyz/Article/details/gthbantplp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gaohongyu789.top/Article/details/gtallkspkm.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.wangdashe.top/Article/details/gtmvtonuha.html

[D25] Set 集合去重与交并差
来源：http://dali.dianchejie.cn/Article/details/gtkielkopf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhixingplan.top/Article/details/gtirfgdtzo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cqqwz.cn/Article/details/gtdcojqwgh.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.aibaodan.cn/Article/details/gtfjrruryr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.dianchejie.cn/Article/details/gtzfxssnuf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sufxvd.cn/Article/details/gtgweossah.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.pycfn.com/Article/details/gtkxglfceu.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.tanke756.top/Article/details/gtwxtbkxpq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cucudq.cn/Article/details/gtearonelw.html

[D26] 数组转字符串
来源：http://dali.hammf.cn/Article/details/gtvgrscvnw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gotoacloud.top/Article/details/gtyvwfhtoc.html

PHP:  implode(", ", $arr);
来源：http://dali.9152youxi.cn/Article/details/gtzogzcpbq.html

JS:   arr.join(", ")
来源：http://dali.hnqzz.top/Article/details/gtftkrteau.html

TS:   arr.join(", ")
来源：http://dali.zhoulong.xyz/Article/details/gtynwztgpb.html

Java: String.join(", ", list)
来源：http://dali.kuanghao11.cn/Article/details/gtwzxbucwe.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yj202588.top/Article/details/gtfbtkmmyp.html

Ruby: arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gtgcduexni.html

C#:   string.Join(", ", list)
来源：http://dali.andypj.xyz/Article/details/gtcgjiayif.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtriatrxig.html

E. 字符串处理
来源：http://dali.vqdsnc.cn/Article/details/gtocewzpbj.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtdfmqwuir.html

[E01] 拼接字符串
来源：http://dali.xinyue.icu/Article/details/gtxrltjbrl.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yonumen.top/Article/details/gtdtgskfuf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.feifeiyinyue.top/Article/details/gttpkcyrna.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtnjnvkdxg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenzaomai.com/Article/details/gtakacaljf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cashguo.top/Article/details/gtmloebcbm.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zdqjudy.top/Article/details/gtxpkaapgm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.smart0.xyz/Article/details/gtmmgbprov.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtpdyxxwsw.html

[E02] 重复字符串
来源：http://dali.cashguo.top/Article/details/gtybowvbgi.html

Py:   "ab" * 3
来源：http://dali.sxryk.cn/Article/details/gtzcxzqdng.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ehwqpu.com/Article/details/gtyaumnknl.html

JS:   "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gtbzspsyij.html

TS:   "ab".repeat(3)
来源：http://dali.tianlin.xyz/Article/details/gtmsgrapkw.html

Java: "ab".repeat(3)
来源：http://dali.yvedp.cn/Article/details/gttwapxaag.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.smart0.xyz/Article/details/gtddalkadf.html

Ruby: "ab" * 3
来源：http://dali.0kj1m.cn/Article/details/gthapttata.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cashguo.top/Article/details/gtesfaipxu.html

[E03] 截取子串
来源：http://dali.havefunace.top/Article/details/gtsnbdzxuo.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.tian-w.cn/Article/details/gtbnjwpddl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gtqfacijuu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.kuanghao11.cn/Article/details/gtiaeigzzc.html

TS:   s.slice(1, 4)
来源：http://dali.yj202588.top/Article/details/gtqwiwczrr.html

Java: s.substring(1, 4)
来源：http://dali.zhixingplan.top/Article/details/gtgwdfjros.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sufxvd.cn/Article/details/gtyngnoydk.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xuanzx.com/Article/details/gttlsxaxwp.html

C#:   s.Substring(1, 3)
来源：http://dali.guannengcc.top/Article/details/gtbukqflmf.html

[E04] 查找子串位置
来源：http://dali.shanyushiyangtech.top/Article/details/gtqukwxtnp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.dianchejie.cn/Article/details/gtayytqygm.html

PHP:  strpos($s, "x");
来源：http://dali.guowangkeji.top/Article/details/gtpaqpiwhn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xuanzx.com/Article/details/gtmjtukemt.html

TS:   s.indexOf("x")
来源：http://dali.yangfankeji.com/Article/details/gtrqxgplhf.html

Java: s.indexOf("x")
来源：http://dali.svipenyu.cn/Article/details/gtwbysxpxi.html

Go:   strings.Index(s, "x")
来源：http://dali.hysaishi.cn/Article/details/gtzsqqbwvx.html

Ruby: s.index("x")
来源：http://dali.aizwys.cn/Article/details/gtffxpztuc.html

C#:   s.IndexOf("x")
来源：http://dali.pengpengdd.cyou/Article/details/gtmncychky.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.aibaodan.cn/Article/details/gtvaegmmne.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yonumen.top/Article/details/gtvhsclypt.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.c1oappe.top/Article/details/gtvmgxjfxk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daxiang520.top/Article/details/gtmyizphlu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shzxlz.cn/Article/details/gtkkzidcrl.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgfzy.top/Article/details/gthfadlsnc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.dianchejie.cn/Article/details/gtrbxflirc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hywenlv.cn/Article/details/gtwibwrwwc.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gaohongyu789.top/Article/details/gtqeudjtgj.html

[E06] 替换子串
来源：http://dali.hnqzz.top/Article/details/gtrzninurb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yvedp.cn/Article/details/gtlorzidpc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.daxiang520.top/Article/details/gtzksxgjig.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtddtcfcdu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtfjfyvyfd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtquudheou.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtpzemdydd.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfamymokt.html

C#:   s.Replace("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtvptiozqs.html

[E07] 按分隔符拆分
来源：http://dali.tanke756.top/Article/details/gtgnwpvdwl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.birdmap.top/Article/details/gtalabmrhm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sxryk.cn/Article/details/gtttultdfw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.quarkkingdee.top/Article/details/gtnnagzdrv.html

TS:   s.split(",")
来源：http://dali.nwbrower.top/Article/details/gtjpnrxgxh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ivvv.top/Article/details/gtcoiekaxd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmjzxekka.html

Ruby: s.split(",");  s.split
来源：http://dali.wangshuangyany.cn/Article/details/gtclawjgco.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.fengsongda.top/Article/details/gtsxctvwnt.html

[E08] 数组按分隔符合并
来源：http://dali.gotoacloud.top/Article/details/gtssptmtil.html

Py:   ",".join(items)
来源：http://dali.yuxming.cn/Article/details/gttkuazwfg.html

PHP:  implode(",", $items);
来源：http://dali.dianchejie.cn/Article/details/gtjqvredkr.html

JS:   items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gtjusykstp.html

TS:   items.join(",")
来源：http://dali.yonumen.top/Article/details/gtdanrrfkk.html

Java: String.join(",", items)
来源：http://dali.fengsongda.top/Article/details/gtvrjxeqid.html

Go:   strings.Join(items, ",")
来源：http://dali.feifeiyinyue.top/Article/details/gtsjnosusf.html

Ruby: items.join(",")
来源：http://dali.gaohongyu789.top/Article/details/gtcbvngdyg.html

C#:   string.Join(",", items)
来源：http://dali.jyoumei.cn/Article/details/gtpstuirvp.html

[E09] 去除所有空白字符
来源：http://dali.cdnleiting.top/Article/details/gtokbckwqq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yuanzhike.top/Article/details/gtwbgakjjl.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gogol.net.cn/Article/details/gtqcukvyon.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hnqzz.top/Article/details/gtgsmrbbdj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tian-w.cn/Article/details/gtmjdlpguu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.aizwys.cn/Article/details/gtfwuleler.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ybcxt.top/Article/details/gthcjhxmpy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hnxiangtu.top/Article/details/gtainqqcsk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.snrcjt.cn/Article/details/gtjqyctzds.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ehwqpu.com/Article/details/gtguwrgzvj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yuanzhike.top/Article/details/gtmesfyuzr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xuetiantiany.cn/Article/details/gtchmidssa.html

JS:   "7".padStart(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gtdomwoofi.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gtjvemkcrq.html

Java: String.format("%03d", 7)
来源：http://dali.wangdashe.top/Article/details/gteogjbtnc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.havefunace.top/Article/details/gtzxojluqb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gtugaagpnz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.feifeiyinyue.top/Article/details/gtkvnedolx.html

[E11] 反转字符串
来源：http://dali.snrcjt.cn/Article/details/gthguwlzrf.html

Py:   s[::-1]
来源：http://dali.svipenyu.cn/Article/details/gthitlalkr.html

PHP:  strrev($s);
来源：http://dali.gzhubu.top/Article/details/gtueovelst.html

JS:   [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gtjqglhdbq.html

TS:   [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gtokpqnoxo.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ppjwa.cn/Article/details/gtonuaqjtq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ydzc1.top/Article/details/gtcdnqrequ.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gtkburanrf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.svipenyu.cn/Article/details/gtbgqtjahu.html

[E12] 统计某字符出现次数
来源：http://dali.gogol.net.cn/Article/details/gtokeroisg.html

Py:   s.count("a")
来源：http://dali.redwolf501.top/Article/details/gtxhcirton.html

PHP:  substr_count($s, "a");
来源：http://dali.vqdsnc.cn/Article/details/gtcspnjusu.html

JS:   s.split("a").length - 1
来源：http://dali.kuanghao11.cn/Article/details/gtgxezxyqu.html

TS:   s.split("a").length - 1
来源：http://dali.smart0.xyz/Article/details/gtmjjkeuor.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jianghu66.top/Article/details/gtotahwvln.html

Go:   strings.Count(s, "a")
来源：http://dali.pycfn.com/Article/details/gthzggivuu.html

Ruby: s.count("a")
来源：http://dali.dianchejie.cn/Article/details/gtijwxlqzr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhixingplan.top/Article/details/gtrotvuazv.html

[E13] 逐字符遍历
来源：http://dali.tian-w.cn/Article/details/gtbxtznziv.html

Py:   for ch in s: print(ch)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcjyiedwp.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yvedp.cn/Article/details/gtogyyahum.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gtcgldanal.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ybcxt.top/Article/details/gtvkzlcbsf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.fzhhl.top/Article/details/gtuyvldmza.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiqdcpzeb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.daxiang520.top/Article/details/gthysonjxw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.birdmap.top/Article/details/gtukenxyff.html

[E14] URL 编码与 Base64
来源：http://dali.gzhubu.top/Article/details/gtmdrowqef.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.9152youxi.cn/Article/details/gtysswivdz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.sufxvd.cn/Article/details/gthmdqjymr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.feifeiyinyue.top/Article/details/gtyfhkqcjj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.fzhhl.top/Article/details/gtwgzqypqi.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hongshengwenyu.top/Article/details/gteyfztnkb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hammf.cn/Article/details/gtizsreyae.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nwbrower.top/Article/details/gtfaaelpak.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.dashuyun.cn/Article/details/gtfxhctgsj.html

[E15] HTML 转义 / 反转义
来源：http://dali.gotoacloud.top/Article/details/gtvgijnofz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cucudq.cn/Article/details/gtpsvjaadb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.andypj.xyz/Article/details/gtusabwxwm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cdnleiting.top/Article/details/gtgowmuhma.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cdnleiting.top/Article/details/gtjdwiikyq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenlongwang.top/Article/details/gtggyzqomc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.mhx1999.top/Article/details/gtdnlqvhjx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cdnleiting.top/Article/details/gthldiopis.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.snrcjt.cn/Article/details/gtvealxmnu.html

[E16] 数字千分位
来源：http://dali.jinqigufen.top/Article/details/gtzdedmbnt.html

Py:   f"{1234567:,}"
来源：http://dali.sysykeji.top/Article/details/gtcfmpdfcd.html

PHP:  number_format(1234567);
来源：http://dali.jinqigfzy.top/Article/details/gtvaqltban.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.iojbl.cn/Article/details/gtsbkmwbyz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cheryme.top/Article/details/gtpvmuaqlc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.daria6918.cn/Article/details/gtposegfui.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.redwolf501.top/Article/details/gtyukgxqfo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.havefunace.top/Article/details/gtnavcgona.html

C#:   1234567.ToString("N0")
来源：http://dali.yuxming.cn/Article/details/gtlslwidha.html

[E17] 首字母大写
来源：http://dali.chenjidiqi.icu/Article/details/gtuwcbtyli.html


<!-- 参考信息 -->