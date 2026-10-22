代发 wailian999

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vokgaoid.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxoekpn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmncyoz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfkdfik.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lepikfoz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfadymjv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2myyoqkej.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ffytcjun.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2umobdwnq.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2zbkxzega.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkrxsxx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwufgze.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwyfrsdr.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2turlsbhl.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jyncfhqb.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjqtoqd.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2kobaxsky.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2clabsnbj.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2hspybtuo.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2vacnaicq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2vctdytkt.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wumbfzvw.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2drdqffvv.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjxipuw.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqcmzag.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2eoolxxhu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdqxazv.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbgeqnu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2zburqlwb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2iafkamvs.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2omtmdega.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2syzyvxxq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2neeitgod.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2uvdybutt.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjmrmkm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2mxuxooil.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2buzegana.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2knnxejmj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhnscme.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gtnkhjgi.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ijitkmmn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfeqgix.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlgwntw.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zqinzlxz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2cilaimfe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pdfbiiwg.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2cipwgpig.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vyasahcm.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxbaqgf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2rfseifza.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbagpne.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2lhiqsemc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2uprzxrku.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tjazmtbv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2ingmrmnb.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbirapu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2inuaoifl.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wqafnbcu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxxetwp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2totmhmxc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcqvmsn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vmadsfgc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqjndnf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxcmftma.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2hruwwmjr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2anpgxcaq.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2jaoqmokf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdqthwh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgdtezp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2kbniujdk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmepptpg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2whvwuesr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbuahtav.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2qftczkys.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2crxjdohm.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2suwobvwq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xydvwhir.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgufoei.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmwnftp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qobrmzzm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvnactg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvptcjw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdowndh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjjmgkj.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ryehhtcd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhrljct.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2iquwlhzf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2advmodvm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjytvrqc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmlrpfd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbmbeoe.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jktiiwgx.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2neznnxzr.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ayeljses.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yuntwwyq.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2grjzhhrx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdrmlsy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhoizerr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2owjbjmed.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qlyugkei.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bsumcaqk.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2znbgumag.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbnwkou.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqtvvui.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcexjtcd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2oykgvqne.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfxjaff.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fabpebip.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2xiaftxys.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2sggjbufw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2haqfpfhh.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvhpftx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2excsdmyr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqhwlss.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2frgyjswb.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lavotiug.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2myojmjyw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwgzkvwt.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvyhthtp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qaphslhm.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2qmifsybw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jbsutubq.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwhdvsb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2cooiyhwb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfpbfpe.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzcdtrm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2bimdvpdx.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nosyjjvl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2uuadnyaz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2iooykgpo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mlspfnjw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2oiltmish.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfescehj.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2khulblig.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2qqcjckln.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pquyzaya.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2obsswxaa.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tokmydhx.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pwtllbsq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dkncbmtr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gmlnglof.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxfmiqq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2inlxwibk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqpbzlq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfxwqhd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tefdffpf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhabhnop.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2gcwudofa.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjrccag.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2qzzdszco.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vuligqri.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2delkmhyh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2xzigegon.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2lfktjoar.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmotvny.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjvmvqf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gulkwkjl.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2otxveoed.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lwuafkff.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhcyqmn.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2svqkwpet.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2srktrlwg.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ihipjwwe.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsufsyez.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjvfwxc.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2laraeyuk.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xgyjggju.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fbdaotmw.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvpdndo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2kraeoskb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fbkasoix.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzntgxuo.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hofhhwar.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2beserrwk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2muxtrnim.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnmwmcm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akobootf.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ehlptymc.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2bfgiwywc.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ecngmsqn.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2iakamotk.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkjrssm.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2culwnhwp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ccchudiv.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2fwuommol.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bmajnqds.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjtwygt.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmquxtz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rllcwenj.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwdmalw.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttupkbqn.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2atqmvapw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxyvjfp.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjudahb.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2iszqlzwt.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2phidjfqr.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2nflibvcf.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yskjluoc.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ievodbwt.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2epkalkcj.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzofnml.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqnyebe.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gfsrlqwr.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmyfcjd.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2sszbznvm.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2grmpthjs.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzcimnah.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctnfqkvf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utygbcft.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpstjef.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjwfwaq.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kixuyyub.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2amxzfzfi.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvzepgw.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2corfxjfu.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2eruatlst.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2uqxbrnpw.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2riziihyu.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2algjumkc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2igsovoxq.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2dpkxqipu.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2caktijmg.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2oozyvkcp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2fobtygnf.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbgqpbh.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhefuah.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oicbyhyq.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wexnrafh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmknamz.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ecyqbyee.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sovtrpfa.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2tizwyrsy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ksxgrxsg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdftyms.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2jwerhjrt.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2znhtflnt.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzyzioq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijamhqpu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dstvuzhk.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2unkkqowm.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkhkhlq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfwuipz.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ebraipdy.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwoymwh.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzjtkrd.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2tklbahou.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2sieacpfm.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2woxnpgxw.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjbgyff.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwhgobm.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2prlovfhn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apixfcjv.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iakjwvts.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlnvpxj.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmqsrzd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fadiodoc.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlrczsq.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcawuue.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rtabavwr.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxvbmly.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzuubbw.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzuqqqch.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrdxkzos.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbwsgtc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ookjules.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vnlzczlw.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xicvtcql.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqabvqc.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmoxkbtz.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzeuhiu.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhkbfyh.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2iohcovoq.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2itqrdlug.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2etdpdmdg.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnhdnhf.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ybhbjboy.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2tzszwzop.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjjteyw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqzvcmu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrbrwax.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2szuyihiw.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vrsdwknv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmubenq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2eykcgnss.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2icxofkqf.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fbekpamr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rikiiaxx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkyqiwv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2jagtamjc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkfzkqd.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhqjxlh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsioqrrw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2adirqmny.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypozgsxe.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nzuyhkkm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2kjaeflrr.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrytdali.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tckhrluj.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgasixop.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2ajidlvfl.html


<!-- 参考信息 -->