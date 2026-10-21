代发 wailian999

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xinyue.icu/Article/details/gtqnyofzrk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jyoumei.cn/Article/details/gtckjawqbj.html

JS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjivzscej.html

TS:   arr.map(x => x * 2)
来源：http://dali.sufxvd.cn/Article/details/gtdiodjnzs.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.birdmap.top/Article/details/gtqnnwumdr.html

Go:   // 手写循环
来源：http://dali.guowangkeji.top/Article/details/gthylixgts.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.tianlin.xyz/Article/details/gthcsmbirp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtxedbdwev.html

[D15] 去重
来源：http://dali.shangyingyoupin.top/Article/details/gtsqdbkmac.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yueranfly.top/Article/details/gtswifwytr.html

PHP:  array_unique($arr);
来源：http://dali.sysykeji.top/Article/details/gtkcnuzprq.html

JS:   [...new Set(arr)]
来源：http://dali.guowangkeji.top/Article/details/gtghsuaith.html

TS:   [...new Set(arr)]
来源：http://dali.yvedp.cn/Article/details/gtothbefsp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jlsjyb.cn/Article/details/gtxfabltfe.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cashguo.top/Article/details/gtoweaihmn.html

Ruby: arr.uniq
来源：http://dali.yj202588.top/Article/details/gthbezvbmi.html

C#:   list.Distinct().ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtqiirtoah.html

[D16] 求和与平均值
来源：http://dali.jianghu66.top/Article/details/gtoctdrlay.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sufxvd.cn/Article/details/gtbsrxbiyd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.0kj1m.cn/Article/details/gtwkibkedi.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuanzhike.top/Article/details/gtqkyinhlq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.havefunace.top/Article/details/gtorydgypb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xinyue.icu/Article/details/gtogbrwety.html

Go:   // 手写循环累加
来源：http://dali.gaohongyu789.top/Article/details/gtdqdcxuow.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jqgfzy.top/Article/details/gtnhtpylbk.html

C#:   list.Sum();  list.Average()
来源：http://dali.gzhubu.top/Article/details/gtkqzoxxcg.html

[D17] 最大值与最小值
来源：http://dali.pengpengdd.cyou/Article/details/gtlmcbdoqo.html

Py:   max(arr);  min(arr)
来源：http://dali.0kj1m.cn/Article/details/gtcyohqvpr.html

PHP:  max($arr);  min($arr);
来源：http://dali.xylfe.cn/Article/details/gtenwqfrqg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yonumen.top/Article/details/gtciddciyt.html

TS:   Math.max(...arr);
来源：http://dali.ivvv.top/Article/details/gtxeddyrem.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhiwuduotai.top/Article/details/gtqeldhyzt.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shuidangran.top/Article/details/gtqyawhack.html

Ruby: arr.max;  arr.min
来源：http://dali.dianchejie.cn/Article/details/gtojvgqhjq.html

C#:   list.Max();  list.Min()
来源：http://dali.nwbrower.top/Article/details/gtjtbfhycy.html

[D18] 扁平化嵌套数组
来源：http://dali.aizwys.cn/Article/details/gtuzzuacdw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shanyushiyangtech.top/Article/details/gtvvsgspdi.html

PHP:  array_merge(...$nested);
来源：http://dali.9152youxi.cn/Article/details/gtohpbsnuv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ydzc1.top/Article/details/gtcfsreasp.html

TS:   nested.flat();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdggpbnfg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ehwqpu.com/Article/details/gtskvfzamz.html

Go:   // 手写双层循环
来源：http://dali.hnxiangtu.top/Article/details/gtdrgtakjd.html

Ruby: nested.flatten
来源：http://dali.sxryk.cn/Article/details/gtbohvvqti.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cheryme.top/Article/details/gtuotuwsvw.html

