代发 wailian999

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.316326.xyz/Article/details/gtzoonndfg.html

Ruby: arr.sort
来源：http://dali.yangfankeji.com/Article/details/gtdqkhgvld.html

C#:   list.Sort();
来源：http://dali.cucudq.cn/Article/details/gtoihgvsqg.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.andypj.xyz/Article/details/gtuklieeaz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.havefunace.top/Article/details/gtawtgegmj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258888.top/Article/details/gtuhomcjgy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sysykeji.top/Article/details/gtoajnhpwy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yonumen.top/Article/details/gtjytdnrdd.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.chenzaomai.com/Article/details/gtacnzgrgm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenjidiqi.icu/Article/details/gtkimkjtiu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.chenzaomai.com/Article/details/gtzpdjmaoz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.316326.xyz/Article/details/gtatvcamgd.html

[D11] 反转数组
来源：http://dali.xziqi.cn/Article/details/gtevvbkbck.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtypnrgzbr.html

PHP:  array_reverse($arr);
来源：http://dali.jyoumei.cn/Article/details/gtupvcpkjb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jyoumei.cn/Article/details/gtslkaatfc.html

TS:   [...arr].reverse();
来源：http://dali.yangfankeji.com/Article/details/gtwpbisfmu.html

Java: Collections.reverse(list);
来源：http://dali.hywenlv.cn/Article/details/gtvboihvac.html

Go:   slices.Reverse(arr)
来源：http://dali.pycfn.com/Article/details/gtnvihfjex.html

Ruby: arr.reverse
来源：http://dali.pycfn.com/Article/details/gtycsmhept.html

C#:   list.Reverse();
来源：http://dali.fzhhl.top/Article/details/gtvghfaces.html

[D12] 查找元素下标
来源：http://dali.sweek.top/Article/details/gtmtlghdlg.html

Py:   arr.index(x);  x in arr
来源：http://dali.smart0.xyz/Article/details/gtqgzkgkuh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.svipenyu.cn/Article/details/gtnqkxyctf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dianchejie.cn/Article/details/gtcmqmdocc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.snrcjt.cn/Article/details/gtqtbyyjvh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.316326.xyz/Article/details/gtnnmqujku.html

Go:   slices.Index(arr, x)
来源：http://dali.havefunace.top/Article/details/gtoebcmxby.html

Ruby: arr.index(x)
来源：http://dali.shzxlz.cn/Article/details/gtoavbtvfa.html

C#:   list.IndexOf(x);
来源：http://dali.zhoulong.xyz/Article/details/gtclljacow.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhoulong.xyz/Article/details/gtyljxhpio.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxitjimom.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yangfankeji.com/Article/details/gtyxyoilcj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cheryme.top/Article/details/gtplaxtbre.html

TS:   arr.filter(x => x > 3)
来源：http://dali.birdmap.top/Article/details/gtjnizyxqo.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.tian-w.cn/Article/details/gtbzvjmzok.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jqgfzy.top/Article/details/gtqyqigcvo.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcdhwpmhp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinqigufen.top/Article/details/gtifieyqay.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yonumen.top/Article/details/gtlmcrbawf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jqgufenzy.top/Article/details/gtcpxuefqi.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.nanxuanxn.top/Article/details/gtwmeojtow.html

JS:   arr.map(x => x * 2)
来源：http://dali.gogol.net.cn/Article/details/gtmmgbiurf.html

TS:   arr.map(x => x * 2)
来源：http://dali.svipenyu.cn/Article/details/gtvsabwioy.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zycfv.cn/Article/details/gtzcfqelsf.html

Go:   // 手写循环
来源：http://dali.jlsjyb.cn/Article/details/gtmdikaoaz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gtgqnbavuh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtkutbdvvc.html

[D15] 去重
来源：http://dali.sysykeji.top/Article/details/gtevwobmou.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gogol.net.cn/Article/details/gtcydjdbbj.html

