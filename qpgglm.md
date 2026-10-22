代发 wailian999

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2dodbcala.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjqoqea.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2qevrftck.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2khdtdcph.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fwinzhjs.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2auxhztcw.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqocala.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhruato.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2tehdetig.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtzwfoqe.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iurtlcpy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajijzrkm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2znrxqvff.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2thpdsxcz.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzxkhvu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgalgvv.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tzquuuvf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzotbfz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpeaaod.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrfeizo.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxfgtyk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2flidllqd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvrbgdh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2piyxpawd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nsawslgj.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2sjoxjxxt.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2nbccfwsh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzokeyf.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpprmeof.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjhouai.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kksynuxj.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzbkknt.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2pjltcfhh.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2aeowddrx.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2nvufbqgd.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2cwybokrb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2eiogrote.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nvuseymd.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mokitaty.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwhevuy.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxxguql.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2fqoxobyq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qblsgwbs.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2gozlkmjf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2surszxsg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2okfxwbws.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2igfawqyh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcfmned.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmnnokp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2zaowbtgy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvzwtjm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcwgtvn.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hozmqzir.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nonjhzlx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrlreea.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwqslxz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2plsivyau.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2mlpytcas.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqygnmw.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpjukxv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2okkqybmc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lyagrmcb.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2refzwvti.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2avpjnlie.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjsyulx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2xijffchd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2boivxurp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbpppyy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywolokok.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtxzram.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdodegy.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfkgwox.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ambaxxgw.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtqvten.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwooiyh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsujyxxf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2szymjtxc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lbehidwh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbkzkypt.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jygrskaf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2arjsrngs.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtusfwhl.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2bhkfsieb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkelonfg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxvvbyq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmrayays.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrpitxn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2pochdijm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2acvcihor.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhloalyo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ludzitfb.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pakhyrqo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2hijwammh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbymuie.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2paclauia.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2pycfvoaq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxjfjwi.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2umqslhas.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtlydkum.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2skhvohro.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cguotpvh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2nmldekjc.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvatgos.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzxwdydi.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqeefgnp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gojzagxj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2bysyggsi.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2afnszmcx.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uduubedz.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxqqdzv.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxcionk.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2raftbswd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lftzupsd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tykzapau.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2prpacpkg.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnvglzo.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxdbich.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qfnwedgx.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xycocrjq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdmywfw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbyvhhzu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrkqzcw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2spkyvzyu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjevibw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2ackyheij.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdsedsek.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkrinkb.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrdineg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgyovab.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgjbgzny.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2fizsuwau.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2nsllilkb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmfdpzx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqksiga.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qphhowgh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtwiubx.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2tathcump.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzheiww.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hugssceh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2nonbttgu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2fiunakvu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vtfnuadb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2gnffkqlm.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnviaatk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2drdpnxkj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2wpclpekp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhfpahj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vytvxzqx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxnnjpa.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ympsqazk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdnderh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwgmyqb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwpbfpkb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2evklxzjt.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwkhcxs.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2obcnrxmv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xccpelbi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2btjeyarb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnkuniz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvshpwor.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2ttaxqlam.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrkhmga.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbfzabk.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkkgoip.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzuvvtt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2zsoypcpb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2yvczzjpc.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2chouuhvb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2qelrxwoz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2lketzupx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2qaczgivq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvawidx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tsniwkhf.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2awbbymxv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sigmpfec.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2onjhygsk.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrvkpbb.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzbzzsa.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kprzjdnw.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjjshuz.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwevoym.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfchxzw.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gglmkpsk.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjhlnrh.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2goqvedvq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2oergzbrd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hknoaeks.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbyhbpx.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zkpxgyau.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsotgsjv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtyxcqf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvctriz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdswgsq.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hbiycedh.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtqxikp.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqrxerq.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2atfckrvd.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzkorzw.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2udtnubev.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2sobjiivl.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ivoldbcu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2djpkqwon.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vjbuipay.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2faxdurfl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jucrscxs.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzivlvoz.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmasuvma.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2btzymqjw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2feunnfqs.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2spyodenx.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2eeokxlyz.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2llljwkve.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2tmllhaom.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmrvfqz.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ijazzzmz.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oahliotq.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xepcdghp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2psqttymt.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ymuzldqe.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pydwnfai.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmmwvjb.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvvcdtk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzjxjnp.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwwudzo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2emsouben.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjlkcops.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdojnno.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xmntsvse.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2izqzacwk.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbbeqyg.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpgnqjo.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wwogafim.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yopdriml.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2thnteyfb.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mlidxqvk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pujljswl.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2ohcczibr.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhuhxiw.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2toyvaghk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2sesxtmac.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqawtmz.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qysvfpid.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fbnpfodz.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mukrzsel.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2vyaxjtwv.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2henwykcw.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xmefqojd.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2khvmggor.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjgelyn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctezithd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2tlihiiws.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ooepofci.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjmzwyf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nobqcsgm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2szqcznlm.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgokdwih.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqvvwch.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2dqnozmmf.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2kqckcjta.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2qsfpyivn.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hkajtgjt.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2iozzklvh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2dahnanhp.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2dxgouzjt.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2bhavfqbq.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ycesbxxu.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2saqocvgg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmpceki.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljupwmdn.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gikyzghm.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxeinklo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2cerhptiy.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2gnsbarjc.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wymspvmb.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2djfmjwyj.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2zuxlvodm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlszefj.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gserwrpj.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2klrtojfr.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yehakqty.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvoinsfw.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjxgtqh.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yunzbzhg.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqrqdfd.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewultpqk.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2sublbckt.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bhddhscs.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wycvjbvv.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wosdiiif.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgqsgsa.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrwremy.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2tasvdwup.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2mncfgqbi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2hfffyylr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2dtouykxu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxofdxr.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdnrfvz.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mqsoptjm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzzmcdo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2amjcnqji.html


<!-- 参考信息 -->