[D19] 按字段分组
来源：http://dali.quarkkingdee.top/Article/details/gtafownbyr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sysykeji.top/Article/details/gtcwtgrenw.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shanyushiyangtech.top/Article/details/gtchoflasq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sysykeji.top/Article/details/gtfdivneri.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yuxming.cn/Article/details/gtxwaocwby.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.havefunace.top/Article/details/gtejdsezwx.html

Go:   // 手写 map[string][]T
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvhbuliza.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hammf.cn/Article/details/gtnvijzkyc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ivvv.top/Article/details/gtnuwbzmuq.html

[D20] 统计每个元素出现次数
来源：http://dali.316326.xyz/Article/details/gtzdefdppl.html

Py:   Counter(arr)
来源：http://dali.shzxlz.cn/Article/details/gtqmzqjuhs.html

PHP:  array_count_values($arr);
来源：http://dali.nanxinkj.top/Article/details/gtyuhpsxfc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuetiantiany.cn/Article/details/gtxpuwfwvs.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guannengcc.top/Article/details/gtsmukmuvf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhiwuduotai.top/Article/details/gtjdxsasxg.html

Go:   // 手写 map[T]int
来源：http://dali.yanxiufei.cn/Article/details/gtqbvussbe.html

Ruby: arr.tally
来源：http://dali.zycfv.cn/Article/details/gtmthutnjb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ehwqpu.com/Article/details/gtgmwhqmfo.html

[D21] 判断是否包含某元素
来源：http://dali.cashguo.top/Article/details/gtixtrdfkt.html

Py:   x in arr
来源：http://dali.yuanzhike.top/Article/details/gtawmlqrll.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hywenlv.cn/Article/details/gtcfncijxk.html

JS:   arr.includes(x)
来源：http://dali.xylfe.cn/Article/details/gtzscsabmt.html

TS:   arr.includes(x)
来源：http://dali.andypj.xyz/Article/details/gtlwprwxkt.html

Java: list.contains(x)
来源：http://dali.yuanzhike.top/Article/details/gttoaxrueu.html

