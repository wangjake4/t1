代发 wailian999

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hysaishi.cn/Article/details/gtqisibvay.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gtjvexuvuh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gttjoxcdkj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gtyddpikyk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.fengsongda.top/Article/details/gtffpexyqt.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ybcxt.top/Article/details/gttgsvdhfn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gzhubu.top/Article/details/gttqslcayd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtpjjlevgn.html

[E22] 字节长度与字符长度
来源：http://dali.hywenlv.cn/Article/details/gtjwujjmih.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.kuanghao11.cn/Article/details/gtsxoaxzco.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gtpgcfsuvy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shuidangran.top/Article/details/gtxfhzlynj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gtzhfygrjt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.kuanghao11.cn/Article/details/gtqblopnav.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yj20258888.top/Article/details/gtgwywqkuq.html

Ruby: s.bytesize;  s.length
来源：http://dali.gzhubu.top/Article/details/gtnugvwmmx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shuidangran.top/Article/details/gthleousoa.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtgucoxrmm.html

F. 文件与目录
来源：http://dali.aibaodan.cn/Article/details/gtntafseyi.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtubfbdaic.html

[F01] 读取整个文件
来源：http://dali.bjfxy.top/Article/details/gtuudweemv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tianlin.xyz/Article/details/gtlwqhpzzo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtmnncleyd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.nanxuanxn.top/Article/details/gtkrrancpt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.sysykeji.top/Article/details/gtxbopubzw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gtnedqrwoa.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yonumen.top/Article/details/gtdoexezuk.html

