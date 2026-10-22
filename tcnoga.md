代发 wailian999

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2thebsefq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzfsfwsw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2yobvgiyo.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2strnvyii.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vkmkhmcp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2jdciaudv.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgopbesd.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2hpsqkjlr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2shqofvzz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttyheehf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgweqfav.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjbcyey.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxspcjq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2gaovxhhr.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2jsskuibz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2bgqugerz.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjwinkh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcvwzjz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtmwzlg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqklssn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdsrgmvh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgioavy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvyoszn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qridkskf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uofiafly.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2hsaixohk.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2uasvbkdo.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdsyqyfc.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddsdovug.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbyrsvzk.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gltijrqn.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2lfyqzhtx.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpiexup.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2xsgaxvoc.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2wsgxwqdr.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2urppgpox.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2ztiyuzjh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cdggljou.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wnygwwmd.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aupdlxyg.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2akrscwjj.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2bdedddbi.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnwsyof.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2xyycruhh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2pklcywuq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2iratsgql.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2jgyflcfr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2dcejgskh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2wafkwmuz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2murvgxpl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ramzvcnm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2glqfhnsz.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxchlqo.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpopnfrv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2xxuovawg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ikgygykj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtixusz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2jpttveah.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2cszzcdct.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2impyldjn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwgnyxw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2thldfout.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2omhhrgzo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uaullfgd.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ngocmxhd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwdzbtc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvfzwfm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxgqmae.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixpwdacq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsejthp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2qdeiutof.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vkzhhcgq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqtkvpe.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vibwzkpv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpozdgs.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqbycms.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aoyfijto.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwbznyw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmadtzgf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhggkbvx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbeaitni.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2trpwgdlg.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2vlsxpxbc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2gxcqdlne.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xrobalmd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxkpska.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2hejkmfei.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdmjqkm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvsczxnz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2gsuhktco.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2unxbqkbs.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uiztmcyi.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptyhypqk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxuasvlw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvbwjqw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvsicome.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlidufgy.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2lorzpwep.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuaeixmm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrrjfig.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmlaubv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2cynjrdfi.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlxvlbr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2orxgaose.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbsuophl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwllshl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2leiohcpi.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mytflrlr.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2duyllkgx.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wbubgpmk.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfxxfbp.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bokldvzk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gliwhzym.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lypsuyvb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fdzttgss.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aoyvxmwa.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2egtzqnbs.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2scdtcrhc.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2reghbbaf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvlwsoy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpixcvzf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2nwozmrvd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2gndyttnh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2oatieqwn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhkkdrj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2zquptxrx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2tefxxelv.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2nzegnawv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2aspcaska.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmzvpjy.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2cubjchuj.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjibvzlk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtydocu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcsjeaev.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwakalze.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wllymoig.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2cbswkehb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vsglurgh.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlknvwv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2xqyvkhcu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgauwjq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zvsvefkv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2ardqtnvs.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fuefgsxb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vdvipagf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnxancj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfclulc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qvroixha.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dogbonig.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxlyofym.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjczqon.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkhmxhc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2korddupo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjdlliy.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lqarwupy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfiwlns.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvhssqe.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmtrupa.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwjfgqw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kowdgcra.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2lvnwqwlo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojndcsti.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpjxnnm.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2txiycjoz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2lztuwmmi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2dufurfrc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbydqpu.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2dukgknvc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2halbltgr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2adicxcon.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2ctutgzwb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2iswgsetv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmijmhe.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2nwgtusdu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2soedzree.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ozsmzyxw.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2lcekoucf.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfawuyl.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2flxyerym.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykoaswke.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2heaxaxxz.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhkvgckh.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mswiyfyh.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ptwgfdch.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hqoqqtil.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2elkqctjc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdrxhym.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzowbyi.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mclsaicp.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tezfboma.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzhaemc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oydwudpq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtskdjae.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvzjniq.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2vazwiivd.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqmabnh.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2smxcfqpg.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2omgpavct.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkpslsjm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2epedzfkw.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2biajuebx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bkatxvbj.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpoholq.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2qudmassz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2deyfbzec.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqbcgca.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dijubqcj.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkaoxfz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvclzjqa.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqrlnjn.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmhceem.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2izbdouaz.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2blcvqbfy.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwmdabp.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zdsbueou.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tvztdsgh.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2shwsduyb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxxghee.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bxyfhzbk.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2adiammxh.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xkudkkdq.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2sqlnzpsj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdppdbqz.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yodecarm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnzvsdd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uadwxupk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgbxdqz.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qwenbycl.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2labilxlq.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbybhle.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzregvg.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ffetgwgk.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dfsgujqt.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2iykzvlvc.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwnfqkk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjrimlc.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmjojmt.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2oaahmasn.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jxlmnmdt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrgpfys.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfrnbkw.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfacrme.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzzcxkr.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zkizretq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2nedoccnp.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzuxwjy.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhvbdhu.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2vgfgases.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjncpzh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqipjuu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2pibbnrfd.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvtjpyr.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2phwxbxfw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uctucfao.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2isxoasau.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmhdcdv.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2aulovczh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ocskjnsf.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2amgmagia.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbfnffe.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2snltblai.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkfjkuj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2nheztkst.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2gofdafco.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2tmnxmefj.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdhomib.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2orbbqrdl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfgsvrbs.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2snkokwmi.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlcstwa.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bndipjez.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2smvryckq.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtocoqt.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckuqbrjl.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ctphysmn.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnelpsw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkszseh.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxuizdde.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgnqcmg.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hysvkgax.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2uiimdzev.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dalwducc.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bksxiqls.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnchyci.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2xejeolot.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qftvgmmm.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnxlgbl.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2upbpdfio.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gqpcpcpx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhyglgy.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkooaorr.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfesinv.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2eiuperho.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2zrljndwa.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2jproylqs.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnjfcon.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2znvvspvh.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xvuqimaj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2granpxbi.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2rrahusti.html


<!-- 参考信息 -->