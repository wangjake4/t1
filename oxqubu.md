代发 wailian999

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.dianchejie.cn/Article/details/gtwyadxtdv.html

[E19] 多行文本按行拆分
来源：http://dali.snrcjt.cn/Article/details/gtpxmrkzxf.html

Py:   s.splitlines()
来源：http://dali.yonumen.top/Article/details/gtbqxogpbu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtvglnpixr.html

JS:   s.split(/\r?\n/)
来源：http://dali.xziqi.cn/Article/details/gtkmtbdleh.html

TS:   s.split(/\r?\n/)
来源：http://dali.sufxvd.cn/Article/details/gtmmtecbuk.html

Java: s.lines().toList()
来源：http://dali.mhx1999.top/Article/details/gtujsvopox.html

Go:   strings.Split(s, "\n")
来源：http://dali.hnqzz.top/Article/details/gtkzycekwv.html

Ruby: s.lines
来源：http://dali.zycfv.cn/Article/details/gtrewvpltj.html

C#:   s.Split('\n')
来源：http://dali.gotoacloud.top/Article/details/gtdqubvdch.html

[E20] 判断字符串是否为空
来源：http://dali.zdqjudy.top/Article/details/gtkkvqnqga.html

Py:   if not s:
来源：http://dali.tian-w.cn/Article/details/gtnwgdnrer.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tian-w.cn/Article/details/gtxvfhasrw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtwvlgmmux.html

TS:   if (s === "") {}
来源：http://dali.gogol.net.cn/Article/details/gtqgabmghk.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinqigfzy.top/Article/details/gtidpnuhka.html

Go:   if s == "" {}
来源：http://dali.shzxlz.cn/Article/details/gthvholetz.html

Ruby: if s.empty?
来源：http://dali.chenlongwang.top/Article/details/gtuxpcwwde.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xziqi.cn/Article/details/gtvnagnysr.html

[E21] 超长截断加省略号
来源：http://dali.zhixingplan.top/Article/details/gtfynpexmw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ehwqpu.com/Article/details/gtwzfitowr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gtqroowjzv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtrnvtffpe.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gthubflctb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gtfubvooze.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinghuilouyu.cn/Article/details/gtptmzqfeq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtdrgskxyx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gtddjhrfsa.html

[E22] 字节长度与字符长度
来源：http://dali.shangyingyoupin.top/Article/details/gtzkvzwfso.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.daxiang520.top/Article/details/gtersugcou.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gtmjtdggbg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gteekjapvc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nwbrower.top/Article/details/gtovwwtaha.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jqgufenzy.top/Article/details/gtwjvpchfp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.9152youxi.cn/Article/details/gtttbedjpu.html

Ruby: s.bytesize;  s.length
来源：http://dali.jlsjyb.cn/Article/details/gtoyoqfbah.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.fzhhl.top/Article/details/gtwvktiglj.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtvyskgmup.html

F. 文件与目录
来源：http://dali.bjfxy.top/Article/details/gtqbdfvycn.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtjgopxhqq.html

[F01] 读取整个文件
来源：http://dali.fzhhl.top/Article/details/gtzfzkrwnp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shangyingyoupin.top/Article/details/gtlbpcyjgt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtqcjleizc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinyuanbaomall.cn/Article/details/gthznomhhz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.daria6918.cn/Article/details/gtqpbmgemm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gtovroozfj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.dianchejie.cn/Article/details/gtyqfhkehn.html

