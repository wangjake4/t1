代发 wailian999

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2vipdrvnb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfycppgv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbfhzeaf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffejdddg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2yufzbbvh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bruberhq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbotlww.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nvrwtnyk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2afufunps.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhyvlhf.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxkfubi.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2qohhqkdp.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwwabpz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrtzidn.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrahhnz.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgptell.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2exratbvt.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmrymsg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhdqozu.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2saiaygjh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwvqzfy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2shhevsgi.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ucigtaxy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbclkukg.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pswwrvwy.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2osadwioi.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2sejwlzpr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2uygveoep.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2omxfmxba.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2fmayjpho.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrnjnom.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwgdyxrn.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2geipmmoi.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bibbbiwy.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpviuezb.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2wqnreywp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2dbikpqgt.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2knpqjejn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2icjwhtco.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2xuynwrwn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbzmssr.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmklwwtv.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2npuuemjk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqjxbkf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxldksz.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijnmiucn.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvsjkmx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdcuvsx.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2knjrssyy.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqnbiop.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2zuynpgxl.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2chosskwc.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhihnpr.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpoqjqh.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmlrchr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gt2iovzipok.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2ggznnaox.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2hhqtlykp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxfinlv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmuhzsc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqxgyba.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2erbncond.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2girlpxbn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2lorlqhty.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2hymwpbmc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjitgpto.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2sverbctj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhldekt.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvpftbc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2lcsxyvuo.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2itmcpbzk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2doxupmeh.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2dooafttd.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpmayii.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2phgnadum.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhhsibf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2baejuglh.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2cjmmemoq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxnwboj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfvpfuh.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2gaitbwkz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2stfwizrl.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjsrzeb.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2adlqefmx.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2tumisdol.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2waiscaow.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtoygqq.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2sonfkwoo.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ravuunkw.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhpbhyy.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2caaojcnf.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2fccbtnkb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmlhphm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjbyyvl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2bfikqvhs.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2btlfhbth.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2dyypszzp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwehoxqr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixpttpib.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2eawhlveo.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2ujktxaxc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtyohzha.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2ieyvivdl.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2mydyssbo.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbumppbe.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2gliiytms.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwijbme.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2isfmcsnn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2ibyqedzm.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zysvccob.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjmuyad.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzhrdyb.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwzmgvs.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovrjkuxe.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtllhes.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2xgsyiwvq.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2feuqfkxb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2csgbnmrc.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2otobpbrl.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2njzlsvfl.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfuqxmk.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2brjayfji.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdfffzd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqlkust.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2gppxzxcn.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgonvnc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2ogubtwse.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkdykor.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2peqrxjjl.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbgvkoga.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yalqujqp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wznwnyqo.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2shctywyj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ljiccghz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqavjyj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsteiiui.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2mdoaudwr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnqwcbl.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxslhpfv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2keoedyet.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbgyovx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkesekdt.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2ppchnrmu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ificiemg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2qoygxjum.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2bhszvevz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfidujib.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2siotxjnq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzffjcj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hvspfvqv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2slpedpwl.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jseffpyo.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmiyvoil.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rydsnmzz.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2wmehoafz.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2chqegbks.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2xscujavp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfcgsehk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2fydsysyf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjbbuao.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2nmozuehu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtkpjiu.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrgycnb.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2vasbbptt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkreujs.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgslarxj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfxdvyr.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oipcmyso.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qynoixln.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2knjzoecw.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2dgwlknvp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2blqkxapw.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kskhktin.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2flbhpblb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2pffenwdf.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdyuipc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjdxxqi.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwuotyyx.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjcjayc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lohsaptd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yllzwdaw.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2bfrlzqii.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvnodal.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kstibmyx.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2dypxtpvo.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmebbeo.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tzctfsaf.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnggndg.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlliogs.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2svoacbtm.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtavmww.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2htnfwoxp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqilezu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmfcecr.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2njosmlru.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2stnkeeip.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgdvcml.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkeiraz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bumqsuvs.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2hgbpinlr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2llsithuo.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkgaxrs.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdwwrfg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2viqlfbvl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqfocbe.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2lomktgsf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ivissoub.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjnnktj.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cgyjvopd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mroqvbcd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2yzskqsae.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2anqkvhsx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ususakcb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ylloxxiw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrcqjpx.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbtzilx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hlyckrne.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmqkpao.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2yofcxvtu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iafqedkm.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxcmfhv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2aodinmsp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdsrobs.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2artqpsdc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2kshaqwkb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjmggsf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2yjevufxg.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2clfwuoaz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ezydxccq.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xvlzvnpt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2isqjntew.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2luaciiba.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2laefqpsp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lowbckre.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnldqzjd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgaevfci.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjfynof.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iosxumqg.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2damkkhgo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2isrpcbpq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjymlds.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2lyomeism.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmnvlhq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvdxrne.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpbfize.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2nmgnlboz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2lqcicaiz.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmhrmcy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2fpexlpwe.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmjkvlx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2lcksbfao.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2somteagr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqfjcht.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwbhuti.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdsfipcn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2qknhsoie.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yekqfqky.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbhcgub.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hyueamty.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvldmdo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpakdla.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlxatjg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxykrbk.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmhdxdz.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vumqkxla.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sreudczg.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tncijxoy.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2oggpyair.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqjjinj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2avzktcaw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2damnujlc.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqqtgof.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2honpvcsw.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mlcqwegc.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ujeljqij.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bepvudhr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mssgenoy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2sxcntaiz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2cicywggm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2snrulaui.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfudejss.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqupccqs.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2fhawnvhp.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2fbolbhvu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdjavot.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbahpeh.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2cihzopre.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2geqtsshj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdskols.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbxhzxw.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohghjynk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2fvufvhhk.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2umvrvmaw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtldzxbs.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cfaivrdm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2mdlmbjab.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrrkerm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrhjwnz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2dtnxrwav.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uslkdeoy.html


<!-- 参考信息 -->