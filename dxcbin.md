代发 wailian999

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtbbdkczaw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cheryme.top/Article/details/gtwzphkryp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tanke756.top/Article/details/gtovnrrsqw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yvedp.cn/Article/details/gtuojiyzmv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.mhx1999.top/Article/details/gtrqksqqpb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yangfankeji.com/Article/details/gtczfrjpzn.html

[D25] Set 集合去重与交并差
来源：http://dali.aizwys.cn/Article/details/gtiuiqlhxl.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.316326.xyz/Article/details/gtrsgnuvdi.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.mhx1999.top/Article/details/gtbkczfurp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.kuanghao11.cn/Article/details/gtooamelxi.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jlsjyb.cn/Article/details/gtdrlifsij.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sxryk.cn/Article/details/gtrqnypqhc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yanxiufei.cn/Article/details/gtzxrlcrdw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinqigfzy.top/Article/details/gtkgkhjnmm.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcxybcyzx.html

[D26] 数组转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvozvbvoj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.fengsongda.top/Article/details/gtwewdbsil.html

PHP:  implode(", ", $arr);
来源：http://dali.gotoacloud.top/Article/details/gtzasvprkh.html

JS:   arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gtypjpnzuy.html

TS:   arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gtgvdfdzsk.html

Java: String.join(", ", list)
来源：http://dali.zycfv.cn/Article/details/gtvohopqmy.html

Go:   strings.Join(strs, ", ")
来源：http://dali.iojbl.cn/Article/details/gtubtzzdjh.html

Ruby: arr.join(", ")
来源：http://dali.zhoulong.xyz/Article/details/gtyujiible.html

C#:   string.Join(", ", list)
来源：http://dali.cqqwz.cn/Article/details/gtypwclzvc.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtbkumhcxz.html

E. 字符串处理
来源：http://dali.hysaishi.cn/Article/details/gthnanobpm.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtbnurkyjo.html

[E01] 拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuwducbgx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xuanzx.com/Article/details/gtjnmlmswo.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hnxiangtu.top/Article/details/gtpnylqopx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cqqwz.cn/Article/details/gtqafznfpu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxinkj.top/Article/details/gttiacdyrt.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yueranfly.top/Article/details/gtnnhllpts.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sufxvd.cn/Article/details/gtoycoxakj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hnxiangtu.top/Article/details/gtxahgmjol.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ybcxt.top/Article/details/gthzhpwnml.html

[E02] 重复字符串
来源：http://dali.sysykeji.top/Article/details/gtxwsnqaxm.html

Py:   "ab" * 3
来源：http://dali.zhongyouzk.top/Article/details/gtptfjllry.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenzaomai.com/Article/details/gtlonozosn.html

JS:   "ab".repeat(3)
来源：http://dali.hnxiangtu.top/Article/details/gttmooxlvf.html

TS:   "ab".repeat(3)
来源：http://dali.316326.xyz/Article/details/gtcuwdvugo.html

Java: "ab".repeat(3)
来源：http://dali.c1oappe.top/Article/details/gtwdcywsds.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.guannengcc.top/Article/details/gtsbpifywd.html

Ruby: "ab" * 3
来源：http://dali.gaohongyu789.top/Article/details/gtmfhclxfj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.kuanghao11.cn/Article/details/gtzkakbzqd.html

[E03] 截取子串
来源：http://dali.chenzaomai.com/Article/details/gtpidtyczq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zycfv.cn/Article/details/gtmzbsnrvu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gtrvhxksbt.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jyoumei.cn/Article/details/gtotcjeiqn.html

TS:   s.slice(1, 4)
来源：http://dali.andypj.xyz/Article/details/gtizopmnij.html

Java: s.substring(1, 4)
来源：http://dali.yuxming.cn/Article/details/gtpdlzkgil.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hnxiangtu.top/Article/details/gtpdmvtflt.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.nanxinkj.top/Article/details/gtvxmhjhqm.html

C#:   s.Substring(1, 3)
来源：http://dali.yvedp.cn/Article/details/gtbcsbffog.html

[E04] 查找子串位置
来源：http://dali.dianchejie.cn/Article/details/gtcqsnowbg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hammf.cn/Article/details/gtvaqwhaqt.html

