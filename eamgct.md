代发 wailian999

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2psdjtqty.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2suaxuwat.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2uifcmxov.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cayfsdsd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bdouljhn.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2lwneplej.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkbermd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2glnkwamn.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmfobql.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2murrnxjo.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2momjelsu.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqqrxig.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2kswdebfm.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkumozu.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2qkedlcsq.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2qxosbnlw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2jbznqffc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2puyisier.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mruitmvm.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmrzfkt.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2owhmymrk.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgsnzqo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gdigmfkt.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxsbmwu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2xpseisse.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ppuoyzbh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2zlftwgcj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2xoncpuek.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qtijybgk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2pthuplyl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnczbtv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2litwtiiu.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fxegxnnj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxtqrtd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2omlqjsqm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2uridfxse.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2boygkwie.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2slqjrcae.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2khgxjvnb.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2eogshqul.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfhhojl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ocppyiyw.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2znxkhhmn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zxiimipc.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzepymz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcniuxe.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbbkjky.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2kylywcaj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezoyszfq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkyjmgr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2losoygfi.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2giwkrcit.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgdmido.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrsnqij.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2mfblrgsx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nycwmbfc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyqhvak.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2famqjhmk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2czajlvaf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpitorwb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqadvyp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2onzrkppt.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2vauxbeai.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwuiarpc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qamiompa.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdfngbn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2vaamxehi.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2uirnsaoj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxjrtrld.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnsouiqz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2caeqjmck.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjqrlra.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzvuzwq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2czpmhght.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2neqotiwj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vbajhlwu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrhozii.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwhrwkn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2myuzkepn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmejzdh.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rfyucvnz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpgevgb.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqmurgl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzywpojs.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ievztttw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jomzkcoh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2zghbqapy.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmocpln.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxonlpk.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmmlkzq.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2msplzkam.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hzsnldra.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2msgcdmxw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2savhavxf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ecfsrkmk.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjzmijf.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cyswpslf.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjffvyq.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2uhivpion.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvsorddd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xongykkj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrkeyjg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnqhzmd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nnumclgh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2cakduexy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjkxfwd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2ccgetook.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ychsklpz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qztmasev.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbnelzch.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2loshxwqq.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfnfviq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmdicfo.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhajzewl.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2exttnomt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxruktt.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2sqznuras.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hexyjqqz.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vszuutpr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwbqhob.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqcxyjp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nfaaeoqi.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2weyoflax.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvppmbfu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2khqjtoxi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2tsduipwq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlwefcj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xdscfmkc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wrsmsxgh.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2btbkuxno.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2tonfosxq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydyjdxwf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2csvjuzfs.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvunrtk.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bjorxcxq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnixfqy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hbzrgwui.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmdhnyv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfbdpdw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmutpdwt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2iyuwclgo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbsydee.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhwqqdt.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqzhkta.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2shsoxqco.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2suibymac.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jiecwxad.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2dkeiewzr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmnchrz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ccystswg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2sikfuplj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2sumkslgf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvsnuhm.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2hbpxwygu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oopqdtek.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxhtoze.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2tejlfsww.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfwexmt.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2skxztoxp.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwcwcwqh.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rflmmshu.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxuprggk.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdmrhrb.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qpgfuiyn.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hwuabbvj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2vrsdqyoz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vkftzshj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxnnbsuu.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oymgobse.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2goqgtwut.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2swastsjk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ktacqlup.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjzpepc.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vmzrwzsl.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjzyhns.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tpnootwj.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zaptcjpq.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hptrytyv.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2aixbrnaj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2tknuayqt.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrknnzz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vsujrrlp.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwgjmdf.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvifbct.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2novsnunk.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2palmgttd.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iprfewhe.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2itusaxpr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsvnsua.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fooegywe.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtshxuxt.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2hemqrgjh.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2hrsmmbds.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yijvqsax.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjfpyae.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrnpvqu.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvsmlsu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdpgexi.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yshohrjl.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2owdetiht.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfjovva.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxzsqukf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2guclhkuy.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqtyknt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxcwzbfp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwzhocg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2kdukomkt.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eisiuevr.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ioclamrs.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgljiyx.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywoiqfvr.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfgrddq.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dzfzfjkb.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ytikjfxn.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kwixwwfr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2btzjmuah.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwhdmkh.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvfapbj.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dtiulctm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2kolosunv.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbmivew.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2begtpawl.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mgdtkolx.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zowtlfjp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2huqkksli.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xqqgxyyb.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uuiaooek.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxtupoh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2rjimggxm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dukhikyp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2dtyegdax.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdjjghm.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tldghowi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqwuxoh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sgpkbbvf.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2puhflsin.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2txzuayik.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvyztdj.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ekuiclck.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2wchcpgdb.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2pmonwhdp.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2nrblyvhj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2yxifapbu.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2buzrlllx.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvvtbys.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2rdessvat.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmxuxvu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tshomfnr.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdkuhltr.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbhoxcb.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2toatcffq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhvdltl.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhapppm.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxnzeop.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgqtbhi.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwhtjbt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfxlsdu.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbefzde.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbayyqdz.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2muukajyi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2oryapbfn.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wzomfiln.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftawialn.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kuazkcic.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtvxnhe.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dxgnkqyn.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2niqicqgu.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xyioeobe.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wopybpkd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hnowoead.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqeovat.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhpeyas.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2uvrvbirt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2afdhwpwe.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2gopjooeo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2txwratmq.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ogqqpzua.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2icdzzkfu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgiuyndj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2qukoxjji.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkiuwhpr.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjxhuhf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cidbuxga.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmrtxhl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2gmecphpm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2moizcjlc.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcmkmal.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxuofrn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2bripadpw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zuijkozc.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2udnyzeyy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2rqauampk.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcvlnhh.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhqqupy.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2shhxacqf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2tbkpgnsy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxelyaa.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2prujivou.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2oandgihj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2upjkuhmt.html


<!-- 参考信息 -->