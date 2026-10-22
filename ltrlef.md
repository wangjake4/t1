代发 wailian999

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cqqwz.cn/Article/details/gtoqhjazth.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gaohongyu789.top/Article/details/gtdpyhgstg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ppjwa.cn/Article/details/gtaiofcpjy.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.tianlin.xyz/Article/details/gtxdhwfkbv.html

[D11] 反转数组
来源：http://dali.daria6918.cn/Article/details/gtuqgsdkad.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinqigfzy.top/Article/details/gtikzvvywz.html

PHP:  array_reverse($arr);
来源：http://dali.cucudq.cn/Article/details/gtzzmnwrnm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hongshengwenyu.top/Article/details/gtzrwfaxcp.html

TS:   [...arr].reverse();
来源：http://dali.daxiang520.top/Article/details/gtybsmcggb.html

Java: Collections.reverse(list);
来源：http://dali.gogol.net.cn/Article/details/gtvfprrrkj.html

Go:   slices.Reverse(arr)
来源：http://dali.cashguo.top/Article/details/gtbaluhetp.html

Ruby: arr.reverse
来源：http://dali.shuidangran.top/Article/details/gtakktknes.html

C#:   list.Reverse();
来源：http://dali.shuidangran.top/Article/details/gthpbnxbdm.html

[D12] 查找元素下标
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtosaprxjk.html

Py:   arr.index(x);  x in arr
来源：http://dali.nanxinkj.top/Article/details/gtdnjqyoii.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jlsjyb.cn/Article/details/gtbbkkbamm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ehwqpu.com/Article/details/gtxvcvgzgw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xinyue.icu/Article/details/gtfgzfxizh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xuanzx.com/Article/details/gtamdotlpk.html

