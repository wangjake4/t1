代发 wailian999

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xqitxbrw.html

[E19] 多行文本按行拆分
来源：http://dali.ybcxt.top/Article/details/gt2bhadedhn.html

Py:   s.splitlines()
来源：http://dali.gogol.net.cn/Article/details/gt2lwffeinw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yuxming.cn/Article/details/gt2ptanxbvt.html

JS:   s.split(/\r?\n/)
来源：http://dali.sufxvd.cn/Article/details/gt2oimnhnlc.html

TS:   s.split(/\r?\n/)
来源：http://dali.yanxiufei.cn/Article/details/gt2mclqwqfl.html

Java: s.lines().toList()
来源：http://dali.daxiang520.top/Article/details/gt2nihlffsv.html

Go:   strings.Split(s, "\n")
来源：http://dali.redwolf501.top/Article/details/gt2czizizme.html

Ruby: s.lines
来源：http://dali.guannengcc.top/Article/details/gt2nhojgsno.html

C#:   s.Split('\n')
来源：http://dali.jianghu66.top/Article/details/gt2iccqtadi.html

[E20] 判断字符串是否为空
来源：http://dali.gaohongyu789.top/Article/details/gt2zrnjiodf.html

Py:   if not s:
来源：http://dali.tanke756.top/Article/details/gt2vvwqtxzl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jqgufenzy.top/Article/details/gt2cbmkzkha.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2kyigfwpt.html

TS:   if (s === "") {}
来源：http://dali.andypj.xyz/Article/details/gt2wtqogvkw.html

Java: if (s.isEmpty()) {}
来源：http://dali.0kj1m.cn/Article/details/gt2qrxaaswd.html

Go:   if s == "" {}
来源：http://dali.quarkkingdee.top/Article/details/gt2qmctljqp.html

Ruby: if s.empty?
来源：http://dali.wangdashe.top/Article/details/gt2zcjddvas.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yraxklgq.html

[E21] 超长截断加省略号
来源：http://dali.iojbl.cn/Article/details/gt2cmjsfsmt.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cdnleiting.top/Article/details/gt2tkljorbg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gt2ttyiacok.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aizwys.cn/Article/details/gt2tahprtjp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gt2smzxjjzo.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gt2lhbgtsmp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hammf.cn/Article/details/gt2vhhgsodq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gt2sxpfydfi.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ybcxt.top/Article/details/gt2iuafvujn.html

[E22] 字节长度与字符长度
来源：http://dali.jqgufenzy.top/Article/details/gt2xbfkyvwx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hammf.cn/Article/details/gt2vlolhnny.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vvxdgynb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yongpay.top/Article/details/gt2ttwbnukv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fengsongda.top/Article/details/gt2kymcspvg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cheryme.top/Article/details/gt2pboetnrj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sxryk.cn/Article/details/gt2llherrxp.html

Ruby: s.bytesize;  s.length
来源：http://dali.andypj.xyz/Article/details/gt2xscsjyuz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.snrcjt.cn/Article/details/gt2zxkrgfan.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2pqwzekqw.html

F. 文件与目录
来源：http://dali.sweek.top/Article/details/gt2xzimsejo.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2qabahlst.html

[F01] 读取整个文件
来源：http://dali.aizwys.cn/Article/details/gt2jqatgjlw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.andypj.xyz/Article/details/gt2sjczfyhr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kycpxmpu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.vqdsnc.cn/Article/details/gt2ewgqwnfy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gt2hlasikhi.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2wrtvzbuk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.birdmap.top/Article/details/gt2pvkvrdzp.html

