代发 wailian999

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmcbdku.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdkxrcr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tamgwvav.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmlqmvi.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbpgoqzz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2hehjxdks.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2awugxtwy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2oulxlcjb.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gclyymep.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkrmkhw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpambzwo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnlchhn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lujngzal.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xovwhoor.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwmpsbb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqifiym.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnxqjfn.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdmheex.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2onooavni.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhkvwsi.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2sveaasde.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssazrrcj.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2duwiupej.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfnqmnw.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdgrlyl.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2bzimuwkq.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfxzjll.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2znoervey.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgvamay.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sorbvacz.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2szruffpq.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zewiften.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vufrxmza.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2nxfrcczi.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ikgxpzig.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2ondvagiu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2mhsypmjk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqgbluh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhdwpjg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2eydcqwon.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2zioizoec.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqahhvn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtraiqs.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxehxkk.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2abtvxguq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrewvhp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2znyrttll.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dqcpokvd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwkwxdv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2kqxgbaio.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwpiiix.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ujltswdo.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2icykqaws.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2joiittzu.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2gpgjxdmz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ddlonwqv.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ykolujis.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2njnslbou.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzlqgtt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2xnstlthe.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcvmzkc.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dkrfozve.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2admdsjpv.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmxtfze.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2urulunep.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkfnufs.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2imvwfjqa.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2glzhctnt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hywjpixr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qynoxyyq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcltdcil.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtdseml.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwnyivse.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxasver.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2bxujrsgp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdlgydf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgoiyic.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkikuach.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvffumcl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcfkatf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqtefos.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2pviyivyt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbkizdw.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrsquif.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2zpakbmxw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2xspmuogm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2slkkogoc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmolkofq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhntvisk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2uanacpfo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2oihkqldt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2jsmrarql.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkwmtaw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2arlbjfhx.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2aypksaxh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fuonnwhx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgwefpa.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lzcshwsw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxfgfyg.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jtovijqt.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fsiczdha.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmhwrbt.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvhzmlj.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mbldtdto.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqkdvbq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2knhioevr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2grcoxldu.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2spkgzshi.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zblrstxm.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2akgsnile.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhvtuzs.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fositlwr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zaigzsqz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvpddfn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwknvlq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dxznqfvw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbiutobg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2arwaazri.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2sazxbntr.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jyyjozag.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyenvmew.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wndgbixc.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpryltzd.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxiykrd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2agadfvtw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltaqoill.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxruhwlr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvmktsw.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2upoiwqcc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yeytjhpw.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwnwqth.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrvjjed.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2jihkjrdt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2etdillue.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2rptjiqrv.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxaactv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2agyxdrsb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2jupyoeky.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkqexeg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kvphhzxf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2remsbuvl.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fasygcqq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2rlknmqfl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzwnhaq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwtrdcg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aekuzkyc.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2olfggeer.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqblhbyx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmkoxse.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2thucspou.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmwdxak.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjkryfvr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2dfufbixu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zffsszbv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2knevphlu.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2hpyhmwca.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnuoerkq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhmevuy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2junjijdt.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2prawedvn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ywrrkvvh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2mfomqmnb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcevczm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2feavyvpv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wnamgizq.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ockrxcru.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cbttcuac.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2vmurueqp.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ckpapgeu.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2epxniqio.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gqroxedw.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2noxoeaee.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzxczxs.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2vichmtic.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zrcnacii.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjxtgta.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ufsjoish.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2znzidvnx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jsaiycvq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmkbdzo.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pocbaxwc.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjafksh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdkaqcxw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jfcyqroj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2acjzecaq.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbcvuvh.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ksspgach.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ourstcfw.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbfmvwj.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2agygoxsh.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrwxhtk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vodnfvmw.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjchgjl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxinaqb.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zrwpkmzp.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2xsiewxcs.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gubbabve.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfmyvfh.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkyvird.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfshpwdr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztttfhdh.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qhyllzjl.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkqzchxx.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2kwsmjjtf.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2crevmnwb.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ymlkhohv.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcxtnxz.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sieosino.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jiyluhgx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmvdcad.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxgmzix.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jfnsqlps.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xutshpqa.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpicfsj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smhzltuu.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvojsjr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nszchxuc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aguxlahs.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ucpxusvp.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2woxyxnoj.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbdluym.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlqvnea.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnujzbm.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2urmsnrer.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2knxdbugc.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dolwxfgx.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dctzztiq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2odezobkl.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2drxcqydr.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mojwkpue.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gwsfdsss.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmkmmio.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bedjencc.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yshtxsvl.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjpfgmr.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2athtzeyi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2tupypuvt.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtlpock.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrduiky.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2xsfxnwvw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2awpgmhwe.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxnbexde.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmkhczz.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjhxtoo.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbyfzsi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpzwbga.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zzamjlzs.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2thngildr.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwembrt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2fhcxzlgb.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzzfdyo.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2taqvpcbs.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzqoogx.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvlwylg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbrxngu.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2tvfjlyjs.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2txgdaiwm.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2uzofxjrz.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzlicch.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yppxnepo.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqkxosj.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqjolqz.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bidqhzgd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rswuzpoa.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvholqf.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwsnocvt.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rdtpzric.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2knbpykqb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbcinzz.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xobperzl.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndlnbjwc.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckgkolkw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuojlkan.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ocdiytmc.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgkevfc.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxnxzes.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2uoheqhvb.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpeqkvm.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2odjkglxt.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2uroxhbzd.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvdfhoc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtfmdog.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2htsmolod.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2qxsuizvz.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2paqtfxtr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjtyebn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2hmiknjhp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2abfzkntg.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2cybwshia.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hisznvio.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjzmhxb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2chmvsuac.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrhpvnxp.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2idkphofj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mstvegwg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvuczxf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2xggkilth.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2koyumtew.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2veeingjh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwpisee.html


<!-- 参考信息 -->