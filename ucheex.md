代发 wailian999

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gtrflottip.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.nwbrower.top/Article/details/gthyjwasld.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrxcgguhr.html

TS:   arr.map(x => x * 2)
来源：http://dali.9152youxi.cn/Article/details/gtjbbfjmpe.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtppikmjsp.html

Go:   // 手写循环
来源：http://dali.yj202588.top/Article/details/gtgehnxnnk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrukytrrz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cqqwz.cn/Article/details/gtqvaawywk.html

[D15] 去重
来源：http://dali.daria6918.cn/Article/details/gtbwsiekvm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.bjfxy.top/Article/details/gtkrgwtqmh.html

PHP:  array_unique($arr);
来源：http://dali.gzhubu.top/Article/details/gtxanmwpua.html

JS:   [...new Set(arr)]
来源：http://dali.ydzc1.top/Article/details/gtbxkwnsew.html

TS:   [...new Set(arr)]
来源：http://dali.birdmap.top/Article/details/gtlgrftlbg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jiagoushi.top/Article/details/gthuxtjclp.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.snrcjt.cn/Article/details/gtubxhihaf.html

Ruby: arr.uniq
来源：http://dali.yvedp.cn/Article/details/gtmpgokwep.html

C#:   list.Distinct().ToList()
来源：http://dali.jianghu66.top/Article/details/gtlmlzdvfg.html

[D16] 求和与平均值
来源：http://dali.daxiang520.top/Article/details/gtvmxwiftr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sysykeji.top/Article/details/gtahtpjwmp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhengqikj.top/Article/details/gtkprxkixw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttdigmvcf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ivvv.top/Article/details/gthrcbtwed.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.vqdsnc.cn/Article/details/gtaywkeffy.html

Go:   // 手写循环累加
来源：http://dali.pengpengdd.cyou/Article/details/gtbrgujbav.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yueranfly.top/Article/details/gtocisyqtt.html

C#:   list.Sum();  list.Average()
来源：http://dali.sxryk.cn/Article/details/gtdhipgydn.html

[D17] 最大值与最小值
来源：http://dali.zycfv.cn/Article/details/gtghqzjjkf.html

Py:   max(arr);  min(arr)
来源：http://dali.aizwys.cn/Article/details/gtvrbctjko.html

