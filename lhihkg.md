代发 wailian999

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jqgfzy.top/Article/details/gtlqwyanvb.html

[D20] 统计每个元素出现次数
来源：http://dali.gaohongyu789.top/Article/details/gtftcxqtyq.html

Py:   Counter(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtdvsgrgcu.html

PHP:  array_count_values($arr);
来源：http://dali.jqgufenzy.top/Article/details/gttxpteasg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ppjwa.cn/Article/details/gtrhnrbein.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvmxhgqkj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hywenlv.cn/Article/details/gtxcffkidz.html

Go:   // 手写 map[T]int
来源：http://dali.nanxuanxn.top/Article/details/gtdojbvnuc.html

Ruby: arr.tally
来源：http://dali.jyoumei.cn/Article/details/gthgsjlmnv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.bjfxy.top/Article/details/gtfycczybc.html

[D21] 判断是否包含某元素
来源：http://dali.guannengcc.top/Article/details/gtqioleuqa.html

Py:   x in arr
来源：http://dali.ehwqpu.com/Article/details/gtqmzioowk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xuanzx.com/Article/details/gtqsguhect.html

JS:   arr.includes(x)
来源：http://dali.snrcjt.cn/Article/details/gtwwefbqmo.html

TS:   arr.includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gtghdyziql.html

Java: list.contains(x)
来源：http://dali.yj20258888.top/Article/details/gtzganvkbc.html

Go:   slices.Contains(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtwdexcyvz.html

Ruby: arr.include?(x)
来源：http://dali.gzhubu.top/Article/details/gtuhjemeyn.html

C#:   list.Contains(x)
来源：http://dali.shuidangran.top/Article/details/gtjjlvpylz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.redwolf501.top/Article/details/gtwuvlryhc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.dashuyun.cn/Article/details/gtihcxpall.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinqigufen.top/Article/details/gtjoaweoys.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.bjfxy.top/Article/details/gtaguwtmxv.html

TS:   [...arr];
来源：http://dali.hongshengwenyu.top/Article/details/gtvjcnwfji.html

Java: new ArrayList<>(list);
来源：http://dali.daxiang520.top/Article/details/gtmmghyjcs.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhoulong.xyz/Article/details/gtmklkzlpn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.quarkkingdee.top/Article/details/gtxsmoincw.html

C#:   new List<int>(list);
来源：http://dali.dashuyun.cn/Article/details/gtyegeitgp.html

[D23] reduce 累积计算
来源：http://dali.yongpay.top/Article/details/gtdnrrmale.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ehwqpu.com/Article/details/gtfghhuwhz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xinyue.icu/Article/details/gtlconkolj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cqqwz.cn/Article/details/gtndjjujjb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yonumen.top/Article/details/gtlqlsokvq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jlsjyb.cn/Article/details/gtxdmxnbmj.html

Go:   // 手写循环
来源：http://dali.cqqwz.cn/Article/details/gtpymgqdbu.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.redwolf501.top/Article/details/gtxwwlxvrp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cheryme.top/Article/details/gtzxgunbbn.html

[D24] 字典 / Map 基本操作
来源：http://dali.havefunace.top/Article/details/gtyazpnmrj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.aibaodan.cn/Article/details/gtrtqxrpkd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yangfankeji.com/Article/details/gtsceqypdu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hfpthk.cn/Article/details/gtjgluhjgs.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cheryme.top/Article/details/gtlbzmwryb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shuidangran.top/Article/details/gtqlgbqqxq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jlsjyb.cn/Article/details/gtkzzowotn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jiagoushi.top/Article/details/gtmravvzzt.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.bjfxy.top/Article/details/gtfpyaxqos.html

[D25] Set 集合去重与交并差
来源：http://dali.bjfxy.top/Article/details/gtybsxhfop.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.daxiang520.top/Article/details/gtnexxkbvu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrqzpjdon.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jiagoushi.top/Article/details/gthemnbcqt.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jqgufenzy.top/Article/details/gtlhgnixji.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yanxiufei.cn/Article/details/gtrigchwha.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.nanxinkj.top/Article/details/gtcklywipt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zdqjudy.top/Article/details/gtkhjcnzhh.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.andypj.xyz/Article/details/gtsvxmvvbe.html

[D26] 数组转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtovyrpokq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.bjfxy.top/Article/details/gthbzmrvll.html

PHP:  implode(", ", $arr);
来源：http://dali.dashuyun.cn/Article/details/gthvuizmur.html

JS:   arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gtpogziguk.html

TS:   arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gtqiolyfcd.html

Java: String.join(", ", list)
来源：http://dali.shzxlz.cn/Article/details/gtijoywrmi.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cucudq.cn/Article/details/gtxmojsgqn.html

Ruby: arr.join(", ")
来源：http://dali.quarkkingdee.top/Article/details/gtocngimvw.html

C#:   string.Join(", ", list)
来源：http://dali.wangshuangyany.cn/Article/details/gtxlsrlfak.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtzklbgoex.html

E. 字符串处理
来源：http://dali.jinqigufen.top/Article/details/gtxbisywev.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtwafgdwgq.html

[E01] 拼接字符串
来源：http://dali.snrcjt.cn/Article/details/gtvuarbltu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.haohaochexian.top/Article/details/gtgilirsaj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.fzhhl.top/Article/details/gtwahqprhk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhoulong.xyz/Article/details/gtfrdbbeks.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.birdmap.top/Article/details/gtmnnajtvk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.guannengcc.top/Article/details/gtabzcormh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinqigfzy.top/Article/details/gthrtlhdvt.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jianghu66.top/Article/details/gtiwqcbhee.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtilpppsqz.html

[E02] 重复字符串
来源：http://dali.hammf.cn/Article/details/gtrbiiwhkf.html

Py:   "ab" * 3
来源：http://dali.316326.xyz/Article/details/gtwjgmevsd.html

PHP:  str_repeat("ab", 3);
来源：http://dali.tanke756.top/Article/details/gtdcpvwmzh.html

JS:   "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gtrtgmhnjr.html

TS:   "ab".repeat(3)
来源：http://dali.xinyue.icu/Article/details/gtvrgzukns.html

Java: "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gtzrxduyam.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.iojbl.cn/Article/details/gtppejopfs.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gtwflfxqpw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ppjwa.cn/Article/details/gteqghmlux.html

[E03] 截取子串
来源：http://dali.ppjwa.cn/Article/details/gtgkrftobs.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.daxiang520.top/Article/details/gtaaukcnls.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gtimezfyru.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.guannengcc.top/Article/details/gtjqrbqmos.html

TS:   s.slice(1, 4)
来源：http://dali.jqgfzy.top/Article/details/gthxtiduaq.html

Java: s.substring(1, 4)
来源：http://dali.xziqi.cn/Article/details/gtsalljhew.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.tian-w.cn/Article/details/gtmlltjtpl.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.chenzaomai.com/Article/details/gtxdtutawx.html

C#:   s.Substring(1, 3)
来源：http://dali.sweek.top/Article/details/gtbshdlubh.html

[E04] 查找子串位置
来源：http://dali.zhoulong.xyz/Article/details/gtgbirmpah.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yvedp.cn/Article/details/gtedkebcgk.html

PHP:  strpos($s, "x");
来源：http://dali.xuetiantiany.cn/Article/details/gtfbouwvtu.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yvedp.cn/Article/details/gtciiwhvja.html

TS:   s.indexOf("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gtcxtpxwqy.html

Java: s.indexOf("x")
来源：http://dali.ybcxt.top/Article/details/gtwxkunora.html

Go:   strings.Index(s, "x")
来源：http://dali.yj202588.top/Article/details/gtphtiyhmf.html

Ruby: s.index("x")
来源：http://dali.pengpengdd.cyou/Article/details/gtwaedvuwv.html

C#:   s.IndexOf("x")
来源：http://dali.c1oappe.top/Article/details/gtkemhpace.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ybcxt.top/Article/details/gtdqxyjuql.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.dashuyun.cn/Article/details/gtnxbnftfd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.0kj1m.cn/Article/details/gtfntxhbuq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sxryk.cn/Article/details/gtycvxaxlo.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shuidangran.top/Article/details/gtxxbqegnf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxuanxn.top/Article/details/gtstituurc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hysaishi.cn/Article/details/gtyvbikqgt.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.quarkkingdee.top/Article/details/gtkzdsrrtu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jqgufenzy.top/Article/details/gtwtqfydum.html

[E06] 替换子串
来源：http://dali.zhoulong.xyz/Article/details/gtyvxdbvqt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhixingplan.top/Article/details/gtorttxcul.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhixingplan.top/Article/details/gtzygegvxs.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gthpajlffk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gtdznxaxxi.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtigdwduvq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zycfv.cn/Article/details/gteaixzavm.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtiisbpquy.html

C#:   s.Replace("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtaqpnflyb.html

[E07] 按分隔符拆分
来源：http://dali.nanxuanxn.top/Article/details/gtqwvvgvds.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hnqzz.top/Article/details/gtqwysulhq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.c1oappe.top/Article/details/gtwqdmvbyl.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.9152youxi.cn/Article/details/gtzpexthsr.html

TS:   s.split(",")
来源：http://dali.ppjwa.cn/Article/details/gtxljwlyki.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.kuanghao11.cn/Article/details/gtjzgpumtf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtwqkbpdyb.html

Ruby: s.split(",");  s.split
来源：http://dali.nanxuanxn.top/Article/details/gtubrorvwc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyjoplkli.html

[E08] 数组按分隔符合并
来源：http://dali.c1oappe.top/Article/details/gtvgyfuhpe.html

Py:   ",".join(items)
来源：http://dali.hfpthk.cn/Article/details/gtqniziwev.html

PHP:  implode(",", $items);
来源：http://dali.gzhubu.top/Article/details/gteggyuvum.html

JS:   items.join(",")
来源：http://dali.yonumen.top/Article/details/gtqgydtzvg.html

TS:   items.join(",")
来源：http://dali.cheryme.top/Article/details/gtzlyilkhf.html

Java: String.join(",", items)
来源：http://dali.sweek.top/Article/details/gtcggxpgnk.html

Go:   strings.Join(items, ",")
来源：http://dali.yvedp.cn/Article/details/gtfmqvhvvx.html

Ruby: items.join(",")
来源：http://dali.pycfn.com/Article/details/gtornivepo.html

C#:   string.Join(",", items)
来源：http://dali.316326.xyz/Article/details/gtkbqpiksi.html

[E09] 去除所有空白字符
来源：http://dali.yj202588.top/Article/details/gtgtnwttsh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cucudq.cn/Article/details/gttswlxtxm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tianlin.xyz/Article/details/gtvskfxhor.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.c1oappe.top/Article/details/gtxaucdixh.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cheryme.top/Article/details/gtwpomzzxm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yueranfly.top/Article/details/gtaogrlznk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.316326.xyz/Article/details/gtuevtcvsn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hfpthk.cn/Article/details/gtfmcizoqg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj20258.top/Article/details/gtfwxtzgin.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ybcxt.top/Article/details/gtixoofekl.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gtytpezxpe.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yangfankeji.com/Article/details/gtomuwgkcj.html

JS:   "7".padStart(3, "0")
来源：http://dali.daria6918.cn/Article/details/gtrxjjdosy.html

TS:   "7".padStart(3, "0")
来源：http://dali.fengsongda.top/Article/details/gtnbqtcxsh.html

Java: String.format("%03d", 7)
来源：http://dali.jqgufenzy.top/Article/details/gtyafnietz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gtimsbaejx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gtflusnqzk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.9152youxi.cn/Article/details/gtydduotjf.html

[E11] 反转字符串
来源：http://dali.daria6918.cn/Article/details/gtojhfcdny.html

Py:   s[::-1]
来源：http://dali.gotoacloud.top/Article/details/gtiqyurwis.html

PHP:  strrev($s);
来源：http://dali.tianlin.xyz/Article/details/gtzvalqmwo.html

JS:   [...s].reverse().join("")
来源：http://dali.ehwqpu.com/Article/details/gtkneldgfl.html

TS:   [...s].reverse().join("")
来源：http://dali.yj202588.top/Article/details/gtoyvfjihx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yuanzhike.top/Article/details/gtbuclbegc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hysaishi.cn/Article/details/gtfqvfnrng.html

Ruby: s.reverse
来源：http://dali.daxiang520.top/Article/details/gttvaaricl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.kuanghao11.cn/Article/details/gtzvliizve.html

[E12] 统计某字符出现次数
来源：http://dali.bjfxy.top/Article/details/gtiyfeofwx.html

Py:   s.count("a")
来源：http://dali.ybcxt.top/Article/details/gtngfjimoo.html

PHP:  substr_count($s, "a");
来源：http://dali.daria6918.cn/Article/details/gtmsapeqrx.html

JS:   s.split("a").length - 1
来源：http://dali.chenzaomai.com/Article/details/gtdonuishb.html

TS:   s.split("a").length - 1
来源：http://dali.chenjidiqi.icu/Article/details/gtcjrvdjbb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenlongwang.top/Article/details/gtvvlwbwsu.html

Go:   strings.Count(s, "a")
来源：http://dali.hfpthk.cn/Article/details/gtyhnecvag.html

Ruby: s.count("a")
来源：http://dali.wangshuangyany.cn/Article/details/gtlryvxbtc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yanxiufei.cn/Article/details/gtshtbaczl.html

[E13] 逐字符遍历
来源：http://dali.hnqzz.top/Article/details/gtsgvvcbch.html

Py:   for ch in s: print(ch)
来源：http://dali.cashguo.top/Article/details/gtvrzzcpjh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.redwolf501.top/Article/details/gtnixkmrik.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guowangkeji.top/Article/details/gtnktegymg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cheryme.top/Article/details/gtmlnqhqge.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ehwqpu.com/Article/details/gtigkqzgip.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jqgufenzy.top/Article/details/gtbrvvijwo.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtifwkcmty.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yj20258888.top/Article/details/gtcxmavmnk.html

[E14] URL 编码与 Base64
来源：http://dali.haohaochexian.top/Article/details/gtjlotwmtl.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yanxiufei.cn/Article/details/gtvkcmcnwc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hammf.cn/Article/details/gtqqopyonq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.redwolf501.top/Article/details/gtacdpxhai.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.kuanghao11.cn/Article/details/gtgltqheju.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.guannengcc.top/Article/details/gtjwigcnkk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.pycfn.com/Article/details/gtmxhynqfo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.fengsongda.top/Article/details/gtynoayfgo.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jlsjyb.cn/Article/details/gtmtreoqni.html

[E15] HTML 转义 / 反转义
来源：http://dali.gogol.net.cn/Article/details/gtwzfydgxj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtrylprnfc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sysykeji.top/Article/details/gtotqpafbl.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ppjwa.cn/Article/details/gtfympkavi.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.wangdashe.top/Article/details/gtjxnvfuxy.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xinyue.icu/Article/details/gtvrucvfym.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.fengsongda.top/Article/details/gtdppuywfg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.mhx1999.top/Article/details/gteecrdedg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhoulong.xyz/Article/details/gtaymubscu.html

[E16] 数字千分位
来源：http://dali.316326.xyz/Article/details/gtxzairxvm.html

Py:   f"{1234567:,}"
来源：http://dali.redwolf501.top/Article/details/gtkcqefafi.html

PHP:  number_format(1234567);
来源：http://dali.yonumen.top/Article/details/gtufutipxv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.haohaochexian.top/Article/details/gtmttzusdi.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuetiantiany.cn/Article/details/gtipcbtahv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ivvv.top/Article/details/gtyaymzwxk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.daxiang520.top/Article/details/gtwkbvgmtm.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuyfbhnzl.html

C#:   1234567.ToString("N0")
来源：http://dali.tanke756.top/Article/details/gtuzlxkbfx.html

[E17] 首字母大写
来源：http://dali.yuanzhike.top/Article/details/gtxgprmrsu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shangyingyoupin.top/Article/details/gtjfjawipl.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.redwolf501.top/Article/details/gtqhtjtlum.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.havefunace.top/Article/details/gtnkfrnoqq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cashguo.top/Article/details/gtifyzucfv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtstqprcqu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yuanzhike.top/Article/details/gtblvfvsxe.html

Ruby: s.capitalize
来源：http://dali.pengpengdd.cyou/Article/details/gtagtokqye.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jqgufenzy.top/Article/details/gtdvatnxss.html

[E18] 模板占位符替换
来源：http://dali.xuanzx.com/Article/details/gtqvgkpltf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xinyue.icu/Article/details/gtgngcolnr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhiwuduotai.top/Article/details/gtgxptvhls.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258.top/Article/details/gtfgcpqsog.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gtcwgnfdvj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gtpfsdvxcr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yj20258888.top/Article/details/gtvnbtuksh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.dianchejie.cn/Article/details/gtkgveogdw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhixingplan.top/Article/details/gtkpggbptr.html

[E19] 多行文本按行拆分
来源：http://dali.sufxvd.cn/Article/details/gtbegtsfyv.html

Py:   s.splitlines()
来源：http://dali.guowangkeji.top/Article/details/gtbfmhzkzt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gttqxcdmvu.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gtqemiavak.html

TS:   s.split(/\r?\n/)
来源：http://dali.mhx1999.top/Article/details/gtlphbhphh.html

Java: s.lines().toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtrmvnnxoa.html

Go:   strings.Split(s, "\n")
来源：http://dali.yongpay.top/Article/details/gtbwlyuyzv.html

Ruby: s.lines
来源：http://dali.cheryme.top/Article/details/gtlqkkzatb.html

C#:   s.Split('\n')
来源：http://dali.vqdsnc.cn/Article/details/gtoavhuubp.html

[E20] 判断字符串是否为空
来源：http://dali.tianlin.xyz/Article/details/gtoaqkokpy.html

Py:   if not s:
来源：http://dali.316326.xyz/Article/details/gtvzzocekj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jianghu66.top/Article/details/gtdticgxkw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.pycfn.com/Article/details/gtuijupnan.html

TS:   if (s === "") {}
来源：http://dali.9152youxi.cn/Article/details/gtgumvdsyl.html

Java: if (s.isEmpty()) {}
来源：http://dali.ybcxt.top/Article/details/gtqpndhmha.html

Go:   if s == "" {}
来源：http://dali.c1oappe.top/Article/details/gtrbemtaag.html

Ruby: if s.empty?
来源：http://dali.jinghuilouyu.cn/Article/details/gtenpltgou.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhongyouzk.top/Article/details/gtypqspkck.html

[E21] 超长截断加省略号
来源：http://dali.yj20258888.top/Article/details/gtveugtinr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xinyue.icu/Article/details/gtyejloftq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gttyyhxkqe.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sweek.top/Article/details/gtcvctiwcc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.havefunace.top/Article/details/gtofpoxwij.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gtwaxnyyna.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gotoacloud.top/Article/details/gtzwkthxfx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtngplmkiu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtwyxfqeuv.html

[E22] 字节长度与字符长度
来源：http://dali.ydzc1.top/Article/details/gtjjvorqat.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nanxinkj.top/Article/details/gtlzkueztb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tanke756.top/Article/details/gtdkbsfnte.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cqqwz.cn/Article/details/gtkqfwixku.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.mhx1999.top/Article/details/gtrwfybmvt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yj20258888.top/Article/details/gtplapjfzb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xziqi.cn/Article/details/gtziwtbnnt.html

Ruby: s.bytesize;  s.length
来源：http://dali.cucudq.cn/Article/details/gtcsajhcgq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.guannengcc.top/Article/details/gtstqjuyil.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtgtphknjk.html

F. 文件与目录
来源：http://dali.kuanghao11.cn/Article/details/gticbjmawb.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtbnvhlcct.html

[F01] 读取整个文件
来源：http://dali.shanyushiyangtech.top/Article/details/gttnxwcydf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.andypj.xyz/Article/details/gtceewshdz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtllnfrwcl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.snrcjt.cn/Article/details/gtizolpzzf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gtrmvadtuk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gtorcpgmlw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.aibaodan.cn/Article/details/gtycewfmfw.html

Ruby: File.read("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtxdrhtpol.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtkndcgrcg.html

[F02] 逐行读取文件
来源：http://dali.shuidangran.top/Article/details/gtgernuvsh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.birdmap.top/Article/details/gtansosbrq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hongshengwenyu.top/Article/details/gtvgkqacef.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.vqdsnc.cn/Article/details/gtaikoroil.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.vqdsnc.cn/Article/details/gtbrtfxlnl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jqgufenzy.top/Article/details/gtdpvsgxuw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hywenlv.cn/Article/details/gtmkwnjoaq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.iojbl.cn/Article/details/gtpnlqlidn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.vqdsnc.cn/Article/details/gtfrawctpj.html

[F03] 写入文件（覆盖）
来源：http://dali.9152youxi.cn/Article/details/gtnexshyyk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gteaynbsoh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gzhubu.top/Article/details/gtituqmqsw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.mhx1999.top/Article/details/gtmyspqigy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xylfe.cn/Article/details/gtfzzglbck.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.dashuyun.cn/Article/details/gtpcpirqsi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxxrnvkun.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gotoacloud.top/Article/details/gtfdatapie.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cdnleiting.top/Article/details/gtksnyvmmi.html

[F04] 追加写入文件
来源：http://dali.zhongyouzk.top/Article/details/gtusuegkaw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtatuvnudb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jiagoushi.top/Article/details/gtjqygzjib.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhoulong.xyz/Article/details/gtzquhmwcp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dianchejie.cn/Article/details/gtgfjnhnaz.html


<!-- 参考信息 -->