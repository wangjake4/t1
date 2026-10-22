代发 wailian999

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwauqkk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwxwkrp.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oubapzuk.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yvucukwu.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wzyhryus.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2hwaiqdas.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ekaowovg.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrwuuwo.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2twdwcoev.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrxlvko.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2aydgfzzg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmibgdj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwypxfu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbosdrd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2czmcclvz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzjocon.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uigoseap.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynurqvof.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqtqlpl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmmrhrr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwqkyet.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2wcsbcdgn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2vowvpqmk.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkoywrt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2elatbvnf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iajadwni.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2pojhhhsc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqlkxpw.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjpegbx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2foxmipxe.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgodfwz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqxnodq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2lplekcrg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ewchtmvy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtsrmvl.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2waszjjwh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdousli.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ttomliof.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2wczfvlrh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dffipwjw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2npycdyew.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ueixbsvx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2wligghou.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2glzpsvsx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjbcnlkp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yaoxlynv.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2jafhswdg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhpnswl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jocmsabx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhplxdxt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2wvcipyfd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2erjwzuld.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2erbhxoje.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfkhvjf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2horkixvu.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjbbsmy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qntscaph.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfiijwjy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2salwjgot.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2rauepppe.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvwjzss.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qckehbst.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fclggqho.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2jopwiygk.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vulajuzp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkbflwc.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zsewkjwj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfnwdkq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iblerzdd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zqyrziuc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxbnopg.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gclswtzb.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2reclyxqa.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbupxgu.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2saxqqdrq.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kwsngfwd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jahdrhke.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjasoglr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzpksdc.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2knmuivxb.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmpnpke.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2krrkhtus.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2otokqmbg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfpuyht.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnhuwqx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2omftktjz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2qircezda.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2esdyzryd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2meigprmb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2guugmtko.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2isghlgsh.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2oibohgnj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2aawruftq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwpncxm.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2tteltylc.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lciugtas.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2inapcwkx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgyoqrv.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hoirwzot.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqkfdpe.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2xudnzyde.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzdzmdm.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cvtibokl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2cinuhpzt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhjqvze.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vhehzgeb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2spwzvzfl.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qiimwziv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2tstwfnva.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2odbmmspu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqszjlm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nkycxhiq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqmxjcj.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rlldjmyd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2hahyrblb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nwklkixh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcmmcdt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ictlgorx.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ritbzpql.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qztzdrry.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ybxpfaay.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cobqjnwf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bajvxghm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2piwoifys.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpbjekv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzohcmdi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqaouyfh.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2tqoxyntz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipcydpyx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2hghhslbb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqsgynu.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2rhiuvkwi.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2axjllrjd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmwyliq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2vkgnqofh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqxxlbd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxkyahz.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2cphajvfm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2blniklme.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2obaeblyy.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2hawqliuv.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpgqgxe.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwxbucs.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuajoaab.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eaufvrcq.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2uefofwdu.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fwfcpcrn.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdpibfh.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ursqhpun.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwtmnnc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ivaqusss.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmaujtl.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pabbmqpx.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkybxgl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdsxfyha.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kkoetvfz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2keftatdd.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qdttfyue.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2seltzpbu.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kpomfoaw.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrlxoxy.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fdresbyz.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2alvxfjmc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxamsfj.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2unnnnhvc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vusfhjiu.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ihjultpc.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2coopzndl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcsojnam.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2etlepoeb.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgduswml.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuyncgmh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2laldcbzl.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pkrehxuy.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbrdcfi.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2essxrpcj.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2oydqwulq.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhdonfm.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxexqha.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2icqkalxe.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwymdnx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2vwozpoci.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aiarrpln.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgkghua.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2oblmvvys.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhdtuck.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkiaisly.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkonizou.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2elmbqnnc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txyxenhj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2kwlfgkzy.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dznukytk.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrrtzfc.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjjnllp.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrkrzzw.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2flebdazt.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpaepwj.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cilmpbif.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2clfeuncg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hrezxumd.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrlhibr.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wesfjejr.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2oimfaekx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2fonrkiod.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjifpwi.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqqnhnw.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfgsttp.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmmwqxj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2dpjdtkbd.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2geuqjlwq.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbbffdo.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvdhzmu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2gthycvof.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hygcubiz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2njgfxiyk.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lznglfpm.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjppjnf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjtfzcy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bilfmosd.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wazshuii.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2fvefjxrx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjwhimk.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2etqceome.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2cckdnyrm.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxuuhnl.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ughpaqry.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2hzamifhs.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2cavmqras.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjumvdo.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxukdps.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2edvntirq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryogdddl.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rycwfdrw.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kadmjobi.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxydohsj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnytnveg.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjfkbhn.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xelmfsie.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wknmqjil.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2gnzjjyhu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ildxgvrd.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbfrvwji.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2prtfucah.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bixcklwu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2aashrkec.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2etfoxnqp.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2iemxegmr.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrptraz.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmfoqta.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mrpbmfue.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzmpnby.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qexjsrhk.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhdhqph.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qnetkpqf.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvdyjfp.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2zxcqyaqx.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2nvyooviw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2bigtkhpj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbgfeho.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkvdiwg.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2snqkblnr.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2acluwwpm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmnrwmnm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2boioeiwb.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzxxefr.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lemljekj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bpusjqpo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhopvrk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2msdsvwhd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmaqgny.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfwprgd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbkxnwiw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2czgbtmlv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yptflssf.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fwujebgj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlgcigb.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzhxquqk.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2enxacgqs.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fideltmz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjeyjoc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2mehexgvr.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2nekqaoyh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlusala.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2huolpbea.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bwmnwvov.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfwinwt.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2fiosreoz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkeigqzq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dogyxkjj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fftvuzgz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ossddpvi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdzhggl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2uaujfioa.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yggnuduq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqaygzk.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2hecmswfi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2lflmtmqs.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2abdbeycq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjnicgz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2otxugeno.html


<!-- 参考信息 -->