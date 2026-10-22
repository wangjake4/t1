代发 wailian999

C#:   list.GetRange(1, 3);
来源：http://dali.gogol.net.cn/Article/details/gthkicztuu.html

[D08] 合并两个数组
来源：http://dali.jqgufenzy.top/Article/details/gtkttocpcq.html

Py:   a + b;  a.extend(b)
来源：http://dali.daria6918.cn/Article/details/gtkzfatmay.html

PHP:  array_merge($a, $b);
来源：http://dali.xinyue.icu/Article/details/gtjnphnxni.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenzaomai.com/Article/details/gtaxmkffrp.html

TS:   [...a, ...b];
来源：http://dali.snrcjt.cn/Article/details/gtjgvjjydb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.daria6918.cn/Article/details/gtuydnmeta.html

Go:   append(a, b...)
来源：http://dali.nanxinkj.top/Article/details/gtavpmtywp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.feifeiyinyue.top/Article/details/gtriscjilf.html

C#:   a.Concat(b).ToList()
来源：http://dali.xylfe.cn/Article/details/gtyhyyqhkj.html

[D09] 排序（升序）
来源：http://dali.ivvv.top/Article/details/gtgwtpsgzc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuetiantiany.cn/Article/details/gtowniuvbg.html

PHP:  sort($arr);
来源：http://dali.ybcxt.top/Article/details/gtsqmudaih.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.bjfxy.top/Article/details/gtpgngbxqi.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jqgfzy.top/Article/details/gtpjzpacgd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.svipenyu.cn/Article/details/gtngrxgpab.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gogol.net.cn/Article/details/gtvutqnfoo.html

Ruby: arr.sort
来源：http://dali.fengsongda.top/Article/details/gtkysxwdff.html

C#:   list.Sort();
来源：http://dali.sufxvd.cn/Article/details/gtkibfbuky.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.vqdsnc.cn/Article/details/gtzqjwerjf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgkzchhmd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xziqi.cn/Article/details/gtbvwjsjpn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ybcxt.top/Article/details/gtxrdtczwj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.havefunace.top/Article/details/gtmofnbuva.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.0kj1m.cn/Article/details/gtoycgeild.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.vqdsnc.cn/Article/details/gtlcaiblvx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cucudq.cn/Article/details/gtuncdlijg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.daria6918.cn/Article/details/gtxtqhmilb.html

[D11] 反转数组
来源：http://dali.hfpthk.cn/Article/details/gtjioijhdn.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.smart0.xyz/Article/details/gtxunahglt.html

PHP:  array_reverse($arr);
来源：http://dali.haohaochexian.top/Article/details/gtlkofnokj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.kuanghao11.cn/Article/details/gtmdlmqaag.html

TS:   [...arr].reverse();
来源：http://dali.zhiwuduotai.top/Article/details/gtgctikgnh.html

Java: Collections.reverse(list);
来源：http://dali.hfpthk.cn/Article/details/gtdwgafpsp.html

Go:   slices.Reverse(arr)
来源：http://dali.nwbrower.top/Article/details/gtjviyjgvx.html

Ruby: arr.reverse
来源：http://dali.snrcjt.cn/Article/details/gtghzgishb.html

C#:   list.Reverse();
来源：http://dali.jqgfzy.top/Article/details/gtywzseslv.html

[D12] 查找元素下标
来源：http://dali.tanke756.top/Article/details/gtiaqjoakz.html

Py:   arr.index(x);  x in arr
来源：http://dali.chenzaomai.com/Article/details/gtvsuomiol.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zycfv.cn/Article/details/gtauvlxaxs.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dashuyun.cn/Article/details/gthdbvwvnf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jianghu66.top/Article/details/gtsmofoila.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.vqdsnc.cn/Article/details/gtocehbqyn.html

