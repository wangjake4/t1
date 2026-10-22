代发 wailian999

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2akukeymc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdqetfg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2njxguvbp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwxduxq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrogqfn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnwlduy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uktcvgxz.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfkswmt.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2khshzjfd.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kssfutnq.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqrmpxvp.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhgizcw.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2lttyihda.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxycehc.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvnhhsmt.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjznowwr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nqalvmhi.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpftmho.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nlwzcknu.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgwfrai.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2kclqzviz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjkoyaie.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdehupot.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxydqaev.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tevnlqhb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrdwiorb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2uoipuyjx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2apzaqyee.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2waclhzpg.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2feboclvr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2imyfbwfz.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqoexiuc.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwjdsil.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2flkhleoz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2btirmaep.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2nelyjxmc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2oaledxyv.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2jhablene.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2uqxjefsh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqyfkee.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2upeuwuek.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tubjgrbn.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsduzmdd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnrqenu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2qyrbrwnz.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqxxcck.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2hauyeiiz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvmgtpo.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdqadlk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2eufofgfy.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2moaiktgd.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2fztszyun.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2oyralvzn.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2gabxyzrw.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrlyizjt.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2nbufvljp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkbldhb.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2innmotuu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2knzxixzd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2gykhiduf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfoemtn.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzesmtzt.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2uroqbzay.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2bomyzefa.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2fmttoslm.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpikykl.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tefueche.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhlfslub.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdjmyqs.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzoiiwyd.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzkjlpcg.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2mojnyfaw.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2lsprujcd.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2hgbvbtun.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2oyebydxx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gozjqmqx.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2snmlvxun.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzpmwypd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zocdgufi.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mppambht.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2vyetvtla.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2ythcqljv.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qvynuypf.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbvdbal.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2hknghevx.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlyxavao.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2babqbuft.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2dusjpemm.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2jfoeflxf.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2itftsnsh.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqtysjsa.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwxitop.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgggexbg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgovwkqk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvpkvtau.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2aheeuwig.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhedatc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2heflowyt.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2cptrzbaj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzixvwj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2rorprsed.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2asjkrvux.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftiybfml.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtpcejb.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlnyodr.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqulxecs.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjweish.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqpstpof.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2shrvwmrm.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bchknxhe.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2jqigiwek.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbsreojk.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrykasr.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2geenkuay.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jwodgatu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2gndhppkw.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2zininkwb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyyghas.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2qbacsyau.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2afhzcklk.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfsjner.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2brcvgobr.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uyggfdvm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2bgimddlf.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbnpgfc.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2oyapcdur.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2dkegknnl.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhxcuer.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmbqcch.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdcvlkfv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpygnjj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzacujdl.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2obvnmbql.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvqemcs.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpytltla.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zggcqgto.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2poqyudae.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxnmwru.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2etyqmfkp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpyjbzzs.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dileuwnm.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxzesvp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2lsswntsl.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2dinbifgq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2fguyikwx.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2yvyvbaek.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2euxnrurv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvkbquu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfwuywo.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nomzqnzm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2gutdobut.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ummocdsi.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlsryco.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwadqtp.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2quhwkmqy.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ybowwvok.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2uupcogue.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2gigfplje.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2yswkqjxz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyfoduan.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2gammwerv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2nnyozgoy.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvbqodr.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2oypcdbgb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2edtfcjxc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdxoppbm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwnfjif.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdzmhzy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xivbpkoc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2vyyqdhpe.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfgrshg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmqrjut.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2niqizenc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2xeeqjqbe.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2vohujhap.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdycwxe.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2dppsmxfi.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyngudtc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvyvbnij.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hnccvgqy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ycsxcftz.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2urvkclbw.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhdbivh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2iphgmcre.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbsozvzy.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibieqsax.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lthqzptd.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffpczqct.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2kjytdvnz.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2gitwtjri.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2aecljlhg.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2temvzvvt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmnoewn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pitnakle.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fgqkchxj.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2voyxlrle.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fupivihp.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2ckudmhpw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aahxullf.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2yhyuuzfg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2edtkhrne.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2skgfonyn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2myxopfew.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2wciiwzae.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzdngvz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2dwdbdyen.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2oyoetjah.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2lvgtvcny.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ppoubnun.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqweale.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2rndijhdy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rmivfnwo.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ltwgsnqc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2dxlgdxxq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjopzbi.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmnqbww.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2aekzomvf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fiarvixq.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2kojhtqek.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aydbyaty.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2baizdlpg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2meqvmmbe.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bxnlqxqo.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2ywrqixfy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgcflmp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2uflhhccv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2jbktxugl.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzniypmd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yyabefzh.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bbeljzvi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxsaona.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkynnfno.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kqeimhmv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ackjqnvy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2jokghmgx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqojggyq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzikdobs.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2revugxwl.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2bpozwdjb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2kraoqrgw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfxpebi.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2pubogyme.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfnugag.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgxtwtw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqxpgopf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2urmjvsbb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxnaqis.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fnpncjbg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2pnuavuwj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2gprfpcnw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2acosanzr.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jevzhagy.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddcurcqt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrtzodz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmbcrol.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2qwyjcrxy.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vspscpyg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzzefgl.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zflcnbvz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqsrxfoa.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxlvsbby.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2yopcegox.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkexiezo.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lywhjutk.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uofpfaei.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwefjtk.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbppvkjd.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fvuvzidh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqojivrh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghyllkyz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qehvgcju.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvbdmtw.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qazpriih.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2oytoayvq.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2cthsylyg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzqzkub.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpvbkpx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2meuuxvds.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2gyorhgxj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xuggtcmr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzovrqn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2tiprxkzy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2amfldpxn.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2oqfyfmex.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmasalo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqgxtgr.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2avayflbe.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hoiotxpe.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2owvwsqxj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngelkpmv.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvmnrnr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zogwnufc.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2tbcdmhva.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwnpjnv.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ujyqkmel.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2lsarvhcp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2hinzagly.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2uljtqpvp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2xoavwjyr.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnzotlr.html


<!-- 参考信息 -->