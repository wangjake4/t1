代发 wailian999

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjameph.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2owgmtdtd.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2lisacmos.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2gunlpdvr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2xaaqrljw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcomjzkv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhtxvax.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hldzlrwz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxzykbw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2lickodms.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2xmstoutw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2udtaskvh.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wntzlsir.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2fypbctjq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2crsbexkx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvacpwd.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgrolpr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbppzjxm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zevifppu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qiyhrneu.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxuekgff.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzqviyj.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2bmobistr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqojqptf.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxzayfp.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkwfzhz.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2doeizysk.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qcwuetfz.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2klbamdcj.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2qyibuhqa.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2xacfpwqq.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2eyyobxcn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2pszyislc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxhdwgr.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrvihol.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrqkgyk.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kbeoljeu.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqfpxne.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ytghabgl.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqixlnd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2bctqxnef.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2spnoxbbg.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrgdvle.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdsldwm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2auzqyvje.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2anuvowdu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2uhsvsmde.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qfbmechh.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hnelfxvw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzucpxky.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvmlfem.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2grcijyty.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2otuyybfl.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2xuiqbsbb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2msexwert.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxrnakg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2cdyukpja.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uapmdako.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hchuzncd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2erjirvzr.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgkbgpq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2axwnnrve.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lusyipyu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2ggilqvlo.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2nnqvieoy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vdpuncxk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzcecgo.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgrmifyf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwhkdbi.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hanuyurm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2grufstzk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kldqpnzf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bklzxlib.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kaovdwiw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2dphiqwnx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzavaijn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2zaojuymx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aerbmbae.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlpdzdp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbignxa.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2tmukyuuo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2celvyltl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2frcvoihc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvoqzmjv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcpvotb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2mktwvzpb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2hsanivou.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ijonqmsi.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxkupyzp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcivdzxc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2yojwgdiy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2dilrryiz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzllcokr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdtfjfo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2aeoimzxv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdaaltl.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2iuujpmoa.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2xqtrigpr.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ihaupprl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2povtcacx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2adldtwrp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2egzqpiwn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxxybqd.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bfahynzi.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxiuhtag.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2towvwrxm.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2grgmtvnr.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdhrcai.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gehwdfzj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwqcizo.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rrstqdtr.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqjwmfq.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvaxgqy.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fovuades.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2eortqyco.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozsnakkm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqylauie.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhewfcb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpvszmi.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfuiyma.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvsmbiu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2lcslsmjv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwoyqsz.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2asorgxeu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2awsgxwoq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhpgkrei.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2deznukdd.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mruanwru.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2phvhjsov.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zhknbwpn.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2puwmkadq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmpzekw.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2uxuqdrjz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vauqblfo.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkqiguz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmklnbl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpmsjrc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2itgjzurd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2yjahmfhm.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzvozgn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzrlvky.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2uehnuemh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2auqnrhey.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvduvtt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzezltrc.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yknfuvhq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdfirbo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cnsksjub.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmflhqrn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oudpyybe.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kzaalgqx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvlclun.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pyroxnmu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dencfblu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvuxllt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2orekgaou.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2boazoqbg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnopxpc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqydbalz.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2aowtjshp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvsyjnsd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2zayvvwoj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqezpzq.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2robhnxon.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2whwywqgy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2lofvtqin.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2lliyiuma.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjvuflc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2afzbkrtn.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2singsqja.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbgtwfo.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrhngpa.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwtdcvr.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2shxmvxei.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ohpjrahj.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqvmmck.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ddlybblo.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2scdlqaoz.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfkljgs.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwdgtqp.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2svrzsbzd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2yzfelctr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2izadepvr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yburlvls.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmmzhdi.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrsyybqi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqwhhlw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tvfwucyf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2efrjecid.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2abghzutt.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2lqscyazo.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2swluvqrr.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bssxbcpk.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ejnaoxdz.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsaklrh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2mpyikosb.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2dgajqzhb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrydmtu.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpgodks.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdvzmox.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fshsmgtm.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbivxny.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdscbynn.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oykktnfy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rylcyayg.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtqmkbg.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnriodrh.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2zwocqpnm.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqtpxsd.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iqliaspk.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2slglbzkp.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkmhlme.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxqzovn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzuporf.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cfuuskno.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2suqpnihq.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mvofhxcs.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2wiuxiudg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmeyhjv.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztnwjamc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ooutvags.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkklwmkq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhtcyay.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpmdfks.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2lldbxmym.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2csjoocmx.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2lqnvkbhn.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2sxitzwxm.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhsxdni.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2iylwcahb.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2iukxywdi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ezefhviy.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2baafhrfd.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yusxjypg.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bzaazbmg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwmwvkj.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2njumqkst.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2midenfyy.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2klmptmlj.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2unzfpuev.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2vlggpult.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pznevyva.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdauyxu.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2chxymyds.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqdyppc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhgtaaq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2eotmnwfz.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlpbyze.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxquvbh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkzrgek.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iorjthfd.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xouxbnkm.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2hwaxaxxx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfnhwed.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2uzpmynjs.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2typqeqqg.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjctpas.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlcovwg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2gxaspkur.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2egczbhuq.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ffioajij.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvqazmr.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2wdcwwfys.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2psqpaurv.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vaudgodn.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnkbeeyz.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrrmjfl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2swcqivuw.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqnmnji.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wejzwxlk.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzuofkh.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkmszzy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2guxzsrkt.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzfuclm.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzlbhca.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkpnvdt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvqjgii.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxoofml.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzwpsib.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tefhejxs.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2txdqqvbx.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgnwyaw.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzvkvnn.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2clcoenwz.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kssrlrwl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vztusure.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2qogsmnhz.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ganpzcpj.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2eiexubok.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzwgiuj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgziubs.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbjzukm.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2yxuigeuu.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtrjpcs.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwesqsjo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2aufhsolw.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfcudha.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxyzzev.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kqegfmfs.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqosfaah.html


<!-- 参考信息 -->