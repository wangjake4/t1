代发 wailian999

[D11] 反转数组
来源：http://dali.havefunace.top/Article/details/gtptkburya.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cdnleiting.top/Article/details/gtmoaydxps.html

PHP:  array_reverse($arr);
来源：http://dali.yueranfly.top/Article/details/gtsdnkbfhg.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.snrcjt.cn/Article/details/gteeodpoax.html

TS:   [...arr].reverse();
来源：http://dali.yangfankeji.com/Article/details/gtjpqmfday.html

Java: Collections.reverse(list);
来源：http://dali.zhiwuduotai.top/Article/details/gtsotkbbnb.html

Go:   slices.Reverse(arr)
来源：http://dali.svipenyu.cn/Article/details/gtlquxvrfc.html

Ruby: arr.reverse
来源：http://dali.chenzaomai.com/Article/details/gtunbgszri.html

C#:   list.Reverse();
来源：http://dali.ehwqpu.com/Article/details/gtvysptien.html

[D12] 查找元素下标
来源：http://dali.chenlongwang.top/Article/details/gtxggxidcj.html

Py:   arr.index(x);  x in arr
来源：http://dali.wangdashe.top/Article/details/gtdlefjmuh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xinyue.icu/Article/details/gtntkuoqal.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtgawderxk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtksmfxpht.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yongpay.top/Article/details/gtswihwtvb.html

