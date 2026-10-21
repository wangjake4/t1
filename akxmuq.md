代发 wailian999

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtcjvjqbui.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtjtjqkddh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xylfe.cn/Article/details/gtjlogofuu.html

Go:   // 手写循环累加
来源：http://dali.hnxiangtu.top/Article/details/gtantosvpv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shanyushiyangtech.top/Article/details/gtkfshpkgg.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinghuilouyu.cn/Article/details/gtjhlgdmgb.html

[D17] 最大值与最小值
来源：http://dali.gogol.net.cn/Article/details/gtzxuekjqg.html

Py:   max(arr);  min(arr)
来源：http://dali.snrcjt.cn/Article/details/gthccizhwe.html

PHP:  max($arr);  min($arr);
来源：http://dali.xuanzx.com/Article/details/gtuyposgys.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ivvv.top/Article/details/gtxqdsvvjq.html

TS:   Math.max(...arr);
来源：http://dali.hnxiangtu.top/Article/details/gtspcjovoy.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yuxming.cn/Article/details/gtutrcrylm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.svipenyu.cn/Article/details/gthjqxaxdi.html

Ruby: arr.max;  arr.min
来源：http://dali.aizwys.cn/Article/details/gtipaxlmyy.html

C#:   list.Max();  list.Min()
来源：http://dali.jyoumei.cn/Article/details/gtlofeigqu.html

[D18] 扁平化嵌套数组
来源：http://dali.gogol.net.cn/Article/details/gtxpamdbgb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ybcxt.top/Article/details/gtsklwfutq.html

PHP:  array_merge(...$nested);
来源：http://dali.xinyue.icu/Article/details/gthkqvzszd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cucudq.cn/Article/details/gtklfpkurg.html

TS:   nested.flat();
来源：http://dali.hongshengwenyu.top/Article/details/gtrabihnwk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhengqikj.top/Article/details/gtqrtspvwz.html

Go:   // 手写双层循环
来源：http://dali.guowangkeji.top/Article/details/gttyhhyccu.html

Ruby: nested.flatten
来源：http://dali.xinyue.icu/Article/details/gtlelaccea.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hfpthk.cn/Article/details/gtuzjaooxl.html

[D19] 按字段分组
来源：http://dali.fzhhl.top/Article/details/gtbcbcgefh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.meibo888.top/Article/details/gtpammvwnf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.chenzaomai.com/Article/details/gtzgwcxjwa.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jyoumei.cn/Article/details/gtsfoarvhq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttgnjjylb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.0kj1m.cn/Article/details/gtfuafltwu.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gtrpefifwb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yangfankeji.com/Article/details/gthxuopaao.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.aibaodan.cn/Article/details/gtzsurcpmt.html

[D20] 统计每个元素出现次数
来源：http://dali.jinqigfzy.top/Article/details/gtsgqvmsaq.html

Py:   Counter(arr)
来源：http://dali.meibo888.top/Article/details/gtadvzaklq.html