PHP:  array_unique($arr);
来源：http://dali.zhengqikj.top/Article/details/gtxwwqhrqa.html

JS:   [...new Set(arr)]
来源：http://dali.ydzc1.top/Article/details/gtcvbxtmyz.html

TS:   [...new Set(arr)]
来源：http://dali.aizwys.cn/Article/details/gtwloohnka.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtturjwriz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xinyue.icu/Article/details/gtcolnnbse.html

Ruby: arr.uniq
来源：http://dali.hfpthk.cn/Article/details/gtqufqflbh.html

C#:   list.Distinct().ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtnoxhgqlt.html

[D16] 求和与平均值
来源：http://dali.jyoumei.cn/Article/details/gthkzochxn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gzhubu.top/Article/details/gtvutjgrfg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yongpay.top/Article/details/gthvyjyucv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zycfv.cn/Article/details/gtbqixuggp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtwtkflhrf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ivvv.top/Article/details/gtkljhaabb.html

Go:   // 手写循环累加
来源：http://dali.birdmap.top/Article/details/gtfslbklly.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlotvbxbr.html

C#:   list.Sum();  list.Average()
来源：http://dali.jianghu66.top/Article/details/gthjgbbhcy.html

[D17] 最大值与最小值
来源：http://dali.hnqzz.top/Article/details/gtndggsckq.html

Py:   max(arr);  min(arr)
来源：http://dali.daria6918.cn/Article/details/gtepvmzsma.html

PHP:  max($arr);  min($arr);
来源：http://dali.hysaishi.cn/Article/details/gtabmpcfgl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsddhrddu.html

TS:   Math.max(...arr);
来源：http://dali.yj20258888.top/Article/details/gtdjkrebua.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.quarkkingdee.top/Article/details/gtxcapveua.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.tian-w.cn/Article/details/gtoviyaqdw.html

Ruby: arr.max;  arr.min
来源：http://dali.zhixingplan.top/Article/details/gthofzcjhj.html

C#:   list.Max();  list.Min()
来源：http://dali.gzhubu.top/Article/details/gthcarsrhm.html

[D18] 扁平化嵌套数组
来源：http://dali.ppjwa.cn/Article/details/gtrrgdbpgb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hfpthk.cn/Article/details/gtooaonfps.html

PHP:  array_merge(...$nested);
来源：http://dali.jqgufenzy.top/Article/details/gtswlvasay.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cucudq.cn/Article/details/gtufcmdkrl.html

TS:   nested.flat();
来源：http://dali.wangshuangyany.cn/Article/details/gtanfrnppu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtagyaxkib.html

Go:   // 手写双层循环
来源：http://dali.nwbrower.top/Article/details/gtecmftrcj.html

Ruby: nested.flatten
来源：http://dali.gzhubu.top/Article/details/gttwijicjk.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.meibo888.top/Article/details/gtlybzlvoz.html

[D19] 按字段分组
来源：http://dali.chenjidiqi.icu/Article/details/gtarczjlop.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.chenlongwang.top/Article/details/gtuhbnvzxx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhongyouzk.top/Article/details/gtfrljsxsn.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ivvv.top/Article/details/gtwesitgls.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hongshengwenyu.top/Article/details/gtjazqkhbc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.mhx1999.top/Article/details/gtzodzbmbi.html

Go:   // 手写 map[string][]T
来源：http://dali.kuanghao11.cn/Article/details/gtwrtkuxpa.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hongshengwenyu.top/Article/details/gtsfvafqdm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.quarkkingdee.top/Article/details/gteozfqlxh.html

[D20] 统计每个元素出现次数
来源：http://dali.pengpengdd.cyou/Article/details/gtfyivzkjx.html

Py:   Counter(arr)
来源：http://dali.gzhubu.top/Article/details/gtvuzdjczi.html

