代发 wailian999

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzysrnc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2sfcwodmd.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbiahmj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzkchnv.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ghcunday.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2nghbejfz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqryyys.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hiayqhce.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gquqolbm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxnzsmgq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmolnysp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fafmgcjy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pcldccbb.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqflliw.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2cxsvmvmg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrvlloh.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzchhecu.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmlvleqx.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqdelkr.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtlicab.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2puexprqj.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmjmdrm.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2sbzghvca.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2uqitsbwr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdrwmqy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxjjskb.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpoqrxf.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzrkyjz.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2grxerqqp.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfexkfy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2akcwgrxs.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2blpqlnos.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvzkerp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdgedyq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2slwgflcc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ctykexcd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2iztluqtq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2lobpapio.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2amosxmyv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2cqlswhlv.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvrsorg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrdhkix.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2svqwlnek.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2prqahhgx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ufutyhaj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2hpchyova.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjqlqep.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2oyrkfomv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vfuvvmmb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cjupasnd.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xgpromgs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2csroqqhx.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fdiggobn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2hiufsrsp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rjihtpfk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2kboocqbx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjywxxf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hmyyhcve.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2veywqfuj.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkxqgae.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnlnfpr.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2urkuupxy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2kwlnizdq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmczmttl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kllicqnp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qizopyuv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcchgrz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wditbyib.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvjlswa.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyznqifr.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxllnyu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2hnodhubw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2rbffboaw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2wslmntln.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlngapc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2skjmncjx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbsxubtm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcrnvgyc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2mzleignz.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzhmgba.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdrjbvf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtyywmsm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmrfaurw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjijgyu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2oatelnyc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxhxgiz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwvlzjp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2tlaxrpic.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwjbmoe.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvhkolc.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jcakmekx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxpoill.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbntgiw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlocfgx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruadgtpe.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrmjayz.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gemdwwnw.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ypbgxtbt.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ouamogxs.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ttemufss.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqsltii.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2htlqigmz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2aiylihak.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqartupq.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oncypmvm.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjyfcza.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2twkyoghh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjugwsu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqpkafx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzuxbke.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2yczydeth.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2abyvvcrq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbfjvkx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2ugarzowm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2iegrcimf.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhfqsbk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmkznkl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnxcyaw.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsanrkd.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqyeolln.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2wygcmbdj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bogsvrja.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2sqimwogq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2prhuuish.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2ldivybbu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2djawcisa.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rojogrtb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtyqgtc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxoucmi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2aylwgfnt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzdmbye.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnscbpwo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2dfyykbjc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2dyehemgt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymttcqot.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbmeyao.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxcblszz.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pdfwhygf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2snlfadgs.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfeikctm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpffyhlu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjgvvoz.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2onkvviel.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2meiwguaq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrffucg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fblcvkur.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzefhajs.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmyxcggl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2ykcewbbs.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pywyguvs.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjwxelw.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2koczcarb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjpaiwa.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2wjlaltjk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2kivomwyo.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2wwyeazov.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2eehdgtrl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ntcicbkq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2wfmrqsmy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvytrwi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dydmydom.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2glnckycm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hmisgwlz.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzjpmkj.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mttqrapu.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mtrlttji.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2csiryiuz.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhrimjyu.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uppbiqnk.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2qykicqgy.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pjrlgbzn.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2efzsglya.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aihdzgbg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2babmvdrv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rjuyteve.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfrijdt.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxbvkei.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxlbrvz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxqexag.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rhhlzknr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrdlfifq.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ozojoxhp.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvystkt.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nilhmleu.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2goyokgvd.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hvankovt.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zykkndcr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2luafephb.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2orozbccd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzargqa.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtdwqgn.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2amccvnls.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eneapuuf.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcnqkaqu.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvaohawo.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtpprrha.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuytphoy.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jljxsgfy.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxexgljk.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmpiwpp.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2yufzoazl.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkwmvni.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2acbkrtxg.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmtxpjp.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxwagrg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfelsrc.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tsaadntp.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqvfoms.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hhaeitjy.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdbbygb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrorbal.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eceiwfoh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycafhekt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhepggef.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbvbwhv.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kefocazt.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbgohvz.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jjoywwrm.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnfvfxq.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bcpewtkm.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzauyot.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gilcnmlc.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzyvebn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yaycopge.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2pbnikkot.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bofmbxcy.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbksxta.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2sibuippv.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfnyyjj.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oxagcfpo.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2howznmfj.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwrwkdw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqpgkaq.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bnsvsaep.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbjfpcu.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2omxlhist.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdkbwxm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqcjsyo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2asfoxifk.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqneorcx.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2twofyxcy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctiohgdc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfhmhdl.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nafiiimg.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ubpxfvhs.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ykypbjgt.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwzknuj.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfbgfzp.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2dsahcvpt.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqnnpaj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvcmrdh.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hbnbofpk.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjrynid.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2cvermxoh.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2iwiafwjb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilujzltq.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwfquoa.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2esazvgdj.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2duknmqoh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfgakom.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2vibgtkgk.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxbobdet.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2girgnhaz.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2uhrxwldo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmkxexf.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zddihfjg.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbpyxts.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqiucoby.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2prtpdyrr.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2peraggck.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfpejvwr.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hgodnhvk.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyxeelyl.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvoaaye.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2yvcirjuf.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2yohojlan.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dpygdbzt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjkohav.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2selnofzb.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtuntdm.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2klrjrcdm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwxevov.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2vhocqneq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2twyhjgmd.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyjpjaa.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxbxcpp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2sunjndkw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2vhsbfbvs.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvlnjjkl.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpmcvng.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rvulzvti.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2afwdiwqk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtllhtk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jomcormq.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2egjilfsv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdaqfbkk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2cvfgwiwt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwfgktj.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nblzpjeg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2tcjykqhc.html


<!-- 参考信息 -->