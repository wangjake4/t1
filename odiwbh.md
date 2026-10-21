代发 wailian999

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gtnincqjap.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gtibdvuyxk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gtvalybiok.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nanxuanxn.top/Article/details/gtjmutxosi.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yuxming.cn/Article/details/gtbmdzfndf.html

[E19] 多行文本按行拆分
来源：http://dali.chenlongwang.top/Article/details/gtummasmrd.html

Py:   s.splitlines()
来源：http://dali.316326.xyz/Article/details/gtifpheuqk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xziqi.cn/Article/details/gtrvvqyhse.html

JS:   s.split(/\r?\n/)
来源：http://dali.sufxvd.cn/Article/details/gtftjqngxa.html

TS:   s.split(/\r?\n/)
来源：http://dali.hammf.cn/Article/details/gtnrevecym.html

Java: s.lines().toList()
来源：http://dali.mhx1999.top/Article/details/gtkcrtkkyv.html

Go:   strings.Split(s, "\n")
来源：http://dali.sysykeji.top/Article/details/gtpjjwezfi.html

Ruby: s.lines
来源：http://dali.sysykeji.top/Article/details/gtfbvyzaaj.html

C#:   s.Split('\n')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtooaocqhe.html

[E20] 判断字符串是否为空
来源：http://dali.xinyue.icu/Article/details/gtdvbforcw.html

Py:   if not s:
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcvkzsbte.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nanxinkj.top/Article/details/gtqemasprf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ehwqpu.com/Article/details/gttnuxexhp.html

TS:   if (s === "") {}
来源：http://dali.jyoumei.cn/Article/details/gtklowysjm.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhixingplan.top/Article/details/gtayvlttbw.html

Go:   if s == "" {}
来源：http://dali.jianghu66.top/Article/details/gtdpjecdur.html

Ruby: if s.empty?
来源：http://dali.jiagoushi.top/Article/details/gtaptsuhcw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shuidangran.top/Article/details/gtnfjgjwds.html

[E21] 超长截断加省略号
来源：http://dali.jqgfzy.top/Article/details/gtejixlewu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.snrcjt.cn/Article/details/gtdmochwwr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gtzgrunojl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gtcevuolqy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtdvbsxzpl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtseocpyiu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xuetiantiany.cn/Article/details/gtzlkhtqvz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gttwoxxepa.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gtocbalpht.html

[E22] 字节长度与字符长度
来源：http://dali.tianlin.xyz/Article/details/gtbrfznzmb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cashguo.top/Article/details/gtndyoigrg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gtupuaeckf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.redwolf501.top/Article/details/gtxjoupqcw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.316326.xyz/Article/details/gttfgyqdei.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cheryme.top/Article/details/gtykgrirlr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yvedp.cn/Article/details/gtboyzjtdb.html

Ruby: s.bytesize;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gtzqhhbiip.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.redwolf501.top/Article/details/gtneozvoch.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtwvmlcaob.html

F. 文件与目录
来源：http://dali.nanxuanxn.top/Article/details/gtlwntgepp.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtirdobxre.html

[F01] 读取整个文件
来源：http://dali.yuxming.cn/Article/details/gtqjozeira.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yonumen.top/Article/details/gtxxckbocu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcywjuxxt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.redwolf501.top/Article/details/gtfxgfqevz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.redwolf501.top/Article/details/gtotmifhkk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gthrfhxjbe.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhongyouzk.top/Article/details/gtxrdbuhip.html

