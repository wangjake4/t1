代发 wailian999

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnvmzzq.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2nftwcmdk.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2lfcesunv.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2zddeucaj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwahdwn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjsxhhw.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmxdkmp.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjcpwxa.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2amurgrjw.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2ghbvnrow.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kccaejdn.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkesyya.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2jdoxgfuu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2rleoinjw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2rkcicezd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ahkndpat.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvoczak.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2jqrrnhwv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2okcsjssh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxmlzpi.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hgczqzfa.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2txfjtjfg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2dvytrypw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqsqcle.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2omkajiec.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2mchrzesm.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdblluu.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzqujhr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2mbhhltoy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rphdbiws.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxayjqy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aftbykyq.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oomzegai.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2fbskjkgx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bmglacpw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2ckuqmmqy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfhxryf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rurdlijd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2cxodtmhb.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fwfviyww.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qhtgmpxr.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hfijilci.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2uukrkkcl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdxttix.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbgogwl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2havqxjxv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2iiywktbf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzhsszy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2kodznjmq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eufrrbcx.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhvwaab.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxylhek.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhphyrz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbnhhqa.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqssrtzb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqritpw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfthafza.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2qylffnzp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgobtzz.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvabkkf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2czhjhlqv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2yghqoter.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogplxtio.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbjdpxk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvlhsca.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgxlleo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxlofwk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ixaqwiwf.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wcoewose.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2geblnhyd.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2omecznet.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2axpuqxeb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmdeelb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ecfhsgoi.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmccotcs.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkadwohv.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojapclfm.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2veovdtov.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnfzmzc.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvrfjuv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2csjvapdr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tydquwje.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jwefgxqn.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxknxft.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xonhkdcd.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwpncun.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgpfaru.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2iquukfwv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrytkwjp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2hvohknyi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2utwtacin.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lrmucnus.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzyelcoy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkfxogk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjyrpyu.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2swqrprzp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2phzqayzz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmpqurh.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjnhpblv.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwriygvc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksonggmo.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2oowopzto.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2oahvhfay.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvlmoqh.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2uslmcgok.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rphsiyue.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbbumwi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2whacrsqr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ycnnhwwy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mhiwoufo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjdpsbz.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdffrsek.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2addjyixu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2yffcwwqi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2txouetod.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvrixis.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yaawiwef.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pktfvcdh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnvcjcd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2avgetkjp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ercqvxhu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ajydmbhq.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2opbnrrmm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxmpvlj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jltfyfzf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmysuofx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlegnues.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucptefyn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2wifsthaa.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gitwsyaw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctulwinm.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2jfanmahb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfcwbka.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2dtoqlkcd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbrtmuv.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhuwssx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2onnrgahb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2dikfzehz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjhrslx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2osxyyndm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mgwakoyy.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2aesgxmcp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2liquuxkm.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhssqmy.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbjevyd.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhhopjo.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cintonrk.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltolexur.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqcbbcy.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsyuqmkh.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tpsoccid.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cscanzxk.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2usjfnngw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2fexowgkv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbxotmg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwydcjd.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgsquin.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgllbxy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2niudzpdo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ukyegsqg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yugsswlr.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xjokqqdl.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2dvijhykm.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fmdptudf.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2acerwsqo.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhjkcxm.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2euxconya.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2etodqphu.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2lgluakhs.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2eaixjnvx.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxoxswl.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnqrmiq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yihdzdxw.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2okpqpzcp.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xolvkhym.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqtcprf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqlorow.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lbsmhzac.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwveooy.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2uasospyd.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2lvldptqc.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lgcuchri.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvnmzzv.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fccruaij.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwxikha.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmjcrlm.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yyijohvn.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxxtyly.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2awpoglkk.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmchxlf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2laybgiua.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnrflxw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjstqig.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmwhgza.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2zyeljoxa.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2elawotth.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhsrxfo.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rqcvrkhb.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2obhvkwys.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2eedqlbkk.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmubonq.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2klltsouv.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2erjiycvt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqhvurj.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2hitlicyz.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2utryhksk.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lxltalcz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvbfonw.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ailnyvyy.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvnqzsk.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2orklyswe.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkowneb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdgcxen.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2smsrhjgi.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2whkknqql.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2albhrxer.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2psnwhjwe.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zraknije.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2yeuwztmz.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzimzjjx.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjggorg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhgfhtq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkiqzhj.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgblyklm.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2mpggzomx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmnylvc.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrzgwpx.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdckpky.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2dxaqycsd.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2fexhkqld.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2smubzkhn.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbsshrj.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ixirarhx.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxvydky.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxxfrqm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2swcgiwpn.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aavnicav.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtrgovm.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpnjodfk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ourkwffk.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2yomwzsfm.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzymtuuz.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zinkqpkv.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgqrtwz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsufzads.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdonneu.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdpilvs.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdbsovk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvtycug.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nhppvqog.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhcmloh.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iwkitdxy.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2mawzgdcs.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzzyhql.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bmllvwsr.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vlaxtofd.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ksoxlcff.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2yywllgpx.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2acivfkay.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2yqaactdb.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2giveeesq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2pylqxojj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2xytimyon.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2swwoeeuk.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2keyggfkb.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yrppxvcr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2skabrxkx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2jfsuckmf.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgjlybh.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jppcpbsz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmtaivo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iekntmlv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2bqixjuuo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2aslzqhom.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2epitfyvr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqfpeip.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfckpjj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cihwrafl.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ljuyfqha.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2fggejvxp.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2nabimity.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2neoomytt.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrayegs.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmlmowj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvmpxju.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2luyewlbx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtthqbp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgdelhc.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2elrzmiiy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kjkxrsyb.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfcdlpq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqoikrzi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpecmfh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2huzqlcyl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vblithhn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkacydzi.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2efgfpsnw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mdynexah.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwledikm.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2eeysobcq.html


<!-- 参考信息 -->