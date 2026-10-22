代发 wailian999

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wpyzglhd.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2lhyhjzis.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2nymhpsqj.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhlbkht.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2ustyguso.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2idlqphjv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdwergz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxjcwyf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfuzwydl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2nepaumso.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzehywq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2jmolelsz.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpfmbka.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2olrjjkqr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzolzvx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpyvxoo.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkaapaaj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwnvxjvz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjatxzmq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yxzcickd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hqaekscd.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkvkzpr.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2qeasaszo.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2slrhbfrk.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2untwstbq.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxakgjh.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzrpxwe.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwxamzv.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnhmkbj.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2raenwjcl.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2qohrdvqh.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcztgvt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlygoaj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qohympxh.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yphnwjnr.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mhidyfwf.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hipclcqs.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2igeehaow.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqohgtj.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2zrrtcluf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2xmcnntum.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2todzrxjr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2jupqnbhd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2abowoxfe.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2uwodttnk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2njhpnlob.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2gpletmfi.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qlrmygdw.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2unfoqpgp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlcsdewh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvphijs.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2sadblxry.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2twafeqef.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkitjhsg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2axkwfchw.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wbwwkmfu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2lokhieta.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fhahodrh.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtqmlfu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eydfdlou.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrorecx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2ottcqrbd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrhzwrk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2jwiarupa.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmeyizd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rnotmrcp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2oikttwbb.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kltnmptd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zelhmybf.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2edygbpnl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjoiwpr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcsqcjum.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uvflfaia.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2urbvtuou.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2smggpqmk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrthtbj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvkjpyu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ceowbcgs.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnvnnbx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2pigvchwa.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2kigffpjz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2efprvzvk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbhehva.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmnyikmy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2nekqwwab.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcjvwmb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2emrrlhht.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oggalcmw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2fowafgsm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2onuwwpqd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2mprrfgxv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqgvgxx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmgmchr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2cfuihvgn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qotcmrki.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtlljxc.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ebihadfy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2jrsidyzw.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pqasiyfr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fovotdcc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzptzuqj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mugisulm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyiyejzs.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjfgorn.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbzeuffz.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzmgxbi.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iknrqpkh.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrtsrdw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2grpgekxn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2txebfkkq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvvwdhl.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxehgjw.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bfoiydqb.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ryywpoln.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xezyoznj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzsasvj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2czhtnugb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfaauop.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqxvwnv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ysysroxr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnyrsvg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2onerdxtw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2axxjblal.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2nnobnkcs.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2axesgupc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2arcrjmcf.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2uuaswfyn.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfiwnjku.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdirohcs.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxfuflaw.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbwtvmz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lciftymq.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2kloecvfg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkpaylw.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pvglrnba.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2oojzxags.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmkwcik.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2utdxehku.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdpwvcj.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qkznzejn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2aadzsuvm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2vslyvxpt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jufqffne.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lxoqdqva.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwpoaoe.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbwvpkq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2mybxdhbd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cztmuzeh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnwuqsg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqeokuhy.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hveccoab.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xpttpmpw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2isccayft.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kcddschq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2acmhadyg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwuuzcf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2jmiytaiv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pokocnhc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2plqyewoh.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzerftb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfoaqkca.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2gcebvhho.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ecubzsak.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzuyrni.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ewovtxft.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2szxhjdvg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2oziwhbof.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2absnvgfq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2folvusvt.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ndawkehe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhpstcp.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2dddwsuym.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2nfneuisi.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2plqbstak.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxsvnca.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxzhesi.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jhlqdyim.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdtdzhc.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2utpdihya.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpaluvw.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxpdufm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2gifehbjg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2srqkywdx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbvxqmt.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2grzddfqq.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yoyjcysp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbwipxu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbredxp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzeryun.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wwuvaeuc.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2yqobimyj.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2oehanbar.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnafaia.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jrswealy.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2goldemcv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2enonciuz.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2holacxyg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zsbsfjkh.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zajpwcze.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2relzkvng.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfjoeel.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulaydelm.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgksvea.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcxuyxb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnauhrs.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xzsgtunp.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mabkgvmc.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2hukbrhho.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2bnysroav.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2itoagnlf.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oepsikkq.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2molovztk.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkncebp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2iyetgncs.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhmlctc.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrqbodp.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2koiymiju.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxfulzk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhampkz.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2itltilgi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2resffoey.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyteralz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2auwdvjru.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzopagt.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2wyyruqug.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tuozwdoi.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhxrkbn.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ocraiebt.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqmidxp.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tgnkevuh.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yusucvyg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ardcjulr.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2awmmumrt.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2idhlrqdv.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxqtnxs.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2rwejuefs.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2glxzrkvl.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uisxende.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2opiyuzxh.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2brlqefit.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2hdecgotl.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rpprnnxb.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwkctmb.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2uhuccocx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2elwrzgyn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcbwzox.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2kinuitfx.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqooyelp.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dorwjjzc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xiotrocx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmkdspk.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzuzotqx.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqtrhgz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmrryau.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwjsrgh.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ycymfcyo.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2thttnvvl.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2znileupz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2fwedrtjc.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hnleohaz.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzmbgip.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkevtaf.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhuoidl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xddkltjp.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqqbjtyg.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvinwqqx.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpcrihob.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2aidkokcl.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2skeprvmz.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulyxwdkc.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2avedepqk.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2hujkesfi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vivfeegl.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2afbhtcgr.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hngbfkbm.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aazncjfh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2yoexbxcn.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dvlvgmrv.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2llbqvzxx.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrrjwly.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgiqgxqz.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2eemflsmy.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2uapokjac.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2sqopuwpv.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmwwfwe.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbblpju.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2inbzhlit.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmmibys.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2bcklbehz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwpdsmb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxodqhx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2gkelqejw.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2jydffxdn.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2crwhbjhl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxotfwlv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2gmoavzuw.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhvshxt.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dyrtxmzp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxjqzye.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqydskhv.html


<!-- 参考信息 -->