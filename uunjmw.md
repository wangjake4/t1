代发 wailian999

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gt2vzbffztb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gt2zxgjisbf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sysykeji.top/Article/details/gt2hxmvkusp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.daria6918.cn/Article/details/gt2npfeiqhs.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.aibaodan.cn/Article/details/gt2nlvrukqy.html

[E19] 多行文本按行拆分
来源：http://dali.xziqi.cn/Article/details/gt2mmtdknws.html

Py:   s.splitlines()
来源：http://dali.sweek.top/Article/details/gt2dqekvqmt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.nwbrower.top/Article/details/gt2zohozfze.html

JS:   s.split(/\r?\n/)
来源：http://dali.xinyue.icu/Article/details/gt2knrwzftb.html

TS:   s.split(/\r?\n/)
来源：http://dali.yonumen.top/Article/details/gt2yjxqohyh.html

Java: s.lines().toList()
来源：http://dali.yuxming.cn/Article/details/gt2bhlsreyh.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhoulong.xyz/Article/details/gt2bzzdvlwn.html

Ruby: s.lines
来源：http://dali.cucudq.cn/Article/details/gt2iqftskij.html

C#:   s.Split('\n')
来源：http://dali.yj20258.top/Article/details/gt2ymoiqhlr.html

[E20] 判断字符串是否为空
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eskuxdty.html

Py:   if not s:
来源：http://dali.yanxiufei.cn/Article/details/gt2dulujyor.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jianghu66.top/Article/details/gt2sszdheaa.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ydzc1.top/Article/details/gt2iyalcgub.html

TS:   if (s === "") {}
来源：http://dali.yangfankeji.com/Article/details/gt2hzzezyag.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhengqikj.top/Article/details/gt2lkknzyvg.html

Go:   if s == "" {}
来源：http://dali.jiagoushi.top/Article/details/gt2hnoirpaf.html

Ruby: if s.empty?
来源：http://dali.kuanghao11.cn/Article/details/gt2zqnfchmr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2uzwwqrdq.html

[E21] 超长截断加省略号
来源：http://dali.snrcjt.cn/Article/details/gt2vltbwyjp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dhsumsxs.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gt2hvkvixev.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gt2wldammxx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gt2qksfycna.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gt2ljkulakg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cdnleiting.top/Article/details/gt2trgzyzoe.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2evveechu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yueranfly.top/Article/details/gt2zigtvviz.html

[E22] 字节长度与字符长度
来源：http://dali.birdmap.top/Article/details/gt2rczmpiwd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.daria6918.cn/Article/details/gt2maoejnsc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gt2jcpyiexx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shzxlz.cn/Article/details/gt2repenmri.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yueranfly.top/Article/details/gt2yqaxnfxy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ralibpbu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jyoumei.cn/Article/details/gt2okpefytb.html

Ruby: s.bytesize;  s.length
来源：http://dali.cdnleiting.top/Article/details/gt2umdqvxqj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.0kj1m.cn/Article/details/gt2nzksvzyp.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2vkfqpjyg.html

F. 文件与目录
来源：http://dali.cqqwz.cn/Article/details/gt2vqhvubfm.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2rnxunifz.html

[F01] 读取整个文件
来源：http://dali.sweek.top/Article/details/gt2avjtpwsf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sweek.top/Article/details/gt2safztplx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.bjfxy.top/Article/details/gt2ragssxtw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bltvbxnv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ydzc1.top/Article/details/gt2urmqpcea.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2lxxuvbjt.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.pengpengdd.cyou/Article/details/gt2wbvxbztr.html

