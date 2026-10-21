代发 wailian999

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnqzz.top/Article/details/gtpzgevaeb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.kuanghao11.cn/Article/details/gtnggcvfnr.html

Go:   // 手写循环
来源：http://dali.cqqwz.cn/Article/details/gtjlnnabla.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.snrcjt.cn/Article/details/gtbvhqpdma.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yj20258888.top/Article/details/gtlrjqplyr.html

[D24] 字典 / Map 基本操作
来源：http://dali.wangdashe.top/Article/details/gtavjkfimp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.tian-w.cn/Article/details/gtifnivizu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.316326.xyz/Article/details/gtlcgzvvgf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yuanzhike.top/Article/details/gtceuwhnbz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gtmndmqbef.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hammf.cn/Article/details/gtijldsbpq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xuetiantiany.cn/Article/details/gtcysufcxn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.haohaochexian.top/Article/details/gtsgtccevs.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.mhx1999.top/Article/details/gtxvbonhjq.html

[D25] Set 集合去重与交并差
来源：http://dali.snrcjt.cn/Article/details/gtzigtrsgp.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.haohaochexian.top/Article/details/gtthsudozd.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yvedp.cn/Article/details/gtcstqdgof.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.iojbl.cn/Article/details/gtkurphngm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhengqikj.top/Article/details/gtfpqpaidd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yuanzhike.top/Article/details/gtkjnqsazj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jqgufenzy.top/Article/details/gtyoykbucy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.fzhhl.top/Article/details/gtmmxcfdtc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cashguo.top/Article/details/gtdufrysht.html

[D26] 数组转字符串
来源：http://dali.nanxinkj.top/Article/details/gthwynadde.html

Py:   ", ".join(map(str, arr))
来源：http://dali.wangdashe.top/Article/details/gttcvpkund.html

PHP:  implode(", ", $arr);
来源：http://dali.yj20258888.top/Article/details/gtawuyxeci.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gtfrvjfqoy.html

TS:   arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gtuaenraiw.html

Java: String.join(", ", list)
来源：http://dali.bjfxy.top/Article/details/gtwdbzdfkp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cucudq.cn/Article/details/gtifnybjrd.html

Ruby: arr.join(", ")
来源：http://dali.aizwys.cn/Article/details/gtgeafskft.html

C#:   string.Join(", ", list)
来源：http://dali.hnxiangtu.top/Article/details/gthksmxwod.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtvxrdkcyv.html

E. 字符串处理
来源：http://dali.ybcxt.top/Article/details/gtnkboorjh.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtbtvtroiy.html

[E01] 拼接字符串
来源：http://dali.zhoulong.xyz/Article/details/gtuledarve.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmfpmewfu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jianghu66.top/Article/details/gttnfxfgor.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ivvv.top/Article/details/gtxhmoiefj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xinyue.icu/Article/details/gtxvwwwkrb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.feifeiyinyue.top/Article/details/gtlpcbyxwq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.feifeiyinyue.top/Article/details/gtenbzrmgn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinghuilouyu.cn/Article/details/gtukrmcwws.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtslwhfvbi.html

[E02] 重复字符串
来源：http://dali.jqgufenzy.top/Article/details/gtiyqnseea.html

Py:   "ab" * 3
来源：http://dali.ydzc1.top/Article/details/gtgqahhhjc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hysaishi.cn/Article/details/gttlpjjsxv.html

JS:   "ab".repeat(3)
来源：http://dali.cheryme.top/Article/details/gttbslsbin.html

TS:   "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gtjbgnthem.html

Java: "ab".repeat(3)
来源：http://dali.vqdsnc.cn/Article/details/gtezejcpml.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.nanxuanxn.top/Article/details/gtbdpfhtzl.html

Ruby: "ab" * 3
来源：http://dali.shzxlz.cn/Article/details/gtwlvpsjll.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.quarkkingdee.top/Article/details/gtqiptxznx.html

[E03] 截取子串
来源：http://dali.ppjwa.cn/Article/details/gtibffuqls.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hnqzz.top/Article/details/gteyrowalg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.316326.xyz/Article/details/gtputsrkfe.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cqqwz.cn/Article/details/gtryfnxyra.html

