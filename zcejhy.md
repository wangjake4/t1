代发 wailian999

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yuxming.cn/Article/details/gt2rrwbzota.html

[E19] 多行文本按行拆分
来源：http://dali.fzhhl.top/Article/details/gt2furqajlh.html

Py:   s.splitlines()
来源：http://dali.havefunace.top/Article/details/gt2ypvsidly.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jiagoushi.top/Article/details/gt2nvgpzgtz.html

JS:   s.split(/\r?\n/)
来源：http://dali.chenzaomai.com/Article/details/gt2kfjoiywr.html

TS:   s.split(/\r?\n/)
来源：http://dali.yvedp.cn/Article/details/gt2pwjsixat.html

Java: s.lines().toList()
来源：http://dali.zycfv.cn/Article/details/gt2nhedkasb.html

Go:   strings.Split(s, "\n")
来源：http://dali.cdnleiting.top/Article/details/gt2ewccmraq.html

Ruby: s.lines
来源：http://dali.haohaochexian.top/Article/details/gt2xjcfsylu.html

C#:   s.Split('\n')
来源：http://dali.tian-w.cn/Article/details/gt2avnqhffv.html

[E20] 判断字符串是否为空
来源：http://dali.hongshengwenyu.top/Article/details/gt2gnzkbkpj.html

Py:   if not s:
来源：http://dali.dianchejie.cn/Article/details/gt2fudvsfkw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yanxiufei.cn/Article/details/gt2wwwaibol.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2idpjzngj.html

TS:   if (s === "") {}
来源：http://dali.jinqigufen.top/Article/details/gt2phyuypyf.html

Java: if (s.isEmpty()) {}
来源：http://dali.xylfe.cn/Article/details/gt2caxrzswa.html

Go:   if s == "" {}
来源：http://dali.gzhubu.top/Article/details/gt2pbybreuc.html

Ruby: if s.empty?
来源：http://dali.daxiang520.top/Article/details/gt2xhbduebw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2umnawnoa.html

[E21] 超长截断加省略号
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vqgtuqrt.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2auuwxesd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cashguo.top/Article/details/gt2vipltnis.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gt2qhmtctya.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gt2tibhsgvm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ltnvfacn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinqigufen.top/Article/details/gt2zzavmsly.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gt2ydhojgaz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.smart0.xyz/Article/details/gt2cnhfahof.html

[E22] 字节长度与字符长度
来源：http://dali.c1oappe.top/Article/details/gt2fwwxmvwx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.guannengcc.top/Article/details/gt2usleabga.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gt2egnfsvee.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ppjwa.cn/Article/details/gt2srmcvdoz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zdqjudy.top/Article/details/gt2tjwipqec.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.9152youxi.cn/Article/details/gt2ypeewyiw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ngtjkujj.html

Ruby: s.bytesize;  s.length
来源：http://dali.gzhubu.top/Article/details/gt2jxavazop.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhixingplan.top/Article/details/gt2bxovyttz.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ausoipcl.html

F. 文件与目录
来源：http://dali.ybcxt.top/Article/details/gt2uqwuykht.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxxzjwo.html

[F01] 读取整个文件
来源：http://dali.hnxiangtu.top/Article/details/gt2jnitbvvp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.guowangkeji.top/Article/details/gt2trrkkuno.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2igafnwnc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.guannengcc.top/Article/details/gt2typfpqsw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shuidangran.top/Article/details/gt2iiimxgox.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gt2nzmyilsn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xuetiantiany.cn/Article/details/gt2wrojjobv.html

