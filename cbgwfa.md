代发 wailian999

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.andypj.xyz/Article/details/gt2cwztdldw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hywenlv.cn/Article/details/gt2lyrgcfco.html

TS:   if (s === "") {}
来源：http://dali.gaohongyu789.top/Article/details/gt2kcbpemxx.html

Java: if (s.isEmpty()) {}
来源：http://dali.aizwys.cn/Article/details/gt2qfrkdxwd.html

Go:   if s == "" {}
来源：http://dali.9152youxi.cn/Article/details/gt2vturijwe.html

Ruby: if s.empty?
来源：http://dali.nanxinkj.top/Article/details/gt2qekhzant.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.haohaochexian.top/Article/details/gt2cihczbgl.html

[E21] 超长截断加省略号
来源：http://dali.xuanzx.com/Article/details/gt2oxohozlq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hnxiangtu.top/Article/details/gt2edozfvho.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qfhpbkcu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gt2kunvgbdf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gt2slyieyrz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gt2psaopmnt.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.nanxuanxn.top/Article/details/gt2mzsjuwyo.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gt2dxsfzfzy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ttkdjwdy.html

[E22] 字节长度与字符长度
来源：http://dali.zhengqikj.top/Article/details/gt2lxhwqzxv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2vdskcxys.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gt2nmrepfbt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.9152youxi.cn/Article/details/gt2ggcljkur.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.haohaochexian.top/Article/details/gt2dgqlrrnw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sweek.top/Article/details/gt2vqkvfrrw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zycfv.cn/Article/details/gt2leaypszr.html

Ruby: s.bytesize;  s.length
来源：http://dali.fengsongda.top/Article/details/gt2zfbyzxfh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yuxming.cn/Article/details/gt2bhrcqplg.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2lrfypdin.html

F. 文件与目录
来源：http://dali.cqqwz.cn/Article/details/gt2ypewwfzx.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2qmmzcctu.html

[F01] 读取整个文件
来源：http://dali.redwolf501.top/Article/details/gt2crvfdcua.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hnqzz.top/Article/details/gt2pzpvbprz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2adyebkxo.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hongshengwenyu.top/Article/details/gt2kqbdmlol.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ydzc1.top/Article/details/gt2egtesrxu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gt2ufbdlsdi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.0kj1m.cn/Article/details/gt2suizcbst.html

