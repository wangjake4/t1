代发 wailian999

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2uojtyygx.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2ubevnxrn.html

F. 文件与目录
来源：http://dali.daxiang520.top/Article/details/gt2vkzquxya.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2thufvtja.html

[F01] 读取整个文件
来源：http://dali.yj202588.top/Article/details/gt2goybbtzx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yueranfly.top/Article/details/gt2dyswukly.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yvedp.cn/Article/details/gt2mjhzajvs.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ppjwa.cn/Article/details/gt2efjgahcd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gt2zhfyehbv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gt2nkdryedb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sweek.top/Article/details/gt2nvojsxkl.html

Ruby: File.read("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2yvgalkef.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tanke756.top/Article/details/gt2uviggmqp.html

[F02] 逐行读取文件
来源：http://dali.chenzaomai.com/Article/details/gt2ctnauxrn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.guannengcc.top/Article/details/gt2cqaiicbt.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shzxlz.cn/Article/details/gt2ateamhuc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tian-w.cn/Article/details/gt2rzabidmh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.c1oappe.top/Article/details/gt2zpdfvjao.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.birdmap.top/Article/details/gt2jajgwrqs.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.guowangkeji.top/Article/details/gt2myepzjxi.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sweek.top/Article/details/gt2wmzjjusy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.daxiang520.top/Article/details/gt2odbxlshe.html

[F03] 写入文件（覆盖）
来源：http://dali.cashguo.top/Article/details/gt2qlrznkha.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.wangshuangyany.cn/Article/details/gt2mlbhdvyz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.daxiang520.top/Article/details/gt2eznstnth.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sweek.top/Article/details/gt2eybmiosd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yvedp.cn/Article/details/gt2gwigrxuw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gogol.net.cn/Article/details/gt2qbqnhhan.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.mhx1999.top/Article/details/gt2cbqyjrgx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jfenqedn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yonumen.top/Article/details/gt2vxxzjite.html

[F04] 追加写入文件
来源：http://dali.jqgufenzy.top/Article/details/gt2levuwnxn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.fengsongda.top/Article/details/gt2dehejpre.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.haohaochexian.top/Article/details/gt2iyfpbjwo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pycfn.com/Article/details/gt2amnlyevq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hbbklamm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.aibaodan.cn/Article/details/gt2sgeqwhfj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hfedzfzr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hfpthk.cn/Article/details/gt2phunwxon.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yuanzhike.top/Article/details/gt2rryubenp.html

[F05] 判断文件或目录是否存在
来源：http://dali.yuanzhike.top/Article/details/gt2qsaneomv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yanxiufei.cn/Article/details/gt2xgnqhird.html

PHP:  file_exists("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yzxedobu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2wefmkrjw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2tyxnjngp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gt2kahpetar.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gogol.net.cn/Article/details/gt2qywmtslk.html

Ruby: File.exist?("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2nmgcztul.html

C#:   File.Exists("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2hbtcvjlt.html

[F06] 删除文件
来源：http://dali.havefunace.top/Article/details/gt2gjocqlvd.html

Py:   os.remove("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2luxiofch.html

PHP:  unlink("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2lcmydqny.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2dvgmbtgc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2uqyujpye.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gt2myenqrlc.html

Go:   os.Remove("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2wiibtyxx.html

Ruby: File.delete("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2sovebekn.html

C#:   File.Delete("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2lurhffvq.html

[F07] 创建目录（含多级）
来源：http://dali.xuanzx.com/Article/details/gt2egjnkmhi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zycfv.cn/Article/details/gt2fzaqyxeb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hywenlv.cn/Article/details/gt2dubjcfnz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2krfgfluq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pycfn.com/Article/details/gt2drcdvzbu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2hqrbuuif.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yanxiufei.cn/Article/details/gt2znedodwj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jiagoushi.top/Article/details/gt2uvnvviqt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cheryme.top/Article/details/gt2uyvhyhvo.html

[F08] 遍历目录
来源：http://dali.redwolf501.top/Article/details/gt2hspepxrm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ypteymxj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.guannengcc.top/Article/details/gt2kkkycrhs.html

JS:   fs.readdirSync("dir")
来源：http://dali.cashguo.top/Article/details/gt2ceyyykye.html

TS:   fs.readdirSync("dir")
来源：http://dali.andypj.xyz/Article/details/gt2cukbmvto.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.fengsongda.top/Article/details/gt2qzqkunyv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhixingplan.top/Article/details/gt2sfcofoal.html

Ruby: Dir.children("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gt2sviaxctj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nanxinkj.top/Article/details/gt2actpciph.html

[F09] 获取文件大小
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lzcdjzhh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2rximdlyp.html

PHP:  filesize("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2njlceiqf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.daria6918.cn/Article/details/gt2ebinuzni.html

TS:   fs.statSync("a.txt").size
来源：http://dali.dianchejie.cn/Article/details/gt2ubhahjog.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gt2ogousrdu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jiagoushi.top/Article/details/gt2gcxkjgtk.html

Ruby: File.size("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2uoqqpnky.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ymjloblc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.guannengcc.top/Article/details/gt2tkxkxkob.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gt2eolcjyuk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2wxcjhhku.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gt2oxdyeins.html

TS:   path.extname("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2awdjovgp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yongpay.top/Article/details/gt2cwlcytrr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2ntzmsoln.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2wozjksda.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2uoacczhn.html

[F11] 复制与移动文件
来源：http://dali.hammf.cn/Article/details/gt2pmvezljp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gt2oaozngwu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2fgzjiwqx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gt2fvoujmob.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qvueaclg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xziqi.cn/Article/details/gt2ukwyjsgi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinqigfzy.top/Article/details/gt2yaikqqqv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gt2vyogsgom.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.aibaodan.cn/Article/details/gt2cdhaanwv.html

[F12] CSV 读写
来源：http://dali.ybcxt.top/Article/details/gt2lmindphb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.quarkkingdee.top/Article/details/gt2ftvvzvdg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oshcuzmk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenjidiqi.icu/Article/details/gt2xbhociaz.html

TS:   // 同上
来源：http://dali.chenzaomai.com/Article/details/gt2sfogfxek.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.mhx1999.top/Article/details/gt2aygtlekg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hmvqsnfd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jyoumei.cn/Article/details/gt2fseqfugo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.guannengcc.top/Article/details/gt2rlccikte.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2jqbbrdxv.html

G. 面向对象
来源：http://dali.yj202588.top/Article/details/gt2jogribmi.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2jwlwejab.html

[G01] 定义类
来源：http://dali.guowangkeji.top/Article/details/gt2wuevagba.html

Py:   class User: pass
来源：http://dali.cdnleiting.top/Article/details/gt2vajaiucv.html

PHP:  class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kkqccjuo.html

JS:   class User {}
来源：http://dali.9152youxi.cn/Article/details/gt2dhwucdil.html

TS:   class User { name: string = ""; }
来源：http://dali.yj202588.top/Article/details/gt2itkefznt.html

Java: class User {}
来源：http://dali.andypj.xyz/Article/details/gt2iovwhkfb.html

Go:   type User struct { Name string }
来源：http://dali.sysykeji.top/Article/details/gt2pysmktiq.html

Ruby: class User; end
来源：http://dali.tian-w.cn/Article/details/gt2zdbrlkcl.html

C#:   class User {}
来源：http://dali.yuanzhike.top/Article/details/gt2zibfsoro.html

[G02] 构造函数
来源：http://dali.zhengqikj.top/Article/details/gt2bdswvkim.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yongpay.top/Article/details/gt2ctxfevwq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2hylkkxeg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hnqzz.top/Article/details/gt2dqkpbllq.html

TS:   constructor(public name: string) {}
来源：http://dali.fengsongda.top/Article/details/gt2qzkyvams.html

Java: User(String name) { this.name = name; }
来源：http://dali.snrcjt.cn/Article/details/gt2qayiwvwx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hongshengwenyu.top/Article/details/gt2sdlwxglp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.andypj.xyz/Article/details/gt2sfjyfxps.html

C#:   public User(string name) { Name = name; }
来源：http://dali.guowangkeji.top/Article/details/gt2wggffxix.html

[G03] 实例属性
来源：http://dali.zhoulong.xyz/Article/details/gt2xdjayamr.html

Py:   self.name = "x"
来源：http://dali.chenzaomai.com/Article/details/gt2uygzmldi.html

PHP:  public string $name = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jxazixns.html

JS:   this.name = "x";
来源：http://dali.nanxinkj.top/Article/details/gt2kchywnfq.html

TS:   name: string = "x";
来源：http://dali.yj202588.top/Article/details/gt2vjzummsn.html

Java: private String name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ayztkouu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.dianchejie.cn/Article/details/gt2dzwipqag.html

Ruby: @name = "x"
来源：http://dali.iojbl.cn/Article/details/gt2sashtblk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shzxlz.cn/Article/details/gt2fpulvitb.html

[G04] 定义方法
来源：http://dali.yanxiufei.cn/Article/details/gt2ksepgsrx.html

Py:   def greet(self): return self.name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dvkmgjyr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gt2ongcsesw.html

JS:   greet() { return this.name; }
来源：http://dali.cheryme.top/Article/details/gt2dtksyxbm.html

TS:   greet(): string { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gt2xbfaxtxr.html

Java: String greet() { return name; }
来源：http://dali.fzhhl.top/Article/details/gt2aspzsgqd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gt2kwkybkqt.html

Ruby: def greet; @name; end
来源：http://dali.pycfn.com/Article/details/gt2kqlpqbay.html

C#:   public string Greet() => Name;
来源：http://dali.xuanzx.com/Article/details/gt2thvcaykk.html

[G05] 继承
来源：http://dali.jqgufenzy.top/Article/details/gt2npksetft.html

Py:   class Admin(User): pass
来源：http://dali.gogol.net.cn/Article/details/gt2saegaxxa.html

PHP:  class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gt2sbygltel.html

JS:   class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gt2eakvfyps.html

TS:   class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2jtyhcsvm.html

Java: class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gt2ngngrehf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zdqjudy.top/Article/details/gt2bekhdrja.html

Ruby: class Admin < User; end
来源：http://dali.dashuyun.cn/Article/details/gt2yiryxjdl.html

C#:   class Admin : User {}
来源：http://dali.gzhubu.top/Article/details/gt2ogtrgtfg.html

[G06] 重写方法
来源：http://dali.ydzc1.top/Article/details/gt2kaogyzzb.html

Py:   def greet(self): return "admin"
来源：http://dali.shangyingyoupin.top/Article/details/gt2dmaqtcze.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gt2wskzibsi.html

JS:   greet() { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2adwikpfq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gt2iqyrdaht.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gt2elwxjcrv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.kuanghao11.cn/Article/details/gt2zrvecsie.html

Ruby: def greet; "admin"; end
来源：http://dali.cheryme.top/Article/details/gt2qvqzwrwi.html

C#:   public override string Greet() => "admin";
来源：http://dali.yangfankeji.com/Article/details/gt2rbpdjkgh.html

[G07] 调用父类方法
来源：http://dali.jlsjyb.cn/Article/details/gt2gbwsvyxb.html

Py:   super().greet()
来源：http://dali.ivvv.top/Article/details/gt2pdxzvvtv.html

PHP:  parent::greet();
来源：http://dali.smart0.xyz/Article/details/gt2xtzetqxn.html

JS:   super.greet();
来源：http://dali.daxiang520.top/Article/details/gt2ktmvfhyl.html

TS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gt2tzirczva.html

Java: super.greet();
来源：http://dali.mhx1999.top/Article/details/gt2rskdngfm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.316326.xyz/Article/details/gt2koghuixf.html

Ruby: super
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jqtqkwso.html

C#:   base.Greet();
来源：http://dali.kuanghao11.cn/Article/details/gt2memoretj.html

[G08] 静态方法与属性
来源：http://dali.pycfn.com/Article/details/gt2zjxnxflv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yongpay.top/Article/details/gt2ristyzkp.html

PHP:  public static function f() {}
来源：http://dali.yj202588.top/Article/details/gt2ciggqmal.html

JS:   static f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2briagbos.html

TS:   static f(): void {}
来源：http://dali.cqqwz.cn/Article/details/gt2ncwuhako.html

Java: static void f() {}
来源：http://dali.ydzc1.top/Article/details/gt2ajxmjcvb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gotoacloud.top/Article/details/gt2okmkfudy.html

Ruby: def self.f; end
来源：http://dali.xylfe.cn/Article/details/gt2espnoipc.html

C#:   public static void F() {}
来源：http://dali.snrcjt.cn/Article/details/gt2wiytbvai.html

[G09] 接口 / 抽象类
来源：http://dali.zdqjudy.top/Article/details/gt2ojxwcfqk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jiagoushi.top/Article/details/gt2lmaansxx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sufxvd.cn/Article/details/gt2atoddwfz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cucudq.cn/Article/details/gt2owgforzb.html

TS:   interface Shape { area(): number; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dqturivx.html

Java: interface Shape { double area(); }
来源：http://dali.chenzaomai.com/Article/details/gt2akngpxqb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hfpthk.cn/Article/details/gt2muedhsjc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yvedp.cn/Article/details/gt2jftpyops.html

C#:   interface IShape { double Area(); }
来源：http://dali.yvedp.cn/Article/details/gt2nhypofma.html

[G10] 访问控制
来源：http://dali.jqgfzy.top/Article/details/gt2zxxirbui.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.birdmap.top/Article/details/gt2vvtjhpqr.html

PHP:  public / protected / private
来源：http://dali.tanke756.top/Article/details/gt2qttljtbv.html

JS:   #private 字段；其余公开
来源：http://dali.tianlin.xyz/Article/details/gt2mpdbevet.html

TS:   public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gt2wzfrhlwi.html

Java: public / protected / private / 默认包级
来源：http://dali.hammf.cn/Article/details/gt2viiildsk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jlsjyb.cn/Article/details/gt2nkgmvafs.html

Ruby: public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gt2pvjaozat.html

C#:   public / protected / private / internal
来源：http://dali.xylfe.cn/Article/details/gt2wopowzrl.html

[G11] getter / setter
来源：http://dali.jqgfzy.top/Article/details/gt2nfohzvlv.html

Py:   @property 与 @x.setter
来源：http://dali.sufxvd.cn/Article/details/gt2ythtptiy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jzwyghvc.html

JS:   get name() { return this._name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2pihxfafm.html

TS:   get name(): string { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2zydtcllh.html

Java: public String getName() { return name; }
来源：http://dali.xziqi.cn/Article/details/gt2htrdigcq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gt2iwrytfig.html

Ruby: attr_accessor :name
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pxeojcnb.html

C#:   public string Name { get; set; }
来源：http://dali.jqgufenzy.top/Article/details/gt2mbicdqpp.html

[G12] 对象转字符串
来源：http://dali.snrcjt.cn/Article/details/gt2dmbbkhyp.html

Py:   def __str__(self): return self.name
来源：http://dali.0kj1m.cn/Article/details/gt2hqiltjsz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gt2pycxopvt.html

JS:   toString() { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gt2sszadoyc.html

TS:   toString(): string { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gt2epfqdotr.html

Java: @Override public String toString() { return name; }
来源：http://dali.gzhubu.top/Article/details/gt2hlqfufwy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gt2sxnbtblp.html

Ruby: def to_s; @name; end
来源：http://dali.xuanzx.com/Article/details/gt2ulxlvvpq.html

C#:   public override string ToString() => Name;
来源：http://dali.svipenyu.cn/Article/details/gt2byhsnbri.html

[G13] 判断对象类型
来源：http://dali.hnqzz.top/Article/details/gt2bxddgksj.html

Py:   isinstance(u, User)
来源：http://dali.nanxuanxn.top/Article/details/gt2mtlkvhae.html

PHP:  $u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gt2ulhywalu.html

JS:   u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gt2nvsugmtw.html

TS:   u instanceof User
来源：http://dali.zycfv.cn/Article/details/gt2reromdrq.html

Java: u instanceof User
来源：http://dali.cashguo.top/Article/details/gt2ndxmimhr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.iojbl.cn/Article/details/gt2envucgnr.html

Ruby: u.is_a?(User)
来源：http://dali.sxryk.cn/Article/details/gt2nyyrkino.html

C#:   u is User
来源：http://dali.daria6918.cn/Article/details/gt2vacdmhdm.html

[G14] 数据类 / record
来源：http://dali.yj20258.top/Article/details/gt2mylcoeci.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.fzhhl.top/Article/details/gt2twblwquq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hnxiangtu.top/Article/details/gt2pwghfdke.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kuaobugq.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2acnvlpep.html

Java: record User(String name, int age) {}
来源：http://dali.hfpthk.cn/Article/details/gt2yzszdsey.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hysaishi.cn/Article/details/gt2urkdavmt.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hfpthk.cn/Article/details/gt2lzoinlcq.html

C#:   record User(string Name, int Age);
来源：http://dali.yj202588.top/Article/details/gt2cjfdhaqt.html

[G15] 枚举
来源：http://dali.hnxiangtu.top/Article/details/gt2qapmrvip.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xinyue.icu/Article/details/gt2yxkbmnrv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ybcxt.top/Article/details/gt2tmlraere.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vngccltt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gotoacloud.top/Article/details/gt2xpkbsfii.html

Java: enum Color { RED, GREEN }
来源：http://dali.yangfankeji.com/Article/details/gt2kvpvatjr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guannengcc.top/Article/details/gt2wtjpitku.html

Ruby: Color = %i[red green].freeze
来源：http://dali.haohaochexian.top/Article/details/gt2mbhbtkos.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hfpthk.cn/Article/details/gt2ypsxypai.html

[G16] 对象转数组 / 字典
来源：http://dali.vqdsnc.cn/Article/details/gt2bcsxagih.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hfpthk.cn/Article/details/gt2zjgrioje.html

PHP:  get_object_vars($obj);
来源：http://dali.dianchejie.cn/Article/details/gt2rcveqcid.html

JS:   Object.entries(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2neeisypa.html

TS:   Object.entries(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2ivknynup.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iotfuirh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenjidiqi.icu/Article/details/gt2wmcjbzxg.html

Ruby: obj.instance_variables
来源：http://dali.zdqjudy.top/Article/details/gt2zvegjedm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xylfe.cn/Article/details/gt2cjkvakor.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2qqozlojq.html

H. 异常与错误处理
来源：http://dali.sufxvd.cn/Article/details/gt2iiuhanlv.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2hnxbpvys.html

[H01] try / catch 基础
来源：http://dali.ehwqpu.com/Article/details/gt2ncacwdvj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2twmlugio.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.316326.xyz/Article/details/gt2xgieirqr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.guannengcc.top/Article/details/gt2btbxwead.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.aizwys.cn/Article/details/gt2djsxjcgl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shzxlz.cn/Article/details/gt2ugeimdqc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenzaomai.com/Article/details/gt2vrcwhxal.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2stfulsvb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cucudq.cn/Article/details/gt2uoxumgnb.html

[H02] finally / ensure 收尾
来源：http://dali.redwolf501.top/Article/details/gt2jinlbxpz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ugaagkxb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gt2vefshpjc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gt2ljlwrfpg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gt2ipkysgji.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gt2kykjrkbq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.svipenyu.cn/Article/details/gt2nftjospa.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hammf.cn/Article/details/gt2hohtaain.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.meibo888.top/Article/details/gt2prddbfnr.html

[H03] 主动抛出异常
来源：http://dali.wangdashe.top/Article/details/gt2yhilumvb.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj202588.top/Article/details/gt2uugjdlmu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gt2ugwlpvod.html

JS:   throw new Error("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gt2tjulqnxp.html

TS:   throw new Error("错误信息");
来源：http://dali.sxryk.cn/Article/details/gt2ktlvlevg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gt2oqpcdsna.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.pycfn.com/Article/details/gt2atfjeflq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xziqi.cn/Article/details/gt2mfrxcqxx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gt2rgilhrta.html

[H04] 自定义异常类型
来源：http://dali.tian-w.cn/Article/details/gt2efjvqjfw.html

Py:   class MyError(Exception): pass
来源：http://dali.aibaodan.cn/Article/details/gt2fsafmchm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.quarkkingdee.top/Article/details/gt2evcazyhy.html

JS:   class MyError extends Error {}
来源：http://dali.aibaodan.cn/Article/details/gt2tbgyoqha.html

TS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kaqaekeh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.iojbl.cn/Article/details/gt2bxtffzog.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhiwuduotai.top/Article/details/gt2jrtromxv.html

Ruby: class MyError < StandardError; end
来源：http://dali.c1oappe.top/Article/details/gt2kdncwyoy.html

C#:   class MyException : Exception {}
来源：http://dali.snrcjt.cn/Article/details/gt2tktycezv.html

[H05] 捕获特定类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2svqsnoht.html

Py:   except ValueError as e:
来源：http://dali.bjfxy.top/Article/details/gt2awsotabs.html


<!-- 参考信息 -->