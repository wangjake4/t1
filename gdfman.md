代发 wailian999

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xuetiantiany.cn/Article/details/gthlruvbtp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinqigfzy.top/Article/details/gtoyzxhyra.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhiwuduotai.top/Article/details/gtbvxhkqwa.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.9152youxi.cn/Article/details/gtyipdaimq.html

[D11] 反转数组
来源：http://dali.redwolf501.top/Article/details/gtnmxmcnme.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.tianlin.xyz/Article/details/gtvwfndbdz.html

PHP:  array_reverse($arr);
来源：http://dali.snrcjt.cn/Article/details/gtbykhozdk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtabjrnxld.html

TS:   [...arr].reverse();
来源：http://dali.jqgufenzy.top/Article/details/gtzfdhryks.html

Java: Collections.reverse(list);
来源：http://dali.hnxiangtu.top/Article/details/gtukmfqthn.html

Go:   slices.Reverse(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcixxmqkh.html

Ruby: arr.reverse
来源：http://dali.xziqi.cn/Article/details/gtiukghnaz.html

C#:   list.Reverse();
来源：http://dali.redwolf501.top/Article/details/gtiwrjxacp.html

[D12] 查找元素下标
来源：http://dali.gaohongyu789.top/Article/details/gtdwhcbiag.html

Py:   arr.index(x);  x in arr
来源：http://dali.yuanzhike.top/Article/details/gtmszislxf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhengqikj.top/Article/details/gtfroklmiu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yonumen.top/Article/details/gtdbnhiyfw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xinyue.icu/Article/details/gtrjleaffi.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhixingplan.top/Article/details/gtvvdasxuh.html

Go:   slices.Index(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtsvwtkrem.html

Ruby: arr.index(x)
来源：http://dali.hysaishi.cn/Article/details/gtetvsgkuu.html

C#:   list.IndexOf(x);
来源：http://dali.dashuyun.cn/Article/details/gtxbzqzuxr.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jqgufenzy.top/Article/details/gtvmnyefvh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtedvfhszu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.dianchejie.cn/Article/details/gtsvosyiap.html

JS:   arr.filter(x => x > 3)
来源：http://dali.nanxuanxn.top/Article/details/gtzgmtryze.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yuxming.cn/Article/details/gtjntlqmsr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nanxinkj.top/Article/details/gtjezzcmti.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.wangdashe.top/Article/details/gtpimkzzfv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yangfankeji.com/Article/details/gtsqwyxucw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtuzgjabsr.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hnxiangtu.top/Article/details/gtkctifimw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.chenlongwang.top/Article/details/gtrqprpxwz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cucudq.cn/Article/details/gtaqzubadw.html

JS:   arr.map(x => x * 2)
来源：http://dali.cucudq.cn/Article/details/gtaziecpuv.html

TS:   arr.map(x => x * 2)
来源：http://dali.0kj1m.cn/Article/details/gttnrlskmq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.guowangkeji.top/Article/details/gtppppezxz.html

Go:   // 手写循环
来源：http://dali.fengsongda.top/Article/details/gtzdhtbnzl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yvedp.cn/Article/details/gtrtbfbbpq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.meibo888.top/Article/details/gtabktrkcr.html

[D15] 去重
来源：http://dali.kuanghao11.cn/Article/details/gtdcnkksig.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cucudq.cn/Article/details/gtxzgyhhqw.html

PHP:  array_unique($arr);
来源：http://dali.hfpthk.cn/Article/details/gtjmdcesdm.html

JS:   [...new Set(arr)]
来源：http://dali.yj20258.top/Article/details/gtesbszdms.html

TS:   [...new Set(arr)]
来源：http://dali.chenjidiqi.icu/Article/details/gtiubmober.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.dianchejie.cn/Article/details/gtcwbtlcyj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhengqikj.top/Article/details/gtrlcamlsc.html

Ruby: arr.uniq
来源：http://dali.daria6918.cn/Article/details/gtanaqjiil.html

C#:   list.Distinct().ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtyagtdbkb.html

[D16] 求和与平均值
来源：http://dali.havefunace.top/Article/details/gtaqvvbwxz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenlongwang.top/Article/details/gttsrgagil.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.mhx1999.top/Article/details/gtzpdstsaa.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ydzc1.top/Article/details/gtsjmoiblz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.0kj1m.cn/Article/details/gtdyloximm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj20258.top/Article/details/gtjywgowjl.html

Go:   // 手写循环累加
来源：http://dali.jinqigfzy.top/Article/details/gtscyhvtyh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zycfv.cn/Article/details/gtpuchncak.html

C#:   list.Sum();  list.Average()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfwtxeidu.html

[D17] 最大值与最小值
来源：http://dali.yongpay.top/Article/details/gtikzsklov.html

Py:   max(arr);  min(arr)
来源：http://dali.shuidangran.top/Article/details/gtpgioxhfb.html

PHP:  max($arr);  min($arr);
来源：http://dali.sufxvd.cn/Article/details/gtdnfxahxx.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hammf.cn/Article/details/gtnvvuzwdy.html

TS:   Math.max(...arr);
来源：http://dali.redwolf501.top/Article/details/gtdgcjxcfy.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhixingplan.top/Article/details/gthmrmmiop.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yueranfly.top/Article/details/gtkatmyzra.html

Ruby: arr.max;  arr.min
来源：http://dali.0kj1m.cn/Article/details/gtagextqot.html

C#:   list.Max();  list.Min()
来源：http://dali.fengsongda.top/Article/details/gtmjzbezbm.html

[D18] 扁平化嵌套数组
来源：http://dali.cqqwz.cn/Article/details/gtzgzwrwxl.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.haohaochexian.top/Article/details/gtfvhuleqc.html

PHP:  array_merge(...$nested);
来源：http://dali.wangdashe.top/Article/details/gtdzkrexnh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hnqzz.top/Article/details/gtybqpjmla.html

TS:   nested.flat();
来源：http://dali.hysaishi.cn/Article/details/gtebhhapcr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.316326.xyz/Article/details/gtcyeqzgrt.html

Go:   // 手写双层循环
来源：http://dali.birdmap.top/Article/details/gtossyvywr.html

Ruby: nested.flatten
来源：http://dali.c1oappe.top/Article/details/gtkmgauhxq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yj20258888.top/Article/details/gtaohxclmf.html

[D19] 按字段分组
来源：http://dali.dashuyun.cn/Article/details/gtubtdycfa.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sweek.top/Article/details/gtytgopxso.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.daxiang520.top/Article/details/gtnffwgzip.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.quarkkingdee.top/Article/details/gtbhvkahtg.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmjgqvigr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.mhx1999.top/Article/details/gtwsedixvm.html

Go:   // 手写 map[string][]T
来源：http://dali.hongshengwenyu.top/Article/details/gtatimprfx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cdnleiting.top/Article/details/gtekabowmh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shanyushiyangtech.top/Article/details/gtmngyyyyn.html

[D20] 统计每个元素出现次数
来源：http://dali.nwbrower.top/Article/details/gtgjnerlic.html

Py:   Counter(arr)
来源：http://dali.snrcjt.cn/Article/details/gtdutbzczn.html

PHP:  array_count_values($arr);
来源：http://dali.fengsongda.top/Article/details/gtwbuxezee.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sufxvd.cn/Article/details/gtqbvpgjem.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.vqdsnc.cn/Article/details/gtnfpqqbxs.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtebpcvisk.html

Go:   // 手写 map[T]int
来源：http://dali.jqgufenzy.top/Article/details/gtfmrofhzu.html

Ruby: arr.tally
来源：http://dali.chenjidiqi.icu/Article/details/gtuqdnncob.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.tanke756.top/Article/details/gtvtfypsxc.html

[D21] 判断是否包含某元素
来源：http://dali.sysykeji.top/Article/details/gtgpydqssn.html

Py:   x in arr
来源：http://dali.jinqigfzy.top/Article/details/gtfjcmpxwk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.tian-w.cn/Article/details/gtcbygtfog.html

JS:   arr.includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtgjavelxy.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gtwlwxuzxw.html

Java: list.contains(x)
来源：http://dali.shangyingyoupin.top/Article/details/gthayldfsl.html

Go:   slices.Contains(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtzbcgvdry.html

Ruby: arr.include?(x)
来源：http://dali.yj202588.top/Article/details/gttxiycgmi.html

C#:   list.Contains(x)
来源：http://dali.ehwqpu.com/Article/details/gtzssnfgjd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.iojbl.cn/Article/details/gtwmnvojkp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhengqikj.top/Article/details/gtmvhlkzqt.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xylfe.cn/Article/details/gtfjoeyktf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtbmtdyujo.html

TS:   [...arr];
来源：http://dali.hammf.cn/Article/details/gtomcedogg.html

Java: new ArrayList<>(list);
来源：http://dali.yuanzhike.top/Article/details/gtqarkdeif.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.wangdashe.top/Article/details/gtshgfamax.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yueranfly.top/Article/details/gtapjdmbtd.html

C#:   new List<int>(list);
来源：http://dali.daxiang520.top/Article/details/gttmcenend.html

[D23] reduce 累积计算
来源：http://dali.xinyue.icu/Article/details/gtqbttqaut.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ivvv.top/Article/details/gteozhyxjk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.haohaochexian.top/Article/details/gtnvpgmfmc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gotoacloud.top/Article/details/gtkaxgmjmc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.havefunace.top/Article/details/gtqwiaezwt.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthffrngue.html

Go:   // 手写循环
来源：http://dali.guowangkeji.top/Article/details/gtzhoulzgx.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gotoacloud.top/Article/details/gtoynioflu.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shzxlz.cn/Article/details/gtcejwbajb.html

[D24] 字典 / Map 基本操作
来源：http://dali.316326.xyz/Article/details/gtytokdaxj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hnxiangtu.top/Article/details/gtrpehbloo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.fengsongda.top/Article/details/gtninwxttu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.dianchejie.cn/Article/details/gttokxldyw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtmdzvclxn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hfpthk.cn/Article/details/gtbtwtjqev.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.redwolf501.top/Article/details/gthfnbkqjz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hongshengwenyu.top/Article/details/gtbcmmfyni.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.svipenyu.cn/Article/details/gtdivrilim.html

[D25] Set 集合去重与交并差
来源：http://dali.mhx1999.top/Article/details/gthqiuutbv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinqigfzy.top/Article/details/gtovczlijy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ivvv.top/Article/details/gtebpcxchw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.wangdashe.top/Article/details/gttywurktl.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.chenzaomai.com/Article/details/gtqgwypavg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhixingplan.top/Article/details/gtfsxfcegg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jlsjyb.cn/Article/details/gtrddohwke.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhoulong.xyz/Article/details/gtukmadegl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsfmliffj.html

[D26] 数组转字符串
来源：http://dali.cashguo.top/Article/details/gtqsinrtlv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yonumen.top/Article/details/gtewhjnafb.html

PHP:  implode(", ", $arr);
来源：http://dali.gaohongyu789.top/Article/details/gtvxqmyyut.html

JS:   arr.join(", ")
来源：http://dali.chenlongwang.top/Article/details/gtvrwnwgjn.html

TS:   arr.join(", ")
来源：http://dali.daria6918.cn/Article/details/gtqsrwtjbd.html

Java: String.join(", ", list)
来源：http://dali.yj202588.top/Article/details/gteyoydmuq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.birdmap.top/Article/details/gtfgpdzdim.html

Ruby: arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gtfirxcxgx.html

C#:   string.Join(", ", list)
来源：http://dali.cucudq.cn/Article/details/gthxebeeib.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtuxxftqri.html

E. 字符串处理
来源：http://dali.pycfn.com/Article/details/gtswnmfvxf.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtaiugnldu.html

[E01] 拼接字符串
来源：http://dali.c1oappe.top/Article/details/gtudzyueez.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.nanxuanxn.top/Article/details/gtrppsnrzi.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.gogol.net.cn/Article/details/gtltbdsmwp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuanzhike.top/Article/details/gtayymdmje.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zdqjudy.top/Article/details/gtmltogdpt.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ppjwa.cn/Article/details/gtjxjnetge.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.dianchejie.cn/Article/details/gtmwgpxjfa.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhongyouzk.top/Article/details/gtkkqiycow.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gtuczyewkg.html

[E02] 重复字符串
来源：http://dali.hysaishi.cn/Article/details/gtrqzngpkn.html

Py:   "ab" * 3
来源：http://dali.yangfankeji.com/Article/details/gtcsfwanyf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthnoalszf.html

JS:   "ab".repeat(3)
来源：http://dali.cdnleiting.top/Article/details/gtqjszxczb.html

TS:   "ab".repeat(3)
来源：http://dali.kuanghao11.cn/Article/details/gtgykhrvts.html

Java: "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gtzfjeenzz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.redwolf501.top/Article/details/gtjezsjeou.html

Ruby: "ab" * 3
来源：http://dali.yj20258.top/Article/details/gthhfwhahe.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jqgufenzy.top/Article/details/gtrovqvpun.html

[E03] 截取子串
来源：http://dali.sysykeji.top/Article/details/gtxqdntbzn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ppjwa.cn/Article/details/gtztbepixq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gtfdjeqsdc.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.nanxinkj.top/Article/details/gtisopaiub.html

TS:   s.slice(1, 4)
来源：http://dali.sufxvd.cn/Article/details/gtzpujzotp.html

Java: s.substring(1, 4)
来源：http://dali.kuanghao11.cn/Article/details/gtwmetluuc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jqgufenzy.top/Article/details/gtioprlmjc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jqgufenzy.top/Article/details/gthcjyrwkc.html

C#:   s.Substring(1, 3)
来源：http://dali.jianghu66.top/Article/details/gtcfqcqxwu.html

[E04] 查找子串位置
来源：http://dali.andypj.xyz/Article/details/gtyvgtwyog.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sxryk.cn/Article/details/gtmqqxrtld.html

PHP:  strpos($s, "x");
来源：http://dali.quarkkingdee.top/Article/details/gtmafxvyyr.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ppjwa.cn/Article/details/gtacxlaaqh.html

TS:   s.indexOf("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcwkcumkh.html

Java: s.indexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gttocwbvio.html

Go:   strings.Index(s, "x")
来源：http://dali.nwbrower.top/Article/details/gtapcyfwet.html

Ruby: s.index("x")
来源：http://dali.chenjidiqi.icu/Article/details/gtvfkwmyno.html

C#:   s.IndexOf("x")
来源：http://dali.mhx1999.top/Article/details/gticysenme.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shuidangran.top/Article/details/gtstruksdu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.daxiang520.top/Article/details/gtbklwocwi.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxqjaaphw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.aizwys.cn/Article/details/gtzolxqtff.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.chenlongwang.top/Article/details/gtsxfeehio.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gotoacloud.top/Article/details/gtcfcoruwp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.aibaodan.cn/Article/details/gtrilhjazk.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ydzc1.top/Article/details/gtskrgwmlv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hnqzz.top/Article/details/gtusdyqinr.html

[E06] 替换子串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtixftldor.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtlguoewcy.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqiyfzzq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtbashlugz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtioydqywy.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtrzcvqlfq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.svipenyu.cn/Article/details/gtnezvygqx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtlqikheka.html

C#:   s.Replace("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtapmbifmp.html

[E07] 按分隔符拆分
来源：http://dali.svipenyu.cn/Article/details/gtimpecsha.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.smart0.xyz/Article/details/gtfjupdeyf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinqigufen.top/Article/details/gtywxugqsx.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.nanxinkj.top/Article/details/gtgiwqgnyp.html

TS:   s.split(",")
来源：http://dali.nanxuanxn.top/Article/details/gttkzdzter.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.birdmap.top/Article/details/gtdsoztvfx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gotoacloud.top/Article/details/gtpuolwnoo.html

Ruby: s.split(",");  s.split
来源：http://dali.hysaishi.cn/Article/details/gtbawigwpx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ybcxt.top/Article/details/gtiryvwcqj.html

[E08] 数组按分隔符合并
来源：http://dali.bjfxy.top/Article/details/gtwnpfowcw.html

Py:   ",".join(items)
来源：http://dali.sweek.top/Article/details/gtokupigqc.html

PHP:  implode(",", $items);
来源：http://dali.zhixingplan.top/Article/details/gtswiouopd.html

JS:   items.join(",")
来源：http://dali.yonumen.top/Article/details/gtcrpshfbn.html

TS:   items.join(",")
来源：http://dali.gaohongyu789.top/Article/details/gtvqailjfc.html

Java: String.join(",", items)
来源：http://dali.shangyingyoupin.top/Article/details/gttickuder.html

Go:   strings.Join(items, ",")
来源：http://dali.jianghu66.top/Article/details/gtgrrgohyw.html

Ruby: items.join(",")
来源：http://dali.nanxinkj.top/Article/details/gtoswmgozj.html

C#:   string.Join(",", items)
来源：http://dali.bjfxy.top/Article/details/gtjtdmzugi.html

[E09] 去除所有空白字符
来源：http://dali.yuanzhike.top/Article/details/gtlhygrbmb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gotoacloud.top/Article/details/gtlbrbqdjq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtpbqlcvsn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xylfe.cn/Article/details/gtutyjdzlg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yj20258.top/Article/details/gtbqyfskcw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.chenlongwang.top/Article/details/gtgqexoitj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenjidiqi.icu/Article/details/gtntdkjqds.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.redwolf501.top/Article/details/gtipdognhb.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.guannengcc.top/Article/details/gtoyfuozhz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.0kj1m.cn/Article/details/gtibhrlurb.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gtzfyylyfw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yongpay.top/Article/details/gtjudobqzi.html

JS:   "7".padStart(3, "0")
来源：http://dali.yvedp.cn/Article/details/gttatulexe.html

TS:   "7".padStart(3, "0")
来源：http://dali.yj20258888.top/Article/details/gtmgffvsvu.html

Java: String.format("%03d", 7)
来源：http://dali.jiagoushi.top/Article/details/gtwmmttevc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gtepdxgwry.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gtzprphkas.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jlsjyb.cn/Article/details/gtbrliikjv.html

[E11] 反转字符串
来源：http://dali.guowangkeji.top/Article/details/gttpefagjf.html

Py:   s[::-1]
来源：http://dali.jianghu66.top/Article/details/gthtikpxiq.html

PHP:  strrev($s);
来源：http://dali.zycfv.cn/Article/details/gtfpxyhgiq.html

JS:   [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gtcpdgqzjq.html

TS:   [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gtdmvvwvgv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shuidangran.top/Article/details/gtpmossgeo.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hnxiangtu.top/Article/details/gtmrnbaolc.html

Ruby: s.reverse
来源：http://dali.ehwqpu.com/Article/details/gtzziepqye.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrpyqnkxj.html

[E12] 统计某字符出现次数
来源：http://dali.feifeiyinyue.top/Article/details/gtnyjwhkdh.html

Py:   s.count("a")
来源：http://dali.jiagoushi.top/Article/details/gtdhxgyfip.html

PHP:  substr_count($s, "a");
来源：http://dali.chenzaomai.com/Article/details/gtkejxszie.html

JS:   s.split("a").length - 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gttxtptudu.html

TS:   s.split("a").length - 1
来源：http://dali.aizwys.cn/Article/details/gtedgmfdmr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ehwqpu.com/Article/details/gtpjozmpzz.html

Go:   strings.Count(s, "a")
来源：http://dali.ehwqpu.com/Article/details/gtrtbtillv.html

Ruby: s.count("a")
来源：http://dali.yangfankeji.com/Article/details/gtiwdgtvks.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhengqikj.top/Article/details/gtnmswqyyi.html

[E13] 逐字符遍历
来源：http://dali.tian-w.cn/Article/details/gtyekurfue.html

Py:   for ch in s: print(ch)
来源：http://dali.andypj.xyz/Article/details/gtcydatzoq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yanxiufei.cn/Article/details/gtbkwqwslf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.meibo888.top/Article/details/gtkzavaadl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gttoervrjw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sysykeji.top/Article/details/gtyxjoitnn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yvedp.cn/Article/details/gthhbltbby.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.mhx1999.top/Article/details/gtcczcujea.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gtbacmttnp.html

[E14] URL 编码与 Base64
来源：http://dali.fengsongda.top/Article/details/gtoobgkann.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhengqikj.top/Article/details/gtzgxdjjyl.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.guowangkeji.top/Article/details/gtirabyrge.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.9152youxi.cn/Article/details/gtxcmembjb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.iojbl.cn/Article/details/gtnbffjnwp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjwsqioze.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yj20258.top/Article/details/gtwevcvjeq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hysaishi.cn/Article/details/gtanwtbltd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.chenzaomai.com/Article/details/gtyvomwcai.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenjidiqi.icu/Article/details/gtflwzfiul.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jqgufenzy.top/Article/details/gtttyxcvej.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hnxiangtu.top/Article/details/gtiortcopg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yanxiufei.cn/Article/details/gtpaowethu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.havefunace.top/Article/details/gtdaujsdqx.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.birdmap.top/Article/details/gtuprhmznn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtrsiheksn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.guannengcc.top/Article/details/gtbppgbblh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhoulong.xyz/Article/details/gtqpjuxavj.html

[E16] 数字千分位
来源：http://dali.birdmap.top/Article/details/gtchnemzfn.html

Py:   f"{1234567:,}"
来源：http://dali.xylfe.cn/Article/details/gtfoqczpyh.html

PHP:  number_format(1234567);
来源：http://dali.yanxiufei.cn/Article/details/gtotwwwptx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yanxiufei.cn/Article/details/gtndcaphpe.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.guannengcc.top/Article/details/gtqbfqkjkb.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttqmlzluy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.snrcjt.cn/Article/details/gtvhbgahww.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenjidiqi.icu/Article/details/gtkjiwtnzd.html

C#:   1234567.ToString("N0")
来源：http://dali.ydzc1.top/Article/details/gtftpcolsc.html

[E17] 首字母大写
来源：http://dali.cqqwz.cn/Article/details/gtcguhmsgj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdepwzcnx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.guowangkeji.top/Article/details/gtimbtmobw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.vqdsnc.cn/Article/details/gtsycxnjdn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jlsjyb.cn/Article/details/gtugacswws.html


<!-- 参考信息 -->