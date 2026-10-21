代发 wailian999

JS:   s.split(/\r?\n/)
来源：http://dali.zhoulong.xyz/Article/details/gtobezwxbf.html

TS:   s.split(/\r?\n/)
来源：http://dali.yuxming.cn/Article/details/gtbnejlxeq.html

Java: s.lines().toList()
来源：http://dali.tanke756.top/Article/details/gtyhqjagsp.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj20258.top/Article/details/gtvtcwoabh.html

Ruby: s.lines
来源：http://dali.nanxinkj.top/Article/details/gtjzlxtnzs.html

C#:   s.Split('\n')
来源：http://dali.zhoulong.xyz/Article/details/gtcidbvjbu.html

[E20] 判断字符串是否为空
来源：http://dali.xuetiantiany.cn/Article/details/gtsurfjlrf.html

Py:   if not s:
来源：http://dali.kuanghao11.cn/Article/details/gtikeemnph.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shanyushiyangtech.top/Article/details/gtfdtxonbk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cdnleiting.top/Article/details/gttfydetaz.html

TS:   if (s === "") {}
来源：http://dali.zhengqikj.top/Article/details/gtighltbgi.html

Java: if (s.isEmpty()) {}
来源：http://dali.xuetiantiany.cn/Article/details/gthqkdjkfp.html

Go:   if s == "" {}
来源：http://dali.sufxvd.cn/Article/details/gthtqmxeym.html

Ruby: if s.empty?
来源：http://dali.vqdsnc.cn/Article/details/gtykfuzque.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.aizwys.cn/Article/details/gtchapoqrx.html

[E21] 超长截断加省略号
来源：http://dali.chenlongwang.top/Article/details/gtesktpkcc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sufxvd.cn/Article/details/gtcylrjtvr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinqigufen.top/Article/details/gtvefxfvmn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtmimejzsi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtztlsxsxn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwhcxsliu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zycfv.cn/Article/details/gtcdlbsfof.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtjrnojtkq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jianghu66.top/Article/details/gtgzxpyfbh.html

[E22] 字节长度与字符长度
来源：http://dali.cucudq.cn/Article/details/gtahgustin.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yonumen.top/Article/details/gttxzsepzs.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinqigufen.top/Article/details/gtfrmamave.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gtvyeuyzhp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.316326.xyz/Article/details/gtqcputdxy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.smart0.xyz/Article/details/gtxzxtzjjy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.wangshuangyany.cn/Article/details/gtnergcydv.html

Ruby: s.bytesize;  s.length
来源：http://dali.yj20258.top/Article/details/gtbwpoefqg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yvedp.cn/Article/details/gtwfpgkdxt.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtcwxpglnm.html

F. 文件与目录
来源：http://dali.ppjwa.cn/Article/details/gtrmjppadg.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhnmajcl.html

[F01] 读取整个文件
来源：http://dali.gaohongyu789.top/Article/details/gtwshizykb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.aibaodan.cn/Article/details/gtpleqwacj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yonumen.top/Article/details/gtugdijvtv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhongyouzk.top/Article/details/gtpwxamjjj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.redwolf501.top/Article/details/gtvdjosvxm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gtwetbkwbf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhongyouzk.top/Article/details/gtljbyhpzr.html