Ruby: File.read("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqqqupeip.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtdkvwdnod.html

[F02] 逐行读取文件
来源：http://dali.hysaishi.cn/Article/details/gtcirfshrd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jiagoushi.top/Article/details/gtcfdosodc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.316326.xyz/Article/details/gtwctdtqpi.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gotoacloud.top/Article/details/gthxvsohgo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigfzy.top/Article/details/gtoxskzjec.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj202588.top/Article/details/gtaelixhxw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.wangshuangyany.cn/Article/details/gtxwngarsw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gaohongyu789.top/Article/details/gtmgtwelrq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.andypj.xyz/Article/details/gtmygftqcc.html

[F03] 写入文件（覆盖）
来源：http://dali.tanke756.top/Article/details/gtuozvurfe.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nwbrower.top/Article/details/gtcleupzar.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hfpthk.cn/Article/details/gtgxlygofh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gtapbxcbnv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.c1oappe.top/Article/details/gtantrnzpd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.daria6918.cn/Article/details/gtmztjwroe.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tianlin.xyz/Article/details/gtjrrclkla.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jyoumei.cn/Article/details/gtjtvzqalm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yongpay.top/Article/details/gtpirfvvpx.html

[F04] 追加写入文件
来源：http://dali.jinqigfzy.top/Article/details/gtdkxtyewg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqyuapkcg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinqigfzy.top/Article/details/gthzpxfpoe.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cucudq.cn/Article/details/gtiyywninx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpxeoqgdf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xylfe.cn/Article/details/gtdggjxnaf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrglhmqrv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenzaomai.com/Article/details/gtoamqxtdj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shzxlz.cn/Article/details/gtuszecann.html

[F05] 判断文件或目录是否存在
来源：http://dali.dashuyun.cn/Article/details/gtafpdblks.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzlrecvyj.html

PHP:  file_exists("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtinprxtst.html

JS:   fs.existsSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtftldomnr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtfqeqblws.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gtbyusruaw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.kuanghao11.cn/Article/details/gtrobikkih.html

Ruby: File.exist?("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtsyqzrgmt.html

C#:   File.Exists("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtubcekvfh.html

[F06] 删除文件
来源：http://dali.guowangkeji.top/Article/details/gtcyargwtz.html

Py:   os.remove("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtnicyybrk.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtufkjkjnz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtzqxmovkx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtnvnakiri.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtiefgnuoz.html

Go:   os.Remove("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtkfnupabr.html

Ruby: File.delete("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtvjjmwxpq.html

C#:   File.Delete("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqplkqiav.html

[F07] 创建目录（含多级）
来源：http://dali.ehwqpu.com/Article/details/gtsnigweej.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.aibaodan.cn/Article/details/gtflzizayo.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jyoumei.cn/Article/details/gthrglhhqp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hysaishi.cn/Article/details/gtwgbzdncu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tanke756.top/Article/details/gtvbnsftrd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.iojbl.cn/Article/details/gtwmpkrllf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shangyingyoupin.top/Article/details/gtmiubbmrt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.mhx1999.top/Article/details/gtxkdtjlpb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhengqikj.top/Article/details/gteargbzpi.html

[F08] 遍历目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxchtvgqn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinqigfzy.top/Article/details/gtlqfavwko.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hysaishi.cn/Article/details/gtesmdvlfy.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhengqikj.top/Article/details/gtznsjcsks.html

TS:   fs.readdirSync("dir")
来源：http://dali.sysykeji.top/Article/details/gtkthwhjvj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ybcxt.top/Article/details/gthgeazkzg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cashguo.top/Article/details/gtfpfpkrsm.html

Ruby: Dir.children("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtklstmjje.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjfplqokp.html

[F09] 获取文件大小
来源：http://dali.meibo888.top/Article/details/gtrjnammhb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtuptwahax.html

PHP:  filesize("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtvxmfybzm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yanxiufei.cn/Article/details/gtppszwtkz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gtdbmrxwsu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gticvuhnkt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.aibaodan.cn/Article/details/gtwbqbueta.html

Ruby: File.size("a.txt")
来源：http://dali.yonumen.top/Article/details/gtmvmuozzf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnpppaqab.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ivvv.top/Article/details/gtqfplbeof.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtdktibpjn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtqceadysc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtqiajcuyu.html

TS:   path.extname("a.txt")
来源：http://dali.cashguo.top/Article/details/gtrcsvbvnr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yongpay.top/Article/details/gtbeayaiws.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtnjevhmxr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtazklarbo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtxtzjszcx.html

[F11] 复制与移动文件
来源：http://dali.tanke756.top/Article/details/gtsaxdiifi.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtfsuictqd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.guannengcc.top/Article/details/gtwkiujsnt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gtolyoziqe.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmtnnsprv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jyoumei.cn/Article/details/gtxhwiqmnh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.redwolf501.top/Article/details/gtnigvptsh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gtnmotbkdm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.aizwys.cn/Article/details/gtvkigoikh.html

[F12] CSV 读写
来源：http://dali.jinqigufen.top/Article/details/gtpioonaqk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhengqikj.top/Article/details/gtlixpfcee.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gtpsdclsbc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hnxiangtu.top/Article/details/gtuchmgmwe.html

TS:   // 同上
来源：http://dali.nwbrower.top/Article/details/gtiyesnkty.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yangfankeji.com/Article/details/gtcqhalqwq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jlsjyb.cn/Article/details/gtjtqdgaoj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gaohongyu789.top/Article/details/gtwpjuflzu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yuxming.cn/Article/details/gttgahigry.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtzaqcgdao.html

G. 面向对象
来源：http://dali.dianchejie.cn/Article/details/gtqffzlxfx.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtvpvflenu.html

[G01] 定义类
来源：http://dali.yongpay.top/Article/details/gtyvrzfjwk.html

Py:   class User: pass
来源：http://dali.nanxuanxn.top/Article/details/gtofmiyqoq.html

PHP:  class User {}
来源：http://dali.sysykeji.top/Article/details/gtvtpynkif.html

JS:   class User {}
来源：http://dali.yuxming.cn/Article/details/gtehtszgyc.html

TS:   class User { name: string = ""; }
来源：http://dali.yj202588.top/Article/details/gtvncpbijc.html

Java: class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtyhjrhkgs.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gtoogvqeqv.html

Ruby: class User; end
来源：http://dali.jqgfzy.top/Article/details/gtpcgpikcd.html

C#:   class User {}
来源：http://dali.yj202588.top/Article/details/gtfgtamvrt.html

[G02] 构造函数
来源：http://dali.fengsongda.top/Article/details/gtaqleuaeu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhengqikj.top/Article/details/gtrpwhslvk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.dashuyun.cn/Article/details/gtpujepisq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.birdmap.top/Article/details/gtqgxxuxut.html

TS:   constructor(public name: string) {}
来源：http://dali.yuanzhike.top/Article/details/gtbitqzawj.html

Java: User(String name) { this.name = name; }
来源：http://dali.cqqwz.cn/Article/details/gtlbaenbkw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jqgufenzy.top/Article/details/gtrvhboikh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sysykeji.top/Article/details/gthwqqcsin.html

C#:   public User(string name) { Name = name; }
来源：http://dali.redwolf501.top/Article/details/gtjygwfafo.html

[G03] 实例属性
来源：http://dali.gotoacloud.top/Article/details/gtnmefwkox.html

Py:   self.name = "x"
来源：http://dali.bjfxy.top/Article/details/gtweaixrys.html

PHP:  public string $name = "x";
来源：http://dali.316326.xyz/Article/details/gtnszquogp.html

JS:   this.name = "x";
来源：http://dali.xuanzx.com/Article/details/gtidgmrvvh.html

TS:   name: string = "x";
来源：http://dali.xziqi.cn/Article/details/gtrmpultil.html

Java: private String name;
来源：http://dali.daxiang520.top/Article/details/gtmgbibswj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.pengpengdd.cyou/Article/details/gtlxfuruhf.html

Ruby: @name = "x"
来源：http://dali.tian-w.cn/Article/details/gtcpgecvvq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnujvoxrw.html

[G04] 定义方法
来源：http://dali.kuanghao11.cn/Article/details/gtztcejqvv.html

Py:   def greet(self): return self.name
来源：http://dali.nanxinkj.top/Article/details/gtjifzfycd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gtedlaupzj.html

JS:   greet() { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtvlmyuuht.html

TS:   greet(): string { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gtznithoyh.html

Java: String greet() { return name; }
来源：http://dali.316326.xyz/Article/details/gtxyualgkn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gtshnszhzd.html

Ruby: def greet; @name; end
来源：http://dali.yj202588.top/Article/details/gtbodfltpa.html

C#:   public string Greet() => Name;
来源：http://dali.yonumen.top/Article/details/gtzhorqpoo.html

[G05] 继承
来源：http://dali.shanyushiyangtech.top/Article/details/gttojsbacs.html

Py:   class Admin(User): pass
来源：http://dali.wangdashe.top/Article/details/gtwcwfyvbg.html

PHP:  class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtqbgaiouu.html

JS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtfpyambom.html

TS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtntklhrck.html

Java: class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtefnzwagn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cdnleiting.top/Article/details/gtwlrdgyav.html

Ruby: class Admin < User; end
来源：http://dali.yj202588.top/Article/details/gtkvbpilqn.html

C#:   class Admin : User {}
来源：http://dali.yueranfly.top/Article/details/gtxjrtcthy.html

[G06] 重写方法
来源：http://dali.hongshengwenyu.top/Article/details/gtwfowicje.html

Py:   def greet(self): return "admin"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtevjfbekp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtfclrlhrr.html

JS:   greet() { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gtwypsrbvt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtsidkrdpn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gtdxafojyn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gaohongyu789.top/Article/details/gtlqbvwoxv.html

Ruby: def greet; "admin"; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtocguhkrc.html

C#:   public override string Greet() => "admin";
来源：http://dali.jianghu66.top/Article/details/gtzlfrvami.html

[G07] 调用父类方法
来源：http://dali.tian-w.cn/Article/details/gtfomsjcgl.html

Py:   super().greet()
来源：http://dali.fzhhl.top/Article/details/gtetbuhymd.html

PHP:  parent::greet();
来源：http://dali.daxiang520.top/Article/details/gtfiafrivz.html

JS:   super.greet();
来源：http://dali.fengsongda.top/Article/details/gtmmjcjbhu.html

TS:   super.greet();
来源：http://dali.yuxming.cn/Article/details/gtscjethdd.html

Java: super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtdxztqthp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cashguo.top/Article/details/gtckwcvfwg.html

Ruby: super
来源：http://dali.jinqigufen.top/Article/details/gtklgwjowh.html

C#:   base.Greet();
来源：http://dali.bjfxy.top/Article/details/gtipjviuku.html

[G08] 静态方法与属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvqhqwpvo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sysykeji.top/Article/details/gtnnsggucb.html

PHP:  public static function f() {}
来源：http://dali.jqgufenzy.top/Article/details/gtuuedhvgi.html

JS:   static f() {}
来源：http://dali.xuanzx.com/Article/details/gtgaxtlzuh.html

TS:   static f(): void {}
来源：http://dali.xuetiantiany.cn/Article/details/gtomqrrhjm.html

Java: static void f() {}
来源：http://dali.yongpay.top/Article/details/gtngkfazta.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuxkyuice.html

Ruby: def self.f; end
来源：http://dali.jianghu66.top/Article/details/gtmxscvpbd.html

C#:   public static void F() {}
来源：http://dali.havefunace.top/Article/details/gtynqrizro.html

[G09] 接口 / 抽象类
来源：http://dali.redwolf501.top/Article/details/gtrzqxyioo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.dashuyun.cn/Article/details/gtsutirowa.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hongshengwenyu.top/Article/details/gtcrdgyrwd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.bjfxy.top/Article/details/gtssdniunl.html

TS:   interface Shape { area(): number; }
来源：http://dali.hammf.cn/Article/details/gtfrvsdaxs.html

Java: interface Shape { double area(); }
来源：http://dali.shuidangran.top/Article/details/gtoczrrtkn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.c1oappe.top/Article/details/gtvcavumix.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.daxiang520.top/Article/details/gtufpdeqnl.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhixingplan.top/Article/details/gtetrmhsew.html

[G10] 访问控制
来源：http://dali.sweek.top/Article/details/gtsuoiemzn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.daria6918.cn/Article/details/gtjdmwkjht.html

PHP:  public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gtehgdnznp.html

JS:   #private 字段；其余公开
来源：http://dali.xinyue.icu/Article/details/gthbucdmhm.html

TS:   public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gtvdqackai.html

Java: public / protected / private / 默认包级
来源：http://dali.feifeiyinyue.top/Article/details/gtrcqxcepp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sufxvd.cn/Article/details/gttrlhriia.html

Ruby: public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gtiokwwjyv.html

C#:   public / protected / private / internal
来源：http://dali.fzhhl.top/Article/details/gtzlllvuop.html

[G11] getter / setter
来源：http://dali.aizwys.cn/Article/details/gtlpddtffs.html

Py:   @property 与 @x.setter
来源：http://dali.jqgfzy.top/Article/details/gtbpcbgcyw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gtgjiblqew.html

JS:   get name() { return this._name; }
来源：http://dali.yangfankeji.com/Article/details/gtxbaltuko.html

TS:   get name(): string { return this._name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtxfgzmruk.html

Java: public String getName() { return name; }
来源：http://dali.sxryk.cn/Article/details/gtsescacbz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gtybgylgqn.html

Ruby: attr_accessor :name
来源：http://dali.zycfv.cn/Article/details/gtqnopkyez.html

C#:   public string Name { get; set; }
来源：http://dali.hfpthk.cn/Article/details/gtrhprbcht.html

[G12] 对象转字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtgckuezsm.html

Py:   def __str__(self): return self.name
来源：http://dali.fengsongda.top/Article/details/gtmbsuimbg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gtdtjfcfrz.html

JS:   toString() { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gtrwllfddg.html

TS:   toString(): string { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gthfefswol.html

Java: @Override public String toString() { return name; }
来源：http://dali.yuxming.cn/Article/details/gtfmtatrkc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtgviljzye.html

Ruby: def to_s; @name; end
来源：http://dali.cqqwz.cn/Article/details/gtecxlzssk.html

C#:   public override string ToString() => Name;
来源：http://dali.gogol.net.cn/Article/details/gtksyfxzqj.html

[G13] 判断对象类型
来源：http://dali.jyoumei.cn/Article/details/gtosfxjklp.html

Py:   isinstance(u, User)
来源：http://dali.chenjidiqi.icu/Article/details/gtkbfyblut.html

PHP:  $u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gtryjoxihu.html

JS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gtxoufhaho.html

TS:   u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gtcfeoskgz.html

Java: u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gtfqgroeot.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hfpthk.cn/Article/details/gtzpfkzhdw.html

Ruby: u.is_a?(User)
来源：http://dali.sufxvd.cn/Article/details/gtuigntale.html

C#:   u is User
来源：http://dali.xuetiantiany.cn/Article/details/gtjobkczoz.html

[G14] 数据类 / record
来源：http://dali.ppjwa.cn/Article/details/gtgmdtfgie.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tianlin.xyz/Article/details/gtdzayyzrn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.c1oappe.top/Article/details/gtiqobtgdw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ydzc1.top/Article/details/gtbihduics.html

TS:   type User = { name: string; age: number };
来源：http://dali.nanxuanxn.top/Article/details/gtirdodbfm.html

Java: record User(String name, int age) {}
来源：http://dali.zycfv.cn/Article/details/gtkchbkhss.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zdqjudy.top/Article/details/gtjerfsvie.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cqqwz.cn/Article/details/gtucgaevcr.html

C#:   record User(string Name, int Age);
来源：http://dali.hammf.cn/Article/details/gthcvstnxw.html

[G15] 枚举
来源：http://dali.0kj1m.cn/Article/details/gtdiwifrgv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.mhx1999.top/Article/details/gtwgjlqjtc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yueranfly.top/Article/details/gtjbmeagbb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenjidiqi.icu/Article/details/gtohafphue.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhixingplan.top/Article/details/gtizidtjoa.html

Java: enum Color { RED, GREEN }
来源：http://dali.hammf.cn/Article/details/gtrsbahqvz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhoulong.xyz/Article/details/gthaquvpeo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sysykeji.top/Article/details/gtpqslphhp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gtrjkmmgnb.html

[G16] 对象转数组 / 字典
来源：http://dali.shzxlz.cn/Article/details/gtjodkmyze.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.fzhhl.top/Article/details/gteukvnsol.html

PHP:  get_object_vars($obj);
来源：http://dali.yj202588.top/Article/details/gtuwxninsh.html

JS:   Object.entries(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgnnhopsh.html

TS:   Object.entries(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtmjgkjjbh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jyoumei.cn/Article/details/gtctiidvje.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ehwqpu.com/Article/details/gtibjevvbt.html

Ruby: obj.instance_variables
来源：http://dali.ydzc1.top/Article/details/gtzsfxzeko.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jiagoushi.top/Article/details/gtoyuifduy.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtdixwrfyw.html

H. 异常与错误处理
来源：http://dali.smart0.xyz/Article/details/gtuuekncmo.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtrtbvfdom.html

[H01] try / catch 基础
来源：http://dali.tanke756.top/Article/details/gtpbwgtwom.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.c1oappe.top/Article/details/gtzupcrcqi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtlhwfdcnd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.birdmap.top/Article/details/gttcuidyai.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gtyebhiify.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jiagoushi.top/Article/details/gtxkefdeoo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nanxuanxn.top/Article/details/gtrxymashs.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yanxiufei.cn/Article/details/gtgjzfngya.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xuanzx.com/Article/details/gtjecqlxtl.html

[H02] finally / ensure 收尾
来源：http://dali.jiagoushi.top/Article/details/gtkqccxbht.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cqqwz.cn/Article/details/gtnazmsmtw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtpalbxzdu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkszigdhe.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtjigglafw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gtcjivynkm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hongshengwenyu.top/Article/details/gtjglwhnsw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.guannengcc.top/Article/details/gthdlbxlof.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtuazwqifb.html

[H03] 主动抛出异常
来源：http://dali.cheryme.top/Article/details/gtorydwckw.html

Py:   raise ValueError("错误信息")
来源：http://dali.hongshengwenyu.top/Article/details/gtzpjbwcax.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gtzuzgycqy.html

JS:   throw new Error("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtpwlyyabz.html


<!-- 参考信息 -->