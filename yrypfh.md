代发 wailian999

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhgzlch.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuosocwk.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jaluwbtk.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ylsyfnmn.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2falfwrfv.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjxkywx.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmymobs.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwhamjt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdualfq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zbnflmma.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zatesfsp.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrgyakv.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lwizyyqv.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2egasjyox.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yepfvwgq.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdtqzhe.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2wraojnwp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvpzmtd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2fdigdbbz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkwmkow.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwnfkva.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2zwuhksck.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwqcpfy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2thyclepq.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dtaoelct.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvpehcap.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjpbtrl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nowzhjlm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ixksvikr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqkbpou.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgnnsrb.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2aiendtar.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzwrdma.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2amdtltuo.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wszthprn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxdopvb.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwaoail.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhlivmw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvwpnpt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdimfzl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewafvxmy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ffcbrtpm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2nvculatw.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lyibqxqw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2giebxces.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzfjkke.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2vbozlrva.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfcgbnzz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qbitwfnf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ucimjbtk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2tptnbqzw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zolzyctv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2voiqjllj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtfnroz.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2dhltgyqg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2scxhaddq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qynrnqpe.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2eipkgouo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2veiohtci.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2veqjxwqs.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdgiwbp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvxfdbv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2uluqqmrw.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfhpmds.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxkdudu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2boircnpj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnniuvld.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2utdikoem.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdbcpgj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrryxkv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmcedxjm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqhbiim.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ijniiwvn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2piaibgki.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2myxwpzvh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrlhuky.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2izidrjxx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2afkigbyj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnccfjgj.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tgyaugln.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2obylohuy.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfiikph.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvnpcyv.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmyiqcu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtquotgu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwkhvbf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tckrxnnm.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmcpxukz.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkhsjsc.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2plyhygfo.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqlmcle.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2edfccptk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2yklicdoo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2skmetsgd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwtdlpu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbhbnin.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqfjggr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2akijpnsx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2bbntcues.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2zdewhxwi.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2aymbfsmm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkeqrnvx.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2obecmukw.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hszlplab.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouapxcbd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2njpwlvpo.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2fonpcqwg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2onyxcfxs.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2tbggfsao.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdvwern.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lzahdhxv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2meleajki.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ksridoxh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbdggah.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvzskbk.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nltdbpxl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgeuuzn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdcnfck.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzabgcnp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pzlbmebj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvncqspy.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsgysrg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2zngtwajh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvgjkvn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2atrjhvwr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wlewbvvf.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pqawocyx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfzyhin.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rhlkkkys.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2feewtvjt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yecyilri.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2idyjicpn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2vosaxplp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qndwfpde.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2eofhnisc.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzkrkfn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuzctvjm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2fdsvrahn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2dablvjif.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgekyqo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkhfdxt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2lggvrgvt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2kshggetn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2mznjqfrb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ptalvzka.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvczaor.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjnawbr.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkgzcxc.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtrvqsn.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qnoagwcs.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkmzzjt.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yirwwcco.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cnsdpjyw.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2jafthlrj.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tclkespt.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwjqnfx.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2txnqooca.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmulxcu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qmaoipts.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdsixuo.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjxctjr.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyujmfds.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpmthsd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aljszxxn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhoafhs.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zzoybuok.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2qpcbhflx.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qjollhfu.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnfnfzn.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tsopqgqz.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzuzyug.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjbjebk.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwdmbir.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vyyblwpu.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcklenc.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2fzflwrrw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrsybup.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtrurevg.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmoopuqe.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2elhfyxld.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkjevcy.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wsabricf.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2iogapswz.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2fekhmkwn.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmqpoai.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgwbncr.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iysimdjc.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pnebcxvg.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rfevpwws.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2whqbcngj.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nellgayu.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfsketh.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2btmfzngw.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkvkfpu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qanhlqii.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjjxijz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvidzmo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvufysk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2buitvlzn.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqbvatn.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2rxguhihg.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvmzqeb.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrsjwcr.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbtpoiu.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2sagzpbyv.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2imighpsd.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2svrtumlp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zouywibn.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2qodykrqy.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2uwszxvhe.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzqjuoq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2nepzjvzl.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wasxuati.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2csddfxkj.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ukhkqpsd.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zeccaupm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvqwxkb.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2retaulsh.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pjfcocmk.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2zrsilpkc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2axlnpjwu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aoyarcqi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmdbcfa.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2anhviphn.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpnahqxe.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtxetlq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhtaqyj.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqgzfhc.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2szisqdzb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2zdapbuam.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2skjtfbds.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2wzzbxjtv.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqbjolj.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ubadgzol.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhmyiia.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjujruo.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2yddvgmup.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgiazrr.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2swcdztba.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmwhgwz.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwbiqmo.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yieuilny.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oojinryp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2dadpmcbj.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2iwcueozg.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzvvvun.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ohnbszmu.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfmkbph.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2muzaopih.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbclvgc.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqnzjmy.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbqlxvj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rigchdwx.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qieqoypb.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdozcyl.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nshnqbjj.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2kakcxcym.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vbynelyu.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qggqbgls.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2triodurp.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtxyled.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2awssfdrg.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzvunqd.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2oavhlzvn.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2kthiymwz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2iafwmlvl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfyvhku.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2wkznxsvi.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2iximeixg.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bgirbiap.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuucbedd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2hamtefkf.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2yricmaxq.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbscuhf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgerdli.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsihryd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2kmtezlcg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cquynudd.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwxsvto.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxbzsjb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2uzkqfuvk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihddjmpp.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgomusa.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2jhejmnto.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpkmsmpy.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2adnngxkl.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhuyslf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2hyrnfman.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlxwgrg.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2cpyuikzz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2mhaykgsc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mysfxmti.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2paanljcp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgbqoah.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpqlswl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfebdts.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhmklyl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhvrblj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvsdxqle.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gutvgzjy.html


<!-- 参考信息 -->