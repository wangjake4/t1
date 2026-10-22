代发 wailian999

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbszmhe.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbopgmv.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2ottqhgyy.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmjzfjb.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqsnxhw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhewnaq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqviuvxz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxehbvc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2xjemyxmd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekcwqvsb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrrrovr.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qmusfysq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2upllqzaa.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnntsjx.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2wowyevkv.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwcynmwh.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulnjkzga.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvfxkmn.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlccodjs.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxhnqjo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cbyznjgg.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nrulmxlj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ufidayrh.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2todnjnag.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2bkrpwoxz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mynnkvfy.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjafitt.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmltxpb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bbncyejp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2pifffdij.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2lzriglbj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzkgixz.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxbvpfa.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2cnggrlen.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvpoqhh.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjkecow.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfptpkg.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnrvzwx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhrqmjc.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrwgchk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxemhnw.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2orrjjdnv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2idvfrhfg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2rzyqrpmc.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbdrynf.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2arcevlck.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlpwnyus.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2rwieqymh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ilcrpspr.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cihgutqt.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvtqqwn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdeynoor.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfcpyss.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrldklgf.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2oconnlmc.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmptoebt.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2shkmbarc.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxvbjax.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2meucazgz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ieldzuee.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2sazoomou.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvoocig.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2oizkgxlh.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgefzaa.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrnddqw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2fbyekwxu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxcbrbp.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2diusfalf.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhrneaq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ortgexpk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yygadoqw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2srasrngv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmugjypx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2wigfqahv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruqkvlqx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvcvcpmn.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwmcksv.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2hugzsgyu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwwryaf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikalogas.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohaimitk.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ciijheyo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ucarkskd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lavrsons.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2krjxcyis.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmmdzyj.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2yocxdegf.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2vojwqsck.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2svjwlmrg.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvyjccyn.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2lemehvco.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwneszmp.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdlhdmre.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzynlgso.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2drunazpx.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2roymolur.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2naitoflk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgibdwyn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2hliqmbvz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcyhobwq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2owpbsdsu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2griybcdt.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxlysfa.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqehwbl.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2ganulmtq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlonzjwl.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpfjwav.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfanstgy.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2muxzifzi.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxycbgf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcwtuxg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkyhearz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2tncjicbr.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjjztmw.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ypstjltq.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqeiqgom.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2buaxknaj.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdegeie.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjollan.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2mynrgbgr.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpvrwpo.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2jdiyddbm.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2mfalrvzl.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvbjuhwz.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2adqatxia.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxljunq.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dobymnjg.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2wousaynk.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkapducd.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2cgnapgvh.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2eziftvsj.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bgcftoqp.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtoraaj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hefmxxki.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxuivdzh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzilbib.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmmezqj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbnpnce.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2erxwffop.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rywvtxga.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2jbexcfnm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2egjaswix.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqjxwbm.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxvrquu.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2atedfmzg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2knquzljj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkktmup.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpchblr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2feusdxhi.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2rdumulnb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzopuwud.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbimmsz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmgkbcc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ouegolmu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2tblejrcw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqojluo.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqqgbvg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpfznurk.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2jbesglny.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vaspduwt.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2bitbfomr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2wstihwfd.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2btecwjpg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2isludlft.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2msxfynhi.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbuivxc.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzgcblrd.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmyfbsb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqeratk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmxypdu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbxfiaf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgvvswm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzcseyth.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2qtikvzce.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmqqubb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2gfogqcut.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cpcwkizo.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2qiecpuji.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2aofmjddj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhnsmzj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2blvvpsyk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjlapxqg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojtpjlna.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2caagytpd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2stnexyra.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2fukxjfnh.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2tepsrima.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxijgtsd.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmelsxwg.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2niqkllxg.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dwyyfhiv.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhqbvnkq.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2ynezxavh.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxznexv.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2siqcfbwf.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2xkckbypq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqhseve.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbtafae.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvzqill.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cevyxwuq.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2egebuxmd.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2marwsges.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kxoqruwd.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2bwpqsumd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2dnfqoyfd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhppeur.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2eogrdyzs.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqhixya.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2rimjorpw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2ddchrvbc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2tljybqlr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2knplyoby.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nzifokwg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlpjkjpo.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2obbkpfqh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bywqcuep.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjyahlv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2glznauut.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqsdkdk.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdcqyoc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2irdjowlt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvbsjer.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2whmclbuo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yznfamnk.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wmimbque.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzodakm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnbwdcd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2smskueqj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2fspuhozc.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqmtjgz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2wpolntwq.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kzelslja.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yggsxaup.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gfyvaqll.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2qdiqauax.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eucsibmt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gtxepblb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxqhvei.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipazqtoa.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhvfdzp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2rygtmwgo.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsduevzj.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxymzly.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypnjaems.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2egneznqt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2sipupvmk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmxermv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2wivjmnhc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzihbzv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2tygsngbk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ponrcuch.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kvnkvjmp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2zimeycmo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhlfwxnd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwiqrrj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2utezwgdb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjrvvsr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2hluwwllt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fisvkobf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtlxgsx.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rhgoiker.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2exuhpjom.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ptiolrst.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yrruedmw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vyialsnt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2sosztarq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmfuuxjd.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ctcneong.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljeyshnb.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ailmyijc.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjefxbnn.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jldkzbxh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vrspzkbx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2smukagcw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2yruhbqxk.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkoxbjb.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cyukdnxm.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxgmuuy.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2cldpufki.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbbqzuiq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjffzrtd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqnjqhm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2nphrlnlq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gadayehb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2oehwqnxk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2vuyrjonb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtxlzwp.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqjospz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2cliddhti.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2knbezbvm.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2umpwsmmd.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dewoicsa.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewnqtyoz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrldarwn.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ndypfikc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qnlrfvgz.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdoiwbe.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qnoyvdlf.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zgbujmjb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2iwsrppms.html


<!-- 参考信息 -->