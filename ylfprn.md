代发 wailian999

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2odqicmxm.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcljelh.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqmywoh.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2iyerdxjx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2buvhbmir.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xshcbtit.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ordojpea.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnorogcq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vofiwvtu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2wsslhudh.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2jotuowkh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2onspxenj.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjizllt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2cycymecx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqlqrmkx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqjwbre.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzvvori.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2jweidbay.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfchkbrc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lfchmsiq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yytarwdl.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmcitfm.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2pqejkntx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rehtqiad.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhcncqf.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvthqgo.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mrspufzt.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2frkhfmfd.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2uuensggp.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2bybjemyv.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwuankq.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2mfesnncy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcifdzm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nbcjfehx.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dujuspfa.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uvivlrxy.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zozuqztp.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2xmriamyf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfcytxc.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2trppwfgv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2dcggubic.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhfcicr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2brsvjcjt.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2okidcbdb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2xjsyzhte.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2apoldhbp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2kriwnhnz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrpkyrn.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmfobqo.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejcrkxgg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2pjewxdxt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2strmkonu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gylnrbtw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ruevfdzy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvkibkm.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmtouzf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2exctmcfu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrannow.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xobxoykn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wigzludj.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpbepwj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2qplcdjdq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fccwodkl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2eysacedd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvryssd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xqtrcbcn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2nuybclrz.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvolybx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpvwhvl.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cibxgxdd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqbzgim.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bapvttng.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2adtvzxjj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hajhnnbv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkssczd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvupunxv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfjfaod.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvlsylks.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvchtsy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgjugya.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtiryru.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2wkcvdiav.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxlmasgh.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbralknw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkffejf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqtyhgq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhfpylp.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxlbbpc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2luhogrcg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntsabjhm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpobrcvw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbpfony.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2mudoilnd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhyqhpkb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvussqn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2fuohwvcj.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2souqjnoa.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2bgppqnhw.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yvjwoutn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ziafenmz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtcbihb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cqkcfddo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbnpqiu.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lfcwqzji.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jbytqstt.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqlpbtj.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tezcsxbt.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbqlkzz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpeappn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfakjoho.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cddxlarh.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aotvezur.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhodcmld.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nylxvmvh.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2svfycdmy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvlkuogg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2etdqowpw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwuqwia.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2vcknzwjf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2eexwqrdq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2vagbjias.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfbjkbe.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2gmrunrtu.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mjstkvwf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofutdrnp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jytftyjz.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lusvnlah.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jczcdblu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtiodrr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvfsujv.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwcztsae.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpihbko.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2qqimtact.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2egjfnomo.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbouftz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdytvmu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvhpkbm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmydljx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2igzijani.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yoemxeug.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2tekmzpod.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2cihwhkrh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhqxcci.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjryjei.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpjdebwg.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2viirjdwv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2sfenvyep.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2unjwsvvz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzxeiwl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrlnyve.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjgwycr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxdnpdpr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvplowa.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jajlgzpf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtyifdcn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtminnal.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgkfrtg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqvrzqi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2gahoqtrt.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdtjhrq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjstftii.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjzxsth.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbekumy.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2fznghhsh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2dgsoxxxp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzhmixb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2ospguxde.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2napgaasv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2obemydsx.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2shanrzff.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnqhoyt.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2yfegdaep.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2izxuslqy.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnozedr.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lpemanjj.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebenniuu.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fcknwcwi.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxauskao.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lnidrbsj.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hstaxvmg.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2maakymmx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpproia.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwtijtq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwnxwwf.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cimskbtf.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxdbxla.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mizlziyb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2glfnmcsi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qymbhcji.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzjkgty.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqxdovm.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mlppdnrp.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbvhmgh.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pknxodhw.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2exrskrya.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxcjvst.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ephqvopt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bfntrnik.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhsxxqm.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2owmgwvzt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkytida.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmnwbwrz.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxdfclj.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrfwqnrq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvimgas.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pomyzdsq.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcxfyqp.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2dzafohny.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvdzyou.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbgynzw.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ydllxows.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2flkjdeoh.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vrkzbhfj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2bzbpcbro.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjgdvyx.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nogskpmj.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2negahliq.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjkvqsl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2afdezjxc.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubibqbwa.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pinajyxc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkuyrstr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2chxgopmz.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jraajfie.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkuehat.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2urkzsbid.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2niwkmovf.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xoojjemf.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yacyofkq.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2sxevlwhf.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rgebrteb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2crpnsxbu.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2smpwytby.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mstghahg.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdpqfzo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2mizyicky.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtqzozp.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2amlcuuyd.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bdttascv.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mxauylki.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2svnwcyfj.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqcjuki.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2biyyhsab.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwrdylk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2uyisyfka.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aaivqtkw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzbchgt.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpvvcjz.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbbwxve.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2voooqsdp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhqgnwj.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsuywmdf.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2xxduhocm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2tjuyzeop.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2bpkbvjce.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2mlplhvxp.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2aogycdzw.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgptazw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgrfhrf.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2dtkxwmzc.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2yissjpgl.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2gszffzao.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2dsizzobq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmuzsghc.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jidmljdf.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmvotdm.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdghaah.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2racdjumm.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrfixqx.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aftjnmpc.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvsxbrq.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2yobcltix.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2phfijsvm.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdtxtzhg.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytddhljf.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aghgagnz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2olvyaonz.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gbackfdr.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyrtjyfv.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zezvrcqh.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnwrtkf.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vhygahep.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2trspbxfn.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qaszhtsv.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2phmdciea.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrtkxix.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjmxiuh.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2gzuqlexj.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfvdcjs.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2nsrmdckb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2qdrifknf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxjtxjb.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2vglhheui.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zazqkhsv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2uylbuleo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2tzlbpjfy.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2qthnwexz.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxgcmhg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2srakktql.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqifgouo.html


<!-- 参考信息 -->