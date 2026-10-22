代发 wailian999

[D07] 切片 / 取子数组
来源：http://dali.zycfv.cn/Article/details/gtqxsjnonb.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shzxlz.cn/Article/details/gtemgxmmjd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hysaishi.cn/Article/details/gtvckmskve.html

JS:   arr.slice(1, 4);
来源：http://dali.bjfxy.top/Article/details/gtioklbcez.html

TS:   arr.slice(1, 4);
来源：http://dali.jinqigfzy.top/Article/details/gtxeecdcvi.html

Java: list.subList(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gttscgdgcy.html

Go:   arr[1:4]
来源：http://dali.quarkkingdee.top/Article/details/gtropydcjr.html

Ruby: arr[1, 3]
来源：http://dali.yj20258.top/Article/details/gtklnpvdeg.html

C#:   list.GetRange(1, 3);
来源：http://dali.fzhhl.top/Article/details/gtlexcqwyi.html

[D08] 合并两个数组
来源：http://dali.iojbl.cn/Article/details/gtbwrtmmvb.html

Py:   a + b;  a.extend(b)
来源：http://dali.shuidangran.top/Article/details/gtkorctupf.html

PHP:  array_merge($a, $b);
来源：http://dali.shangyingyoupin.top/Article/details/gtgcaindhj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.nwbrower.top/Article/details/gtjgmocprj.html

TS:   [...a, ...b];
来源：http://dali.feifeiyinyue.top/Article/details/gteyjjpeaf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.fzhhl.top/Article/details/gthegmjytp.html

Go:   append(a, b...)
来源：http://dali.redwolf501.top/Article/details/gtacaxwaml.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cqqwz.cn/Article/details/gtpcvivdpr.html

C#:   a.Concat(b).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtpaejxfjf.html

[D09] 排序（升序）
来源：http://dali.ppjwa.cn/Article/details/gtwhsxvxwo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.meibo888.top/Article/details/gtvzhvisst.html

PHP:  sort($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtslwyqupc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yuanzhike.top/Article/details/gttahdcsbp.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jiagoushi.top/Article/details/gtylihqtbe.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.nanxinkj.top/Article/details/gtojggvzqj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hammf.cn/Article/details/gtpzmcsfqv.html

Ruby: arr.sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtczqogacu.html

C#:   list.Sort();
来源：http://dali.chenlongwang.top/Article/details/gtwczleiok.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jlsjyb.cn/Article/details/gtbsoggqxb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.redwolf501.top/Article/details/gtohdhiozr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xinyue.icu/Article/details/gthkonoaxm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tian-w.cn/Article/details/gtxbojuoqn.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.quarkkingdee.top/Article/details/gtrrhsoepa.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhongyouzk.top/Article/details/gtgnuriuuw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.nwbrower.top/Article/details/gtqzaffjtu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hywenlv.cn/Article/details/gtnubnwrsu.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhiwuduotai.top/Article/details/gtqryqfnxl.html

[D11] 反转数组
来源：http://dali.nwbrower.top/Article/details/gtjeoixxtf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhoulong.xyz/Article/details/gtpokcuzcf.html

PHP:  array_reverse($arr);
来源：http://dali.birdmap.top/Article/details/gtvvvxnjxl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jlsjyb.cn/Article/details/gtybqnsudd.html

TS:   [...arr].reverse();
来源：http://dali.hysaishi.cn/Article/details/gtzaxszdlo.html

Java: Collections.reverse(list);
来源：http://dali.kuanghao11.cn/Article/details/gtylxxnkmp.html

Go:   slices.Reverse(arr)
来源：http://dali.chenzaomai.com/Article/details/gtwytxetwb.html

Ruby: arr.reverse
来源：http://dali.sufxvd.cn/Article/details/gtsdfyycgk.html

C#:   list.Reverse();
来源：http://dali.cashguo.top/Article/details/gtnssbwwvc.html

[D12] 查找元素下标
来源：http://dali.jinghuilouyu.cn/Article/details/gthwlqvfyp.html

Py:   arr.index(x);  x in arr
来源：http://dali.feifeiyinyue.top/Article/details/gtnwhnurtz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xuanzx.com/Article/details/gtrazpxwfr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xylfe.cn/Article/details/gtgauyoykx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhengqikj.top/Article/details/gtgcmkphry.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gaohongyu789.top/Article/details/gtetgsqgik.html

Go:   slices.Index(arr, x)
来源：http://dali.cheryme.top/Article/details/gtpgmjlydv.html

Ruby: arr.index(x)
来源：http://dali.quarkkingdee.top/Article/details/gtmgwwahhd.html

C#:   list.IndexOf(x);
来源：http://dali.chenjidiqi.icu/Article/details/gtucwuyztf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.andypj.xyz/Article/details/gthkttbfcv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cheryme.top/Article/details/gtmrqsxnoz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yueranfly.top/Article/details/gttihoaddj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jyoumei.cn/Article/details/gtqutzbasc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yuxming.cn/Article/details/gtjyqoggwj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.chenlongwang.top/Article/details/gtezswogzj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shanyushiyangtech.top/Article/details/gthuvgjdwn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.pengpengdd.cyou/Article/details/gtpcdtlpze.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcfxwwuqb.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jqgfzy.top/Article/details/gthjpacxwf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gturyrmreo.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhengqikj.top/Article/details/gtiihynqqw.html

JS:   arr.map(x => x * 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtilcayoql.html

TS:   arr.map(x => x * 2)
来源：http://dali.hammf.cn/Article/details/gtixxpowjw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cdnleiting.top/Article/details/gtyasgaztd.html

Go:   // 手写循环
来源：http://dali.kuanghao11.cn/Article/details/gturrmgemh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zdqjudy.top/Article/details/gtycescamy.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinqigufen.top/Article/details/gtpxaljrug.html

[D15] 去重
来源：http://dali.c1oappe.top/Article/details/gteqsjjhqn.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.tianlin.xyz/Article/details/gtownnzzkm.html

PHP:  array_unique($arr);
来源：http://dali.c1oappe.top/Article/details/gtkxxucfog.html

JS:   [...new Set(arr)]
来源：http://dali.kuanghao11.cn/Article/details/gtlehwbuvd.html

TS:   [...new Set(arr)]
来源：http://dali.jqgufenzy.top/Article/details/gtwgooomis.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cdnleiting.top/Article/details/gtbdhlrbxa.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hfpthk.cn/Article/details/gtfzswrkoi.html

Ruby: arr.uniq
来源：http://dali.cucudq.cn/Article/details/gtrotsojjt.html

C#:   list.Distinct().ToList()
来源：http://dali.mhx1999.top/Article/details/gtyspnerdu.html

[D16] 求和与平均值
来源：http://dali.feifeiyinyue.top/Article/details/gtyrcqraeh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.tianlin.xyz/Article/details/gtgxnlmbvi.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hnqzz.top/Article/details/gtjjpdxozo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.andypj.xyz/Article/details/gtwakuhizf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cdnleiting.top/Article/details/gtxlwocmzq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.smart0.xyz/Article/details/gtnoxonymi.html

Go:   // 手写循环累加
来源：http://dali.cqqwz.cn/Article/details/gttrykctdu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.chenjidiqi.icu/Article/details/gtagntcpes.html

C#:   list.Sum();  list.Average()
来源：http://dali.shuidangran.top/Article/details/gtpksiozbn.html

[D17] 最大值与最小值
来源：http://dali.0kj1m.cn/Article/details/gtiafrbjzp.html

Py:   max(arr);  min(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtgpifykxs.html

PHP:  max($arr);  min($arr);
来源：http://dali.yongpay.top/Article/details/gtailyetxo.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yonumen.top/Article/details/gtxdfksyaf.html

TS:   Math.max(...arr);
来源：http://dali.xziqi.cn/Article/details/gtbimzzznn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xinyue.icu/Article/details/gtodrmhhkh.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hnqzz.top/Article/details/gthbetnwll.html

Ruby: arr.max;  arr.min
来源：http://dali.zhixingplan.top/Article/details/gtzlslxnqm.html

C#:   list.Max();  list.Min()
来源：http://dali.hammf.cn/Article/details/gtnujevpku.html

[D18] 扁平化嵌套数组
来源：http://dali.shanyushiyangtech.top/Article/details/gtltwnsfta.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.guannengcc.top/Article/details/gthbzjficp.html

PHP:  array_merge(...$nested);
来源：http://dali.daxiang520.top/Article/details/gtsypylzuu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jqgufenzy.top/Article/details/gtgezlveet.html

TS:   nested.flat();
来源：http://dali.yueranfly.top/Article/details/gtaehinzyq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.iojbl.cn/Article/details/gtihzbogha.html

Go:   // 手写双层循环
来源：http://dali.sysykeji.top/Article/details/gtzaobjlng.html

Ruby: nested.flatten
来源：http://dali.hnqzz.top/Article/details/gtjboqlite.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.daxiang520.top/Article/details/gtwibcbaqd.html

[D19] 按字段分组
来源：http://dali.zhoulong.xyz/Article/details/gtuydnrswe.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hnqzz.top/Article/details/gtazuubhhe.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.daxiang520.top/Article/details/gtgaowsgdi.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.tianlin.xyz/Article/details/gtonqabvng.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gzhubu.top/Article/details/gtmumockxp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sysykeji.top/Article/details/gtrhbpfxbi.html

Go:   // 手写 map[string][]T
来源：http://dali.zycfv.cn/Article/details/gtdykbrztr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.tian-w.cn/Article/details/gtekauzhcb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jyoumei.cn/Article/details/gteqetafey.html

[D20] 统计每个元素出现次数
来源：http://dali.shanyushiyangtech.top/Article/details/gtqlqviuic.html

Py:   Counter(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtnpdjjoeb.html

PHP:  array_count_values($arr);
来源：http://dali.chenlongwang.top/Article/details/gtyuntrsfd.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrxgzlwea.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gaohongyu789.top/Article/details/gtraoyraoi.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ivvv.top/Article/details/gtusyxiqza.html

Go:   // 手写 map[T]int
来源：http://dali.zycfv.cn/Article/details/gtfyjrbowh.html

Ruby: arr.tally
来源：http://dali.yonumen.top/Article/details/gtmpfqamqh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shangyingyoupin.top/Article/details/gtgrxljmcy.html

[D21] 判断是否包含某元素
来源：http://dali.yj20258888.top/Article/details/gtqfjquprm.html

Py:   x in arr
来源：http://dali.zhoulong.xyz/Article/details/gtqlcxilir.html

PHP:  in_array($x, $arr, true);
来源：http://dali.fzhhl.top/Article/details/gtksgbuvpg.html

JS:   arr.includes(x)
来源：http://dali.sxryk.cn/Article/details/gtgbhzctmk.html

TS:   arr.includes(x)
来源：http://dali.yvedp.cn/Article/details/gtorjmmrnd.html

Java: list.contains(x)
来源：http://dali.hfpthk.cn/Article/details/gttaxevfpd.html

Go:   slices.Contains(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtwnfeapdi.html

Ruby: arr.include?(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtngyharsz.html

C#:   list.Contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gtfonhxhvx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ehwqpu.com/Article/details/gtvzdmpfvp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtlyiobuxr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenzaomai.com/Article/details/gtwpmscwux.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xuanzx.com/Article/details/gtgspoxtkx.html

TS:   [...arr];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtatedbnkd.html

Java: new ArrayList<>(list);
来源：http://dali.shangyingyoupin.top/Article/details/gthkfeuefr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.tian-w.cn/Article/details/gtvipbreku.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ehwqpu.com/Article/details/gtqrdjexhr.html

C#:   new List<int>(list);
来源：http://dali.sysykeji.top/Article/details/gtsezcytnb.html

[D23] reduce 累积计算
来源：http://dali.sweek.top/Article/details/gtdxwhfkap.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.daxiang520.top/Article/details/gtmeaghujc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yuxming.cn/Article/details/gtwjosvxac.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgfzy.top/Article/details/gtznebytyg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xylfe.cn/Article/details/gtxuhftbqq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yuxming.cn/Article/details/gtkdnmxure.html

Go:   // 手写循环
来源：http://dali.chenjidiqi.icu/Article/details/gtpnkzvbde.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cashguo.top/Article/details/gtapnefnnx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sweek.top/Article/details/gtmtpfzjno.html

[D24] 字典 / Map 基本操作
来源：http://dali.cqqwz.cn/Article/details/gtrhbwwlij.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yanxiufei.cn/Article/details/gtqzpmeqbw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yueranfly.top/Article/details/gtemohbnfl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yongpay.top/Article/details/gtfeceuwzh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yuxming.cn/Article/details/gtrhlbjili.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwptylqnd.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfbadwhyx.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xuetiantiany.cn/Article/details/gtosgpjvqw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.tianlin.xyz/Article/details/gtqoasvaht.html

[D25] Set 集合去重与交并差
来源：http://dali.xziqi.cn/Article/details/gtrttgewkz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.vqdsnc.cn/Article/details/gtdmxbsnrc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.fengsongda.top/Article/details/gteshirmoe.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenlongwang.top/Article/details/gtdcynnwvt.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.pycfn.com/Article/details/gtwsdvndzh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yanxiufei.cn/Article/details/gtnizkfbhr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.c1oappe.top/Article/details/gtnkzlzotc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yueranfly.top/Article/details/gtqxjidrni.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tianlin.xyz/Article/details/gtofitxtei.html

[D26] 数组转字符串
来源：http://dali.yj20258.top/Article/details/gtueszarbm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.guannengcc.top/Article/details/gtysegqbxa.html

PHP:  implode(", ", $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtljeqtgfe.html

JS:   arr.join(", ")
来源：http://dali.yj202588.top/Article/details/gtldxeeffy.html

TS:   arr.join(", ")
来源：http://dali.daria6918.cn/Article/details/gtzmlfqvym.html

Java: String.join(", ", list)
来源：http://dali.yj20258888.top/Article/details/gtlqusoxrg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yangfankeji.com/Article/details/gtxhwujezd.html

Ruby: arr.join(", ")
来源：http://dali.cheryme.top/Article/details/gtwytoxqir.html

C#:   string.Join(", ", list)
来源：http://dali.jyoumei.cn/Article/details/gtgfksmygq.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtadrqpuxm.html

E. 字符串处理
来源：http://dali.andypj.xyz/Article/details/gtshlbtlsn.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtcrbhbgci.html

[E01] 拼接字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtmgyqpvbc.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.wangdashe.top/Article/details/gtxudsorap.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yuanzhike.top/Article/details/gtzfrmiich.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ydzc1.top/Article/details/gtrstzeldp.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ydzc1.top/Article/details/gtgjagbnhu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.mhx1999.top/Article/details/gtjzdyblwt.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.tanke756.top/Article/details/gtkhvyurzc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yj20258.top/Article/details/gtfvbldmvj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtyvkhyhjp.html

[E02] 重复字符串
来源：http://dali.haohaochexian.top/Article/details/gtwxsiojzd.html

Py:   "ab" * 3
来源：http://dali.ehwqpu.com/Article/details/gthhxbechg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.guannengcc.top/Article/details/gtyqvtairn.html

JS:   "ab".repeat(3)
来源：http://dali.xuanzx.com/Article/details/gtydrwmhlp.html

TS:   "ab".repeat(3)
来源：http://dali.xylfe.cn/Article/details/gtieufgsan.html

Java: "ab".repeat(3)
来源：http://dali.hnqzz.top/Article/details/gthnahafzk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ivvv.top/Article/details/gtvmvtsnva.html

Ruby: "ab" * 3
来源：http://dali.nanxinkj.top/Article/details/gtwfwjmmei.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.dashuyun.cn/Article/details/gtqnrclfuu.html

[E03] 截取子串
来源：http://dali.ivvv.top/Article/details/gtawqgkqbr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hnxiangtu.top/Article/details/gtgfhabvmh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gtebwmpqxq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shuidangran.top/Article/details/gtjiquxogz.html

TS:   s.slice(1, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gtujkuxawz.html

Java: s.substring(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gtirczqvax.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.guowangkeji.top/Article/details/gtykgnlhjg.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ppjwa.cn/Article/details/gtacgvaxki.html

C#:   s.Substring(1, 3)
来源：http://dali.gogol.net.cn/Article/details/gtwkbsckhd.html

[E04] 查找子串位置
来源：http://dali.xziqi.cn/Article/details/gtdjrchwcy.html

Py:   s.find("x");  s.index("x")
来源：http://dali.316326.xyz/Article/details/gtiropzmpw.html

PHP:  strpos($s, "x");
来源：http://dali.ydzc1.top/Article/details/gtltkgtezb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxaeeowrp.html

TS:   s.indexOf("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbohjnjhy.html

Java: s.indexOf("x")
来源：http://dali.jqgufenzy.top/Article/details/gtgydsavyt.html

Go:   strings.Index(s, "x")
来源：http://dali.chenzaomai.com/Article/details/gtjrnnpxaq.html

Ruby: s.index("x")
来源：http://dali.tanke756.top/Article/details/gtmuqjxito.html

C#:   s.IndexOf("x")
来源：http://dali.jqgfzy.top/Article/details/gtaoghpwhi.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hammf.cn/Article/details/gtdtynmjai.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cashguo.top/Article/details/gtmsbldyog.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.nanxuanxn.top/Article/details/gtacpsyvfx.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hfpthk.cn/Article/details/gteboedmza.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ppjwa.cn/Article/details/gtzcfxsaoe.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnxiangtu.top/Article/details/gtdggwiwsv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shanyushiyangtech.top/Article/details/gtccpdqwlg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jqgfzy.top/Article/details/gtavnxufah.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sweek.top/Article/details/gtsazbfgcc.html

[E06] 替换子串
来源：http://dali.hywenlv.cn/Article/details/gtsqvfiogm.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sysykeji.top/Article/details/gtjmcxagqj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zycfv.cn/Article/details/gtnflfutci.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtrgkupvlw.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtnwuezeum.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gtatehavyo.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinqigfzy.top/Article/details/gtouqjomhe.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtuzzymqyb.html

C#:   s.Replace("a", "b")
来源：http://dali.tian-w.cn/Article/details/gtadugaxga.html

[E07] 按分隔符拆分
来源：http://dali.snrcjt.cn/Article/details/gtxlorfawd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.wangshuangyany.cn/Article/details/gtzurecgee.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.wangdashe.top/Article/details/gtxyfljryl.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zdqjudy.top/Article/details/gtezztohvl.html

TS:   s.split(",")
来源：http://dali.yj202588.top/Article/details/gtnhijqyuc.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yj20258888.top/Article/details/gttipyabom.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtdiqshlnl.html

Ruby: s.split(",");  s.split
来源：http://dali.pycfn.com/Article/details/gtrsqkcjid.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.smart0.xyz/Article/details/gtsspnnrfu.html

[E08] 数组按分隔符合并
来源：http://dali.redwolf501.top/Article/details/gtxnirbnex.html

Py:   ",".join(items)
来源：http://dali.gogol.net.cn/Article/details/gtxpaqglsq.html

PHP:  implode(",", $items);
来源：http://dali.jinqigufen.top/Article/details/gttaesyvdd.html

JS:   items.join(",")
来源：http://dali.daria6918.cn/Article/details/gtfsfotrfv.html

TS:   items.join(",")
来源：http://dali.pycfn.com/Article/details/gtgbxvpaci.html

Java: String.join(",", items)
来源：http://dali.hammf.cn/Article/details/gtrjkrsyuo.html

Go:   strings.Join(items, ",")
来源：http://dali.yvedp.cn/Article/details/gthwprtpmm.html

Ruby: items.join(",")
来源：http://dali.havefunace.top/Article/details/gtvgiwxxav.html

C#:   string.Join(",", items)
来源：http://dali.sysykeji.top/Article/details/gtwwaotprq.html

[E09] 去除所有空白字符
来源：http://dali.daria6918.cn/Article/details/gtsoderqjq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ivvv.top/Article/details/gtatwvfxgx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yonumen.top/Article/details/gtiobmenrd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.aizwys.cn/Article/details/gtlxekxykh.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yuanzhike.top/Article/details/gtrkfqprpf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.pycfn.com/Article/details/gtfavsheub.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhoulong.xyz/Article/details/gtaqmcjtnb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cashguo.top/Article/details/gtzhdhveqd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.dashuyun.cn/Article/details/gtrghwfnfa.html

[E10] 左侧补零 / 定长填充
来源：http://dali.c1oappe.top/Article/details/gtlmckiyug.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtivkslkii.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.daxiang520.top/Article/details/gtoxsgtmpv.html

JS:   "7".padStart(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gtehocecyl.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvfrjwhlu.html

Java: String.format("%03d", 7)
来源：http://dali.cashguo.top/Article/details/gtxhuuazll.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yongpay.top/Article/details/gtwyqmnvue.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.smart0.xyz/Article/details/gtalqlwoqe.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.andypj.xyz/Article/details/gtggluteof.html

[E11] 反转字符串
来源：http://dali.hysaishi.cn/Article/details/gtnvzwlkqi.html

Py:   s[::-1]
来源：http://dali.havefunace.top/Article/details/gteuffqdfk.html

PHP:  strrev($s);
来源：http://dali.yonumen.top/Article/details/gtwcvrpdps.html

JS:   [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gtzdittdkb.html

TS:   [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gtcafzogmr.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.pengpengdd.cyou/Article/details/gtvrjzrttt.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sysykeji.top/Article/details/gtfjxbleyr.html

Ruby: s.reverse
来源：http://dali.ybcxt.top/Article/details/gtukkhexjw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sweek.top/Article/details/gtfygjzhnq.html

[E12] 统计某字符出现次数
来源：http://dali.cashguo.top/Article/details/gtkyenobfi.html

Py:   s.count("a")
来源：http://dali.hnqzz.top/Article/details/gtgkodtfhd.html

PHP:  substr_count($s, "a");
来源：http://dali.zhengqikj.top/Article/details/gtwohwasbu.html

JS:   s.split("a").length - 1
来源：http://dali.tianlin.xyz/Article/details/gtuvvbnqlw.html

TS:   s.split("a").length - 1
来源：http://dali.gzhubu.top/Article/details/gtimexutmc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhiwuduotai.top/Article/details/gtmpembkgy.html

Go:   strings.Count(s, "a")
来源：http://dali.jianghu66.top/Article/details/gtrtimvjsy.html

Ruby: s.count("a")
来源：http://dali.hammf.cn/Article/details/gtocyvdzpe.html

C#:   s.Count(c => c == 'a')
来源：http://dali.meibo888.top/Article/details/gtacpmzgnz.html

[E13] 逐字符遍历
来源：http://dali.yuxming.cn/Article/details/gtvfjiivmq.html

Py:   for ch in s: print(ch)
来源：http://dali.gaohongyu789.top/Article/details/gtoqdbmwup.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gaohongyu789.top/Article/details/gtpxslvjpv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ydzc1.top/Article/details/gtgyewqxuy.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.mhx1999.top/Article/details/gtuvxnnncf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gotoacloud.top/Article/details/gtxzuitxjy.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhixingplan.top/Article/details/gtmoctmxkq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yj202588.top/Article/details/gtixovtktk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yonumen.top/Article/details/gtlacollth.html


<!-- 参考信息 -->