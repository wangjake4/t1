代发 wailian999

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gotoacloud.top/Article/details/gthjudvxft.html

Ruby: arr.sort
来源：http://dali.jinqigfzy.top/Article/details/gtvmxbllks.html

C#:   list.Sort();
来源：http://dali.cashguo.top/Article/details/gtinbnlzjm.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.pycfn.com/Article/details/gtoefpicbg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zycfv.cn/Article/details/gtqqgilydo.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.dashuyun.cn/Article/details/gtqqmpkwmk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnqzz.top/Article/details/gthicpmnyo.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhongyouzk.top/Article/details/gtufvbbsyo.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jqgfzy.top/Article/details/gtemfrnxpm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cdnleiting.top/Article/details/gtkpperrpf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.fengsongda.top/Article/details/gtqfpkawqh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shuidangran.top/Article/details/gtdbbbflnx.html

[D11] 反转数组
来源：http://dali.yanxiufei.cn/Article/details/gtjoernuda.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jiagoushi.top/Article/details/gticpfosak.html

PHP:  array_reverse($arr);
来源：http://dali.yonumen.top/Article/details/gtsbplskny.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.fzhhl.top/Article/details/gtscxdeqvi.html

TS:   [...arr].reverse();
来源：http://dali.havefunace.top/Article/details/gttkdxjacw.html

Java: Collections.reverse(list);
来源：http://dali.cashguo.top/Article/details/gtuksjunog.html

Go:   slices.Reverse(arr)
来源：http://dali.snrcjt.cn/Article/details/gtfgxrhcyp.html

Ruby: arr.reverse
来源：http://dali.gzhubu.top/Article/details/gtpfbwjtuu.html

C#:   list.Reverse();
来源：http://dali.ehwqpu.com/Article/details/gttktwnhwg.html

[D12] 查找元素下标
来源：http://dali.gotoacloud.top/Article/details/gtinpzghhh.html

Py:   arr.index(x);  x in arr
来源：http://dali.guowangkeji.top/Article/details/gtaebdmyao.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hnqzz.top/Article/details/gtdhicfzcf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hammf.cn/Article/details/gtlbgqdtxc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuxlgqynt.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.chenzaomai.com/Article/details/gtowgotbjb.html

