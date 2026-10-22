代发 wailian999

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovaribfw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttztdmrk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjmuyaf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcovaqs.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrzload.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2gafsqucz.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2dzuiatzd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsefembo.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjtpkbq.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgerfeo.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jbgmgasq.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2suugeedq.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlvqstn.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2kprfkqjg.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqaqcdu.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2glqlnxcv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmuxndc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ptypleqk.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2icggxiuv.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgtnggo.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ypluzukw.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2kebctmqq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bbcfxrsn.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2fnnuoiul.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjhgtvz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfsaogy.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2givhncsl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2nxeljwid.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2mchtsdyt.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2xpsvefkg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhrltmc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ijavzrpm.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2psnwnzjm.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhbfzfq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2lezjepjw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2thaeaquq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhgrymi.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrbbmqv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxckxhw.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrsuveb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2endiqgmx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qccnwcfy.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdhxmhf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2slqdtqcd.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yujbmtyr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnetntl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2flmqbyak.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2dmnxuhnm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrjcuwx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wkizclyq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2wppjeqkz.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kuiwhoeh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnqoewk.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqbultx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2wodgskhs.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2agebfrhe.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cxsnwgoc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tzeruepu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2jshbiqwm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwzsohz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2dezbmxys.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqsicaki.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2eifpmpry.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbrtgbhr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2eircwdeg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2isskeiak.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvddehqg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2fsihruog.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdmfjpq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2noatrxzl.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtklzmn.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gexwcjgd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2iojbgzua.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2fuewdkkz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdmtnljf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqjbwrm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2uihxqqlr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vpybbzjz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2knzjdmkz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnwlgjt.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vkufxypc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpfrruw.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxfjvyr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxcwlhs.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jiuusagm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjxupmq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2upghctip.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnmzgyp.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ucuahfdk.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2natmrmar.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbjpxwy.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xouaucdc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rezaxrhu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qejdkccj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfpmxiw.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2krbtpgmz.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqiuwsj.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2otmoavac.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ptwgcoiy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsftgblk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2docvjxov.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjcjxue.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2iaevyhbg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqalyqz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2noutkrog.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2xobtfyoc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2paymfopo.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2inotbqau.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xieruhio.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ievkculq.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhizvso.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqbewho.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbzdnbkr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvcsxpyd.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpqpcwu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfiomvul.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbskwxk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqbciwi.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bohlgdve.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxkesdc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2fdslqsgo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qyoaeynw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2crjzyvlf.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kveqfgmi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvgnezq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2yvnbizap.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2splpewii.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2igkckqpn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbxmcje.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqtzohd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2xevhcmlt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnumzhkj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwohvya.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2apenvcfk.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjyebjm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xocwnhjr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtcaywf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzqtkkb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cymxtvcs.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyupkzyq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnzyrnv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxofusxv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2irjehwnp.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2bcrnnesf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgayueb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpygjvt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vvnclfwm.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2exxfaxvd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2tdklqszy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ubuxztef.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2jcumgxjp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2moymttiv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yrialmee.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2nulxzbsi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbmojvd.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwsbzxk.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2dtyzyfng.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgtguzo.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wyuchesb.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezyugrne.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qooadnqe.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtditfi.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fefvedco.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dmexaomq.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtcsydp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2aoelnfet.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2klxolfgi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lammxtkf.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2epbqavoy.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmttirth.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpfothpu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2njlleals.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dguqpmqs.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zwcgkheq.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2icdrdjcg.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2owoktkhp.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpuhueu.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpekcpq.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2brejezss.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vdvolboc.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2rxafmdmo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgjqbft.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rwkysuuq.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2sqihxzno.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtxalfi.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqecrvot.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2woxyjlzt.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjzzptvl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzbxrrh.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vivzsqag.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yubhdlcv.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2aslkgsph.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2nktbhuyq.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yzpvcmno.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lqyxzobk.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fdadaxvu.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uacsxuwa.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2oeecvdhq.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwesuhz.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qntnmnyy.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lckgltch.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ejafyenc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkljuyf.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2daddwhok.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwzahmm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtycxzil.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqwqymf.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgyfgtc.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzwscgc.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjcwisq.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2serimcwv.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dcalyklg.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dwddsqra.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hashhmkz.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhtsmts.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2iaakmdui.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrttnjr.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yaegpsqn.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvdckei.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2bngasmby.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjdtmyy.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2antyxdll.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2olpcsawk.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxplusu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2hnsqucgs.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdxfjby.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvmjabh.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2uvkkjvqz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2qwifcdxh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvhetja.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2tjwtiagx.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2optpvhhe.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhsjugu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilpbidbo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ysubmiys.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkcmqpn.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsdjkfx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2utydcnnt.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2yxumdowh.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2byiczymu.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzteunq.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwdkacw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhvwefq.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2yfplobzf.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2cflbjtza.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzjdoyo.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ntkgoqwr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygznopxa.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyokbcsg.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhlywrt.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2unzodewo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgvqcpz.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2alumvylh.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhajdfue.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pwlwdjbe.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbvhdzq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxikrdp.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwtnhid.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuomsebp.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnoeptv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2whtieyzu.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lxoqqeet.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2uamaieve.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjwzgtr.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjytnve.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mjcejcvj.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtiyzzv.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fuexdiyc.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhgyqkw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xystjcan.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2yktifqhb.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2swabebbc.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2kupvsygd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2stlfkyvx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzsdyko.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjcwunm.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2rftzevrv.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfbwrmw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2kznwrrnk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2dyrflvnq.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdidrnvy.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2sciqieph.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2elrhrhzr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpzcqtsj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2knilzxjm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjlwyqmp.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtfysxf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2fidtiluo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2mqndgobi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwuzjgwr.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ozaiovvm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2nxsbhvot.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2sarosszr.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2adtmheox.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnubufkn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmftcsw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2aunywnhd.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2fklnaoux.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2gqidsmic.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkypppp.html


<!-- 参考信息 -->