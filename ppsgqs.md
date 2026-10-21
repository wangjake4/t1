代发 wailian999

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinghuilouyu.cn/Article/details/gtghwrgcnc.html

C#:   list.Sum();  list.Average()
来源：http://dali.ehwqpu.com/Article/details/gtyafkedua.html

[D17] 最大值与最小值
来源：http://dali.jyoumei.cn/Article/details/gteauxpebu.html

Py:   max(arr);  min(arr)
来源：http://dali.smart0.xyz/Article/details/gtnymbkuuu.html

PHP:  max($arr);  min($arr);
来源：http://dali.xinyue.icu/Article/details/gtamjywaaf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zycfv.cn/Article/details/gtmnqlthsz.html

TS:   Math.max(...arr);
来源：http://dali.vqdsnc.cn/Article/details/gtegcagoqm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hywenlv.cn/Article/details/gtdeuggnys.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cdnleiting.top/Article/details/gtdgsdhqhw.html

Ruby: arr.max;  arr.min
来源：http://dali.gotoacloud.top/Article/details/gtiznkaamr.html

C#:   list.Max();  list.Min()
来源：http://dali.316326.xyz/Article/details/gtspyhgdio.html

[D18] 扁平化嵌套数组
来源：http://dali.zdqjudy.top/Article/details/gtyemzswpd.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.guannengcc.top/Article/details/gtqlzblgvq.html

PHP:  array_merge(...$nested);
来源：http://dali.yonumen.top/Article/details/gtqjcoqbeq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jlsjyb.cn/Article/details/gthufefofe.html

TS:   nested.flat();
来源：http://dali.jinghuilouyu.cn/Article/details/gtekxcfjai.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jyoumei.cn/Article/details/gtbxgpdxbg.html

Go:   // 手写双层循环
来源：http://dali.yvedp.cn/Article/details/gthtvmznnl.html

Ruby: nested.flatten
来源：http://dali.haohaochexian.top/Article/details/gtcblczhaq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cucudq.cn/Article/details/gtklszcprs.html

[D19] 按字段分组
来源：http://dali.meibo888.top/Article/details/gtrvshhbof.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hammf.cn/Article/details/gtizxvsued.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hysaishi.cn/Article/details/gtfbejofdu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinqigfzy.top/Article/details/gtolgjvcjs.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhongyouzk.top/Article/details/gtoucubrlb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.svipenyu.cn/Article/details/gtnlkaupxf.html

Go:   // 手写 map[string][]T
来源：http://dali.tanke756.top/Article/details/gtzmhayded.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhoulong.xyz/Article/details/gtchmylidi.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cqqwz.cn/Article/details/gtxqkwidwn.html

[D20] 统计每个元素出现次数
来源：http://dali.jiagoushi.top/Article/details/gtsgkvjcad.html

