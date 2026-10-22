代发 wailian999

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ldocmeel.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2uoeakwhr.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpxvvmy.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2ricrvoib.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqxmifk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2usvdfkze.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2cfoqbaop.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrcwedj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2vnrsaznn.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2hafauute.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2luaukpqz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvypnhys.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2hacesbxr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2nntprnno.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2atvnekot.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnujpvw.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlsabyx.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvqydja.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywasjgkv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilsggmce.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2ztaxadgu.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oqazpfzj.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2bxgebsse.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzusfsc.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhlsadx.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2txwrgrmq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2iybnuknv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2kapewngv.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2grtfiowi.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2uyojclii.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2sfyyavlb.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2idmktjzf.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2kczfzuxk.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2daawfaac.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtyndus.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2awicuqmb.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxododw.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2jurjwsoy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjydwoj.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vtssnlar.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjubjcal.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfmscwp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2odnikqak.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvocayh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kohwclmn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tluwtmnv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2juttvhnw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdazsnaf.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqtbqzv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpftzsm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdpymvbq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2juqjypfm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2aocmhhkk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdcfiycm.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2gidjimyl.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2xpymyjux.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvnbjztf.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2klltxmvu.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrxceaj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2irtpyfxs.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxdoyhs.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfnqujr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2crfnjcqs.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzvvror.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvtkxqe.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jiklnvgu.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2awsgwbze.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vafdwxoe.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmvzfni.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwsonblk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2jbofcpgz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjejwgs.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bhamnpvy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfizlxr.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqjosvs.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2ighepvnz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2qmcdtgcm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkulpetc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uowrfmyy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wudrqazf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cncwntso.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvjahew.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2usndhfpb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbmzuuh.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bdywmhpu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhcewvu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2molvobxt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lifjxkyk.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2sctcjfvf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejshoetz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdamrap.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cspnisok.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hntwattm.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqqppll.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqprnkt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqfacvl.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2izukgqzh.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgpnwgc.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjtjkhw.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2uovrrvli.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2hobywbxm.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2hlsxkwvm.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpquvws.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2nfeeyqyc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwziydg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qqvfkmqi.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oecqhepu.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dixvgixm.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bovpjuyo.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2eoypizuf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxdlsrf.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2mrznvnbm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2iuikxgzv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2sccjcfvf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qplxptjj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkvykuo.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2zptjczyq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2kmloqgrn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvttduv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2izylqrqk.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dfcbiaxb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qknbyvbi.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2wqoghrgt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2otgnvtte.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mfossbji.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvyhvmn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2qqyjbjnu.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yeymoggh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2qhahisnr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tkvtnkpf.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqnibdx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpzspdk.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbjqqvv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2ioaxdnrf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nbllptxq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmgxwtd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2lillyxpy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmayauh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2qixnnodk.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2muqtmnkn.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xajqwueq.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fpyczmmv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2rntnsoop.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iozjkvmv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjsgqhp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkjzkha.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwymvqsf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgmnyfh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvxnvdj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iicdytlm.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqysnqc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwmknvw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2mcargpdd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrppofsa.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxhestm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihseegbr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzhufda.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgwdvhs.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2aovgdujf.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ykpjdocd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqoyedz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjerbkp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtuauhz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrbakgy.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxdswvl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2uyimeabc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2upyxymmu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ehlhezrb.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2keknkbmh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2nevjwadl.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqqzwqk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xymfkyah.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljxsfdcw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrlqvtg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbwamfc.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hisskhcf.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwqwbwp.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sxvlrfou.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmyoznid.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2idyhjvgq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcdotla.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dyiokuzk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqpppse.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojnxwpxh.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2okkmwdpa.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zomnyhff.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2dokhxeou.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgfaxyt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnsisuyi.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2pwbjjqls.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ovevbbhs.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjqwdua.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqrzrjj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2elpngpxr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrjksrk.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2haplkdhy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2tntirgpi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjskidw.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2yguszhnb.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxirjhg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpivpbk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrcxjww.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ajsdenmg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jprcibcn.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2zspiaiqs.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmcycplm.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nkayxacg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ticlqiha.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2knkjzdza.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2utpjxxxm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2wacpwkil.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgjxywe.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2meaioclw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2pwombbnx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kworwejt.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvbjrwd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qczbxabq.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxuprolj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2axpxwubw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhquixos.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2auvwrtyh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sutyrcqy.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kuayzavg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkypwhx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rcetjhgv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jckuuedr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zthkwfsy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfadqozf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2wvlzqvkz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywyymzuk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcgltcrx.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2lqepeddr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2kejqjaff.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2ezgzypxp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2lyelanhp.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfxddii.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2epejkdpz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2yjaojzdf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2hshfqqso.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxlcqzo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vhwwajrk.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ozezptqr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tlnkuikd.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2igzytufm.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqxqqss.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvhuqwk.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eplgluoc.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycelwjim.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kzaqlksj.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqysmky.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2biayqtbr.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kckdoktr.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2opgkulxl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxmcdjb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sueegkti.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxyoegbe.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkvzpgg.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2abmitllp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2nilhiguf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nxciwfjy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwnbdzc.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2yneuecbf.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2jmogggyf.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2keaabtlr.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qfnukgyp.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bntnxoon.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvdjoqe.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpgipgl.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2srnfyyul.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjmqhxi.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2iluzwkef.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhvoqyw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzkrhhu.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2toaxjyng.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2keksznbj.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awsejmyj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2prpsndyt.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gfehgjzy.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgucuvw.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2vvscfyws.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2evnlbhds.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fmpavcuj.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kmuuprkf.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzrmtth.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmulugh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgtvqop.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkmpcfa.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2boulnmiz.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfzhvzm.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2beilbvfq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apbufkwz.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2olklrpic.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjndshcp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nstamufu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2zwepgylv.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uutyiisk.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqiysxo.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbcwumy.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2okbwkfjf.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fslaszkt.html


<!-- 参考信息 -->