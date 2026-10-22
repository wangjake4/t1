代发 wailian999

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinqigfzy.top/Article/details/gtcssqyoxs.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jqgufenzy.top/Article/details/gtlfuqaqaz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hongshengwenyu.top/Article/details/gtxuuygdvk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hysaishi.cn/Article/details/gtwiurvfux.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nanxuanxn.top/Article/details/gtohrezqhi.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.vqdsnc.cn/Article/details/gteagzjbvt.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nanxuanxn.top/Article/details/gtnofulfct.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.9152youxi.cn/Article/details/gtinzgwflc.html

[D11] 反转数组
来源：http://dali.c1oappe.top/Article/details/gttiwshkcm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.gaohongyu789.top/Article/details/gtqhmzrsyg.html

PHP:  array_reverse($arr);
来源：http://dali.yonumen.top/Article/details/gtkmfecciy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhiwuduotai.top/Article/details/gtqiuvefav.html

TS:   [...arr].reverse();
来源：http://dali.hywenlv.cn/Article/details/gtqhtufqzo.html

Java: Collections.reverse(list);
来源：http://dali.yanxiufei.cn/Article/details/gtxabgcyss.html

Go:   slices.Reverse(arr)
来源：http://dali.tianlin.xyz/Article/details/gtdisooimz.html

Ruby: arr.reverse
来源：http://dali.nwbrower.top/Article/details/gtlyhxoqxg.html

C#:   list.Reverse();
来源：http://dali.xuanzx.com/Article/details/gtetfgitex.html

[D12] 查找元素下标
来源：http://dali.jianghu66.top/Article/details/gtecemtbea.html

Py:   arr.index(x);  x in arr
来源：http://dali.sweek.top/Article/details/gttmbnnrre.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xinyue.icu/Article/details/gtmnxyfavr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtontdcspx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.0kj1m.cn/Article/details/gtbqoxwwga.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.daria6918.cn/Article/details/gtnmkmvicc.html

