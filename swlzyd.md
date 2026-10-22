代发 wailian999

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xylfe.cn/Article/details/gtjvbpycsl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkelbjgxo.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.redwolf501.top/Article/details/gtmiptacqr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yongpay.top/Article/details/gtxzpizvpt.html

[D11] 反转数组
来源：http://dali.daxiang520.top/Article/details/gtuildumzq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hysaishi.cn/Article/details/gthzsuiomx.html

PHP:  array_reverse($arr);
来源：http://dali.jyoumei.cn/Article/details/gtfwtqqrwg.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hysaishi.cn/Article/details/gtoqlxsbhh.html

TS:   [...arr].reverse();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtukpplwfd.html

Java: Collections.reverse(list);
来源：http://dali.zycfv.cn/Article/details/gttuqksfsk.html

Go:   slices.Reverse(arr)
来源：http://dali.9152youxi.cn/Article/details/gtxqvwgzti.html

Ruby: arr.reverse
来源：http://dali.zdqjudy.top/Article/details/gtddfdlbkg.html

C#:   list.Reverse();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyfczhlgl.html

[D12] 查找元素下标
来源：http://dali.hnxiangtu.top/Article/details/gtnripixtu.html

Py:   arr.index(x);  x in arr
来源：http://dali.shzxlz.cn/Article/details/gttxcemztt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xinyue.icu/Article/details/gttjpkihal.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gzhubu.top/Article/details/gthuswbpvg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258888.top/Article/details/gtyiewdtft.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.0kj1m.cn/Article/details/gtfymsayna.html

