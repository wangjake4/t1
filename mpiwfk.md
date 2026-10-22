代发 wailian999

[D19] 按字段分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtckdycfmy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yonumen.top/Article/details/gtmmqdbtal.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.redwolf501.top/Article/details/gtzgpfwbjx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.aibaodan.cn/Article/details/gthddntrle.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.fzhhl.top/Article/details/gtbjxmimpy.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sweek.top/Article/details/gtdvjsrprw.html

Go:   // 手写 map[string][]T
来源：http://dali.chenzaomai.com/Article/details/gtxamyscda.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.dashuyun.cn/Article/details/gtatoolfwo.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.haohaochexian.top/Article/details/gtoiqwjnwr.html

[D20] 统计每个元素出现次数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdmzpzvwa.html

Py:   Counter(arr)
来源：http://dali.aizwys.cn/Article/details/gtehsrxugo.html

PHP:  array_count_values($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtprwhuafm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.quarkkingdee.top/Article/details/gtsemoecxz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hammf.cn/Article/details/gtzegckyzu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gaohongyu789.top/Article/details/gtnzojyoad.html

Go:   // 手写 map[T]int
来源：http://dali.chenzaomai.com/Article/details/gtcwmpattx.html

Ruby: arr.tally
来源：http://dali.sysykeji.top/Article/details/gtsxypwuaz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhengqikj.top/Article/details/gtemqsgmvb.html

[D21] 判断是否包含某元素
来源：http://dali.0kj1m.cn/Article/details/gturbbmvoe.html

Py:   x in arr
来源：http://dali.xuanzx.com/Article/details/gtrnmabvdt.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sweek.top/Article/details/gtdiwlqjqj.html

JS:   arr.includes(x)
来源：http://dali.tianlin.xyz/Article/details/gtihgcxdnh.html

TS:   arr.includes(x)
来源：http://dali.nanxuanxn.top/Article/details/gttwsgonel.html

Java: list.contains(x)
来源：http://dali.sufxvd.cn/Article/details/gtanoxepfo.html

Go:   slices.Contains(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtrzmktjix.html

Ruby: arr.include?(x)
来源：http://dali.haohaochexian.top/Article/details/gtvqthqxsk.html

C#:   list.Contains(x)
来源：http://dali.jyoumei.cn/Article/details/gtqmztwmbk.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jiagoushi.top/Article/details/gtvpihfyhs.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttnzdomzi.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yangfankeji.com/Article/details/gthuotxgez.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ydzc1.top/Article/details/gtpekhnvvb.html

TS:   [...arr];
来源：http://dali.kuanghao11.cn/Article/details/gttmspyhed.html

Java: new ArrayList<>(list);
来源：http://dali.zhongyouzk.top/Article/details/gtbvhfrktq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yuanzhike.top/Article/details/gtudukjlbf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yueranfly.top/Article/details/gtzrcmfqtt.html

C#:   new List<int>(list);
来源：http://dali.yongpay.top/Article/details/gtslsjgvdy.html

[D23] reduce 累积计算
来源：http://dali.hnxiangtu.top/Article/details/gtgceqrhtt.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ppjwa.cn/Article/details/gtizsyufsv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtudxwripc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tian-w.cn/Article/details/gtarpdorzq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtktttmwbb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xylfe.cn/Article/details/gtcwhropbt.html

Go:   // 手写循环
来源：http://dali.xinyue.icu/Article/details/gtgymbdqfq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yonumen.top/Article/details/gtrwjayram.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.birdmap.top/Article/details/gtlqbjbrnq.html

[D24] 字典 / Map 基本操作
来源：http://dali.nwbrower.top/Article/details/gtioihavcd.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.havefunace.top/Article/details/gtxfsithli.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xinyue.icu/Article/details/gtggggrfum.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.daxiang520.top/Article/details/gtbdjfrjsb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.wangdashe.top/Article/details/gtxhdvwyeo.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.birdmap.top/Article/details/gthlsxftvi.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtogwvwqoi.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cqqwz.cn/Article/details/gtguaoujlo.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yueranfly.top/Article/details/gtuuuofmfm.html

[D25] Set 集合去重与交并差
来源：http://dali.316326.xyz/Article/details/gtwwfnwtrh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.nanxinkj.top/Article/details/gteacxfvmy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zdqjudy.top/Article/details/gtuqtcvmst.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sufxvd.cn/Article/details/gtkcxrfcwq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.haohaochexian.top/Article/details/gtvdvmjcli.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yongpay.top/Article/details/gtfznmwhfz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cheryme.top/Article/details/gtftdulfjk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shuidangran.top/Article/details/gtykewoqxg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.chenlongwang.top/Article/details/gttnglqtro.html

[D26] 数组转字符串
来源：http://dali.birdmap.top/Article/details/gtlocbziij.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhiwuduotai.top/Article/details/gtkuzjwrub.html

PHP:  implode(", ", $arr);
来源：http://dali.ydzc1.top/Article/details/gtnhfvgydy.html

JS:   arr.join(", ")
来源：http://dali.nanxuanxn.top/Article/details/gtihhnyqof.html

TS:   arr.join(", ")
来源：http://dali.sysykeji.top/Article/details/gtrmkxnuke.html

Java: String.join(", ", list)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqxxxmvee.html

Go:   strings.Join(strs, ", ")
来源：http://dali.havefunace.top/Article/details/gtwxwcskfu.html

Ruby: arr.join(", ")
来源：http://dali.chenzaomai.com/Article/details/gtqdgzzqkc.html

C#:   string.Join(", ", list)
来源：http://dali.yuxming.cn/Article/details/gtgouidckw.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtecaqcclx.html

E. 字符串处理
来源：http://dali.aizwys.cn/Article/details/gtdzvxyxqy.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtgvizajjj.html

[E01] 拼接字符串
来源：http://dali.hysaishi.cn/Article/details/gtaznlxrcv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.havefunace.top/Article/details/gtayeepcyz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hnqzz.top/Article/details/gttvbcqmet.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xylfe.cn/Article/details/gtirjjxspv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhongyouzk.top/Article/details/gtlilxqwto.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.kuanghao11.cn/Article/details/gtnsuicora.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.pycfn.com/Article/details/gtqrkvkufv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zycfv.cn/Article/details/gtmgtrmukz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gtjmtvxnog.html

[E02] 重复字符串
来源：http://dali.hnqzz.top/Article/details/gtofpbdczl.html

Py:   "ab" * 3
来源：http://dali.shanyushiyangtech.top/Article/details/gtkmethtkm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtokflgvss.html

JS:   "ab".repeat(3)
来源：http://dali.guowangkeji.top/Article/details/gtadsgnsjz.html

TS:   "ab".repeat(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtrkfpxouv.html

Java: "ab".repeat(3)
来源：http://dali.jqgufenzy.top/Article/details/gthoneafij.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.daria6918.cn/Article/details/gtevuandgp.html

Ruby: "ab" * 3
来源：http://dali.ehwqpu.com/Article/details/gtpsxsrvbh.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenzaomai.com/Article/details/gtqcbxxncn.html

[E03] 截取子串
来源：http://dali.haohaochexian.top/Article/details/gtvlzmcjqv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ehwqpu.com/Article/details/gtmjqrdlce.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gtjtokfjid.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqmybmqoe.html

TS:   s.slice(1, 4)
来源：http://dali.jinqigufen.top/Article/details/gtkvyydwqa.html

Java: s.substring(1, 4)
来源：http://dali.havefunace.top/Article/details/gtztxijnjf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenzaomai.com/Article/details/gtcadhncpy.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.fzhhl.top/Article/details/gtrofceyoy.html

C#:   s.Substring(1, 3)
来源：http://dali.cheryme.top/Article/details/gtykuqjcne.html

[E04] 查找子串位置
来源：http://dali.andypj.xyz/Article/details/gthnxsgkkr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.aizwys.cn/Article/details/gtgzpryxew.html

PHP:  strpos($s, "x");
来源：http://dali.meibo888.top/Article/details/gtksjhhodq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.wangshuangyany.cn/Article/details/gtujfftwju.html

TS:   s.indexOf("x")
来源：http://dali.wangdashe.top/Article/details/gturcznbhc.html

Java: s.indexOf("x")
来源：http://dali.xuanzx.com/Article/details/gtxbjrpmol.html

Go:   strings.Index(s, "x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrrrvpsbn.html

Ruby: s.index("x")
来源：http://dali.shzxlz.cn/Article/details/gtbixtiwyt.html

C#:   s.IndexOf("x")
来源：http://dali.zdqjudy.top/Article/details/gtfeurixrw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.nwbrower.top/Article/details/gtnkhilzsv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.dianchejie.cn/Article/details/gtsptvmclv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yvedp.cn/Article/details/gtiagnrhii.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.mhx1999.top/Article/details/gtjdgconnu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.snrcjt.cn/Article/details/gtjgsrfxuh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zdqjudy.top/Article/details/gtwastuxiv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xuetiantiany.cn/Article/details/gtqwwcsynt.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.redwolf501.top/Article/details/gtarnltoqm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.dianchejie.cn/Article/details/gteiylndkj.html

[E06] 替换子串
来源：http://dali.ppjwa.cn/Article/details/gtcpnftmmo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtieecoopf.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtrlpnzqfl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cheryme.top/Article/details/gtcuqqkhsf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmtciaoun.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtmpzyzbpb.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gzhubu.top/Article/details/gtlnrgzxmh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtbkhhbvas.html

C#:   s.Replace("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwheuvqvf.html

[E07] 按分隔符拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gtzzbtcfpc.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhengqikj.top/Article/details/gtykqufyop.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtmlxxsbcc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sufxvd.cn/Article/details/gtrhjlxjjw.html

TS:   s.split(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjnvnqtnv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cheryme.top/Article/details/gtwpyqxhqc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hfpthk.cn/Article/details/gtgjvbnndn.html

Ruby: s.split(",");  s.split
来源：http://dali.hammf.cn/Article/details/gtnnayzscg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sweek.top/Article/details/gtdbkejsje.html

[E08] 数组按分隔符合并
来源：http://dali.cucudq.cn/Article/details/gtrglpwjbt.html

Py:   ",".join(items)
来源：http://dali.bjfxy.top/Article/details/gtuenamsyp.html

PHP:  implode(",", $items);
来源：http://dali.yanxiufei.cn/Article/details/gtpitcosfx.html

JS:   items.join(",")
来源：http://dali.yvedp.cn/Article/details/gtmhgnkuus.html

TS:   items.join(",")
来源：http://dali.yvedp.cn/Article/details/gtaljwrdkw.html

Java: String.join(",", items)
来源：http://dali.jinqigfzy.top/Article/details/gtalkayyba.html

Go:   strings.Join(items, ",")
来源：http://dali.mhx1999.top/Article/details/gtjnnmqynv.html

Ruby: items.join(",")
来源：http://dali.hywenlv.cn/Article/details/gtrrqjodjg.html

C#:   string.Join(",", items)
来源：http://dali.fengsongda.top/Article/details/gtfcqiaynb.html

[E09] 去除所有空白字符
来源：http://dali.meibo888.top/Article/details/gtlndewscs.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.tian-w.cn/Article/details/gtjxdnumzm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtamoaxdzt.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yuxming.cn/Article/details/gttlvahzce.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yangfankeji.com/Article/details/gtpghrdgrv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.iojbl.cn/Article/details/gtgymguazz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yuanzhike.top/Article/details/gtnmhzdefd.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gaohongyu789.top/Article/details/gtsuwkrlaa.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cashguo.top/Article/details/gtvtmbsjqy.html

[E10] 左侧补零 / 定长填充
来源：http://dali.nanxinkj.top/Article/details/gtzghcunxy.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.daria6918.cn/Article/details/gtjmfculkw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.havefunace.top/Article/details/gtkbmkoazr.html

JS:   "7".padStart(3, "0")
来源：http://dali.c1oappe.top/Article/details/gtrtiqewxg.html

TS:   "7".padStart(3, "0")
来源：http://dali.xziqi.cn/Article/details/gttmibeuzw.html

Java: String.format("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gtzpbvsrvl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yvedp.cn/Article/details/gtvufxlqfc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinqigufen.top/Article/details/gttgbhieqi.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.iojbl.cn/Article/details/gtmlxbycgk.html

[E11] 反转字符串
来源：http://dali.zhixingplan.top/Article/details/gtplhwflgg.html

Py:   s[::-1]
来源：http://dali.jinqigfzy.top/Article/details/gtwgszpshx.html

PHP:  strrev($s);
来源：http://dali.ydzc1.top/Article/details/gteevnmeax.html

JS:   [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gtdvfdqupv.html

TS:   [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gteawmukdu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shzxlz.cn/Article/details/gtklesuvqu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.aizwys.cn/Article/details/gthywutkee.html

Ruby: s.reverse
来源：http://dali.guannengcc.top/Article/details/gtcnzdkmzx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gzhubu.top/Article/details/gtugopwvrf.html

[E12] 统计某字符出现次数
来源：http://dali.yangfankeji.com/Article/details/gtvipzqlwf.html

Py:   s.count("a")
来源：http://dali.hongshengwenyu.top/Article/details/gtwxyistxl.html

PHP:  substr_count($s, "a");
来源：http://dali.wangdashe.top/Article/details/gteztyvptx.html

JS:   s.split("a").length - 1
来源：http://dali.svipenyu.cn/Article/details/gthwdpotda.html

TS:   s.split("a").length - 1
来源：http://dali.xziqi.cn/Article/details/gtchshgfvx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.quarkkingdee.top/Article/details/gtbdlugerf.html

Go:   strings.Count(s, "a")
来源：http://dali.jyoumei.cn/Article/details/gtmvzzdmtr.html

Ruby: s.count("a")
来源：http://dali.hysaishi.cn/Article/details/gtjuekisar.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhongyouzk.top/Article/details/gtcxyzppmf.html

[E13] 逐字符遍历
来源：http://dali.smart0.xyz/Article/details/gtbyrbullb.html

Py:   for ch in s: print(ch)
来源：http://dali.ydzc1.top/Article/details/gtodkyzvha.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sxryk.cn/Article/details/gtxfiaazhp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258.top/Article/details/gtvywyhrek.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gotoacloud.top/Article/details/gtjhswgoxe.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.havefunace.top/Article/details/gtmnecirrv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenlongwang.top/Article/details/gtokamjjej.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ehwqpu.com/Article/details/gtlecnvutp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gtcnrbwmfz.html

[E14] URL 编码与 Base64
来源：http://dali.quarkkingdee.top/Article/details/gtgqcjppmf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.wangshuangyany.cn/Article/details/gtvszfstdd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.wangshuangyany.cn/Article/details/gttpxvtzun.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.haohaochexian.top/Article/details/gtgwxaxgxt.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.quarkkingdee.top/Article/details/gtqqgjekmb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gzhubu.top/Article/details/gtfjlwkhvw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.havefunace.top/Article/details/gtdzaxraov.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yangfankeji.com/Article/details/gtrewtvndg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zycfv.cn/Article/details/gtlwlioale.html

[E15] HTML 转义 / 反转义
来源：http://dali.yj20258888.top/Article/details/gtpyyhphdh.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtizssudot.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtnkysqoja.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkfoeyvxe.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cashguo.top/Article/details/gtjfxijjyj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.smart0.xyz/Article/details/gtrutzmjot.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.dianchejie.cn/Article/details/gtklgdrhcq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hfpthk.cn/Article/details/gthyfbkpvs.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jianghu66.top/Article/details/gtykfcogau.html

[E16] 数字千分位
来源：http://dali.zhixingplan.top/Article/details/gtuocnzbho.html

Py:   f"{1234567:,}"
来源：http://dali.c1oappe.top/Article/details/gtehlkxuvy.html

PHP:  number_format(1234567);
来源：http://dali.yj20258.top/Article/details/gtnelbhodb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258.top/Article/details/gtpmsfdmza.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tanke756.top/Article/details/gtwtufvtnz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.316326.xyz/Article/details/gtsxxbdwow.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cdnleiting.top/Article/details/gtzimajosk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ppjwa.cn/Article/details/gtqdyjugop.html

C#:   1234567.ToString("N0")
来源：http://dali.kuanghao11.cn/Article/details/gtddjrmwzr.html

[E17] 首字母大写
来源：http://dali.zdqjudy.top/Article/details/gtykoctqql.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.pengpengdd.cyou/Article/details/gtlhpkowgi.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.kuanghao11.cn/Article/details/gtmnxpxynw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yanxiufei.cn/Article/details/gtpjnmvwmk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgufenzy.top/Article/details/gtttxrdosz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjkbvdoyq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.guannengcc.top/Article/details/gtrxwaupuu.html

Ruby: s.capitalize
来源：http://dali.mhx1999.top/Article/details/gtolqqpqhz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhongyouzk.top/Article/details/gtkpshkcdn.html

[E18] 模板占位符替换
来源：http://dali.sweek.top/Article/details/gtjiuqnhco.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sweek.top/Article/details/gtdurnnibu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ydzc1.top/Article/details/gtzbfmtfao.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.aizwys.cn/Article/details/gtbsoupbrn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gthknnysmw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gtuyighous.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgvixifck.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yanxiufei.cn/Article/details/gtjshmrhlj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.chenzaomai.com/Article/details/gtothftvaz.html

[E19] 多行文本按行拆分
来源：http://dali.shzxlz.cn/Article/details/gtbebfqlje.html

Py:   s.splitlines()
来源：http://dali.hywenlv.cn/Article/details/gtskcupnvf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xuanzx.com/Article/details/gtyldentvn.html

JS:   s.split(/\r?\n/)
来源：http://dali.smart0.xyz/Article/details/gtrwcnnxou.html

TS:   s.split(/\r?\n/)
来源：http://dali.havefunace.top/Article/details/gtgedhhbcr.html

Java: s.lines().toList()
来源：http://dali.hammf.cn/Article/details/gtiypqxxob.html

Go:   strings.Split(s, "\n")
来源：http://dali.316326.xyz/Article/details/gtghfjkvgu.html

Ruby: s.lines
来源：http://dali.ydzc1.top/Article/details/gtttcnddqa.html

C#:   s.Split('\n')
来源：http://dali.jinqigfzy.top/Article/details/gtjbxakxnc.html

[E20] 判断字符串是否为空
来源：http://dali.jinqigfzy.top/Article/details/gtfdqxzmyg.html

Py:   if not s:
来源：http://dali.chenjidiqi.icu/Article/details/gtqbuwjfvw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xinyue.icu/Article/details/gtdahtjshd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jqgfzy.top/Article/details/gtgbjyyawd.html

TS:   if (s === "") {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaipaekzd.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhongyouzk.top/Article/details/gtmpssoqad.html

Go:   if s == "" {}
来源：http://dali.chenzaomai.com/Article/details/gtgorkumng.html

Ruby: if s.empty?
来源：http://dali.shanyushiyangkeji.top/Article/details/gtucaycrfj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gogol.net.cn/Article/details/gtjrgkuneq.html

[E21] 超长截断加省略号
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoifcxknh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtszjflnwy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.havefunace.top/Article/details/gtyrdaitlf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtthpsjmmn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gtmofqhugi.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gtrctjfwua.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.chenjidiqi.icu/Article/details/gtsmtilmny.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtdirrjyoh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.havefunace.top/Article/details/gthfdgldoh.html

[E22] 字节长度与字符长度
来源：http://dali.shangyingyoupin.top/Article/details/gtydbgfxky.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tian-w.cn/Article/details/gtbsbhqvtf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gtjzeseorc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.haohaochexian.top/Article/details/gtrmgrldlo.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.redwolf501.top/Article/details/gtyfaxoxxb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yj20258888.top/Article/details/gtnmesdxid.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.fengsongda.top/Article/details/gtfeegstpd.html

Ruby: s.bytesize;  s.length
来源：http://dali.c1oappe.top/Article/details/gttwwkkmzr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.redwolf501.top/Article/details/gtbomjdole.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtbnybntzm.html

F. 文件与目录
来源：http://dali.zhoulong.xyz/Article/details/gtnstonwzx.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtabxblnmq.html

[F01] 读取整个文件
来源：http://dali.hnqzz.top/Article/details/gtdtqkihko.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.fengsongda.top/Article/details/gtmzroxagr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hammf.cn/Article/details/gtpxwhwbrg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.nanxuanxn.top/Article/details/gtjteudvgu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gtqxqajtku.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gtnrdqmgxf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.kuanghao11.cn/Article/details/gtywzvrwqn.html

Ruby: File.read("a.txt")
来源：http://dali.shuidangran.top/Article/details/gthlmspthm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yj202588.top/Article/details/gtdedemtul.html

[F02] 逐行读取文件
来源：http://dali.pengpengdd.cyou/Article/details/gtgophckbd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jqgfzy.top/Article/details/gtucugvpki.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.feifeiyinyue.top/Article/details/gtauszbiei.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yongpay.top/Article/details/gtogrlgfec.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnqzz.top/Article/details/gtugrulomn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.andypj.xyz/Article/details/gtoistcssr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yueranfly.top/Article/details/gtbnjrgxns.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shuidangran.top/Article/details/gtgrgyvpya.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gogol.net.cn/Article/details/gtzyeohncp.html

[F03] 写入文件（覆盖）
来源：http://dali.sufxvd.cn/Article/details/gtlszywpbm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hysaishi.cn/Article/details/gtfdgstowz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hywenlv.cn/Article/details/gtpmuwjekt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.iojbl.cn/Article/details/gttqpmrydx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.andypj.xyz/Article/details/gtnmbeyadw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gtklhhxycl.html


<!-- 参考信息 -->