代发 wailian999

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gtwprsrwzn.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gteecssrcz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gtitevpdus.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.svipenyu.cn/Article/details/gtmqhsocme.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtjhmmlqxi.html

[E19] 多行文本按行拆分
来源：http://dali.jianghu66.top/Article/details/gtysatydpn.html

Py:   s.splitlines()
来源：http://dali.hywenlv.cn/Article/details/gtuloackuc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ehwqpu.com/Article/details/gtuucwzyfj.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxujgkodg.html

TS:   s.split(/\r?\n/)
来源：http://dali.chenlongwang.top/Article/details/gtcgechifz.html

Java: s.lines().toList()
来源：http://dali.zhoulong.xyz/Article/details/gtbijjlylz.html

Go:   strings.Split(s, "\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtchargjcc.html

Ruby: s.lines
来源：http://dali.yj202588.top/Article/details/gtfgsvvmig.html

C#:   s.Split('\n')
来源：http://dali.zdqjudy.top/Article/details/gtchqleoqk.html

[E20] 判断字符串是否为空
来源：http://dali.xuanzx.com/Article/details/gtyhllxyds.html

Py:   if not s:
来源：http://dali.yj20258888.top/Article/details/gtkjaukxva.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.redwolf501.top/Article/details/gtgqixhbos.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenlongwang.top/Article/details/gtkqouqezt.html

TS:   if (s === "") {}
来源：http://dali.iojbl.cn/Article/details/gtwkygtgxl.html

Java: if (s.isEmpty()) {}
来源：http://dali.yvedp.cn/Article/details/gtpyzwwssy.html

Go:   if s == "" {}
来源：http://dali.zycfv.cn/Article/details/gtlnbuwuok.html

Ruby: if s.empty?
来源：http://dali.mhx1999.top/Article/details/gtcznysgbk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.316326.xyz/Article/details/gtjlgqypdv.html

[E21] 超长截断加省略号
来源：http://dali.shanyushiyangtech.top/Article/details/gturjcpiwv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.smart0.xyz/Article/details/gtngxelrig.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gtzmbgrufc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gtamyxkqtt.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtvgzzmirx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtrfdrddsy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hnxiangtu.top/Article/details/gtiqbmqqdp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtwzktlnpi.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtqardvdne.html

[E22] 字节长度与字符长度
来源：http://dali.0kj1m.cn/Article/details/gtcpfquimr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.andypj.xyz/Article/details/gtwrxxysbc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gtcohgrvhw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenjidiqi.icu/Article/details/gttbypjgff.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gtppcmdqmf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gotoacloud.top/Article/details/gtmgbryvot.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gtiqwuaejp.html

Ruby: s.bytesize;  s.length
来源：http://dali.chenlongwang.top/Article/details/gtjtsryybf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gzhubu.top/Article/details/gtpigxqqoc.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtstrnxsji.html

F. 文件与目录
来源：http://dali.kuanghao11.cn/Article/details/gtkzwbfhih.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtxrolqsem.html

[F01] 读取整个文件
来源：http://dali.jinqigfzy.top/Article/details/gtbrnainur.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.iojbl.cn/Article/details/gtnhevwbff.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtyymsimdz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.andypj.xyz/Article/details/gthgqivplu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gtcbiiaubb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gtkwrxqajx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hywenlv.cn/Article/details/gtlbxeckos.html

Ruby: File.read("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtvqvzywzs.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtygyikvei.html

[F02] 逐行读取文件
来源：http://dali.ybcxt.top/Article/details/gtcnhsomch.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.smart0.xyz/Article/details/gtjbxxyyus.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gtnnonvwst.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hfpthk.cn/Article/details/gtfxwygrsq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sufxvd.cn/Article/details/gtzvvmssii.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj20258888.top/Article/details/gtxyptfjrg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ydzc1.top/Article/details/gtanfoombo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hongshengwenyu.top/Article/details/gtgfkcwqiy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hywenlv.cn/Article/details/gthhqlfxqy.html

[F03] 写入文件（覆盖）
来源：http://dali.yuanzhike.top/Article/details/gtdupjypah.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbexbyjmy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sweek.top/Article/details/gtuojttwgx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ivvv.top/Article/details/gtbmutszty.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.316326.xyz/Article/details/gtqbhdziot.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinqigfzy.top/Article/details/gtjdbwnxnv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ehwqpu.com/Article/details/gtvfegabtw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gaohongyu789.top/Article/details/gtyhllioah.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenzaomai.com/Article/details/gtdctbsncd.html

[F04] 追加写入文件
来源：http://dali.mhx1999.top/Article/details/gthburwpbp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gtkceirsec.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gogol.net.cn/Article/details/gtoxhbspap.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgufenzy.top/Article/details/gtuokduaob.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgfzy.top/Article/details/gtylpnzlfq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gogol.net.cn/Article/details/gtvffrnfqu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gtxozclkmi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.wangdashe.top/Article/details/gtfhjimtik.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jlsjyb.cn/Article/details/gtowqfqvyb.html

[F05] 判断文件或目录是否存在
来源：http://dali.cucudq.cn/Article/details/gtdrwzvpie.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.0kj1m.cn/Article/details/gtxljquerb.html

PHP:  file_exists("a.txt");
来源：http://dali.tanke756.top/Article/details/gtgrkbhbzn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gteegdcgrx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtzpwfvrtx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gtcmqduudh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthadzyebj.html

Ruby: File.exist?("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtpdugbbus.html

C#:   File.Exists("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtfdgsbgcd.html

[F06] 删除文件
来源：http://dali.jiagoushi.top/Article/details/gtpjunhzrd.html

Py:   os.remove("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtufolyrfn.html

PHP:  unlink("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrvrakisf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtslftjuvj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtmcqzqaih.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gtlgfpairc.html

Go:   os.Remove("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtihyxkkbb.html

Ruby: File.delete("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gthemqexol.html

C#:   File.Delete("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtatymhyja.html

[F07] 创建目录（含多级）
来源：http://dali.cucudq.cn/Article/details/gtwnbmnzmx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hongshengwenyu.top/Article/details/gtfqxlymgp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.aibaodan.cn/Article/details/gtbshikrta.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.iojbl.cn/Article/details/gtwufqpqee.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangshuangyany.cn/Article/details/gtrkeowpja.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.haohaochexian.top/Article/details/gtoougehwk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenjidiqi.icu/Article/details/gtzgdrtjxs.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.mhx1999.top/Article/details/gtydlvwfux.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinghuilouyu.cn/Article/details/gtlyoanfhs.html

[F08] 遍历目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwvktcqgn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jlsjyb.cn/Article/details/gtznylvaar.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zycfv.cn/Article/details/gtfpsnfsle.html

JS:   fs.readdirSync("dir")
来源：http://dali.fzhhl.top/Article/details/gtvnqxnqkm.html

TS:   fs.readdirSync("dir")
来源：http://dali.ybcxt.top/Article/details/gtfkdulzwm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cashguo.top/Article/details/gtcnjlrhkq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sweek.top/Article/details/gtrrkimhzp.html

Ruby: Dir.children("dir")
来源：http://dali.yj202588.top/Article/details/gtovawzdun.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hnqzz.top/Article/details/gtsslnozac.html

[F09] 获取文件大小
来源：http://dali.jianghu66.top/Article/details/gtfxhsofhu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtmxejacsz.html

PHP:  filesize("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtlgsmtazf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.daxiang520.top/Article/details/gtptvykuyy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenjidiqi.icu/Article/details/gtjgytmvus.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gthhklvzio.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jianghu66.top/Article/details/gtvqgqffgq.html

Ruby: File.size("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtyvxxuejf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jianghu66.top/Article/details/gtskbxfiig.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gogol.net.cn/Article/details/gtftnxswrl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtmtvrfivf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtnqflcpvi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtpetcdekc.html

TS:   path.extname("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtbqubiuok.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinqigfzy.top/Article/details/gtmrgunlyl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtcmpmbili.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtfhbwjcxh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtlpyhcvgr.html

[F11] 复制与移动文件
来源：http://dali.hammf.cn/Article/details/gtkltkzetw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gtfdwnbzqz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtvyxvttsy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gtxznjfwxj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtwomzaqie.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ehwqpu.com/Article/details/gtvzykbyze.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hnxiangtu.top/Article/details/gtvaoqhrxw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gttieqthlp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jyoumei.cn/Article/details/gthgkenyge.html

[F12] CSV 读写
来源：http://dali.nanxuanxn.top/Article/details/gtuwmqgprg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.dashuyun.cn/Article/details/gtrcqyyxfi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.wangdashe.top/Article/details/gtbokyirat.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenzaomai.com/Article/details/gtvzxgxquo.html

TS:   // 同上
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxachnasn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hnqzz.top/Article/details/gtsgpwbgbd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinqigufen.top/Article/details/gtghygcnqt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jianghu66.top/Article/details/gtxwojsieb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hnxiangtu.top/Article/details/gtxrdaorzx.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtrounbeag.html

G. 面向对象
来源：http://dali.jyoumei.cn/Article/details/gtjgcovmro.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtgxhrxknw.html

[G01] 定义类
来源：http://dali.chenlongwang.top/Article/details/gtghzdfaop.html

Py:   class User: pass
来源：http://dali.snrcjt.cn/Article/details/gtxqbickmx.html

PHP:  class User {}
来源：http://dali.dianchejie.cn/Article/details/gtcchscmpq.html

JS:   class User {}
来源：http://dali.jinqigufen.top/Article/details/gtnxmavvbp.html

TS:   class User { name: string = ""; }
来源：http://dali.wangshuangyany.cn/Article/details/gtkcgyltxm.html

Java: class User {}
来源：http://dali.wangdashe.top/Article/details/gtfigmqvoi.html

Go:   type User struct { Name string }
来源：http://dali.sysykeji.top/Article/details/gtwqbmccxq.html

Ruby: class User; end
来源：http://dali.yj20258888.top/Article/details/gtornmputi.html

C#:   class User {}
来源：http://dali.mhx1999.top/Article/details/gtvhcknuct.html

[G02] 构造函数
来源：http://dali.ivvv.top/Article/details/gtyzxbejoq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.guowangkeji.top/Article/details/gtppxslian.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.dianchejie.cn/Article/details/gtuugvxmad.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yueranfly.top/Article/details/gthzimizdj.html

TS:   constructor(public name: string) {}
来源：http://dali.ppjwa.cn/Article/details/gtfhxqbxmd.html

Java: User(String name) { this.name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzkfeiflb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.guannengcc.top/Article/details/gtwhjhwity.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ehwqpu.com/Article/details/gtzsspcvgq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhixingplan.top/Article/details/gtvpzdcuqx.html

[G03] 实例属性
来源：http://dali.smart0.xyz/Article/details/gtvmdzrhag.html

Py:   self.name = "x"
来源：http://dali.shangyingyoupin.top/Article/details/gtfenatmia.html

PHP:  public string $name = "x";
来源：http://dali.c1oappe.top/Article/details/gtzvpwubvs.html

JS:   this.name = "x";
来源：http://dali.jyoumei.cn/Article/details/gtkyjrlxld.html

TS:   name: string = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtqlvwbfjf.html

Java: private String name;
来源：http://dali.nwbrower.top/Article/details/gtrpcspmsb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.redwolf501.top/Article/details/gtormcpjbx.html

Ruby: @name = "x"
来源：http://dali.316326.xyz/Article/details/gtyceskupf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hywenlv.cn/Article/details/gtbmxbzerq.html

[G04] 定义方法
来源：http://dali.cheryme.top/Article/details/gtpvipkbas.html

Py:   def greet(self): return self.name
来源：http://dali.9152youxi.cn/Article/details/gtsdonfsvw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gtynoymsrw.html

JS:   greet() { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gtzrddlnco.html

TS:   greet(): string { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gtvvzzyzrt.html

Java: String greet() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtusayxahn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gtmtvghrzx.html

Ruby: def greet; @name; end
来源：http://dali.tianlin.xyz/Article/details/gtaklnqnsw.html

C#:   public string Greet() => Name;
来源：http://dali.hammf.cn/Article/details/gtrqtkrcia.html

[G05] 继承
来源：http://dali.hongshengwenyu.top/Article/details/gtcceyvfxp.html

Py:   class Admin(User): pass
来源：http://dali.chenlongwang.top/Article/details/gtmvrqkbiw.html

PHP:  class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxomalhoa.html

JS:   class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtapaxpdpe.html

TS:   class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gtimenptwl.html

Java: class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtcvnxjzdj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.pengpengdd.cyou/Article/details/gtbxjgbchf.html

Ruby: class Admin < User; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyamwhriq.html

C#:   class Admin : User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtsxtuljsd.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gtveqilwga.html

Py:   def greet(self): return "admin"
来源：http://dali.wangdashe.top/Article/details/gtovfgmlkj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gtagajiqfk.html

JS:   greet() { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gtrggtfelv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gtfodpswfv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sweek.top/Article/details/gtrhsayvad.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.andypj.xyz/Article/details/gtxyxftobl.html

Ruby: def greet; "admin"; end
来源：http://dali.tanke756.top/Article/details/gthxgjnqgs.html

C#:   public override string Greet() => "admin";
来源：http://dali.pycfn.com/Article/details/gtnexyeixl.html

[G07] 调用父类方法
来源：http://dali.jiagoushi.top/Article/details/gtfukamaxf.html

Py:   super().greet()
来源：http://dali.daria6918.cn/Article/details/gtldcnfjhc.html

PHP:  parent::greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbsoidiuo.html

JS:   super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gtjfghkrop.html

TS:   super.greet();
来源：http://dali.shuidangran.top/Article/details/gtmgtfsajk.html

Java: super.greet();
来源：http://dali.hfpthk.cn/Article/details/gtognjyfmg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tian-w.cn/Article/details/gtaxmkqcbk.html

Ruby: super
来源：http://dali.wangshuangyany.cn/Article/details/gtbzcrmmfy.html

C#:   base.Greet();
来源：http://dali.sysykeji.top/Article/details/gtijyoaabz.html

[G08] 静态方法与属性
来源：http://dali.xylfe.cn/Article/details/gtqrllccse.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.havefunace.top/Article/details/gtmkckcqmt.html

PHP:  public static function f() {}
来源：http://dali.jianghu66.top/Article/details/gtijnpvxwi.html

JS:   static f() {}
来源：http://dali.xinyue.icu/Article/details/gtqrgsgypa.html

TS:   static f(): void {}
来源：http://dali.hammf.cn/Article/details/gtxgshugzk.html

Java: static void f() {}
来源：http://dali.jinqigufen.top/Article/details/gtynyahmoj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenjidiqi.icu/Article/details/gtpfojjjdn.html

Ruby: def self.f; end
来源：http://dali.ybcxt.top/Article/details/gtfvljfdka.html

C#:   public static void F() {}
来源：http://dali.quarkkingdee.top/Article/details/gtuhrmnbui.html

[G09] 接口 / 抽象类
来源：http://dali.sufxvd.cn/Article/details/gtduwaspsv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yonumen.top/Article/details/gtryfvghfm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ehwqpu.com/Article/details/gtwdvchnwg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.daxiang520.top/Article/details/gtwrzougil.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhixingplan.top/Article/details/gtdvasgvbn.html

Java: interface Shape { double area(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtimqkzfal.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ivvv.top/Article/details/gtptjyhiaj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.c1oappe.top/Article/details/gteaeqygex.html

C#:   interface IShape { double Area(); }
来源：http://dali.havefunace.top/Article/details/gtnfmcwozw.html

[G10] 访问控制
来源：http://dali.cheryme.top/Article/details/gtmmmqxega.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shangyingyoupin.top/Article/details/gtzqfwssqw.html

PHP:  public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gtvydwdrhn.html

JS:   #private 字段；其余公开
来源：http://dali.0kj1m.cn/Article/details/gtuqmwapeg.html

TS:   public / protected / private
来源：http://dali.guowangkeji.top/Article/details/gtzwtwhsax.html

Java: public / protected / private / 默认包级
来源：http://dali.jianghu66.top/Article/details/gtevpkgkaj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.andypj.xyz/Article/details/gtguwfwred.html

Ruby: public / protected / private
来源：http://dali.mhx1999.top/Article/details/gtgjapnqzu.html

C#:   public / protected / private / internal
来源：http://dali.shangyingyoupin.top/Article/details/gtlowcanhf.html

[G11] getter / setter
来源：http://dali.yanxiufei.cn/Article/details/gtduvbuwef.html

Py:   @property 与 @x.setter
来源：http://dali.jyoumei.cn/Article/details/gtkfrlnvwp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gtzugppedq.html

JS:   get name() { return this._name; }
来源：http://dali.cqqwz.cn/Article/details/gtfpgdtppo.html

TS:   get name(): string { return this._name; }
来源：http://dali.yvedp.cn/Article/details/gtivnfrhad.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gtaxmhacqc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gtactbjwqz.html

Ruby: attr_accessor :name
来源：http://dali.ydzc1.top/Article/details/gtdivebheq.html

C#:   public string Name { get; set; }
来源：http://dali.jiagoushi.top/Article/details/gtujngabhy.html

[G12] 对象转字符串
来源：http://dali.cucudq.cn/Article/details/gtfixocayg.html

Py:   def __str__(self): return self.name
来源：http://dali.shangyingyoupin.top/Article/details/gtexpjdbkp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gttwxueipd.html

JS:   toString() { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtztlgugxx.html

TS:   toString(): string { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtyuwehcdz.html

Java: @Override public String toString() { return name; }
来源：http://dali.hammf.cn/Article/details/gtyvhubvvz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.feifeiyinyue.top/Article/details/gtfsfmloty.html

Ruby: def to_s; @name; end
来源：http://dali.aibaodan.cn/Article/details/gtylecxxzn.html

C#:   public override string ToString() => Name;
来源：http://dali.yj202588.top/Article/details/gttoekkwgl.html

[G13] 判断对象类型
来源：http://dali.andypj.xyz/Article/details/gtmzmnyjwz.html

Py:   isinstance(u, User)
来源：http://dali.aizwys.cn/Article/details/gtxfllvxlw.html

PHP:  $u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gtwmjvdgav.html

JS:   u instanceof User
来源：http://dali.hnqzz.top/Article/details/gthultzbgh.html

TS:   u instanceof User
来源：http://dali.nwbrower.top/Article/details/gtvlwoxkqj.html

Java: u instanceof User
来源：http://dali.yj202588.top/Article/details/gttaxkpwmi.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hfpthk.cn/Article/details/gtbyekdtzs.html

Ruby: u.is_a?(User)
来源：http://dali.cdnleiting.top/Article/details/gtbuyljcrj.html

C#:   u is User
来源：http://dali.yuanzhike.top/Article/details/gtmrdmcamt.html

[G14] 数据类 / record
来源：http://dali.hnxiangtu.top/Article/details/gthqobzlcv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yongpay.top/Article/details/gtawolpomu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.bjfxy.top/Article/details/gtnkvahbhi.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.pengpengdd.cyou/Article/details/gtympxvogv.html

TS:   type User = { name: string; age: number };
来源：http://dali.yvedp.cn/Article/details/gtcgjxovhr.html

Java: record User(String name, int age) {}
来源：http://dali.cdnleiting.top/Article/details/gtwbjozfsw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sxryk.cn/Article/details/gtvaukbwsx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinghuilouyu.cn/Article/details/gthcxqfytb.html

C#:   record User(string Name, int Age);
来源：http://dali.svipenyu.cn/Article/details/gtkhtitovx.html

[G15] 枚举
来源：http://dali.cdnleiting.top/Article/details/gtfsapvway.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.redwolf501.top/Article/details/gtlvvoksnr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.birdmap.top/Article/details/gtaxtzmqij.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gotoacloud.top/Article/details/gtwvztkqeb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hammf.cn/Article/details/gtvwcvpvcc.html

Java: enum Color { RED, GREEN }
来源：http://dali.dianchejie.cn/Article/details/gttaczgblx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhoulong.xyz/Article/details/gtakabmobg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.kuanghao11.cn/Article/details/gtaftvqtoz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tianlin.xyz/Article/details/gtwffrqkip.html

[G16] 对象转数组 / 字典
来源：http://dali.dianchejie.cn/Article/details/gtarwpgofp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.haohaochexian.top/Article/details/gtsyqkhndl.html

PHP:  get_object_vars($obj);
来源：http://dali.yongpay.top/Article/details/gtrxxpxegn.html

JS:   Object.entries(obj)
来源：http://dali.smart0.xyz/Article/details/gtdgswdnya.html

TS:   Object.entries(obj)
来源：http://dali.chenzaomai.com/Article/details/gtnhuuwbsn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.quarkkingdee.top/Article/details/gtvvqylezq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jqgufenzy.top/Article/details/gtckfozjin.html

Ruby: obj.instance_variables
来源：http://dali.hongshengwenyu.top/Article/details/gthjaxydrr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fzhhl.top/Article/details/gtswmqvgxx.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtfaneeqik.html


<!-- 参考信息 -->