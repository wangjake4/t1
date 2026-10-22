代发 wailian999

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.bjfxy.top/Article/details/gt2ucdprfmb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2utniqzon.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gt2tuwycvop.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gt2wfycjgnc.html

[E22] 字节长度与字符长度
来源：http://dali.yj20258888.top/Article/details/gt2ztktqwxd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.havefunace.top/Article/details/gt2yjomyovi.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhoulong.xyz/Article/details/gt2ugfhadny.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cdnleiting.top/Article/details/gt2byvldsve.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ehwqpu.com/Article/details/gt2lvfnqgeq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tpjsjrii.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iuexqyuu.html

Ruby: s.bytesize;  s.length
来源：http://dali.sufxvd.cn/Article/details/gt2ahhkbtza.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sysykeji.top/Article/details/gt2pznoogyx.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2dlgjmxhw.html

F. 文件与目录
来源：http://dali.yongpay.top/Article/details/gt2tjjlivyo.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2vjugjxty.html

[F01] 读取整个文件
来源：http://dali.jqgufenzy.top/Article/details/gt2butfjsow.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhiwuduotai.top/Article/details/gt2siceeche.html

PHP:  file_get_contents("a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2mryhvmvc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gogol.net.cn/Article/details/gt2dklrvoxh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.0kj1m.cn/Article/details/gt2ueitlhra.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gt2wtkruhzk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.vqdsnc.cn/Article/details/gt2ktphlskk.html

Ruby: File.read("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2hdtojowd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2znludnql.html

[F02] 逐行读取文件
来源：http://dali.yj20258888.top/Article/details/gt2pzkocqdb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yngnrqwv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2mjnflnqh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ehwqpu.com/Article/details/gt2qcuogwtb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sysykeji.top/Article/details/gt2sutmbxzp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ybcxt.top/Article/details/gt2edxjwsqx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hfpthk.cn/Article/details/gt2rxgirgsq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jlsjyb.cn/Article/details/gt2nalwufxs.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sxryk.cn/Article/details/gt2uxjgrdtf.html

[F03] 写入文件（覆盖）
来源：http://dali.316326.xyz/Article/details/gt2spbmmqwr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.pycfn.com/Article/details/gt2krmnxomn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hammf.cn/Article/details/gt2zwhiqqyu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.kuanghao11.cn/Article/details/gt2pksjkgcn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sxryk.cn/Article/details/gt2zfexjdqn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinqigufen.top/Article/details/gt2soaasdsq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhixingplan.top/Article/details/gt2dejbogxl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.9152youxi.cn/Article/details/gt2byoayvjm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhixingplan.top/Article/details/gt2uvjioxvr.html

[F04] 追加写入文件
来源：http://dali.daxiang520.top/Article/details/gt2kcnohlgv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sxryk.cn/Article/details/gt2uenmxuan.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ehwqpu.com/Article/details/gt2zwzpmlej.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhoulong.xyz/Article/details/gt2vtktoezs.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xziqi.cn/Article/details/gt2bpmdlerf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.smart0.xyz/Article/details/gt2bpyfgmga.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gt2dydqfoka.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.fzhhl.top/Article/details/gt2wyzvanrb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gzhubu.top/Article/details/gt2pukaewpc.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rqfrnbot.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cucudq.cn/Article/details/gt2rbffruue.html

PHP:  file_exists("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2qxuiwgpy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2wceqxgro.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2bpxaloae.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gt2aajkugpn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yuanzhike.top/Article/details/gt2jqbazrht.html

Ruby: File.exist?("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2esxpljrm.html

C#:   File.Exists("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2vgbkgedz.html

[F06] 删除文件
来源：http://dali.hnqzz.top/Article/details/gt2ygtacsee.html

Py:   os.remove("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2dvtjphze.html

PHP:  unlink("a.txt");
来源：http://dali.hammf.cn/Article/details/gt2cadlewjp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2qmwreetk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2yxjmniwm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gt2dbpbmess.html

Go:   os.Remove("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2poowvfzq.html

Ruby: File.delete("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2agcwurma.html

C#:   File.Delete("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gt2ghmtrsie.html

[F07] 创建目录（含多级）
来源：http://dali.pycfn.com/Article/details/gt2fcffoblq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.9152youxi.cn/Article/details/gt2gkyheeoy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.feifeiyinyue.top/Article/details/gt2wsxeawzb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ehwqpu.com/Article/details/gt2nsmwhmay.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258888.top/Article/details/gt2jdhgmkgo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cheryme.top/Article/details/gt2renbrunb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinqigfzy.top/Article/details/gt2rlcxthwl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj202588.top/Article/details/gt2fflglgma.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.fengsongda.top/Article/details/gt2nywqgqdx.html

[F08] 遍历目录
来源：http://dali.meibo888.top/Article/details/gt2tvdrqnuo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenzaomai.com/Article/details/gt2nuaoxslt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yongpay.top/Article/details/gt2vitzsbmf.html

JS:   fs.readdirSync("dir")
来源：http://dali.yvedp.cn/Article/details/gt2vsoxgkmk.html

TS:   fs.readdirSync("dir")
来源：http://dali.c1oappe.top/Article/details/gt2fgwpydls.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gzhubu.top/Article/details/gt2xnlhsdle.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ivvv.top/Article/details/gt2ulipimeq.html

Ruby: Dir.children("dir")
来源：http://dali.aizwys.cn/Article/details/gt2pmuakcix.html

C#:   Directory.GetFiles("dir")
来源：http://dali.snrcjt.cn/Article/details/gt2viosfupp.html

[F09] 获取文件大小
来源：http://dali.yueranfly.top/Article/details/gt2rbdunwiv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2wqsvjrnh.html

PHP:  filesize("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2esohmnbj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.aizwys.cn/Article/details/gt2iztykcml.html

TS:   fs.statSync("a.txt").size
来源：http://dali.quarkkingdee.top/Article/details/gt2zabedpuf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gt2aydfiill.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hnxiangtu.top/Article/details/gt2pzisnuas.html

Ruby: File.size("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2jlicjckd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.dashuyun.cn/Article/details/gt2cdhxnufr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jlsjyb.cn/Article/details/gt2eowyngof.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2xcjztfco.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2ehiywbun.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gt2yavkzzms.html

TS:   path.extname("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2gwkuoupj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jiagoushi.top/Article/details/gt2llbmzwai.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2mxahvzgk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2qxjaxpmj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2qcafjprk.html

[F11] 复制与移动文件
来源：http://dali.yueranfly.top/Article/details/gt2ljhwwead.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gt2irqqtawa.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.316326.xyz/Article/details/gt2tacphdlo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rmafpyqs.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gt2zoucxygz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zdqjudy.top/Article/details/gt2mpjbgxrz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ivvv.top/Article/details/gt2xvfiavag.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gt2txdhdofu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zycfv.cn/Article/details/gt2rjkogosa.html

[F12] CSV 读写
来源：http://dali.tanke756.top/Article/details/gt2mfsuyteu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tanke756.top/Article/details/gt2wlpgcikm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.c1oappe.top/Article/details/gt2khmhiltc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2efgddnxo.html

TS:   // 同上
来源：http://dali.aizwys.cn/Article/details/gt2qlmgqihw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hnxiangtu.top/Article/details/gt2xgwtcjhs.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yangfankeji.com/Article/details/gt2fpgaxkcq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenzaomai.com/Article/details/gt2lvpqmohg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cucudq.cn/Article/details/gt2rjxhivfg.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2hohoedpo.html

G. 面向对象
来源：http://dali.yangfankeji.com/Article/details/gt2hgbfqemo.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2mipkofpo.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2fngtelqv.html

Py:   class User: pass
来源：http://dali.smart0.xyz/Article/details/gt2bepuatmd.html

PHP:  class User {}
来源：http://dali.pycfn.com/Article/details/gt2mcpralnx.html

JS:   class User {}
来源：http://dali.fzhhl.top/Article/details/gt2xobzbsvj.html

TS:   class User { name: string = ""; }
来源：http://dali.yj20258888.top/Article/details/gt2vlujitsu.html

Java: class User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2wlmviwmr.html

Go:   type User struct { Name string }
来源：http://dali.shzxlz.cn/Article/details/gt2fxdyroei.html

Ruby: class User; end
来源：http://dali.ydzc1.top/Article/details/gt2nzfuknej.html

C#:   class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2zjrjelfe.html

[G02] 构造函数
来源：http://dali.cashguo.top/Article/details/gt2woelxrsu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cucudq.cn/Article/details/gt2khfauhcd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2jsqtqtxw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xuanzx.com/Article/details/gt2hcwvryil.html

TS:   constructor(public name: string) {}
来源：http://dali.cucudq.cn/Article/details/gt2aqczudwc.html

Java: User(String name) { this.name = name; }
来源：http://dali.tian-w.cn/Article/details/gt2onjshfvk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shuidangran.top/Article/details/gt2oisbjrgo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.0kj1m.cn/Article/details/gt2bsbhvowa.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hysaishi.cn/Article/details/gt2bbkookzi.html

[G03] 实例属性
来源：http://dali.c1oappe.top/Article/details/gt2sbddffvg.html

Py:   self.name = "x"
来源：http://dali.cqqwz.cn/Article/details/gt2jiuzgpja.html

PHP:  public string $name = "x";
来源：http://dali.sweek.top/Article/details/gt2mteikwow.html

JS:   this.name = "x";
来源：http://dali.zdqjudy.top/Article/details/gt2xmjpjlfz.html

TS:   name: string = "x";
来源：http://dali.guannengcc.top/Article/details/gt2osdwgted.html

Java: private String name;
来源：http://dali.hfpthk.cn/Article/details/gt2jnbgzijn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.guowangkeji.top/Article/details/gt2vnfrfqhl.html

Ruby: @name = "x"
来源：http://dali.nanxuanxn.top/Article/details/gt2iunxvsjy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.c1oappe.top/Article/details/gt2shhsmgfy.html

[G04] 定义方法
来源：http://dali.jinqigufen.top/Article/details/gt2kwadrstg.html

Py:   def greet(self): return self.name
来源：http://dali.snrcjt.cn/Article/details/gt2makrugzi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2tsgixeyh.html

JS:   greet() { return this.name; }
来源：http://dali.tanke756.top/Article/details/gt2bohblyvd.html

TS:   greet(): string { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gt2bllqmfxo.html

Java: String greet() { return name; }
来源：http://dali.ivvv.top/Article/details/gt2dpyjnzpl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gt2zgubbqwx.html

Ruby: def greet; @name; end
来源：http://dali.aizwys.cn/Article/details/gt2niwetpyb.html

C#:   public string Greet() => Name;
来源：http://dali.dianchejie.cn/Article/details/gt2dwgojnba.html

[G05] 继承
来源：http://dali.hysaishi.cn/Article/details/gt2oatrockv.html

Py:   class Admin(User): pass
来源：http://dali.yangfankeji.com/Article/details/gt2gtcegyga.html

PHP:  class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gt2axeodoju.html

JS:   class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2zlzrxais.html

TS:   class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2dunxjgfg.html

Java: class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gt2frhkbuix.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cdnleiting.top/Article/details/gt2srdosvxq.html

Ruby: class Admin < User; end
来源：http://dali.sweek.top/Article/details/gt2slhrsaxf.html

C#:   class Admin : User {}
来源：http://dali.daxiang520.top/Article/details/gt2tfujxxeh.html

[G06] 重写方法
来源：http://dali.yueranfly.top/Article/details/gt2vpiabqhd.html

Py:   def greet(self): return "admin"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bvwyzkpz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gt2dmtzzyww.html

JS:   greet() { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2iijqvueo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gt2habqzogj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ntrdxigb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jjafhchj.html

Ruby: def greet; "admin"; end
来源：http://dali.jyoumei.cn/Article/details/gt2khdvbadn.html

C#:   public override string Greet() => "admin";
来源：http://dali.cheryme.top/Article/details/gt2fevzoevp.html

[G07] 调用父类方法
来源：http://dali.quarkkingdee.top/Article/details/gt2rcdghnjl.html

Py:   super().greet()
来源：http://dali.ppjwa.cn/Article/details/gt2dyjnyvek.html

PHP:  parent::greet();
来源：http://dali.yongpay.top/Article/details/gt2vmtskjqn.html

JS:   super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gt2dcxxkayt.html

TS:   super.greet();
来源：http://dali.tanke756.top/Article/details/gt2thhkfjpx.html

Java: super.greet();
来源：http://dali.yj20258888.top/Article/details/gt2thgdrxkl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hammf.cn/Article/details/gt2dafojlqd.html

Ruby: super
来源：http://dali.zhixingplan.top/Article/details/gt2soqjxosc.html

C#:   base.Greet();
来源：http://dali.pengpengdd.cyou/Article/details/gt2jfvlfiju.html

[G08] 静态方法与属性
来源：http://dali.9152youxi.cn/Article/details/gt2dmxpdccp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xinyue.icu/Article/details/gt2euasctmt.html

PHP:  public static function f() {}
来源：http://dali.daxiang520.top/Article/details/gt2uzfzvgzd.html

JS:   static f() {}
来源：http://dali.cheryme.top/Article/details/gt2gvkfizkv.html

TS:   static f(): void {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2disyvsff.html

Java: static void f() {}
来源：http://dali.316326.xyz/Article/details/gt2mwozdcru.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.316326.xyz/Article/details/gt2hembtmve.html

Ruby: def self.f; end
来源：http://dali.meibo888.top/Article/details/gt2juwfygiv.html

C#:   public static void F() {}
来源：http://dali.fzhhl.top/Article/details/gt2donfxqus.html

[G09] 接口 / 抽象类
来源：http://dali.hfpthk.cn/Article/details/gt2sdeolkvi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gaohongyu789.top/Article/details/gt2xqayyxgy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.316326.xyz/Article/details/gt2gnfdnboy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cashguo.top/Article/details/gt2cxccbsxl.html

TS:   interface Shape { area(): number; }
来源：http://dali.hfpthk.cn/Article/details/gt2znybylqj.html

Java: interface Shape { double area(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2kgbktbpi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zdqjudy.top/Article/details/gt2ocaipuss.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.dianchejie.cn/Article/details/gt2wdxjthyp.html

C#:   interface IShape { double Area(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2stwmhzye.html

[G10] 访问控制
来源：http://dali.gogol.net.cn/Article/details/gt2uvwjrahh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ivvv.top/Article/details/gt2rdjrfkwe.html

PHP:  public / protected / private
来源：http://dali.shuidangran.top/Article/details/gt2xrodfnlb.html

JS:   #private 字段；其余公开
来源：http://dali.zhoulong.xyz/Article/details/gt2cuejzxfs.html

TS:   public / protected / private
来源：http://dali.daxiang520.top/Article/details/gt2dtukodoz.html

Java: public / protected / private / 默认包级
来源：http://dali.zycfv.cn/Article/details/gt2ajrgcxds.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.feifeiyinyue.top/Article/details/gt2iedbthss.html

Ruby: public / protected / private
来源：http://dali.yonumen.top/Article/details/gt2qzjqdvin.html

C#:   public / protected / private / internal
来源：http://dali.zycfv.cn/Article/details/gt2xohjjlbt.html

[G11] getter / setter
来源：http://dali.xinyue.icu/Article/details/gt2bssbtksx.html

Py:   @property 与 @x.setter
来源：http://dali.chenjidiqi.icu/Article/details/gt2hyzsadcn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gt2lxdfafkn.html

JS:   get name() { return this._name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2wafotxgm.html

TS:   get name(): string { return this._name; }
来源：http://dali.tanke756.top/Article/details/gt2hhhcsqho.html

Java: public String getName() { return name; }
来源：http://dali.nwbrower.top/Article/details/gt2xvfjmfeb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gt2peikecvp.html

Ruby: attr_accessor :name
来源：http://dali.jlsjyb.cn/Article/details/gt2fdaxjkds.html

C#:   public string Name { get; set; }
来源：http://dali.ydzc1.top/Article/details/gt2wiumnckv.html

[G12] 对象转字符串
来源：http://dali.cdnleiting.top/Article/details/gt2yuoplcwk.html

Py:   def __str__(self): return self.name
来源：http://dali.tanke756.top/Article/details/gt2dbgvvcpw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gt2inadfpcu.html

JS:   toString() { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gt2onxhtkmv.html

TS:   toString(): string { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2jiyfjmio.html

Java: @Override public String toString() { return name; }
来源：http://dali.tian-w.cn/Article/details/gt2uqnspdca.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gt2rbnjoekn.html

Ruby: def to_s; @name; end
来源：http://dali.xinyue.icu/Article/details/gt2yoisavql.html

C#:   public override string ToString() => Name;
来源：http://dali.0kj1m.cn/Article/details/gt2jhbqexvl.html

[G13] 判断对象类型
来源：http://dali.jiagoushi.top/Article/details/gt2tjdplqbc.html

Py:   isinstance(u, User)
来源：http://dali.sufxvd.cn/Article/details/gt2odbfgtnl.html

PHP:  $u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gt2ohlkadke.html

JS:   u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gt2wkzrglmy.html

TS:   u instanceof User
来源：http://dali.aizwys.cn/Article/details/gt2zzscwnya.html

Java: u instanceof User
来源：http://dali.xuanzx.com/Article/details/gt2gpfkelta.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gzhubu.top/Article/details/gt2kkiiwywv.html

Ruby: u.is_a?(User)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ukjaiprw.html

C#:   u is User
来源：http://dali.chenlongwang.top/Article/details/gt2nkyaipnr.html

[G14] 数据类 / record
来源：http://dali.jinqigfzy.top/Article/details/gt2kkjklpee.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tianlin.xyz/Article/details/gt2eenlalok.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.c1oappe.top/Article/details/gt2whtueual.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zycfv.cn/Article/details/gt2wodvmbtq.html

TS:   type User = { name: string; age: number };
来源：http://dali.sysykeji.top/Article/details/gt2jainorrx.html

Java: record User(String name, int age) {}
来源：http://dali.zhengqikj.top/Article/details/gt2ejgzeara.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sufxvd.cn/Article/details/gt2ohopuwmu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jlsjyb.cn/Article/details/gt2vcnzdupo.html

C#:   record User(string Name, int Age);
来源：http://dali.wangdashe.top/Article/details/gt2drufulzb.html

[G15] 枚举
来源：http://dali.daria6918.cn/Article/details/gt2cgkvblmq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.mhx1999.top/Article/details/gt2bmwhtrlw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cdnleiting.top/Article/details/gt2zpbibizc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.daxiang520.top/Article/details/gt2khgzmbuz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aibaodan.cn/Article/details/gt2wytntyld.html

Java: enum Color { RED, GREEN }
来源：http://dali.cashguo.top/Article/details/gt2uzcbvogw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gzhubu.top/Article/details/gt2itykdenj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinqigfzy.top/Article/details/gt2cddsvpxa.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tian-w.cn/Article/details/gt2mmbzibzm.html

[G16] 对象转数组 / 字典
来源：http://dali.ydzc1.top/Article/details/gt2tyssxghj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.quarkkingdee.top/Article/details/gt2nbgwpdno.html

PHP:  get_object_vars($obj);
来源：http://dali.pycfn.com/Article/details/gt2nidvipgh.html

JS:   Object.entries(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2jewogpuz.html

TS:   Object.entries(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2ovttwcpa.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jiagoushi.top/Article/details/gt2bltcpjwb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sysykeji.top/Article/details/gt2kdvwortt.html

Ruby: obj.instance_variables
来源：http://dali.gzhubu.top/Article/details/gt2ingfihfy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.dianchejie.cn/Article/details/gt2kvpuapmq.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2ijavihfu.html

H. 异常与错误处理
来源：http://dali.zhiwuduotai.top/Article/details/gt2znwhixkb.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2eqjsxcce.html

[H01] try / catch 基础
来源：http://dali.jinqigfzy.top/Article/details/gt2ueewutxv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2xeosfzes.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ivvv.top/Article/details/gt2rnuyeflj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hysaishi.cn/Article/details/gt2ccmnjjyv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hfpthk.cn/Article/details/gt2iknrwhwo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2aidjrlca.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yuxming.cn/Article/details/gt2vlcalyzq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenzaomai.com/Article/details/gt2hbhqnoun.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sweek.top/Article/details/gt2ehbedbke.html

[H02] finally / ensure 收尾
来源：http://dali.fengsongda.top/Article/details/gt2zwuovzyv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gogol.net.cn/Article/details/gt2wtiuwjet.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2imnhrnqv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gt2wdsdixdw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gt2vyrevjka.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gt2ktmtdalf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ydzc1.top/Article/details/gt2uifsphot.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2kqrzbpga.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2tfpiqjcd.html

[H03] 主动抛出异常
来源：http://dali.jiagoushi.top/Article/details/gt2wqoikqjv.html

Py:   raise ValueError("错误信息")
来源：http://dali.snrcjt.cn/Article/details/gt2pclzrvab.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2prlnwmmd.html

JS:   throw new Error("错误信息");
来源：http://dali.fengsongda.top/Article/details/gt2vksbwyaq.html

TS:   throw new Error("错误信息");
来源：http://dali.aizwys.cn/Article/details/gt2uusdrnvr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gt2zjhwmvhp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shzxlz.cn/Article/details/gt2bunjvwcf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.dianchejie.cn/Article/details/gt2gtdoadem.html


<!-- 参考信息 -->