TS:   s.slice(1, 4)
来源：http://dali.zhengqikj.top/Article/details/gttnfipezd.html

Java: s.substring(1, 4)
来源：http://dali.yj202588.top/Article/details/gtakjxvtlx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenlongwang.top/Article/details/gtqohzemfv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yvedp.cn/Article/details/gtgyqraedm.html

C#:   s.Substring(1, 3)
来源：http://dali.hongshengwenyu.top/Article/details/gtjzabdgah.html

[E04] 查找子串位置
来源：http://dali.daria6918.cn/Article/details/gtsppzsdou.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yongpay.top/Article/details/gtchhokghy.html

PHP:  strpos($s, "x");
来源：http://dali.dashuyun.cn/Article/details/gthytwboaz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yj20258888.top/Article/details/gtkkoncuip.html

TS:   s.indexOf("x")
来源：http://dali.xinyue.icu/Article/details/gttwiehmub.html

Java: s.indexOf("x")
来源：http://dali.sysykeji.top/Article/details/gtqrfvlzwe.html

Go:   strings.Index(s, "x")
来源：http://dali.jqgufenzy.top/Article/details/gtbbyqgwpm.html

Ruby: s.index("x")
来源：http://dali.xylfe.cn/Article/details/gtddyqguwa.html

C#:   s.IndexOf("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gtyhjmersj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yonumen.top/Article/details/gthhvixgbc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhongyouzk.top/Article/details/gtyjjdybou.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinqigufen.top/Article/details/gtdvsmgnle.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.c1oappe.top/Article/details/gtmmiltjaq.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhixingplan.top/Article/details/gtjxasromp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hysaishi.cn/Article/details/gtygnyfusd.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.snrcjt.cn/Article/details/gtxtkhctki.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hywenlv.cn/Article/details/gtguisbmxz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jinqigufen.top/Article/details/gtxwthyifg.html

[E06] 替换子串
来源：http://dali.jinqigfzy.top/Article/details/gtbkmmffiz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nwbrower.top/Article/details/gtzjnqdyln.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtplvfqips.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtmjoejtnh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtebtsdsnl.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtbxxhtegv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gogol.net.cn/Article/details/gtjycobhcl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gtysetkgca.html

C#:   s.Replace("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gtnpqatbeo.html

[E07] 按分隔符拆分
来源：http://dali.daria6918.cn/Article/details/gtwghxspdn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.andypj.xyz/Article/details/gtfxsqzrpp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jqgfzy.top/Article/details/gtbzuoqhwz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.9152youxi.cn/Article/details/gtkzdxkpqz.html

TS:   s.split(",")
来源：http://dali.ehwqpu.com/Article/details/gtvazythuq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shangyingyoupin.top/Article/details/gtcbxlngwn.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ppjwa.cn/Article/details/gtigrgblxp.html

Ruby: s.split(",");  s.split
来源：http://dali.cheryme.top/Article/details/gtvthldojn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yvedp.cn/Article/details/gtmuptezcc.html

[E08] 数组按分隔符合并
来源：http://dali.xziqi.cn/Article/details/gtzetwhzun.html

Py:   ",".join(items)
来源：http://dali.hfpthk.cn/Article/details/gtgwxdjysm.html

PHP:  implode(",", $items);
来源：http://dali.redwolf501.top/Article/details/gthvjqucuh.html

JS:   items.join(",")
来源：http://dali.smart0.xyz/Article/details/gtaqosttxp.html

TS:   items.join(",")
来源：http://dali.yueranfly.top/Article/details/gtifpwukkn.html

Java: String.join(",", items)
来源：http://dali.gogol.net.cn/Article/details/gtdplhrqky.html

Go:   strings.Join(items, ",")
来源：http://dali.zhiwuduotai.top/Article/details/gtitytkuaz.html

Ruby: items.join(",")
来源：http://dali.smart0.xyz/Article/details/gthdcmcide.html

C#:   string.Join(",", items)
来源：http://dali.gogol.net.cn/Article/details/gtacuanfbx.html

