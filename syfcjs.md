代发 wailian999

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gepgmrsc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjyrrpky.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwufawvj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhatmxu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2fprxlypl.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmtwyokr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfastna.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vetgkwso.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ckgkhbrg.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwytjxw.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbeemcp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqidggdm.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcodyck.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrjxrfu.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ubibepav.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2woqznftt.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2tqpchixe.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2amxbjwgu.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2tnolfari.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2wxivshti.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2ublbrxlj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vgttieby.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqmbxwg.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kstrnrnj.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hpsmdtqq.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2ygpillri.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lfzalvpt.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2volhzpkf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzjzxlw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbvdxax.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2xehduxuj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjuskoh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2imciimms.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2pxesdbsp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ubpqwcun.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ggaenztp.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdrvrih.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhaqqohj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2byblpgal.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvqouzr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lebaxkxm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2eywchrlc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbedayp.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2sobyhcju.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ltobsghu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhzksqt.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2blnpoqjy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2afexaasj.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2brbmfivj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2imwhmgre.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqpekvh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2ynodebcx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjpnyaa.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2czxlikkx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2tiwgqdmw.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qygolyou.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bigfzxju.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnzindt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2ebskfbkb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgaeorcn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vmsrtimc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzcrrim.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqytgajg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2soesqfww.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrnjdai.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkuqeyh.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2selsvcaj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2nekpakbl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfirekv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2eaiylljo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ozfjwnbs.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2uewgvpgs.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmslwog.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2uijpsjiw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2spkgmeao.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqnhqzy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjrwsep.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2yujmqbvl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2kzenutqh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhbjmwxv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxvlbet.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxygwesy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgojkpgz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdjrpvp.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wboomqge.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2wldnildj.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2viagovco.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hvipfabq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngppxawx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2eaaswmkj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbvkkjq.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iumvhipi.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ivktjprm.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bmzvlplx.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqymvcgq.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lklsfrir.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwlgupj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqwmozf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cisdctzg.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmwikcd.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qylesorz.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yzcryeax.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xzccoqfp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wucweeii.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfjkadx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2wpitpofd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2qdcbcfbb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbmbecp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvyszylf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdumshff.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2bztbhvin.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2eyczggjf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmknkxdd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2biliukrz.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyshjli.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2knyedpab.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2moygwvvq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2exmngeqd.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzmompi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ctuatxoh.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjsyjdp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rpczlfgv.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qdnuockg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmqzxoc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqcpvas.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdkzona.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2ivafmjub.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2znncgznv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2lveyyxam.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2igmgimbx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aduavedv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2iqinpggr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bumveeut.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hvbkexxy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2puajehgz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqfzpyq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nynyjiom.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zyprxbbu.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrvtnaz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgznyxvb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pkdufdrh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvcombe.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrestzl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2joginbvv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2qhajuqzs.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbexkzy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2uerplivs.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2faiihwob.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmlbtyeh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkwjdie.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2pyehlzau.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2xuufnijr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2xurrldoj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvjiovr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2odnaaukm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlwvntt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hysophbr.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2muiocfvl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2huljassz.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbfioyt.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2hjqdygld.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkikozo.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbimmfn.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtbwzpay.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2npwncapx.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbkmrae.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2seevtlsg.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2siiasiau.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2unsmiwja.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2lweijhey.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbimfwh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvansnyc.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zhtkpjlt.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shkkdlea.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjuyjsru.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uczcutvm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlyzoeua.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwpmolm.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2rskvfnux.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dnznvvno.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kauvvesz.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wczgvetn.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lygdmury.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvtfjks.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2enafvcyb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tpatqtfb.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tfymduyb.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2orufmjqa.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2exaaqdig.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnihxzvt.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yejsfvkv.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzzopyc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbksuyi.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2khsqjjkl.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2frydghgk.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2pddcnkgh.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2bgroaxtr.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxroytw.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2turubcll.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqdsvua.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uukeowgg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2celzsdcg.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2clifiyic.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jygtotqa.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zjyyuvzc.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjwpfar.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwezoptu.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmojklp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjbhuio.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfqckpx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsaiptx.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ykevgrxw.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdtiaxb.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbxrtcm.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ifacbdrn.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fgnbpmbi.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2avszvhhn.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qvewyvzr.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cvbcczjd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzjqhxs.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2gsnbtarz.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tpeawxeb.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2yjsqovmr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgyuijm.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cabntpff.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cfozbwla.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvarzjb.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmevsas.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2lkuntnne.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2olxcuvzw.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tksevfck.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2xjyaqfwq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgotwab.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkaqsljz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqdlzen.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxspgfrn.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrobztwm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2umtfcjnl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2igmwenli.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kikhhtta.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2gismvhoz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2utcmzgff.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2aoictzoy.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2jtgkyuuu.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2kdcnnscx.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2wuoaziuv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvjtcym.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ncenuojd.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2mgyyeggt.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjotkvb.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2wtcdhsxs.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbqnvht.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2glwddzzf.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2icfqvjxz.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlfyweb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmccoqj.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ufguxusf.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obgtjzha.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vctfowab.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2lfzyhszp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xarohobq.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyoduxu.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rizeohui.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkoojfye.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrkdzcw.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjhsorw.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2edtmouuv.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzbeldc.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2clbttjgp.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ceugbxcm.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2swzwkulg.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2blhjcify.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pueislhm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2esiskvby.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgnrvisd.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2bbedvtvf.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrpbqnp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnaxadl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2letxeebq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2thakfrqk.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2dvilrqxj.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzpwmam.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzswxlsz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2kozqgtqh.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2knupofzi.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ioldbakn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmziuih.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqyqavf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwttyqz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2arqfmdmf.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2sudweatm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2eerxvbzi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ocynhyhv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmrqqoa.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwebifr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmsccmw.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipprdhiv.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbgehlb.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhcrucq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfcyjia.html


<!-- 参考信息 -->