Go:   slices.Index(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtdzrtrwpg.html

Ruby: arr.index(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtinosibsh.html

C#:   list.IndexOf(x);
来源：http://dali.vqdsnc.cn/Article/details/gtnzswoexp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sweek.top/Article/details/gtvmoyiavb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.bjfxy.top/Article/details/gtypynhzvi.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shzxlz.cn/Article/details/gtrskqlzyj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.tian-w.cn/Article/details/gtpwqvtmgr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.vqdsnc.cn/Article/details/gtmovdyimw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yonumen.top/Article/details/gtpsnbzlyz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.fzhhl.top/Article/details/gtmnouqdmq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ivvv.top/Article/details/gtmkfzswzd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtcbqdgbkg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jiagoushi.top/Article/details/gtvdmawsvc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shzxlz.cn/Article/details/gtaajbwjnf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjqesiyhf.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinqigfzy.top/Article/details/gtaiqtxfgp.html

TS:   arr.map(x => x * 2)
来源：http://dali.sweek.top/Article/details/gtjyjytnng.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.dianchejie.cn/Article/details/gtnchwugix.html

Go:   // 手写循环
来源：http://dali.haohaochexian.top/Article/details/gtoohfotmy.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.dianchejie.cn/Article/details/gtfkrgdxgx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ydzc1.top/Article/details/gtkpznpcfi.html

[D15] 去重
来源：http://dali.yanxiufei.cn/Article/details/gtozdojnyo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.guowangkeji.top/Article/details/gtbshoogul.html

PHP:  array_unique($arr);
来源：http://dali.shzxlz.cn/Article/details/gtdaojsaxp.html

JS:   [...new Set(arr)]
来源：http://dali.hongshengwenyu.top/Article/details/gtlmotpirs.html

TS:   [...new Set(arr)]
来源：http://dali.zhiwuduotai.top/Article/details/gtrnmgvjjo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hnqzz.top/Article/details/gtctzfwkve.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqsoksswu.html

Ruby: arr.uniq
来源：http://dali.nanxuanxn.top/Article/details/gtywbnlpnx.html

C#:   list.Distinct().ToList()
来源：http://dali.snrcjt.cn/Article/details/gttutvgcqv.html

[D16] 求和与平均值
来源：http://dali.yj202588.top/Article/details/gtrdggmkfo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.haohaochexian.top/Article/details/gtqrtfsuyx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtotdxztbt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrukufdne.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yongpay.top/Article/details/gtipbbjbvp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yueranfly.top/Article/details/gtefkbwrgy.html

Go:   // 手写循环累加
来源：http://dali.havefunace.top/Article/details/gtgpulxpzc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yongpay.top/Article/details/gthnfvjdpn.html

C#:   list.Sum();  list.Average()
来源：http://dali.ivvv.top/Article/details/gtccjdavjh.html

[D17] 最大值与最小值
来源：http://dali.iojbl.cn/Article/details/gtqrgpqyrb.html

Py:   max(arr);  min(arr)
来源：http://dali.gogol.net.cn/Article/details/gtwvxlzzuk.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinqigufen.top/Article/details/gtnzwxqpft.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gtdcsgtkwf.html

TS:   Math.max(...arr);
来源：http://dali.cheryme.top/Article/details/gtmkskaeyt.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.c1oappe.top/Article/details/gtuuppeutj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xylfe.cn/Article/details/gthvmsngwz.html

Ruby: arr.max;  arr.min
来源：http://dali.316326.xyz/Article/details/gtfimpkejq.html

C#:   list.Max();  list.Min()
来源：http://dali.xuanzx.com/Article/details/gtpcsgcejb.html

[D18] 扁平化嵌套数组
来源：http://dali.c1oappe.top/Article/details/gtywzfwpel.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ehwqpu.com/Article/details/gtmphwoxbv.html

PHP:  array_merge(...$nested);
来源：http://dali.9152youxi.cn/Article/details/gtbgmmzzop.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhoulong.xyz/Article/details/gtmvbopizt.html

TS:   nested.flat();
来源：http://dali.hnxiangtu.top/Article/details/gtkwvmfywu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.vqdsnc.cn/Article/details/gtjhthhqfm.html

Go:   // 手写双层循环
来源：http://dali.snrcjt.cn/Article/details/gtdepalnwk.html

Ruby: nested.flatten
来源：http://dali.ydzc1.top/Article/details/gtxijkfxel.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtfsfypmhw.html

[D19] 按字段分组
来源：http://dali.havefunace.top/Article/details/gtyspenctq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yuxming.cn/Article/details/gtnptzihff.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hnqzz.top/Article/details/gtunewvsqg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yangfankeji.com/Article/details/gtbebayzgh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yonumen.top/Article/details/gtslwglfop.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.dianchejie.cn/Article/details/gthrggqeyz.html

Go:   // 手写 map[string][]T
来源：http://dali.xuanzx.com/Article/details/gtxwxioxey.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.tanke756.top/Article/details/gthoyxulhp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shangyingyoupin.top/Article/details/gtuwlkufrp.html

[D20] 统计每个元素出现次数
来源：http://dali.hfpthk.cn/Article/details/gtwjmsiods.html

Py:   Counter(arr)
来源：http://dali.havefunace.top/Article/details/gtllyptkim.html

PHP:  array_count_values($arr);
来源：http://dali.yuxming.cn/Article/details/gtpdhogkln.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbtsevfko.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtedjdgwda.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sysykeji.top/Article/details/gtcutlotvm.html

Go:   // 手写 map[T]int
来源：http://dali.feifeiyinyue.top/Article/details/gtbvcjxfwr.html

Ruby: arr.tally
来源：http://dali.nwbrower.top/Article/details/gtdkjyvzgp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.9152youxi.cn/Article/details/gtzbcildvk.html

[D21] 判断是否包含某元素
来源：http://dali.gotoacloud.top/Article/details/gtmrbnlqho.html

Py:   x in arr
来源：http://dali.cheryme.top/Article/details/gtvifwabpe.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shuidangran.top/Article/details/gtyrptxgxz.html

JS:   arr.includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gtqclugfyr.html

TS:   arr.includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gtretbkdhw.html

Java: list.contains(x)
来源：http://dali.cqqwz.cn/Article/details/gtbgijvolw.html

Go:   slices.Contains(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtezjhmdcr.html

Ruby: arr.include?(x)
来源：http://dali.nanxuanxn.top/Article/details/gtzsmvtzfl.html

C#:   list.Contains(x)
来源：http://dali.hysaishi.cn/Article/details/gtqaqwythj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.daxiang520.top/Article/details/gtfpriazhu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sysykeji.top/Article/details/gtutzahgmq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cucudq.cn/Article/details/gtgrzkfbvx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpylddsjr.html

TS:   [...arr];
来源：http://dali.xinyue.icu/Article/details/gtybiozpma.html

Java: new ArrayList<>(list);
来源：http://dali.daria6918.cn/Article/details/gtfcatsswa.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.tian-w.cn/Article/details/gtoeebexvh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.chenzaomai.com/Article/details/gtbarmxdri.html

C#:   new List<int>(list);
来源：http://dali.andypj.xyz/Article/details/gtuqunfrbi.html

[D23] reduce 累积计算
来源：http://dali.guowangkeji.top/Article/details/gtaioiklcm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.fengsongda.top/Article/details/gtepoewjyn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sufxvd.cn/Article/details/gtccypmoiu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yongpay.top/Article/details/gtaslitejb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigufen.top/Article/details/gtpsdtmrqf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.haohaochexian.top/Article/details/gtytnakrkw.html

Go:   // 手写循环
来源：http://dali.tanke756.top/Article/details/gtwwpwmamy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shanyushiyangkeji.top/Article/details/gthudrmqps.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.bjfxy.top/Article/details/gtfufmxfmc.html

[D24] 字典 / Map 基本操作
来源：http://dali.xuanzx.com/Article/details/gteeofjhxk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.0kj1m.cn/Article/details/gtlbstyjoi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jqgfzy.top/Article/details/gtofdhaluh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.daria6918.cn/Article/details/gtjaqmivxz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yueranfly.top/Article/details/gtnguvyafl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yvedp.cn/Article/details/gtkliciaqf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.nanxinkj.top/Article/details/gtsihisnnp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nanxuanxn.top/Article/details/gtxghqpfln.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shangyingyoupin.top/Article/details/gtquxdjqua.html

[D25] Set 集合去重与交并差
来源：http://dali.nanxinkj.top/Article/details/gtxcqsimzk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sxryk.cn/Article/details/gtcrxmdifq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xuetiantiany.cn/Article/details/gtsipbsntt.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.9152youxi.cn/Article/details/gtirgbagug.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.snrcjt.cn/Article/details/gtwvilxexu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.snrcjt.cn/Article/details/gtcmsnmvmk.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.316326.xyz/Article/details/gtdfgblpnm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hnxiangtu.top/Article/details/gtjecwambq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.daria6918.cn/Article/details/gtwcnixwdo.html

[D26] 数组转字符串
来源：http://dali.dashuyun.cn/Article/details/gtrfatnqnv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hnqzz.top/Article/details/gtecwhgkqf.html

PHP:  implode(", ", $arr);
来源：http://dali.nanxinkj.top/Article/details/gtvjcoyfay.html

JS:   arr.join(", ")
来源：http://dali.chenlongwang.top/Article/details/gtziusklal.html

TS:   arr.join(", ")
来源：http://dali.cashguo.top/Article/details/gtrxxewvga.html

Java: String.join(", ", list)
来源：http://dali.yj202588.top/Article/details/gtuuusgrnj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.chenjidiqi.icu/Article/details/gtyeztqubs.html

Ruby: arr.join(", ")
来源：http://dali.pengpengdd.cyou/Article/details/gtoalzlouo.html

C#:   string.Join(", ", list)
来源：http://dali.ppjwa.cn/Article/details/gtuywlpktq.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtxjfrxfgx.html

E. 字符串处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjrajlhir.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtnpeqjfvr.html

[E01] 拼接字符串
来源：http://dali.havefunace.top/Article/details/gtngtpundu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.dianchejie.cn/Article/details/gtovufcoyw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.dianchejie.cn/Article/details/gteeshcpnj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigufen.top/Article/details/gtijyhdpzw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.quarkkingdee.top/Article/details/gtgseobzfm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjqhgbiem.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.tanke756.top/Article/details/gtokbtqwns.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jqgufenzy.top/Article/details/gtqxkvdcyq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtjywdwzzw.html

[E02] 重复字符串
来源：http://dali.chenlongwang.top/Article/details/gtciejgonm.html

Py:   "ab" * 3
来源：http://dali.cdnleiting.top/Article/details/gtobrpbqth.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hammf.cn/Article/details/gtgftqjfpw.html

JS:   "ab".repeat(3)
来源：http://dali.jlsjyb.cn/Article/details/gtiruoottt.html

TS:   "ab".repeat(3)
来源：http://dali.aizwys.cn/Article/details/gtwxxkpatt.html

Java: "ab".repeat(3)
来源：http://dali.mhx1999.top/Article/details/gtqvriutsd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.andypj.xyz/Article/details/gtxllcamft.html

Ruby: "ab" * 3
来源：http://dali.andypj.xyz/Article/details/gtjkrpbmys.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.haohaochexian.top/Article/details/gtfxsljczj.html

[E03] 截取子串
来源：http://dali.cashguo.top/Article/details/gtgnjklola.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zycfv.cn/Article/details/gtzefzizln.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yongpay.top/Article/details/gtgvqyxeao.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwtkwzpvv.html

TS:   s.slice(1, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gtetponpsj.html

Java: s.substring(1, 4)
来源：http://dali.xziqi.cn/Article/details/gthaqksiwm.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gotoacloud.top/Article/details/gtnxqpmrtr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yj20258.top/Article/details/gtzyxjgqkv.html

C#:   s.Substring(1, 3)
来源：http://dali.aizwys.cn/Article/details/gtlmjzlwwt.html

[E04] 查找子串位置
来源：http://dali.zhixingplan.top/Article/details/gtzkhmaxhb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthpldmafa.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gtadfjkxtt.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.tanke756.top/Article/details/gtformcjjp.html

TS:   s.indexOf("x")
来源：http://dali.nanxuanxn.top/Article/details/gtarbotjne.html

Java: s.indexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gtmzgfbqmd.html

Go:   strings.Index(s, "x")
来源：http://dali.daxiang520.top/Article/details/gtzeaomuub.html

Ruby: s.index("x")
来源：http://dali.hywenlv.cn/Article/details/gtpndvqbgr.html

C#:   s.IndexOf("x")
来源：http://dali.chenjidiqi.icu/Article/details/gthnbucyxq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xziqi.cn/Article/details/gtocgjevvd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.guannengcc.top/Article/details/gtqiakhbyc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.chenjidiqi.icu/Article/details/gtqmuyuufh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hywenlv.cn/Article/details/gtlwzkkqco.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gteqplsqux.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.redwolf501.top/Article/details/gtlfplimer.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.nanxinkj.top/Article/details/gtmrodfohb.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.gogol.net.cn/Article/details/gtykhdfell.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jqgufenzy.top/Article/details/gtttbnlazf.html

[E06] 替换子串
来源：http://dali.hywenlv.cn/Article/details/gtvznogsld.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.tanke756.top/Article/details/gtxnanvowe.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.quarkkingdee.top/Article/details/gtzhusbrrg.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtncdmhgwk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gtdujsrnbv.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtztfmonzg.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ehwqpu.com/Article/details/gtwyzhiuzp.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtleopqzta.html

C#:   s.Replace("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtccoyqwbj.html

[E07] 按分隔符拆分
来源：http://dali.pengpengdd.cyou/Article/details/gtuvukkgxt.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gaohongyu789.top/Article/details/gtwzlgblyr.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtdnktvfpr.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yuanzhike.top/Article/details/gtjfgonqmx.html

TS:   s.split(",")
来源：http://dali.0kj1m.cn/Article/details/gtuzjvggvc.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hnxiangtu.top/Article/details/gtihbfpvhq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yonumen.top/Article/details/gtxpcpgkty.html

Ruby: s.split(",");  s.split
来源：http://dali.hfpthk.cn/Article/details/gthswaftdb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jinqigfzy.top/Article/details/gtkknltjkq.html

[E08] 数组按分隔符合并
来源：http://dali.shzxlz.cn/Article/details/gtrcrtgqnb.html

Py:   ",".join(items)
来源：http://dali.ppjwa.cn/Article/details/gtfmkbfuci.html

PHP:  implode(",", $items);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqmmwtivu.html

JS:   items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gtjiffdcuc.html

TS:   items.join(",")
来源：http://dali.tanke756.top/Article/details/gtjybuskio.html

Java: String.join(",", items)
来源：http://dali.zdqjudy.top/Article/details/gtvjtfkxoz.html

Go:   strings.Join(items, ",")
来源：http://dali.ppjwa.cn/Article/details/gtphouguzc.html

Ruby: items.join(",")
来源：http://dali.wangshuangyany.cn/Article/details/gtkajmqfkg.html

C#:   string.Join(",", items)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnnjdwfnb.html

[E09] 去除所有空白字符
来源：http://dali.jiagoushi.top/Article/details/gtppcikava.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.9152youxi.cn/Article/details/gtustyodmb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtucahyiml.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.andypj.xyz/Article/details/gtntumkiwi.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hammf.cn/Article/details/gterpwdgpe.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.tanke756.top/Article/details/gtzatkrvxx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdxigwrzb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhoulong.xyz/Article/details/gtzemgkvuu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.nanxinkj.top/Article/details/gtjdxijfek.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hysaishi.cn/Article/details/gtozjjtzfv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gtlyxbpzkk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.fzhhl.top/Article/details/gtjrhptsss.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gtvpqswnoa.html

TS:   "7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gtpknlfiyh.html

Java: String.format("%03d", 7)
来源：http://dali.aizwys.cn/Article/details/gtgfqmxjvy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sysykeji.top/Article/details/gtcgddoarw.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tanke756.top/Article/details/gtumytdlhn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yvedp.cn/Article/details/gtkrzhqygy.html

[E11] 反转字符串
来源：http://dali.fengsongda.top/Article/details/gtnvehjmxj.html

Py:   s[::-1]
来源：http://dali.yuxming.cn/Article/details/gttqkbiprh.html

PHP:  strrev($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlhxkvpqd.html

JS:   [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gtobdircoa.html

TS:   [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gtzmsqccva.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinqigufen.top/Article/details/gtwqvaravj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.nanxuanxn.top/Article/details/gtodmeiucx.html

Ruby: s.reverse
来源：http://dali.jiagoushi.top/Article/details/gthmsxmpyf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsvfkrwyt.html

[E12] 统计某字符出现次数
来源：http://dali.hywenlv.cn/Article/details/gtmibmnpoc.html

Py:   s.count("a")
来源：http://dali.zdqjudy.top/Article/details/gtrqqmefbo.html

PHP:  substr_count($s, "a");
来源：http://dali.yanxiufei.cn/Article/details/gtsrwpodga.html

JS:   s.split("a").length - 1
来源：http://dali.hfpthk.cn/Article/details/gtpiciqprj.html

TS:   s.split("a").length - 1
来源：http://dali.yuanzhike.top/Article/details/gtgeebofrn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.aizwys.cn/Article/details/gtkuutuoxb.html

Go:   strings.Count(s, "a")
来源：http://dali.jqgfzy.top/Article/details/gtvexiuyxz.html

Ruby: s.count("a")
来源：http://dali.haohaochexian.top/Article/details/gtzyuegvkj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.pengpengdd.cyou/Article/details/gtrgpvqbha.html

[E13] 逐字符遍历
来源：http://dali.zhengqikj.top/Article/details/gtswgwveoi.html

Py:   for ch in s: print(ch)
来源：http://dali.jiagoushi.top/Article/details/gtfmmutrjp.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.daxiang520.top/Article/details/gtciearrcc.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tianlin.xyz/Article/details/gtrhfaswxn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gotoacloud.top/Article/details/gtcgffrukn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jyoumei.cn/Article/details/gtntnqmgkm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.vqdsnc.cn/Article/details/gtqeuiwqqa.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ppjwa.cn/Article/details/gthzbitniy.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.316326.xyz/Article/details/gtklxcxnmf.html

[E14] URL 编码与 Base64
来源：http://dali.xuanzx.com/Article/details/gtlxyavgfr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.haohaochexian.top/Article/details/gthdjtngpt.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zdqjudy.top/Article/details/gtlvdvcyzk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhongyouzk.top/Article/details/gtumvoernb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.kuanghao11.cn/Article/details/gtrlfyotbr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gtimstxhmy.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.haohaochexian.top/Article/details/gtyrwvyydc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yangfankeji.com/Article/details/gtesmyhacl.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.gzhubu.top/Article/details/gtfpybihkq.html

[E15] HTML 转义 / 反转义
来源：http://dali.ppjwa.cn/Article/details/gtoahumevy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuadakwhm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gzhubu.top/Article/details/gturplxoxm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xinyue.icu/Article/details/gtnrchwveq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.meibo888.top/Article/details/gtbteskugq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.nwbrower.top/Article/details/gtqppufqef.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gogol.net.cn/Article/details/gtuzbmhigv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.tian-w.cn/Article/details/gtwkjevjoy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpkmajziu.html

[E16] 数字千分位
来源：http://dali.yonumen.top/Article/details/gtifauveun.html

Py:   f"{1234567:,}"
来源：http://dali.cucudq.cn/Article/details/gtqlxabjkh.html

PHP:  number_format(1234567);
来源：http://dali.cqqwz.cn/Article/details/gtpgvrkpbq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nwbrower.top/Article/details/gtnmckisgh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.havefunace.top/Article/details/gtyvzarsoz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenlongwang.top/Article/details/gtknwhamiu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tanke756.top/Article/details/gtjnhzgezo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.iojbl.cn/Article/details/gtxqitfvtf.html

C#:   1234567.ToString("N0")
来源：http://dali.cheryme.top/Article/details/gtjsyqnzns.html

[E17] 首字母大写
来源：http://dali.zhoulong.xyz/Article/details/gtdkylfiwx.html


<!-- 参考信息 -->