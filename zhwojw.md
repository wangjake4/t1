代发 wailian999

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzjdxup.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2smvocwcz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgctvvl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhynwqf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ljgelphv.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfbehew.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2bbujtrmt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrdwlwr.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltipvpdu.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2sooestid.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xntkpart.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrryepvg.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2dzukqjay.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2veauymwq.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2xdoubmdm.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2zshiirqz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2cyxyxvbt.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iqktigya.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbxvajj.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jxmlvwfx.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkfcftz.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2koawylsl.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nnuwvvfp.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2ypcnxwyq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzhfzzt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2iutoyjpj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2lswodvnl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2iiuvpyak.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2edrhhlkm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2wphqtwfe.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2djcnqqlj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2cperjcvr.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkdmgzo.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtbyuwi.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqyrabz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jvsnbzbw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rtoxnlpt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxdvobb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqnifxa.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xrzqolil.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2kibibtpg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2epttarzq.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2yptkujsp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qrccpnrh.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpqiimt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzbgscb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtzqszk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2apkgujnx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2wunnxhnl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cvwekfmn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2ijgjwxkg.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmohpumz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zslvgidu.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxjvxim.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2elurfnda.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aehyrmlh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2karuomhz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2msiauxyc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2doumbpyz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2oztsipdt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2sltotivx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldcnpsjf.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2njqugvrz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvehwyjv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2yrebbfxi.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbedpsp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2fydnaizp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvzprtn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2xymcyboz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkoiabhp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2zckjeneh.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzjtice.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2pllxlwmm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2sufaqujr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2tyelxrku.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2svjbouym.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnptjjrx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2byekqnkb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsuaprop.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ffijssfo.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mozwqodr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2gjarjxhy.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmosopk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjnfhgbf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hufuptzw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2eczwfqwc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2aecufuec.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkzknpx.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqscujpf.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbgkcqp.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmezpfpl.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbxdlxs.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzjphdf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtzsiah.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwzqyrb.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnpejzfz.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrfwmcz.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zrlyvbei.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2egajzbwy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2watmsjrt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjaiwshc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2txpqtshw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2hcoxxrbe.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jdirypru.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwtzmvq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfebokes.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjownvp.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xfunhdsb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnbeenm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjcpfkx.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zafwvyng.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zntqhehe.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxlgabb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgwkgrq.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2scctyebb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkecwvpt.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfzhbik.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mizxisjt.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cubgouoq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2upvfspui.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2bnijkore.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pxyyqgxv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2chtgzrgc.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2odkjtwjc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2evkmkhcc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2vuovaqbx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfkvvjrj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2udcomrdc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmtblbl.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzywxvj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgozzzq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjsnivxl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhpiwam.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwqpzmb.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tcwrlboy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqyxlnv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmrzrls.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fuorifoj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mcocgqgw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2idyjmoyb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpkhqya.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxoojgkx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpyksik.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2jgdrqxhm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjwjalw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2nepmxqqh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2brjsdcmv.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzicbxd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2jxuxtzoy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwwacvl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2tevijlkm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2azrztulj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bxswhdph.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ziyfxake.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrnpqzh.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhwgzox.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2twolybxj.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ohosvlpr.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qsgxtvzu.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxbocgp.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrzdmne.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2afhbapwd.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2flukxidl.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vjplrhka.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rauaradp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkazimo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hzninold.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2efarlqcg.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zkquqfis.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2erbdvqms.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdlrksm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwenvtb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uaasmzba.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzjjbtr.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2yfiwztkg.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpnhraa.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jglbydfx.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxyuqid.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2spyeqaah.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2toxqdfcn.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2oyywmvso.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mmlnscts.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2haevkebt.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtmgajy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpbtgrm.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnddret.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdhobklc.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2stnsicbm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmxgdbm.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvqonlq.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2eaynmafh.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbwrfpz.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jcykpwhx.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhshdkn.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oacuzxsy.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qaomqpvw.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2anlrjnpa.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2vwixrqvy.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrtmyjb.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cioycvrv.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2slfnwkms.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2zdycouer.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ituxijyp.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhjrptx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlrqmpds.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjixdrj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2zdoogaah.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jpctqokw.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2rubymqai.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2galuepnv.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxjaduk.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bwnyjlym.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfykgnq.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbkjbqz.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cqkhtpaj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wewcmzuu.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2vovszdnp.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhmlrwi.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2iktwnefj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2dxixrgks.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lplkhytj.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrhohck.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcqmucd.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbmnaqr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2idazjcaq.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gelekhow.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2luegotvt.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2swkmujli.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2qycgqnxw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkwtjzt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmgsbcm.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcelifmj.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzbdkeq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2osgbnsqg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hhqouaim.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2usmzyefx.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2joiqayzr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2swscccsw.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwsqcou.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2pahmmlbq.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2tnowujgk.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ensvreuk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdyjpcb.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2plemvvjh.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqoxbxo.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ydptgxru.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2iokarmhf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwegfnf.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjveukl.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmkijqg.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rszstnzw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqryslbd.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2dgwqvqiq.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ittxhqdr.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mywfekyn.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2nuiezxcp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qesouogc.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eovlihvf.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdarobmx.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkjnnpr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfexfhtk.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zobvntko.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dopimoyy.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2idttoset.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzgllrw.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vzoyfyss.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ahbmhiem.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2iuunzryk.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ymptbyhj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2mondqshz.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2mglnbdah.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2azfkywkm.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2jijbhaoj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2qzignpay.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2fizptzfn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzfticq.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2djhlrdhu.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sojwmfig.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmkmykk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmcnhwm.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqdbaqr.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfmpwkn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2urxhhiye.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2evdujmlr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnktjnz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zffwajph.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2jejnjnlq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2oaoqgqin.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ycirkedi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvcunov.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbejqpy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2gdffqmua.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzcqvkf.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfepiroo.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqlyipia.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2jkuarcwa.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvhtrst.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2afizigyz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ozptceoe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdyrxpv.html


<!-- 参考信息 -->