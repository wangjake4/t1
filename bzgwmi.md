代发 wailian999

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.redwolf501.top/Article/details/gtxiixmyzw.html

Go:   // 手写双层循环
来源：http://dali.xylfe.cn/Article/details/gtufusamhl.html

Ruby: nested.flatten
来源：http://dali.yueranfly.top/Article/details/gtplrfdbjz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtczobakvt.html

[D19] 按字段分组
来源：http://dali.0kj1m.cn/Article/details/gtqwmuywup.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtnuujllrf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hywenlv.cn/Article/details/gtxhrsbvlw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhiwuduotai.top/Article/details/gtujenprqe.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gotoacloud.top/Article/details/gtsrpyrehs.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.pycfn.com/Article/details/gtxlwxsdfw.html

Go:   // 手写 map[string][]T
来源：http://dali.yj20258888.top/Article/details/gtkawyxcje.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jlsjyb.cn/Article/details/gtyqhnhvql.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.dashuyun.cn/Article/details/gtaurkeivg.html

[D20] 统计每个元素出现次数
来源：http://dali.jinqigufen.top/Article/details/gtfcedtgfd.html

Py:   Counter(arr)
来源：http://dali.jinqigufen.top/Article/details/gtxbufdiwl.html

PHP:  array_count_values($arr);
来源：http://dali.pycfn.com/Article/details/gtelncmvvd.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jyoumei.cn/Article/details/gtmmfdtozc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.havefunace.top/Article/details/gtnwgwfksy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cheryme.top/Article/details/gtbfzpnizd.html

Go:   // 手写 map[T]int
来源：http://dali.yuxming.cn/Article/details/gtnoosjbit.html

Ruby: arr.tally
来源：http://dali.quarkkingdee.top/Article/details/gthbtusguk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.pycfn.com/Article/details/gtntvcfsni.html

[D21] 判断是否包含某元素
来源：http://dali.sxryk.cn/Article/details/gtjpegzqzh.html

Py:   x in arr
来源：http://dali.jyoumei.cn/Article/details/gttsnvtrmm.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gaohongyu789.top/Article/details/gtjcvsugdr.html

JS:   arr.includes(x)
来源：http://dali.yj20258.top/Article/details/gtgrcfewnw.html

TS:   arr.includes(x)
来源：http://dali.cucudq.cn/Article/details/gtklsbwwis.html

Java: list.contains(x)
来源：http://dali.sysykeji.top/Article/details/gtyrhoejjt.html

