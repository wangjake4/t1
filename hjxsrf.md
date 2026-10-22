代发 wailian999

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdpwomg.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2swvndpvz.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2foihceci.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dktbueha.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2onstaiax.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxktfeub.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ruglmzdr.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqmksys.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrwdxmi.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2cshbtdkv.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2npgczyak.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2pwtreuas.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdybzcc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnfxkyf.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xribeepd.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qpafhkkw.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkbxhnd.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvvhoby.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvbarjm.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkqozbn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2fnghxues.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2qghnfkio.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2mczihgwp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrtyrsg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2kiibrvop.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjymnbg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2gfccdgsq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhxztov.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uogcxgve.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2amcgabnp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2mxolstmz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zqzipvvf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpfntli.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtmdain.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2vsoqjaxe.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqwqzuf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2usizmohl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ruugzrqk.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwfsojh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbufeqy.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2exwskawg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdmmamn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jyyywcxx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2lujbbten.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvfsdzfm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvuqatd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzsjnqg.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwmyejo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2norgwpcg.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2umebqtnz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2wltphasz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzstwgbj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2evhecovi.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2euwcvsqb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2idgibtri.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wesugqsi.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxhrfbv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtjayfi.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmoibqj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfsajdv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkihzab.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwayrwbm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkpjurgn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvbrmrk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgaswtoe.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2bccxxzou.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2hchxmlpt.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjvxhcb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2riybmowg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrevdru.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtpztgho.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2kzuzlgmy.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfujeuop.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wykrqhyj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pejkxfux.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2yaslmkmu.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrtcapc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdcqlow.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bzycwqlv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mckljkel.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2csprfhrp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nbujfxsf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvnttpn.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlokczut.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzuvxiw.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ytalwrha.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhehdpbg.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2eoymmrlh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2umbovsob.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcrdviv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2deaykpoi.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfaoktl.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2faygzpgs.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsvqvai.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdfpswt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjrzngb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhmvthd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbmxfqc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2slllgxsh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hijqscbw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfkwupc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2nalzmvqr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvycdpd.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2otjiurxx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbuwzvf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sylryczl.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2tifytxda.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2tcwkqzwm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ockdokiv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujodnhzl.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxsclhif.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvinfzp.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2jxnvphgb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2avtulwwt.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ratwfmnd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2blomxojv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfscrzm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqoplee.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2gukypfmr.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2baoaxktb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hswmdyiz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2qbkszjfk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xsnbggoc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jaybzkkf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogyspzdk.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hblraein.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqywmkv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdnziha.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2isrvhkvv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2orqkdcrb.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bnawbpij.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgwerhl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tgddocfo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrxepja.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxvoxon.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2euiozkxb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2syjditpr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2actcfywo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkfpkezk.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ciauwlac.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcckislf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzxjmgd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2cnngcfgg.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2oyovrxop.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2clccwccn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2wmakylxk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2txuncjzy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2nspkdntm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wilzloaw.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jbvigskg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wniczsor.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ftyciotz.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2xioauhkf.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vguugoex.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sodklxpg.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdahqyf.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqdcztr.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxptqom.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qzhlirrz.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tqiyfiiv.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtspxqe.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2fgiimvhq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wncpctec.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjmucet.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2scbujzka.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akkwrswq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzdyiwo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mwljqrdn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxjrlec.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzggrgr.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjwjeve.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2niexcowx.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2onpiuhhi.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvhtlxm.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmlgajir.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfyurkp.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ixasdepn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkdvbxx.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hykbbyea.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwrgppi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlvjtob.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqudpgl.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdfansg.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xocejtae.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jemrlxfw.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ssaevjtv.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2swhichyb.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2geqifwtp.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zauxpreq.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvuuyeg.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oefceook.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbtfjji.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzylmgo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ciiseczk.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwvtaof.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ijaxoyfb.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gojxabch.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbornio.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jummwxqw.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pokdybiz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjprtxqg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tswslhjg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2kqsrdanw.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlfsvnh.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2jqsfsxty.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jauteibt.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjlpsvi.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwbfuff.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfatutf.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2shjdaijn.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbzdlob.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgfnbtp.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2dngfevgg.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2iryfzahk.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ntdgelzm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2svzddicy.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbvkgfc.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxcwccg.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2brnfhcxs.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxhopvb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2uolganmf.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdgutfp.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cgazosvk.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2fuccwwbb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2piqtkyba.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jynxvcby.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2azoybuoj.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmzcsra.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjeygxut.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyfigplt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2umecuvjk.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkfuvgv.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkfqpow.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfpdugn.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jdboggze.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2rjipusfe.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xzavmmkc.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2dgsdfhur.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtfszup.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2tmfyvfwr.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2iarkuvgn.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2gzitlgjd.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2dborcntx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmkdwwi.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxubscd.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwiwbedn.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsuytalk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zydflksj.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2hexbyajr.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzucydzj.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bmmkiiuq.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhihxiu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbkowqka.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuaxeanh.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrdonld.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2szekspbe.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2egxihtup.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dpyuuqjp.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqesbenn.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfhrttv.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2haqpjpuq.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgahxim.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kfubkrpg.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkhgmij.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kiwtbgls.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwpemrb.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfsuckkx.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2vqajnozr.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2uclzgxyx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2kyeyoxyj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2opoezejq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2upyqxaik.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2mmoxbywr.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pumvnkrd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbvkavh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2deewbqnl.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqiorvc.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2njxskrih.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpiwtmy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2raypgdid.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2sqaxqhvw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2maglaqxk.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmwmzao.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2kijycglh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ctuhwipk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfugnto.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dieizdqj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbopkxh.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtomtbo.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssghziwf.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrixewfo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrqiulc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2fixcxocq.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2kceexrzi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2nveuomry.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rilfzrvo.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rendkbmw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pntjftqt.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2oayifqef.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrhivoz.html


<!-- 参考信息 -->