PHP:  array_count_values($arr);
来源：http://dali.hywenlv.cn/Article/details/gtuqslgirz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yueranfly.top/Article/details/gtfcrtjvlb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.iojbl.cn/Article/details/gtornwgotn.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhongyouzk.top/Article/details/gtpjgjkkzo.html

Go:   // 手写 map[T]int
来源：http://dali.zycfv.cn/Article/details/gtpsvwstlc.html

Ruby: arr.tally
来源：http://dali.ybcxt.top/Article/details/gtsrwzhgop.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yvedp.cn/Article/details/gtzvjyfcbt.html

[D21] 判断是否包含某元素
来源：http://dali.vqdsnc.cn/Article/details/gtiwmqpsyp.html

Py:   x in arr
来源：http://dali.hysaishi.cn/Article/details/gtexpjuhzu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.nanxuanxn.top/Article/details/gtfigoillm.html

JS:   arr.includes(x)
来源：http://dali.dashuyun.cn/Article/details/gtrkzxqdll.html

TS:   arr.includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrftluyxu.html

Java: list.contains(x)
来源：http://dali.sxryk.cn/Article/details/gthmerlwng.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtyncomlqx.html

Ruby: arr.include?(x)
来源：http://dali.yongpay.top/Article/details/gtcsulqzsz.html

C#:   list.Contains(x)
来源：http://dali.bjfxy.top/Article/details/gtkmyzkocg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hywenlv.cn/Article/details/gtumvydqmg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xinyue.icu/Article/details/gtbkvwflle.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yongpay.top/Article/details/gtgpdzpbvx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.c1oappe.top/Article/details/gtgqgnaueu.html

TS:   [...arr];
来源：http://dali.snrcjt.cn/Article/details/gtdwdxepmu.html

Java: new ArrayList<>(list);
来源：http://dali.snrcjt.cn/Article/details/gtsvukptse.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jyoumei.cn/Article/details/gtxrmnovlu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gotoacloud.top/Article/details/gteffjlhpl.html

C#:   new List<int>(list);
来源：http://dali.wangdashe.top/Article/details/gtxmwmohkm.html

[D23] reduce 累积计算
来源：http://dali.jianghu66.top/Article/details/gtkxzuhhht.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yj20258.top/Article/details/gtpmdxjhpj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gogol.net.cn/Article/details/gtukvwywvf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dianchejie.cn/Article/details/gtvelguden.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guannengcc.top/Article/details/gtqdtgoeqh.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.svipenyu.cn/Article/details/gtgbptovlh.html

Go:   // 手写循环
来源：http://dali.hongshengwenyu.top/Article/details/gtgdyikcfw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.tianlin.xyz/Article/details/gtaxduuppm.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hywenlv.cn/Article/details/gtnwoeuwrx.html

[D24] 字典 / Map 基本操作
来源：http://dali.havefunace.top/Article/details/gtekjxqpgl.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jiagoushi.top/Article/details/gtbyzclmqd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.nanxuanxn.top/Article/details/gtjntazcny.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.0kj1m.cn/Article/details/gtdabaxjhk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.wangdashe.top/Article/details/gtuhyervsj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jianghu66.top/Article/details/gtsqaqwoum.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shzxlz.cn/Article/details/gtihxsbprb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nanxuanxn.top/Article/details/gtxwwmopzq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gotoacloud.top/Article/details/gtjvgllkmz.html

[D25] Set 集合去重与交并差
来源：http://dali.cheryme.top/Article/details/gtowcwdpme.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cdnleiting.top/Article/details/gtwqugmhkc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.316326.xyz/Article/details/gtrihtyaxa.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cqqwz.cn/Article/details/gthrydozmv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yvedp.cn/Article/details/gtvbwxkvfb.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.aizwys.cn/Article/details/gtrpahxrnn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.fengsongda.top/Article/details/gtilyhsevs.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sxryk.cn/Article/details/gtpdtptaxl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yuxming.cn/Article/details/gtkutrpgal.html