PHP:  strpos($s, "x");
来源：http://dali.jqgufenzy.top/Article/details/gtxjzlbciv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.aibaodan.cn/Article/details/gtoexpncrd.html

TS:   s.indexOf("x")
来源：http://dali.andypj.xyz/Article/details/gtjwnpgvqw.html

Java: s.indexOf("x")
来源：http://dali.svipenyu.cn/Article/details/gtioijfghp.html

Go:   strings.Index(s, "x")
来源：http://dali.jqgfzy.top/Article/details/gtwudekbib.html

Ruby: s.index("x")
来源：http://dali.shangyingyoupin.top/Article/details/gtcabxlclc.html

C#:   s.IndexOf("x")
来源：http://dali.tian-w.cn/Article/details/gtyhhadxhz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.vqdsnc.cn/Article/details/gtmmzetjmf.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj20258.top/Article/details/gtnjlalnjk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.haohaochexian.top/Article/details/gtabeufnfx.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yanxiufei.cn/Article/details/gtymwxgwuh.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hfpthk.cn/Article/details/gtnegicjho.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gzhubu.top/Article/details/gtjnolkaqt.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.snrcjt.cn/Article/details/gtkprdreps.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ppjwa.cn/Article/details/gtuqxnqney.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hongshengwenyu.top/Article/details/gtrqslgydp.html

[E06] 替换子串
来源：http://dali.xylfe.cn/Article/details/gtipnhyxhp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.tianlin.xyz/Article/details/gtxnteivtl.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tanke756.top/Article/details/gtciyrxaky.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gtkgysmqow.html

