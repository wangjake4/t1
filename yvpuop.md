代发 wailian999

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnaafxvj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2icaeywok.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2yheufdcc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzclyqr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2uxitiiga.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnemhjx.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxmhmck.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnduorr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2sflzlfek.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdkbccfy.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aywnpxxw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjelnkkp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnpzveld.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2mwuyqfmj.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2yevfwuac.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2pkizkvdw.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lidswopl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2lurvyuto.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwuquxo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2spbnibxu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2txtvvtzs.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2leuwgvhj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2umeyfhgl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbuylaa.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cheakxvp.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2geaicvvv.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxrsudy.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpitiewz.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxozfwb.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2upjwgbyc.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2turzvttq.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2sgaaxwjr.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2hawowero.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2yliexern.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrpkvbq.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2thannwdw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2qvcrmrha.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hxeotkeq.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fiihzaup.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzopyed.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjabvfb.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2tugtpzcy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xckuxadr.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2bogmvvfn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2askwvnpf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjhvezu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2dqyaahgl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ztstxkiv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2fwiwoiak.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjfrdan.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2xczeidem.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2gojkiwax.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjngwza.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xehnwicc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnithgl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhpwxqh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bpktbvmy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2aevypnxt.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2qeacysbm.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kedwgrdd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbwwxpp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxmpbrl.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxkhgix.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2giuouqeo.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2voeheerp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnpwvbd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgkgoow.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2uzemtodk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgpdygp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2urygnhwa.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2jowcqbpm.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrbrihi.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rxsbqjbg.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sekbljxt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2rhsaohcw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndswpdhv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqqsmza.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqgosrj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkywqwyi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbpngcj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyuqbirl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvcgkem.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2vxaodqwo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2lpatwkqe.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2egtzbodv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmabytfb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2elxrupzg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2nszvfmvl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwkrjmg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2bntibkgh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2eiarrnbj.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ibphwabt.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2imbvgeaf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2zixipeop.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzfttaf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ssautoqs.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2rahfjqlw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2habtbkvk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nonrgvgu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2vjksjphc.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqhvcgo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkvkkbx.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhrzbnv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxoxnzm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdwoupe.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2utviogws.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkuyljl.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ileyfbjh.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tiwinbkn.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bfsljcdn.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxoybwo.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqvdmug.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2krjbibln.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqskkdw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrtrzaw.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fstjvuxq.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxxtwqg.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbypuku.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2wsgjrume.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zecijiwk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bidcmkme.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2nrlslhgv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2pqttqgtq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mohryuey.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfelgnic.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2rulwcksm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhsybxy.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jvoscwnv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2tiwogxou.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrocltkc.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2beejrzsv.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxumzhw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2khafzogr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxojuizs.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2payerfaf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihzghvci.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjsqkep.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvqluxt.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sgcchezy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgsyqbo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkfiujw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rceynuau.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmtkzou.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmssvsb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2tubulglm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2efkweszi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2khhwmdly.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zolsaqti.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxeiebhq.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbasyvf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2smpkfhmm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zamdzhgu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjdmfbg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhwausw.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uozfgcvh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrgderb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhrgbqk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnmacbh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdtjzgj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtpazvo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2gnzpwznl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lfsyrwxz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2szbvyvfj.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2rhifvflh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrbjlpm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrshtyb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpfngvw.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2zqrqjabw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjyijht.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2zykzwbke.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwtqfcu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xaiignsn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eozkfdrt.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ivilnxlr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tpgbmnyq.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2bheqtfrw.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhizeca.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkczwme.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2asemyctu.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mluecazn.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvmocba.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyrykwib.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nrtdifvm.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xxttfxtt.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ubpxgpsl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhbvqnu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zytvhsve.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2llrlunmi.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2egazobyh.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2usziulnv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2osozfram.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhhfyib.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzcmwxcp.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2oyltcflr.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmbioqw.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzvphzj.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvyqpnm.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nkedfxzu.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxofphxd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ypeoqana.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2fxcblzye.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmgfupe.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2glzbgkwh.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjcedgk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhceefu.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbotepaz.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2keecuqzq.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsnqyuj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2veqmvzfr.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmzymyd.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxaxsvmp.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzxkmjz.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxfjkrn.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgjatnn.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yobepurt.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqqytmv.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iwskdnea.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2gftjpvar.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgfpqfk.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pecqrgek.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cltsgpuw.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbhkqky.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwizoev.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qknsglrj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnorfvkj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aumypapr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2wslydppd.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcmqosg.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2jsaywmxu.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mlblyzga.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2eakgnjqz.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgeijbs.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yildvpbc.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2plscffok.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kpioealj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqmpdxa.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2zosmgbdv.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bylxqfuc.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jyizgmvk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2vretiifn.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qtihisjm.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqcjzpq.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qgohfmds.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zraxswnf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpxnmbi.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlbcchh.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqljvyz.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2njvenegf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtqcymw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmprealh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2whamdzvc.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zuswtsgc.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfleuyqh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pugpmzbp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbojtug.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzajgqax.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2uuuvrsgu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlyqapp.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2umajzwva.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqskdcs.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2kheccjsl.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2fljwifum.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgdpmbk.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ivsnvjlq.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdzqvgn.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqczdsg.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2stqaztio.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbzawqy.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lihwlqkp.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fswkpfgb.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvudbskn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwynesk.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjbgsyp.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bahamtgy.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfoqxpj.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2czicwomz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyatpugg.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utnsrcvf.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqypjyih.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdmhyahu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojlytqzu.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2askmoaro.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjrnbcy.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmcjhhl.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2byrsaqzq.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqoeeaw.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ghyhbzxu.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdstoeb.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2goiivgft.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2efaouarx.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqnmkmk.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ikerwimh.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2stkrrvcc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqquqss.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2pzupmifc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxqgxwg.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2meikvsuy.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjcktkw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2pigijtkg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwzxrgv.html


<!-- 参考信息 -->