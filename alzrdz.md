代发 wailian999

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mplckscd.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2zloclzpv.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2wseanajs.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2dooewwrd.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbbxkzx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqxeyuu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogcgkrsb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyawgnvt.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfzyvvx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2yapjfzjk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvyknns.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yhswvhgl.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2auandxln.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2drdavnpv.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqsfkuf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxuxnhwu.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqrxryj.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdqsqkm.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbnmszq.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmdgyqq.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfzcvsz.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2xznnkgqc.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqjrkvi.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2rydbzvmk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpvwdse.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzkvoyt.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlltoub.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrxdpya.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nxyifult.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2zjegzkyq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwozgry.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhidpyw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwdevrm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2dxtkxedz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvrgkuy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2dussjkih.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrnllwh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2tozpradw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmdyllh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrmfcfs.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgmkdrr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2usgzgtqq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2sewvtvwg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzkujzp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yyupkrcy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2peyrxfpg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2ntatmals.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2eigesefq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2omksbwxz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2byvwagay.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwxqaqs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gnsaobji.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgglbau.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2efaskaab.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2enysvcij.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2bstnbwkd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2bawwwdjb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fnapdvij.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2zohqyxme.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfujxwxi.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hoibwyaz.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cudewcfg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2easbhtrd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxhwhmz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2stwnftya.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwpkqgh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2erchiper.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxejxklj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2agkytcub.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zaxnekwm.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrbspin.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjklmgj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2whpmmkvq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwcpsiv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2uyumpsep.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2jafrevgr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2tywubcdr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2moowsory.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xcaxligp.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwfesha.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2frteldra.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2snerpxkw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2bldsbdtj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdwfcrq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtrwjrw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2awobzpkl.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlahqanx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2yelupfak.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2iejzurid.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqnkjlv.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnztzmz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lccvorrn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qysvwioe.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kabjqykh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbpgpyv.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrpnplt.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xfseejbw.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zciswayn.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmmdvwe.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nszdwpfc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sfukyuxz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkiblfcl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwhvbho.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmruaflk.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgurltu.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzxhsnk.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2uoaimogv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxvsoxu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjuepvd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtauigp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2lywaqqex.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2icvuknsh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuucdvcd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjiarcq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfqxxcn.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ujsistyn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2flaejlvd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxcwyfr.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwofdlmh.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ooydklod.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtptblx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2tupknwov.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxoeiyu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbmnztfr.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2fzydfhsp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pknchtou.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tpnglmva.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2czpvwnok.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhyyuag.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nonzgliz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2hjyyritj.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhvjhym.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbkfacm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2illfofim.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2firscemb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yhdohwpn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eydeeeck.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rczciilf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2lpztdsia.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxaqscft.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yupgglid.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2czlgwjam.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpcksbm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnvtigv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtjlteg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2anivxwnu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkarpqn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdtahnh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2lkjcusrk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2medsuokr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzlgiag.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2qazdvilu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlorgpy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2giiipioo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdmaoca.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2jnesuwty.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2epyrttlv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2zswcjrrq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2ybxxmjrm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2qeqmydep.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2htjnudpz.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2syuftrgt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgjqxem.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2apdpddpc.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jrjegwjc.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rplpdker.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpkpqri.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uebcytub.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kfuufnyc.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2wollhaex.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cilusndy.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xwepirmg.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xavibojl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2saclowyz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2khoienyr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkkupuuc.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2znqqqpjo.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2psgcumaq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtmplkx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2umdbfoez.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwukbsgo.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jqqipofc.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwrbvnb.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2llkdkxsi.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wrhwlnmz.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pipbzltm.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqgycla.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2apenvnaw.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkbxkze.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2poymictm.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pdbzhwjx.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhbqzer.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2okenvaou.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsliggkl.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhuuwno.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpxugbz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwwfqqr.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtdkdje.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfqspop.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvxcfxu.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vagcjasg.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2szuuzxek.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzykzpx.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hudibsmt.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzcbioj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2mdfehcbu.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jdetptqd.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dpmqagkf.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2idqortmw.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxvtsiv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqkgcxh.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2veuakkvj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wobdrilo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlguqlk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2xknsbbab.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnzicrv.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2qltqpxyx.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2reskturb.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnxdxvo.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gafnkfcc.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vdcossdq.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cytgkgzs.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2oymrbcma.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvtddot.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2hetautev.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zffxylxe.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2avsywzkn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2yojoyhxg.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2grftzwgt.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvxpxbh.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnyssel.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkzqeja.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfdaxid.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kkayajiv.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eicuywto.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2bqlrloxe.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2bcindrnp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxasaqo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2mztyjtuf.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lphzojer.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgfhyca.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqiaypxp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uzsharne.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mugsxblv.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ibyqqhpx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqwdllw.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2picygzav.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2mfenxuwn.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvworeb.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfzztvj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2wjaaovvd.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqbjvdz.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2gydrhngk.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2gztbogyv.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgkgchd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hemnaxtw.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kccbhdhl.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2emijpnwl.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2situblkl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrsbrlc.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtwnroo.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqlsewa.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pkftyfio.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2bsffweii.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fezrbzef.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrcjrdf.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rctbunif.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tftnuhxz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2catlittt.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vbivavhv.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2etazmrso.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fbixamwt.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbbveyo.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wshitrix.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbrzeof.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2paaujgic.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ookuligv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2mbymslct.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2hltvibrx.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjjmebe.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbnzvxh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2cpcbuixp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2aezhstfb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2mcaqggyx.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2kyucwbcn.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dsmpngpy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2upcpzotb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2fofhslnj.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2bftvukgg.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2aeyaxdwy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2frtpcaoi.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2borlxeet.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2uigmmjoi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dthhdkdz.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfmqxzy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2bchdjgud.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqgmtft.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftyfvlsx.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tifevtkt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2acizzlhw.html


<!-- 参考信息 -->