代发 wailian999

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yuanzhike.top/Article/details/gthfhketze.html

[D20] 统计每个元素出现次数
来源：http://dali.bjfxy.top/Article/details/gtwkstjzzf.html

Py:   Counter(arr)
来源：http://dali.pycfn.com/Article/details/gtydfkwggq.html

PHP:  array_count_values($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtwkoiamqw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.redwolf501.top/Article/details/gthjjhjimt.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.haohaochexian.top/Article/details/gtvtmdaobr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.kuanghao11.cn/Article/details/gtdftsxqut.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gtfrwrfzvw.html

Ruby: arr.tally
来源：http://dali.jianghu66.top/Article/details/gturjqqvtx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yj20258888.top/Article/details/gtbbfkqcio.html

[D21] 判断是否包含某元素
来源：http://dali.pengpengdd.cyou/Article/details/gtoeqkwtsy.html

Py:   x in arr
来源：http://dali.yongpay.top/Article/details/gtrtliqtpt.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cheryme.top/Article/details/gtvqappzyx.html

JS:   arr.includes(x)
来源：http://dali.yuxming.cn/Article/details/gtwxsescgi.html

TS:   arr.includes(x)
来源：http://dali.snrcjt.cn/Article/details/gtzentffsg.html

Java: list.contains(x)
来源：http://dali.gotoacloud.top/Article/details/gtvwmaqkcn.html

Go:   slices.Contains(arr, x)
来源：http://dali.ivvv.top/Article/details/gtrctgfwcn.html

Ruby: arr.include?(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaeaamfgl.html

C#:   list.Contains(x)
来源：http://dali.zycfv.cn/Article/details/gtwuwdcmnu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yueranfly.top/Article/details/gtmmuhucuy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.andypj.xyz/Article/details/gtqvxjiqwp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.nwbrower.top/Article/details/gtppejhlex.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zdqjudy.top/Article/details/gtzvakzvvc.html

TS:   [...arr];
来源：http://dali.yvedp.cn/Article/details/gttqostqhx.html

Java: new ArrayList<>(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvdjcveex.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.redwolf501.top/Article/details/gtxcbsppbs.html

Ruby: arr.dup;  arr.clone
来源：http://dali.316326.xyz/Article/details/gtjnkhgvyq.html

C#:   new List<int>(list);
来源：http://dali.shzxlz.cn/Article/details/gtncxxetev.html

[D23] reduce 累积计算
来源：http://dali.yangfankeji.com/Article/details/gtbzftzxel.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xinyue.icu/Article/details/gtgidbiknu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkioupazd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sweek.top/Article/details/gtflwinppg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.birdmap.top/Article/details/gtidmfwhum.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ppjwa.cn/Article/details/gthkdboyef.html

Go:   // 手写循环
来源：http://dali.birdmap.top/Article/details/gtwonaqurq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqiyghisy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xuetiantiany.cn/Article/details/gtlrsuxtkw.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhiwuduotai.top/Article/details/gttuftmdjz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zycfv.cn/Article/details/gtivspizik.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cashguo.top/Article/details/gtxixzbifj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.fzhhl.top/Article/details/gttrfhznio.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtgjnnxhht.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.aizwys.cn/Article/details/gtzfpfekzx.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gturfkgfyk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.smart0.xyz/Article/details/gtfrwkvgme.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.nanxinkj.top/Article/details/gtrlkwimhj.html

[D25] Set 集合去重与交并差
来源：http://dali.redwolf501.top/Article/details/gthdcwmzke.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.birdmap.top/Article/details/gtuxtvbuti.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shanyushiyangtech.top/Article/details/gtoizmixaf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jianghu66.top/Article/details/gtinzhgeyl.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.daria6918.cn/Article/details/gtlkcqbuhw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hammf.cn/Article/details/gtvjhfmqkf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hongshengwenyu.top/Article/details/gttndodria.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.dianchejie.cn/Article/details/gtjxggltha.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.bjfxy.top/Article/details/gtzivmhcuh.html

[D26] 数组转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtykacbdke.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ivvv.top/Article/details/gtzfcmplqs.html

PHP:  implode(", ", $arr);
来源：http://dali.yangfankeji.com/Article/details/gtrrwvgqhs.html

JS:   arr.join(", ")
来源：http://dali.hnqzz.top/Article/details/gtgeeyrttx.html

TS:   arr.join(", ")
来源：http://dali.jlsjyb.cn/Article/details/gtkmntlvqw.html

Java: String.join(", ", list)
来源：http://dali.pengpengdd.cyou/Article/details/gthugkvurh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthdmyvcsp.html

Ruby: arr.join(", ")
来源：http://dali.guannengcc.top/Article/details/gteckzcdnm.html

C#:   string.Join(", ", list)
来源：http://dali.zycfv.cn/Article/details/gtpdtqfmah.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtnqzplacd.html

E. 字符串处理
来源：http://dali.mhx1999.top/Article/details/gtdlzxdkvo.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtakolgnfj.html

[E01] 拼接字符串
来源：http://dali.sufxvd.cn/Article/details/gtwkceqalt.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yuxming.cn/Article/details/gtacostiuo.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ehwqpu.com/Article/details/gtyampjhhn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aizwys.cn/Article/details/gtejqtbzgq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yangfankeji.com/Article/details/gtuhyiewle.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.smart0.xyz/Article/details/gtclovuswb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.tianlin.xyz/Article/details/gtyvcnmjdz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sweek.top/Article/details/gtyfjivbog.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtkqnpplsq.html

[E02] 重复字符串
来源：http://dali.xuanzx.com/Article/details/gtbcmfiqjf.html

Py:   "ab" * 3
来源：http://dali.hongshengwenyu.top/Article/details/gtjhwqpwwq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.dianchejie.cn/Article/details/gtfflvztvm.html

JS:   "ab".repeat(3)
来源：http://dali.yuanzhike.top/Article/details/gtmlbobayr.html

TS:   "ab".repeat(3)
来源：http://dali.ppjwa.cn/Article/details/gtnhxsppie.html

Java: "ab".repeat(3)
来源：http://dali.snrcjt.cn/Article/details/gtxrokmllt.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jyoumei.cn/Article/details/gtdpajtjsb.html

Ruby: "ab" * 3
来源：http://dali.zhoulong.xyz/Article/details/gtfzxoxrfw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ivvv.top/Article/details/gtrxvcbgsa.html

[E03] 截取子串
来源：http://dali.jqgfzy.top/Article/details/gtplkrkhnf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.wangshuangyany.cn/Article/details/gtrklybcnp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gtyllvqsnb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yuxming.cn/Article/details/gtvpttrmlc.html

TS:   s.slice(1, 4)
来源：http://dali.hnqzz.top/Article/details/gtglvdsayz.html

Java: s.substring(1, 4)
来源：http://dali.gogol.net.cn/Article/details/gtfeblmjfq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhongyouzk.top/Article/details/gtehuizemz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.pycfn.com/Article/details/gtnvjezugh.html

C#:   s.Substring(1, 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtkxeaajqs.html

[E04] 查找子串位置
来源：http://dali.quarkkingdee.top/Article/details/gtiowppwiq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hammf.cn/Article/details/gtdocxbfrh.html

PHP:  strpos($s, "x");
来源：http://dali.meibo888.top/Article/details/gtqguuzzvn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xylfe.cn/Article/details/gtcgvdwhfu.html

TS:   s.indexOf("x")
来源：http://dali.gaohongyu789.top/Article/details/gtwijawcmv.html

Java: s.indexOf("x")
来源：http://dali.aizwys.cn/Article/details/gtcfdxnykf.html

Go:   strings.Index(s, "x")
来源：http://dali.yj20258.top/Article/details/gtvulywzur.html

Ruby: s.index("x")
来源：http://dali.aizwys.cn/Article/details/gtovigtsmt.html

C#:   s.IndexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gtflacepvp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxsyzjtcc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.snrcjt.cn/Article/details/gtuyifjihp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.dashuyun.cn/Article/details/gtfknynkgz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.birdmap.top/Article/details/gttdnnjsex.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.guowangkeji.top/Article/details/gthihetyuh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxinkj.top/Article/details/gtlzbtamab.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.fengsongda.top/Article/details/gtruczefar.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jqgufenzy.top/Article/details/gtgiyztvnd.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gtxfuknagg.html

[E06] 替换子串
来源：http://dali.chenzaomai.com/Article/details/gtzmjdyyvt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cashguo.top/Article/details/gteefjstmw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj20258888.top/Article/details/gtqimfjqrd.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtbqstvnss.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtnodqqkkv.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gthtvifvul.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cqqwz.cn/Article/details/gtdjjblpzf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtpqvwhcof.html

C#:   s.Replace("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtkkczamwe.html

[E07] 按分隔符拆分
来源：http://dali.ivvv.top/Article/details/gtcnrdmfjn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.smart0.xyz/Article/details/gtunyzydje.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xylfe.cn/Article/details/gtryytpkji.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.havefunace.top/Article/details/gtrwsyqndl.html

TS:   s.split(",")
来源：http://dali.hywenlv.cn/Article/details/gtjhcpbmey.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.nwbrower.top/Article/details/gtzprchspy.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgpsoroeo.html

Ruby: s.split(",");  s.split
来源：http://dali.jinghuilouyu.cn/Article/details/gtodfageue.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.wangdashe.top/Article/details/gtggvkurqj.html

[E08] 数组按分隔符合并
来源：http://dali.gzhubu.top/Article/details/gtviirivgq.html

Py:   ",".join(items)
来源：http://dali.jlsjyb.cn/Article/details/gtyxgzxixx.html

PHP:  implode(",", $items);
来源：http://dali.gogol.net.cn/Article/details/gtvebaehtx.html

JS:   items.join(",")
来源：http://dali.tanke756.top/Article/details/gtwftxdodw.html

TS:   items.join(",")
来源：http://dali.nanxinkj.top/Article/details/gthupxhycf.html

Java: String.join(",", items)
来源：http://dali.xziqi.cn/Article/details/gtzxoftfzd.html

Go:   strings.Join(items, ",")
来源：http://dali.dashuyun.cn/Article/details/gtdftimcqf.html

Ruby: items.join(",")
来源：http://dali.shzxlz.cn/Article/details/gtzzebxjsl.html

C#:   string.Join(",", items)
来源：http://dali.xinyue.icu/Article/details/gtdtdpggmp.html

[E09] 去除所有空白字符
来源：http://dali.aibaodan.cn/Article/details/gteaqpnorh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlnmyqnpb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tian-w.cn/Article/details/gtkjvptawt.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.aibaodan.cn/Article/details/gtnhzeadoy.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xylfe.cn/Article/details/gtieqtsrzv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.daxiang520.top/Article/details/gtisygydus.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhoulong.xyz/Article/details/gtmibklnii.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.haohaochexian.top/Article/details/gtmicodufa.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sweek.top/Article/details/gtzlinsmaq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.nanxinkj.top/Article/details/gthcpntynf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gtlnfubjaw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.haohaochexian.top/Article/details/gtuivffqhv.html

JS:   "7".padStart(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gtxxaabpnw.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gtvdhkrkmj.html

Java: String.format("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gtpyrabynw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gtfuqngxgg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gthpajadoa.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.bjfxy.top/Article/details/gtqonbxlff.html

[E11] 反转字符串
来源：http://dali.fengsongda.top/Article/details/gtvemhamzi.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gtugzazvee.html

PHP:  strrev($s);
来源：http://dali.smart0.xyz/Article/details/gtuzmsmnhr.html

JS:   [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gtkzfwxigi.html

TS:   [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gtsidrlklu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvjwphrbu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.tianlin.xyz/Article/details/gthxhmpcbb.html

Ruby: s.reverse
来源：http://dali.yj20258.top/Article/details/gtmvgeeueo.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gogol.net.cn/Article/details/gtnkwcniyf.html

[E12] 统计某字符出现次数
来源：http://dali.jqgufenzy.top/Article/details/gtpicfienj.html

Py:   s.count("a")
来源：http://dali.nanxuanxn.top/Article/details/gtfdkrlzsx.html

PHP:  substr_count($s, "a");
来源：http://dali.jinqigfzy.top/Article/details/gtxxwdqmfk.html

JS:   s.split("a").length - 1
来源：http://dali.pycfn.com/Article/details/gtuarmdfsc.html

TS:   s.split("a").length - 1
来源：http://dali.dashuyun.cn/Article/details/gtlxbctisr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.nwbrower.top/Article/details/gtunclllep.html

Go:   strings.Count(s, "a")
来源：http://dali.hysaishi.cn/Article/details/gtrpevotvj.html

Ruby: s.count("a")
来源：http://dali.bjfxy.top/Article/details/gtfrvkxtkf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hnxiangtu.top/Article/details/gtvomnrusd.html

[E13] 逐字符遍历
来源：http://dali.chenlongwang.top/Article/details/gtqsvkuxdl.html

Py:   for ch in s: print(ch)
来源：http://dali.kuanghao11.cn/Article/details/gtvewnbqkr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj20258.top/Article/details/gtevxjjakd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gticmcnmei.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuxming.cn/Article/details/gtkxjozppc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yonumen.top/Article/details/gtlqvvqehg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cheryme.top/Article/details/gtkuxcwbpb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ivvv.top/Article/details/gtueexpynu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gtivcwarre.html

[E14] URL 编码与 Base64
来源：http://dali.ivvv.top/Article/details/gtlyiumybf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sweek.top/Article/details/gtnidmpvke.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ybcxt.top/Article/details/gtgddvmqka.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shanyushiyangtech.top/Article/details/gtewkbtpcv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.dianchejie.cn/Article/details/gtqfhdvytt.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.smart0.xyz/Article/details/gtmqkaxbao.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shzxlz.cn/Article/details/gtsbokjdlu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jqgufenzy.top/Article/details/gtqlcvxkpp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hysaishi.cn/Article/details/gtsbxjzszl.html

[E15] HTML 转义 / 反转义
来源：http://dali.shzxlz.cn/Article/details/gtofpcplrl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.haohaochexian.top/Article/details/gtscujpqxs.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.wangdashe.top/Article/details/gtvsqqjtdp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.bjfxy.top/Article/details/gtpxxtryyi.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhoulong.xyz/Article/details/gtkyhbinyz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.feifeiyinyue.top/Article/details/gtgugiaqii.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.wangshuangyany.cn/Article/details/gthtqeuqmu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinqigfzy.top/Article/details/gtzmyysnto.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sysykeji.top/Article/details/gtxheesqqy.html

[E16] 数字千分位
来源：http://dali.daxiang520.top/Article/details/gthrqhitqg.html

Py:   f"{1234567:,}"
来源：http://dali.tianlin.xyz/Article/details/gtxldntlst.html

PHP:  number_format(1234567);
来源：http://dali.jyoumei.cn/Article/details/gthiogxora.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yueranfly.top/Article/details/gtskpizdtp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sufxvd.cn/Article/details/gtofvzpqxt.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenlongwang.top/Article/details/gthiiochsa.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jianghu66.top/Article/details/gtaonawiks.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yueranfly.top/Article/details/gtvucnqjby.html

C#:   1234567.ToString("N0")
来源：http://dali.aibaodan.cn/Article/details/gtkvyoznxr.html

[E17] 首字母大写
来源：http://dali.tian-w.cn/Article/details/gtxxmigqai.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhengqikj.top/Article/details/gtzluakqup.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jianghu66.top/Article/details/gtiyvfxgpm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyaonfmlw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hfpthk.cn/Article/details/gttfzakjwh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xinyue.icu/Article/details/gtndyjzazc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yueranfly.top/Article/details/gtwcwdmstb.html

Ruby: s.capitalize
来源：http://dali.nanxuanxn.top/Article/details/gtxdelmwxq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ehwqpu.com/Article/details/gtybhbmlpw.html

[E18] 模板占位符替换
来源：http://dali.yangfankeji.com/Article/details/gtlgmvtlkr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jianghu66.top/Article/details/gtfpbpqsra.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.pengpengdd.cyou/Article/details/gtbdxgbrei.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ppjwa.cn/Article/details/gtniatctdm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gtapnchgzb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gtzdogjwqr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.mhx1999.top/Article/details/gtyhtdrtey.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tianlin.xyz/Article/details/gtirnlyhmy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xylfe.cn/Article/details/gtaytejzqt.html

[E19] 多行文本按行拆分
来源：http://dali.tanke756.top/Article/details/gtiupbgnwi.html

Py:   s.splitlines()
来源：http://dali.iojbl.cn/Article/details/gtgrqaegom.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gzhubu.top/Article/details/gtziwjplmg.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinqigufen.top/Article/details/gtkocsusvr.html

TS:   s.split(/\r?\n/)
来源：http://dali.ppjwa.cn/Article/details/gtdbbfszrz.html

Java: s.lines().toList()
来源：http://dali.gzhubu.top/Article/details/gttccjlkxu.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcuxiwszr.html

Ruby: s.lines
来源：http://dali.smart0.xyz/Article/details/gtvkazokwq.html

C#:   s.Split('\n')
来源：http://dali.cheryme.top/Article/details/gtpwsgzpjq.html

[E20] 判断字符串是否为空
来源：http://dali.haohaochexian.top/Article/details/gtrszwvron.html

Py:   if not s:
来源：http://dali.smart0.xyz/Article/details/gtjkzlsxce.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xuanzx.com/Article/details/gtewguyxtc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhixingplan.top/Article/details/gtjumkbmbp.html

TS:   if (s === "") {}
来源：http://dali.cqqwz.cn/Article/details/gtjchrusuv.html

Java: if (s.isEmpty()) {}
来源：http://dali.havefunace.top/Article/details/gtqzmuljmx.html

Go:   if s == "" {}
来源：http://dali.chenzaomai.com/Article/details/gtxbpzorxq.html

Ruby: if s.empty?
来源：http://dali.tianlin.xyz/Article/details/gtrevbomnv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shzxlz.cn/Article/details/gtolelugeo.html

[E21] 超长截断加省略号
来源：http://dali.tian-w.cn/Article/details/gtixvdunss.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenzaomai.com/Article/details/gtqqebveii.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvkjwcbjv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtkypvoosb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtulfhkild.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtfvlzwrha.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jianghu66.top/Article/details/gtscnuqpel.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtffddswgu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpaymbpta.html

[E22] 字节长度与字符长度
来源：http://dali.hnxiangtu.top/Article/details/gtddkbwcab.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gogol.net.cn/Article/details/gtyombmjut.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gtixvdrmwd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gtktigdocl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hammf.cn/Article/details/gtgjlddluz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xinyue.icu/Article/details/gtyhgshpui.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.smart0.xyz/Article/details/gtuvdsqwoh.html

Ruby: s.bytesize;  s.length
来源：http://dali.jiagoushi.top/Article/details/gtookakfwk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nanxinkj.top/Article/details/gtihlfuxus.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtigsufgop.html

F. 文件与目录
来源：http://dali.yj20258888.top/Article/details/gtdzvhocjh.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtenvflzvo.html

[F01] 读取整个文件
来源：http://dali.shuidangran.top/Article/details/gtvciijewt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gogol.net.cn/Article/details/gtfteckqhe.html

PHP:  file_get_contents("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gterumvdgl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.snrcjt.cn/Article/details/gteexyicqd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gtfhugdbny.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gtucbaiehl.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.feifeiyinyue.top/Article/details/gtddyjsfid.html

Ruby: File.read("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtwkkxaudf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtorqlbyxr.html

[F02] 逐行读取文件
来源：http://dali.jinqigufen.top/Article/details/gtenhqkknz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sxryk.cn/Article/details/gtmfadrhoq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.316326.xyz/Article/details/gtrlcnuxtx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zdqjudy.top/Article/details/gthsuzigyv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fengsongda.top/Article/details/gtqrpwwgdt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.chenzaomai.com/Article/details/gtjiktiqds.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.guannengcc.top/Article/details/gtfxsaxnms.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.tianlin.xyz/Article/details/gtdeuellms.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrshkzxdj.html

[F03] 写入文件（覆盖）
来源：http://dali.yuanzhike.top/Article/details/gtuahpduzp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj202588.top/Article/details/gtlvwyfejc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinghuilouyu.cn/Article/details/gtrdkdbvtd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sysykeji.top/Article/details/gtpdtjtdaj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xylfe.cn/Article/details/gtcgbnnycp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cucudq.cn/Article/details/gtanzaxmvi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.dianchejie.cn/Article/details/gttdzhrzpw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttccfteil.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gtdtzynppj.html

[F04] 追加写入文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkchiovnh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.0kj1m.cn/Article/details/gtvmuwsytz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqeogcmlu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.316326.xyz/Article/details/gtdxyxjayj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigfzy.top/Article/details/gtokxmutsv.html


<!-- 参考信息 -->