Ruby: File.read("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtbhfhxugi.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtrxlvfuwl.html

[F02] 逐行读取文件
来源：http://dali.jqgfzy.top/Article/details/gtaslndlfi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.dianchejie.cn/Article/details/gtqxwdjese.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtonecuwuu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgfzy.top/Article/details/gtgxqnpket.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.c1oappe.top/Article/details/gtnemhhpge.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sysykeji.top/Article/details/gtnannifge.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gzhubu.top/Article/details/gthecomrwh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgivqupnd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yanxiufei.cn/Article/details/gtkavkzqcu.html

[F03] 写入文件（覆盖）
来源：http://dali.iojbl.cn/Article/details/gtumulmvqx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsrfqvxao.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nanxuanxn.top/Article/details/gtjhhnbdxm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgdrvcorq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.316326.xyz/Article/details/gtacdmekdj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yongpay.top/Article/details/gtpqmkgstv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cucudq.cn/Article/details/gthitgakyn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtprrypsfy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yvedp.cn/Article/details/gtlbtagrpa.html

[F04] 追加写入文件
来源：http://dali.bjfxy.top/Article/details/gtknrchvnd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.birdmap.top/Article/details/gtkjkahsrf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shanyushiyangtech.top/Article/details/gttkuumrxg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shuidangran.top/Article/details/gtqiqtgolf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258.top/Article/details/gtqdwlbmqi.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.dianchejie.cn/Article/details/gtkynupibd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tianlin.xyz/Article/details/gtxzznhzez.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zdqjudy.top/Article/details/gtiensspie.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hnqzz.top/Article/details/gtiuxwigjt.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhoulong.xyz/Article/details/gtmxjuqsux.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tian-w.cn/Article/details/gtbzcbzpvn.html

PHP:  file_exists("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtyntmyyui.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtexrzlfnq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtcybauyft.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtgnnemehn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jyoumei.cn/Article/details/gttesdpqkt.html

Ruby: File.exist?("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtnnalvzco.html

C#:   File.Exists("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtwghrtkws.html

[F06] 删除文件
来源：http://dali.yueranfly.top/Article/details/gtmrmllizb.html

Py:   os.remove("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtfwavhrlg.html

PHP:  unlink("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtllijytbu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtpxftppxj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtfdhfonid.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gtzrbwtvnb.html

Go:   os.Remove("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtaxjsmflx.html

Ruby: File.delete("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gttxzammdu.html

C#:   File.Delete("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtsybxzibb.html

[F07] 创建目录（含多级）
来源：http://dali.yanxiufei.cn/Article/details/gtmkhyldfp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.9152youxi.cn/Article/details/gtlmiptuat.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ehwqpu.com/Article/details/gtqgempnsq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj202588.top/Article/details/gtzhdpxiuf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cqqwz.cn/Article/details/gteyqbvcua.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tian-w.cn/Article/details/gtrbuyayha.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinqigufen.top/Article/details/gtwafuycty.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hongshengwenyu.top/Article/details/gtjvztgllg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hfpthk.cn/Article/details/gtvivvfmjo.html

[F08] 遍历目录
来源：http://dali.yueranfly.top/Article/details/gtupcqvdlz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jqgufenzy.top/Article/details/gtcnzskiuj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gaohongyu789.top/Article/details/gtypkygmfj.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzjasurnl.html

TS:   fs.readdirSync("dir")
来源：http://dali.havefunace.top/Article/details/gtvebmbjng.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.fzhhl.top/Article/details/gtozgnwlvp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xuanzx.com/Article/details/gtotweecoi.html

Ruby: Dir.children("dir")
来源：http://dali.pycfn.com/Article/details/gtupylmltr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gotoacloud.top/Article/details/gtmcljyfhl.html

[F09] 获取文件大小
来源：http://dali.daria6918.cn/Article/details/gtdtzekeie.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtlzifknkl.html

PHP:  filesize("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtayoxroez.html

JS:   fs.statSync("a.txt").size
来源：http://dali.chenzaomai.com/Article/details/gtuhxnzyap.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sxryk.cn/Article/details/gtayuwcreh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gtjclcsogy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.daria6918.cn/Article/details/gtcixmbkvc.html

Ruby: File.size("a.txt")
来源：http://dali.meibo888.top/Article/details/gtnyawobtr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.kuanghao11.cn/Article/details/gtixrvxkej.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjachmdq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtksdmwyfj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yvedp.cn/Article/details/gtbqobeape.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtmblxbebk.html

TS:   path.extname("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtlsliplkh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.tianlin.xyz/Article/details/gtrzmaehfz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtjcyllshl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtibemvfys.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtmcpopgdz.html

[F11] 复制与移动文件
来源：http://dali.zdqjudy.top/Article/details/gtwvinqhme.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gtqsnfjcxh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtiwutgouv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtmjudctgs.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtqoghgoot.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zdqjudy.top/Article/details/gtfnuqgdmf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xuetiantiany.cn/Article/details/gtoysyjhqf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtirfdcckg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhixingplan.top/Article/details/gtcynyiuwo.html

[F12] CSV 读写
来源：http://dali.jinqigufen.top/Article/details/gtnxkqlvcc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hammf.cn/Article/details/gtvakpcttu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.iojbl.cn/Article/details/gtbkjsjazd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenlongwang.top/Article/details/gtslomhaci.html

TS:   // 同上
来源：http://dali.hywenlv.cn/Article/details/gtzdhrbzws.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nanxinkj.top/Article/details/gtfzdbbuvu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ydzc1.top/Article/details/gtldbhermi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sysykeji.top/Article/details/gtflfvcczv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jlsjyb.cn/Article/details/gtonbrygvr.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtxzohxidw.html

G. 面向对象
来源：http://dali.jinqigfzy.top/Article/details/gtesrrctpg.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtqmdipqmf.html

[G01] 定义类
来源：http://dali.dashuyun.cn/Article/details/gtkvzurugz.html

Py:   class User: pass
来源：http://dali.0kj1m.cn/Article/details/gtmycqnzek.html

PHP:  class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtxfhynbjs.html

JS:   class User {}
来源：http://dali.tianlin.xyz/Article/details/gtskphkzwt.html

TS:   class User { name: string = ""; }
来源：http://dali.hnqzz.top/Article/details/gthkpkefli.html

Java: class User {}
来源：http://dali.yonumen.top/Article/details/gtyvgmzuoo.html

Go:   type User struct { Name string }
来源：http://dali.jinqigfzy.top/Article/details/gtksfowgrd.html

Ruby: class User; end
来源：http://dali.cheryme.top/Article/details/gtkeghviqt.html

C#:   class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtufssszpy.html

[G02] 构造函数
来源：http://dali.ydzc1.top/Article/details/gtmxtelixs.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xuanzx.com/Article/details/gtvpqmkxut.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhoulong.xyz/Article/details/gtyccexrov.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ydzc1.top/Article/details/gtgkvnsbce.html

TS:   constructor(public name: string) {}
来源：http://dali.ydzc1.top/Article/details/gtuyqwwjeo.html

Java: User(String name) { this.name = name; }
来源：http://dali.mhx1999.top/Article/details/gtqswyrbcg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zdqjudy.top/Article/details/gtagfzoclo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xuanzx.com/Article/details/gtozrliysl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenlongwang.top/Article/details/gtzyeckikl.html

[G03] 实例属性
来源：http://dali.jiagoushi.top/Article/details/gthaoqyqnl.html

Py:   self.name = "x"
来源：http://dali.kuanghao11.cn/Article/details/gtyuifnjgn.html

PHP:  public string $name = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtcavtrgpx.html

JS:   this.name = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtxbpncqhl.html

TS:   name: string = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtstmpryqd.html

Java: private String name;
来源：http://dali.c1oappe.top/Article/details/gteebmipst.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.smart0.xyz/Article/details/gtsribdavg.html

Ruby: @name = "x"
来源：http://dali.cheryme.top/Article/details/gtwklwpids.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.316326.xyz/Article/details/gthqhjpztm.html

[G04] 定义方法
来源：http://dali.yuxming.cn/Article/details/gtjogvamur.html

Py:   def greet(self): return self.name
来源：http://dali.yj202588.top/Article/details/gtwaqxtfgo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtfvayctlb.html

JS:   greet() { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtchvhbnkc.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gtyztnwipk.html

Java: String greet() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtrnplohql.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gttyypwiao.html

Ruby: def greet; @name; end
来源：http://dali.ehwqpu.com/Article/details/gtgfujbasz.html

C#:   public string Greet() => Name;
来源：http://dali.birdmap.top/Article/details/gtklqsqreh.html

[G05] 继承
来源：http://dali.jlsjyb.cn/Article/details/gtpjtzovux.html

Py:   class Admin(User): pass
来源：http://dali.nanxuanxn.top/Article/details/gtqwroqlyl.html

PHP:  class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gtfrwbhwlo.html

JS:   class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtasdsalip.html

TS:   class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gteqcrkhwz.html

Java: class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gthudtfpgp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.birdmap.top/Article/details/gtflcnyftj.html

Ruby: class Admin < User; end
来源：http://dali.sysykeji.top/Article/details/gttkuzkpjw.html

C#:   class Admin : User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtqoroywvo.html

[G06] 重写方法
来源：http://dali.smart0.xyz/Article/details/gtvhkbdmxz.html

Py:   def greet(self): return "admin"
来源：http://dali.svipenyu.cn/Article/details/gtwulekiee.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gtavuztavm.html

JS:   greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtojgbwwgl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gtcmrbniuc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gtcmqztclj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hysaishi.cn/Article/details/gtogxchgiu.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigfzy.top/Article/details/gtzmtpkkix.html

C#:   public override string Greet() => "admin";
来源：http://dali.nanxinkj.top/Article/details/gtvvexsveq.html

[G07] 调用父类方法
来源：http://dali.shzxlz.cn/Article/details/gtvfzapjhv.html

Py:   super().greet()
来源：http://dali.chenzaomai.com/Article/details/gtujnxkmxp.html

PHP:  parent::greet();
来源：http://dali.hysaishi.cn/Article/details/gtrcnwxagg.html

JS:   super.greet();
来源：http://dali.zhixingplan.top/Article/details/gtprexruag.html

TS:   super.greet();
来源：http://dali.yuanzhike.top/Article/details/gtefmfdmop.html

Java: super.greet();
来源：http://dali.yj202588.top/Article/details/gthfmwdgsc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.bjfxy.top/Article/details/gtymjgsvtz.html

Ruby: super
来源：http://dali.guowangkeji.top/Article/details/gtcfvsvzta.html

C#:   base.Greet();
来源：http://dali.ivvv.top/Article/details/gtilmdtdzh.html

[G08] 静态方法与属性
来源：http://dali.redwolf501.top/Article/details/gttsjthotr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sweek.top/Article/details/gtzzwrhdtb.html

PHP:  public static function f() {}
来源：http://dali.yvedp.cn/Article/details/gtytnlpcmr.html

JS:   static f() {}
来源：http://dali.ehwqpu.com/Article/details/gteprcdyhx.html

TS:   static f(): void {}
来源：http://dali.birdmap.top/Article/details/gtigfsousr.html

Java: static void f() {}
来源：http://dali.jianghu66.top/Article/details/gtknwaruum.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.vqdsnc.cn/Article/details/gthvgocevq.html

Ruby: def self.f; end
来源：http://dali.quarkkingdee.top/Article/details/gtgdzutcpm.html

C#:   public static void F() {}
来源：http://dali.jqgfzy.top/Article/details/gtjzzffieu.html

[G09] 接口 / 抽象类
来源：http://dali.daria6918.cn/Article/details/gterdqbuit.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xinyue.icu/Article/details/gtdgckbkxe.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdgdryknn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj20258888.top/Article/details/gtmwkpakaw.html

TS:   interface Shape { area(): number; }
来源：http://dali.nanxuanxn.top/Article/details/gtkscvyfsx.html

Java: interface Shape { double area(); }
来源：http://dali.zhongyouzk.top/Article/details/gtmpkzhueg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ivvv.top/Article/details/gtedhmaqxk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jqgufenzy.top/Article/details/gtjhlslnvw.html

C#:   interface IShape { double Area(); }
来源：http://dali.smart0.xyz/Article/details/gttcxyfmee.html

[G10] 访问控制
来源：http://dali.zycfv.cn/Article/details/gtvsittqqw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jlsjyb.cn/Article/details/gtautiorou.html

PHP:  public / protected / private
来源：http://dali.fengsongda.top/Article/details/gtacoiwhaa.html

JS:   #private 字段；其余公开
来源：http://dali.hywenlv.cn/Article/details/gtlwulurwx.html

TS:   public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gtynglkqxz.html

Java: public / protected / private / 默认包级
来源：http://dali.jqgufenzy.top/Article/details/gtznbvizem.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tianlin.xyz/Article/details/gtpmdcfbqt.html

Ruby: public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gtsjlwhcgq.html

C#:   public / protected / private / internal
来源：http://dali.bjfxy.top/Article/details/gthexyregh.html

[G11] getter / setter
来源：http://dali.sxryk.cn/Article/details/gtlzkvabsg.html

Py:   @property 与 @x.setter
来源：http://dali.wangdashe.top/Article/details/gtsnzjocfa.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtuqhoeccp.html

JS:   get name() { return this._name; }
来源：http://dali.redwolf501.top/Article/details/gtdlbuvuff.html

TS:   get name(): string { return this._name; }
来源：http://dali.tianlin.xyz/Article/details/gtebsshqcq.html

Java: public String getName() { return name; }
来源：http://dali.yvedp.cn/Article/details/gtxhjczrai.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gtkmamiaso.html

Ruby: attr_accessor :name
来源：http://dali.meibo888.top/Article/details/gtfkownspd.html

C#:   public string Name { get; set; }
来源：http://dali.zhoulong.xyz/Article/details/gtcuaqmqpt.html

[G12] 对象转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtthsdvfzs.html

Py:   def __str__(self): return self.name
来源：http://dali.jqgufenzy.top/Article/details/gtzrmysldf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gtqigyftou.html

JS:   toString() { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtasoofazh.html

TS:   toString(): string { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gtiyzoictf.html

Java: @Override public String toString() { return name; }
来源：http://dali.guannengcc.top/Article/details/gtddmelmrl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gtnkzqsemx.html

Ruby: def to_s; @name; end
来源：http://dali.sysykeji.top/Article/details/gtbhtqpjou.html

C#:   public override string ToString() => Name;
来源：http://dali.iojbl.cn/Article/details/gtbmpssgit.html

[G13] 判断对象类型
来源：http://dali.smart0.xyz/Article/details/gtwnloqqoz.html

Py:   isinstance(u, User)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfkkeidvp.html

PHP:  $u instanceof User
来源：http://dali.ybcxt.top/Article/details/gtfcgyyiep.html

JS:   u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtgcbrrywy.html

TS:   u instanceof User
来源：http://dali.wangdashe.top/Article/details/gtuortvxrb.html

Java: u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtgsvzwsyv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gaohongyu789.top/Article/details/gtvwimmjyp.html

Ruby: u.is_a?(User)
来源：http://dali.pengpengdd.cyou/Article/details/gtpadrvwqs.html

C#:   u is User
来源：http://dali.cashguo.top/Article/details/gtniykksmd.html

[G14] 数据类 / record
来源：http://dali.zhengqikj.top/Article/details/gthfaucxmg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gaohongyu789.top/Article/details/gtbbnxafif.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yj20258888.top/Article/details/gtxakgmgrr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shzxlz.cn/Article/details/gtumtrnizr.html

TS:   type User = { name: string; age: number };
来源：http://dali.0kj1m.cn/Article/details/gtzlllnzmz.html

Java: record User(String name, int age) {}
来源：http://dali.zhoulong.xyz/Article/details/gtauaxnhgv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinqigufen.top/Article/details/gtnpjbqgzh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenzaomai.com/Article/details/gtnpywvpxb.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxuanxn.top/Article/details/gtjmygfrlm.html

[G15] 枚举
来源：http://dali.9152youxi.cn/Article/details/gtxawvxajk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hfpthk.cn/Article/details/gtwalhlxii.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jqgufenzy.top/Article/details/gtssxpoiwt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj202588.top/Article/details/gtxmocbtdj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shuidangran.top/Article/details/gthmbmnbkk.html

Java: enum Color { RED, GREEN }
来源：http://dali.andypj.xyz/Article/details/gtrdkgroqu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.haohaochexian.top/Article/details/gtakrkkcqn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shuidangran.top/Article/details/gtwfmjkmgr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fengsongda.top/Article/details/gtoppaesjt.html

[G16] 对象转数组 / 字典
来源：http://dali.xuetiantiany.cn/Article/details/gtayokdedl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenzaomai.com/Article/details/gtafxuzkak.html

PHP:  get_object_vars($obj);
来源：http://dali.andypj.xyz/Article/details/gtrmqptbuo.html

JS:   Object.entries(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtjmrcxgib.html

TS:   Object.entries(obj)
来源：http://dali.daxiang520.top/Article/details/gttviwevol.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhiwuduotai.top/Article/details/gtlrgmwhhe.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gotoacloud.top/Article/details/gtfeekfvsd.html

Ruby: obj.instance_variables
来源：http://dali.snrcjt.cn/Article/details/gtbkvtgqai.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.wangshuangyany.cn/Article/details/gtrhzjevdw.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtxrhqsqgw.html

H. 异常与错误处理
来源：http://dali.yj20258.top/Article/details/gtmexzukpq.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtnqbkggcw.html

[H01] try / catch 基础
来源：http://dali.gzhubu.top/Article/details/gtynoilfsw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.birdmap.top/Article/details/gtdqgwqjfy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.iojbl.cn/Article/details/gtwkxqcfop.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gtuayabtzy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hywenlv.cn/Article/details/gtcdknisri.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yanxiufei.cn/Article/details/gtglzqrojz.html


<!-- 参考信息 -->