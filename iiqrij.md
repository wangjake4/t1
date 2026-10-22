代发 wailian999

PHP:  sort($arr);
来源：http://dali.ppjwa.cn/Article/details/gtioybagac.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenzaomai.com/Article/details/gtywoyvtms.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zycfv.cn/Article/details/gtiiaqpeyj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hywenlv.cn/Article/details/gtjoeqqrgm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.guowangkeji.top/Article/details/gtbasjduch.html

Ruby: arr.sort
来源：http://dali.hnqzz.top/Article/details/gtqudttmib.html

C#:   list.Sort();
来源：http://dali.ppjwa.cn/Article/details/gttepoqdlx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhengqikj.top/Article/details/gticvucuqx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xziqi.cn/Article/details/gtazxmwfkv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jqgfzy.top/Article/details/gtbvrvntrd.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zycfv.cn/Article/details/gtncptckxx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyybftrox.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.fengsongda.top/Article/details/gthnocdpca.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zdqjudy.top/Article/details/gtvxnmodxk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhoulong.xyz/Article/details/gtgitlzjmj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yj20258888.top/Article/details/gtddhrmcwm.html

[D11] 反转数组
来源：http://dali.meibo888.top/Article/details/gtqizvojti.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hfpthk.cn/Article/details/gtcdmxpguk.html

