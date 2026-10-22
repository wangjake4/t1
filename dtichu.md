代发 wailian999

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmtsitmyv.html

Ruby: arr.sort
来源：http://dali.shuidangran.top/Article/details/gtvveozaqe.html

C#:   list.Sort();
来源：http://dali.zdqjudy.top/Article/details/gtdjlxwulg.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shangyingyoupin.top/Article/details/gtlbbslrii.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gtevjjoflj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yuanzhike.top/Article/details/gthqjwqaqi.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pycfn.com/Article/details/gtgwoxezin.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuetiantiany.cn/Article/details/gthgklvdtb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.tian-w.cn/Article/details/gtmgpuahja.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppwonpjt.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gtaskfseuy.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jqgfzy.top/Article/details/gtztrnlxdi.html

[D11] 反转数组
来源：http://dali.yueranfly.top/Article/details/gtlbxhdexo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jianghu66.top/Article/details/gtmklaglkw.html

PHP:  array_reverse($arr);
来源：http://dali.ehwqpu.com/Article/details/gtyovvoznh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cashguo.top/Article/details/gtoznkxqna.html

TS:   [...arr].reverse();
来源：http://dali.jlsjyb.cn/Article/details/gtrrkwkibw.html

Java: Collections.reverse(list);
来源：http://dali.jinqigufen.top/Article/details/gtbjvgdyzv.html

Go:   slices.Reverse(arr)
来源：http://dali.iojbl.cn/Article/details/gtddhdjxwu.html

Ruby: arr.reverse
来源：http://dali.jlsjyb.cn/Article/details/gtoogxfsky.html

C#:   list.Reverse();
来源：http://dali.ehwqpu.com/Article/details/gtjfdxzord.html

[D12] 查找元素下标
来源：http://dali.jinqigufen.top/Article/details/gtirwkflln.html

Py:   arr.index(x);  x in arr
来源：http://dali.shanyushiyangtech.top/Article/details/gtmpwbylwm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.bjfxy.top/Article/details/gtwkzgjcpx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yongpay.top/Article/details/gtiamjnvhw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yangfankeji.com/Article/details/gtcisbxmnv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zdqjudy.top/Article/details/gtimpwpdfk.html