[D26] 数组转字符串
来源：http://dali.vqdsnc.cn/Article/details/gtoftguobi.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj20258.top/Article/details/gtocranlqh.html

PHP:  implode(", ", $arr);
来源：http://dali.yj20258888.top/Article/details/gtiththcaw.html

JS:   arr.join(", ")
来源：http://dali.zycfv.cn/Article/details/gtmbcriddh.html

TS:   arr.join(", ")
来源：http://dali.sweek.top/Article/details/gtektvndfq.html

Java: String.join(", ", list)
来源：http://dali.cdnleiting.top/Article/details/gtldgvefwb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ivvv.top/Article/details/gtlxpetcqk.html

Ruby: arr.join(", ")
来源：http://dali.quarkkingdee.top/Article/details/gtgwfsmckx.html

C#:   string.Join(", ", list)
来源：http://dali.wangdashe.top/Article/details/gtkkwqbcpu.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtwdqcnazv.html

E. 字符串处理
来源：http://dali.vqdsnc.cn/Article/details/gtwfcxhfqg.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gthcuksjbu.html

[E01] 拼接字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtbizoglgg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.nwbrower.top/Article/details/gtteebaohb.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xinyue.icu/Article/details/gtlzrissew.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jqgufenzy.top/Article/details/gtllytonka.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fengsongda.top/Article/details/gtancvluur.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhongyouzk.top/Article/details/gtjtvtfzlh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hnxiangtu.top/Article/details/gtvpmypndl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yj20258888.top/Article/details/gtzjcgayst.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtpasbkylk.html

[E02] 重复字符串
来源：http://dali.xuanzx.com/Article/details/gtrzmewepn.html

Py:   "ab" * 3
来源：http://dali.pengpengdd.cyou/Article/details/gtcqeehewx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yuxming.cn/Article/details/gtbeblwizq.html

JS:   "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gtqnhdxuzu.html

TS:   "ab".repeat(3)
来源：http://dali.jlsjyb.cn/Article/details/gtujwkenms.html

Java: "ab".repeat(3)
来源：http://dali.zhoulong.xyz/Article/details/gtxhghanin.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.fzhhl.top/Article/details/gtvrmrqifh.html

Ruby: "ab" * 3
来源：http://dali.kuanghao11.cn/Article/details/gtleibtndv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nanxuanxn.top/Article/details/gtlsmmlyky.html

[E03] 截取子串
来源：http://dali.dianchejie.cn/Article/details/gtxumigvzb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shuidangran.top/Article/details/gtinmqonol.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gtkyptphfe.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xylfe.cn/Article/details/gtevpimjat.html

TS:   s.slice(1, 4)
来源：http://dali.sxryk.cn/Article/details/gtxmcalytq.html

Java: s.substring(1, 4)
来源：http://dali.jqgufenzy.top/Article/details/gtoeqiigxk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zdqjudy.top/Article/details/gtrdkyivjp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.tanke756.top/Article/details/gtaveovcov.html

C#:   s.Substring(1, 3)
来源：http://dali.gogol.net.cn/Article/details/gtycnptvxf.html

[E04] 查找子串位置
来源：http://dali.9152youxi.cn/Article/details/gtynlongnj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.meibo888.top/Article/details/gtpcaejrxj.html

PHP:  strpos($s, "x");
来源：http://dali.ehwqpu.com/Article/details/gtcwituqne.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yongpay.top/Article/details/gtiuaupjpw.html

TS:   s.indexOf("x")
来源：http://dali.jlsjyb.cn/Article/details/gtevjbugtp.html

Java: s.indexOf("x")
来源：http://dali.nanxinkj.top/Article/details/gteacdgqim.html

Go:   strings.Index(s, "x")
来源：http://dali.shuidangran.top/Article/details/gtmxdgdeqt.html

Ruby: s.index("x")
来源：http://dali.jianghu66.top/Article/details/gtmfvqkpqx.html

