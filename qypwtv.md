代发 wailian999

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.snrcjt.cn/Article/details/gtwrkwjxrc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hnxiangtu.top/Article/details/gtketfisuq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nwbrower.top/Article/details/gtdncbrrwp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinqigfzy.top/Article/details/gtzzdsfpjg.html

[D11] 反转数组
来源：http://dali.yanxiufei.cn/Article/details/gtezmhvxis.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hongshengwenyu.top/Article/details/gtcmcvooat.html

PHP:  array_reverse($arr);
来源：http://dali.svipenyu.cn/Article/details/gttumcdfaz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhoulong.xyz/Article/details/gtkfgjyzrf.html

TS:   [...arr].reverse();
来源：http://dali.yuanzhike.top/Article/details/gtdtlcbgoy.html

Java: Collections.reverse(list);
来源：http://dali.yuxming.cn/Article/details/gthwijxvts.html

Go:   slices.Reverse(arr)
来源：http://dali.ivvv.top/Article/details/gtoirxrzhh.html

Ruby: arr.reverse
来源：http://dali.zdqjudy.top/Article/details/gteagafthj.html

C#:   list.Reverse();
来源：http://dali.hnqzz.top/Article/details/gtpiyjuzcx.html

[D12] 查找元素下标
来源：http://dali.iojbl.cn/Article/details/gtpfjbvtiv.html

Py:   arr.index(x);  x in arr
来源：http://dali.jqgfzy.top/Article/details/gtxfzewkaf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xinyue.icu/Article/details/gtqpgarriq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dianchejie.cn/Article/details/gtwxrplbvr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuanzhike.top/Article/details/gthqrzinob.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zdqjudy.top/Article/details/gtvmjdydnc.html

