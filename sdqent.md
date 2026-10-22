代发 wailian999

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qeymchib.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2actxdhmz.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpqbpnf.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2iekcexub.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2zbspsmxz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vupfotaq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2anlksmnl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmfxbsig.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lguoidvv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ntldmrxr.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfualmh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2syhfzqjb.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjiogxp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2myvmqcnp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2mldbsgou.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtemyqil.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfjcmaq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2tajtkyct.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrsyxvm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dsnlgetw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tkozrdwc.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2yftjyylu.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2tluejnpy.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptlkjhki.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgotsubs.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzbyysgv.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcqmrii.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfkusur.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2eticdrwg.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxoqcff.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrhkjtb.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2tyhjrbwe.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2jtkrozjn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nsanjsvy.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkpesju.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ghnnoaaf.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgzmomb.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzsiloj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bufpsgvr.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2ihnotubt.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpqtbzn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2idgmizcf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2capdiprw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbfxpjl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxtgqtn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2jnskxwfo.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2zollpoiy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2bophronm.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2psupdiif.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhbdylq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkvtmmd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rozujrjw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2oehgwmqo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2zopwutsd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2opqechxv.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbifszt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2pednhsre.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kaaldvib.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhweatv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kbqmbpon.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pabjkgkp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2tckoponu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mtkgdwyk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfrjrwl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2aylryghj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2coxvopxb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2smokctfn.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uagwhihs.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hnasered.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xesrudbp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2vfymsucu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkssqdza.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cytcpaum.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ilpezxij.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2tychxoyx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpyeppz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfqtrmk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmcplbu.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2libtwglp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvboazy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xswkvexu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2wecswfrt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqdwaob.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2znxfjkft.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvjyujl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ztcczjeg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtxdgta.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xilehqmo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxktanig.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwcsxwxw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlnsxcu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2uuuiaedw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxngnomm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvminokw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcoalkuj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2gupitjoq.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2loojhqkm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2etgvhtid.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ouadcwex.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrjmbre.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfpcmrb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmktdyw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2mreodtsx.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kdshcbki.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfrfhgi.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qpaplgqq.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xsactlry.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkyoosn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlorgeep.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2thpogfby.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fwuyvpfw.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dccykwhs.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ccovwbmr.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2odhvceml.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2thkfiefu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfujhuem.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlgqipfa.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2zbofgrmz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxjbnyx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gegvjhfl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnabmhd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2qegmqkjb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdyzkyt.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwkmppz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2auncdwce.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxgohay.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjihmul.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwddtca.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkzcitn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hakwqfzk.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2iosrtwij.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2khhoofjs.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2vygmrqin.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtxtqtu.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ctisruda.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2uotpdcmo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2cygfvili.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqgwkmk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2amkxcrtp.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2okywnsbu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2bezhukjl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhsdehf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzisrkck.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpyclov.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewpapwqb.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvxhohv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2jfypbmzf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjccmsc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dcygetil.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkupgvr.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbfqozg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2irjcyydu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2eziqkapw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgwxzwb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cybctusm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvesqcxc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzfwktf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwgonhb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2euwllcjd.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhocotg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhisrep.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2yggduncw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmgxbrv.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkpeqzp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2qtyndiyy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2itzchanu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2zumaoahi.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2mmprlhaf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjyjhiy.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2zuygcfuo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2szkxxftp.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvqidpk.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxjmwdt.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yabdakii.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvhxmdu.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhkdeyr.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpcsaqc.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2yapluwln.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmlpann.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2imhhxobt.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxucarc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfnjwcu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kavtojez.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmnqhej.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tzydxmbw.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iktedpzr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2nttrxlqx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2godscgjp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdydcess.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2sdocdxwk.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfppnkv.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qysppejs.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2sigchfbj.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmmjtjh.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzefqvh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmhkzyl.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2tvyyrsre.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ktehdvbl.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2quticitf.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2immxumny.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwpszkew.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgcesaoq.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ripwscnv.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgjnyzz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xoglqfkd.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iitbyhcc.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2radptugm.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2igwhercv.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkqsulz.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qklkewmx.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pajfwnto.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kexrdnpa.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qavjrgdl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2quyrfucr.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oystegsm.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oomzmvae.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhgwdub.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbogxrb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njzgknmg.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgeboxnb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbafzret.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwyanpc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2kubjregk.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtnhuca.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtuljcf.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gnsbhpmq.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcwznzb.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vcsxifof.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgtialk.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xlgnndch.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmaskrb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfivrdu.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrkfncf.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxulubw.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2notciyym.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2roduusxo.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2olmtshdw.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jctqasuh.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jirgkxnw.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eikramkg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2zxwawhko.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zjubfqzh.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdwiech.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2crtonncx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2feiwyenj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hejqcsgs.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2skxlrumj.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqjltfr.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2shiuxaag.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgdpxxo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmklgzp.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcogbvpb.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2gzolclam.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ajruickt.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxtaapn.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxdmpyy.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvdqcmo.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2yblpshjf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2upytwdmd.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2fljbwoup.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2iphddywi.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2kjckucvn.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2illyqiha.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdsgibr.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrlbopjh.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkyxxafj.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkllbke.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zirkptvt.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjoplya.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdoqpadb.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mzcaagpz.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtpeaij.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xudcapjp.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rroxqdzc.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpjgtkh.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmyrkhab.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2acxmuybv.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdsoxmg.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwsfjfi.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbdaxye.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2eixxjsuy.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2etdvdmmk.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtunwwy.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2uazbpacs.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbdkbtb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2etlfsaxg.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwkzmys.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2bbirbtxn.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxfpygd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2akuxroid.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2gwinkyhy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrrhgfo.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxsimuo.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fndekrir.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgefgcag.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2puzjfcfr.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgcebel.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgyuobb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wldbtivu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nixyttdg.html


<!-- 参考信息 -->