Go:   slices.Index(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtayuctcwq.html

Ruby: arr.index(x)
来源：http://dali.gzhubu.top/Article/details/gtuapcjcrv.html

C#:   list.IndexOf(x);
来源：http://dali.guannengcc.top/Article/details/gtzipifnbw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.aibaodan.cn/Article/details/gtntcylibg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.kuanghao11.cn/Article/details/gtedsaqkpw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yuxming.cn/Article/details/gtlgcnnilw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.redwolf501.top/Article/details/gtghsafikd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.guowangkeji.top/Article/details/gtfkgqswbg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.aizwys.cn/Article/details/gtyrhpixmi.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hnxiangtu.top/Article/details/gtijhwtklp.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.wangdashe.top/Article/details/gtodvrlitz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtwbmyscan.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sxryk.cn/Article/details/gtgzklbdln.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hnxiangtu.top/Article/details/gtmsjhlwbh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.aizwys.cn/Article/details/gthnmrgkmc.html

JS:   arr.map(x => x * 2)
来源：http://dali.cheryme.top/Article/details/gtlxsquwzb.html

TS:   arr.map(x => x * 2)
来源：http://dali.snrcjt.cn/Article/details/gtrbvxyaej.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.meibo888.top/Article/details/gtzmwkyatt.html

Go:   // 手写循环
来源：http://dali.tian-w.cn/Article/details/gtfdmpwohn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yuanzhike.top/Article/details/gtmjbhjmbf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xziqi.cn/Article/details/gtedpulizh.html

[D15] 去重
来源：http://dali.sweek.top/Article/details/gtzijznnkm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xuetiantiany.cn/Article/details/gtickledhd.html

PHP:  array_unique($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtubaemszs.html

JS:   [...new Set(arr)]
来源：http://dali.zhongyouzk.top/Article/details/gtkkzrcpsg.html

TS:   [...new Set(arr)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpbhthnta.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cheryme.top/Article/details/gtylyxdolo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.mhx1999.top/Article/details/gtzbvtfocm.html

Ruby: arr.uniq
来源：http://dali.yvedp.cn/Article/details/gtiaqtmsoq.html

C#:   list.Distinct().ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gttetdufoo.html

[D16] 求和与平均值
来源：http://dali.quarkkingdee.top/Article/details/gtcyugxhmf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.c1oappe.top/Article/details/gtiffuurak.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.daria6918.cn/Article/details/gtczeclxhf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuxming.cn/Article/details/gtblxdrfkw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.svipenyu.cn/Article/details/gtktnnkvnf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hnqzz.top/Article/details/gthtynafqw.html

Go:   // 手写循环累加
来源：http://dali.jinghuilouyu.cn/Article/details/gteriajoxh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xuanzx.com/Article/details/gtquehpxsh.html

C#:   list.Sum();  list.Average()
来源：http://dali.kuanghao11.cn/Article/details/gtenwuizln.html

[D17] 最大值与最小值
来源：http://dali.chenlongwang.top/Article/details/gtzsriwmcq.html

Py:   max(arr);  min(arr)
来源：http://dali.nanxinkj.top/Article/details/gtjflycbfg.html

PHP:  max($arr);  min($arr);
来源：http://dali.zycfv.cn/Article/details/gtacmyqvdf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.havefunace.top/Article/details/gtkvsxyhpr.html

TS:   Math.max(...arr);
来源：http://dali.daria6918.cn/Article/details/gtnlfmduzx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ybcxt.top/Article/details/gteeiwqegs.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ppjwa.cn/Article/details/gtqjcxlrpw.html

Ruby: arr.max;  arr.min
来源：http://dali.xylfe.cn/Article/details/gtzoifebhk.html

C#:   list.Max();  list.Min()
来源：http://dali.guowangkeji.top/Article/details/gtwjpnoife.html

[D18] 扁平化嵌套数组
来源：http://dali.hfpthk.cn/Article/details/gtpoivvtla.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cqqwz.cn/Article/details/gtiqkbaqqj.html

PHP:  array_merge(...$nested);
来源：http://dali.ydzc1.top/Article/details/gtmudxleqb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.meibo888.top/Article/details/gtfmndasmv.html

TS:   nested.flat();
来源：http://dali.guowangkeji.top/Article/details/gtfllmefqx.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.guannengcc.top/Article/details/gtugvmjszo.html

Go:   // 手写双层循环
来源：http://dali.dianchejie.cn/Article/details/gtlkbkfydr.html

Ruby: nested.flatten
来源：http://dali.jyoumei.cn/Article/details/gtugqlkmpt.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.havefunace.top/Article/details/gtefgwpzhj.html

[D19] 按字段分组
来源：http://dali.yj202588.top/Article/details/gtjhkdsgld.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jyoumei.cn/Article/details/gtzhygnink.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtatkdgbdq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.tian-w.cn/Article/details/gttdsgfita.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.guannengcc.top/Article/details/gtrpbgpsdv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shangyingyoupin.top/Article/details/gtrbozzull.html

Go:   // 手写 map[string][]T
来源：http://dali.yangfankeji.com/Article/details/gtwyskfnhg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gtmeozxoog.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.meibo888.top/Article/details/gtgsvggngz.html

[D20] 统计每个元素出现次数
来源：http://dali.andypj.xyz/Article/details/gtmricfbgt.html

Py:   Counter(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtnijqbxpw.html

PHP:  array_count_values($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtbqabnthp.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jiagoushi.top/Article/details/gtukafqeav.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xziqi.cn/Article/details/gthvzfnuem.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xuanzx.com/Article/details/gtfyozymcn.html

Go:   // 手写 map[T]int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjjomqssv.html

Ruby: arr.tally
来源：http://dali.andypj.xyz/Article/details/gtrabpxouk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sxryk.cn/Article/details/gtaavofxde.html

[D21] 判断是否包含某元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtebslkhzk.html

Py:   x in arr
来源：http://dali.sysykeji.top/Article/details/gtwbjefpbf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cqqwz.cn/Article/details/gtboorzxoz.html

JS:   arr.includes(x)
来源：http://dali.dianchejie.cn/Article/details/gtxrbjnixq.html

TS:   arr.includes(x)
来源：http://dali.chenlongwang.top/Article/details/gthxtibjbu.html

Java: list.contains(x)
来源：http://dali.xinyue.icu/Article/details/gtfobszdvz.html

Go:   slices.Contains(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtlzwmchqt.html

Ruby: arr.include?(x)
来源：http://dali.c1oappe.top/Article/details/gtfaunhtoz.html

C#:   list.Contains(x)
来源：http://dali.hammf.cn/Article/details/gtceemohsl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.nanxuanxn.top/Article/details/gtzfgkcjqn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinqigufen.top/Article/details/gteewvugke.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jyoumei.cn/Article/details/gtnfmgfmin.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.meibo888.top/Article/details/gtuuuakcpz.html

TS:   [...arr];
来源：http://dali.ybcxt.top/Article/details/gtowhvewuw.html

Java: new ArrayList<>(list);
来源：http://dali.xylfe.cn/Article/details/gtnyzeovhw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinqigufen.top/Article/details/gtxjcrcach.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sufxvd.cn/Article/details/gtpqpxwegu.html

C#:   new List<int>(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttoivlvzo.html

[D23] reduce 累积计算
来源：http://dali.jqgfzy.top/Article/details/gtigqqgydf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xuanzx.com/Article/details/gttpbuwsat.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yuxming.cn/Article/details/gtccgtorfo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hfpthk.cn/Article/details/gtmdubycgz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yueranfly.top/Article/details/gtlwnccnsw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ydzc1.top/Article/details/gtbghmxydy.html

Go:   // 手写循环
来源：http://dali.andypj.xyz/Article/details/gticqbrzzb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjkchbcuj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.nanxinkj.top/Article/details/gtoqsnxdmz.html

[D24] 字典 / Map 基本操作
来源：http://dali.yvedp.cn/Article/details/gtpiucwbxb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xylfe.cn/Article/details/gttgcrstgd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tanke756.top/Article/details/gtrfcjizea.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.nwbrower.top/Article/details/gtlfcjhnyj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtasltnarf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yuxming.cn/Article/details/gtequvhkrt.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jqgufenzy.top/Article/details/gtgkfpdgrf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.wangshuangyany.cn/Article/details/gtzopenboc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ybcxt.top/Article/details/gtitqchzbz.html

[D25] Set 集合去重与交并差
来源：http://dali.jqgfzy.top/Article/details/gtmoskprqd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hywenlv.cn/Article/details/gtbkgcwflu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gzhubu.top/Article/details/gtjwkhplyw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.nanxuanxn.top/Article/details/gttawrzfsz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhixingplan.top/Article/details/gtcqxegbyo.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zdqjudy.top/Article/details/gtwyotrkga.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shzxlz.cn/Article/details/gtfftihhdv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.9152youxi.cn/Article/details/gtqtclsmeg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yueranfly.top/Article/details/gthffubvye.html

[D26] 数组转字符串
来源：http://dali.smart0.xyz/Article/details/gtcndinlmn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinqigfzy.top/Article/details/gtblvfgrvw.html

PHP:  implode(", ", $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnbplmrby.html

JS:   arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gtiwsrdkmi.html

TS:   arr.join(", ")
来源：http://dali.chenlongwang.top/Article/details/gthsfmktiu.html

Java: String.join(", ", list)
来源：http://dali.gaohongyu789.top/Article/details/gtsagtajrs.html

Go:   strings.Join(strs, ", ")
来源：http://dali.smart0.xyz/Article/details/gtjvpknoag.html

Ruby: arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gtpsaqwadu.html

C#:   string.Join(", ", list)
来源：http://dali.hongshengwenyu.top/Article/details/gtycoixrxz.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtolxcdkmq.html

E. 字符串处理
来源：http://dali.zhixingplan.top/Article/details/gtzmgmdbqo.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtmaxptkdu.html

[E01] 拼接字符串
来源：http://dali.yuanzhike.top/Article/details/gtddkksmpu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmttckda.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.pengpengdd.cyou/Article/details/gtyifkyipf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dashuyun.cn/Article/details/gtkcarnnwc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jqgfzy.top/Article/details/gthjfmkrpx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xuetiantiany.cn/Article/details/gtvwvggzzd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.aizwys.cn/Article/details/gtlrizlbqe.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jqgufenzy.top/Article/details/gtjhsbwoyk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gtbnnihxjj.html

[E02] 重复字符串
来源：http://dali.316326.xyz/Article/details/gtbmbcgnnt.html

Py:   "ab" * 3
来源：http://dali.9152youxi.cn/Article/details/gtfxwwnoee.html

PHP:  str_repeat("ab", 3);
来源：http://dali.c1oappe.top/Article/details/gtdbjfedcv.html

JS:   "ab".repeat(3)
来源：http://dali.ppjwa.cn/Article/details/gtrgljkmku.html

TS:   "ab".repeat(3)
来源：http://dali.tian-w.cn/Article/details/gtrqmfgkdd.html

Java: "ab".repeat(3)
来源：http://dali.hysaishi.cn/Article/details/gtnrpxrvio.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gzhubu.top/Article/details/gtltplrabj.html

Ruby: "ab" * 3
来源：http://dali.cashguo.top/Article/details/gtzxxcxxvl.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.smart0.xyz/Article/details/gtbincyzmi.html

[E03] 截取子串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwdmielkn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jqgfzy.top/Article/details/gtlcuhitbq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gtjmuwjvci.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.smart0.xyz/Article/details/gtvakgdgug.html

TS:   s.slice(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gtthlemgbq.html

Java: s.substring(1, 4)
来源：http://dali.xylfe.cn/Article/details/gtovnkrblj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hywenlv.cn/Article/details/gtsjceykqv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zycfv.cn/Article/details/gtqmuoelqm.html

C#:   s.Substring(1, 3)
来源：http://dali.jlsjyb.cn/Article/details/gtgfqnwfkj.html

[E04] 查找子串位置
来源：http://dali.ehwqpu.com/Article/details/gtixgbaylh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.pengpengdd.cyou/Article/details/gtqategiqk.html

PHP:  strpos($s, "x");
来源：http://dali.zhongyouzk.top/Article/details/gtnkyovzda.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.dianchejie.cn/Article/details/gtgouxxotc.html

TS:   s.indexOf("x")
来源：http://dali.hywenlv.cn/Article/details/gtvxitdrhg.html

Java: s.indexOf("x")
来源：http://dali.daria6918.cn/Article/details/gtpxxpbfjz.html

Go:   strings.Index(s, "x")
来源：http://dali.hongshengwenyu.top/Article/details/gthsxwtrjh.html

Ruby: s.index("x")
来源：http://dali.guowangkeji.top/Article/details/gtgbxvwymr.html

C#:   s.IndexOf("x")
来源：http://dali.ivvv.top/Article/details/gtvftkiaom.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.smart0.xyz/Article/details/gtshqxgutk.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yuxming.cn/Article/details/gtpwjhjhgl.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shuidangran.top/Article/details/gtrtzqvttq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj202588.top/Article/details/gteennsavr.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jyoumei.cn/Article/details/gthqadbnqn.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gtlgvaxmyc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xuetiantiany.cn/Article/details/gtztchlydy.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ybcxt.top/Article/details/gtvdupmzxf.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.chenlongwang.top/Article/details/gteewyenqz.html

[E06] 替换子串
来源：http://dali.yvedp.cn/Article/details/gtrkbxnzqn.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtenosmevh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ivvv.top/Article/details/gtgdrqwvla.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtxzhorvps.html

TS:   s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gtmvsvtqtu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gttcierirc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yonumen.top/Article/details/gtmooamqcx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtnwlrtftj.html

C#:   s.Replace("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gtqgcygwpq.html

[E07] 按分隔符拆分
来源：http://dali.ivvv.top/Article/details/gtkelzzoup.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.daxiang520.top/Article/details/gtuovexahy.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yuanzhike.top/Article/details/gtrbccfycb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hongshengwenyu.top/Article/details/gtscstgsuo.html

TS:   s.split(",")
来源：http://dali.chenlongwang.top/Article/details/gtnryhqdik.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jqgufenzy.top/Article/details/gtiytkyrki.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.guowangkeji.top/Article/details/gtaqqhgdmr.html

Ruby: s.split(",");  s.split
来源：http://dali.nwbrower.top/Article/details/gtcvtlklvk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.0kj1m.cn/Article/details/gthicvucbi.html

[E08] 数组按分隔符合并
来源：http://dali.yonumen.top/Article/details/gtoalrspzh.html

Py:   ",".join(items)
来源：http://dali.zhoulong.xyz/Article/details/gtxzlxvnxz.html

PHP:  implode(",", $items);
来源：http://dali.nanxinkj.top/Article/details/gthkwzyoun.html

JS:   items.join(",")
来源：http://dali.fengsongda.top/Article/details/gtbocsgeuc.html

TS:   items.join(",")
来源：http://dali.pycfn.com/Article/details/gtgpfitvdt.html

Java: String.join(",", items)
来源：http://dali.guowangkeji.top/Article/details/gtrtmojaih.html

Go:   strings.Join(items, ",")
来源：http://dali.yj20258.top/Article/details/gtwngkhibr.html

Ruby: items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gtnwrwyvkk.html

C#:   string.Join(",", items)
来源：http://dali.hammf.cn/Article/details/gtyfgflgzc.html

[E09] 去除所有空白字符
来源：http://dali.cucudq.cn/Article/details/gthcyzlfyi.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sysykeji.top/Article/details/gtildbexsx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.aibaodan.cn/Article/details/gtevpdjemw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdfdpawxo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.daxiang520.top/Article/details/gtgydzjzor.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.daxiang520.top/Article/details/gtzbkqdaqg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.nanxuanxn.top/Article/details/gtwaqgvrfu.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.316326.xyz/Article/details/gtjxxjwzaa.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gotoacloud.top/Article/details/gtailfomgy.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhaomingkeji.xyz/Article/details/gteslskxzv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gtaidnftdv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhixingplan.top/Article/details/gtdefvtghf.html

JS:   "7".padStart(3, "0")
来源：http://dali.zdqjudy.top/Article/details/gtvltjvbxu.html

TS:   "7".padStart(3, "0")
来源：http://dali.ivvv.top/Article/details/gtxkxycfos.html

Java: String.format("%03d", 7)
来源：http://dali.xuanzx.com/Article/details/gtpxltxjdw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.daxiang520.top/Article/details/gthvpdqtcs.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.aizwys.cn/Article/details/gtbxjlpsas.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gotoacloud.top/Article/details/gtlonimqzv.html

[E11] 反转字符串
来源：http://dali.jinqigufen.top/Article/details/gtayepeovn.html

Py:   s[::-1]
来源：http://dali.cucudq.cn/Article/details/gtpycvmbwy.html

PHP:  strrev($s);
来源：http://dali.hnxiangtu.top/Article/details/gtotghkoof.html

JS:   [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbdfodvhv.html

TS:   [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gtjtlvhjgg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zycfv.cn/Article/details/gtwfvejuyf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.fzhhl.top/Article/details/gtwakswxod.html

Ruby: s.reverse
来源：http://dali.guowangkeji.top/Article/details/gtjmoscwdl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cucudq.cn/Article/details/gtfjassmyn.html

[E12] 统计某字符出现次数
来源：http://dali.aibaodan.cn/Article/details/gtpyduspdq.html

Py:   s.count("a")
来源：http://dali.hywenlv.cn/Article/details/gthcuuaeww.html

PHP:  substr_count($s, "a");
来源：http://dali.zhengqikj.top/Article/details/gtfkpdfjgw.html

JS:   s.split("a").length - 1
来源：http://dali.hongshengwenyu.top/Article/details/gtkrargefg.html

TS:   s.split("a").length - 1
来源：http://dali.gogol.net.cn/Article/details/gtmutozqxn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.aibaodan.cn/Article/details/gtjikufkey.html

Go:   strings.Count(s, "a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtarewgeex.html

Ruby: s.count("a")
来源：http://dali.zhiwuduotai.top/Article/details/gtheeevmsq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xuanzx.com/Article/details/gtezedbxkh.html

[E13] 逐字符遍历
来源：http://dali.xylfe.cn/Article/details/gtpahcuqzp.html

Py:   for ch in s: print(ch)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvnexkis.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhongyouzk.top/Article/details/gtiwcjwjpq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtdoqsgidh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guowangkeji.top/Article/details/gtcpjvpyxb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gtkgxgewhw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.pycfn.com/Article/details/gtywlyjjea.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jianghu66.top/Article/details/gtjttxmhel.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cqqwz.cn/Article/details/gtdqhlwyrf.html

[E14] URL 编码与 Base64
来源：http://dali.smart0.xyz/Article/details/gtwktwadlw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.daxiang520.top/Article/details/gtgeslktjr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.sweek.top/Article/details/gtlintsuqj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ybcxt.top/Article/details/gtezypchgz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.meibo888.top/Article/details/gtimklfgzx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.316326.xyz/Article/details/gtmeuhkztu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ybcxt.top/Article/details/gtiqybrcvg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xuanzx.com/Article/details/gtrsalhrzx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.0kj1m.cn/Article/details/gtzhixtncn.html

[E15] HTML 转义 / 反转义
来源：http://dali.sufxvd.cn/Article/details/gtnmztwgrn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtsbfelqfv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtqswptvuj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuunepywo.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.tanke756.top/Article/details/gtkfbqnukg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhengqikj.top/Article/details/gtqgatmkxv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hammf.cn/Article/details/gtjrajxdlc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.chenzaomai.com/Article/details/gtfxutgseq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.dianchejie.cn/Article/details/gtamscrpdk.html

[E16] 数字千分位
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuoubmxwh.html

Py:   f"{1234567:,}"
来源：http://dali.cqqwz.cn/Article/details/gtlfxdzovm.html

PHP:  number_format(1234567);
来源：http://dali.zdqjudy.top/Article/details/gtmznapuxh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.bjfxy.top/Article/details/gtmvozzncp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrxymeubd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvrckeqcb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sufxvd.cn/Article/details/gtddkvoqqc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.wangshuangyany.cn/Article/details/gtzduwutbw.html

C#:   1234567.ToString("N0")
来源：http://dali.ivvv.top/Article/details/gtaopwobrj.html

[E17] 首字母大写
来源：http://dali.hammf.cn/Article/details/gtiouuvxfh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.316326.xyz/Article/details/gtutbkwjrs.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnfvisbog.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sweek.top/Article/details/gtwaxqhcfb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfdreaduo.html


<!-- 参考信息 -->