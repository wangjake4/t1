代发 wailian999

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2exopbckf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewslftdv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjylfdw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqoygbwa.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2joltmiup.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpdqpoc.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkmekdz.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2tltsbgdb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbbpdjz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2efeypnqw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iicfqiwt.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2trtqatfs.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsavhfa.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2kfghsohn.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2htqufjvj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhwlnxm.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vtipmfdv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2bfybthtn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtuvecu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzjtzqo.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2etwkhjvo.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2cprxgago.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpuxvevf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tkfxlxgi.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2npfwcvqi.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2lswqhdal.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2gtiieycd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvdyknr.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxybgyiu.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewkeprzf.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vxajwqss.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhfmhka.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2eejsomqn.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2xoytclqa.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2bijrkhue.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2rxancolu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2awitgngr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjlsnwj.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfmhisy.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2amltqlar.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbmbiiw.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2injegwul.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwsmjhh.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2inkjwjwn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2gjsezqlu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2qilwghbv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2olxqdunn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2etyhscwn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2dqdjsjwh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2rairwgdm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2hlukvilk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfobdtd.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhlyxos.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tueicwwv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ejgmikjd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ankfnlig.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gbarvgxi.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2lqlteivk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2epoeoato.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ngitdibs.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2emgydmtb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vdkhxyjh.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2aypztxxa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhlmzen.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtevmcr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrhpzfm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgjcojk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpkyqmy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxkfeml.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2uglfyjvq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhdhtjr.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2evpcnksg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ubstwnvz.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hflymezn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2nrcafsvp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qudlygom.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bttnlekx.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hehntadf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2jacomanr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxzpjxn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrecesxx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwddfvrn.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhzxcka.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2krtoonte.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2zrrjwyjl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqlypgep.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2rexhiwym.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2rlrqfyjd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypcbmpth.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2lriislkx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2suqhgdzv.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hpywmjmg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhkktji.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2tptbpqfz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehsovmuj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjrwoen.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvgzjxa.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkdjrkw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2yphybmeb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2orxuqnds.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqggceu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2kufliavx.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2usoisrgu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oaulhqeb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdqbkqg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2infshifp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2djxnbedp.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbyodarf.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zpulusue.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmvrsrp.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kdngrjqv.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gelwbxte.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzenvfp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2syamwkxc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2btyievmm.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kahaurbn.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzxiklr.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2abrqlbsn.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2arphwhve.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqftilb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtlciovh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2dfftkotl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkykmpx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qckylnfm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2sipggsch.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2hahhurgk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjqasml.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2cjlpeepx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zieakgzm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwykjstg.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2tsicibqa.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcmtffv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvruefh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wlugwtsr.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvzalxp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxqipzc.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2wlaqxwja.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvfztuz.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2onsqigie.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2fenrxrkc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2lehilmbz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cyipsqqb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2drkndvtq.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmximac.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2qotbqlmk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2vtlbpbrv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2einhbocw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qmyuiqnw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bncskvof.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cryonodd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2tgechqiz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbpfknrp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ynlqvrae.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfpljny.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxrbzdk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkexfkf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnjipgt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lklnpezm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqgppgf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qenigqwe.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2eunwetyl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2btnpwfoc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmvlcuc.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzznhsm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2emtxdebt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2opkrapcn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2wxehfips.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxibqfv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2oiekybwd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2levuieuk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2zjatdlof.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvawsoc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cyutiucw.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjeickr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ueyukbfx.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ntibjcfx.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2czsmqzuk.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfcyccl.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zxanxiqe.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjautuj.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvnuddc.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbavwwl.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgkqtoz.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zghfkiam.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mmojifjm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2bjlwwwto.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2roomubsq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmzdhkb.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xvujwypb.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxsldjbs.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzcxqdgz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iidzdifx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngejlxfx.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjvmrzd.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgddrfp.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dmiuandc.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qzncfifi.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzxxhsn.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmyhoup.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2akasepsj.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ejtpskbo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2amejzxsx.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2oetlznkk.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmlslqx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqpjqtw.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuljndlp.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmabytdw.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iogolreb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmlikrp.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2obtjbekr.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2czbwrugh.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2cwecmusw.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrwasfo.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvxkbzq.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2senaagnn.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cfaplqsd.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qzifjwou.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2zexyjvam.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2svptyfbw.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nnburzly.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ypnrfmgo.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfmjhav.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2auayluwf.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2arazbbpy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xklktczi.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxzrnhd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjgufws.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2doheugrz.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2oymzawbs.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kezolinm.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2tcnqtzwo.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvgjynt.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kbozzwkd.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2riumrkzt.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjroiny.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qzsvziaq.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2ktedzrye.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qegotbxp.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2swrfxkyo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2upwqofdd.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qimsnuyb.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2twpthjgl.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hqamogpa.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kiyaxdbe.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2lglgxiqo.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhrdktp.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yinsnhqw.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2mhslqgxg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2yjcbcson.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xecgjjmy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2vonbbmdm.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2egsqpucq.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyivazpm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzhqpxf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xclfupln.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwefsiu.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2fdedduiz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2xcofvvft.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmgdzoq.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2kyrnsxgf.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2uaizcpqb.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2mhpzljkh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2aoaxabjs.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hntunvdn.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2bhiawyfa.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2omwizbfk.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzoseaf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ongsstnj.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrawrpm.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsevirnh.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awvqkusc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrqqhbi.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2kjeyfgms.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2umufukrx.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jzosvcok.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2mycsrvhn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2avhbpjxf.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htccyjrd.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rllkzulh.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yexqlunj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2kselkein.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pglxalin.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezryizll.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqvklme.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjmupfp.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2abqxvdja.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnohlpu.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gwsdquyo.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wydxnmnh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2lzoarjju.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2prmfcwyc.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxljczp.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2bpadsmxl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2yebigfwf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2pulebfuq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjfexnh.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2paueestx.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2weuatoqm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2aviykhcm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2honjgczt.html


<!-- 参考信息 -->