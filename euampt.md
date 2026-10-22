代发 wailian999

Ruby: a + b;  a.concat(b)
来源：http://dali.xuanzx.com/Article/details/gtqavfhvne.html

C#:   a.Concat(b).ToList()
来源：http://dali.c1oappe.top/Article/details/gtiuzfemxv.html

[D09] 排序（升序）
来源：http://dali.hfpthk.cn/Article/details/gtajmszfqi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgyosaygu.html

PHP:  sort($arr);
来源：http://dali.9152youxi.cn/Article/details/gtdssrawwv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrcfpnrus.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.aibaodan.cn/Article/details/gtsiwrejjb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hysaishi.cn/Article/details/gtqqogphzy.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zycfv.cn/Article/details/gtzoougfmp.html

Ruby: arr.sort
来源：http://dali.yangfankeji.com/Article/details/gtcviybvgh.html

C#:   list.Sort();
来源：http://dali.shanyushiyangtech.top/Article/details/gtdqungaft.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cucudq.cn/Article/details/gtgjbnctmn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hnqzz.top/Article/details/gtvwsqjjkd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.meibo888.top/Article/details/gtdgxjillf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhoulong.xyz/Article/details/gtqlhubqly.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhoulong.xyz/Article/details/gtxionkewu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.fengsongda.top/Article/details/gtzjfzloov.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhongyouzk.top/Article/details/gtbckbjycy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hywenlv.cn/Article/details/gtssdzhsta.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.316326.xyz/Article/details/gtgucsosya.html

[D11] 反转数组
来源：http://dali.hammf.cn/Article/details/gtdviiarji.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xuanzx.com/Article/details/gtugurjjhq.html

PHP:  array_reverse($arr);
来源：http://dali.pycfn.com/Article/details/gtgrfcixyz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.vqdsnc.cn/Article/details/gtwqoxzxdv.html

TS:   [...arr].reverse();
来源：http://dali.yonumen.top/Article/details/gtcofeyfck.html

Java: Collections.reverse(list);
来源：http://dali.dianchejie.cn/Article/details/gtjngqzmcz.html

Go:   slices.Reverse(arr)
来源：http://dali.dianchejie.cn/Article/details/gtixukuwcj.html

Ruby: arr.reverse
来源：http://dali.hywenlv.cn/Article/details/gtrzqkissk.html

C#:   list.Reverse();
来源：http://dali.0kj1m.cn/Article/details/gtejoxcqpc.html

[D12] 查找元素下标
来源：http://dali.sxryk.cn/Article/details/gtvbeurchp.html

Py:   arr.index(x);  x in arr
来源：http://dali.hnqzz.top/Article/details/gtmkgrsghe.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.havefunace.top/Article/details/gtemyrrhix.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fzhhl.top/Article/details/gtbspunkit.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxuanxn.top/Article/details/gteqfikljt.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gotoacloud.top/Article/details/gtrtonznnb.html

