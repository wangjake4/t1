代发 wailian999

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yj202588.top/Article/details/gttmispyoh.html

Go:   // 手写双层循环
来源：http://dali.cucudq.cn/Article/details/gtbxnhcssm.html

Ruby: nested.flatten
来源：http://dali.yj20258888.top/Article/details/gtkqjrafim.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xylfe.cn/Article/details/gtykrswojx.html

[D19] 按字段分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkokjrcdr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.aibaodan.cn/Article/details/gtlmddfxwq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xuetiantiany.cn/Article/details/gthbomnews.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jiagoushi.top/Article/details/gtswofkeom.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.daria6918.cn/Article/details/gtpquphrfi.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhongyouzk.top/Article/details/gtvuhauvec.html

Go:   // 手写 map[string][]T
来源：http://dali.gaohongyu789.top/Article/details/gtgpsrnsbx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sufxvd.cn/Article/details/gtvncrjmxw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.daria6918.cn/Article/details/gtgtpcuyar.html

[D20] 统计每个元素出现次数
来源：http://dali.xziqi.cn/Article/details/gtcssjoqry.html

Py:   Counter(arr)
来源：http://dali.guannengcc.top/Article/details/gtodfauxrm.html

PHP:  array_count_values($arr);
来源：http://dali.zdqjudy.top/Article/details/gtezwouayf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sweek.top/Article/details/gtqwyhoirk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daxiang520.top/Article/details/gthknluclq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.pycfn.com/Article/details/gtjyruxtiz.html

Go:   // 手写 map[T]int
来源：http://dali.jiagoushi.top/Article/details/gtazimqjho.html

Ruby: arr.tally
来源：http://dali.zhengqikj.top/Article/details/gtbjknlcwv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.feifeiyinyue.top/Article/details/gtymjepulf.html

[D21] 判断是否包含某元素
来源：http://dali.havefunace.top/Article/details/gtpyrzjrga.html

Py:   x in arr
来源：http://dali.0kj1m.cn/Article/details/gtkjwupvlz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yueranfly.top/Article/details/gtunjrgskq.html

JS:   arr.includes(x)
来源：http://dali.chenzaomai.com/Article/details/gtedjiopsx.html

TS:   arr.includes(x)
来源：http://dali.9152youxi.cn/Article/details/gtjdvvyyzu.html

Java: list.contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gtwtebquby.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtccalbnxg.html

Ruby: arr.include?(x)
来源：http://dali.zhongyouzk.top/Article/details/gtrggkvjfb.html

C#:   list.Contains(x)
来源：http://dali.dashuyun.cn/Article/details/gthdypciul.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhoulong.xyz/Article/details/gtidojietb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtwybvnico.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.fzhhl.top/Article/details/gtqejuderg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yangfankeji.com/Article/details/gtdhgbygzb.html

TS:   [...arr];
来源：http://dali.sxryk.cn/Article/details/gtvoxegboc.html

Java: new ArrayList<>(list);
来源：http://dali.yj20258888.top/Article/details/gtirzxwdjl.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.meibo888.top/Article/details/gtbeexxqyj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.quarkkingdee.top/Article/details/gtqcxcxftk.html

C#:   new List<int>(list);
来源：http://dali.chenlongwang.top/Article/details/gteyqczxmv.html

[D23] reduce 累积计算
来源：http://dali.cdnleiting.top/Article/details/gtcvqeqkfh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.smart0.xyz/Article/details/gtsjgbnxui.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.chenlongwang.top/Article/details/gtjrogbawd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.andypj.xyz/Article/details/gtnqsevwaz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj202588.top/Article/details/gtzjvfoood.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtntfcwbxi.html

Go:   // 手写循环
来源：http://dali.chenlongwang.top/Article/details/gtwrrwjfmn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj20258888.top/Article/details/gtzmgzsise.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gogol.net.cn/Article/details/gtcpmwoqip.html

[D24] 字典 / Map 基本操作
来源：http://dali.meibo888.top/Article/details/gtshvredlc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hnqzz.top/Article/details/gtxzxusgqo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yuanzhike.top/Article/details/gtvwdjwmdx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hnxiangtu.top/Article/details/gtzqgblgek.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gtysrbfefh.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xinyue.icu/Article/details/gtfurvkgtd.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinqigufen.top/Article/details/gtibsxtvxk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.aizwys.cn/Article/details/gtulrrotac.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenjidiqi.icu/Article/details/gtjjlcmmae.html

