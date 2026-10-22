代发 wailian999

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2utjfhgjz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2oaonfpik.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2krsiqqbw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfjehju.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2phfvmctl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2beflqwrt.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrtduuq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojifeies.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfhzgqm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgoytkkn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydacupap.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpfhgzh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2adornnyr.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2isruyohk.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2mpybdzbg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2iactnnmf.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2srqywbdp.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2idkmnjpt.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wkituljn.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nifshusc.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2dwskclph.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxqxmeq.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2dtozjzfe.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2ovpusfqe.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2aezheekw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bosyrsiz.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yirhhoiz.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jtuterls.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqpxhzm.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmlwwsb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkyhpub.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnzjibp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2ftddeqpo.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhrvpny.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2khpjiskk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2rwyrovkw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgrxfgz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2rztayiay.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2dobqrlak.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qswxlvpx.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzjkafk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrimfch.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2fukxgsns.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jwspxtsd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrhztza.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2zhzsgszq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2exqdakcf.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmtyrnc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2jpegcjgq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ecifzkbu.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkluhzk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhneczf.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dpjelgow.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2tfclhzro.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlbhoal.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpnrqit.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2avgywuwy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbcfyug.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2najyotll.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gosvetqb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xlktigbw.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2glewqvzz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2caqcmiej.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zegdnogd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcgrrrg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yibmeanr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdfbqgh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zauorxak.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2seeicgjt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqbtxdk.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2chgvddbc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvugpqu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ykpripke.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrxbfxp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2enyvrpof.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2cnycqnnj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkubvznm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxpudzd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2vusjgohg.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vlgskkpn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2bydfqyua.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmphnnt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2owldhryc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmqlfrf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcztemcn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2aopuoixs.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsylgqzo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2zzlkgukw.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xiutuyav.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2euqsxpts.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvbsdki.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qglpntcs.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdarngs.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ayylqgpx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2gawztsij.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhczivfo.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlebhkku.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2blzsiukf.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxeydfs.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqfkyhn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fycizxqs.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhzkjae.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfqlvhn.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2obgfixpa.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfzsgyd.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wdcirqvo.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvjctov.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2caoanltr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbxxfpm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2skyqwqor.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2meqgvpmb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2asvkqxkw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxuymyhz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxxgfcf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqugaro.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2iusodndo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qokkdach.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2otsfycoz.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2snjeaebe.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bcaiennn.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2furmyueo.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrlhtwl.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dspgybov.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vekkmqhk.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2gnooyjoj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2evavvplp.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fmujpivq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2vtuejblm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ilawvrsc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2khuxuvev.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2whuilmuo.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbggsui.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2lamaqrmk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2lnyoqdkq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yagchqqn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxshvhj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlcpeid.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2trjaugqi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbjcloa.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2afberglw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxpgzlg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltslkfvu.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qckkphwi.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2voztawdx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xdtcydjm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qyoopgvp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cunpbimv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2erlztvrt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2ntotcaxh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmqfqwp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2huoxgalo.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2mblbkyqc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjzjjvy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2vgeizqke.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwrwpuw.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2awirbapo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgqcmgs.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ftuvmksi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2piblcmvu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2qktvordo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2phvfpuyo.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgmaaix.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ywpbgtpr.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsygdta.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2takabmez.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lxzbdebx.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdyhwmt.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bafluwbb.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qyrzxgub.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdzxcas.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2muveyqph.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2azwhejlm.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwzqymn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2jhndmqap.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwfxqbm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysptoulf.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iwatzemq.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmhseuj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2shonrnna.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qefurint.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyikjkuo.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2njyvavwt.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2gillbovo.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lfgjplis.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxzqclc.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2duclbnhx.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjdxjkf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqljwxi.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2uukxqvib.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rsphyugf.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hplyoepn.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2jsrjrxez.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgrhjssg.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvvqhjo.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhlquraw.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgnylfdy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkqlgcx.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ctotfagy.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxotqgw.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcmnvec.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbwmdqe.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgpohwg.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2flqevdoq.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2guacznrh.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mludtqen.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2pmacqzwv.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nmepsxhz.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bgheivry.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kslxwzlr.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcnrfrz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhjfskl.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2olfpriav.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqoxbxwd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppaveipa.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2qvivpkgb.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2twjmomlp.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ykoqobyu.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ojejjxzp.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2fnsfonur.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bfntstrx.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lvkypwin.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mokxnmdi.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxfuucf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2telddfnh.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2cscdpzby.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qhldlpin.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zdeqwmdl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2xccorojk.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dhostdhc.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ukyeddkf.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgzklxf.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmsjjfc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2obmgctow.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gcpblkpf.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qcpdrtdt.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2igmkohxs.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2usfthuio.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2msmajkvc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2qmojcrhw.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aoatkuwc.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yaepgjqx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pophknvm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iltmzcll.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkchjsa.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwbvefe.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2sryqocmb.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hdlmrpdt.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjecyey.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkxnvrp.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2asafajmp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhwlkph.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2bomcirgp.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2raqgnadn.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2kiavdmis.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2faexylwg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkhsdgb.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbapuhtv.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yinxitkg.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvazqhs.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgsmzplh.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2eykjdobm.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zruwzovv.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ghovmqub.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ghcbuzob.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2glglxmdu.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmunolxp.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zszakasu.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wiruybso.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqhdhyl.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2euaibgzl.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbypgrov.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qghwieeu.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2skhgrpvi.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rtoszywp.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfvhlsb.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrwqbuf.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zjambmfc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2mckzvucj.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2lknheejl.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2owbvocsb.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdlwbcz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2japowmrb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2aufqdvwf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2abcdronq.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2qlsptcqf.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2paumwzly.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqwkbod.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2cdghrfwd.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlutvusc.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2axdwajio.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nneyptbj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cekqwnnt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2fiswaara.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvoxtfal.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwzynmjy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2szpfafkg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2huhgutvp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewszdufn.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ipslbfxa.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2wuirutre.html


<!-- 参考信息 -->