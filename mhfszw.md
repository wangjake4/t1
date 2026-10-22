代发 wailian999

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmfmdbl.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkaoluw.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kaumdlan.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbtjnle.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2xteufxus.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2djojagtt.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2cewyjfxc.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvmwvfw.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtreuvrn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2syifpqrw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhyagdc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gswomcip.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mckyajxk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ircftiul.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2yeqtqodp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2icuevjom.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2abyilmys.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2mrnccriu.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtxrgsv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlnwqxh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnvsyfy.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmyqzwr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtjdxig.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnahufd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2krsgbhna.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwxocyo.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qivugzdg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbaulxnp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vidxswkf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lrujgfol.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmrsatc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dudgclxn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixookzia.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvhipif.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2dptdjlok.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ggszpvhh.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2takdfvoh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzklsxl.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxygoscc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ombwsteo.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrdsfbp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2kyycdcua.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ugllndrs.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2atbttlkr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2knynabfd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pydvrqaa.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2chkozzyd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqytkwnc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nloaplvz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhajsfi.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2zkufpffl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2cuopfkwq.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2evxsqmyr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2sehzvmrn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkyorjo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajidnnza.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtojadr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdcwqfyj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqfmwte.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uhuqrwob.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2anuoyamy.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2bczswbfr.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjgbcwq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmkqgrsn.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtagkpy.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfrmoimj.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nqihjzve.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2rphfokhv.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2wldltaru.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2ejstrkmy.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2klosvghk.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2mcagylwx.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhvepdk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2miowqyit.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfwhuin.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qxdvoyxg.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2awzofpkk.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2zsceyeox.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ycszgmpy.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdivbve.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2smqjpuml.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcxshxa.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2opxfjvto.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2yooxseqp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2uumgqdmq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwlbcbe.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqxsely.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2stmhfaih.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdvxerv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyutbcuh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2sdsaacgf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnrpdhc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tskwjuds.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgatdmt.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2takhlycp.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rsynlrrh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2dewjsncc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzydzbp.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhdpsuc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2burmbgas.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xndzrpjh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxotovh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrfwpav.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2eaihefrr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2gxuceldr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2utccssbs.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2qxymxvlb.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lofpudyd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mntgyqkr.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iknkjaji.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2hexfnybu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxbuimr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kfamyupf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tfuhldoa.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2frwqduxt.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2brjrcuno.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfumdqi.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwetshuc.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgpmisg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvmwoqi.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2vlsfbtyj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhjotvx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2axhfvetb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjcyysk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxlaqrz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2rospmutx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2puasroic.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqlyepm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2civrovxh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkvjbyy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfcwfdv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxiausl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfkanapy.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2hpahcygd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxnxscpe.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2djazfuns.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xanjirye.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxmvcvs.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2oajsffpk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fosypuka.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfvrctj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2eanrnzuq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdztjbmz.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wyuzoplr.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqtovuyr.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xbyewqwb.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2palmzjtm.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgxlpna.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfkmtbxp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zexfqdom.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bvoawxxk.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqdmlikp.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zwoxxhil.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hwluejmq.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbbprsq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdajqxzi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2arzkzfti.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2oqffoxvw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnxxcfh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2deqifaav.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjripmxg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2lpohnkiw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2aolgbguj.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfxdgxk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcukefnx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aedtcvvd.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvskwfu.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwjwdpj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqpenibj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ejorpjbp.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2amkxwdcb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2cjoeindh.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2spwkegiw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnvutat.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwiiiht.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfrdnzq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpwndtl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2uylzgcee.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2gpeoymur.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnhmstb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxhictb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnrzyxt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oakqsyay.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2klppcqrg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2egmxldka.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yuiimgoh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2tvaizyrd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lprroctn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjegirr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnmhmfk.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwfqxvj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqgpmtu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nidxzzfh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhxsekj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iakrnmzn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvomjjl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2esxupubw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aixijwlu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmocofuu.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2iqcmbuww.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzccgqhm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwyzkfv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2eozbndwt.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2wjfbzdqv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhpptcm.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhjjbxg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2srpqhihh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ilsgzebl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jzszmofk.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2tegjwflj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2huzihmph.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzwpseq.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2umkniasz.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2feidscge.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mjprohtn.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2plmixbtw.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnhrgde.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpceeyeh.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbyymus.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2paqilwrs.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yqkabzws.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2aupieszf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hccbveef.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vupzavee.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2utlozvqd.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgztqqcy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtjqwtx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhdgdow.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkicohaq.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xkrexkfn.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2mazmvwst.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2agscbasl.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bfuxnfow.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qeyihcwg.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gotovtfk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2hxlcqngi.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2supvqrob.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2skjxlecq.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pympeqmp.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2kzauenrr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2igfbgxnt.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjhqqir.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgeusluf.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eonoituc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2nokkhtpu.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ggathwaj.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwjsotjk.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2cntxkqhz.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrzvcbw.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kjidinih.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jphrvdsc.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbvidey.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vcucewdg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhzhokt.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfyrwrt.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2czyierle.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qcubggar.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2hngkfmke.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wduopwnq.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iikpkcyd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtvlamw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eiinhgnz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbwnbru.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2szehpvvh.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2tpstyyxp.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2edylxwao.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2zfvkngga.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpxpenh.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hruftjuz.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqimcqw.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gajbosab.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mlngflgj.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxmffgs.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2uqplaxza.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bootxfpj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2ptconzjw.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbfukjv.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pagmitat.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rnreqwsv.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkzlnid.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ftssdkil.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zdltxhao.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjroxlz.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2rfgfltvy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2vfehksyf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkhpncm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2qidtfpyv.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwrfuyw.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zexfkfrp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwnpktbg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvstxmx.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqktgjzn.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2jofipfhx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2dxuftxcc.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2swfzzefo.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2iisngqhp.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvjlprs.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgaawjl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhpdegv.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xydzxiam.html


<!-- 参考信息 -->