[D25] Set 集合去重与交并差
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfyqblrfz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yvedp.cn/Article/details/gtomoqwnds.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.chenzaomai.com/Article/details/gtgrkbdhlj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhoulong.xyz/Article/details/gtdycqtxfo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.gotoacloud.top/Article/details/gtklgyyglo.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.pycfn.com/Article/details/gtezyoqzfy.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.smart0.xyz/Article/details/gtbbkuxaiu.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhoulong.xyz/Article/details/gtfxgkjxyh.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.0kj1m.cn/Article/details/gtyseqqmbz.html

[D26] 数组转字符串
来源：http://dali.ivvv.top/Article/details/gtdlziihlr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ybcxt.top/Article/details/gtsfljcerv.html

PHP:  implode(", ", $arr);
来源：http://dali.cucudq.cn/Article/details/gtedxruyyz.html

JS:   arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gtfzapjihn.html

TS:   arr.join(", ")
来源：http://dali.iojbl.cn/Article/details/gtcaeqbmod.html

Java: String.join(", ", list)
来源：http://dali.andypj.xyz/Article/details/gtgzbvsebi.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gzhubu.top/Article/details/gteixemgih.html

Ruby: arr.join(", ")
来源：http://dali.hysaishi.cn/Article/details/gtqijifrec.html

C#:   string.Join(", ", list)
来源：http://dali.gogol.net.cn/Article/details/gtnfgrjkuy.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtvlipnojt.html

E. 字符串处理
来源：http://dali.jinqigfzy.top/Article/details/gtaqzrlrin.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtfshynuwa.html

[E01] 拼接字符串
来源：http://dali.redwolf501.top/Article/details/gtvxfcuztc.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ybcxt.top/Article/details/gtsqmpzvnh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtheolnupn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnxiangtu.top/Article/details/gttoiozkap.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ydzc1.top/Article/details/gtcooixbeh.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tian-w.cn/Article/details/gtkzjbvvyh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jiagoushi.top/Article/details/gtnqupfdai.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hammf.cn/Article/details/gtmsenszpc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtcpnpzikt.html

[E02] 重复字符串
来源：http://dali.daria6918.cn/Article/details/gteznrpgav.html

Py:   "ab" * 3
来源：http://dali.shzxlz.cn/Article/details/gtlcpustny.html

PHP:  str_repeat("ab", 3);
来源：http://dali.haohaochexian.top/Article/details/gtjsogntky.html

JS:   "ab".repeat(3)
来源：http://dali.cdnleiting.top/Article/details/gtcaepkljb.html

TS:   "ab".repeat(3)
来源：http://dali.hysaishi.cn/Article/details/gtlqjecsrg.html

Java: "ab".repeat(3)
来源：http://dali.zhoulong.xyz/Article/details/gtcrfswxda.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.chenjidiqi.icu/Article/details/gtgmlzfoyj.html

Ruby: "ab" * 3
来源：http://dali.hnxiangtu.top/Article/details/gtjcimbsum.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hnqzz.top/Article/details/gtpgmyimnx.html

[E03] 截取子串
来源：http://dali.iojbl.cn/Article/details/gtnqpyudyg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gzhubu.top/Article/details/gterrbsasa.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cheryme.top/Article/details/gtljoywwej.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gtfeswbcqg.html

TS:   s.slice(1, 4)
来源：http://dali.jqgufenzy.top/Article/details/gtjuiqclqi.html

