代发 wailian999

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yvedp.cn/Article/details/gtzvniszlo.html

[E19] 多行文本按行拆分
来源：http://dali.xziqi.cn/Article/details/gtlpvkhswb.html

Py:   s.splitlines()
来源：http://dali.zdqjudy.top/Article/details/gtmabsgbox.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gzhubu.top/Article/details/gtnxnqljqo.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gtbhdibtal.html

TS:   s.split(/\r?\n/)
来源：http://dali.aibaodan.cn/Article/details/gtoyjqfshz.html

Java: s.lines().toList()
来源：http://dali.xinyue.icu/Article/details/gthaktisiz.html

Go:   strings.Split(s, "\n")
来源：http://dali.bjfxy.top/Article/details/gtkdqotyyl.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gtarueiygg.html

C#:   s.Split('\n')
来源：http://dali.ppjwa.cn/Article/details/gtlsrzqyxr.html

[E20] 判断字符串是否为空
来源：http://dali.0kj1m.cn/Article/details/gtfsetscoi.html

Py:   if not s:
来源：http://dali.hnxiangtu.top/Article/details/gtlsgmbtyk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nanxuanxn.top/Article/details/gtvfjnjnxo.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jqgufenzy.top/Article/details/gtsgswiiqr.html

TS:   if (s === "") {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnxtghlkv.html

Java: if (s.isEmpty()) {}
来源：http://dali.haohaochexian.top/Article/details/gtwmtrqkja.html

Go:   if s == "" {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmlezznep.html

Ruby: if s.empty?
来源：http://dali.ppjwa.cn/Article/details/gtlwuejrdd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gaohongyu789.top/Article/details/gtvayseled.html

[E21] 超长截断加省略号
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbozlyfvj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.smart0.xyz/Article/details/gtgruzftlo.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinqigufen.top/Article/details/gtmiyowfsq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtflpwvguw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gtfsqvyynr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gtyyciuugy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.quarkkingdee.top/Article/details/gtktsxlpnm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sxryk.cn/Article/details/gttjauusqc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gtwxdgxkfq.html

[E22] 字节长度与字符长度
来源：http://dali.hongshengwenyu.top/Article/details/gtjpepidfx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.fengsongda.top/Article/details/gtyykqhugc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmgqhsskk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ybcxt.top/Article/details/gtxaivzyzm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gtcnisstrc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ybcxt.top/Article/details/gtsnhfajxg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shuidangran.top/Article/details/gtbteyfxqg.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gtsfunhroa.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.9152youxi.cn/Article/details/gtkavvewjn.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtxtzpvpqo.html

F. 文件与目录
来源：http://dali.gogol.net.cn/Article/details/gtyedtncjv.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtyhxkujiw.html

[F01] 读取整个文件
来源：http://dali.xinyue.icu/Article/details/gtheuebvxk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hnxiangtu.top/Article/details/gttglkdtuj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtywjkvtus.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yangfankeji.com/Article/details/gttqvnecem.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gtmevgczmz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gtltwhimws.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shzxlz.cn/Article/details/gtgrjsldpl.html

Ruby: File.read("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtzgafntzl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yongpay.top/Article/details/gtomuinymj.html

[F02] 逐行读取文件
来源：http://dali.gaohongyu789.top/Article/details/gtqrnhxpce.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jiagoushi.top/Article/details/gtgaltfrtm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nanxinkj.top/Article/details/gtdreyjajd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigufen.top/Article/details/gtxkiuxybf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgufenzy.top/Article/details/gtvlresrjl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ivvv.top/Article/details/gtxiemfbdc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinqigufen.top/Article/details/gtbwnafgeb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.fzhhl.top/Article/details/gtyszgquwu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.dianchejie.cn/Article/details/gtcpmrfqbz.html

[F03] 写入文件（覆盖）
来源：http://dali.smart0.xyz/Article/details/gtplydxpev.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xylfe.cn/Article/details/gttjjbzpdy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.andypj.xyz/Article/details/gtkwqiobmb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnarouahq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gtkexixxbm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.dianchejie.cn/Article/details/gtvwggdomg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinqigfzy.top/Article/details/gtzsnbflkd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zdqjudy.top/Article/details/gtjllajpjv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yvedp.cn/Article/details/gtwhwysmzy.html

[F04] 追加写入文件
来源：http://dali.tianlin.xyz/Article/details/gtayevqocx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ppjwa.cn/Article/details/gtghqjtrvx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.feifeiyinyue.top/Article/details/gtngmzwand.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.kuanghao11.cn/Article/details/gtnjfgnroh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cqqwz.cn/Article/details/gtooldhrqh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jlsjyb.cn/Article/details/gtllttenla.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jqgufenzy.top/Article/details/gtjpwyfqrf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.wangshuangyany.cn/Article/details/gtnryrvtjv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.daxiang520.top/Article/details/gtgxupvpvh.html

[F05] 判断文件或目录是否存在
来源：http://dali.bjfxy.top/Article/details/gtxuytffyj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhoulong.xyz/Article/details/gtictwfiev.html

PHP:  file_exists("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtyhbxlylh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtscrgyoco.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjqfqebeu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gtcclvexxy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.birdmap.top/Article/details/gtflbvxspk.html

Ruby: File.exist?("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtdczcevpw.html

C#:   File.Exists("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtfpbaxzli.html

[F06] 删除文件
来源：http://dali.hnqzz.top/Article/details/gtebssfjxo.html

Py:   os.remove("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtolguxesw.html

PHP:  unlink("a.txt");
来源：http://dali.yonumen.top/Article/details/gtdpsuozxj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtmgfgbgwo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtmxeavovq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtdrstqdxu.html

Go:   os.Remove("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtmpounwwh.html

Ruby: File.delete("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtdwgiudmm.html

C#:   File.Delete("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtfqmotpxk.html

[F07] 创建目录（含多级）
来源：http://dali.yj20258888.top/Article/details/gtxhnvekry.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cdnleiting.top/Article/details/gtdncolorl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.wangdashe.top/Article/details/gtpnivymjo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gtrpmelosu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hysaishi.cn/Article/details/gtopnxczna.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yonumen.top/Article/details/gthcwhsfxs.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.haohaochexian.top/Article/details/gtapeyhfhi.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenzaomai.com/Article/details/gtbvykqqkm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zdqjudy.top/Article/details/gtmsxnmrli.html

[F08] 遍历目录
来源：http://dali.cdnleiting.top/Article/details/gtqdjzxiez.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.wangdashe.top/Article/details/gtqksbpyjl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhiwuduotai.top/Article/details/gtbaxqdxnn.html

JS:   fs.readdirSync("dir")
来源：http://dali.chenlongwang.top/Article/details/gtoulyftss.html

TS:   fs.readdirSync("dir")
来源：http://dali.yangfankeji.com/Article/details/gtrmicvqpt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdstvezyd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yuxming.cn/Article/details/gtpbccnhjx.html

Ruby: Dir.children("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtorfhxhro.html

C#:   Directory.GetFiles("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gtedkaogfs.html

[F09] 获取文件大小
来源：http://dali.zhengqikj.top/Article/details/gtxkghwzrg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gttdhkuapl.html

PHP:  filesize("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtbfdvamjz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfwhetpgj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnlomyqrb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtddeuzumq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenzaomai.com/Article/details/gthqzelvbi.html

Ruby: File.size("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtbptubjzi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hongshengwenyu.top/Article/details/gtixbweqwi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhengqikj.top/Article/details/gtnqzblqfs.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtkmmgyosv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hfpthk.cn/Article/details/gthfmkdeep.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtqkrxzqlq.html

TS:   path.extname("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtcfqlbuzh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.c1oappe.top/Article/details/gtphyarpge.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtketgzujq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gtjhtdwiae.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtbjmjiwuw.html

[F11] 复制与移动文件
来源：http://dali.xuanzx.com/Article/details/gtknqgbxly.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtqpamkcfc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtucmxotcu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gtuazbtaya.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtmzlkoima.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.pengpengdd.cyou/Article/details/gtykwesgqq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gotoacloud.top/Article/details/gtmqdcrkpq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gteuojdapx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cqqwz.cn/Article/details/gtmhyyppch.html

[F12] CSV 读写
来源：http://dali.cucudq.cn/Article/details/gtbkmpdifn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.dianchejie.cn/Article/details/gtbmagkmun.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinqigufen.top/Article/details/gtbjcjckni.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jyoumei.cn/Article/details/gtgojimlee.html

TS:   // 同上
来源：http://dali.dashuyun.cn/Article/details/gttcvdxchc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenzaomai.com/Article/details/gtdluakpmd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.chenjidiqi.icu/Article/details/gtblmpyasl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.snrcjt.cn/Article/details/gtgkipczhc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.dianchejie.cn/Article/details/gtsgtgptwa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtaoymyuqn.html

G. 面向对象
来源：http://dali.jinghuilouyu.cn/Article/details/gtdtjjfpkd.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtjekqoagr.html

[G01] 定义类
来源：http://dali.aizwys.cn/Article/details/gtnwuelefo.html

Py:   class User: pass
来源：http://dali.sweek.top/Article/details/gtyipszqiy.html

PHP:  class User {}
来源：http://dali.jianghu66.top/Article/details/gtkxvbkzfp.html

JS:   class User {}
来源：http://dali.jqgufenzy.top/Article/details/gtsifcolxw.html

TS:   class User { name: string = ""; }
来源：http://dali.iojbl.cn/Article/details/gtjdjevnor.html

Java: class User {}
来源：http://dali.jinqigufen.top/Article/details/gtjpoiqkhu.html

Go:   type User struct { Name string }
来源：http://dali.birdmap.top/Article/details/gtikygvldx.html

Ruby: class User; end
来源：http://dali.jinqigfzy.top/Article/details/gtafnamqfr.html

C#:   class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gthlgegsha.html

[G02] 构造函数
来源：http://dali.316326.xyz/Article/details/gtrpnflapq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.svipenyu.cn/Article/details/gtgfitbglc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yuanzhike.top/Article/details/gtmagpqwfy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.aibaodan.cn/Article/details/gtopsxfmfm.html

TS:   constructor(public name: string) {}
来源：http://dali.sysykeji.top/Article/details/gtpzvzasgm.html

Java: User(String name) { this.name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcoqbjsqi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.316326.xyz/Article/details/gtnziqbczb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nanxuanxn.top/Article/details/gtuekosbrh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cucudq.cn/Article/details/gthuorwqro.html

[G03] 实例属性
来源：http://dali.xylfe.cn/Article/details/gtxhfsxffu.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gtqaclbyqe.html

PHP:  public string $name = "x";
来源：http://dali.cqqwz.cn/Article/details/gtcqfmzuwa.html

JS:   this.name = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gtyzvykzmf.html

TS:   name: string = "x";
来源：http://dali.chenzaomai.com/Article/details/gtztfxxpsp.html

Java: private String name;
来源：http://dali.gogol.net.cn/Article/details/gtcrjrzqzb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinqigufen.top/Article/details/gtlrbewbkb.html

Ruby: @name = "x"
来源：http://dali.0kj1m.cn/Article/details/gtsuhcyywo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yvedp.cn/Article/details/gtuszftbuh.html

[G04] 定义方法
来源：http://dali.feifeiyinyue.top/Article/details/gtdiflabnl.html

Py:   def greet(self): return self.name
来源：http://dali.xziqi.cn/Article/details/gtnbzsafab.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtvnvszlws.html

JS:   greet() { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gtfhzfmeca.html

TS:   greet(): string { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gtgixeeyqn.html

Java: String greet() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtucguwxoe.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gtcfosffsh.html

Ruby: def greet; @name; end
来源：http://dali.nanxuanxn.top/Article/details/gtonqylsud.html

C#:   public string Greet() => Name;
来源：http://dali.xinyue.icu/Article/details/gtfcfxlscu.html

[G05] 继承
来源：http://dali.jinghuilouyu.cn/Article/details/gtvyhaybtw.html

Py:   class Admin(User): pass
来源：http://dali.quarkkingdee.top/Article/details/gtptdpsifl.html

PHP:  class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpkojpolz.html

JS:   class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtllwgvzrd.html

TS:   class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gthigrpfsx.html

Java: class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtqgxrihbo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gtcotbdbdz.html

Ruby: class Admin < User; end
来源：http://dali.316326.xyz/Article/details/gtfhkdpwkk.html

C#:   class Admin : User {}
来源：http://dali.fengsongda.top/Article/details/gtcpzxiohm.html

[G06] 重写方法
来源：http://dali.wangdashe.top/Article/details/gthulifdri.html

Py:   def greet(self): return "admin"
来源：http://dali.ydzc1.top/Article/details/gtdrsnereh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gtyyemyilp.html

JS:   greet() { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gttigaptzu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gtmpsipdri.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gtmbvwrpxu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.dianchejie.cn/Article/details/gtkxlgetsn.html

Ruby: def greet; "admin"; end
来源：http://dali.hnxiangtu.top/Article/details/gtffejzxvz.html

C#:   public override string Greet() => "admin";
来源：http://dali.havefunace.top/Article/details/gtpvcvyxeb.html

[G07] 调用父类方法
来源：http://dali.xuanzx.com/Article/details/gtqpcotqnf.html

Py:   super().greet()
来源：http://dali.yangfankeji.com/Article/details/gtoztofnfr.html

PHP:  parent::greet();
来源：http://dali.zhengqikj.top/Article/details/gtzcbfbfpa.html

JS:   super.greet();
来源：http://dali.fengsongda.top/Article/details/gtqvxdeaah.html

TS:   super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gtskhfnlzo.html

Java: super.greet();
来源：http://dali.birdmap.top/Article/details/gtnzpociha.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yangfankeji.com/Article/details/gtonzdqcht.html

Ruby: super
来源：http://dali.jqgufenzy.top/Article/details/gtnxgeptdb.html

C#:   base.Greet();
来源：http://dali.hywenlv.cn/Article/details/gtucuctkly.html

[G08] 静态方法与属性
来源：http://dali.jianghu66.top/Article/details/gtreliknwy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xinyue.icu/Article/details/gtbwfnyeda.html

PHP:  public static function f() {}
来源：http://dali.yueranfly.top/Article/details/gthftlkakq.html

JS:   static f() {}
来源：http://dali.316326.xyz/Article/details/gtigiorfkw.html

TS:   static f(): void {}
来源：http://dali.yanxiufei.cn/Article/details/gtavlescah.html

Java: static void f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gthkqxubye.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hywenlv.cn/Article/details/gthakhnpis.html

Ruby: def self.f; end
来源：http://dali.gzhubu.top/Article/details/gtownxxryi.html

C#:   public static void F() {}
来源：http://dali.yj20258.top/Article/details/gtvlxlytoe.html

[G09] 接口 / 抽象类
来源：http://dali.dashuyun.cn/Article/details/gtdefbzwbz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sysykeji.top/Article/details/gtnujqotvt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yvedp.cn/Article/details/gtkugbokbm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.chenlongwang.top/Article/details/gtpuqtlbvd.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenzaomai.com/Article/details/gttstdefpn.html

Java: interface Shape { double area(); }
来源：http://dali.tianlin.xyz/Article/details/gtyypnumrf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.iojbl.cn/Article/details/gtmkbbuqls.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xylfe.cn/Article/details/gtoiedvaor.html

C#:   interface IShape { double Area(); }
来源：http://dali.jqgfzy.top/Article/details/gtuosegyoo.html

[G10] 访问控制
来源：http://dali.yuxming.cn/Article/details/gtruqtokqy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gotoacloud.top/Article/details/gtyxfxbfxa.html

PHP:  public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gtjgkhniuy.html

JS:   #private 字段；其余公开
来源：http://dali.yj20258888.top/Article/details/gtxvpftgef.html

TS:   public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gttxziaewh.html

Java: public / protected / private / 默认包级
来源：http://dali.jyoumei.cn/Article/details/gtkdfzhfuk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.fzhhl.top/Article/details/gtmopvmqxk.html

Ruby: public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gtswfpouat.html

C#:   public / protected / private / internal
来源：http://dali.wangshuangyany.cn/Article/details/gtwqojceob.html

[G11] getter / setter
来源：http://dali.0kj1m.cn/Article/details/gtmemymris.html

Py:   @property 与 @x.setter
来源：http://dali.zdqjudy.top/Article/details/gtgmzwarin.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaehihwnq.html

JS:   get name() { return this._name; }
来源：http://dali.ivvv.top/Article/details/gthhzwsxau.html

TS:   get name(): string { return this._name; }
来源：http://dali.ppjwa.cn/Article/details/gtgyqwvkmi.html

Java: public String getName() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtglmubara.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gtnttabzjv.html

Ruby: attr_accessor :name
来源：http://dali.jlsjyb.cn/Article/details/gtzlxkabsv.html

C#:   public string Name { get; set; }
来源：http://dali.yuanzhike.top/Article/details/gtnasnttea.html

[G12] 对象转字符串
来源：http://dali.cdnleiting.top/Article/details/gtfxdgzdfq.html

Py:   def __str__(self): return self.name
来源：http://dali.gotoacloud.top/Article/details/gttkofmbus.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gtlwpnzcxp.html

JS:   toString() { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtftgdfqpd.html

TS:   toString(): string { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gtpnlmtvqx.html

Java: @Override public String toString() { return name; }
来源：http://dali.hnqzz.top/Article/details/gtgyvcuhyk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gtwneyvlhk.html

Ruby: def to_s; @name; end
来源：http://dali.hysaishi.cn/Article/details/gtvzzruupe.html

C#:   public override string ToString() => Name;
来源：http://dali.dianchejie.cn/Article/details/gtrcfbqtrj.html

[G13] 判断对象类型
来源：http://dali.ydzc1.top/Article/details/gtmcxkcsrp.html

Py:   isinstance(u, User)
来源：http://dali.chenjidiqi.icu/Article/details/gtuyragkwi.html

PHP:  $u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtegcwlvbp.html

JS:   u instanceof User
来源：http://dali.bjfxy.top/Article/details/gtdafrfbwk.html

TS:   u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtbhtlxvfo.html

Java: u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtieioyosu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shangyingyoupin.top/Article/details/gtuyugyzco.html

Ruby: u.is_a?(User)
来源：http://dali.iojbl.cn/Article/details/gtipnkvraw.html

C#:   u is User
来源：http://dali.pycfn.com/Article/details/gtgrkamfkj.html

[G14] 数据类 / record
来源：http://dali.haohaochexian.top/Article/details/gtxgsvtwnr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.316326.xyz/Article/details/gthjyazjbb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinghuilouyu.cn/Article/details/gtastchizl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xuetiantiany.cn/Article/details/gtndvccrcz.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtneqiyiyb.html

Java: record User(String name, int age) {}
来源：http://dali.quarkkingdee.top/Article/details/gtmifsaiti.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ydzc1.top/Article/details/gtbtjwyjdv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.316326.xyz/Article/details/gtdmajmcnq.html

C#:   record User(string Name, int Age);
来源：http://dali.xylfe.cn/Article/details/gtplpbcwkg.html

[G15] 枚举
来源：http://dali.wangshuangyany.cn/Article/details/gtkittscbz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gogol.net.cn/Article/details/gtrsldsmsy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sxryk.cn/Article/details/gtixefzeqo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.svipenyu.cn/Article/details/gtcxzyvcsj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlfxivwgh.html

Java: enum Color { RED, GREEN }
来源：http://dali.xinyue.icu/Article/details/gtssoecnrv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nanxuanxn.top/Article/details/gtaodxbysn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmluroqxe.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtprryavnk.html

[G16] 对象转数组 / 字典
来源：http://dali.daxiang520.top/Article/details/gtxbfyloil.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gtpfcjinof.html

PHP:  get_object_vars($obj);
来源：http://dali.jiagoushi.top/Article/details/gtdvwmruak.html

JS:   Object.entries(obj)
来源：http://dali.cashguo.top/Article/details/gtaoeoqpqo.html

TS:   Object.entries(obj)
来源：http://dali.zdqjudy.top/Article/details/gtluvewzai.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gaohongyu789.top/Article/details/gtqeiadhae.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nanxinkj.top/Article/details/gtacoxkwdf.html

Ruby: obj.instance_variables
来源：http://dali.jiagoushi.top/Article/details/gtwdjdfbgt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fzhhl.top/Article/details/gtdyrvfssh.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gttpgiwwve.html

H. 异常与错误处理
来源：http://dali.jqgufenzy.top/Article/details/gtasytfvaf.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtjmkuicze.html

[H01] try / catch 基础
来源：http://dali.jinghuilouyu.cn/Article/details/gtoyyozoiq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.aizwys.cn/Article/details/gtyknxpimm.html


<!-- 参考信息 -->