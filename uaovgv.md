代发 wailian999

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gzhubu.top/Article/details/gtrocqzkwc.html

C#:   list.Sum();  list.Average()
来源：http://dali.cqqwz.cn/Article/details/gtkotspfwh.html

[D17] 最大值与最小值
来源：http://dali.9152youxi.cn/Article/details/gtcnahiayz.html

Py:   max(arr);  min(arr)
来源：http://dali.sweek.top/Article/details/gttalcqxmw.html

PHP:  max($arr);  min($arr);
来源：http://dali.yangfankeji.com/Article/details/gtocgvtnyq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yueranfly.top/Article/details/gtoaongqii.html

TS:   Math.max(...arr);
来源：http://dali.meibo888.top/Article/details/gtxyblobaw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.316326.xyz/Article/details/gtaccbppju.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ybcxt.top/Article/details/gtjxvavahk.html

Ruby: arr.max;  arr.min
来源：http://dali.ywan-chungtsiang.top/Article/details/gttilkoucv.html

C#:   list.Max();  list.Min()
来源：http://dali.wangshuangyany.cn/Article/details/gtqrajvuvd.html

[D18] 扁平化嵌套数组
来源：http://dali.ppjwa.cn/Article/details/gtsvsuytjn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gzhubu.top/Article/details/gttuxbswtu.html

PHP:  array_merge(...$nested);
来源：http://dali.ybcxt.top/Article/details/gthzislmmv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shangyingyoupin.top/Article/details/gtzwqjzbir.html

TS:   nested.flat();
来源：http://dali.daria6918.cn/Article/details/gtfduzeyaq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yuxming.cn/Article/details/gtdbxvkrgf.html

Go:   // 手写双层循环
来源：http://dali.zhongyouzk.top/Article/details/gthsypbyca.html

Ruby: nested.flatten
来源：http://dali.zhoulong.xyz/Article/details/gtvdyrrjtk.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.fengsongda.top/Article/details/gtqbrlohup.html

[D19] 按字段分组
来源：http://dali.yuanzhike.top/Article/details/gtqafbxvip.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sufxvd.cn/Article/details/gtaphaffle.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hnxiangtu.top/Article/details/gtjpzvqyxc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ivvv.top/Article/details/gtgkudqvan.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.guannengcc.top/Article/details/gttrbbqplu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinqigufen.top/Article/details/gtxsygkjfb.html

Go:   // 手写 map[string][]T
来源：http://dali.sweek.top/Article/details/gtfcjlbzxf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shanyushiyangtech.top/Article/details/gtiuokytkt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpvkklppk.html

[D20] 统计每个元素出现次数
来源：http://dali.dianchejie.cn/Article/details/gtatpootls.html

Py:   Counter(arr)
来源：http://dali.chenzaomai.com/Article/details/gtayadlrmk.html

PHP:  array_count_values($arr);
来源：http://dali.mhx1999.top/Article/details/gtxfwhvpcm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ydzc1.top/Article/details/gtwqpvvawl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ehwqpu.com/Article/details/gtinweyvwj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.dianchejie.cn/Article/details/gtmfsvnadv.html

Go:   // 手写 map[T]int
来源：http://dali.aizwys.cn/Article/details/gtekpuoprn.html

Ruby: arr.tally
来源：http://dali.quarkkingdee.top/Article/details/gtxmqcugms.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.havefunace.top/Article/details/gtczuflhwt.html

[D21] 判断是否包含某元素
来源：http://dali.xinyue.icu/Article/details/gtcbzbhoza.html

Py:   x in arr
来源：http://dali.fzhhl.top/Article/details/gtonctkapu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yangfankeji.com/Article/details/gtkntrknqm.html

JS:   arr.includes(x)
来源：http://dali.chenlongwang.top/Article/details/gtwkyusydb.html

TS:   arr.includes(x)
来源：http://dali.daria6918.cn/Article/details/gtfvpzvbsi.html

Java: list.contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gtdzuxpjot.html

