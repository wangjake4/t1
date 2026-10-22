代发 wailian999

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oengyfep.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcubqmli.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2joupqxtk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2isjwnfji.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnfdgxe.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qeneinda.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzmvcoa.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqamjvh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxipeie.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2dzchgmqd.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvqqsrc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rflrhpdr.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcahpkkj.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdckfbdy.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2htagiczj.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxiflbsq.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2pxizqjre.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2twnsqpik.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvpnqvu.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2smtsmban.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhedmif.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2joyeoqmo.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfkrirn.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrlxvbi.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2punclnev.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2oterunjm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ugzzqcts.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqvclhw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2javxcxeg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhwuvsp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2amebsgam.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2idxcwxgm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdajihi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwuxtjq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2uynzgrjv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwbdccw.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2teywfdof.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2airendzn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzwnohw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbnvytt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmbyfuq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhmztjn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhdsuem.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ujyfgziz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2fktxpmak.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bfrxdeep.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2bovtkdcf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwkpzuf.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hplqlidc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2uojxidxa.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jwyzeabc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnykfdw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2etjgptjm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ezivusnq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtqdqaj.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cklnujza.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ekkfmcnl.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2higilzzj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2uafoeylm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuijdedk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2knzoryih.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vkzlgsvj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbgjoex.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2znlxaoqx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2irdfzsap.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkbmwwb.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2higyjcox.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2vryqzprx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qivkjjtx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfiuigfh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2usoitsqy.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2dcredjak.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikilwgvc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2gubmycct.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2itrcqpey.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hvsweirv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfoswaqm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2amzyufql.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2iiifnqqe.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2yailzauu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmngbvc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdkrikc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjsvtvf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2axgvmbcr.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2remvzvco.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2uefagonw.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hpipszkz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwoelis.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hvbmyrxb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qykxlnqh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2phrcfkxu.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfyvrfjr.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xdefaqaj.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bvsuiqlz.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ntuepjbp.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vldtzmsp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lycbfwnl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eefmvcik.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zgghhtmk.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtponvck.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfqpplr.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pflollao.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkvbsbz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfihtvbg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpswltbh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2cdixkekl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2stzfiwgi.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lztvghby.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2oefzmzoy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgfvulbv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2rprejgys.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2releuxxj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2evxvxnnl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2abktezlw.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdhpjjc.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwvlpox.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqakrwts.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpajamxo.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vizwarru.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzeklsu.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgplvpj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhyalutz.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cjmxchxx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvgdxcz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2binmtxgp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zusgxhld.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqmpozr.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pnavtzri.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkmjbxp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2ilpksptp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2caggybow.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qyfpynve.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvwxosy.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcjoabt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2kklveumk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vraeulnl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwhjpqr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpwffth.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2acwsusxy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvhctxu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmsvesn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvgwmqzt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ldoxhccq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrekpgh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2zqidgqph.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lghobdug.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpddvvez.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqupwwa.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjomxth.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkaecwl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjsbirw.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2zqerhnrb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2wkyxdhlt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2cyorqntj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2zxupjtnu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2cllacucf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aqysahbx.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmgmrzx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ohotzsbc.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2waszkpxq.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2lizohmuc.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vudhehvo.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qpadnkxx.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfikbgvw.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uytpmegi.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwoobli.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwyqkhd.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2efhqjxve.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gtspqxtp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2kpchfpbi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uhanjaub.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxaqwwqv.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uybbdmfv.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccfhpsxk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2oimncysv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uyavksup.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlmlukv.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2emyjssdh.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2abngaedt.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmrdsyl.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2drmyqajs.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnicyun.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmysvonr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2nzekeouw.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2wruuezlt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ctpcinea.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yulvgdnz.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2npfifxzm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhzutjy.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aiafahon.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrevvysd.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqosncgb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2nixvjbwm.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fpenxifj.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2chsfstdm.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2nhwwcwqu.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ujchfaoa.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrlryjy.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrvjzrb.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhxwrne.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ayuaabpf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgncykt.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdsduub.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2imngknfr.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tifmjjpj.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2aruvxsys.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2moggteha.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfzkrjf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcrajhd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbumgatq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2scvhlmju.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rtrwsvkk.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ojozepvo.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qaeyznxj.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2enrewftu.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qqshizuz.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2eiluvsvn.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjbphqg.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnpqgut.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yqugqxcx.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2nuboajxt.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxzrmzk.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ajswxela.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2founycgm.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2avqlehqf.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjfuequ.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxpacvp.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgaebka.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2szyqhjne.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2luyqdalw.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhryqph.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2qogpyncv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2qlpawnqe.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hznswkyw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2brhngcex.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwnhxel.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2czxiweyb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmiwgpnq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2anyhwity.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpkjxbfp.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2gpcyrtnh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2uftuxzvn.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2whhwcyzd.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnyhtdq.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2lozrddkl.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2xsbcomtl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2nieplaps.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2stfgwylk.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2zqembric.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2vtggzdjl.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxuwdry.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2unvqgqtj.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jniuveib.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bazsfpmv.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjtmzfh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvebzou.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2goqhbwho.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mirqwlqw.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2abeykabf.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkzipnj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rauxqpff.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2faxydusk.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdrjiks.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mehslzxh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqujvnk.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrjxgpd.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfknloet.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yzyysguh.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqfojas.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2sughskaz.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwdnqut.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgfukwf.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wvimbahc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgtfwgh.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdnizhi.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2vltjbgly.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2wesfzqrq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2knoelzeu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2admkkvnb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2giwwzubv.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2refrqhkw.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhwfosz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2exdttfmm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2lazgmsrk.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2uonytwuj.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vlybfqpy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrlyylp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2agjdrugn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2snsiwesf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wphacejm.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgevjsre.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvbrqkn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2soxfctxz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxrikkr.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pkcdswnc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2tmiouyks.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcpjdmj.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nimohbsm.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnstohn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbjeecg.html


<!-- 参考信息 -->