PHP:  array_count_values($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtvbtwaowq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guannengcc.top/Article/details/gtchqcpncs.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhengqikj.top/Article/details/gtmdognuhd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.tianlin.xyz/Article/details/gtvnyaulcy.html

Go:   // 手写 map[T]int
来源：http://dali.pycfn.com/Article/details/gtlwkfxgyd.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gtkzzgmluo.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.snrcjt.cn/Article/details/gtomhmfkzc.html

[D21] 判断是否包含某元素
来源：http://dali.xinyue.icu/Article/details/gtvvzhlkqa.html

Py:   x in arr
来源：http://dali.bjfxy.top/Article/details/gtqznfeiom.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xziqi.cn/Article/details/gtxdtgovtc.html

JS:   arr.includes(x)
来源：http://dali.svipenyu.cn/Article/details/gtddagzkgw.html

TS:   arr.includes(x)
来源：http://dali.pycfn.com/Article/details/gtpldpnadb.html

Java: list.contains(x)
来源：http://dali.shzxlz.cn/Article/details/gtizyjrvfh.html

Go:   slices.Contains(arr, x)
来源：http://dali.xinyue.icu/Article/details/gttwqhegta.html

Ruby: arr.include?(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttnnenjts.html

C#:   list.Contains(x)
来源：http://dali.chenlongwang.top/Article/details/gtwlxttvgh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jlsjyb.cn/Article/details/gtwncpogjn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sweek.top/Article/details/gtbfmseshj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jqgfzy.top/Article/details/gtasihnffs.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hnqzz.top/Article/details/gtaetotzmo.html

TS:   [...arr];
来源：http://dali.yanxiufei.cn/Article/details/gtxdqkfxev.html

Java: new ArrayList<>(list);
来源：http://dali.ivvv.top/Article/details/gtaiiqockr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenjidiqi.icu/Article/details/gtdzbmvzvv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zycfv.cn/Article/details/gtkuspegar.html

C#:   new List<int>(list);
来源：http://dali.sufxvd.cn/Article/details/gtxgolsqux.html

[D23] reduce 累积计算
来源：http://dali.yuxming.cn/Article/details/gthppxvyvp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gttppsmyuh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shuidangran.top/Article/details/gtrmxsfnds.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtlmpdfseg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xinyue.icu/Article/details/gtaukcpiux.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cucudq.cn/Article/details/gtnbcwgavq.html

Go:   // 手写循环
来源：http://dali.yuxming.cn/Article/details/gtknjxkcun.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjqizugoh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinqigufen.top/Article/details/gthjxerlha.html

[D24] 字典 / Map 基本操作
来源：http://dali.yongpay.top/Article/details/gtpdpxiano.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cashguo.top/Article/details/gttbkdfzfs.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj20258888.top/Article/details/gtpjwptsda.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.guowangkeji.top/Article/details/gtiidbqjab.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtgbmtohds.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yvedp.cn/Article/details/gtbnkgsutw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.svipenyu.cn/Article/details/gtupltbwru.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nwbrower.top/Article/details/gtlhydlrhe.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yueranfly.top/Article/details/gtwyvugpkq.html

[D25] Set 集合去重与交并差
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiqznyxmm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jlsjyb.cn/Article/details/gtvrjsorqh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.tian-w.cn/Article/details/gtauyfftlf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.smart0.xyz/Article/details/gtzhtibzot.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.0kj1m.cn/Article/details/gtgibqaxza.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.svipenyu.cn/Article/details/gtqxpfgqml.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xinyue.icu/Article/details/gtvzqkhlwi.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.wangdashe.top/Article/details/gtqrrccbnf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sysykeji.top/Article/details/gtzlsewgze.html

[D26] 数组转字符串
来源：http://dali.hnxiangtu.top/Article/details/gtaflunvth.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpcschkwq.html

PHP:  implode(", ", $arr);
来源：http://dali.cqqwz.cn/Article/details/gtlcywmhva.html

JS:   arr.join(", ")
来源：http://dali.svipenyu.cn/Article/details/gtftjjttfs.html

TS:   arr.join(", ")
来源：http://dali.zhongyouzk.top/Article/details/gtxoiiinwu.html

Java: String.join(", ", list)
来源：http://dali.sweek.top/Article/details/gtmxtsmnuh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yongpay.top/Article/details/gtpnyoabom.html

Ruby: arr.join(", ")
来源：http://dali.tianlin.xyz/Article/details/gttsjzkiyq.html

C#:   string.Join(", ", list)
来源：http://dali.yuxming.cn/Article/details/gtfjbywdpq.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtqotxovut.html

E. 字符串处理
来源：http://dali.sysykeji.top/Article/details/gtqkjmuber.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtsnrdcmod.html

[E01] 拼接字符串
来源：http://dali.hysaishi.cn/Article/details/gtcomjaiem.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.tanke756.top/Article/details/gtmuvsmpwt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.guannengcc.top/Article/details/gtylwsjwzk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tian-w.cn/Article/details/gtiinbbszv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258888.top/Article/details/gthdqxcqtg.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.chenlongwang.top/Article/details/gtepgagudj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhiwuduotai.top/Article/details/gtgoumzzbv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.havefunace.top/Article/details/gtulirdqvt.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtbhddnvxa.html

[E02] 重复字符串
来源：http://dali.0kj1m.cn/Article/details/gtobnyfqig.html

Py:   "ab" * 3
来源：http://dali.gzhubu.top/Article/details/gtxpmmbyqo.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yj202588.top/Article/details/gtpemxhtzf.html

JS:   "ab".repeat(3)
来源：http://dali.hnxiangtu.top/Article/details/gtegiuestt.html

TS:   "ab".repeat(3)
来源：http://dali.zhengqikj.top/Article/details/gttodhgyft.html

Java: "ab".repeat(3)
来源：http://dali.chenzaomai.com/Article/details/gtjnhcidmt.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ydzc1.top/Article/details/gtbuosnckx.html

Ruby: "ab" * 3
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbebruzlj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhiwuduotai.top/Article/details/gtinhtuwfe.html

[E03] 截取子串
来源：http://dali.zhengqikj.top/Article/details/gtsuzyybej.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gotoacloud.top/Article/details/gtdzuzkxie.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gtrlciurou.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gtlkyieezc.html

TS:   s.slice(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gtfgfpczto.html

Java: s.substring(1, 4)
来源：http://dali.cucudq.cn/Article/details/gtnwabaajf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yongpay.top/Article/details/gtoqinthjt.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cashguo.top/Article/details/gtzzozjglk.html

C#:   s.Substring(1, 3)
来源：http://dali.0kj1m.cn/Article/details/gtqlxcubea.html

[E04] 查找子串位置
来源：http://dali.aizwys.cn/Article/details/gttxkituzn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jqgfzy.top/Article/details/gtmmdoifdz.html

PHP:  strpos($s, "x");
来源：http://dali.316326.xyz/Article/details/gtapwmeeey.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtslplcyvn.html

TS:   s.indexOf("x")
来源：http://dali.sweek.top/Article/details/gtkkkzeddq.html

Java: s.indexOf("x")
来源：http://dali.yj202588.top/Article/details/gtdxyalwun.html

Go:   strings.Index(s, "x")
来源：http://dali.zhoulong.xyz/Article/details/gtdfoepflq.html

Ruby: s.index("x")
来源：http://dali.yonumen.top/Article/details/gtnjqleuef.html

C#:   s.IndexOf("x")
来源：http://dali.yongpay.top/Article/details/gtpcljrhnt.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinqigufen.top/Article/details/gtsbbrdesr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtisaassag.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.0kj1m.cn/Article/details/gtnsnfzknw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ydzc1.top/Article/details/gtplsvpdoo.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yangfankeji.com/Article/details/gtedieovdh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jianghu66.top/Article/details/gtplmlbcgj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.0kj1m.cn/Article/details/gtznqceijt.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnjmytofe.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhiwuduotai.top/Article/details/gtirhwhoiu.html

[E06] 替换子串
来源：http://dali.nwbrower.top/Article/details/gtclaqigld.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtspjxmzwp.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yueranfly.top/Article/details/gthvvtdnns.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtctdmyzkp.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtjwrdqnaa.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gthapuzwyt.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hywenlv.cn/Article/details/gtmtpahwak.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.gzhubu.top/Article/details/gtotggailw.html

C#:   s.Replace("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gthucrwpsi.html

[E07] 按分隔符拆分
来源：http://dali.tian-w.cn/Article/details/gtquftjoru.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.fzhhl.top/Article/details/gtdpoaofql.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sufxvd.cn/Article/details/gtvaugbdwb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yangfankeji.com/Article/details/gtrxsysudr.html

TS:   s.split(",")
来源：http://dali.ydzc1.top/Article/details/gtzjnlndhb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttpgeogvo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yongpay.top/Article/details/gtgjaapbwy.html

Ruby: s.split(",");  s.split
来源：http://dali.gotoacloud.top/Article/details/gtqbvdgmgy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqrifedgy.html

[E08] 数组按分隔符合并
来源：http://dali.yj20258.top/Article/details/gttuqvvkyz.html

Py:   ",".join(items)
来源：http://dali.tian-w.cn/Article/details/gttomxgmxg.html

PHP:  implode(",", $items);
来源：http://dali.jianghu66.top/Article/details/gtbzajcwss.html

JS:   items.join(",")
来源：http://dali.cashguo.top/Article/details/gtyhkshxar.html

TS:   items.join(",")
来源：http://dali.nanxinkj.top/Article/details/gtwkwjcxdf.html

Java: String.join(",", items)
来源：http://dali.yuxming.cn/Article/details/gtpupffuqo.html

Go:   strings.Join(items, ",")
来源：http://dali.zhixingplan.top/Article/details/gtbhkorqrb.html

Ruby: items.join(",")
来源：http://dali.zhoulong.xyz/Article/details/gtbuwdkvfe.html

C#:   string.Join(",", items)
来源：http://dali.dashuyun.cn/Article/details/gtnauvkvyb.html

[E09] 去除所有空白字符
来源：http://dali.0kj1m.cn/Article/details/gtkzzjmbtb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gogol.net.cn/Article/details/gtrjvnuffi.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtzqalcljn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.daria6918.cn/Article/details/gtquzrtoji.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.aibaodan.cn/Article/details/gtbuceaocw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdoqixjlq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.pengpengdd.cyou/Article/details/gtyxzdmkbe.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.tianlin.xyz/Article/details/gttvmvatmy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtucbksubc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hongshengwenyu.top/Article/details/gthctkkzcq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.c1oappe.top/Article/details/gtfjtugvyk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.pycfn.com/Article/details/gtofmoltqv.html

JS:   "7".padStart(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gtajyxlodc.html

TS:   "7".padStart(3, "0")
来源：http://dali.jyoumei.cn/Article/details/gtlfwlxaai.html

Java: String.format("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gtjoaxivpf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gtbbtswvxe.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gtksusisuv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sufxvd.cn/Article/details/gtsxepsrrc.html

[E11] 反转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcwkrjbku.html

Py:   s[::-1]
来源：http://dali.yueranfly.top/Article/details/gtnhruhlsm.html

PHP:  strrev($s);
来源：http://dali.zhixingplan.top/Article/details/gtkjpmxhtn.html

JS:   [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gtvmmbgyxt.html

TS:   [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gtzrorpcex.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tanke756.top/Article/details/gtpkvqkqgv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.0kj1m.cn/Article/details/gtkrxtxrez.html

Ruby: s.reverse
来源：http://dali.vqdsnc.cn/Article/details/gttszpkmfp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hysaishi.cn/Article/details/gtzohnwhgs.html

[E12] 统计某字符出现次数
来源：http://dali.sxryk.cn/Article/details/gtqrcucvol.html

Py:   s.count("a")
来源：http://dali.ivvv.top/Article/details/gtlijegavv.html

PHP:  substr_count($s, "a");
来源：http://dali.shuidangran.top/Article/details/gtirxriurh.html

JS:   s.split("a").length - 1
来源：http://dali.meibo888.top/Article/details/gthzpiawqj.html

TS:   s.split("a").length - 1
来源：http://dali.yj20258888.top/Article/details/gtjdpaukmh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhiwuduotai.top/Article/details/gtpywwvvkz.html

Go:   strings.Count(s, "a")
来源：http://dali.0kj1m.cn/Article/details/gtiklqjobl.html

Ruby: s.count("a")
来源：http://dali.hammf.cn/Article/details/gtdetxvhlf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gotoacloud.top/Article/details/gtbuaywfrg.html

[E13] 逐字符遍历
来源：http://dali.dianchejie.cn/Article/details/gtxwolmyvm.html

Py:   for ch in s: print(ch)
来源：http://dali.jinqigfzy.top/Article/details/gtieuqsfca.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.vqdsnc.cn/Article/details/gtrnvbhwfz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigufen.top/Article/details/gtckhkzbyq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jiagoushi.top/Article/details/gtipyayrga.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.tanke756.top/Article/details/gtcauqkiwv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.tanke756.top/Article/details/gtvpaydnlr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhengqikj.top/Article/details/gtlitsvtuy.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jyoumei.cn/Article/details/gtkhlyerdm.html

[E14] URL 编码与 Base64
来源：http://dali.cashguo.top/Article/details/gtyyzqfuum.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yongpay.top/Article/details/gtfayqndjv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xinyue.icu/Article/details/gtwajsosyk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcyxqsvjm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shzxlz.cn/Article/details/gtwhvfxrjt.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtburvlyzd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cdnleiting.top/Article/details/gtjcqnxoxb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xuetiantiany.cn/Article/details/gtdandudnq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhixingplan.top/Article/details/gtducweggz.html

[E15] HTML 转义 / 反转义
来源：http://dali.gaohongyu789.top/Article/details/gtbyrhjgdh.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jyoumei.cn/Article/details/gtqvsvgblo.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zdqjudy.top/Article/details/gtmhwcjvky.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yvedp.cn/Article/details/gtdyzavtws.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cashguo.top/Article/details/gtotsqfipy.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cashguo.top/Article/details/gtekegpaci.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gtemeorlcq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jiagoushi.top/Article/details/gtyqfjfdww.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cucudq.cn/Article/details/gtayillzwf.html

[E16] 数字千分位
来源：http://dali.yj20258888.top/Article/details/gtaqborabq.html

Py:   f"{1234567:,}"
来源：http://dali.guannengcc.top/Article/details/gtyqavhsae.html

PHP:  number_format(1234567);
来源：http://dali.nanxuanxn.top/Article/details/gtszjdxenm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.smart0.xyz/Article/details/gtpxioauqs.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tanke756.top/Article/details/gthoqokyqq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.sysykeji.top/Article/details/gtqpjyjfhb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj202588.top/Article/details/gtzmpeudhl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hammf.cn/Article/details/gteksmkeqw.html

C#:   1234567.ToString("N0")
来源：http://dali.xinyue.icu/Article/details/gtwqtoyiso.html

[E17] 首字母大写
来源：http://dali.hammf.cn/Article/details/gtoauesiqm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinqigfzy.top/Article/details/gtlnytauin.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.meibo888.top/Article/details/gtcghbnjbo.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cdnleiting.top/Article/details/gtbtuyilim.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hywenlv.cn/Article/details/gttjqfombl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjzfuuqbb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hammf.cn/Article/details/gtsqrgowaa.html

Ruby: s.capitalize
来源：http://dali.cdnleiting.top/Article/details/gtqehoatpl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xinyue.icu/Article/details/gtacbbxjai.html

[E18] 模板占位符替换
来源：http://dali.havefunace.top/Article/details/gtbpnvpsxn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhiwuduotai.top/Article/details/gtzmmrvjbb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhixingplan.top/Article/details/gtdlwbpulb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yonumen.top/Article/details/gtlejpuief.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gtfqzyamey.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gtudsykuva.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.pycfn.com/Article/details/gtwjfwtlxj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gotoacloud.top/Article/details/gtqodfnpiq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hywenlv.cn/Article/details/gtqqqnuxjv.html

[E19] 多行文本按行拆分
来源：http://dali.aibaodan.cn/Article/details/gtqnmkioda.html

Py:   s.splitlines()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtklhguigj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yj20258.top/Article/details/gtvpiukhpx.html

JS:   s.split(/\r?\n/)
来源：http://dali.nanxuanxn.top/Article/details/gtblcuobaf.html

TS:   s.split(/\r?\n/)
来源：http://dali.chenzaomai.com/Article/details/gtzffxtlxw.html

Java: s.lines().toList()
来源：http://dali.haohaochexian.top/Article/details/gtgpqvpqds.html

Go:   strings.Split(s, "\n")
来源：http://dali.ivvv.top/Article/details/gtyxizsdys.html

Ruby: s.lines
来源：http://dali.yuanzhike.top/Article/details/gtqydzlkdt.html

C#:   s.Split('\n')
来源：http://dali.chenzaomai.com/Article/details/gtptswmlvl.html

[E20] 判断字符串是否为空
来源：http://dali.zdqjudy.top/Article/details/gtmvevskbb.html

Py:   if not s:
来源：http://dali.316326.xyz/Article/details/gtactdejdf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpzflpzhb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.pycfn.com/Article/details/gtswysmdvh.html

TS:   if (s === "") {}
来源：http://dali.jlsjyb.cn/Article/details/gtuktbbtxs.html

Java: if (s.isEmpty()) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtngbjmytj.html

Go:   if s == "" {}
来源：http://dali.xylfe.cn/Article/details/gtoeaahodx.html

Ruby: if s.empty?
来源：http://dali.jiagoushi.top/Article/details/gtvjlckzmh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhengqikj.top/Article/details/gtdhmtqjwm.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gthmycjskx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nwbrower.top/Article/details/gtmlzpagoz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gtqyswcals.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gttquoaung.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtdztbowam.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnoqckhmc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.quarkkingdee.top/Article/details/gtznbcvbet.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtacslepta.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gtrjrwvnxu.html

[E22] 字节长度与字符长度
来源：http://dali.daxiang520.top/Article/details/gtdpffoukf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gzhubu.top/Article/details/gtqzcagxwi.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gtiimaslwa.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.mhx1999.top/Article/details/gtktgmlmba.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuanzx.com/Article/details/gteqfvdyfz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jianghu66.top/Article/details/gtcyqhowyd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfddyfnxd.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtzgjhpaju.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hywenlv.cn/Article/details/gtasgmakzc.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtxhagoppg.html

F. 文件与目录
来源：http://dali.yj20258888.top/Article/details/gtsgidsjhx.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtueeadxkt.html


<!-- 参考信息 -->