PHP:  array_reverse($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtortdxyyh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.9152youxi.cn/Article/details/gtlghomzgv.html

TS:   [...arr].reverse();
来源：http://dali.guowangkeji.top/Article/details/gtjvwngktf.html

Java: Collections.reverse(list);
来源：http://dali.dianchejie.cn/Article/details/gttevzekod.html

Go:   slices.Reverse(arr)
来源：http://dali.316326.xyz/Article/details/gtpfkkgwlk.html

Ruby: arr.reverse
来源：http://dali.dianchejie.cn/Article/details/gtryoxvhij.html

C#:   list.Reverse();
来源：http://dali.hywenlv.cn/Article/details/gtnusloxas.html

[D12] 查找元素下标
来源：http://dali.zhiwuduotai.top/Article/details/gtkcobjptb.html

Py:   arr.index(x);  x in arr
来源：http://dali.ybcxt.top/Article/details/gtfjcyzhxw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yuanzhike.top/Article/details/gtxxgxzudh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hammf.cn/Article/details/gtqnyhfkhe.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.daxiang520.top/Article/details/gtswwspfhp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.vqdsnc.cn/Article/details/gtowskciss.html

Go:   slices.Index(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtxcrgwlix.html

Ruby: arr.index(x)
来源：http://dali.smart0.xyz/Article/details/gtiecmwmrf.html

C#:   list.IndexOf(x);
来源：http://dali.redwolf501.top/Article/details/gtcxlvcqvl.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hfpthk.cn/Article/details/gtsgteljfs.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.daria6918.cn/Article/details/gtwxqihbki.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.smart0.xyz/Article/details/gtkuxzbkap.html

JS:   arr.filter(x => x > 3)
来源：http://dali.bjfxy.top/Article/details/gteuxyqdso.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yvedp.cn/Article/details/gtvynlreqf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yangfankeji.com/Article/details/gtlrlyuuje.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ybcxt.top/Article/details/gtqvwcghvg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zycfv.cn/Article/details/gtymtjuqbn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtjommogur.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenjidiqi.icu/Article/details/gtptowcqbu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.svipenyu.cn/Article/details/gtsrpmqvry.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cashguo.top/Article/details/gtihpysxep.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtcbksvmhr.html

TS:   arr.map(x => x * 2)
来源：http://dali.pycfn.com/Article/details/gtsjhtslef.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cucudq.cn/Article/details/gtwzyphszt.html

Go:   // 手写循环
来源：http://dali.shangyingyoupin.top/Article/details/gtxgpoyddk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.daria6918.cn/Article/details/gtxoxycbwr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yj20258888.top/Article/details/gtccwklqrr.html

[D15] 去重
来源：http://dali.zhongyouzk.top/Article/details/gtnaxoskqh.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinqigufen.top/Article/details/gtovmdlsog.html

PHP:  array_unique($arr);
来源：http://dali.snrcjt.cn/Article/details/gtnesjpcve.html

JS:   [...new Set(arr)]
来源：http://dali.mhx1999.top/Article/details/gtavgptbgh.html

TS:   [...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gtwawhtdwq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.chenjidiqi.icu/Article/details/gtdrpxfrlq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.pengpengdd.cyou/Article/details/gtwvxwyaol.html

Ruby: arr.uniq
来源：http://dali.jinqigfzy.top/Article/details/gtuhrufwpy.html

C#:   list.Distinct().ToList()
来源：http://dali.yuanzhike.top/Article/details/gtgmjckihg.html

[D16] 求和与平均值
来源：http://dali.jinqigufen.top/Article/details/gtlghilejy.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jqgfzy.top/Article/details/gtyjgyxkll.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hnqzz.top/Article/details/gtduhngrxw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guannengcc.top/Article/details/gtttiwzxqx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtebzxpvkg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.guannengcc.top/Article/details/gtxcgdbmbk.html

Go:   // 手写循环累加
来源：http://dali.nwbrower.top/Article/details/gtsolkjxew.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.haohaochexian.top/Article/details/gtjgvkqlzm.html

C#:   list.Sum();  list.Average()
来源：http://dali.hongshengwenyu.top/Article/details/gtsfquksmv.html

[D17] 最大值与最小值
来源：http://dali.daxiang520.top/Article/details/gtjddhskpb.html

Py:   max(arr);  min(arr)
来源：http://dali.ivvv.top/Article/details/gtsvzvgvvz.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtorbublvb.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gogol.net.cn/Article/details/gtosheltif.html

TS:   Math.max(...arr);
来源：http://dali.hysaishi.cn/Article/details/gtzripzrrk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gogol.net.cn/Article/details/gtpfkfnrpq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cqqwz.cn/Article/details/gtwfzajrpu.html

Ruby: arr.max;  arr.min
来源：http://dali.0kj1m.cn/Article/details/gtuzpxcwcf.html

C#:   list.Max();  list.Min()
来源：http://dali.gaohongyu789.top/Article/details/gtrwvyzclt.html

[D18] 扁平化嵌套数组
来源：http://dali.cucudq.cn/Article/details/gtrkayyaai.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zycfv.cn/Article/details/gtlybskzud.html

PHP:  array_merge(...$nested);
来源：http://dali.nanxuanxn.top/Article/details/gthiafpked.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hfpthk.cn/Article/details/gtgpbzggrn.html

TS:   nested.flat();
来源：http://dali.sufxvd.cn/Article/details/gtzqjgowqi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtleoctngn.html

Go:   // 手写双层循环
来源：http://dali.hnqzz.top/Article/details/gtabtizzxr.html

Ruby: nested.flatten
来源：http://dali.yanxiufei.cn/Article/details/gtsgdbtclp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtezhjldcg.html

[D19] 按字段分组
来源：http://dali.yj20258.top/Article/details/gteavwmrol.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.guannengcc.top/Article/details/gtpxaygnev.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hywenlv.cn/Article/details/gtikfcknpq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj202588.top/Article/details/gtnjejncdq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hammf.cn/Article/details/gteapveajy.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.nwbrower.top/Article/details/gteosdzrrj.html

Go:   // 手写 map[string][]T
来源：http://dali.shangyingyoupin.top/Article/details/gtocolczsu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.9152youxi.cn/Article/details/gtiffrjayi.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.feifeiyinyue.top/Article/details/gtryctgsft.html

[D20] 统计每个元素出现次数
来源：http://dali.tian-w.cn/Article/details/gtnepafmyp.html

Py:   Counter(arr)
来源：http://dali.ivvv.top/Article/details/gtmftsnuzf.html

PHP:  array_count_values($arr);
来源：http://dali.shuidangran.top/Article/details/gtybtwhiie.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgufenzy.top/Article/details/gttufriovp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yangfankeji.com/Article/details/gtwhkxlyjx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenjidiqi.icu/Article/details/gtjykfgwhz.html

Go:   // 手写 map[T]int
来源：http://dali.0kj1m.cn/Article/details/gthuakhfya.html

Ruby: arr.tally
来源：http://dali.cheryme.top/Article/details/gtvsdhsvmh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.dashuyun.cn/Article/details/gtmhpsqqci.html

[D21] 判断是否包含某元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbhzsmcti.html

Py:   x in arr
来源：http://dali.ehwqpu.com/Article/details/gtxwsqjzwf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sweek.top/Article/details/gtilobdzao.html

JS:   arr.includes(x)
来源：http://dali.guannengcc.top/Article/details/gtqhwsfgpq.html

TS:   arr.includes(x)
来源：http://dali.xylfe.cn/Article/details/gtuquycbjs.html

Java: list.contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthjlxfvnv.html

Go:   slices.Contains(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtqagastrf.html

Ruby: arr.include?(x)
来源：http://dali.jyoumei.cn/Article/details/gthklostgy.html

C#:   list.Contains(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnhxooszd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sufxvd.cn/Article/details/gtdkjkrjyy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.dianchejie.cn/Article/details/gtocmvcdtr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hywenlv.cn/Article/details/gtgeltxzzd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.andypj.xyz/Article/details/gtnzledkta.html

TS:   [...arr];
来源：http://dali.zhengqikj.top/Article/details/gtbxruhfcv.html

Java: new ArrayList<>(list);
来源：http://dali.sxryk.cn/Article/details/gtffnjkyeg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xziqi.cn/Article/details/gtvheccngn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.mhx1999.top/Article/details/gtfbmetpqi.html

C#:   new List<int>(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwphkafrc.html

[D23] reduce 累积计算
来源：http://dali.ppjwa.cn/Article/details/gtrxbmqkuf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yangfankeji.com/Article/details/gtijivzpea.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.haohaochexian.top/Article/details/gtmcnzbkre.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tian-w.cn/Article/details/gtukleqicp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.meibo888.top/Article/details/gtrmgqmplc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shzxlz.cn/Article/details/gtncxfephd.html

Go:   // 手写循环
来源：http://dali.hnqzz.top/Article/details/gtmgqohfvt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hnqzz.top/Article/details/gtcizgpsuc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shuidangran.top/Article/details/gtzmrslbew.html

[D24] 字典 / Map 基本操作
来源：http://dali.redwolf501.top/Article/details/gtvlllcshv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.kuanghao11.cn/Article/details/gtjjbsducf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hywenlv.cn/Article/details/gtvjfjxnwj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.chenzaomai.com/Article/details/gtxegzxkwg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtgobsjfsz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ppjwa.cn/Article/details/gthwyedill.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.redwolf501.top/Article/details/gtvtljkfms.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.9152youxi.cn/Article/details/gtsfxmgldo.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yj20258888.top/Article/details/gtmyebezrz.html

[D25] Set 集合去重与交并差
来源：http://dali.meibo888.top/Article/details/gtweruwbju.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.quarkkingdee.top/Article/details/gtqohasjwm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jqgufenzy.top/Article/details/gttcjadhqk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtqeqdglyy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xinyue.icu/Article/details/gtpfqkffjl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ybcxt.top/Article/details/gtfgkaxasu.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yj20258888.top/Article/details/gtxagjexhq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.daria6918.cn/Article/details/gteklbrnyg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtbmkdeirt.html

[D26] 数组转字符串
来源：http://dali.nwbrower.top/Article/details/gtwschzepb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cheryme.top/Article/details/gtflsfemoj.html

PHP:  implode(", ", $arr);
来源：http://dali.dashuyun.cn/Article/details/gtbvavdgrr.html

JS:   arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gtgqpevnhm.html

TS:   arr.join(", ")
来源：http://dali.meibo888.top/Article/details/gtbogyqjxm.html

Java: String.join(", ", list)
来源：http://dali.xuetiantiany.cn/Article/details/gtcndpeleh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sufxvd.cn/Article/details/gthdllmdpb.html

Ruby: arr.join(", ")
来源：http://dali.svipenyu.cn/Article/details/gtqdjihtsn.html

C#:   string.Join(", ", list)
来源：http://dali.zhengqikj.top/Article/details/gtfowrjqow.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtdqfxlbpa.html

E. 字符串处理
来源：http://dali.sweek.top/Article/details/gtwicccxuj.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtptwthecz.html

[E01] 拼接字符串
来源：http://dali.316326.xyz/Article/details/gtozecxlnr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sxryk.cn/Article/details/gtlykirtha.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.birdmap.top/Article/details/gtpnhkwamd.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtljzvrpxz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gzhubu.top/Article/details/gtqboqscef.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gaohongyu789.top/Article/details/gtlcflqrcb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.0kj1m.cn/Article/details/gtatvmfmen.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yangfankeji.com/Article/details/gtsywsdjnx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtgwaznpnz.html

[E02] 重复字符串
来源：http://dali.yuanzhike.top/Article/details/gtrnvfpvsr.html

Py:   "ab" * 3
来源：http://dali.hfpthk.cn/Article/details/gtwuauszek.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sweek.top/Article/details/gtzfvweqbc.html

JS:   "ab".repeat(3)
来源：http://dali.9152youxi.cn/Article/details/gtfexssjly.html

TS:   "ab".repeat(3)
来源：http://dali.wangdashe.top/Article/details/gtlphvqnrj.html

Java: "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gtuvvqhmlq.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.316326.xyz/Article/details/gtmzwosmjy.html

Ruby: "ab" * 3
来源：http://dali.xuanzx.com/Article/details/gtnfgtxuhz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhiwuduotai.top/Article/details/gthdydljik.html

[E03] 截取子串
来源：http://dali.c1oappe.top/Article/details/gtvlrdstnu.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shangyingyoupin.top/Article/details/gtwbrgvptw.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gtcybsqtxn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.redwolf501.top/Article/details/gtssdvzwbh.html

TS:   s.slice(1, 4)
来源：http://dali.mhx1999.top/Article/details/gtlttzgbwx.html

Java: s.substring(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gtqhjhksiq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.dianchejie.cn/Article/details/gtmfzrnujz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.nanxinkj.top/Article/details/gthigefxtd.html

C#:   s.Substring(1, 3)
来源：http://dali.316326.xyz/Article/details/gtkzwcnsch.html

[E04] 查找子串位置
来源：http://dali.snrcjt.cn/Article/details/gthqmxapuq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cdnleiting.top/Article/details/gtyhtgkjul.html

PHP:  strpos($s, "x");
来源：http://dali.gzhubu.top/Article/details/gtwvnghpkt.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.quarkkingdee.top/Article/details/gttqeebrnk.html

TS:   s.indexOf("x")
来源：http://dali.redwolf501.top/Article/details/gtwlgvuptm.html

Java: s.indexOf("x")
来源：http://dali.cashguo.top/Article/details/gthuqpqqpd.html

Go:   strings.Index(s, "x")
来源：http://dali.ehwqpu.com/Article/details/gtwdgcyrbj.html

Ruby: s.index("x")
来源：http://dali.zhiwuduotai.top/Article/details/gtkpgdbkvw.html

C#:   s.IndexOf("x")
来源：http://dali.sxryk.cn/Article/details/gtpvsalulj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cheryme.top/Article/details/gtvhcmcsbo.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hysaishi.cn/Article/details/gtepuzirnv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.pycfn.com/Article/details/gthxkydxin.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgfzy.top/Article/details/gthzazkkit.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sweek.top/Article/details/gtzyzwasva.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuanzx.com/Article/details/gtwxfyyfba.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.meibo888.top/Article/details/gtcuypfihn.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmedfojgv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.aibaodan.cn/Article/details/gtydmeopye.html

[E06] 替换子串
来源：http://dali.yj20258.top/Article/details/gtclcvbyie.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.pycfn.com/Article/details/gtvatakxsx.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.chenzaomai.com/Article/details/gtxkphefmr.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtscdwmbrz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtytxwqpyc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtiwdtomde.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.nanxinkj.top/Article/details/gtiyhhteid.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yvedp.cn/Article/details/gthqdtcesl.html

C#:   s.Replace("a", "b")
来源：http://dali.ivvv.top/Article/details/gtdouoiihi.html

[E07] 按分隔符拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gthmuctaum.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.nanxuanxn.top/Article/details/gtztzmlhpm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.aizwys.cn/Article/details/gtnrlfxbqs.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.pengpengdd.cyou/Article/details/gtxcxguztz.html

TS:   s.split(",")
来源：http://dali.hammf.cn/Article/details/gtsinaihvz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cucudq.cn/Article/details/gteuiuydrb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gaohongyu789.top/Article/details/gtbdliqxed.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gtcgecbvuj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cashguo.top/Article/details/gtxfeygitb.html

[E08] 数组按分隔符合并
来源：http://dali.nwbrower.top/Article/details/gtpkbbygwk.html

Py:   ",".join(items)
来源：http://dali.yonumen.top/Article/details/gtaqmnmbor.html

PHP:  implode(",", $items);
来源：http://dali.cashguo.top/Article/details/gtwumarkvp.html

JS:   items.join(",")
来源：http://dali.guowangkeji.top/Article/details/gtdzxafdbn.html

TS:   items.join(",")
来源：http://dali.yj20258888.top/Article/details/gtipbmjeea.html

Java: String.join(",", items)
来源：http://dali.nanxinkj.top/Article/details/gtaopbzkyd.html

Go:   strings.Join(items, ",")
来源：http://dali.shzxlz.cn/Article/details/gtbzgaosxe.html

Ruby: items.join(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxkfysjdo.html

C#:   string.Join(",", items)
来源：http://dali.9152youxi.cn/Article/details/gtqzpcadxw.html

[E09] 去除所有空白字符
来源：http://dali.jinqigufen.top/Article/details/gtcdxqappk.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xylfe.cn/Article/details/gtctnjkpmk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gzhubu.top/Article/details/gtfoqnieab.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.dianchejie.cn/Article/details/gtlcwpgjvb.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yonumen.top/Article/details/gtralgntob.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.vqdsnc.cn/Article/details/gtyfrkwfrk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xylfe.cn/Article/details/gttmydkxmi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhoulong.xyz/Article/details/gtqmzihmxs.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqsftvtcu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cashguo.top/Article/details/gtwedoiuvf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xinyue.icu/Article/details/gtaeopobjf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenzaomai.com/Article/details/gtzhsimuur.html

JS:   "7".padStart(3, "0")
来源：http://dali.c1oappe.top/Article/details/gtxruwirgd.html

TS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfwtqriua.html

Java: String.format("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gtvqhnddnl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhiwuduotai.top/Article/details/gtuzsuyjdg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gtfpeapizw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cashguo.top/Article/details/gtqxlhmfpw.html

[E11] 反转字符串
来源：http://dali.xuanzx.com/Article/details/gtispicenb.html

Py:   s[::-1]
来源：http://dali.hongshengwenyu.top/Article/details/gtycxggvfp.html

PHP:  strrev($s);
来源：http://dali.dianchejie.cn/Article/details/gtneyumqrv.html

JS:   [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gturdwsnep.html

TS:   [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gtmjkcsqso.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shuidangran.top/Article/details/gtiarbksqh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gaohongyu789.top/Article/details/gtqjlksort.html

Ruby: s.reverse
来源：http://dali.daxiang520.top/Article/details/gtvhapszqt.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.redwolf501.top/Article/details/gtscyryxwk.html

[E12] 统计某字符出现次数
来源：http://dali.zdqjudy.top/Article/details/gtlqwansss.html

Py:   s.count("a")
来源：http://dali.yuanzhike.top/Article/details/gtjfwpfkyd.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gttfdumddg.html

JS:   s.split("a").length - 1
来源：http://dali.jiagoushi.top/Article/details/gtzpidlstz.html

TS:   s.split("a").length - 1
来源：http://dali.cdnleiting.top/Article/details/gtkhkkjgyc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shangyingyoupin.top/Article/details/gtobbrspst.html

Go:   strings.Count(s, "a")
来源：http://dali.havefunace.top/Article/details/gtvwlqwfnx.html

Ruby: s.count("a")
来源：http://dali.vqdsnc.cn/Article/details/gtmgwrbcqv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jqgufenzy.top/Article/details/gtrxpckfmu.html

[E13] 逐字符遍历
来源：http://dali.cdnleiting.top/Article/details/gtjnltjsro.html

Py:   for ch in s: print(ch)
来源：http://dali.cheryme.top/Article/details/gtntuscxbg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.316326.xyz/Article/details/gtbkmaxxyo.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gogol.net.cn/Article/details/gtbgivrren.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.mhx1999.top/Article/details/gtvafhljvf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.bjfxy.top/Article/details/gthpzvvtjk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.bjfxy.top/Article/details/gtarhuyblk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.tanke756.top/Article/details/gtyypmuoia.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.guannengcc.top/Article/details/gtfmlbalum.html

[E14] URL 编码与 Base64
来源：http://dali.zhoulong.xyz/Article/details/gtfrvdhvxm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj20258888.top/Article/details/gtlzzzbjoi.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.sxryk.cn/Article/details/gtstxbfjlj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.smart0.xyz/Article/details/gthiitchek.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxqbkppg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.dianchejie.cn/Article/details/gtdmewadcu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gotoacloud.top/Article/details/gteqjlgtfv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.smart0.xyz/Article/details/gtycnezxuj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.pycfn.com/Article/details/gtsifnpuxm.html

[E15] HTML 转义 / 反转义
来源：http://dali.shanyushiyangtech.top/Article/details/gtvbqcoixm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jlsjyb.cn/Article/details/gtyafsylzy.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.aibaodan.cn/Article/details/gtvxmcfkml.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gogol.net.cn/Article/details/gttqzjbfin.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.iojbl.cn/Article/details/gttgrqsdpo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hywenlv.cn/Article/details/gtrjdqhyrz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.daria6918.cn/Article/details/gtnmlkvpfg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hnqzz.top/Article/details/gtxkstwsch.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.guowangkeji.top/Article/details/gtxhflikdo.html

[E16] 数字千分位
来源：http://dali.shanyushiyangkeji.top/Article/details/gtidhmignd.html

Py:   f"{1234567:,}"
来源：http://dali.zhiwuduotai.top/Article/details/gtsqwmzfmj.html


<!-- 参考信息 -->