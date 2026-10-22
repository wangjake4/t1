代发 wailian999

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfgsduv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivsgvdmo.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxplhwg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvwxkis.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhooipi.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2fozeczet.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2waymdxvw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2llwtjleg.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfdppgn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqvqmyn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmwfqpi.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhlfafv.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzizjnwu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2obmcpthe.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2osawqpyg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lsnnmsuk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqigsxq.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnjcnhs.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2thjtawks.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsstucvm.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvijpdz.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2mscdkeag.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kownfxni.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhofpil.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2kjioqkzc.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkqnyhv.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhnzmck.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2mibyalim.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2ncvthpqe.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2orkzdfpk.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sgeqfjgs.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yrizqdrk.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wvlmeygx.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2hydqqihg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yivzxcil.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2udjqaxea.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2fiyqncml.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2jskvntdk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2mbsmnqvw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2mhajvols.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqltkbw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2eptrlycf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ibgujzpz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2lxwvwcqg.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtzknkf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxihdkyd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2yupynrfa.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ywncxsnt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2knyygeml.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2vaiuulrt.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2eitimanu.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2atdnbdck.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2sihxkmlk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yckewapy.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2uannenqh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nnixbobq.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ellgbajt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2asofvmts.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ijeugoyi.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcxkqlk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2zylztvwf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqzygjp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2fgryicck.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qchvjsud.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qpktllcm.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yafzdvwq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2oshzgmxp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2upejgszp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbnmxxo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjnbxop.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwcnpozn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwyfdqe.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2tduhtrvc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwlebwy.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2wihibpgy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2zktfetes.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbwcipk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2thfmzwoe.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2hxoomarb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkybuqqf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpafmam.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2fpiedvoo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2awfnbwkz.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kaebwdap.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2erhkjsyp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvogktvy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxboefk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2sitwkrru.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2aeszckke.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrzwqheo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwblyhxw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwaegfn.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wwklniaf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2ighmertv.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kesqsohu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwyikau.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2snjqhdzr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2aacplhfj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvfqimwt.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdhnkht.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bupqndfn.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ayerwppf.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xpsflvkg.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlzajuo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2chsfbvfn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwofman.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxrsccb.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjsufhyx.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvglhon.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2djffcuri.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hicofpiw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqtrpeb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkgcdkuo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdiwmdo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2vonxcwtk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wswfilad.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2kekinvqb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxkaqay.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdzrybu.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2egaymgjv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gochbvgr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmlnvpx.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmxirvx.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2werqnkfl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2huusfsjm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxibkag.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfnmdur.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzsfxsxb.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2knrhflqt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cngniqvu.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdjbvce.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2vxslhdmg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ervxjmln.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mwaahfqe.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2qcypzcjf.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2demswtpx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2oelysnmc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2quzfnsxk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ablfoixz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lvnsayug.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pdpyiexm.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfavcpl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2fdibtero.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pureqexz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mojifduc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jfvepokq.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ywygyuzk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sibxklbj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnbbome.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvnwcip.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2skgoktra.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ophuqmsp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2nslkbarb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mowxgaao.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnrxdqj.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2pylemfcf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbmcyns.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2cduojvmj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2grykglct.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2scfjpyqi.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2zuciyqov.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrfsbke.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2sosrvbig.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqhwviz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bnpuaexw.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2acdozjih.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jqlovjcp.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2qntwgiyx.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2hywqjqrf.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2slesnipi.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tzlmzfwu.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2trscffpy.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aoiowlea.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2abdjbvwt.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvifyai.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sihzeabq.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzkvzwa.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqtmjgq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gqsqeuql.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwcqfir.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iuemgwko.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmtlpor.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2nciakltx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqndiku.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlsajcim.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrjnlgn.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjewzwn.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmnhmwl.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2aucnnunr.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2onvhmehe.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2udgwoare.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjxpupb.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2txtwhqxb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrlzhns.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrunhzy.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2sprkecae.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2llncvgtg.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnxivgz.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gquwogcv.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2adbmxxse.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2efdinzoa.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sxovpmif.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxgiida.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2npykpjsq.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmssfdn.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhzwqeb.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2isguthei.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjiqwpj.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zbkpyxsd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2heyissnc.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kroiegna.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2khaewoee.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ninprvqv.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2pwnkvvuf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2prhpbkeh.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dandoblg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbvghti.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2djqbgodz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2qapnrnga.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmcatml.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2sdawowwj.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpfbtlh.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwyysfj.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vautrjcq.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tfthlkek.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2edwnirid.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2twtnnman.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rrutxgap.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwcqlbx.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjhlhhv.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2prbfgkns.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2iioomctt.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2paibtgsr.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xlgedmja.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cifuhmec.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2utcxiand.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmlvbzy.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvlwkqr.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ssenlyoo.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpvuqry.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjtwjfe.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iviuehly.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjnbves.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmicaezc.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nekwtypt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zubibzms.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ktztimeb.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsjcxhit.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2jblzvgcg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2pydywnkw.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2fnifshax.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjfzbph.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wlulsboz.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2rsneesqq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2flnrygix.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hskhcfsy.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2gauybezs.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjhxxas.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2pyngmksu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcjvzfgk.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kktonqhz.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuturvxm.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrfacel.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgsicux.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2spuzcptr.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqpwjfzy.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qfymknir.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2tniwfxhb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjjiiia.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2czguijrz.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2genacmyk.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzscgkzy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2inweqmkx.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2attpipkr.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfvjkop.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tivimmah.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffvyzgvj.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fuptmctp.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ndtoetuk.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2insqeagd.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2chzroear.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ynnaxhzl.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2nolwlyak.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2xgubbtrh.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfvjxqa.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2eaxgofep.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2beuduknc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2zhrbgbcg.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2kiujmbag.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nfttgblp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccwiygic.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2pvacunvu.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsoljiig.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nuamfgpj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkjjklr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojehbaem.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2vchatoyq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wttkveuf.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkbgcms.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjibrxp.html


<!-- 参考信息 -->