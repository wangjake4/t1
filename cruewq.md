代发 wailian999

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2zrirdief.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxldtom.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgzqbww.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gapcczlh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ceocqgtr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2hthyuzhu.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2xegcdlfa.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2acetvuzz.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwpofvg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbpdfch.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndlcixye.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2naqxorrc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdccnoe.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmwwjuj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2oagqglms.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ojndurhu.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzxpxan.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2qyobfksf.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2shtxysju.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnurrbhr.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxocndah.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ingphawk.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2suggesbu.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ereafyfi.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2mldkcqwd.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2rzpgngua.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2abdyyhnl.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxybdpg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2sktjphkj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2irohrayx.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2frksduou.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdgpjms.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dofbinuh.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxiczoo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rclkgees.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2xsfhvxoi.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwydwpj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2bgadxyco.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2opxxhggm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2iyubrchr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2efcaifng.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2ciysihqi.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qwndofcp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2rgsxxfsy.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wlaosono.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmuiycj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2eizosyxv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xyecvdhp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmicuuh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxpoyuf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxpplbq.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vquxpssi.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2uyanywgr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqnqsxb.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdrhaxx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2orsrhvkt.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2deerxpqq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2fenwchmz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnnkgsy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2mzctwrqg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2pxsroybp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwxtjgj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2ycsuttsc.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjstbtwg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkhlfoz.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2erlvtytz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2ybhaiqxs.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkyhdlak.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjhjrzf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iovfcbhv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqtgvdi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkblwmni.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2veqmzcft.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdzlpkw.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2rsizhakz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ryktdntg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2oosocfvr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwwvkqq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2wajtgwrs.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrhitvn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2idsqxksv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwdiixh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2oynupxvv.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ivsjcfwd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ntkgpbxh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmbwaod.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlwbzbx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2goncfaqv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxuvulb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtsvytnx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdxrgkr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ucarkbjo.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2albdvvgg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2tfohwmnb.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnbcmaf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2scfzepgv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2olenbtqr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pnsnobiy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzexmvg.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbjcedm.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptiupprm.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2alwzuath.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvdmkred.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2udrfbfcu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptopdzof.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdrtkpu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhmtcvj.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmomsvm.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ginnoifb.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnzlowv.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2wkulrbyh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqjhbsb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgzihwt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2mvaibagw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2snuhoelp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fnuoehtr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixumrjln.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlorpmf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqddjyf.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jyymldku.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvmpkso.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdjfrpz.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgftcuup.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2baacpcmk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2jindgnkn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2juhtrwvw.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpcykqp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2forfzgtk.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2tqirvtqo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zynhsvpw.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgrassr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ubdlacxf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2euwumpxg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtiktom.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2dexwadvu.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxsrrsw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2daosqjwl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2awwqiipd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqlgmfw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xqyutqxz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpomvezt.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rjovnmkl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzarfcx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjiwbjn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxazldn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2phdbpbgt.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vfycdyek.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxxutei.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2okscvkhn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxsdcoi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rutarmvf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pknmisds.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqfalng.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbsvefn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rocmxyfg.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2hscpihbw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfttgli.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2nuessrld.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2anssufae.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2irfyyaho.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2nfemeika.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2bhriqnqc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2iuyeavvo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmzctcs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jcyvwqxp.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2trhminge.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnbgzql.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjzdarh.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkqwhku.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xhaxjajb.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dhuearwr.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbobdvo.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpverkq.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfgaobm.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jlpdywer.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2heoxuedf.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2brpkzzxt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbesldi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vxkpjskg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfobkfed.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvmwetb.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2teaxdoka.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppengjzx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vvyohvlc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwqdfym.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xmlmcqyx.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2bbcudgsb.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2usdqpzcg.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdngooy.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfwvuli.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmsuqmb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ouarexfx.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgxyxuj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvtwcgz.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2twtfcatu.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwnnmmo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqctcua.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qiyphvaz.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjeukysr.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwaaijqj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnzrvufi.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eaxhedhh.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfcbiyt.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2yaibjxzs.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2emmnmwen.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jekhzuqi.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lueuafzu.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2shquzkqy.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bznjnptg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgbxxxh.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oiudphxe.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2amsbgyhj.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjvtopf.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqnatbm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkupwtt.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axnglbuk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2plscknpg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmywfsi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2dtggcshb.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkfkxxi.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnziylq.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdzkpcg.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2pohoyvhi.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvxujno.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkweybd.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lemcuwak.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2iaebtliu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cifvsyqn.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2vsuazfkp.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2srtjvgnk.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrbyhas.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2hobykbdd.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjhvdbt.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fgqiwwfz.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvxloou.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wunhxfli.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2yvszmvaa.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrxcbtl.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2osuymixw.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2avuxcxco.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2qrljcjco.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oikyulbm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2obxidwla.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlyyupk.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gclrzrqc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkiwnsdr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjcovyq.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dakliiyp.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2rtezmjtk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgfdmrp.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqzcxrz.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmyqybk.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2amcdbqjp.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbomqmz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2hokletef.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jovoigkg.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2cqkwikcw.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2nftmjsaf.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2kaamzlkf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlaykdcu.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2riyxjode.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhhjgjz.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tftzmwan.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrgutmr.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcogmyw.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sobtfsvp.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhltqmq.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpdgvft.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrhaqdg.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbehpbz.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsesbde.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyoorruq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjldlouf.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2enkcwymx.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqolhxa.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzjqpqp.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggaohbob.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwydlxy.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwmjrgq.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wihsmqzd.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gzyfbwvt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmrzzcx.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmdegyrt.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxepwvi.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2dtnpomgk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2tfosshql.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2zheluqzw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2boabbrwi.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2dvatkfgl.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iirremjr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2kiaiuxya.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkfvjvm.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnyeavt.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cseqidsd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mimyezpj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2snynyiua.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2kqultmrg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjqpnxr.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwzamhcj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2nitoaqlq.html


<!-- 参考信息 -->