Go:   slices.Contains(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtwixtsvze.html

Ruby: arr.include?(x)
来源：http://dali.vqdsnc.cn/Article/details/gtcxenffag.html

C#:   list.Contains(x)
来源：http://dali.hfpthk.cn/Article/details/gtcdomdesf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hnqzz.top/Article/details/gthkioahnw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.daxiang520.top/Article/details/gtrpikyyvf.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xuanzx.com/Article/details/gtersfetqa.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.bjfxy.top/Article/details/gtbmwfmtko.html

TS:   [...arr];
来源：http://dali.havefunace.top/Article/details/gtriiuxugz.html

Java: new ArrayList<>(list);
来源：http://dali.cqqwz.cn/Article/details/gtjttruxyu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.haohaochexian.top/Article/details/gtwpvfllof.html

Ruby: arr.dup;  arr.clone
来源：http://dali.nanxinkj.top/Article/details/gtddkeyhbx.html

C#:   new List<int>(list);
来源：http://dali.quarkkingdee.top/Article/details/gtvvkjaccg.html

[D23] reduce 累积计算
来源：http://dali.yongpay.top/Article/details/gtkpwimiap.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yj20258.top/Article/details/gtnkqxlieu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.tian-w.cn/Article/details/gtvkhycsww.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigufen.top/Article/details/gttfazmmuw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrepcwovu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.mhx1999.top/Article/details/gtnurzdmwm.html

Go:   // 手写循环
来源：http://dali.guowangkeji.top/Article/details/gtvjesjyxr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.redwolf501.top/Article/details/gtkrggxkhl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.fengsongda.top/Article/details/gteywsaiit.html

[D24] 字典 / Map 基本操作
来源：http://dali.gotoacloud.top/Article/details/gtamzohklw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hnqzz.top/Article/details/gtxsffielj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj202588.top/Article/details/gtyceleyec.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ppjwa.cn/Article/details/gtxkjpgdzd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gtcfwehabo.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhiwuduotai.top/Article/details/gtgrrkfpen.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.smart0.xyz/Article/details/gtvznmnjvu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.daxiang520.top/Article/details/gtufhsvfzq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.316326.xyz/Article/details/gtidukrdeh.html

[D25] Set 集合去重与交并差
来源：http://dali.yuanzhike.top/Article/details/gtxkjrsiuj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.meibo888.top/Article/details/gtsblcfpbu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cashguo.top/Article/details/gtekhliphv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.iojbl.cn/Article/details/gtklnjsjne.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj202588.top/Article/details/gttzdnlyns.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yueranfly.top/Article/details/gtjxdezpwk.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cdnleiting.top/Article/details/gtftifvpqw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yuanzhike.top/Article/details/gtzgjbbggx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.birdmap.top/Article/details/gtkvtmzdph.html

[D26] 数组转字符串
来源：http://dali.tianlin.xyz/Article/details/gtsotmfudu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.quarkkingdee.top/Article/details/gtzebecagd.html

PHP:  implode(", ", $arr);
来源：http://dali.cqqwz.cn/Article/details/gtjucqqfze.html

JS:   arr.join(", ")
来源：http://dali.gaohongyu789.top/Article/details/gthzpnnbnb.html

TS:   arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gtrhjrioms.html

Java: String.join(", ", list)
来源：http://dali.jiagoushi.top/Article/details/gtoyhjoobd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.aibaodan.cn/Article/details/gtdhcqcfbm.html

Ruby: arr.join(", ")
来源：http://dali.hnqzz.top/Article/details/gtinihnoxj.html

C#:   string.Join(", ", list)
来源：http://dali.shzxlz.cn/Article/details/gtpjbluqin.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtriphucdk.html

E. 字符串处理
来源：http://dali.snrcjt.cn/Article/details/gtnsnpkquu.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtihwwabqe.html

[E01] 拼接字符串
来源：http://dali.jqgufenzy.top/Article/details/gttdcbpvwm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jianghu66.top/Article/details/gtsjqrbpnv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.gaohongyu789.top/Article/details/gtlvkckwex.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.svipenyu.cn/Article/details/gtvaladgpa.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sweek.top/Article/details/gtcsgtjhdi.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gogol.net.cn/Article/details/gtlxjcrujj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yvedp.cn/Article/details/gtmvmaifnv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yueranfly.top/Article/details/gtlsowxifv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtffbxthzt.html

[E02] 重复字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsyfvqdqw.html

Py:   "ab" * 3
来源：http://dali.jqgufenzy.top/Article/details/gtadlbsoyv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtahnlfoep.html

JS:   "ab".repeat(3)
来源：http://dali.guowangkeji.top/Article/details/gtxnsutdkg.html

TS:   "ab".repeat(3)
来源：http://dali.yanxiufei.cn/Article/details/gtsgmdudsq.html

Java: "ab".repeat(3)
来源：http://dali.cdnleiting.top/Article/details/gtlmtkdcmh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.wangdashe.top/Article/details/gtiteixgdo.html

Ruby: "ab" * 3
来源：http://dali.yongpay.top/Article/details/gtrizdfygc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yvedp.cn/Article/details/gtfxrwjgrg.html

[E03] 截取子串
来源：http://dali.jyoumei.cn/Article/details/gtbjbrfxea.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xziqi.cn/Article/details/gtdyitmehw.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gtjxremcfh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhengqikj.top/Article/details/gtopqjxmgt.html

TS:   s.slice(1, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gtbfppxgat.html

Java: s.substring(1, 4)
来源：http://dali.kuanghao11.cn/Article/details/gtkfcjueqi.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gaohongyu789.top/Article/details/gtwupceqtf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yuanzhike.top/Article/details/gtuwwgckra.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gtbgvcosbm.html

[E04] 查找子串位置
来源：http://dali.ppjwa.cn/Article/details/gtemjsbpld.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gotoacloud.top/Article/details/gtuvqtfqzd.html

PHP:  strpos($s, "x");
来源：http://dali.xinyue.icu/Article/details/gtkzjotcwu.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hnqzz.top/Article/details/gtntpbllhv.html

TS:   s.indexOf("x")
来源：http://dali.cqqwz.cn/Article/details/gtptjgfktg.html

Java: s.indexOf("x")
来源：http://dali.jinqigufen.top/Article/details/gtzcwlgsvm.html

Go:   strings.Index(s, "x")
来源：http://dali.ybcxt.top/Article/details/gtqniueekt.html

Ruby: s.index("x")
来源：http://dali.yj20258888.top/Article/details/gtwinkevtk.html

C#:   s.IndexOf("x")
来源：http://dali.guannengcc.top/Article/details/gtrkrvcgmt.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xylfe.cn/Article/details/gttshhwnnu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnsnymbyd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhixingplan.top/Article/details/gtvbiqhanw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hammf.cn/Article/details/gthpkkjswu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sxryk.cn/Article/details/gtjokggdov.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.bjfxy.top/Article/details/gteiyaldsv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shangyingyoupin.top/Article/details/gtwqorgvtd.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.andypj.xyz/Article/details/gtwxinkiig.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yueranfly.top/Article/details/gtcxsmeoir.html

[E06] 替换子串
来源：http://dali.dashuyun.cn/Article/details/gtptcvuger.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hnxiangtu.top/Article/details/gtvuawpgyp.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtqujfunii.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gtueaevplj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtuslaerqg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtltlfiegj.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.svipenyu.cn/Article/details/gtqdpxswcj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yj20258.top/Article/details/gtbwwowjdp.html

C#:   s.Replace("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtghireghr.html

[E07] 按分隔符拆分
来源：http://dali.yonumen.top/Article/details/gtyfodbtqy.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.9152youxi.cn/Article/details/gtkmcejaxc.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.havefunace.top/Article/details/gtdpavhbrt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yuanzhike.top/Article/details/gtzvolncba.html

TS:   s.split(",")
来源：http://dali.yuanzhike.top/Article/details/gtpolvunjv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.aizwys.cn/Article/details/gtzcmwxhej.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.andypj.xyz/Article/details/gthvsvgves.html

Ruby: s.split(",");  s.split
来源：http://dali.zhixingplan.top/Article/details/gtfnohkswg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yonumen.top/Article/details/gtttkpezuj.html

[E08] 数组按分隔符合并
来源：http://dali.meibo888.top/Article/details/gtgqwwledx.html

Py:   ",".join(items)
来源：http://dali.sysykeji.top/Article/details/gtbausnfla.html

PHP:  implode(",", $items);
来源：http://dali.hnqzz.top/Article/details/gtwtlwoaxp.html

JS:   items.join(",")
来源：http://dali.yuxming.cn/Article/details/gtytxmssyg.html

TS:   items.join(",")
来源：http://dali.sysykeji.top/Article/details/gtsljvnkvt.html

Java: String.join(",", items)
来源：http://dali.316326.xyz/Article/details/gtctwoofnk.html

Go:   strings.Join(items, ",")
来源：http://dali.yongpay.top/Article/details/gtuetpbghu.html

Ruby: items.join(",")
来源：http://dali.hongshengwenyu.top/Article/details/gtjbizhjol.html

C#:   string.Join(",", items)
来源：http://dali.feifeiyinyue.top/Article/details/gtcfonmnuk.html

[E09] 去除所有空白字符
来源：http://dali.yongpay.top/Article/details/gtwtnmnjgo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cashguo.top/Article/details/gtwdpurqmg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtmediumqn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hywenlv.cn/Article/details/gturribyyj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.smart0.xyz/Article/details/gtqtwoucrq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgldflfot.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.dianchejie.cn/Article/details/gtcahuumgg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.dashuyun.cn/Article/details/gtttgampqd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.chenjidiqi.icu/Article/details/gtredwecil.html

[E10] 左侧补零 / 定长填充
来源：http://dali.nwbrower.top/Article/details/gtswfnmjje.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gtcnsbiwjg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ivvv.top/Article/details/gtjdoieynq.html

JS:   "7".padStart(3, "0")
来源：http://dali.hongshengwenyu.top/Article/details/gtgmpiwxnv.html

TS:   "7".padStart(3, "0")
来源：http://dali.xylfe.cn/Article/details/gtlgnojida.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gtttlyjcav.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvoqgljkp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cucudq.cn/Article/details/gtkwpxlnpv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.iojbl.cn/Article/details/gtoamayeno.html

[E11] 反转字符串
来源：http://dali.daxiang520.top/Article/details/gtctflxedq.html

Py:   s[::-1]
来源：http://dali.vqdsnc.cn/Article/details/gtjbtcblht.html

PHP:  strrev($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrxttczku.html

JS:   [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtwyuocusa.html

TS:   [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gtfvghpnbz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yueranfly.top/Article/details/gthpbklwmi.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxhjkljdt.html

Ruby: s.reverse
来源：http://dali.nanxinkj.top/Article/details/gtlwhfsnjv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.svipenyu.cn/Article/details/gtleqzzapu.html

[E12] 统计某字符出现次数
来源：http://dali.zhiwuduotai.top/Article/details/gtxfaaqmwy.html

Py:   s.count("a")
来源：http://dali.tianlin.xyz/Article/details/gtxrxmnprs.html

PHP:  substr_count($s, "a");
来源：http://dali.svipenyu.cn/Article/details/gtzhvklqpx.html

JS:   s.split("a").length - 1
来源：http://dali.cdnleiting.top/Article/details/gtmqivjfsh.html

TS:   s.split("a").length - 1
来源：http://dali.svipenyu.cn/Article/details/gtzokgsivz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnrnlpece.html

Go:   strings.Count(s, "a")
来源：http://dali.vqdsnc.cn/Article/details/gtijnlbpjh.html

Ruby: s.count("a")
来源：http://dali.cdnleiting.top/Article/details/gtkdheigbh.html

C#:   s.Count(c => c == 'a')
来源：http://dali.quarkkingdee.top/Article/details/gtrhuxgybq.html

[E13] 逐字符遍历
来源：http://dali.shuidangran.top/Article/details/gtamksxcte.html

Py:   for ch in s: print(ch)
来源：http://dali.zdqjudy.top/Article/details/gtcxczrntn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xuetiantiany.cn/Article/details/gtyzfnbzvz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ehwqpu.com/Article/details/gtedizbqjz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gtuvpbtist.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.316326.xyz/Article/details/gtxdesqkmg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jyoumei.cn/Article/details/gtqxtmlwzf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hfpthk.cn/Article/details/gtdvrpbldw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.iojbl.cn/Article/details/gtautxjkgb.html

[E14] URL 编码与 Base64
来源：http://dali.zhoulong.xyz/Article/details/gtbqghqzty.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.birdmap.top/Article/details/gtmkabfzfm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nwbrower.top/Article/details/gtixiwvhah.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqjhldhob.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.nwbrower.top/Article/details/gtzkdiusig.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ydzc1.top/Article/details/gtwylskloj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gzhubu.top/Article/details/gtbahmyftb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhiwuduotai.top/Article/details/gtmsgsgrrm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.chenlongwang.top/Article/details/gtxrrilejw.html

[E15] HTML 转义 / 反转义
来源：http://dali.shzxlz.cn/Article/details/gtizwiveav.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj202588.top/Article/details/gtpzjdnwma.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zycfv.cn/Article/details/gtnnygoyqj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.0kj1m.cn/Article/details/gtdbynbqus.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gzhubu.top/Article/details/gthhwqxmrt.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.0kj1m.cn/Article/details/gtchfttrap.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xuanzx.com/Article/details/gtqiazghfe.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.aizwys.cn/Article/details/gtoeenmqhh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yj202588.top/Article/details/gttlfhilet.html

[E16] 数字千分位
来源：http://dali.snrcjt.cn/Article/details/gtwsrmcxdn.html

Py:   f"{1234567:,}"
来源：http://dali.ivvv.top/Article/details/gtubnqrxmq.html

PHP:  number_format(1234567);
来源：http://dali.hammf.cn/Article/details/gtxfmezkgm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sxryk.cn/Article/details/gtfdskimbf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxinkj.top/Article/details/gtmsyzsndp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gtafrbelbw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xuanzx.com/Article/details/gtwekqbwvz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yongpay.top/Article/details/gtpevaseph.html

C#:   1234567.ToString("N0")
来源：http://dali.tianlin.xyz/Article/details/gtnhnzigjj.html

[E17] 首字母大写
来源：http://dali.hnxiangtu.top/Article/details/gtqkecxrvc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yj202588.top/Article/details/gtuhiianxe.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.guowangkeji.top/Article/details/gtipmsfouw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ivvv.top/Article/details/gtrlhfaugk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.aibaodan.cn/Article/details/gtwantcgxu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.vqdsnc.cn/Article/details/gtqccnylbl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gogol.net.cn/Article/details/gtuzivrgxr.html

Ruby: s.capitalize
来源：http://dali.hywenlv.cn/Article/details/gteofzdzti.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jyoumei.cn/Article/details/gttpseljbu.html

[E18] 模板占位符替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdevdiirg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.mhx1999.top/Article/details/gtmyjiudpw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.nwbrower.top/Article/details/gtypzfummt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cheryme.top/Article/details/gtntiqlmjj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gthlczybsu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gtvepypbqw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nwbrower.top/Article/details/gtdjwsjlzx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jqgfzy.top/Article/details/gtipdciwqm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cheryme.top/Article/details/gtsqvxbbfm.html

[E19] 多行文本按行拆分
来源：http://dali.yj20258.top/Article/details/gtqpfhnfcf.html

Py:   s.splitlines()
来源：http://dali.pengpengdd.cyou/Article/details/gtohqmmiem.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jiagoushi.top/Article/details/gtrxvwwiqw.html

JS:   s.split(/\r?\n/)
来源：http://dali.mhx1999.top/Article/details/gtrvddbdeo.html

TS:   s.split(/\r?\n/)
来源：http://dali.yj202588.top/Article/details/gtmlwktgxl.html

Java: s.lines().toList()
来源：http://dali.ivvv.top/Article/details/gtzzrigteo.html

Go:   strings.Split(s, "\n")
来源：http://dali.meibo888.top/Article/details/gtqzzfmfdm.html

Ruby: s.lines
来源：http://dali.meibo888.top/Article/details/gtfegvqrhe.html

C#:   s.Split('\n')
来源：http://dali.birdmap.top/Article/details/gtsbmiivsv.html

[E20] 判断字符串是否为空
来源：http://dali.zhongyouzk.top/Article/details/gtxsymckhk.html

Py:   if not s:
来源：http://dali.shanyushiyangtech.top/Article/details/gtgeolhvlz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.mhx1999.top/Article/details/gtcmpcmdfq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtzidwfbjz.html

TS:   if (s === "") {}
来源：http://dali.shangyingyoupin.top/Article/details/gtfcxiyelx.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhongyouzk.top/Article/details/gtxlzrsctp.html

Go:   if s == "" {}
来源：http://dali.daxiang520.top/Article/details/gtikoygirp.html

Ruby: if s.empty?
来源：http://dali.haohaochexian.top/Article/details/gtwrbvddui.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.tian-w.cn/Article/details/gtttemdbmi.html

[E21] 超长截断加省略号
来源：http://dali.feifeiyinyue.top/Article/details/gtzijqbpib.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.pycfn.com/Article/details/gtlayypdgx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gtjlbxvfqo.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gtblmzjged.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gtcosbqmco.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.pycfn.com/Article/details/gtbvlyyefb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yueranfly.top/Article/details/gtnnqkszfo.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtyhpzjkca.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtruuydfvg.html

[E22] 字节长度与字符长度
来源：http://dali.tanke756.top/Article/details/gtemmuoahp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.havefunace.top/Article/details/gthjnbklgg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yongpay.top/Article/details/gtyhxsaaxz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.snrcjt.cn/Article/details/gtjcnnszjt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dianchejie.cn/Article/details/gtzvxhozid.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cqqwz.cn/Article/details/gtlpoywhaw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nanxuanxn.top/Article/details/gtlpwpxsyc.html

Ruby: s.bytesize;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gtlvghkpwk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinqigfzy.top/Article/details/gtvaffjwgx.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtwpxoudjp.html

F. 文件与目录
来源：http://dali.snrcjt.cn/Article/details/gtlqwaysnb.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtqrovlmbo.html

[F01] 读取整个文件
来源：http://dali.haohaochexian.top/Article/details/gtvdcfssel.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.fengsongda.top/Article/details/gtvlklnyoy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtjksmxvmt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cucudq.cn/Article/details/gtlclarhdo.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hammf.cn/Article/details/gttusvwkye.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gtggvoxxqt.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sysykeji.top/Article/details/gtkiatsgtm.html

Ruby: File.read("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtpevieank.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtgkjfbqge.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gtsyybwsrg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.havefunace.top/Article/details/gtfyxbxvyt.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.daria6918.cn/Article/details/gtxwgvzbfq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuxming.cn/Article/details/gtyjjzeiiw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zdqjudy.top/Article/details/gtvgeydjni.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zycfv.cn/Article/details/gtbzgvlmng.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yj20258888.top/Article/details/gtlvkfyzvm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.0kj1m.cn/Article/details/gtlrddydxx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shangyingyoupin.top/Article/details/gtkiegtgqr.html

[F03] 写入文件（覆盖）
来源：http://dali.pengpengdd.cyou/Article/details/gtpkkhokfg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.redwolf501.top/Article/details/gtgjmtyyef.html


<!-- 参考信息 -->