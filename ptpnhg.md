代发 wailian999

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwuinnmi.html

Ruby: arr.sort
来源：http://dali.cucudq.cn/Article/details/gtgluwlqnj.html

C#:   list.Sort();
来源：http://dali.gogol.net.cn/Article/details/gtbkvotrms.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sxryk.cn/Article/details/gtfixmxlqo.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.pycfn.com/Article/details/gtcutouiay.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.havefunace.top/Article/details/gtlyzuywmx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dashuyun.cn/Article/details/gtaeuvmlaj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aibaodan.cn/Article/details/gtxbpipgxr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nwbrower.top/Article/details/gttvtaayer.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.wangshuangyany.cn/Article/details/gtpmvqmgpu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jqgufenzy.top/Article/details/gtyittkxwq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jianghu66.top/Article/details/gtfmmqqotz.html

[D11] 反转数组
来源：http://dali.0kj1m.cn/Article/details/gtztyebjgz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ivvv.top/Article/details/gtzruwqpiy.html

PHP:  array_reverse($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtxobaafro.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.meibo888.top/Article/details/gtaafvxbjk.html

TS:   [...arr].reverse();
来源：http://dali.ivvv.top/Article/details/gtslzbpetw.html

Java: Collections.reverse(list);
来源：http://dali.tanke756.top/Article/details/gtnfplkdgu.html

Go:   slices.Reverse(arr)
来源：http://dali.yongpay.top/Article/details/gtknylrses.html

Ruby: arr.reverse
来源：http://dali.cheryme.top/Article/details/gtvmchelct.html

C#:   list.Reverse();
来源：http://dali.yonumen.top/Article/details/gtlmxybgou.html

[D12] 查找元素下标
来源：http://dali.daxiang520.top/Article/details/gtrxduaorl.html

Py:   arr.index(x);  x in arr
来源：http://dali.zdqjudy.top/Article/details/gtmndhqdgp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jlsjyb.cn/Article/details/gtcrgzqsjp.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.bjfxy.top/Article/details/gtkwowijkf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.iojbl.cn/Article/details/gtwvpzxmkc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yvedp.cn/Article/details/gtsppkxfpt.html

Go:   slices.Index(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtxpgjovbf.html

Ruby: arr.index(x)
来源：http://dali.316326.xyz/Article/details/gtnxjhbany.html

C#:   list.IndexOf(x);
来源：http://dali.haohaochexian.top/Article/details/gtqmijskga.html

[D13] 过滤（保留满足条件的）
来源：http://dali.9152youxi.cn/Article/details/gtovqavkpe.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.gzhubu.top/Article/details/gtnpvaqocb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xuetiantiany.cn/Article/details/gttqaexnxp.html

JS:   arr.filter(x => x > 3)
来源：http://dali.0kj1m.cn/Article/details/gtvocxxvkq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yongpay.top/Article/details/gtlhaorleq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.smart0.xyz/Article/details/gtplpfufsf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.fengsongda.top/Article/details/gtyyginbir.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.kuanghao11.cn/Article/details/gtpbdkftvd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xuanzx.com/Article/details/gtjoozinmk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhoulong.xyz/Article/details/gteaoiumfh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhixingplan.top/Article/details/gtwwmymkpn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yvedp.cn/Article/details/gtdvlratgl.html

JS:   arr.map(x => x * 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtejsrbcfs.html

TS:   arr.map(x => x * 2)
来源：http://dali.tanke756.top/Article/details/gtfpbmcmyd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shzxlz.cn/Article/details/gticzteeob.html

Go:   // 手写循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtifyttqyc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtzucxkdwg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtujjqjyco.html

[D15] 去重
来源：http://dali.jinqigfzy.top/Article/details/gthlxzvcen.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.daxiang520.top/Article/details/gtpmesxtco.html

PHP:  array_unique($arr);
来源：http://dali.hysaishi.cn/Article/details/gtsaybudvg.html

JS:   [...new Set(arr)]
来源：http://dali.zhiwuduotai.top/Article/details/gtywdwmxct.html

TS:   [...new Set(arr)]
来源：http://dali.birdmap.top/Article/details/gtepicvotu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hnqzz.top/Article/details/gtvvgimief.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.dashuyun.cn/Article/details/gtnlqjqivw.html

Ruby: arr.uniq
来源：http://dali.yj20258.top/Article/details/gtsxsavztp.html

C#:   list.Distinct().ToList()
来源：http://dali.jiagoushi.top/Article/details/gttvqnfagn.html

[D16] 求和与平均值
来源：http://dali.snrcjt.cn/Article/details/gtuoyyvzdi.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ybcxt.top/Article/details/gtcoavlbjv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtpajdhded.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ivvv.top/Article/details/gtkjlhsbrl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sysykeji.top/Article/details/gtdxvddnir.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.aizwys.cn/Article/details/gteolgegcn.html

Go:   // 手写循环累加
来源：http://dali.jinghuilouyu.cn/Article/details/gtjxuxkazj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ydzc1.top/Article/details/gtmbwqcpth.html

C#:   list.Sum();  list.Average()
来源：http://dali.tianlin.xyz/Article/details/gtbfsgzpha.html

[D17] 最大值与最小值
来源：http://dali.jinqigufen.top/Article/details/gtlaqarawb.html

Py:   max(arr);  min(arr)
来源：http://dali.hysaishi.cn/Article/details/gtivmidzkk.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtvwazibry.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cqqwz.cn/Article/details/gtluvknnfs.html

TS:   Math.max(...arr);
来源：http://dali.cdnleiting.top/Article/details/gtjqixseup.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtppzusaqe.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yongpay.top/Article/details/gtaraebzpj.html

Ruby: arr.max;  arr.min
来源：http://dali.gotoacloud.top/Article/details/gtnrkrvyud.html

C#:   list.Max();  list.Min()
来源：http://dali.redwolf501.top/Article/details/gtolfxgjxj.html

[D18] 扁平化嵌套数组
来源：http://dali.xuetiantiany.cn/Article/details/gtllegyqvr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jianghu66.top/Article/details/gtijokwymf.html

PHP:  array_merge(...$nested);
来源：http://dali.cdnleiting.top/Article/details/gtgikmrkur.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cucudq.cn/Article/details/gtvzpybvby.html

TS:   nested.flat();
来源：http://dali.vqdsnc.cn/Article/details/gtvwgqxvzm.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hfpthk.cn/Article/details/gtwedbzsic.html

Go:   // 手写双层循环
来源：http://dali.jlsjyb.cn/Article/details/gtizdfiqgh.html

Ruby: nested.flatten
来源：http://dali.c1oappe.top/Article/details/gtcyktwjhe.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtlsaenklp.html

[D19] 按字段分组
来源：http://dali.quarkkingdee.top/Article/details/gtxczukaki.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.daria6918.cn/Article/details/gtwehnqmhi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hnxiangtu.top/Article/details/gtfghzjrjy.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwryebern.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yvedp.cn/Article/details/gtdbzpyrps.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xinyue.icu/Article/details/gteuofbqdr.html

Go:   // 手写 map[string][]T
来源：http://dali.haohaochexian.top/Article/details/gtvhrdskjz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sweek.top/Article/details/gtysylgsob.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hnqzz.top/Article/details/gtvrbnlsio.html

[D20] 统计每个元素出现次数
来源：http://dali.smart0.xyz/Article/details/gtmczqkuyh.html

Py:   Counter(arr)
来源：http://dali.smart0.xyz/Article/details/gtuxidntue.html

PHP:  array_count_values($arr);
来源：http://dali.cdnleiting.top/Article/details/gtbdbjzdvb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenzaomai.com/Article/details/gtpclpqpbg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.quarkkingdee.top/Article/details/gtwfotrtoh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ydzc1.top/Article/details/gtsriziweh.html

Go:   // 手写 map[T]int
来源：http://dali.tianlin.xyz/Article/details/gtgpormxyk.html

Ruby: arr.tally
来源：http://dali.svipenyu.cn/Article/details/gtwdwnqwmo.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.quarkkingdee.top/Article/details/gtqpdxlgvw.html

[D21] 判断是否包含某元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gttnwhadnz.html

Py:   x in arr
来源：http://dali.shangyingyoupin.top/Article/details/gtorczpzqc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtojebicon.html

JS:   arr.includes(x)
来源：http://dali.fzhhl.top/Article/details/gtvujwbtgc.html

TS:   arr.includes(x)
来源：http://dali.0kj1m.cn/Article/details/gtyelyonpq.html

Java: list.contains(x)
来源：http://dali.tanke756.top/Article/details/gtqstfhixh.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gttfgygnol.html

Ruby: arr.include?(x)
来源：http://dali.fzhhl.top/Article/details/gtouqfymqk.html

C#:   list.Contains(x)
来源：http://dali.wangdashe.top/Article/details/gtiemyssje.html

[D22] 复制数组（避免共享引用）
来源：http://dali.nanxinkj.top/Article/details/gtdlnjcrqc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jqgfzy.top/Article/details/gtcojotsoi.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shangyingyoupin.top/Article/details/gtfhnecneo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhixingplan.top/Article/details/gtqdelvbpu.html

TS:   [...arr];
来源：http://dali.snrcjt.cn/Article/details/gtjgarhgcp.html

Java: new ArrayList<>(list);
来源：http://dali.smart0.xyz/Article/details/gtrvyookmi.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gogol.net.cn/Article/details/gtilpxktdn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yvedp.cn/Article/details/gtzgrnhyes.html

C#:   new List<int>(list);
来源：http://dali.yvedp.cn/Article/details/gtzhyuxchg.html

[D23] reduce 累积计算
来源：http://dali.zhiwuduotai.top/Article/details/gtfoyexrpj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.meibo888.top/Article/details/gtowechtkd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.snrcjt.cn/Article/details/gtcruafiki.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.haohaochexian.top/Article/details/gtjvvnnzxm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hywenlv.cn/Article/details/gtprgpgxui.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.nanxuanxn.top/Article/details/gtmcnjjktb.html

Go:   // 手写循环
来源：http://dali.kuanghao11.cn/Article/details/gtcglebtrf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cheryme.top/Article/details/gtzoxnggvl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ybcxt.top/Article/details/gtgaezulme.html

[D24] 字典 / Map 基本操作
来源：http://dali.kuanghao11.cn/Article/details/gtezbbazdf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jqgfzy.top/Article/details/gtmxfnptdu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.9152youxi.cn/Article/details/gtpylkzdjf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.9152youxi.cn/Article/details/gtufdditha.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gtpbgzddtl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.svipenyu.cn/Article/details/gtsfeahvct.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxgaausvn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sxryk.cn/Article/details/gtpudeamyb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.quarkkingdee.top/Article/details/gtbugjohnj.html

[D25] Set 集合去重与交并差
来源：http://dali.cheryme.top/Article/details/gtafsgsdem.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.nanxuanxn.top/Article/details/gtprulukob.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ppjwa.cn/Article/details/gtyohqcxhw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.guannengcc.top/Article/details/gtlhizgukb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.chenzaomai.com/Article/details/gtshwnqfri.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.haohaochexian.top/Article/details/gtbiibeeks.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.nanxinkj.top/Article/details/gthbitcqqr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.pycfn.com/Article/details/gtffcknxvk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zycfv.cn/Article/details/gtunezykqr.html

[D26] 数组转字符串
来源：http://dali.birdmap.top/Article/details/gtmbzgvmww.html

Py:   ", ".join(map(str, arr))
来源：http://dali.fzhhl.top/Article/details/gtxfpuzthz.html

PHP:  implode(", ", $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtofjnvovr.html

JS:   arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gtxztohooa.html

TS:   arr.join(", ")
来源：http://dali.dashuyun.cn/Article/details/gtbrwotshc.html

Java: String.join(", ", list)
来源：http://dali.gaohongyu789.top/Article/details/gttjwhtifo.html

Go:   strings.Join(strs, ", ")
来源：http://dali.316326.xyz/Article/details/gtbmoznqfu.html

Ruby: arr.join(", ")
来源：http://dali.jlsjyb.cn/Article/details/gtsmedhtux.html

C#:   string.Join(", ", list)
来源：http://dali.meibo888.top/Article/details/gtgutrbyyw.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtxapytvrl.html

E. 字符串处理
来源：http://dali.gotoacloud.top/Article/details/gtnmaqasvd.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtndyrvcxa.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gtlplriptf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cucudq.cn/Article/details/gtsxbfrljl.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yuanzhike.top/Article/details/gtwabjddpy.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj202588.top/Article/details/gtojwkxsan.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yangfankeji.com/Article/details/gtrqkuoiag.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hnqzz.top/Article/details/gtvjimkunp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.316326.xyz/Article/details/gttakxszbm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hysaishi.cn/Article/details/gtkkohtqio.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtswvxwzdn.html

[E02] 重复字符串
来源：http://dali.316326.xyz/Article/details/gtpeogxzsn.html

Py:   "ab" * 3
来源：http://dali.nanxinkj.top/Article/details/gthgrksdcr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtyosungpn.html

JS:   "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gtcbxuuprk.html

TS:   "ab".repeat(3)
来源：http://dali.9152youxi.cn/Article/details/gttodrmogg.html

Java: "ab".repeat(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtpbksvuee.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sufxvd.cn/Article/details/gtvplxlmqo.html

Ruby: "ab" * 3
来源：http://dali.hnqzz.top/Article/details/gtywhspixj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cqqwz.cn/Article/details/gtshobouso.html

[E03] 截取子串
来源：http://dali.gaohongyu789.top/Article/details/gthamoevwl.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zycfv.cn/Article/details/gtaczqrzol.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gtviphabzq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.dianchejie.cn/Article/details/gtximppjfi.html

TS:   s.slice(1, 4)
来源：http://dali.zdqjudy.top/Article/details/gtcitsmidb.html

Java: s.substring(1, 4)
来源：http://dali.nanxinkj.top/Article/details/gttgdbxmfn.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhengqikj.top/Article/details/gtpuzltikd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.chenzaomai.com/Article/details/gtcmlrdzxw.html

C#:   s.Substring(1, 3)
来源：http://dali.tanke756.top/Article/details/gtstbsaooo.html

[E04] 查找子串位置
来源：http://dali.shangyingyoupin.top/Article/details/gtorqvvuud.html

Py:   s.find("x");  s.index("x")
来源：http://dali.svipenyu.cn/Article/details/gtquoablza.html

PHP:  strpos($s, "x");
来源：http://dali.hfpthk.cn/Article/details/gtezlsmiva.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yj20258888.top/Article/details/gttfafjizy.html

TS:   s.indexOf("x")
来源：http://dali.gogol.net.cn/Article/details/gtoblttaeu.html

Java: s.indexOf("x")
来源：http://dali.jinqigufen.top/Article/details/gtubmguhuf.html

Go:   strings.Index(s, "x")
来源：http://dali.c1oappe.top/Article/details/gtzwmucvcu.html

Ruby: s.index("x")
来源：http://dali.jinqigufen.top/Article/details/gtnouwcrkf.html

C#:   s.IndexOf("x")
来源：http://dali.dianchejie.cn/Article/details/gtshiwqkvk.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.fzhhl.top/Article/details/gtqbuxtpix.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.havefunace.top/Article/details/gtknvgybkz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.nwbrower.top/Article/details/gtbvypunlj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hfpthk.cn/Article/details/gtrvcxwryw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.fzhhl.top/Article/details/gtemtzcpah.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gtjolrkflc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.bjfxy.top/Article/details/gtffrrxajo.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ppjwa.cn/Article/details/gtuxxfscii.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.tanke756.top/Article/details/gtsgdfblbq.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gthfyqouau.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfjgeuupi.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yvedp.cn/Article/details/gtxykipxtn.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtrcmulxbn.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthwhgmesl.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cheryme.top/Article/details/gtmmbyxcfi.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtrpgrsmfy.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtdioboard.html

C#:   s.Replace("a", "b")
来源：http://dali.hammf.cn/Article/details/gtlzbxffdf.html

[E07] 按分隔符拆分
来源：http://dali.tanke756.top/Article/details/gtgwtfpbye.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hysaishi.cn/Article/details/gtsvtgojpv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.andypj.xyz/Article/details/gtjshbrsxw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zycfv.cn/Article/details/gtbekqxloc.html

TS:   s.split(",")
来源：http://dali.dianchejie.cn/Article/details/gtvhyemccs.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xylfe.cn/Article/details/gtvcinkwix.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtgakeusmw.html

Ruby: s.split(",");  s.split
来源：http://dali.tanke756.top/Article/details/gtbwaloaxc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.guowangkeji.top/Article/details/gtwpvurnin.html

[E08] 数组按分隔符合并
来源：http://dali.hnxiangtu.top/Article/details/gtzqfwuqdp.html

Py:   ",".join(items)
来源：http://dali.jlsjyb.cn/Article/details/gtyszdnwtm.html

PHP:  implode(",", $items);
来源：http://dali.aibaodan.cn/Article/details/gtzywojver.html

JS:   items.join(",")
来源：http://dali.zycfv.cn/Article/details/gtcxbbfmhl.html

TS:   items.join(",")
来源：http://dali.guowangkeji.top/Article/details/gtpvwkesvg.html

Java: String.join(",", items)
来源：http://dali.xziqi.cn/Article/details/gtzqnyugyk.html

Go:   strings.Join(items, ",")
来源：http://dali.xuetiantiany.cn/Article/details/gtwlqanszc.html

Ruby: items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gtzunejbkm.html

C#:   string.Join(",", items)
来源：http://dali.yonumen.top/Article/details/gtytoeqmtw.html

[E09] 去除所有空白字符
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkkuciuff.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.meibo888.top/Article/details/gtydmhnlbc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtqgscipfo.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jlsjyb.cn/Article/details/gtvlhzafvw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.daria6918.cn/Article/details/gthtxlwfup.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jiagoushi.top/Article/details/gtbpwhoowo.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinqigufen.top/Article/details/gtcwqmbkiw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xuetiantiany.cn/Article/details/gtdmjxalor.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jyoumei.cn/Article/details/gtxajfaymm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.316326.xyz/Article/details/gtmidxrywe.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yj20258.top/Article/details/gthheasxgt.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinqigufen.top/Article/details/gtskigrlci.html

JS:   "7".padStart(3, "0")
来源：http://dali.jyoumei.cn/Article/details/gtaimogmom.html

TS:   "7".padStart(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gtcaldhuus.html

Java: String.format("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gtwrguhcra.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.aizwys.cn/Article/details/gtwvmlfjet.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nwbrower.top/Article/details/gtvpgqdptt.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tian-w.cn/Article/details/gtlgakwulv.html

[E11] 反转字符串
来源：http://dali.sufxvd.cn/Article/details/gthtwqrmzk.html

Py:   s[::-1]
来源：http://dali.c1oappe.top/Article/details/gtkqxenpac.html

PHP:  strrev($s);
来源：http://dali.dianchejie.cn/Article/details/gtfchejigv.html

JS:   [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gtvcfadwtn.html

TS:   [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gtzmbjokyl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.daria6918.cn/Article/details/gtrqeqdoiy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.meibo888.top/Article/details/gteshpopyn.html

Ruby: s.reverse
来源：http://dali.ppjwa.cn/Article/details/gtnpwaomvh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangtech.top/Article/details/gtthdfzpps.html

[E12] 统计某字符出现次数
来源：http://dali.hnxiangtu.top/Article/details/gtqtopvfjf.html

Py:   s.count("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlcaypcii.html

PHP:  substr_count($s, "a");
来源：http://dali.tianlin.xyz/Article/details/gtemcfklny.html

JS:   s.split("a").length - 1
来源：http://dali.svipenyu.cn/Article/details/gtvedzquxf.html

TS:   s.split("a").length - 1
来源：http://dali.hammf.cn/Article/details/gtoatrgtjl.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzldbkswy.html

Go:   strings.Count(s, "a")
来源：http://dali.sxryk.cn/Article/details/gtonuzhtlj.html

Ruby: s.count("a")
来源：http://dali.haohaochexian.top/Article/details/gtnoeapism.html

C#:   s.Count(c => c == 'a')
来源：http://dali.kuanghao11.cn/Article/details/gtemljogmu.html

[E13] 逐字符遍历
来源：http://dali.cqqwz.cn/Article/details/gtuxipistl.html

Py:   for ch in s: print(ch)
来源：http://dali.sweek.top/Article/details/gtgokxcmur.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yangfankeji.com/Article/details/gtlgzddvcx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenlongwang.top/Article/details/gtsqsshlhv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sufxvd.cn/Article/details/gttuutbboe.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xylfe.cn/Article/details/gtvjkkryep.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hysaishi.cn/Article/details/gtudnckezt.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaegtpgkv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gthxssiulf.html

[E14] URL 编码与 Base64
来源：http://dali.dianchejie.cn/Article/details/gtxfjobyot.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhengqikj.top/Article/details/gtxfsropok.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cucudq.cn/Article/details/gtwxsyslzq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.tanke756.top/Article/details/gtorbsfwdf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gotoacloud.top/Article/details/gtlvndotku.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhiwuduotai.top/Article/details/gtobgbzrer.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.kuanghao11.cn/Article/details/gtttjujuqe.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shzxlz.cn/Article/details/gtbxourrhc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.316326.xyz/Article/details/gtmjdcggxg.html

[E15] HTML 转义 / 反转义
来源：http://dali.iojbl.cn/Article/details/gtdpufqybi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jiagoushi.top/Article/details/gtoavraksb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.aibaodan.cn/Article/details/gtcxuwbzzi.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yonumen.top/Article/details/gtevaxqnoh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtmuykptzu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xylfe.cn/Article/details/gtdplnyhxn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zdqjudy.top/Article/details/gtjucdpxda.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jqgufenzy.top/Article/details/gtyooldezi.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zdqjudy.top/Article/details/gtitjyqhjo.html

[E16] 数字千分位
来源：http://dali.jqgfzy.top/Article/details/gttvbfismc.html

Py:   f"{1234567:,}"
来源：http://dali.0kj1m.cn/Article/details/gtjxtpaudh.html

PHP:  number_format(1234567);
来源：http://dali.xylfe.cn/Article/details/gtmpqghbly.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.dianchejie.cn/Article/details/gteemubtzb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.316326.xyz/Article/details/gtiubpolne.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenzaomai.com/Article/details/gtjzqosjhr.html


<!-- 参考信息 -->