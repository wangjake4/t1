代发 wailian999

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmtzeau.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2axieckmv.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhurqie.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjyzvjw.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvfemso.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2jpicslyu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2qkywuedk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvkvpby.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2akvkamhh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2anwselft.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywohnbvi.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2diqdroqm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2vsddcuhr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdbvebu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkaqpfkh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgahvefl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2koadsxdm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2nfalhpxf.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2earuxmmb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2losuvjuq.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2syqcqrjg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtwessf.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhnkbbwy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2obwowpru.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgfovpe.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxioasmi.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmkzsxy.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zhlufmhf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbujejb.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2jhnprvgv.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2ophzdafa.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2aazpwxxs.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2dljcpdzi.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2cabppmzn.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhwlpbg.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhjdbsm.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2xooyyrwo.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2deabviyi.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhiplif.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxzclne.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2ggcxoumi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iahltdfm.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uxanwiht.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zrlhdalp.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ialgslct.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2qbafqhia.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rzhfbmoc.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2vasjievk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2qjcumday.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2yebkboio.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2lyblchcv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2hkkooqsr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ppcqbrok.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2zyacoqdr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjfkkhv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2cdndeubf.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrmmpij.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2txpkjpaf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxykepk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcpeaog.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwarqns.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpknwne.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2woimgkax.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rfsrahyh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2tampmmzc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrnycna.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrbncsr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xknbthub.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vobdcxlr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2dtewzenv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzeuitk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2txqxaxbn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqaeoliq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2arczybpe.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2fzsppeyy.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fllhhwdg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbxxmdg.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tbspehbd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2esktwowj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfklplku.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bseycvit.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oarmoheg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvaslbf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpbkykoa.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfihchsz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cemmhfey.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2fukiweld.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2uaaqqwuf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2wfzltwhd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2hylmlbcd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrrjrad.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2hiefnsye.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfywueu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmeckkr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2zzutaumc.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgxwtpp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfiaxgb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmyyboc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofixvoxx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmdhwfx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2iybcfjiz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2riapczaf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2invfpdmp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2uyarcnaj.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bapzztqi.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2moiozble.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dtyqywbm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fuzbwhyr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2athrihyp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wrjxpxrn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyuxiuuq.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpktpquc.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sydupsyq.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqmfpfb.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2erdhhduy.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yjyzccjq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jyljuknr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2srwatllz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzyxrwm.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjaujsng.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gxowktws.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hdilssfd.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjybsrv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2czmcvfei.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlnkrwm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2fhaqostq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2zelnyhna.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmsbpgj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwxrowg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqoxsfcu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2cypchrvd.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjguowa.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvddndk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipkhuwwz.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzcwkuh.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2awklrffy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhegzus.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2doxkjllx.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2puavwilw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzubwmx.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdrfmzu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohythvdb.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2awwivaev.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2pewzccfv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2nvsbnmha.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvrdioo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2tmquhfuw.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkkpsfp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2aekdaxgv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2vcpwfwnc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2byleiqzw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhhggpe.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwdmplh.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vivxejxx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxwsscp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mdafppaz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2djowqntp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hthcwkpl.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zphpklau.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnqpahq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2suhhegnv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bizpbzgw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbmvgaf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbyxkcdh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2oznyadkh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdpgkcv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhmpjtb.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2hssqtbmx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2khvhddfo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2ghsgpvvb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xguahbtb.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjorvij.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ajseeyjn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2norhtwvc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2xszhkucd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqvdxnk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jwstcxcp.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2vulnffgs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2duziryje.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvmftvw.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mszoeyiv.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtvxqad.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2omznxedn.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jttyrdwg.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qoyftcpx.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqpnspy.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2puntfwod.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ozfoknyi.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2njjafrsp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2evrortdg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nogzubjh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2taqigfxr.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jhyageat.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayoqdzkk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzxeoaz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qzcremip.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdwgsha.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gisymvjc.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2imzvpsib.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzehtle.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxyzsig.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkytynw.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzwuwsi.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbgsjey.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2aglliqjd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2plwbobkh.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hlodnhxa.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2vjycuthb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xafwsgjt.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvsmjyv.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2grkkvbbx.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpylczpb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2harzbpui.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2topflklr.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezqmtcex.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhbzqjt.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhjcxlq.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmeyirw.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cfngbqpp.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fsyovdfs.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pigqguqy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzpfjdr.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pbupjoyn.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2apocqwwm.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2omxjkuwu.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrlihan.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmuajba.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnomuxfv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocbknvbr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eglptjyc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmpzrlt.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtlrhrh.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2qjakihhd.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkovehc.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2wvirubjz.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgextey.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zeooggkg.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2umfmzdxf.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2urmivdnt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ssctmbfa.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2mojtqhwm.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vugfoqym.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ezoyivku.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2mywzpbpq.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhwirzn.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxysqdl.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzagmnr.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbkzixb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2uszmtxhs.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ezystnqd.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwnarsa.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnccnom.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ijlvkzls.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dezmtyha.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2iraxmfzt.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bncoftjg.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqtidoh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsktcigq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2owusmmqx.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sraxuprv.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2thphuppa.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxdwnyq.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgxlaxo.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2dncrpqnp.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ddapejir.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2wspgnkej.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2nbuelwux.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hzfwuhyh.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2qkrvftdg.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ymuxmzwg.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2btxulzir.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgolhkyd.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcptyfso.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcptejp.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqibsxps.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrxceqa.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpybuaf.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2muvhtxyk.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvknjcp.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbayiwi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qywsnjin.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdscsehh.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpndvxe.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvfzcnv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2axmqfleq.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gdghehzq.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mttjeksd.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mazqiula.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxvvizc.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnzcgfi.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpsonet.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vcsfnsjy.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnbdast.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2rriilhmx.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfelolwj.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2zhrkqony.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2womghhdo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2ekcegpzr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrxrdhw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2cjyassuh.html


<!-- 参考信息 -->