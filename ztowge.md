代发 wailian999

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbfcntn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcetpof.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmserln.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqepesq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhepyqfg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2sscfuqsh.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2aflmgdeo.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2vovzorlq.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjvcxdr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2njzbdasf.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhgsoiop.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2rldqtcin.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsgzmgsi.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2incqcycy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjgasqtu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bztnmovk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vmadupha.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2spjcbqdw.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2ebklztus.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyercydm.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2mniuhjmi.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2hghklyaq.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmbpmsr.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnjoxjy.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2romserri.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrzyzfy.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2vegbbvpq.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqzviky.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2xqcuhnea.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqqepfl.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oltxoupu.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvajggj.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xunoxsaj.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvascqk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dqtaduht.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpoumkc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2wogtbbir.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2qobgzgic.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2hcntcqds.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2mcdsrjgv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2awiaiwbm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2upmibpxn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjfgglg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2rblkvkkh.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdhzfbo.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywsxyyme.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ecwybhao.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhuglja.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2axmreorw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2xplihhvy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkjkxvg.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mylkecpc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbjrbhe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2efawpjat.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzzbnqw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2webzsjjp.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xypazctk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjwlwhy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjvechj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2uygebvsd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhcicxa.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2eykyppzw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2ixktanut.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzzuszws.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhokzjr.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfrqkii.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2wbcezfiq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wplwpkqj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzmmweb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2shxgdxqh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2thrwfnyy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdxazrt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2mktqcsqx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjrslvg.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2bcekmlps.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2vplzzyqr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2zfccsxiy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2okudfmkq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2tsquenrb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2plijyubm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2zblstrpl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2vyftnubp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ewcdfpcn.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2prxkmsbn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwgzfvb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtgefbg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojgpyrqp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkbilkf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkksgvyi.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfcoolf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfidsft.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2xcsbwmkx.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gzngfwpr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2ecyjqnqx.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrzigth.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tpavhckg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iveifqit.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2reedyudk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2faoeiyjx.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmagqgfk.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfixjrux.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqwrvbv.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aloqzqcm.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xxcfbfjq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwkzewuo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjgqwms.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmcqsnl.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2angqwiio.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fovrhdtj.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2arhvqacz.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwiraje.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2alpskxjb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2guhirzwp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvrqjlh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2krixqouv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xcehetmi.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhjoboo.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhefzmbw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2seawxned.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wjihhwna.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxmlwfd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnnfqve.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2cjywbjft.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxxkfwn.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpndtojg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2itidzobb.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwnguiu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqlvyujo.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2svmpilgl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ycnkwyco.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwfyuwk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqzdsts.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2yuyhktei.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lypaqafj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2ranoosph.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnmmnzw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ommdtfaj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnxudhw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhiboxk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2miqzgcrj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2utphadha.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2arfilrgx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2crejzvhl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpluqyr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2llnjclgs.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dleeyidp.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfebzxv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2stdllfvt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvbbmqe.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xuuboizl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfquebqv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmotlvmf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhvtnmc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrdossr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqswqnf.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxrvwwb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvazyqxn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2prfharnp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2qzknylzk.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2lwshtywb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2txmbwjhl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhlnizz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmtmcew.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2plichupw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2omtsstxp.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2eipklxav.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hgaumfzm.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2axtskxyi.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxduamm.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gnghqeqz.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmqpvio.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtlqjlx.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwbxpae.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2eztiqkhw.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lueqhvhb.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2epyzafta.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fwssimko.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxgmdyh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2exqdmdgu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcwfdrxz.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhriaxr.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtybosjl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2oeozwwvt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cskydaqq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2idtnqqwo.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qazxlgwc.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ackshvfy.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2isvauryf.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwpylxz.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfybtja.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmurjgvs.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2obrirlvn.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtshlsp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2akuehdjv.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ltynkdso.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzblfrw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmsvqyi.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgazjbw.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uutkuaat.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwaigryr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2cltujmhk.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rfeeahyl.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2nszktqei.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ushjoaha.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjfticv.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkpgglk.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zchalmod.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hbpzyhgp.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtbojuo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2wccifspo.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrvznyo.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fzuktyvq.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2iazxquec.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2drxntfny.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2arfrlrxw.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmffctvz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtslhdsa.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2quvherul.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2gppkvxxg.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xjshbzku.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2etguanoy.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsftcgr.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpzhtqt.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvirssx.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjeiefv.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cztcjzcc.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jdngpgll.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nybzlwzv.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2kfaqbhjq.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yunqlwbh.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnrzwfj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2dscyaeys.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2osalbbts.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zsupxjdg.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzmhgcd.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aiurskct.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2kxcgzrkl.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ssefbnfj.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvnoozw.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbpfmki.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2bohabfqy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2grksvkra.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2rloftkwy.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2viudlmfc.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cieqifxg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcfgyhp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bplfgltk.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkdkjje.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2yurrsmeg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2rqnwbenq.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hurmihsz.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2cyuwsecv.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdvcunj.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzvhcez.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2klqkfeay.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvfepyp.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2tugekqjr.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2qjihqlaj.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwiksfv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuostuzc.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2snndujbp.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kicxakts.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2joqfpvng.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzfawaf.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2mdfvkkeq.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2orwnxtmc.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlekdmd.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbfanld.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2clbtdkfo.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvyiuznm.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqjlvdz.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgrtraix.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsiwofkc.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xcsfyace.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxsfgjln.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dljrkopu.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2aznvekyl.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdzglge.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqydweh.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmimflr.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgcxsbm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2imjhnbzz.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyecrdgt.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2xpckauht.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdhvcwk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2wokrxuoj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqwrjqr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtqvjtt.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2cimmxcpg.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2airdxyih.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2utqowair.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbjxwrl.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2krpmyvgk.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkqexdc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdyllii.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjxytyb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqfraid.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbejblrj.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqavtga.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2eplsxjeb.html


<!-- 参考信息 -->