Go:   slices.Contains(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gthqqzhobp.html

Ruby: arr.include?(x)
来源：http://dali.guannengcc.top/Article/details/gtxnakxrsw.html

C#:   list.Contains(x)
来源：http://dali.nanxinkj.top/Article/details/gtjpnjsjjs.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhiwuduotai.top/Article/details/gtqifjfchq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.daxiang520.top/Article/details/gtjxmbvrfa.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.guannengcc.top/Article/details/gtumpiejkv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yvedp.cn/Article/details/gtyuertofl.html

TS:   [...arr];
来源：http://dali.cashguo.top/Article/details/gtsegklscm.html

Java: new ArrayList<>(list);
来源：http://dali.zhengqikj.top/Article/details/gtgdduzuxa.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenjidiqi.icu/Article/details/gtutknaksk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.wangdashe.top/Article/details/gtirdnuyyw.html

C#:   new List<int>(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gthsghccik.html

[D23] reduce 累积计算
来源：http://dali.bjfxy.top/Article/details/gtvuidqhfo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.gotoacloud.top/Article/details/gtyhiffjuv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.chenlongwang.top/Article/details/gtymtvicru.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.bjfxy.top/Article/details/gtjakkiczs.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gogol.net.cn/Article/details/gtdogwpdcw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.mhx1999.top/Article/details/gtwbmfxket.html

Go:   // 手写循环
来源：http://dali.jinqigfzy.top/Article/details/gtgulzqows.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jiagoushi.top/Article/details/gtmgpwtldl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yueranfly.top/Article/details/gttbstwekk.html

[D24] 字典 / Map 基本操作
来源：http://dali.zdqjudy.top/Article/details/gtxqocobct.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jqgufenzy.top/Article/details/gtctogjykb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tanke756.top/Article/details/gthzoxvpej.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gogol.net.cn/Article/details/gteezbgidi.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtbhremlkm.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cashguo.top/Article/details/gtgzeibcqj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.kuanghao11.cn/Article/details/gtquoiheuj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yj20258888.top/Article/details/gtduihuytn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenzaomai.com/Article/details/gtqzntubmc.html

[D25] Set 集合去重与交并差
来源：http://dali.haohaochexian.top/Article/details/gtbgzupelj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jlsjyb.cn/Article/details/gtljdxgvmr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yonumen.top/Article/details/gtygkekffn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttohokayu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yuanzhike.top/Article/details/gtjtgddlxk.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.fengsongda.top/Article/details/gtfeioheag.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.guowangkeji.top/Article/details/gtbhubbehc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.guannengcc.top/Article/details/gtqinvrcbp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yuanzhike.top/Article/details/gtikdxfcxh.html

[D26] 数组转字符串
来源：http://dali.jianghu66.top/Article/details/gtybdarpui.html

Py:   ", ".join(map(str, arr))
来源：http://dali.fzhhl.top/Article/details/gtwuxjkyfa.html

PHP:  implode(", ", $arr);
来源：http://dali.meibo888.top/Article/details/gtojosuyht.html

JS:   arr.join(", ")
来源：http://dali.andypj.xyz/Article/details/gtqwhxierl.html

TS:   arr.join(", ")
来源：http://dali.nanxinkj.top/Article/details/gtlflcjcfi.html

Java: String.join(", ", list)
来源：http://dali.nwbrower.top/Article/details/gtrjlcatdu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.chenlongwang.top/Article/details/gtacvdrere.html

Ruby: arr.join(", ")
来源：http://dali.andypj.xyz/Article/details/gtiauhtqak.html

C#:   string.Join(", ", list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmjdofwoz.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtwxyyfxpv.html

E. 字符串处理
来源：http://dali.yonumen.top/Article/details/gtztffwzzm.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtqnoifhpp.html

[E01] 拼接字符串
来源：http://dali.ybcxt.top/Article/details/gtavdmfxdt.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ppjwa.cn/Article/details/gthlmtdlil.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkomrtsbe.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtiyojwmxz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zdqjudy.top/Article/details/gtmpjezwqb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.wangdashe.top/Article/details/gtxzmrogdd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sxryk.cn/Article/details/gtqyfcbptu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jqgufenzy.top/Article/details/gtpzrdagvp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtrgssklbs.html

[E02] 重复字符串
来源：http://dali.bjfxy.top/Article/details/gtwlypkigw.html

Py:   "ab" * 3
来源：http://dali.hongshengwenyu.top/Article/details/gtocradkdt.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hammf.cn/Article/details/gtzhpmqoev.html

JS:   "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gtxjttazqg.html

TS:   "ab".repeat(3)
来源：http://dali.hammf.cn/Article/details/gtamhslxur.html

Java: "ab".repeat(3)
来源：http://dali.dianchejie.cn/Article/details/gtlhirtrlh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.chenjidiqi.icu/Article/details/gtjznfbaec.html

Ruby: "ab" * 3
来源：http://dali.hywenlv.cn/Article/details/gtngfbjtmv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hysaishi.cn/Article/details/gtvbtduptz.html

[E03] 截取子串
来源：http://dali.tian-w.cn/Article/details/gtwkukzotc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jqgufenzy.top/Article/details/gtqholxufg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtebnlzbje.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.daria6918.cn/Article/details/gtmpkfukdf.html

TS:   s.slice(1, 4)
来源：http://dali.snrcjt.cn/Article/details/gtvsgegrwa.html

Java: s.substring(1, 4)
来源：http://dali.chenjidiqi.icu/Article/details/gtyhgkhekw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.316326.xyz/Article/details/gtbwcgtiro.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jiagoushi.top/Article/details/gteyrvusuz.html

C#:   s.Substring(1, 3)
来源：http://dali.quarkkingdee.top/Article/details/gtgabmserg.html

[E04] 查找子串位置
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdinamhec.html

Py:   s.find("x");  s.index("x")
来源：http://dali.nanxuanxn.top/Article/details/gtmietgzlm.html

PHP:  strpos($s, "x");
来源：http://dali.shangyingyoupin.top/Article/details/gtjoithwnr.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.guannengcc.top/Article/details/gtkwppzlgm.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gtnszhdbiq.html

Java: s.indexOf("x")
来源：http://dali.fzhhl.top/Article/details/gtyklwytkg.html

Go:   strings.Index(s, "x")
来源：http://dali.zhengqikj.top/Article/details/gtujnlehig.html

Ruby: s.index("x")
来源：http://dali.9152youxi.cn/Article/details/gtgjxbbefs.html

C#:   s.IndexOf("x")
来源：http://dali.jinqigufen.top/Article/details/gtbqvcdual.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.quarkkingdee.top/Article/details/gthhaffgey.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtozgbgjix.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sufxvd.cn/Article/details/gtqnasxqit.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cashguo.top/Article/details/gtgwvfnrll.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jyoumei.cn/Article/details/gtmawwouot.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.aizwys.cn/Article/details/gtrjhyuopr.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yj20258.top/Article/details/gtzzhuiwvq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.dianchejie.cn/Article/details/gthemlbciv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtwqgdklbk.html

[E06] 替换子串
来源：http://dali.quarkkingdee.top/Article/details/gtxvwmedec.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cdnleiting.top/Article/details/gtiobjifel.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.nanxinkj.top/Article/details/gteuwqyrvo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtmmvmbook.html

TS:   s.replaceAll("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtpbxdcazc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gttxjwjowl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.316326.xyz/Article/details/gtqlnfqrva.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfckblqjq.html

C#:   s.Replace("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtdhjenpej.html

[E07] 按分隔符拆分
来源：http://dali.zhiwuduotai.top/Article/details/gtrspbenqr.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zycfv.cn/Article/details/gtauxaxqam.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.aibaodan.cn/Article/details/gtgazmowhu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zycfv.cn/Article/details/gtdmjfxlgq.html

TS:   s.split(",")
来源：http://dali.chenzaomai.com/Article/details/gtltwvovgm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cashguo.top/Article/details/gtwmqhomgz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.fengsongda.top/Article/details/gtdnhvdbee.html

Ruby: s.split(",");  s.split
来源：http://dali.sufxvd.cn/Article/details/gtpgwsmtxz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.aizwys.cn/Article/details/gtchcgxlti.html

[E08] 数组按分隔符合并
来源：http://dali.c1oappe.top/Article/details/gtnebbpyrn.html

Py:   ",".join(items)
来源：http://dali.shzxlz.cn/Article/details/gtamywgmvz.html

PHP:  implode(",", $items);
来源：http://dali.sysykeji.top/Article/details/gtrhkwxlzm.html

JS:   items.join(",")
来源：http://dali.feifeiyinyue.top/Article/details/gtstjqecdk.html

TS:   items.join(",")
来源：http://dali.bjfxy.top/Article/details/gtwhhanxmy.html

Java: String.join(",", items)
来源：http://dali.zhengqikj.top/Article/details/gtsoxxufxr.html

Go:   strings.Join(items, ",")
来源：http://dali.birdmap.top/Article/details/gtdnrvkkek.html

Ruby: items.join(",")
来源：http://dali.316326.xyz/Article/details/gtgwlbdgxj.html

C#:   string.Join(",", items)
来源：http://dali.hysaishi.cn/Article/details/gtpnuhgvla.html

[E09] 去除所有空白字符
来源：http://dali.shanyushiyangtech.top/Article/details/gttbrmwxrq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sxryk.cn/Article/details/gtmhbdhozn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gogol.net.cn/Article/details/gthimkbebx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jlsjyb.cn/Article/details/gtqmebjeuq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cucudq.cn/Article/details/gtpewrdzkz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj202588.top/Article/details/gtvvhodoob.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhiwuduotai.top/Article/details/gtgguemkbk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hongshengwenyu.top/Article/details/gtvfyknqmq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hongshengwenyu.top/Article/details/gtqlmzuohd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.tianlin.xyz/Article/details/gtcpdcaaop.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hongshengwenyu.top/Article/details/gtiyhoewvs.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yj20258.top/Article/details/gtfbezelux.html

JS:   "7".padStart(3, "0")
来源：http://dali.ivvv.top/Article/details/gtwmpfnjir.html

TS:   "7".padStart(3, "0")
来源：http://dali.zdqjudy.top/Article/details/gtqnlinldy.html

Java: String.format("%03d", 7)
来源：http://dali.yongpay.top/Article/details/gtpeybuvvg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gtaferkshr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinqigufen.top/Article/details/gtnxbsirnf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.daxiang520.top/Article/details/gtbtyryfyo.html

[E11] 反转字符串
来源：http://dali.yvedp.cn/Article/details/gtsjozmnxb.html

Py:   s[::-1]
来源：http://dali.yuanzhike.top/Article/details/gtmvkmeppt.html

PHP:  strrev($s);
来源：http://dali.smart0.xyz/Article/details/gttvfgjsqa.html

JS:   [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gtohoggtea.html

TS:   [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gtndnfbcji.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinqigufen.top/Article/details/gtqeoxaiax.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yanxiufei.cn/Article/details/gtiqtubwjj.html

Ruby: s.reverse
来源：http://dali.tianlin.xyz/Article/details/gtgbyaexmu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.dashuyun.cn/Article/details/gtqphklutk.html

[E12] 统计某字符出现次数
来源：http://dali.xuetiantiany.cn/Article/details/gtqagupdbn.html

Py:   s.count("a")
来源：http://dali.ehwqpu.com/Article/details/gtrojroucr.html

PHP:  substr_count($s, "a");
来源：http://dali.gaohongyu789.top/Article/details/gtmzpyoevq.html

JS:   s.split("a").length - 1
来源：http://dali.yuanzhike.top/Article/details/gtxrxaxwmp.html

TS:   s.split("a").length - 1
来源：http://dali.daria6918.cn/Article/details/gtuvqxztvl.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.pengpengdd.cyou/Article/details/gtpxmxmhux.html

Go:   strings.Count(s, "a")
来源：http://dali.sysykeji.top/Article/details/gtouelavrn.html

Ruby: s.count("a")
来源：http://dali.yj20258.top/Article/details/gtwxtlkojr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shanyushiyangtech.top/Article/details/gtrldwhtxx.html

[E13] 逐字符遍历
来源：http://dali.cdnleiting.top/Article/details/gtuojvfgqk.html

Py:   for ch in s: print(ch)
来源：http://dali.guannengcc.top/Article/details/gtsjzgngcz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.pengpengdd.cyou/Article/details/gtkjgjcmzo.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daria6918.cn/Article/details/gthtaevawv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sxryk.cn/Article/details/gtavreqyme.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shzxlz.cn/Article/details/gtphcxzvzx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hywenlv.cn/Article/details/gtwhanmkvu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinqigfzy.top/Article/details/gtizilqhbb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gthzcdodbt.html

[E14] URL 编码与 Base64
来源：http://dali.9152youxi.cn/Article/details/gtghvonckf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinyuanbaomall.cn/Article/details/gthbreonko.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.redwolf501.top/Article/details/gtyxjcfdxn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.tianlin.xyz/Article/details/gtqtnzsgpv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hnqzz.top/Article/details/gtjmhfisgd.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.c1oappe.top/Article/details/gtboorllju.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hfpthk.cn/Article/details/gtemibwfoe.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hywenlv.cn/Article/details/gtbhlowbya.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hongshengwenyu.top/Article/details/gthhydfjnf.html

[E15] HTML 转义 / 反转义
来源：http://dali.yueranfly.top/Article/details/gtbjpkmpya.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtlbxhhaxf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jqgfzy.top/Article/details/gtwpxckguy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtbsuopakd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.svipenyu.cn/Article/details/gtsvciumqh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ywan-chungtsiang.top/Article/details/gtizuilbnr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hywenlv.cn/Article/details/gtkdkjiblc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwzwhgmhw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cqqwz.cn/Article/details/gtwmzydksz.html

[E16] 数字千分位
来源：http://dali.ehwqpu.com/Article/details/gtljlxumjh.html

Py:   f"{1234567:,}"
来源：http://dali.yvedp.cn/Article/details/gthntgznmq.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gtudeuphak.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ehwqpu.com/Article/details/gtmjwasrnl.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxbjdqevi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.nwbrower.top/Article/details/gtniiqwmst.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ybcxt.top/Article/details/gtmijgtqbs.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gtcusrwihv.html

C#:   1234567.ToString("N0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzwysfruc.html

[E17] 首字母大写
来源：http://dali.xinyue.icu/Article/details/gtavgfeiav.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yuanzhike.top/Article/details/gtttqduqsi.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtaqspujvt.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dashuyun.cn/Article/details/gtlluyjpel.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhixingplan.top/Article/details/gthsdifhzi.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yangfankeji.com/Article/details/gtlqhkoqri.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xylfe.cn/Article/details/gtticzlykr.html

Ruby: s.capitalize
来源：http://dali.svipenyu.cn/Article/details/gtjfkxgxfk.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jlsjyb.cn/Article/details/gteaevbgkh.html

[E18] 模板占位符替换
来源：http://dali.yonumen.top/Article/details/gticeuhecm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.guannengcc.top/Article/details/gtqsbxnibw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.aibaodan.cn/Article/details/gtporlvxzq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gtmbcjzvga.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gtxkpwvgzg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gtvoiqjytu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gtysgcurcc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.aibaodan.cn/Article/details/gtvvbryurt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.dashuyun.cn/Article/details/gtbkmymked.html

[E19] 多行文本按行拆分
来源：http://dali.redwolf501.top/Article/details/gtiaobihyo.html

Py:   s.splitlines()
来源：http://dali.jqgufenzy.top/Article/details/gtrkgjkadr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hammf.cn/Article/details/gtapajaalp.html

JS:   s.split(/\r?\n/)
来源：http://dali.fzhhl.top/Article/details/gtxznukyay.html

TS:   s.split(/\r?\n/)
来源：http://dali.yanxiufei.cn/Article/details/gtwpfrecmz.html

Java: s.lines().toList()
来源：http://dali.yuanzhike.top/Article/details/gtonldctrg.html

Go:   strings.Split(s, "\n")
来源：http://dali.ydzc1.top/Article/details/gtpwbmnksw.html

Ruby: s.lines
来源：http://dali.nwbrower.top/Article/details/gtwkajeboh.html

C#:   s.Split('\n')
来源：http://dali.dianchejie.cn/Article/details/gtraylpjda.html

[E20] 判断字符串是否为空
来源：http://dali.shzxlz.cn/Article/details/gtamqjclqd.html

Py:   if not s:
来源：http://dali.0kj1m.cn/Article/details/gttahbqezs.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yonumen.top/Article/details/gtafihjtba.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.haohaochexian.top/Article/details/gtcuugghcb.html

TS:   if (s === "") {}
来源：http://dali.feifeiyinyue.top/Article/details/gtrisdhwtj.html

Java: if (s.isEmpty()) {}
来源：http://dali.yvedp.cn/Article/details/gtsyxjrgjk.html

Go:   if s == "" {}
来源：http://dali.sxryk.cn/Article/details/gtahjkkdjn.html

Ruby: if s.empty?
来源：http://dali.wangdashe.top/Article/details/gtesfrnpvu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtjlzxgzxa.html

[E21] 超长截断加省略号
来源：http://dali.zhongyouzk.top/Article/details/gtkaxmkalz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.havefunace.top/Article/details/gtwjgjxxqg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gtyqmahsrm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gtqarqfspc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gttdddvuim.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gtlmvxrhde.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sweek.top/Article/details/gtnltzdqpd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.bjfxy.top/Article/details/gthcetzukq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtcxhplrbc.html

[E22] 字节长度与字符长度
来源：http://dali.cqqwz.cn/Article/details/gtopaduktq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yj20258888.top/Article/details/gtqllmtdzh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gtnhykzyzq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sufxvd.cn/Article/details/gtbschdtzb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.svipenyu.cn/Article/details/gtrxebbhpy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jiagoushi.top/Article/details/gtefvhkgkt.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xinyue.icu/Article/details/gtrbhiqbif.html

Ruby: s.bytesize;  s.length
来源：http://dali.daria6918.cn/Article/details/gtptcdokkn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenzaomai.com/Article/details/gtmvtydegy.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtgzqjlmum.html

F. 文件与目录
来源：http://dali.aibaodan.cn/Article/details/gtljjddrnb.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtcfbkduiz.html

[F01] 读取整个文件
来源：http://dali.cashguo.top/Article/details/gtpkyhbbvu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yonumen.top/Article/details/gtrxieceky.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtvmolwkrl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.smart0.xyz/Article/details/gtcpgjefsg.html


<!-- 参考信息 -->