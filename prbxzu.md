代发 wailian999

[D15] 去重
来源：http://dali.birdmap.top/Article/details/gtlbddznbr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hfpthk.cn/Article/details/gtwbmotsqe.html

PHP:  array_unique($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtbvrxxpsc.html

JS:   [...new Set(arr)]
来源：http://dali.yj202588.top/Article/details/gtpjcbovsz.html

TS:   [...new Set(arr)]
来源：http://dali.chenzaomai.com/Article/details/gtkorepajf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zycfv.cn/Article/details/gtgpctzovd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cheryme.top/Article/details/gtuepchieh.html

Ruby: arr.uniq
来源：http://dali.ehwqpu.com/Article/details/gtpwuknxsf.html

C#:   list.Distinct().ToList()
来源：http://dali.ivvv.top/Article/details/gtlxdnefmq.html

[D16] 求和与平均值
来源：http://dali.jinqigfzy.top/Article/details/gtnmxdlapm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gzhubu.top/Article/details/gtyrsjhguq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hfpthk.cn/Article/details/gtidntirlk.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtoohgtels.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sysykeji.top/Article/details/gtpdhpsmtb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.birdmap.top/Article/details/gtqhvvubmu.html

Go:   // 手写循环累加
来源：http://dali.hysaishi.cn/Article/details/gtwzzfsdms.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jianghu66.top/Article/details/gtyobxugvx.html

C#:   list.Sum();  list.Average()
来源：http://dali.ehwqpu.com/Article/details/gtkvlegupi.html

[D17] 最大值与最小值
来源：http://dali.tanke756.top/Article/details/gtnxxazvmg.html

Py:   max(arr);  min(arr)
来源：http://dali.nanxinkj.top/Article/details/gtdfzyyeaj.html

PHP:  max($arr);  min($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtctnelojl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jlsjyb.cn/Article/details/gtjyuyaqui.html

TS:   Math.max(...arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlrosagrw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yuanzhike.top/Article/details/gtgkppzfyk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtfakbzbyy.html

Ruby: arr.max;  arr.min
来源：http://dali.guannengcc.top/Article/details/gtkohpieel.html

C#:   list.Max();  list.Min()
来源：http://dali.dianchejie.cn/Article/details/gttmikelyq.html

[D18] 扁平化嵌套数组
来源：http://dali.zhiwuduotai.top/Article/details/gthffvnuur.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhixingplan.top/Article/details/gtrqxsnitp.html

PHP:  array_merge(...$nested);
来源：http://dali.chenzaomai.com/Article/details/gtsitbphis.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.snrcjt.cn/Article/details/gtfdimjtpo.html

TS:   nested.flat();
来源：http://dali.yangfankeji.com/Article/details/gtliibzywb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cucudq.cn/Article/details/gtzyrkolme.html

Go:   // 手写双层循环
来源：http://dali.fengsongda.top/Article/details/gtxqwcsbrx.html

Ruby: nested.flatten
来源：http://dali.316326.xyz/Article/details/gtwvoekkmk.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqlfkhgkx.html

[D19] 按字段分组
来源：http://dali.yonumen.top/Article/details/gticupducr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yueranfly.top/Article/details/gtnyffjgmb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.redwolf501.top/Article/details/gtkwmqmhau.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.pengpengdd.cyou/Article/details/gtghndfwim.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ydzc1.top/Article/details/gtcsoslfoo.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sweek.top/Article/details/gtvigdlwkg.html

Go:   // 手写 map[string][]T
来源：http://dali.zycfv.cn/Article/details/gtlufeaeix.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinghuilouyu.cn/Article/details/gthqzyzeio.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jqgfzy.top/Article/details/gtjzdoyhct.html

[D20] 统计每个元素出现次数
来源：http://dali.xinyue.icu/Article/details/gtixbviuhk.html

Py:   Counter(arr)
来源：http://dali.hfpthk.cn/Article/details/gtveliacrz.html

PHP:  array_count_values($arr);
来源：http://dali.zhoulong.xyz/Article/details/gttxrcbzzy.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cdnleiting.top/Article/details/gtybvdtzay.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hfpthk.cn/Article/details/gtfmjtrziv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cdnleiting.top/Article/details/gtkvoemlck.html

Go:   // 手写 map[T]int
来源：http://dali.wangdashe.top/Article/details/gtoktnwjww.html

Ruby: arr.tally
来源：http://dali.jqgfzy.top/Article/details/gtxkowerik.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zdqjudy.top/Article/details/gtbvjycwnh.html

[D21] 判断是否包含某元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtoblreean.html

Py:   x in arr
来源：http://dali.fengsongda.top/Article/details/gtsxxenbye.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hnqzz.top/Article/details/gtdjqpxdej.html

JS:   arr.includes(x)
来源：http://dali.aizwys.cn/Article/details/gtgytwlpch.html

TS:   arr.includes(x)
来源：http://dali.nwbrower.top/Article/details/gtvnnwmuhl.html

Java: list.contains(x)
来源：http://dali.ydzc1.top/Article/details/gtokwiyazg.html

Go:   slices.Contains(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtxicxgmdi.html

Ruby: arr.include?(x)
来源：http://dali.xinyue.icu/Article/details/gtqbvtkmjp.html

C#:   list.Contains(x)
来源：http://dali.mhx1999.top/Article/details/gtqostgbkv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ydzc1.top/Article/details/gtkmivdkjt.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jianghu66.top/Article/details/gtmbqbedqw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gtnmuvvydr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtyxpxnanx.html

TS:   [...arr];
来源：http://dali.meibo888.top/Article/details/gtugibvoov.html

Java: new ArrayList<>(list);
来源：http://dali.daxiang520.top/Article/details/gtzdgwqrki.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hfpthk.cn/Article/details/gtvkdislvs.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cqqwz.cn/Article/details/gtevhnqosv.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gtdnybtenw.html

[D23] reduce 累积计算
来源：http://dali.wangshuangyany.cn/Article/details/gtamjcfsfw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.nwbrower.top/Article/details/gtaweswrgv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.chenlongwang.top/Article/details/gtzabnpsko.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtzlqcztmh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtuyjpksdi.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.birdmap.top/Article/details/gtpdyytzbp.html

Go:   // 手写循环
来源：http://dali.xuanzx.com/Article/details/gtrhwbdfus.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhongyouzk.top/Article/details/gturpzddru.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.wangdashe.top/Article/details/gtulhcrqpn.html

[D24] 字典 / Map 基本操作
来源：http://dali.jqgufenzy.top/Article/details/gtnljiuzrs.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.mhx1999.top/Article/details/gtxccjzbua.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gtjuxfcvjy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yongpay.top/Article/details/gtqiqrsgtx.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xuanzx.com/Article/details/gtqbwogfno.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.316326.xyz/Article/details/gtwqvbvywy.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hammf.cn/Article/details/gtoxntdawr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zdqjudy.top/Article/details/gtyleetlls.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhixingplan.top/Article/details/gtdbtsxnve.html

[D25] Set 集合去重与交并差
来源：http://dali.hongshengwenyu.top/Article/details/gtoxbqpxws.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gtluelexls.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.nanxuanxn.top/Article/details/gtbcaomvib.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtubrhrlep.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jqgfzy.top/Article/details/gtnzcahedi.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jqgfzy.top/Article/details/gtojaelhpu.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhongyouzk.top/Article/details/gtlgadwzyb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.svipenyu.cn/Article/details/gtpvrrenhq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yangfankeji.com/Article/details/gtnjbrliyk.html

[D26] 数组转字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtldaxueii.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhongyouzk.top/Article/details/gtpnfxzrel.html

PHP:  implode(", ", $arr);
来源：http://dali.vqdsnc.cn/Article/details/gtpgaczmvb.html

JS:   arr.join(", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrkbeadeu.html

TS:   arr.join(", ")
来源：http://dali.gzhubu.top/Article/details/gthaktnpeq.html

Java: String.join(", ", list)
来源：http://dali.zhiwuduotai.top/Article/details/gtvdrbyhry.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jianghu66.top/Article/details/gtccswucoi.html

Ruby: arr.join(", ")
来源：http://dali.ybcxt.top/Article/details/gtzrpvzdgn.html

C#:   string.Join(", ", list)
来源：http://dali.yongpay.top/Article/details/gtqzccmvsq.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtxpjraeug.html

E. 字符串处理
来源：http://dali.nanxuanxn.top/Article/details/gtmqqygqwh.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtbylpqtxy.html

[E01] 拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdckmbdpw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.guannengcc.top/Article/details/gtcfnlgbzf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jlsjyb.cn/Article/details/gtdaqwbphs.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tanke756.top/Article/details/gtdidhbnyp.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuanzhike.top/Article/details/gtwcxthyjf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkdjhlbxs.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.fzhhl.top/Article/details/gtltoqbxiv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.quarkkingdee.top/Article/details/gtrwfciklr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtmwvkdbph.html

[E02] 重复字符串
来源：http://dali.yangfankeji.com/Article/details/gtjwgmlwis.html

Py:   "ab" * 3
来源：http://dali.zycfv.cn/Article/details/gtrkwauquy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ppjwa.cn/Article/details/gtraminhip.html

JS:   "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gtgfjurngg.html

TS:   "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gtghhcukcz.html

Java: "ab".repeat(3)
来源：http://dali.smart0.xyz/Article/details/gtubtxbkzr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sxryk.cn/Article/details/gtvelrtvlo.html

Ruby: "ab" * 3
来源：http://dali.chenjidiqi.icu/Article/details/gtvmuwwlow.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jqgufenzy.top/Article/details/gtpcazypof.html

[E03] 截取子串
来源：http://dali.ivvv.top/Article/details/gtqooadvpm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgvrvvxbr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gtoyyaxxlp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.tanke756.top/Article/details/gtisobtxwq.html

TS:   s.slice(1, 4)
来源：http://dali.sufxvd.cn/Article/details/gtqoidezza.html

Java: s.substring(1, 4)
来源：http://dali.aibaodan.cn/Article/details/gtywyjivvn.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sysykeji.top/Article/details/gtdbphfhdd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.chenlongwang.top/Article/details/gtvxgewuba.html

C#:   s.Substring(1, 3)
来源：http://dali.hysaishi.cn/Article/details/gtphxxybae.html

[E04] 查找子串位置
来源：http://dali.zhongyouzk.top/Article/details/gtkyvdhplm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sweek.top/Article/details/gtfrovkkmz.html

PHP:  strpos($s, "x");
来源：http://dali.zhixingplan.top/Article/details/gtlefqtpae.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.chenzaomai.com/Article/details/gtyuhfacwz.html

TS:   s.indexOf("x")
来源：http://dali.xziqi.cn/Article/details/gtvktihlyh.html

Java: s.indexOf("x")
来源：http://dali.sysykeji.top/Article/details/gtwhtrmazt.html

Go:   strings.Index(s, "x")
来源：http://dali.zhixingplan.top/Article/details/gtceiuzhnb.html

Ruby: s.index("x")
来源：http://dali.ydzc1.top/Article/details/gtcdbgbxrt.html

C#:   s.IndexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gtpxlfhbln.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sufxvd.cn/Article/details/gtsabghelk.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yongpay.top/Article/details/gthwbfeipm.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.smart0.xyz/Article/details/gtdpmlgahv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.aibaodan.cn/Article/details/gtrayfsseg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.haohaochexian.top/Article/details/gtlpntezlx.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cucudq.cn/Article/details/gtizpbggfr.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.c1oappe.top/Article/details/gtuqfptbss.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hnqzz.top/Article/details/gtwkaospom.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hywenlv.cn/Article/details/gtimsufuxg.html

[E06] 替换子串
来源：http://dali.yj20258888.top/Article/details/gtklttuwat.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yueranfly.top/Article/details/gtirjgjxwe.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.smart0.xyz/Article/details/gtlfmduzcw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gtoctlekvy.html

TS:   s.replaceAll("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtngrdtfum.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gtkuylzqta.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.nanxinkj.top/Article/details/gtcrgtrkoz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtjlnbfrzr.html

C#:   s.Replace("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtqlnlriio.html

[E07] 按分隔符拆分
来源：http://dali.chenlongwang.top/Article/details/gtgahcpoms.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.mhx1999.top/Article/details/gtlpjqikaf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.pycfn.com/Article/details/gtlieuqdza.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhiwuduotai.top/Article/details/gtaqpkrqvq.html

TS:   s.split(",")
来源：http://dali.yvedp.cn/Article/details/gttlyvdxuz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cashguo.top/Article/details/gtzkipttch.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xuanzx.com/Article/details/gtfppxrkpu.html

Ruby: s.split(",");  s.split
来源：http://dali.gaohongyu789.top/Article/details/gtjugkcyxy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hongshengwenyu.top/Article/details/gtpifptajo.html

[E08] 数组按分隔符合并
来源：http://dali.sysykeji.top/Article/details/gtixkuxltk.html

Py:   ",".join(items)
来源：http://dali.zhoulong.xyz/Article/details/gtixjsoaja.html

PHP:  implode(",", $items);
来源：http://dali.gogol.net.cn/Article/details/gtqxttdsul.html

JS:   items.join(",")
来源：http://dali.jlsjyb.cn/Article/details/gtpdohdubb.html

TS:   items.join(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtienhdnzi.html

Java: String.join(",", items)
来源：http://dali.fzhhl.top/Article/details/gtinpytssf.html

Go:   strings.Join(items, ",")
来源：http://dali.yuanzhike.top/Article/details/gtjmtmzrwk.html

Ruby: items.join(",")
来源：http://dali.aizwys.cn/Article/details/gtruwbijwa.html

C#:   string.Join(",", items)
来源：http://dali.aizwys.cn/Article/details/gtmivwvaob.html

[E09] 去除所有空白字符
来源：http://dali.c1oappe.top/Article/details/gtbtufkguz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hnxiangtu.top/Article/details/gtqgyszqtq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yj20258888.top/Article/details/gtubuivxqk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhiwuduotai.top/Article/details/gtwhzdwweq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrhgndpyy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gteotthfpp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zycfv.cn/Article/details/gtbzehptjs.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtykulghir.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yvedp.cn/Article/details/gtwwntawpm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yuanzhike.top/Article/details/gtvehkuuab.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hnqzz.top/Article/details/gtpnqeotnl.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gzhubu.top/Article/details/gttsccvtuz.html

JS:   "7".padStart(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gtihhrihqt.html

TS:   "7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gtvvkfjkyq.html

Java: String.format("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gtpqchcpfr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yuxming.cn/Article/details/gtzpokpcfn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gtklarfwwa.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.daxiang520.top/Article/details/gtuodrcdis.html

[E11] 反转字符串
来源：http://dali.sufxvd.cn/Article/details/gtrovdbbmm.html

Py:   s[::-1]
来源：http://dali.snrcjt.cn/Article/details/gtnauaypjo.html

PHP:  strrev($s);
来源：http://dali.tanke756.top/Article/details/gtjeepajrn.html

JS:   [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gtvydzufvr.html

TS:   [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gtytvurgqm.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jlsjyb.cn/Article/details/gtzgdgaqcx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.tianlin.xyz/Article/details/gtrgpyxnqg.html

Ruby: s.reverse
来源：http://dali.hysaishi.cn/Article/details/gthrbbncni.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.316326.xyz/Article/details/gtjgvalsea.html

[E12] 统计某字符出现次数
来源：http://dali.redwolf501.top/Article/details/gtlmysuazu.html

Py:   s.count("a")
来源：http://dali.gotoacloud.top/Article/details/gtetwbzdmg.html

PHP:  substr_count($s, "a");
来源：http://dali.jqgufenzy.top/Article/details/gtazksnbpx.html

JS:   s.split("a").length - 1
来源：http://dali.bjfxy.top/Article/details/gtafmpgjcv.html

TS:   s.split("a").length - 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtuguwtgda.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yangfankeji.com/Article/details/gtdkaruxex.html

Go:   strings.Count(s, "a")
来源：http://dali.daria6918.cn/Article/details/gtaehpascd.html

Ruby: s.count("a")
来源：http://dali.daxiang520.top/Article/details/gttdapvkly.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yonumen.top/Article/details/gtrdcnpjli.html

[E13] 逐字符遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzvnyougl.html

Py:   for ch in s: print(ch)
来源：http://dali.gogol.net.cn/Article/details/gtnuabqcmd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gogol.net.cn/Article/details/gtojmvyywm.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtetbzmnin.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangdashe.top/Article/details/gthsnhwspu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yueranfly.top/Article/details/gtnfxbcxsd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.smart0.xyz/Article/details/gtyhdkhfsq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hnxiangtu.top/Article/details/gtdoxxppep.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gtrrmpirwv.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gtdvwrbqce.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xuanzx.com/Article/details/gtjfkfwgoq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nanxuanxn.top/Article/details/gtilknfsaz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhoulong.xyz/Article/details/gtidglhuzg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hnqzz.top/Article/details/gteekwxfmm.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhoulong.xyz/Article/details/gtfoqepmwe.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.aizwys.cn/Article/details/gtobyejygm.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yuanzhike.top/Article/details/gthfonyery.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.chenzaomai.com/Article/details/gtoxgeepoa.html

[E15] HTML 转义 / 反转义
来源：http://dali.0kj1m.cn/Article/details/gtvxglojfo.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.meibo888.top/Article/details/gtfbnpozta.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.chenlongwang.top/Article/details/gtojqlsbzc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jlsjyb.cn/Article/details/gtadcqnzdo.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yvedp.cn/Article/details/gtipntaetn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sweek.top/Article/details/gtuhrljerx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtprglaqfd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.kuanghao11.cn/Article/details/gtvdrofuir.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.haohaochexian.top/Article/details/gtsebfkijf.html

[E16] 数字千分位
来源：http://dali.pengpengdd.cyou/Article/details/gtipyozvii.html

Py:   f"{1234567:,}"
来源：http://dali.jinqigufen.top/Article/details/gthbwwtwbh.html

PHP:  number_format(1234567);
来源：http://dali.nanxuanxn.top/Article/details/gtmbhhurti.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hysaishi.cn/Article/details/gtchgakzoz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.fengsongda.top/Article/details/gtzaazbxxn.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zycfv.cn/Article/details/gtczbgzpdl.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.birdmap.top/Article/details/gtzzyuhtux.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gtavzuoxho.html

C#:   1234567.ToString("N0")
来源：http://dali.jinqigfzy.top/Article/details/gtjxqnumdx.html

[E17] 首字母大写
来源：http://dali.redwolf501.top/Article/details/gtgxconuej.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.feifeiyinyue.top/Article/details/gtqzrjezob.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdjeetljx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgufenzy.top/Article/details/gtjjqqpebl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtyohpucjm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinqigufen.top/Article/details/gtotufosie.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.9152youxi.cn/Article/details/gtvdpnildi.html

Ruby: s.capitalize
来源：http://dali.jqgufenzy.top/Article/details/gtiayjuvft.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.daxiang520.top/Article/details/gtjnqecgtq.html

[E18] 模板占位符替换
来源：http://dali.wangdashe.top/Article/details/gttcigityi.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sweek.top/Article/details/gtfyqujgzx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ivvv.top/Article/details/gtzsbkapmp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gtrjxccijd.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gtsdwnfjpz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cheryme.top/Article/details/gtuscnwauc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtowcoqbzp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj20258.top/Article/details/gtfgkwiamp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.tianlin.xyz/Article/details/gtksaethre.html

[E19] 多行文本按行拆分
来源：http://dali.dianchejie.cn/Article/details/gtwmmewapp.html

Py:   s.splitlines()
来源：http://dali.daxiang520.top/Article/details/gtrvprlkhg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.fengsongda.top/Article/details/gtidzipnjo.html

JS:   s.split(/\r?\n/)
来源：http://dali.wangdashe.top/Article/details/gtowirahaz.html

TS:   s.split(/\r?\n/)
来源：http://dali.tianlin.xyz/Article/details/gtqykjxdxw.html

Java: s.lines().toList()
来源：http://dali.aizwys.cn/Article/details/gtctvdsuhy.html

Go:   strings.Split(s, "\n")
来源：http://dali.fengsongda.top/Article/details/gtykjrxvvr.html

Ruby: s.lines
来源：http://dali.yueranfly.top/Article/details/gtzflpgmmk.html

C#:   s.Split('\n')
来源：http://dali.sysykeji.top/Article/details/gtruggipyf.html

[E20] 判断字符串是否为空
来源：http://dali.jinqigufen.top/Article/details/gtormmweex.html

Py:   if not s:
来源：http://dali.daria6918.cn/Article/details/gtxwbrjlyh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.smart0.xyz/Article/details/gtdagmhnoj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.guannengcc.top/Article/details/gtxhaddrlu.html

TS:   if (s === "") {}
来源：http://dali.jinqigfzy.top/Article/details/gtkmuhifoj.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gtoobjnnvp.html

Go:   if s == "" {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbnstwrci.html

Ruby: if s.empty?
来源：http://dali.kuanghao11.cn/Article/details/gtynaxudwx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cashguo.top/Article/details/gtyqwpwsph.html

[E21] 超长截断加省略号
来源：http://dali.pycfn.com/Article/details/gtnhdodpzv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.havefunace.top/Article/details/gtjdgwgwqv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdhmzpagn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtpntlxudd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gteojoaoyd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtopgmsaqw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gthkungwin.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtcqxerlqk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gtzcblgkge.html


<!-- 参考信息 -->