代发 wailian999

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cpunnaad.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzmgzck.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2uilklazw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2itrblvyx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrtjwuy.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2oowqiqzc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vijzaoay.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wuycbmdb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdjvwrs.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2rwzifdov.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2gcyuonem.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvrgrth.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfvrongz.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjnadypf.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnrpyrc.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvjgquig.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2hcfcdyru.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjibiiw.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqeksyk.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2edhmltns.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2uakbxgeh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kauwytha.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzbntuc.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2emslyswn.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hfaolqtd.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2exbpsoxa.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2njxkzrql.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2givqkvrh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2qvoortkm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2szxbnyoi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2sewduhlf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsswidt.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2czctskpo.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2ygznbigg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2fhegifxt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjnshsw.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnsdmjx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2takhvjrj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2pfahwfln.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqafpww.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ysnvpckr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2epjfvwmu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqdjqwk.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxumvmh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcsmbrw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpicjwo.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2yapqmqrb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bolfmvbb.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvnhyrc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxlkpbm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2etjtumwn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2slzjdhfh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2lauocfxk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pevdmyhr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2tsauasrc.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgzahsi.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xisliprx.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kozyuxmi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwafsjf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbhiarg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwjztwc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lksmddlc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2pakoivcl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjnilmj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlolyawo.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlaxplc.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxihzrp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2wltskwzj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2illhuuzs.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdqhbnf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhrtvyf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ludepgps.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfdoxcm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2webyvjgk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2uvfxmvfs.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ulatepjn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfywots.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvqpcxn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjvqlsr.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpfqnzsb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjigepax.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nnsbmuwn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwrdlyy.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqbtxlq.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2esiqvqjq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmarptx.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2caniqlob.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sehxcbmf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zadkgydd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2whlqwoyb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2npodvjvu.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lobadckl.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vucuvqkp.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmichqg.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdadgyrx.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmmaqsq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2htxntwcr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2apidzstz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vakfvplk.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lynyayaj.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzbcxvzm.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pioqiqmf.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2izhrmszr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cupqafwu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vncmcoce.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2eybrsbvh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2vmyllgwn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2osrohggr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2yubupazo.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2uakftvwr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2cpalbxxj.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhcrbik.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2spfnbmec.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhkdfok.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2aezwdnfg.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptorbjat.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2itftlays.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2nintqlvj.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ziukpbpx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pianoteq.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbiglls.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rerxaunp.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvaskxx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ftcswijh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2tghrijjv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdflopw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmwncsx.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2daqhrnbs.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2apadmzll.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxsbeao.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnxlpxf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rxobxylc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2weqgpdey.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xadmfehj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2ndudmisa.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2thyjmrjd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yejqsoms.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbmabjr.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2taahycgp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpayigwk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2anyqqhhs.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzcnrkf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrlmhmo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttcqjbjs.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2ihocomko.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xebqldrg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvzeboz.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjnbrwl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtniwsn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2sieatiaw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2swplkybz.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2xalgdamh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfcevnr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ggggmzcs.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2totnbsbh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2efybkxty.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ifkbabre.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgqfqox.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xodzsnfv.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2lknfvhio.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ehysuenn.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxjbvkv.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hardrnmb.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aooqeydi.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ybnvzbob.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpgelll.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjvhmtg.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvptoin.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sxftlkkz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ucozlxon.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2homvhijf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obpwrbqw.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fvlujnmy.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qygcclwo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2guufcppw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtwhntj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqakrzso.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ozergkxd.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmcfzey.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ictgeaee.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdxxbwn.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2phylyavb.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbwurfu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2tgufbxlc.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2lzefhrbp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlijeaz.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qojusizg.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvuvpei.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrlriukt.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqlljnxd.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqcrofy.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxlhzzz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzytkzqj.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pfiqxvyk.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnggbdw.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2nrsuvcwe.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vrivqifz.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwqhqji.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qldsxafp.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkofbcb.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pbebekdy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2rehquyam.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmzcxdw.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmnijli.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fszaaszo.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2bbeeijfj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pulwsclp.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzhglxs.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkknomd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcswvqdo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjgwwiq.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ywcrfauh.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2rlemeshr.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2alldhgil.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbzbdgu.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dszkxilf.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yyoykzew.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ejcvzszj.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2edyzeeor.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzwvwsa.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnqjaro.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gsmdpjcl.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bigmmonv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2ikadnhcm.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hugyherq.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pysyogmb.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gkswmsun.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkratfi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjdpyfk.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xwoashlk.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ystieguv.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2saelfqcv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbhgyky.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drhzskwz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2shhcrxij.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jabvezug.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjkubcq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwuuiuz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eznufxlo.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzpkixay.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2pphaqsce.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2cizarwpo.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdlldxi.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2rnybhdde.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2huxkngpr.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2airhzhit.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmkoxzx.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2lpilnalq.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2enbsjllq.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ticktdfn.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ukeoikev.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2secatlhb.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvbypqk.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdguxmy.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rofiutly.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2sllxpviq.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlzrdat.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjrvnged.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2asfijlet.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2vebsxpdl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fulmsmkn.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zglhgrvj.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbakcxxv.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxntwtr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2lthueowm.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvjbvdn.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkukxic.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxlpiuo.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2iafwumkl.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqtcjdm.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ridstdwf.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ypaurtyu.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfhrezo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wwamnrgd.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2vundilfa.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2abydnwvs.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2jodhgeil.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdngrcs.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgqvaoj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwlugld.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2syletpxo.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sokimrjq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwjdigb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2mpqyofqs.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikyfhxpy.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhbttpx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxknzoh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlsxahbv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2btejpxqy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkffxef.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrmwmjf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuyvjmom.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2fqoihcpg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kytbqphp.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mmiurnkp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrmejki.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2udpequcy.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qglgqwov.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxsmemn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2eqnykypb.html


<!-- 参考信息 -->