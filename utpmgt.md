代发 wailian999

JS:   s.split(/\r?\n/)
来源：http://dali.chenjidiqi.icu/Article/details/gthdmpazuc.html

TS:   s.split(/\r?\n/)
来源：http://dali.gotoacloud.top/Article/details/gtvinwtjae.html

Java: s.lines().toList()
来源：http://dali.yongpay.top/Article/details/gtnygcfshn.html

Go:   strings.Split(s, "\n")
来源：http://dali.gaohongyu789.top/Article/details/gtxtjpowps.html

Ruby: s.lines
来源：http://dali.9152youxi.cn/Article/details/gtlpecggmk.html

C#:   s.Split('\n')
来源：http://dali.smart0.xyz/Article/details/gtuhlolnpw.html

[E20] 判断字符串是否为空
来源：http://dali.ywan-chungtsiang.top/Article/details/gtboewnwfi.html

Py:   if not s:
来源：http://dali.guowangkeji.top/Article/details/gtsmhdfxgg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhiwuduotai.top/Article/details/gtwcgmduxk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.nanxuanxn.top/Article/details/gtihbrpupj.html

TS:   if (s === "") {}
来源：http://dali.ydzc1.top/Article/details/gtogxmyyzo.html

Java: if (s.isEmpty()) {}
来源：http://dali.aibaodan.cn/Article/details/gtqggwnlbc.html

Go:   if s == "" {}
来源：http://dali.yuxming.cn/Article/details/gtsnoocxup.html

Ruby: if s.empty?
来源：http://dali.chenjidiqi.icu/Article/details/gtzyafjjgj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zycfv.cn/Article/details/gthpccwfth.html

[E21] 超长截断加省略号
来源：http://dali.haohaochexian.top/Article/details/gtuhavkvmq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.pycfn.com/Article/details/gtctgubpjr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gtjlgsdeet.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fengsongda.top/Article/details/gthzqgkusa.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gtbntqmxsh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtktjhpoua.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.feifeiyinyue.top/Article/details/gtitzlssts.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtlduimrua.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gtqfdrefhc.html

[E22] 字节长度与字符长度
来源：http://dali.jianghu66.top/Article/details/gtzrepuhix.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gotoacloud.top/Article/details/gtwhwbppuz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gtpgdjjhln.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgufenzy.top/Article/details/gtqcqsqjgi.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhixingplan.top/Article/details/gtdadjegfo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.fzhhl.top/Article/details/gtxdyujctu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenzaomai.com/Article/details/gtcggqywuh.html

Ruby: s.bytesize;  s.length
来源：http://dali.sufxvd.cn/Article/details/gtdgrrlksy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jqgfzy.top/Article/details/gtnanccbhc.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteppkmbaf.html

F. 文件与目录
来源：http://dali.bjfxy.top/Article/details/gtlsnxcklk.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gteygkrtjq.html

[F01] 读取整个文件
来源：http://dali.wangdashe.top/Article/details/gtnwaizjpp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.dianchejie.cn/Article/details/gtyolqprdq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtxbbxhgrt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.bjfxy.top/Article/details/gtwwnsneau.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.daxiang520.top/Article/details/gtbjpsisdr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdwtfcocf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.smart0.xyz/Article/details/gtglgqajfh.html

