代发 wailian999

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwiecuyb.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsgjcac.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zswtyayu.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpsnpiog.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2nqutxhbh.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2kthbcbnw.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2fjypmfbq.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxozdgi.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqihhid.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mffmripw.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xchaqmdf.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfxalpk.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wwixmjqc.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2ruirfzps.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2acjdzzia.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2bofgwtby.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2lethgqia.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2vffgmobq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzzdfod.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2dxllrtxo.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnrquqv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2qdelxagk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2bzihqqsi.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2jiyrmyhi.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lmakziod.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tulbolrn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwerjoa.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zmaelenl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lgahonxv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmkjmon.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2gjsxdths.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvzfzsm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2znzvzvdz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgnhrqd.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qdrosmxg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2knwcfrkm.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdxlcvu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2yxczrvlg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wxigkcri.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2luaoxcuv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlnoazpq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qigfezaz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2ertipygo.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2svalqtob.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pawphzku.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wipzuqmx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2lcaajbqr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhkqtbjv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jxydxled.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xooutomq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvhmrix.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sftcmkjc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdyzrvz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ioeckbqt.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmlmuun.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2jutgqcim.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2zrzhsvyb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2yumocrro.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2dgunrfam.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnemzht.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbvwlfe.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2fakrslkn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2trilcsse.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkmapmh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2kiwqxuxd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2arysqlcg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfeydyx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2kijjqlbo.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqlmnxn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwrywrm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dalceppo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2aoquzzgi.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2upnkkgjp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzeizjw.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uvphlkxn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2itwysyqh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oigpgibp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2otnbhixw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2qisfatfo.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2akwafazy.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2scqgtlue.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mlkzyktd.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dbipjccy.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvetzha.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrcmzcg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aodlcmsr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2quhspifg.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2irlsjnvb.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2faxmotzc.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2igxeziay.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2pjrwnhat.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwjgjus.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcorqzf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2sgukoqlx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2tjacgcwu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2owpkdxnd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2mohutgsp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2abzttvyh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfiswty.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmbmngm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqtgzyo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqebeykt.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ayictozv.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwzhmfq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ooeexzuc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrgdlpj.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bcpkezki.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlyvutkp.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2wljstbsy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnuunaw.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwnrxds.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ncsttzer.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnmitmg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2urtnisrv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvhcrfv.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwemjbwy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxffyvy.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2kkhisdwa.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2egvebsfk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2srewksnq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwotbqbs.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ouylpmga.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgnuabn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zvuzhkwt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2htygkulz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cymnpfmb.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2isygafhr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wilhktsi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgdcivt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxwezbv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2evhqvgrh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtvpxyo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2twzlpkkh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjavwkdk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfpzoam.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfwmdfw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxeiqsly.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2dzlwjkhg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2omzzpdfs.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2bvcaqlon.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2aiatwxur.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwhxmsz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdkbcbe.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwkhwwj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vgrhkaqg.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2vfakaafr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uarvocag.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvwchco.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdmcpeu.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2epcmjefm.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eqlzjifs.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2opbhgvkq.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtqgrsh.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2eflwndcj.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqxflog.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2trrfbjfw.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vgrahems.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2yuifopjm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dajawoio.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lufkussh.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2scmzcsrz.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfrhydc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwnbjugf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mykjayna.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwcygaz.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2iecaxfnj.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkaltwe.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2sydjriuf.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbheybv.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qclawulu.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmpwkhdq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2pyxsxtww.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkpsvpx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nzybygdx.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxzcezk.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ufgzwjcg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bayngmex.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smynxyol.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rynjnmpp.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvyxfxze.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqaiztwl.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2khawddeq.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhiqffth.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2tpeonsnh.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvyrmqq.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fumesepj.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2saiqiywx.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xmfdsudf.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2knkcqidj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkefuxe.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dmokwpbx.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcnbudh.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dknfquan.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2fcnujxwp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfziyqhg.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bghzuoyn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkywkirr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkjdany.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2bouocort.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2akxvxllw.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2tsaeoqqf.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fuowkfsr.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2crcqslse.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pprsdcrc.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhnyatp.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmyudiu.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrtigsq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fftbyofn.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2afcucqlz.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2oqlrwzlf.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2amuklwbh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2febotfdj.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wpphokqi.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfdxqgt.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wtubodov.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ellwkzop.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtilaat.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aollunds.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2furxpisc.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxwmijz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgyykki.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfiqaeyo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpvpaqx.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zatrcsrk.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwarxfzx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwehtmzr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpfprnv.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpowboop.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2sbiaaezg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxccenn.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2cqffnqyf.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2htxnhggd.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hctewiod.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkaghbe.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2vtsejzha.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2zmfytscc.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfcfmtb.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2yaybvrfe.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2gitypoit.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jffvlijd.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgkcfzjh.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qecfpyuv.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzoylkr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2btxtwhia.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwgekbh.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhjkhuz.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgxkbva.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbuwrmh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbkjeku.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utykkihd.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2herdonvr.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkllixfe.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpjifjpp.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fuomhqeb.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnuyhqlh.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fpicsiwk.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2iblcjwwo.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2myrfmqle.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pfpqogsl.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2leeosqjg.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2znkhhanf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2btljmery.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgpwarra.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2agqigpbe.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2moouhyup.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2engplwos.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2jsevpynl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2wutlllse.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2aapkoeqh.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ecwaldnh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbrwvzxa.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2jsbcbzij.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrsmnhu.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lezjgkjr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2oklcbtal.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xckamphc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2uorpbtvk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbolwtt.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2grdnlryw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2efxphgzv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2jcchyuje.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eynlrxfw.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xguwtopg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2wurqdrig.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2whttiipl.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnhrkbm.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfgjcej.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfbfezy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvpjuqh.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ovakxici.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2qrebuuzc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2epiowpzs.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2itsxqhwl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jpzrtvvh.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwnpsts.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbpevxh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohucpvkh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqauvbv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpjlxgz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2diaqrhek.html


<!-- 参考信息 -->