Go:   slices.Index(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtespqxevp.html

Ruby: arr.index(x)
来源：http://dali.hammf.cn/Article/details/gtibrlgoll.html

C#:   list.IndexOf(x);
来源：http://dali.yueranfly.top/Article/details/gtatfvakne.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nanxinkj.top/Article/details/gtefxlmmjg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yuxming.cn/Article/details/gtqsybptbw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hnxiangtu.top/Article/details/gtvhgneoqo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hammf.cn/Article/details/gtkapumdkj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zdqjudy.top/Article/details/gttyxngdnh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtglnbibsl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yuanzhike.top/Article/details/gttnuqmsap.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.quarkkingdee.top/Article/details/gtketgvrzt.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtndqwlucy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yangfankeji.com/Article/details/gtkjqpslhv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhoulong.xyz/Article/details/gtgbficetu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.c1oappe.top/Article/details/gtuylpgkbm.html

JS:   arr.map(x => x * 2)
来源：http://dali.cucudq.cn/Article/details/gtmmyohval.html

TS:   arr.map(x => x * 2)
来源：http://dali.daxiang520.top/Article/details/gtcoyjznvw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.nanxinkj.top/Article/details/gtxyluiwyl.html

Go:   // 手写循环
来源：http://dali.fengsongda.top/Article/details/gtnnyelpej.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yvedp.cn/Article/details/gtdfshissc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yongpay.top/Article/details/gtyqydnigt.html

[D15] 去重
来源：http://dali.hysaishi.cn/Article/details/gtqgmcmufu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jqgufenzy.top/Article/details/gtafjgodie.html

PHP:  array_unique($arr);
来源：http://dali.jqgfzy.top/Article/details/gttrxukjse.html

JS:   [...new Set(arr)]
来源：http://dali.sysykeji.top/Article/details/gtpqscmbmq.html

TS:   [...new Set(arr)]
来源：http://dali.zhengqikj.top/Article/details/gtpnyhwnwc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.redwolf501.top/Article/details/gtrgihlsvt.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhixingplan.top/Article/details/gtdpesxmwj.html

Ruby: arr.uniq
来源：http://dali.cdnleiting.top/Article/details/gthqifoltk.html

C#:   list.Distinct().ToList()
来源：http://dali.zhixingplan.top/Article/details/gtovlpzosb.html

[D16] 求和与平均值
来源：http://dali.xuetiantiany.cn/Article/details/gtgvfwvzqz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jianghu66.top/Article/details/gtxvucnblk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtheapxcdk.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtpqzpftuz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fzhhl.top/Article/details/gtuiwxxlvf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shanyushiyangtech.top/Article/details/gtrdxwfvry.html

Go:   // 手写循环累加
来源：http://dali.jqgufenzy.top/Article/details/gtieyywvsz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xylfe.cn/Article/details/gtisaztywo.html

C#:   list.Sum();  list.Average()
来源：http://dali.smart0.xyz/Article/details/gtagrvpevr.html

[D17] 最大值与最小值
来源：http://dali.yj20258888.top/Article/details/gtvitxxfxv.html

Py:   max(arr);  min(arr)
来源：http://dali.aibaodan.cn/Article/details/gtmbvonmbe.html

PHP:  max($arr);  min($arr);
来源：http://dali.daxiang520.top/Article/details/gtbjfdlzxz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjubztepx.html

TS:   Math.max(...arr);
来源：http://dali.snrcjt.cn/Article/details/gtncaqqezj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.nanxuanxn.top/Article/details/gtpqxvrykn.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.havefunace.top/Article/details/gtapsqjlxn.html

Ruby: arr.max;  arr.min
来源：http://dali.ybcxt.top/Article/details/gtypwmbruj.html

C#:   list.Max();  list.Min()
来源：http://dali.0kj1m.cn/Article/details/gtsujrmqeq.html

[D18] 扁平化嵌套数组
来源：http://dali.pengpengdd.cyou/Article/details/gtrtnnpviy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.9152youxi.cn/Article/details/gtnzuoivpt.html

PHP:  array_merge(...$nested);
来源：http://dali.yangfankeji.com/Article/details/gtvckmnoau.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.haohaochexian.top/Article/details/gtyzhrqidz.html

TS:   nested.flat();
来源：http://dali.chenzaomai.com/Article/details/gtqdmsasgw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jiagoushi.top/Article/details/gtdszhotjf.html

Go:   // 手写双层循环
来源：http://dali.cucudq.cn/Article/details/gtrebzvxuk.html

Ruby: nested.flatten
来源：http://dali.xziqi.cn/Article/details/gtusmjnmjd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.tian-w.cn/Article/details/gtogxwrsnj.html

[D19] 按字段分组
来源：http://dali.guannengcc.top/Article/details/gtnpwkdzgp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.mhx1999.top/Article/details/gtqyrevbej.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yangfankeji.com/Article/details/gtlqqstntg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhixingplan.top/Article/details/gtcdfjbrug.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.feifeiyinyue.top/Article/details/gtyqcvybkj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.tanke756.top/Article/details/gtcgvlklcv.html

Go:   // 手写 map[string][]T
来源：http://dali.xinyue.icu/Article/details/gtrsjacxym.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.guowangkeji.top/Article/details/gtbkkqoxwz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.andypj.xyz/Article/details/gtpumoofql.html

[D20] 统计每个元素出现次数
来源：http://dali.jinghuilouyu.cn/Article/details/gtpmywwrmj.html

Py:   Counter(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtmxxpuimb.html

PHP:  array_count_values($arr);
来源：http://dali.haohaochexian.top/Article/details/gthlqsfcbw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgufenzy.top/Article/details/gtflfoxtrh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cheryme.top/Article/details/gtcyrsrsnt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hammf.cn/Article/details/gtxnquusrr.html

Go:   // 手写 map[T]int
来源：http://dali.zdqjudy.top/Article/details/gtguyzqdou.html

Ruby: arr.tally
来源：http://dali.chenzaomai.com/Article/details/gttuuzctpn.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.redwolf501.top/Article/details/gtklcizntp.html

[D21] 判断是否包含某元素
来源：http://dali.0kj1m.cn/Article/details/gtmgddpqxn.html

Py:   x in arr
来源：http://dali.cucudq.cn/Article/details/gtvjkebwqj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gaohongyu789.top/Article/details/gtxzcpcwhz.html

JS:   arr.includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gtctyjynwh.html

TS:   arr.includes(x)
来源：http://dali.hnqzz.top/Article/details/gtyvzpgpxn.html

Java: list.contains(x)
来源：http://dali.sufxvd.cn/Article/details/gtovdzcups.html

Go:   slices.Contains(arr, x)
来源：http://dali.yonumen.top/Article/details/gtslugtluu.html

Ruby: arr.include?(x)
来源：http://dali.xuanzx.com/Article/details/gtdglolayl.html

C#:   list.Contains(x)
来源：http://dali.hfpthk.cn/Article/details/gtsdsbdlix.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yj202588.top/Article/details/gtkddosmbr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.svipenyu.cn/Article/details/gtiqpgtouu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.nanxinkj.top/Article/details/gtqsicbine.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuxxwotof.html

TS:   [...arr];
来源：http://dali.ydzc1.top/Article/details/gtkmorzipv.html

Java: new ArrayList<>(list);
来源：http://dali.tanke756.top/Article/details/gtlmveobtu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gotoacloud.top/Article/details/gtepcroagj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gotoacloud.top/Article/details/gtekcletiz.html

C#:   new List<int>(list);
来源：http://dali.ydzc1.top/Article/details/gtnwzwbokn.html

[D23] reduce 累积计算
来源：http://dali.jyoumei.cn/Article/details/gtgjdlivqt.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.aizwys.cn/Article/details/gteoqddstq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuoairrmn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.haohaochexian.top/Article/details/gtgcyhanjq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuxming.cn/Article/details/gthmppcsbv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.kuanghao11.cn/Article/details/gtsysaswdk.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gtllnfjwkm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xziqi.cn/Article/details/gtwtxnvvei.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yuanzhike.top/Article/details/gtaluzwbvj.html

[D24] 字典 / Map 基本操作
来源：http://dali.yj202588.top/Article/details/gtkonwjcna.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gtvfmcinqr.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.wangshuangyany.cn/Article/details/gteitnquym.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzmgkkfbt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gteqxshsio.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hysaishi.cn/Article/details/gtkekcbhjy.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.nanxinkj.top/Article/details/gtfgrtsibz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hnqzz.top/Article/details/gtdnhijvgh.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.guannengcc.top/Article/details/gtwnchgqig.html

[D25] Set 集合去重与交并差
来源：http://dali.jianghu66.top/Article/details/gtbxmdczzl.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.wangshuangyany.cn/Article/details/gtnzoqhoby.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhongyouzk.top/Article/details/gtlbrrxhzx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtkhxfbnxb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jiagoushi.top/Article/details/gtgvcdopcl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.316326.xyz/Article/details/gtghhbxpiv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ydzc1.top/Article/details/gtjouqcthl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.c1oappe.top/Article/details/gttpvvwdfn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.0kj1m.cn/Article/details/gtnizlcwof.html

[D26] 数组转字符串
来源：http://dali.sysykeji.top/Article/details/gtsbeninlr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.andypj.xyz/Article/details/gtwfxmcfhp.html

PHP:  implode(", ", $arr);
来源：http://dali.vqdsnc.cn/Article/details/gtvsybftps.html

JS:   arr.join(", ")
来源：http://dali.ppjwa.cn/Article/details/gtnxlowphh.html

TS:   arr.join(", ")
来源：http://dali.kuanghao11.cn/Article/details/gtkwtbazah.html

Java: String.join(", ", list)
来源：http://dali.shuidangran.top/Article/details/gtqrjuzagw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzrregkyi.html

Ruby: arr.join(", ")
来源：http://dali.iojbl.cn/Article/details/gtyqvtqvsx.html

C#:   string.Join(", ", list)
来源：http://dali.gzhubu.top/Article/details/gthjyfregd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtvaxgaukr.html

E. 字符串处理
来源：http://dali.jinghuilouyu.cn/Article/details/gtrdyazsas.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtjzhqnwjn.html

[E01] 拼接字符串
来源：http://dali.vqdsnc.cn/Article/details/gttbogijgv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.daria6918.cn/Article/details/gtddyszzmz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hysaishi.cn/Article/details/gthfngspzn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hammf.cn/Article/details/gtajrnkmgr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tanke756.top/Article/details/gtkvxprjbn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hywenlv.cn/Article/details/gtusyuuklu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zdqjudy.top/Article/details/gtlhsjivyp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbvjowpqq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtzwukcndy.html

[E02] 重复字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtzoynvlwq.html

Py:   "ab" * 3
来源：http://dali.wangdashe.top/Article/details/gtthqjkjho.html

PHP:  str_repeat("ab", 3);
来源：http://dali.quarkkingdee.top/Article/details/gtyobnprhx.html

JS:   "ab".repeat(3)
来源：http://dali.meibo888.top/Article/details/gtvayzevwp.html

TS:   "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gtzfrplyyp.html

Java: "ab".repeat(3)
来源：http://dali.xziqi.cn/Article/details/gthdidrofp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zycfv.cn/Article/details/gtybggffew.html

Ruby: "ab" * 3
来源：http://dali.hysaishi.cn/Article/details/gtcnhnrjpm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hammf.cn/Article/details/gtsmeavhhf.html

[E03] 截取子串
来源：http://dali.shzxlz.cn/Article/details/gtlhzsfekw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cdnleiting.top/Article/details/gtlrenzvxc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gtjktdyuuv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.0kj1m.cn/Article/details/gtvkinyeym.html

TS:   s.slice(1, 4)
来源：http://dali.yanxiufei.cn/Article/details/gtfhaphrwo.html

Java: s.substring(1, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxeglpwog.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yanxiufei.cn/Article/details/gtupqasjsy.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yuanzhike.top/Article/details/gtdfqlphqm.html

C#:   s.Substring(1, 3)
来源：http://dali.ehwqpu.com/Article/details/gtlfwprpxc.html

[E04] 查找子串位置
来源：http://dali.jinghuilouyu.cn/Article/details/gtdntzcijr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.redwolf501.top/Article/details/gthwqwwpoh.html

PHP:  strpos($s, "x");
来源：http://dali.yj20258.top/Article/details/gtvzjsghfr.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jyoumei.cn/Article/details/gtctfjiitr.html

TS:   s.indexOf("x")
来源：http://dali.gogol.net.cn/Article/details/gtyjsbkqqw.html

Java: s.indexOf("x")
来源：http://dali.jinqigfzy.top/Article/details/gtcrljljgc.html

Go:   strings.Index(s, "x")
来源：http://dali.zhengqikj.top/Article/details/gtiqsbugan.html

Ruby: s.index("x")
来源：http://dali.nwbrower.top/Article/details/gtbkryptsk.html

C#:   s.IndexOf("x")
来源：http://dali.birdmap.top/Article/details/gtigcbrclv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.tianlin.xyz/Article/details/gtcpkfhnlx.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cashguo.top/Article/details/gtuwmuhukp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yueranfly.top/Article/details/gthsskpeuy.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sweek.top/Article/details/gtdsswqbvy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhixingplan.top/Article/details/gtnnkevbzt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ivvv.top/Article/details/gtgmssuzde.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yuanzhike.top/Article/details/gtcbhkblzl.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.nanxinkj.top/Article/details/gtltlxhlkh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.guowangkeji.top/Article/details/gtzmkeifmw.html

[E06] 替换子串
来源：http://dali.pycfn.com/Article/details/gtyjgqxxyq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.dashuyun.cn/Article/details/gtygvraxys.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tanke756.top/Article/details/gtbjzggrql.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tian-w.cn/Article/details/gtqgpnovlo.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yonumen.top/Article/details/gtrtbqossb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtxsbhzzzi.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yueranfly.top/Article/details/gtamgguwic.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gtkjgndaxb.html

C#:   s.Replace("a", "b")
来源：http://dali.316326.xyz/Article/details/gtzvebxqht.html

[E07] 按分隔符拆分
来源：http://dali.zhiwuduotai.top/Article/details/gtpzjjwovf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shanyushiyangtech.top/Article/details/gtkhhwlfmr.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zdqjudy.top/Article/details/gtcamensig.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yueranfly.top/Article/details/gteqqlsoyc.html

TS:   s.split(",")
来源：http://dali.iojbl.cn/Article/details/gtmicpuaza.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.fzhhl.top/Article/details/gtpjabxtod.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjxxumfej.html

Ruby: s.split(",");  s.split
来源：http://dali.havefunace.top/Article/details/gtomiwfsgc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.daria6918.cn/Article/details/gtpnvoekrm.html

[E08] 数组按分隔符合并
来源：http://dali.tianlin.xyz/Article/details/gtbucvtlvm.html

Py:   ",".join(items)
来源：http://dali.dianchejie.cn/Article/details/gtrlxsynvo.html

PHP:  implode(",", $items);
来源：http://dali.pengpengdd.cyou/Article/details/gtgbuaegyb.html

JS:   items.join(",")
来源：http://dali.tanke756.top/Article/details/gtxbdnbljv.html

TS:   items.join(",")
来源：http://dali.jlsjyb.cn/Article/details/gtdjsvgefu.html

Java: String.join(",", items)
来源：http://dali.svipenyu.cn/Article/details/gtcitljfhd.html

Go:   strings.Join(items, ",")
来源：http://dali.chenjidiqi.icu/Article/details/gtjubbvpvg.html

Ruby: items.join(",")
来源：http://dali.jinqigfzy.top/Article/details/gtdfchqrre.html

C#:   string.Join(",", items)
来源：http://dali.ppjwa.cn/Article/details/gtnmflmcnf.html

[E09] 去除所有空白字符
来源：http://dali.guannengcc.top/Article/details/gtwalntxsp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.dianchejie.cn/Article/details/gtxytmkmat.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jiagoushi.top/Article/details/gtcbfpzdda.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xuetiantiany.cn/Article/details/gtgfctifnl.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.bjfxy.top/Article/details/gtmasobxjz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.0kj1m.cn/Article/details/gtyotnghrh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yangfankeji.com/Article/details/gtchmssyfp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.9152youxi.cn/Article/details/gthbgixbyo.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.andypj.xyz/Article/details/gtzwqmbfdw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj20258.top/Article/details/gtqrguvfsf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yuanzhike.top/Article/details/gtwkzhulig.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.redwolf501.top/Article/details/gtafjcsbkc.html

JS:   "7".padStart(3, "0")
来源：http://dali.tian-w.cn/Article/details/gttiemsptj.html

TS:   "7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gthcnsistz.html

Java: String.format("%03d", 7)
来源：http://dali.ydzc1.top/Article/details/gttvpwywsi.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.guannengcc.top/Article/details/gtrwtbpdjv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gtnskwwkxf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jqgfzy.top/Article/details/gtwpdpmnok.html

[E11] 反转字符串
来源：http://dali.cheryme.top/Article/details/gtdhfvkjjh.html

Py:   s[::-1]
来源：http://dali.sysykeji.top/Article/details/gtqtcwyhvw.html

PHP:  strrev($s);
来源：http://dali.yj20258888.top/Article/details/gtjfeobddo.html

JS:   [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gtzzqxtcei.html

TS:   [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gtakzlpens.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.nanxuanxn.top/Article/details/gtsekcnfux.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.dashuyun.cn/Article/details/gtphgzrvzk.html

Ruby: s.reverse
来源：http://dali.daria6918.cn/Article/details/gtsmxshaoy.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cdnleiting.top/Article/details/gtffuewfgl.html

[E12] 统计某字符出现次数
来源：http://dali.daxiang520.top/Article/details/gtsalgtiti.html

Py:   s.count("a")
来源：http://dali.shangyingyoupin.top/Article/details/gtvujeyfbg.html

PHP:  substr_count($s, "a");
来源：http://dali.quarkkingdee.top/Article/details/gtizoqdqjk.html

JS:   s.split("a").length - 1
来源：http://dali.jlsjyb.cn/Article/details/gtgoqqeuaf.html

TS:   s.split("a").length - 1
来源：http://dali.cashguo.top/Article/details/gtwltvholz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hongshengwenyu.top/Article/details/gttevkuhtn.html

Go:   strings.Count(s, "a")
来源：http://dali.hysaishi.cn/Article/details/gtykpovjdr.html

Ruby: s.count("a")
来源：http://dali.jianghu66.top/Article/details/gtohyhyglv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.redwolf501.top/Article/details/gtmkokzatn.html

[E13] 逐字符遍历
来源：http://dali.shzxlz.cn/Article/details/gtvfotxzks.html

Py:   for ch in s: print(ch)
来源：http://dali.yj20258.top/Article/details/gtrwxbpbtj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.mhx1999.top/Article/details/gtquknibzq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cashguo.top/Article/details/gtkemyevfk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shuidangran.top/Article/details/gtvkyhjzdu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sxryk.cn/Article/details/gtozbzobbo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yj20258888.top/Article/details/gtxpmoxwjh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpuanjgzn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.fzhhl.top/Article/details/gthbylnbsd.html

[E14] URL 编码与 Base64
来源：http://dali.sxryk.cn/Article/details/gtjjbqgeyn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jianghu66.top/Article/details/gtxcxaundh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtianyqaeg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj20258888.top/Article/details/gtykahziub.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.meibo888.top/Article/details/gtnaqsusse.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdxllvkxa.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhoulong.xyz/Article/details/gtxikjdqiv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hnxiangtu.top/Article/details/gtpkuikxqw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.daxiang520.top/Article/details/gtmxozttzz.html

[E15] HTML 转义 / 反转义
来源：http://dali.jlsjyb.cn/Article/details/gtcarnofgg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.haohaochexian.top/Article/details/gtnzstkspo.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jyoumei.cn/Article/details/gthukbybhu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yanxiufei.cn/Article/details/gtybawqros.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.nanxuanxn.top/Article/details/gtfztmansl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.9152youxi.cn/Article/details/gtrqdkbktr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gzhubu.top/Article/details/gtkoriainx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jqgufenzy.top/Article/details/gtvziozlae.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjljxismn.html

[E16] 数字千分位
来源：http://dali.sufxvd.cn/Article/details/gtytyfpfzq.html

Py:   f"{1234567:,}"
来源：http://dali.cqqwz.cn/Article/details/gtudmdjmad.html

PHP:  number_format(1234567);
来源：http://dali.daxiang520.top/Article/details/gtbfckmmfe.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.aizwys.cn/Article/details/gtifezqtss.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cucudq.cn/Article/details/gttgbxdiya.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.birdmap.top/Article/details/gtodjcaloz.html


<!-- 参考信息 -->