Ruby: File.read("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtnalvgudu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gttrlznevt.html

[F02] 逐行读取文件
来源：http://dali.kuanghao11.cn/Article/details/gteffyrauq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gtrmpdtyuk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.andypj.xyz/Article/details/gtjyijkxbj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yanxiufei.cn/Article/details/gtubfibwyk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pengpengdd.cyou/Article/details/gthayttynb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.chenzaomai.com/Article/details/gtpdekclvt.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tanke756.top/Article/details/gtwznkypvc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.haohaochexian.top/Article/details/gtjodpoyzj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.kuanghao11.cn/Article/details/gtjefxxfsp.html

[F03] 写入文件（覆盖）
来源：http://dali.shanyushiyangtech.top/Article/details/gtygoicvyw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xziqi.cn/Article/details/gtbhqralhr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hammf.cn/Article/details/gtaupyyxri.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhongyouzk.top/Article/details/gtwetervre.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xinyue.icu/Article/details/gtfudnrxbd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yongpay.top/Article/details/gtnfphmazm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.fzhhl.top/Article/details/gtmseiepzu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.daria6918.cn/Article/details/gtingommmd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpgtmjppe.html

[F04] 追加写入文件
来源：http://dali.shuidangran.top/Article/details/gtmhntontg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sxryk.cn/Article/details/gtjvpnojxz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sysykeji.top/Article/details/gtngafvali.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yangfankeji.com/Article/details/gtqprohcnj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuxming.cn/Article/details/gtfpbktrtd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yueranfly.top/Article/details/gtidmigpih.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.mhx1999.top/Article/details/gtbrybsstd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sweek.top/Article/details/gtptquokyk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sufxvd.cn/Article/details/gtowevpdbp.html

[F05] 判断文件或目录是否存在
来源：http://dali.hongshengwenyu.top/Article/details/gtmdvwieag.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.iojbl.cn/Article/details/gtbonopwzj.html

PHP:  file_exists("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtjsmjsmzy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtvepqhvoy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtjjuccmjt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gtdqycofof.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhixingplan.top/Article/details/gtvlydcril.html

Ruby: File.exist?("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtxrfxglbu.html

C#:   File.Exists("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtbrvqxdiv.html

[F06] 删除文件
来源：http://dali.aizwys.cn/Article/details/gttefaudrb.html

Py:   os.remove("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtayerxdhg.html

PHP:  unlink("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtdqenhzyo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtjkaxcxlr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtrqtdhbse.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gtqtsngcdf.html

Go:   os.Remove("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtfcvcheph.html

Ruby: File.delete("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmjbfzgub.html

C#:   File.Delete("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtgvihazsc.html

[F07] 创建目录（含多级）
来源：http://dali.birdmap.top/Article/details/gtwgyucmqi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.smart0.xyz/Article/details/gtswsfcaen.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ydzc1.top/Article/details/gtuubgbmvi.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pycfn.com/Article/details/gtekzxagjq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxuanxn.top/Article/details/gtejuamoph.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ppjwa.cn/Article/details/gtgxzqerwb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cheryme.top/Article/details/gtritltyns.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hammf.cn/Article/details/gthhlycjvj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.haohaochexian.top/Article/details/gtesnexdoo.html

[F08] 遍历目录
来源：http://dali.jyoumei.cn/Article/details/gteftgipxk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.andypj.xyz/Article/details/gtrzmocgch.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.kuanghao11.cn/Article/details/gttfrwfhbb.html

JS:   fs.readdirSync("dir")
来源：http://dali.ppjwa.cn/Article/details/gtkzezehru.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyujytjdl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.svipenyu.cn/Article/details/gtndssmrbp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jiagoushi.top/Article/details/gtjkhkjgle.html

Ruby: Dir.children("dir")
来源：http://dali.hysaishi.cn/Article/details/gtkdjdnwti.html

C#:   Directory.GetFiles("dir")
来源：http://dali.birdmap.top/Article/details/gtwdvmeqdz.html

[F09] 获取文件大小
来源：http://dali.hongshengwenyu.top/Article/details/gtxzwyyifa.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrfbzdkrn.html

PHP:  filesize("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gttrbrbqcg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hywenlv.cn/Article/details/gtuolbopyg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuvogafys.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gtygumgubu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jqgfzy.top/Article/details/gtyjyegseq.html

Ruby: File.size("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtnalfdygr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.andypj.xyz/Article/details/gtsnxoeeiw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.iojbl.cn/Article/details/gtpnsotpql.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtmuqydhcy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtcgcvjklv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtbfxpwipd.html

TS:   path.extname("a.txt")
来源：http://dali.316326.xyz/Article/details/gtcjymyrec.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.havefunace.top/Article/details/gtmoxbumcm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gticvtecki.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtxdlfesms.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtqvkequpx.html

[F11] 复制与移动文件
来源：http://dali.xuanzx.com/Article/details/gtjryscnvd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtptqdklpt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cdnleiting.top/Article/details/gtucrxvetn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gtjdnzpjqz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gthkhsbozc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xinyue.icu/Article/details/gtambrrflo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zdqjudy.top/Article/details/gtyaaoiqsy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gtkwnbwybx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.chenjidiqi.icu/Article/details/gtespeiiig.html

[F12] CSV 读写
来源：http://dali.fzhhl.top/Article/details/gtcqemyjcb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zdqjudy.top/Article/details/gtyuuheqej.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.dianchejie.cn/Article/details/gtptetvjsz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cucudq.cn/Article/details/gtpjspsvbm.html

TS:   // 同上
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpooczofg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ppjwa.cn/Article/details/gtplilhdii.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ppjwa.cn/Article/details/gtzieilxfq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hywenlv.cn/Article/details/gtolclnhxp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.bjfxy.top/Article/details/gtpbzeadzu.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtmgjrzjoz.html

G. 面向对象
来源：http://dali.hnqzz.top/Article/details/gtjbnrhhio.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtchbajzrp.html

[G01] 定义类
来源：http://dali.ydzc1.top/Article/details/gtrinilpzw.html

Py:   class User: pass
来源：http://dali.xuanzx.com/Article/details/gtxttgigil.html

PHP:  class User {}
来源：http://dali.zdqjudy.top/Article/details/gtjhzojebk.html

JS:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gtckaamrba.html

TS:   class User { name: string = ""; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwpfscsca.html

Java: class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtghkwaykf.html

Go:   type User struct { Name string }
来源：http://dali.mhx1999.top/Article/details/gtdbgabkyi.html

Ruby: class User; end
来源：http://dali.fzhhl.top/Article/details/gtfmskopuo.html

C#:   class User {}
来源：http://dali.chenzaomai.com/Article/details/gtdryxegiu.html

[G02] 构造函数
来源：http://dali.yuanzhike.top/Article/details/gthtlekgjt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zycfv.cn/Article/details/gtvzealvxd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ivvv.top/Article/details/gtybvkjxnw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvwthnonw.html

TS:   constructor(public name: string) {}
来源：http://dali.xylfe.cn/Article/details/gtjoglahos.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkfzppknx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sysykeji.top/Article/details/gtcbdxmsno.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jlsjyb.cn/Article/details/gtfiqilnzr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtluclxnzj.html

[G03] 实例属性
来源：http://dali.xziqi.cn/Article/details/gtdjxvjpxp.html

Py:   self.name = "x"
来源：http://dali.svipenyu.cn/Article/details/gtdhbshwyk.html

PHP:  public string $name = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gtosmeqanl.html

JS:   this.name = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtpqehewej.html

TS:   name: string = "x";
来源：http://dali.redwolf501.top/Article/details/gtlzrlltzf.html

Java: private String name;
来源：http://dali.tianlin.xyz/Article/details/gtmkvpotap.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.aibaodan.cn/Article/details/gtyrayxyoo.html

Ruby: @name = "x"
来源：http://dali.jinqigufen.top/Article/details/gtjfyusjwp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.guannengcc.top/Article/details/gtqqbwmdak.html

[G04] 定义方法
来源：http://dali.guowangkeji.top/Article/details/gtvpudfohu.html

Py:   def greet(self): return self.name
来源：http://dali.yuxming.cn/Article/details/gtfjyormgo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gtgzxmhenx.html

JS:   greet() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrcbhlwrk.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gtvdkrueqh.html

Java: String greet() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtzictgrej.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gttcjqjmct.html

Ruby: def greet; @name; end
来源：http://dali.tian-w.cn/Article/details/gtmeujxfgt.html

C#:   public string Greet() => Name;
来源：http://dali.zhengqikj.top/Article/details/gtdinbdhgv.html

[G05] 继承
来源：http://dali.jinghuilouyu.cn/Article/details/gtfpnqkyyc.html

Py:   class Admin(User): pass
来源：http://dali.jianghu66.top/Article/details/gtlwlrrcmm.html

PHP:  class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gtvjyivijj.html

JS:   class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtskwraltp.html

TS:   class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gtverbkydt.html

Java: class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtidhbkktu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.vqdsnc.cn/Article/details/gtmitmgxbc.html

Ruby: class Admin < User; end
来源：http://dali.ehwqpu.com/Article/details/gthpibkbug.html

C#:   class Admin : User {}
来源：http://dali.aizwys.cn/Article/details/gtyqnbvgld.html

[G06] 重写方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwvfvrcox.html

Py:   def greet(self): return "admin"
来源：http://dali.andypj.xyz/Article/details/gtypnyrqut.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gtlcsgwroy.html

JS:   greet() { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtpmxbsyvf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gtozkxpmfc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtlwonzbpe.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.pengpengdd.cyou/Article/details/gtzsdxmiyp.html

Ruby: def greet; "admin"; end
来源：http://dali.yonumen.top/Article/details/gtexpttisw.html

C#:   public override string Greet() => "admin";
来源：http://dali.kuanghao11.cn/Article/details/gtvglqfluz.html

[G07] 调用父类方法
来源：http://dali.chenlongwang.top/Article/details/gtkfukgijc.html

Py:   super().greet()
来源：http://dali.zycfv.cn/Article/details/gtwgvgzkpd.html

PHP:  parent::greet();
来源：http://dali.gaohongyu789.top/Article/details/gtydbfvuvc.html

JS:   super.greet();
来源：http://dali.yj202588.top/Article/details/gthplnfolb.html

TS:   super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gtcrtxhttl.html

Java: super.greet();
来源：http://dali.sweek.top/Article/details/gtnrdzkitr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tianlin.xyz/Article/details/gtxnvekyev.html

Ruby: super
来源：http://dali.shangyingyoupin.top/Article/details/gtjhmgqkeg.html

C#:   base.Greet();
来源：http://dali.nwbrower.top/Article/details/gthnuedeuc.html

[G08] 静态方法与属性
来源：http://dali.sxryk.cn/Article/details/gtabadvvly.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuanzx.com/Article/details/gtazvtdpwt.html

PHP:  public static function f() {}
来源：http://dali.sxryk.cn/Article/details/gtjimhkfwb.html

JS:   static f() {}
来源：http://dali.jqgufenzy.top/Article/details/gtghqyqfiq.html

TS:   static f(): void {}
来源：http://dali.yueranfly.top/Article/details/gthycdreob.html

Java: static void f() {}
来源：http://dali.shuidangran.top/Article/details/gtzlvwvseq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zycfv.cn/Article/details/gtqodwvkpk.html

Ruby: def self.f; end
来源：http://dali.shangyingyoupin.top/Article/details/gtymvvnpdh.html

C#:   public static void F() {}
来源：http://dali.jiagoushi.top/Article/details/gtjxjomexo.html

[G09] 接口 / 抽象类
来源：http://dali.jlsjyb.cn/Article/details/gtusqtsdyk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gaohongyu789.top/Article/details/gtgchvagix.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jlsjyb.cn/Article/details/gtripnmaus.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nanxuanxn.top/Article/details/gthlsyoied.html

TS:   interface Shape { area(): number; }
来源：http://dali.jyoumei.cn/Article/details/gtshxbjrps.html

Java: interface Shape { double area(); }
来源：http://dali.sysykeji.top/Article/details/gtntllunsj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhixingplan.top/Article/details/gtzfszterd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.dianchejie.cn/Article/details/gtgatrdfai.html

C#:   interface IShape { double Area(); }
来源：http://dali.quarkkingdee.top/Article/details/gtxatqitpn.html

[G10] 访问控制
来源：http://dali.quarkkingdee.top/Article/details/gtcfheefcy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xinyue.icu/Article/details/gtftppbyoq.html

PHP:  public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gtapcvtewd.html

JS:   #private 字段；其余公开
来源：http://dali.ppjwa.cn/Article/details/gtucjjyerp.html

TS:   public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gtklgczfgg.html

Java: public / protected / private / 默认包级
来源：http://dali.zhiwuduotai.top/Article/details/gtacjgmplc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tianlin.xyz/Article/details/gtbnkgwgdy.html

Ruby: public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gtrtzabekl.html

C#:   public / protected / private / internal
来源：http://dali.jinqigfzy.top/Article/details/gtlpwuynko.html

[G11] getter / setter
来源：http://dali.iojbl.cn/Article/details/gtsheaermo.html

Py:   @property 与 @x.setter
来源：http://dali.shangyingyoupin.top/Article/details/gtkvkdvcye.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gtlnxmmect.html

JS:   get name() { return this._name; }
来源：http://dali.zhixingplan.top/Article/details/gtkdqhtovn.html

TS:   get name(): string { return this._name; }
来源：http://dali.ivvv.top/Article/details/gtbnmrriih.html

Java: public String getName() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gtvkekoxpw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gtbhbxiznp.html

Ruby: attr_accessor :name
来源：http://dali.fzhhl.top/Article/details/gtfpmtyngy.html

C#:   public string Name { get; set; }
来源：http://dali.andypj.xyz/Article/details/gtobxmcqkd.html

[G12] 对象转字符串
来源：http://dali.gaohongyu789.top/Article/details/gtebyslrcn.html

Py:   def __str__(self): return self.name
来源：http://dali.nanxuanxn.top/Article/details/gtdpbggwyz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtslhtusov.html

JS:   toString() { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gttwvknbek.html

TS:   toString(): string { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtuccikzlx.html

Java: @Override public String toString() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtlyhljaxx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gtufyrlpbn.html

Ruby: def to_s; @name; end
来源：http://dali.hnxiangtu.top/Article/details/gttjxcqfhf.html

C#:   public override string ToString() => Name;
来源：http://dali.c1oappe.top/Article/details/gtvkiatzel.html

[G13] 判断对象类型
来源：http://dali.shangyingyoupin.top/Article/details/gtawexrqhm.html

Py:   isinstance(u, User)
来源：http://dali.yuanzhike.top/Article/details/gtvrncmwcm.html

PHP:  $u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gtviqlcawn.html

JS:   u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gtarbvmmnp.html

TS:   u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gtrsqcnjpu.html

Java: u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtljjpushi.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.aibaodan.cn/Article/details/gtfnrhbhng.html

Ruby: u.is_a?(User)
来源：http://dali.svipenyu.cn/Article/details/gtuoipbxaz.html

C#:   u is User
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuleivtpi.html

[G14] 数据类 / record
来源：http://dali.guowangkeji.top/Article/details/gtkkpzqbzo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sysykeji.top/Article/details/gtggquoxzu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhoulong.xyz/Article/details/gtxkbrlugl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.bjfxy.top/Article/details/gtggmacobi.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj202588.top/Article/details/gteatiygyf.html

Java: record User(String name, int age) {}
来源：http://dali.jqgfzy.top/Article/details/gtfmddyvbw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sxryk.cn/Article/details/gtfijffftx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.iojbl.cn/Article/details/gtkzaehfox.html

C#:   record User(string Name, int Age);
来源：http://dali.chenzaomai.com/Article/details/gttvnxlvdp.html

[G15] 枚举
来源：http://dali.guowangkeji.top/Article/details/gtppoogovx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hysaishi.cn/Article/details/gtnmrsdiji.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jianghu66.top/Article/details/gtuifsunra.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.svipenyu.cn/Article/details/gtylmdjgev.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.kuanghao11.cn/Article/details/gtrsszrwvd.html

Java: enum Color { RED, GREEN }
来源：http://dali.ydzc1.top/Article/details/gttsjnpsah.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cashguo.top/Article/details/gtporwjixk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nanxuanxn.top/Article/details/gtselvcmrm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tianlin.xyz/Article/details/gtcfkilncb.html

[G16] 对象转数组 / 字典
来源：http://dali.ehwqpu.com/Article/details/gtnebyjmmn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hywenlv.cn/Article/details/gtsnkhaovq.html

PHP:  get_object_vars($obj);
来源：http://dali.ydzc1.top/Article/details/gtylkrhmto.html

JS:   Object.entries(obj)
来源：http://dali.jinqigufen.top/Article/details/gtehbgmqhp.html

TS:   Object.entries(obj)
来源：http://dali.mhx1999.top/Article/details/gtrfisnybq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhixingplan.top/Article/details/gtffwllswt.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shanyushiyangtech.top/Article/details/gtmstszntm.html

Ruby: obj.instance_variables
来源：http://dali.sweek.top/Article/details/gtssyzbqef.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xuetiantiany.cn/Article/details/gtrvxqgyhb.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gttucwaoyt.html

H. 异常与错误处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtowkvfexv.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtptnetchg.html

[H01] try / catch 基础
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvvjfmune.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jianghu66.top/Article/details/gtyswwczcs.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cqqwz.cn/Article/details/gtlyerduqo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmmkcfutn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gtukykorsz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhiwuduotai.top/Article/details/gtqmrlfhdr.html


<!-- 参考信息 -->