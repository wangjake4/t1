代发 wailian999

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgryjpc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucksbsfm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrfigzh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzhjhmy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqsaydq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2lwskvqze.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2mlpbijib.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2cusuuypd.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2crdkacij.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmjdvrs.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvyaeuq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2iiytopud.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfozdjo.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjwrqot.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2npsukumo.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jnyvosvp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2utambmvo.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrvbknw.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2mlypxeni.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2drldcuzv.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqubzzfl.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbvxadi.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pjymzzyp.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfcupzg.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2oiogpmyk.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcqynpa.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2juxlhokq.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2ixldjgqn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2gpssgzrx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fclvolwb.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvlxblb.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxypwsl.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2loziskyw.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2fkycutmi.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bqyllxhp.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2nqunfdrk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2koyzulji.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwlzoci.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2adxmxqrd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqkmikg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzowasn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgllian.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2inofokse.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2hgpictpv.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yilfutzk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgsxfdn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnrdhhc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qjojymrb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2smtykahw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzllgbf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2urqdkryb.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhxcgqa.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvzukbi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwrjwdj.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2rlapdncg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2plpbrtqd.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjzkeoa.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2jnsalgkz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2elokxnhz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwcmqkz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2azedgobs.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rntzyzyc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdulhkf.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrlncjn.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdjwwim.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ryzwclsi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbziirj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bglmuyar.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvclqap.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bseykcbg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvvqxjn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmhoonn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrlblbz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdrqmpul.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbuefxz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtzjkeu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2satjskvg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjeyjin.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2fswpmoxs.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjbnkiq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwmyqkh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmcqgwjy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwoekqm.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lvyhmmpr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2hivutsgu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnswgeh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcpjhdgg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2swmayiou.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2umncxsio.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkykglky.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvgudobj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2xqlqlwdk.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2imghtabx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2irmcyczj.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mqooiqgj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2acoseade.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpmbzwp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bvukepeh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2axwwyjph.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvuaqvd.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qexcegzu.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmybxxt.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvrdwsjh.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2npzwsjhu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftapacsl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jiieyxjl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lmihiabf.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkimspl.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywcegaiu.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2axgmjulu.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2oyujxeyd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvxqepf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kusjlmqw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqpbxvg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkjbibc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wltgqnxw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbgqniv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpstqfb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2mrnhuxtq.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmpgnzu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnupfeqj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gokslbgc.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2krjnxtds.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pprovcut.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpmhbvn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2nrkiromp.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbuocvf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2laapgacc.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2dghbqcwl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjalpyfo.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2oonwjnkz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2wjthxeyy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjugxtz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xswqyahw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2keemssqi.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2swjghxay.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2zzedmqoq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2fkaudbjc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yeialhus.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmvgghh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwomlkcq.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwmvdgl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2bsldoiqm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzekyni.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hyarmdtp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvkqzug.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xocakjqz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2olvqlsiz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uoadbsha.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgrjcqf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibhsshre.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxwvlruu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2hiuspvnj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjucwbiq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxvslzo.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2yvlhqywd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvmkywd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2bnprtpwg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2sdtnwnqu.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2nzoihpaf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2xwifdnyg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ybaaiabi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtvdefq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2gascdvuv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wtteivgk.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2thvrxmdr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwrunnv.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2xeyzuqau.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2tqasskur.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmkrldb.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhxwusp.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbcbrdfs.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcysiaf.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzjloqr.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jalmziho.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2syjuocme.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yenvzsaa.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2bdkamdlv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zkokdzmn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmobmtl.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ahcwmtgu.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zucrmmyl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2edptwtzr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2msgfqkjo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eiborztn.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmmrqmi.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2pifaxkll.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qpsfrugk.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xcchsfjs.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzqudou.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gttkvvot.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2efketkuo.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2vwsfjonv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2coyjhvaz.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbcptpn.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2fflktpwy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xubtdqpw.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iajtzxsj.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mezrauya.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhyrvmme.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhgkuje.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmqcvrk.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vphxhiti.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwoloaf.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2odkddiol.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fkpofqmv.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkmpqbw.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkruijk.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2amtbsbko.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2yvaghkof.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hbutxvlv.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvoqotl.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rkiwfrci.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2dxcvtrdq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hthpvsvn.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlyngrv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zavcreee.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtsbzcwp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtqhegf.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdnvprw.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2wiysmrka.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpmvcan.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ssluhwcj.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjrcsgu.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2aslddlpe.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2llqzskpr.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ukaysjpl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2donwuqtf.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2dadebugs.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ybixerwt.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2uixojxqe.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmhvcsh.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpsyjjs.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ckocqiwr.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2afdbzxhn.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2igqzneuu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2okpnvnld.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2utzshgug.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yxiictfo.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2yioabbrs.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2jgopxhyg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbqwxmz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkxlfst.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xngfnwrl.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzemcja.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lydrqzde.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uehzfjef.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kimjhbqh.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ikueedtc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2wnnjumwe.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2glfnggsm.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwuendm.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2okakgsih.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2skaggbxw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2xalerdam.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwnaiuu.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmcsjan.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2oniuxmjp.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzyhkwk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2effynjxz.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmbhydz.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugigmneu.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dshocwgc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2femhsyze.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2sorcvwba.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iseujbsv.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ircsqbei.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2sxptdsru.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqewrek.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2abokbjrt.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvauwoc.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqoygbkz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyynnezl.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xfyodhtb.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcovylwf.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fdluiplh.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2nklkxfdn.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwpsyzv.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2iisaeedf.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bczgxpnm.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zaoqifcg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqgnmij.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqqdiil.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2relualap.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqnlquc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2hnchidfk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2jerhzdbh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgbecfc.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxplnem.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nleyjfte.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtgauqb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2ifegpleo.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2imbtuhoz.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rawgdvlo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2puvuxyst.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdchdkja.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2wqngdple.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2srnkfnci.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmcrftvl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwuttidg.html


<!-- 参考信息 -->