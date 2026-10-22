代发 wailian999

JS:   s.split(/\r?\n/)
来源：http://dali.bjfxy.top/Article/details/gt2knmybnxh.html

TS:   s.split(/\r?\n/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2pmbugbuf.html

Java: s.lines().toList()
来源：http://dali.zhixingplan.top/Article/details/gt2ircwcwlo.html

Go:   strings.Split(s, "\n")
来源：http://dali.snrcjt.cn/Article/details/gt2kfdjqczm.html

Ruby: s.lines
来源：http://dali.svipenyu.cn/Article/details/gt2xzvyfqki.html

C#:   s.Split('\n')
来源：http://dali.tianlin.xyz/Article/details/gt2cbktregn.html

[E20] 判断字符串是否为空
来源：http://dali.gogol.net.cn/Article/details/gt2xjfoszvx.html

Py:   if not s:
来源：http://dali.sufxvd.cn/Article/details/gt2enrqdxaa.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gotoacloud.top/Article/details/gt2pfibrsrs.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2skndtvrm.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2chcbhinc.html

Java: if (s.isEmpty()) {}
来源：http://dali.cucudq.cn/Article/details/gt2aflotbfh.html

Go:   if s == "" {}
来源：http://dali.tianlin.xyz/Article/details/gt2xiooojaw.html

Ruby: if s.empty?
来源：http://dali.gotoacloud.top/Article/details/gt2dxizafjf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.tanke756.top/Article/details/gt2rmxpromq.html

[E21] 超长截断加省略号
来源：http://dali.shangyingyoupin.top/Article/details/gt2svtlivqu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sysykeji.top/Article/details/gt2yzenikww.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gt2wxsmleut.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yonumen.top/Article/details/gt2jnouautf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gt2lfndkcgm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.iojbl.cn/Article/details/gt2vwlmrykg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yj202588.top/Article/details/gt2tybvmbld.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gt2shhezcny.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.fengsongda.top/Article/details/gt2yrebkcme.html

[E22] 字节长度与字符长度
来源：http://dali.jqgufenzy.top/Article/details/gt2fqnwoarf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yjmzgiya.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cheryme.top/Article/details/gt2tkircfqq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tian-w.cn/Article/details/gt2ujfqaucq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jianghu66.top/Article/details/gt2kkideaph.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gaohongyu789.top/Article/details/gt2yqzaujyy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhengqikj.top/Article/details/gt2qgkdelpy.html

Ruby: s.bytesize;  s.length
来源：http://dali.316326.xyz/Article/details/gt2knewpyce.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zycfv.cn/Article/details/gt2hrazxecr.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2ibrqjqjs.html

F. 文件与目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vzvpruql.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2vxrdtymz.html

[F01] 读取整个文件
来源：http://dali.quarkkingdee.top/Article/details/gt2uokgnskx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shangyingyoupin.top/Article/details/gt2iqbakccp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gt2gkxsaahr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.wangshuangyany.cn/Article/details/gt2xvzozmiy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yongpay.top/Article/details/gt2ulcniktk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gt2dschclvz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jqgfzy.top/Article/details/gt2xktrpyta.html

Ruby: File.read("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2ceypvcru.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2pcxvezrj.html

[F02] 逐行读取文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qmfabhnx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nanxuanxn.top/Article/details/gt2diopupcw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2kawzmfhu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.bjfxy.top/Article/details/gt2osfavpie.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cqqwz.cn/Article/details/gt2ppttjzev.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.birdmap.top/Article/details/gt2kennnjbx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.meibo888.top/Article/details/gt2nouxusmm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jiagoushi.top/Article/details/gt2crevjwkc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yonumen.top/Article/details/gt2kotamoss.html

[F03] 写入文件（覆盖）
来源：http://dali.yuanzhike.top/Article/details/gt2mozkexqu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jianghu66.top/Article/details/gt2ngxjovmr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yongpay.top/Article/details/gt2ijbdijsc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gt2nhflckar.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gt2aycnaddg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenzaomai.com/Article/details/gt2skwpxgyx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mckjhvrx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinqigufen.top/Article/details/gt2eydexpbe.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kbwogdvh.html

[F04] 追加写入文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zopnkzsf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sysykeji.top/Article/details/gt2krrsayzs.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.redwolf501.top/Article/details/gt2pcnqwyop.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhoulong.xyz/Article/details/gt2lsfrdcfc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbllgkn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.wangshuangyany.cn/Article/details/gt2pbkfzjwa.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gt2xoexfjpk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shuidangran.top/Article/details/gt2buudimns.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cqqwz.cn/Article/details/gt2fthveqam.html

[F05] 判断文件或目录是否存在
来源：http://dali.jlsjyb.cn/Article/details/gt2ayreujlp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tian-w.cn/Article/details/gt2nqbrdzhi.html

PHP:  file_exists("a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2lixovztw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2tismuzbh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2xysvatoz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2ahddciva.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.wangshuangyany.cn/Article/details/gt2bdntzcwu.html

Ruby: File.exist?("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2avyyapyq.html

C#:   File.Exists("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2cavrncqd.html

[F06] 删除文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2kpqpniwa.html

Py:   os.remove("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2eybtgxtn.html

PHP:  unlink("a.txt");
来源：http://dali.yonumen.top/Article/details/gt2skeecmlk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2queyggsn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2rlalxlcr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gt2xcugwkrj.html

Go:   os.Remove("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2jnawjyyc.html

Ruby: File.delete("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2tbgtfgwx.html

C#:   File.Delete("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2hsujlglf.html

[F07] 创建目录（含多级）
来源：http://dali.zycfv.cn/Article/details/gt2sjuspyqd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jlsjyb.cn/Article/details/gt2mfhcuzrc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shangyingyoupin.top/Article/details/gt2hijkewwz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yvedp.cn/Article/details/gt2tedjvbne.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.kuanghao11.cn/Article/details/gt2tpqunrpu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xziqi.cn/Article/details/gt2aaeaywhr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yanxiufei.cn/Article/details/gt2kprfvxwn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hnxiangtu.top/Article/details/gt2uoperzlj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yangfankeji.com/Article/details/gt2xzxouwbb.html

[F08] 遍历目录
来源：http://dali.9152youxi.cn/Article/details/gt2ltlloelg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yuanzhike.top/Article/details/gt2gvcyxbfd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.haohaochexian.top/Article/details/gt2jzotwhao.html

JS:   fs.readdirSync("dir")
来源：http://dali.kuanghao11.cn/Article/details/gt2uvsghmjw.html

TS:   fs.readdirSync("dir")
来源：http://dali.cheryme.top/Article/details/gt2oylzvglw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yonumen.top/Article/details/gt2hrypctmj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nanxuanxn.top/Article/details/gt2bfbylrnp.html

Ruby: Dir.children("dir")
来源：http://dali.yvedp.cn/Article/details/gt2xfhcfsmp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ybcxt.top/Article/details/gt2bhlrewhq.html

[F09] 获取文件大小
来源：http://dali.cheryme.top/Article/details/gt2awungexk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2dijzdxim.html

PHP:  filesize("a.txt");
来源：http://dali.yvedp.cn/Article/details/gt2wxgvskxr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.svipenyu.cn/Article/details/gt2adbnhkny.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sweek.top/Article/details/gt2melbvzht.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gt2mggkxmks.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mwzlouhl.html

Ruby: File.size("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2btmsfxtd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hnxiangtu.top/Article/details/gt2brrnexwe.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bywuawgm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2lzfyfoay.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hammf.cn/Article/details/gt2gojakplu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2sgcezkym.html

TS:   path.extname("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2pbjbrldy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.c1oappe.top/Article/details/gt2xlsylfqx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2lbtvtwok.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2xcpwhhda.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2lbkbkrwo.html

[F11] 复制与移动文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jjwcrwiy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gt2gsrfptdw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2wrmtnlnd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2lzdekdkv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2nbwzotlh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rgowstmw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.snrcjt.cn/Article/details/gt2miflcxnn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2awqaerag.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yueranfly.top/Article/details/gt2cvhsyrul.html

[F12] CSV 读写
来源：http://dali.dashuyun.cn/Article/details/gt2hsiotram.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jiagoushi.top/Article/details/gt2vzqmilfx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jianghu66.top/Article/details/gt2zhzdynfu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhongyouzk.top/Article/details/gt2muinhwhp.html

TS:   // 同上
来源：http://dali.zhoulong.xyz/Article/details/gt2fokfymow.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yj20258888.top/Article/details/gt2jwtjwbzc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gogol.net.cn/Article/details/gt2jxdqusdf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sufxvd.cn/Article/details/gt2umruddne.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tanke756.top/Article/details/gt2smxfkyiq.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2fptbdqga.html

G. 面向对象
来源：http://dali.hfpthk.cn/Article/details/gt2mautzmoq.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2wumhzhlw.html

[G01] 定义类
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ergnzcbn.html

Py:   class User: pass
来源：http://dali.birdmap.top/Article/details/gt2ttfnjykh.html

PHP:  class User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2zyrqxavp.html

JS:   class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tqmnpeod.html

TS:   class User { name: string = ""; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tjkzdpoq.html

Java: class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mkkoiwyh.html

Go:   type User struct { Name string }
来源：http://dali.vqdsnc.cn/Article/details/gt2yezonjwl.html

Ruby: class User; end
来源：http://dali.xuanzx.com/Article/details/gt2lbyaxmna.html

C#:   class User {}
来源：http://dali.cdnleiting.top/Article/details/gt2ffktukxb.html

[G02] 构造函数
来源：http://dali.ybcxt.top/Article/details/gt2bbtujwuu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ffttetzc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sweek.top/Article/details/gt2ugotpjca.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yuanzhike.top/Article/details/gt2gcfhqfhq.html

TS:   constructor(public name: string) {}
来源：http://dali.ydzc1.top/Article/details/gt2gzezvswq.html

Java: User(String name) { this.name = name; }
来源：http://dali.gzhubu.top/Article/details/gt2gwejhcry.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhiwuduotai.top/Article/details/gt2acbqmchb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhixingplan.top/Article/details/gt2ugtgrphi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2pxdutpuj.html

[G03] 实例属性
来源：http://dali.jlsjyb.cn/Article/details/gt2rsfekfpj.html

Py:   self.name = "x"
来源：http://dali.hfpthk.cn/Article/details/gt2fvisvuxv.html

PHP:  public string $name = "x";
来源：http://dali.cdnleiting.top/Article/details/gt2pybkodlc.html

JS:   this.name = "x";
来源：http://dali.chenlongwang.top/Article/details/gt2zjjolypo.html

TS:   name: string = "x";
来源：http://dali.yongpay.top/Article/details/gt2ewpdjypf.html

Java: private String name;
来源：http://dali.sweek.top/Article/details/gt2eawnihwk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.9152youxi.cn/Article/details/gt2eyfasuei.html

Ruby: @name = "x"
来源：http://dali.pengpengdd.cyou/Article/details/gt2slcfjtzw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinqigufen.top/Article/details/gt2umrttwve.html

[G04] 定义方法
来源：http://dali.zhixingplan.top/Article/details/gt2ltdbzhit.html

Py:   def greet(self): return self.name
来源：http://dali.jiagoushi.top/Article/details/gt2ehtxnkpk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2zcstvuje.html

JS:   greet() { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vjotdvcd.html

TS:   greet(): string { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gt2yettptuf.html

Java: String greet() { return name; }
来源：http://dali.meibo888.top/Article/details/gt2msmpnpas.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2muptrkhu.html

Ruby: def greet; @name; end
来源：http://dali.tianlin.xyz/Article/details/gt2bzpgjwew.html

C#:   public string Greet() => Name;
来源：http://dali.jiagoushi.top/Article/details/gt2hkwmxlay.html

[G05] 继承
来源：http://dali.feifeiyinyue.top/Article/details/gt2cjwlohvw.html

Py:   class Admin(User): pass
来源：http://dali.guowangkeji.top/Article/details/gt2obvaqgot.html

PHP:  class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gt2ncrwrefx.html

JS:   class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gt2yuaisxbm.html

TS:   class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gt2iqfzfwbx.html

Java: class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gt2kpqlcmsf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.guannengcc.top/Article/details/gt2ncnsxbez.html

Ruby: class Admin < User; end
来源：http://dali.9152youxi.cn/Article/details/gt2izfujtki.html

C#:   class Admin : User {}
来源：http://dali.andypj.xyz/Article/details/gt2hzkyftwb.html

[G06] 重写方法
来源：http://dali.gotoacloud.top/Article/details/gt2ulcflrxs.html

Py:   def greet(self): return "admin"
来源：http://dali.zhengqikj.top/Article/details/gt2wbyrmxvm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gt2srmmxhmr.html

JS:   greet() { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gt2bpzfbtfn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eamxfrmy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pweavivc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.bjfxy.top/Article/details/gt2piadvpol.html

Ruby: def greet; "admin"; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2ehpytxlx.html

C#:   public override string Greet() => "admin";
来源：http://dali.sufxvd.cn/Article/details/gt2okkzyoni.html

[G07] 调用父类方法
来源：http://dali.snrcjt.cn/Article/details/gt2zsptxybe.html

Py:   super().greet()
来源：http://dali.mhx1999.top/Article/details/gt2jkwcrjkb.html

PHP:  parent::greet();
来源：http://dali.zhoulong.xyz/Article/details/gt2uwoyvuww.html

JS:   super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gt2tlcwfqmk.html

TS:   super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gt2csxqfltq.html

Java: super.greet();
来源：http://dali.tianlin.xyz/Article/details/gt2klimncvd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.dashuyun.cn/Article/details/gt2wuhqgbob.html

Ruby: super
来源：http://dali.svipenyu.cn/Article/details/gt2dbnfmlfy.html

C#:   base.Greet();
来源：http://dali.feifeiyinyue.top/Article/details/gt2qcmujjrn.html

[G08] 静态方法与属性
来源：http://dali.vqdsnc.cn/Article/details/gt2evgzsxyq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.kuanghao11.cn/Article/details/gt2udmwfdxf.html

PHP:  public static function f() {}
来源：http://dali.guannengcc.top/Article/details/gt2zqmjibte.html

JS:   static f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2prwzunen.html

TS:   static f(): void {}
来源：http://dali.0kj1m.cn/Article/details/gt2xfojjegc.html

Java: static void f() {}
来源：http://dali.zhongyouzk.top/Article/details/gt2walesoeg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nwfaklrx.html

Ruby: def self.f; end
来源：http://dali.cucudq.cn/Article/details/gt2jmazzmke.html

C#:   public static void F() {}
来源：http://dali.iojbl.cn/Article/details/gt2vmnmrunr.html

[G09] 接口 / 抽象类
来源：http://dali.yuanzhike.top/Article/details/gt2mxltdftw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.andypj.xyz/Article/details/gt2qnnnkhle.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.quarkkingdee.top/Article/details/gt2qtnwjlki.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jqgfzy.top/Article/details/gt2ltsiqpuh.html

TS:   interface Shape { area(): number; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ccjmwonn.html

Java: interface Shape { double area(); }
来源：http://dali.bjfxy.top/Article/details/gt2nyexpwqv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.fengsongda.top/Article/details/gt2ormlklkf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2ztoxnvcx.html

C#:   interface IShape { double Area(); }
来源：http://dali.sufxvd.cn/Article/details/gt2vikferqo.html

[G10] 访问控制
来源：http://dali.nanxuanxn.top/Article/details/gt2qkyydrqz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gogol.net.cn/Article/details/gt2gtqbewlz.html

PHP:  public / protected / private
来源：http://dali.mhx1999.top/Article/details/gt2ciuxwtxc.html

JS:   #private 字段；其余公开
来源：http://dali.xziqi.cn/Article/details/gt2xwmvofjq.html

TS:   public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jaqxnbko.html

Java: public / protected / private / 默认包级
来源：http://dali.aizwys.cn/Article/details/gt2jptnqcom.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nanxuanxn.top/Article/details/gt2unxedmgt.html

Ruby: public / protected / private
来源：http://dali.xinyue.icu/Article/details/gt2bdwgpyjo.html

C#:   public / protected / private / internal
来源：http://dali.c1oappe.top/Article/details/gt2jawbdnzv.html

[G11] getter / setter
来源：http://dali.ybcxt.top/Article/details/gt2llrbksrd.html

Py:   @property 与 @x.setter
来源：http://dali.tianlin.xyz/Article/details/gt2vbuqyfem.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gt2akyotnwv.html

JS:   get name() { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gt2lfwzxqbr.html

TS:   get name(): string { return this._name; }
来源：http://dali.tanke756.top/Article/details/gt2xqxbprxh.html

Java: public String getName() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eubgskkj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shangyingyoupin.top/Article/details/gt2hzzofbvb.html

Ruby: attr_accessor :name
来源：http://dali.andypj.xyz/Article/details/gt2vbhjpmki.html

C#:   public string Name { get; set; }
来源：http://dali.meibo888.top/Article/details/gt2ecqqplgk.html

[G12] 对象转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2holxmoxg.html

Py:   def __str__(self): return self.name
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iuytguru.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gt2cbkwkzed.html

JS:   toString() { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gt2tyisayux.html

TS:   toString(): string { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gt2dqplniqn.html

Java: @Override public String toString() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gt2xnnetnli.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gt2yxxlnaep.html

Ruby: def to_s; @name; end
来源：http://dali.yvedp.cn/Article/details/gt2ffisqijl.html

C#:   public override string ToString() => Name;
来源：http://dali.sxryk.cn/Article/details/gt2qglhyhpy.html

[G13] 判断对象类型
来源：http://dali.gaohongyu789.top/Article/details/gt2uzeskcqm.html

Py:   isinstance(u, User)
来源：http://dali.hammf.cn/Article/details/gt2mrgiesiz.html

PHP:  $u instanceof User
来源：http://dali.yongpay.top/Article/details/gt2fexogghn.html

JS:   u instanceof User
来源：http://dali.cucudq.cn/Article/details/gt2qzlgkrtv.html

TS:   u instanceof User
来源：http://dali.yj20258888.top/Article/details/gt2vucixmon.html

Java: u instanceof User
来源：http://dali.sysykeji.top/Article/details/gt2brnubxee.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.andypj.xyz/Article/details/gt2pnxzpkmj.html

Ruby: u.is_a?(User)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2thirodks.html

C#:   u is User
来源：http://dali.wangshuangyany.cn/Article/details/gt2yjtjzila.html

[G14] 数据类 / record
来源：http://dali.smart0.xyz/Article/details/gt2ueggjfsp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.svipenyu.cn/Article/details/gt2ferducyb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hnqzz.top/Article/details/gt2iqqjjtuc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.redwolf501.top/Article/details/gt2hvzyrvmb.html

TS:   type User = { name: string; age: number };
来源：http://dali.hnxiangtu.top/Article/details/gt2wvkyjtfv.html

Java: record User(String name, int age) {}
来源：http://dali.ybcxt.top/Article/details/gt2ijomgyhf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hywenlv.cn/Article/details/gt2ubbrgfwm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xylfe.cn/Article/details/gt2jdvcwbbq.html

C#:   record User(string Name, int Age);
来源：http://dali.andypj.xyz/Article/details/gt2tyifewzu.html

[G15] 枚举
来源：http://dali.sysykeji.top/Article/details/gt2bkqzxwef.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.iojbl.cn/Article/details/gt2musmzuva.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.redwolf501.top/Article/details/gt2zxjczluf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.mhx1999.top/Article/details/gt2amedcikh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.meibo888.top/Article/details/gt2itoytplw.html

Java: enum Color { RED, GREEN }
来源：http://dali.wangshuangyany.cn/Article/details/gt2tiwiothy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.aizwys.cn/Article/details/gt2chfuozek.html

Ruby: Color = %i[red green].freeze
来源：http://dali.tianlin.xyz/Article/details/gt2eesvydcl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hysaishi.cn/Article/details/gt2hyjyxydh.html

[G16] 对象转数组 / 字典
来源：http://dali.hysaishi.cn/Article/details/gt2dgomnypn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhongyouzk.top/Article/details/gt2umfkspgi.html

PHP:  get_object_vars($obj);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pcyrmpbi.html

JS:   Object.entries(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2rhjrfjdv.html

TS:   Object.entries(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2gxkrmhzx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yuxming.cn/Article/details/gt2lkdmnjho.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cheryme.top/Article/details/gt2ufweixqn.html

Ruby: obj.instance_variables
来源：http://dali.nwbrower.top/Article/details/gt2gyhortxi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gogol.net.cn/Article/details/gt2jozvpfmd.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2xwubwlmq.html

H. 异常与错误处理
来源：http://dali.jianghu66.top/Article/details/gt2exqycbov.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2jcigeknw.html

[H01] try / catch 基础
来源：http://dali.daxiang520.top/Article/details/gt2imvhyfhu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hammf.cn/Article/details/gt2epupqbys.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zdqjudy.top/Article/details/gt2uxlknuhx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zycfv.cn/Article/details/gt2rhalhcap.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nwbrower.top/Article/details/gt2armylgtb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.dianchejie.cn/Article/details/gt2neckywcu.html


<!-- 参考信息 -->