Go:   slices.Index(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtaxdqtcly.html

Ruby: arr.index(x)
来源：http://dali.fengsongda.top/Article/details/gttwiaabpq.html

C#:   list.IndexOf(x);
来源：http://dali.ybcxt.top/Article/details/gtwmfduyra.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hfpthk.cn/Article/details/gtpyncjmfs.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.wangshuangyany.cn/Article/details/gtvsgixsrn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jqgfzy.top/Article/details/gtgggharrw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.aizwys.cn/Article/details/gtayhlnlwg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yvedp.cn/Article/details/gtbyebglog.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jqgfzy.top/Article/details/gtfzrqcypf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtijdcfrst.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hammf.cn/Article/details/gtifoqgcgs.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xuanzx.com/Article/details/gteokqbhga.html

[D14] 映射转换（每个元素变形）
来源：http://dali.meibo888.top/Article/details/gtarjudduj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xuanzx.com/Article/details/gtuxobcezf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtkjtxlkjr.html

JS:   arr.map(x => x * 2)
来源：http://dali.sufxvd.cn/Article/details/gtgrjvcxly.html

TS:   arr.map(x => x * 2)
来源：http://dali.aizwys.cn/Article/details/gtvkmofawa.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtzcofhuwa.html

Go:   // 手写循环
来源：http://dali.jyoumei.cn/Article/details/gttnhggpia.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.chenlongwang.top/Article/details/gtkashhlee.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtrkryqapq.html

[D15] 去重
来源：http://dali.wangshuangyany.cn/Article/details/gtidmwrqvx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jyoumei.cn/Article/details/gtdkhgwzut.html

PHP:  array_unique($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtdgbkhnxq.html

JS:   [...new Set(arr)]
来源：http://dali.feifeiyinyue.top/Article/details/gtkxvpvjpz.html

TS:   [...new Set(arr)]
来源：http://dali.zhiwuduotai.top/Article/details/gtkxdhlpyh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnozgbkse.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.pycfn.com/Article/details/gtfhepsuzh.html

Ruby: arr.uniq
来源：http://dali.jiagoushi.top/Article/details/gtztqhgiis.html

C#:   list.Distinct().ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtxxrkkhux.html

[D16] 求和与平均值
来源：http://dali.sweek.top/Article/details/gthsnshuxf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.fengsongda.top/Article/details/gtpevfjmcq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtyknpsfeo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.mhx1999.top/Article/details/gthejsnagv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtnklnlfpg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ehwqpu.com/Article/details/gtluolhpxe.html

Go:   // 手写循环累加
来源：http://dali.aibaodan.cn/Article/details/gtcynavzin.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.svipenyu.cn/Article/details/gtuixbjthj.html

C#:   list.Sum();  list.Average()
来源：http://dali.quarkkingdee.top/Article/details/gtkcjalbsq.html

[D17] 最大值与最小值
来源：http://dali.chenjidiqi.icu/Article/details/gtwayvoqfn.html

Py:   max(arr);  min(arr)
来源：http://dali.yuxming.cn/Article/details/gtipzxhxnh.html

PHP:  max($arr);  min($arr);
来源：http://dali.birdmap.top/Article/details/gtdagbuxso.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cdnleiting.top/Article/details/gtuuceqkjc.html

TS:   Math.max(...arr);
来源：http://dali.ybcxt.top/Article/details/gtqvbrcfem.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yangfankeji.com/Article/details/gtwtzdciqr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.0kj1m.cn/Article/details/gtewqghnje.html

Ruby: arr.max;  arr.min
来源：http://dali.jqgufenzy.top/Article/details/gtoqhgnhtz.html

C#:   list.Max();  list.Min()
来源：http://dali.vqdsnc.cn/Article/details/gtnxmijdhf.html

[D18] 扁平化嵌套数组
来源：http://dali.chenzaomai.com/Article/details/gthrcstlms.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.0kj1m.cn/Article/details/gtrqefjjpx.html

PHP:  array_merge(...$nested);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtduxqglzw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.9152youxi.cn/Article/details/gtivhkgkto.html

TS:   nested.flat();
来源：http://dali.wangshuangyany.cn/Article/details/gtwihzscdu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yuanzhike.top/Article/details/gtkoigvyax.html

Go:   // 手写双层循环
来源：http://dali.guannengcc.top/Article/details/gtbwwxqgce.html

Ruby: nested.flatten
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzugrkocg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hammf.cn/Article/details/gtslogndhl.html

[D19] 按字段分组
来源：http://dali.yvedp.cn/Article/details/gtlrefszhs.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.dianchejie.cn/Article/details/gthnryvsbi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cucudq.cn/Article/details/gtrlgmbsvl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.guannengcc.top/Article/details/gtuilbyjjk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cucudq.cn/Article/details/gtzvozxiup.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhiwuduotai.top/Article/details/gtwjhiijun.html

Go:   // 手写 map[string][]T
来源：http://dali.iojbl.cn/Article/details/gtklfbnbtm.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinghuilouyu.cn/Article/details/gtoaqsrnih.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gzhubu.top/Article/details/gtryjqmwmn.html

[D20] 统计每个元素出现次数
来源：http://dali.birdmap.top/Article/details/gtztoeugge.html

Py:   Counter(arr)
来源：http://dali.tanke756.top/Article/details/gtxweoicqd.html

PHP:  array_count_values($arr);
来源：http://dali.hysaishi.cn/Article/details/gtnvqjgvvm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.snrcjt.cn/Article/details/gtzghigwcw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dianchejie.cn/Article/details/gtuijkzffh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hnqzz.top/Article/details/gtusfcntyp.html

Go:   // 手写 map[T]int
来源：http://dali.cheryme.top/Article/details/gtitsptpzs.html

Ruby: arr.tally
来源：http://dali.haohaochexian.top/Article/details/gtnuqotolc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.vqdsnc.cn/Article/details/gtwykcxawe.html

[D21] 判断是否包含某元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyasfrauv.html

Py:   x in arr
来源：http://dali.xinyue.icu/Article/details/gtgjhsojst.html

PHP:  in_array($x, $arr, true);
来源：http://dali.aibaodan.cn/Article/details/gtgqxxhzdf.html

JS:   arr.includes(x)
来源：http://dali.yuxming.cn/Article/details/gtjtqkvczy.html

TS:   arr.includes(x)
来源：http://dali.daxiang520.top/Article/details/gtcwcjwxzw.html

Java: list.contains(x)
来源：http://dali.mhx1999.top/Article/details/gtpkokcahq.html

Go:   slices.Contains(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwgjujyip.html

Ruby: arr.include?(x)
来源：http://dali.hysaishi.cn/Article/details/gtculieiie.html

C#:   list.Contains(x)
来源：http://dali.sufxvd.cn/Article/details/gteshxaqwz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.iojbl.cn/Article/details/gtyrffobar.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.fengsongda.top/Article/details/gtvrohnate.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sxryk.cn/Article/details/gthbtjfgnz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.guannengcc.top/Article/details/gtxmxkatwb.html

TS:   [...arr];
来源：http://dali.daxiang520.top/Article/details/gtvryqkgpp.html

Java: new ArrayList<>(list);
来源：http://dali.svipenyu.cn/Article/details/gtultzbtxt.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhiwuduotai.top/Article/details/gtuxzkhmob.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yonumen.top/Article/details/gtbwwkbcqi.html

C#:   new List<int>(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtstlaijzo.html

[D23] reduce 累积计算
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjaxdzyvf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtjdvtfzbm.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.meibo888.top/Article/details/gtycptvqzt.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.mhx1999.top/Article/details/gtklvhqqiy.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.svipenyu.cn/Article/details/gtvnplggru.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sxryk.cn/Article/details/gtsxxesory.html

Go:   // 手写循环
来源：http://dali.nwbrower.top/Article/details/gtrudaozuc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gtjovvijkv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.wangshuangyany.cn/Article/details/gtiucpnapq.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdyuwakxa.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sufxvd.cn/Article/details/gtckxnqwlg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jqgfzy.top/Article/details/gtyftqoukk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtjiehkcby.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtkxosqovf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gtojdpbvot.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.316326.xyz/Article/details/gtbwdhmpdk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cqqwz.cn/Article/details/gtakobabqg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zycfv.cn/Article/details/gtvdlakklq.html

[D25] Set 集合去重与交并差
来源：http://dali.smart0.xyz/Article/details/gtgcheulno.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.feifeiyinyue.top/Article/details/gtdykzjabe.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.316326.xyz/Article/details/gtthswrghr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.316326.xyz/Article/details/gtmzcyecbl.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yongpay.top/Article/details/gtmpweeadi.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hnqzz.top/Article/details/gtntgjbtta.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.havefunace.top/Article/details/gtwitlbjyr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ybcxt.top/Article/details/gtrftthcbu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinqigufen.top/Article/details/gtschryyeg.html

[D26] 数组转字符串
来源：http://dali.cqqwz.cn/Article/details/gtympjdhvp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcwhocejx.html

PHP:  implode(", ", $arr);
来源：http://dali.yj20258.top/Article/details/gtzeamgxrr.html

JS:   arr.join(", ")
来源：http://dali.ydzc1.top/Article/details/gtbqtwfbkr.html

TS:   arr.join(", ")
来源：http://dali.zhixingplan.top/Article/details/gtuupyhhwl.html

Java: String.join(", ", list)
来源：http://dali.xziqi.cn/Article/details/gtakkevfol.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hammf.cn/Article/details/gtkcofgfmq.html

Ruby: arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gtubfennrd.html

C#:   string.Join(", ", list)
来源：http://dali.zycfv.cn/Article/details/gtocuqchec.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtqpmqrzoc.html

E. 字符串处理
来源：http://dali.hysaishi.cn/Article/details/gtnkfbixuk.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtglyjijfc.html

[E01] 拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gtwqtsxqum.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shzxlz.cn/Article/details/gtbfimuajn.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hammf.cn/Article/details/gttbdiujtc.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cdnleiting.top/Article/details/gtjurytmmj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tian-w.cn/Article/details/gthyxktsal.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.chenzaomai.com/Article/details/gtiwopvjcs.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jlsjyb.cn/Article/details/gtbohytukm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yuxming.cn/Article/details/gtgthqcmtu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtjdhkgdwn.html

[E02] 重复字符串
来源：http://dali.kuanghao11.cn/Article/details/gtxbewinle.html

Py:   "ab" * 3
来源：http://dali.yuanzhike.top/Article/details/gtnjwxtxlp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtuqlqpsjo.html

JS:   "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gtchcahqml.html

TS:   "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gtiyivfxpm.html

Java: "ab".repeat(3)
来源：http://dali.yonumen.top/Article/details/gtvkxqhnuo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaxktsybq.html

Ruby: "ab" * 3
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgyygyrcd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zdqjudy.top/Article/details/gtsagvmvpa.html

[E03] 截取子串
来源：http://dali.zhengqikj.top/Article/details/gtcfxhfbwp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.meibo888.top/Article/details/gtvcgpxdzu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gtbxqnsfkn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.fengsongda.top/Article/details/gtxtxxdbvh.html

TS:   s.slice(1, 4)
来源：http://dali.havefunace.top/Article/details/gtppiazcbz.html

Java: s.substring(1, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtajmyndaa.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.birdmap.top/Article/details/gtmyqsjcnh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.tian-w.cn/Article/details/gtthpfrnbk.html

C#:   s.Substring(1, 3)
来源：http://dali.yj20258888.top/Article/details/gtmnumzgdq.html

[E04] 查找子串位置
来源：http://dali.chenjidiqi.icu/Article/details/gtzsmnorov.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cdnleiting.top/Article/details/gtcebcxtha.html

PHP:  strpos($s, "x");
来源：http://dali.snrcjt.cn/Article/details/gtufitmuzk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ehwqpu.com/Article/details/gtkalfsjjw.html

TS:   s.indexOf("x")
来源：http://dali.fzhhl.top/Article/details/gtbsstngxo.html

Java: s.indexOf("x")
来源：http://dali.aibaodan.cn/Article/details/gtraougbxd.html

Go:   strings.Index(s, "x")
来源：http://dali.meibo888.top/Article/details/gtirumslov.html

Ruby: s.index("x")
来源：http://dali.redwolf501.top/Article/details/gtmyremcfn.html

C#:   s.IndexOf("x")
来源：http://dali.wangdashe.top/Article/details/gtacpcyqno.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.chenlongwang.top/Article/details/gtobysiwkj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.svipenyu.cn/Article/details/gtrkoclxcu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.quarkkingdee.top/Article/details/gtllhtabhl.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gttffhemor.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtlromvind.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gzhubu.top/Article/details/gtrkzhqnmk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.0kj1m.cn/Article/details/gtgmjecerh.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cucudq.cn/Article/details/gtxgigpttr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gzhubu.top/Article/details/gtgadfoeud.html

[E06] 替换子串
来源：http://dali.jlsjyb.cn/Article/details/gtjqlwztyy.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.quarkkingdee.top/Article/details/gtebpniomz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jianghu66.top/Article/details/gtsskpjrnm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtsctzdzmj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtaltdoniw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hammf.cn/Article/details/gtrbhsgqxi.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jianghu66.top/Article/details/gtooovldmk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hammf.cn/Article/details/gtfnrcymct.html

C#:   s.Replace("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtxqdsxsry.html

[E07] 按分隔符拆分
来源：http://dali.jqgufenzy.top/Article/details/gtwiaiskhb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gtfvtvxaso.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cdnleiting.top/Article/details/gtfrclmnpz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj202588.top/Article/details/gtvhdlyzns.html

TS:   s.split(",")
来源：http://dali.316326.xyz/Article/details/gteclttwro.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hnqzz.top/Article/details/gtogauylat.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgswphehe.html

Ruby: s.split(",");  s.split
来源：http://dali.sysykeji.top/Article/details/gtjzbdhvfm.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.daria6918.cn/Article/details/gtjappfgra.html

[E08] 数组按分隔符合并
来源：http://dali.guannengcc.top/Article/details/gtgxjybkfr.html

Py:   ",".join(items)
来源：http://dali.fzhhl.top/Article/details/gtbxntiihu.html

PHP:  implode(",", $items);
来源：http://dali.jyoumei.cn/Article/details/gtwgkmfezu.html

JS:   items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gtjgxwrkek.html

TS:   items.join(",")
来源：http://dali.smart0.xyz/Article/details/gtsocnibio.html

Java: String.join(",", items)
来源：http://dali.cqqwz.cn/Article/details/gtpbdgnwkw.html

Go:   strings.Join(items, ",")
来源：http://dali.ehwqpu.com/Article/details/gtklsntfab.html

Ruby: items.join(",")
来源：http://dali.zhoulong.xyz/Article/details/gtqnyvsqxp.html

C#:   string.Join(",", items)
来源：http://dali.ydzc1.top/Article/details/gthlymxweq.html

[E09] 去除所有空白字符
来源：http://dali.dianchejie.cn/Article/details/gtypmpfkjl.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinqigufen.top/Article/details/gtnsaoxufq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tian-w.cn/Article/details/gtejrscqzh.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sysykeji.top/Article/details/gtrodwwhpk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigfzy.top/Article/details/gtqbwibulq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.guannengcc.top/Article/details/gtkslnathd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hnxiangtu.top/Article/details/gtkaeqgbqr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.iojbl.cn/Article/details/gtjdkglyfc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.snrcjt.cn/Article/details/gtfxjsgxcf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cdnleiting.top/Article/details/gtdmbgduwz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gtvwvcaznm.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gtoegjmtpb.html

JS:   "7".padStart(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gtbrbotctl.html

TS:   "7".padStart(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gtbzelqlgj.html

Java: String.format("%03d", 7)
来源：http://dali.snrcjt.cn/Article/details/gtvtaqnfpl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqqqqxlbb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gttastaeqx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinqigufen.top/Article/details/gtqdkeuonn.html

[E11] 反转字符串
来源：http://dali.xinyue.icu/Article/details/gtuffzvahy.html

Py:   s[::-1]
来源：http://dali.smart0.xyz/Article/details/gtguupfgcy.html

PHP:  strrev($s);
来源：http://dali.nanxuanxn.top/Article/details/gtbrlxjfcu.html

JS:   [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gtaapvinoc.html

TS:   [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gtevsnnpny.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.kuanghao11.cn/Article/details/gtqnydalak.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.iojbl.cn/Article/details/gtqjilzacw.html

Ruby: s.reverse
来源：http://dali.cashguo.top/Article/details/gtbgjvzydg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sysykeji.top/Article/details/gtvmuuvpgv.html

[E12] 统计某字符出现次数
来源：http://dali.hammf.cn/Article/details/gtweqjwhnf.html

Py:   s.count("a")
来源：http://dali.dianchejie.cn/Article/details/gtruqyvrut.html

PHP:  substr_count($s, "a");
来源：http://dali.gaohongyu789.top/Article/details/gtwpviwjmu.html

JS:   s.split("a").length - 1
来源：http://dali.cucudq.cn/Article/details/gtyqwpsyha.html

TS:   s.split("a").length - 1
来源：http://dali.yvedp.cn/Article/details/gtkymyzmbt.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.bjfxy.top/Article/details/gtyxpmirgc.html

Go:   strings.Count(s, "a")
来源：http://dali.aibaodan.cn/Article/details/gtpnfkvzsl.html

Ruby: s.count("a")
来源：http://dali.gotoacloud.top/Article/details/gtaqokhydt.html

C#:   s.Count(c => c == 'a')
来源：http://dali.aizwys.cn/Article/details/gtyovrfool.html

[E13] 逐字符遍历
来源：http://dali.yvedp.cn/Article/details/gtrpmlwctk.html

Py:   for ch in s: print(ch)
来源：http://dali.hnqzz.top/Article/details/gteyrxicps.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtelxauanw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xinyue.icu/Article/details/gtlmvmngqr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenzaomai.com/Article/details/gtaewsdhsj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gzhubu.top/Article/details/gtfmvmkjcl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cheryme.top/Article/details/gthcyipqhw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.9152youxi.cn/Article/details/gtdgflltoc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.316326.xyz/Article/details/gtmodofmbx.html

[E14] URL 编码与 Base64
来源：http://dali.jqgfzy.top/Article/details/gtieshyivn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gaohongyu789.top/Article/details/gtrjltkncr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gaohongyu789.top/Article/details/gtsfqjtrme.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.0kj1m.cn/Article/details/gtcwcgkzlz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtmbezaupn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cashguo.top/Article/details/gthvnsjpkt.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtldeuqown.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yuanzhike.top/Article/details/gtetsexqfn.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hfpthk.cn/Article/details/gtlnvlicdt.html

[E15] HTML 转义 / 反转义
来源：http://dali.dianchejie.cn/Article/details/gtsnvkqipn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.tanke756.top/Article/details/gtkpzippwx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.havefunace.top/Article/details/gtojubzbnt.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zdqjudy.top/Article/details/gteekuajhn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.pengpengdd.cyou/Article/details/gtepeqvswt.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhoulong.xyz/Article/details/gtcphyatpr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.kuanghao11.cn/Article/details/gtenhmsipw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthribqoav.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hnxiangtu.top/Article/details/gtyezqzvvs.html

[E16] 数字千分位
来源：http://dali.9152youxi.cn/Article/details/gtfalzopfs.html

Py:   f"{1234567:,}"
来源：http://dali.chenzaomai.com/Article/details/gtekjwfagt.html

PHP:  number_format(1234567);
来源：http://dali.vqdsnc.cn/Article/details/gtxohsxnll.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.kuanghao11.cn/Article/details/gtvcriqcmr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ppjwa.cn/Article/details/gtkdphfqcx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.tanke756.top/Article/details/gtlfiabzlc.html


<!-- 参考信息 -->