[E09] 去除所有空白字符
来源：http://dali.zhixingplan.top/Article/details/gteufzbpyw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hfpthk.cn/Article/details/gtdgpmrzrs.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtgxlcxksa.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sufxvd.cn/Article/details/gtuehiwbop.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gotoacloud.top/Article/details/gtieyaiyux.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gaohongyu789.top/Article/details/gtjkivvzge.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.pycfn.com/Article/details/gtyqwwjpce.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.tanke756.top/Article/details/gtkdjabxpy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.dianchejie.cn/Article/details/gtkyvnnuku.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zycfv.cn/Article/details/gtjnqxliou.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gtnmmzwaty.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.mhx1999.top/Article/details/gtpastbiov.html

JS:   "7".padStart(3, "0")
来源：http://dali.gogol.net.cn/Article/details/gthpbdcmav.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gtvzulrxbs.html

Java: String.format("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gtoewlfmmg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gttwrwyycj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.smart0.xyz/Article/details/gtaiiybeua.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj202588.top/Article/details/gtvqbdvwws.html

[E11] 反转字符串
来源：http://dali.snrcjt.cn/Article/details/gtndplbqei.html

Py:   s[::-1]
来源：http://dali.xuanzx.com/Article/details/gtfzdbdypj.html

PHP:  strrev($s);
来源：http://dali.jqgfzy.top/Article/details/gtqxmulmrw.html

JS:   [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gtackbiutl.html

TS:   [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gtekxhphgn.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.feifeiyinyue.top/Article/details/gtbltynmiw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yvedp.cn/Article/details/gtyntrbspw.html

Ruby: s.reverse
来源：http://dali.bjfxy.top/Article/details/gtyghibfhx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gzhubu.top/Article/details/gtzrrhvlas.html

[E12] 统计某字符出现次数
来源：http://dali.ehwqpu.com/Article/details/gtrgtkjoja.html

Py:   s.count("a")
来源：http://dali.aibaodan.cn/Article/details/gtfmfkydah.html

PHP:  substr_count($s, "a");
来源：http://dali.bjfxy.top/Article/details/gtdjiqtthr.html

JS:   s.split("a").length - 1
来源：http://dali.snrcjt.cn/Article/details/gtujiyodsy.html

TS:   s.split("a").length - 1
来源：http://dali.hongshengwenyu.top/Article/details/gtfwbouqnx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqnpuhbp.html

Go:   strings.Count(s, "a")
来源：http://dali.ppjwa.cn/Article/details/gtyqhihdfl.html

Ruby: s.count("a")
来源：http://dali.xuanzx.com/Article/details/gtvnyzmmnu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.fengsongda.top/Article/details/gtdljpqivz.html

[E13] 逐字符遍历
来源：http://dali.guowangkeji.top/Article/details/gtdfgpabkn.html

Py:   for ch in s: print(ch)
来源：http://dali.ydzc1.top/Article/details/gtqumqsjzz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj20258888.top/Article/details/gtdnlgijim.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cheryme.top/Article/details/gttlztywnb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fengsongda.top/Article/details/gtriknkybj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.daxiang520.top/Article/details/gtlqlkvdxy.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cdnleiting.top/Article/details/gtcjglenhq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jqgfzy.top/Article/details/gtlggwtmop.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gtzqqmirmn.html

[E14] URL 编码与 Base64
来源：http://dali.vqdsnc.cn/Article/details/gtsrtgtxrt.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shanyushiyangtech.top/Article/details/gtuxbtmojf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.meibo888.top/Article/details/gtfrnmzieo.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ydzc1.top/Article/details/gtkaodxhgt.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.dianchejie.cn/Article/details/gtyxcahqyc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gzhubu.top/Article/details/gtznvtuxgr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gotoacloud.top/Article/details/gtfcttubjr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj202588.top/Article/details/gtbdjuzfxv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.daxiang520.top/Article/details/gtaruvbcsp.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxuanxn.top/Article/details/gtcxijetnc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.havefunace.top/Article/details/gtdsgrujcn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthotqithl.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zycfv.cn/Article/details/gtvvfsnlpn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yvedp.cn/Article/details/gtbjhbtzgf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zdqjudy.top/Article/details/gtuezmncgz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yuxming.cn/Article/details/gtmclexddo.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtbqvyfqrw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hammf.cn/Article/details/gtbtjortqj.html

[E16] 数字千分位
来源：http://dali.gotoacloud.top/Article/details/gtxnepufic.html

Py:   f"{1234567:,}"
来源：http://dali.ivvv.top/Article/details/gtydxvxtlu.html

PHP:  number_format(1234567);
来源：http://dali.nanxinkj.top/Article/details/gtzfngldbs.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hammf.cn/Article/details/gteenrozuj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgufenzy.top/Article/details/gtwpczcuuq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.daxiang520.top/Article/details/gtcwsdycby.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.aibaodan.cn/Article/details/gtthqcobvl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.0kj1m.cn/Article/details/gtdazrajtc.html

C#:   1234567.ToString("N0")
来源：http://dali.dianchejie.cn/Article/details/gtnxlrsesr.html

[E17] 首字母大写
来源：http://dali.c1oappe.top/Article/details/gtzppnjuyh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.dashuyun.cn/Article/details/gtfezpivph.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpitdwyjl.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jlsjyb.cn/Article/details/gtlpsgikqc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jyoumei.cn/Article/details/gtkjttrosl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinqigufen.top/Article/details/gtgdlmbtua.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yonumen.top/Article/details/gtoiztujdf.html

Ruby: s.capitalize
来源：http://dali.yj20258.top/Article/details/gthbbnxegg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlciyhvhs.html

[E18] 模板占位符替换
来源：http://dali.ybcxt.top/Article/details/gtwnfpgigi.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ppjwa.cn/Article/details/gtgfccmuif.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.nanxinkj.top/Article/details/gtvisygext.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gtunesdbaa.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gtualhwjos.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gtqnexnsrd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtbkzicrzn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.fengsongda.top/Article/details/gtrnirfwri.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yanxiufei.cn/Article/details/gteiszmhsp.html

[E19] 多行文本按行拆分
来源：http://dali.iojbl.cn/Article/details/gtqiweqchn.html

Py:   s.splitlines()
来源：http://dali.cheryme.top/Article/details/gtyhcfqnxg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtnzcbmyhl.html

JS:   s.split(/\r?\n/)
来源：http://dali.daria6918.cn/Article/details/gtuqyvcgbh.html

TS:   s.split(/\r?\n/)
来源：http://dali.yonumen.top/Article/details/gtwacoxunj.html

Java: s.lines().toList()
来源：http://dali.svipenyu.cn/Article/details/gtvxgtnydy.html

Go:   strings.Split(s, "\n")
来源：http://dali.sufxvd.cn/Article/details/gtvnmxlnpc.html

Ruby: s.lines
来源：http://dali.jqgfzy.top/Article/details/gtzjjnqxsk.html

C#:   s.Split('\n')
来源：http://dali.zhoulong.xyz/Article/details/gtuxjzbrgy.html

[E20] 判断字符串是否为空
来源：http://dali.gotoacloud.top/Article/details/gtbqfzgwky.html

Py:   if not s:
来源：http://dali.redwolf501.top/Article/details/gtsjfbucgy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhongyouzk.top/Article/details/gtunpokmrl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenzaomai.com/Article/details/gtqvkedsja.html

TS:   if (s === "") {}
来源：http://dali.cdnleiting.top/Article/details/gtxjwnzzaw.html

Java: if (s.isEmpty()) {}
来源：http://dali.tian-w.cn/Article/details/gtpetibcho.html

Go:   if s == "" {}
来源：http://dali.cashguo.top/Article/details/gtyyxxopoo.html

Ruby: if s.empty?
来源：http://dali.yueranfly.top/Article/details/gtmfiwrrkn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yonumen.top/Article/details/gtlptduung.html

[E21] 超长截断加省略号
来源：http://dali.xuanzx.com/Article/details/gtsbdyhbfg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cdnleiting.top/Article/details/gtlzxenuac.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gttnwqzcpw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtgvdvpwav.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gttabzxocl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtrvfeuiiw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.daxiang520.top/Article/details/gtmpzshyad.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtcepwsumd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gtuuahakyn.html

[E22] 字节长度与字符长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtkihcibjj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ivvv.top/Article/details/gtyfdkwtlw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gtohsjjtgj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ppjwa.cn/Article/details/gtqvsjkhca.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daxiang520.top/Article/details/gtxvsstzis.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ppjwa.cn/Article/details/gtefxdzbbj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.pycfn.com/Article/details/gtggjjcezv.html

Ruby: s.bytesize;  s.length
来源：http://dali.bjfxy.top/Article/details/gtikfqtwtn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.wangdashe.top/Article/details/gtiroiqccl.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtarfajbbd.html

F. 文件与目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmiwzoffd.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtajzccpbp.html

[F01] 读取整个文件
来源：http://dali.zhixingplan.top/Article/details/gtpxeqnkyk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hongshengwenyu.top/Article/details/gtcpypmxuz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.pycfn.com/Article/details/gttbcwodqr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xuanzx.com/Article/details/gtowbojkmb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yj20258.top/Article/details/gtudvumfea.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gtlaohopmp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jlsjyb.cn/Article/details/gtaumkyjpw.html

Ruby: File.read("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtwzhwukrb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtfzlktxnv.html

[F02] 逐行读取文件
来源：http://dali.xuanzx.com/Article/details/gtbbxvzuyy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhixingplan.top/Article/details/gtmjrhtkbc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj20258888.top/Article/details/gtpptwbxrj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.kuanghao11.cn/Article/details/gtnkjsmrny.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sxryk.cn/Article/details/gtolhybwqv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.iojbl.cn/Article/details/gtwrfxajmm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yangfankeji.com/Article/details/gtaxrpmtuf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jiagoushi.top/Article/details/gticwrdgpo.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthvdkbkjz.html

[F03] 写入文件（覆盖）
来源：http://dali.xinyue.icu/Article/details/gtfdsqwyjm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.chenlongwang.top/Article/details/gtddifvtix.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.mhx1999.top/Article/details/gtkgqmnisx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gtboypmsjv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sysykeji.top/Article/details/gtcvqmxngv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shuidangran.top/Article/details/gtfwpprooq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jianghu66.top/Article/details/gthhosuzci.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.mhx1999.top/Article/details/gtogetlfyq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cashguo.top/Article/details/gtkjfyouhn.html

[F04] 追加写入文件
来源：http://dali.zhengqikj.top/Article/details/gtfiwietij.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yueranfly.top/Article/details/gtllufxzxo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yongpay.top/Article/details/gtuanzxnet.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtxwapzwqb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.smart0.xyz/Article/details/gtspmjcdct.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.iojbl.cn/Article/details/gtztjioaqq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.nanxuanxn.top/Article/details/gtqolocfwb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtitmmvicl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xylfe.cn/Article/details/gtcthvpgyw.html

[F05] 判断文件或目录是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtovbkuwnm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcfkzcicw.html

PHP:  file_exists("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtwcahuqxp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gthdvmltub.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtmbwkfifh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gtgyffonix.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jqgfzy.top/Article/details/gtgfspycul.html

Ruby: File.exist?("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtivuyrran.html

C#:   File.Exists("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtovljeers.html

[F06] 删除文件
来源：http://dali.hnqzz.top/Article/details/gtnathptxj.html

Py:   os.remove("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtpmlkaffk.html

PHP:  unlink("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtbfjniutm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtttywdsvg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtipfbwqxf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gtfcuukgzw.html

Go:   os.Remove("a.txt")
来源：http://dali.yj20258.top/Article/details/gtfvnvnget.html

Ruby: File.delete("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtystqhwcu.html

C#:   File.Delete("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtasonmaeg.html

[F07] 创建目录（含多级）
来源：http://dali.vqdsnc.cn/Article/details/gtfhemiwef.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yanxiufei.cn/Article/details/gtfkytzfwg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj20258.top/Article/details/gtrgoglcjo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuanzhike.top/Article/details/gtutzouxhn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.snrcjt.cn/Article/details/gtzbcyovor.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpsngdulw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jqgufenzy.top/Article/details/gtsfqagwqf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yvedp.cn/Article/details/gtnmegchrc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yj20258888.top/Article/details/gtudizfcto.html

[F08] 遍历目录
来源：http://dali.zhengqikj.top/Article/details/gtjnjynomq.html


<!-- 参考信息 -->