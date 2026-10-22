代发 wailian999

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xiybfdxg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhgbwaam.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzknadjw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wypnlfay.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlfciyk.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2sfikojgn.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2gnreutwy.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2anqzjsdg.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2azgpsajw.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2dshpcwke.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xljqcsgx.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmjzphq.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2prsbmzet.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwfhzgp.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkkovyi.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2wbvedhbw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbkomfw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhcfvyx.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2seaymdoi.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vwsskjev.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wnirttzm.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2ubuxefdx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kvpjgpuc.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2whvesnxn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2umnzvuaw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ozngdkoa.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlqudjs.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2btmngmqh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfgbypa.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2sdesbdey.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qcoaseyu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2otkctnmy.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bufiahjn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxfqura.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgbdfub.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ozfxibgs.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwvxaeo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2tcdyvsas.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2djjeixnc.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ljnzzubt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hrnmlseu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mfallflw.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2spzjpvhc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cadcvhxt.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gmudjrrn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhtrlte.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2haicxpif.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2vrsfhsxh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2pizxvkxc.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwfmgrk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnwcojd.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eagyplsa.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fttrnjnz.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbqsojc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxzbspz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqdlrdh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqfxhfe.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ytelfzvm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrqreom.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjcvqtv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuupbofa.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwiiwaxp.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgraxfc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqhumyl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2hzrqtnfy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtweqvxm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgqvqmm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2yooarbrn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkavbgek.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdnetol.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2eqywltff.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qswvjwsw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqxzrlef.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2airfzjex.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2acuymgsf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwivskye.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukstbdan.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgzchrq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2oykjtqua.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2oqoztrga.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2egvdpyxk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzzrlbt.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmwezfw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wreetiaq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjgkmkn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmudlzq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2zncqmloi.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmczxru.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdcpsav.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkntgyu.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqaybel.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2igbbmduk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dapamjxb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fadwxbfs.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xqqhqekb.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aoojyrco.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxodmouv.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmvitnt.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ksosgozs.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgsfmgb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qefrslpd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2srdswjgs.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbwwwue.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xbtiknqr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjbzeff.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwmfiby.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlcpzkp.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qtzprwgl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2efkrwgmk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqaxlhy.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmwotan.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jezleipg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqiinit.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwuyadjk.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2cisylmjy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2grbsehus.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2zvyppjqk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oyexleul.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2osaulfmn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrvmmjh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2yklzfert.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2eejvtydf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqhpgcu.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxauqhj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2rszlrcwl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwotimx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2csvquimz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxpezjz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwmigsx.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2krobvque.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2wadhhhek.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhuabgew.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xeaujuyr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yeokvveu.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwaynrq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbjqujz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxpvpbn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnsikga.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2enxnqnqd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbnnlxe.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2grybthps.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjxaqwk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdmrvgj.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2dwugsszr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2duyccavo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2dzafuhaq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2szdouchc.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2edishcas.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdxpxbf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2isqoqkym.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2eyybkbvq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2orozxszs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jjovqkfg.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjbsaxz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2srqbybpy.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvfbrhp.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbfuxrz.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nzuhrfko.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqbdopp.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tutrdpxs.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bneubrls.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbkwduiz.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qucrqhxw.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgsqaxo.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hccxjogo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2elxowiov.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kfuxvoiy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdydwzh.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhylfpe.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcmpztw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2asjszgup.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kibhixeq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmnbkik.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kfiaevhc.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2gcwcebkw.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwmamli.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zwquonxj.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2boaqcxvx.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2exrftoyp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2tuivpfom.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2zhkctzyl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jedilrsr.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xreeubej.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2flqepqux.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgamqvb.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukquggdj.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzxzqbb.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfwuelz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtshoec.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mlkbqivl.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2srumovbf.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhnpusb.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtqlaou.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkhensv.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2amekdqro.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbrsapn.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kggjrtjt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhxbksv.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwilukx.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgboquh.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jrjzuxdv.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2bztscott.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfinlnt.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtysmib.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgpyvgr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fojhprqa.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2bprtpdcu.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sptkstef.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrhmqqv.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvlhyni.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmtqjmh.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2eoistuiu.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2odbwqhil.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2surdpiaa.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxnhebx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cbecbghx.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwppgvx.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mfkokdij.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dfofhxap.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2rzevncrf.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhozpar.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2prtrjzkp.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqqlear.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tubisiym.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrkuqhq.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rkuqkzfk.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzuckpl.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2kqegahkx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2cqeouztz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypbrjgbk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2rzyqdnog.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eglblwts.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvayfqoa.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyezqmuk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgoxpff.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgzxefaa.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2pinwmcsm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ivubvsto.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvnxllq.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqgnzcr.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2bxscckvn.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2bxcbjygi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2sajmtfxu.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2lznvqhlq.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2whuhxfvv.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvfytdz.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2blhqtcit.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2puttkiqw.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqweseli.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfcrrbw.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzsyqcto.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2smwpbeaj.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2wrpybdeo.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkhfjey.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkwvfuo.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdqlnif.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2symoosnm.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxludeft.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2csrovdbb.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfyadsj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgirqfke.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hvokfsjz.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pshxmhyd.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2plpdndlm.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2auleytkx.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnnryzo.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrdmzos.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgkkuar.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvpzsjh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2imvdkvyd.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbwkjoh.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2kntltwad.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2egtwlynf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrqsrhp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjzlywm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqrlkll.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzbceym.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pogiezvc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpclldik.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2skdzlyrt.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ncedgnfy.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqubaji.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kupxiacw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqldqzj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2qaqnsdxk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pirxargn.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhfswhe.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuirtzkg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2xqebkzla.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwypcsb.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cwzgydrm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2baghjwhg.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2heegyjwt.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzginesk.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2egdxkvie.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjqpuyi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvkxrfz.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2cpaivhgb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzmsmya.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ibopfbxy.html


<!-- 参考信息 -->