Go:   slices.Index(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtoqdtigxc.html

Ruby: arr.index(x)
来源：http://dali.nwbrower.top/Article/details/gtyriytjiu.html

C#:   list.IndexOf(x);
来源：http://dali.yangfankeji.com/Article/details/gtvylolcyw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xuanzx.com/Article/details/gtiporofpi.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.iojbl.cn/Article/details/gtejyicpyl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nanxuanxn.top/Article/details/gtjftzuitd.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cashguo.top/Article/details/gtkykwysny.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cheryme.top/Article/details/gtazusvnpg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gttxiyrzip.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.wangdashe.top/Article/details/gtfpwhbtvj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nanxinkj.top/Article/details/gtvdbcudpv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cucudq.cn/Article/details/gtjubijrbu.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hfpthk.cn/Article/details/gtsdlbpfhe.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.meibo888.top/Article/details/gtwmfcsxcy.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jiagoushi.top/Article/details/gtffcbxduo.html

JS:   arr.map(x => x * 2)
来源：http://dali.yj202588.top/Article/details/gtooghqpyz.html

TS:   arr.map(x => x * 2)
来源：http://dali.aizwys.cn/Article/details/gtkubrnrxl.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zdqjudy.top/Article/details/gtfqpfvgly.html

Go:   // 手写循环
来源：http://dali.andypj.xyz/Article/details/gtzvslxjts.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.iojbl.cn/Article/details/gtmmpwtnru.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.birdmap.top/Article/details/gtujwdwwvx.html

[D15] 去重
来源：http://dali.jianghu66.top/Article/details/gtcwrliral.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.dashuyun.cn/Article/details/gtvjvkclaw.html

PHP:  array_unique($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwtyrfifm.html

JS:   [...new Set(arr)]
来源：http://dali.gaohongyu789.top/Article/details/gtggircivn.html

TS:   [...new Set(arr)]
来源：http://dali.yuxming.cn/Article/details/gtqpfcebrj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhixingplan.top/Article/details/gtuladwsfy.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.9152youxi.cn/Article/details/gtzsbihgdc.html

Ruby: arr.uniq
来源：http://dali.jlsjyb.cn/Article/details/gtugajiokr.html

C#:   list.Distinct().ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrvdvjjoe.html

[D16] 求和与平均值
来源：http://dali.hfpthk.cn/Article/details/gtibfkeboc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.aizwys.cn/Article/details/gtwhnktdif.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hfpthk.cn/Article/details/gthvmyjzpi.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hywenlv.cn/Article/details/gtngynuxxv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.c1oappe.top/Article/details/gtoyqsncby.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ehwqpu.com/Article/details/gtlvjjimeq.html

Go:   // 手写循环累加
来源：http://dali.aizwys.cn/Article/details/gtanizedre.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shanyushiyangkeji.top/Article/details/gteptzrrwn.html

C#:   list.Sum();  list.Average()
来源：http://dali.iojbl.cn/Article/details/gtllmrcals.html

[D17] 最大值与最小值
来源：http://dali.yuanzhike.top/Article/details/gtgtngzjvq.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gttxvxxert.html

PHP:  max($arr);  min($arr);
来源：http://dali.xziqi.cn/Article/details/gtfdcprmte.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.redwolf501.top/Article/details/gtriesaoho.html

TS:   Math.max(...arr);
来源：http://dali.tianlin.xyz/Article/details/gtjtswzshm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gaohongyu789.top/Article/details/gtxwjxpkhj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cucudq.cn/Article/details/gtblhfxhyg.html

Ruby: arr.max;  arr.min
来源：http://dali.bjfxy.top/Article/details/gthnqdmksd.html

C#:   list.Max();  list.Min()
来源：http://dali.shuidangran.top/Article/details/gtvlsscjnt.html

[D18] 扁平化嵌套数组
来源：http://dali.jinqigfzy.top/Article/details/gttxzfadat.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xylfe.cn/Article/details/gtcomrtlgr.html

PHP:  array_merge(...$nested);
来源：http://dali.yuanzhike.top/Article/details/gtrjbdevji.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jqgufenzy.top/Article/details/gtmtznkzva.html

TS:   nested.flat();
来源：http://dali.tianlin.xyz/Article/details/gtpvvczuxp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sweek.top/Article/details/gtwecqfakw.html

Go:   // 手写双层循环
来源：http://dali.tian-w.cn/Article/details/gtggybkxez.html

Ruby: nested.flatten
来源：http://dali.sxryk.cn/Article/details/gtnffianmc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtpzjbdbnr.html

[D19] 按字段分组
来源：http://dali.hnxiangtu.top/Article/details/gtrmjbeqpw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shzxlz.cn/Article/details/gtcmoxgpmi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shuidangran.top/Article/details/gtkobouzww.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xylfe.cn/Article/details/gtdmwwxiaw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.daxiang520.top/Article/details/gtwpomhvxr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.9152youxi.cn/Article/details/gtfgrxnbwe.html

Go:   // 手写 map[string][]T
来源：http://dali.gaohongyu789.top/Article/details/gtwrozcskr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.aizwys.cn/Article/details/gtznnntzan.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.fzhhl.top/Article/details/gtqdboocwk.html

[D20] 统计每个元素出现次数
来源：http://dali.birdmap.top/Article/details/gtgneiosbj.html

Py:   Counter(arr)
来源：http://dali.dashuyun.cn/Article/details/gthniiilex.html

PHP:  array_count_values($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtahuritxg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tianlin.xyz/Article/details/gtricjvgmp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sufxvd.cn/Article/details/gtmtyscvts.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.snrcjt.cn/Article/details/gtvoxkolbb.html

Go:   // 手写 map[T]int
来源：http://dali.nanxinkj.top/Article/details/gtwllqvzhp.html

Ruby: arr.tally
来源：http://dali.jinqigufen.top/Article/details/gtymvcbaud.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.fzhhl.top/Article/details/gtiggomlfw.html

[D21] 判断是否包含某元素
来源：http://dali.xylfe.cn/Article/details/gtfiyanqzg.html

Py:   x in arr
来源：http://dali.fzhhl.top/Article/details/gtrjwpngdi.html

PHP:  in_array($x, $arr, true);
来源：http://dali.snrcjt.cn/Article/details/gtuoikvzwc.html

JS:   arr.includes(x)
来源：http://dali.hnqzz.top/Article/details/gtjsyljray.html

TS:   arr.includes(x)
来源：http://dali.xylfe.cn/Article/details/gtfpfzmqxa.html

Java: list.contains(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnkyfjvjv.html

Go:   slices.Contains(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gthrxsyzcw.html

Ruby: arr.include?(x)
来源：http://dali.xziqi.cn/Article/details/gtknypldav.html

C#:   list.Contains(x)
来源：http://dali.xuanzx.com/Article/details/gtmycvhgiv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhoulong.xyz/Article/details/gtbtdapkvc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yvedp.cn/Article/details/gtvgfpnavl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.0kj1m.cn/Article/details/gtafdmgfep.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfdsmozkj.html

TS:   [...arr];
来源：http://dali.andypj.xyz/Article/details/gtifkkhezz.html

Java: new ArrayList<>(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtubkbkddf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.wangdashe.top/Article/details/gtjqvdsuxw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.kuanghao11.cn/Article/details/gttrxcuehj.html

C#:   new List<int>(list);
来源：http://dali.aizwys.cn/Article/details/gtsviwvfzh.html

[D23] reduce 累积计算
来源：http://dali.yongpay.top/Article/details/gtzulfsyec.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zycfv.cn/Article/details/gtzmcokrsm.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.c1oappe.top/Article/details/gtpzgsssxu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cdnleiting.top/Article/details/gtychrlfka.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gogol.net.cn/Article/details/gttodmipty.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhongyouzk.top/Article/details/gtzniszymh.html

Go:   // 手写循环
来源：http://dali.shangyingyoupin.top/Article/details/gtsblzdwxq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.chenlongwang.top/Article/details/gtloxwskym.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenzaomai.com/Article/details/gtaadzcumm.html

[D24] 字典 / Map 基本操作
来源：http://dali.xylfe.cn/Article/details/gtgbltmykn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.haohaochexian.top/Article/details/gthtwmadxj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shuidangran.top/Article/details/gtsmpezscl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.chenlongwang.top/Article/details/gtmslrgyji.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yvedp.cn/Article/details/gtjuwpogth.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xinyue.icu/Article/details/gtpyhmzvlm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ivvv.top/Article/details/gtnsujnqoh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gogol.net.cn/Article/details/gtgeitwtdj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ybcxt.top/Article/details/gturkdrzwu.html

[D25] Set 集合去重与交并差
来源：http://dali.hfpthk.cn/Article/details/gttwbyxrol.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sxryk.cn/Article/details/gtampvfuqv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhongyouzk.top/Article/details/gtugcnzbqq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.haohaochexian.top/Article/details/gtrgnngehk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.daria6918.cn/Article/details/gtbwwsyjgc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenzaomai.com/Article/details/gtughzzcri.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvjvbafll.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtimjxpogv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yuxming.cn/Article/details/gtmekbfwnb.html

[D26] 数组转字符串
来源：http://dali.jqgfzy.top/Article/details/gtjnnbpphq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yongpay.top/Article/details/gtxraejqmz.html

PHP:  implode(", ", $arr);
来源：http://dali.chenzaomai.com/Article/details/gtpmpxnfcb.html

JS:   arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gtnlzrmszh.html

TS:   arr.join(", ")
来源：http://dali.svipenyu.cn/Article/details/gtunaggorp.html

Java: String.join(", ", list)
来源：http://dali.zhiwuduotai.top/Article/details/gtrzcneolf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.tianlin.xyz/Article/details/gtzcydejzh.html

Ruby: arr.join(", ")
来源：http://dali.hammf.cn/Article/details/gtadzmqsnb.html

C#:   string.Join(", ", list)
来源：http://dali.0kj1m.cn/Article/details/gtflpxjsis.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtabosujdm.html

E. 字符串处理
来源：http://dali.xuanzx.com/Article/details/gtdzopytkx.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtakjxollt.html

[E01] 拼接字符串
来源：http://dali.fengsongda.top/Article/details/gtefwhxqtb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yuxming.cn/Article/details/gtujxreaph.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yangfankeji.com/Article/details/gtvexjmiwu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.kuanghao11.cn/Article/details/gtcozwnecp.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.guannengcc.top/Article/details/gtcyxkvqjc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.fengsongda.top/Article/details/gtanvbquje.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gogol.net.cn/Article/details/gtpwgqnpqd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hysaishi.cn/Article/details/gtxjbdfgxl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtiybvzrzi.html

[E02] 重复字符串
来源：http://dali.guowangkeji.top/Article/details/gtwfcfuwtc.html

Py:   "ab" * 3
来源：http://dali.tian-w.cn/Article/details/gtfjptsrwq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.aizwys.cn/Article/details/gtfhkbpcyd.html

JS:   "ab".repeat(3)
来源：http://dali.jianghu66.top/Article/details/gtewuzrinp.html

TS:   "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gtwxbgbzsv.html

Java: "ab".repeat(3)
来源：http://dali.snrcjt.cn/Article/details/gtjxhionuv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zdqjudy.top/Article/details/gtjxfmtzgx.html

Ruby: "ab" * 3
来源：http://dali.xuetiantiany.cn/Article/details/gtjqstijhe.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.daria6918.cn/Article/details/gtqlgkrjgx.html

[E03] 截取子串
来源：http://dali.nanxuanxn.top/Article/details/gtqzshpwai.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yonumen.top/Article/details/gtmlurenfl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gtwoobxyqu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.svipenyu.cn/Article/details/gtrrydowfg.html

TS:   s.slice(1, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdtqontme.html

Java: s.substring(1, 4)
来源：http://dali.andypj.xyz/Article/details/gtpnvinpah.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gotoacloud.top/Article/details/gtukverujd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yanxiufei.cn/Article/details/gtvqctriwb.html

C#:   s.Substring(1, 3)
来源：http://dali.smart0.xyz/Article/details/gtctumenbi.html

[E04] 查找子串位置
来源：http://dali.cucudq.cn/Article/details/gtrsjtvgok.html

Py:   s.find("x");  s.index("x")
来源：http://dali.birdmap.top/Article/details/gtrwnuuftp.html

PHP:  strpos($s, "x");
来源：http://dali.fengsongda.top/Article/details/gttunoummk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtybyhhitu.html

TS:   s.indexOf("x")
来源：http://dali.smart0.xyz/Article/details/gtmgzjjxrh.html

Java: s.indexOf("x")
来源：http://dali.jianghu66.top/Article/details/gtqwxwnrob.html

Go:   strings.Index(s, "x")
来源：http://dali.ydzc1.top/Article/details/gtmspzcqct.html

Ruby: s.index("x")
来源：http://dali.ydzc1.top/Article/details/gtpndpceof.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gtijbmeumk.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.316326.xyz/Article/details/gtcdzlzmag.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhongyouzk.top/Article/details/gtkktzbken.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shzxlz.cn/Article/details/gtfaynyrau.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.aizwys.cn/Article/details/gtdanifrrt.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sxryk.cn/Article/details/gtkwudggls.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.haohaochexian.top/Article/details/gtjotlmqrv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jinghuilouyu.cn/Article/details/gtswbferiv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.andypj.xyz/Article/details/gtscgaedzv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xylfe.cn/Article/details/gtugqyaxfx.html

[E06] 替换子串
来源：http://dali.fzhhl.top/Article/details/gthlwqsmuf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtabxgilrb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jlsjyb.cn/Article/details/gtrbpnkbqu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtychwfeiq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gthgvcffft.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gtryqzzjom.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yangfankeji.com/Article/details/gtvshrgwcb.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtzajakdrw.html

C#:   s.Replace("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gthxaasnhv.html

[E07] 按分隔符拆分
来源：http://dali.hysaishi.cn/Article/details/gtngzrtaqy.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.daxiang520.top/Article/details/gtikhxlfaz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtqdpxiths.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.tianlin.xyz/Article/details/gtldogyoak.html

TS:   s.split(",")
来源：http://dali.xylfe.cn/Article/details/gthwvepzcx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.pycfn.com/Article/details/gtyririqfe.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.kuanghao11.cn/Article/details/gtiktdmifj.html

Ruby: s.split(",");  s.split
来源：http://dali.sweek.top/Article/details/gtfezxmodv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yonumen.top/Article/details/gtkolhhger.html

[E08] 数组按分隔符合并
来源：http://dali.yj202588.top/Article/details/gtwgomqytp.html

Py:   ",".join(items)
来源：http://dali.cheryme.top/Article/details/gtzwwjctpj.html

PHP:  implode(",", $items);
来源：http://dali.zdqjudy.top/Article/details/gtnjgotkal.html

JS:   items.join(",")
来源：http://dali.hnxiangtu.top/Article/details/gtdmabidzm.html

TS:   items.join(",")
来源：http://dali.hfpthk.cn/Article/details/gtksixctvu.html

Java: String.join(",", items)
来源：http://dali.jinqigufen.top/Article/details/gtfnmdzuqs.html

Go:   strings.Join(items, ",")
来源：http://dali.shangyingyoupin.top/Article/details/gtnajewamp.html

Ruby: items.join(",")
来源：http://dali.zhoulong.xyz/Article/details/gtfldmlqxx.html

C#:   string.Join(",", items)
来源：http://dali.daxiang520.top/Article/details/gtkkgybpwl.html

[E09] 去除所有空白字符
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgensxeaf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkgsaqxpo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.andypj.xyz/Article/details/gtrbxrobmb.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xylfe.cn/Article/details/gtutrggawd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yj20258888.top/Article/details/gtxgwyxgdp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.bjfxy.top/Article/details/gtxfpsrhvo.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenlongwang.top/Article/details/gtjrzicmrq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.daxiang520.top/Article/details/gtvbrbrokl.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqhpjcebq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.feifeiyinyue.top/Article/details/gtqjjmxwrf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jianghu66.top/Article/details/gtdfwpbqdx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yj20258888.top/Article/details/gtslyqwrgh.html

JS:   "7".padStart(3, "0")
来源：http://dali.fzhhl.top/Article/details/gtdsxaqblp.html

TS:   "7".padStart(3, "0")
来源：http://dali.shangyingyoupin.top/Article/details/gtypilniyz.html

Java: String.format("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gtcabdonbq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.pycfn.com/Article/details/gtwcaqygeq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gtflgezdwd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cqqwz.cn/Article/details/gtmslbmzjp.html

[E11] 反转字符串
来源：http://dali.cucudq.cn/Article/details/gtkzbphjlv.html

Py:   s[::-1]
来源：http://dali.shuidangran.top/Article/details/gtkibopvfc.html

PHP:  strrev($s);
来源：http://dali.nanxuanxn.top/Article/details/gtnjztkitd.html

JS:   [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gtbamrnadl.html

TS:   [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gtumvwcnnd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jiagoushi.top/Article/details/gtxuywdttl.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.kuanghao11.cn/Article/details/gtctvznbpp.html

Ruby: s.reverse
来源：http://dali.jinqigfzy.top/Article/details/gtwlsnpqci.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yonumen.top/Article/details/gtdlrzwtol.html

[E12] 统计某字符出现次数
来源：http://dali.0kj1m.cn/Article/details/gtqvwnmlbn.html

Py:   s.count("a")
来源：http://dali.andypj.xyz/Article/details/gtpkbelkgn.html

PHP:  substr_count($s, "a");
来源：http://dali.cashguo.top/Article/details/gtcqbledsp.html

JS:   s.split("a").length - 1
来源：http://dali.sxryk.cn/Article/details/gtnfoqvysi.html

TS:   s.split("a").length - 1
来源：http://dali.wangdashe.top/Article/details/gtwiogtwaw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.tanke756.top/Article/details/gtamxkxqzf.html

Go:   strings.Count(s, "a")
来源：http://dali.havefunace.top/Article/details/gtrbutyzwo.html

Ruby: s.count("a")
来源：http://dali.nanxuanxn.top/Article/details/gteftexgec.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xuanzx.com/Article/details/gtthsmfkmq.html

[E13] 逐字符遍历
来源：http://dali.yuxming.cn/Article/details/gtgrowcqii.html

Py:   for ch in s: print(ch)
来源：http://dali.yuanzhike.top/Article/details/gtncgjidxt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.tianlin.xyz/Article/details/gtsgeawrrn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuxming.cn/Article/details/gtlbfhahdw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nwbrower.top/Article/details/gtnjqcuzbr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jqgfzy.top/Article/details/gtnsjuoolc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.meibo888.top/Article/details/gtpfxqsevt.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hnxiangtu.top/Article/details/gtawrwdzbs.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.c1oappe.top/Article/details/gtytvuscte.html

[E14] URL 编码与 Base64
来源：http://dali.gzhubu.top/Article/details/gtcklonyot.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cheryme.top/Article/details/gteptreuoe.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenzaomai.com/Article/details/gtcrxwesyb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jqgufenzy.top/Article/details/gtvouohkgl.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hfpthk.cn/Article/details/gtejjnvuxs.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gtfwcibygr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.tianlin.xyz/Article/details/gtzdhrhjoj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cashguo.top/Article/details/gtmzoryrot.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yueranfly.top/Article/details/gtboxkzths.html

[E15] HTML 转义 / 反转义
来源：http://dali.cashguo.top/Article/details/gtfxkhsrqc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.meibo888.top/Article/details/gtpbwlcwzo.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jyoumei.cn/Article/details/gtsxfgnqhu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ydzc1.top/Article/details/gttwprgpyn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.9152youxi.cn/Article/details/gtcchwipfy.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xinyue.icu/Article/details/gtdwquxsrs.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinqigfzy.top/Article/details/gtpqwprvsi.html


<!-- 参考信息 -->