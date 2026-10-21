代发 wailian999

PHP:  sort($arr);
来源：http://dali.yj202588.top/Article/details/gtvfichbnz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shanyushiyangtech.top/Article/details/gtaleyhkar.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhongyouzk.top/Article/details/gtgrsxekgf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.316326.xyz/Article/details/gtjxoseuam.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtdaxmqtwj.html

Ruby: arr.sort
来源：http://dali.jyoumei.cn/Article/details/gtqolowbyv.html

C#:   list.Sort();
来源：http://dali.sweek.top/Article/details/gtoeqczazx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shzxlz.cn/Article/details/gthftwzbvv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cqqwz.cn/Article/details/gtdaymocnz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jqgufenzy.top/Article/details/gtudbclkpn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yongpay.top/Article/details/gtztfedeby.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnxiangtu.top/Article/details/gtiexrsnlq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.redwolf501.top/Article/details/gtsgafzdkv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hnxiangtu.top/Article/details/gtzzonirvd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gaohongyu789.top/Article/details/gtroxcdlqj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.nanxuanxn.top/Article/details/gtpnudjauj.html

[D11] 反转数组
来源：http://dali.cheryme.top/Article/details/gtvaltbgro.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.tanke756.top/Article/details/gturwpmgry.html

PHP:  array_reverse($arr);
来源：http://dali.0kj1m.cn/Article/details/gtcfjsazzm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.fengsongda.top/Article/details/gtslevrpoz.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gtbxuccseg.html

Java: Collections.reverse(list);
来源：http://dali.tianlin.xyz/Article/details/gtxfjzgjbg.html

Go:   slices.Reverse(arr)
来源：http://dali.xziqi.cn/Article/details/gtbhodxrhp.html

Ruby: arr.reverse
来源：http://dali.yj202588.top/Article/details/gtsopaghvu.html

C#:   list.Reverse();
来源：http://dali.yuxming.cn/Article/details/gtpwvihrng.html

[D12] 查找元素下标
来源：http://dali.kuanghao11.cn/Article/details/gtutjnieob.html

Py:   arr.index(x);  x in arr
来源：http://dali.yuanzhike.top/Article/details/gtqnybduef.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdzzlyltr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtulijxdvc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangdashe.top/Article/details/gtgpdxlzno.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ehwqpu.com/Article/details/gtaaqdmsfu.html

