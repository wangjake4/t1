代发 wailian999

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgxkvca.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oriqeouf.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2xntuxurs.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aperyoga.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2jswyqxmc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufywhvcm.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2zumtppmy.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2blzhokpr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxirlvw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkerepj.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ziehzudk.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdhvapr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2cupypiyr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2domhihib.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iunanmon.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2altruqia.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdixwfhq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2opdfwrpc.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2rzpdflyu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxlprnm.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gxamjdgm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxntusl.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2docwntgs.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2pskglsve.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2exgfzbsi.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2izpicmai.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfoxjvdg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uieauzux.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ixiypjbt.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2msgzrwcc.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2tiswgawf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwddcrkh.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwzqefx.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmldhduj.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lqutjubu.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2frygzzuo.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2glnfvstr.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlbdatr.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgzqyxs.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2vvnuquxy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2crtdsopq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yjcifcsz.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkzutul.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvnasox.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2odexlagn.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2adsdvgox.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sltcgjvb.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzjargi.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2cilgiyam.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2etmtziua.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2uiwrtixn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqtjlxs.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2clftqqmx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2vslibobg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2kzmmvski.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2fepjxtuq.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ibeynchv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2glocserz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpqttgf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vunkgman.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2waoghthp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfamchk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2umacphyf.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wexlobrv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2suvkwals.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2arwnvqsr.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2blcajvii.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbtefll.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ghgcexup.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2iumdtzzv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwnzrby.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2uirkkaxb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqxjmqx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rstuyjvj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2dryhhslf.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qezszcxs.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2slwzgnim.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jdogrfqa.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrxodmo.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtzsgtx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kbchtmwj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tucqxvwj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ziceeind.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbekiyuv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuojvwho.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdijefa.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqxglge.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2coqqdrfg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2wshsenbb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsfsaef.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2buzfqojx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2endrfxfy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2unkszbso.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2geybjolw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2spivazdv.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zghmohdw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlaocut.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2tskfewkp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvyfpgm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2gxigdbfu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmairoaa.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqdshcm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwpxegc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2tfugnquw.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vqnxbese.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2zizpvmtn.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2umdgijsg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xadzceao.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmbccog.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjcoske.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzknlmmy.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ivclqrzb.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2anpzemvq.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nwruhmvo.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jttpngph.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sskkheom.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rscewhle.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tuvgzpgs.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2owzputzs.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fexmyjjh.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjufsym.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wngshccl.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvqjvby.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2aoteoyxw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgqapuno.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2pfsuyzws.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2jeefuzch.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2conozhwq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycrhycau.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2zilnhpgt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2uyodhhqg.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbqzznb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2maqmassp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2usjxqwke.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpcwlir.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2omufnhtc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsyrsony.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2neczfpmu.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbhphkj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ivglgfmw.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2qjufhtru.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2amnqoast.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vgepoyqk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2bubgnnbp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgfgwlh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tiphgxxz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2feczwtnk.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2avocxitw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2fnugtzpl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2kxoeaedh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmvgwcn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvinwzd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxlexpq.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjljgflw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2hxzdfxox.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbigkui.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gyeiannp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrhyvrl.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rhnolues.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxybhmw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxevmpd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lktgcjgm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dhknjksd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fplrrkjx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2rchvpvgi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwpcfdk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2oempezpa.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwnuscl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2igvvxsun.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjsogzk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqzytps.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwqucbz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2qadqfrhw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwppsvt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2shxootkh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2pqygalet.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpfhcmj.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbbmvxb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2awpwoubg.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwzeieh.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2kybztapx.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqhfoap.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmqfcie.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqlsefq.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iwndabwx.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2erbfzbjt.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmxivxv.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrmxbyp.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2chelwgbh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2fokhilkn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fgshtixy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jziccrti.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvgyojs.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdttopxu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2luyrzqjd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pskzgidc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmakdvbl.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2suhgrcsl.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2jozefped.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrmzbee.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqhmhyw.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrevssf.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxcsjnnn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2rjiliypi.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2brbgpgzl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvzuzhi.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2narplrdi.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvqhnst.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwgsozv.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjgbovk.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njiblkym.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bepmthar.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2atezaans.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2amksnxmp.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnotboj.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzoxttv.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2xreaqbnb.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgwnrwc.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qldqbndv.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsnrzaa.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjlpqfk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2awtsigsf.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rzoqwawx.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2obmnrtca.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jdsqnjyn.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2uvdanbng.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvyjsmd.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbbxrjn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shtqmybs.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jharuvan.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2acsbckqi.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gcarpovd.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2rfftijej.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lhtbvndb.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzwagig.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdjlnio.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hctzskew.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwopcfc.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bsuygyna.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrmitnl.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2bfgmmhch.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtbkqyf.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mbaazqoa.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2xqecmnuc.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxhgkkt.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gpesudvw.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kxkwukij.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mlljfjak.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ebteurkn.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nidzrgve.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lpydawqc.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjygqyn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2teelalhg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fylirmhg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2rvheoaab.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dilfblua.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2amqprzys.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkuckxcz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uebedurb.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdpaodc.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ygulwwap.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvrcbwtd.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxgocmd.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2sgogpllv.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2lwyevvrm.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2fybhwjzz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2uvaailgu.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfbriif.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ebiyduoy.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2erjposii.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvgqslc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwgcavr.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2srlplitg.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqeisasg.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmognjn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2nalkgxnt.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2yayigxmn.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwrelhh.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qzncntlw.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2nchtickh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmfwncs.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwspaeuk.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjhdeeg.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxveqbhe.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdaotbic.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fmaaxies.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjzharas.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2trszrlcs.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyropehd.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2svpbbprs.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gvowfxzg.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bainkpdz.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvmjphk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2pabqvvlx.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2dweypkqh.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2cyucmxym.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrkwydd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtiqsan.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2iemphoyp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2qnepfiap.html


<!-- 参考信息 -->