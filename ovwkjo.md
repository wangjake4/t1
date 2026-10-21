代发 wailian999

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.smart0.xyz/Article/details/gtpxglypal.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ivvv.top/Article/details/gtqehmbeie.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hfpthk.cn/Article/details/gtntivkhki.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shzxlz.cn/Article/details/gtddnsonva.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yonumen.top/Article/details/gtfbyzevxi.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hysaishi.cn/Article/details/gtbigcdsbp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xziqi.cn/Article/details/gtnzeoqfuv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gotoacloud.top/Article/details/gtitohchxg.html

[D11] 反转数组
来源：http://dali.jlsjyb.cn/Article/details/gtmfnkdxwx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.wangshuangyany.cn/Article/details/gtoedsnati.html

PHP:  array_reverse($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtarbkavvw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.kuanghao11.cn/Article/details/gtmqnrkrpy.html

TS:   [...arr].reverse();
来源：http://dali.snrcjt.cn/Article/details/gtxkqwyecz.html

Java: Collections.reverse(list);
来源：http://dali.meibo888.top/Article/details/gtmvafkhel.html

Go:   slices.Reverse(arr)
来源：http://dali.yonumen.top/Article/details/gtbxkppgdg.html

Ruby: arr.reverse
来源：http://dali.zhiwuduotai.top/Article/details/gtgmuufzac.html

C#:   list.Reverse();
来源：http://dali.tanke756.top/Article/details/gtzecqmiiq.html

[D12] 查找元素下标
来源：http://dali.fzhhl.top/Article/details/gtcddypjzh.html

Py:   arr.index(x);  x in arr
来源：http://dali.xuanzx.com/Article/details/gtvzfadrua.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jiagoushi.top/Article/details/gtrdacumnn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gogol.net.cn/Article/details/gtlrxlzbxt.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gogol.net.cn/Article/details/gtiuyxgxau.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xuetiantiany.cn/Article/details/gtmejenmcw.html

Go:   slices.Index(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtnjelwnrc.html

Ruby: arr.index(x)
来源：http://dali.jlsjyb.cn/Article/details/gtjabprjtf.html

C#:   list.IndexOf(x);
来源：http://dali.redwolf501.top/Article/details/gtoevucekz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gzhubu.top/Article/details/gthssabvdv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.dashuyun.cn/Article/details/gtlsssjots.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yangfankeji.com/Article/details/gthdwrlxyn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.vqdsnc.cn/Article/details/gtqrujjvub.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xinyue.icu/Article/details/gtyzqchutp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtnexzrxas.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hfpthk.cn/Article/details/gtqrqywfnn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.daxiang520.top/Article/details/gtexdlcvve.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yongpay.top/Article/details/gtiulhgnte.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shanyushiyangtech.top/Article/details/gtmokmpngn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.pycfn.com/Article/details/gtpyehmfjd.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.tanke756.top/Article/details/gtfpzkqkak.html

JS:   arr.map(x => x * 2)
来源：http://dali.jqgfzy.top/Article/details/gtpjdifpwi.html

TS:   arr.map(x => x * 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtkqghjbio.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhixingplan.top/Article/details/gtmzdjinxo.html

Go:   // 手写循环
来源：http://dali.daxiang520.top/Article/details/gtnltmbaff.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtxbbzqkop.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtvksqtyxn.html

[D15] 去重
来源：http://dali.pengpengdd.cyou/Article/details/gtwvdknwlg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yj20258888.top/Article/details/gtftxeaamn.html

PHP:  array_unique($arr);
来源：http://dali.aizwys.cn/Article/details/gtwqdsayqe.html

JS:   [...new Set(arr)]
来源：http://dali.andypj.xyz/Article/details/gthgioossk.html

TS:   [...new Set(arr)]
来源：http://dali.dianchejie.cn/Article/details/gtxlmzonup.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.pycfn.com/Article/details/gthjoorpjh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.dashuyun.cn/Article/details/gtmbtsupib.html

Ruby: arr.uniq
来源：http://dali.birdmap.top/Article/details/gtewenjtwg.html

C#:   list.Distinct().ToList()
来源：http://dali.zhengqikj.top/Article/details/gtmpgkxnix.html

[D16] 求和与平均值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuefcrrcx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.iojbl.cn/Article/details/gtqeqbrjwx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtkqtekpip.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtskehlxba.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.0kj1m.cn/Article/details/gtmaxluoim.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.tian-w.cn/Article/details/gtosckrmci.html

Go:   // 手写循环累加
来源：http://dali.yvedp.cn/Article/details/gtlvgozzgs.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yangfankeji.com/Article/details/gtjhlhziva.html

C#:   list.Sum();  list.Average()
来源：http://dali.shangyingyoupin.top/Article/details/gtnuufpxef.html

[D17] 最大值与最小值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmzrcchnm.html

Py:   max(arr);  min(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtbeiyoilb.html

PHP:  max($arr);  min($arr);
来源：http://dali.nwbrower.top/Article/details/gtdpccrhde.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.guannengcc.top/Article/details/gtzqgcsdpf.html

TS:   Math.max(...arr);
来源：http://dali.chenlongwang.top/Article/details/gtasnipkuz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmzwpagvm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xinyue.icu/Article/details/gtakjibzsf.html

Ruby: arr.max;  arr.min
来源：http://dali.daria6918.cn/Article/details/gtnfypsftv.html

C#:   list.Max();  list.Min()
来源：http://dali.snrcjt.cn/Article/details/gtttnxotfg.html

[D18] 扁平化嵌套数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqehevymu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yonumen.top/Article/details/gtqzkpvjmq.html

PHP:  array_merge(...$nested);
来源：http://dali.sysykeji.top/Article/details/gttjdqsjuk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tian-w.cn/Article/details/gtyefcozjg.html

TS:   nested.flat();
来源：http://dali.gaohongyu789.top/Article/details/gtuixawong.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xziqi.cn/Article/details/gtofmskmbq.html

Go:   // 手写双层循环
来源：http://dali.wangdashe.top/Article/details/gtopeuaqjs.html

Ruby: nested.flatten
来源：http://dali.0kj1m.cn/Article/details/gtvkmiqqwz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.iojbl.cn/Article/details/gtvvrqkqjc.html

[D19] 按字段分组
来源：http://dali.yj20258.top/Article/details/gtxftmcuhm.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gotoacloud.top/Article/details/gtoggjfdew.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.wangshuangyany.cn/Article/details/gtmifnjhye.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqqjrhezx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xuanzx.com/Article/details/gtikiifzcn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xziqi.cn/Article/details/gtqxvbbjfd.html

Go:   // 手写 map[string][]T
来源：http://dali.aizwys.cn/Article/details/gtlhlzkfml.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gotoacloud.top/Article/details/gtivoosepa.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cdnleiting.top/Article/details/gtbamjjglp.html

[D20] 统计每个元素出现次数
来源：http://dali.yuxming.cn/Article/details/gtsawmwtfw.html

Py:   Counter(arr)
来源：http://dali.aibaodan.cn/Article/details/gtaakynbkb.html

PHP:  array_count_values($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtplnatlue.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cashguo.top/Article/details/gtrpgxgfoa.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgfzy.top/Article/details/gttjtckzek.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yuxming.cn/Article/details/gtrlhqsubp.html

Go:   // 手写 map[T]int
来源：http://dali.gogol.net.cn/Article/details/gtemfekgpb.html

Ruby: arr.tally
来源：http://dali.ybcxt.top/Article/details/gtdizuewvg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hysaishi.cn/Article/details/gtzgsllrqw.html

[D21] 判断是否包含某元素
来源：http://dali.bjfxy.top/Article/details/gtgqrxqgbl.html

Py:   x in arr
来源：http://dali.daxiang520.top/Article/details/gtuafxujbm.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yvedp.cn/Article/details/gtgqcuwwsd.html

JS:   arr.includes(x)
来源：http://dali.cucudq.cn/Article/details/gtymffpdmz.html

TS:   arr.includes(x)
来源：http://dali.xylfe.cn/Article/details/gthylhykrk.html

Java: list.contains(x)
来源：http://dali.tanke756.top/Article/details/gtxkxrvlqa.html

Go:   slices.Contains(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtwqrokaah.html

Ruby: arr.include?(x)
来源：http://dali.fzhhl.top/Article/details/gtkhqdryah.html

C#:   list.Contains(x)
来源：http://dali.fengsongda.top/Article/details/gtlszinfwu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xuetiantiany.cn/Article/details/gtgeixdztd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.chenlongwang.top/Article/details/gtdczepbpu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenzaomai.com/Article/details/gtxhjvnjth.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmhabcmvy.html

TS:   [...arr];
来源：http://dali.bjfxy.top/Article/details/gtgslswpsk.html

Java: new ArrayList<>(list);
来源：http://dali.tanke756.top/Article/details/gtwvnuitzp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenzaomai.com/Article/details/gtfcjbabbf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jyoumei.cn/Article/details/gtgrwhqxxu.html

C#:   new List<int>(list);
来源：http://dali.pycfn.com/Article/details/gtesyrhxbq.html

[D23] reduce 累积计算
来源：http://dali.yuanzhike.top/Article/details/gthqwmlter.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hfpthk.cn/Article/details/gtniyunirw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.guannengcc.top/Article/details/gtdnwntvol.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtmvgjyeev.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yongpay.top/Article/details/gtnpzqtiaf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.havefunace.top/Article/details/gtlmmhkivq.html

Go:   // 手写循环
来源：http://dali.fengsongda.top/Article/details/gtrmtedayi.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shzxlz.cn/Article/details/gtfnmexrsl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.kuanghao11.cn/Article/details/gtunrseosr.html

[D24] 字典 / Map 基本操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvfderlbi.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrzawbrwg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.snrcjt.cn/Article/details/gtfvjscczl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnnwtzgbi.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtveyqpysc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tianlin.xyz/Article/details/gtadhwpbfx.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yongpay.top/Article/details/gtxhouusss.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tian-w.cn/Article/details/gtfximaoeq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.tian-w.cn/Article/details/gtejjrioji.html

[D25] Set 集合去重与交并差
来源：http://dali.hnxiangtu.top/Article/details/gtlqhucwan.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.c1oappe.top/Article/details/gtcbwvxhqy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yonumen.top/Article/details/gtafqjngss.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yueranfly.top/Article/details/gtwmdmxwhj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shzxlz.cn/Article/details/gtrejlcwnf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.pycfn.com/Article/details/gtcuhlnqbg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xinyue.icu/Article/details/gtbmycxttx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.tian-w.cn/Article/details/gtnxmbatnq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sufxvd.cn/Article/details/gtiilazzyb.html

[D26] 数组转字符串
来源：http://dali.fengsongda.top/Article/details/gtgrogiaem.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jqgufenzy.top/Article/details/gtmfuyxlza.html

PHP:  implode(", ", $arr);
来源：http://dali.chenlongwang.top/Article/details/gthmyjvcss.html

JS:   arr.join(", ")
来源：http://dali.yanxiufei.cn/Article/details/gtzcewrdub.html

TS:   arr.join(", ")
来源：http://dali.sufxvd.cn/Article/details/gtjonvvqqc.html

Java: String.join(", ", list)
来源：http://dali.yj20258888.top/Article/details/gtrehchmub.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sweek.top/Article/details/gtimwiktzk.html

Ruby: arr.join(", ")
来源：http://dali.shzxlz.cn/Article/details/gtposrwixh.html

C#:   string.Join(", ", list)
来源：http://dali.nanxinkj.top/Article/details/gthfcbarof.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gthorrprsl.html

E. 字符串处理
来源：http://dali.chenzaomai.com/Article/details/gtywaxoivj.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtsuakseab.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gtqiofpkcd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yvedp.cn/Article/details/gtzepbgxgw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinqigfzy.top/Article/details/gtspbhvkkc.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtzkqgohxn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.quarkkingdee.top/Article/details/gtpnyxckwe.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.daria6918.cn/Article/details/gtcdtoyaoc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yueranfly.top/Article/details/gtitpcghuj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.dashuyun.cn/Article/details/gtdozqltxf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtcehisgex.html

[E02] 重复字符串
来源：http://dali.c1oappe.top/Article/details/gtuzzdsfne.html

Py:   "ab" * 3
来源：http://dali.hysaishi.cn/Article/details/gtjcgzaxqs.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yj20258888.top/Article/details/gtcwaeobnx.html

JS:   "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gtdeufbwsh.html

TS:   "ab".repeat(3)
来源：http://dali.vqdsnc.cn/Article/details/gtnlfbqvdu.html

Java: "ab".repeat(3)
来源：http://dali.316326.xyz/Article/details/gtiivsnhqf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.daxiang520.top/Article/details/gtfbzlifmn.html

Ruby: "ab" * 3
来源：http://dali.vqdsnc.cn/Article/details/gtfvraaafy.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jqgufenzy.top/Article/details/gtrozmqkwc.html

[E03] 截取子串
来源：http://dali.mhx1999.top/Article/details/gtixferlzf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.tanke756.top/Article/details/gtrplxiojg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gtrkbehbzr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jqgufenzy.top/Article/details/gtrolwaavx.html

TS:   s.slice(1, 4)
来源：http://dali.yvedp.cn/Article/details/gtdgutcaox.html

Java: s.substring(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gtptmbcoxn.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hnqzz.top/Article/details/gtyzswxnld.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.andypj.xyz/Article/details/gtxemavcxl.html

C#:   s.Substring(1, 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrntjzccr.html

[E04] 查找子串位置
来源：http://dali.zhiwuduotai.top/Article/details/gtpnjgeuwf.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zycfv.cn/Article/details/gtabshldor.html

PHP:  strpos($s, "x");
来源：http://dali.cashguo.top/Article/details/gtbwhtbboz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zdqjudy.top/Article/details/gtvvpboaeo.html

TS:   s.indexOf("x")
来源：http://dali.chenjidiqi.icu/Article/details/gtqtgfpggw.html

Java: s.indexOf("x")
来源：http://dali.zdqjudy.top/Article/details/gtyzbtpahc.html

Go:   strings.Index(s, "x")
来源：http://dali.chenlongwang.top/Article/details/gtizhdxabh.html

Ruby: s.index("x")
来源：http://dali.yonumen.top/Article/details/gtpswiepqm.html

C#:   s.IndexOf("x")
来源：http://dali.aizwys.cn/Article/details/gttbnuiwaf.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yangfankeji.com/Article/details/gtsjvlpepc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xylfe.cn/Article/details/gtwfhdtddu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.wangdashe.top/Article/details/gtrfyfypdp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.svipenyu.cn/Article/details/gtxsapmlum.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhongyouzk.top/Article/details/gtuzfgkmqg.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigufen.top/Article/details/gtxezgbxeg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.chenjidiqi.icu/Article/details/gtengkubsv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.redwolf501.top/Article/details/gtawloceuo.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yuxming.cn/Article/details/gtmjjkvdae.html

[E06] 替换子串
来源：http://dali.jinghuilouyu.cn/Article/details/gtktmghncq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shuidangran.top/Article/details/gtnwniwxju.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtxeafdymj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtnluxejwo.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gthlzpxwej.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtpfxzvurw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.guowangkeji.top/Article/details/gtwjkxfksc.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtzenyzwhn.html

C#:   s.Replace("a", "b")
来源：http://dali.meibo888.top/Article/details/gtsofmxtum.html

[E07] 按分隔符拆分
来源：http://dali.nwbrower.top/Article/details/gtvphpbhfx.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.bjfxy.top/Article/details/gtdckagdye.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shuidangran.top/Article/details/gtydizclab.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhoulong.xyz/Article/details/gtgwqmqazz.html

TS:   s.split(",")
来源：http://dali.dashuyun.cn/Article/details/gtucpxuhyq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.nanxinkj.top/Article/details/gtzsimvylb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtyiucupcq.html

Ruby: s.split(",");  s.split
来源：http://dali.yj20258.top/Article/details/gtcozvvnje.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.wangdashe.top/Article/details/gthfqygxmr.html

[E08] 数组按分隔符合并
来源：http://dali.sufxvd.cn/Article/details/gtbgnwvnwz.html

Py:   ",".join(items)
来源：http://dali.316326.xyz/Article/details/gtlithoyuq.html

PHP:  implode(",", $items);
来源：http://dali.cucudq.cn/Article/details/gttzquzxuq.html

JS:   items.join(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsanyevfl.html

TS:   items.join(",")
来源：http://dali.jlsjyb.cn/Article/details/gtojbdtbov.html

Java: String.join(",", items)
来源：http://dali.tianlin.xyz/Article/details/gtfndhdvkk.html

Go:   strings.Join(items, ",")
来源：http://dali.yj20258.top/Article/details/gtetrushha.html

Ruby: items.join(",")
来源：http://dali.smart0.xyz/Article/details/gtzdjjpvbl.html

C#:   string.Join(",", items)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiiabviic.html

[E09] 去除所有空白字符
来源：http://dali.cucudq.cn/Article/details/gtuaotbded.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yj20258888.top/Article/details/gtzywamvae.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtrqeniunt.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yonumen.top/Article/details/gtxntsackd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhongyouzk.top/Article/details/gtspkycsmk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shangyingyoupin.top/Article/details/gtaegoahhe.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.wangshuangyany.cn/Article/details/gtbeznjcjg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmbqjlbyr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.0kj1m.cn/Article/details/gtegisnpyi.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhixingplan.top/Article/details/gttqwhnwow.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.aizwys.cn/Article/details/gtlhbnhosl.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sysykeji.top/Article/details/gtbhmwynck.html

JS:   "7".padStart(3, "0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjljhihek.html

TS:   "7".padStart(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gteiahoxhj.html

Java: String.format("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gtursuubxn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.snrcjt.cn/Article/details/gthfqdqmxb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yuanzhike.top/Article/details/gtrfyuyakm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.wangshuangyany.cn/Article/details/gtqwrwunqc.html

[E11] 反转字符串
来源：http://dali.bjfxy.top/Article/details/gtmfuxaqjk.html

Py:   s[::-1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiggimiox.html

PHP:  strrev($s);
来源：http://dali.aizwys.cn/Article/details/gtykpjrcej.html

JS:   [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gtjjgdmylt.html

TS:   [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gtumtqbdei.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.wangshuangyany.cn/Article/details/gtmksclrhl.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhongyouzk.top/Article/details/gtoobcwjce.html

Ruby: s.reverse
来源：http://dali.yj202588.top/Article/details/gtagdyjhkp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.aizwys.cn/Article/details/gtxjisprmb.html

[E12] 统计某字符出现次数
来源：http://dali.jlsjyb.cn/Article/details/gtwkcjxcmy.html

Py:   s.count("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtjvgcvuwx.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxuanxn.top/Article/details/gtfzwdsfve.html

JS:   s.split("a").length - 1
来源：http://dali.pengpengdd.cyou/Article/details/gtcxdolnej.html

TS:   s.split("a").length - 1
来源：http://dali.jyoumei.cn/Article/details/gtepvftptq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yangfankeji.com/Article/details/gtvhjmahut.html

Go:   strings.Count(s, "a")
来源：http://dali.snrcjt.cn/Article/details/gtftwoibdh.html

Ruby: s.count("a")
来源：http://dali.redwolf501.top/Article/details/gtroodfirq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.fengsongda.top/Article/details/gtdxkuglbp.html

[E13] 逐字符遍历
来源：http://dali.quarkkingdee.top/Article/details/gtdsiujwll.html

Py:   for ch in s: print(ch)
来源：http://dali.birdmap.top/Article/details/gtzarwxvmi.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.nanxuanxn.top/Article/details/gtibrzmyzz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zdqjudy.top/Article/details/gtflrjpmze.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xylfe.cn/Article/details/gtscgpzdiz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.guannengcc.top/Article/details/gtcdawqfck.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxqblqibv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gzhubu.top/Article/details/gtmbmxctcx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sweek.top/Article/details/gtpheqokof.html

[E14] URL 编码与 Base64
来源：http://dali.c1oappe.top/Article/details/gtpoksukal.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.chenlongwang.top/Article/details/gtqtawssnq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjtxuqxxn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.tanke756.top/Article/details/gtnrmfwebc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.daria6918.cn/Article/details/gtqsxvumsc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ehwqpu.com/Article/details/gtjpnqvymg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shanyushiyangtech.top/Article/details/gtboaxsmiv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinqigufen.top/Article/details/gtnafmpsso.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinqigufen.top/Article/details/gtsrmxefic.html

[E15] HTML 转义 / 反转义
来源：http://dali.redwolf501.top/Article/details/gtpofjfycx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.bjfxy.top/Article/details/gtofvginvm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hnxiangtu.top/Article/details/gtpvrzascw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenzaomai.com/Article/details/gtbwrmtkmu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gtxbojtoyn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.nanxuanxn.top/Article/details/gtvrbjnszl.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hfpthk.cn/Article/details/gtfjgpfifu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cdnleiting.top/Article/details/gttputawcg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtmzfjmnof.html

[E16] 数字千分位
来源：http://dali.meibo888.top/Article/details/gtmyrsdwrg.html

Py:   f"{1234567:,}"
来源：http://dali.nanxinkj.top/Article/details/gtpsybiktb.html

PHP:  number_format(1234567);
来源：http://dali.andypj.xyz/Article/details/gtlsjdqmsn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xinyue.icu/Article/details/gtrbhwxecu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gaohongyu789.top/Article/details/gtegdvalat.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jqgufenzy.top/Article/details/gtpyyswhem.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.snrcjt.cn/Article/details/gtwlekfxfh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.snrcjt.cn/Article/details/gttinrsnfh.html

C#:   1234567.ToString("N0")
来源：http://dali.zhongyouzk.top/Article/details/gtpduvynso.html

[E17] 首字母大写
来源：http://dali.hongshengwenyu.top/Article/details/gtscnzphsg.html


<!-- 参考信息 -->