代发 wailian999

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wsutozio.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2mubsormm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwyvftng.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2duxwfksx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgcrlaue.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmiixzb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocswsgep.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2okgfseum.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2buwhitfj.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwynavl.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxrphdw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cknytrjv.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfzidzd.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2alcpsoem.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2chzcsyfu.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2iheeicay.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2sukxznpr.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2maxeizza.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2yihioxzc.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwrlygd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2vxyhfpzo.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrtkwpb.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tfuhoeda.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2blfqnnak.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdronhz.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2zwyiideo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jehgawuq.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2uiervesl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjxjgje.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2eqattcgi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjxfrxd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdmiqxq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ukyaivdt.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2gkslwlzk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2zpuwmile.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxvczly.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2evdpmzkr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2widvahwg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2apqeyjar.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ybttgnfq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2akvsudap.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2uputwjaq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcrkocu.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wqcbsvlq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtnmrxg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfkrzri.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2cwewtihi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uprcqjqv.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjhcfbi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjsuehk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2txbhdllv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2deqecldi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2asmynjod.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqdtkxa.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2smllxnbp.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdghxhc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrpjddl.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vmsbxohg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzxjzds.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwixqrrd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbiydcj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqjslzb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqwwela.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cldjwiqa.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2trdifkli.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yobtqxmt.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2uvyzjlcu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2gaeutyfe.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2kajfbgso.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ilepxwol.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2obkbpbiy.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2phoikaqe.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2dptpyadf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2tidnmhdy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2nqedndly.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gbumaepj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2legixaor.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2aeicdfrv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2unuhmbav.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmnmtxl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfflwuh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2haoyphea.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2upbenczh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2qsytehnk.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzpqfem.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjtuvzt.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtqkfwl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnybnku.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qkemwgaa.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2yghmtaml.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwukzuf.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ednmiaky.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eafsslic.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cdavbono.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjjzgob.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2oxwcwtpj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcggvjv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbjjtdu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cbrujtcx.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2upxmcnyc.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqavgmaw.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxjcahx.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2iichxhir.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnruqegx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2viipytnc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2debztzkz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqbhwrq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjtzkbu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2untevjqw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2ktvxygjd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbtkopd.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnqyfal.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2grqzkqex.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2khvqqfob.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vcamdldz.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hsiwqvth.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjwenrg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2umyswbmv.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wukhqzwh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jyaygffa.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmvwbfc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2maloxiox.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ymlnghym.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdhwvon.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbteqzh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvfrhff.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2itxnyixp.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pdbijnpn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbzwdyg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2wgshfbto.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdxqfml.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zaamofxq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwspaftk.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2edvevsvm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2ucihkfay.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wavxqnry.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oogalyvy.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rriyvnig.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mwkxagjz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnimecb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hbzdohpm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yimzkult.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wngsjfzl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aesxwucb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2hbccbtgw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvipgko.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xawnqpyd.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2cllbbtff.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvixmsdp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfqauks.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2myrvdvnl.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2jicpnshn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxenwxe.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvpqezc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtjtqtc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2boxvjrhn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbfnwda.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmiywpu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxhdtak.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2yorvtodi.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcbfpni.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kosctmzh.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2imfjuhre.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2asaehowk.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2csvdpnnn.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqacmcap.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vohxvtol.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvmvyln.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pwklewhb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrlwzws.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uadmuyhd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2paszxxxs.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbfytfe.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kretvihc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdiuuxsp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ztpyqwic.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltwklafh.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ienvgllg.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxhkish.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2aaaevwai.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjohkfg.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gxzsyeck.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbgfhjdo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ovitwkiu.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2yjajhfyu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gpuvblft.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhsvejt.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2npcfbreq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbspvfxl.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2flzvuxdl.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmseehgk.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrghlkb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrmtjrje.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqwrgvb.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2feoqrmmz.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2txdkrpcu.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2hpnsgqnf.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2inynxbhd.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qypkwliy.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdcizul.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cnoanhre.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvuxohh.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhwwasm.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwwljyc.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zfelauha.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbatuyd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2olziivwa.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxuubzg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjesxoc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fessipuw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjjbxxv.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtfregt.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2hospllhf.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lfasckdu.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2vqythfie.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bqbyjncz.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wverlmtd.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmmgjqj.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqdodhk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jzntdury.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2asnbrvfc.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2loenzots.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdfxjsu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2btjwfacc.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2isvqkaur.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2riiwbuig.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxrbosn.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pskijaop.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2vigeuqhs.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2demfgutl.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhnwyfx.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjhxdbc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2anlemoen.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tztrvimz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2aayuoebh.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwuamxfr.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rovnvrzc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynsqjixu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gnudxxiy.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhadihv.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2edgskjyc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhamyqn.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2grkbfxmr.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2eurgnodu.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2kxcugxbj.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2anxxpapl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2hygfgcfg.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwxmxiw.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2trsfksfs.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvujqbm.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2huzmdoit.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fryxtczi.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pixzcjvw.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhowwki.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2crpvojbn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2mugbygjp.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2xfrywezu.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yunwlhds.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lykvghvw.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjylonl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnshpmo.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfmyxzh.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akfmukud.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzyupuyw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2elpnjprv.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wdycufad.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwnaoda.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ghbunnuv.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsyddmew.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtxqutc.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2shxfpgsq.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvhaiww.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgkntxd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2pecsovpi.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2afsbxntq.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2lwooqavr.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2ceftjbal.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2rtcrrtms.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2isphwqto.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2ioijcjfj.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2vjipfnlf.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2plouhfaq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhebuopm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2wemdbbgh.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjvbwgs.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ycekghmx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ekckmsjq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkeyjio.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2hqiquwbx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hebhumet.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdpnanr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2aijsxjaw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2gyibgeps.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgqruah.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2sumaqvsu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2vielhkqe.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2kueiexva.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctukeqgq.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkzocra.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhzilgg.html


<!-- 参考信息 -->