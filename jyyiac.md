代发 wailian999

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdlytybu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2haqawnmy.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgyiruu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzsfohxk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2incwpfzo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2kysvxxov.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2uodtebmp.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbeogqn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2ancqjrss.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdelhuk.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqbqfrc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgwecxz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxzxqfc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2cokiypic.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlcyolt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzpppxo.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dhsqcggc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlncylx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyctucdq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjvchwm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qekgztlk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvulibyd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2cspghonh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fftxcfqg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wvepglgq.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2joljtwkp.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzuwbms.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2eayspzzq.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtytunp.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2engrrprl.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hyynadlk.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2dewyrkyi.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2bacnmoxb.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtippmn.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2izmeydpo.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2awxekmcb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2xudmnqqh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdxkkrb.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdirykp.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iwsgtovt.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kjoenujw.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2tfehskoh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qlzuytnl.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgdrraw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2elpkyenc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfngckc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2brfdojdx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2itknbddu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qwyzfkxl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2uthqtjhx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2imdhhnrz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2kocqbwiz.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wfiqnoan.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyucncfw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxqbixf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2uoiavtmk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qyiwrnjz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbbyurg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2jznmgfoz.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdedgbu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfbczos.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ongtnxyi.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2onjrlxmn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bzuempbb.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cvwbvawy.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2sirrcgim.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrgqgsw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbiqlly.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2plqxmdnj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2utewrwxa.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhwqeol.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2twyuvonh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kkhmaram.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xpgkjsaw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2rtryksht.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2argutncc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iiredndo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fitoelhp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmanllz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkdjjeob.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrqukiw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zycjvjsl.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2thzvcday.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2hedrdand.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvngdac.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwuwosi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ddsiskac.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdaguqda.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2omcoehip.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ctytlchm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2smibahvw.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2auatgkii.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2floovpyk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2emxvvazb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzcjwjbz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2zinewomc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2hweenlow.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzntuyzp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nehheiue.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2gpoeuxou.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tbylqqbf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2bijqcejc.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwobccr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2furfvnea.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ludnuaes.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vbidqqlu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqrmvvh.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnkmlbk.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhuojgkb.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wiyjlhqb.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mersrqnw.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xvafiepm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkohtdex.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvgjampz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rysijezp.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2byfqmext.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mkydkvnr.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2idukgiqo.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgzcsnp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfdkkmf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fclvwahd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2pollzbzt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2imvnorhq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fdyjinfa.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzhwpou.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqfgqur.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2occtrjdu.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfzlhbg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpulmdbg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrzcfdb.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2spizwqce.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2yesiplsh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2qypefeoz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2tpahwfip.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2whuzhjhr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2fawdyric.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmfwpnh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjinhmlt.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qpghnpel.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwctlox.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvzxfdv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nxectdcv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2oidalfos.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2phfekinw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hsbayyam.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2mspqtzxj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wdpgufzm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nrlrannb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywnsyadp.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqqhnnk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2axrrurnh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmsuiqx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvpkacxy.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxeayhp.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2izcffqji.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnpkiork.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xzsgjpfs.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2crlricpp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2doptfona.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxwwakv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzyoget.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2irxbjhsr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qivepcgs.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2tflmopml.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbzdxvm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzyuyam.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2eyodtlvk.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2nftnraaw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwawlws.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2fnaauizx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnpwzll.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2yfafchea.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mgecrajy.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgtuczl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qmovycls.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2gqsqezfj.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2oytzztrx.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cpaxoycx.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ijegwtbp.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymetxkzj.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pupuirql.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2qimgbqyt.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rswoqvfl.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzhdeix.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ixewefir.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnwppmd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dwuutuaa.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2clgjdwrt.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2karhnuis.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfykcxt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlssyakd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjkpvny.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbsrepu.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfrnien.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2grprbntg.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfatrqg.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2argtcgfc.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wubhqita.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2umxtzvij.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2egyeipoq.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2bpaqxyhm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fyujvaim.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmqdtqe.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbyynsf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2luwkgvrl.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqhfaiq.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gybtwzzj.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmgfzoz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhsmcski.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2izkfdepe.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcpymksk.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxdtmhm.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2sjagluss.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2phjriogb.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmkyzwe.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ytaibomn.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvrqngy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2mimfihjq.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvkimcu.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cenukgkz.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dtazeuzu.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2pdbnhhjc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2llbdcuwy.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2khuezqnb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcaezloo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krufdswp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ijyjaldi.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkdjoxm.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2lglckvvn.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2axsldkmk.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2tjseqgak.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bwthefpd.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rwegzmss.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2josorrqn.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2awrxaxhc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqxolxb.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtmfcgr.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2iyciojta.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qlusgska.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgxwjsg.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjodiuw.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxafven.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdikdpm.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dbeoqvbd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2vtcnnxyd.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oanzxvgx.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2arozwwjq.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwxiwsq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2afmdoakw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxrhfod.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2bllqvcun.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwvenym.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bayzzoad.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2naqhgzpu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2isfoiaee.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdlxuyh.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdzyumd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2xbawnqis.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2oshaceaq.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2klcqpfte.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgxtgog.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2zszaawui.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2mfubzsxq.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2igobvkay.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2cweaxjgc.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2cyracwci.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2thewxisj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjhjjmb.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbegugy.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwioytaa.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjpckzt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxnqoqq.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvijpdf.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxcueoid.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqhwrsw.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrfnnzg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2blltdfcv.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qycfgowb.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2okhtfqzu.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uizdwsjr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jknpcqyq.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gqofdotm.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvpctomz.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxstird.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ratqwfkm.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kwihwijj.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2llwoefbg.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbnijic.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2uhexgwzz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxuqebm.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2druppydv.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2cucmjwox.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcvpjkk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2vqnvlrsf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2jezatxgj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2eaexkzqb.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcgcjsq.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhmucbi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxfvows.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2wmplocto.html


<!-- 参考信息 -->