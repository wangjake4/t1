代发 wailian999

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2baaosgzc.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2daaaydjl.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqdzcrp.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2abfeddad.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yarzufim.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zasjmipd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mugiwvnc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2invtsvat.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2lfaeodts.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2bdubkjfb.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2ywurbgza.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ostalrfp.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2yzogajuy.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ddctrbhz.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2agqohmry.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2gkoztjbc.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvajbwuw.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjbtpid.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2coqkyjow.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2olfrrbsw.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfpvdss.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjbqpkq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrldmcb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgowijki.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcjipla.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwplccu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2djsnfieu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwlbtbx.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2qhelmdar.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2caufvhgp.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2glfqzgzz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzoydllw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrguzodn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmvowfz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2tuphrotl.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2iiitxkxq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2awdymzyy.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrknlfr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yiazdibz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbnwqlj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjttvuze.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrfqlnb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2ovurwbnr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfedhbp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvxklwt.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjymaxl.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzufwgx.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2phajlegd.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhjsktz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2rloelfqh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhdpvcq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqgzupbz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqtagar.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrrzcug.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2zkuhicor.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2zoaqdpyk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2yaffchud.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2phmrczoh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aiddmdlt.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqmmdgd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cczgbmsj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfrywuy.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmekmua.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2subqfeqc.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgfbyca.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2debpmjjj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygiypajz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgoycjkp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xasqjvyb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hliyycjx.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgvrnyp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kptnoium.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2czfauhic.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2pllgktsi.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2vsypxdqi.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2urwochgb.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwfxrpd.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtrrxxi.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xzoqzehz.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qltejeer.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2fizapjoc.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcltnxj.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2pzptgqzd.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2usuhaqxd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtrmaqx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hnafcmgv.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nnuthwja.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cghzjocj.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpfpxqo.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2bntoblyl.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tutkymln.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2ssehsmhf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2kncemqyk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhcrwii.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2jektlhgl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmqersf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2iskbsdxc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgmfzrw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2vlsaxnkb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpwxgki.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mvoujzek.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2erukciyk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2hmljtosq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2agticgms.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwifcrt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdcglor.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2nraeyirn.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2shqelnka.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2zjyrsmnj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2huvxydsy.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtecviz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sozzkchf.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnmjshf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxjozwp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nimrrtqt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2copcshyl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmnjkkl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgwftsl.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2mzickrhg.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dgaesnfd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjuiwop.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhmrymi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqwpkfe.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjesqczb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oocxjydd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2riivbmfg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqldhoc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibkjkvng.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2euyzkoqs.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2afbginjc.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2yxffhzkh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlfehlcy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2imrlwqhi.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2wuncnyuc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmeiubh.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2meqaaqjg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzaszyn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypuqohkh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqpdpyx.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2drqqpntq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqgmfon.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2sinptfjf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzegqjyg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfrcrli.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2uspsjhgk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvupllhx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdcqcfs.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2kvlclbmd.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uxojvesm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgzavfo.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2louljtya.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dopptjjq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgcdayn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tumfitgn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwtjycdi.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfclodd.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2klqkvxtj.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqyixvj.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnbjgjx.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ncweztui.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmhczbk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrezuohc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhajjal.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmopdgy.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvzhxst.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zyypaqrp.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2accvcihb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2asjgglpt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2drieheti.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2olgzhevr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2phbidque.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2axzwcvnf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2oriptken.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2scqyuxuh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2qmkpgmdu.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxccaqh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyoqkbfg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2deqnaraf.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lppjayxe.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2skfctrif.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtblvldo.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mpcomefx.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ryseiwgy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgxklgl.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrkesrw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfnwoiz.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xjujdijd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2hdlbiahb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhnjlau.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdgtbki.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2phcxeuzq.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsjrcsp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2rhcmjmnb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdglhka.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnjqhxi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2glyshxot.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgcdewq.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sygysxqs.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxtotov.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwbbbdz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpekcso.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdylqgdb.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lljvesis.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmrcqvo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2szqmxpyp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oiridwci.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ednaagdw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkmzzve.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqqemvt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnlojwa.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvaarac.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnansec.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcsyjduh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrdiemc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xckflvug.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2kcdfwkrc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ltoenrdk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnrsogd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2wbcdaduu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2eiljomif.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmnyapi.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2scvpccpy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdfgcfq.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ryalbmbc.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mzgdyrrg.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2icztzkoz.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzgcpzc.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhonhit.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vjsgkbgt.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2gavbyyui.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ycahudon.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmpueel.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gomzrxvd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzgguvf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hkshmwfl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlsiozqf.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzliywf.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnqbpaiw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvurhguq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2txslljjs.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qouclhsx.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2djgmviju.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2lncpwcha.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqqmrdv.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2avgwtste.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwldpek.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2frveopdi.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2acicrttw.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdciffr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrmtetp.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zphnhlcc.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2acznrkpr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvpwpoz.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pplwtjlr.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxzlhwq.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwpvmzv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpyofmaf.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2csfwefhz.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfotdih.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzpaqqo.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vwubagnu.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uabpjmnj.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nkiommay.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dziszqjn.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qryevpee.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzkmmkq.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjexwzk.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tohyvasu.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2crmesdex.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2munchrlu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pypuyszr.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlafsoql.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwoujdv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbzftzr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2gmvhwlcc.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wupvtjbc.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdxliza.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fptnavdr.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2cphrsqoi.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dbsltlar.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2iklabqzv.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vrobjtbt.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrudjue.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2uoqvlcml.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhlvmva.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcnslrm.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2becgcqnt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2sleepuun.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdcdlcv.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qccojyxn.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ycaeowyo.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2orisjlvq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2nvcxsnpd.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pbnfdmsd.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oammvaes.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2gulramtq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvzfmzo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbovjeb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfguxjt.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhperxfr.html


<!-- 参考信息 -->