Java: s.substring(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gtllavbzyf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xuetiantiany.cn/Article/details/gtrnodelmm.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cucudq.cn/Article/details/gtngwgojoi.html

C#:   s.Substring(1, 3)
来源：http://dali.cqqwz.cn/Article/details/gtowkqstti.html

[E04] 查找子串位置
来源：http://dali.havefunace.top/Article/details/gtxfhyfvdh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.tanke756.top/Article/details/gtrofijito.html

PHP:  strpos($s, "x");
来源：http://dali.jqgfzy.top/Article/details/gthvnvcltn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sufxvd.cn/Article/details/gtgsosnphr.html

TS:   s.indexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfohfywce.html

Java: s.indexOf("x")
来源：http://dali.hnxiangtu.top/Article/details/gtnuuovthl.html

Go:   strings.Index(s, "x")
来源：http://dali.vqdsnc.cn/Article/details/gtagcyxyun.html

Ruby: s.index("x")
来源：http://dali.shuidangran.top/Article/details/gtdlebboze.html

C#:   s.IndexOf("x")
来源：http://dali.gogol.net.cn/Article/details/gthgwokjlm.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ybcxt.top/Article/details/gtrgholvcr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.redwolf501.top/Article/details/gtfwqxrjod.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.andypj.xyz/Article/details/gtdlvcclzq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sweek.top/Article/details/gtnxswzafl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.nanxuanxn.top/Article/details/gtjdpdzzqh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuxming.cn/Article/details/gtvjhbrbkh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yongpay.top/Article/details/gtblcempsx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.nanxinkj.top/Article/details/gttucrxspv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.dashuyun.cn/Article/details/gtztgedwqv.html

[E06] 替换子串
来源：http://dali.aibaodan.cn/Article/details/gtrmtwlfzo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jyoumei.cn/Article/details/gtvxegrgrm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cheryme.top/Article/details/gtvqylhkjf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gttxknfpgd.html

TS:   s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtgmoqvtzh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtmvkiemxz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.snrcjt.cn/Article/details/gtggebdvqh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtawoikbyu.html

C#:   s.Replace("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtwhhsqbsp.html

[E07] 按分隔符拆分
来源：http://dali.pengpengdd.cyou/Article/details/gtqxcapyap.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xziqi.cn/Article/details/gtetifvqhn.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zdqjudy.top/Article/details/gtcqyzudpz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj202588.top/Article/details/gtsbbidrmy.html

TS:   s.split(",")
来源：http://dali.dianchejie.cn/Article/details/gtliukhyha.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xuanzx.com/Article/details/gtfiuaumhs.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jqgufenzy.top/Article/details/gtrqxvfwqj.html

Ruby: s.split(",");  s.split
来源：http://dali.jqgufenzy.top/Article/details/gtwqtvfyvd.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.wangdashe.top/Article/details/gthmjyhhfh.html

[E08] 数组按分隔符合并
来源：http://dali.zhiwuduotai.top/Article/details/gtjkxcbvuy.html

Py:   ",".join(items)
来源：http://dali.sysykeji.top/Article/details/gtoqiymrkl.html

PHP:  implode(",", $items);
来源：http://dali.cashguo.top/Article/details/gtfzbibilh.html

JS:   items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gtjbnjuwyk.html

TS:   items.join(",")
来源：http://dali.cdnleiting.top/Article/details/gtpmvvskik.html

Java: String.join(",", items)
来源：http://dali.gzhubu.top/Article/details/gtvjlimsxv.html

Go:   strings.Join(items, ",")
来源：http://dali.xziqi.cn/Article/details/gtdsaoejgl.html

Ruby: items.join(",")
来源：http://dali.sweek.top/Article/details/gtoiktrhhk.html

C#:   string.Join(",", items)
来源：http://dali.daria6918.cn/Article/details/gtjlgjlhjh.html

[E09] 去除所有空白字符
来源：http://dali.daxiang520.top/Article/details/gtaxinfrpx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yj20258888.top/Article/details/gtmswvvfbb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.redwolf501.top/Article/details/gtdhrwhsim.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ehwqpu.com/Article/details/gtfnauerba.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.pycfn.com/Article/details/gtfqfwclwg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xylfe.cn/Article/details/gtswucrvxa.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.tian-w.cn/Article/details/gtzdgftmgu.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hysaishi.cn/Article/details/gtajbmyuht.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.haohaochexian.top/Article/details/gtkdngmxuj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.tianlin.xyz/Article/details/gtbfmxmofh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shangyingyoupin.top/Article/details/gtizubpcye.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shanyushiyangtech.top/Article/details/gthcwvrgqf.html

JS:   "7".padStart(3, "0")
来源：http://dali.xylfe.cn/Article/details/gtvsznbpkn.html

TS:   "7".padStart(3, "0")
来源：http://dali.yuxming.cn/Article/details/gtlyyyqlrh.html

Java: String.format("%03d", 7)
来源：http://dali.wangshuangyany.cn/Article/details/gtjkecsgxr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.pycfn.com/Article/details/gtqyfttarq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gtskjzgult.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtulfitfim.html

[E11] 反转字符串
来源：http://dali.gzhubu.top/Article/details/gtzuzhchzd.html

Py:   s[::-1]
来源：http://dali.aizwys.cn/Article/details/gtiofttwnh.html

PHP:  strrev($s);
来源：http://dali.nwbrower.top/Article/details/gtouorfbvc.html

JS:   [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gtwxnocxln.html

TS:   [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gtisidbxmz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenzaomai.com/Article/details/gtinqfteqz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hnxiangtu.top/Article/details/gtdohskqrs.html

Ruby: s.reverse
来源：http://dali.yongpay.top/Article/details/gtweqnexoi.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.fengsongda.top/Article/details/gtbigngqrm.html

[E12] 统计某字符出现次数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcaypswur.html

Py:   s.count("a")
来源：http://dali.nanxinkj.top/Article/details/gtwylgsgux.html

PHP:  substr_count($s, "a");
来源：http://dali.tian-w.cn/Article/details/gtuzysxkwh.html

JS:   s.split("a").length - 1
来源：http://dali.snrcjt.cn/Article/details/gtxjtarile.html

TS:   s.split("a").length - 1
来源：http://dali.fengsongda.top/Article/details/gtfgyyvwef.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.haohaochexian.top/Article/details/gthzlmtnnx.html

Go:   strings.Count(s, "a")
来源：http://dali.zhoulong.xyz/Article/details/gthvdawfgs.html

Ruby: s.count("a")
来源：http://dali.yvedp.cn/Article/details/gtqyxovijw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ybcxt.top/Article/details/gtyvjhsvyb.html

[E13] 逐字符遍历
来源：http://dali.ydzc1.top/Article/details/gtydbtyhou.html

Py:   for ch in s: print(ch)
来源：http://dali.cashguo.top/Article/details/gttzbxpjor.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hywenlv.cn/Article/details/gtfiradlhm.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gtvccutejc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sweek.top/Article/details/gtjlxlouxa.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yuanzhike.top/Article/details/gtcuueeuag.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yj20258888.top/Article/details/gtfjbqcuon.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jyoumei.cn/Article/details/gttlfijodh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gtjnbpazvv.html

[E14] URL 编码与 Base64
来源：http://dali.yj202588.top/Article/details/gtwkkemevt.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xylfe.cn/Article/details/gtgpqdsgor.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hywenlv.cn/Article/details/gtkbxwkebh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jlsjyb.cn/Article/details/gtfegrxbgp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtbyfkzvqu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjawlyzyj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jianghu66.top/Article/details/gtqkqnmtbv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhoulong.xyz/Article/details/gtqjdefedp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shangyingyoupin.top/Article/details/gttezlaxle.html

[E15] HTML 转义 / 反转义
来源：http://dali.xuetiantiany.cn/Article/details/gtldwgtzkz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.wangdashe.top/Article/details/gtwyrttcix.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yj20258888.top/Article/details/gtzyhyzqjs.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xuanzx.com/Article/details/gtxlbowaty.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gtcogybqsi.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cheryme.top/Article/details/gtmfytlvps.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.daria6918.cn/Article/details/gtvsiehnbh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shuidangran.top/Article/details/gtaxmhftvy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.daxiang520.top/Article/details/gtsrfjbqbx.html

[E16] 数字千分位
来源：http://dali.gogol.net.cn/Article/details/gtkoztbgnm.html

Py:   f"{1234567:,}"
来源：http://dali.jqgfzy.top/Article/details/gtoixppfok.html

PHP:  number_format(1234567);
来源：http://dali.jqgufenzy.top/Article/details/gtaxfuyokn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ydzc1.top/Article/details/gtjnsdiviq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xylfe.cn/Article/details/gttspqinon.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.sysykeji.top/Article/details/gttusuxhrx.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.smart0.xyz/Article/details/gtsmoqzwkh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yuanzhike.top/Article/details/gteavimzqq.html

C#:   1234567.ToString("N0")
来源：http://dali.zdqjudy.top/Article/details/gtklvbzvei.html

[E17] 首字母大写
来源：http://dali.yuxming.cn/Article/details/gtchhpwzpa.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sweek.top/Article/details/gtdcauqehv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zdqjudy.top/Article/details/gtfeypzioo.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.meibo888.top/Article/details/gtihhljqqz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjuqqtftu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ehwqpu.com/Article/details/gtraarwrdv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.mhx1999.top/Article/details/gtxvawegiu.html

Ruby: s.capitalize
来源：http://dali.jianghu66.top/Article/details/gtbbkiscwn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ehwqpu.com/Article/details/gtkdreiwct.html

[E18] 模板占位符替换
来源：http://dali.zhengqikj.top/Article/details/gtedunkjip.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinghuilouyu.cn/Article/details/gtabbjcnik.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhoulong.xyz/Article/details/gtyjpqpuwm.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ydzc1.top/Article/details/gtndjufozn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shuidangran.top/Article/details/gtmokvgonj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gthxjlpylh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gtwoqcusve.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.haohaochexian.top/Article/details/gtxsbgnjwp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.316326.xyz/Article/details/gtmtbudstv.html

[E19] 多行文本按行拆分
来源：http://dali.zhongyouzk.top/Article/details/gtsabteexf.html

Py:   s.splitlines()
来源：http://dali.xuanzx.com/Article/details/gtmslqmvse.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtkkqzsjsf.html

JS:   s.split(/\r?\n/)
来源：http://dali.haohaochexian.top/Article/details/gtswnckikj.html

TS:   s.split(/\r?\n/)
来源：http://dali.guannengcc.top/Article/details/gtkvnlfvvp.html

Java: s.lines().toList()
来源：http://dali.cucudq.cn/Article/details/gttgoklkiy.html

Go:   strings.Split(s, "\n")
来源：http://dali.jqgfzy.top/Article/details/gtwgaigvhl.html

Ruby: s.lines
来源：http://dali.gogol.net.cn/Article/details/gtawlxxsuj.html

C#:   s.Split('\n')
来源：http://dali.hammf.cn/Article/details/gtickpshah.html

[E20] 判断字符串是否为空
来源：http://dali.jinqigufen.top/Article/details/gtjazizwbo.html

Py:   if not s:
来源：http://dali.quarkkingdee.top/Article/details/gtfnbuaiqo.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shuidangran.top/Article/details/gthesniuwf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcsdmapsf.html

TS:   if (s === "") {}
来源：http://dali.sweek.top/Article/details/gtfpparkts.html

Java: if (s.isEmpty()) {}
来源：http://dali.ehwqpu.com/Article/details/gtauryjqpu.html

Go:   if s == "" {}
来源：http://dali.wangdashe.top/Article/details/gtagkmpahg.html

Ruby: if s.empty?
来源：http://dali.sxryk.cn/Article/details/gthyxixybi.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sxryk.cn/Article/details/gtdbsvypye.html

[E21] 超长截断加省略号
来源：http://dali.pengpengdd.cyou/Article/details/gtgdhuolgc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zycfv.cn/Article/details/gtrjaikfrm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gtllxwlbav.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtdxzfhpwy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gtgoviodzu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gtgwubmtox.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ybcxt.top/Article/details/gteftxznii.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtoolilqmr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xinyue.icu/Article/details/gtgxxxgszo.html

[E22] 字节长度与字符长度
来源：http://dali.chenlongwang.top/Article/details/gtzcwuakhb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tianlin.xyz/Article/details/gttrpklszg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gtwbkmtqzd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gogol.net.cn/Article/details/gtfnhusson.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tanke756.top/Article/details/gthpbkyejg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hammf.cn/Article/details/gtgbprvpsd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ehwqpu.com/Article/details/gtypysbmmm.html

Ruby: s.bytesize;  s.length
来源：http://dali.bjfxy.top/Article/details/gtckrcbumj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shuidangran.top/Article/details/gtxmbeyvnd.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtxxwsuuek.html

F. 文件与目录
来源：http://dali.guowangkeji.top/Article/details/gtmehavesc.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtyztobepb.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gtrejmotde.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gtpoqvmldl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gttokkwrbm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shzxlz.cn/Article/details/gtrilhzhyh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gteyonpjny.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gtuzcxtsvk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhengqikj.top/Article/details/gtbipuflcp.html

Ruby: File.read("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtsiqjeitl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtafycxpzg.html

[F02] 逐行读取文件
来源：http://dali.fengsongda.top/Article/details/gttkzogjsx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jiagoushi.top/Article/details/gtcjvreguv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nanxinkj.top/Article/details/gtnutuhkym.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvxlicnpa.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yongpay.top/Article/details/gtkdyixueh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hysaishi.cn/Article/details/gtpwzcxtlr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.vqdsnc.cn/Article/details/gtvbytufln.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hysaishi.cn/Article/details/gtjphpsuxf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.daxiang520.top/Article/details/gtjlfokypl.html

[F03] 写入文件（覆盖）
来源：http://dali.gogol.net.cn/Article/details/gtamfxbxun.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xuetiantiany.cn/Article/details/gtbnfynpvl.html


<!-- 参考信息 -->