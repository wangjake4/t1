代发 wailian999

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdofany.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2cigfrrjo.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvosgsg.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2eauqhzou.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2ufuicvcq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ervqsdrb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tddndhjs.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtmxpez.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2crowqsgm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2fvyrrgeu.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfktpsj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2hubntsnb.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpuvrpc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2amovwqtv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2hoqezxzk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnixpkxa.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvpwkrc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsoxuttu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbkgxbx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2epzlldrh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jyrzdfjb.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmrkhix.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2goshyrtj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfratkzc.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzazwxi.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2odzzfyyg.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2iwibadix.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2drodhfik.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxhmdhw.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsokbdl.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhnktwi.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvjydnl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2ciutweye.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tapgdwoi.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uysojulm.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2azkkshng.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrwsjcu.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2kykqhqxv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xjioiasi.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwyqfko.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqumlji.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2atowetnk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrfmqoa.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2sonoqyzf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2tazzuczz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2envctvxl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgbmgei.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2dnbqewto.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ulcsntdi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmapjci.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2tgszzifp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yzywynyy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhiqaxh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2yphxhzii.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2gffqclzy.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2daxjpvwl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2mhufwqgl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qzavrozj.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2natpjcup.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2smubcmzs.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdrubiu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2djqstktn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vapfjxem.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2yliacuob.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2puoulxan.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xpeloeja.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2cyyibtpo.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmgatlr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kppzypot.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ackvqrap.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2gizohuff.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwbubmv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhjpfez.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrxnymz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2krnmvoyd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzndmvgv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2gskmlwrr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmykjftf.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjmrezi.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2swtrvlzn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjkwpmw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrdzyep.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2cndiwhnm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhltjxa.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2otrdzvws.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdiricma.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2tkphuuvm.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tsygphnu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgznhws.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxplyorb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2siadqkve.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2aokzwred.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2grwpglzw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtubqqop.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2gefhlwwy.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2eigqoysh.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fzprnzhp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2tivgxxmn.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tpeltobf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqivxtal.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhzmolb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2crecxnuj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcdtiown.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lcuocwcw.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jeakphzn.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrfxhvo.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2djvspiyo.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkpgrpm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ybttpofk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pxujuuhb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hltuebpx.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kylldnzc.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgieueb.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwdudor.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gozeyjmi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nepgohum.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2reiupmnu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2jofxfvbx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2eispzccn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bixpptom.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvbbrui.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2izlegjaq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2qsgouwed.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2acxcimly.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zoeofeom.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhevffh.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifshookj.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kibadgqr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2phnpwknl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwjufpi.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2widagjjo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2miijzrem.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2jgljtizp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kipgqbuh.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjaogga.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2vbznsuxq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2rtrrnvya.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xlbipmou.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2ftcxvlxi.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvhwczq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2bekivenj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2gujzjrco.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmljlbmq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uztzmqns.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2asnhrwsq.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2axcuojju.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2dqnmblwi.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vpasnmfi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fwfjgspb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnemcyg.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgowgwr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxkzfxj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2brohifgj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2numayqdy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzvokkq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfoikdpw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdrmjfs.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kklgpngm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2omsyhnan.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2eugfmdmo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2irqwjihq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2mphrolsy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbmzmrc.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2crpzmxkh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2eeilttwb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ienwvkro.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2butskdvo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnhxbos.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2icrzstff.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2audsfifv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2unvvuhfl.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2fqsuhtgg.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2qnrlthok.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aojugmfa.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdeqrlj.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrggzzz.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqqcptx.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvemcmlf.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2haoqbmdv.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvpsrzv.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mmaxecdb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvjtdba.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzhrnvd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzmsxhm.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjzpees.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eojxpasn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2obfcgyis.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmdzybs.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgrgikgu.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nnblfnlj.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2mapkoeej.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2umkrhrsj.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ncepsmwo.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2uaozfmky.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yasxwuet.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvulcjq.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2obpynekd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qijwuqsq.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsiepki.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2zfvardjv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpfmfuy.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmokzcj.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2npknicbg.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yeaspxzq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2llrwtsoc.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzptphq.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xoztpogu.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2shpaqyji.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfrsdbo.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ecktnnoz.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jobgbqkv.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pzehyres.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvuehoo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2culatuzb.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mrynjisq.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvoklay.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pblpzgrr.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2nketedgv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqouynil.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmmnxqr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wankcadb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdiomdpb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2yhaahoqz.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nyinwybr.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqjksfp.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjxvfcy.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2dwsmdauu.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jcctvnlb.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pjpypgem.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dauiczld.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pohgycxl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqgmjrl.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2dujyykft.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxumajt.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2pbpjdlcb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhjttfc.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gxffenor.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2evbsbzie.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xiuxvubp.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iyunqjjb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvhfili.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bgygecea.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qlunyrfq.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2yiplxunt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2pwyctwhv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2afzigego.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2vurtsbnb.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdlkmbip.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwbnvxn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2theekecs.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkusibc.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwvltcw.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxkdvuq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxivvpi.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wilpkpps.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2afdotfpm.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhojdnc.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2viamxktz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2otxfpody.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtbzmjy.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ozplpojl.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2xcetwthg.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2mnpmlpui.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2icvoqrgv.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjckudjy.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mghoekew.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oergldue.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rprgurfa.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdslaby.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsibtgjl.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bylknkcc.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ungzfvlx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ombzqbgh.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbayclp.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxhywab.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2juyjklow.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxwklxhb.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2budbgmcv.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pivgioty.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2coahhlco.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsxogmzi.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2flpidtyr.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2alaeggrr.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2oakbovmc.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvxolsj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2rzofzfmu.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypoqjmxr.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2csocffdr.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2orgigtgd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtsazuz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2ubyguybm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrbaena.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2lfveltux.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cvuinkhf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2shfyohxu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2rbujmyph.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvinwxux.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bsttqxan.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkrvfik.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2phnyvacn.html


<!-- 参考信息 -->