Ruby: File.read("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2ivjbngbu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2owkwbsbq.html

[F02] 逐行读取文件
来源：http://dali.yuxming.cn/Article/details/gt2afajrydb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhoulong.xyz/Article/details/gt2jvwuuujb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhongyouzk.top/Article/details/gt2tsvovhns.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daxiang520.top/Article/details/gt2xybzzdka.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ppjwa.cn/Article/details/gt2jeoqqrft.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jyoumei.cn/Article/details/gt2kqntkzjw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.316326.xyz/Article/details/gt2exwhpdfa.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yvedp.cn/Article/details/gt2vkznemhz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nanxinkj.top/Article/details/gt2okyppmmd.html

[F03] 写入文件（覆盖）
来源：http://dali.aizwys.cn/Article/details/gt2ppegnjzq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jyoumei.cn/Article/details/gt2ddlmrdzn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.daxiang520.top/Article/details/gt2hqgzxpel.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258888.top/Article/details/gt2xoiceekh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ivvv.top/Article/details/gt2mrpqykuz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2okxeepgw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gynplmeg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cqqwz.cn/Article/details/gt2rksogksi.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhiwuduotai.top/Article/details/gt2njlnvwmx.html

[F04] 追加写入文件
来源：http://dali.ppjwa.cn/Article/details/gt2zhsbvctg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xlpspjzb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.dashuyun.cn/Article/details/gt2mfmnofwe.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yvedp.cn/Article/details/gt2pjvelndj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fkqqwzij.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ydzc1.top/Article/details/gt2ppnkxrzt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.redwolf501.top/Article/details/gt2xoxqjuln.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fgwbcsgn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqxwapz.html

[F05] 判断文件或目录是否存在
来源：http://dali.hnqzz.top/Article/details/gt2fbhgnshq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.birdmap.top/Article/details/gt2omealzac.html

PHP:  file_exists("a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2togmzuya.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2pydovfnp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2xyvnlaxt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2uytvjzvj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhiwuduotai.top/Article/details/gt2vnvhfwag.html

Ruby: File.exist?("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2zceylodr.html

C#:   File.Exists("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2ifahvdim.html

[F06] 删除文件
来源：http://dali.jqgfzy.top/Article/details/gt2uxybtmjq.html

Py:   os.remove("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2ciyiebbz.html

PHP:  unlink("a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2azgtzfaf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2ntdixeet.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2yfqlcsxv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2bpltkejb.html

Go:   os.Remove("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2kgauvcqr.html

Ruby: File.delete("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2guswfico.html

C#:   File.Delete("a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2tzfjlmjr.html

[F07] 创建目录（含多级）
来源：http://dali.0kj1m.cn/Article/details/gt2mmozxwke.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhoulong.xyz/Article/details/gt2blgihinj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xylfe.cn/Article/details/gt2qifgrfmw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj202588.top/Article/details/gt2abbvkupe.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangshuangyany.cn/Article/details/gt2klbdcspx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhengqikj.top/Article/details/gt2fwkeicze.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.nwbrower.top/Article/details/gt2jmbmuzgn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj202588.top/Article/details/gt2zihwhpot.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.fengsongda.top/Article/details/gt2mpktvcfb.html

[F08] 遍历目录
来源：http://dali.sxryk.cn/Article/details/gt2gsvvqkeb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.smart0.xyz/Article/details/gt2qmpqheuy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj202588.top/Article/details/gt2bojgnltx.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhixingplan.top/Article/details/gt2xvfjkuzc.html

TS:   fs.readdirSync("dir")
来源：http://dali.gotoacloud.top/Article/details/gt2xsxttbun.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eefalllf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sysykeji.top/Article/details/gt2eflyzdjk.html

Ruby: Dir.children("dir")
来源：http://dali.yj202588.top/Article/details/gt2khtyyxao.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gt2csvvbmff.html

[F09] 获取文件大小
来源：http://dali.hfpthk.cn/Article/details/gt2rbzddcjt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2xdmvouug.html

PHP:  filesize("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2douqnoto.html

JS:   fs.statSync("a.txt").size
来源：http://dali.dashuyun.cn/Article/details/gt2ezbgzerb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sysykeji.top/Article/details/gt2jihfzqxn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gt2kgvhedtr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tianlin.xyz/Article/details/gt2rvchjled.html

Ruby: File.size("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2tlvyhgfn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yuanzhike.top/Article/details/gt2vrvspgex.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kgnwoooq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2krglrnkm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2celrxogi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2tqcqptqn.html

TS:   path.extname("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2hrgqiont.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gogol.net.cn/Article/details/gt2dssrhsiv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gt2xkcecuau.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2jmcksfog.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2gmhdzkji.html

[F11] 复制与移动文件
来源：http://dali.yanxiufei.cn/Article/details/gt2rhnszisb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xhlxsviy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2kygyenmq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gt2pobitaij.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gt2wggmncyj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gt2kaczjfbt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.c1oappe.top/Article/details/gt2puvjybjm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gt2syorhtan.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gogol.net.cn/Article/details/gt2qburwrax.html

[F12] CSV 读写
来源：http://dali.cashguo.top/Article/details/gt2ldkbsoqz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhixingplan.top/Article/details/gt2nzlenvxq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xuanzx.com/Article/details/gt2ehxvqplh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ybcxt.top/Article/details/gt2fuslswdi.html

TS:   // 同上
来源：http://dali.316326.xyz/Article/details/gt2cxlmqntd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.c1oappe.top/Article/details/gt2dxsudphf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xuetiantiany.cn/Article/details/gt2kvcuvgec.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.pycfn.com/Article/details/gt2ldqvpnng.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.quarkkingdee.top/Article/details/gt2dxkmsyke.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2kukeowus.html

G. 面向对象
来源：http://dali.andypj.xyz/Article/details/gt2pzltobpi.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2agsbcmyg.html

[G01] 定义类
来源：http://dali.cqqwz.cn/Article/details/gt2drfjwmes.html

Py:   class User: pass
来源：http://dali.feifeiyinyue.top/Article/details/gt2ghnskiab.html

PHP:  class User {}
来源：http://dali.tianlin.xyz/Article/details/gt2yfogjjpl.html

JS:   class User {}
来源：http://dali.ivvv.top/Article/details/gt2doyuvjmz.html

TS:   class User { name: string = ""; }
来源：http://dali.cdnleiting.top/Article/details/gt2scnxmpvb.html

Java: class User {}
来源：http://dali.yuanzhike.top/Article/details/gt2iprusyyl.html

Go:   type User struct { Name string }
来源：http://dali.jinqigufen.top/Article/details/gt2pfsdsjbt.html

Ruby: class User; end
来源：http://dali.sysykeji.top/Article/details/gt2xqfijodv.html

C#:   class User {}
来源：http://dali.9152youxi.cn/Article/details/gt2atutwtnw.html

[G02] 构造函数
来源：http://dali.gzhubu.top/Article/details/gt2fitbxeht.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cqqwz.cn/Article/details/gt2rglujrhh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenlongwang.top/Article/details/gt2brtupyhl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xinyue.icu/Article/details/gt2yhhkqyhh.html

TS:   constructor(public name: string) {}
来源：http://dali.xinyue.icu/Article/details/gt2qigqmcpk.html

Java: User(String name) { this.name = name; }
来源：http://dali.sufxvd.cn/Article/details/gt2fifzzzja.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.feifeiyinyue.top/Article/details/gt2wbuydlfc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yonumen.top/Article/details/gt2khqhjbbd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tanke756.top/Article/details/gt2emdeczdy.html

[G03] 实例属性
来源：http://dali.tianlin.xyz/Article/details/gt2xlsqrcfb.html

Py:   self.name = "x"
来源：http://dali.chenzaomai.com/Article/details/gt2gwzxoxou.html

PHP:  public string $name = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gt2bcurqdmp.html

JS:   this.name = "x";
来源：http://dali.hysaishi.cn/Article/details/gt2riyycbvv.html

TS:   name: string = "x";
来源：http://dali.ydzc1.top/Article/details/gt2entmekei.html

Java: private String name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nudxkalq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.dianchejie.cn/Article/details/gt2itgmlntu.html

Ruby: @name = "x"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xmudwxat.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yuxming.cn/Article/details/gt2omjvzkao.html

[G04] 定义方法
来源：http://dali.gzhubu.top/Article/details/gt2baoxunez.html

Py:   def greet(self): return self.name
来源：http://dali.jinqigufen.top/Article/details/gt2hehaglay.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2axvepnyn.html

JS:   greet() { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gt2aeztfxei.html

TS:   greet(): string { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gt2oalvwxms.html

Java: String greet() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gt2lbmkjkld.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gt2atomowru.html

Ruby: def greet; @name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2npjuzyym.html

C#:   public string Greet() => Name;
来源：http://dali.gotoacloud.top/Article/details/gt2mwepcdep.html

[G05] 继承
来源：http://dali.kuanghao11.cn/Article/details/gt2ejrsrxcb.html

Py:   class Admin(User): pass
来源：http://dali.yj20258888.top/Article/details/gt2kmzvajpy.html

PHP:  class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mkinjfeu.html

JS:   class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2ztmsmrom.html

TS:   class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gt2rjlgmttg.html

Java: class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gt2oiwwhwbs.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhoulong.xyz/Article/details/gt2rnnecqgf.html

Ruby: class Admin < User; end
来源：http://dali.iojbl.cn/Article/details/gt2yrqppiuy.html

C#:   class Admin : User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2twjnlzeo.html

[G06] 重写方法
来源：http://dali.yongpay.top/Article/details/gt2tbvjxybb.html

Py:   def greet(self): return "admin"
来源：http://dali.chenzaomai.com/Article/details/gt2bbhgvrjm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gt2wenrigof.html

JS:   greet() { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2zabpgjca.html

TS:   greet(): string { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2vcbziael.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gt2sfzxjzcq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.vqdsnc.cn/Article/details/gt2qinwtshd.html

Ruby: def greet; "admin"; end
来源：http://dali.smart0.xyz/Article/details/gt2llefgxsz.html

C#:   public override string Greet() => "admin";
来源：http://dali.xuetiantiany.cn/Article/details/gt2ldfiwpkx.html

[G07] 调用父类方法
来源：http://dali.jlsjyb.cn/Article/details/gt2vlvxbtwk.html

Py:   super().greet()
来源：http://dali.chenzaomai.com/Article/details/gt2nfjqtrfi.html

PHP:  parent::greet();
来源：http://dali.sysykeji.top/Article/details/gt2gsqujted.html

JS:   super.greet();
来源：http://dali.zhoulong.xyz/Article/details/gt2vbkhmjod.html

TS:   super.greet();
来源：http://dali.yonumen.top/Article/details/gt2ewibqlkl.html

Java: super.greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xsklxmvz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jyoumei.cn/Article/details/gt2bmprrkid.html

Ruby: super
来源：http://dali.nanxuanxn.top/Article/details/gt2utjoilew.html

C#:   base.Greet();
来源：http://dali.hongshengwenyu.top/Article/details/gt2wsrplnen.html

[G08] 静态方法与属性
来源：http://dali.yanxiufei.cn/Article/details/gt2tqfvsmza.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.meibo888.top/Article/details/gt2rrjprimt.html

PHP:  public static function f() {}
来源：http://dali.cheryme.top/Article/details/gt2zrfmpbxl.html

JS:   static f() {}
来源：http://dali.shzxlz.cn/Article/details/gt2mmitxbgt.html

TS:   static f(): void {}
来源：http://dali.ivvv.top/Article/details/gt2gupjbioz.html

Java: static void f() {}
来源：http://dali.hammf.cn/Article/details/gt2ixaugvoc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hfpthk.cn/Article/details/gt2wqzoksct.html

Ruby: def self.f; end
来源：http://dali.gzhubu.top/Article/details/gt2lbsgexhh.html

C#:   public static void F() {}
来源：http://dali.cucudq.cn/Article/details/gt2cvivjmac.html

[G09] 接口 / 抽象类
来源：http://dali.hammf.cn/Article/details/gt2cwvhqbna.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mrgxzmvb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xpuctgdm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhiwuduotai.top/Article/details/gt2ibljtoco.html

TS:   interface Shape { area(): number; }
来源：http://dali.jqgfzy.top/Article/details/gt2zvsziljd.html

Java: interface Shape { double area(); }
来源：http://dali.cheryme.top/Article/details/gt2yhzhmiuk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.meibo888.top/Article/details/gt2rblixqki.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.fengsongda.top/Article/details/gt2ucuzhlnl.html

C#:   interface IShape { double Area(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2qbnlqsvc.html

[G10] 访问控制
来源：http://dali.nanxuanxn.top/Article/details/gt2rzixrhqx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hbggoqbn.html

PHP:  public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2isexejtg.html

JS:   #private 字段；其余公开
来源：http://dali.smart0.xyz/Article/details/gt2fffbguhs.html

TS:   public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gt2xyxuiecw.html

Java: public / protected / private / 默认包级
来源：http://dali.meibo888.top/Article/details/gt2abripvyg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sxryk.cn/Article/details/gt2zujevrns.html

Ruby: public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tzacaqrr.html

C#:   public / protected / private / internal
来源：http://dali.ivvv.top/Article/details/gt2jimvowgl.html

[G11] getter / setter
来源：http://dali.daria6918.cn/Article/details/gt2hjhqmjtd.html

Py:   @property 与 @x.setter
来源：http://dali.pycfn.com/Article/details/gt2rqiymihi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gt2wnntnjnw.html

JS:   get name() { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gt2nvfkxawk.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gt2uznoqfob.html

Java: public String getName() { return name; }
来源：http://dali.fzhhl.top/Article/details/gt2dwkajuqy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.feifeiyinyue.top/Article/details/gt2oufnwovn.html

Ruby: attr_accessor :name
来源：http://dali.dianchejie.cn/Article/details/gt2xjheifgd.html

C#:   public string Name { get; set; }
来源：http://dali.xuanzx.com/Article/details/gt2zzdskfwn.html

[G12] 对象转字符串
来源：http://dali.ppjwa.cn/Article/details/gt2ksgfvwxu.html

Py:   def __str__(self): return self.name
来源：http://dali.jiagoushi.top/Article/details/gt2zrvcpozw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2anamsjst.html

JS:   toString() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kdhektop.html

TS:   toString(): string { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ufhokkdd.html

Java: @Override public String toString() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gt2ejsqfpnz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.iojbl.cn/Article/details/gt2wacwiwqq.html

Ruby: def to_s; @name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ghautode.html

C#:   public override string ToString() => Name;
来源：http://dali.xuetiantiany.cn/Article/details/gt2nyirqtmm.html

[G13] 判断对象类型
来源：http://dali.jiagoushi.top/Article/details/gt2placekud.html

Py:   isinstance(u, User)
来源：http://dali.daxiang520.top/Article/details/gt2nscoaqfe.html

PHP:  $u instanceof User
来源：http://dali.jianghu66.top/Article/details/gt2hjapfrly.html

JS:   u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gt2loecxifq.html

TS:   u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gt2pvuzqyfd.html

Java: u instanceof User
来源：http://dali.bjfxy.top/Article/details/gt2ognsopal.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ybcxt.top/Article/details/gt2vtwjfmdf.html

Ruby: u.is_a?(User)
来源：http://dali.hongshengwenyu.top/Article/details/gt2tgebbqpd.html

C#:   u is User
来源：http://dali.gotoacloud.top/Article/details/gt2hzgevacs.html

[G14] 数据类 / record
来源：http://dali.haohaochexian.top/Article/details/gt2rskllags.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shzxlz.cn/Article/details/gt2hfcijvqk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.feifeiyinyue.top/Article/details/gt2ofqkljyv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nfnixcha.html

TS:   type User = { name: string; age: number };
来源：http://dali.dashuyun.cn/Article/details/gt2udujwurm.html

Java: record User(String name, int age) {}
来源：http://dali.meibo888.top/Article/details/gt2kdrrgsrm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cheryme.top/Article/details/gt2lfprncau.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.wangdashe.top/Article/details/gt2vjrltalz.html

C#:   record User(string Name, int Age);
来源：http://dali.yj20258.top/Article/details/gt2afkkjuod.html

[G15] 枚举
来源：http://dali.nanxinkj.top/Article/details/gt2rwxeiblw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xinyue.icu/Article/details/gt2grlrifzy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sweek.top/Article/details/gt2orezlhbw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yvedp.cn/Article/details/gt2lvxznvzk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fzhhl.top/Article/details/gt2bofpwwlw.html

Java: enum Color { RED, GREEN }
来源：http://dali.yueranfly.top/Article/details/gt2kvrixuqn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xinyue.icu/Article/details/gt2upzfvbeq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenzaomai.com/Article/details/gt2hqftjbuu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxinkj.top/Article/details/gt2cgbnswkr.html

[G16] 对象转数组 / 字典
来源：http://dali.jinqigfzy.top/Article/details/gt2uujefgaq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.daria6918.cn/Article/details/gt2lthwjkkr.html

PHP:  get_object_vars($obj);
来源：http://dali.sweek.top/Article/details/gt2fknjxcgp.html

JS:   Object.entries(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2jgahnqoo.html

TS:   Object.entries(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2axtiyokg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.fengsongda.top/Article/details/gt2iffwdajj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.daria6918.cn/Article/details/gt2eredqsvp.html

Ruby: obj.instance_variables
来源：http://dali.gotoacloud.top/Article/details/gt2xtcpfoue.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.havefunace.top/Article/details/gt2rwmzluqm.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2xcnfvsyp.html

H. 异常与错误处理
来源：http://dali.birdmap.top/Article/details/gt2xelspcrs.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2pdyguuiy.html

[H01] try / catch 基础
来源：http://dali.nanxinkj.top/Article/details/gt2acrjbtqx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.fzhhl.top/Article/details/gt2gvdqqrpu.html


<!-- 参考信息 -->