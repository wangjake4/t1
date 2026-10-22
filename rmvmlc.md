代发 wailian999

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dlniugmo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwwotve.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2cycgebxc.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2pwlwcqxa.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2fmftfwbt.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxqikbo.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2brcpiypd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxerkeyz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dausxmik.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2cptmgiwm.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnfwvuy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2uirvpmss.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uutpqxbo.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2psakxuot.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbxtvja.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2izmkrtlc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2jisvwujo.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfktsbul.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfshyzjv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2evxussbh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxhyiai.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzmnedc.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2meawdteh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjysatva.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddyorlre.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmtebvyq.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjjppct.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2scgbnepj.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2xrccspxx.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpnwsdj.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2uynlydyu.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2pdnxbxff.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2uhndnnja.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2svsxmojp.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrfozpm.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lyazzivt.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjdbzav.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxmfurd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iedcroke.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2lfdmuwsx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2rbspuuuk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2criatzpf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2bpialykc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfqslor.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ngurwyna.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwnwcia.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qnypqwps.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnsijqg.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gabvcryn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2blvnrcjv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2omrfbgjq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rnyipffk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjgzlrs.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2syswcfyx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2jyytccwo.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2divnzdwv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2mbhstzdd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcbjszy.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2cuuprkzz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2itruakeq.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zibavetj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2rmucmfhw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rssicxpa.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2shhydfyx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2eixoootu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gnltytuu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2lozzqmcw.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2acvdxtof.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2whmsngat.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrtghfl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2rtscdbsg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kggzbvqo.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlzisxa.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mapmhbkb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfrxqfsa.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tudmzexx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpkaevb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oejdngmg.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2yjiopqib.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2yeylhfgv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqazafp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2jyggyhyn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2iffryasu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2qbajpudq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2dazbufnb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjehqnw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qmrbduwq.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xiojjmqw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxnoybq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpqjjiz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2enmhluyb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlebbirz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2qovvsqcq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2amlinngb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfryhcar.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2sjypkwcx.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2twhzmvbn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqtxrmq.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqqsakn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2adyzqrao.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtmkplp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xldakbqr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2wejmadod.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bygxkrkj.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nwuklxis.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xplvwcvv.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ueojzbyv.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2eiyknweb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxvqecg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmylcue.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lhtctomb.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nogkwzxn.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmnshiq.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dunxthnd.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhrprxd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2oveughdw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqinrpcu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfwjepe.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhtvrff.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gykwwwpj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzfxpae.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2xprupaum.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjlxycc.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzbsuol.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2orxmhnna.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvcmqzbd.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qvofcktk.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2snnnvnfq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2afehdkcv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2clnzozzv.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfajugdb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkybmcs.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2pnsadvze.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2omnplghy.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rzexrlnq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2qkamaeve.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ogocobwv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hpaoycqk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2jrodsbcr.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwlispm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhjdfha.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxwcycc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tyyxtvxn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2juvrpnqf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqqldib.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogybgavx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjsemxx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ucahynip.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvaxfji.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kshtvgax.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2viewchwr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmlafsf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrsjqok.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2juomqjoo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zsgnhkau.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2msdxxreu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtquzjd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vsaetwtv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2cyrorssm.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2fmpujqnt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2iujedyki.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2lujqnptw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2swvuhcpk.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmrsxyv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2vonjkcao.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsbtdsb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgizcxs.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2iklnnjvd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ledgtcwd.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2enoiwvin.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2skhxwjpr.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbbzvrr.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2reogdrqr.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjyldhx.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlqpalj.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpehawc.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ilipduzy.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbjmokr.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wnollvbk.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bayzuxwl.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tcenwhmx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2vjccfoii.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrnyfln.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhpjswj.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrefoap.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrfimjl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjoohhd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxfsguw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qeopishd.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2krnpglop.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqbbimx.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2abmgqepc.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ijiyztht.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2doaebqgp.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjtgpdc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2myjjfyjr.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdcastw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mbhwewae.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tfizwdih.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmphjlg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dszxonat.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzuuxjq.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwroqxk.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkfexbuf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2txvqirbr.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxlfrnm.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2uutehgbv.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdreypy.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnhuuij.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2enousxeb.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqxslfm.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfciygr.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wdyagdxp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2swxewono.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjoxrji.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxanvcs.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvxzhec.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2taqecdsp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqrjvtzf.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqezjvvj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2arepeorg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmeiqbug.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2mewzeipt.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzelgmh.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2efykvkjy.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ikerqldn.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2xezzxzmf.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dukrgdwj.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tbbyowgl.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2unufnxec.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rganebea.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2decbxjig.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2cvcwuogj.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2swphquxf.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vywdarff.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkktoal.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmjdcaw.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rayykxwh.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdlcjsl.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2suuzdthn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ctltdion.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vegdxuyd.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxvmcfk.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmapalq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2arhskfij.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrhkwae.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjuaght.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2muruaitr.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxyrbvx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqopkwwz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bbmzwgxr.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2efzavors.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2gngnrhas.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzraews.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvijqvh.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2yqscjlwl.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2skzlbubw.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbvkvlf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2hfozgbov.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2sghrrddm.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnkylbn.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ilrzajft.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2blqzurpd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfnigjj.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dksaecwn.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvplnsp.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2neaathgj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2upvrbnrq.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2lstbqdup.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdalceq.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjxwotn.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2jmpckvpx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpezjppc.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hopwqljo.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xthttyxp.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuglgxrq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2aaywgxcv.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mjgamtuj.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2upnmotue.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xptphodv.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzldxvnv.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2spqdfcya.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhyjnlz.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbarrus.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2edlquirz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2nroddezk.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnylbwhl.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2bpodoibg.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2epxpuphz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2hvyfmylb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2zkndsvry.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2uqjrnrqz.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2mtmwpwyp.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wczjpuuq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2bangwuqj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzqyktn.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxcbxol.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uszdheew.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ttruftnr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgszqnut.html


<!-- 参考信息 -->