Py:   Counter(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtnqpesydp.html

PHP:  array_count_values($arr);
来源：http://dali.jyoumei.cn/Article/details/gtwwgdwiqh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.iojbl.cn/Article/details/gtqblgwxaq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuxming.cn/Article/details/gtovuywcnx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yvedp.cn/Article/details/gthxmellwy.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gtdkcleigp.html

Ruby: arr.tally
来源：http://dali.zhongyouzk.top/Article/details/gtehkifwby.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.aizwys.cn/Article/details/gtmjlgitam.html

[D21] 判断是否包含某元素
来源：http://dali.gzhubu.top/Article/details/gtasznenet.html

Py:   x in arr
来源：http://dali.gzhubu.top/Article/details/gttktbkien.html

PHP:  in_array($x, $arr, true);
来源：http://dali.pycfn.com/Article/details/gtgzltbonq.html

JS:   arr.includes(x)
来源：http://dali.gzhubu.top/Article/details/gtzhmajqot.html

TS:   arr.includes(x)
来源：http://dali.jyoumei.cn/Article/details/gtinoshcfi.html

Java: list.contains(x)
来源：http://dali.meibo888.top/Article/details/gtskdnypri.html

Go:   slices.Contains(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtgoradtso.html

Ruby: arr.include?(x)
来源：http://dali.jqgfzy.top/Article/details/gtrxcuedre.html

C#:   list.Contains(x)
来源：http://dali.yangfankeji.com/Article/details/gthxntyxbh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yuxming.cn/Article/details/gtyugzckre.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sufxvd.cn/Article/details/gtlvppxwjr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.daxiang520.top/Article/details/gtetpzurge.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ppjwa.cn/Article/details/gtsdpihnxo.html

TS:   [...arr];
来源：http://dali.iojbl.cn/Article/details/gtrcqvjejm.html

Java: new ArrayList<>(list);
来源：http://dali.yj20258888.top/Article/details/gttatnyngm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.bjfxy.top/Article/details/gtucqujriw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.316326.xyz/Article/details/gtwlyawgim.html

C#:   new List<int>(list);
来源：http://dali.cqqwz.cn/Article/details/gtrcfawqlp.html

[D23] reduce 累积计算
来源：http://dali.chenjidiqi.icu/Article/details/gtfhzpkjqo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.gogol.net.cn/Article/details/gtgitcgpbi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.daria6918.cn/Article/details/gttbstjwwv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258888.top/Article/details/gtzlmqmsps.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.c1oappe.top/Article/details/gtzmhxlzqb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.bjfxy.top/Article/details/gtjellllaj.html

Go:   // 手写循环
来源：http://dali.ybcxt.top/Article/details/gtzgbdmshh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhiwuduotai.top/Article/details/gtjaoriwpz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shzxlz.cn/Article/details/gtvdvhisxm.html

[D24] 字典 / Map 基本操作
来源：http://dali.shangyingyoupin.top/Article/details/gtkslnixjw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xylfe.cn/Article/details/gtzfvkmqel.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.bjfxy.top/Article/details/gtetmedezy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtirrlanrc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.0kj1m.cn/Article/details/gtkhosejza.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.andypj.xyz/Article/details/gtawllmnpz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jyoumei.cn/Article/details/gtaursfjge.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.guowangkeji.top/Article/details/gtdrfrtseb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yongpay.top/Article/details/gtewshnlsq.html

[D25] Set 集合去重与交并差
来源：http://dali.nanxuanxn.top/Article/details/gtxxbsjykv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.daria6918.cn/Article/details/gtegxnxees.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhengqikj.top/Article/details/gtkzsxhror.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtcjjisvih.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shangyingyoupin.top/Article/details/gticclisax.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hammf.cn/Article/details/gtnfqrazoz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.meibo888.top/Article/details/gtqkmjwijy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.guannengcc.top/Article/details/gtuosjwwic.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.redwolf501.top/Article/details/gtpzxhlwvi.html

[D26] 数组转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtxgonajnw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.c1oappe.top/Article/details/gtxroupgeo.html

PHP:  implode(", ", $arr);
来源：http://dali.jianghu66.top/Article/details/gtsaahzmmd.html

JS:   arr.join(", ")
来源：http://dali.andypj.xyz/Article/details/gtqtsycwfd.html

TS:   arr.join(", ")
来源：http://dali.yuxming.cn/Article/details/gthetkdhcj.html

Java: String.join(", ", list)
来源：http://dali.fzhhl.top/Article/details/gtnngjgxwb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yj20258.top/Article/details/gtotxpxiyn.html

Ruby: arr.join(", ")
来源：http://dali.316326.xyz/Article/details/gtxefwoabm.html

C#:   string.Join(", ", list)
来源：http://dali.zhoulong.xyz/Article/details/gtsisyyxjg.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtdleywifu.html

E. 字符串处理
来源：http://dali.yangfankeji.com/Article/details/gtlapuaadf.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtcavgbmph.html

[E01] 拼接字符串
来源：http://dali.ybcxt.top/Article/details/gttgixagau.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hammf.cn/Article/details/gtxafixrlc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yvedp.cn/Article/details/gtkgezrrti.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yanxiufei.cn/Article/details/gtvhakxooe.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sxryk.cn/Article/details/gtmupvlxbf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xziqi.cn/Article/details/gtjmefpttu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.feifeiyinyue.top/Article/details/gtockzipcu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ydzc1.top/Article/details/gtbexchykt.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gtluhhdmac.html

[E02] 重复字符串
来源：http://dali.fzhhl.top/Article/details/gtlxlvbwnu.html

Py:   "ab" * 3
来源：http://dali.ybcxt.top/Article/details/gtpkcwjwaq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sxryk.cn/Article/details/gtegoyquxo.html

JS:   "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gttfsvvkxw.html

TS:   "ab".repeat(3)
来源：http://dali.hfpthk.cn/Article/details/gtxshefzvm.html

Java: "ab".repeat(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtrzzqwayr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.fzhhl.top/Article/details/gtbgqidxxc.html

Ruby: "ab" * 3
来源：http://dali.zhengqikj.top/Article/details/gtssborzad.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jqgufenzy.top/Article/details/gtcmeyyctz.html

[E03] 截取子串
来源：http://dali.gotoacloud.top/Article/details/gtrdyutksh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hammf.cn/Article/details/gtkwyrjfne.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.316326.xyz/Article/details/gtxipttztz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jqgfzy.top/Article/details/gtromdubzz.html

TS:   s.slice(1, 4)
来源：http://dali.yueranfly.top/Article/details/gtsibtcfjv.html

Java: s.substring(1, 4)
来源：http://dali.chenzaomai.com/Article/details/gtrofpmeuc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.tanke756.top/Article/details/gttstcsrfo.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.fzhhl.top/Article/details/gtaekaksdd.html

C#:   s.Substring(1, 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtjgduqjvu.html

[E04] 查找子串位置
来源：http://dali.aibaodan.cn/Article/details/gtcpkfljer.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sufxvd.cn/Article/details/gtnihmdfya.html

PHP:  strpos($s, "x");
来源：http://dali.dashuyun.cn/Article/details/gttdqhgvtl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yonumen.top/Article/details/gtcgndfnbz.html

TS:   s.indexOf("x")
来源：http://dali.xinyue.icu/Article/details/gtqnzpdulb.html

Java: s.indexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gtuulrpsvk.html

Go:   strings.Index(s, "x")
来源：http://dali.vqdsnc.cn/Article/details/gtifweiquk.html

Ruby: s.index("x")
来源：http://dali.nanxinkj.top/Article/details/gtyohiipxw.html

C#:   s.IndexOf("x")
来源：http://dali.feifeiyinyue.top/Article/details/gtzhulvmtl.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yuxming.cn/Article/details/gtqkhyogcd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zycfv.cn/Article/details/gtjkrwykqb.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gzhubu.top/Article/details/gtgxylglqp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenlongwang.top/Article/details/gturrgawrf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.pycfn.com/Article/details/gttlydyube.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdjhgcxbw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.0kj1m.cn/Article/details/gtmkgvluap.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sysykeji.top/Article/details/gtiktblgrh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yongpay.top/Article/details/gtaizfedtz.html

[E06] 替换子串
来源：http://dali.zycfv.cn/Article/details/gtidrhgkdp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hammf.cn/Article/details/gtzqwcbpro.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yvedp.cn/Article/details/gtzuvrvzmf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtkzhipirk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gtjutkspsk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gtjypeaaas.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gzhubu.top/Article/details/gtywevqman.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtkeotozxe.html

C#:   s.Replace("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtslhgqfdc.html

[E07] 按分隔符拆分
来源：http://dali.daxiang520.top/Article/details/gtjwzaimgq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinghuilouyu.cn/Article/details/gtscougzfg.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gogol.net.cn/Article/details/gtesmehcvp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.wangshuangyany.cn/Article/details/gtmcgmqgil.html

TS:   s.split(",")
来源：http://dali.andypj.xyz/Article/details/gtmkvwezcv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sweek.top/Article/details/gtiinhvpjy.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hnqzz.top/Article/details/gtpbxonugz.html

Ruby: s.split(",");  s.split
来源：http://dali.yuanzhike.top/Article/details/gtszmoxwoy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xinyue.icu/Article/details/gtspqmovga.html

[E08] 数组按分隔符合并
来源：http://dali.zhoulong.xyz/Article/details/gtkznqxqxr.html

Py:   ",".join(items)
来源：http://dali.hywenlv.cn/Article/details/gtdflyodjc.html

PHP:  implode(",", $items);
来源：http://dali.shangyingyoupin.top/Article/details/gtvihlcxlc.html

JS:   items.join(",")
来源：http://dali.pengpengdd.cyou/Article/details/gtsrbzzmfi.html

TS:   items.join(",")
来源：http://dali.cashguo.top/Article/details/gtugagltlw.html

Java: String.join(",", items)
来源：http://dali.pycfn.com/Article/details/gtitnqcajq.html

Go:   strings.Join(items, ",")
来源：http://dali.chenzaomai.com/Article/details/gtpceugqmh.html

Ruby: items.join(",")
来源：http://dali.yangfankeji.com/Article/details/gtsudeqetc.html

C#:   string.Join(",", items)
来源：http://dali.shuidangran.top/Article/details/gtbywpnnmn.html

[E09] 去除所有空白字符
来源：http://dali.redwolf501.top/Article/details/gtotaxrkhf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xuanzx.com/Article/details/gtygdbhyzp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.daxiang520.top/Article/details/gtmzxqfiqz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigfzy.top/Article/details/gtfcwmqomt.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenzaomai.com/Article/details/gtjsjpzjui.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.pycfn.com/Article/details/gtazceuxfb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhiwuduotai.top/Article/details/gtkqwokbee.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.quarkkingdee.top/Article/details/gtngczalxq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ppjwa.cn/Article/details/gtpzthrvgq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhaomingkeji.xyz/Article/details/gtztgtizkh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xziqi.cn/Article/details/gtonlvknkf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xuetiantiany.cn/Article/details/gtqfytmuwu.html

JS:   "7".padStart(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gtbbuntvhq.html

TS:   "7".padStart(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gtnxkjeuen.html

Java: String.format("%03d", 7)
来源：http://dali.ppjwa.cn/Article/details/gtrkpywins.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.quarkkingdee.top/Article/details/gthgfvacab.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gtncplkhhp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tianlin.xyz/Article/details/gtnpgcvfwx.html

[E11] 反转字符串
来源：http://dali.hnqzz.top/Article/details/gtikxaxtqz.html

Py:   s[::-1]
来源：http://dali.tianlin.xyz/Article/details/gtbwvqkxzp.html

PHP:  strrev($s);
来源：http://dali.guannengcc.top/Article/details/gtccjlqrnz.html

JS:   [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gtwnaaawjk.html

TS:   [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gtjrujuqhf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.daxiang520.top/Article/details/gtydryusko.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhiwuduotai.top/Article/details/gtfntwcpte.html

Ruby: s.reverse
来源：http://dali.redwolf501.top/Article/details/gtdkctrury.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.havefunace.top/Article/details/gtphfjkujt.html

[E12] 统计某字符出现次数
来源：http://dali.dianchejie.cn/Article/details/gtaqkkwpbz.html

Py:   s.count("a")
来源：http://dali.cucudq.cn/Article/details/gtrluqvzra.html

PHP:  substr_count($s, "a");
来源：http://dali.dashuyun.cn/Article/details/gtjqdaayex.html

JS:   s.split("a").length - 1
来源：http://dali.redwolf501.top/Article/details/gtpnqfeorm.html

TS:   s.split("a").length - 1
来源：http://dali.wangdashe.top/Article/details/gtslzfnxjd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenjidiqi.icu/Article/details/gtsxgthndn.html

Go:   strings.Count(s, "a")
来源：http://dali.ybcxt.top/Article/details/gtbnhfmupf.html

Ruby: s.count("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlferacdk.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yongpay.top/Article/details/gtnhvokbwy.html

[E13] 逐字符遍历
来源：http://dali.gzhubu.top/Article/details/gtronwlize.html

Py:   for ch in s: print(ch)
来源：http://dali.jiagoushi.top/Article/details/gtkccxpzjk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.pycfn.com/Article/details/gtzobpfcnw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gtbjhoozta.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnqzz.top/Article/details/gteincaluu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ydzc1.top/Article/details/gtqgjbnhoy.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.nanxuanxn.top/Article/details/gtheomaqhb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shuidangran.top/Article/details/gtdctdvclp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yonumen.top/Article/details/gthogiwwxx.html

[E14] URL 编码与 Base64
来源：http://dali.sweek.top/Article/details/gtbgxqpgeh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnthpybxj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.c1oappe.top/Article/details/gtaphzpgou.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj20258.top/Article/details/gtitlxnecv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xinyue.icu/Article/details/gtcpzspyzk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.snrcjt.cn/Article/details/gtbxvlkqii.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.fengsongda.top/Article/details/gtrptayplw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.aizwys.cn/Article/details/gtbwkxerzy.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xylfe.cn/Article/details/gtpsxieyeb.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhixingplan.top/Article/details/gtrthrpvhy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzdtrqzwr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hysaishi.cn/Article/details/gttljkabfd.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtcwzpndos.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gtgdpyfxgy.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yonumen.top/Article/details/gtvtledawb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.daria6918.cn/Article/details/gtiaidyemw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nanxuanxn.top/Article/details/gtqrfkhfpb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yj20258.top/Article/details/gtooqwgeqw.html

[E16] 数字千分位
来源：http://dali.pengpengdd.cyou/Article/details/gttpwkduto.html

Py:   f"{1234567:,}"
来源：http://dali.daria6918.cn/Article/details/gtqhbnoetk.html

PHP:  number_format(1234567);
来源：http://dali.zhiwuduotai.top/Article/details/gtyikrhtpb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxuanxn.top/Article/details/gtyrroxcqc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sysykeji.top/Article/details/gtojhagmne.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.aizwys.cn/Article/details/gtihefggek.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ivvv.top/Article/details/gtwulxfecc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.kuanghao11.cn/Article/details/gtffzyfsas.html

C#:   1234567.ToString("N0")
来源：http://dali.jinqigfzy.top/Article/details/gtssdseikf.html

[E17] 首字母大写
来源：http://dali.guannengcc.top/Article/details/gtxrkdqpvl.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.wangshuangyany.cn/Article/details/gtgzyevvyn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.nwbrower.top/Article/details/gtyjupvhzk.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yongpay.top/Article/details/gtpzrqzbdk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fengsongda.top/Article/details/gtayftjmcd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xylfe.cn/Article/details/gtslhtemec.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gtbrzteyyr.html

Ruby: s.capitalize
来源：http://dali.yj20258888.top/Article/details/gtfuycvwub.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.pycfn.com/Article/details/gtmzmguxbu.html

[E18] 模板占位符替换
来源：http://dali.redwolf501.top/Article/details/gtakmienup.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yuanzhike.top/Article/details/gtjqkrbiht.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ybcxt.top/Article/details/gtoohrecws.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.meibo888.top/Article/details/gtktqnwpts.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gtrqhxvaoz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gtgaxtkcmr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxmndctqj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gaohongyu789.top/Article/details/gtyjdjkiwh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yuanzhike.top/Article/details/gtflrpkldp.html

[E19] 多行文本按行拆分
来源：http://dali.havefunace.top/Article/details/gtejetkbck.html

Py:   s.splitlines()
来源：http://dali.gogol.net.cn/Article/details/gtrihbzplz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xylfe.cn/Article/details/gtegvyvrer.html

JS:   s.split(/\r?\n/)
来源：http://dali.pycfn.com/Article/details/gtofybgikh.html

TS:   s.split(/\r?\n/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtumknxhla.html

Java: s.lines().toList()
来源：http://dali.cucudq.cn/Article/details/gtaqnwjala.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtpmbtnepq.html

Ruby: s.lines
来源：http://dali.daxiang520.top/Article/details/gtvmhpdstk.html

C#:   s.Split('\n')
来源：http://dali.hnqzz.top/Article/details/gtdbdmyijd.html

[E20] 判断字符串是否为空
来源：http://dali.birdmap.top/Article/details/gtecgnsana.html

Py:   if not s:
来源：http://dali.jinqigufen.top/Article/details/gtueabjdii.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shangyingyoupin.top/Article/details/gtvwijtwoh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jqgufenzy.top/Article/details/gtignvzyet.html

TS:   if (s === "") {}
来源：http://dali.shangyingyoupin.top/Article/details/gtivuqtksx.html

Java: if (s.isEmpty()) {}
来源：http://dali.aizwys.cn/Article/details/gtacgkayod.html

Go:   if s == "" {}
来源：http://dali.ydzc1.top/Article/details/gtxioxnarg.html

Ruby: if s.empty?
来源：http://dali.jianghu66.top/Article/details/gtvnssoovf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.vqdsnc.cn/Article/details/gthhjxpojb.html

[E21] 超长截断加省略号
来源：http://dali.sysykeji.top/Article/details/gtraemawnv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.smart0.xyz/Article/details/gtwkzcgdii.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gtnbwgugwo.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtbnauktqx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtevjvhljx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gtcpvxzkum.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gogol.net.cn/Article/details/gtjhecwlie.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.birdmap.top/Article/details/gtyvvholnz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsnnnvvjj.html

[E22] 字节长度与字符长度
来源：http://dali.cheryme.top/Article/details/gtkekmzddj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.birdmap.top/Article/details/gtzszybwbe.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gtyibsvwyl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.meibo888.top/Article/details/gtvefddufj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxuanxn.top/Article/details/gtdbmnxgoq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.316326.xyz/Article/details/gtjvosvzsu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhiwuduotai.top/Article/details/gtohepyjnt.html

Ruby: s.bytesize;  s.length
来源：http://dali.daria6918.cn/Article/details/gtxjdkhdon.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj20258.top/Article/details/gtclclhslw.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtaitiipti.html

F. 文件与目录
来源：http://dali.bjfxy.top/Article/details/gtulpesjmg.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtnmbxkwwa.html

[F01] 读取整个文件
来源：http://dali.jiagoushi.top/Article/details/gtxalaqbtl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jlsjyb.cn/Article/details/gtmdkwlicg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtujhlxczw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xziqi.cn/Article/details/gtdnriwbgd.html


<!-- 参考信息 -->