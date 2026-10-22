代发 wailian999

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wasddgeg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcslfsqo.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2yeluauty.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjgitxy.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxzjuhh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2fstlmzfz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2xiyguyrt.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbwlmmm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnzgier.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxsbfjf.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkipwbnt.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2stamyunz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2kccawihp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmjafvv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzqlqex.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sebivhgr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjdgigz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2cvsyeivd.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2umhhlqya.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2zhylmmos.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2huqaqfdt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcltlkqg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwmcmud.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2nglddtbd.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwokxgf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvuwtyj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfokynl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2elghojxv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjgqjfd.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2uuiplbnz.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2xabhldly.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrguynjt.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2mthxdaej.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojeyipwj.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cebenvuw.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnropyli.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2wqasnwsj.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjnvsmx.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2wugqoslu.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2mivcvgya.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2omvkxydf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pmfwotmi.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2erjnxbqy.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qdaqkore.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2achginfh.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2hdackkrc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2luukbebt.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2zijbxxaq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjwdiyc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2yhiiudwy.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2dizpmmhu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2yaswnlxg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrbvzld.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdbyzxv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2nlsjgftg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2emfxwoya.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zeabfvdh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2htlgcpkc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2eodqgtop.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mdyfmzuj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2uywnlnqa.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2bugqsasp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2czmfuyjw.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yonjvirk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhnlnoo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eoujkvxl.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jrrxrona.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yzkbibcp.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bapmfgvd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2fhcyahxr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dqthtohv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcrvays.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2dbsmnian.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zzazaayx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmddbdp.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lymsrbun.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ifeeorgb.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mnokmqip.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2efxjythr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2noegjgll.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tskggkrh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fozwaupi.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgoolffh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2imiusntl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwocrkt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2chmmxduy.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2vjynxghz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjnooug.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdibdrd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkfgfvka.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2qcuprfee.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2zyyogmya.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibntrxkf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjtcjii.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2mepnmfzj.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kgemhnek.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghiibfwb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgsrlog.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2pniualxg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhplkts.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixeiqxvy.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpusmse.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdyywlwg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2csdraomr.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgyvsan.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2ortfhtie.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvqglha.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkpepvl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mevqemcq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmalfvr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2hemjvfbo.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fvijmdas.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqkzzrt.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rhafqfko.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhvicht.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gozbehhq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvlyzix.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdubemsh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2shfosczi.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzempcwk.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfoblsrp.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2obwwvvtp.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ohimolno.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxyfqqno.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2auugenlf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvzgyxu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkgptzz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qbghlgik.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqefjxv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2uimppprh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2ysnvprfd.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hnoaxbed.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhsstrbz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zghahcoe.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxkowtf.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrosgbwo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwomlhel.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2olccorfi.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2fiaszbvj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2royodknm.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2slsdrxkk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhboljm.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfsbwjo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkojani.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2jcaekzav.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vyawkuqw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkcsryp.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wknlklxt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2pexbucjf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdejjub.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqkjtcky.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dapadaqm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2njqvwwhu.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ucaajoei.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2yezakfii.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnhqlev.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dotougle.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwjxcao.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nulfmjpa.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgjsedd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mdykgptk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdkccxc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxcelog.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2popclptj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2phrgbrdu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfuhlus.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2izwvrwet.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ibcnxyih.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2lljpzzpi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2fpviobif.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjwezsg.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2krlvyvat.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2mltykiky.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2rhrmbzkz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2pyksfqpl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjjgvzo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hpaamzlh.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxmlsok.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvuxcna.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2qemsvuln.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rklhjzap.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhrfvuh.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2noppwjrv.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpjiczcf.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jwimbetf.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkysneci.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tlaurukq.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxgvbtf.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zohdqopu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2bzuhgiei.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2boguqujs.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqaqniji.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dljhjnlm.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrjvwxwl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2vynxrozb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lgebosnt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqotelsq.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdklvug.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2cejtbpjt.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mocfqbky.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fnskbsqm.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2leeswbun.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqocnbqp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrfcwoe.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjuvegz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvapwzo.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlfifvd.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2oajlckpz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2abqugewz.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqazpauy.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqdhdcr.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2igkzaxjb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2clmmtymm.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2frvzptqz.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtkmwond.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2fvlxvley.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbrrfzq.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqbrdyy.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xadssrbu.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hccwxihk.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yfryvukn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgiyivm.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ukoeumod.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ptycydmc.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdnjkxz.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ewnfqmfk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhubtod.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifclaehn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxihzgd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2srozrlhz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2vgizxuke.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mgccofno.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2hoypwzgi.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2msnpugdr.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2dyprdjkh.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2srcjhkti.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgcejtm.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fnybbmah.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2enqwcewv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pijjvspo.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnxkrzv.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wzsgnlbh.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrbbsrb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2pqryqayz.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2clomgnnb.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yqubybtw.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ehaihksh.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qpydqtip.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbsozcb.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zukdpdkd.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pvoeviit.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkvyynv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgwcmrl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oehorpki.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2apuqsfam.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxpummt.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtodulg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdafrpzs.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2itzshfem.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybyzyhuq.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqxvrnh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhucnnf.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2drxpirxa.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgpawnr.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ekopuhho.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2goawljfe.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2acnpbfbp.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qvyonwdr.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2otcuskbn.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ectojvnv.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2cnoaqaft.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmyybui.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2klrjkdro.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmgyurc.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdakxpl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgwxstt.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2idradgqz.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwcrepb.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrkpwnq.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2frcffgkh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcrpmmz.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gouoofae.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dktusffl.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxcpsmio.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2egukledl.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbaismj.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lruelvwj.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjjcdnp.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsoyhbj.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxbocvx.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvhhdla.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ezefapuz.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwfeekk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrpnggn.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2zruumnxe.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbwwhre.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzkukja.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2jhnflbmt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2xqqwcfvx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmphxgn.html


<!-- 参考信息 -->