代发 wailian999

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ldoftxhk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2icszlgxk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2fahpcbxm.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbeaysks.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwfuadk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qufcypxu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfohacp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2awkfhchx.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxucqwbn.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2ovepuezh.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2uamgiboo.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2btlfhhot.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhanulcv.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2coptvbrb.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2otzupdxg.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzylixw.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcjxaeu.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2twphoivb.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxztitx.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2fxakksvb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjfdbjt.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfmzuaz.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jgiadxdn.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gzldeyph.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fgievgwk.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2gzlpdhgu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlqcodv.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2nvoeewym.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2vngqxeny.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqjnrge.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2clczfyoh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ujuzwaaw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwdctec.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2ghuzbrwv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvfrhvy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfmeagg.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nhapodrs.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zivaylnw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2sopvnsdm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xcyapmsl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zmchlohs.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2xomlgxiw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwjturl.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bygapejm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxbrpke.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2orippnsh.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2yrwkwymz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vorqudrf.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lragozov.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmusvja.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bbcllgzz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2isuogsqu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjbcitj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mclcpvrg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgmspuk.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnkfikb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qabqtpry.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jjtopzxl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkcyhnp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbpntws.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uicivxcy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2smoldobh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfqfijc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2muwssgcm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxcauql.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwlwrjn.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhrknin.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2fooshrou.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2odxrsalg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2kddwoofb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsmgzux.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2lernzszf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2clpgtxku.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2nasiwdpt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xaesdmjm.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2javjtnue.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2mylsdfsj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvezfxe.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2kdcmacxh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2aksoyvqu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjkbeqn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2dixwoqpp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkdflsm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgtywyv.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dloiuydx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2gojakgmi.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxfbwhr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2adiwffda.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lypicdcu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qsoampnh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqoomyd.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjuddgmo.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2azlntvkm.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mqufzgib.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttnntecd.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpwhjnp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmrgxbw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgiarbwb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2blamyigb.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjbnefjm.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkokyzqo.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbqxwmp.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqjdgrh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxgessz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwkdmbxt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2kyygppzf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2nywtymzg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2grixizwh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxppiocv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2iicyfnol.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2kxaozzpw.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ttebjqml.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxvtlkv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqsdjuhm.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrounji.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2palzlbgt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2husedcyc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhjfrfx.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2anwucdqd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwjdddd.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2leyttmrs.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oerpofce.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvazwdv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2iovcqhst.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmowaqr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2iereyotl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfohnqs.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkuvsnh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2jfroukyr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhaopia.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jenlddrl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjkcymy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwsiswk.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2keaoskch.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2gqlyflvu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpymyfx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwehcrm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gaiakvwg.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rcglcjwi.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ablwsmyz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fvltpdkc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hsvbxxil.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hguciune.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgnezkw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2zwheykim.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pufctodz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnutxeek.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2qjursief.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2alkaxnol.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfdlkfl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjdfbnw.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvszere.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2haqyamxf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwsnlwn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqzbnxr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jomhfdrx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zivyyqit.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmvzvmb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sarvqunn.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2foxfsvtn.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2hitsgmfl.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rtphiipu.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2crdgqgvv.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqnbkdo.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ssngzref.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqodrtbi.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pepdjkuu.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2flfvmudr.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fpeaqzlp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2quhjecny.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lfdhiatg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkeekrih.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2naxmcbyi.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjjfyib.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqcgroh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qinhqgfh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ragsiufe.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wevmdkgm.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdnjgiu.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhtzirq.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wuecdjoj.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2veldltbf.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2upbvchzf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2asnvehye.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2kubwijnb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkcfzxb.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2puavorzi.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2nvrztoyg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmbgdbn.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eapdbkkl.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uphrdurk.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mitpmlqs.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrzabea.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ulecxqok.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmghyxga.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2kqxzykrt.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2xctopqqe.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pqyazajg.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mhxogxpt.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqfsbqc.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nwozyaub.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2xiluphgp.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mjawdyhf.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lznmdddi.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lxthlvnp.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2lehgfack.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvihjxdk.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvcnfle.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpfrebh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smxwlkqq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdzfvfy.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2handesyn.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2buprfkax.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvclhcj.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdxfsga.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrrzkij.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfcwjhk.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xshdbacl.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2sralixxw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2aibmeygd.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpvhujv.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qdrbqcai.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrjuxfz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2ujneqnwh.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2alrhzomb.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzymvcp.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xghtvwbt.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwmmggh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2rqoqimix.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2imzaqrne.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpcpymn.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2jseculex.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbamehb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2itjcdgzr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcsszuk.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpspwnhl.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdqwcwy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijndhudi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhoketb.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lplokcnw.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2qxleddaq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2yylkllsu.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzwcmam.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2pclxbzve.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkfcfqr.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2exwpmnhd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2jljgetkb.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2biwxywmq.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2vaodmlnk.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2auiwdtom.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2crglhwfj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2csjfofnj.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjhbcsf.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkgzzux.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bamtsckp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbvzhxe.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2gkagxpmj.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxqhgfn.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gunfyrgb.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2imekqqys.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fokmsbku.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxgapgtg.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlzqiyn.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxkpypnw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2irdhvxlh.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hazsbjqc.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cltpnjsq.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jxezadmq.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbpxwya.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2egcxwpwu.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrfyhxa.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbnsaka.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2cecuegih.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfebfnb.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgocergq.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2gtaanovg.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2hrsnzmdh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2iderkgzk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2scgtowpf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2baqcgviu.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhtewjj.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jvsvqgde.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfghwjks.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2iujcztqf.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdapozq.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cduemavi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hrnhcnzl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mchsvvvk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2nifiuopv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdwguou.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2zclujyph.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggcsoyau.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2irxvlogr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtytzgwt.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wdqenyej.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkjgwyp.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2aecgvyfm.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2szuucgdo.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2snslmwba.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2pixppbcw.html


<!-- 参考信息 -->