Go:   slices.Index(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtrgrqgley.html

Ruby: arr.index(x)
来源：http://dali.ehwqpu.com/Article/details/gtavoddfgy.html

C#:   list.IndexOf(x);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmgltfepx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.redwolf501.top/Article/details/gtxjoeqfvl.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yj20258.top/Article/details/gttcsxiazl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ydzc1.top/Article/details/gtfbwdinpb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.andypj.xyz/Article/details/gtuedrevyv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.tianlin.xyz/Article/details/gtaroiiwep.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jqgufenzy.top/Article/details/gtdrebcerc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.fengsongda.top/Article/details/gtcbungvtf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.fzhhl.top/Article/details/gtvsvhgttd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.iojbl.cn/Article/details/gtaibvjnug.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwfowiiwv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrgwohyeh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhengqikj.top/Article/details/gtbwvknyyp.html

JS:   arr.map(x => x * 2)
来源：http://dali.ivvv.top/Article/details/gtjpedyhlo.html

TS:   arr.map(x => x * 2)
来源：http://dali.xylfe.cn/Article/details/gtvojiunob.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.smart0.xyz/Article/details/gtarloeckc.html

Go:   // 手写循环
来源：http://dali.yj20258.top/Article/details/gtrbpxkelu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ppjwa.cn/Article/details/gtfrniosps.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzhbzfyha.html

[D15] 去重
来源：http://dali.hnqzz.top/Article/details/gtqlddaftk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.dianchejie.cn/Article/details/gtubohevxk.html

PHP:  array_unique($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtovcxbrgy.html

JS:   [...new Set(arr)]
来源：http://dali.hysaishi.cn/Article/details/gtugvqlmlp.html

TS:   [...new Set(arr)]
来源：http://dali.guowangkeji.top/Article/details/gtrhfyochm.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cdnleiting.top/Article/details/gtsejuovpb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.wangshuangyany.cn/Article/details/gtcgrfijmn.html

Ruby: arr.uniq
来源：http://dali.yj202588.top/Article/details/gtbrbxuwbv.html

C#:   list.Distinct().ToList()
来源：http://dali.smart0.xyz/Article/details/gtadtlkdws.html

[D16] 求和与平均值
来源：http://dali.xuanzx.com/Article/details/gticxoivgb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.fzhhl.top/Article/details/gtmeknfqib.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jianghu66.top/Article/details/gtrifcemsh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmnvovcpu.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.haohaochexian.top/Article/details/gtwdssbzar.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hnxiangtu.top/Article/details/gtmhaamjhi.html

Go:   // 手写循环累加
来源：http://dali.wangshuangyany.cn/Article/details/gtofkbivzg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj202588.top/Article/details/gtduxaigca.html

C#:   list.Sum();  list.Average()
来源：http://dali.bjfxy.top/Article/details/gtaortuoug.html

[D17] 最大值与最小值
来源：http://dali.gzhubu.top/Article/details/gtwtzhyimj.html

Py:   max(arr);  min(arr)
来源：http://dali.iojbl.cn/Article/details/gtwkpyuekn.html

PHP:  max($arr);  min($arr);
来源：http://dali.mhx1999.top/Article/details/gthogjmxaw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtijqlwrwj.html

TS:   Math.max(...arr);
来源：http://dali.hywenlv.cn/Article/details/gtqqicfmdy.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtozhlcagf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.0kj1m.cn/Article/details/gtkapgdxdh.html

Ruby: arr.max;  arr.min
来源：http://dali.shuidangran.top/Article/details/gtqbbenova.html

C#:   list.Max();  list.Min()
来源：http://dali.ivvv.top/Article/details/gtyolindiv.html

[D18] 扁平化嵌套数组
来源：http://dali.jinqigfzy.top/Article/details/gttqiopqrz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.9152youxi.cn/Article/details/gtvnwzecae.html

PHP:  array_merge(...$nested);
来源：http://dali.ivvv.top/Article/details/gtuisazcii.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.haohaochexian.top/Article/details/gtpvtbussz.html

TS:   nested.flat();
来源：http://dali.haohaochexian.top/Article/details/gtvhclyqzl.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinqigufen.top/Article/details/gtzkxtfmtp.html

Go:   // 手写双层循环
来源：http://dali.snrcjt.cn/Article/details/gtttoalsco.html

Ruby: nested.flatten
来源：http://dali.316326.xyz/Article/details/gtmlxkcfyb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.gzhubu.top/Article/details/gtifludlhi.html

[D19] 按字段分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtweaumyao.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yuxming.cn/Article/details/gtrcatknvb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.tanke756.top/Article/details/gtkqvplaiw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hnxiangtu.top/Article/details/gthhiughxo.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.fzhhl.top/Article/details/gtwmrnfwjk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xuanzx.com/Article/details/gthqqnbchf.html

Go:   // 手写 map[string][]T
来源：http://dali.aibaodan.cn/Article/details/gtcvdnlgba.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sweek.top/Article/details/gtxzyqtccb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jqgfzy.top/Article/details/gtpxzznzin.html

[D20] 统计每个元素出现次数
来源：http://dali.yj20258888.top/Article/details/gtbngdlukx.html

Py:   Counter(arr)
来源：http://dali.zdqjudy.top/Article/details/gtpslxjnhb.html

PHP:  array_count_values($arr);
来源：http://dali.yj202588.top/Article/details/gtmerbqxki.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xinyue.icu/Article/details/gtbsqloooc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuxming.cn/Article/details/gttrihtgcg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hywenlv.cn/Article/details/gtmyrsmpqc.html

Go:   // 手写 map[T]int
来源：http://dali.smart0.xyz/Article/details/gthtxpgjnh.html

Ruby: arr.tally
来源：http://dali.ydzc1.top/Article/details/gtzfkumolb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shangyingyoupin.top/Article/details/gtzjxrbkam.html

[D21] 判断是否包含某元素
来源：http://dali.iojbl.cn/Article/details/gtxvhlemzi.html

Py:   x in arr
来源：http://dali.cheryme.top/Article/details/gtufnwbtcp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cqqwz.cn/Article/details/gtngxllwmp.html

JS:   arr.includes(x)
来源：http://dali.xylfe.cn/Article/details/gtdggbbxuk.html

TS:   arr.includes(x)
来源：http://dali.gzhubu.top/Article/details/gtynyclpea.html

Java: list.contains(x)
来源：http://dali.yj20258888.top/Article/details/gtasfavtvx.html

Go:   slices.Contains(arr, x)
来源：http://dali.meibo888.top/Article/details/gtpuaqfgpj.html

Ruby: arr.include?(x)
来源：http://dali.fzhhl.top/Article/details/gthxkrcgde.html

C#:   list.Contains(x)
来源：http://dali.bjfxy.top/Article/details/gticspyeea.html

[D22] 复制数组（避免共享引用）
来源：http://dali.aizwys.cn/Article/details/gtvzoiovhe.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj20258.top/Article/details/gtvxjblfzp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gotoacloud.top/Article/details/gtdaekzdnt.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.havefunace.top/Article/details/gtoqhzbuwp.html

TS:   [...arr];
来源：http://dali.cucudq.cn/Article/details/gtrsrpfyge.html

Java: new ArrayList<>(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtausecdgn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ehwqpu.com/Article/details/gtjjiwevbe.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zdqjudy.top/Article/details/gtwxnwluar.html

C#:   new List<int>(list);
来源：http://dali.haohaochexian.top/Article/details/gtotgrslre.html

[D23] reduce 累积计算
来源：http://dali.yj20258888.top/Article/details/gtcnqequph.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ybcxt.top/Article/details/gtzzsordgx.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.tian-w.cn/Article/details/gttmwxiarf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.birdmap.top/Article/details/gtixbwjitu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xziqi.cn/Article/details/gtfymtbses.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yj202588.top/Article/details/gtrdcneyax.html

Go:   // 手写循环
来源：http://dali.ydzc1.top/Article/details/gtydrntzkz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xylfe.cn/Article/details/gtmtynjnfy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jianghu66.top/Article/details/gtvdliuhtv.html

[D24] 字典 / Map 基本操作
来源：http://dali.gotoacloud.top/Article/details/gtrbngqlid.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jqgfzy.top/Article/details/gttaurruta.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xuetiantiany.cn/Article/details/gtgwppmicy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cucudq.cn/Article/details/gtmokobdmw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.daria6918.cn/Article/details/gtkltfkaut.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shangyingyoupin.top/Article/details/gtosascmsv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hfpthk.cn/Article/details/gtojdatcvt.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gzhubu.top/Article/details/gtlhzhfdwi.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.wangdashe.top/Article/details/gtupianoxc.html

[D25] Set 集合去重与交并差
来源：http://dali.hnqzz.top/Article/details/gtmcjhlqzy.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.meibo888.top/Article/details/gtczzywsir.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.316326.xyz/Article/details/gtdfbfkgqm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinqigfzy.top/Article/details/gtfxlounbi.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hfpthk.cn/Article/details/gtpedkixkx.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jianghu66.top/Article/details/gtephkcptx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenjidiqi.icu/Article/details/gtvzeycyey.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.fzhhl.top/Article/details/gtmsauwcrr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yonumen.top/Article/details/gtmygdqcvl.html

[D26] 数组转字符串
来源：http://dali.ybcxt.top/Article/details/gtgukypded.html

Py:   ", ".join(map(str, arr))
来源：http://dali.316326.xyz/Article/details/gteftwkokd.html

PHP:  implode(", ", $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtyqtjvntx.html

JS:   arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gtmmvvnlga.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gtrsizddrl.html

Java: String.join(", ", list)
来源：http://dali.0kj1m.cn/Article/details/gtrngucmhp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.meibo888.top/Article/details/gttfhfwlcm.html

Ruby: arr.join(", ")
来源：http://dali.feifeiyinyue.top/Article/details/gtgytobbcj.html

C#:   string.Join(", ", list)
来源：http://dali.jyoumei.cn/Article/details/gteyfwgdfm.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtcccnpedu.html

E. 字符串处理
来源：http://dali.cucudq.cn/Article/details/gtxjknbnio.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtyhppxkgs.html

[E01] 拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwwzctwqd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.bjfxy.top/Article/details/gtrzucsppu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hammf.cn/Article/details/gtqnovgevz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.svipenyu.cn/Article/details/gtfsoshmgc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.smart0.xyz/Article/details/gtxdzwinht.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.guannengcc.top/Article/details/gtpzjohrwv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hywenlv.cn/Article/details/gtdrupwisx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xuanzx.com/Article/details/gtltcdzuwi.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtmhuguogf.html

[E02] 重复字符串
来源：http://dali.yonumen.top/Article/details/gtevczhjum.html

Py:   "ab" * 3
来源：http://dali.bjfxy.top/Article/details/gtjupffgnf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.mhx1999.top/Article/details/gttfceymxb.html

JS:   "ab".repeat(3)
来源：http://dali.zhoulong.xyz/Article/details/gtnhdcwqwf.html

TS:   "ab".repeat(3)
来源：http://dali.nwbrower.top/Article/details/gtzzmqqvrf.html

Java: "ab".repeat(3)
来源：http://dali.tianlin.xyz/Article/details/gtfiyuyiuq.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.vqdsnc.cn/Article/details/gtfudzyozj.html

Ruby: "ab" * 3
来源：http://dali.haohaochexian.top/Article/details/gtqnvbqspn.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.iojbl.cn/Article/details/gttzjeilva.html

[E03] 截取子串
来源：http://dali.shuidangran.top/Article/details/gtkapoijuk.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jyoumei.cn/Article/details/gtlrrqdjax.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gtzugsulzk.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.c1oappe.top/Article/details/gtakllqvms.html

TS:   s.slice(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gtmjeynwff.html

Java: s.substring(1, 4)
来源：http://dali.mhx1999.top/Article/details/gtmpwoeori.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sufxvd.cn/Article/details/gtvuvyllcb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinqigfzy.top/Article/details/gtticjjcgm.html

C#:   s.Substring(1, 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtifpvdash.html

[E04] 查找子串位置
来源：http://dali.yuanzhike.top/Article/details/gtmzdftczz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.9152youxi.cn/Article/details/gtgxmbwytk.html

PHP:  strpos($s, "x");
来源：http://dali.dianchejie.cn/Article/details/gtpznzofoj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.fengsongda.top/Article/details/gtemnexhtc.html

TS:   s.indexOf("x")
来源：http://dali.svipenyu.cn/Article/details/gtkxmckzfg.html

Java: s.indexOf("x")
来源：http://dali.zycfv.cn/Article/details/gtdzipmcpo.html

Go:   strings.Index(s, "x")
来源：http://dali.yongpay.top/Article/details/gtypmmpiys.html

Ruby: s.index("x")
来源：http://dali.zdqjudy.top/Article/details/gtzekmzfml.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gtfwiagplv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.bjfxy.top/Article/details/gtnfzprqdu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zdqjudy.top/Article/details/gtzmhaagtc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.redwolf501.top/Article/details/gtudbjqmjj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sxryk.cn/Article/details/gtizwhzwcc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jinqigfzy.top/Article/details/gtjmtslljw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gaohongyu789.top/Article/details/gtfyembhoq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.gogol.net.cn/Article/details/gtephwshql.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jianghu66.top/Article/details/gtjbgekcgy.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gtyfklwntm.html

[E06] 替换子串
来源：http://dali.vqdsnc.cn/Article/details/gtxnwewflw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gotoacloud.top/Article/details/gtushviaoq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hfpthk.cn/Article/details/gtypoweuwu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tian-w.cn/Article/details/gtiifpcrug.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtwdwdqmfu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyfwgwanq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.snrcjt.cn/Article/details/gtmdhosprr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yonumen.top/Article/details/gtgvorjlcw.html

C#:   s.Replace("a", "b")
来源：http://dali.cucudq.cn/Article/details/gthbxxnbmk.html

[E07] 按分隔符拆分
来源：http://dali.yueranfly.top/Article/details/gtefkcxoml.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yvedp.cn/Article/details/gtiolrcclv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.wangdashe.top/Article/details/gtbbicrohh.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.gotoacloud.top/Article/details/gtiiovlzez.html

TS:   s.split(",")
来源：http://dali.cqqwz.cn/Article/details/gtsyqgdogu.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.feifeiyinyue.top/Article/details/gtyqjhirar.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cucudq.cn/Article/details/gtxiosalty.html

Ruby: s.split(",");  s.split
来源：http://dali.meibo888.top/Article/details/gtvqwsnwvo.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.0kj1m.cn/Article/details/gtuirawqsx.html

[E08] 数组按分隔符合并
来源：http://dali.zhongyouzk.top/Article/details/gtmozeirud.html

Py:   ",".join(items)
来源：http://dali.xziqi.cn/Article/details/gthkutdjjr.html

PHP:  implode(",", $items);
来源：http://dali.dashuyun.cn/Article/details/gtbtzyqrsm.html

JS:   items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gtvpyjfygn.html

TS:   items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gtbapkgztq.html

Java: String.join(",", items)
来源：http://dali.cucudq.cn/Article/details/gtjhiabafh.html

Go:   strings.Join(items, ",")
来源：http://dali.shangyingyoupin.top/Article/details/gtnzhguccy.html

Ruby: items.join(",")
来源：http://dali.zhixingplan.top/Article/details/gtwnijedur.html

C#:   string.Join(",", items)
来源：http://dali.yuanzhike.top/Article/details/gttruxblax.html

[E09] 去除所有空白字符
来源：http://dali.jqgufenzy.top/Article/details/gtckzfigye.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cucudq.cn/Article/details/gtbyfxusgv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.aizwys.cn/Article/details/gtytcrmvqc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zycfv.cn/Article/details/gtnnqowlqg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yonumen.top/Article/details/gtktcmfxtf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.snrcjt.cn/Article/details/gtrkinelrx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yvedp.cn/Article/details/gtydapmyuy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhiwuduotai.top/Article/details/gtuxiejkrg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shangyingyoupin.top/Article/details/gttibwqsej.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinqigfzy.top/Article/details/gtnhicpuqv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.daxiang520.top/Article/details/gtytqzmwnn.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zdqjudy.top/Article/details/gtbrzoepzd.html

JS:   "7".padStart(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gtiybsxyvn.html

TS:   "7".padStart(3, "0")
来源：http://dali.dianchejie.cn/Article/details/gtrogjvxfx.html

Java: String.format("%03d", 7)
来源：http://dali.gogol.net.cn/Article/details/gtytddutub.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gzhubu.top/Article/details/gtefigzpqg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnmhrexpw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.aizwys.cn/Article/details/gtonbtpyhc.html

[E11] 反转字符串
来源：http://dali.aibaodan.cn/Article/details/gtetdjtqyz.html

Py:   s[::-1]
来源：http://dali.nanxinkj.top/Article/details/gtwiwfwahb.html

PHP:  strrev($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtstxmrspw.html

JS:   [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gtnjklzqkk.html

TS:   [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gtjboxnxrd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jianghu66.top/Article/details/gtuauzbbrc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.c1oappe.top/Article/details/gtlvrmleoq.html

Ruby: s.reverse
来源：http://dali.xziqi.cn/Article/details/gtnjqjgifr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xuanzx.com/Article/details/gtiglhnxun.html

[E12] 统计某字符出现次数
来源：http://dali.svipenyu.cn/Article/details/gtlrifwznd.html

Py:   s.count("a")
来源：http://dali.nanxuanxn.top/Article/details/gtmusezeit.html

PHP:  substr_count($s, "a");
来源：http://dali.meibo888.top/Article/details/gtthpqvios.html

JS:   s.split("a").length - 1
来源：http://dali.xuanzx.com/Article/details/gtcdoywoxx.html

TS:   s.split("a").length - 1
来源：http://dali.hnqzz.top/Article/details/gtgkmkveen.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zdqjudy.top/Article/details/gtjwfmhere.html

Go:   strings.Count(s, "a")
来源：http://dali.fzhhl.top/Article/details/gtbayrjcda.html

Ruby: s.count("a")
来源：http://dali.dashuyun.cn/Article/details/gtvopwlyes.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shzxlz.cn/Article/details/gteqnbtukd.html

[E13] 逐字符遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqygcfcgl.html

Py:   for ch in s: print(ch)
来源：http://dali.shangyingyoupin.top/Article/details/gtcwesmamu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yueranfly.top/Article/details/gtldwrheas.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xylfe.cn/Article/details/gttwieulsz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxinkj.top/Article/details/gtneyjnjhi.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hnqzz.top/Article/details/gtojthsqiz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hnxiangtu.top/Article/details/gtpivnlftv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yvedp.cn/Article/details/gtdtyxieod.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.snrcjt.cn/Article/details/gtoiuklesw.html

[E14] URL 编码与 Base64
来源：http://dali.yanxiufei.cn/Article/details/gttarzskts.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhixingplan.top/Article/details/gtovtjphgz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ivvv.top/Article/details/gtanpmpfah.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hnxiangtu.top/Article/details/gtxtkqalil.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yangfankeji.com/Article/details/gtoxshjjub.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gaohongyu789.top/Article/details/gtnkjgzwny.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gotoacloud.top/Article/details/gtatfwkfpe.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cheryme.top/Article/details/gtgkilpces.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yanxiufei.cn/Article/details/gtxvsboood.html

[E15] HTML 转义 / 反转义
来源：http://dali.jqgfzy.top/Article/details/gtdoiehfom.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhoulong.xyz/Article/details/gtsxrtuzry.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtweemyivn.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtxsvanihz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.kuanghao11.cn/Article/details/gtbjggvzfl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyfumgimx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.tian-w.cn/Article/details/gtnfzdundt.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sysykeji.top/Article/details/gtwjkaqipb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gogol.net.cn/Article/details/gtfmennvdx.html

[E16] 数字千分位
来源：http://dali.havefunace.top/Article/details/gtmfwrwuiv.html

Py:   f"{1234567:,}"
来源：http://dali.yvedp.cn/Article/details/gtulkqhrav.html

PHP:  number_format(1234567);
来源：http://dali.aibaodan.cn/Article/details/gtlpdlsrti.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ivvv.top/Article/details/gtnhbnxfxe.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.fzhhl.top/Article/details/gtwkbpscav.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.andypj.xyz/Article/details/gtlkoeomcp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yuanzhike.top/Article/details/gtfvehctqo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jqgufenzy.top/Article/details/gtwvzggjlv.html

C#:   1234567.ToString("N0")
来源：http://dali.ivvv.top/Article/details/gtiwsdygac.html

[E17] 首字母大写
来源：http://dali.0kj1m.cn/Article/details/gtlynhhrgh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shangyingyoupin.top/Article/details/gtokxoidpt.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.fzhhl.top/Article/details/gtudjfwkty.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yangfankeji.com/Article/details/gttnljoehn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guowangkeji.top/Article/details/gtgrfxsuey.html


<!-- 参考信息 -->