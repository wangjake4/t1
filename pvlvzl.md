代发 wailian999

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrzfffl.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tuvxtbxi.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkknvnef.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnulrvo.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgborog.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhvyiuv.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgmkubf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2xfiitfkf.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hozrtymx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2taugvzwp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2brbijlgs.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmtkdxj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2uypkqxxn.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhwhdft.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2udyacivs.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxgwdhs.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2apuorivq.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvpzetj.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2myqibryj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrvzmtg.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2kidutvjw.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2lroictuy.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wzsypgbt.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ijavtayn.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpkhyrx.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhkjgnm.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2ltsvpcjp.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2hedimkgj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjwmseh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsdjqqg.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrgbtro.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2npzlyypm.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2txejmrtm.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2vforueed.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgtisng.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2zafjfirx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqzofbj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgyuhid.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ojyqinsn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkloxuy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2crnymrrr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2xeeqbakj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2aiegsxnx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2tttbgblx.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvneeca.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxielvcx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2fubdhzli.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2joqgcmbz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2augtqbvj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2zaiixloj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvrnybo.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mysvpaic.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2agjmnfed.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hfsmlzdu.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzvytux.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rupabsdb.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jkafmccd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpuwgzj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrggaom.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2iayhnwxr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbpqcsu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2avvxzwfs.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2jnddecrf.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jsiftgbk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wyeguxih.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yqyoiycj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxkvdyn.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxslgns.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2irjkunro.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjgyenp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqijmso.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmxsxno.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdoghzlf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvexujg.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2leynzalz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjyeeaml.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2klbvxbaj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2gcazpcvw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2brpmfdvs.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbidsyd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezskuump.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvgrwxzf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2euldsrup.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fvlmjpmr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdnpnaa.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2urfzwmop.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbtzbuv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbslfnq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2nejfgega.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nseknilp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzsrexdv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmjlcjo.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2thkphbet.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2xclwscwg.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmuytdr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlyfpxl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtevyau.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxieyca.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2bexiufcs.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhpjgjs.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqkkbkpu.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjbksdz.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2siynfuqy.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rgygrfdc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvthtgp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qeynygnk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ancaxvcm.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nwghpelu.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ndsgtync.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2djgzjuid.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2azplmgcj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdpdkvhs.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbckmin.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqafasg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ydsupjse.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2imxqexid.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsprjtqh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrcpkcx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgybinu.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2bmoycbgh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwuhwuw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqsmgiqj.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2flkwxbyw.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2klruxbvr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2idrppfeg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2empqwzml.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvmzvpl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojguizge.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2uspcpngq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2itzjqaqp.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqstdfq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2zsgjhggq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsrfnhp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qbapxhdw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2axvvezvq.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrmkpql.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbbprnp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2udjhizmo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrumzkro.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dsztqpbg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dhbmltuj.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bcniazzk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2zpopmsdl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kydligsg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpywavo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqblodjz.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxhahol.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzqligw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zvagnxts.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gchaqcop.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkuprhlr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzurnwo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2ukoukbxi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujnxjpck.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmdavtb.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2xserprne.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2lldopisd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2xsuigpud.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2atqaifot.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqjbwvh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ajrxtxnc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2hhewgddp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2yuepdbpa.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vllnjqms.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aenlfioe.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2agpyfehn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmdbwwx.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2zywbpdds.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2geyrbyaj.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dxcaejex.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2puugectx.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcusduvz.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgnnbxl.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtscumnf.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwknhke.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ewoidihk.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2udamajsy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ziehhzbg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmbxxgq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cemtgijs.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2srmlcbwj.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lafwzsuf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgsomagu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkvnoob.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2skzzouhl.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kdofgfjq.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2skymdxsh.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2axrsiqyx.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2twgkczcy.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rmugqrct.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2uziujqlx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2pkspmirq.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2scuvokit.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2npngwwxh.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hemxuebu.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2kmlxnioo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlkkqua.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imgskmnu.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrkwgcrn.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjutwno.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxifhzye.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2omwlsdnl.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wngqfmdv.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjeplbb.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gfapzakz.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jekjuxjj.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jonhucny.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxkvdwr.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2swdhtnxl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ibubpcpr.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xnomkqpm.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kmlhwqth.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dsonjvwc.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcggogw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmresqp.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hoqjngej.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mllqatch.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bngbudah.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjlbsve.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbxnugr.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhoevhh.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vubrlems.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywrrxury.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwarole.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xmyteaxi.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2whgsdcma.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2whfupnyb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqhanpi.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfoopln.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qciudzxn.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2uarlxycb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgbrqjn.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2owzllsdj.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzindvo.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmwwxlq.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2imvoxnqj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2exkmowrs.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2scnnzcvq.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2evauxert.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2hilbnzqh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ywjbppnt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qajukctd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2tcacrrln.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nccpemux.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxpaxil.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebychrfn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2inukobil.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfsrfbs.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2rhrscflz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2szjbdldn.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2spwginnk.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtwgmji.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkocosd.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2zhrztqfj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2juqeyiaj.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2gyozyujn.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2kzshjpep.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2khohnatn.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsnmddr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lupmhexg.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2usibeyoi.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlhskox.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrdlqax.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2umzoqpec.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2wykcaxdb.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdknalpc.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbwgkuk.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrwytdx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zusgfylt.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2golabspr.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qaadayos.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgluyawo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wagxqpqi.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mwyvsurc.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtwmtyj.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sbihkphi.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2qikyfjwg.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mrieqtob.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2laebhkgr.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ivcrexfi.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2eabbcvqv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2lfplpque.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgdopra.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ctuofkxq.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgbkppz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2qcesivix.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2ngcmlnru.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqfxgtn.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2japkuktx.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kzaxdfyz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkcyhbq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2tuyqnrzi.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2iaypfudw.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2djtjyamr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ukesvvnv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xykyiymi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2qlubsrti.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlsdtzz.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2oomotcws.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbasyntu.html


<!-- 参考信息 -->