Ruby: File.read("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtfssuogst.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtqxzzjaky.html

[F02] 逐行读取文件
来源：http://dali.shangyingyoupin.top/Article/details/gtnmtvsrrn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.chenzaomai.com/Article/details/gtykwegsul.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.feifeiyinyue.top/Article/details/gtgwveaqbw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shzxlz.cn/Article/details/gtjdysoloa.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pycfn.com/Article/details/gtgcqjejsp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sysykeji.top/Article/details/gtfwlxhtvd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinqigfzy.top/Article/details/gtiavpvseg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ehwqpu.com/Article/details/gtfxxkbkgm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yongpay.top/Article/details/gtpfgwzxfo.html

[F03] 写入文件（覆盖）
来源：http://dali.xylfe.cn/Article/details/gtaenmakch.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinqigufen.top/Article/details/gtyxsxamca.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nanxuanxn.top/Article/details/gtaucrpttt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gtxljodand.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.0kj1m.cn/Article/details/gtizcfgsad.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenzaomai.com/Article/details/gtojsewepv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nanxuanxn.top/Article/details/gtqjvovayz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cqqwz.cn/Article/details/gtroxvtoys.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sufxvd.cn/Article/details/gtnkytyelb.html

[F04] 追加写入文件
来源：http://dali.wangdashe.top/Article/details/gtkgtsvchh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhoulong.xyz/Article/details/gtspalogse.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.daxiang520.top/Article/details/gtnujhavjo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sweek.top/Article/details/gttioygkzl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.c1oappe.top/Article/details/gtcijwuyjh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.andypj.xyz/Article/details/gtjoqhwcua.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yongpay.top/Article/details/gtinncnnri.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hywenlv.cn/Article/details/gthkwafsih.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.andypj.xyz/Article/details/gtkajkfaeq.html

[F05] 判断文件或目录是否存在
来源：http://dali.hongshengwenyu.top/Article/details/gtfxosomhx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.haohaochexian.top/Article/details/gtylwqrakm.html

PHP:  file_exists("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtpjstfzfh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtnrwjaced.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtmqsqrlak.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gtahgvyxdf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shangyingyoupin.top/Article/details/gtqhqqkpae.html

Ruby: File.exist?("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtzyapnfqc.html

C#:   File.Exists("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtuxxadrxs.html

[F06] 删除文件
来源：http://dali.sweek.top/Article/details/gtdctjvjha.html

Py:   os.remove("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxcuspjzp.html

PHP:  unlink("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtivvbqtnm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtgixzdypv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtgyaxgvaz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtyqvrqcnw.html

Go:   os.Remove("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtkrwxfbbo.html

Ruby: File.delete("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gthhiwljzh.html

C#:   File.Delete("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gttotrqfln.html

[F07] 创建目录（含多级）
来源：http://dali.jinqigfzy.top/Article/details/gtpfbtiiem.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tanke756.top/Article/details/gtfyzbgncx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cdnleiting.top/Article/details/gtztemcvst.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xylfe.cn/Article/details/gtuzmovzgh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guannengcc.top/Article/details/gtrrqjubdz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj20258.top/Article/details/gttfuacmhd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jiagoushi.top/Article/details/gtegjciaqy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.dashuyun.cn/Article/details/gtfuiqaffv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.pycfn.com/Article/details/gtckkouffc.html

[F08] 遍历目录
来源：http://dali.zycfv.cn/Article/details/gtznysksjd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.9152youxi.cn/Article/details/gtasukpwud.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinqigfzy.top/Article/details/gtigvkursw.html

JS:   fs.readdirSync("dir")
来源：http://dali.ydzc1.top/Article/details/gtjqumjqkp.html

TS:   fs.readdirSync("dir")
来源：http://dali.zycfv.cn/Article/details/gtmncisfro.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jqgufenzy.top/Article/details/gtoejpbopq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.snrcjt.cn/Article/details/gtxkirgzrh.html

Ruby: Dir.children("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtleuofzgb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gaohongyu789.top/Article/details/gtoqpdpxzj.html

[F09] 获取文件大小
来源：http://dali.hnxiangtu.top/Article/details/gtbknzpzxm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtxtltbmnd.html

PHP:  filesize("a.txt");
来源：http://dali.havefunace.top/Article/details/gtmybfuyrw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhengqikj.top/Article/details/gtzmnknfiq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.kuanghao11.cn/Article/details/gtexebrpdb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gtsazajxhv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hnxiangtu.top/Article/details/gtlntlaafd.html

Ruby: File.size("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcfkuepmg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yvedp.cn/Article/details/gtjmhoekux.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhiwuduotai.top/Article/details/gtbfnajija.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtuifiecwy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xuanzx.com/Article/details/gtltcrqdir.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtoakhdecu.html

TS:   path.extname("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtqnpsvjar.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.guowangkeji.top/Article/details/gtwlbabqea.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtnowfjhym.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtbuiogmju.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrnpviwrm.html

[F11] 复制与移动文件
来源：http://dali.sxryk.cn/Article/details/gtdusehcnd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gtcejoryye.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sysykeji.top/Article/details/gtyilxjwfb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gtwkkusytx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtpavudiwu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdxvnqvod.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sxryk.cn/Article/details/gtxzapmqeg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gtkfuzufgw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj20258888.top/Article/details/gtctmxzjbi.html

[F12] CSV 读写
来源：http://dali.jinqigufen.top/Article/details/gtihdpxeps.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xziqi.cn/Article/details/gtwqjaznbd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zdqjudy.top/Article/details/gtqepvlcle.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkybbocim.html

TS:   // 同上
来源：http://dali.shangyingyoupin.top/Article/details/gtwcdbkgny.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yuxming.cn/Article/details/gtfihydfdd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gogol.net.cn/Article/details/gtcrkaryfu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sweek.top/Article/details/gtnighopmp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nwbrower.top/Article/details/gtrmebefyi.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtrlpfgnln.html

G. 面向对象
来源：http://dali.aibaodan.cn/Article/details/gtsmgufhee.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtxpzpregw.html

[G01] 定义类
来源：http://dali.chenjidiqi.icu/Article/details/gtdzeywpqd.html

Py:   class User: pass
来源：http://dali.sxryk.cn/Article/details/gtyabintuk.html

PHP:  class User {}
来源：http://dali.ehwqpu.com/Article/details/gtdwyqjtud.html

JS:   class User {}
来源：http://dali.yj20258.top/Article/details/gtxbgddhba.html

TS:   class User { name: string = ""; }
来源：http://dali.yj20258888.top/Article/details/gtwjldktlq.html

Java: class User {}
来源：http://dali.fzhhl.top/Article/details/gtynueirpp.html

Go:   type User struct { Name string }
来源：http://dali.jinqigufen.top/Article/details/gtainosgbd.html

Ruby: class User; end
来源：http://dali.ppjwa.cn/Article/details/gthcdifuph.html

C#:   class User {}
来源：http://dali.hammf.cn/Article/details/gtelvwtmlt.html

[G02] 构造函数
来源：http://dali.bjfxy.top/Article/details/gtlwwugeee.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hywenlv.cn/Article/details/gtgaqnsmzb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.fengsongda.top/Article/details/gtnkvdqric.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xziqi.cn/Article/details/gtewrypvdf.html

TS:   constructor(public name: string) {}
来源：http://dali.c1oappe.top/Article/details/gtsfblortb.html

Java: User(String name) { this.name = name; }
来源：http://dali.sysykeji.top/Article/details/gtxfrurzef.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shangyingyoupin.top/Article/details/gtwkuemzxi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.mhx1999.top/Article/details/gtbnmjtcrc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hywenlv.cn/Article/details/gtqddenzbv.html

[G03] 实例属性
来源：http://dali.cdnleiting.top/Article/details/gtevkbqegm.html

Py:   self.name = "x"
来源：http://dali.bjfxy.top/Article/details/gtmfhxolic.html

PHP:  public string $name = "x";
来源：http://dali.0kj1m.cn/Article/details/gtyxzbbndp.html

JS:   this.name = "x";
来源：http://dali.yueranfly.top/Article/details/gtrbessvbj.html

TS:   name: string = "x";
来源：http://dali.yvedp.cn/Article/details/gtseuqfcog.html

Java: private String name;
来源：http://dali.tanke756.top/Article/details/gtbcphjyuh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenlongwang.top/Article/details/gtidobrgpy.html

Ruby: @name = "x"
来源：http://dali.hnxiangtu.top/Article/details/gtdfgnmlss.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tian-w.cn/Article/details/gtshbfnrck.html

[G04] 定义方法
来源：http://dali.fzhhl.top/Article/details/gtnesmjzqv.html

Py:   def greet(self): return self.name
来源：http://dali.yuanzhike.top/Article/details/gtbvwqgmvc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtapomavoo.html

JS:   greet() { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gtmatxbnam.html

TS:   greet(): string { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gtbcgpwpyg.html

Java: String greet() { return name; }
来源：http://dali.sweek.top/Article/details/gtbinlnibq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gtxpuuohuq.html

Ruby: def greet; @name; end
来源：http://dali.sysykeji.top/Article/details/gtkvcpveln.html

C#:   public string Greet() => Name;
来源：http://dali.ydzc1.top/Article/details/gtxkhwittv.html

[G05] 继承
来源：http://dali.yvedp.cn/Article/details/gthobfspos.html

Py:   class Admin(User): pass
来源：http://dali.jianghu66.top/Article/details/gtgoxdiwoi.html

PHP:  class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtixrqfprb.html

JS:   class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gtgloedapj.html

TS:   class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtafkkzltu.html

Java: class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gtayutxcbs.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tian-w.cn/Article/details/gtkqppyhaa.html

Ruby: class Admin < User; end
来源：http://dali.guowangkeji.top/Article/details/gthufiakyn.html

C#:   class Admin : User {}
来源：http://dali.guowangkeji.top/Article/details/gtooujvtnj.html

[G06] 重写方法
来源：http://dali.gzhubu.top/Article/details/gtmhmkjatj.html

Py:   def greet(self): return "admin"
来源：http://dali.yuxming.cn/Article/details/gtwixxsufj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gtwkkgxlac.html

JS:   greet() { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyzoqkhjv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gtkrbfbmse.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gthunzrzro.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.guowangkeji.top/Article/details/gthnxxfsot.html

Ruby: def greet; "admin"; end
来源：http://dali.jiagoushi.top/Article/details/gtqfvjhrhv.html

C#:   public override string Greet() => "admin";
来源：http://dali.ydzc1.top/Article/details/gtjeintmqq.html

[G07] 调用父类方法
来源：http://dali.xylfe.cn/Article/details/gtzrhouamu.html

Py:   super().greet()
来源：http://dali.0kj1m.cn/Article/details/gtxmyvjgmg.html

PHP:  parent::greet();
来源：http://dali.yuanzhike.top/Article/details/gtjfsrenpa.html

JS:   super.greet();
来源：http://dali.yj20258.top/Article/details/gtklsbvvbo.html

TS:   super.greet();
来源：http://dali.iojbl.cn/Article/details/gtomnbgawv.html

Java: super.greet();
来源：http://dali.cdnleiting.top/Article/details/gtyeqahiyn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gotoacloud.top/Article/details/gtlkjdlebu.html

Ruby: super
来源：http://dali.jinqigufen.top/Article/details/gtdvjicbri.html

C#:   base.Greet();
来源：http://dali.vqdsnc.cn/Article/details/gtfsztlyyq.html

[G08] 静态方法与属性
来源：http://dali.yanxiufei.cn/Article/details/gtlvjfkaxu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhongyouzk.top/Article/details/gtfdxoaybg.html

PHP:  public static function f() {}
来源：http://dali.gaohongyu789.top/Article/details/gtzpvpjgze.html

JS:   static f() {}
来源：http://dali.xylfe.cn/Article/details/gtzwgujbai.html

TS:   static f(): void {}
来源：http://dali.aizwys.cn/Article/details/gtcpkarfhi.html

Java: static void f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbprjjxvk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.dianchejie.cn/Article/details/gtybhpaakb.html

Ruby: def self.f; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsaxvmkea.html

C#:   public static void F() {}
来源：http://dali.jianghu66.top/Article/details/gtryhygyuh.html

[G09] 接口 / 抽象类
来源：http://dali.nanxuanxn.top/Article/details/gtfcatplou.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xuetiantiany.cn/Article/details/gtemoxsrgc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ybcxt.top/Article/details/gtvlnmqukc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sxryk.cn/Article/details/gtsbafztay.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj20258888.top/Article/details/gtjgghzpxe.html

Java: interface Shape { double area(); }
来源：http://dali.cdnleiting.top/Article/details/gtsojbuaij.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.c1oappe.top/Article/details/gtznzopuue.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.dashuyun.cn/Article/details/gtlmxqqrfc.html

C#:   interface IShape { double Area(); }
来源：http://dali.ydzc1.top/Article/details/gtngmpiftg.html

[G10] 访问控制
来源：http://dali.zhoulong.xyz/Article/details/gtpvinsyyl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrtsimeqx.html

PHP:  public / protected / private
来源：http://dali.yj20258.top/Article/details/gtgzjapdec.html

JS:   #private 字段；其余公开
来源：http://dali.jlsjyb.cn/Article/details/gtgjuefzrr.html

TS:   public / protected / private
来源：http://dali.xziqi.cn/Article/details/gtunkkhegb.html

Java: public / protected / private / 默认包级
来源：http://dali.andypj.xyz/Article/details/gtrwnstbjk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sufxvd.cn/Article/details/gtpxesefwk.html

Ruby: public / protected / private
来源：http://dali.mhx1999.top/Article/details/gtsmuxkbcx.html

C#:   public / protected / private / internal
来源：http://dali.hongshengwenyu.top/Article/details/gttufqfbbd.html

[G11] getter / setter
来源：http://dali.cdnleiting.top/Article/details/gtxrmnbijm.html

Py:   @property 与 @x.setter
来源：http://dali.dashuyun.cn/Article/details/gtpiodglev.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gtkamwrprd.html

JS:   get name() { return this._name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtydnwmryx.html

TS:   get name(): string { return this._name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtxkrboldf.html

Java: public String getName() { return name; }
来源：http://dali.tian-w.cn/Article/details/gtlkaaxrwq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gtsaxchdbb.html

Ruby: attr_accessor :name
来源：http://dali.kuanghao11.cn/Article/details/gtwzflqufz.html

C#:   public string Name { get; set; }
来源：http://dali.haohaochexian.top/Article/details/gtbpgurfap.html

[G12] 对象转字符串
来源：http://dali.sweek.top/Article/details/gtnylrjqlc.html

Py:   def __str__(self): return self.name
来源：http://dali.jinghuilouyu.cn/Article/details/gtreayjqmc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gthknhcsop.html

JS:   toString() { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gtxhgnqctb.html

TS:   toString(): string { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gtvtstlzyp.html

Java: @Override public String toString() { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtxvuwuwth.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gtolkevgcw.html

Ruby: def to_s; @name; end
来源：http://dali.svipenyu.cn/Article/details/gtkoahjoun.html

C#:   public override string ToString() => Name;
来源：http://dali.daxiang520.top/Article/details/gtvgmphihv.html

[G13] 判断对象类型
来源：http://dali.gzhubu.top/Article/details/gtxvgclutm.html

Py:   isinstance(u, User)
来源：http://dali.cheryme.top/Article/details/gtyubvsdjc.html

PHP:  $u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtosgjdlqu.html

JS:   u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gtyslxzqer.html

TS:   u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gtrdbknmxh.html

Java: u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtjpdxgjvs.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xuanzx.com/Article/details/gtrcpzoxmi.html

Ruby: u.is_a?(User)
来源：http://dali.svipenyu.cn/Article/details/gtijrrvifa.html

C#:   u is User
来源：http://dali.shzxlz.cn/Article/details/gtldeqozze.html

[G14] 数据类 / record
来源：http://dali.yuxming.cn/Article/details/gtiqlfcwoy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.redwolf501.top/Article/details/gtzabwnter.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shuidangran.top/Article/details/gtcslufazu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.haohaochexian.top/Article/details/gtwxhvdcws.html

TS:   type User = { name: string; age: number };
来源：http://dali.iojbl.cn/Article/details/gtffzvrxkt.html

Java: record User(String name, int age) {}
来源：http://dali.sxryk.cn/Article/details/gtkxusdynq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenlongwang.top/Article/details/gtqkkhmher.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jqgufenzy.top/Article/details/gtilvdvbqe.html

C#:   record User(string Name, int Age);
来源：http://dali.sufxvd.cn/Article/details/gtkvyxpeee.html

[G15] 枚举
来源：http://dali.cheryme.top/Article/details/gtrwvhmtin.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.meibo888.top/Article/details/gtgkdkjktg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhengqikj.top/Article/details/gtodocxbha.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj20258.top/Article/details/gtsskcmhfl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jianghu66.top/Article/details/gtmnmzdzoz.html

Java: enum Color { RED, GREEN }
来源：http://dali.dianchejie.cn/Article/details/gtosfagniq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenzaomai.com/Article/details/gtyvwluqvp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yj20258888.top/Article/details/gtcynzpscc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigufen.top/Article/details/gtiisfhhbz.html

[G16] 对象转数组 / 字典
来源：http://dali.mhx1999.top/Article/details/gtgpjawscr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tianlin.xyz/Article/details/gtfygcprxu.html

PHP:  get_object_vars($obj);
来源：http://dali.jiagoushi.top/Article/details/gtreckavwy.html

JS:   Object.entries(obj)
来源：http://dali.svipenyu.cn/Article/details/gtiuffnclq.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtuoyufwmg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.0kj1m.cn/Article/details/gtbsdttmcz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shangyingyoupin.top/Article/details/gtppolktmw.html

Ruby: obj.instance_variables
来源：http://dali.sxryk.cn/Article/details/gtwmxcbzcy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.dianchejie.cn/Article/details/gtsyjvxlhj.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtigbyprtg.html

H. 异常与错误处理
来源：http://dali.tanke756.top/Article/details/gtislcwxzi.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtxkptloaz.html

[H01] try / catch 基础
来源：http://dali.wangdashe.top/Article/details/gtisjwvjca.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yangfankeji.com/Article/details/gtddbcnueh.html


<!-- 参考信息 -->