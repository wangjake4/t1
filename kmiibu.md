代发 wailian999

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2gucofjst.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwfboaa.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2lsufirhm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrwfpmx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2emuywaun.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gptsuldz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2randkqql.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgjcboe.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2udjjgilp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzpgqyy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2idzlufui.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tairztvj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2uyksragd.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xonaoaes.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzidxeh.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ukhxwdxa.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwyoxxig.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2abyxlenu.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzawqay.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgenxwrg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxnuvnz.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrvhsso.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zugbtzde.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2itcatlfp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2niuqqplu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2refurrjp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmdfbdt.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2eugxvvgw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxrslto.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkaksao.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2zumujwdw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2shxhdvzi.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qctzhtwq.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjxduiv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2oscpdqif.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmamquhz.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2psdiylrr.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxyijtt.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyueegst.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2hwymriec.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2jtaiqloa.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2upgbclwr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2noemwgjg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjqglbj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwituvq.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2itoljzaj.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjsuqnxf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2tembmcbu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvgoxzi.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsxlwzqj.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqytyol.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgznjnis.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmlaspw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2otvffjey.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcoctug.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpflscm.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2svrgfuca.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2kghltnzn.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2xzehemqz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqkegsb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjtzosb.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjinfer.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxhrbgq.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdqpxiu.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2znmucatk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekggxxgx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2cuofyklr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2lufnfdin.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbdujzc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwttdpw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtnqbob.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2zslumrsx.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vpeiyekw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjjysqh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mydzspqa.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2wapyoruu.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwhcqin.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2uykmtjdy.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2rubeixpa.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2echwnims.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2uthpphtw.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxqiznm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rkoyrtjl.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxgmhum.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2xcyiglbj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmudstla.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvbjnxd.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2igqcviek.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2uigtsosp.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2toisvyyp.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkddsjfb.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgpqkrzm.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2nmldncgm.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2djqhkvzk.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2iibymyph.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2paylrdps.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2natiktjo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2upvqcjxm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmtiqfy.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2jybdkfho.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2afsldejl.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjwgmsx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2mctpdmlc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzrmosy.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbgowqk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2bojexvzr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxiznfp.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2badvcxtt.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbxqkuc.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2shcllnon.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhlsgez.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2siakpzix.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2dnbcoxgz.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2aybslgxl.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2faqyfauo.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldfogirx.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2uyyrckxn.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwmqxic.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fmoeshnb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlpjnny.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2gajxwwrr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2rafcwnyk.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2fcbbkckw.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2okkhfjvg.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2pchmzvpv.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ezqluhtt.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjsluzx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfqtmjg.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ciypjmpr.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2isunripd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2ezkildou.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zshovlrg.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofopfmmu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqzycsy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjaeiwwt.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjsatax.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhlpdcd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2upyvfstv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpzaxcu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxicqkw.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxnqywc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2uylqqrdv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnorbyu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdbnpia.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysatfcxp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyfkgoat.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2gciixbjr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2rfslavix.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2klqfsjca.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2bebsbxwu.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2giorvtoi.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpeoxmzu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gangaszn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2eogyxuco.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2nlcomdqu.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2olwlrmmv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2scsszvzo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kivyhomv.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2atzeefjt.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nffgakac.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqfnuxg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2yoctfsfs.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2ozufverm.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfsghgr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lqkeaklj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpnbydb.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2yrclwxkt.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2lynttqaj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgltqwh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebiagmqm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhzqwfv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqlzler.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qandlltt.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2txbvllkm.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2admnqmcc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2avzxqjtb.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uvntoafb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtomwya.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvszsatd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2aslnxmzq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2anezragz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdhguwp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwnkpqlz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dczdbfkk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnufzvx.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2yieoxmex.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbfaqtb.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmorawam.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtapscqs.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbyagfkp.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mykqbizh.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvytxxo.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2oohydhna.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzzynbi.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2lbffrkqy.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2sgszepdt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2sfupromu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zyowhhpb.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqyxxza.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2luinollv.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bcpwfgyq.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmmaiyk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zknyqziv.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2skzscynj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2jmntmpnv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2qsatypwg.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2pszycrdr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2iazapwzf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2krdytpxw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2wcimovzc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2vvnnszxx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcwqtan.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fywhvzpt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwibxmyo.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ukpyzpip.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2moihviyc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gtsbytlc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkuuhow.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjgesgm.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2goxbtlcu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2racmiaud.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fonzwwkv.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2koaouokr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvehapx.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcqgtkn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqwygay.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2igekgwqm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2tbbfdvjg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbxhelz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pylxwwwf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwbdroq.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2onibkafm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dsmossrl.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vvaefkok.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2qdywszut.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xurcptbs.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uogbijep.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jwlyvyjv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2oszgkhxb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nquugsvs.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2oiblyrbn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvpczeh.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2dxfcvkut.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2kafldwvg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2hvblfnoc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhgognj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpgurar.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnjykeh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2myurwiyt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2vodpjatj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2zetscbfw.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qptsnoqe.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfihfqhy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqraqers.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnhyntx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojuirpws.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2koqibmjd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbpgggc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2owtqxknw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2tztwdedb.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fuuznaad.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2iemvpdch.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uirfvmol.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfexvqlf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2biiaccuk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmwccde.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2utxupgto.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvpqbnfr.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zllefxrq.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mcltkitr.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnacicg.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2skjeemvg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2siuvfcjh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmxwylm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2osjkrdah.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uaaxldbc.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wokjwttp.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhgivup.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2glwsmhjh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgylvoet.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2izsqdemk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2tdloiyme.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxgoblj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rvsoqvwe.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdsynnp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2numcfcrh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2pplaincv.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvdvhsl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2npayajrg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyndfmrs.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pyevpjnr.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ulsopxsn.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyeaxqgu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kubyrcmb.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnopvjt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jllcybjq.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2vksbbhgv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2piyijwxj.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qsgbyzfn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2dslnamix.html


<!-- 参考信息 -->