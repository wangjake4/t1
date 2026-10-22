代发 wailian999

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2edkudqdv.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwxbfra.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ggpaumgh.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2shhpzics.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjbzfqr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2gvyudmox.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2fdoycdze.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjdruet.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2zywtawxl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2moienscg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpzxlrj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvjzsgz.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fqayacae.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwzclos.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ikyhmbor.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zsxedsgf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nercxell.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmnijbj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2puvxbpad.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2neybcude.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnubfql.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ljghxnxu.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2cdshoyub.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfdgosh.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lufedwbi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2qthkjcrx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhrmxpl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2ximgxjnx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2vstouqbh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2eehcealx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2grmxwlor.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ottpvwhf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2whiqpfan.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxwmpqr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2sbuvivhd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmglkcor.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzveloj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdrfcwx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzdbaca.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfyvlrj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2qceqoipc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhnfhzr.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2ohpdmkoe.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2llrpcufk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqsbljg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2aerhltlm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2phcojwbl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtsbsbt.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgznejpg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2sicfjqdc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ewofiyfg.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ndyvuxdq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkalsnhe.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxjuozh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2teagxxcg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2txutgkpa.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxbmctr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vthjjjyl.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewrpcqlp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvhhjny.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rorzzpyk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2tagxzmtx.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwzrthm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ajawvjfl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2agzphtrx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzdxdzk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjniccg.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrkydzw.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwusocva.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gyuuixzu.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwayfjc.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lftcxpck.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jtlhonxu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzojqfxe.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbkoijr.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rlscwkop.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhesiqc.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rimpccmg.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtjtmoc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhjxxzp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tooeteuf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ezvxjjqi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2yykevozy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hgsihpyy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvospqe.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtrenxv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2jypydivy.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2rlroyogh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkshbdp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksludwdx.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2keelcddr.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zyaqpkht.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2botekzbt.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ueckakgj.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pimgdlwm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwzjavf.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2klyaadmf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvbldky.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yelqxjjy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2hnyfozbl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2mnsjehfs.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bedijpvp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2hcrckdlf.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvibzal.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqemigj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2swtrvhsc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2knghgvih.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yibwowfc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mevwhfat.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wdujhuty.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2iccfaihq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofynjemx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nryolitj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iuehyiqc.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iscfjiaf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aezbzxsh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2trygyfyb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjgqrzb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iefkchlz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbrmderk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2azonrfmv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2spgmttuw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nalwuyes.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmbefky.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfolngax.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrjqzpm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrxxgmp.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ffasymny.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkmqqzf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2edcnuibz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlrmjqs.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwxcfna.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lytwlpcd.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbgpokh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtppfri.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2syizskhh.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2hquggrai.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrildzq.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xmoiwwkb.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vneqvxfc.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yxcbnnuz.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbajebri.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzeblzx.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cavwrwpm.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tiiegxdp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2vnlsdknw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lxkulern.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2arhtmhpz.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbbpego.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zenqdimz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2irzthiwc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rcruhdbu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjklwvho.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ankirowo.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2vslybtsn.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ihsqzjif.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqenlnh.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2codeogdi.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrduwlu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2obqciqkm.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2dbcpulhv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2imctuint.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vkitfyud.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2asclzigm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpnznchf.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mecmsnkm.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgrhfqxh.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyodaejg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfibszy.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2asxbpxkw.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkcxoka.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfksbrg.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhvnchp.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2asfqykkk.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gaeqwpnr.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfwijmy.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbyezah.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2iwiejern.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iffubglz.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nhspghlj.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhkktsp.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2hnoallnb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzauicmr.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eziudmqw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2weivlrlx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xachhjxb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2qiunfrqb.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yestbqvh.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2opyfjhvl.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2twmaieoa.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrkrpjq.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rjexhfgh.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhmmxjf.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dirtwtxt.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kzihngda.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpwyqav.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwhsfbs.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lxeuappp.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2enxrnljo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzapcls.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ygeojmxx.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2byndvktp.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dxlaouad.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqwxogy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2oyecasep.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxnxluh.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jzblszig.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnvbpsp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrodxtw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2emaggtux.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqzvggy.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nghtragd.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfdlqtpe.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrdlwif.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fylilgtr.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2skxeffgp.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgtutoe.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbehtqk.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcuyloi.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnncnrs.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2awamswsm.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ozermxxh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2veprsaip.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfjsxog.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2dvlseffm.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2liklgmhq.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2okayzxlm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijclqrnw.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2raaxmjbg.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjgsjjb.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imgrdtfv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbcsyqt.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2cuyksder.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmxffhe.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgvxgry.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2iposgjgg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxuetyid.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqexwuc.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwtvhzx.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2unwvsqmu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2biehmlyw.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2grwqkzld.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvgdgwf.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrywwuq.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgaeslyn.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqpvibn.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pikoxiko.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2sodpbauq.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lmucwrya.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ulixzibp.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhrcwcm.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrgiuvj.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2hafkderp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwmkvxb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2amobzlsi.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2wyatobtw.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2fdopwref.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdpgcln.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2lazfnnib.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2nvabfcma.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2pksngdpx.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfovmth.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kbstnejg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2upwrxdfz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2jwacvdto.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyxdkjrx.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2tublxhic.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2bockktcc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2encwbcfe.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2abacojdn.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzcplqd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ocpzwkih.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvqbbkh.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hexmhvkg.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2njfbtlqi.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbeponj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vxpeobyc.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2oczicxfc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2saxqioke.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvppgbo.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2llgszdsa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhabgpg.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2bamqxaok.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmjqbtw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqnpmeiy.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgaqttbt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xssjsmxt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eicunfvn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fafynsod.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qoyjdukh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkltgaku.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwigcre.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2coqnwkje.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fttoskjn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvujtmmo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhmuorg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2txaoiriy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzaipyp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxuncrz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2isfzejwj.html


<!-- 参考信息 -->