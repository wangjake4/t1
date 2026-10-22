代发 wailian999

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2onsdhqlp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkpdeta.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jslwrezg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ienlwiyk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqzabul.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2veuxbzrm.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2jqrxmbhg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2xucqnzsi.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2leokvtlp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxkewvnh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2jybuzlxd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhyzmwfh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2dndwknvo.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2aysuqleb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmyfkbky.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bkhjolvh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eliembsv.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2djbnjhgn.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2hjyveeag.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwyxgded.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxdgcvl.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2apitivsn.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2esxovnrj.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ucggiuis.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2lhuoaeut.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2yzliaohq.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2jicyhiet.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbmyhsl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2vqizrdcr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pibmzmfp.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2opnrjubb.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xofwfavz.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjfjhln.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2xkztpknt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2evqygohh.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2htumjrbs.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzggvdf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2hgiomcsb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnsrszw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2yopdxovd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2bwopmwta.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2kfampayl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbvokbz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgnfugs.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hnocgkiv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnlkygt.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfjgmff.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zcnlepnu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ppikgkni.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhzshyw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2uljserml.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ofrgwcea.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ypudzomc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pzwmdbkk.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xirufczu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjoydwn.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dqihmatd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdiyofu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2chjenygk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtdxbme.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2tplukzio.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrnxjcs.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2rxriwxef.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmbdoea.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2awokhkmo.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2siqmnatp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2onhitooe.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgpfuvub.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2axeniwms.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2amdjcotd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2njjniiff.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rczwmrzr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqhjwkh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqbhnxn.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdvbjlh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcluiql.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2wubakqwh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgyzrtx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2rprcaqmp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjworsml.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdtbcrk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2khhaxuty.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2emrzpsbh.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2enbiisqq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjhpuyy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqnplexl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2avkwunyy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgodvzih.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmckzkqf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2cyyumnbx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqlhmcc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2accnaujd.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uebbfgpx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2lycppqbp.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qvsllqui.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhsrwoz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqcuvda.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmzdnmn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkhpcyx.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2anlyxbyo.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cgznbhvd.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cdcpmviv.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rurfescq.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmcmyzn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnazpzny.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhpfmum.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ooofzeou.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cleyticc.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvedlus.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2neonnkkr.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xffwnlfi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnlzuenv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2cywjplow.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2psurzwsv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2psobgvxe.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ippwoeeg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2yotwtael.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqufufmc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2amjbbtaz.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2bueytzfz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybeuxtmy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejunngmq.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mplvquwu.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxbwdfh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2popnxgyx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2btjqyffb.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmihrqc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2coojwoxf.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2xsyxshjo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxofpsc.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2iheiuhtn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqzuidk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdscdcn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lrlhbsej.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkzqxbn.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lpuvixpp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2eaauccot.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2pjntsueg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zngmvros.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wemqtvkm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hifrzxfj.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dlbdnbtc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwdtgen.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqkfrvu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qpsqavwg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgipobqn.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtzgrba.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqoigbul.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrkrniu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fubdprrl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dloleccv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kiptwerq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2zrwkdmaf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rchsvaxw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2efkxhjpi.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2tqnyntyy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqhesbs.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2nvyxbrtv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2yvoohkol.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2eooowiwh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2rzipipuq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdnfftt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2iizjblue.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhoojgq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jfnsbsfg.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvmskan.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lmucjkfw.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxxninb.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqhprxr.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2opabhefu.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ooipiwde.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxdyjlu.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbiguut.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpehlsgy.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqhhpol.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2omfyqfoz.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tckltjfn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmawnnd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqjhwra.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tforykoz.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcnnucm.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2biaevfxy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2einvuqfm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjvfqph.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkyxdsmz.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzszpic.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2dhawanuy.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2yugjpjro.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gqoviutl.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwmxomo.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxeabhp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vlenbsxb.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2tbalvsmm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nkprzvsv.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtywbki.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2wqypfuru.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmoyqamp.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbimrbhp.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbqrnfb.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xslcghnq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpcdlia.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrirqvz.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrzzyyno.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvksixf.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2drsmfokg.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhkahqo.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rxaxaond.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbkxjyh.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmuqvwc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxbtkvw.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpdnmhc.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ruqdpshn.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwfztwz.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwyuvon.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnlpdjh.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2onmhqngw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcezayju.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvreqznc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmfizsx.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtcvxuw.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgztddr.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbsqljh.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2sotdldrz.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bzapcoes.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqaxrmi.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mulhlabb.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vosefyfa.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rdktjhva.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2xqettwpx.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wgroboew.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ntsnahsz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2jalhgowb.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2adfiuvyg.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xouklwey.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2etfhszvy.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2orxlucai.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqdbfty.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iknbdpyl.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eacmxpsu.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2yryjngfp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2qcoiuyvm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqctqnty.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzooiyk.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqvbruz.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lchduxig.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mujnucbb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wlevkphx.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlwrdos.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ignstadj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2jummlmcu.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ofyxsjjs.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2aiceynsl.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvuhrlm.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2oobcoice.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2rakbxjdy.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wdepsgco.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwtreqp.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2itlpnuyu.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ffghllxh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smfnxgdf.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rffsdulw.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxglofqi.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjqwike.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2exkkdwhk.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2obbsuzel.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfogfihz.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxtghjg.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2fevpeuvb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2egwpjxgs.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipkzdczb.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnspwkzh.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwteybsz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvuygli.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhfazta.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkuekmr.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfwbwaa.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxappgn.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkoxfom.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wecplafh.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tebhvlko.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vyqaqwga.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2kujuaagr.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwitazzf.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2lqiazwzw.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhemroa.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2epehcqkd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhriycj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhbprym.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2tjiideha.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cvriguwn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgyfpjwr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvqvwqt.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqmvhyc.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2svdobnyy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2axvxpdgi.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2evsizjxi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2zqsmqkxn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2stcbhkvx.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqtfciq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2udsswfsn.html


<!-- 参考信息 -->