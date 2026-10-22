代发 wailian999

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yswsnafz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2oqlbaqsm.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2prqgxrpw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2sudqfboq.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2peztyakt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehpsnrxi.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsnbnchm.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvothkzw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2bataogcg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwslspr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpkbhged.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nymarsly.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aclnlkbl.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfnloqs.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbdtwzc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrihvura.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnxnymh.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhdlyxb.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vortrzma.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2djwwvxbk.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzgeyiy.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwkgnmp.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2vvklvyhs.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2aaltqxcv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvkozag.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ffsairgw.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qykjlxjc.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nxohuhwo.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwesmzq.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2dxoamkly.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2paquyzsm.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2glkcjfjf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2sjpiezha.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmtakth.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ufefkxxv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2mobbvwox.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2osjtgtel.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvfioqk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjjcbny.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2hrheyqhk.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2peydmkno.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywrihyum.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2dyiulsdc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfmxrsv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nhcsgreu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2xumfruox.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhmaiaw.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2npgsshtq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2lknzijls.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cwchzwka.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjdtfko.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpemjof.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vihubulk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2wqimrfwk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2iibsphti.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2tdeqqifi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvmttbb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jvopdcrc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2rlkjfkmw.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqibwmv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdqekil.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tovhtxqp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2yksyklpu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztroevwq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgyostj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxpirct.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2shpmnaaz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2voaamtka.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2aycbsckc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmhcfmj.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2ifoioyqr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdvohqg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qryuvqtw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2xllbnhiq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdpkuzil.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2jnjhnuqn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmatenk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2svwoymnq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qiajxniw.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kcujnxvd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhcuxiua.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2cisikjqy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlhuoez.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2iebkmyup.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnybzykx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwzonwy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnsllhu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmizvhn.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmojuwg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2hivhkgdt.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xfavdenn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2raieeypo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2paazjalq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2umfijlnm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlketnqo.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzqkbgk.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqopibrw.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2twrarvaw.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmutbnt.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2aopvagnn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sldzapon.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtvmvlx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbcwerv.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhozjdim.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzwiagc.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhlgbwc.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkomqcu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqyorvaj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qioqkyyv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbrpggw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2bvsuqfgt.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hivmkivx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2trutfcyi.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdndhtn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2obldqntq.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2aikwtpvb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xihgbawp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfgdwud.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ahkysqqg.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wywqgqqj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpmbuck.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2tcaofsck.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kyrxwaak.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxlbhir.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2nbuxbzno.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzmfmhd.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2txziipbg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2mojtahrm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2sfglsbfs.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqrewym.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2rymuzaev.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlsknhtr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrwnolu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqayflt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2otvzoaem.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lpotxeiu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpbswcc.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bfodncbb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2zwobvqtb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tusxcfvl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rouydcma.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzybqbiw.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dlntvcwx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxmdmig.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqgdngh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2whirpyrh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjuxbdj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2msgahclm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxklqvf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2blxpufzd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwuflkm.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2nbimxuhm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqonrxf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2anfcspxy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzrujvo.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2exgrkudm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2pswyxwzt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2outqxfhs.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2aftpimyp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2gbcucshg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gunthjjk.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpacsmn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwtbbfw.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2mtiyiafd.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jreqpmby.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgkadfk.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ykiykdsf.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtczhao.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhojvox.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2kavjksag.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sulltqpy.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpjlpwa.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2imxuiqns.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2mpadhoie.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xylwxgle.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2grfgjeue.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hefhmbka.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2alqhvksi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqvdqdc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmhahtm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsyzirjz.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqesyir.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2psmoxhmv.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2flollajj.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lxybaewr.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2czbcfgoh.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xacmaduh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2lefkdwhr.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjcufri.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqzrpuc.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zmyhucdc.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2qzzemfao.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfklngq.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlfaadf.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eexmnqxz.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjvysne.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2etsdlhrh.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wplpxxnp.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfurwtbe.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ihooujeo.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjtbsbp.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wixnhkhs.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dngpjnmo.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pmaqkkdl.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uyirtzjj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjczeui.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oeadkzsa.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2osujpdkz.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2aculewej.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ffraxugf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xquxbbtw.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2egprzjoq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyrxwdkg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2psanrcop.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2zukdkpep.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgdsgbb.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbxgplz.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bwoqpewy.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2lneenezx.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqwmlbp.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lbobxuue.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lezamhce.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2oriyhqnw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qfolpqlt.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgbaxsn.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfibjto.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmxkwkw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqiafhx.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yjuwdasx.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zegzgcgp.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ognocchr.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pylboeey.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbquxhj.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aayeddvz.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2enrzlwnu.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2kleetuhz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqgcdgo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sweutgsi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhoydpx.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmxrhgz.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnzsxkg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcaiucgx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iblxpvfa.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgfrfzf.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2fodkicid.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkeqrnc.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ywyhzflp.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvfpdad.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vqslabhn.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2uyettorw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqfeozy.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2nftvuahj.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2zhkthewm.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2zshsnqgi.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2fantxbcj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zecsnwjz.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dubtcbdr.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqhmpqk.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jludqcrw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jioojdcn.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2alnjpsnb.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqhavao.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zayfntjw.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxsenni.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2menkiiwz.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rseliyro.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brtttnzu.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gamxgkkk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2guekgvzl.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pzwtlwbz.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlyepvj.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2frhnvdju.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjsjtjd.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqdllkb.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnjevvz.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xhywrqxc.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtaypkj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2todtcabc.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihndtllv.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpnrtyv.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2tllmjqfl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2mmstpxht.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2thomwbil.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2dqalxccm.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2kjljbhlm.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2majxjldr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2whvegppe.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2wgabtqpe.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2sisvuwut.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xdcysfry.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xqanhnov.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvtywhw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2kddzshuo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2amgyschu.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzsvgyw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2qiworvlg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2trcbnvbb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sypnslil.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ieznryty.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2dibqqcqz.html


<!-- 参考信息 -->