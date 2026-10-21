代发 wailian999

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.tanke756.top/Article/details/gtljmlmmvx.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.316326.xyz/Article/details/gtavfwgmpy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ybcxt.top/Article/details/gtqmcfvarj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenlongwang.top/Article/details/gtgosqerxd.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gzhubu.top/Article/details/gtwjtepzts.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.wangdashe.top/Article/details/gtfodchast.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yuanzhike.top/Article/details/gtoyajuxto.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.nanxuanxn.top/Article/details/gtuxyshkwd.html

[D11] 反转数组
来源：http://dali.sweek.top/Article/details/gtylesyaiw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shanyushiyangtech.top/Article/details/gtspviafdc.html

PHP:  array_reverse($arr);
来源：http://dali.cdnleiting.top/Article/details/gtufcixtiu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.feifeiyinyue.top/Article/details/gtxgthilmx.html

TS:   [...arr].reverse();
来源：http://dali.ehwqpu.com/Article/details/gtnrtmflyx.html

Java: Collections.reverse(list);
来源：http://dali.gogol.net.cn/Article/details/gtxscqjsmi.html

Go:   slices.Reverse(arr)
来源：http://dali.havefunace.top/Article/details/gtrfexjjlm.html

Ruby: arr.reverse
来源：http://dali.chenlongwang.top/Article/details/gtqsiqzseh.html

C#:   list.Reverse();
来源：http://dali.kuanghao11.cn/Article/details/gtrgjnavlg.html

[D12] 查找元素下标
来源：http://dali.shzxlz.cn/Article/details/gtrcfllskj.html

Py:   arr.index(x);  x in arr
来源：http://dali.cucudq.cn/Article/details/gtefqxpoei.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtydrvcmaw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xinyue.icu/Article/details/gtdhjlgdim.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fengsongda.top/Article/details/gtovhoxszj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yongpay.top/Article/details/gtvunpnnwo.html

Go:   slices.Index(arr, x)
来源：http://dali.cheryme.top/Article/details/gtecyzxmxd.html

Ruby: arr.index(x)
来源：http://dali.yangfankeji.com/Article/details/gthkkgordu.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gttonbvjdj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gzhubu.top/Article/details/gtwkgiqswm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yvedp.cn/Article/details/gtslteywtt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gzhubu.top/Article/details/gtgcdwldjv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jqgufenzy.top/Article/details/gthbqnqxye.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtpfffvmsx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gaohongyu789.top/Article/details/gtqextiowd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ydzc1.top/Article/details/gtcacvztac.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nanxinkj.top/Article/details/gthxotsvmk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinqigufen.top/Article/details/gtxgkdqphn.html

[D14] 映射转换（每个元素变形）
来源：http://dali.wangshuangyany.cn/Article/details/gtbvuygbbd.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gotoacloud.top/Article/details/gtcjlttcyo.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sysykeji.top/Article/details/gtbnmaqlyd.html

