代发 wailian999

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bopeiamg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2azugtgtx.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2uztpsekp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqfhqck.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2znbsweds.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2pskselze.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtmkwnp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qazffxak.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2siyqbuke.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxixyzjw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2srflomus.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvptcwh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uvghisie.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbapcjw.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdxyxjh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfbebmw.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfolmvmi.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpoirtul.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2aftzikhj.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmpncbe.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2savfnvil.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2bxoijgkv.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxqbcqy.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2oprrrhkl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2rsygncov.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zqplzphb.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdhegxj.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bnecjlex.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2drpeaaak.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2bwonnoqx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2afxvlipy.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2cuximeom.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgvdgao.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvgmkcn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2farsvtkg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxtorny.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2pmeksspa.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2tdiahsoq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtzbjrz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtqnqhn.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhxkpqc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2srowagzs.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2fyuzwmxp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkgiovs.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmilgnl.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2vxaotnjy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2jjhbpfoq.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgttctu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvwinlf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fmdzklhw.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgrzswk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2weroekfn.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2snrtavkp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgdekgm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uuelklsp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2jancxxwt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhfpsav.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxvbrkz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxleqpx.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkfuatr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lirajeph.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2czqumtso.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2qttubesd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2whxuhfbz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ziavjidx.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kctpqjur.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvebgyx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxqeszh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpkoxdmw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbaugkej.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvwgcdo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjmgqjp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnmghmc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2czluyudu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2omkzwdev.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2rrulpqjo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkzvyoc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ukyfirad.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jakkngcy.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ptevouds.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2paqkepdt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrhscjd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbuhbdi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkmenom.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjterum.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxeixai.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxucike.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjqrvak.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjvmrwz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2xjycefsa.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgggflk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxuljlb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbsixnt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vinllbvv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2hylwfxda.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxajcea.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjuyyvj.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qbyturuc.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kolcxyop.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rohohfoz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovugdapq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwawfxex.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wyehpouv.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ringhznj.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzcuyhzl.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xfrczqgy.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qnorpijy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gaponevm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdxosbd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqgsdwb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2juqtdgly.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2oahusxbd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgedcldg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2wlndhtie.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2onggobby.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzqjjdz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpumazme.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhptxdc.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ambbmjys.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kaiovydv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovyuiznq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2msvogqyx.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rupgivke.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwoxhon.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2amfgncbl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ictlbnou.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qeiotsem.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2uqymudkz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgtbjbd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2spyedmnp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2mxpcoyek.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkzildl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmlvjqb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2dfuboofd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oloqzoka.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kysuhtwz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvqzlsv.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iyuruhfh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2lizebcyz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oowftwdq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtgjymv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pkthngfi.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgfnmfo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sfuteqqx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2twbsgfnu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uexqicxm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ynuwgvnm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucpaauso.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrjnvtk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvtridw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2isyxtxnb.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2jntuktji.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2usjgqthl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2coflonbm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2avkelyxn.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2udfpqjdo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2yvisefjt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2nhbodktd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2yeypyfbv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2uredjnvi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpivtyb.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2eltrczjk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqbjjnm.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxxkecd.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2cltfwyje.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxskeuj.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cqnkqqmu.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xijeangz.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wfoxnnwf.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2prowbjfk.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2snuksykg.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2agnaqrgq.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwbxqoj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2laoqvqwf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tozrfzjs.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eauiqbqt.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrdugsq.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfpvwgye.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2muageyag.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzyosgs.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqohfrbs.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hajcpgzg.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhiharx.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzplqag.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhwapyn.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2oqoxydru.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqzmops.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2dpjtkeep.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2vviygrss.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqrdyho.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdqxwjl.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqxlsho.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqsqcnyb.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2boqsbmed.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fspjopic.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2edgepldc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzqzwyn.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbnkwuy.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2aucivocp.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2oenufjwf.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzzkhwx.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oyejctxv.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lyalngud.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jntnfqdt.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbjsyzp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2nwligvqs.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjfplen.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ypsrligm.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2amyihbqm.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2gpblzpua.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzqrwvl.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvdjzbi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqravtf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2caataafx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2uioyxfgz.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dxaaxqtn.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxuztyk.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gzstrctp.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2nokkboea.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgtrzfd.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjvinvs.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yscboedz.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2odvxdssp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvitkjg.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2axihgqmw.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lytwwxlr.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2avthvtcz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2yepcscpk.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2imbcxxtd.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpyqvwl.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yupckqoy.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hfikptsp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwyakft.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2djfhzlcy.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2adjjvvym.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2eisknwge.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ghnuhhat.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwprpss.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2lfeaauhv.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqxvhmr.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2canvgvir.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2inugnvmz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dfyyygbh.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbybhgti.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2bccpwcdu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2egaduwcn.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2beyhcsmo.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjrpjac.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2uatewkvk.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2fadnltws.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlskeqc.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hldvxbbq.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2jyngypac.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2cozuwvxd.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwrkrlf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgrrbfd.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2puhtfbvs.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbuttceb.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtqklld.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdycigm.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxvowwd.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2juukjtoq.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2eblojpxx.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxldrvj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjhafjb.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtfyivc.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2srwyehwu.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bufzqwct.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zybluwfm.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mxiuvujy.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2odgtldvg.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vbiiljny.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2frnaaiaf.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2emqaimzg.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjjtvrz.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wxirhmlc.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hewzstub.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wgyhhasa.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2urfzhjtf.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2wadjwgyq.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgmlnpm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2alzmepzu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhshvxd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2gbihabrr.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2xknxosmy.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2igzjbzwv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2msyaastg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2fwheijab.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2yitzwdcd.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjyjagr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnjtoht.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2enrgieqt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdqfrwz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtfhnhy.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2frvedgnw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2owtcjnrk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2vetinpbr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tehedert.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2riwmgkuk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjhmoei.html


<!-- 参考信息 -->