Go:   slices.Index(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtgietcmjd.html

Ruby: arr.index(x)
来源：http://dali.shuidangran.top/Article/details/gtcalpdmdo.html

C#:   list.IndexOf(x);
来源：http://dali.jqgufenzy.top/Article/details/gtksyirsxh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jiagoushi.top/Article/details/gtfgxmvxtc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ydzc1.top/Article/details/gtoeptdcid.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cheryme.top/Article/details/gttmheapbj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.havefunace.top/Article/details/gtgxrtljtt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yj202588.top/Article/details/gttumlojhz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbjlgbub.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinqigfzy.top/Article/details/gtmbypayqg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cqqwz.cn/Article/details/gtjzapgnco.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.sxryk.cn/Article/details/gtrrofweor.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xuanzx.com/Article/details/gtcdpsmsxy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.aizwys.cn/Article/details/gtdgpodooi.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xinyue.icu/Article/details/gtwuefjmsf.html

JS:   arr.map(x => x * 2)
来源：http://dali.iojbl.cn/Article/details/gtiylkryqw.html

TS:   arr.map(x => x * 2)
来源：http://dali.yj20258888.top/Article/details/gtlluicvtt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.andypj.xyz/Article/details/gtiudrohkm.html

Go:   // 手写循环
来源：http://dali.shuidangran.top/Article/details/gtflrtktxe.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.tianlin.xyz/Article/details/gtfhefassg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cdnleiting.top/Article/details/gttxjmhjru.html

[D15] 去重
来源：http://dali.gzhubu.top/Article/details/gtekfwaxqu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.dashuyun.cn/Article/details/gtoysmwgnd.html

PHP:  array_unique($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtisztjnuj.html

JS:   [...new Set(arr)]
来源：http://dali.jyoumei.cn/Article/details/gtsmoingqt.html

TS:   [...new Set(arr)]
来源：http://dali.xziqi.cn/Article/details/gtubryqvon.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yj202588.top/Article/details/gtexrrocei.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.c1oappe.top/Article/details/gtwbhezvfi.html

Ruby: arr.uniq
来源：http://dali.xuetiantiany.cn/Article/details/gtdrrwbqts.html

C#:   list.Distinct().ToList()
来源：http://dali.zhixingplan.top/Article/details/gtcjfafegy.html

[D16] 求和与平均值
来源：http://dali.vqdsnc.cn/Article/details/gtnhzavyip.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.svipenyu.cn/Article/details/gtxcynnbqe.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtulvuzsxc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hywenlv.cn/Article/details/gtbbmyycwp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.0kj1m.cn/Article/details/gthqndmihf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jianghu66.top/Article/details/gtjkectusi.html

Go:   // 手写循环累加
来源：http://dali.andypj.xyz/Article/details/gtibmddots.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sufxvd.cn/Article/details/gtfznyqhxl.html

C#:   list.Sum();  list.Average()
来源：http://dali.andypj.xyz/Article/details/gtjcaqkgcn.html

[D17] 最大值与最小值
来源：http://dali.ybcxt.top/Article/details/gtgslkcsad.html

Py:   max(arr);  min(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtbkkgodhr.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhoulong.xyz/Article/details/gthnylxjvn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.redwolf501.top/Article/details/gtzsggvliz.html

TS:   Math.max(...arr);
来源：http://dali.redwolf501.top/Article/details/gtcbocwcxi.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.nwbrower.top/Article/details/gtulquwxxe.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.birdmap.top/Article/details/gtnryanovq.html

Ruby: arr.max;  arr.min
来源：http://dali.yongpay.top/Article/details/gtvuonzdek.html

C#:   list.Max();  list.Min()
来源：http://dali.redwolf501.top/Article/details/gtahgapphe.html

[D18] 扁平化嵌套数组
来源：http://dali.hywenlv.cn/Article/details/gtyzuvwfdb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ehwqpu.com/Article/details/gtfyzdppfn.html

PHP:  array_merge(...$nested);
来源：http://dali.havefunace.top/Article/details/gtsplsvako.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shangyingyoupin.top/Article/details/gtbmkenksr.html

TS:   nested.flat();
来源：http://dali.hammf.cn/Article/details/gtdublohpz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hammf.cn/Article/details/gtxmiifebp.html

Go:   // 手写双层循环
来源：http://dali.chenjidiqi.icu/Article/details/gtlihsctbv.html

Ruby: nested.flatten
来源：http://dali.tian-w.cn/Article/details/gtzfhodobo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtofhdmnji.html

[D19] 按字段分组
来源：http://dali.hnqzz.top/Article/details/gtahhkyyfn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yanxiufei.cn/Article/details/gtrbobpwzd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhengqikj.top/Article/details/gtqdtdxhyg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xuetiantiany.cn/Article/details/gtpmeiqxhu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.bjfxy.top/Article/details/gtzlxlaxsl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cheryme.top/Article/details/gtfsmiznih.html

Go:   // 手写 map[string][]T
来源：http://dali.xuanzx.com/Article/details/gtujisdvmw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yangfankeji.com/Article/details/gtbgcxntbh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhiwuduotai.top/Article/details/gtgoigrqcv.html

[D20] 统计每个元素出现次数
来源：http://dali.yueranfly.top/Article/details/gtmvwtnkel.html

Py:   Counter(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtunmpubfu.html

PHP:  array_count_values($arr);
来源：http://dali.dashuyun.cn/Article/details/gtjiqkotte.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.iojbl.cn/Article/details/gtialekshp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aibaodan.cn/Article/details/gtlywezrdi.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuqkdtjlk.html

Go:   // 手写 map[T]int
来源：http://dali.chenzaomai.com/Article/details/gtclgkkejb.html

Ruby: arr.tally
来源：http://dali.sufxvd.cn/Article/details/gtehxobppv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.vqdsnc.cn/Article/details/gtbrurpkns.html

[D21] 判断是否包含某元素
来源：http://dali.quarkkingdee.top/Article/details/gtkyutwyyr.html

Py:   x in arr
来源：http://dali.quarkkingdee.top/Article/details/gtioxzpxbn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yangfankeji.com/Article/details/gtykfjrhog.html

JS:   arr.includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtoujqstyn.html

TS:   arr.includes(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtnttiihpe.html

Java: list.contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gtukhihnqe.html

Go:   slices.Contains(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtuaazodot.html

Ruby: arr.include?(x)
来源：http://dali.jlsjyb.cn/Article/details/gtohipcrep.html

C#:   list.Contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gtptnbiqui.html

[D22] 复制数组（避免共享引用）
来源：http://dali.c1oappe.top/Article/details/gtghurzrcq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.dianchejie.cn/Article/details/gtuuufdscs.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.nanxinkj.top/Article/details/gtrnnddfns.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yvedp.cn/Article/details/gtludeexoc.html

TS:   [...arr];
来源：http://dali.zhengqikj.top/Article/details/gthvdfoojy.html

Java: new ArrayList<>(list);
来源：http://dali.c1oappe.top/Article/details/gtvhkekysk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gogol.net.cn/Article/details/gtbvtevnnh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hfpthk.cn/Article/details/gthohlqvzq.html

C#:   new List<int>(list);
来源：http://dali.zhengqikj.top/Article/details/gtprjnyoib.html

[D23] reduce 累积计算
来源：http://dali.xuetiantiany.cn/Article/details/gtziwdvvee.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.guowangkeji.top/Article/details/gtaqmvtqnn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj20258888.top/Article/details/gtidlltwaw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtixmigbfl.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aibaodan.cn/Article/details/gtivzjjozb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.pycfn.com/Article/details/gtqwiyrkzj.html

Go:   // 手写循环
来源：http://dali.nanxuanxn.top/Article/details/gtcrgxlhvq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cheryme.top/Article/details/gtcumlehuv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.birdmap.top/Article/details/gtkggskggn.html

[D24] 字典 / Map 基本操作
来源：http://dali.feifeiyinyue.top/Article/details/gtpxtlblso.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.haohaochexian.top/Article/details/gtgqcokpuw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.c1oappe.top/Article/details/gtwyvkikki.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ydzc1.top/Article/details/gtlkcikpgk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gttcpyzarw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.wangdashe.top/Article/details/gtexhxiwzs.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jlsjyb.cn/Article/details/gtqxebeqge.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ehwqpu.com/Article/details/gtxvcllgah.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yj202588.top/Article/details/gtvkvihqnc.html

[D25] Set 集合去重与交并差
来源：http://dali.9152youxi.cn/Article/details/gtkcaskjkx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ppjwa.cn/Article/details/gthekhnmga.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zdqjudy.top/Article/details/gtlievxbrx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hywenlv.cn/Article/details/gtznfvjiwr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hysaishi.cn/Article/details/gtolifuqbk.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtmdqjnqbt.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hnqzz.top/Article/details/gtgsuhebdr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xinyue.icu/Article/details/gtttaiyebq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbgbhtoei.html

[D26] 数组转字符串
来源：http://dali.gaohongyu789.top/Article/details/gtwfqvkvhk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.andypj.xyz/Article/details/gtmglqmghu.html

PHP:  implode(", ", $arr);
来源：http://dali.jyoumei.cn/Article/details/gtucfldscs.html

JS:   arr.join(", ")
来源：http://dali.chenjidiqi.icu/Article/details/gtcglocixq.html

TS:   arr.join(", ")
来源：http://dali.fengsongda.top/Article/details/gtllqbtsdp.html

Java: String.join(", ", list)
来源：http://dali.sufxvd.cn/Article/details/gtcxioqeos.html

Go:   strings.Join(strs, ", ")
来源：http://dali.chenzaomai.com/Article/details/gttznrllkz.html

Ruby: arr.join(", ")
来源：http://dali.hnxiangtu.top/Article/details/gtnliptdbi.html

C#:   string.Join(", ", list)
来源：http://dali.daxiang520.top/Article/details/gtcsiblacm.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtoigzbzoe.html

E. 字符串处理
来源：http://dali.fengsongda.top/Article/details/gtnzdqqbyt.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtyspjdxwl.html

[E01] 拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxyqnpcde.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yvedp.cn/Article/details/gtekkrdaqc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.dashuyun.cn/Article/details/gtcreszzwu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigufen.top/Article/details/gtnliscsef.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigufen.top/Article/details/gtrmnmedgd.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cheryme.top/Article/details/gtsqdhliel.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yj20258888.top/Article/details/gtmtubfast.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hammf.cn/Article/details/gtaexrkghq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtbxbuoycr.html

[E02] 重复字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtibmzwwvz.html

Py:   "ab" * 3
来源：http://dali.wangshuangyany.cn/Article/details/gtefywjpur.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jqgfzy.top/Article/details/gtlefpudvq.html

JS:   "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gtvubwqbhw.html

TS:   "ab".repeat(3)
来源：http://dali.smart0.xyz/Article/details/gtrognryxf.html

Java: "ab".repeat(3)
来源：http://dali.quarkkingdee.top/Article/details/gtorbaxzzw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xinyue.icu/Article/details/gtmkwqbgcy.html

Ruby: "ab" * 3
来源：http://dali.316326.xyz/Article/details/gttcwqjeup.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yangfankeji.com/Article/details/gtcyjlkqth.html

[E03] 截取子串
来源：http://dali.nwbrower.top/Article/details/gthcqdhwpv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gogol.net.cn/Article/details/gtlqameixo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gtspyactob.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gtpykaqsui.html

TS:   s.slice(1, 4)
来源：http://dali.zhoulong.xyz/Article/details/gtjxsmqmtu.html

Java: s.substring(1, 4)
来源：http://dali.xziqi.cn/Article/details/gtorohyxdj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hongshengwenyu.top/Article/details/gtdrqygoep.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jiagoushi.top/Article/details/gtgsxtnqrp.html

C#:   s.Substring(1, 3)
来源：http://dali.aizwys.cn/Article/details/gtpxibnacc.html

[E04] 查找子串位置
来源：http://dali.sysykeji.top/Article/details/gtxrwnhsmx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.svipenyu.cn/Article/details/gtzlvwoxin.html

PHP:  strpos($s, "x");
来源：http://dali.yj20258888.top/Article/details/gtspmjtbrc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yongpay.top/Article/details/gtoojplzaw.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gtlyfggnyc.html

Java: s.indexOf("x")
来源：http://dali.aibaodan.cn/Article/details/gtketsjmog.html

Go:   strings.Index(s, "x")
来源：http://dali.cdnleiting.top/Article/details/gttbtekmfy.html

Ruby: s.index("x")
来源：http://dali.tianlin.xyz/Article/details/gtlcxetzkj.html

C#:   s.IndexOf("x")
来源：http://dali.redwolf501.top/Article/details/gthktumulk.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhiwuduotai.top/Article/details/gtcvtyfmfu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.wangdashe.top/Article/details/gtgcfghshy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.pycfn.com/Article/details/gtkxkfckft.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gogol.net.cn/Article/details/gttlpyofle.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zdqjudy.top/Article/details/gtfigxajvu.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258.top/Article/details/gtraacgjhw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhongyouzk.top/Article/details/gtspcwbrkr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinqigfzy.top/Article/details/gtcmdkpgma.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gtkbvyzlyj.html

[E06] 替换子串
来源：http://dali.tian-w.cn/Article/details/gtpijcyvud.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmtqejsrp.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtmsalonpf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtufcbikbt.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtckplgelk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gttvnwglyz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hammf.cn/Article/details/gtpbdkswdh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtbtvqdslu.html

C#:   s.Replace("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtpsmbrdee.html

[E07] 按分隔符拆分
来源：http://dali.xziqi.cn/Article/details/gtnqxpsljc.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xziqi.cn/Article/details/gtslbmcndk.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinqigufen.top/Article/details/gthallmeiv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hfpthk.cn/Article/details/gtjatlwsde.html

TS:   s.split(",")
来源：http://dali.haohaochexian.top/Article/details/gtmyollkqu.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gaohongyu789.top/Article/details/gtvopjvbyt.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinqigfzy.top/Article/details/gtabrvpmtp.html

Ruby: s.split(",");  s.split
来源：http://dali.xuanzx.com/Article/details/gtnqseoxds.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shzxlz.cn/Article/details/gtsrvknzdo.html

[E08] 数组按分隔符合并
来源：http://dali.wangshuangyany.cn/Article/details/gtcnswalhs.html

Py:   ",".join(items)
来源：http://dali.sysykeji.top/Article/details/gtsyxqpeds.html

PHP:  implode(",", $items);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdaslisfy.html

JS:   items.join(",")
来源：http://dali.xziqi.cn/Article/details/gtmmskzhyo.html

TS:   items.join(",")
来源：http://dali.havefunace.top/Article/details/gtjeaujphh.html

Java: String.join(",", items)
来源：http://dali.cdnleiting.top/Article/details/gttyjmtasm.html

Go:   strings.Join(items, ",")
来源：http://dali.316326.xyz/Article/details/gtwmatejls.html

Ruby: items.join(",")
来源：http://dali.jqgufenzy.top/Article/details/gtswxzhhcn.html

C#:   string.Join(",", items)
来源：http://dali.zdqjudy.top/Article/details/gtynwojmkg.html

[E09] 去除所有空白字符
来源：http://dali.pengpengdd.cyou/Article/details/gtasnororp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.havefunace.top/Article/details/gtbiotjyql.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gogol.net.cn/Article/details/gtulovnizu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.quarkkingdee.top/Article/details/gtmxebgnkk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrurfpjtl.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhongyouzk.top/Article/details/gtjxyemrtk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sxryk.cn/Article/details/gtdohxgwlo.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.0kj1m.cn/Article/details/gtkofpfpif.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jqgfzy.top/Article/details/gtjaeupkio.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gtyijusbcr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.iojbl.cn/Article/details/gtcsvlqysy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwudqscgw.html

JS:   "7".padStart(3, "0")
来源：http://dali.jianghu66.top/Article/details/gthmomzozm.html

TS:   "7".padStart(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gtsdnelegq.html

Java: String.format("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gtkhpzgczx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.9152youxi.cn/Article/details/gtmpizmtus.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shangyingyoupin.top/Article/details/gtydbcfxdm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jiagoushi.top/Article/details/gtdlwxoefc.html

[E11] 反转字符串
来源：http://dali.mhx1999.top/Article/details/gthndcmfbc.html

Py:   s[::-1]
来源：http://dali.cheryme.top/Article/details/gtswjwuvac.html

PHP:  strrev($s);
来源：http://dali.wangdashe.top/Article/details/gtgfwbivzh.html

JS:   [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gtkoaliclx.html

TS:   [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gtxiobvffl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhoulong.xyz/Article/details/gtgsytpjkd.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shangyingyoupin.top/Article/details/gtehtpjbhr.html

Ruby: s.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gtdfqfrnjr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.9152youxi.cn/Article/details/gttmzfhita.html

[E12] 统计某字符出现次数
来源：http://dali.yj20258888.top/Article/details/gtwhhjqcdi.html

Py:   s.count("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtebgqiudz.html

PHP:  substr_count($s, "a");
来源：http://dali.nwbrower.top/Article/details/gtyyizhekt.html

JS:   s.split("a").length - 1
来源：http://dali.xylfe.cn/Article/details/gtldegejor.html

TS:   s.split("a").length - 1
来源：http://dali.nanxuanxn.top/Article/details/gtmptuvaqv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.pycfn.com/Article/details/gtoccbxspe.html

Go:   strings.Count(s, "a")
来源：http://dali.sufxvd.cn/Article/details/gtbhgyyjol.html

Ruby: s.count("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpvtxbjsg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yvedp.cn/Article/details/gtuoydiqvn.html

[E13] 逐字符遍历
来源：http://dali.jlsjyb.cn/Article/details/gtphbtjqse.html

Py:   for ch in s: print(ch)
来源：http://dali.fengsongda.top/Article/details/gttguduccc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.quarkkingdee.top/Article/details/gtiflvgoli.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sufxvd.cn/Article/details/gtrcffmihc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yvedp.cn/Article/details/gtxyciidwz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jianghu66.top/Article/details/gtvaddhmmf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gzhubu.top/Article/details/gtededmwtc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.vqdsnc.cn/Article/details/gtdshjhdsk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.aibaodan.cn/Article/details/gtijutuqyc.html

[E14] URL 编码与 Base64
来源：http://dali.vqdsnc.cn/Article/details/gthsntecjq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinqigufen.top/Article/details/gtgdhhkutn.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtabetatxg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jyoumei.cn/Article/details/gtrvyoroom.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.c1oappe.top/Article/details/gtoojdrhfh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.birdmap.top/Article/details/gtuuwehrqx.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gotoacloud.top/Article/details/gtcqwpixxr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hywenlv.cn/Article/details/gteacjkbcm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xziqi.cn/Article/details/gtrflwmmvj.html

[E15] HTML 转义 / 反转义
来源：http://dali.ppjwa.cn/Article/details/gtwlrwouhi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jqgfzy.top/Article/details/gtmguoyufx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jlsjyb.cn/Article/details/gthjmngbmp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.dianchejie.cn/Article/details/gtnzkrrcvp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.c1oappe.top/Article/details/gtkvsrtznn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj20258.top/Article/details/gtfjxjfsoo.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhoulong.xyz/Article/details/gtrtviazpx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gotoacloud.top/Article/details/gtxdiuxkga.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.guowangkeji.top/Article/details/gttqcfolup.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gtpgvopfkj.html

Py:   f"{1234567:,}"
来源：http://dali.haohaochexian.top/Article/details/gtkjwmgfri.html

PHP:  number_format(1234567);
来源：http://dali.gzhubu.top/Article/details/gtudbmlvtr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.smart0.xyz/Article/details/gtodivmwgu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tian-w.cn/Article/details/gtyxagbhvr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenzaomai.com/Article/details/gtqquixwlq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.316326.xyz/Article/details/gtqrfkmels.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.fengsongda.top/Article/details/gtiueidevu.html

C#:   1234567.ToString("N0")
来源：http://dali.pengpengdd.cyou/Article/details/gtiqcjtart.html

[E17] 首字母大写
来源：http://dali.guannengcc.top/Article/details/gtvrlvxccd.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.meibo888.top/Article/details/gtpzwemxxa.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gtgfdgyqnr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ehwqpu.com/Article/details/gthzutlrzm.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hysaishi.cn/Article/details/gtzkhybzvn.html


<!-- 参考信息 -->