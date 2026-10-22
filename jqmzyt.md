代发 wailian999

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shzxlz.cn/Article/details/gtpswuggpj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gtksljijht.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtzemduygu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtjiyexvhq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gtsapqqcqv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxaeaqwfq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gtaksdvfzf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.fengsongda.top/Article/details/gtwyczomxp.html

[E22] 字节长度与字符长度
来源：http://dali.xylfe.cn/Article/details/gtlwrayaze.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinqigufen.top/Article/details/gtbxlucejx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pycfn.com/Article/details/gtpgbdomvm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gtomomueno.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.bjfxy.top/Article/details/gtyddmgsty.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.nanxuanxn.top/Article/details/gthhozedjw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.andypj.xyz/Article/details/gtckzbbkrd.html

Ruby: s.bytesize;  s.length
来源：http://dali.aizwys.cn/Article/details/gtvloczrph.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.pycfn.com/Article/details/gtyxzwvzfn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtkyvuocay.html

F. 文件与目录
来源：http://dali.hnqzz.top/Article/details/gttzfrtwbv.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuaeddpdm.html

[F01] 读取整个文件
来源：http://dali.tanke756.top/Article/details/gtqkfgatyu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yueranfly.top/Article/details/gtrethhkga.html

PHP:  file_get_contents("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtnygzcitt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gaohongyu789.top/Article/details/gtgfjydzgp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.guannengcc.top/Article/details/gtiunptehk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gtbwhtzhan.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.snrcjt.cn/Article/details/gtjzdzqhvf.html

Ruby: File.read("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtbysvrbtv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtrktvpmtg.html

[F02] 逐行读取文件
来源：http://dali.yuanzhike.top/Article/details/gtyirtigph.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.9152youxi.cn/Article/details/gtphyuwvnc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.tanke756.top/Article/details/gtcycozyil.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jianghu66.top/Article/details/gtayrlpfep.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cheryme.top/Article/details/gtqauoakuh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrbtmtcmk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.daxiang520.top/Article/details/gtzwsgiuis.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shangyingyoupin.top/Article/details/gtazooavkm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.chenlongwang.top/Article/details/gtbjyeepkq.html

[F03] 写入文件（覆盖）
来源：http://dali.ivvv.top/Article/details/gtvmdmmgno.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ydzc1.top/Article/details/gtplksyjdp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hfpthk.cn/Article/details/gtlydsidon.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gtflpwjqyf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gtoektgtby.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.fengsongda.top/Article/details/gtagmntdbq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jlsjyb.cn/Article/details/gtntaocmwe.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.fengsongda.top/Article/details/gtfxyotcnx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.birdmap.top/Article/details/gtmwrwmikx.html

[F04] 追加写入文件
来源：http://dali.gogol.net.cn/Article/details/gtlevydkhu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.316326.xyz/Article/details/gtfmifoxeb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jlsjyb.cn/Article/details/gtrwiaryho.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuxming.cn/Article/details/gtktsvudno.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hammf.cn/Article/details/gtxdpspand.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nwbrower.top/Article/details/gtgtrggjpk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhengqikj.top/Article/details/gtlebyvhwn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gtybaakprd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtudwyotwq.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhongyouzk.top/Article/details/gtuywhyuvj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sysykeji.top/Article/details/gtxvwncsos.html

PHP:  file_exists("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtlhcujvcq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtpwmdylfs.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtjvxwaimj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gtcsegqdtr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhixingplan.top/Article/details/gtoqjomazv.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtdeirtqts.html

C#:   File.Exists("a.txt")
来源：http://dali.jianghu66.top/Article/details/gttzgjdynh.html

[F06] 删除文件
来源：http://dali.tian-w.cn/Article/details/gtghrkzwpf.html

Py:   os.remove("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtlkhxvmsn.html

PHP:  unlink("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtqpjdfyhb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtpcfpanif.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtdsvjaomj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gtysimwjqa.html

Go:   os.Remove("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtdroezdjj.html

Ruby: File.delete("a.txt")
来源：http://dali.pycfn.com/Article/details/gtuaqftxxa.html

C#:   File.Delete("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtblpzwesk.html

[F07] 创建目录（含多级）
来源：http://dali.chenlongwang.top/Article/details/gtrahypsxw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.smart0.xyz/Article/details/gtlcsqtnvy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.haohaochexian.top/Article/details/gtyoaanovi.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aizwys.cn/Article/details/gtzgubobod.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daria6918.cn/Article/details/gtmbhiifzl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cdnleiting.top/Article/details/gtsmmgrmjt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhixingplan.top/Article/details/gtgddeuxkg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.c1oappe.top/Article/details/gthaqpjlft.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jianghu66.top/Article/details/gtmsanblhv.html

[F08] 遍历目录
来源：http://dali.iojbl.cn/Article/details/gtytxdvqdj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.9152youxi.cn/Article/details/gtpnweojzx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yonumen.top/Article/details/gtugcxkfht.html

JS:   fs.readdirSync("dir")
来源：http://dali.gotoacloud.top/Article/details/gtaqmrioll.html

TS:   fs.readdirSync("dir")
来源：http://dali.pycfn.com/Article/details/gtuqsbiery.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ivvv.top/Article/details/gtmqtpdmnm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cashguo.top/Article/details/gtflyutgxy.html

Ruby: Dir.children("dir")
来源：http://dali.xylfe.cn/Article/details/gtmdmytwgj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.wangdashe.top/Article/details/gtudgbdeaj.html

[F09] 获取文件大小
来源：http://dali.cheryme.top/Article/details/gtjjaxthif.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtiliplfjm.html

PHP:  filesize("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtioridvad.html

JS:   fs.statSync("a.txt").size
来源：http://dali.birdmap.top/Article/details/gtucdnkyii.html

TS:   fs.statSync("a.txt").size
来源：http://dali.snrcjt.cn/Article/details/gtlmndxkgg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gtkqfsqezu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.haohaochexian.top/Article/details/gtyyvqngfj.html

Ruby: File.size("a.txt")
来源：http://dali.yongpay.top/Article/details/gtimocasok.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ydzc1.top/Article/details/gtokuefkzf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nwbrower.top/Article/details/gtrhsqywcw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtlyyxfaeq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hfpthk.cn/Article/details/gttqctybej.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtvdketmuz.html

TS:   path.extname("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtbyvxxupo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.vqdsnc.cn/Article/details/gtxbreypmm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtropsnmpm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gteybtiman.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtqpdtjmuf.html

[F11] 复制与移动文件
来源：http://dali.shzxlz.cn/Article/details/gtbuztbeit.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gthyqxrvzt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shzxlz.cn/Article/details/gtgvwqlkds.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gtzhmrbvdz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gtjvmrszba.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.dianchejie.cn/Article/details/gthzvimiix.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tianlin.xyz/Article/details/gthuaxpqva.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gtmkamnfsh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gaohongyu789.top/Article/details/gtbspznalr.html

[F12] CSV 读写
来源：http://dali.nanxuanxn.top/Article/details/gtfwroceic.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shzxlz.cn/Article/details/gtiwonzvdd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cdnleiting.top/Article/details/gtuhsykxil.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yuxming.cn/Article/details/gtstrljprk.html

TS:   // 同上
来源：http://dali.haohaochexian.top/Article/details/gtxijqgise.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yj20258888.top/Article/details/gtpemiufci.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yanxiufei.cn/Article/details/gtyfvlvedh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthhbhcxqz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj202588.top/Article/details/gtreuwuayt.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtibfqmnib.html

G. 面向对象
来源：http://dali.meibo888.top/Article/details/gtdicdilxq.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtdnxgykqh.html

[G01] 定义类
来源：http://dali.yvedp.cn/Article/details/gtjqbxwgvp.html

Py:   class User: pass
来源：http://dali.yj20258.top/Article/details/gtfjnmqbzi.html

PHP:  class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqkgsndui.html

JS:   class User {}
来源：http://dali.bjfxy.top/Article/details/gtmsfjhrjb.html

TS:   class User { name: string = ""; }
来源：http://dali.yanxiufei.cn/Article/details/gtbihhcjzm.html

Java: class User {}
来源：http://dali.yj202588.top/Article/details/gtotktdtzk.html

Go:   type User struct { Name string }
来源：http://dali.gogol.net.cn/Article/details/gtzbibcexp.html

Ruby: class User; end
来源：http://dali.zhongyouzk.top/Article/details/gtkfzrlokx.html

C#:   class User {}
来源：http://dali.jyoumei.cn/Article/details/gtblptzywx.html

[G02] 构造函数
来源：http://dali.bjfxy.top/Article/details/gtkninqkhq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.0kj1m.cn/Article/details/gtyfewxaye.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cucudq.cn/Article/details/gtimgxxjln.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gtbterphhp.html

TS:   constructor(public name: string) {}
来源：http://dali.iojbl.cn/Article/details/gtgdchajgr.html

Java: User(String name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gtvsxceypa.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hfpthk.cn/Article/details/gtaymdyhsf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hnqzz.top/Article/details/gtqxdtgpmx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yonumen.top/Article/details/gtnyheyile.html

[G03] 实例属性
来源：http://dali.zhoulong.xyz/Article/details/gtzfdkfdaw.html

Py:   self.name = "x"
来源：http://dali.quarkkingdee.top/Article/details/gtxcajjysb.html

PHP:  public string $name = "x";
来源：http://dali.gzhubu.top/Article/details/gtppvqditq.html

JS:   this.name = "x";
来源：http://dali.c1oappe.top/Article/details/gtozzbhkyk.html

TS:   name: string = "x";
来源：http://dali.yangfankeji.com/Article/details/gtktudbxxj.html

Java: private String name;
来源：http://dali.zhengqikj.top/Article/details/gtszwyukiy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shanyushiyangkeji.top/Article/details/gturaatpgd.html

Ruby: @name = "x"
来源：http://dali.ybcxt.top/Article/details/gtsxpoojhd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yuanzhike.top/Article/details/gtgqbwxvqn.html

[G04] 定义方法
来源：http://dali.yj202588.top/Article/details/gtazmmdthn.html

Py:   def greet(self): return self.name
来源：http://dali.xuetiantiany.cn/Article/details/gtibpokrsb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gtockpxazj.html

JS:   greet() { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtvydzcgtv.html

TS:   greet(): string { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtixwxcrxv.html

Java: String greet() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnziyqauf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtblkenjyn.html

Ruby: def greet; @name; end
来源：http://dali.xuanzx.com/Article/details/gtvlugzczl.html

C#:   public string Greet() => Name;
来源：http://dali.zhiwuduotai.top/Article/details/gtgqekowlv.html

[G05] 继承
来源：http://dali.zdqjudy.top/Article/details/gtsitjnqxo.html

Py:   class Admin(User): pass
来源：http://dali.yueranfly.top/Article/details/gtdhzakbhr.html

PHP:  class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtdopzrtif.html

JS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtiwhjgyeb.html

TS:   class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gtjlqyhplh.html

Java: class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gtlevuvvsp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hnxiangtu.top/Article/details/gtpcrfiydr.html

Ruby: class Admin < User; end
来源：http://dali.hongshengwenyu.top/Article/details/gtvcvaysyz.html

C#:   class Admin : User {}
来源：http://dali.ydzc1.top/Article/details/gtlaoxooqy.html

[G06] 重写方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnxmksoid.html

Py:   def greet(self): return "admin"
来源：http://dali.ydzc1.top/Article/details/gtknlvsmpd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gthhbmouam.html

JS:   greet() { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gtefkxmwgo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gtkjynbuso.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gtlzctpusc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.snrcjt.cn/Article/details/gtnjfzogeq.html

Ruby: def greet; "admin"; end
来源：http://dali.birdmap.top/Article/details/gtnwnkzoxj.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhongyouzk.top/Article/details/gtabwhkrjv.html

[G07] 调用父类方法
来源：http://dali.hammf.cn/Article/details/gtgxhshrhl.html

Py:   super().greet()
来源：http://dali.cashguo.top/Article/details/gttwkyxggd.html

PHP:  parent::greet();
来源：http://dali.vqdsnc.cn/Article/details/gtvnddjcyq.html

JS:   super.greet();
来源：http://dali.andypj.xyz/Article/details/gtkojrocjl.html

TS:   super.greet();
来源：http://dali.jyoumei.cn/Article/details/gteskzknqr.html

Java: super.greet();
来源：http://dali.jianghu66.top/Article/details/gtrwhlrddl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.feifeiyinyue.top/Article/details/gtqcpoklrg.html

Ruby: super
来源：http://dali.xuetiantiany.cn/Article/details/gtbysxahus.html

C#:   base.Greet();
来源：http://dali.vqdsnc.cn/Article/details/gtiubogmrm.html

[G08] 静态方法与属性
来源：http://dali.yvedp.cn/Article/details/gtvpbnrsnl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hywenlv.cn/Article/details/gtnopfwwjr.html

PHP:  public static function f() {}
来源：http://dali.zycfv.cn/Article/details/gtrxnzzkxa.html

JS:   static f() {}
来源：http://dali.hfpthk.cn/Article/details/gtkxjvwcza.html

TS:   static f(): void {}
来源：http://dali.cucudq.cn/Article/details/gtjfzegxdt.html

Java: static void f() {}
来源：http://dali.yj20258888.top/Article/details/gtamqkefat.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuivrtvfy.html

Ruby: def self.f; end
来源：http://dali.pengpengdd.cyou/Article/details/gtgqijaylq.html

C#:   public static void F() {}
来源：http://dali.hywenlv.cn/Article/details/gttejyqtrl.html

[G09] 接口 / 抽象类
来源：http://dali.nanxinkj.top/Article/details/gtuxeibnnv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ydzc1.top/Article/details/gtzcdsfjxw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zdqjudy.top/Article/details/gtfncjlejy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.c1oappe.top/Article/details/gtviprcztj.html

TS:   interface Shape { area(): number; }
来源：http://dali.smart0.xyz/Article/details/gtkvrjwmhv.html

Java: interface Shape { double area(); }
来源：http://dali.havefunace.top/Article/details/gtfoshyscj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.tianlin.xyz/Article/details/gtescpmesm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shzxlz.cn/Article/details/gtcxsqjdrb.html

C#:   interface IShape { double Area(); }
来源：http://dali.ppjwa.cn/Article/details/gtsypmikyt.html

[G10] 访问控制
来源：http://dali.ivvv.top/Article/details/gtccbeqngo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ehwqpu.com/Article/details/gtxoxtrobu.html

PHP:  public / protected / private
来源：http://dali.yuxming.cn/Article/details/gtmuckibth.html

JS:   #private 字段；其余公开
来源：http://dali.xziqi.cn/Article/details/gtnztskkiz.html

TS:   public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gtxzprnfkn.html

Java: public / protected / private / 默认包级
来源：http://dali.chenzaomai.com/Article/details/gtgimxycqh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shzxlz.cn/Article/details/gtkybikyjc.html

Ruby: public / protected / private
来源：http://dali.iojbl.cn/Article/details/gttfsmgwft.html

C#:   public / protected / private / internal
来源：http://dali.xinyue.icu/Article/details/gtsomqfumb.html

[G11] getter / setter
来源：http://dali.sysykeji.top/Article/details/gtokosrxel.html

Py:   @property 与 @x.setter
来源：http://dali.0kj1m.cn/Article/details/gtrfgddpae.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gtunslgzba.html

JS:   get name() { return this._name; }
来源：http://dali.gaohongyu789.top/Article/details/gtoscpemzf.html

TS:   get name(): string { return this._name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtckqxzkem.html

Java: public String getName() { return name; }
来源：http://dali.aizwys.cn/Article/details/gtgzehwwlj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gtdpkqbgmg.html

Ruby: attr_accessor :name
来源：http://dali.zycfv.cn/Article/details/gtfwulfghp.html

C#:   public string Name { get; set; }
来源：http://dali.kuanghao11.cn/Article/details/gtzfvqbsfu.html

[G12] 对象转字符串
来源：http://dali.sxryk.cn/Article/details/gtrmnxufes.html

Py:   def __str__(self): return self.name
来源：http://dali.316326.xyz/Article/details/gtfipquyfv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gtywehnaxc.html

JS:   toString() { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtzqajaxbk.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gtkeqvmyaj.html

Java: @Override public String toString() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gtsghckpfy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gtlvyrhdlb.html

Ruby: def to_s; @name; end
来源：http://dali.xylfe.cn/Article/details/gteeepessz.html

C#:   public override string ToString() => Name;
来源：http://dali.meibo888.top/Article/details/gtqnfiobyu.html

[G13] 判断对象类型
来源：http://dali.chenlongwang.top/Article/details/gttptogmcl.html

Py:   isinstance(u, User)
来源：http://dali.jiagoushi.top/Article/details/gtfximkbzs.html

PHP:  $u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtuyxnucme.html

JS:   u instanceof User
来源：http://dali.guannengcc.top/Article/details/gtacqvngnb.html

TS:   u instanceof User
来源：http://dali.cashguo.top/Article/details/gtkgzlytay.html

Java: u instanceof User
来源：http://dali.xuanzx.com/Article/details/gtmrbbsofx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhixingplan.top/Article/details/gtpocjwabz.html

Ruby: u.is_a?(User)
来源：http://dali.yuxming.cn/Article/details/gtfbyrehxz.html

C#:   u is User
来源：http://dali.yj20258.top/Article/details/gtrkezhfyv.html

[G14] 数据类 / record
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgtfmmvpk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.snrcjt.cn/Article/details/gtjfruixrw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zycfv.cn/Article/details/gtlwzvbxso.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.guannengcc.top/Article/details/gtejjjffqd.html

TS:   type User = { name: string; age: number };
来源：http://dali.snrcjt.cn/Article/details/gtbmhsveim.html

Java: record User(String name, int age) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrygcwtrt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sxryk.cn/Article/details/gtyogqyxgk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cqqwz.cn/Article/details/gtttexlnlh.html

C#:   record User(string Name, int Age);
来源：http://dali.sysykeji.top/Article/details/gtmxqfxvsz.html

[G15] 枚举
来源：http://dali.zycfv.cn/Article/details/gtwlabbbwn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yonumen.top/Article/details/gtomrzxwyd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jqgufenzy.top/Article/details/gtrqtraorq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.meibo888.top/Article/details/gtfgdsoneo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtiixepvuh.html

Java: enum Color { RED, GREEN }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlrjbchrk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jqgufenzy.top/Article/details/gtukvucumu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hnqzz.top/Article/details/gthdbhfszf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fengsongda.top/Article/details/gtmnkmkbdn.html

[G16] 对象转数组 / 字典
来源：http://dali.haohaochexian.top/Article/details/gtlvfsevvu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ywan-chungtsiang.top/Article/details/gthgjmbzue.html

PHP:  get_object_vars($obj);
来源：http://dali.sufxvd.cn/Article/details/gtlvukilgq.html

JS:   Object.entries(obj)
来源：http://dali.sweek.top/Article/details/gtdjozscvn.html

TS:   Object.entries(obj)
来源：http://dali.0kj1m.cn/Article/details/gttbuegnkj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.aizwys.cn/Article/details/gtsnuyyhfo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.daria6918.cn/Article/details/gtnpbgetsk.html

Ruby: obj.instance_variables
来源：http://dali.cheryme.top/Article/details/gtypbovsab.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.guannengcc.top/Article/details/gtzdiemqls.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtzwhxmjaf.html

H. 异常与错误处理
来源：http://dali.yj202588.top/Article/details/gthgaaxslw.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtaubjwelu.html

[H01] try / catch 基础
来源：http://dali.havefunace.top/Article/details/gtvtbuurxq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xinyue.icu/Article/details/gtmvsvwlmo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.0kj1m.cn/Article/details/gtywxsqklq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmaoygkrr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj202588.top/Article/details/gtayozbjrz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xuanzx.com/Article/details/gtigvdmayc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinghuilouyu.cn/Article/details/gtvgownkno.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cdnleiting.top/Article/details/gtxkzemsgu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hywenlv.cn/Article/details/gtlvyitsch.html

[H02] finally / ensure 收尾
来源：http://dali.chenjidiqi.icu/Article/details/gtcvgcsquc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfqfzjxda.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtgcjoljab.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtgubrkzsg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtqnnnvncj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtcwxlfjul.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.aizwys.cn/Article/details/gtbnnqtatu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cucudq.cn/Article/details/gtngomdxre.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtzyxcahus.html

[H03] 主动抛出异常
来源：http://dali.c1oappe.top/Article/details/gtkadjicij.html

Py:   raise ValueError("错误信息")
来源：http://dali.feifeiyinyue.top/Article/details/gtfsytigva.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtuzggzgyk.html

JS:   throw new Error("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtdranecld.html


<!-- 参考信息 -->