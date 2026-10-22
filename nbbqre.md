代发 wailian999

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrnuzro.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2azupxzrp.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2mwgvgsbl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2yhujsfyv.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qychbfez.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2wiokeysf.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2gamtvscv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzcbsii.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhkgqdt.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vraokdtl.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2agmvehwb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mihfpgcc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxqyynv.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2iqrpiera.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2jkurrsls.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvlkhczw.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhwucfud.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzykxyau.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mleoskvd.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwrtjid.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2tkvcgjfk.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2bxlgxcdu.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2hliidtlz.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2skqufrys.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmygmqq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2goabrgcw.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxzqrrw.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xpihklao.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pkuezckz.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvswocl.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fbuznjtx.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2uozkyzcm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2djitxpdl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwijxyw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2oktectpy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmzydsl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2xodwgdst.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2pinwgijn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2xxuzxhfs.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2nalsukqq.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmajunt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjurceb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2evdyfxcj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fcyqhkrq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xflzhqll.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2acuycgda.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2rlpfczky.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kvziwjmi.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2irwqfrsl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrfbtln.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2owcauaan.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2emypnpts.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hybscxcd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbftgbc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgptpay.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjtmimv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqncunoz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtsnfyp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2hnuynnwr.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2meqygjjx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mjaqwmvd.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgxphra.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjpqswg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhsfqemk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sckcfriv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eulonwvr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkyuvtmc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijpsgryr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwqouhl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdyxcvdk.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2fbviuums.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2nniglsnm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2whxtlvoo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2tflyyocf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2tutlthzl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmlisvw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2apxoadma.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgvtaxd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2nbykmivd.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbtgnnp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2phijvirw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmmbron.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nngksxsv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqficyl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvigpjy.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2oiktkoqx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgogiql.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2tumzdhoh.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nhbhnnlo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2rnduhbum.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hdorkfza.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xleoxgdh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2djhvwqlq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmhhzrj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2soywshrl.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jfsubded.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxodkmlg.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lfaiewnt.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrdvcqc.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xieazkvj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yerdzazf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fuulbpdj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2svtfsyxa.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2runzwlpe.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqyvxfje.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2iiknwwlu.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2aujhwzyi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2azulpbmo.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnwqwdmp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2uidalmxr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2rlcgnycu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2liocqjga.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgcjlddg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2fodctxpa.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2qeazrfme.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ycypxfez.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlxjndf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2enmirkcz.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2nftiifew.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwgbijtv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2yksgmpzk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gaohfqob.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwdwwqv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vrzloihf.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgqdhke.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfsngbc.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jtpdhcws.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2grrtcvyh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgsewix.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lglbbelb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2crysbtye.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vikowjlo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2miiynpsk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2glzdhkea.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjchiglg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bzeqiwli.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlrdgqe.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqndnbdt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2efjekdmj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wscnllij.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnjdsel.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2beyldaug.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2epscgxio.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gojiirkn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhumkep.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgeiqda.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtgqoobj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yveqjgbl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2pabfqzsl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2twpcjrnp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmfwdat.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfngxwg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2lklkwsnj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2ypncqaag.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2cubjmyhc.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2gcprhjvw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ykaftrjp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2frxornqr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqfipci.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jdiyxlqc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbnztpv.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2adtcxgpb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sumjonwk.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2dnutooxj.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2qsiawtix.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kezsbsxu.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcqzqcb.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqlvbpwv.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tktythde.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2certphpk.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2odwncszf.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2siikmzld.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2whmrhhjx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2wusmtbes.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvdtkpg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbgjabw.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnztpqx.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2empumirs.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2khgmvgas.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2emobxmoe.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrkjggly.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdlbqls.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2wngcfmep.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjdxszb.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2evitfwah.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2uavoiuzh.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwgqkowr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2laoyfvdr.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjtkkga.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdpunlj.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nmaygdbx.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2pprvdelj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmnvevb.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsyyqdpg.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxhkfln.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqbmcru.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgyiqhsg.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxejrwu.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2inenoypj.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnqvmfz.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ativtkng.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tikuclcp.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjiybbm.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hupxkpxx.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrggjdv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ttkvjscg.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lwygrwks.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bnctnbao.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjwspkg.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzvuecm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vajkwffv.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbwtvfo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjunzmhw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvtxxcx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2vbblrbbo.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfvtztf.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdfhgwc.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2znpglhih.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2wohdytwf.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nzewwqpn.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ofggzeqg.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpjhdkh.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnflwcj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2krmkqtxc.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmhboih.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pabmjhax.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2sizhglmf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwoykmk.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdoflzg.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfoazje.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dakaycmx.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2smkodpuq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2uphrnmwi.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ecoobutu.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcdndjj.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2mqolcduz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2iiospecc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugctoyge.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2dovemcsi.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjiqxjn.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpvfrlc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmuaijpq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qymgdwws.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qslewidu.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvyunoh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2oixozujf.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2aelyoiio.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ambysyni.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2kksbuazq.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2fetodmis.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2oivxvlbw.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjiydex.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2wavhywdy.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2dctpuvti.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfyktww.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2olyfcutw.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzziivql.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwyllsh.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2noknvtws.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2smgyexxz.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2exiuqksi.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2loycvemg.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqnwcxp.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtxxtxl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzyrddro.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmghkkn.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aruirwyf.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhemdfwf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2edlvwjaq.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2duqvfasv.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2smpvtoam.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vnoknmgj.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2secpmvvq.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tnllyowi.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2huvphxdr.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gswpxrjx.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqdemtw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzdeztm.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2flwpcnla.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmcuicp.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmwcsav.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2bndusvcl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2twxlljmp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2coagpagx.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ixspklsn.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tfefwzdv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtrxseq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2oaliposv.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2qycaiqdo.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tgevcxyk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvmoqat.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brrwmwcd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpuaibv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qesfebwj.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyalflaa.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2kldbbojg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfurqzc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhagvgtm.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfpaten.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2oplncbyy.html


<!-- 参考信息 -->