Ruby: File.read("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtlfjgmfzm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtkfzkywqs.html

[F02] 逐行读取文件
来源：http://dali.wangshuangyany.cn/Article/details/gtoeavzmiq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jqgufenzy.top/Article/details/gtdffpwson.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.redwolf501.top/Article/details/gteoszhjzj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hammf.cn/Article/details/gtgnqkxmzd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aizwys.cn/Article/details/gtudumqqes.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xuanzx.com/Article/details/gtdspptcqv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shuidangran.top/Article/details/gtqwdkfbwx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xylfe.cn/Article/details/gtflpscula.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hnxiangtu.top/Article/details/gtolixiros.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gtdnsewilz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.quarkkingdee.top/Article/details/gtboianwsi.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yj20258888.top/Article/details/gtglzttued.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fzhhl.top/Article/details/gtgyagqvpg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmdlhryfw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sweek.top/Article/details/gtwwofyxmb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hfpthk.cn/Article/details/gtcvhgoopm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xinyue.icu/Article/details/gtvgpigojy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhengqikj.top/Article/details/gtoyevnauo.html

[F04] 追加写入文件
来源：http://dali.xinyue.icu/Article/details/gtnhitfohn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zycfv.cn/Article/details/gthvoxutdg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yj202588.top/Article/details/gtlhznzajb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guowangkeji.top/Article/details/gtbrlddbaz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ivvv.top/Article/details/gttsssqzad.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sweek.top/Article/details/gtqgrmurzt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.quarkkingdee.top/Article/details/gtgkcgrseu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.316326.xyz/Article/details/gtqpcqsmac.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.dashuyun.cn/Article/details/gtjhyyyfqd.html

[F05] 判断文件或目录是否存在
来源：http://dali.ydzc1.top/Article/details/gtmayacwyh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinghuilouyu.cn/Article/details/gtxircfhbs.html

PHP:  file_exists("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtirumcoui.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtiunoqmol.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtsakabwon.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gttvxmdcev.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.daria6918.cn/Article/details/gtrrqdspfn.html

Ruby: File.exist?("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtwjphffdu.html

C#:   File.Exists("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtwgdrbsmo.html

[F06] 删除文件
来源：http://dali.sweek.top/Article/details/gtpahyzjns.html

Py:   os.remove("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtecszfemi.html

PHP:  unlink("a.txt");
来源：http://dali.316326.xyz/Article/details/gtwjkzsiqe.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gthvkanifx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyccoulfg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gtzbqphipo.html

Go:   os.Remove("a.txt")
来源：http://dali.cheryme.top/Article/details/gtepfxamwz.html

Ruby: File.delete("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtxporumme.html

C#:   File.Delete("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtlfwiqgyo.html

[F07] 创建目录（含多级）
来源：http://dali.aizwys.cn/Article/details/gthgexlhqb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gotoacloud.top/Article/details/gtfwdgytzc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zycfv.cn/Article/details/gtreoabosn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sweek.top/Article/details/gtmdhfyqxy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ehwqpu.com/Article/details/gtnkxvsawq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.daria6918.cn/Article/details/gtaoympzak.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gotoacloud.top/Article/details/gtlntjklxl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shzxlz.cn/Article/details/gtxxxrcyjh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xylfe.cn/Article/details/gtmonvpczi.html

[F08] 遍历目录
来源：http://dali.cdnleiting.top/Article/details/gtadrortnn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jlsjyb.cn/Article/details/gtfbzfaino.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zdqjudy.top/Article/details/gtpurukxxa.html

JS:   fs.readdirSync("dir")
来源：http://dali.hfpthk.cn/Article/details/gtbtxcdkji.html

TS:   fs.readdirSync("dir")
来源：http://dali.pycfn.com/Article/details/gthilryzoc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xziqi.cn/Article/details/gtvvraplkm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hywenlv.cn/Article/details/gtuprpyrir.html

Ruby: Dir.children("dir")
来源：http://dali.bjfxy.top/Article/details/gtxqlzaljp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtxxxvewmz.html

[F09] 获取文件大小
来源：http://dali.guowangkeji.top/Article/details/gtdeutfkdf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtngnlbyua.html

PHP:  filesize("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtdjvqstjp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlaxjgmmk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gogol.net.cn/Article/details/gtaoykvkwz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gthqqhbbxh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.redwolf501.top/Article/details/gtnxtxyvon.html

Ruby: File.size("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtojfpbvzs.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.aizwys.cn/Article/details/gtxdozolou.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj20258.top/Article/details/gttwuxjhhp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtlxkxnrgo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtcchxwiet.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtdzdadntk.html

TS:   path.extname("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtajadeeta.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.snrcjt.cn/Article/details/gtyocvissb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtvsicogte.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtbdazumkf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gtwsfigqrt.html

[F11] 复制与移动文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtgaizssbo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtzhrfkuiw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.wangdashe.top/Article/details/gtuoebpcpz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtqldihxvb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtgdupvjbe.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yj20258.top/Article/details/gtmxvhdvhe.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xinyue.icu/Article/details/gtgywosrol.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtwzcmoeio.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhengqikj.top/Article/details/gtfewmvngz.html

[F12] CSV 读写
来源：http://dali.cqqwz.cn/Article/details/gtkdonmwox.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.birdmap.top/Article/details/gtynzyoaal.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj202588.top/Article/details/gtqzyxhain.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtucsceptv.html

TS:   // 同上
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxouyffi.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.feifeiyinyue.top/Article/details/gtjchincob.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhongyouzk.top/Article/details/gtjuhidnmm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ppjwa.cn/Article/details/gtxihppdqt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gotoacloud.top/Article/details/gtyeyxwjbd.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtdseqlpqb.html

G. 面向对象
来源：http://dali.cheryme.top/Article/details/gtevfbkuxk.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtancgvhik.html

[G01] 定义类
来源：http://dali.jqgufenzy.top/Article/details/gtufxkurvw.html

Py:   class User: pass
来源：http://dali.jlsjyb.cn/Article/details/gtbnpivwjv.html

PHP:  class User {}
来源：http://dali.jqgufenzy.top/Article/details/gtcmsgxnfw.html

JS:   class User {}
来源：http://dali.gogol.net.cn/Article/details/gtvdkcsyme.html

TS:   class User { name: string = ""; }
来源：http://dali.xinyue.icu/Article/details/gtrglhdatm.html

Java: class User {}
来源：http://dali.yuanzhike.top/Article/details/gtzncagcqg.html

Go:   type User struct { Name string }
来源：http://dali.pycfn.com/Article/details/gttdlhjpdw.html

Ruby: class User; end
来源：http://dali.nwbrower.top/Article/details/gtnexhawqi.html

C#:   class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtajdyufmd.html

[G02] 构造函数
来源：http://dali.zhixingplan.top/Article/details/gtycjstbnx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ehwqpu.com/Article/details/gtxnweufdr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.nanxuanxn.top/Article/details/gtfwnavdms.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yuanzhike.top/Article/details/gtvarnywpf.html

TS:   constructor(public name: string) {}
来源：http://dali.0kj1m.cn/Article/details/gtjgevvjdl.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gtxkebbkmt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ehwqpu.com/Article/details/gteqjizsbu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yangfankeji.com/Article/details/gtkbsqitak.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hywenlv.cn/Article/details/gtbdccjvnf.html

[G03] 实例属性
来源：http://dali.sweek.top/Article/details/gtdyrxnghc.html

Py:   self.name = "x"
来源：http://dali.nwbrower.top/Article/details/gtefpadret.html

PHP:  public string $name = "x";
来源：http://dali.yuxming.cn/Article/details/gtzzcfgiyw.html

JS:   this.name = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtibnakwdl.html

TS:   name: string = "x";
来源：http://dali.smart0.xyz/Article/details/gtbzfvevst.html

Java: private String name;
来源：http://dali.hywenlv.cn/Article/details/gtmlhxkbqr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yvedp.cn/Article/details/gtdbplvsps.html

Ruby: @name = "x"
来源：http://dali.xziqi.cn/Article/details/gtbvpbcemd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zycfv.cn/Article/details/gtdvfrpdiq.html

[G04] 定义方法
来源：http://dali.tianlin.xyz/Article/details/gturxugcvw.html

Py:   def greet(self): return self.name
来源：http://dali.dashuyun.cn/Article/details/gtsujjyboa.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gtzwhidrol.html

JS:   greet() { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gtbwlljvvd.html

TS:   greet(): string { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gtwupftpgf.html

Java: String greet() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gtdxvekxao.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hysaishi.cn/Article/details/gthxltjivq.html

Ruby: def greet; @name; end
来源：http://dali.xziqi.cn/Article/details/gtfvoljqyl.html

C#:   public string Greet() => Name;
来源：http://dali.hnxiangtu.top/Article/details/gtynfwhhvr.html

[G05] 继承
来源：http://dali.ybcxt.top/Article/details/gttggfwppk.html

Py:   class Admin(User): pass
来源：http://dali.nanxuanxn.top/Article/details/gtuhjhtovw.html

PHP:  class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gtuohstyjd.html

JS:   class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gtqxvyflcc.html

TS:   class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtpidfjvjn.html

Java: class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtvvbdnpav.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cqqwz.cn/Article/details/gtntkemnee.html

Ruby: class Admin < User; end
来源：http://dali.feifeiyinyue.top/Article/details/gtkmfcezlp.html

C#:   class Admin : User {}
来源：http://dali.jyoumei.cn/Article/details/gtuiixxhjt.html

[G06] 重写方法
来源：http://dali.yangfankeji.com/Article/details/gtmszxkkre.html

Py:   def greet(self): return "admin"
来源：http://dali.aibaodan.cn/Article/details/gtpvoiigei.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtlwkggwcl.html

JS:   greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtcvfbumbk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtldyevpha.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtfygqxmuz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hammf.cn/Article/details/gtaskihzny.html

Ruby: def greet; "admin"; end
来源：http://dali.jqgufenzy.top/Article/details/gtzisevgqn.html

C#:   public override string Greet() => "admin";
来源：http://dali.316326.xyz/Article/details/gtliqvaiyp.html

[G07] 调用父类方法
来源：http://dali.aizwys.cn/Article/details/gtdgzlkibt.html

Py:   super().greet()
来源：http://dali.shzxlz.cn/Article/details/gtpwnileql.html

PHP:  parent::greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfifaxdtg.html

JS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtjqrivqni.html

TS:   super.greet();
来源：http://dali.hysaishi.cn/Article/details/gtqagpjwkf.html

Java: super.greet();
来源：http://dali.jyoumei.cn/Article/details/gtlsddgadn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jiagoushi.top/Article/details/gtjgxotisg.html

Ruby: super
来源：http://dali.ybcxt.top/Article/details/gtentbwsyi.html

C#:   base.Greet();
来源：http://dali.kuanghao11.cn/Article/details/gtplnqfhii.html

[G08] 静态方法与属性
来源：http://dali.jiagoushi.top/Article/details/gtwpvmykgm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cashguo.top/Article/details/gtnfxjldin.html

PHP:  public static function f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtvmhrunqx.html

JS:   static f() {}
来源：http://dali.sxryk.cn/Article/details/gtfrukxpiw.html

TS:   static f(): void {}
来源：http://dali.xuanzx.com/Article/details/gtykjxzlty.html

Java: static void f() {}
来源：http://dali.jianghu66.top/Article/details/gtjzpyyxmn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.svipenyu.cn/Article/details/gtpviwnwhe.html

Ruby: def self.f; end
来源：http://dali.jinqigufen.top/Article/details/gtixbnbqyr.html

C#:   public static void F() {}
来源：http://dali.tianlin.xyz/Article/details/gtjeqfntkx.html

[G09] 接口 / 抽象类
来源：http://dali.hongshengwenyu.top/Article/details/gtndbdtrxk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinqigufen.top/Article/details/gtnddsraob.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.snrcjt.cn/Article/details/gtrikskppf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gogol.net.cn/Article/details/gtlwtobyug.html

TS:   interface Shape { area(): number; }
来源：http://dali.tian-w.cn/Article/details/gtaubmnbhp.html

Java: interface Shape { double area(); }
来源：http://dali.sufxvd.cn/Article/details/gtagsomeql.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrjtgrzvy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.svipenyu.cn/Article/details/gtxypywwzz.html

C#:   interface IShape { double Area(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtahjuipvi.html

[G10] 访问控制
来源：http://dali.snrcjt.cn/Article/details/gtswrsdagb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.pycfn.com/Article/details/gtempynkmw.html

PHP:  public / protected / private
来源：http://dali.guannengcc.top/Article/details/gtlvkjuopp.html

JS:   #private 字段；其余公开
来源：http://dali.hywenlv.cn/Article/details/gtkzzotogk.html

TS:   public / protected / private
来源：http://dali.havefunace.top/Article/details/gtosdyggtf.html

Java: public / protected / private / 默认包级
来源：http://dali.mhx1999.top/Article/details/gtrommxiji.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenzaomai.com/Article/details/gtfbgqkjry.html

Ruby: public / protected / private
来源：http://dali.yuxming.cn/Article/details/gtobjsgtjk.html

C#:   public / protected / private / internal
来源：http://dali.smart0.xyz/Article/details/gtfyebxvtc.html

[G11] getter / setter
来源：http://dali.vqdsnc.cn/Article/details/gtivhsygkm.html

Py:   @property 与 @x.setter
来源：http://dali.zhengqikj.top/Article/details/gtffwloemq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gtowlimzvh.html

JS:   get name() { return this._name; }
来源：http://dali.zhixingplan.top/Article/details/gtllbzrakb.html

TS:   get name(): string { return this._name; }
来源：http://dali.tianlin.xyz/Article/details/gtasdhruff.html

Java: public String getName() { return name; }
来源：http://dali.aibaodan.cn/Article/details/gtijqymrbr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gtfhhkteye.html

Ruby: attr_accessor :name
来源：http://dali.gotoacloud.top/Article/details/gtjlmvivoy.html

C#:   public string Name { get; set; }
来源：http://dali.dianchejie.cn/Article/details/gtillwqsxr.html

[G12] 对象转字符串
来源：http://dali.hywenlv.cn/Article/details/gtyyqfasxa.html

Py:   def __str__(self): return self.name
来源：http://dali.aibaodan.cn/Article/details/gtcarapilf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gtdhxfbeam.html

JS:   toString() { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gtdivavdyr.html

TS:   toString(): string { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtjqlaihuv.html

Java: @Override public String toString() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxhxcqiwm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gtygnthobc.html

Ruby: def to_s; @name; end
来源：http://dali.bjfxy.top/Article/details/gthbmlsyjf.html

C#:   public override string ToString() => Name;
来源：http://dali.ivvv.top/Article/details/gtfbyudcmn.html

[G13] 判断对象类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtddfzpyys.html

Py:   isinstance(u, User)
来源：http://dali.sysykeji.top/Article/details/gtxrvcwvgs.html

PHP:  $u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtswxlbqvq.html

JS:   u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvaqowxzv.html

TS:   u instanceof User
来源：http://dali.yueranfly.top/Article/details/gttbyjpdlb.html

Java: u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtphknvrtf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhongyouzk.top/Article/details/gtabctlzfp.html

Ruby: u.is_a?(User)
来源：http://dali.yj20258.top/Article/details/gtxyimbczp.html

C#:   u is User
来源：http://dali.dashuyun.cn/Article/details/gtetpwbgeh.html

[G14] 数据类 / record
来源：http://dali.tanke756.top/Article/details/gtlttfepea.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.wangdashe.top/Article/details/gtjxtwfyxu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yj202588.top/Article/details/gtxflewpmq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xylfe.cn/Article/details/gtkasupsqy.html

TS:   type User = { name: string; age: number };
来源：http://dali.ivvv.top/Article/details/gttuvljecx.html

Java: record User(String name, int age) {}
来源：http://dali.yangfankeji.com/Article/details/gtwjilusgg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbpavvfia.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.smart0.xyz/Article/details/gtbitkxubx.html

C#:   record User(string Name, int Age);
来源：http://dali.tian-w.cn/Article/details/gtwkktxajo.html

[G15] 枚举
来源：http://dali.hywenlv.cn/Article/details/gttohpgkcu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jyoumei.cn/Article/details/gtiwghhwbm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.smart0.xyz/Article/details/gtvufcfsbk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.wangshuangyany.cn/Article/details/gtomnaonoh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhixingplan.top/Article/details/gtavyhrqcn.html

Java: enum Color { RED, GREEN }
来源：http://dali.wangshuangyany.cn/Article/details/gtorzpbfwf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hywenlv.cn/Article/details/gtbwocmsov.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hongshengwenyu.top/Article/details/gtghknrsxn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.c1oappe.top/Article/details/gthcxldsed.html

[G16] 对象转数组 / 字典
来源：http://dali.0kj1m.cn/Article/details/gtfueltwdn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.birdmap.top/Article/details/gtdkknwtxc.html

PHP:  get_object_vars($obj);
来源：http://dali.cashguo.top/Article/details/gtbuvnptmz.html

JS:   Object.entries(obj)
来源：http://dali.fengsongda.top/Article/details/gtfcssecvz.html

TS:   Object.entries(obj)
来源：http://dali.havefunace.top/Article/details/gtmkjocgpn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.fengsongda.top/Article/details/gtgijxqrby.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hnxiangtu.top/Article/details/gtfdhrqipk.html

Ruby: obj.instance_variables
来源：http://dali.ybcxt.top/Article/details/gtdqqbdyvj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hnqzz.top/Article/details/gtqoozyftw.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtnctorhdv.html


<!-- 参考信息 -->