代发 wailian999

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oousprbn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2dwewotot.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2uayishxu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2oeyqjxid.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mflqqbns.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrdpaee.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvbunmge.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hilbjkjp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwevqxeu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqubjbs.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2madzgqfh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wzcueqqu.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yigrhibl.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2frpzsggh.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2cazjaopa.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvyvjkx.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdttnmqo.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgonxfq.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2onisndse.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2tblbhwfs.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqzzrei.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnqbnlt.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2bojlkflk.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2eehsujwx.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2sehdditg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqznrin.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2htpgfcxb.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqqmjea.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mnndoslh.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2jpkxhszk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rkitatdv.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2kcaniqrl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdpvimq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2sjuhyybr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfdayym.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2erjasgip.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqzfqal.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjkrcbo.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2nqgcigfr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2cduuwqca.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jquxlwbi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijpnaaof.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnzoocl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdayljo.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2sejxmuik.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2gutunmnq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxxetmw.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjpydes.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2uhoiydmq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iryruwhz.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2gooskzkk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jyacmoxx.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tocapmfc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2nepsxfbb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ubdneavb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2wrvkzric.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvrelwy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jbhhbhnw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvqefmm.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgaxpna.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kbowlqrm.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkuvjmg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2mlnlkqmc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lueywgoq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkjjwpw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhoqbah.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkqljiz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwqplll.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2etvmqrvb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ormpuvjg.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2kexwmxmr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2dhyvvnlx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2udtsenwp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2axecgvll.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtsevwyg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2rahbqvbk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfqxskw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzcvdxl.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2smflyenc.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2honmalpn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbsbcbny.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2psnapxua.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2uaylkqqs.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2uavqwopf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2yctykxmv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzaxzowh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjsgrkb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2kjaibbtc.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvavezs.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrrkqdh.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2axsagomz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2strqpjpu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmskxtno.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pureoytf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqlqpazr.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2btejhzfk.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpqopdq.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tjpgrtvh.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uiaeedwg.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2igezxdms.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lstiugzi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2blveqhur.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzxusux.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aewismdd.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fildiiag.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwduygx.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2nivsnclx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbpdeduh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2anhzvlgb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2gheaxlqm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2kqivmdmp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbaybzg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtidozyl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxzfeje.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2lftzrcng.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2eijuwcfr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbblmhhz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvmbdxr.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpotiyv.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnypfud.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2tckqgamg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2swbyulyq.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmhrxlb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2seupkoed.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjohtpv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfpphacd.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2epgbtkzx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2stdcegfk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2gcawynlq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qsfgksqx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2jyozacxy.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjeyqpg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2lhyweyzq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2flthtmkf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dujoqbfu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kjehkclp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqryuwrx.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvabnsxe.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2glboakfp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2safwfkzk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnkyorg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rgogfvck.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2soxwltkv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwyudtp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwolnip.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dgajjybw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvydcdu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjvxudn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2vgiyatfu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iobjqtgb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcbxpts.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxkanzp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpniezf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbbrbzi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zifvsiwg.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2jvriuajq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2uebfmaak.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ebcargjq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhxvkkv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ghuzarcn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cepmbmfg.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtyxksr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2trwlxzai.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ystfsulx.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlklzjl.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqboxxf.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2phoqryru.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvrgbbp.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eekgzgtw.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2avkfhbks.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2axwoivfi.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2azoqqhwx.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rkyrmuak.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2acgjsidp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zldptpon.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzrtyyj.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aybltqsz.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwitods.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqokbtd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2srrflwsb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gokoicxq.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2shrxjenf.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2pssycwbs.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2buayzlxx.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lwldgqbg.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfkppar.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmsttgl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2cxynnmvp.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjhaakb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hvryvuff.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2simsfqpc.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2windvtqv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyskooye.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2daceymnu.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2affsbmfx.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbumdmhf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywawimet.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2guczxhyk.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqxivah.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2lswdlxlr.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2wozrpkhb.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gmihfyji.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kemqvayj.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2apxanpxv.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpcgdkl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2wapzkcfb.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rgunnbff.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2betfmxbj.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2easxidjj.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2snwivdoz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kapeiniu.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpobgnit.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjwwzoy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2msmibbgc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2kwztwxcg.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iepggrbf.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2owpyyvwv.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmslgoo.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2grinxxqf.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlfpzpu.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yadozfef.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwqbomn.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmpcfkz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdamfdm.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2kpiqlmok.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvnpwyh.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xjczqnig.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxzquhu.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2spzjhrrw.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlazjvf.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fapcmuth.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2japwepxt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2mfeykqil.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zzosejvq.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ritzvicp.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2fxggofwk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjxmijo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnorhzby.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqlrzcl.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmhkdub.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dahbdgfm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxzrvlb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvyzfvg.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvatcxef.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2zabxzpir.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2xztmsehb.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jsumxzxh.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2whuyaanf.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2kolsvgvn.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2fofwncdp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2omdviler.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2usdnpnoy.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2sprnmmxm.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2exyzotlh.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2zfiyzqqx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcqpdcn.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2luirfgpb.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2asjyhzxf.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfztvvpf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvcrjyt.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2qilexjns.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnduzve.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jmefgufg.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2vjerubrm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2glvoblcz.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcyfgwgz.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pltdscpk.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhvmtfi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2byzbkams.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vzcrhsuy.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdfdarf.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cwuzwbmi.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlojwapr.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2twfvdlsa.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ernbvqkv.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tukmopgg.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jlpjnkjg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2pdfrecpm.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2iilbtzhc.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2nlyubosh.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqigibz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2dqopdryq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2uyojalen.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzlloyv.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxorpnr.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2njhhorca.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhpdnuxw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwygmoa.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxpvkwjy.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2oerqqagk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2udqzghgr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnecvfq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtgpcke.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkryarq.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfppqsuw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhoahpio.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2blsacocb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bebfatdf.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yczcrvht.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2aomivgwb.html


<!-- 参考信息 -->