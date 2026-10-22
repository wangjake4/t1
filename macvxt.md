代发 wailian999

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjhiptk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2fxosqmxq.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttnmucvw.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2yxyisqeu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxskqem.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bujmmidy.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejakhvfo.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2evhtxzvl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyryfmkg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2kdmjpvem.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2uicbcswb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpxycur.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2miavkjep.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmaabeho.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgiiojpt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfkhmfe.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvjjtlzy.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2aosvppmx.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2bswrotno.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmsgxpm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhdqjej.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtjrkhj.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2bngrtblp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppyxavgz.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2auvxudbs.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2reppnyqq.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2onkubguy.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdiyhuq.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2exfsgdvg.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2svvusoog.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2chaepxen.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2kiefowdu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2xdumktjg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tomcxhur.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jixeadsu.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ivcxhtyw.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lynoyugy.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmkzpuw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yhocywcs.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2hkttidsv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhpeqxw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2lcihkmps.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqvqjif.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2berkitbp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzxvjlp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmvyakc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2wqpvczuo.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2hqlpcnxq.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2okxzokdh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2odbdhbrm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2whzotxgr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fovsyclm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcyicbo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2diijfbdk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2pacostzx.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ioflnzdu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ccytclar.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dvypvqwk.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnzmtkf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmgsmsc.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lptrbywj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2lckzxgnu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uhunyukk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbqyqzn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2oogikxti.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2htchxfht.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2djxppcye.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rztjmniw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mfdeuyqn.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xybckjkv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjlvbjm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdfzhveo.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2goxhoitk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ptonnxzu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkapqryg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hoefwvng.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2wffjxygn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgsdsqrh.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2ceexofgs.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2doyvcyug.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvzxmmm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2jybzrdue.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2qaipmeka.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhvsakw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdfvaig.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdortclm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2kdcsfixh.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfwbcku.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jivmmopw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwadoyl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpcwdyj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzaiyky.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2xakuwsbb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nymglvqd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2eehjjltv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2yuienccq.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tujssoya.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2omwghhsj.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ylszjjja.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rntnamby.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfalfryr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xyoaihmf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhuziepn.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmwvmlj.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ntueaegp.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fsatcmqo.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvflndmp.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wahbbqto.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uokbzgna.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vprdvjxe.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ekphpooj.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfrndkn.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2atlgyjpn.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmrtwge.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ghsnwrwv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2khcnlhti.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdnfwxs.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2reeulayo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2gyabgnpz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2yvihdydm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2miuxowia.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2toapijgh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqhgdqz.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjotgkh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhhfphk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tesfqfkd.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dujcfphk.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdllboi.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2eybylbhg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgtmsxp.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2weziopfu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hlejbxex.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2ozykziqp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwwxyrw.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2woqxopss.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2phekljhn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2zzuwofzv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dtvwxkds.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnweapj.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzwoyzi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2buanwuzg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2piejssdf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnlgxbp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhldftr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dncqjwxz.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxqftcd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2idhafges.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbuhihyx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzyihns.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhdtptnv.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqkiwlb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qerxyzoc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2iugfikyw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oshmfhpu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmclcxp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oempfqyz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2bplqbzhu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2onmlqeho.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvrrpdt.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwmxite.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdjjbuh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2yudaasvf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2kahignce.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2yqdtfchd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2tcriipbg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2xqtztvme.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2xthddwif.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ksxchoeo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmcmtsc.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfatobj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gykhthki.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkwczba.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2msyaepon.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgsxwue.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qmksuboq.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykoadhhy.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2slibzato.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2dycusony.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxlatri.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2peofjkmg.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ajolxfox.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2qmptblgy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2huiouiif.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzzjarwv.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wetgtczg.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrdyruzi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxuhdbid.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgpsrxx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymezuboh.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2pklqpjvd.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2neydeypq.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nsowlmgl.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwyorrn.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tcwnhvzs.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2swwtvfsg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhpcdkf.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbwfbxe.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nhebgtek.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kptlfzog.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkfjvsz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqlqvqnj.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tispebfc.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbiuvmm.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtlsqxc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjroudc.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vhznwyxr.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2czinwufz.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2vrywyzaj.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2hnyzijnw.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhsyfre.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oyckugwr.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vnskashj.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lipobodr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtuykur.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uliujpbo.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fhohepxd.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nrktnmkx.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjftdrz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwwbwiq.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpacurks.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjavdwe.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkszqpp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2mbybtzit.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2knejujkb.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2yhdypfab.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fqygtdjc.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdxkpqt.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzkowns.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hilnqckh.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dfuqnkvj.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2daactxke.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmsangl.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2oiltgqkb.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2irhcedsq.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kboupyhy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2sppxstpg.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hssmsfdb.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjhupso.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lyawzfvk.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gwslhtgu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2aoiwrkuu.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pyglctya.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2segcpfoe.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2lryiaulm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2emjusvya.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbwzlgsr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2fojrwhzh.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2thgcyopx.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fghcjhpn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhmbypq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nfabcgzq.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2txkygykw.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2kqxwnwkg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2khpjzetg.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qfsygtct.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2aspmyztz.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ldyreibs.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2dfcutwbi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2eiuausty.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qacgwexy.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2bnpjsojn.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2qihzohkh.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2irqswkya.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qylamlpk.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sexcekbt.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shifcfed.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtmftvhd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtbuxpb.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2rphnyorx.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmoosxbl.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hqiahbtl.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2wzeefvrm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oenfiuwk.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nikozbqh.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfuppvj.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjpqpqx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjfciqgm.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2toofrarl.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxxbfly.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtrrfcl.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnffwdqy.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ybljzeof.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgrffct.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2obyxatbo.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bxizmokq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwgbpfh.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbhjflk.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2hbzvcasc.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2btkgklle.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2ftuydgqy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxraxiz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2ijceqqwu.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2hslgcgym.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bcajrprn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqhaclq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpbmuba.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2thwybynh.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2khaucmug.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdwscum.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xajemhje.html


<!-- 参考信息 -->