Ruby: File.read("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2qkegehrd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2vqcbmocs.html

[F02] 逐行读取文件
来源：http://dali.pycfn.com/Article/details/gt2hftmjdbi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yongpay.top/Article/details/gt2vptkbsfj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.0kj1m.cn/Article/details/gt2pbwxqzrg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hywenlv.cn/Article/details/gt2cjnxxgxb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shzxlz.cn/Article/details/gt2yvoxkmvi.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nwbrower.top/Article/details/gt2onfqqmng.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhongyouzk.top/Article/details/gt2mdjxwgzr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uivpobpu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2xeghwjsp.html

[F03] 写入文件（覆盖）
来源：http://dali.haohaochexian.top/Article/details/gt2cqdlwmfq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hnqzz.top/Article/details/gt2eiiwmboi.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yonumen.top/Article/details/gt2nanygoza.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gt2cyhcjchu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gt2cnnfidfo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.c1oappe.top/Article/details/gt2pawovofw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.bjfxy.top/Article/details/gt2amirenkz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hnxiangtu.top/Article/details/gt2damexkvk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cheryme.top/Article/details/gt2pzxextbs.html

[F04] 追加写入文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2ftafnozc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yvedp.cn/Article/details/gt2vwrfhoeu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.mhx1999.top/Article/details/gt2zhytszra.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2mztvchpf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fengsongda.top/Article/details/gt2aczvmuqw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.iojbl.cn/Article/details/gt2kkbijwfn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gt2qwtuxhnm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yongpay.top/Article/details/gt2pxlrujem.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yangfankeji.com/Article/details/gt2wrqhkuwk.html

[F05] 判断文件或目录是否存在
来源：http://dali.daria6918.cn/Article/details/gt2iklmrfwc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shuidangran.top/Article/details/gt2nynthckx.html

PHP:  file_exists("a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2svgguypm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2aymcfmbr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2zlkpszwl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gt2gzdtwxsd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.pycfn.com/Article/details/gt2iddhczpk.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2znagaqbc.html

C#:   File.Exists("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2fcuzctok.html

[F06] 删除文件
来源：http://dali.iojbl.cn/Article/details/gt2srajefnc.html

Py:   os.remove("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2aeadcjks.html

PHP:  unlink("a.txt");
来源：http://dali.ivvv.top/Article/details/gt2mlkhtjqy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2imafauin.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2yutnpvwm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gt2flsafzau.html

Go:   os.Remove("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2wvwysytg.html

Ruby: File.delete("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2vprvyizs.html

C#:   File.Delete("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2swwelzgu.html

[F07] 创建目录（含多级）
来源：http://dali.zycfv.cn/Article/details/gt2htdfbljd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hfpthk.cn/Article/details/gt2zpavgqbi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nanxuanxn.top/Article/details/gt2azjlwjdc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nwbrower.top/Article/details/gt2ylvhvnms.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fengsongda.top/Article/details/gt2yafsqfix.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.daria6918.cn/Article/details/gt2nploejsn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sweek.top/Article/details/gt2dbpjweet.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jianghu66.top/Article/details/gt2bqcglwea.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.meibo888.top/Article/details/gt2fuqkegfj.html

[F08] 遍历目录
来源：http://dali.zdqjudy.top/Article/details/gt2ocaaycee.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.andypj.xyz/Article/details/gt2szrnjlea.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sxryk.cn/Article/details/gt2bydkinse.html

JS:   fs.readdirSync("dir")
来源：http://dali.9152youxi.cn/Article/details/gt2tddklglx.html

TS:   fs.readdirSync("dir")
来源：http://dali.redwolf501.top/Article/details/gt2rzvkdkze.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.haohaochexian.top/Article/details/gt2dxihbrap.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.guannengcc.top/Article/details/gt2qrlxrskp.html

Ruby: Dir.children("dir")
来源：http://dali.vqdsnc.cn/Article/details/gt2lxvrslej.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hysaishi.cn/Article/details/gt2zkobhsem.html

[F09] 获取文件大小
来源：http://dali.hnqzz.top/Article/details/gt2tezayecf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2nutitzbe.html

PHP:  filesize("a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2yfjzrktz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.fengsongda.top/Article/details/gt2kjqjsdtq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cheryme.top/Article/details/gt2rjesdcqh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gt2fyirgqgw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cashguo.top/Article/details/gt2eopgsfwr.html

Ruby: File.size("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2masdfmue.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.fzhhl.top/Article/details/gt2ujyoguhf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ppjwa.cn/Article/details/gt2hxcqudhy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2srzbvkkz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2qzibhtxn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2lofkratd.html

TS:   path.extname("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2esttnocs.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenjidiqi.icu/Article/details/gt2gcdpmjhm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2laeeikzh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mlvcelnl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2ilzdosql.html

[F11] 复制与移动文件
来源：http://dali.xziqi.cn/Article/details/gt2tddubwwv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gt2vthgvmsh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2akfqzdhb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gt2fsovdlzw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uezkjyie.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hfpthk.cn/Article/details/gt2crccerid.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.snrcjt.cn/Article/details/gt2egfrbkns.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gt2nxffsiih.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gaohongyu789.top/Article/details/gt2aigurkkb.html

[F12] CSV 读写
来源：http://dali.aizwys.cn/Article/details/gt2cbjjmwsl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tanke756.top/Article/details/gt2kavfcpfo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj20258.top/Article/details/gt2unwlywsv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tanke756.top/Article/details/gt2tikwzdrp.html

TS:   // 同上
来源：http://dali.gotoacloud.top/Article/details/gt2umtmouxf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nwbrower.top/Article/details/gt2ghdsdhuf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinqigfzy.top/Article/details/gt2yjawosvn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hnqzz.top/Article/details/gt2syfpyzym.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.fzhhl.top/Article/details/gt2xxjpqpfi.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2sqrtgigc.html

G. 面向对象
来源：http://dali.ivvv.top/Article/details/gt2tmnzauyj.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2sszgrfgh.html

[G01] 定义类
来源：http://dali.gogol.net.cn/Article/details/gt2appbmyeq.html

Py:   class User: pass
来源：http://dali.cdnleiting.top/Article/details/gt2jgjqygck.html

PHP:  class User {}
来源：http://dali.ppjwa.cn/Article/details/gt2rjnhmyuv.html

JS:   class User {}
来源：http://dali.dashuyun.cn/Article/details/gt2jsvsycfb.html

TS:   class User { name: string = ""; }
来源：http://dali.dianchejie.cn/Article/details/gt2opzobdlc.html

Java: class User {}
来源：http://dali.yongpay.top/Article/details/gt2ykfbsaja.html

Go:   type User struct { Name string }
来源：http://dali.quarkkingdee.top/Article/details/gt2ymgnzelr.html

Ruby: class User; end
来源：http://dali.snrcjt.cn/Article/details/gt2wxjrjqal.html

C#:   class User {}
来源：http://dali.shzxlz.cn/Article/details/gt2bcbypuic.html

[G02] 构造函数
来源：http://dali.yueranfly.top/Article/details/gt2pxgmdhqz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xziqi.cn/Article/details/gt2vyqxvfcq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yuxming.cn/Article/details/gt2jlrvyjua.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.fengsongda.top/Article/details/gt2twvmegzf.html

TS:   constructor(public name: string) {}
来源：http://dali.0kj1m.cn/Article/details/gt2fjruwcfn.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2skfcnlpc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sxryk.cn/Article/details/gt2deggtbmd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ymmikuzu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tianlin.xyz/Article/details/gt2eqevebqw.html

[G03] 实例属性
来源：http://dali.yj20258.top/Article/details/gt2pqcqggbo.html

Py:   self.name = "x"
来源：http://dali.bjfxy.top/Article/details/gt2uujgcaqn.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kbeyooag.html

JS:   this.name = "x";
来源：http://dali.dianchejie.cn/Article/details/gt2xhbmbdhb.html

TS:   name: string = "x";
来源：http://dali.shuidangran.top/Article/details/gt2vihchjwn.html

Java: private String name;
来源：http://dali.xylfe.cn/Article/details/gt2pesbsmik.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tianlin.xyz/Article/details/gt2leeyrkjm.html

Ruby: @name = "x"
来源：http://dali.jqgufenzy.top/Article/details/gt2vpqnhqhp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.smart0.xyz/Article/details/gt2alehsaiw.html

[G04] 定义方法
来源：http://dali.yanxiufei.cn/Article/details/gt2jlbmmpcd.html

Py:   def greet(self): return self.name
来源：http://dali.jyoumei.cn/Article/details/gt2qzfjudaf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gt2ursasmmv.html

JS:   greet() { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gt2szeaihqx.html

TS:   greet(): string { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2avrrxsjb.html

Java: String greet() { return name; }
来源：http://dali.redwolf501.top/Article/details/gt2ayhrzrlj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gt2esdcjplg.html

Ruby: def greet; @name; end
来源：http://dali.jinqigfzy.top/Article/details/gt2qtdwyvdt.html

C#:   public string Greet() => Name;
来源：http://dali.hongshengwenyu.top/Article/details/gt2nchimerz.html

[G05] 继承
来源：http://dali.tanke756.top/Article/details/gt2yatgeciq.html

Py:   class Admin(User): pass
来源：http://dali.xylfe.cn/Article/details/gt2oukxuamn.html

PHP:  class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gt2wgpsvftm.html

JS:   class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gt2svuqbtmd.html

TS:   class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2uoomszxg.html

Java: class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gt2xwfnzagm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cashguo.top/Article/details/gt2xxsoflix.html

Ruby: class Admin < User; end
来源：http://dali.vqdsnc.cn/Article/details/gt2wbwsgoyy.html

C#:   class Admin : User {}
来源：http://dali.tanke756.top/Article/details/gt2egvoomph.html

[G06] 重写方法
来源：http://dali.wangdashe.top/Article/details/gt2cdhlqvib.html

Py:   def greet(self): return "admin"
来源：http://dali.yj20258.top/Article/details/gt2urizwhxq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gt2sfokblxf.html

JS:   greet() { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gt2zudkncwu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2hcggvezh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gt2kevttpzz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.andypj.xyz/Article/details/gt2trpxheze.html

Ruby: def greet; "admin"; end
来源：http://dali.dianchejie.cn/Article/details/gt2fvcsksfm.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oqcfrwbl.html

[G07] 调用父类方法
来源：http://dali.nanxuanxn.top/Article/details/gt2ushalimo.html

Py:   super().greet()
来源：http://dali.haohaochexian.top/Article/details/gt2tziurrlt.html

PHP:  parent::greet();
来源：http://dali.aizwys.cn/Article/details/gt2zepncjeq.html

JS:   super.greet();
来源：http://dali.sufxvd.cn/Article/details/gt2pidwoomt.html

TS:   super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gt2glldwtcy.html

Java: super.greet();
来源：http://dali.jinqigfzy.top/Article/details/gt2egrwvgld.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sufxvd.cn/Article/details/gt2ttzhibtp.html

Ruby: super
来源：http://dali.shangyingyoupin.top/Article/details/gt2aoutjken.html

C#:   base.Greet();
来源：http://dali.xinyue.icu/Article/details/gt2qbpgohof.html

[G08] 静态方法与属性
来源：http://dali.meibo888.top/Article/details/gt2mkadyvyg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj20258.top/Article/details/gt2dfmenzxw.html

PHP:  public static function f() {}
来源：http://dali.svipenyu.cn/Article/details/gt2cpzqpuer.html

JS:   static f() {}
来源：http://dali.meibo888.top/Article/details/gt2eacaoqnc.html

TS:   static f(): void {}
来源：http://dali.shuidangran.top/Article/details/gt2unxtdsvs.html

Java: static void f() {}
来源：http://dali.mhx1999.top/Article/details/gt2ftepoose.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yueranfly.top/Article/details/gt2smubbvsx.html

Ruby: def self.f; end
来源：http://dali.ivvv.top/Article/details/gt2zogmfzvf.html

C#:   public static void F() {}
来源：http://dali.dianchejie.cn/Article/details/gt2aqlfhxnu.html

[G09] 接口 / 抽象类
来源：http://dali.dianchejie.cn/Article/details/gt2bzccxgbk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cashguo.top/Article/details/gt2piuvufaz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ytcltkpj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tian-w.cn/Article/details/gt2nbfvxxrj.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinqigufen.top/Article/details/gt2jjttmqkf.html

Java: interface Shape { double area(); }
来源：http://dali.andypj.xyz/Article/details/gt2scxqtbig.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xalpbmsr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2ylseefxt.html

C#:   interface IShape { double Area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vxnhuxky.html

[G10] 访问控制
来源：http://dali.snrcjt.cn/Article/details/gt2btpkthyu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xuetiantiany.cn/Article/details/gt2xxezvjls.html

PHP:  public / protected / private
来源：http://dali.hnqzz.top/Article/details/gt2tyowcmju.html

JS:   #private 字段；其余公开
来源：http://dali.yj202588.top/Article/details/gt2npdynsar.html

TS:   public / protected / private
来源：http://dali.hammf.cn/Article/details/gt2kbgwiihm.html

Java: public / protected / private / 默认包级
来源：http://dali.snrcjt.cn/Article/details/gt2tinldnxw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tanke756.top/Article/details/gt2cldpatuu.html

Ruby: public / protected / private
来源：http://dali.jqgufenzy.top/Article/details/gt2qlilhsyg.html

C#:   public / protected / private / internal
来源：http://dali.mhx1999.top/Article/details/gt2nddlbmxn.html

[G11] getter / setter
来源：http://dali.chenlongwang.top/Article/details/gt2wkvsaxct.html

Py:   @property 与 @x.setter
来源：http://dali.ybcxt.top/Article/details/gt2gyxdormo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gt2cfqhltxo.html

JS:   get name() { return this._name; }
来源：http://dali.nwbrower.top/Article/details/gt2sdtrheuh.html

TS:   get name(): string { return this._name; }
来源：http://dali.cqqwz.cn/Article/details/gt2mtclmkrc.html

Java: public String getName() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2fzlpduqf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gt2bgwtrlxo.html

Ruby: attr_accessor :name
来源：http://dali.zycfv.cn/Article/details/gt2orlnrllo.html

C#:   public string Name { get; set; }
来源：http://dali.shuidangran.top/Article/details/gt2bkgefgfr.html

[G12] 对象转字符串
来源：http://dali.jinqigufen.top/Article/details/gt2pzloebbs.html

Py:   def __str__(self): return self.name
来源：http://dali.9152youxi.cn/Article/details/gt2svierfga.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gt2lpaninfx.html

JS:   toString() { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gt2xabpyiua.html

TS:   toString(): string { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2vkybqypw.html

Java: @Override public String toString() { return name; }
来源：http://dali.meibo888.top/Article/details/gt2jomiibqe.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gt2lgdhayuy.html

Ruby: def to_s; @name; end
来源：http://dali.sufxvd.cn/Article/details/gt2fyglrqbq.html

C#:   public override string ToString() => Name;
来源：http://dali.chenjidiqi.icu/Article/details/gt2xtidqqxf.html

[G13] 判断对象类型
来源：http://dali.zycfv.cn/Article/details/gt2qqmsauhv.html

Py:   isinstance(u, User)
来源：http://dali.zdqjudy.top/Article/details/gt2yqzzprtp.html

PHP:  $u instanceof User
来源：http://dali.guannengcc.top/Article/details/gt2nddekjvj.html

JS:   u instanceof User
来源：http://dali.guannengcc.top/Article/details/gt2zbxpzree.html

TS:   u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gt2yucvmraq.html

Java: u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gt2ecwblpye.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cheryme.top/Article/details/gt2waidywhe.html

Ruby: u.is_a?(User)
来源：http://dali.guowangkeji.top/Article/details/gt2wutnwszz.html

C#:   u is User
来源：http://dali.chenlongwang.top/Article/details/gt2ruegdiqo.html

[G14] 数据类 / record
来源：http://dali.smart0.xyz/Article/details/gt2texyzgvl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.aibaodan.cn/Article/details/gt2bpieagdr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cknrhyoh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yongpay.top/Article/details/gt2jpcpvcgn.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2erwbhauc.html

Java: record User(String name, int age) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2tuiywytk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.fengsongda.top/Article/details/gt2icoyvnss.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhixingplan.top/Article/details/gt2prtgsigy.html

C#:   record User(string Name, int Age);
来源：http://dali.svipenyu.cn/Article/details/gt2nuovnzju.html

[G15] 枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jlsffxzj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jlsjyb.cn/Article/details/gt2khazrruu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2iyarpdnj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wfbqlbfc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guowangkeji.top/Article/details/gt2ttwmpmxw.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhixingplan.top/Article/details/gt2dzkqhrmq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.aizwys.cn/Article/details/gt2otyhvmuu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.redwolf501.top/Article/details/gt2ahrhtyok.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daria6918.cn/Article/details/gt2wynuujmo.html

[G16] 对象转数组 / 字典
来源：http://dali.xziqi.cn/Article/details/gt2tacbgaoo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhixingplan.top/Article/details/gt2qjzytwee.html

PHP:  get_object_vars($obj);
来源：http://dali.andypj.xyz/Article/details/gt2yoyclhnf.html

JS:   Object.entries(obj)
来源：http://dali.c1oappe.top/Article/details/gt2rxjfeqiw.html

TS:   Object.entries(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2xjhxagbg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.316326.xyz/Article/details/gt2euezxelo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.aibaodan.cn/Article/details/gt2tixjufhn.html

Ruby: obj.instance_variables
来源：http://dali.gzhubu.top/Article/details/gt2remmzqfr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yanxiufei.cn/Article/details/gt2hxguqiso.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2bzekasob.html

H. 异常与错误处理
来源：http://dali.smart0.xyz/Article/details/gt2luijrebz.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2zraztdfp.html

[H01] try / catch 基础
来源：http://dali.ehwqpu.com/Article/details/gt2obtbjepm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.guowangkeji.top/Article/details/gt2fvymxwgx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yj20258.top/Article/details/gt2ksepjpmt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ehwqpu.com/Article/details/gt2rrivcpny.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jianghu66.top/Article/details/gt2xdnrxsjz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hnxiangtu.top/Article/details/gt2msemfoed.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhoulong.xyz/Article/details/gt2jkxgngus.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ivvv.top/Article/details/gt2dqfhlsdo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.0kj1m.cn/Article/details/gt2hzuvmpwp.html

[H02] finally / ensure 收尾
来源：http://dali.316326.xyz/Article/details/gt2fchzlcdd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dpvgxsah.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gt2gafqdwar.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gt2eoaxmttx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gt2jatofimb.html


<!-- 参考信息 -->