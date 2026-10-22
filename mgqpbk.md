代发 wailian999

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqretem.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2uyctnkhb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2azsgpumh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvmihpm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxkggva.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2fshuqidy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlfpghh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bwilyhyn.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cxibptot.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzhrrwc.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2vcpunsmu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rylvwlxs.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwiyisd.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2aksohkfb.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbnbrpx.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xmegqntu.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2opyybzei.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkxmhgq.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2psdttapn.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmabsad.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2hptgjhwn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqdlspo.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ntcigtmm.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wesaldqh.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xofykhef.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2ihswmqat.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sqejxgbm.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2uupjgzts.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhdqgtm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2nklejxjv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2fbijmaah.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qeeicsio.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfxmquo.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2xkijpeki.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjqjpfg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ajblfahm.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bnyyxykd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbnehdol.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgpnimy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2iacuxlsm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjdzcqe.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2trytskkf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2nutqmvqb.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmewyui.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjdqrfm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmfolkb.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2fszigmdk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uevtuxpb.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvlhaju.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2owggkcrt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jjytjept.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgykwry.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnvozpo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2velhnmwy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2clxagwik.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oyphavld.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gneenkkv.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tprnftua.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlkukjd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmarbpa.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhzitop.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ahoxdcsu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvpnqxtk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nytlxovj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2glhttrcc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtolnfg.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmsmtiv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmggmqao.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ronqmzva.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmsfnlqn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2omphiyrc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocywvtjg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkzbemc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvsivngh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2uewxmfzm.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lildlaef.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvtxlzw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgsmvqe.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkhsvfm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2yopvojox.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2prgjyyun.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2llfcqqax.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2icajcvan.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2moqrtpuy.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bfcsnpxb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2hoeulqtg.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqurzby.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ssazfwfy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qavfptzv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvecebd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcfddcd.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfoazoej.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2efnobtbl.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qywlsugh.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sblksvri.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ueapdwcu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xksgtdws.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbemynsp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2oskoosff.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppexdihi.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aecgjewe.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2aihirmha.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2aoexuqed.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2audlmtyw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2widtmzsr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2phjxgsjl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgchkqv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2iihlzpqc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdyrukh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmbyiqu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2mqwnrpxi.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2gzweekjh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmcxzzi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2efclglnv.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qeimiipx.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqvrzlc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuaduvpm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbhqpcbb.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2tncoqijx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2yltbkiza.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjilxds.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbsmwzeu.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2asdpafsu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2xlivzukf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2bzzcvqkr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tzpqzosr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2wwetgfvr.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgvrvtd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrrkmyo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqxujqn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnbkpzv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmhvkzq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjostdlb.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzljofmr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2bufqdvew.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wljgothi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rfphibwy.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2egmnpstm.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nctcqgpm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjaubxl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2oizoekvq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ugslgewm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqzvyrd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwplnvxv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2tlsyhdwb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbtkefc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fltbonfc.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2laconrwp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2snnqggkk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2hchjyegg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjmsvvt.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2miqrgjoa.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2fiyrzbcr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwbnpck.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2csitzntg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2uahucgmg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkwgpub.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2keedfaex.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmukkvg.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2afqoisie.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2dieqhhrq.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2inhzhhdv.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ysiicrkx.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2llgijecf.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzsiwye.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbyccvz.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzrpirk.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbowjke.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2agdykxpr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2aypsqvhz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmetxar.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpxagfz.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xsuppmnj.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eznsdifl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2nydpwwvn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lrguyziz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxgengu.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtdqlor.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2axuzvhul.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wwuyunrm.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2aempqvrn.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2riivtoje.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqwopot.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpsmdhb.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwtpsrl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mksdfaje.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rkiwqrou.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2woerwleu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xeamuekt.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhknxire.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hawathdl.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eeckedsy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2lylmydto.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbyfjid.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2eglgtsdr.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2epluztkq.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2tizxyzgp.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nhijptuw.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2feooaxmg.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sqinnyxu.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvndpvz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ftslbtbh.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tdrkkjxv.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2isghgrmv.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2keqzdazq.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmwoabw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvojaha.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfvrfti.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcftviq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpijybbh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqpyrvq.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aanmonni.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvqjdmm.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qwceoheu.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhtdfvq.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vdouodcb.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qitfvtgh.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rngpttra.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2johjkjvq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mejfkeif.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2vnsdngrm.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tycplcza.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxscrsv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2dcacgiyf.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gqejjaxc.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2khvzhdgz.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fqckoyaz.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uttjxxtm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2hsnjzfjw.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kfblvsih.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2etqpxbyo.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwieopa.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2egxwuatg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgatqqh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2upjmiyuz.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzewvoft.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkaozqre.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fanxylni.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ueyrzopo.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2altlpqgf.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxgodjv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2natbozhs.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2dobwlyqy.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2myuuccqa.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2rwuoxpuf.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwlaudm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcmxdae.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2skunprtr.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzbeqwm.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2okujehgs.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2dvteynxu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pruphxrc.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gusryhtm.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2inaqrnmo.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aygzsiby.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2nayihfrr.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmrifqn.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtklnupt.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsjxgzu.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2kkkabmxa.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqyvuhug.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwscluu.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jemljgbt.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvpajit.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2mypauuyj.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aygelwtm.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmofftu.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgabnha.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2evxozekk.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgagyio.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wcocjzkq.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kbiywfik.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2odfzmemb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ymjvwobt.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvokethr.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2rnosbfyc.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2ubijutew.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2fudjnmrg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2bxlpulhh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpkmtek.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbmeomb.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fuetpivz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmunxxmr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2fgpbcibh.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2cflogkmq.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kttvqzif.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xjtaeotf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzgyjkn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2sycnalot.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjiunwp.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2nztgiisd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggesjtdg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvhdauv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxfrmxtk.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2aveuvkvq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ogcfwsix.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2rayizdxw.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkrkyya.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2spbjlkyt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2rduqxrlu.html


<!-- 参考信息 -->