代发 wailian999

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkvmedv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjyjshc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2stulywvu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdrlasz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xfchhblx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2meplfzbu.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcytkdtn.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2efdutvkt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2wyamdzdj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2eilrsnpw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxawwqw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2huxlkisj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nthqdzif.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2qmspfpyy.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjqlzpm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2qnatgtvm.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oszqegzc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2gketzadp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2nviqaltg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2osazzflw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcnairfv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdktrbe.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2snfnovrd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ubiriczb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kwevazss.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2libnlnuy.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2smvyfgwk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2riyzticd.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2rojjibno.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfrqnmki.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2llcqmwxl.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkruodwj.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2ezqysfqy.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfzulma.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2lrydkohd.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2pjviqtgg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnakgbm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zxgcifhu.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nyumzcxl.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2scearkpi.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2csyikwch.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2bnyctdbr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2plshrsua.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2awigdjjw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2sgannpjm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2qqvswenw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2fauybuvg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2mogwebma.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjfnrgf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2blqdmoui.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjpzjrz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2rhcywuii.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmueids.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogthkryc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2boxrsbxz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxrsqix.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpuabvk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmesaka.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmdreed.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jldbajdo.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2baxbgfes.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jxghefnx.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtpghhe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzzzzji.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxhiklu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2vimoykbz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rgychfok.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2oshjornw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2taoqepzg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hpbvesal.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkvkiul.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhazepb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kvcxidnl.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ievzcrai.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2ztyjtkdv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbxuijy.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oodtndtg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhijivb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtkjdlb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2eknzfwyw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrjxham.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvwfkbdo.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2kfztnsug.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqsyszeq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jccjsnnc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2mexmgqva.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkbcevl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ygaifrdi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxpnlqf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpdlajz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwhkiqz.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbeiitt.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfgxokb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2rujlrdxx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmwndhr.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqsqamq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbisxum.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2zeffecgu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxuofnvn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfdgnol.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gzyfimhr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2ccusycub.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2iymgxwrt.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2knxbwgez.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2izigojfs.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2icofvguo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2mokloybo.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjsdbthl.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmfqflaj.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpbzkvk.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtmfsxn.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjuvyob.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2arzttqkc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2trcncerw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2daaraqvb.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2asosjmgr.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmotbqi.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cxivwnvz.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ctdjrpcs.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjhehmf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzqtlrx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2cefzulub.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2uxayymwf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2eeckeqiq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmyhoinx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfljrey.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrrizvy.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2pinfrccu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmfqqzf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvpezha.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvixhgqu.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmyeyxv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ciftnucu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hxajauci.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpwizao.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2uglxogmy.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2mblfxulc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvorcmnh.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uzavnfoz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2iivfgvzv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2gponfjtf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqbusvt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2hkomuqeh.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbsnsgk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2oizmcqzq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2pptgzpkk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2edxbjuyw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfudqhu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhytgql.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdexxya.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2rdfshaag.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxceudc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2daaoatwg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcvaocf.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfztzni.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hugwyfbq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2suzngbct.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdonpig.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgvmvpg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2auxwlwlx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtkrkzw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ruobvngk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2anxfthru.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2tytyohwl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2byzjonom.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2njycrvtx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2lkjofhho.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfsiqeu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwygfar.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzqswsz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2sumxiyjw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdbnxkm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ysenezja.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2gjutcimc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2quxhluki.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2rfifzvbf.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2psulenbd.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfybkgm.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yficmyvb.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2etiwvjwm.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2asqsrzvd.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2kumiuzdu.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pjsvftbw.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2woqxhlap.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ubktbvpx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfsbdfg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ochvuskd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkebkadu.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2idqjwdrk.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxllsjq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2pabxlhpo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsbqnml.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ciazvzhl.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2iwztjepu.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2recviqhm.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xkfctqad.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wpyxkuxw.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bsspnuko.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwfnbaz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2imyoalfr.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2nfltbsdy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzwvoke.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fajwyzix.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2unddqsim.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpruycay.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgurvwb.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2afwyscde.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ooyjlqys.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2txkllypf.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jguxtnbj.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmsisdpt.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqiuujw.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjkhgai.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpkzcqk.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gbknareu.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2czvofwsp.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzryhyv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqrfixk.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfuvzgf.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzxotxo.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mrphhkav.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwoprol.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2camxfcmu.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xccbtfiw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhwioyhq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbpcbubf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2zspfipte.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwbcabd.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2qwohhzso.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvxmbvg.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2glugpnzs.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mevekbqd.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2uzcmuovf.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mxuoszoz.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zmaihgux.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wevisyan.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2toipxgkq.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xuotudxo.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bowsghzq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2tyykkzgm.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpgovig.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gezczsbm.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpowjca.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sghflfyq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2gjimdtvo.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lxeftujx.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dcyhwwhh.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2klgrzgvt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhptxtt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imqrjhac.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2islptkob.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqpxorol.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmuzema.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzojazr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qadwdqkb.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvsqcfc.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2edwcpalr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdeytxs.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2bsuccdfr.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2hcoradmu.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ljptxadh.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsdihqd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbabmmu.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2tidtyzwb.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmcfzby.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jqltqrom.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2xalhnlhz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pytyeoci.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlyyagd.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbefwoht.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dotcmdrr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmahbbdo.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfuymfo.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2irddipyv.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lgsgoatk.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2oijhgbig.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjmmjxi.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2welpfxrb.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvoobzu.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnqkzri.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqfctmc.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xuoquzjd.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgneojq.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxxvsqd.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2jermpbmw.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhungad.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2holgasup.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2enbvmaau.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vesobcee.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2svhzgfkd.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2xswhbcjt.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbhtsrp.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2pnssyqup.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2utoddtwd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2dkrvmjuz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpjeiyh.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2kflglxun.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iqirlboq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2oykxivsf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2ielzkdve.html


<!-- 参考信息 -->