Go:   slices.Contains(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtgdhadoib.html

Ruby: arr.include?(x)
来源：http://dali.jiagoushi.top/Article/details/gtosrtgxno.html

C#:   list.Contains(x)
来源：http://dali.cheryme.top/Article/details/gtnfnveego.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xziqi.cn/Article/details/gtuecvocwf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtslwokkae.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ivvv.top/Article/details/gtcrylyuio.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtosfbcipy.html

TS:   [...arr];
来源：http://dali.jinghuilouyu.cn/Article/details/gtmoampbrz.html

Java: new ArrayList<>(list);
来源：http://dali.haohaochexian.top/Article/details/gtitbnqigb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.mhx1999.top/Article/details/gttfobufar.html

Ruby: arr.dup;  arr.clone
来源：http://dali.havefunace.top/Article/details/gtpknzmpil.html

C#:   new List<int>(list);
来源：http://dali.yj202588.top/Article/details/gtwwvsagjr.html

[D23] reduce 累积计算
来源：http://dali.jlsjyb.cn/Article/details/gtunmswowl.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.iojbl.cn/Article/details/gtwwwgkwdc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.vqdsnc.cn/Article/details/gtivkcjbpr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.pycfn.com/Article/details/gtbdmkwulr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yonumen.top/Article/details/gtpecitxen.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.kuanghao11.cn/Article/details/gtjfogrwyf.html

Go:   // 手写循环
来源：http://dali.xylfe.cn/Article/details/gtkykxrqvr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yuanzhike.top/Article/details/gtcsyjwong.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.dashuyun.cn/Article/details/gtqptbtuim.html

[D24] 字典 / Map 基本操作
来源：http://dali.ppjwa.cn/Article/details/gtgrglyjhi.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.aizwys.cn/Article/details/gtmlfxfzmj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ehwqpu.com/Article/details/gtiutjfkrd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.9152youxi.cn/Article/details/gtsbctdqej.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gtpscqeuky.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shanyushiyangtech.top/Article/details/gtweljwkwl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sweek.top/Article/details/gtnryxqdrg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.meibo888.top/Article/details/gtbcmmoqgo.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.feifeiyinyue.top/Article/details/gtilkfttuc.html

[D25] Set 集合去重与交并差
来源：http://dali.jiagoushi.top/Article/details/gtqzepzlvh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.316326.xyz/Article/details/gtwtvwlcxx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.svipenyu.cn/Article/details/gthsepanyp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtfxxjjluv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.andypj.xyz/Article/details/gtkvbkoklr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.c1oappe.top/Article/details/gtnhwlygoe.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tanke756.top/Article/details/gtggnhzfco.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtkicfrnqy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ivvv.top/Article/details/gtjyxrvaol.html

[D26] 数组转字符串
来源：http://dali.gaohongyu789.top/Article/details/gtqlyuemat.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yanxiufei.cn/Article/details/gtnlcwgshi.html

PHP:  implode(", ", $arr);
来源：http://dali.aizwys.cn/Article/details/gtxwojytdy.html

JS:   arr.join(", ")
来源：http://dali.jianghu66.top/Article/details/gtpypfltyc.html

TS:   arr.join(", ")
来源：http://dali.jiagoushi.top/Article/details/gtjftijnxh.html

Java: String.join(", ", list)
来源：http://dali.cdnleiting.top/Article/details/gtlbixwmrf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.fzhhl.top/Article/details/gtwjdfnxlf.html

Ruby: arr.join(", ")
来源：http://dali.yj202588.top/Article/details/gtdiwesltt.html

C#:   string.Join(", ", list)
来源：http://dali.dashuyun.cn/Article/details/gtdriaeaae.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtkrhfizob.html

E. 字符串处理
来源：http://dali.ivvv.top/Article/details/gtbxstozjy.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtoxdcubsa.html

[E01] 拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtgfbdsite.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sweek.top/Article/details/gtgdejnwzd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.snrcjt.cn/Article/details/gthgqiyqok.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.smart0.xyz/Article/details/gtyokbkwlt.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenzaomai.com/Article/details/gtwkjzbssz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hnxiangtu.top/Article/details/gtnjkcnbvs.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jianghu66.top/Article/details/gtcurobqgz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinqigfzy.top/Article/details/gthzjnkide.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtjubkpkgd.html

[E02] 重复字符串
来源：http://dali.sufxvd.cn/Article/details/gtosdxugij.html

Py:   "ab" * 3
来源：http://dali.chenjidiqi.icu/Article/details/gtjpnmoutv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhoulong.xyz/Article/details/gtkaqxkjhx.html

JS:   "ab".repeat(3)
来源：http://dali.wangdashe.top/Article/details/gtoqwuoxkb.html

TS:   "ab".repeat(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtiswlmgiy.html

Java: "ab".repeat(3)
来源：http://dali.316326.xyz/Article/details/gtzqaftqss.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yangfankeji.com/Article/details/gtrmuicvcw.html

Ruby: "ab" * 3
来源：http://dali.cqqwz.cn/Article/details/gtxaoftqvn.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.dianchejie.cn/Article/details/gtxbdlbomq.html

[E03] 截取子串
来源：http://dali.aizwys.cn/Article/details/gtqshainma.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shangyingyoupin.top/Article/details/gtdupyglfe.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gtrfmqdhyu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yj20258.top/Article/details/gteezitcus.html

TS:   s.slice(1, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gtfofecycj.html

Java: s.substring(1, 4)
来源：http://dali.daxiang520.top/Article/details/gtzqlfsxiu.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jinghuilouyu.cn/Article/details/gtpvbutady.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ybcxt.top/Article/details/gtirwtjkqv.html

C#:   s.Substring(1, 3)
来源：http://dali.9152youxi.cn/Article/details/gthrawvwyr.html

[E04] 查找子串位置
来源：http://dali.xuanzx.com/Article/details/gttrtqujih.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ybcxt.top/Article/details/gtmjecnlqk.html

PHP:  strpos($s, "x");
来源：http://dali.pycfn.com/Article/details/gtutudkrfb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ehwqpu.com/Article/details/gtfjggzgtb.html

TS:   s.indexOf("x")
来源：http://dali.aizwys.cn/Article/details/gtlucfmfiy.html

Java: s.indexOf("x")
来源：http://dali.guowangkeji.top/Article/details/gthsxvrvdg.html

Go:   strings.Index(s, "x")
来源：http://dali.ehwqpu.com/Article/details/gtpanoijzz.html

Ruby: s.index("x")
来源：http://dali.sufxvd.cn/Article/details/gtohyjufgn.html

C#:   s.IndexOf("x")
来源：http://dali.yvedp.cn/Article/details/gtjsdhnzro.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jiagoushi.top/Article/details/gtrbjhydsx.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yanxiufei.cn/Article/details/gtcwfyqqvg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.smart0.xyz/Article/details/gtytmccxox.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tianlin.xyz/Article/details/gtdbnybpvw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yuanzhike.top/Article/details/gtkeikrcdu.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.iojbl.cn/Article/details/gttvcszpqp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yuxming.cn/Article/details/gtpsarjyax.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.fengsongda.top/Article/details/gttnxtyeav.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jqgfzy.top/Article/details/gtnuuxkvig.html

[E06] 替换子串
来源：http://dali.xuanzx.com/Article/details/gtknfpffbj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.0kj1m.cn/Article/details/gtasvsatvq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sweek.top/Article/details/gtvzatuvnu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgzrezkld.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hammf.cn/Article/details/gttrnkfffs.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gtdogveomc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ehwqpu.com/Article/details/gtpzzeghpr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtitcmamfn.html

C#:   s.Replace("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtbudtljbo.html

[E07] 按分隔符拆分
来源：http://dali.havefunace.top/Article/details/gtrejtrldr.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ybcxt.top/Article/details/gthiulvvmn.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yj20258888.top/Article/details/gttjobbyzp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtifdddqfm.html

TS:   s.split(",")
来源：http://dali.yvedp.cn/Article/details/gtbdczeera.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.smart0.xyz/Article/details/gtdyyqbnuw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xuanzx.com/Article/details/gtyauotjnb.html

Ruby: s.split(",");  s.split
来源：http://dali.nwbrower.top/Article/details/gtqjlonbql.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jyoumei.cn/Article/details/gtlaagpnin.html

[E08] 数组按分隔符合并
来源：http://dali.zycfv.cn/Article/details/gtivdcodnb.html

Py:   ",".join(items)
来源：http://dali.iojbl.cn/Article/details/gtlukkpigf.html

PHP:  implode(",", $items);
来源：http://dali.c1oappe.top/Article/details/gtmfdjcgdh.html

JS:   items.join(",")
来源：http://dali.shuidangran.top/Article/details/gtgwfyujbb.html

TS:   items.join(",")
来源：http://dali.sxryk.cn/Article/details/gtyouwpwzt.html

Java: String.join(",", items)
来源：http://dali.gogol.net.cn/Article/details/gtithibrlj.html

Go:   strings.Join(items, ",")
来源：http://dali.hnqzz.top/Article/details/gtcafrbdzl.html

Ruby: items.join(",")
来源：http://dali.ydzc1.top/Article/details/gtaxgxtkdk.html

C#:   string.Join(",", items)
来源：http://dali.jqgufenzy.top/Article/details/gtzkzyzemu.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gtdnqfqxsq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.mhx1999.top/Article/details/gtdelalpua.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtogxoomae.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gtyoxsqwcq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tian-w.cn/Article/details/gtvhlewmws.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinqigufen.top/Article/details/gthndvqtjb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhoulong.xyz/Article/details/gtrjttmowr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hongshengwenyu.top/Article/details/gtkywzyhfr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hywenlv.cn/Article/details/gtaiylkach.html

[E10] 左侧补零 / 定长填充
来源：http://dali.vqdsnc.cn/Article/details/gtxoqegisk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gtiiurmahv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yj20258.top/Article/details/gtsbuifajn.html

JS:   "7".padStart(3, "0")
来源：http://dali.cheryme.top/Article/details/gtjdnkrljp.html

TS:   "7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gtwaybvfuy.html

Java: String.format("%03d", 7)
来源：http://dali.fengsongda.top/Article/details/gtfjgjzdmb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gtjdbbhbsf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yanxiufei.cn/Article/details/gtjqnooiov.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cqqwz.cn/Article/details/gtygzovupk.html

[E11] 反转字符串
来源：http://dali.xziqi.cn/Article/details/gtpptmhzqu.html

Py:   s[::-1]
来源：http://dali.yj20258.top/Article/details/gtbuoewyov.html

PHP:  strrev($s);
来源：http://dali.fzhhl.top/Article/details/gtqjzyokag.html

JS:   [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gtqicwukta.html

TS:   [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrrahkdum.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xylfe.cn/Article/details/gtkasxparp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.vqdsnc.cn/Article/details/gttjlqwsem.html

Ruby: s.reverse
来源：http://dali.fzhhl.top/Article/details/gtmpubqcpx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj20258888.top/Article/details/gtrggzykpu.html

[E12] 统计某字符出现次数
来源：http://dali.dianchejie.cn/Article/details/gtpkhqfufa.html

Py:   s.count("a")
来源：http://dali.zhiwuduotai.top/Article/details/gtmvvmeuma.html

PHP:  substr_count($s, "a");
来源：http://dali.jyoumei.cn/Article/details/gtgfwutdxk.html

JS:   s.split("a").length - 1
来源：http://dali.quarkkingdee.top/Article/details/gtymkggxmh.html

TS:   s.split("a").length - 1
来源：http://dali.shangyingyoupin.top/Article/details/gtdlgbvjpk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhixingplan.top/Article/details/gtufpnrwqd.html

Go:   strings.Count(s, "a")
来源：http://dali.nanxuanxn.top/Article/details/gtqhgdpowu.html

Ruby: s.count("a")
来源：http://dali.nanxinkj.top/Article/details/gtomfdaucw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.chenlongwang.top/Article/details/gtqzwilytx.html

[E13] 逐字符遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttxumstsi.html

Py:   for ch in s: print(ch)
来源：http://dali.ybcxt.top/Article/details/gttjhwaxkn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gtgkwirtnr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dashuyun.cn/Article/details/gtvydxpiun.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gotoacloud.top/Article/details/gtbmchvcuw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yangfankeji.com/Article/details/gticbkzipg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cashguo.top/Article/details/gtqmyynews.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sysykeji.top/Article/details/gtclhpnpxv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dianchejie.cn/Article/details/gteqazoeyx.html

[E14] URL 编码与 Base64
来源：http://dali.smart0.xyz/Article/details/gttowklgdq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtthajbrbz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhengqikj.top/Article/details/gtnujqohac.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jqgfzy.top/Article/details/gtmjhvlpmv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ydzc1.top/Article/details/gtmkjvadto.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gtajydrrkz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbbwgsoyb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zdqjudy.top/Article/details/gtkycyebcv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.pycfn.com/Article/details/gthblhjedu.html

[E15] HTML 转义 / 反转义
来源：http://dali.hfpthk.cn/Article/details/gtqflozpbk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zdqjudy.top/Article/details/gtyfrsffrw.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yanxiufei.cn/Article/details/gtcihixovs.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ppjwa.cn/Article/details/gtsbnrligi.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.pycfn.com/Article/details/gtwfkcvrjz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj20258888.top/Article/details/gtvglchvqx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.aibaodan.cn/Article/details/gteyizldqj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.0kj1m.cn/Article/details/gtirpnhngo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhoulong.xyz/Article/details/gtwqhaxqwn.html

[E16] 数字千分位
来源：http://dali.dianchejie.cn/Article/details/gtuobmgfid.html

Py:   f"{1234567:,}"
来源：http://dali.guowangkeji.top/Article/details/gtbqdfckwg.html

PHP:  number_format(1234567);
来源：http://dali.vqdsnc.cn/Article/details/gtmtfdeuak.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnqzz.top/Article/details/gtmkcfpszr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhongyouzk.top/Article/details/gtkxfsambj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.guowangkeji.top/Article/details/gthxjafbwy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.wangdashe.top/Article/details/gtfroxilds.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.meibo888.top/Article/details/gtcrdfzmqv.html

C#:   1234567.ToString("N0")
来源：http://dali.cdnleiting.top/Article/details/gtfpiekugq.html

[E17] 首字母大写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjbkoqqqn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xinyue.icu/Article/details/gtekpmsdgr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.havefunace.top/Article/details/gthaxfjjeu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.aizwys.cn/Article/details/gtigochdvg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hfpthk.cn/Article/details/gtmyoatewn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yuanzhike.top/Article/details/gtbsiufgkq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhoulong.xyz/Article/details/gtknkulbck.html

Ruby: s.capitalize
来源：http://dali.cdnleiting.top/Article/details/gtcysszogf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.snrcjt.cn/Article/details/gtijvvcfxt.html

[E18] 模板占位符替换
来源：http://dali.meibo888.top/Article/details/gtelxuimsd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zdqjudy.top/Article/details/gtyczcrdet.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xinyue.icu/Article/details/gtzvxvxczm.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzksofjtt.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gtxkotdldw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gtbypxlwdr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yj202588.top/Article/details/gtgyaytzsr.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cqqwz.cn/Article/details/gtxgrdlwbf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yj20258888.top/Article/details/gttqhfbsyw.html

[E19] 多行文本按行拆分
来源：http://dali.yj20258.top/Article/details/gtektqixmh.html

Py:   s.splitlines()
来源：http://dali.gzhubu.top/Article/details/gtwineuahg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cdnleiting.top/Article/details/gteablisae.html

JS:   s.split(/\r?\n/)
来源：http://dali.yangfankeji.com/Article/details/gtzxmokabm.html

TS:   s.split(/\r?\n/)
来源：http://dali.xylfe.cn/Article/details/gteeaakxtn.html

Java: s.lines().toList()
来源：http://dali.yj20258.top/Article/details/gtperwxkav.html

Go:   strings.Split(s, "\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttqvmlkwr.html

Ruby: s.lines
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfggtrvnv.html

C#:   s.Split('\n')
来源：http://dali.kuanghao11.cn/Article/details/gtkekkzvom.html

[E20] 判断字符串是否为空
来源：http://dali.meibo888.top/Article/details/gtrdzoooup.html

Py:   if not s:
来源：http://dali.xinyue.icu/Article/details/gtunpnrgna.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.feifeiyinyue.top/Article/details/gtkuawunpj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shuidangran.top/Article/details/gteggqmsah.html

TS:   if (s === "") {}
来源：http://dali.aizwys.cn/Article/details/gteyatmkng.html

Java: if (s.isEmpty()) {}
来源：http://dali.ybcxt.top/Article/details/gtezkwcwvp.html

Go:   if s == "" {}
来源：http://dali.nanxinkj.top/Article/details/gttacogdlj.html

Ruby: if s.empty?
来源：http://dali.xylfe.cn/Article/details/gtysfpqviq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yueranfly.top/Article/details/gtpnugagxw.html

[E21] 超长截断加省略号
来源：http://dali.xuetiantiany.cn/Article/details/gtsftrfqen.html


<!-- 参考信息 -->