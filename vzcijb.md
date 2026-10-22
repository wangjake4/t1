代发 wailian999

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2hwclgucu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzybednt.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcjdwdd.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdegcds.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2alqucocu.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2bghodsam.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2slxgqbqo.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtskmzi.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkqjyqu.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfdexmsl.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuoyovnu.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzqvdqv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdpxvhx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzwobsg.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvusiqgs.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2wglubhws.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2veayfkng.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqovaajy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2thidskfz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhpjtzg.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2atjaunpx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2jfpvnycm.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsecsccz.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxmvbrs.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzfjifbi.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2laormhya.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxacbxiy.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpjapqin.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2oqodeshw.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2umjjgqtq.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ownbwyko.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtyschzz.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqskgdj.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2stsonffh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmuvqhf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2bwnfzjjm.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2rloyyxgf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2bewvsphf.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2kvorltmp.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2dplnumba.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2jdofjphf.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fnyjatyk.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjtaisa.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2obwdrqgp.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2fokqplqn.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypiczzqg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2axmuxnoa.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2aqnscpjq.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2njkblukk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uscbwicn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2makwjgcx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jilrgewj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbigylad.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qcsaygov.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkidyqb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2csewrsgc.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2lwunidtl.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqzntxr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqoehmhd.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2axicdryb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhbmkve.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2upfodcdz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwimdfj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwqfxgo.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkvcloc.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2suwpqqrf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oswitlqx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqnowywq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjaahvft.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkoeprc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2qnygnbvc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvdxacf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqerrxha.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2owsyounf.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2emgzmyrm.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlrsfad.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkaoieyg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbgvmzv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2drwphjas.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxbyrxu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbliqhh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2odlexsdv.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqldkdu.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2zikigyxi.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbvnnhv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfcvtmgu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvkfxtay.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfnybbe.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvawpve.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2phwzgbvo.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2sjpixkrg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2ndipgpjn.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2eunladip.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqbdjmx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2gemtbkpl.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwotxdip.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhymosfd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbleewz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqweqowb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhkdicl.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yypkidfn.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2httcgrto.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2ozfvteqa.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgwblmy.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2fszdugln.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqwuviw.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkreycy.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbflgjzz.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2jepubuek.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2rimxcwje.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpupwrb.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2jekurnzy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtnmuoe.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mnuxsrsu.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bvylvkvp.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzgdncw.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwvaytq.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmnmjtb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2esdeipzm.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2kevabodl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2pidpwqjz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2nyuqyqxc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkltavk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2efnfqsxx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2iiidyalw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2xculwhhb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxwnniw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqersvo.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhahftg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfatkgxq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2owvrxeiw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kppxkrep.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dilfxrrm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfyzpsm.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2doclopkf.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hgymusrx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2qqljjhwy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oegphkko.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2kgokiqzz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eskmmyga.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdxbmow.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2befgzkuu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxlpets.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtljzfa.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxcdpjs.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjtogxp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2vvutphmc.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uaojjydo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2njfsxwui.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hipmbznf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2mdalnzgr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpribjhq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2itmhouhn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzgouwa.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvxzahv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuehudzh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2neanrywm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvlhzbi.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrpgcpx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxwlcva.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2beksofhl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzftxbpb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkizmjp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdctmkr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2srssxqdo.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2qnllktgu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2feknlwsp.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iutevlug.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jonmugat.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzjetlz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfyaigc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2annmtdyt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2haaihbsa.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jydnpmyk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2edgimoww.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2wpoamitr.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fewfancf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvlhlwu.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jdexnusb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjnvogy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kbkffkld.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2krafmjbt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzimcvt.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2arerjmux.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymzzdwki.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrlgavl.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2osvfwwmt.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ysifjpbn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oatmfnpg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ccowilol.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tkvrvimq.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2voztrdti.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jfcbrwhw.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2atcxbjbp.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2epgpvlgf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2aiuxrtzc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnomftrt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrbevxr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2bglpbpii.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ostsofbg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwgbkpuv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghcafktv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2qukoygrf.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2lfejdjrj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxazsyl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqapeol.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrletat.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqavplpx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2bszolzat.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gamphnks.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kltskfsg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2umigysqo.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2rqeeemqu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2krwalzjv.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ezouuzry.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbkkduy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2afglhrux.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mptuhfug.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2lskheoya.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2okjsmxas.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2jalpruun.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvqrsrw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqlzudpj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pncmaoqe.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2grjkwege.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrpdnxx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2wozwndse.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbryrhyi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhatjvb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzkzzqi.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eqiljjhz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjzlkpv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2udxwnywm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxpceglo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmfwjuk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfwzdre.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2niaiyacx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ieodrfpj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2frqungfz.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2jpcwzjzo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwcynia.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2icougtno.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgmnxkb.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2elwxynsq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnbctbz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2juhshqxe.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2hscmrsqm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2fczupwjb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qvulmlnk.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzfeuqa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbbauoa.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxvmzoq.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2wiisjpms.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2plhntdxz.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpbmifj.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2klsqfmqd.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qopgklhr.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfurisbe.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hllvymya.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2shznxioi.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jpysgllh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2fvowlkir.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lqopikfj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dezxpeed.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrmnpfx.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvifdob.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2iztkmouy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uiwejemp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjqxelr.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2eykdvdpg.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2lksughng.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ndulcjmv.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwajuiy.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ggpdrguu.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2iulxcjly.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2zfaciutt.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvyqzad.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmgweci.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ftccqebn.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtswypo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgjidrl.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtjordp.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwitemf.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrihlwzw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2glesufka.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cylsnqek.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmmaahz.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2eymtgyqs.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjezrfp.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nztroifu.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpixpaj.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhawyub.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwvjori.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxkupve.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmlaxos.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhegzkf.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mfdfsjpc.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2liqjoohz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uighocrx.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfbhaam.html


<!-- 参考信息 -->