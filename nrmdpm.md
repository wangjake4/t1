代发 wailian999

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvttxssd.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzmhehe.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2froxtbgd.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltblygte.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kttrynto.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2shbuvhef.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzwvvdk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkxeewv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2koeethjf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfsvqkj.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2muvtgake.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnhlxmu.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhedtuy.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxhohgj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2mldcgmde.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2pixnppqv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrzjvat.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2nemmzzye.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2qvihvoxg.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhuzoxo.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvrjokf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhehpqoo.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzeuzevk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sidyetvq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrgxlet.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2thimhujm.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2kigcyjxe.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2jlacfmtt.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvujfoe.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmenuqar.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfcsriw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpruzhw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2enuvouku.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2waldlmlq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvyfabnh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hqyaqnpy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ghiytmxa.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2qcpqgpoe.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2yssvpkyw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfjubms.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydiusooc.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2udtlchwd.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2perfppzb.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwoftdq.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbboveq.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2esnghucs.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2bjzzfbzt.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkxibia.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtfzjtv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqovzij.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzjtjqj.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2veduoyyn.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jsypkmyj.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2vlovazup.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rgrzrcvo.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2shhmammq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxdnnsd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2umumyglu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2mshfhqbr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2uvckeqxe.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2yyyzqggl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcrffuq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2utbbtini.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjohzjh.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2voiuocux.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxrzaxo.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ximxrttq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjgvcbt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwntbif.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2jisiwslu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2gbiyyfkd.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fmdyemim.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfgdvmg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zdpwgpme.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ymuvqjis.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oimiwdta.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmjvhao.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2njfapdom.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2atarswte.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwyhrsy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhjtlqh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzjsfxj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2bcoteooy.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oanppdef.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2avwztenu.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwzfvfj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxkuegt.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgprxal.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtttehh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jznigheh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgiddwe.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmalqafu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2lihcfynh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oatgifjv.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2boudbeav.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2okohemzk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjhnedm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ricrkhca.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2eeuyufst.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2mexetllq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxxjbwn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ziyysesv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrvgnll.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mmekbgak.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwdknxe.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2fceffuuu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qefhtjqw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2stbiufnp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqcfghat.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2gavxwjah.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnzzevpt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2sloxpqhz.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2falbaquf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2qefndjuj.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2decbuhky.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfuwdov.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qoyrtipr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzcuesf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2nawproyt.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdmuhdm.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtlxwpp.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bllcixaf.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbrnyjm.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2babggjfs.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgtohbs.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2crzxvaan.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2eixxaybh.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2shiijelh.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2veaeubxr.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwhukci.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2wrjwfuig.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2heyuracl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdonrzzc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnowcke.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjwawsk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2eoligfso.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjckgzve.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwklrrcb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2haagcbmz.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbcjnvj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmepivkk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2juijtinr.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lojqihea.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwcaxihw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmluwrx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbmfcmg.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qahsvtju.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ijidgkny.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2kunliaxs.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjoplhm.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2abpstmno.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ellkrewm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2vvherlde.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2npzsasci.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmhpksl.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oaproyld.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2aqnkdwrd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2ildimlnc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yecbcilu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vflbfsds.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbuwxqeq.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qslzfnjv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzzwcer.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjthvuhx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxiirfh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lcehgmqy.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rcolbnfn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgaykaa.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kxigbgnh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgacuqzj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgxzftx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2capyikjb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2hesojzql.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrsmsubf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxrqohp.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjdnivn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlyaamog.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzayumf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2rwzvvive.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2lijserkt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2avfyvjqo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbqlhdn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrvvntm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhhdhzs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2frccdgbf.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2rnigrndk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tdswajup.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtriszy.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2plxvqzvo.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2toqryadz.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkeghzv.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2maoddnup.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gwapordu.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2izlimgxp.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2robaghxx.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tagphmzy.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wgymluyc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2rihonaxt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqijish.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkbfifc.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhnuyzk.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eckyotcw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2megalzhy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvlzmck.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aftplkep.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nprrpftj.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2toauucyk.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2oeuovgjg.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xgosrsdu.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ywysmfsr.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmystclc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpxmgbh.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvifdjj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzlimpc.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wkagxqpi.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2jeomjjvr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcopxgd.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xufuohnj.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwuotagd.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpioqbm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcohqnvh.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkkeifz.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ausahixb.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2cbombyyg.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zoplktvc.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kubcswpn.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wutplhwr.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ktlwwukr.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2inbbqoln.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ijukacvm.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2diqmxecy.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ilggzdxs.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2uixojsze.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrxruql.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfpijfv.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zidkknum.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztoykyjg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hazkivvr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2zimtxzlk.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tikkswin.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzuoevu.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ylttcsnn.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2jskfylwe.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrugisb.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gboqdqni.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vhwlcyej.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2myrexyac.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxcqpre.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfhinqn.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtbduxj.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2khhpcwsz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2almftoyf.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kiekjbsu.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oijetlpi.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbjfhen.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfsqioi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxccpks.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pursiqtn.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sykeulei.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2yjpktscb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2qknyvqgv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvsgkyx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhbxdav.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vaepmwdr.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftylwymy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnonewit.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kgioftyq.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxbubaf.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2mnngjwwt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2osnqmizp.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2sdeibjpy.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrrwvlx.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2aumepxpk.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdibyll.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2qbrqllbs.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2uscrtrrp.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2kiytuyiw.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjdrbsa.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdrnctd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2okqvxevy.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyumbqit.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzcxayg.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdauemge.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfcofzm.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2afirkqff.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzhjwir.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zcozuqdl.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqatack.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsbtwip.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmppqaf.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqyynesj.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2seoczfos.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsepjamx.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pbehjned.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsovvpm.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjznsec.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrcfdyst.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpkmfll.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrzbbyf.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzfhzni.html


<!-- 参考信息 -->