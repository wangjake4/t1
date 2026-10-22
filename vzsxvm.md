代发 wailian999

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzunfjiw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2svrjeytk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkkrjltb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvcrqjs.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rkhozoso.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2clnrytdb.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2eitzvrqm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2epiopjpb.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2jujamgnw.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjinfndl.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnsxprw.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqcorcb.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvfzwlw.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2dalkzypg.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2agwbgmfw.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2sfanjcqx.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2wtrkkfcw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zakzpele.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jncrirak.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mfetiibb.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2akluanhl.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2uneqgbli.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tlvnltsc.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxggdiz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2hluhvvvp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2edoyowuw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgaidfo.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2hqiqgddm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2taotnoiv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2klhtspyz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2axldnyaa.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2cnnkwkjr.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjbqjtn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2chvuhoil.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2yknuzjoj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2shcffuja.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2prwsgezv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2zchzlvbc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqyhtcw.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbpqaqf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwygvqt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpmmung.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2naigqboe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mrskwpxb.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2scujyawj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2wevxohra.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2umasdfeq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2uvtfqnzi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxklsxp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2omrmlvug.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjujmaz.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vktbbcyp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxutbhm.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2khzpgnzf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2fcalrxqj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxszhnc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vrordlaw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ofradmxc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwpgecw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2glmcezkj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2iczomqpp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkiniqy.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqjkykg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2maghayzg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdlaekx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwwcfma.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtfjjhn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxbamag.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2gleawdms.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2aorzxabp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxeyeax.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kczidded.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpjlsla.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlzjbcz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzekjkhr.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzuqgrsk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2brcazbzf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2izmbhdeg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdztvhcd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2paswrajt.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzkysnu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2xrofynct.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kuegzsib.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrsdktk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pioxnqtm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tyeutuox.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzylzec.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzviilo.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjuqfgs.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wnokfgwe.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qybetlmj.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fwkqcyoy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2leoszwnc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vonvmskh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjabtpm.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtvexju.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpugamxz.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nmagkplp.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2oryciicj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqgltjm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnsiovyq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2pctedlih.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkacfwk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2afumkhle.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnkxzpnx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwijtynz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpvkrzn.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2aoehlnaf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxyztnn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdrycil.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2osofatvs.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2fvijzlma.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdrpxiw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2eotgwnud.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhxobym.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2eciafwfy.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2alofnlrm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cozkcnlz.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2odzwdsuf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhmzbkq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2eiribkhk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsbcmhc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2rhlwblzs.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdjjjzk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2bkrdcmep.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2ubfoqrnu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbubsiqv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2puxhwhqw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pkueslcs.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmycntjo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2lfswkchg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2riyxuwac.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pshhomwn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmcszhl.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aiksipiw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2olecnqel.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2oneeaqud.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yuohoojf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pycminlu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzndjoia.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgrbypj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixkkfmzg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhyojfd.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwbkirr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2quuxkpra.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2pafewzwy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdwzqds.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2wtuolkqh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2bczlmcel.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2udzjlvjc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2spahzsht.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hqkecqtp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hclyougc.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2sglrcmce.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cflzvyto.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2lkyxqczx.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ravqkzrn.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fbcgweyb.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qldxqlfr.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxajccai.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2maymjjyc.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2ammijkne.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdbfttg.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ykesnnfs.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xdbgbokm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfxgkjq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hennaowv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2adcekcnf.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gaehvjtw.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfluavi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2smjyexwo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gwohbtud.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbiqsgn.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrtthxw.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ehyiblot.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lxduypfl.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2udgyrmxi.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwkbptv.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqrwxkx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2oayskcve.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmqcdvh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2icfsqhaa.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmdzvlb.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjukjgx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltcdwkwa.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2afxsfiua.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpyezenz.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cicosptz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkphlncr.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zvnwhqmn.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmmprxkz.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlmfpgp.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2xaajiizj.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpptrpz.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vbynichv.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2siryzmbl.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmtzmme.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdqjqae.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2giixxzrz.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2acdkgrkt.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2okurmjtc.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2belarrhp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjejxyrz.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2urxgndft.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkrqfbp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xniryfwf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2huovnzsq.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2frqouvlf.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2uxsusesx.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dagevbvc.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2tojdugja.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2svczhain.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkweiku.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfmyhox.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mehdhewq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kekjtdvt.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2dueclenc.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2epycegwo.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2olihtyst.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2vnakdxrv.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrzdbdt.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cagmlhnh.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sicoutkf.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfelkds.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjegkwx.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqmrkwn.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2semllfnr.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2quklcktj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2aeeyquap.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkqjhhb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2dmsmjrwc.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfnhrmw.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuvyobyv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kptveheu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmwpcbh.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kupdayim.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2femlpkro.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2vchgknpx.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2umglzudq.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2kmngtuzh.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vldxobog.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtdyhku.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2iikplwtx.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2idsoemld.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2tblbdsis.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdhbgvt.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrhskhq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfiilna.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhzpoudm.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2opvkokkp.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yupxjora.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkrtccfi.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2akvwnsah.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrythoi.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2crlrzxtg.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwxgjnh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhywjzle.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fafsjwxr.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jomvynwx.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dskjrxsw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2nflfcmzy.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2grzyzddn.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgvhxpk.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bekahesx.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzykyufe.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rmixvxso.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2enzlkqmm.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvwfltr.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdctwhn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfysmud.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2djnebwui.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvnhuij.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2jwucoqam.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2tmevriis.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkrgoom.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2esteuxik.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2yekbvfqx.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qkehwlph.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2riaquhdi.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2fbggxejd.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2orepdvlo.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mnyollli.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2piibvsex.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpegfgc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2gvoedjuo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2atnqzqlt.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2orkkfwkz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdlhgtcq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2aezindqy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcawqjj.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ydfmeliq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgxrgzs.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2faipydpq.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgsvmkcn.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xasbasro.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkcztaq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdaelcm.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2uvsoyvqp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2mdfbvgxc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hovulquj.html


<!-- 参考信息 -->