Go:   slices.Index(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtgwvqnisb.html

Ruby: arr.index(x)
来源：http://dali.c1oappe.top/Article/details/gtcoyiethm.html

C#:   list.IndexOf(x);
来源：http://dali.havefunace.top/Article/details/gtqdoonfzn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gogol.net.cn/Article/details/gtjkvucicy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zycfv.cn/Article/details/gtwwcuxynr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.pycfn.com/Article/details/gtaaogfuqz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxqwxlqyw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.0kj1m.cn/Article/details/gtcuxobtnw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.dashuyun.cn/Article/details/gtuhrvmfdd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cashguo.top/Article/details/gtssxeckiv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zdqjudy.top/Article/details/gtdkitmqsb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtpgmmsvev.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sweek.top/Article/details/gtmqhoulsc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yj20258.top/Article/details/gtgiijdkpg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtahemsjzr.html

JS:   arr.map(x => x * 2)
来源：http://dali.aibaodan.cn/Article/details/gtpnvvysuq.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvcmhdrdu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zycfv.cn/Article/details/gtycqbhgvd.html

Go:   // 手写循环
来源：http://dali.zdqjudy.top/Article/details/gtaoammfvt.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtzmvidhrc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gthaoyldmh.html

[D15] 去重
来源：http://dali.havefunace.top/Article/details/gtqnzigdcx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cdnleiting.top/Article/details/gtwukbsqbg.html

PHP:  array_unique($arr);
来源：http://dali.shzxlz.cn/Article/details/gtnmlhxrrc.html

JS:   [...new Set(arr)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtejlaivie.html

TS:   [...new Set(arr)]
来源：http://dali.nwbrower.top/Article/details/gtllqykmaz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.chenzaomai.com/Article/details/gtacssefnw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yanxiufei.cn/Article/details/gtecpspgoa.html

Ruby: arr.uniq
来源：http://dali.yongpay.top/Article/details/gtcofkuzwf.html

C#:   list.Distinct().ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtoljjzdls.html

[D16] 求和与平均值
来源：http://dali.ivvv.top/Article/details/gtutoyglnm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.guowangkeji.top/Article/details/gtpqiomkbc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtpxlknyxj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jiagoushi.top/Article/details/gtrbfivefe.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.andypj.xyz/Article/details/gtsekplond.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.dianchejie.cn/Article/details/gtcaypjvfl.html

Go:   // 手写循环累加
来源：http://dali.yangfankeji.com/Article/details/gtgzszgnva.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ehwqpu.com/Article/details/gtdkojuldi.html

C#:   list.Sum();  list.Average()
来源：http://dali.ywan-chungtsiang.top/Article/details/gthdcqtqus.html

[D17] 最大值与最小值
来源：http://dali.gogol.net.cn/Article/details/gtvwwmdfba.html

Py:   max(arr);  min(arr)
来源：http://dali.meibo888.top/Article/details/gtzvdrhimx.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinqigufen.top/Article/details/gtjrmsfrcz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.daxiang520.top/Article/details/gtbcmgvedg.html

TS:   Math.max(...arr);
来源：http://dali.daria6918.cn/Article/details/gtxhzzwahj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.haohaochexian.top/Article/details/gtagbpqjrg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.tanke756.top/Article/details/gttidhxonh.html

Ruby: arr.max;  arr.min
来源：http://dali.9152youxi.cn/Article/details/gtrohfkulb.html

C#:   list.Max();  list.Min()
来源：http://dali.meibo888.top/Article/details/gtgbjdnxna.html

[D18] 扁平化嵌套数组
来源：http://dali.cqqwz.cn/Article/details/gtovfwmqzx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sweek.top/Article/details/gtticlhtsb.html

PHP:  array_merge(...$nested);
来源：http://dali.yj20258.top/Article/details/gtonerraqs.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.svipenyu.cn/Article/details/gtbhlyxlvx.html

TS:   nested.flat();
来源：http://dali.316326.xyz/Article/details/gtmcdkfldn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.daxiang520.top/Article/details/gtbvzzixyv.html

Go:   // 手写双层循环
来源：http://dali.dashuyun.cn/Article/details/gtnunzmwts.html

Ruby: nested.flatten
来源：http://dali.fengsongda.top/Article/details/gthpmelfvc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xziqi.cn/Article/details/gthdxvhktv.html

[D19] 按字段分组
来源：http://dali.guowangkeji.top/Article/details/gtqlkumbuh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinqigufen.top/Article/details/gtzlvvnqxw.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xylfe.cn/Article/details/gtsuigimae.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shuidangran.top/Article/details/gtwruecysa.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.smart0.xyz/Article/details/gtkgdcmcdu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jianghu66.top/Article/details/gtstrnrwff.html

Go:   // 手写 map[string][]T
来源：http://dali.yueranfly.top/Article/details/gthwizabbe.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinqigufen.top/Article/details/gtneoggtkj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yongpay.top/Article/details/gtspxywlzf.html

[D20] 统计每个元素出现次数
来源：http://dali.cheryme.top/Article/details/gtftmowcsf.html

Py:   Counter(arr)
来源：http://dali.xziqi.cn/Article/details/gtecbghihz.html

PHP:  array_count_values($arr);
来源：http://dali.jinqigufen.top/Article/details/gtkqqlqzwz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shzxlz.cn/Article/details/gtfdvhgmwy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.bjfxy.top/Article/details/gtkusjwuzd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.tian-w.cn/Article/details/gtrbekmpev.html

Go:   // 手写 map[T]int
来源：http://dali.jqgfzy.top/Article/details/gtbavjxcan.html

Ruby: arr.tally
来源：http://dali.feifeiyinyue.top/Article/details/gtkfsnrssc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsliwjfxg.html

[D21] 判断是否包含某元素
来源：http://dali.jiagoushi.top/Article/details/gtgxflgtek.html

Py:   x in arr
来源：http://dali.meibo888.top/Article/details/gtqbamkumv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.aibaodan.cn/Article/details/gtoszradus.html

JS:   arr.includes(x)
来源：http://dali.meibo888.top/Article/details/gtgrtfvall.html

TS:   arr.includes(x)
来源：http://dali.tanke756.top/Article/details/gtfazuyqvm.html

Java: list.contains(x)
来源：http://dali.hammf.cn/Article/details/gttmgiotpc.html

Go:   slices.Contains(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gtegihkzqt.html

Ruby: arr.include?(x)
来源：http://dali.snrcjt.cn/Article/details/gtrigykuai.html

C#:   list.Contains(x)
来源：http://dali.shzxlz.cn/Article/details/gtxdevdfiw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hnxiangtu.top/Article/details/gtzkhozfvm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.fzhhl.top/Article/details/gtlsfltnrv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cucudq.cn/Article/details/gtpicxnayz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yj20258888.top/Article/details/gtngtetbkk.html

TS:   [...arr];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpvkjefgd.html

Java: new ArrayList<>(list);
来源：http://dali.ydzc1.top/Article/details/gtequsdiyo.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zdqjudy.top/Article/details/gtzimwiiio.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hnqzz.top/Article/details/gtkhprefux.html

C#:   new List<int>(list);
来源：http://dali.chenjidiqi.icu/Article/details/gtsipbjcmq.html

[D23] reduce 累积计算
来源：http://dali.sufxvd.cn/Article/details/gtokiemhsf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hywenlv.cn/Article/details/gttdricztb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhongyouzk.top/Article/details/gtgxjbnvme.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yvedp.cn/Article/details/gtqttangnp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daria6918.cn/Article/details/gtriuwfxrv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhongyouzk.top/Article/details/gtxtzeqsjd.html

Go:   // 手写循环
来源：http://dali.hnxiangtu.top/Article/details/gtotmmfhhk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinghuilouyu.cn/Article/details/gtlvnpftee.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsgamtovj.html

[D24] 字典 / Map 基本操作
来源：http://dali.havefunace.top/Article/details/gtnhgrphai.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.bjfxy.top/Article/details/gtkvnbaumx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tianlin.xyz/Article/details/gtetmnskfc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtegveqwzf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.316326.xyz/Article/details/gtfxhocvaw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tian-w.cn/Article/details/gtverlqtyj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jianghu66.top/Article/details/gtigkyiugz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.smart0.xyz/Article/details/gtiwlbnkic.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.0kj1m.cn/Article/details/gtvbpcqjfb.html

[D25] Set 集合去重与交并差
来源：http://dali.wangshuangyany.cn/Article/details/gthaomkzpo.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yvedp.cn/Article/details/gtenrbrlbc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ywan-chungtsiang.top/Article/details/gtemzvibsh.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkwfkvcmy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ppjwa.cn/Article/details/gtyvmjskgt.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.dashuyun.cn/Article/details/gtpcotoaeg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cdnleiting.top/Article/details/gteywksjxt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gotoacloud.top/Article/details/gtvtnzxnrs.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shzxlz.cn/Article/details/gtjxhuiqtq.html

[D26] 数组转字符串
来源：http://dali.zhoulong.xyz/Article/details/gtfzmsvanq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hammf.cn/Article/details/gthhatdayt.html

PHP:  implode(", ", $arr);
来源：http://dali.nanxinkj.top/Article/details/gtwxhykrft.html

JS:   arr.join(", ")
来源：http://dali.meibo888.top/Article/details/gttrzuxdpt.html

TS:   arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gtzznlxogu.html

Java: String.join(", ", list)
来源：http://dali.xziqi.cn/Article/details/gtierpwiif.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hfpthk.cn/Article/details/gtswgtxtps.html

Ruby: arr.join(", ")
来源：http://dali.pycfn.com/Article/details/gtagejanbz.html

C#:   string.Join(", ", list)
来源：http://dali.vqdsnc.cn/Article/details/gtzmrrgszy.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtygmbsxib.html

E. 字符串处理
来源：http://dali.hnqzz.top/Article/details/gthmabyvxk.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtzdulvkiw.html

[E01] 拼接字符串
来源：http://dali.cheryme.top/Article/details/gtrtpolhsn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.andypj.xyz/Article/details/gtzsdzirxo.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.chenzaomai.com/Article/details/gtibojbxdw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gaohongyu789.top/Article/details/gtudsowqca.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnqzz.top/Article/details/gtsuulirgq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjmowxnak.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hnxiangtu.top/Article/details/gtrcsggmrj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhongyouzk.top/Article/details/gtarvrhynz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtxbjkwqah.html

[E02] 重复字符串
来源：http://dali.hnxiangtu.top/Article/details/gtkmapqirf.html

Py:   "ab" * 3
来源：http://dali.hongshengwenyu.top/Article/details/gtdzehgloh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.svipenyu.cn/Article/details/gtksgjyzeb.html

JS:   "ab".repeat(3)
来源：http://dali.yanxiufei.cn/Article/details/gtlagvhthy.html

TS:   "ab".repeat(3)
来源：http://dali.9152youxi.cn/Article/details/gtqxvgnzxs.html

Java: "ab".repeat(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbhffdfxr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.9152youxi.cn/Article/details/gtpblszpfe.html

Ruby: "ab" * 3
来源：http://dali.smart0.xyz/Article/details/gtrkczfgzq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.dianchejie.cn/Article/details/gtyiiuslae.html

[E03] 截取子串
来源：http://dali.nanxuanxn.top/Article/details/gtdgujfnvl.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhixingplan.top/Article/details/gteiaveomx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gttynxygcg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hywenlv.cn/Article/details/gtjmfkktzi.html

TS:   s.slice(1, 4)
来源：http://dali.ivvv.top/Article/details/gthrjvonjy.html

Java: s.substring(1, 4)
来源：http://dali.chenjidiqi.icu/Article/details/gtrtdnhrhh.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhengqikj.top/Article/details/gtbmqkseer.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.chenlongwang.top/Article/details/gtrnyznbwg.html

C#:   s.Substring(1, 3)
来源：http://dali.cqqwz.cn/Article/details/gtavrmtcbo.html

[E04] 查找子串位置
来源：http://dali.zhengqikj.top/Article/details/gtyryqytmg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.snrcjt.cn/Article/details/gtajusyvcg.html

PHP:  strpos($s, "x");
来源：http://dali.xylfe.cn/Article/details/gttywaverd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jyoumei.cn/Article/details/gtjtzhcrdx.html

TS:   s.indexOf("x")
来源：http://dali.gotoacloud.top/Article/details/gtajotzcxr.html

Java: s.indexOf("x")
来源：http://dali.guowangkeji.top/Article/details/gtzvbuqugo.html

Go:   strings.Index(s, "x")
来源：http://dali.pycfn.com/Article/details/gtfcabmdat.html

Ruby: s.index("x")
来源：http://dali.gaohongyu789.top/Article/details/gtquvewose.html

C#:   s.IndexOf("x")
来源：http://dali.tanke756.top/Article/details/gtkfxpcfyh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yonumen.top/Article/details/gtleqdsshz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.guannengcc.top/Article/details/gtjappbmeq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.pycfn.com/Article/details/gtyjiatwld.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.wangdashe.top/Article/details/gtpinsdxjb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.iojbl.cn/Article/details/gtyycxzree.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtznzcctac.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yongpay.top/Article/details/gttfrskilu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hfpthk.cn/Article/details/gtmlvfwcao.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtopbedwui.html

[E06] 替换子串
来源：http://dali.shangyingyoupin.top/Article/details/gtusietprm.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.tianlin.xyz/Article/details/gtzfspmycz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.bjfxy.top/Article/details/gtgkxoipkf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.fengsongda.top/Article/details/gttyosvsjm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtgsmhowjg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtiyomzpco.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ydzc1.top/Article/details/gttcngkkrd.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtcyoslfdf.html

C#:   s.Replace("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtbzgnwvkm.html

[E07] 按分隔符拆分
来源：http://dali.chenzaomai.com/Article/details/gtnjdnohij.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yueranfly.top/Article/details/gtlfiwspfo.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hywenlv.cn/Article/details/gtkvytqybf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.nanxinkj.top/Article/details/gtsvhpaayz.html

TS:   s.split(",")
来源：http://dali.xylfe.cn/Article/details/gtymvokjok.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.c1oappe.top/Article/details/gtyoengpkz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yanxiufei.cn/Article/details/gtyfmlyqmk.html

Ruby: s.split(",");  s.split
来源：http://dali.yj202588.top/Article/details/gteksxddah.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.pycfn.com/Article/details/gtkwopbjrz.html

[E08] 数组按分隔符合并
来源：http://dali.jqgfzy.top/Article/details/gtmnnrgmdj.html

Py:   ",".join(items)
来源：http://dali.ydzc1.top/Article/details/gtbedhvxwn.html

PHP:  implode(",", $items);
来源：http://dali.cqqwz.cn/Article/details/gtwbvgsauf.html

JS:   items.join(",")
来源：http://dali.vqdsnc.cn/Article/details/gteubvzmcp.html

TS:   items.join(",")
来源：http://dali.fengsongda.top/Article/details/gtlviudwyg.html

Java: String.join(",", items)
来源：http://dali.jqgufenzy.top/Article/details/gtkiqhmlwi.html

Go:   strings.Join(items, ",")
来源：http://dali.316326.xyz/Article/details/gtrubibrso.html

Ruby: items.join(",")
来源：http://dali.cheryme.top/Article/details/gtcoumszui.html

C#:   string.Join(",", items)
来源：http://dali.ydzc1.top/Article/details/gtguxbclev.html

[E09] 去除所有空白字符
来源：http://dali.zycfv.cn/Article/details/gtahxqjhzn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtcitkzufa.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.316326.xyz/Article/details/gtmyghnarn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.tian-w.cn/Article/details/gtjyhunotj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.pycfn.com/Article/details/gtthznlxuj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtprnujrje.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jqgfzy.top/Article/details/gtghvpuwqn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenjidiqi.icu/Article/details/gtrmomkuqj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jiagoushi.top/Article/details/gtemzthcay.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yuxming.cn/Article/details/gtcebyccis.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xylfe.cn/Article/details/gtlbxtcued.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenzaomai.com/Article/details/gteywrmcwc.html

JS:   "7".padStart(3, "0")
来源：http://dali.shuidangran.top/Article/details/gtdmenkmww.html

TS:   "7".padStart(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gtrtrjukpm.html

Java: String.format("%03d", 7)
来源：http://dali.jyoumei.cn/Article/details/gtshpwrdtt.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbrovjfvs.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gtsatvmvtz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cdnleiting.top/Article/details/gtflngftpy.html

[E11] 反转字符串
来源：http://dali.sweek.top/Article/details/gtngbzkxvi.html

Py:   s[::-1]
来源：http://dali.nanxinkj.top/Article/details/gtkamxhrbl.html

PHP:  strrev($s);
来源：http://dali.jyoumei.cn/Article/details/gtdmyuefdw.html

JS:   [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gtkrlpwgnr.html

TS:   [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gtkiyrfdys.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.vqdsnc.cn/Article/details/gtihpwwuoc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yj20258888.top/Article/details/gtrnobjyzb.html

Ruby: s.reverse
来源：http://dali.jlsjyb.cn/Article/details/gtndhulaqb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hfpthk.cn/Article/details/gtytekvytn.html

[E12] 统计某字符出现次数
来源：http://dali.guannengcc.top/Article/details/gtoqmvdmfd.html

Py:   s.count("a")
来源：http://dali.redwolf501.top/Article/details/gtpkwlthku.html

PHP:  substr_count($s, "a");
来源：http://dali.daria6918.cn/Article/details/gtllnjhmyl.html

JS:   s.split("a").length - 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvbppmbdp.html

TS:   s.split("a").length - 1
来源：http://dali.xuetiantiany.cn/Article/details/gtsylwsscv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.aibaodan.cn/Article/details/gtdthhrcfp.html

Go:   strings.Count(s, "a")
来源：http://dali.jinqigfzy.top/Article/details/gtwrqhkmno.html

Ruby: s.count("a")
来源：http://dali.chenzaomai.com/Article/details/gtaldpdfqx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shuidangran.top/Article/details/gtcrxwhvja.html

[E13] 逐字符遍历
来源：http://dali.gotoacloud.top/Article/details/gthldvzosx.html

Py:   for ch in s: print(ch)
来源：http://dali.vqdsnc.cn/Article/details/gtnzgermyq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.tianlin.xyz/Article/details/gthhvuhinz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenlongwang.top/Article/details/gtgfbsefcr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zdqjudy.top/Article/details/gtmaldvaax.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jiagoushi.top/Article/details/gtlmnxkbpn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hfpthk.cn/Article/details/gtyafpeigm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.aibaodan.cn/Article/details/gtnqfquttb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gotoacloud.top/Article/details/gtzqzjmkmm.html

[E14] URL 编码与 Base64
来源：http://dali.hysaishi.cn/Article/details/gtdgqgkcwe.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ppjwa.cn/Article/details/gtnpfnttai.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gotoacloud.top/Article/details/gtitxnkmxw.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.guannengcc.top/Article/details/gtuuqhluvy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.fzhhl.top/Article/details/gtgjfhtkig.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yuxming.cn/Article/details/gtcwmwbbxn.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ybcxt.top/Article/details/gtrrhwqexw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jyoumei.cn/Article/details/gtkrpkfkvy.html


<!-- 参考信息 -->