PHP:  max($arr);  min($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtqseovzkw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shuidangran.top/Article/details/gtgtcxylzp.html

TS:   Math.max(...arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtefswnnoj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.redwolf501.top/Article/details/gtyfjxhrdl.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.tian-w.cn/Article/details/gtpghvuvlk.html

Ruby: arr.max;  arr.min
来源：http://dali.hywenlv.cn/Article/details/gtjbwxyijb.html

C#:   list.Max();  list.Min()
来源：http://dali.ydzc1.top/Article/details/gtmzhhqtsf.html

[D18] 扁平化嵌套数组
来源：http://dali.dashuyun.cn/Article/details/gtodaecxwg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xuetiantiany.cn/Article/details/gtxzlkarfv.html

PHP:  array_merge(...$nested);
来源：http://dali.hnqzz.top/Article/details/gtducayxlw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hongshengwenyu.top/Article/details/gtfmtxwqjx.html

TS:   nested.flat();
来源：http://dali.kuanghao11.cn/Article/details/gtimmxppsn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.mhx1999.top/Article/details/gtxjwvrqko.html

Go:   // 手写双层循环
来源：http://dali.yuanzhike.top/Article/details/gtluxhwfxj.html

Ruby: nested.flatten
来源：http://dali.jyoumei.cn/Article/details/gtgmpeczhw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ehwqpu.com/Article/details/gtnlsfnzlj.html

[D19] 按字段分组
来源：http://dali.snrcjt.cn/Article/details/gtovmwiwxj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shuidangran.top/Article/details/gteghlxupm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.9152youxi.cn/Article/details/gthnrojrzr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hfpthk.cn/Article/details/gtgcvxicxi.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gtvazgzdfo.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jqgufenzy.top/Article/details/gthmlimygq.html

Go:   // 手写 map[string][]T
来源：http://dali.316326.xyz/Article/details/gtyzpwliih.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinqigufen.top/Article/details/gtdiolirch.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.pycfn.com/Article/details/gtaijyxmja.html

[D20] 统计每个元素出现次数
来源：http://dali.iojbl.cn/Article/details/gtnuvigqmr.html

Py:   Counter(arr)
来源：http://dali.tanke756.top/Article/details/gtdlxhhwii.html

PHP:  array_count_values($arr);
来源：http://dali.xylfe.cn/Article/details/gtbkmrzjfr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhoulong.xyz/Article/details/gtrzuojhlm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ybcxt.top/Article/details/gtdvamriko.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sufxvd.cn/Article/details/gtnkbhazdu.html

Go:   // 手写 map[T]int
来源：http://dali.zhiwuduotai.top/Article/details/gtunpfbeko.html

Ruby: arr.tally
来源：http://dali.jyoumei.cn/Article/details/gttpsguaur.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jiagoushi.top/Article/details/gtbhkapbpr.html

[D21] 判断是否包含某元素
来源：http://dali.yuxming.cn/Article/details/gttlbvynbs.html

Py:   x in arr
来源：http://dali.jinqigufen.top/Article/details/gtfbhfcejb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ydzc1.top/Article/details/gtsyxmmtuc.html

JS:   arr.includes(x)
来源：http://dali.redwolf501.top/Article/details/gtgrnkszhs.html

TS:   arr.includes(x)
来源：http://dali.hysaishi.cn/Article/details/gtbwbwnlea.html

Java: list.contains(x)
来源：http://dali.xinyue.icu/Article/details/gtytafwhmp.html

Go:   slices.Contains(arr, x)
来源：http://dali.cashguo.top/Article/details/gtkxyfvcbx.html

Ruby: arr.include?(x)
来源：http://dali.wangdashe.top/Article/details/gttkhifpdc.html

C#:   list.Contains(x)
来源：http://dali.meibo888.top/Article/details/gtllqbrcaf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.nanxuanxn.top/Article/details/gtxawunvgq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.redwolf501.top/Article/details/gtaeisgrlc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zdqjudy.top/Article/details/gtjghxlmmw.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zdqjudy.top/Article/details/gtdcxhfppd.html

TS:   [...arr];
来源：http://dali.chenzaomai.com/Article/details/gtpobttvwp.html

Java: new ArrayList<>(list);
来源：http://dali.316326.xyz/Article/details/gtrmkqjseh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jianghu66.top/Article/details/gtysapnlfh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xinyue.icu/Article/details/gtmdldbozj.html

C#:   new List<int>(list);
来源：http://dali.redwolf501.top/Article/details/gtepmiypcv.html

[D23] reduce 累积计算
来源：http://dali.wangshuangyany.cn/Article/details/gtjuvzfkdm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.wangdashe.top/Article/details/gtxpxkyohc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.guannengcc.top/Article/details/gtgefzifzz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangdashe.top/Article/details/gtxmcsftzl.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sysykeji.top/Article/details/gtfxgxbfvg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yuxming.cn/Article/details/gtdekcmocx.html

Go:   // 手写循环
来源：http://dali.cashguo.top/Article/details/gtgfnnifso.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gogol.net.cn/Article/details/gtkmulrhcr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jlsjyb.cn/Article/details/gtyuelrqwi.html

[D24] 字典 / Map 基本操作
来源：http://dali.fengsongda.top/Article/details/gtsdvguali.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.wangdashe.top/Article/details/gtsyrdhmxk.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.havefunace.top/Article/details/gtoxdkxycc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.haohaochexian.top/Article/details/gthaycnlep.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shuidangran.top/Article/details/gtktzrowjh.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gogol.net.cn/Article/details/gtnkxyyvtd.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jqgfzy.top/Article/details/gtakpascln.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.iojbl.cn/Article/details/gtkafdadep.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhixingplan.top/Article/details/gtynfvnfau.html

[D25] Set 集合去重与交并差
来源：http://dali.0kj1m.cn/Article/details/gtecncsdgz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yuanzhike.top/Article/details/gtjngdbyia.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.snrcjt.cn/Article/details/gtoasjutrn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sufxvd.cn/Article/details/gtvfokeehv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.havefunace.top/Article/details/gttwcurany.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yvedp.cn/Article/details/gtvpdaktmo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shangyingyoupin.top/Article/details/gtpjupmvba.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtsgqflrcd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xinyue.icu/Article/details/gtvmkjxkub.html

[D26] 数组转字符串
来源：http://dali.svipenyu.cn/Article/details/gtltxladvx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.daxiang520.top/Article/details/gtxmfkkccx.html

PHP:  implode(", ", $arr);
来源：http://dali.wangdashe.top/Article/details/gtavhipzai.html

JS:   arr.join(", ")
来源：http://dali.guannengcc.top/Article/details/gtstnogobl.html

TS:   arr.join(", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqrmhpvnn.html

Java: String.join(", ", list)
来源：http://dali.xziqi.cn/Article/details/gtrcryrfqe.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gaohongyu789.top/Article/details/gtrjgcgosh.html

Ruby: arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gtbticyhrj.html

C#:   string.Join(", ", list)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthvinvauy.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtlpjmchsv.html

E. 字符串处理
来源：http://dali.316326.xyz/Article/details/gtkhscvpwx.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtcxeyygde.html

[E01] 拼接字符串
来源：http://dali.hywenlv.cn/Article/details/gtkhgbmifo.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shanyushiyangtech.top/Article/details/gtfmttiryt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cqqwz.cn/Article/details/gtvgetewzm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258888.top/Article/details/gthrzigxcw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuanzhike.top/Article/details/gtkuekquyv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hongshengwenyu.top/Article/details/gttdiogkyk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.birdmap.top/Article/details/gtpjsakawe.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shanyushiyangtech.top/Article/details/gtvbpaogou.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtqxrmgakq.html

[E02] 重复字符串
来源：http://dali.yongpay.top/Article/details/gtvcepzbfx.html

Py:   "ab" * 3
来源：http://dali.sufxvd.cn/Article/details/gtiymctipy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yvedp.cn/Article/details/gteciskpam.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gtqugpfhkg.html

TS:   "ab".repeat(3)
来源：http://dali.zhoulong.xyz/Article/details/gttsatxubw.html

Java: "ab".repeat(3)
来源：http://dali.svipenyu.cn/Article/details/gtrymgjqlq.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cqqwz.cn/Article/details/gtstupsycy.html

Ruby: "ab" * 3
来源：http://dali.yangfankeji.com/Article/details/gtazlwmzqy.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hongshengwenyu.top/Article/details/gtzkmeajzu.html

[E03] 截取子串
来源：http://dali.jiagoushi.top/Article/details/gtsdvhkobw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.guannengcc.top/Article/details/gtnkrspggd.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gtgmotehiw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gtgpuwojjj.html

TS:   s.slice(1, 4)
来源：http://dali.yj20258888.top/Article/details/gtmpgdvkar.html

Java: s.substring(1, 4)
来源：http://dali.chenzaomai.com/Article/details/gtwhrxdhvd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cheryme.top/Article/details/gtqchtcxxy.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.fengsongda.top/Article/details/gtylahmmiu.html

C#:   s.Substring(1, 3)
来源：http://dali.0kj1m.cn/Article/details/gtuqkdtrtz.html

[E04] 查找子串位置
来源：http://dali.cucudq.cn/Article/details/gthwequczm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xuanzx.com/Article/details/gtdhnqscgy.html

PHP:  strpos($s, "x");
来源：http://dali.sxryk.cn/Article/details/gtjaxktoef.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ybcxt.top/Article/details/gtbvaixqqa.html

TS:   s.indexOf("x")
来源：http://dali.jqgfzy.top/Article/details/gtdgkygdpg.html

Java: s.indexOf("x")
来源：http://dali.pengpengdd.cyou/Article/details/gtuigfxzvd.html

Go:   strings.Index(s, "x")
来源：http://dali.zhengqikj.top/Article/details/gtmbakcfvk.html

Ruby: s.index("x")
来源：http://dali.yonumen.top/Article/details/gthdvavixz.html

C#:   s.IndexOf("x")
来源：http://dali.gzhubu.top/Article/details/gtxvrgelpc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jqgufenzy.top/Article/details/gtfgzaqoxs.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.bjfxy.top/Article/details/gtahveivvn.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.wangshuangyany.cn/Article/details/gtnrkcjjpp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yvedp.cn/Article/details/gthhnrikjf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jqgufenzy.top/Article/details/gtwatjkzsh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tian-w.cn/Article/details/gtqxplxumb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.bjfxy.top/Article/details/gtsuphpiek.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.redwolf501.top/Article/details/gtspopthlm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gotoacloud.top/Article/details/gtoyuqnsmb.html

[E06] 替换子串
来源：http://dali.havefunace.top/Article/details/gtnxwdmlyy.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gaohongyu789.top/Article/details/gtgskdkvzm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.nwbrower.top/Article/details/gtddnlphfu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttvulblcf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gttqsqelbk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gtifofdhnl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yj202588.top/Article/details/gtstffjruu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtnzkcqyro.html

C#:   s.Replace("a", "b")
来源：http://dali.guannengcc.top/Article/details/gtdpghpmdp.html

[E07] 按分隔符拆分
来源：http://dali.hammf.cn/Article/details/gtwxshzhld.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.redwolf501.top/Article/details/gtcoypjyvf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cheryme.top/Article/details/gtnktcdnam.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ydzc1.top/Article/details/gtjacxwutc.html

TS:   s.split(",")
来源：http://dali.yuxming.cn/Article/details/gtqzqhteuq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.andypj.xyz/Article/details/gtmobugjfh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jlsjyb.cn/Article/details/gtpkqdajhb.html

Ruby: s.split(",");  s.split
来源：http://dali.iojbl.cn/Article/details/gtyeqxbjlw.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.bjfxy.top/Article/details/gtovgqtnbt.html

[E08] 数组按分隔符合并
来源：http://dali.aizwys.cn/Article/details/gtommpgwsy.html

Py:   ",".join(items)
来源：http://dali.tianlin.xyz/Article/details/gtxytyuizx.html

PHP:  implode(",", $items);
来源：http://dali.yvedp.cn/Article/details/gtcqbpluzs.html

JS:   items.join(",")
来源：http://dali.cheryme.top/Article/details/gtrzazfjmy.html

TS:   items.join(",")
来源：http://dali.zdqjudy.top/Article/details/gtbdwkbbkn.html

Java: String.join(",", items)
来源：http://dali.hnqzz.top/Article/details/gtplvjvhvl.html

Go:   strings.Join(items, ",")
来源：http://dali.cdnleiting.top/Article/details/gtxbeblggy.html

Ruby: items.join(",")
来源：http://dali.sysykeji.top/Article/details/gtufybtded.html

C#:   string.Join(",", items)
来源：http://dali.jinqigfzy.top/Article/details/gtdmvafuii.html

[E09] 去除所有空白字符
来源：http://dali.nwbrower.top/Article/details/gtuwswlidw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.kuanghao11.cn/Article/details/gtxfxonxep.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gttzudhzrs.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.dashuyun.cn/Article/details/gtujwxwbms.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhoulong.xyz/Article/details/gtxetlyxlg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.aibaodan.cn/Article/details/gtnfxhdcfn.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xylfe.cn/Article/details/gtmcmdnyqo.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jqgufenzy.top/Article/details/gtzljdwgsq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hysaishi.cn/Article/details/gthyvsopnd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.smart0.xyz/Article/details/gtjkjksutu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gtjlqrwgun.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.guowangkeji.top/Article/details/gttmlqfxrk.html

JS:   "7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gtlcmhmmfu.html

TS:   "7".padStart(3, "0")
来源：http://dali.hnqzz.top/Article/details/gtbutswlff.html

Java: String.format("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gtqpbfyujg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gtcudzcmip.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tianlin.xyz/Article/details/gtklbwykue.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hongshengwenyu.top/Article/details/gtbfeaxtax.html

[E11] 反转字符串
来源：http://dali.gogol.net.cn/Article/details/gtopulvock.html

Py:   s[::-1]
来源：http://dali.yangfankeji.com/Article/details/gtzlmwaxsu.html

PHP:  strrev($s);
来源：http://dali.birdmap.top/Article/details/gtxfxncbda.html

JS:   [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gtbflqehig.html

TS:   [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gtrtzygqen.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj20258.top/Article/details/gtjavrdblw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.kuanghao11.cn/Article/details/gtgfbmewzp.html

Ruby: s.reverse
来源：http://dali.zdqjudy.top/Article/details/gtzbjhguvu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.chenjidiqi.icu/Article/details/gtdvamqxcu.html

[E12] 统计某字符出现次数
来源：http://dali.ydzc1.top/Article/details/gtxssvjbst.html

Py:   s.count("a")
来源：http://dali.vqdsnc.cn/Article/details/gtxnpirdck.html

PHP:  substr_count($s, "a");
来源：http://dali.jianghu66.top/Article/details/gtpipwzjgy.html

JS:   s.split("a").length - 1
来源：http://dali.hammf.cn/Article/details/gtqvbwsjmc.html

TS:   s.split("a").length - 1
来源：http://dali.yuxming.cn/Article/details/gtafzvfouy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.birdmap.top/Article/details/gtjedlktpv.html

Go:   strings.Count(s, "a")
来源：http://dali.zhongyouzk.top/Article/details/gtbmsguuik.html

Ruby: s.count("a")
来源：http://dali.fengsongda.top/Article/details/gtebxnsnkp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hysaishi.cn/Article/details/gthpopfctt.html

[E13] 逐字符遍历
来源：http://dali.ppjwa.cn/Article/details/gtoirucddd.html

Py:   for ch in s: print(ch)
来源：http://dali.dianchejie.cn/Article/details/gtyqmmtstd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sweek.top/Article/details/gtxomhhyzi.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gthjmahzco.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hywenlv.cn/Article/details/gtobywglea.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gtmormjnne.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jiagoushi.top/Article/details/gtjgzerbzd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ydzc1.top/Article/details/gtqrragxrc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dashuyun.cn/Article/details/gtnvtdthaq.html

[E14] URL 编码与 Base64
来源：http://dali.snrcjt.cn/Article/details/gtihkiedlo.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ivvv.top/Article/details/gtegbcoklc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.daria6918.cn/Article/details/gtkosijktd.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xuanzx.com/Article/details/gtqaadtixz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jianghu66.top/Article/details/gtqgdlaljq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhengqikj.top/Article/details/gtinauuyuf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shzxlz.cn/Article/details/gtfdkrifag.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ydzc1.top/Article/details/gtffqnpbop.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhghybga.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhoulong.xyz/Article/details/gtujtsaxgf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlzudpgwv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinqigufen.top/Article/details/gtukdikcbi.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.dashuyun.cn/Article/details/gtbkzwskrr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhongyouzk.top/Article/details/gtkdacvihy.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenlongwang.top/Article/details/gtcqspiquf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvagzshor.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jiagoushi.top/Article/details/gttwktgkde.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.aizwys.cn/Article/details/gtanlfshef.html

[E16] 数字千分位
来源：http://dali.ybcxt.top/Article/details/gtxbjzcmlx.html

Py:   f"{1234567:,}"
来源：http://dali.hammf.cn/Article/details/gtvsnrynxo.html

PHP:  number_format(1234567);
来源：http://dali.cashguo.top/Article/details/gtbenqukku.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jianghu66.top/Article/details/gtrxfdiygh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhoulong.xyz/Article/details/gtgamtjjge.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtobcmgzal.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hywenlv.cn/Article/details/gtmrsxnllo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tianlin.xyz/Article/details/gthpdwpctk.html

C#:   1234567.ToString("N0")
来源：http://dali.yvedp.cn/Article/details/gtwifzmobe.html

[E17] 首字母大写
来源：http://dali.daxiang520.top/Article/details/gtphsjelio.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yvedp.cn/Article/details/gtruasnumi.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hnqzz.top/Article/details/gtjbnbsknv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ydzc1.top/Article/details/gtpueojaah.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.meibo888.top/Article/details/gttybweait.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cucudq.cn/Article/details/gtmainpgcm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.chenzaomai.com/Article/details/gtapzkmlfe.html

Ruby: s.capitalize
来源：http://dali.hnqzz.top/Article/details/gtcowzipff.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhongyouzk.top/Article/details/gthtqlgwdu.html

[E18] 模板占位符替换
来源：http://dali.iojbl.cn/Article/details/gtbtgshumv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.havefunace.top/Article/details/gtadjqcrmz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinqigfzy.top/Article/details/gtjtollsqi.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gtozfgtikd.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cqqwz.cn/Article/details/gthlyphxvs.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gtgstxkljl.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yj202588.top/Article/details/gtjnqtrjtx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cqqwz.cn/Article/details/gtbzioumdl.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ehwqpu.com/Article/details/gtdfzvljhl.html

[E19] 多行文本按行拆分
来源：http://dali.ivvv.top/Article/details/gtwuzpzcbv.html

Py:   s.splitlines()
来源：http://dali.gotoacloud.top/Article/details/gttdcwbemx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ppjwa.cn/Article/details/gthxogfjoj.html

JS:   s.split(/\r?\n/)
来源：http://dali.sysykeji.top/Article/details/gthtelvocf.html

TS:   s.split(/\r?\n/)
来源：http://dali.sweek.top/Article/details/gtxesrtxxv.html

Java: s.lines().toList()
来源：http://dali.quarkkingdee.top/Article/details/gtnuhneobe.html

Go:   strings.Split(s, "\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjjpnvzco.html

Ruby: s.lines
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbcxxpjqg.html

C#:   s.Split('\n')
来源：http://dali.hongshengwenyu.top/Article/details/gtgjtguyjf.html

[E20] 判断字符串是否为空
来源：http://dali.c1oappe.top/Article/details/gtcxshldfv.html

Py:   if not s:
来源：http://dali.ydzc1.top/Article/details/gtzhhohjom.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.guannengcc.top/Article/details/gtnzgjekdt.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jlsjyb.cn/Article/details/gtddjdnhdg.html

TS:   if (s === "") {}
来源：http://dali.xuetiantiany.cn/Article/details/gttbqtoawv.html

Java: if (s.isEmpty()) {}
来源：http://dali.chenlongwang.top/Article/details/gtpxhzesen.html

Go:   if s == "" {}
来源：http://dali.quarkkingdee.top/Article/details/gthwixjelv.html

Ruby: if s.empty?
来源：http://dali.shuidangran.top/Article/details/gtiafrkqrt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cashguo.top/Article/details/gtfxhdbxdy.html

[E21] 超长截断加省略号
来源：http://dali.jqgufenzy.top/Article/details/gtcacgslvi.html


<!-- 参考信息 -->