代发 wailian999

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvhaido.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwopezm.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgtyxmm.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xfppzlmq.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tdamyyka.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2inemkdpn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jojgyqfe.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnvuorn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2vknbfbab.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxlxtix.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxthlqr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2vtokvnks.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2pubesxme.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2phhhdyyp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2xhaiplxn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqvdnvh.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rovhyzes.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2knftpyvt.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkabhob.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ixyexazm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfymkyi.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2flmrsvln.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpcbpps.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtvxyub.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2cgihzlvn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvqhhss.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2blrnmglo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2afmrjfwc.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2luurrxaz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2tzsnwekp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2imovoqem.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfffosv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvpounlw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2buvnldck.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpifrwy.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gsacyyre.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2oznjiwbe.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xusglfjm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkalpcp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrackzc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dlumrwhu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2efizegxo.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2dayxkllx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2alyuebfi.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpnfrvmf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrkqosct.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2osyiotcw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2dbiscmhj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkkhmsp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2stvlopsp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2owlkliul.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2elnqjjhx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2suwdrggw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvfdbgj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2zcizwzke.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmtdjui.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2hvkqgvvw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2aepjbqyv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2bormndex.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhodbrpq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvefuvrv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbgueus.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2freehwlh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpcprqh.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvshhrm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2wufjcner.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dmovxkxa.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfaazcxn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkpzqsc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2irvxwage.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2naixwipz.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nklzucjc.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lylfqjrn.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dtyisbjk.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2brvmkhgv.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdffbbk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmxvnhz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ithouujm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfwjzhl.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqlijbzj.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dncwkqfz.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fsibgnqb.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2akaweqmb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2womjcemh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjcbvvzd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2kzepkbvm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2vxacqqor.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ieinkfks.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2yowougoe.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgoaqvm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpkjoxu.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2bihenjbj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrqazjl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmahgfgf.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vraylgrm.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhjnnno.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqoypgg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gadeybmu.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ccenabys.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2frpcdutc.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvmrpab.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hrznoqjp.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkacrbn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzmtevg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2yekbzozi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzvvxhb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2twpptfdr.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bltzbbea.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ggucfgbt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2uvrcyhoz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzixodu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zktjtevq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnquoln.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jsajmljq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkzfkhf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvjsbmx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfuwptt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtgxbes.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zayeawci.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2osuurydl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ptwouflp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fymxgmkk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqtheqr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2epyppnqn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2snazrvhf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfimqpm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tboqzsqx.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkucosa.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2glcbvhay.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2apmjutek.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgxawvh.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrlbikg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2robtsjxz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2zklqpqkw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2neepyzdn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2pyunnzwo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zfuutsab.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2mzprbwgr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yotygxil.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2sikzdnyd.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2eajkklse.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yadrrfcu.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfsbywk.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nikgdfhu.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yvcpqksa.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2krxcaubg.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mywzcofw.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzrpcnl.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ouokchpe.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvgxtwx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qarqfsah.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnhoxir.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2evbrnusi.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tixlvcxo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtfnswb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tmekqwms.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivydtabq.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2izlazrgt.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2qeukzczv.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjrwjbi.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2oxushjmt.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdsgogu.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrkaswii.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2anlrbgyk.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2uydckwga.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2efdukiip.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lltpwkfo.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2bzhdqoyl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnoyyti.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rljwstmv.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfznbma.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2izpkujbt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlcwqvce.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tufptxfw.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2skyaqyzd.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2sfdvjgwo.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2fsyrddeu.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kanuhgrx.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2onhxbkav.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xocqswot.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qliqktyg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2lffljgpq.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2inbxakew.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2floziznw.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkfbiiy.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ancxznra.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txewewis.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxvhwfq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxztpqvi.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfpjlouc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2smpjhbvk.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iaikvxkg.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrrriez.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2buluavmu.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfoyviw.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rrywkbjs.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vviaeclu.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bglfzvpj.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbjpnsf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvxvjzp.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2pfuknggh.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2oiptgmms.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2itchpejg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2zxciqsqy.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfdlxez.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtrzloh.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gratrmpy.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpydefx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2bdajtgfw.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2npklnkmj.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wiaktcel.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2hifaqoxq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ujbyfdtd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipofkhxe.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbavcfu.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmgbgkv.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbvuicu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2blcmgkzs.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2edeidodh.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2znsfoyxw.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnxnmjn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2zypzusoc.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqdqdob.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2hqnaiqto.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdcfsok.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2avmvgrwz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxfxbwa.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ddsfgrue.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ktfldlli.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxmvcnm.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2qmsamlxj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvzirue.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2clkgvqhv.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kspszyzf.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdjooqo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrpkgtg.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2rlptsoiq.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2izhemozi.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2riobyqqa.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2znqiupgn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nusseixd.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwdzhlj.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgccgun.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pesjhisg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkbvdwi.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pxysdjbd.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbtjppod.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xupkmgnw.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbxtyjz.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxjhguz.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rerlsdyf.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2joflkjuu.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxttqxf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xtkpiiac.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2chmigpws.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2newsvipp.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2hekgxkmn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2wliyrufj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2zpiekiuy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2irjnzycn.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2puqpbpbf.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2twklemni.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2weiesxnd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwbxglz.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2czqapntb.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvxzcvi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bucehsko.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhjkfdl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2imexbmwt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqnufdf.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2dadwfpng.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2rruzeffg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2xpyskgcr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jokneokb.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2boevhzqy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2evdrgozi.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2fslbxzre.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbxdfxj.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqknhfv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnhxjgy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2tofzitbx.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2gfpzktno.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2tueuecjs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2saucrzwx.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2stpjsfcy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqogzcx.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvmzmit.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkblxqm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hklhaxbn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuflfvfi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bulmncmu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kypjcxie.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgsaiht.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjufrxi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2byrcbdiz.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2cemlyele.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2bwnwhydi.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyzuimze.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2awztaugj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uitjqqgk.html


<!-- 参考信息 -->