JS:   arr.map(x => x * 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsdiknhtg.html

TS:   arr.map(x => x * 2)
来源：http://dali.dashuyun.cn/Article/details/gtshzbtwrc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.daria6918.cn/Article/details/gttbfgmknu.html

Go:   // 手写循环
来源：http://dali.yj20258888.top/Article/details/gtbozvqbpr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shzxlz.cn/Article/details/gtoycbayoq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtyyjzjtcg.html

[D15] 去重
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlrajnsai.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhixingplan.top/Article/details/gtiglvcvzz.html

PHP:  array_unique($arr);
来源：http://dali.iojbl.cn/Article/details/gttcvhybgy.html

JS:   [...new Set(arr)]
来源：http://dali.havefunace.top/Article/details/gtarqpkvwr.html

TS:   [...new Set(arr)]
来源：http://dali.nanxuanxn.top/Article/details/gtbrkvrdtk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jqgufenzy.top/Article/details/gtqrqsegrc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhengqikj.top/Article/details/gtaooqbask.html

Ruby: arr.uniq
来源：http://dali.xinyue.icu/Article/details/gtygwlbpyp.html

C#:   list.Distinct().ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtczbszyge.html

[D16] 求和与平均值
来源：http://dali.daxiang520.top/Article/details/gtqejyiutv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xziqi.cn/Article/details/gtsltkxcsb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ivvv.top/Article/details/gtorypbebk.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtsmutyfla.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daria6918.cn/Article/details/gtosyiotkv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.meibo888.top/Article/details/gtavaembqo.html

Go:   // 手写循环累加
来源：http://dali.ivvv.top/Article/details/gtgorefwna.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cdnleiting.top/Article/details/gtljsnmlfx.html

C#:   list.Sum();  list.Average()
来源：http://dali.mhx1999.top/Article/details/gtuzjfqevs.html

[D17] 最大值与最小值
来源：http://dali.quarkkingdee.top/Article/details/gtsbhttawg.html

Py:   max(arr);  min(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtvlvytbit.html

PHP:  max($arr);  min($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkxtmmaru.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.tian-w.cn/Article/details/gtnsikswmh.html

TS:   Math.max(...arr);
来源：http://dali.havefunace.top/Article/details/gttauluvfk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.9152youxi.cn/Article/details/gteioajhsa.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthrqylcet.html

Ruby: arr.max;  arr.min
来源：http://dali.havefunace.top/Article/details/gtprivqhwe.html

C#:   list.Max();  list.Min()
来源：http://dali.meibo888.top/Article/details/gtihdgprow.html

[D18] 扁平化嵌套数组
来源：http://dali.yanxiufei.cn/Article/details/gtjpkdmaxt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sxryk.cn/Article/details/gtexfdqbez.html

PHP:  array_merge(...$nested);
来源：http://dali.hfpthk.cn/Article/details/gtfkwguuci.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yj202588.top/Article/details/gtfcxpbzts.html

TS:   nested.flat();
来源：http://dali.meibo888.top/Article/details/gtavlgmmjh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.andypj.xyz/Article/details/gtrivesnsu.html

Go:   // 手写双层循环
来源：http://dali.0kj1m.cn/Article/details/gtwhdjddub.html

Ruby: nested.flatten
来源：http://dali.yonumen.top/Article/details/gtwmegfipu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtrmpmntvl.html

[D19] 按字段分组
来源：http://dali.pengpengdd.cyou/Article/details/gtsumqsfla.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.daria6918.cn/Article/details/gtbbwbvqvd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hnqzz.top/Article/details/gtpctvyqlr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.aibaodan.cn/Article/details/gtnbvdtshj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.mhx1999.top/Article/details/gtrbtdzlxm.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shzxlz.cn/Article/details/gtwlaxceuu.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gtykamfpze.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhiwuduotai.top/Article/details/gtmoeqebzm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yuanzhike.top/Article/details/gtcqagnoca.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gtvcfvevse.html

Py:   Counter(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsiijafaa.html

PHP:  array_count_values($arr);
来源：http://dali.tian-w.cn/Article/details/gteotlkreo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xziqi.cn/Article/details/gtdwwblvfu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258888.top/Article/details/gtvevsitxh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xinyue.icu/Article/details/gtkkjxbjgx.html

Go:   // 手写 map[T]int
来源：http://dali.cucudq.cn/Article/details/gtczfdxzmd.html

Ruby: arr.tally
来源：http://dali.zhengqikj.top/Article/details/gtbbtihqxo.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.wangdashe.top/Article/details/gtrkusvpyb.html

[D21] 判断是否包含某元素
来源：http://dali.cheryme.top/Article/details/gtgsopwcet.html

Py:   x in arr
来源：http://dali.shanyushiyangtech.top/Article/details/gtlvxmrhss.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xziqi.cn/Article/details/gtsvrqibod.html

JS:   arr.includes(x)
来源：http://dali.gogol.net.cn/Article/details/gtkseezwmn.html

TS:   arr.includes(x)
来源：http://dali.daria6918.cn/Article/details/gtqdzljfjg.html

Java: list.contains(x)
来源：http://dali.jinqigufen.top/Article/details/gtzlkzgbur.html

Go:   slices.Contains(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtbkrryliz.html

Ruby: arr.include?(x)
来源：http://dali.daria6918.cn/Article/details/gtorgruptj.html

C#:   list.Contains(x)
来源：http://dali.daxiang520.top/Article/details/gtmcupgcnk.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hywenlv.cn/Article/details/gtgppamrtc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtlwhbzfih.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gotoacloud.top/Article/details/gtilepgtoe.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yueranfly.top/Article/details/gtiacnmdhs.html

TS:   [...arr];
来源：http://dali.yanxiufei.cn/Article/details/gtvcdkmmms.html

Java: new ArrayList<>(list);
来源：http://dali.iojbl.cn/Article/details/gtgcsqthcp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jyoumei.cn/Article/details/gtgefzfrqh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.mhx1999.top/Article/details/gtpuntvazb.html

C#:   new List<int>(list);
来源：http://dali.cdnleiting.top/Article/details/gtlxjcsmwx.html

[D23] reduce 累积计算
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbfjevjj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.daxiang520.top/Article/details/gtbgiwzelo.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cucudq.cn/Article/details/gtmyugnlsi.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dianchejie.cn/Article/details/gtefcspkex.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj202588.top/Article/details/gtdmgwidqf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xuanzx.com/Article/details/gtdlpibtan.html

Go:   // 手写循环
来源：http://dali.birdmap.top/Article/details/gtublxwkqi.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.fengsongda.top/Article/details/gtlvjbqymo.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sweek.top/Article/details/gthtyqkhfh.html

[D24] 字典 / Map 基本操作
来源：http://dali.zycfv.cn/Article/details/gtkyqszqrr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhengqikj.top/Article/details/gtypodmdgs.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.nanxuanxn.top/Article/details/gtvptwvxtd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.mhx1999.top/Article/details/gtjapfgpfm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shuidangran.top/Article/details/gtnfurrpsb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.iojbl.cn/Article/details/gtgpaelmdl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hywenlv.cn/Article/details/gtshavokob.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.aibaodan.cn/Article/details/gtqwwumjxo.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenzaomai.com/Article/details/gtkuureucv.html

[D25] Set 集合去重与交并差
来源：http://dali.aizwys.cn/Article/details/gtsaaukjpp.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zdqjudy.top/Article/details/gtvthcqilz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.guannengcc.top/Article/details/gtajrhevdp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.meibo888.top/Article/details/gtcbqjwfzh.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhiwuduotai.top/Article/details/gtzkmutrba.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtderhtlsv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jqgufenzy.top/Article/details/gtfiehgjpp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hnxiangtu.top/Article/details/gtdrmsuddo.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.haohaochexian.top/Article/details/gtffzpobxw.html

[D26] 数组转字符串
来源：http://dali.jiagoushi.top/Article/details/gtirjhflyf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.nanxuanxn.top/Article/details/gtvpdevhyc.html

PHP:  implode(", ", $arr);
来源：http://dali.meibo888.top/Article/details/gtcdevvrux.html

JS:   arr.join(", ")
来源：http://dali.ybcxt.top/Article/details/gtvotvtith.html

TS:   arr.join(", ")
来源：http://dali.sxryk.cn/Article/details/gtvxqhxwkj.html

Java: String.join(", ", list)
来源：http://dali.cdnleiting.top/Article/details/gtvgscarkz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.chenzaomai.com/Article/details/gtlpqsuyfl.html

Ruby: arr.join(", ")
来源：http://dali.bjfxy.top/Article/details/gtjvuqgjnb.html

C#:   string.Join(", ", list)
来源：http://dali.feifeiyinyue.top/Article/details/gtzhwnccxu.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtiuvhqqdz.html

E. 字符串处理
来源：http://dali.zhongyouzk.top/Article/details/gtlwysguih.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtduwenlif.html

[E01] 拼接字符串
来源：http://dali.iojbl.cn/Article/details/gtgcxcjzsr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xziqi.cn/Article/details/gttsqubnol.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xylfe.cn/Article/details/gtztdxmgds.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenlongwang.top/Article/details/gtgvrjeoyo.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daxiang520.top/Article/details/gtsgzgeqra.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.haohaochexian.top/Article/details/gtsbcjfaxk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.aibaodan.cn/Article/details/gtmcfclwmi.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.tanke756.top/Article/details/gtqjbtneyi.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjhzthfmk.html

[E02] 重复字符串
来源：http://dali.daxiang520.top/Article/details/gtjcektwgv.html

Py:   "ab" * 3
来源：http://dali.aizwys.cn/Article/details/gtdduotker.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cheryme.top/Article/details/gteqzdzjxf.html

JS:   "ab".repeat(3)
来源：http://dali.sweek.top/Article/details/gtjbxmdlgq.html

TS:   "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gtslqjrbhz.html

Java: "ab".repeat(3)
来源：http://dali.jqgufenzy.top/Article/details/gtngmgekhk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xuanzx.com/Article/details/gtclvxuivu.html

Ruby: "ab" * 3
来源：http://dali.shanyushiyangtech.top/Article/details/gtcjqretmo.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gaohongyu789.top/Article/details/gtbhnwiwkh.html

[E03] 截取子串
来源：http://dali.redwolf501.top/Article/details/gtctxqgnbj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hfpthk.cn/Article/details/gtgjwobanq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gthxiuzbow.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yj20258888.top/Article/details/gttzqpeqda.html

TS:   s.slice(1, 4)
来源：http://dali.cashguo.top/Article/details/gtztudoqry.html

Java: s.substring(1, 4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgnijfuds.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.pengpengdd.cyou/Article/details/gtiknmeele.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hnxiangtu.top/Article/details/gtffshimem.html

C#:   s.Substring(1, 3)
来源：http://dali.ivvv.top/Article/details/gtxowvjqfb.html

[E04] 查找子串位置
来源：http://dali.kuanghao11.cn/Article/details/gtlihzxvsy.html

Py:   s.find("x");  s.index("x")
来源：http://dali.vqdsnc.cn/Article/details/gtkksnlcpk.html

PHP:  strpos($s, "x");
来源：http://dali.cucudq.cn/Article/details/gtqqnyvjkn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.svipenyu.cn/Article/details/gtpahqymvz.html

TS:   s.indexOf("x")
来源：http://dali.zdqjudy.top/Article/details/gtknuaewir.html

Java: s.indexOf("x")
来源：http://dali.fengsongda.top/Article/details/gtmvuhztui.html

Go:   strings.Index(s, "x")
来源：http://dali.shuidangran.top/Article/details/gtipdbbzwc.html

Ruby: s.index("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgrqemrja.html

C#:   s.IndexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gtmnvipesw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhoulong.xyz/Article/details/gtlerjomct.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.aibaodan.cn/Article/details/gtrseooxtp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hammf.cn/Article/details/gtgemmmerc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.wangdashe.top/Article/details/gtzhzusqjw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yj202588.top/Article/details/gtveskfhjz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gzhubu.top/Article/details/gtdviabqev.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.smart0.xyz/Article/details/gtzjofrblg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.gzhubu.top/Article/details/gtiwaatstm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jqgfzy.top/Article/details/gtijopesol.html

[E06] 替换子串
来源：http://dali.yongpay.top/Article/details/gtickejoqc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.tianlin.xyz/Article/details/gtuabnewgb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.redwolf501.top/Article/details/gtabpghaye.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gthrbxyesz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.smart0.xyz/Article/details/gtjlwxswlf.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtkxsgmbym.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yj202588.top/Article/details/gtscomhrvz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtpnfqvhog.html

C#:   s.Replace("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtitchtoel.html

[E07] 按分隔符拆分
来源：http://dali.chenjidiqi.icu/Article/details/gtordssyio.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yangfankeji.com/Article/details/gtjjftobpa.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sweek.top/Article/details/gtbfilidfd.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zycfv.cn/Article/details/gtojxmwcvg.html

TS:   s.split(",")
来源：http://dali.ivvv.top/Article/details/gtgdhrljkt.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.aibaodan.cn/Article/details/gtinigarso.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xinyue.icu/Article/details/gtpjesgyco.html

Ruby: s.split(",");  s.split
来源：http://dali.snrcjt.cn/Article/details/gtqvwcrpok.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.dashuyun.cn/Article/details/gtewvzkuvb.html

[E08] 数组按分隔符合并
来源：http://dali.daxiang520.top/Article/details/gtuqqfmdpb.html

Py:   ",".join(items)
来源：http://dali.feifeiyinyue.top/Article/details/gthhwimtbe.html

PHP:  implode(",", $items);
来源：http://dali.meibo888.top/Article/details/gtghmmwxvp.html

JS:   items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gtnqctfsuk.html

TS:   items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvbjownhp.html

Java: String.join(",", items)
来源：http://dali.jlsjyb.cn/Article/details/gtelskdber.html

Go:   strings.Join(items, ",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqdxyeghy.html

Ruby: items.join(",")
来源：http://dali.fzhhl.top/Article/details/gtgcsfktbx.html

C#:   string.Join(",", items)
来源：http://dali.dashuyun.cn/Article/details/gtoqferjig.html

[E09] 去除所有空白字符
来源：http://dali.jinqigufen.top/Article/details/gtltmggosj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hfpthk.cn/Article/details/gtdepwjbuf.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gogol.net.cn/Article/details/gtvpenasyu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhiwuduotai.top/Article/details/gtmxitmycq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xinyue.icu/Article/details/gtszrbylzw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.wangdashe.top/Article/details/gtmyznkpqw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcvaaeovi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.aibaodan.cn/Article/details/gtrabtmkmr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yangfankeji.com/Article/details/gtvfdjawcn.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj20258888.top/Article/details/gtbazenptz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gtxgujlmza.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyelgszgk.html

JS:   "7".padStart(3, "0")
来源：http://dali.svipenyu.cn/Article/details/gtjcmofpiq.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfrekoue.html

Java: String.format("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gtgfthetjv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.dashuyun.cn/Article/details/gtfqhojpcz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gtuckyzoae.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jqgufenzy.top/Article/details/gteqgqzdib.html

[E11] 反转字符串
来源：http://dali.haohaochexian.top/Article/details/gtsipcftbd.html

Py:   s[::-1]
来源：http://dali.chenjidiqi.icu/Article/details/gtvyahzobf.html

PHP:  strrev($s);
来源：http://dali.0kj1m.cn/Article/details/gtcmfmgakv.html

JS:   [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gtmfbkfwhg.html

TS:   [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gtewikmzxu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.bjfxy.top/Article/details/gtceqkwqav.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yj20258888.top/Article/details/gtnataekhl.html

Ruby: s.reverse
来源：http://dali.ppjwa.cn/Article/details/gtifcvvzjq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nwbrower.top/Article/details/gtuqkihlrs.html

[E12] 统计某字符出现次数
来源：http://dali.yj20258888.top/Article/details/gtcomjtmib.html

Py:   s.count("a")
来源：http://dali.xuetiantiany.cn/Article/details/gtoebwsfxa.html

PHP:  substr_count($s, "a");
来源：http://dali.iojbl.cn/Article/details/gtqbzzjlgt.html

JS:   s.split("a").length - 1
来源：http://dali.fzhhl.top/Article/details/gtbqdkipii.html

TS:   s.split("a").length - 1
来源：http://dali.snrcjt.cn/Article/details/gteqglgpyn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.nwbrower.top/Article/details/gteniczlke.html

Go:   strings.Count(s, "a")
来源：http://dali.jqgufenzy.top/Article/details/gtrsuoqenf.html

Ruby: s.count("a")
来源：http://dali.9152youxi.cn/Article/details/gtgxjmozsi.html

C#:   s.Count(c => c == 'a')
来源：http://dali.316326.xyz/Article/details/gtnjzwqdhv.html

[E13] 逐字符遍历
来源：http://dali.dashuyun.cn/Article/details/gtomwuvkxh.html

Py:   for ch in s: print(ch)
来源：http://dali.ivvv.top/Article/details/gtauredbxc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shuidangran.top/Article/details/gtsrmeypmn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zdqjudy.top/Article/details/gtcpmibnuh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gtogxzzkpf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ydzc1.top/Article/details/gtjfjeyfhu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtudjkqgzh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cdnleiting.top/Article/details/gtncaylsov.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.fzhhl.top/Article/details/gtpikggexo.html

[E14] URL 编码与 Base64
来源：http://dali.yvedp.cn/Article/details/gtencmttis.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj202588.top/Article/details/gtlvdbwxxq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtersumamb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinghuilouyu.cn/Article/details/gtozapiddk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cqqwz.cn/Article/details/gtshvvtxwh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.fzhhl.top/Article/details/gtxqkasozc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cucudq.cn/Article/details/gtyplupxyb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.dashuyun.cn/Article/details/gtdocdfckx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj20258.top/Article/details/gtbfhxaekx.html

[E15] HTML 转义 / 反转义
来源：http://dali.sufxvd.cn/Article/details/gtaqghqbxm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj20258.top/Article/details/gtvfetiaan.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.birdmap.top/Article/details/gtyyzrfwgi.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zycfv.cn/Article/details/gtxfcprwjv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yonumen.top/Article/details/gtranueypn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.wangshuangyany.cn/Article/details/gtoftgqekc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtjrihssqg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.dianchejie.cn/Article/details/gtymrnhvft.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.haohaochexian.top/Article/details/gtbdnrgrfd.html

[E16] 数字千分位
来源：http://dali.bjfxy.top/Article/details/gteodxjhvx.html

Py:   f"{1234567:,}"
来源：http://dali.jinqigufen.top/Article/details/gthtqzavyq.html

PHP:  number_format(1234567);
来源：http://dali.gogol.net.cn/Article/details/gtwlhkkegt.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yanxiufei.cn/Article/details/gtdfwhkbai.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.vqdsnc.cn/Article/details/gtcxtzusgb.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.gogol.net.cn/Article/details/gtmoayhmiz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.fzhhl.top/Article/details/gtyfqvfszw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenzaomai.com/Article/details/gtwaxrhzsp.html

C#:   1234567.ToString("N0")
来源：http://dali.sxryk.cn/Article/details/gtznihlwdr.html

[E17] 首字母大写
来源：http://dali.9152youxi.cn/Article/details/gtgabkshjq.html


<!-- 参考信息 -->