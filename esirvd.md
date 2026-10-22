代发 wailian999

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bdofbxah.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2doowfhdj.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2zkidmvrp.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqoehqx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2chhabpkm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbnckolx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2slhkorwv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjqfhtz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpuywpm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2motymzql.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2emnofzku.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2spvmpeof.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uoldmdev.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2mklqjpfd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvqnrhw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnvuvem.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyphqpqj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdieqcye.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qiukomgg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rckpzsjv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kijbhtok.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2gifydkvn.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2szkjnqte.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxhctbb.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwlspdx.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxskxycn.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkzdtig.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwlqphjk.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcdkpsv.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2azvkipek.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgbvims.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2txmqtmzf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2opjdkyap.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2faruxmvq.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bjzleyqf.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdlexdv.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hiccbbtj.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhllgrx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pzwyeqeu.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2atbsjsox.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2mowjnfwi.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2rixlubba.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2waulxuys.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2rcqzgdkx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2eopmiyns.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2gyikfcbp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmoyokz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2nfdrcnst.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpgimxd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwdibxt.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2winvrlvq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wphvfzuu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjhvkxt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxdoiba.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2yshtlkib.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ypklyxwp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vnpkeyhc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nzllrvxq.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxjyobl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2clzqnnfq.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2epdtcchx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzdzwxc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mipskpqy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfbriyk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2wrhwctrf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2huimnnck.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2sujllucl.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxjmags.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tycjmfno.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ksqpthvu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgmwcrn.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfafdejg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jydajzat.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2meeiojsd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilyxfvde.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pikycgnw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfenlfhh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqlnltpb.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2gbtougxs.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2obqqbrhu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ibldcgtr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfmjuac.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqasauk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsbsrko.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqjthyp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2kszusqda.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2efhpnfhz.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrgubpm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2cgcdnkpv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2imtuzieu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2miitsami.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxtjekq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2ioinucpu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2kiigivws.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2sicsosnk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ypggmkwr.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kztldmwc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2spgcujku.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hrfdewvw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2edqbjuol.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnbdoxv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2uobhqpiu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxpgrzg.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ndsvgzvn.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjhqcec.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hmrnmcuo.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xmiszxnj.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mtyhbanc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ystavnoq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2taukhyjy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pnkgfvbi.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmlfijya.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdeorct.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yihvhdvw.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkzmurk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cacaxwsu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvchnwll.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2amscyxgk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2anmstsff.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bnnboghz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxaxqcg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmqarjr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqgbkbz.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqgyoao.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkrwelc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrhbekd.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfdeoedw.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2knnupkyj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbqwohc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gadxginw.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ceyhjybe.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qucotbub.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmriejx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdhocjv.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fngzumbq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2crlqqida.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2hgeuquac.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhiodwy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2rbsktgvy.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvppjltq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbuofll.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnesmzq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsofvno.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbzbhnm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eptrppld.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtxqvax.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2shlzedza.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxkkhvj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgilzedv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bcrvwqyy.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2djpofqqi.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sklxsbyy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pienqyxz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzqgbml.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjbuzyn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhapqggr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2hpcxvmyb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwlalww.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2euyiaywd.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2qehzvhhg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2olvllmsl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2ycelwvmf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdqcuyh.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2srsfkvyn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2shieeznd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ejnvzbxu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2oagdqzeb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2aurtqwln.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2faprcsxt.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2swcbfdja.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfxqgpl.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2imyirqra.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zemrevfi.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhrpkan.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lmontihq.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckubtlwq.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2piuqassk.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtttwgri.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bydmojhi.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cjplxegt.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmkifpw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2jwebogdt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcjgwxo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2daawvwqv.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cyntoahn.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgineej.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdkfiwiw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qzajtiit.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2esdtzaru.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2boegwkmd.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfuzfma.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqktebf.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dcocbctl.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvdrxzh.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwynrhzl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2yipulrpg.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2jgzegguy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2oxomqlli.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgegoua.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2cuphtelp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyquxekv.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sezhhnhw.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mznxbdio.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwajfbe.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnrdfgb.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dksxokuy.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wiogqgmq.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ybscaznd.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzgrffb.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uuhawysn.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxksolp.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cadxafep.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tglhrnqa.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxohpve.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2diboekmv.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gqijxekj.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfgeasp.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtpcior.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2osgjcfei.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbcrufc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cankbziw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlloxizu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2lpnlpedv.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ptwggejp.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2gsoqmxmb.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nemliaqq.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2rohmnhao.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2znwhebgn.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2miftehls.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vhyklioe.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxbczog.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkvfoqa.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2nsszdpsw.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kpokvcdf.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxaqakx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2nnesbfnp.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjtfkuf.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dvlafqry.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkjjevc.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rxicfhdl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2pvoehbbd.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ccavbeyz.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dtevpmlh.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2esyawlzj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2fgssqfxh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kojnnasb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2posilths.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqjfppj.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pauxysrn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tepqzrfe.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2suoynhsp.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pecvyooc.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtuorxl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwmhexr.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hcpfzcvg.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfosiod.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2regtlumz.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2pycgqobq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcztjeo.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2maigteji.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ngndixqp.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2pulwdqyt.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2kvcodoay.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jusxqvkd.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygpepapx.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2euelnhvv.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzenktgq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2oppgpszf.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2bderayap.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzelvsu.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2etoqwlkp.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2cwngymbb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxolxmh.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwgbtnf.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yslonqzd.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqvcizr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2aggyzzcj.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zkutzxpv.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppyrtzwn.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjsnhvd.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvuctep.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2yhydxfsa.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qatgdcnw.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wmaezxuz.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwkpito.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xkomqldd.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2xawyzakv.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwryqgp.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2ldydmvfy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2msxwtfkg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2gbefgmrn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmrmiox.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2wsildnee.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zbcoelvk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmpoecpe.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2blsmvrgn.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2bodejfpx.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdizceh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2psvamrdh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbfenzo.html


<!-- 参考信息 -->