TS:   s.replaceAll("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtfnwybjkg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtqdppvjhb.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.aizwys.cn/Article/details/gtvgtqwfed.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hnqzz.top/Article/details/gtlrbutyqg.html

C#:   s.Replace("a", "b")
来源：http://dali.hammf.cn/Article/details/gtivrgjrxj.html

[E07] 按分隔符拆分
来源：http://dali.cashguo.top/Article/details/gtlfvllkwm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinqigfzy.top/Article/details/gtsloggtsg.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xinyue.icu/Article/details/gtusgljhjb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.chenjidiqi.icu/Article/details/gtesbfmfrg.html

TS:   s.split(",")
来源：http://dali.pengpengdd.cyou/Article/details/gtpjwmvvac.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.0kj1m.cn/Article/details/gtjjgmassf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtvqfnnmjd.html

Ruby: s.split(",");  s.split
来源：http://dali.tianlin.xyz/Article/details/gtoxcxrvde.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yangfankeji.com/Article/details/gtmelmgmqj.html

[E08] 数组按分隔符合并
来源：http://dali.hongshengwenyu.top/Article/details/gtzhacxeje.html

Py:   ",".join(items)
来源：http://dali.daria6918.cn/Article/details/gtjmlfgflx.html

PHP:  implode(",", $items);
来源：http://dali.zycfv.cn/Article/details/gtuxvhsmok.html

JS:   items.join(",")
来源：http://dali.jianghu66.top/Article/details/gtrmwwrlhn.html

TS:   items.join(",")
来源：http://dali.xinyue.icu/Article/details/gtlsrhcqyc.html

Java: String.join(",", items)
来源：http://dali.guannengcc.top/Article/details/gtuvkjsyrg.html

Go:   strings.Join(items, ",")
来源：http://dali.chenjidiqi.icu/Article/details/gtqdnozugj.html

Ruby: items.join(",")
来源：http://dali.ybcxt.top/Article/details/gtziwcvyfn.html

C#:   string.Join(",", items)
来源：http://dali.fzhhl.top/Article/details/gtqnknudit.html

[E09] 去除所有空白字符
来源：http://dali.shanyushiyangkeji.top/Article/details/gtesowxsyx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.316326.xyz/Article/details/gtywzmwtqy.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yongpay.top/Article/details/gtpvqujupd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.9152youxi.cn/Article/details/gtryxpsfjo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.birdmap.top/Article/details/gtjrivuakr.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgezbveur.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sysykeji.top/Article/details/gtszblmekc.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.mhx1999.top/Article/details/gtouqvqtyd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yuxming.cn/Article/details/gtoqzoccea.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ehwqpu.com/Article/details/gtgcjbcood.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gthsyeemzs.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhongyouzk.top/Article/details/gtdfbbehvp.html

JS:   "7".padStart(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gtpmqreqlq.html

TS:   "7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gtpxcgznyr.html

Java: String.format("%03d", 7)
来源：http://dali.smart0.xyz/Article/details/gtlvqleaxf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gtznwzqzdi.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gthreysigr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sufxvd.cn/Article/details/gtvdxjjqhh.html

[E11] 反转字符串
来源：http://dali.gzhubu.top/Article/details/gtabcxefwa.html

Py:   s[::-1]
来源：http://dali.zdqjudy.top/Article/details/gteeyvvtan.html

PHP:  strrev($s);
来源：http://dali.yj20258888.top/Article/details/gtyonadcxr.html

JS:   [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gtszmflbav.html

TS:   [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gtnyvhrvzn.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shangyingyoupin.top/Article/details/gtomifiaml.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hnxiangtu.top/Article/details/gtzprvnkph.html

Ruby: s.reverse
来源：http://dali.fengsongda.top/Article/details/gtbnaaowas.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jyoumei.cn/Article/details/gtboipsora.html

[E12] 统计某字符出现次数
来源：http://dali.chenlongwang.top/Article/details/gtlqnpzeyn.html

Py:   s.count("a")
来源：http://dali.zycfv.cn/Article/details/gtodswtpfn.html

PHP:  substr_count($s, "a");
来源：http://dali.jinqigufen.top/Article/details/gtcelkpafr.html

JS:   s.split("a").length - 1
来源：http://dali.dashuyun.cn/Article/details/gtnclmambg.html

TS:   s.split("a").length - 1
来源：http://dali.iojbl.cn/Article/details/gtmzzfzdbr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.guannengcc.top/Article/details/gtngsomazx.html

Go:   strings.Count(s, "a")
来源：http://dali.andypj.xyz/Article/details/gtmgmtuumx.html

Ruby: s.count("a")
来源：http://dali.ehwqpu.com/Article/details/gtrqhettck.html

C#:   s.Count(c => c == 'a')
来源：http://dali.wangdashe.top/Article/details/gtwpudqsuj.html

[E13] 逐字符遍历
来源：http://dali.chenzaomai.com/Article/details/gtkirzardi.html

Py:   for ch in s: print(ch)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttaplwukq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jyoumei.cn/Article/details/gtmcevjbeo.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gtbaoijmgz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aizwys.cn/Article/details/gtlmdswjqw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yj202588.top/Article/details/gtynczlulf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ppjwa.cn/Article/details/gtlmjzojwi.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.tianlin.xyz/Article/details/gtxyvecssm.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gogol.net.cn/Article/details/gtlqangsyi.html

[E14] URL 编码与 Base64
来源：http://dali.yongpay.top/Article/details/gtuuapdbhy.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jianghu66.top/Article/details/gtqghglpyy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xuetiantiany.cn/Article/details/gthchkjzfz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.0kj1m.cn/Article/details/gtzjtgyfte.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gtwudodavv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqvtiybmx.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.pycfn.com/Article/details/gtfjrgibwh.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cucudq.cn/Article/details/gtdfwzudeo.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.0kj1m.cn/Article/details/gtkcnujpdm.html

[E15] HTML 转义 / 反转义
来源：http://dali.sufxvd.cn/Article/details/gtjvdhodfi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ydzc1.top/Article/details/gtacpjkeez.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hfpthk.cn/Article/details/gtzctrtypx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.iojbl.cn/Article/details/gtrfnqbgzu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.nanxinkj.top/Article/details/gtnalzzzkh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.redwolf501.top/Article/details/gtqatxzljg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.nanxinkj.top/Article/details/gtqfixxksq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.redwolf501.top/Article/details/gtrhtrycfp.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.redwolf501.top/Article/details/gtedldjhda.html

[E16] 数字千分位
来源：http://dali.aibaodan.cn/Article/details/gtfhuzhhts.html

Py:   f"{1234567:,}"
来源：http://dali.pengpengdd.cyou/Article/details/gtbkzymqlw.html

PHP:  number_format(1234567);
来源：http://dali.andypj.xyz/Article/details/gttzfmvxbj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.fzhhl.top/Article/details/gtjwdnyniw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkyjncvsu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.fzhhl.top/Article/details/gtmmnqolna.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yonumen.top/Article/details/gtlbaxlbni.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhiwuduotai.top/Article/details/gtdudwlwaa.html

C#:   1234567.ToString("N0")
来源：http://dali.xylfe.cn/Article/details/gtusiheura.html

[E17] 首字母大写
来源：http://dali.mhx1999.top/Article/details/gthawfdrin.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ydzc1.top/Article/details/gtqswoiiks.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.tianlin.xyz/Article/details/gtfzaehwik.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.haohaochexian.top/Article/details/gtelamejel.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yvedp.cn/Article/details/gtcrxlcjho.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.svipenyu.cn/Article/details/gteexxuhli.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.haohaochexian.top/Article/details/gtmiiafbcl.html

Ruby: s.capitalize
来源：http://dali.hnqzz.top/Article/details/gteidqehnt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhengqikj.top/Article/details/gtfhdyrwer.html

[E18] 模板占位符替换
来源：http://dali.xuetiantiany.cn/Article/details/gtfidlvsoi.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jiagoushi.top/Article/details/gtbiqigftp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xinyue.icu/Article/details/gtreboatyb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkcxbcwgd.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ydzc1.top/Article/details/gtkcloagqu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gturfiparg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gttbsylfmy.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shzxlz.cn/Article/details/gtzqmwcpto.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xylfe.cn/Article/details/gtlcyumnzs.html

[E19] 多行文本按行拆分
来源：http://dali.c1oappe.top/Article/details/gtjjekxzkn.html

Py:   s.splitlines()
来源：http://dali.yuanzhike.top/Article/details/gtucmfsgao.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yj202588.top/Article/details/gtdbmdcfjm.html

JS:   s.split(/\r?\n/)
来源：http://dali.xuetiantiany.cn/Article/details/gtmbvfichb.html

TS:   s.split(/\r?\n/)
来源：http://dali.quarkkingdee.top/Article/details/gtqxxnhyhg.html

Java: s.lines().toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtirztqjbh.html

Go:   strings.Split(s, "\n")
来源：http://dali.birdmap.top/Article/details/gtkcpfiqfy.html

Ruby: s.lines
来源：http://dali.dianchejie.cn/Article/details/gtibrecaps.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gtkbbdipai.html

[E20] 判断字符串是否为空
来源：http://dali.yj202588.top/Article/details/gtjhiqujce.html

Py:   if not s:
来源：http://dali.nwbrower.top/Article/details/gthfspglea.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jyoumei.cn/Article/details/gteqhilume.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ivvv.top/Article/details/gtdffecumi.html

TS:   if (s === "") {}
来源：http://dali.xylfe.cn/Article/details/gtfivxcquv.html

Java: if (s.isEmpty()) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtohppjvxa.html

Go:   if s == "" {}
来源：http://dali.c1oappe.top/Article/details/gtvaeeqfsx.html

Ruby: if s.empty?
来源：http://dali.vqdsnc.cn/Article/details/gtsxxioris.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.mhx1999.top/Article/details/gtcxbnlsxq.html

[E21] 超长截断加省略号
来源：http://dali.cdnleiting.top/Article/details/gtgwyzqqry.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.havefunace.top/Article/details/gtfukyggof.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gtzjqqxzbs.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.havefunace.top/Article/details/gtjjhltoxl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sweek.top/Article/details/gteoltylmb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gthxhuxfzs.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.chenzaomai.com/Article/details/gtiqkzvmtt.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtvxxzdhkl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gtifjidrak.html

[E22] 字节长度与字符长度
来源：http://dali.jqgufenzy.top/Article/details/gtshjrniqy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jqgfzy.top/Article/details/gtqsbbmhqn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gtmoiztldg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigufen.top/Article/details/gtzpolblgh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gthtgbjbig.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ivvv.top/Article/details/gtldkhphaf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.haohaochexian.top/Article/details/gtzclvijlr.html

Ruby: s.bytesize;  s.length
来源：http://dali.guowangkeji.top/Article/details/gtvqhlqgic.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cashguo.top/Article/details/gtvqszggfa.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtumwskfzt.html

F. 文件与目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttssimxpv.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtfqjpkmjt.html

[F01] 读取整个文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbrxhcujg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gogol.net.cn/Article/details/gtvzcpyqdb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtyrbhouue.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ybcxt.top/Article/details/gtftbnhhum.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xylfe.cn/Article/details/gtvzoajefl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gtishddvgy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.vqdsnc.cn/Article/details/gtfyxususg.html

Ruby: File.read("a.txt")
来源：http://dali.meibo888.top/Article/details/gtdzjbhqyd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtolkxmwxz.html

[F02] 逐行读取文件
来源：http://dali.cucudq.cn/Article/details/gtdabifyxk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.daxiang520.top/Article/details/gtsygpovfg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj202588.top/Article/details/gtykaxjlam.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yangfankeji.com/Article/details/gtvujhwqrm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenlongwang.top/Article/details/gttxwyepon.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.meibo888.top/Article/details/gtthsiazji.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jqgufenzy.top/Article/details/gtgpkimllm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqtplcvdq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhixingplan.top/Article/details/gthzzpqjjr.html

[F03] 写入文件（覆盖）
来源：http://dali.birdmap.top/Article/details/gtnzmvvyxp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbabllqfn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yj20258888.top/Article/details/gtzbpljzth.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sysykeji.top/Article/details/gtczoadsri.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gteruzwtog.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxnxdltmv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hfpthk.cn/Article/details/gtlhcetcmf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.9152youxi.cn/Article/details/gtemxhsbdb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cucudq.cn/Article/details/gtmhzqefen.html

[F04] 追加写入文件
来源：http://dali.xinyue.icu/Article/details/gtvlcpgrsx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.snrcjt.cn/Article/details/gtlhrprfaf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yanxiufei.cn/Article/details/gtugzerwoh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cqqwz.cn/Article/details/gtrpouefrm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtartweojl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shuidangran.top/Article/details/gthubhplkz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtargsiehf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.quarkkingdee.top/Article/details/gtnhvnzmym.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zdqjudy.top/Article/details/gtttuhlzxj.html

[F05] 判断文件或目录是否存在
来源：http://dali.nwbrower.top/Article/details/gthjylifsp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xinyue.icu/Article/details/gtostautup.html

PHP:  file_exists("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtlqoimybn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtlwwhcwje.html

TS:   fs.existsSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtwghokzts.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gtpbkpajnh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yonumen.top/Article/details/gtsfyhegws.html

Ruby: File.exist?("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtlkvynens.html

C#:   File.Exists("a.txt")
来源：http://dali.316326.xyz/Article/details/gtzykvsira.html

[F06] 删除文件
来源：http://dali.ydzc1.top/Article/details/gtyieswqof.html

Py:   os.remove("a.txt")
来源：http://dali.tanke756.top/Article/details/gtlaecvucq.html

PHP:  unlink("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtnlasnwpo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtztyojyug.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtpsvzjjfi.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtghopimpf.html

Go:   os.Remove("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtgbijuddh.html

Ruby: File.delete("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtjrukekwj.html

C#:   File.Delete("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtawoptywk.html

[F07] 创建目录（含多级）
来源：http://dali.yuxming.cn/Article/details/gtlemeiixc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hywenlv.cn/Article/details/gtzdiaepxx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.fzhhl.top/Article/details/gtywbuoxse.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.andypj.xyz/Article/details/gtmpqxwbsr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hongshengwenyu.top/Article/details/gtgyjzjfum.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.haohaochexian.top/Article/details/gtomcfeaez.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yangfankeji.com/Article/details/gtprndqryj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yongpay.top/Article/details/gtsycljigu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.havefunace.top/Article/details/gtnxpdchzv.html

[F08] 遍历目录
来源：http://dali.xziqi.cn/Article/details/gttxgehbgo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.daxiang520.top/Article/details/gtshcejgtr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.wangdashe.top/Article/details/gtffqivmim.html

JS:   fs.readdirSync("dir")
来源：http://dali.chenlongwang.top/Article/details/gtsougbrrw.html

TS:   fs.readdirSync("dir")
来源：http://dali.yj20258.top/Article/details/gtbovczhat.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.aizwys.cn/Article/details/gthnpljyhi.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.daria6918.cn/Article/details/gtehtokcfs.html

Ruby: Dir.children("dir")
来源：http://dali.dashuyun.cn/Article/details/gtbgbqzssb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhixingplan.top/Article/details/gtfzpsizfh.html


<!-- 参考信息 -->