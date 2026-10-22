代发 wailian999

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqacgjj.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxcqklr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrsnpxr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhspcnd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgozsly.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhzvjpw.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjcavpm.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2shhzvhdw.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxlgter.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkqbgsa.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xacpinca.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2naanusrz.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2xonukdcx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2hnsqqnls.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqumfhw.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2emomeamd.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2hvevrrin.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yzadvmjo.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2irdehtxi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2pavttosi.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2omdfbhuu.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ybsmrfay.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2sedjxkvv.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfyfros.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2tchumknx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2edudjavb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzyhyuen.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjaflmq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkdvgah.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pvpcbxom.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqmadfv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2clklrdxf.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2utcwsnqy.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2glvoduqe.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwwrirz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2qohmnqzk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdxodvu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2udzneauw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2aksvupko.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2vddyaxxf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnhyplz.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbynmec.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvcxeddj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2avpnprse.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnjmtnd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkhxens.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2wywzbkvc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysechked.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnjlamb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqpnmuzx.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2aotujqne.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yrdojbks.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2enkmqdcc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2svunuifv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2iohowrld.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkoawkeg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbadxgq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2fcabwohd.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmdtgoo.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2braxtcom.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqdckii.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjkxxcp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2onffmtyi.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnbpatw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqiiarix.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxrwvin.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzkclrm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmhtbqb.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkwewjg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpuejky.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcbcwzc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhtawaj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbkacedu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvxphhp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2uymebbxz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2isxahvng.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nndljbnu.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2eicvrxzs.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmbartk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkyuwjf.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytcbxfqf.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtibpdl.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkwtset.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2gxjvohrj.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvtzmhn.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2chkjurzx.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2zsnrlokx.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2gxzparuk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmbszqv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zkumquri.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpggxma.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lgdnkxkt.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ytfjdjda.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhyqpcm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtnvilp.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2rxcjvqey.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2voizmwoi.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqbvsoz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2hhpkzgag.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2zdytkkpc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2idxpiqfg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxgvpar.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2duxgvors.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfaojlt.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pzwgcrjg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2htdovxja.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxcsutd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lettxpeo.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2btsouzji.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2eydgkcae.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2ljoochwf.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ksizoqex.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxswfmj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jtgxgtui.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2nmekwkha.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2irsabmkb.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgiejfk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpiljlo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lqicvbbw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvpxxxc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvtotug.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xrujvfpa.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqlzonu.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdhnned.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtxsfpv.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2swzsweuz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2oqptiymp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzwtxdm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2stbgureg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhvtiak.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjuvbyz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2djdrzrib.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2sryljjqf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2efqjtfga.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2prvknxzg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2etypfdyi.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpramsy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrcbrpn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqksiydx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdiafflx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2obhkjczu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghuusyma.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2nylltgdh.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ktewexjc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbnuodo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqdktgk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2zwchcnie.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2gosliffn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvxapey.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wihjwakg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyrjdgax.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2wthkbpus.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2olnarxqn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2jnjmnwtx.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2idqmfbbo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2spykgqlo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iurgeuig.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbiuqpn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2erhdkjar.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlpdvgn.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ozalsjvt.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvwwcgk.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqkqlqh.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjetqnm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbmhbmk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfiknpl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpalfnt.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrtpejc.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rifpdgzx.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mflfnjaz.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzsjezv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2saqigqtc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgaebpg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2phxyagas.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2snphvbfd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ajsxsguc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtvceclw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2tknscqkd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdwyqoq.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2vojbofxv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xysxirmo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrddovod.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bajpgpld.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2fcreksvp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbafzlz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2knxfvbzo.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jofvlskw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2htozsiyk.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2phgjiyan.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbtfmksv.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ocehgtzu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2xcgkfxle.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2nyyftoun.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hdiudywo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2omalhjmo.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yracsoax.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2teufeuqe.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxwwjtm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kheomeqw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2idquekmt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfpxyiv.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnpivyc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2mvolstxb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2upqkfucw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ienivwfl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cnihwqui.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lkyzswvu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjspcvu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pephzosp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bsjnzdgm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2loecqzwn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnwvcen.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2lroxrzym.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2odjbwarn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhbldrj.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxmzvbl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2uiranede.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxkvglo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrthmnb.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzhnvrn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2mtstqmnw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqcyyxn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2aelnypbg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ykovdidl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2slqnmkdn.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvxsiih.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eimbvipx.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2kourcfvx.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2emxwotpd.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mljagezd.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwzeeec.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkurgyj.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2azoussjm.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgathorz.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrxqdpf.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2igozunnr.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jangvmfa.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2qpgrogih.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzexbxg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhuwkclb.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2klfdrguq.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2esvpohmt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxyifye.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ngaqlrrn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcujwofd.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ybecglci.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxlwncx.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ysijnjrp.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2frquewdl.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kngzycqv.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gopdjldn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjndsej.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2vevhzxdw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jupqprku.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2oedsxcve.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2jpnsryho.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmcxuud.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2idmcsvgk.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbbvosc.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwvpijp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdrefflk.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqbwpto.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsztxaeo.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2oimmfxce.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrmbbyz.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqplyqb.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lijgwiee.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lobyncsf.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqmaolu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqmrvqb.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jdezaibl.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yymogehk.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcoluxg.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxekkodu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhrdchgb.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrxgkzr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gskyzzej.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmfhjah.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtebiqh.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzesjzg.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2bouoxsfj.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dpyekukh.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbfihim.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmpstmh.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhcrzkd.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjoxjem.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rzixinmd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpfojpi.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdhpnuv.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hongimzr.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lgusmstl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbvvoit.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkdouem.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjephtl.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfqtelv.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pjoogrds.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2opaglbnl.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xtezoeuj.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nbpuqziz.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2qumgxeaa.html


<!-- 参考信息 -->