Go:   slices.Index(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtwmfnfdxl.html

Ruby: arr.index(x)
来源：http://dali.shzxlz.cn/Article/details/gteuvenasd.html

C#:   list.IndexOf(x);
来源：http://dali.shangyingyoupin.top/Article/details/gtyrcuhpgs.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shangyingyoupin.top/Article/details/gtnmhxbaov.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ybcxt.top/Article/details/gtxkzvpymw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jqgfzy.top/Article/details/gtsruanxel.html

JS:   arr.filter(x => x > 3)
来源：http://dali.aibaodan.cn/Article/details/gtwurffltn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrogjcihs.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.dashuyun.cn/Article/details/gtdpcnuixv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.fzhhl.top/Article/details/gtnrdlyhrn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tanke756.top/Article/details/gttooxwcqz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.bjfxy.top/Article/details/gtrmtojfjg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yvedp.cn/Article/details/gtbyqkqbxn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.tanke756.top/Article/details/gtjinmtgia.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtsendyatw.html

JS:   arr.map(x => x * 2)
来源：http://dali.gogol.net.cn/Article/details/gtadmfsbsb.html

TS:   arr.map(x => x * 2)
来源：http://dali.cdnleiting.top/Article/details/gtmlejqtbd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.smart0.xyz/Article/details/gtfzdhosdn.html

Go:   // 手写循环
来源：http://dali.kuanghao11.cn/Article/details/gtbwbsivaz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hysaishi.cn/Article/details/gtigyvnuhn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtseerrbcd.html

[D15] 去重
来源：http://dali.gogol.net.cn/Article/details/gtbhknpaho.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.nwbrower.top/Article/details/gtgrjxqiqm.html

PHP:  array_unique($arr);
来源：http://dali.zycfv.cn/Article/details/gtuzeccjtk.html

JS:   [...new Set(arr)]
来源：http://dali.haohaochexian.top/Article/details/gtccrsrjel.html

TS:   [...new Set(arr)]
来源：http://dali.kuanghao11.cn/Article/details/gtcampjedw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.fengsongda.top/Article/details/gtbcntykbk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gzhubu.top/Article/details/gtuufvfxyr.html

Ruby: arr.uniq
来源：http://dali.shangyingyoupin.top/Article/details/gtpezwmiqq.html

C#:   list.Distinct().ToList()
来源：http://dali.shuidangran.top/Article/details/gtnaziysde.html

[D16] 求和与平均值
来源：http://dali.hnxiangtu.top/Article/details/gttygutbgl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sxryk.cn/Article/details/gtsrvvktjc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtzrabhntt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tian-w.cn/Article/details/gtpudlrppi.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlcamxhzn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hysaishi.cn/Article/details/gtkfbusydm.html

Go:   // 手写循环累加
来源：http://dali.yangfankeji.com/Article/details/gtqpppghba.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yuanzhike.top/Article/details/gtylebyqug.html

C#:   list.Sum();  list.Average()
来源：http://dali.jqgufenzy.top/Article/details/gtjjwqjsjr.html

[D17] 最大值与最小值
来源：http://dali.shanyushiyangtech.top/Article/details/gtlzzgdgez.html

Py:   max(arr);  min(arr)
来源：http://dali.pycfn.com/Article/details/gtsjwlimcs.html

PHP:  max($arr);  min($arr);
来源：http://dali.yvedp.cn/Article/details/gthutfdmrt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhixingplan.top/Article/details/gtnrivvllo.html

TS:   Math.max(...arr);
来源：http://dali.guannengcc.top/Article/details/gtvozkwoct.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hammf.cn/Article/details/gtydaxqukq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yj20258888.top/Article/details/gtwrwhhfzt.html

Ruby: arr.max;  arr.min
来源：http://dali.yangfankeji.com/Article/details/gtejbbzfpn.html

C#:   list.Max();  list.Min()
来源：http://dali.vqdsnc.cn/Article/details/gtngolsqpw.html

[D18] 扁平化嵌套数组
来源：http://dali.dashuyun.cn/Article/details/gtsumnhikz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yonumen.top/Article/details/gtslhnjsak.html

PHP:  array_merge(...$nested);
来源：http://dali.cheryme.top/Article/details/gtnkmydwsh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.pycfn.com/Article/details/gtkecbrtvy.html

TS:   nested.flat();
来源：http://dali.bjfxy.top/Article/details/gtgelvcmwd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.pycfn.com/Article/details/gtqjrsoeuj.html

Go:   // 手写双层循环
来源：http://dali.aizwys.cn/Article/details/gtpnkngega.html

Ruby: nested.flatten
来源：http://dali.jinqigfzy.top/Article/details/gthcvywekc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.tian-w.cn/Article/details/gtnapyejrz.html

[D19] 按字段分组
来源：http://dali.yj20258.top/Article/details/gttqeipkic.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.tian-w.cn/Article/details/gtusxfjaac.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sysykeji.top/Article/details/gtnlwragtc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xuanzx.com/Article/details/gtkpmzxmtb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yangfankeji.com/Article/details/gtsvohbkdm.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.guannengcc.top/Article/details/gtmxmbcoxn.html

Go:   // 手写 map[string][]T
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcodxiwzz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yueranfly.top/Article/details/gtdktwwhew.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.fzhhl.top/Article/details/gtsemjbksv.html

[D20] 统计每个元素出现次数
来源：http://dali.smart0.xyz/Article/details/gtpwmgrsln.html

Py:   Counter(arr)
来源：http://dali.xylfe.cn/Article/details/gtjklzgmpq.html

PHP:  array_count_values($arr);
来源：http://dali.sxryk.cn/Article/details/gtprcolhyj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guannengcc.top/Article/details/gtlwvdikxy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gaohongyu789.top/Article/details/gtvstppntb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.havefunace.top/Article/details/gtyxauddpb.html

Go:   // 手写 map[T]int
来源：http://dali.sweek.top/Article/details/gtclvhqouw.html

Ruby: arr.tally
来源：http://dali.yangfankeji.com/Article/details/gttyzrfgwj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sweek.top/Article/details/gthidynetb.html

[D21] 判断是否包含某元素
来源：http://dali.chenlongwang.top/Article/details/gtdkxyehpf.html

Py:   x in arr
来源：http://dali.xuetiantiany.cn/Article/details/gtnheavxmu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.kuanghao11.cn/Article/details/gtnauedqye.html

JS:   arr.includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtosqonhpp.html

TS:   arr.includes(x)
来源：http://dali.yj20258.top/Article/details/gtioscqetj.html

Java: list.contains(x)
来源：http://dali.nanxinkj.top/Article/details/gtqnwwszri.html

Go:   slices.Contains(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtuduqbflh.html

Ruby: arr.include?(x)
来源：http://dali.ehwqpu.com/Article/details/gtucalrxcl.html

C#:   list.Contains(x)
来源：http://dali.yuxming.cn/Article/details/gtqrhoauyw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.316326.xyz/Article/details/gtqqvjsguu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jqgfzy.top/Article/details/gtslfndtsr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhiwuduotai.top/Article/details/gtandhocik.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jqgfzy.top/Article/details/gtsvqvojtf.html

TS:   [...arr];
来源：http://dali.ppjwa.cn/Article/details/gtmpogdflh.html

Java: new ArrayList<>(list);
来源：http://dali.xuanzx.com/Article/details/gtgwnozzpm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jlsjyb.cn/Article/details/gttskfuuxd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.tian-w.cn/Article/details/gtsifejxwo.html

C#:   new List<int>(list);
来源：http://dali.jinqigufen.top/Article/details/gtrzvwxiuv.html

[D23] reduce 累积计算
来源：http://dali.fengsongda.top/Article/details/gthtzurfct.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.nwbrower.top/Article/details/gtqqlcowhr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xuanzx.com/Article/details/gtfkgurrcs.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aibaodan.cn/Article/details/gtuyjcjexw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyqfmsrdb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ehwqpu.com/Article/details/gttrrwiiwo.html

Go:   // 手写循环
来源：http://dali.tian-w.cn/Article/details/gtrjqdrovi.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.nwbrower.top/Article/details/gtfiwjyxgf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.guowangkeji.top/Article/details/gtmiumltwr.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhixingplan.top/Article/details/gtwkudkdcw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhiwuduotai.top/Article/details/gtodzcuvwi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cashguo.top/Article/details/gtgmnecflj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gtbvaqyffr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtitwpgion.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.guannengcc.top/Article/details/gtdmysjflj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.feifeiyinyue.top/Article/details/gtfixilzzm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.aizwys.cn/Article/details/gtafgasuec.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xuetiantiany.cn/Article/details/gtzoopozuw.html

[D25] Set 集合去重与交并差
来源：http://dali.hammf.cn/Article/details/gtflqvwoxp.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yangfankeji.com/Article/details/gtzgxnsbfu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.dashuyun.cn/Article/details/gtmfqouhdg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yongpay.top/Article/details/gtacwkzurd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.guannengcc.top/Article/details/gtxhjswazz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.aizwys.cn/Article/details/gtvgeftmth.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shzxlz.cn/Article/details/gtyeronppy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhixingplan.top/Article/details/gtvbgunfbs.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.c1oappe.top/Article/details/gtebxzyovf.html

[D26] 数组转字符串
来源：http://dali.shzxlz.cn/Article/details/gtypppxtqr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.tianlin.xyz/Article/details/gtdogntlvh.html

PHP:  implode(", ", $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtaputrmrz.html

JS:   arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gtoitbnucn.html

TS:   arr.join(", ")
来源：http://dali.hnqzz.top/Article/details/gtdmzypxtx.html

Java: String.join(", ", list)
来源：http://dali.mhx1999.top/Article/details/gtxwxzvesb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.bjfxy.top/Article/details/gtdodsvxdv.html

Ruby: arr.join(", ")
来源：http://dali.hnqzz.top/Article/details/gtkdodpwux.html

C#:   string.Join(", ", list)
来源：http://dali.daria6918.cn/Article/details/gtecdcluyb.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gthkrirnaz.html

E. 字符串处理
来源：http://dali.pycfn.com/Article/details/gtcvwqwvyj.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtptqiwtiz.html

[E01] 拼接字符串
来源：http://dali.yj202588.top/Article/details/gtmqqetpwv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.chenzaomai.com/Article/details/gthkviqvgd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.nanxuanxn.top/Article/details/gtsaqbkwdf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cheryme.top/Article/details/gtofpvssws.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gogol.net.cn/Article/details/gtksshsfpk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ivvv.top/Article/details/gtztkgmdsd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jyoumei.cn/Article/details/gtltucxpem.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ehwqpu.com/Article/details/gtdjbqwcpy.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtmxndwjdb.html

[E02] 重复字符串
来源：http://dali.yuanzhike.top/Article/details/gtwnnnrigq.html

Py:   "ab" * 3
来源：http://dali.yj202588.top/Article/details/gtmwkjibhx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.vqdsnc.cn/Article/details/gtyopelqlg.html

JS:   "ab".repeat(3)
来源：http://dali.cucudq.cn/Article/details/gtdwdgsovu.html

TS:   "ab".repeat(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtyquxymnu.html

Java: "ab".repeat(3)
来源：http://dali.yuxming.cn/Article/details/gtqwadszji.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhixingplan.top/Article/details/gtohlpbdfp.html

Ruby: "ab" * 3
来源：http://dali.zhixingplan.top/Article/details/gtauamduoz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.aizwys.cn/Article/details/gtnmpkrvrl.html

[E03] 截取子串
来源：http://dali.cqqwz.cn/Article/details/gttdpeapws.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenzaomai.com/Article/details/gtzdzovwqc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gtiyuxelua.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cheryme.top/Article/details/gtsonbbjxk.html

TS:   s.slice(1, 4)
来源：http://dali.ivvv.top/Article/details/gtfeptbdhc.html

Java: s.substring(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gtmepijwtd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jlsjyb.cn/Article/details/gtlxmmxgbi.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yuxming.cn/Article/details/gtzelloqfb.html

C#:   s.Substring(1, 3)
来源：http://dali.gogol.net.cn/Article/details/gtksqoinsq.html

[E04] 查找子串位置
来源：http://dali.daxiang520.top/Article/details/gtprgsuczk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.pycfn.com/Article/details/gtakofspso.html

PHP:  strpos($s, "x");
来源：http://dali.shzxlz.cn/Article/details/gtmcyatmgp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xuanzx.com/Article/details/gtluocepdm.html

TS:   s.indexOf("x")
来源：http://dali.daxiang520.top/Article/details/gtgaqlxdpu.html

Java: s.indexOf("x")
来源：http://dali.hammf.cn/Article/details/gtxzvxtkhf.html

Go:   strings.Index(s, "x")
来源：http://dali.jlsjyb.cn/Article/details/gtwuolobum.html

Ruby: s.index("x")
来源：http://dali.cqqwz.cn/Article/details/gtujitsxnz.html

C#:   s.IndexOf("x")
来源：http://dali.hywenlv.cn/Article/details/gtgmbhsvux.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gtdezdmybt.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdoggexev.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.wangshuangyany.cn/Article/details/gtzcizjdxn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gtipkrfpkx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shuidangran.top/Article/details/gtecghjvip.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hysaishi.cn/Article/details/gtizqimjbf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yj202588.top/Article/details/gtfghcfxva.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhiwuduotai.top/Article/details/gtlffmooye.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yangfankeji.com/Article/details/gtarfiozox.html

[E06] 替换子串
来源：http://dali.ppjwa.cn/Article/details/gtrioiqnep.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yongpay.top/Article/details/gtjbktvvnt.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj20258.top/Article/details/gtbjynsskn.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtwmycgbex.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gtyedpayiv.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtpdyqafzx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tanke756.top/Article/details/gtphfelnzy.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtdwplhlya.html

C#:   s.Replace("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtpbhjtmjm.html

[E07] 按分隔符拆分
来源：http://dali.cqqwz.cn/Article/details/gtdpxmfhrj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.tianlin.xyz/Article/details/gtudkfxhyw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sufxvd.cn/Article/details/gtnnmixyru.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sysykeji.top/Article/details/gtqczokgoo.html

TS:   s.split(",")
来源：http://dali.jlsjyb.cn/Article/details/gtticjlkgo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yuxming.cn/Article/details/gtspiikojr.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yj20258888.top/Article/details/gtzcpphfdj.html

Ruby: s.split(",");  s.split
来源：http://dali.jqgfzy.top/Article/details/gtbpsavvva.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xinyue.icu/Article/details/gtnxjvbexp.html

[E08] 数组按分隔符合并
来源：http://dali.hywenlv.cn/Article/details/gtootuifqe.html

Py:   ",".join(items)
来源：http://dali.gaohongyu789.top/Article/details/gtdfepikap.html

PHP:  implode(",", $items);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfhdlftxs.html

JS:   items.join(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbbfnaabl.html

TS:   items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gtrvropbyx.html

Java: String.join(",", items)
来源：http://dali.chenjidiqi.icu/Article/details/gtgneaumgl.html

Go:   strings.Join(items, ",")
来源：http://dali.jyoumei.cn/Article/details/gtrcwrlqfk.html

Ruby: items.join(",")
来源：http://dali.feifeiyinyue.top/Article/details/gtyzazenkq.html

C#:   string.Join(",", items)
来源：http://dali.zhoulong.xyz/Article/details/gtbikwlbmn.html

[E09] 去除所有空白字符
来源：http://dali.yonumen.top/Article/details/gtfxnpocsa.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hfpthk.cn/Article/details/gtkujcdqau.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.havefunace.top/Article/details/gtprmcklxo.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jyoumei.cn/Article/details/gtdonbzmeq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.meibo888.top/Article/details/gtcodcknil.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.fengsongda.top/Article/details/gtvnbyxmzj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hnqzz.top/Article/details/gtsaxluqpm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthiesdprx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmirnfbyy.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cqqwz.cn/Article/details/gtnzmcjppz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlqfbwplt.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.meibo888.top/Article/details/gtrinjeteg.html

JS:   "7".padStart(3, "0")
来源：http://dali.sysykeji.top/Article/details/gtkbxvhqms.html

TS:   "7".padStart(3, "0")
来源：http://dali.hongshengwenyu.top/Article/details/gtwbozpuhk.html

Java: String.format("%03d", 7)
来源：http://dali.chenzaomai.com/Article/details/gtcrphtfwe.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cashguo.top/Article/details/gtzsznmrda.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhiwuduotai.top/Article/details/gtzscejsvx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.chenjidiqi.icu/Article/details/gtzpmonjdm.html

[E11] 反转字符串
来源：http://dali.cqqwz.cn/Article/details/gtvznfslwv.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gtvxecluat.html

PHP:  strrev($s);
来源：http://dali.yj20258.top/Article/details/gtdsilitsc.html

JS:   [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gtowgdfbbn.html

TS:   [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gtmnrskkmc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jiagoushi.top/Article/details/gtieovjhnc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xuetiantiany.cn/Article/details/gtneccpnnt.html

Ruby: s.reverse
来源：http://dali.cucudq.cn/Article/details/gtjotxzzoc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yuanzhike.top/Article/details/gtnprmmdcf.html

[E12] 统计某字符出现次数
来源：http://dali.jlsjyb.cn/Article/details/gtcssdfmab.html

Py:   s.count("a")
来源：http://dali.nwbrower.top/Article/details/gtgzpwykyi.html

PHP:  substr_count($s, "a");
来源：http://dali.meibo888.top/Article/details/gtwhiuliot.html

JS:   s.split("a").length - 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtewbhgrwi.html

TS:   s.split("a").length - 1
来源：http://dali.tian-w.cn/Article/details/gtijvwqczm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gotoacloud.top/Article/details/gtvnkncwou.html

Go:   strings.Count(s, "a")
来源：http://dali.yonumen.top/Article/details/gtbklwwcqu.html

Ruby: s.count("a")
来源：http://dali.aizwys.cn/Article/details/gtylfqgnrh.html

C#:   s.Count(c => c == 'a')
来源：http://dali.andypj.xyz/Article/details/gtntiprglw.html

[E13] 逐字符遍历
来源：http://dali.jqgufenzy.top/Article/details/gtqheklwvd.html

Py:   for ch in s: print(ch)
来源：http://dali.yueranfly.top/Article/details/gtsrzoboki.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yuxming.cn/Article/details/gttiwutzxg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cucudq.cn/Article/details/gtohonsaxt.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gtxmkxzyyh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jyoumei.cn/Article/details/gtvaejafdl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zycfv.cn/Article/details/gtcuylcenw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.daria6918.cn/Article/details/gtccxoyypj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.316326.xyz/Article/details/gtoksdeegb.html

[E14] URL 编码与 Base64
来源：http://dali.aizwys.cn/Article/details/gtmzmglrja.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj20258888.top/Article/details/gtdeonpkbe.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ehwqpu.com/Article/details/gtqufunbuk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.wangshuangyany.cn/Article/details/gtgwixfrfa.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yj20258888.top/Article/details/gttygupnvb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqyyzuiyh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jianghu66.top/Article/details/gtnrezzebq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj202588.top/Article/details/gtjymnofpm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj20258888.top/Article/details/gtqooxugtp.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinqigufen.top/Article/details/gtbezxehrz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.haohaochexian.top/Article/details/gtxqgzawxl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tianlin.xyz/Article/details/gtubrwadow.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xziqi.cn/Article/details/gtzhglotev.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cashguo.top/Article/details/gtowboccme.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.havefunace.top/Article/details/gtjbftdcpc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtnoohgnmt.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gogol.net.cn/Article/details/gtqabzxfle.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.aibaodan.cn/Article/details/gtirdhtlpo.html

[E16] 数字千分位
来源：http://dali.zhixingplan.top/Article/details/gtxbcbysze.html

Py:   f"{1234567:,}"
来源：http://dali.jiagoushi.top/Article/details/gtauznxydt.html

PHP:  number_format(1234567);
来源：http://dali.shangyingyoupin.top/Article/details/gtwnmewhxh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnxiangtu.top/Article/details/gtbxstdxeh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xziqi.cn/Article/details/gtivoerywh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ydzc1.top/Article/details/gtnqisgozc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cucudq.cn/Article/details/gtajxgyqqf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.redwolf501.top/Article/details/gtyfexozng.html

C#:   1234567.ToString("N0")
来源：http://dali.cqqwz.cn/Article/details/gthsopakjm.html

[E17] 首字母大写
来源：http://dali.shanyushiyangtech.top/Article/details/gthiiasiau.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhengqikj.top/Article/details/gtrgyevetp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.mhx1999.top/Article/details/gttadjrejm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gtabrszcta.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daria6918.cn/Article/details/gtseuqecbh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gtoyrsbugn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbdqythbh.html

Ruby: s.capitalize
来源：http://dali.pengpengdd.cyou/Article/details/gtiqcosjwf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hnqzz.top/Article/details/gtbfgkyivr.html


<!-- 参考信息 -->