Ruby: File.read("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2aruabjqm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2rtssjjfo.html

[F02] 逐行读取文件
来源：http://dali.pycfn.com/Article/details/gt2shubiszu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.iojbl.cn/Article/details/gt2xggpgshn.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj202588.top/Article/details/gt2gvytqycs.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kjurksld.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgfzy.top/Article/details/gt2isjcpjhk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ehwqpu.com/Article/details/gt2svvcmzab.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hnqzz.top/Article/details/gt2hkvjckxe.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.9152youxi.cn/Article/details/gt2jpjeturg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.iojbl.cn/Article/details/gt2waifpevu.html

[F03] 写入文件（覆盖）
来源：http://dali.gotoacloud.top/Article/details/gt2joevjmex.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.guowangkeji.top/Article/details/gt2kkuzbnzu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yueranfly.top/Article/details/gt2nwfoebsj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhongyouzk.top/Article/details/gt2jqvbnkcs.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.snrcjt.cn/Article/details/gt2royyninw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ehwqpu.com/Article/details/gt2ktnetxus.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yangfankeji.com/Article/details/gt2xwfwvvhq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sxryk.cn/Article/details/gt2hocizgyk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.nwbrower.top/Article/details/gt2vjnzjnby.html

[F04] 追加写入文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xsaptyzd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cashguo.top/Article/details/gt2sccyyfik.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jqgufenzy.top/Article/details/gt2fjznlngr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hfpthk.cn/Article/details/gt2roiltqtl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuxming.cn/Article/details/gt2ntpbzlok.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj20258.top/Article/details/gt2daxcibxl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cucudq.cn/Article/details/gt2bxieitar.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.meibo888.top/Article/details/gt2svvddzlc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xuanzx.com/Article/details/gt2gqokseyr.html

[F05] 判断文件或目录是否存在
来源：http://dali.hnqzz.top/Article/details/gt2noagnduk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.snrcjt.cn/Article/details/gt2kbgghydv.html

PHP:  file_exists("a.txt");
来源：http://dali.yongpay.top/Article/details/gt2skholwzv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2lkzpwgoc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2lajdchnh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gt2bxttektk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jiagoushi.top/Article/details/gt2cuwersvs.html

Ruby: File.exist?("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2aowalilo.html

C#:   File.Exists("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2fglbcawv.html

[F06] 删除文件
来源：http://dali.quarkkingdee.top/Article/details/gt2gmkcrsvf.html

Py:   os.remove("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2gfuaqnrp.html

PHP:  unlink("a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2yowqyiak.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2yhwncgel.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2gpdurfyi.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gt2fiqhujmh.html

Go:   os.Remove("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2uhlbzmhx.html

Ruby: File.delete("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2jwgjezzr.html

C#:   File.Delete("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2dftxtteq.html

[F07] 创建目录（含多级）
来源：http://dali.nanxinkj.top/Article/details/gt2dlxplaha.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yanxiufei.cn/Article/details/gt2zuayzmtz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.wangdashe.top/Article/details/gt2dzsjdxdh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.smart0.xyz/Article/details/gt2oqoopxqo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigfzy.top/Article/details/gt2tzzsbwsw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hnqzz.top/Article/details/gt2uugwlndr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.fzhhl.top/Article/details/gt2gwxtsdnv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenzaomai.com/Article/details/gt2xwjvbqyf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jianghu66.top/Article/details/gt2ifcuzlag.html

[F08] 遍历目录
来源：http://dali.pycfn.com/Article/details/gt2esdxzfdi.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rkxakamz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.andypj.xyz/Article/details/gt2gauiuxaq.html

JS:   fs.readdirSync("dir")
来源：http://dali.gaohongyu789.top/Article/details/gt2ytprrymu.html

TS:   fs.readdirSync("dir")
来源：http://dali.ppjwa.cn/Article/details/gt2rcfvozte.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hnxiangtu.top/Article/details/gt2bapphxee.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sufxvd.cn/Article/details/gt2xxvjredy.html

Ruby: Dir.children("dir")
来源：http://dali.pycfn.com/Article/details/gt2gbsbilzn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gt2cuebgbdj.html

[F09] 获取文件大小
来源：http://dali.yangfankeji.com/Article/details/gt2zwrqvdmt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2nvhtjrcy.html

PHP:  filesize("a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2spyzkoew.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ehwqpu.com/Article/details/gt2pwmxxwll.html

TS:   fs.statSync("a.txt").size
来源：http://dali.smart0.xyz/Article/details/gt2ldfulpjy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gt2ekazhzbn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.aibaodan.cn/Article/details/gt2kfaklhxw.html

Ruby: File.size("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2trkhnhkj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cqqwz.cn/Article/details/gt2krkyhtuz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.feifeiyinyue.top/Article/details/gt2rbyqhadf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tduijpem.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cashguo.top/Article/details/gt2jcpnovsz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2cuexabed.html

TS:   path.extname("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2wjxfiblm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ydzc1.top/Article/details/gt2pynqepfg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2iifvjibb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ohrouzmj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gt2ufxqbjlk.html

[F11] 复制与移动文件
来源：http://dali.xziqi.cn/Article/details/gt2pguxvutd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2mwfbyemq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yonumen.top/Article/details/gt2wfesjkdk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gt2xgkkziam.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2suwlpuey.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aizwys.cn/Article/details/gt2guuinuhk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.kuanghao11.cn/Article/details/gt2djqpmzca.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gt2zjjzzbiu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lekumiqx.html

[F12] CSV 读写
来源：http://dali.cqqwz.cn/Article/details/gt2xuubxvog.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.andypj.xyz/Article/details/gt2vxwyawoe.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.guannengcc.top/Article/details/gt2qtjwwope.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ydzc1.top/Article/details/gt2zicfwmrq.html

TS:   // 同上
来源：http://dali.ybcxt.top/Article/details/gt2fcpcqwtx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cashguo.top/Article/details/gt2jasbcanl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhiwuduotai.top/Article/details/gt2evyqxjcu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhoulong.xyz/Article/details/gt2bkwvaulh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.daria6918.cn/Article/details/gt2gijtffim.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2yledfwjw.html

G. 面向对象
来源：http://dali.yongpay.top/Article/details/gt2fcmcgxir.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2fezaovif.html

[G01] 定义类
来源：http://dali.jinqigufen.top/Article/details/gt2ghpzfbxh.html

Py:   class User: pass
来源：http://dali.dianchejie.cn/Article/details/gt2cauxaujx.html

PHP:  class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hnkedvjv.html

JS:   class User {}
来源：http://dali.jiagoushi.top/Article/details/gt2mmkykndi.html

TS:   class User { name: string = ""; }
来源：http://dali.snrcjt.cn/Article/details/gt2mwakvgmh.html

Java: class User {}
来源：http://dali.cdnleiting.top/Article/details/gt2ziylejgo.html

Go:   type User struct { Name string }
来源：http://dali.svipenyu.cn/Article/details/gt2zwbecihr.html

Ruby: class User; end
来源：http://dali.xziqi.cn/Article/details/gt2aoznkaei.html

C#:   class User {}
来源：http://dali.fzhhl.top/Article/details/gt2ygonxkvt.html

[G02] 构造函数
来源：http://dali.cheryme.top/Article/details/gt2rfveftos.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yueranfly.top/Article/details/gt2biutqytj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ikzazhoq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2bvwqonoj.html

TS:   constructor(public name: string) {}
来源：http://dali.9152youxi.cn/Article/details/gt2eulstgmx.html

Java: User(String name) { this.name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dzjrbmtf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.tanke756.top/Article/details/gt2rwmdmckd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nanxuanxn.top/Article/details/gt2jaoonxhj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tianlin.xyz/Article/details/gt2qafbrqzx.html

[G03] 实例属性
来源：http://dali.andypj.xyz/Article/details/gt2qtpkpyty.html

Py:   self.name = "x"
来源：http://dali.feifeiyinyue.top/Article/details/gt2fbehsglx.html

PHP:  public string $name = "x";
来源：http://dali.c1oappe.top/Article/details/gt2rbgioenz.html

JS:   this.name = "x";
来源：http://dali.mhx1999.top/Article/details/gt2shwkmpsv.html

TS:   name: string = "x";
来源：http://dali.yj20258.top/Article/details/gt2kcnwhcfa.html

Java: private String name;
来源：http://dali.hfpthk.cn/Article/details/gt2mczjjlgd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hongshengwenyu.top/Article/details/gt2vanutyws.html

Ruby: @name = "x"
来源：http://dali.yueranfly.top/Article/details/gt2uzthfsem.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2avhuazbp.html

[G04] 定义方法
来源：http://dali.jqgfzy.top/Article/details/gt2deigcejd.html

Py:   def greet(self): return self.name
来源：http://dali.shangyingyoupin.top/Article/details/gt2nnsbgkuh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2kqpcaxow.html

JS:   greet() { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kqmunevu.html

TS:   greet(): string { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gt2foigwvfl.html

Java: String greet() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tdczcpnx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gt2vffmyksu.html

Ruby: def greet; @name; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2hdpiogmj.html

C#:   public string Greet() => Name;
来源：http://dali.0kj1m.cn/Article/details/gt2jjqploon.html

[G05] 继承
来源：http://dali.cashguo.top/Article/details/gt2igsuileo.html

Py:   class Admin(User): pass
来源：http://dali.pycfn.com/Article/details/gt2waqwwkhs.html

PHP:  class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gt2prwqywou.html

JS:   class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gt2mzwpmodt.html

TS:   class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gt2bqsixohh.html

Java: class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gt2uhapvjib.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.0kj1m.cn/Article/details/gt2cdkyiwgo.html

Ruby: class Admin < User; end
来源：http://dali.chenzaomai.com/Article/details/gt2ohfcvhkh.html

C#:   class Admin : User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yphjxkwz.html

[G06] 重写方法
来源：http://dali.chenzaomai.com/Article/details/gt2yhbwkiqp.html

Py:   def greet(self): return "admin"
来源：http://dali.yonumen.top/Article/details/gt2odavgywh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gt2bcatfcsm.html

JS:   greet() { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gt2laofxsaf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gt2aywsstqt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gt2sxrlfaix.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cheryme.top/Article/details/gt2npfkeijm.html

Ruby: def greet; "admin"; end
来源：http://dali.dashuyun.cn/Article/details/gt2lvjtysnn.html

C#:   public override string Greet() => "admin";
来源：http://dali.xylfe.cn/Article/details/gt2zjieicxr.html

[G07] 调用父类方法
来源：http://dali.zhixingplan.top/Article/details/gt2nohxcsxw.html

Py:   super().greet()
来源：http://dali.svipenyu.cn/Article/details/gt2fcczlkmm.html

PHP:  parent::greet();
来源：http://dali.yuanzhike.top/Article/details/gt2mcdrwhxj.html

JS:   super.greet();
来源：http://dali.aizwys.cn/Article/details/gt2scafueyw.html

TS:   super.greet();
来源：http://dali.0kj1m.cn/Article/details/gt2powkwpov.html

Java: super.greet();
来源：http://dali.jlsjyb.cn/Article/details/gt2rwozpdjc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.kuanghao11.cn/Article/details/gt2kkcoohxf.html

Ruby: super
来源：http://dali.chenzaomai.com/Article/details/gt2gikkxpmu.html

C#:   base.Greet();
来源：http://dali.wangshuangyany.cn/Article/details/gt2bnhnjobc.html

[G08] 静态方法与属性
来源：http://dali.wangshuangyany.cn/Article/details/gt2ccxpqrdh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hongshengwenyu.top/Article/details/gt2qgaizisk.html

PHP:  public static function f() {}
来源：http://dali.yvedp.cn/Article/details/gt2iewfrdjs.html

JS:   static f() {}
来源：http://dali.zhengqikj.top/Article/details/gt2ypozeujp.html

TS:   static f(): void {}
来源：http://dali.chenzaomai.com/Article/details/gt2nvnyvzvg.html

Java: static void f() {}
来源：http://dali.hysaishi.cn/Article/details/gt2qhgbnsgt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yanxiufei.cn/Article/details/gt2wuzvzubn.html

Ruby: def self.f; end
来源：http://dali.zhongyouzk.top/Article/details/gt2pcyyhwgk.html

C#:   public static void F() {}
来源：http://dali.gogol.net.cn/Article/details/gt2efuqqiym.html

[G09] 接口 / 抽象类
来源：http://dali.zhengqikj.top/Article/details/gt2ibdzuqmh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.daria6918.cn/Article/details/gt2fapllxtj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yvedp.cn/Article/details/gt2buqvtzak.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.dianchejie.cn/Article/details/gt2qosijwch.html

TS:   interface Shape { area(): number; }
来源：http://dali.sysykeji.top/Article/details/gt2pngqvnco.html

Java: interface Shape { double area(); }
来源：http://dali.guannengcc.top/Article/details/gt2ukworezy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.feifeiyinyue.top/Article/details/gt2dvzccuca.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jyoumei.cn/Article/details/gt2fagppvno.html

C#:   interface IShape { double Area(); }
来源：http://dali.xinyue.icu/Article/details/gt2idfrrkly.html

[G10] 访问控制
来源：http://dali.vqdsnc.cn/Article/details/gt2ooqomtyt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cashguo.top/Article/details/gt2cjxrcata.html

PHP:  public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gt2cqzmcwca.html

JS:   #private 字段；其余公开
来源：http://dali.zhiwuduotai.top/Article/details/gt2lldmdpbo.html

TS:   public / protected / private
来源：http://dali.xuanzx.com/Article/details/gt2cwnhbazz.html

Java: public / protected / private / 默认包级
来源：http://dali.guannengcc.top/Article/details/gt2ejerifyr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.guowangkeji.top/Article/details/gt2lshqcmzg.html

Ruby: public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gt2kavmavfc.html

C#:   public / protected / private / internal
来源：http://dali.xylfe.cn/Article/details/gt2veqejsre.html

[G11] getter / setter
来源：http://dali.hnqzz.top/Article/details/gt2ggtbusde.html

Py:   @property 与 @x.setter
来源：http://dali.sweek.top/Article/details/gt2oppossih.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.meibo888.top/Article/details/gt2attokpag.html

JS:   get name() { return this._name; }
来源：http://dali.zhixingplan.top/Article/details/gt2nsboiieq.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2wuovzmcx.html

Java: public String getName() { return name; }
来源：http://dali.hnqzz.top/Article/details/gt2rgmldxbl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gt2ixkgyxkz.html

Ruby: attr_accessor :name
来源：http://dali.jqgfzy.top/Article/details/gt2jycurxwk.html

C#:   public string Name { get; set; }
来源：http://dali.zhoulong.xyz/Article/details/gt2zhhotlum.html

[G12] 对象转字符串
来源：http://dali.dashuyun.cn/Article/details/gt2iuuzxugr.html

Py:   def __str__(self): return self.name
来源：http://dali.zhongyouzk.top/Article/details/gt2vctstxfn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gt2abqrebma.html

JS:   toString() { return this.name; }
来源：http://dali.cashguo.top/Article/details/gt2dkcueyht.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bgqeryla.html

Java: @Override public String toString() { return name; }
来源：http://dali.redwolf501.top/Article/details/gt2kbajppsq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gt2akdwrrcn.html

Ruby: def to_s; @name; end
来源：http://dali.tanke756.top/Article/details/gt2injzvcot.html

C#:   public override string ToString() => Name;
来源：http://dali.chenzaomai.com/Article/details/gt2uhqlhnnd.html

[G13] 判断对象类型
来源：http://dali.kuanghao11.cn/Article/details/gt2qxzbklud.html

Py:   isinstance(u, User)
来源：http://dali.zhixingplan.top/Article/details/gt2zmjdkcji.html

PHP:  $u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cbtdhvxe.html

JS:   u instanceof User
来源：http://dali.guannengcc.top/Article/details/gt2oezktvvp.html

TS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gt2qwsajyjo.html

Java: u instanceof User
来源：http://dali.ybcxt.top/Article/details/gt2caomzrju.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhengqikj.top/Article/details/gt2chvtgzoq.html

Ruby: u.is_a?(User)
来源：http://dali.daxiang520.top/Article/details/gt2ygarjmri.html

C#:   u is User
来源：http://dali.zdqjudy.top/Article/details/gt2nzqgumzl.html

[G14] 数据类 / record
来源：http://dali.hysaishi.cn/Article/details/gt2khoggnzu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.aizwys.cn/Article/details/gt2samswvay.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.iojbl.cn/Article/details/gt2vorewuvu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ydzc1.top/Article/details/gt2afjlzdfw.html

TS:   type User = { name: string; age: number };
来源：http://dali.cheryme.top/Article/details/gt2lbphivot.html

Java: record User(String name, int age) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2whagoxxf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.pengpengdd.cyou/Article/details/gt2eiqkhcdp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.dashuyun.cn/Article/details/gt2weisrhmt.html

C#:   record User(string Name, int Age);
来源：http://dali.jyoumei.cn/Article/details/gt2lllkhumc.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hguquxfo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sysykeji.top/Article/details/gt2rreqmkpb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xuanzx.com/Article/details/gt2drlzvmxf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.daxiang520.top/Article/details/gt2neczubcj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gaohongyu789.top/Article/details/gt2ilnfjwzt.html

Java: enum Color { RED, GREEN }
来源：http://dali.xuetiantiany.cn/Article/details/gt2eoiynnbk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cdnleiting.top/Article/details/gt2haqwffty.html

Ruby: Color = %i[red green].freeze
来源：http://dali.haohaochexian.top/Article/details/gt2meuzbicl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fzhhl.top/Article/details/gt2zgwooldu.html

[G16] 对象转数组 / 字典
来源：http://dali.yj20258.top/Article/details/gt2hxlfbrkj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj20258888.top/Article/details/gt2xtkzcijb.html

PHP:  get_object_vars($obj);
来源：http://dali.zhoulong.xyz/Article/details/gt2beeqrpcs.html

JS:   Object.entries(obj)
来源：http://dali.ivvv.top/Article/details/gt2ufuhkqcm.html

TS:   Object.entries(obj)
来源：http://dali.ybcxt.top/Article/details/gt2ujirzsxx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cucudq.cn/Article/details/gt2uzuywxzj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.redwolf501.top/Article/details/gt2kehcopfl.html

Ruby: obj.instance_variables
来源：http://dali.yj20258888.top/Article/details/gt2nupxtvxe.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xinyue.icu/Article/details/gt2kqehpjxh.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2entaczzb.html


<!-- 参考信息 -->