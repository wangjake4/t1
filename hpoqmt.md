代发 wailian999

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxrxjak.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2tztgwrke.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjcerhly.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2abwwqijs.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2giqojvtu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2tiasngmt.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2kjznkmzx.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjzqeqd.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkxkcuc.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2iaakivva.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2veynlkfc.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdrxxny.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnevfii.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2zllxwxip.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbchdchb.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2bpepuwdc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfcteukb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrnqyozh.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpxbcma.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2kohcugot.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2wciwyczt.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdipxbeb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhiewqm.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2foebuald.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2sptcvacz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbrdaaxw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcccoqwy.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2pkisienf.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzyuyxpy.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhgjphz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2iohehysh.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzynyjl.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbywbcb.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjhsneo.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2tciqahrq.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nscmoycc.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxaduhpp.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zueyuvxx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmdadvb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2ozsmiqba.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2amcpfzrm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2tblgvqew.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjhujwa.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2adbhnyva.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhwiubl.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yvyorzxp.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhjayha.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2srcrjsab.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2kzfsnzic.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrgjyuz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2nckozhtg.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2amgvrasn.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqjkxek.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htzqexqb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2powytasc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2olqbhylg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrsvpky.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uarxpscc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcbhyus.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lujgjuyn.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2gogopnuf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvjuxct.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2unggzcpi.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqwqbhr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbkztbh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhegexkd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2yexjoqdh.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2chufjkac.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgysoux.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2ctymrzcn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvpiymj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2oyomrcck.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncvtnrtt.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzrrzev.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2zsnvverf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2larmpeqs.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxocvyy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qytoinpl.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2lzynlroo.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2enzgtvqe.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkehklk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2oklgzjrl.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvqiwiq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2msshionk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqjdgzg.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzjrlbk.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnwukca.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2ysntdxix.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2mrsysauo.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpghhjk.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2egekrzxn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtnnzjq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogbpjnbm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpcckfn.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2huserhkr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzctcng.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pgogbedv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbczxnvm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbiakfrf.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgqvkte.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkluwsqe.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2najwncze.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ervpdymk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kufjsnmz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvaiftp.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2ynlycnir.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2fercgfad.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhlpwodt.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ritqpeud.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkooxmb.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zwllibow.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdadhtpm.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzdbmtn.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2eyuymtxv.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2pncriinf.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwxbeel.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2luxymtkj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxvihln.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oloztepu.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dweymaoc.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dnewvpzu.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2piffypdv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aefcpiud.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2meupkvgd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmbucaz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2llflduqq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2kfucqfuc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmohbpz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2zapimugg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2damlukhe.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2oskerlsv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2mytlmjjw.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtibzsl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ordzewgf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkttiww.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrksbwb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2poeujmqa.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2udtkicqt.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmpzluv.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxafsyy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2tgntkcgd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eaekycob.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnyagmm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhgoggk.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhzczxy.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2rqsdlgkk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jrngilct.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2brakelav.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2arwbrxtp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzowyod.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2uyecwcix.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yysdpchl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dyduabce.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wjenffia.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2vroypvbt.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmthmdsr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqtaadv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2woijoczo.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqdvvqdt.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyetssrz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxuoqzwt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uslgmnpf.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2tntthuac.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2igswsuyh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqbregm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2foazxvbq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnymvbby.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2xfpnhsvz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqzlgwl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2txnxcvli.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2srscedqc.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzchide.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxjglxq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnehpwht.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzcabjhi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqamygau.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtonzfdm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nixrrwnd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgdcbdv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdgqvmc.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qudfahbw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2ipswmecf.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvlkaro.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iudmclvm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2juuxuigr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmzotik.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwhqtit.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iliktdom.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmyqtlr.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yhcrmibw.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gxftcidb.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjxynux.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkinwny.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gyranmxd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ainxbzea.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ktcyyxpt.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wivzhsmi.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2valunvgs.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ovojjuih.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfavrjgw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2htojrfwn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjhjodm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2kerdychd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xrlrjmhn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqkwyva.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqhjyse.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2lqcqxsza.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hayazmmr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2jiccgnsb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzoebtb.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnauewww.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxkgfvi.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkcydxvm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jautzofd.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kssnljss.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhlsnma.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkzxnps.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nyafablr.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnodazk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2jodvejsp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2rkzeleac.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mipypvdz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhmccds.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnofvpix.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2zskfpvdc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2pdyrturk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbrgjsdf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxjnqtb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvdnubc.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2afpyqild.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2qfngtsyt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqamfruf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zspuuaim.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ddiusgsn.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfkdksr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2giikezud.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qqlotkcw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zatexuga.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncoazgcu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bftrqast.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2drwzpieq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqfgrfq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcrznyz.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2kgflrajm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsyyllbo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2raqhlypv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2onoquacd.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2hggczlgr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2rcregcbr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ffibjena.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2hvcdqqim.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2gbyvcrka.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ssovpofx.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2fevvjvhw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2caavzkdx.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmwfskt.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2qknhltjx.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2baaoteep.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jqaqgpwm.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txccjwdz.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvdzaon.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2svhowmed.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxwnrfb.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqhltnl.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fxyspzad.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvyhxfx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2obugirka.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfbyuwy.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nvagcvqs.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzfqkpif.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvbssvh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xknhajrw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxqbhjr.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2afovhllx.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2kasgdokf.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pyujjizu.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqcvuoq.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ceodgcan.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2oasdbauu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnkhtjd.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2notcwvcw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zutlzknw.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2abbmpdki.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdwfecc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2btdlkhtd.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpeikjyz.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2naahsjgn.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgzzwfts.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2prwedbbt.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2koizqaau.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtjvetv.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2tbnrjifd.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2qbofrnce.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2urdhmlgh.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmzxhfm.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdmuckk.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2woxnoprw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2jesyetnp.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nzysmlea.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2etizkjrq.html


<!-- 参考信息 -->