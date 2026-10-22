代发 wailian999

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2kxndbuwv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2qizrvxxw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqzmkri.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2gsekkrle.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtgokxx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqckxgd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2dlupyscx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kitxasak.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ebonvfbm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2cxpmpixv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2zvuyqxmn.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jvojqhxt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2altkrhrc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2srtdsqby.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhgcoem.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2axhwjppi.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eipjzzcb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrxcnzb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2liulhcdb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2fawdnchq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2gsimsool.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjpoxjx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2ojowyrtd.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2enopdjno.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2twsnmcup.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fagyigpu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2tprdvaxq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slrehuoy.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwknfro.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xxljvhax.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmendqm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkgdewt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2owwuvajk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mttfvfmz.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2oshzvkgk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2umasslli.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2zifsginr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2slbooxqi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqpjgca.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2cixagrno.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqskaig.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvjusiu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2umxfzgnv.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgrrval.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgivrgfg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqtecbl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlicgakd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsfkpac.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofyafmwd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2kywojvlf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpuqeppo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2qelhvvjg.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yydkwzxa.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhjojam.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qeyxynnj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqoboctc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pulkddgu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kfyyclsk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2ripitgly.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrvdgyq.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbvutcy.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgmoein.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqlwijn.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jktgxmpu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdnaaro.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2itxevgky.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jnloxahk.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iavfndab.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhrfvupr.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ahuthapy.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2zokflcdk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2borlenhr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtlwasx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpdspmy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2szxgkbna.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrkyeor.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpzijdx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2pnttxprs.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2rgezlrkn.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hombyqpc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtqoemed.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2saiqbbcu.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pyseqgre.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxmkywfa.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxteydjg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgiqymdh.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlaiirql.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dalqixqw.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2goyetydw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pyzvjzxk.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vxosdwlt.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjvbwtn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxpjfcz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2oblsketi.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2aoeytrbx.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgebywj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2pumoyfde.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2gpkposzz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2znzwhnta.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rltbqqbq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ukygmmto.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvpkbso.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwqddbb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2voaenocm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iljgyckh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqyxceu.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xltyuyrg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2brmjslnt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sglvegof.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uizciydo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2keqgomvj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhkrlmw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmaklvk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrnxfgh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryfetmqj.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjzheqw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdwpsgq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2mqceqfxl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2bjblniwo.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ktvvmwla.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2zletdvdf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2obxliszw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2mfsmepdo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2rldkhejh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2maxogcfi.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2zkuslete.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ucpdkgus.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxkwzhk.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zcamktim.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yokgyhnk.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2emohbwrp.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwotcur.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2momddpnk.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqgczpn.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ohinzgpr.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2amcajczy.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vkclppob.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2redxyxtt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xsaelroj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2blwystai.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmwbsjq.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2scltqbvt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxzuyrw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kaimmlrj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyiwwzga.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzphtjr.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2snshjqxg.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dxaphdvk.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2arixsgbd.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqocvsc.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibctvkmw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2kxcddkdw.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2sbjgdbks.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nydqpvrj.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzahotd.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgicgha.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvinlrii.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbsguiz.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlfaaama.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpibgcod.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehyfwsca.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnyuudo.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvgyeetd.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2dabbzpnf.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2futyspqc.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2onshgoaf.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ugelggjl.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cirzqoze.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oksibbci.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2msxawjqo.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2woftasug.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2umljssot.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gaoveeav.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvzdnlu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgnmgtr.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuncnqvt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oagzyklm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxuopmsd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ssapyclm.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbxhcwt.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2jncfehpu.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ckuttred.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjrrnyi.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2puzhadzq.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tznryztb.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzpjozk.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rghzvnzq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqropbr.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2jviizukt.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2amarxaga.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cezoicge.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2nwszvuyg.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2raxgzsgb.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vaaseukd.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cphnphaw.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqlpaxg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2hfpajtnn.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sltizeug.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2btakwtkq.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2grvwhiug.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ndlftxql.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsfovxrn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2pawfvuvr.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mknposfx.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aaeyxhpu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxdpkhi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2feiviihs.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjahnlfj.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxtpdmf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2phbjhxrx.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgmvcqo.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2glgnhber.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jiiaiyvy.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2znqkfyjs.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2buwjhwnv.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ggoddstq.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2qkmpggxr.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2oijrupcf.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2innwdknt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgvzjee.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lukraztv.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygalouij.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2opmqfezg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2gecxkjst.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmkgjxh.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdcbjpr.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfzxkhs.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvgwtxs.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgedjle.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzspyjkh.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2deiqbyso.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzdojka.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujsuzmlp.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jeuniqtr.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmekqtd.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eykkejnb.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtxzidf.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bshzipce.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrbosyz.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjygzol.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2popupzyr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2riosacbu.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2isduaimm.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2sthiwtiu.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxoiifa.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqdohcl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvhlcdn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2hhzqniln.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2onsgbniw.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iylwzhbn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzojdyi.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2oaplhvjh.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhorkunm.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gyudnzaq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gdadbven.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iygwrydx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2hguzuzra.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpcnyed.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcwbcuob.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmdwwpy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2pnonufon.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qedckkmt.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2aiecltqs.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvsaokq.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnummobb.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2laeciltm.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbgrwmt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbevqqm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2psdftzmr.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2uecpcxtz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2votmkfvi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwdifly.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kmtptyfz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvuynjx.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2vtcoichk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbjgwhb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmsfkis.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnnhosvd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfkqhmz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcoyvatg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2savgdgka.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gxajnyet.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2runsizlo.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2zribgxug.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2wbsevszp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvmopvx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtfiobf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkglhopc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkrzgogg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmsbkyk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2olmrowfq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtgudkm.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlqubtq.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2yodcxkma.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2arkaklds.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2cueazlaq.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2doerjmds.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2yrhqooiy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxfkceu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2yhhwnvpz.html


<!-- 参考信息 -->