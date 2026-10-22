代发 wailian999

Ruby: s.lines
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ogiuqrsc.html

C#:   s.Split('\n')
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xdrnlavi.html

[E20] 判断字符串是否为空
来源：http://dali.ivvv.top/Article/details/gt2aewreuum.html

Py:   if not s:
来源：http://dali.chenzaomai.com/Article/details/gt2wuyilijq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jiagoushi.top/Article/details/gt2yjsecpeu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yonumen.top/Article/details/gt2gsjzvxzt.html

TS:   if (s === "") {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2breqhajr.html

Java: if (s.isEmpty()) {}
来源：http://dali.sysykeji.top/Article/details/gt2cmmqbiws.html

Go:   if s == "" {}
来源：http://dali.sxryk.cn/Article/details/gt2ivgsjtqx.html

Ruby: if s.empty?
来源：http://dali.sweek.top/Article/details/gt2dklfazee.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.aizwys.cn/Article/details/gt2gobohygx.html

[E21] 超长截断加省略号
来源：http://dali.jlsjyb.cn/Article/details/gt2klqihwpw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hysaishi.cn/Article/details/gt2weunxutr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gt2uydyaesa.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gt2scuzocae.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nwbrower.top/Article/details/gt2dyxdrngz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gt2grpwfhvs.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.dianchejie.cn/Article/details/gt2kmhngpnc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gt2pxdxmteg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gt2kgqxvqsw.html

[E22] 字节长度与字符长度
来源：http://dali.tian-w.cn/Article/details/gt2mfhiigwx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2ycncyvdf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gt2dhzkzqpi.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tianlin.xyz/Article/details/gt2tsajhvbe.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.meibo888.top/Article/details/gt2btxtdvhs.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gmhtgxpd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.fengsongda.top/Article/details/gt2uvlkqsvp.html

Ruby: s.bytesize;  s.length
来源：http://dali.nanxuanxn.top/Article/details/gt2nbvoopiy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhongyouzk.top/Article/details/gt2hgkquidn.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2zmnhnuad.html

F. 文件与目录
来源：http://dali.yueranfly.top/Article/details/gt2uwddatfy.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2efgbgdcw.html

[F01] 读取整个文件
来源：http://dali.cashguo.top/Article/details/gt2kygumbzc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hysaishi.cn/Article/details/gt2fcvhfczg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2twakwobt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.chenlongwang.top/Article/details/gt2ttetrwhi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.c1oappe.top/Article/details/gt2ygvjddlq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gt2mnajyrga.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2alchoziw.html

Ruby: File.read("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2auhibaqd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2mwxzrkdb.html

[F02] 逐行读取文件
来源：http://dali.yangfankeji.com/Article/details/gt2lufdqzgq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zdqjudy.top/Article/details/gt2lggdosrz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yongpay.top/Article/details/gt2zldwpulf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nwbrower.top/Article/details/gt2myfsovmv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgfzy.top/Article/details/gt2zllimytt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.birdmap.top/Article/details/gt2tgsihigf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xylfe.cn/Article/details/gt2wmqqdnif.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.andypj.xyz/Article/details/gt2cqxljfrc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.birdmap.top/Article/details/gt2gfbgaesd.html

[F03] 写入文件（覆盖）
来源：http://dali.hysaishi.cn/Article/details/gt2lzpgkdwr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nwbrower.top/Article/details/gt2jmwdredu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.iojbl.cn/Article/details/gt2jsxohbua.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gt2jzktyern.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.birdmap.top/Article/details/gt2gnvwgnmq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xuanzx.com/Article/details/gt2lyehneoi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlobqky.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jiagoushi.top/Article/details/gt2bkfreadp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.pycfn.com/Article/details/gt2jlmfregq.html

[F04] 追加写入文件
来源：http://dali.fengsongda.top/Article/details/gt2xrrqnxuu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nskdnqee.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.snrcjt.cn/Article/details/gt2xowhgqig.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sxryk.cn/Article/details/gt2ttrntzmx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gt2tjcyplwl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zdqjudy.top/Article/details/gt2kybckopb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yimzuoux.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sxryk.cn/Article/details/gt2xhurgvdi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zdqjudy.top/Article/details/gt2wufujqua.html

[F05] 判断文件或目录是否存在
来源：http://dali.xuanzx.com/Article/details/gt2htxlniwo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.316326.xyz/Article/details/gt2aarhjedx.html

PHP:  file_exists("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gt2nhyfpwgo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2opidwylq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2inuhckhw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ekkyfebr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yuanzhike.top/Article/details/gt2oyvxrnyd.html

Ruby: File.exist?("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2icsjocsd.html

C#:   File.Exists("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2vxnfxhxm.html

[F06] 删除文件
来源：http://dali.wangdashe.top/Article/details/gt2kewqzqrw.html

Py:   os.remove("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2zwrcyevw.html

PHP:  unlink("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gt2jurjkkju.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2ukhrmztw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2offpqurz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gt2edcschwk.html

Go:   os.Remove("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2lgtzrwvr.html

Ruby: File.delete("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2rynmexqo.html

C#:   File.Delete("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2xdebmsla.html

[F07] 创建目录（含多级）
来源：http://dali.meibo888.top/Article/details/gt2idaauffi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jbngogoo.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cqqwz.cn/Article/details/gt2zegqgucn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxuanxn.top/Article/details/gt2zijogogc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shuidangran.top/Article/details/gt2rtcqcumh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.quarkkingdee.top/Article/details/gt2qltbnfsw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ehwqpu.com/Article/details/gt2xnuljtcd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.redwolf501.top/Article/details/gt2nfpcdzrs.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yangfankeji.com/Article/details/gt2fiovmelf.html

[F08] 遍历目录
来源：http://dali.guannengcc.top/Article/details/gt2yzriopdi.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.haohaochexian.top/Article/details/gt2hdbucdvh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hnqzz.top/Article/details/gt2tkjvlphg.html

JS:   fs.readdirSync("dir")
来源：http://dali.cashguo.top/Article/details/gt2vrhecikl.html

TS:   fs.readdirSync("dir")
来源：http://dali.yvedp.cn/Article/details/gt2cobubyhs.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhixingplan.top/Article/details/gt2jkwtwpty.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.dianchejie.cn/Article/details/gt2kldfgdsy.html

Ruby: Dir.children("dir")
来源：http://dali.ivvv.top/Article/details/gt2rbdpnueu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj20258888.top/Article/details/gt2dvwgazwx.html

[F09] 获取文件大小
来源：http://dali.jqgufenzy.top/Article/details/gt2lyqngykb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2meviowfc.html

PHP:  filesize("a.txt");
来源：http://dali.yj202588.top/Article/details/gt2ytkqqiyw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhoulong.xyz/Article/details/gt2tvxjagcj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tian-w.cn/Article/details/gt2xtdeevin.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gt2mknaeqwh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yanxiufei.cn/Article/details/gt2qufcyqud.html

Ruby: File.size("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2ecphcbpe.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.havefunace.top/Article/details/gt2rartqhnk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tanke756.top/Article/details/gt2aumkfjto.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2xgokbfxn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2vmsoylcx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2teiwnksy.html

TS:   path.extname("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2imluzcnv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xuanzx.com/Article/details/gt2knpaqqrv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2xdngfqbm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2vpajysug.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xnebuzfk.html

[F11] 复制与移动文件
来源：http://dali.zdqjudy.top/Article/details/gt2ffqyfsfa.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gt2fwztuvkc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yvedp.cn/Article/details/gt2ioiuwdkb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gt2bvgvoawx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gt2ozufqftp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tian-w.cn/Article/details/gt2tsbeewla.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shzxlz.cn/Article/details/gt2ietdsmds.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2lbsckyzf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.fengsongda.top/Article/details/gt2lzysepbq.html

[F12] CSV 读写
来源：http://dali.fengsongda.top/Article/details/gt2kqqibvua.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tikbwnqm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhongyouzk.top/Article/details/gt2bxrlkriw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yangfankeji.com/Article/details/gt2guszfqnc.html

TS:   // 同上
来源：http://dali.cdnleiting.top/Article/details/gt2ywudnmrl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xziqi.cn/Article/details/gt2alkkwcpo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ethctxml.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.svipenyu.cn/Article/details/gt2leergoxv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hnxiangtu.top/Article/details/gt2sibutxtt.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2loegbagi.html

G. 面向对象
来源：http://dali.sufxvd.cn/Article/details/gt2sidlihdt.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2tlccmlxd.html

[G01] 定义类
来源：http://dali.zycfv.cn/Article/details/gt2gdhfdcqd.html

Py:   class User: pass
来源：http://dali.gzhubu.top/Article/details/gt2mgriuuyz.html

PHP:  class User {}
来源：http://dali.ybcxt.top/Article/details/gt2ddcskwre.html

JS:   class User {}
来源：http://dali.iojbl.cn/Article/details/gt2tjvhdnmr.html

TS:   class User { name: string = ""; }
来源：http://dali.0kj1m.cn/Article/details/gt2grfckhsn.html

Java: class User {}
来源：http://dali.jiagoushi.top/Article/details/gt2ozuuizts.html

Go:   type User struct { Name string }
来源：http://dali.chenzaomai.com/Article/details/gt2octgqjjt.html

Ruby: class User; end
来源：http://dali.tanke756.top/Article/details/gt2rffbcowr.html

C#:   class User {}
来源：http://dali.andypj.xyz/Article/details/gt2frihqtxw.html

[G02] 构造函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ugunnpmd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jlsjyb.cn/Article/details/gt2gxxbmywr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2wtqjiuqn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cucudq.cn/Article/details/gt2kgliksyg.html

TS:   constructor(public name: string) {}
来源：http://dali.mhx1999.top/Article/details/gt2lvywogbu.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2izrtqzhi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ybcxt.top/Article/details/gt2dqaptynr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gogol.net.cn/Article/details/gt2qynjbgxp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.havefunace.top/Article/details/gt2obawkxih.html

[G03] 实例属性
来源：http://dali.hnqzz.top/Article/details/gt2qwokidua.html

Py:   self.name = "x"
来源：http://dali.cashguo.top/Article/details/gt2romrelma.html

PHP:  public string $name = "x";
来源：http://dali.nanxinkj.top/Article/details/gt2cqgwqrqz.html

JS:   this.name = "x";
来源：http://dali.mhx1999.top/Article/details/gt2xteiwhey.html

TS:   name: string = "x";
来源：http://dali.tanke756.top/Article/details/gt2fllkjndo.html

Java: private String name;
来源：http://dali.gogol.net.cn/Article/details/gt2gghlnsdc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ehwqpu.com/Article/details/gt2jqkbqtbr.html

Ruby: @name = "x"
来源：http://dali.jqgufenzy.top/Article/details/gt2dltrwymo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gogol.net.cn/Article/details/gt2rnescesx.html

[G04] 定义方法
来源：http://dali.shangyingyoupin.top/Article/details/gt2vhdisfey.html

Py:   def greet(self): return self.name
来源：http://dali.meibo888.top/Article/details/gt2bakroofn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gt2bqurbstu.html

JS:   greet() { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gt2gateztfd.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2kpxrztme.html

Java: String greet() { return name; }
来源：http://dali.tian-w.cn/Article/details/gt2wjizldot.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sysykeji.top/Article/details/gt2qorchiuo.html

Ruby: def greet; @name; end
来源：http://dali.fengsongda.top/Article/details/gt2svucztkl.html

C#:   public string Greet() => Name;
来源：http://dali.zycfv.cn/Article/details/gt2ddhzcinn.html

[G05] 继承
来源：http://dali.daria6918.cn/Article/details/gt2wumxvbuj.html

Py:   class Admin(User): pass
来源：http://dali.shzxlz.cn/Article/details/gt2ojoiulyt.html

PHP:  class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gt2qwbcrvyx.html

JS:   class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gt2bxzptovd.html

TS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gt2satckukh.html

Java: class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gt2ankyxxrp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cucudq.cn/Article/details/gt2mmratxzf.html

Ruby: class Admin < User; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aklmmedr.html

C#:   class Admin : User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vjijqbsl.html

[G06] 重写方法
来源：http://dali.yvedp.cn/Article/details/gt2ngbpvrxt.html

Py:   def greet(self): return "admin"
来源：http://dali.xinyue.icu/Article/details/gt2hxhwpbtc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tpkdfrhg.html

JS:   greet() { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gt2bzibkyde.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gt2yueebltq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2anysudmj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.quarkkingdee.top/Article/details/gt2rtstkbxq.html

Ruby: def greet; "admin"; end
来源：http://dali.jqgfzy.top/Article/details/gt2rqcpzbih.html

C#:   public override string Greet() => "admin";
来源：http://dali.ydzc1.top/Article/details/gt2hcknthez.html

[G07] 调用父类方法
来源：http://dali.zhengqikj.top/Article/details/gt2wzzupabc.html

Py:   super().greet()
来源：http://dali.gotoacloud.top/Article/details/gt2soiuyjyt.html

PHP:  parent::greet();
来源：http://dali.jinqigufen.top/Article/details/gt2bwkmkmuu.html

JS:   super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gt2eqiawuei.html

TS:   super.greet();
来源：http://dali.smart0.xyz/Article/details/gt2kgghffwb.html

Java: super.greet();
来源：http://dali.ehwqpu.com/Article/details/gt2jpmhlutz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.mhx1999.top/Article/details/gt2yolqhilp.html

Ruby: super
来源：http://dali.sxryk.cn/Article/details/gt2jheugouv.html

C#:   base.Greet();
来源：http://dali.dianchejie.cn/Article/details/gt2mljtdqon.html

[G08] 静态方法与属性
来源：http://dali.xylfe.cn/Article/details/gt2dksflcvb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tianlin.xyz/Article/details/gt2yagpumxj.html

PHP:  public static function f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2anmvmxhz.html

JS:   static f() {}
来源：http://dali.hfpthk.cn/Article/details/gt2qludcexp.html

TS:   static f(): void {}
来源：http://dali.yanxiufei.cn/Article/details/gt2jsdrwfin.html

Java: static void f() {}
来源：http://dali.sysykeji.top/Article/details/gt2izspyrbj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinqigfzy.top/Article/details/gt2ifheyxxn.html

Ruby: def self.f; end
来源：http://dali.yueranfly.top/Article/details/gt2idwuvozm.html

C#:   public static void F() {}
来源：http://dali.guowangkeji.top/Article/details/gt2teyhzddy.html

[G09] 接口 / 抽象类
来源：http://dali.tanke756.top/Article/details/gt2kceaalcg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ybcxt.top/Article/details/gt2ofwgnabz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xuanzx.com/Article/details/gt2voyitkcg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.chenzaomai.com/Article/details/gt2htzheiou.html

TS:   interface Shape { area(): number; }
来源：http://dali.daxiang520.top/Article/details/gt2zvolaarc.html

Java: interface Shape { double area(); }
来源：http://dali.gogol.net.cn/Article/details/gt2rhzohkea.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivcvcthr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2ozbaxcvd.html

C#:   interface IShape { double Area(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2hkbcrgho.html

[G10] 访问控制
来源：http://dali.fzhhl.top/Article/details/gt2bdzvvrzs.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.quarkkingdee.top/Article/details/gt2ruyatsem.html

PHP:  public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gt2lcrowtqr.html

JS:   #private 字段；其余公开
来源：http://dali.xziqi.cn/Article/details/gt2umrrmbui.html

TS:   public / protected / private
来源：http://dali.pycfn.com/Article/details/gt2fxmlndco.html

Java: public / protected / private / 默认包级
来源：http://dali.ppjwa.cn/Article/details/gt2ocnaqdhw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yvedp.cn/Article/details/gt2gpthpvtd.html

Ruby: public / protected / private
来源：http://dali.mhx1999.top/Article/details/gt2qcxbglks.html

C#:   public / protected / private / internal
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xdqyqedc.html

[G11] getter / setter
来源：http://dali.fzhhl.top/Article/details/gt2boyltmmu.html

Py:   @property 与 @x.setter
来源：http://dali.gogol.net.cn/Article/details/gt2rdzoirll.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2rrfptbjb.html

JS:   get name() { return this._name; }
来源：http://dali.shzxlz.cn/Article/details/gt2yeprwkjx.html

TS:   get name(): string { return this._name; }
来源：http://dali.tianlin.xyz/Article/details/gt2pugktury.html

Java: public String getName() { return name; }
来源：http://dali.dianchejie.cn/Article/details/gt2cfjeeuqv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.havefunace.top/Article/details/gt2xzmllgjy.html

Ruby: attr_accessor :name
来源：http://dali.smart0.xyz/Article/details/gt2ffwbghuk.html

C#:   public string Name { get; set; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2jlpwrpoi.html

[G12] 对象转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2okmvnugs.html

Py:   def __str__(self): return self.name
来源：http://dali.jianghu66.top/Article/details/gt2ouxpxtcv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gt2jivaajpf.html

JS:   toString() { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gt2zixnjybs.html

TS:   toString(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gt2wowuvplv.html

Java: @Override public String toString() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gt2ufdhvvcv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2bobsfypr.html

Ruby: def to_s; @name; end
来源：http://dali.ehwqpu.com/Article/details/gt2owivxtug.html

C#:   public override string ToString() => Name;
来源：http://dali.hnqzz.top/Article/details/gt2akgtdgqo.html

[G13] 判断对象类型
来源：http://dali.daxiang520.top/Article/details/gt2yjhxxsir.html

Py:   isinstance(u, User)
来源：http://dali.jinqigfzy.top/Article/details/gt2mrfyclwk.html

PHP:  $u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gt2hownystt.html

JS:   u instanceof User
来源：http://dali.aizwys.cn/Article/details/gt2ylpcppdx.html

TS:   u instanceof User
来源：http://dali.gzhubu.top/Article/details/gt2bxehwevo.html

Java: u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gt2eucfmxal.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.kuanghao11.cn/Article/details/gt2pjegjvkz.html

Ruby: u.is_a?(User)
来源：http://dali.hysaishi.cn/Article/details/gt2bsvdfxyy.html

C#:   u is User
来源：http://dali.yueranfly.top/Article/details/gt2qrzhvtfg.html

[G14] 数据类 / record
来源：http://dali.daxiang520.top/Article/details/gt2flwbecrl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.aibaodan.cn/Article/details/gt2fwchulmm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.vqdsnc.cn/Article/details/gt2rjhaekxl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hysaishi.cn/Article/details/gt2nkigryti.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhixingplan.top/Article/details/gt2uvukwhyj.html

Java: record User(String name, int age) {}
来源：http://dali.sweek.top/Article/details/gt2svtmaypg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.9152youxi.cn/Article/details/gt2tdbietjk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gaohongyu789.top/Article/details/gt2yywnozgx.html

C#:   record User(string Name, int Age);
来源：http://dali.xziqi.cn/Article/details/gt2vdruaciw.html

[G15] 枚举
来源：http://dali.cdnleiting.top/Article/details/gt2czbljspa.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ydzc1.top/Article/details/gt2zsmhmwot.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2owlviqko.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yangfankeji.com/Article/details/gt2keajsnkb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gt2jbxyffku.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhengqikj.top/Article/details/gt2zjuxisxk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shzxlz.cn/Article/details/gt2emdeixmd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gotoacloud.top/Article/details/gt2gyktjxyk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aibaodan.cn/Article/details/gt2pniiugdd.html

[G16] 对象转数组 / 字典
来源：http://dali.nwbrower.top/Article/details/gt2vunkrjfg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.daria6918.cn/Article/details/gt2bigyjdeo.html

PHP:  get_object_vars($obj);
来源：http://dali.sweek.top/Article/details/gt2yyjjxqwq.html

JS:   Object.entries(obj)
来源：http://dali.birdmap.top/Article/details/gt2rqvqnahp.html

TS:   Object.entries(obj)
来源：http://dali.yj20258888.top/Article/details/gt2rmpyteoe.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tzmngkwq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.wangshuangyany.cn/Article/details/gt2zxjfppij.html

Ruby: obj.instance_variables
来源：http://dali.dianchejie.cn/Article/details/gt2vthhcncr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yonumen.top/Article/details/gt2uamnzwnl.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2nslgiepm.html

H. 异常与错误处理
来源：http://dali.feifeiyinyue.top/Article/details/gt2tsjlcwgt.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2wnfzrmxh.html

[H01] try / catch 基础
来源：http://dali.redwolf501.top/Article/details/gt2pppxhkhc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shzxlz.cn/Article/details/gt2cirmldgk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cheryme.top/Article/details/gt2bitpmwyh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.kuanghao11.cn/Article/details/gt2qazfhrdg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yuxming.cn/Article/details/gt2qoyqmrfy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinqigfzy.top/Article/details/gt2fqzpbcxq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.havefunace.top/Article/details/gt2anxpxwzc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.redwolf501.top/Article/details/gt2pdhbcblh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.9152youxi.cn/Article/details/gt2jhscwqfa.html

[H02] finally / ensure 收尾
来源：http://dali.hongshengwenyu.top/Article/details/gt2fagscfec.html


<!-- 参考信息 -->