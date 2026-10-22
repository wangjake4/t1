代发 wailian999

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzsnbojd.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxosmcsu.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2fpkxyyrv.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwovzcl.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2iurgrilc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvsvipb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkumhgna.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzlfisq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzruyin.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2smamwywg.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2zylnkzov.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2onxwfsei.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2mprbcrko.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtxhplw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzqkgsw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkcukysi.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmegtsv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2iyyovrfi.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjaiclh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2csdfpvce.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrsufml.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxopxfag.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqyylpj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2nepcaiff.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2aijusbbz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zccpdaib.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hajrtppp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dqukqhdd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2btxoqnko.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2sypdgfto.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2vvneqrwj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylinufxj.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2irujggco.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtypqrq.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjaxynk.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhkkkfb.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2nrczixjc.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2bxodtjly.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2rugmwwmd.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2xztvvtey.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2nwcwxuek.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpxwaiv.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2reqrtovy.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dklbjkjv.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wjciftwz.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2ryeskmnc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cquvkajz.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2otjkrldu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2fczegjsp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2xsisrmiv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqkooqm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmtjqbi.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhyhshg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2tiiiupul.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2redqtxiv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2hdifrlke.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hikhygrk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxeexelj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2oihznlbf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2cmglkjxy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmgxrol.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2azeyjvnw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpbfmvi.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qkmgmbrj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2acsyzkrl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cdeapcqq.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xafnqkhi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2opztzkxj.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iqomeqag.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2kikithts.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ipngwibg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2umkmwiil.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2xacmalss.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2khwielql.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2espuxyvx.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2loslicge.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ckenwjdw.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xszllugv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2fisyrbai.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbodasj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fziwdmfy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fautnake.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdjtory.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydcenstk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdysatsj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkpthdk.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2ccokcbhl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2otbqtntf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqvxtde.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2uadbdnxy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2xazynbhu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqmrlwx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdtwvow.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvnktpax.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2kjuvsyzw.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pljtpybx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnvkkdz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2trghlcme.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2uolrrhrz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpdbitg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzoogak.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2krqotqxi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxnzsuk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2aqysarth.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rngxtlwj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgkzhsa.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wlpujtft.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2geujotkl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yobvmcxm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbdbeel.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2obquvpvc.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cyuzsamf.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkhysptk.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgijdsq.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqvwmqq.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2oebulpix.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpuvhznu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2htjpyrfi.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fljymndk.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2muivplcy.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpuldraa.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cfextujl.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2awsvwopq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffpykqho.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2srivpofn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2muvzzzvh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfalfyx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vksrqiyn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2baivzyat.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymzxcjff.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2xqaotneh.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbaunpb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2nssmxrut.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xspabvcw.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2slixaikm.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnlgwww.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhntcmow.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvyixkr.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dnksicgy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxvezrt.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbqxuzk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnutkvv.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kmlvxxzp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2gtapogtd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2iurgmwjp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcobgdt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2jswzxzws.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lniiipkz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnkqlvr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2fmubznvx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wefzobhi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2aiauegfd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jyferxzc.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmlpkhc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxocrqt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjcenxll.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gxepbunu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dakszbwd.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2imkdnvwa.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mcwbyank.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qpawgbgj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvspfzua.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwhrjax.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhoaiheb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2qmpztfux.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlejszuu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kocisfos.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrfhvcx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcesyroj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2zsubidjl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrqixlk.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxfsbrp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ueuchbnp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2wiakdeze.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2iimurtum.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2evztrmba.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tamfdmlj.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2rdywwjwe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxnnazo.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwbirkh.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2wqsdxvvw.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rbrnpeql.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qzremzav.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnpcwdl.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2txfreemq.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2zowiguvk.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxuivzk.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrxxhli.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2refuozpl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2zduvlcry.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wacrnrvk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yttcchpj.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kdztgeed.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdjvxhv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksiwrliy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2deszjfyb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2unprbitb.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgnbwfu.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2wcyrasql.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2iumlfcpl.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xoiugtlr.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2brwhgjgf.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjymvdw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwhtkfk.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2gxscyckw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2exajnent.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jxlloiow.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2jiybnbsw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rubaoixj.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksiwaadn.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpdwyqn.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwgvuyv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvuhjwo.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pnsgxvki.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpzvran.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2zacfscqx.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2otjxzzeg.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tosavprd.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtoiljo.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpiydtt.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwxbjnr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2inxsdubm.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bqufqxjo.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2faawymus.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzsrsxz.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2lvgppehf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrixxvzk.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmtjthx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyksigfd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nydwqnbz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2fszrskgr.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2okiqhqjv.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2dthoxqnl.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lzroapzu.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2kbeipfcc.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gewfbnrm.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ucclzaap.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zkkhemsc.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrpiqqx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmscwok.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2celatcwf.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gihvyylh.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxlvltq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnjvifg.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2azvmgzjm.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2snafuqov.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnnanvv.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jzojrncc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2imbkctbp.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2irkgvdcp.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2diptunuh.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwwxsii.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrcdqee.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2puqblyvi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxfugfp.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzzgnqiu.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rowsllpw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2autivsjf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfwadbq.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtdhcek.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpzmtlc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2zulgotln.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wrndjgvz.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ebphgjii.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2onagunnv.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2iczgczgi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbisqwf.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hixzkuci.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbgxahc.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2kjflbtkx.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2acasnvze.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsyxcvzl.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ontphucp.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvqhdaa.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2otzepwuq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2akixnpie.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ygnzngem.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2semipxww.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dbiqtycp.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxsrtcx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qricamqo.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2minsclxz.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2skyvgizy.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2diftigqw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qroimnwa.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmzdhic.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqifvos.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2axwhhejh.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ommtnsjo.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvcyuog.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2sdtbwoqr.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2cqksrufs.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxqkbwy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmrduuu.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2peaprleq.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtcvqml.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjrhfxf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnveeen.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2dtzvsvlw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2pyzzvtke.html


<!-- 参考信息 -->