代发 wailian999

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cuevwtst.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2yavaakui.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2igynygib.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtweeik.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2cctaplls.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzppqay.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljprpkwa.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yremfauz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aeoyhqgn.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2azlzfxzh.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdqenql.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2unntkbmc.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2invmhoon.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvdzqqh.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvfgnwx.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjrepym.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2dapggdle.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2gozaerzd.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2uermzqyd.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2dxltkoct.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2asohyaui.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2udgtnstd.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxwqeom.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjfencw.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhxrukv.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2uumbjbon.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ayiakpds.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqckrhv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcelcpp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnvhslg.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2cxedbsei.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2njgrzrfz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2nfadxvhp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmsbbyy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2fyoobkui.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2oohejhqg.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtiktnh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eytztghn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2uidkfszm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bwmmnzuc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdwhdxu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2dafcezrp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2heolciad.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lsequomz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2umzczeju.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mzqsywcs.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcedlwb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ueshijtv.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwvjlqc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2fshgkthc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qbedaypv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2uybozbkq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2spamvisz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zsporrus.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrivviq.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dozapjtt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwcisbi.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nntudcfz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkseskd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrkaxkcu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdotbuz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xyibnwmq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqxkolli.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwluqons.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzyibms.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcbckpe.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnkbgcb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2sftynyrj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xkrnrbgz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2givzavfi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxeomqfj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2uopusplq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvyxgjvf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2atazmune.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2dwpwgjir.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcbdqzz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvaprqfl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzvtwnh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjsyipt.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhufdxqd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2kamuadlo.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2edesqdhp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbnhvlt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzkykbs.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cadujztl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2nfprgljx.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqxchhy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fuuibzvb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxtvwfh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjyznra.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvggzvh.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwldrzs.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jidxlydh.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lnalmtia.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jebjegop.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmdgkmf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzjqbsm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtjryjz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgcytkf.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2notzqxdl.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfcxqdch.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2beagbatb.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rsncekph.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2snbxiymh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjgbeyq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwkavly.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ftpotdqu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2uoanmbvj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdsfwsml.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2owgpyyqw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2cyokhmpd.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2iowwktop.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdabyrlj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkftuzdy.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcarqvv.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfkfcll.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzksqulz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhsxeqtt.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjfqhne.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2tpaizvur.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcosigi.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uoewxfyu.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pcubivvi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2vorfaeib.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzgngai.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2phqdrnds.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpvseuc.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gxsopqzr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvufgdj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdnkwqd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgmicfe.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dczcvxok.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxpcbtpo.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bguzevcy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2oiflrxgt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzgbdml.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmzxsig.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbljvol.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bephjlqb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkndjdww.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kbsqnusd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqyzegzi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ouftvfpq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhudembo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2dmarmspn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rsasbsfk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcvzbur.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcwvter.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozssaabb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2vyeakpst.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfcugop.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvzfuxv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2kjznfpsm.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdjxiju.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2dzefeevb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwhdlah.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlrsdtx.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2zhkrtyep.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjjyrbt.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ugordpcu.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gjcxubrw.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwrzrxt.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xqrbwzfy.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsdczlxc.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2spgpinpy.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxaswzel.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zskcjcxo.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtcejwv.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkbzbtl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjwuacl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lhigxtmw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpixjivr.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gftteybg.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvosmqko.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2huwmwjte.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2obmetlck.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyubsmoe.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbmtubp.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2gnacvnbj.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkwvtwn.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkfkzsr.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vikanheg.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qepknxhl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjqselm.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2rjgvgidc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2appkvoeh.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tgnjwmfh.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2bzweqlse.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgokfzto.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkciddvw.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdexekab.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncdhbldn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygoylnje.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eypzolgv.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmvaviv.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkblrwd.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqeeujr.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2misptjno.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhsvins.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdihkuo.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2seabnqzb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnbbmre.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvozstk.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hftcmnfh.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ncujpsuq.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2zjcwourd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sihvlmun.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slynjjan.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyahgife.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wovkqymv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2mwusckpz.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2adrautze.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnxgqdk.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlvfvcu.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqqtebk.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgrszec.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fsyrylev.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqfcgfc.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wzcpgykr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2sclhjugp.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2grdaescu.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2axlokidy.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jublmibv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2iabvmdzy.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwdhlgb.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfjqmgx.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmkjbcs.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxcngfy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2esfygyke.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qsguxvww.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2revvxqie.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2dngppxrw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdyzhfb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uktwdxkb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2avcelkpp.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hucobyjn.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfkeqss.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnuqrnru.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdvpurx.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdfvtklb.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2mxknzclf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbvnxvg.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2icmlpops.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrxtqrh.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbotdkx.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2njncpxnw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2lpewgjac.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2srblxqrr.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbzwepp.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2bxyppemj.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvegmnf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhwwceba.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsreuhcf.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aoyxovpb.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fymsnkav.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkwyzfk.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2cszrikgj.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqncuyna.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ugutkaer.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2pgclszuh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkxajmn.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvusppy.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2femjjskf.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqaspkiq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2chfplsbv.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnbmttx.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmddemww.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hjsytlkt.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2qryiuzfj.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2irbjcuma.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnudpka.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2acbehmfu.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vmejybqh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2fgipfpst.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbztjerq.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2yvyjjava.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2jsbwccfx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2ixyngzjg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcwswkk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxauqlr.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2vngayema.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhxvxam.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdehowg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbbjhnb.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcszwiwt.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2iprdabqk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2healkdyz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rltopyii.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwcgnir.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2medoxnxk.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdspgesw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqpirkd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbtoenw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlseqlly.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgifygn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2cymkzgiu.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcstbien.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhvjvrw.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbapdla.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2khlqjsbz.html


<!-- 参考信息 -->