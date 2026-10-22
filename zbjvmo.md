代发 wailian999

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2gnymgckl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtpwyau.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2gytugpmh.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtwvxpj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2dbeawfmc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjmcqjx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlcdopo.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxovizao.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvcganwp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2fkiafkma.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2gfsajfms.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvbyxks.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cakjmzqh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2whdpipdm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzyadaz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2leesszxq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqpkmoo.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcizvurl.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxictzq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2awswtqeb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dvuzaawl.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2esgultka.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2uayiemkn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnakenky.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqztffar.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdwdisk.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qorjyrmw.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2fukvcvqc.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2ymabdyvj.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwndsie.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2jemfqocz.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2dpapkqvt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2pbsbowlq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxiijys.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxshsnn.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vccvdont.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvotcuk.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtzazgd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zntjrsax.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2clotyiin.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbyycct.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2wppwjckd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2mojnqgrc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ougqdfzk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkypwch.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2luyogqqk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2hdislqaf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbiydqe.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gysoasic.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpajpnrm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwmmpfx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxjsyig.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2eehqlnmm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2udxlqbqp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2xnghqewy.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2woseizvu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvphpub.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2paighfrz.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qlsegkub.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbnvwle.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2icgfcxvs.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2gcsywknp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hyckfccb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2aeonwbcu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmkvfte.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2daasditm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2fhcspijp.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hoecagtf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2khovtvgx.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqglolh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjofzql.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnelbzo.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zzshmkwh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bjczxiap.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrtczsq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uaspnwkn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpqrtiu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2klbmriqg.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2vggxlaik.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwkcena.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgwlbfw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvzteuc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2woechbxa.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzcixdf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfygnznj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2sslpfggp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwjarce.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xxgazlos.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjrgwcc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwnljmp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfyxjrb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2eumvdcuq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvprjtsj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwlxppp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfcrnus.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgkiaje.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hvciuibd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2nxisfmnd.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2caydwwfs.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxeizpgf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwnvzues.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qsptudew.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2mltoijum.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwdiogt.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwaixgo.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gkeaelbm.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2btvjoxkd.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2abwnfelc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tglikdyp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwdvjnq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgedfad.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwpfeux.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwewinyz.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxyeloq.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2zltpengr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fraspmmf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkuliawz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2kafbecln.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ddertaau.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2woknozcw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2sclvszuc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkncyyv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2kilwmcwr.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwoadxu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2eweozscz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2foimtmyg.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvxseze.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2sclnmhst.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2obuduoqk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnynnqq.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2swbibxni.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vshvbffm.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2kshmkmvh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbprilo.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2grxjmbif.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkgkscv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2vykmyepu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rbaftlzd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2yndlmefy.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqrgqbg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrepyxg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2jztbjrwk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxtpbgs.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhulfhj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqzuaow.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gujhuyrd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxedoxd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cenmjppz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ndpintpl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxljqjh.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kkidgzko.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzhalpsv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgcxqtn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ryuosjah.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uuffmqgz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwywmozo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjhkixq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pxforjuj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjtzlgr.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2thjtezes.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2yubyodif.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2mqiycbdp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvuswta.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2nlczouub.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmrdddt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2uogrornj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2mctmisyk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2axyoamjb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjboxez.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jjuwynbz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nrbrwulh.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2acuqvvvz.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2wawpdqry.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nisjvqnl.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pgamybby.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcrgjfc.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmdavtj.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2sptzncmh.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cvexjnfw.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2koegykjd.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fveihidb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ersihssd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcsdywp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sytgmhfk.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zscjxofi.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmaqrtnr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2seqwxhjh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjbalfq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmelcfw.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmqfvul.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2rmsfyjeh.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vptbsrla.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ijpnimpe.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2yhrjborg.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnsrbyqh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2msstapqq.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2hpstiwqz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ksubunch.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2puoxmcpf.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqegpat.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdawuhbc.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtyjzis.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrciivo.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2znmzvzui.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhjpraw.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uywzeqjr.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfowjif.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2gykyrbyi.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2bqknneag.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2awtcxarp.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lsogmtwa.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vftiulsm.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qdysordm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqrcegn.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2axvlcakc.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxozlmv.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2atmkhsoc.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbkqyfz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxnybsn.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvomecl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tavfafrz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2irbrydow.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjjdhsa.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2djamdeez.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2nomidiin.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cbziizdk.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmqvpvz.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2axcbiyiu.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfzbalt.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cngroiec.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2loddpfvs.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxaejas.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2qibspjol.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hueurfrr.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwphmau.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2qeglhkmn.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xqizdbos.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gehbgmmq.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzxinoh.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uqjmsssc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2exlpmemr.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bvraivhy.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2atytcggd.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2wmawxngv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2jrriotzb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chkqhsxr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2licohpkz.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhkpnge.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zihgrocq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcebuqry.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqhjgee.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2odzkiqpb.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2xlejstfo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2atgmfxfy.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpvczsx.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2likclijh.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vvztjmgx.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmefpvp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2galhrpbw.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmbonxe.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2aekathqw.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhhdfrj.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfttsxe.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzdjwnj.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2irzamlyb.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omhhifqg.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hacdbnvv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2cipaxzun.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2febdmvdi.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdtkijp.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qfyklxxc.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvlbqho.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slsuxyuk.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2baiwmrww.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsxcmuy.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2reouafyp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hixelpwv.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmutyiy.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2grvwwxsh.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lriufnws.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjktgbry.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2knvaoamt.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2supqrbkr.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2unqguhqa.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhvomml.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzvcgcg.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgwcwqs.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkemzjc.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2egehrtab.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2labseuyk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2fwkofdwp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjjttng.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkejqsi.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvwrqcl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2itwajmhq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcrvfnm.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2srrhuehm.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gopxwsfe.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxounaq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpkucauo.html


<!-- 参考信息 -->