Go:   slices.Index(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlwpdmykt.html

Ruby: arr.index(x)
来源：http://dali.daria6918.cn/Article/details/gtfkpdijai.html

C#:   list.IndexOf(x);
来源：http://dali.jinghuilouyu.cn/Article/details/gtenbvcisf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnkudwttv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jqgufenzy.top/Article/details/gtqtfuhrdf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtwbmaigwz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yvedp.cn/Article/details/gtkqqcgdvy.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hywenlv.cn/Article/details/gtxcjtryfo.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.snrcjt.cn/Article/details/gtoqxhhqcz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yangfankeji.com/Article/details/gtxjouhmel.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yangfankeji.com/Article/details/gtngdovxbi.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtqvjlxzen.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xinyue.icu/Article/details/gtvvdiqbbz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xuanzx.com/Article/details/gtsdapddbq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.fengsongda.top/Article/details/gtjtlkhdbn.html

JS:   arr.map(x => x * 2)
来源：http://dali.hammf.cn/Article/details/gtmsufxnjw.html

TS:   arr.map(x => x * 2)
来源：http://dali.yonumen.top/Article/details/gtshvcsvyu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hnxiangtu.top/Article/details/gtfjfwduvy.html

Go:   // 手写循环
来源：http://dali.haohaochexian.top/Article/details/gtuswdjsle.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.haohaochexian.top/Article/details/gtnzvrgpac.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.nanxinkj.top/Article/details/gthycghjrt.html

[D15] 去重
来源：http://dali.chenzaomai.com/Article/details/gtjtsqtoaf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.guannengcc.top/Article/details/gtvrxywspv.html

PHP:  array_unique($arr);
来源：http://dali.jinqigufen.top/Article/details/gtwzqvfshm.html

JS:   [...new Set(arr)]
来源：http://dali.daxiang520.top/Article/details/gtlwzocrsd.html

TS:   [...new Set(arr)]
来源：http://dali.birdmap.top/Article/details/gtulmsblus.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.feifeiyinyue.top/Article/details/gtquxekaqw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.redwolf501.top/Article/details/gtjigxvatf.html

Ruby: arr.uniq
来源：http://dali.tian-w.cn/Article/details/gtpkzgpjbd.html

C#:   list.Distinct().ToList()
来源：http://dali.yj20258888.top/Article/details/gtfnqkwubt.html

[D16] 求和与平均值
来源：http://dali.zhoulong.xyz/Article/details/gtoomoerxk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ivvv.top/Article/details/gtbetrpvgi.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cdnleiting.top/Article/details/gtftczmtvx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yvedp.cn/Article/details/gtpraubaff.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.9152youxi.cn/Article/details/gtdgpdhhqy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.tian-w.cn/Article/details/gtcdwwukbg.html

Go:   // 手写循环累加
来源：http://dali.havefunace.top/Article/details/gtemqvhqfa.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.wangdashe.top/Article/details/gtaqnkkrlq.html

C#:   list.Sum();  list.Average()
来源：http://dali.cucudq.cn/Article/details/gtefqucpdb.html

[D17] 最大值与最小值
来源：http://dali.jinghuilouyu.cn/Article/details/gtdlnwvjhw.html

Py:   max(arr);  min(arr)
来源：http://dali.ydzc1.top/Article/details/gtrivtiddt.html

PHP:  max($arr);  min($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtcsvuwqyp.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yueranfly.top/Article/details/gtdrwkqajw.html

TS:   Math.max(...arr);
来源：http://dali.bjfxy.top/Article/details/gtlebzikhn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ppjwa.cn/Article/details/gtajfqyihp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ybcxt.top/Article/details/gtofkoupag.html

Ruby: arr.max;  arr.min
来源：http://dali.yanxiufei.cn/Article/details/gtcnhnffuw.html

C#:   list.Max();  list.Min()
来源：http://dali.ehwqpu.com/Article/details/gtipauwycs.html

[D18] 扁平化嵌套数组
来源：http://dali.smart0.xyz/Article/details/gtfgldxvem.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yueranfly.top/Article/details/gtzszaulyz.html

PHP:  array_merge(...$nested);
来源：http://dali.ppjwa.cn/Article/details/gtkfnzlmtz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.smart0.xyz/Article/details/gttpntfqxt.html

TS:   nested.flat();
来源：http://dali.tanke756.top/Article/details/gtmrwstdqi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gzhubu.top/Article/details/gtfumcefkx.html

Go:   // 手写双层循环
来源：http://dali.9152youxi.cn/Article/details/gtwglccfoz.html

Ruby: nested.flatten
来源：http://dali.cqqwz.cn/Article/details/gtykkdqcrd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yj20258888.top/Article/details/gtxxmcwykn.html

[D19] 按字段分组
来源：http://dali.gotoacloud.top/Article/details/gtafldvozu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.9152youxi.cn/Article/details/gtmmnrkmkw.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shuidangran.top/Article/details/gtboedpahf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yonumen.top/Article/details/gtkljlqchf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.guannengcc.top/Article/details/gtankscjvu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xinyue.icu/Article/details/gtyemjchkk.html

Go:   // 手写 map[string][]T
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoiaqtjkl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.vqdsnc.cn/Article/details/gtqzrmyjuw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.svipenyu.cn/Article/details/gthaknkuge.html

[D20] 统计每个元素出现次数
来源：http://dali.sxryk.cn/Article/details/gtdradrwdf.html

Py:   Counter(arr)
来源：http://dali.0kj1m.cn/Article/details/gtjovevjwa.html

PHP:  array_count_values($arr);
来源：http://dali.yueranfly.top/Article/details/gtfhlujtnu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgufenzy.top/Article/details/gtdzaisijw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangdashe.top/Article/details/gtpteodoau.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yuxming.cn/Article/details/gtroolarwo.html

Go:   // 手写 map[T]int
来源：http://dali.sufxvd.cn/Article/details/gtrxcesxww.html

Ruby: arr.tally
来源：http://dali.jiagoushi.top/Article/details/gtvyurbxxr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhiwuduotai.top/Article/details/gtcyblvqgk.html

[D21] 判断是否包含某元素
来源：http://dali.jiagoushi.top/Article/details/gtmkjwoszk.html

Py:   x in arr
来源：http://dali.tianlin.xyz/Article/details/gtltqsrifq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.wangshuangyany.cn/Article/details/gtaufeuilz.html

JS:   arr.includes(x)
来源：http://dali.0kj1m.cn/Article/details/gtyuwdiyeq.html

TS:   arr.includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gtpjzhtfuh.html

Java: list.contains(x)
来源：http://dali.xuanzx.com/Article/details/gtmmwbsvlp.html

Go:   slices.Contains(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtnbpubltp.html

Ruby: arr.include?(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtomdchsoj.html

C#:   list.Contains(x)
来源：http://dali.smart0.xyz/Article/details/gtgnqlntjd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ydzc1.top/Article/details/gtfpmllgew.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yuanzhike.top/Article/details/gtmjvjxfwv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ybcxt.top/Article/details/gtqdlverni.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yuanzhike.top/Article/details/gtpmnodwtz.html

TS:   [...arr];
来源：http://dali.cqqwz.cn/Article/details/gtczkjcjyq.html

Java: new ArrayList<>(list);
来源：http://dali.fengsongda.top/Article/details/gtsfyjkrym.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.pengpengdd.cyou/Article/details/gtgdjfjnac.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xinyue.icu/Article/details/gtlffhyvqr.html

C#:   new List<int>(list);
来源：http://dali.chenzaomai.com/Article/details/gtnywdqgba.html

[D23] reduce 累积计算
来源：http://dali.feifeiyinyue.top/Article/details/gtyxfactdx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiuraxlzx.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ehwqpu.com/Article/details/gtxsefvsid.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ppjwa.cn/Article/details/gthmljcyfd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.meibo888.top/Article/details/gtavjffksn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ybcxt.top/Article/details/gtwkdipeyb.html

Go:   // 手写循环
来源：http://dali.zhixingplan.top/Article/details/gthvczpmai.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hfpthk.cn/Article/details/gtykaexuij.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jqgufenzy.top/Article/details/gttnlzqhun.html

[D24] 字典 / Map 基本操作
来源：http://dali.cqqwz.cn/Article/details/gttxgoqbdi.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sysykeji.top/Article/details/gtzczjbyls.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hongshengwenyu.top/Article/details/gtkbrankcj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.dashuyun.cn/Article/details/gtfomerflm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.iojbl.cn/Article/details/gtfbvjkqkz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jianghu66.top/Article/details/gtkprugzea.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yanxiufei.cn/Article/details/gtqmfoumcu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhongyouzk.top/Article/details/gtyianwzoo.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jianghu66.top/Article/details/gtucbeaoeg.html

[D25] Set 集合去重与交并差
来源：http://dali.shanyushiyangtech.top/Article/details/gtheghnynl.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cheryme.top/Article/details/gtamuxgzrq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.smart0.xyz/Article/details/gtrdslosff.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gzhubu.top/Article/details/gtmvbyfyph.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.chenjidiqi.icu/Article/details/gtusoayqba.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.snrcjt.cn/Article/details/gtpcgjajxy.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xuetiantiany.cn/Article/details/gtzeitlolg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jlsjyb.cn/Article/details/gtrsbfewwq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.316326.xyz/Article/details/gtjzqqflmx.html

[D26] 数组转字符串
来源：http://dali.cqqwz.cn/Article/details/gtkxbcycik.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gtjyfxsubc.html

PHP:  implode(", ", $arr);
来源：http://dali.316326.xyz/Article/details/gtkodibpso.html

JS:   arr.join(", ")
来源：http://dali.snrcjt.cn/Article/details/gtuwczbxtc.html

TS:   arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gtluuomfak.html

Java: String.join(", ", list)
来源：http://dali.daria6918.cn/Article/details/gtxtotkboy.html

Go:   strings.Join(strs, ", ")
来源：http://dali.tanke756.top/Article/details/gtofmjqlrm.html

Ruby: arr.join(", ")
来源：http://dali.chenjidiqi.icu/Article/details/gtefvlljgo.html

C#:   string.Join(", ", list)
来源：http://dali.vqdsnc.cn/Article/details/gtseziyjiv.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtpeeieksm.html

E. 字符串处理
来源：http://dali.chenzaomai.com/Article/details/gtudnyjwsi.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtoskrvflx.html

[E01] 拼接字符串
来源：http://dali.zhengqikj.top/Article/details/gttawgpdfs.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.chenlongwang.top/Article/details/gttskhmitx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.tanke756.top/Article/details/gtikifdzja.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.haohaochexian.top/Article/details/gtbzfbdofr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.meibo888.top/Article/details/gttiuqjnzw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sufxvd.cn/Article/details/gtjqlmbzhy.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhongyouzk.top/Article/details/gtxemvjzys.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xuanzx.com/Article/details/gtqkyocvsr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hnqzz.top/Article/details/gtfkoroodc.html

[E02] 重复字符串
来源：http://dali.chenlongwang.top/Article/details/gtxglbmezt.html

Py:   "ab" * 3
来源：http://dali.shangyingyoupin.top/Article/details/gtfujensuk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.svipenyu.cn/Article/details/gtfeldxvjq.html

JS:   "ab".repeat(3)
来源：http://dali.xuanzx.com/Article/details/gtaijqvmgd.html

TS:   "ab".repeat(3)
来源：http://dali.aizwys.cn/Article/details/gtdvuztqti.html

Java: "ab".repeat(3)
来源：http://dali.haohaochexian.top/Article/details/gtayrpfrwv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgzdrtpnm.html

Ruby: "ab" * 3
来源：http://dali.quarkkingdee.top/Article/details/gtfazxnxgl.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.svipenyu.cn/Article/details/gtwrssskiu.html

[E03] 截取子串
来源：http://dali.yuanzhike.top/Article/details/gtlnscaaef.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.feifeiyinyue.top/Article/details/gtdfouqjtk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shangyingyoupin.top/Article/details/gtjmaductd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jianghu66.top/Article/details/gtokqhmydk.html

TS:   s.slice(1, 4)
来源：http://dali.jlsjyb.cn/Article/details/gtxxpyvlqe.html

Java: s.substring(1, 4)
来源：http://dali.c1oappe.top/Article/details/gtdmxfnvcv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.feifeiyinyue.top/Article/details/gtxyasvamb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxbqkzelg.html

C#:   s.Substring(1, 3)
来源：http://dali.ehwqpu.com/Article/details/gtjaxuounb.html

[E04] 查找子串位置
来源：http://dali.jlsjyb.cn/Article/details/gtooalnizm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jiagoushi.top/Article/details/gttaraepyr.html

PHP:  strpos($s, "x");
来源：http://dali.havefunace.top/Article/details/gtwizsqagz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtybppfiky.html

TS:   s.indexOf("x")
来源：http://dali.yuxming.cn/Article/details/gtdwqirbwo.html

Java: s.indexOf("x")
来源：http://dali.daxiang520.top/Article/details/gttsgbszqp.html

Go:   strings.Index(s, "x")
来源：http://dali.shangyingyoupin.top/Article/details/gtcxobqfeo.html

Ruby: s.index("x")
来源：http://dali.fzhhl.top/Article/details/gtcwsezffw.html

C#:   s.IndexOf("x")
来源：http://dali.hnxiangtu.top/Article/details/gtliwwwjow.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yongpay.top/Article/details/gtfapzluii.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cashguo.top/Article/details/gtrolmunoz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinqigufen.top/Article/details/gtjhbvrxta.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgufenzy.top/Article/details/gtghggrpze.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.svipenyu.cn/Article/details/gtalsykrqn.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cucudq.cn/Article/details/gtcpdbnhci.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hongshengwenyu.top/Article/details/gtydohbrlw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.daxiang520.top/Article/details/gtoxhdbpsc.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.316326.xyz/Article/details/gtfjjbmviy.html

[E06] 替换子串
来源：http://dali.svipenyu.cn/Article/details/gtulxmwdmk.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gtgkvxopaq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xziqi.cn/Article/details/gtpgzscttl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtaghpsonf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sweek.top/Article/details/gtqtexnpmd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cashguo.top/Article/details/gtypmqazza.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jlsjyb.cn/Article/details/gtiemmxswk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gtofeiewbw.html

C#:   s.Replace("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gtanivlyip.html

[E07] 按分隔符拆分
来源：http://dali.ywan-chungtsiang.top/Article/details/gtodwrregp.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jyoumei.cn/Article/details/gtdnyqbynr.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.meibo888.top/Article/details/gtohswkrjn.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinqigufen.top/Article/details/gtjaydppgx.html

TS:   s.split(",")
来源：http://dali.316326.xyz/Article/details/gtvqggcfpw.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xziqi.cn/Article/details/gthkfzkemz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.birdmap.top/Article/details/gtfmrmjzzd.html

Ruby: s.split(",");  s.split
来源：http://dali.tianlin.xyz/Article/details/gtxgsipefv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.mhx1999.top/Article/details/gttxwvpxao.html

[E08] 数组按分隔符合并
来源：http://dali.yonumen.top/Article/details/gtqnrcbvke.html

Py:   ",".join(items)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjauyhkcf.html

PHP:  implode(",", $items);
来源：http://dali.tian-w.cn/Article/details/gtqsumgyke.html

JS:   items.join(",")
来源：http://dali.havefunace.top/Article/details/gtnhnkzxoh.html

TS:   items.join(",")
来源：http://dali.sufxvd.cn/Article/details/gthsinmchg.html

Java: String.join(",", items)
来源：http://dali.zhoulong.xyz/Article/details/gtxdnnjrmo.html

Go:   strings.Join(items, ",")
来源：http://dali.andypj.xyz/Article/details/gthmdvwypd.html

Ruby: items.join(",")
来源：http://dali.zycfv.cn/Article/details/gtmwldnuxe.html

C#:   string.Join(",", items)
来源：http://dali.fengsongda.top/Article/details/gtlolhrawk.html

[E09] 去除所有空白字符
来源：http://dali.dashuyun.cn/Article/details/gtguqrhzxd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cheryme.top/Article/details/gtcjctztxb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtpwabgcwq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.iojbl.cn/Article/details/gtkbtinchm.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.daria6918.cn/Article/details/gteycqvmae.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hnqzz.top/Article/details/gtowzyamhh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhongyouzk.top/Article/details/gtuqfgzsmn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hammf.cn/Article/details/gtjzohliti.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.mhx1999.top/Article/details/gtkxmrnuzr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cqqwz.cn/Article/details/gtxfnhsjom.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.iojbl.cn/Article/details/gtimxiszuj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yuanzhike.top/Article/details/gtxtdlxyoy.html

JS:   "7".padStart(3, "0")
来源：http://dali.bjfxy.top/Article/details/gtmwjjayiq.html

TS:   "7".padStart(3, "0")
来源：http://dali.yongpay.top/Article/details/gtnyjvgpxk.html

Java: String.format("%03d", 7)
来源：http://dali.gogol.net.cn/Article/details/gtracfnbyl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtooijeoyb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gtxoyvmohd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.aizwys.cn/Article/details/gtiehaezku.html

[E11] 反转字符串
来源：http://dali.hywenlv.cn/Article/details/gtvwqhfwkl.html

Py:   s[::-1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyhujhvhr.html

PHP:  strrev($s);
来源：http://dali.hnqzz.top/Article/details/gtfispxoes.html

JS:   [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gtuxbatjvt.html

TS:   [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gtfeksyebp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.feifeiyinyue.top/Article/details/gtfupfnyxz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.mhx1999.top/Article/details/gtmczvqoui.html

Ruby: s.reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gtuxukhrpl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xziqi.cn/Article/details/gtdtlrmpzo.html

[E12] 统计某字符出现次数
来源：http://dali.jinghuilouyu.cn/Article/details/gtyjcnrerw.html

Py:   s.count("a")
来源：http://dali.pengpengdd.cyou/Article/details/gttwbyrqgh.html

PHP:  substr_count($s, "a");
来源：http://dali.yangfankeji.com/Article/details/gtcdiqbowv.html

JS:   s.split("a").length - 1
来源：http://dali.kuanghao11.cn/Article/details/gthdkwbzfe.html

TS:   s.split("a").length - 1
来源：http://dali.yanxiufei.cn/Article/details/gtegoomfto.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yueranfly.top/Article/details/gtoiwpyism.html

Go:   strings.Count(s, "a")
来源：http://dali.yj202588.top/Article/details/gtlyxsjqhu.html

Ruby: s.count("a")
来源：http://dali.havefunace.top/Article/details/gtcaczomxy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj20258888.top/Article/details/gtbydlcjqm.html

[E13] 逐字符遍历
来源：http://dali.jqgfzy.top/Article/details/gtqhjrxgxc.html

Py:   for ch in s: print(ch)
来源：http://dali.jinqigufen.top/Article/details/gtyiyrubny.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.fzhhl.top/Article/details/gtmucazgrq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guowangkeji.top/Article/details/gtttejqbpj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuxming.cn/Article/details/gtzlybwtqp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.daria6918.cn/Article/details/gttgazeclm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xinyue.icu/Article/details/gtsqgjxghr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jiagoushi.top/Article/details/gtdvjmtuet.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jiagoushi.top/Article/details/gteweliget.html

[E14] URL 编码与 Base64
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdurxggpb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinqigfzy.top/Article/details/gtsjkxrlsy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xziqi.cn/Article/details/gtxibntbir.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.havefunace.top/Article/details/gtoosrggaq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.0kj1m.cn/Article/details/gtbmsaycvm.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cashguo.top/Article/details/gtlwyksqte.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.fzhhl.top/Article/details/gtbhymrsct.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj20258888.top/Article/details/gtjguwizhx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.tanke756.top/Article/details/gtmqceaozt.html

[E15] HTML 转义 / 反转义
来源：http://dali.zdqjudy.top/Article/details/gtmguaaztp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.daria6918.cn/Article/details/gthybleqge.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hnqzz.top/Article/details/gtzppsljrs.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.vqdsnc.cn/Article/details/gtzhbrozbw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenjidiqi.icu/Article/details/gttapxswnz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hnqzz.top/Article/details/gtdlslprqf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.haohaochexian.top/Article/details/gtrapxkuqz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xylfe.cn/Article/details/gtasqnlnzj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.fengsongda.top/Article/details/gtafllclgo.html

[E16] 数字千分位
来源：http://dali.yongpay.top/Article/details/gtmkabbhzv.html

Py:   f"{1234567:,}"
来源：http://dali.hnxiangtu.top/Article/details/gtlsizajac.html


<!-- 参考信息 -->