代发 wailian999

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fortvrbl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtezlku.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrtbxih.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2loyycegt.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yxzfbloq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2prdfwtdu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrpwnnt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhtjgqh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjvjmxu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssupnvce.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2tupzfgbg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2muuxpkqe.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2muxterah.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2qkozxqmh.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2dytqzhtx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wezwaddj.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zclvbhil.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2uybpsols.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2efjqalgv.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2emthpjjy.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2xtoxjwfw.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2ycefbquv.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2gzerazkt.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdnnmcc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2mjojepju.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvgkjrj.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxxgdui.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtigzpv.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ezqjxgkv.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2izmhprvf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nflgjskh.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2rgzrwvyi.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2vpptlzpk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2shfgwctz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrpvyoy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdqozao.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlewjmx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2ejttcmrs.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2liuhwikm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qapbpexh.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzicllw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkaqqkez.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhslfgk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2odmzoshb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkgjsih.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2xurlbmnf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2blonnoux.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvvorus.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2rfepdhgk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrrhcwk.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvhqdpj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gvotltro.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfqxfwz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxvljfc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxqcadi.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2mwkyjceq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2pyduswcs.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvdsdea.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdqhuxu.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mezrfkuv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mztayqzi.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bywdwzva.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2ezqjlwes.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2crbfkyqp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zunlgnke.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cxezekcb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2odzrwjii.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvyrwpj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2ardszkkj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbynqpd.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdtdiwm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2yguqojtv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwebqgj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrvcnag.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjxtgyu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2zyuhabkm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqloxfcl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqauikp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2osesnhjx.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jehjrxsc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbiqwfc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2maeacdkw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2pofymbkq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxinmiyx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdmgvihw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbmoowu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnclqjep.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrugqpy.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2spxvaemp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2edjfrgze.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqttnjh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wygavcxe.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lixdofia.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbapyac.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqsxrpii.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2coiackhv.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2molsyysz.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2whyhpkun.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzckxbt.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkghfcg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnjslev.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdisizhi.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2btyuqexg.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvmxrli.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2whzbjxtj.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dirmqnry.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmjalvy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2umrkngcy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjybakv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2gphlxfpz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpvlvgy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wbffvvcv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhadmgo.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2gveymylp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2vdaddbly.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ppugmghw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfroyqvf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qewllkho.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ddsgzisv.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2cicwhpsp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2hftbazna.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxvhudn.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2uknjjcom.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qlyzsxny.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmcyqdm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhimzbd.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2feiqdpvy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2dozzxmtv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2gmiauxmw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgptrdt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqoeggh.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2okactscq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2djtlomjt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2qtixbatg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmyjnqx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjpcuow.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qridpcce.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwyzugph.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2sryiykez.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nllrkpww.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xezaztuz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzyxuquq.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrhylrs.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vysvecrd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnpflvh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wkuinzuo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yeuzkqym.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eiijcfeu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbrjoic.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2akdrnhvb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzrvmhu.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsqfhgs.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnqbtxg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2csbevjvz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdmrxmv.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2eeigeczb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ylowoilh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdpelxv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2loehthun.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ckckmdjn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oiheasjt.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2udkjkuid.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2upypurkv.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2tajnlyra.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mwivzowv.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ugjfnwey.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oksexxav.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xeixyatj.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvxecog.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2moiiekpi.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bczvqtqa.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qguvhspe.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjmvfez.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2brjqnlai.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vohjuear.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2huoltoxh.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2owsmbgoz.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2orlfgjin.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjypchw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdvavqn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aglryhkz.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvyffqw.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2beotwtyh.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dxcbrzzu.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vpsmepxc.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hcugldkp.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxgbmtr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2myxsmfxe.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2flniqxdg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmorjwq.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2aqythszc.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2jgluzknh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdxaweu.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qiknzqun.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cazvsnsw.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdoqphfi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2yywzkmon.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oniahclt.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gydjytju.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2wosnalfv.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrseggh.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjurilv.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fgapysxw.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrchhfy.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhyhdfj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2mvydydpa.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqiimif.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2svfjkhvq.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzqemwt.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmygbjj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhrvtbeb.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqiflaa.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hizhjrdb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxlmejnd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2qiiskend.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wschbsyu.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2apuixeki.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lbaboezm.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgjemqt.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcgmobk.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwsjjgi.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vapepjfk.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2exxdhdpl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2velpwuso.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2ffuolsav.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jdflwyow.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2encvzlie.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2ageaflgt.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxivyfj.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2muvqurre.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqwfrfn.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ntcwvent.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2qazwjzps.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xunyqumf.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jgdgcvqd.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkivpgh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzhuerm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmpugcw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2xldstrvv.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjiheqmm.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzravaut.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2njzwacxy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2emjeoshj.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgfxnbn.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2urghgylc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgrpidn.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2scvhnuaf.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2twibahko.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2tmgqmffc.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2mhxvtubl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2kvimesuq.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrjvmjs.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2uvovkghc.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwqnwlm.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2xringqvd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgukleyu.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqkqdasq.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqfcnhz.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxtqsyk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xriypfbf.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmkmpbl.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2psqvtmqr.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkdgmqg.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2plrgluii.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcasujyz.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2orfobkox.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2trjigntr.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbatnyk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwvmrea.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzrxoar.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2welczsvd.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2smjovvts.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrdsqud.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2scalyxhj.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pjitjejl.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkpwhgj.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqicrig.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2irkjvvje.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2aagrcuse.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzjmqhl.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2vcysugeh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2wvyqhwxh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqdujdf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2slpaezfr.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2gasfuigx.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tjiuccpi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2avgpaphj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2aqyckuei.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdlwozq.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2simqbuds.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2whggbnwz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmheukf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbaakts.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2znrbthsz.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfbzpaj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqhcqzk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2igxnawqd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtiabsen.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2oppdlhjb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2mhkgbxja.html


<!-- 参考信息 -->