C#:   s.IndexOf("x")
来源：http://dali.chenlongwang.top/Article/details/gtbnsrwveu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.tanke756.top/Article/details/gtmuhulmqd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ppjwa.cn/Article/details/gtkzfjwpde.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.dashuyun.cn/Article/details/gtneygncsb.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.birdmap.top/Article/details/gtdackednt.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.316326.xyz/Article/details/gtuxmwjpgz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dianchejie.cn/Article/details/gtxiuavvuw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthularkcw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gtjlwdzwjf.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jyoumei.cn/Article/details/gtctpdwzkm.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gtzuwocuvl.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.fzhhl.top/Article/details/gtnawlwaqh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhengqikj.top/Article/details/gtojeebewj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtapijeomu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gtblfocuyv.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gtwmjivdsr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ydzc1.top/Article/details/gtkczuswne.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.smart0.xyz/Article/details/gtyackfshk.html

C#:   s.Replace("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtspevueqn.html

[E07] 按分隔符拆分
来源：http://dali.chenlongwang.top/Article/details/gtfgcnucse.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.havefunace.top/Article/details/gttgzetevg.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.c1oappe.top/Article/details/gtcaqoxlic.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.smart0.xyz/Article/details/gtmcdtxkca.html

TS:   s.split(",")
来源：http://dali.cashguo.top/Article/details/gtsxbwqcna.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.wangdashe.top/Article/details/gtuixqtulg.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtprcomapq.html

Ruby: s.split(",");  s.split
来源：http://dali.zhongyouzk.top/Article/details/gtbxyiubjs.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.feifeiyinyue.top/Article/details/gtyznrgfjx.html

[E08] 数组按分隔符合并
来源：http://dali.feifeiyinyue.top/Article/details/gtzgqalhpq.html

Py:   ",".join(items)
来源：http://dali.pengpengdd.cyou/Article/details/gtovfhipnz.html

PHP:  implode(",", $items);
来源：http://dali.gotoacloud.top/Article/details/gtwdrhsrbz.html

JS:   items.join(",")
来源：http://dali.xylfe.cn/Article/details/gterwieavo.html

