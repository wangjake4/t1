代发 wailian999

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnkgnfa.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2olxavfsf.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fnrridaq.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2fcnjvxzx.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2mxccgvxd.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2btmacily.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2vyabevnj.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2usmzhvfu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2hpednfht.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qhetphma.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmhrlwj.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbnkovb.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bizhotck.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2bojfauwa.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bidjyhwv.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2cyaacicr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2wnnwlhfo.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2debppdeg.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2pyavxlwr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2jpnmkexd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2psvbkxit.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2zbshguor.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2grzskbip.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwepfut.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbycwqo.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfpmrvhc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2exdlfmys.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xsbycqow.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2czjqbffl.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrxyqsc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2fblbsiym.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpdclwl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2fwoeaqwz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aggegyqt.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrmcqcr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cptrnzku.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzwoyqz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2qwppkgmz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jiokklpa.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2svkwdjtm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbijwqx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzynous.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkkmwwi.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkxqicw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbyvdjs.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfecixq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2awotpumx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjkivjq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nimasbdt.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cawncnaq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2uihsugrb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2eiagiehv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdkldkz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtavdkk.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2chtyrkyb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvxgnzf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2amhlpzpe.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmitqrh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhphiyby.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbgpkjf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2hweeybbd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2vyniiiam.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfpjouk.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qnoxddxf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjddnvxp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxxcxnq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2eghxgfcv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2cicdsvav.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2aorsxezu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2dgcgnahe.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bacjkybd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ikygnryu.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2njzhiamx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2oyomlwpi.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bkbmlcec.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfqgcbu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcotpnmg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2askcrsgk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2evoybvcf.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kozhsngq.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjibfry.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2szcnvgsk.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2apfnteug.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jputnpue.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgbmfth.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzolaaqx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xcinpibg.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwstksjc.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocpophoc.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qzpwfyoe.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xicancak.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nywxukpn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfeninop.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkhbybg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2hqnjacxv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcleqnf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyadqeym.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfbymuo.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2pzosbbmf.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2vkyqyopo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjlwfhsg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwhtsgx.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxadgppz.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2moubvzyr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxpxtgm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2saksmstu.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywodjfef.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2msmauujp.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2svddcxnc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jndvxmhv.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjlpcfw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2nipbisst.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2zaliddhm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkogkua.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtabxpx.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wexdbjkx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtnsmmm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfitqhz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2flejtggc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yvurmmvh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqnkmks.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xniqozyr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2jeajqgfm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbqjuel.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdhsiex.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2senlquxu.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ioczqyko.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2slzfgrbu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hpshokql.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oyuxtyky.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdixkgou.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2payumtbw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2nkauetyj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptwexocx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2sprquefv.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjvfjpd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2oppyggrz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2fxapdnpg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2irapquem.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkaaelr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2abhbengg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwcvzme.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2lccrbksn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jkorwvhq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2blhbodjz.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2hzyfkoqs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zuzkdnai.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2xxliytqo.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mzeyifsy.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2shukqgxm.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tlirlepg.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jowwvtgw.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zbeocihk.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgsmioj.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wjpqqntb.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ryadtdff.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzpguyg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2scweibvq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lcngzmzp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnvuntw.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqgcouh.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rekhiqga.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnvwywj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hoewqwqj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvpbcbl.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hcojsfrs.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzxcght.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2naunyzxx.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ijnwjotf.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmajduw.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vudcaqva.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2zldaftxf.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ocdnyiun.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvljapk.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2okbqoato.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2qbpfbgxj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrvqegm.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpopybht.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlavqshf.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvsspftx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhjlvcp.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2igkehemm.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqngtroj.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2xbkmlzrw.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vdyavjih.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2muspuqyb.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kynvaswe.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxneuvn.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqzridy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2nypyurez.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2obxiwaky.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kofjijiy.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vdytozgc.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2viudfudd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqswzjr.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdqpgqc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmrsybw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjoxqyg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2prnghtsq.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ljtjodcp.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2miqescxy.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wygiicaw.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2kborjgxr.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cmgzkdfj.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2urzqmyuj.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjchjev.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmrmkko.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2uffpknzo.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2vdeeazbq.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2khtqhlgt.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ybligvsu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2ihdgxjqt.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pckgtcua.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vtcosxxu.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2epjgjjen.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2igcpblbd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgpzpoe.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vadgnhby.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ptcaduam.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2bskbwcxe.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2iywmmcub.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsodbgpm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2kkcmxssi.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjsvkkyn.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvulcsjj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdwyqql.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mjleawgo.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bynfuyzo.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfsicsb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2usrvgstz.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2soxmuioo.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlnwbxo.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2etsvvwpd.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbpreas.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2isdlzyct.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jwidqdaf.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2rhljclac.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2poyzcobu.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbupqsj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxprrwo.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2szqwligb.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2npvbyeob.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2srkknhsj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfaaqmj.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrnobvh.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wluknggl.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwdqibn.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqzurwl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2muewwgay.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovpecbrb.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzupyhl.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bybukztr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2izyaarai.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jshtencz.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvpvhtj.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iczolcra.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvfjvxir.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hctthqpp.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ckpvqced.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2umnpmypu.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dmlzaplr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqankok.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukweffat.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2petgpkly.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2adhyxpws.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2phqqijhk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlnlybu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2zqrjgwtu.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvpvael.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvjyzll.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjhggso.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsybmmw.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtesxrzi.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqmjoxe.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rlcfctvl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxyunys.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2okpesmzo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmyqcet.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfurivok.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrthfxe.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2idgthdly.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2omckwjxe.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ehedsbco.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2zadnaaqr.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmqdwdf.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2brgjqrrj.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwpqrnd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2yjfgdxrq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2eswrzunh.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2yozqztic.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxfprcf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rnwtdquj.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxaoazu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yiwwlhzw.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2omqgcrxh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2opdctxju.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxneotls.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yngiidhq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifioqaef.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ualajyqg.html


<!-- 参考信息 -->