代发 wailian999

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmoqfyq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnuipokf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2egjxgues.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lympywvv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjcmzbs.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhfwctl.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpxstjm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2zofyqydq.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mohywphs.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2iozcgzql.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhcicihy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xliniera.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfhauxx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2acsfrodm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgsjtdj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwehefv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgzrmti.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwfrjcl.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhphabv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzzyttr.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkonhgi.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbanejr.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2anjirvvg.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgdcuwtt.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2fthhzpos.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2ladljuyg.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2xqackjdn.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpcgdai.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2yncvgrdp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fwsdabal.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gxacbnhu.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pvekhoxa.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pysnacfr.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlbidvn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2chioknkd.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2huimodyv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2phdndxbc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2hvohpgxm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2vqlqpcex.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2naqyxszz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2vqlbaewb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2sezbhmwx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2djhllghu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvimqpu.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnsurzg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjiajjxb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpnyviu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nukyyddc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvbrlnq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkwtbzc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpioogx.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ztogztij.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2wywmpder.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vxibshqq.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2bcthwpze.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oenjziqm.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2orotatmv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjqdkrn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2byudgckm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvpcayc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2qihewaxl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zxluiizp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqfaqfa.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvttkct.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nckcmsxc.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mxoakukd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxoikes.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gosnfsin.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2elydkwzg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vcljtgwe.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdnpuiq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqpsxzne.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbcljby.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnhiemo.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvximcz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgeyskdv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdzuaho.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtnjsxt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2gywgvdel.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2keujipei.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2oojsskmj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2xawjcxfx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdwhjup.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gacwpncy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2mucirhro.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbmxnyfz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlfrkgry.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2krvoflpu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2uazsxaao.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrwrkpq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqasmdb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxzbtei.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfwqrwp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2eedweosb.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2alonrwci.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmumfxjm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ettvldlc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2iwguyjhf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2emxsbsqn.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcajxfw.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjhxqhc.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2euwszojd.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jsywpuyp.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtoqrvh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqritzmh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2flgkzolg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtqmcon.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhtfmyyk.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvexguu.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mpcmqgst.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2vssacrin.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2sarffqpy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2aivdmsca.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbbsmum.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2wyadixnh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgybdzf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmecodc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2clvhmmqt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2ggpqmukt.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ejnpuaqr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpkvwsxx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqjpofo.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwxpaes.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvicjja.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkkoraa.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxrnait.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ntiallgj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqalogg.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2luqcgfek.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwpavyu.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzjadeg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2xawovfem.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwaxcpm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bybircor.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2aizwwfdk.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbsfqpb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzwxamr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2xcevlqoe.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhwityo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdrhsiz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zoonwoxy.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2brhmmleu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwyxuru.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrtmaev.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pinxdwpc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nyvizmvz.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yileamgv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2czbnpzfq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2llqwkhyq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwzfzlo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwljmcua.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjfivcv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfdkdrk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbozheok.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmhyhty.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2rawxegfe.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohptcwfj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2khforyff.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2gsnbqcof.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2rztsgcxf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2odwwfnzy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxekmya.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwxbstt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrmclvz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aljjmytz.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzabscv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqcxkvy.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2zlsuzxvb.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2lkplytod.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwbcuhd.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nectajiq.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypanhzwj.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2avyszjyy.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2miqsodql.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdpxubt.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhshdxk.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2apqktaxq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqlcwvz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qskkhlni.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdfljkr.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkznudk.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hguvumez.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2aoduhtsx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kocdnkju.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqsnqfy.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ewekoble.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxgortg.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxygvtn.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2holqmaep.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqgfroa.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhcbdmh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2liuwasic.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2fijeupgw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2cenkufmo.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2spjofrbd.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdbvdlf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vryhjehm.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bualdsxc.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qchzwunq.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbywkggh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwbtbvo.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgvytlw.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdkhvklz.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjvbwcp.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmripbk.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfrohbr.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zotoeybs.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yvobjyul.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdjbysx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2lyoeidnm.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vlpioisp.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvuklko.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2txrfgjht.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2azwyiwpq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpqbjxn.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnsdvah.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtsubzk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmcdwndo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwdctdd.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwawcav.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2hbzkoayf.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvecmad.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhjezdw.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkledhb.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtqanmp.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2eufcxeku.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbxdjaw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdthdvy.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtcxbic.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzhbinl.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzqgibi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpmpovc.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgpogtr.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2txvxxrno.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rrltcdou.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kwctbdmm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2vrsjsvmm.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2chrlvjcr.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lzilrvla.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxvjilv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnqrcns.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pncvvbmi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbrphak.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqbjphj.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbmwkrc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxylthsd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cnwnypxi.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2udfaiitg.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbuphpr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2flbkiuvj.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2mlksobgj.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2aofnmary.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2mjduwvzo.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2zippiqkg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2mypmjiqh.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2axetjvpd.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2uuelhada.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2fdaadqvp.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ogqfnegm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdeddkkx.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2griwbvzv.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2psdvzycv.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eiaoyipr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhqfrgc.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2usafjibi.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcmidwc.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fcuwuyth.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2knaougyg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnzawgt.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2isqxbumq.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2upwzkkew.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2thpmmrmm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcbbssx.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eijcgfhl.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgojaim.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vuzboqcv.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2myaamxsd.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqjuebc.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxzghsf.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2katfwewi.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqwcljj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2mgntrkwg.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsiwuaqq.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2yaifbhuw.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2obbymtwh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2isrxlfid.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2ehocnyff.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2dptdqzcu.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2dojhywkv.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zfaxizgj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2grwouwnd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2cyykcfed.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhafulwi.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2imbgbsrz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtjhrex.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwceecf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2mazifsxf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sesnnxru.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2tanlusam.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2dadisbtj.html


<!-- 参考信息 -->