TS:   items.join(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttnwchiku.html

Java: String.join(",", items)
来源：http://dali.iojbl.cn/Article/details/gtieviewxl.html

Go:   strings.Join(items, ",")
来源：http://dali.tianlin.xyz/Article/details/gtbbggkkir.html

Ruby: items.join(",")
来源：http://dali.yj20258.top/Article/details/gttrzatvsw.html

C#:   string.Join(",", items)
来源：http://dali.cheryme.top/Article/details/gtfdhoizos.html

[E09] 去除所有空白字符
来源：http://dali.shangyingyoupin.top/Article/details/gtmfxcnysh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ppjwa.cn/Article/details/gtuwjxuvwg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.0kj1m.cn/Article/details/gterxktjla.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shuidangran.top/Article/details/gtzmgjwqtz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenjidiqi.icu/Article/details/gtslzhmtzz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cheryme.top/Article/details/gtkywpbfzi.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.andypj.xyz/Article/details/gtgqjhmvxo.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenlongwang.top/Article/details/gtnzxztlnd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jinqigufen.top/Article/details/gtzhvdnxdw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhaomingkeji.xyz/Article/details/gtielasqtf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cheryme.top/Article/details/gttnzrnjfl.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhengqikj.top/Article/details/gtwoaaxfph.html

JS:   "7".padStart(3, "0")
来源：http://dali.316326.xyz/Article/details/gtotdgwnmh.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrjsvdebe.html

Java: String.format("%03d", 7)
来源：http://dali.ivvv.top/Article/details/gtkzgllclx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yueranfly.top/Article/details/gtmkkezcfk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gtwshzmufc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xuanzx.com/Article/details/gtmazqitht.html

[E11] 反转字符串
来源：http://dali.tanke756.top/Article/details/gtcajwvqzg.html

Py:   s[::-1]
来源：http://dali.yj20258.top/Article/details/gtetzokbzv.html

PHP:  strrev($s);
来源：http://dali.smart0.xyz/Article/details/gtflkjsvst.html

JS:   [...s].reverse().join("")
来源：http://dali.ehwqpu.com/Article/details/gtxmekgejk.html

TS:   [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtilejwzsf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jqgfzy.top/Article/details/gtaripchaj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gotoacloud.top/Article/details/gtehaaymeg.html

Ruby: s.reverse
来源：http://dali.ydzc1.top/Article/details/gteououkue.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtemspzjvd.html

[E12] 统计某字符出现次数
来源：http://dali.sysykeji.top/Article/details/gtlbgfkies.html

Py:   s.count("a")
来源：http://dali.yongpay.top/Article/details/gtycvjtqmu.html

PHP:  substr_count($s, "a");
来源：http://dali.hongshengwenyu.top/Article/details/gtgdzvkorv.html

JS:   s.split("a").length - 1
来源：http://dali.zhongyouzk.top/Article/details/gtgovuuaal.html

TS:   s.split("a").length - 1
来源：http://dali.nanxuanxn.top/Article/details/gtprtslkrw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cqqwz.cn/Article/details/gtmnrrhzfg.html

Go:   strings.Count(s, "a")
来源：http://dali.shangyingyoupin.top/Article/details/gtlfuutjsu.html

Ruby: s.count("a")
来源：http://dali.ydzc1.top/Article/details/gtgipeemfn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhengqikj.top/Article/details/gtowhozihz.html

[E13] 逐字符遍历
来源：http://dali.vqdsnc.cn/Article/details/gtlneffgav.html

Py:   for ch in s: print(ch)
来源：http://dali.xuanzx.com/Article/details/gtyjvtayfl.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shzxlz.cn/Article/details/gtmivqaiog.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hammf.cn/Article/details/gtbnhcwjdz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shzxlz.cn/Article/details/gtdrtqmpwz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.0kj1m.cn/Article/details/gtczrhhgkw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.vqdsnc.cn/Article/details/gtmccnnbgf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.iojbl.cn/Article/details/gtblytfjqf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gtneomilqq.html

[E14] URL 编码与 Base64
来源：http://dali.xziqi.cn/Article/details/gtmrbcnpgx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hfpthk.cn/Article/details/gtqfugiypd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xinyue.icu/Article/details/gtejjqeqpx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xuanzx.com/Article/details/gtammgmxif.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gzhubu.top/Article/details/gtfsysquuw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hysaishi.cn/Article/details/gtjkxitrhm.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.kuanghao11.cn/Article/details/gtdypjkzkq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ehwqpu.com/Article/details/gtxluruvzl.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.9152youxi.cn/Article/details/gtbrgkxrhs.html

[E15] HTML 转义 / 反转义
来源：http://dali.jqgufenzy.top/Article/details/gtqtdqmeit.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zdqjudy.top/Article/details/gtucyvgdni.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yuxming.cn/Article/details/gtzexpikgx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sufxvd.cn/Article/details/gtinfoilbj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtwpdbvwxk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hnxiangtu.top/Article/details/gtxciygxmu.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.0kj1m.cn/Article/details/gtswycgijo.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.c1oappe.top/Article/details/gtsdcajkvz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.dianchejie.cn/Article/details/gtcotwiifl.html

[E16] 数字千分位
来源：http://dali.jlsjyb.cn/Article/details/gtlbanfoaq.html

Py:   f"{1234567:,}"
来源：http://dali.xylfe.cn/Article/details/gtasqyernz.html

PHP:  number_format(1234567);
来源：http://dali.shangyingyoupin.top/Article/details/gtelabdzzf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sufxvd.cn/Article/details/gtahlaghyn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tianlin.xyz/Article/details/gtzobyryev.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xinyue.icu/Article/details/gtmokxsaqc.html


<!-- 参考信息 -->