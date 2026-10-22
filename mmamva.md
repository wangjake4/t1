代发 wailian999

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2drdovapz.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwghukf.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2exswqzzs.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfpqmwf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfexknn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2maiyvnjl.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ektapbho.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdsrntf.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cnooaflq.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjcdvpc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2meiroqbe.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhozusp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2stpzekim.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2airfyeae.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2rajevyqa.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkastcm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2dzuntahw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2agsrmdia.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzuwdpa.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2bydqijqe.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cyaopmme.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rylicjqw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2pijnzykw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bosppgcr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2umfwxyxb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2sbsxnsud.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2lalxqrqg.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfmetwb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2iqplodeg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jzldpqdy.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2zrokatsj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cewoubfn.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2chmofmrp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkttvctd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbkbtyw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2jjafyhwk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhccvycr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hkegsbll.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2iojwgnfr.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbtqmyu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ehihnsvx.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oabosoed.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2ejedshdf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbuljry.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lplheoec.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aekyoerm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjgnedu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsleehpr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2qelxnmup.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxxmvea.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxzbgzd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2xprqxkiu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2hcfdfmch.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrsbryo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxeofgz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfcgkur.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2eumqqcvg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbeyjti.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fiaaxhrj.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwyvoiz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jykdckjb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrdyjxm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2elosohsl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2hshbvqdd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntcfshee.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2piskaeuv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lthigygc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmajidg.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nkywupgu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2rslftdna.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrntqnh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwnjybb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2omzrcenl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hdblopsf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2dynuyogf.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jftjtubp.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjvavrp.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtdjvke.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vkuscacj.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yonclwcp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2abkihefw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxjqktx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2imrrukbm.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2swgrxrkd.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2guvjrqip.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zktorzay.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rbmwazup.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvamntui.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsijlkn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxifkpo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmjmcol.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmbeaiw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfpjnxh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2tiiszuwc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2rzudyudm.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2grqzyhav.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxljhzel.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqtawvq.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xiuqgfvg.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2imdqqayw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqokkime.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfycgxzg.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2urebenht.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwtcqnu.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2vjalgwjs.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxirbkht.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvgyefd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2bzzngkck.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2xohtjxje.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdtbfhj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2guokcgnw.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2onvobwby.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2elrengdl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2xieyjcrq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2akjebtdf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mzclardv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rykdlmfn.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxmntfi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2knuylqpf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmgsmsoz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aofrrptl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxutcjf.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hazuactf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uewacjic.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hotockzn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2srfodzru.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zkaetfia.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdbfcvu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2fzktbglg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2izpahegg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hydkasjk.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkehhqt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2arbselgi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2iclrzrjl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbuuieq.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfxdtgp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2mqecznmb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdaqysa.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2qscfciuy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfntijg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2asrligzv.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmbbrmh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pvofqdrp.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2toqjxhfg.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdpilmg.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rltbjlvl.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kecsflhh.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcasbxkt.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wljpmufq.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcjqjtl.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wtigcpjl.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbauafq.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vjthismd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2vzydyvno.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ibhjuobb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukcnjejz.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dtthvooz.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbfrrth.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsyzvyob.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tmiicbwe.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qijfbsjx.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fperhfby.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgoqyhf.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hollfayo.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2srrehqda.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xyhezucq.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2szjfxopm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2cokghyfv.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2isiwtsqg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tvoqkqwz.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxggfkh.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxnzgzi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfoibaox.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtwvmox.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjduaaqg.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssptwjxa.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvpgmqg.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aqcpbeno.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfbyyrw.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkerspc.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjpbtmq.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kfuatfzy.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2igtyjphv.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hepyrtrm.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqdkqpo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2eabamjxg.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yeznheaw.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbqqwix.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fxcphfxz.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2axevdtcj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxqysks.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2codtjlkc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svffvrls.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2exucovho.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2zzttvegu.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2diimkouq.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ozukwpqm.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nezntstn.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2sxumenoj.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmouuoj.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwpfmkr.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2uzcpcvvt.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzachvs.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wjfntzym.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2iaulzvtm.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmnidaa.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2iyooswhh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjptipo.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2toxviknx.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2stvramjk.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdyazlj.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lplnqran.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2yvogxkqy.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hbvuawmz.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxcqawx.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2wunqewdw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2sfrlfgxz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htsjygkr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2sykybvqi.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sftjtqcs.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbkxkuj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdnaiget.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjclnfr.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwhoisi.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2zlyfsfsv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2jrphkfvn.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2glyywtfr.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2myurntun.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2enietmkg.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrpbmsr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxlilgd.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2usiqnmzu.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2dopzhady.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2kchmlciq.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2tymgcwhf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zonzuzns.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmyradi.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obyaopud.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yghwysyr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnublmoq.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2kuiwdjcp.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhnwskc.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbbibec.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtkpkwk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgjbkzn.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eclbuwal.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gatwbttj.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmziilte.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgoqibip.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jpsedkny.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpthpzxy.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2blbkorak.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2etqqbthm.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rvuftpqt.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgweguc.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbjpgeq.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqnotzg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2eedbojdq.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2uiyoiryy.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2xhszzzrs.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2pyzhieqo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2zdevmuss.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2niyuwbbx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2tppkyvjs.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgukaxn.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kgzztueg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2zunhliaw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2ususqxcg.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkobgcgo.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vytcfznb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwjjgge.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdiqrvyi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcodvzs.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwojyoq.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2fumbnpwt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2krdqxzqx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjgiyiz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ungdzdtt.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fqyhqlnh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpygzem.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2gspygjge.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2etfevzxd.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvdgyou.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2xrlmtfkl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdpjofd.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2kypvqvkr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnmbxlm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2txgkboki.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2smkhrfos.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkxnczo.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpywkzy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2lowrerji.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kldkqwgw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfaktjh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcquqqcm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxojfqoo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wtzatvgn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxlhghh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlttzef.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjvwtwx.html


<!-- 参考信息 -->