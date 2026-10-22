代发 wailian999

Ruby: a + b;  a.concat(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmrbsytez.html

C#:   a.Concat(b).ToList()
来源：http://dali.ivvv.top/Article/details/gtojsqrhzq.html

[D09] 排序（升序）
来源：http://dali.chenzaomai.com/Article/details/gtaeeqvtjj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cqqwz.cn/Article/details/gtvskysrpf.html

PHP:  sort($arr);
来源：http://dali.yueranfly.top/Article/details/gtirunfudm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.nanxinkj.top/Article/details/gtapxhhbbo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sufxvd.cn/Article/details/gtnvfkhhgg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cucudq.cn/Article/details/gtmnujbjta.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.tanke756.top/Article/details/gtdwtatrqc.html

Ruby: arr.sort
来源：http://dali.bjfxy.top/Article/details/gtdcwzvpac.html

C#:   list.Sort();
来源：http://dali.dashuyun.cn/Article/details/gtjhbheivr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hnqzz.top/Article/details/gtklqjvjxm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhoulong.xyz/Article/details/gthxrqccax.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.pengpengdd.cyou/Article/details/gtwqwljfhd.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yongpay.top/Article/details/gtspdxinla.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yueranfly.top/Article/details/gtpfpdewld.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.snrcjt.cn/Article/details/gtmzxrhzhs.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.0kj1m.cn/Article/details/gtbxxhedjb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yonumen.top/Article/details/gtrviucnif.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sysykeji.top/Article/details/gtkakzdbvp.html

[D11] 反转数组
来源：http://dali.guowangkeji.top/Article/details/gtrojuzvzn.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhongyouzk.top/Article/details/gttsavquco.html

PHP:  array_reverse($arr);
来源：http://dali.meibo888.top/Article/details/gteibapabe.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yangfankeji.com/Article/details/gtvzhjcevx.html

TS:   [...arr].reverse();
来源：http://dali.daxiang520.top/Article/details/gtncahycyb.html

Java: Collections.reverse(list);
来源：http://dali.ehwqpu.com/Article/details/gtthpusfhj.html

Go:   slices.Reverse(arr)
来源：http://dali.zdqjudy.top/Article/details/gtijrgpylw.html

Ruby: arr.reverse
来源：http://dali.yvedp.cn/Article/details/gtaxotohcx.html

C#:   list.Reverse();
来源：http://dali.hysaishi.cn/Article/details/gtiubnvswe.html

[D12] 查找元素下标
来源：http://dali.pycfn.com/Article/details/gtgvdqhocv.html

Py:   arr.index(x);  x in arr
来源：http://dali.dianchejie.cn/Article/details/gtsvqysuer.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yuanzhike.top/Article/details/gtwepbvbzo.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.birdmap.top/Article/details/gtsgtyhmph.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.birdmap.top/Article/details/gtakrjhybv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hnqzz.top/Article/details/gtotnulqev.html

Go:   slices.Index(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtnnnfmpvh.html

Ruby: arr.index(x)
来源：http://dali.gotoacloud.top/Article/details/gtkhgskgfs.html

C#:   list.IndexOf(x);
来源：http://dali.zhengqikj.top/Article/details/gtblqvbtmw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yueranfly.top/Article/details/gtxkndiqmh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ehwqpu.com/Article/details/gttomxzeoz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.mhx1999.top/Article/details/gtpfaimkxs.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gzhubu.top/Article/details/gtmqtooxtd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.pycfn.com/Article/details/gtrhxxqtly.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.vqdsnc.cn/Article/details/gtkdziriji.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.kuanghao11.cn/Article/details/gtaxujhpmx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.smart0.xyz/Article/details/gtzvqohkyw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtvvlwxxsk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.guowangkeji.top/Article/details/gtdnxgzctl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jyoumei.cn/Article/details/gtclvizwyw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.fengsongda.top/Article/details/gtlrahdpmu.html

JS:   arr.map(x => x * 2)
来源：http://dali.fzhhl.top/Article/details/gtbenjmiuc.html

TS:   arr.map(x => x * 2)
来源：http://dali.nanxuanxn.top/Article/details/gtfuvabkgu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hnqzz.top/Article/details/gtkjnuqquz.html

Go:   // 手写循环
来源：http://dali.daria6918.cn/Article/details/gtmkznnalm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yuxming.cn/Article/details/gtyposxvzl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cheryme.top/Article/details/gtiimuvujg.html

[D15] 去重
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnyoxnxej.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yonumen.top/Article/details/gtrcubeohu.html

PHP:  array_unique($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtscrfcgbf.html

JS:   [...new Set(arr)]
来源：http://dali.fzhhl.top/Article/details/gtnwmkmcvw.html

TS:   [...new Set(arr)]
来源：http://dali.zhixingplan.top/Article/details/gtfseskinu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gzhubu.top/Article/details/gtcozrfysk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhongyouzk.top/Article/details/gtxwgohsua.html

Ruby: arr.uniq
来源：http://dali.yueranfly.top/Article/details/gtjfnbawie.html

C#:   list.Distinct().ToList()
来源：http://dali.sxryk.cn/Article/details/gtftbxzwff.html

[D16] 求和与平均值
来源：http://dali.haohaochexian.top/Article/details/gtqxbiimkv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtxxoubjzr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.tianlin.xyz/Article/details/gtioqkffto.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gttjzuxwfc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtapsfvbdh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hnxiangtu.top/Article/details/gtitdzqymn.html

Go:   // 手写循环累加
来源：http://dali.guowangkeji.top/Article/details/gtijjhilpx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yuanzhike.top/Article/details/gtbfhtloah.html

C#:   list.Sum();  list.Average()
来源：http://dali.cqqwz.cn/Article/details/gtwynvdanj.html

[D17] 最大值与最小值
来源：http://dali.jqgufenzy.top/Article/details/gtggvcajqh.html

Py:   max(arr);  min(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtmmtozdmp.html

PHP:  max($arr);  min($arr);
来源：http://dali.yj20258.top/Article/details/gtafuocppl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jqgfzy.top/Article/details/gtggznfuwy.html

TS:   Math.max(...arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtpeioznes.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.andypj.xyz/Article/details/gtgrdblfaw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zycfv.cn/Article/details/gtitoxplqt.html

Ruby: arr.max;  arr.min
来源：http://dali.jinghuilouyu.cn/Article/details/gtuodxhnzl.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gtxzzolyvg.html

[D18] 扁平化嵌套数组
来源：http://dali.zhoulong.xyz/Article/details/gtfxihcggr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gtifpcbwdc.html

PHP:  array_merge(...$nested);
来源：http://dali.jinghuilouyu.cn/Article/details/gthiblqhye.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhiwuduotai.top/Article/details/gthwddyqcd.html

TS:   nested.flat();
来源：http://dali.bjfxy.top/Article/details/gthofdpuzu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jiagoushi.top/Article/details/gtpwmxbtqo.html

Go:   // 手写双层循环
来源：http://dali.zdqjudy.top/Article/details/gtikmgeqlt.html

Ruby: nested.flatten
来源：http://dali.fzhhl.top/Article/details/gtbshthbav.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.snrcjt.cn/Article/details/gtbepasujc.html

[D19] 按字段分组
来源：http://dali.sysykeji.top/Article/details/gtbzakjgvj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtjfauacnr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.iojbl.cn/Article/details/gtwzmkwedy.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.316326.xyz/Article/details/gthkifjwni.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.iojbl.cn/Article/details/gtmacbpuzc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xinyue.icu/Article/details/gtzshdtxrm.html

Go:   // 手写 map[string][]T
来源：http://dali.pengpengdd.cyou/Article/details/gtidxmuedc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yj20258.top/Article/details/gtalqnjdmb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.pengpengdd.cyou/Article/details/gtpwaadgjz.html

[D20] 统计每个元素出现次数
来源：http://dali.svipenyu.cn/Article/details/gtgjnmopeo.html

Py:   Counter(arr)
来源：http://dali.pycfn.com/Article/details/gtvlxnljdx.html

PHP:  array_count_values($arr);
来源：http://dali.yuanzhike.top/Article/details/gtydzbhawf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ppjwa.cn/Article/details/gtlsusyuqm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cheryme.top/Article/details/gtdkrkfyoo.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hnxiangtu.top/Article/details/gtngcskudj.html

Go:   // 手写 map[T]int
来源：http://dali.smart0.xyz/Article/details/gtgjzbdwly.html

Ruby: arr.tally
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtscpxmmzv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yueranfly.top/Article/details/gtmxyzxyir.html

[D21] 判断是否包含某元素
来源：http://dali.aizwys.cn/Article/details/gtbcmwkvbc.html

Py:   x in arr
来源：http://dali.jinqigfzy.top/Article/details/gtlivlaooe.html

PHP:  in_array($x, $arr, true);
来源：http://dali.havefunace.top/Article/details/gtzisbmozx.html

JS:   arr.includes(x)
来源：http://dali.zhixingplan.top/Article/details/gtcbqvkbpj.html

TS:   arr.includes(x)
来源：http://dali.sufxvd.cn/Article/details/gtnxuojhjl.html

Java: list.contains(x)
来源：http://dali.chenlongwang.top/Article/details/gtmdhulyek.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtctljjzwy.html

Ruby: arr.include?(x)
来源：http://dali.nwbrower.top/Article/details/gtxeoqiaxo.html

C#:   list.Contains(x)
来源：http://dali.cqqwz.cn/Article/details/gtvfyzxlep.html

[D22] 复制数组（避免共享引用）
来源：http://dali.feifeiyinyue.top/Article/details/gtoqhickdp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.redwolf501.top/Article/details/gtlarzwlxb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hongshengwenyu.top/Article/details/gtltdmzgbq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yuanzhike.top/Article/details/gtvyykwuff.html

TS:   [...arr];
来源：http://dali.zhongyouzk.top/Article/details/gthxszuzft.html

Java: new ArrayList<>(list);
来源：http://dali.bjfxy.top/Article/details/gtjnmhiheb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqalvxvqu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yvedp.cn/Article/details/gtclcarqtg.html

C#:   new List<int>(list);
来源：http://dali.smart0.xyz/Article/details/gthqldszns.html

[D23] reduce 累积计算
来源：http://dali.yongpay.top/Article/details/gtqsgmgbku.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtjglnzlns.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.aizwys.cn/Article/details/gtlkreppvj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gotoacloud.top/Article/details/gtbreqjhuz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxinkj.top/Article/details/gtfwmgwswk.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hongshengwenyu.top/Article/details/gtwonngree.html

Go:   // 手写循环
来源：http://dali.zhengqikj.top/Article/details/gtwqnublxi.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.nanxuanxn.top/Article/details/gtzkvhxqti.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.snrcjt.cn/Article/details/gtocnmdnth.html

[D24] 字典 / Map 基本操作
来源：http://dali.smart0.xyz/Article/details/gtfvaqtdhz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gzhubu.top/Article/details/gtbordnkfc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.wangshuangyany.cn/Article/details/gtwcgnnbko.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cashguo.top/Article/details/gtliuxrvpy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gtiorqjgry.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.wangshuangyany.cn/Article/details/gtoxqzseou.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.meibo888.top/Article/details/gtvucaawrz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gotoacloud.top/Article/details/gtabdciypj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.nanxuanxn.top/Article/details/gteymnxoal.html

[D25] Set 集合去重与交并差
来源：http://dali.jlsjyb.cn/Article/details/gtwoqiqlfk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.mhx1999.top/Article/details/gtuxturkqc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.haohaochexian.top/Article/details/gtbygdnpnx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.snrcjt.cn/Article/details/gtrfqsqigr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shzxlz.cn/Article/details/gtjskssybr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yangfankeji.com/Article/details/gtrjsfuzwh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hfpthk.cn/Article/details/gtvxyrhhjn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hammf.cn/Article/details/gtfwitjpcx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhixingplan.top/Article/details/gtwounpytw.html

[D26] 数组转字符串
来源：http://dali.jinqigfzy.top/Article/details/gtmtrdspfm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.smart0.xyz/Article/details/gtpnwetohm.html

PHP:  implode(", ", $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtjskidyvg.html

JS:   arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gtpudkqdxn.html

TS:   arr.join(", ")
来源：http://dali.snrcjt.cn/Article/details/gtbwcphqcs.html

Java: String.join(", ", list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmiyyqmgs.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhixingplan.top/Article/details/gtgraefgsx.html

Ruby: arr.join(", ")
来源：http://dali.andypj.xyz/Article/details/gtqcbsatcw.html

C#:   string.Join(", ", list)
来源：http://dali.0kj1m.cn/Article/details/gtuxkfumqh.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnuwnptvf.html

E. 字符串处理
来源：http://dali.ehwqpu.com/Article/details/gtwkakqbwt.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtxbkaxdwy.html

[E01] 拼接字符串
来源：http://dali.zhongyouzk.top/Article/details/gtcwnzdgvy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hnqzz.top/Article/details/gtdstblgem.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yuanzhike.top/Article/details/gtbwzndvtv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yongpay.top/Article/details/gtlkswckmt.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigfzy.top/Article/details/gtbbeyhtrr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfxawnkfv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhengqikj.top/Article/details/gtbbfufbpg.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hnxiangtu.top/Article/details/gthpyaawrf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvtpvhgeu.html

[E02] 重复字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtlowffzpg.html

Py:   "ab" * 3
来源：http://dali.jinqigufen.top/Article/details/gtiznhqvja.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jlsjyb.cn/Article/details/gtvhgcupry.html

JS:   "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gtryxblkwi.html

TS:   "ab".repeat(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpuywbgxu.html

Java: "ab".repeat(3)
来源：http://dali.xylfe.cn/Article/details/gtwtrybkvc.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthmkazacp.html

Ruby: "ab" * 3
来源：http://dali.fengsongda.top/Article/details/gtoukhoyyt.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.vqdsnc.cn/Article/details/gtmtazmcmj.html

[E03] 截取子串
来源：http://dali.ehwqpu.com/Article/details/gtlabmukzh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.guannengcc.top/Article/details/gtylesjqvb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yonumen.top/Article/details/gtwvzkgdiu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbkfpsgpq.html

TS:   s.slice(1, 4)
来源：http://dali.jqgufenzy.top/Article/details/gtfufuckno.html

Java: s.substring(1, 4)
来源：http://dali.zhoulong.xyz/Article/details/gtmeanjdzg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yonumen.top/Article/details/gtvyswrvpk.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.tanke756.top/Article/details/gtoddndsfk.html

C#:   s.Substring(1, 3)
来源：http://dali.daxiang520.top/Article/details/gtuwwasjvr.html

[E04] 查找子串位置
来源：http://dali.xuetiantiany.cn/Article/details/gtjdipewsh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ybcxt.top/Article/details/gtsndmhihb.html

PHP:  strpos($s, "x");
来源：http://dali.jlsjyb.cn/Article/details/gtpevssxth.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkhqqsscv.html

TS:   s.indexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmlnwfvgy.html

Java: s.indexOf("x")
来源：http://dali.zhiwuduotai.top/Article/details/gtredygsbw.html

Go:   strings.Index(s, "x")
来源：http://dali.kuanghao11.cn/Article/details/gtprasnwnx.html

Ruby: s.index("x")
来源：http://dali.pengpengdd.cyou/Article/details/gtmzsuuozz.html

C#:   s.IndexOf("x")
来源：http://dali.snrcjt.cn/Article/details/gtuvpbpjcn.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.guowangkeji.top/Article/details/gtoylohlmz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yuanzhike.top/Article/details/gtjigugksn.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jlsjyb.cn/Article/details/gttthgmwui.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigfzy.top/Article/details/gtjwmgypzx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hfpthk.cn/Article/details/gtyirmmyen.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yangfankeji.com/Article/details/gtxobxpzmj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.wangshuangyany.cn/Article/details/gtsehdggef.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hammf.cn/Article/details/gtlacvlyoi.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.wangdashe.top/Article/details/gtdumiorik.html

[E06] 替换子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmlcyjqxz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.bjfxy.top/Article/details/gtwsdtfyuq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hywenlv.cn/Article/details/gthkudtqlc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtmfqqdxnp.html

TS:   s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtosoweflz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gtpoykvbde.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cucudq.cn/Article/details/gttiqxalxg.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gttdnxcuvl.html

C#:   s.Replace("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtlysfaizu.html

[E07] 按分隔符拆分
来源：http://dali.jlsjyb.cn/Article/details/gtwlgiodsl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hammf.cn/Article/details/gtnpbpteqg.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtkmbaahnk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.wangshuangyany.cn/Article/details/gtbsqdfmvg.html

TS:   s.split(",")
来源：http://dali.nanxuanxn.top/Article/details/gtrgkzpyuw.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hfpthk.cn/Article/details/gtcsisxnhp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jiagoushi.top/Article/details/gtkouugvzs.html

Ruby: s.split(",");  s.split
来源：http://dali.zhengqikj.top/Article/details/gtcshdazaa.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yvedp.cn/Article/details/gtvidotlvf.html

[E08] 数组按分隔符合并
来源：http://dali.ydzc1.top/Article/details/gtzqbjxizl.html

Py:   ",".join(items)
来源：http://dali.yonumen.top/Article/details/gttwcbszqa.html

PHP:  implode(",", $items);
来源：http://dali.tanke756.top/Article/details/gtddgnhjga.html

JS:   items.join(",")
来源：http://dali.9152youxi.cn/Article/details/gtoueslmrp.html

TS:   items.join(",")
来源：http://dali.yuxming.cn/Article/details/gttextiigd.html

Java: String.join(",", items)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqdjwlaiz.html

Go:   strings.Join(items, ",")
来源：http://dali.zhiwuduotai.top/Article/details/gtncswwezp.html

Ruby: items.join(",")
来源：http://dali.chenzaomai.com/Article/details/gtkxrvfklc.html

C#:   string.Join(",", items)
来源：http://dali.daria6918.cn/Article/details/gtajlmawns.html

[E09] 去除所有空白字符
来源：http://dali.shanyushiyangtech.top/Article/details/gtwlnpmfir.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.9152youxi.cn/Article/details/gtuhfcfgau.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hfpthk.cn/Article/details/gttalxiatl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yongpay.top/Article/details/gtdvsfbixb.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hongshengwenyu.top/Article/details/gtkjijtqhb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sufxvd.cn/Article/details/gttpkuqdzz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shuidangran.top/Article/details/gtigedhfgs.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.kuanghao11.cn/Article/details/gtjmqbkaus.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.daria6918.cn/Article/details/gtztreenra.html

[E10] 左侧补零 / 定长填充
来源：http://dali.wangdashe.top/Article/details/gtzmsfcngj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ivvv.top/Article/details/gtsgxxgxmg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shangyingyoupin.top/Article/details/gtmxvvjrrc.html

JS:   "7".padStart(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gtblmnjsyl.html

TS:   "7".padStart(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gtvszmemcz.html

Java: String.format("%03d", 7)
来源：http://dali.gzhubu.top/Article/details/gtnnfsqxan.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gtcbeegcyu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jqgufenzy.top/Article/details/gtlhntslkd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhengqikj.top/Article/details/gtagqjjkwi.html

[E11] 反转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gthpdkjate.html

Py:   s[::-1]
来源：http://dali.zhongyouzk.top/Article/details/gtdetnuwhy.html

PHP:  strrev($s);
来源：http://dali.yj202588.top/Article/details/gthlrwlwzn.html

JS:   [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gtsxxvywhl.html

TS:   [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gtlcbrngwp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlyvsddnp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.daria6918.cn/Article/details/gtdytxtmfw.html

Ruby: s.reverse
来源：http://dali.xziqi.cn/Article/details/gtgcyhzlag.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ybcxt.top/Article/details/gtbuevmupi.html

[E12] 统计某字符出现次数
来源：http://dali.yanxiufei.cn/Article/details/gtiuknymua.html

Py:   s.count("a")
来源：http://dali.yueranfly.top/Article/details/gtrrktvivn.html

PHP:  substr_count($s, "a");
来源：http://dali.fzhhl.top/Article/details/gtyrfwdxjm.html

JS:   s.split("a").length - 1
来源：http://dali.aizwys.cn/Article/details/gtbqrclpap.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gtsbqgwdpu.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shanyushiyangtech.top/Article/details/gtlpmgjhhl.html

Go:   strings.Count(s, "a")
来源：http://dali.feifeiyinyue.top/Article/details/gtgoztdvrh.html

Ruby: s.count("a")
来源：http://dali.ybcxt.top/Article/details/gtcfnsmtej.html

C#:   s.Count(c => c == 'a')
来源：http://dali.chenzaomai.com/Article/details/gtegeumerq.html

[E13] 逐字符遍历
来源：http://dali.hfpthk.cn/Article/details/gtvleuvajq.html

Py:   for ch in s: print(ch)
来源：http://dali.svipenyu.cn/Article/details/gtshmgngmm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.dashuyun.cn/Article/details/gtvstxibvo.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gtploabmgn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gtmcippbbn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gtubjfvkcu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.haohaochexian.top/Article/details/gtbqxlyhkm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gzhubu.top/Article/details/gtofjwwwfl.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yuanzhike.top/Article/details/gtszqkeeum.html

[E14] URL 编码与 Base64
来源：http://dali.gogol.net.cn/Article/details/gtrhupulry.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqsmeztff.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jqgufenzy.top/Article/details/gtfqzythas.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hysaishi.cn/Article/details/gthnpnhuxx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.meibo888.top/Article/details/gtvnxvpysg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gtzvvkdiwa.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.wangshuangyany.cn/Article/details/gtgpnahatp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sweek.top/Article/details/gtnioxyjtl.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.havefunace.top/Article/details/gtjopncpte.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinghuilouyu.cn/Article/details/gtqslicftw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ybcxt.top/Article/details/gtbjughxrq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ydzc1.top/Article/details/gtqtlnuiut.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jqgfzy.top/Article/details/gtvyvswwff.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jqgfzy.top/Article/details/gtgbqrucma.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.daria6918.cn/Article/details/gtkgffwrmy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthzbpqpab.html


<!-- 参考信息 -->