Ruby: File.read("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2liqlfulc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2uxrhbsgb.html

[F02] 逐行读取文件
来源：http://dali.c1oappe.top/Article/details/gt2mhrsnpxj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hammf.cn/Article/details/gt2oresbbip.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cucudq.cn/Article/details/gt2dmktkibq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guowangkeji.top/Article/details/gt2ryfmplqp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.0kj1m.cn/Article/details/gt2lbrhusnh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.snrcjt.cn/Article/details/gt2irusouwr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shuidangran.top/Article/details/gt2mkjajcmt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zdqjudy.top/Article/details/gt2pxkdnhel.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.kuanghao11.cn/Article/details/gt2vgoeowvx.html

[F03] 写入文件（覆盖）
来源：http://dali.xinyue.icu/Article/details/gt2ikquklkp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.guannengcc.top/Article/details/gt2rqyajtcl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cashguo.top/Article/details/gt2hqpwgdsu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuxming.cn/Article/details/gt2xddclnyz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gnixhvpw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.aizwys.cn/Article/details/gt2iimlelci.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nwbrower.top/Article/details/gt2sradtafi.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.guannengcc.top/Article/details/gt2sqyelqva.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.dashuyun.cn/Article/details/gt2mrveqhvr.html

[F04] 追加写入文件
来源：http://dali.yvedp.cn/Article/details/gt2zikrmaia.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yanxiufei.cn/Article/details/gt2krzcidzr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.dianchejie.cn/Article/details/gt2ffhutjnx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gt2iwwwbfzx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gaifkehs.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.redwolf501.top/Article/details/gt2edtpxwyh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhixingplan.top/Article/details/gt2qdhpcxfx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cqqwz.cn/Article/details/gt2loymmeze.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj20258888.top/Article/details/gt2dzzzfskq.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhixingplan.top/Article/details/gt2iqidhhcr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yuanzhike.top/Article/details/gt2ymolzkqn.html

PHP:  file_exists("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2cwpshkrm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2rxmwzwjb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2zcnczlez.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gt2mtyhkdge.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sufxvd.cn/Article/details/gt2qbblrqtv.html

Ruby: File.exist?("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2mupnevqc.html

C#:   File.Exists("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2zdpctcfl.html

[F06] 删除文件
来源：http://dali.tianlin.xyz/Article/details/gt2lmwxrmlt.html

Py:   os.remove("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2lxckzmkm.html

PHP:  unlink("a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2jcqxgvqd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2ckwhkzfr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2gbaazuqz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gt2ztjclwsv.html

Go:   os.Remove("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2rjfdjjaa.html

Ruby: File.delete("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2kgnauvec.html

C#:   File.Delete("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2flaxtlli.html

[F07] 创建目录（含多级）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eppabsgv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xuanzx.com/Article/details/gt2loiclzqp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zycfv.cn/Article/details/gt2caqkgerq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenlongwang.top/Article/details/gt2bqcxdfqv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gzhubu.top/Article/details/gt2vieidoqq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.dianchejie.cn/Article/details/gt2fgmwaith.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hysaishi.cn/Article/details/gt2vpzcizjd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xziqi.cn/Article/details/gt2jrtwhnvz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jiagoushi.top/Article/details/gt2exwytbai.html

[F08] 遍历目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bfrqghlr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.quarkkingdee.top/Article/details/gt2gtbmbpye.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hammf.cn/Article/details/gt2rinevtue.html

JS:   fs.readdirSync("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gt2pvyespdg.html

TS:   fs.readdirSync("dir")
来源：http://dali.nanxinkj.top/Article/details/gt2ekbuxkcx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ndrzyfdb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jiagoushi.top/Article/details/gt2jxofjuel.html

Ruby: Dir.children("dir")
来源：http://dali.jqgfzy.top/Article/details/gt2qnsaklxc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yvedp.cn/Article/details/gt2lpputyhx.html

[F09] 获取文件大小
来源：http://dali.tianlin.xyz/Article/details/gt2fziwufrz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2jbjilbxk.html

PHP:  filesize("a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2rsrdgapn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ydzc1.top/Article/details/gt2hijcdwsx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.316326.xyz/Article/details/gt2ynucxexp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gt2emxgmjxu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinqigufen.top/Article/details/gt2bqdoctdj.html

Ruby: File.size("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2ebhlepoi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.smart0.xyz/Article/details/gt2uxhcktho.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xziqi.cn/Article/details/gt2pcxondvw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gt2pzhkwvka.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2dujbcdgy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2asntpexc.html

TS:   path.extname("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2ulczmjaj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.dashuyun.cn/Article/details/gt2npgbqapt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2ewfxecea.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2xtljasax.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xbwdpzja.html

[F11] 复制与移动文件
来源：http://dali.cqqwz.cn/Article/details/gt2rggbpmrw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2rphjlqsj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hnqzz.top/Article/details/gt2qifxndoz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2ebqfkuis.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2pdncdngx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.nanxuanxn.top/Article/details/gt2rnvmgbvb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.fzhhl.top/Article/details/gt2dmisfkup.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2ppuldsos.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhiwuduotai.top/Article/details/gt2fvtzjzsl.html

[F12] CSV 读写
来源：http://dali.yuanzhike.top/Article/details/gt2dswbarud.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.birdmap.top/Article/details/gt2ownurflt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.havefunace.top/Article/details/gt2vwarhosc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenjidiqi.icu/Article/details/gt2nayuykru.html

TS:   // 同上
来源：http://dali.birdmap.top/Article/details/gt2bgkmtqwg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yj20258888.top/Article/details/gt2ysbtreya.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.0kj1m.cn/Article/details/gt2axfuaskf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.dashuyun.cn/Article/details/gt2jnegmlxj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tanke756.top/Article/details/gt2ddwjwvvt.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2vgedxssn.html

G. 面向对象
来源：http://dali.yj20258888.top/Article/details/gt2vigagcsn.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2mpwfvwas.html

[G01] 定义类
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qxuuivro.html

Py:   class User: pass
来源：http://dali.havefunace.top/Article/details/gt2shdhqgxm.html

PHP:  class User {}
来源：http://dali.dianchejie.cn/Article/details/gt2siwouwdx.html

JS:   class User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2xznuawfn.html

TS:   class User { name: string = ""; }
来源：http://dali.tianlin.xyz/Article/details/gt2druofmms.html

Java: class User {}
来源：http://dali.nanxinkj.top/Article/details/gt2omssaxfr.html

Go:   type User struct { Name string }
来源：http://dali.shzxlz.cn/Article/details/gt2cffjogxo.html

Ruby: class User; end
来源：http://dali.jinqigufen.top/Article/details/gt2tzzezlxy.html

C#:   class User {}
来源：http://dali.sysykeji.top/Article/details/gt2dcevwxvn.html

[G02] 构造函数
来源：http://dali.cqqwz.cn/Article/details/gt2xnedkqlh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shzxlz.cn/Article/details/gt2mtwlgodv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xinyue.icu/Article/details/gt2oiowlndg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2uuorslsi.html

TS:   constructor(public name: string) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2zriscagp.html

Java: User(String name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gt2acujibdx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.feifeiyinyue.top/Article/details/gt2optgpodv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinqigfzy.top/Article/details/gt2qtajrjwi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yongpay.top/Article/details/gt2rreohlwt.html

[G03] 实例属性
来源：http://dali.shuidangran.top/Article/details/gt2bdluxguw.html

Py:   self.name = "x"
来源：http://dali.yueranfly.top/Article/details/gt2yxujjcqc.html

PHP:  public string $name = "x";
来源：http://dali.kuanghao11.cn/Article/details/gt2jwyjfuzk.html

JS:   this.name = "x";
来源：http://dali.tianlin.xyz/Article/details/gt2dmvmbqbb.html

TS:   name: string = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gt2kdsyesft.html

Java: private String name;
来源：http://dali.cdnleiting.top/Article/details/gt2dvuzybmq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhengqikj.top/Article/details/gt2lvssxjfm.html

Ruby: @name = "x"
来源：http://dali.meibo888.top/Article/details/gt2qirlkzud.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinqigfzy.top/Article/details/gt2dqpcfbsd.html

[G04] 定义方法
来源：http://dali.cashguo.top/Article/details/gt2oidnyfov.html

Py:   def greet(self): return self.name
来源：http://dali.fzhhl.top/Article/details/gt2jvwymrjx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gt2fnnyfisd.html

JS:   greet() { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gt2xbimvkqr.html

TS:   greet(): string { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gt2kvdtlglv.html

Java: String greet() { return name; }
来源：http://dali.cheryme.top/Article/details/gt2gawltznb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gt2xtxdvtww.html

Ruby: def greet; @name; end
来源：http://dali.guannengcc.top/Article/details/gt2aimuhfml.html

C#:   public string Greet() => Name;
来源：http://dali.ppjwa.cn/Article/details/gt2lxxrijvv.html

[G05] 继承
来源：http://dali.gzhubu.top/Article/details/gt2kjkspuov.html

Py:   class Admin(User): pass
来源：http://dali.cucudq.cn/Article/details/gt2fwvjlhlf.html

PHP:  class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gt2vrwbczeh.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dhullpby.html

TS:   class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gt2szkixqug.html

Java: class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gt2vhxeboqb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.andypj.xyz/Article/details/gt2yipdqhtu.html

Ruby: class Admin < User; end
来源：http://dali.quarkkingdee.top/Article/details/gt2iidehbdd.html

C#:   class Admin : User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2zszpnryh.html

[G06] 重写方法
来源：http://dali.guannengcc.top/Article/details/gt2xbbpvksv.html

Py:   def greet(self): return "admin"
来源：http://dali.gogol.net.cn/Article/details/gt2rntzosob.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gt2gbzkczlv.html

JS:   greet() { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gt2xgdffbjr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gt2jroykvrd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2eljkkong.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ybcxt.top/Article/details/gt2znumezjw.html

Ruby: def greet; "admin"; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2lyxlapof.html

C#:   public override string Greet() => "admin";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zphpiamz.html

[G07] 调用父类方法
来源：http://dali.yuxming.cn/Article/details/gt2awikwdij.html

Py:   super().greet()
来源：http://dali.yj20258.top/Article/details/gt2yhgmwckw.html

PHP:  parent::greet();
来源：http://dali.wangshuangyany.cn/Article/details/gt2hlkbuhsm.html

JS:   super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gt2kheyjcry.html

TS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gt2soafvfsi.html

Java: super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gt2jllilvdh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sweek.top/Article/details/gt2drgnthqm.html

Ruby: super
来源：http://dali.hywenlv.cn/Article/details/gt2uzxsfkfq.html

C#:   base.Greet();
来源：http://dali.fengsongda.top/Article/details/gt2lqdexqzr.html

[G08] 静态方法与属性
来源：http://dali.0kj1m.cn/Article/details/gt2jzlxolpb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cqqwz.cn/Article/details/gt2vtzgrdwc.html

PHP:  public static function f() {}
来源：http://dali.yangfankeji.com/Article/details/gt2konlcard.html

JS:   static f() {}
来源：http://dali.yj202588.top/Article/details/gt2recstkmq.html

TS:   static f(): void {}
来源：http://dali.sysykeji.top/Article/details/gt2zvgvirxo.html

Java: static void f() {}
来源：http://dali.yangfankeji.com/Article/details/gt2qjpuasuo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenlongwang.top/Article/details/gt2mbpwchbk.html

Ruby: def self.f; end
来源：http://dali.sufxvd.cn/Article/details/gt2aujekrmf.html

C#:   public static void F() {}
来源：http://dali.ydzc1.top/Article/details/gt2awzmyyhj.html

[G09] 接口 / 抽象类
来源：http://dali.jqgufenzy.top/Article/details/gt2wbbgownq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj20258888.top/Article/details/gt2thlywcmw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wjsaussr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nanxuanxn.top/Article/details/gt2icxbubrv.html

TS:   interface Shape { area(): number; }
来源：http://dali.wangdashe.top/Article/details/gt2ycrafmgr.html

Java: interface Shape { double area(); }
来源：http://dali.jiagoushi.top/Article/details/gt2uyvctlao.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.dashuyun.cn/Article/details/gt2qiazibws.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jyoumei.cn/Article/details/gt2gcuedqmd.html

C#:   interface IShape { double Area(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2hgyhzaur.html

[G10] 访问控制
来源：http://dali.guowangkeji.top/Article/details/gt2chbksetn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ivvv.top/Article/details/gt2cgewxztr.html

PHP:  public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gt2zrxpqfoo.html

JS:   #private 字段；其余公开
来源：http://dali.ivvv.top/Article/details/gt2lrhubaod.html

TS:   public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gt2guximleq.html

Java: public / protected / private / 默认包级
来源：http://dali.yj202588.top/Article/details/gt2hbvfrirb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.bjfxy.top/Article/details/gt2fphjchsw.html

Ruby: public / protected / private
来源：http://dali.yongpay.top/Article/details/gt2zephnygs.html

C#:   public / protected / private / internal
来源：http://dali.hnxiangtu.top/Article/details/gt2zdxgfzdy.html

[G11] getter / setter
来源：http://dali.nwbrower.top/Article/details/gt2zyqnvjmw.html

Py:   @property 与 @x.setter
来源：http://dali.yj20258.top/Article/details/gt2umtmdgmn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gt2luughhuo.html

JS:   get name() { return this._name; }
来源：http://dali.tanke756.top/Article/details/gt2lzboewks.html

TS:   get name(): string { return this._name; }
来源：http://dali.ydzc1.top/Article/details/gt2qzvjfuma.html

Java: public String getName() { return name; }
来源：http://dali.havefunace.top/Article/details/gt2lpajldfw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gt2sxsbxhcg.html

Ruby: attr_accessor :name
来源：http://dali.andypj.xyz/Article/details/gt2afnmkxyl.html

C#:   public string Name { get; set; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lvtklggl.html

[G12] 对象转字符串
来源：http://dali.iojbl.cn/Article/details/gt2fwahqukv.html

Py:   def __str__(self): return self.name
来源：http://dali.yanxiufei.cn/Article/details/gt2qqdrgyop.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gt2imehnbgh.html

JS:   toString() { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gt2woxozvwc.html

TS:   toString(): string { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wwrebwkl.html

Java: @Override public String toString() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gt2qhhrixgm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gt2grjjonsa.html

Ruby: def to_s; @name; end
来源：http://dali.zhongyouzk.top/Article/details/gt2ritnyemd.html

C#:   public override string ToString() => Name;
来源：http://dali.dianchejie.cn/Article/details/gt2djxtunii.html

[G13] 判断对象类型
来源：http://dali.sweek.top/Article/details/gt2kiiglxeq.html

Py:   isinstance(u, User)
来源：http://dali.chenzaomai.com/Article/details/gt2priahvvq.html

PHP:  $u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2anfszdes.html

JS:   u instanceof User
来源：http://dali.xuanzx.com/Article/details/gt2jfjmtubt.html

TS:   u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gt2kawhqsgx.html

Java: u instanceof User
来源：http://dali.yuxming.cn/Article/details/gt2mkdnlgfa.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhoulong.xyz/Article/details/gt2eeguihrf.html

Ruby: u.is_a?(User)
来源：http://dali.hywenlv.cn/Article/details/gt2wmksfjrc.html

C#:   u is User
来源：http://dali.cdnleiting.top/Article/details/gt2kvwvcbnh.html

[G14] 数据类 / record
来源：http://dali.zhengqikj.top/Article/details/gt2dngpaoey.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.wangshuangyany.cn/Article/details/gt2slioytgm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenzaomai.com/Article/details/gt2yptrmopm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.svipenyu.cn/Article/details/gt2nbcmbxcn.html

TS:   type User = { name: string; age: number };
来源：http://dali.sufxvd.cn/Article/details/gt2oxnywxqa.html

Java: record User(String name, int age) {}
来源：http://dali.nwbrower.top/Article/details/gt2dbdkvkys.html

Go:   type User struct { Name string; Age int }
来源：http://dali.dashuyun.cn/Article/details/gt2rjffoehd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.redwolf501.top/Article/details/gt2wmtocutp.html

C#:   record User(string Name, int Age);
来源：http://dali.sxryk.cn/Article/details/gt2vyogynht.html

[G15] 枚举
来源：http://dali.jlsjyb.cn/Article/details/gt2nzhzcluy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.snrcjt.cn/Article/details/gt2szkkknnf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tian-w.cn/Article/details/gt2dbbgijvd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.fzhhl.top/Article/details/gt2icfvkukn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgfzy.top/Article/details/gt2tujwchsl.html

Java: enum Color { RED, GREEN }
来源：http://dali.hnqzz.top/Article/details/gt2uebdpfxz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xylfe.cn/Article/details/gt2axqynlol.html

Ruby: Color = %i[red green].freeze
来源：http://dali.andypj.xyz/Article/details/gt2oacsyfjc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cdnleiting.top/Article/details/gt2jhrqjujd.html

[G16] 对象转数组 / 字典
来源：http://dali.hywenlv.cn/Article/details/gt2wjjbodab.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jiagoushi.top/Article/details/gt2eydttjns.html

PHP:  get_object_vars($obj);
来源：http://dali.9152youxi.cn/Article/details/gt2fwzxpfgu.html

JS:   Object.entries(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2kajrrwvs.html

TS:   Object.entries(obj)
来源：http://dali.ydzc1.top/Article/details/gt2ybdrtekk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cszbqbmc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gotoacloud.top/Article/details/gt2pemrgbac.html

Ruby: obj.instance_variables
来源：http://dali.iojbl.cn/Article/details/gt2fwcwaqon.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nanxinkj.top/Article/details/gt2ojqlghvf.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2fnxxxfjx.html

H. 异常与错误处理
来源：http://dali.yj20258888.top/Article/details/gt2boksepdv.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2frxqmhov.html

[H01] try / catch 基础
来源：http://dali.jinqigfzy.top/Article/details/gt2dicbqclx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.pycfn.com/Article/details/gt2vglueviv.html


<!-- 参考信息 -->