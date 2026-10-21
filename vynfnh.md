代发 wailian999

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gtucabomrb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtgszeuzvu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yj202588.top/Article/details/gtqboqdkko.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.wangshuangyany.cn/Article/details/gtgsbcvmso.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yangfankeji.com/Article/details/gtzuavsphl.html

[E19] 多行文本按行拆分
来源：http://dali.andypj.xyz/Article/details/gtileilvnh.html

Py:   s.splitlines()
来源：http://dali.bjfxy.top/Article/details/gtpwzykguz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cashguo.top/Article/details/gtfwqxpyye.html

JS:   s.split(/\r?\n/)
来源：http://dali.0kj1m.cn/Article/details/gtehztfrmf.html

TS:   s.split(/\r?\n/)
来源：http://dali.ivvv.top/Article/details/gtynbcqjnf.html

Java: s.lines().toList()
来源：http://dali.bjfxy.top/Article/details/gtvhesmlrk.html

Go:   strings.Split(s, "\n")
来源：http://dali.xylfe.cn/Article/details/gtfudxtpdj.html

Ruby: s.lines
来源：http://dali.xuetiantiany.cn/Article/details/gtbadrgkng.html

C#:   s.Split('\n')
来源：http://dali.sweek.top/Article/details/gtaqslspvf.html

[E20] 判断字符串是否为空
来源：http://dali.chenzaomai.com/Article/details/gttwigygdh.html

Py:   if not s:
来源：http://dali.wangshuangyany.cn/Article/details/gtvsysyhmf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yueranfly.top/Article/details/gtntbkvqan.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yuanzhike.top/Article/details/gtvkivysfq.html

TS:   if (s === "") {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfgumkcek.html

Java: if (s.isEmpty()) {}
来源：http://dali.nwbrower.top/Article/details/gtvprjyxgp.html

Go:   if s == "" {}
来源：http://dali.hnxiangtu.top/Article/details/gteflinekf.html

Ruby: if s.empty?
来源：http://dali.vqdsnc.cn/Article/details/gtkmbiuziy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gtxsqgfhfz.html

[E21] 超长截断加省略号
来源：http://dali.zhiwuduotai.top/Article/details/gtfpfxbtwi.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jiagoushi.top/Article/details/gtrcjwgrcl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gthvvbtdvj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtervbdpyz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtggfsctbo.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sxryk.cn/Article/details/gtcmryrriv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hnxiangtu.top/Article/details/gtgzoqzike.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtanyjmyuw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gtttahgshq.html

[E22] 字节长度与字符长度
来源：http://dali.ydzc1.top/Article/details/gtldshkxax.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtsaxigwoj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gtswpbgqhs.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jiagoushi.top/Article/details/gtlxzkehny.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.c1oappe.top/Article/details/gteesurons.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.feifeiyinyue.top/Article/details/gtcmofrcsh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.kuanghao11.cn/Article/details/gtjmcsvajd.html

Ruby: s.bytesize;  s.length
来源：http://dali.guowangkeji.top/Article/details/gtgszzzstg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jiagoushi.top/Article/details/gtpvtnmonc.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtyuxgpykh.html

F. 文件与目录
来源：http://dali.sweek.top/Article/details/gtgbihbzgk.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtbrqignwi.html

[F01] 读取整个文件
来源：http://dali.zhixingplan.top/Article/details/gtxhnsobbv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.aibaodan.cn/Article/details/gtypnjmwig.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hnqzz.top/Article/details/gttmaempwi.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xziqi.cn/Article/details/gtnianaboh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhixingplan.top/Article/details/gtyddsqdpm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtooymjkag.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hammf.cn/Article/details/gtpezjxgwz.html

Ruby: File.read("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtuwqmyita.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtajxnniuu.html

[F02] 逐行读取文件
来源：http://dali.jinqigfzy.top/Article/details/gtipmwthtm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.chenlongwang.top/Article/details/gtngzeesfz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhengqikj.top/Article/details/gtebtrmbwm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlhntsxfb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.haohaochexian.top/Article/details/gtjuwfgtby.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ehwqpu.com/Article/details/gtkyxhjikf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.guowangkeji.top/Article/details/gteqgoftyq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jqgfzy.top/Article/details/gtvnduzacy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xinyue.icu/Article/details/gtgkibcovh.html

[F03] 写入文件（覆盖）
来源：http://dali.ybcxt.top/Article/details/gtodedowjf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.guannengcc.top/Article/details/gtkoofpxye.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.svipenyu.cn/Article/details/gtuhvjbbwx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrbtvhuwq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gtqtelaert.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.c1oappe.top/Article/details/gtbcubaknw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.9152youxi.cn/Article/details/gtajqgmulg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shzxlz.cn/Article/details/gtpxjpxkbw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hysaishi.cn/Article/details/gtshhwsbbk.html

[F04] 追加写入文件
来源：http://dali.chenlongwang.top/Article/details/gtbnllcikr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvzvylgjx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.chenlongwang.top/Article/details/gtbhkcqtqm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigfzy.top/Article/details/gtxkpuynee.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.haohaochexian.top/Article/details/gtqtkrdvqk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gtoonzovmg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shzxlz.cn/Article/details/gtkbmesgjv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ybcxt.top/Article/details/gtubqjhnuf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sweek.top/Article/details/gtzrbcjpas.html

[F05] 判断文件或目录是否存在
来源：http://dali.xylfe.cn/Article/details/gtmscgculk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xziqi.cn/Article/details/gtvokgbtkj.html

PHP:  file_exists("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtolvznaix.html

JS:   fs.existsSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtloslbnxw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtgdpxvcgq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gtpvjebdss.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.haohaochexian.top/Article/details/gtnpvapcgw.html

Ruby: File.exist?("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtfcmkcerj.html

C#:   File.Exists("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtadmmjrqw.html

[F06] 删除文件
来源：http://dali.wangshuangyany.cn/Article/details/gtjksavnbe.html

Py:   os.remove("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtpftuqyoh.html

PHP:  unlink("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtqbqucrfi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtfmtbtvev.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcdepmguo.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtvfwlssan.html

Go:   os.Remove("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtrsjmntis.html

Ruby: File.delete("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtefmmvnwo.html

C#:   File.Delete("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtxnxfuzzy.html

[F07] 创建目录（含多级）
来源：http://dali.nwbrower.top/Article/details/gtvdddejth.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shzxlz.cn/Article/details/gtzhesbdov.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hysaishi.cn/Article/details/gtpmuofovk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.kuanghao11.cn/Article/details/gtoqjdunng.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tian-w.cn/Article/details/gtcylkiazj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.daxiang520.top/Article/details/gtkqhhuoum.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.wangshuangyany.cn/Article/details/gtrcrxgjjw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinqigufen.top/Article/details/gtkatyinby.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinqigufen.top/Article/details/gtrevfmhuy.html

[F08] 遍历目录
来源：http://dali.guannengcc.top/Article/details/gtonpidonw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.dianchejie.cn/Article/details/gtbyxabbuz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shangyingyoupin.top/Article/details/gtvjddtlbj.html

JS:   fs.readdirSync("dir")
来源：http://dali.ppjwa.cn/Article/details/gtviosaxst.html

TS:   fs.readdirSync("dir")
来源：http://dali.guowangkeji.top/Article/details/gteddmiovz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yueranfly.top/Article/details/gtxrcienrg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtnuhhhrtx.html

Ruby: Dir.children("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwnsvaeco.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtyrkjffoy.html

[F09] 获取文件大小
来源：http://dali.guowangkeji.top/Article/details/gterzqjxdu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtgdligkgu.html

PHP:  filesize("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gttkeaimnv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.pycfn.com/Article/details/gtkynuwkaj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinqigufen.top/Article/details/gtdsfpirte.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtyqkslahq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hywenlv.cn/Article/details/gtuqqwogzp.html

Ruby: File.size("a.txt")
来源：http://dali.meibo888.top/Article/details/gtwjralpga.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenjidiqi.icu/Article/details/gtkmshzklk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj20258888.top/Article/details/gtdvmfcgub.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtpkraazsk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.havefunace.top/Article/details/gtqwyojzyc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtimfkmxlt.html

TS:   path.extname("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtuofrtryf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.iojbl.cn/Article/details/gtihfttrub.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtkfmgdmoo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gteyqcsuui.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtlisallid.html

[F11] 复制与移动文件
来源：http://dali.yonumen.top/Article/details/gtffvvtevk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtbeuccdar.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhengqikj.top/Article/details/gtcwjofqdz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gthbaaoacj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtwbteetaf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.c1oappe.top/Article/details/gtaxvnrltj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sufxvd.cn/Article/details/gtaolniwjy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtmlywmfog.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cucudq.cn/Article/details/gtcicffmag.html

[F12] CSV 读写
来源：http://dali.jianghu66.top/Article/details/gtpnvxojcn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hongshengwenyu.top/Article/details/gtbztopffg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cheryme.top/Article/details/gtxwpknque.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tanke756.top/Article/details/gtgtuabhza.html

TS:   // 同上
来源：http://dali.hysaishi.cn/Article/details/gttgghiuxl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.guowangkeji.top/Article/details/gtxgspfkey.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hysaishi.cn/Article/details/gtghzrovey.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.feifeiyinyue.top/Article/details/gtxnigghgs.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.svipenyu.cn/Article/details/gtgujdeizm.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtwpcdcicj.html

G. 面向对象
来源：http://dali.316326.xyz/Article/details/gtliaeidvu.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtemurzmhq.html

[G01] 定义类
来源：http://dali.hongshengwenyu.top/Article/details/gtqlchvxja.html

Py:   class User: pass
来源：http://dali.sxryk.cn/Article/details/gtttyccusk.html

PHP:  class User {}
来源：http://dali.hfpthk.cn/Article/details/gtxmafiukh.html

JS:   class User {}
来源：http://dali.wangdashe.top/Article/details/gtwwppmrab.html

TS:   class User { name: string = ""; }
来源：http://dali.smart0.xyz/Article/details/gtivhyvdmx.html

Java: class User {}
来源：http://dali.hywenlv.cn/Article/details/gtxvnwsrac.html

Go:   type User struct { Name string }
来源：http://dali.fengsongda.top/Article/details/gtovfelkip.html

Ruby: class User; end
来源：http://dali.chenzaomai.com/Article/details/gtfwznqslw.html

C#:   class User {}
来源：http://dali.iojbl.cn/Article/details/gtuvlvmruz.html

[G02] 构造函数
来源：http://dali.yangfankeji.com/Article/details/gtjeuyoest.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tianlin.xyz/Article/details/gtavgilnkj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.wangdashe.top/Article/details/gtgjlxinqh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.nanxinkj.top/Article/details/gtgjqxjbpy.html

TS:   constructor(public name: string) {}
来源：http://dali.cucudq.cn/Article/details/gtgfclvllo.html

Java: User(String name) { this.name = name; }
来源：http://dali.hywenlv.cn/Article/details/gtotorfoir.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yanxiufei.cn/Article/details/gtdndevfmt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jyoumei.cn/Article/details/gtleixritl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gtjxvnhjzf.html

[G03] 实例属性
来源：http://dali.daria6918.cn/Article/details/gtksjaygfe.html

Py:   self.name = "x"
来源：http://dali.nwbrower.top/Article/details/gtgekwoxxu.html

PHP:  public string $name = "x";
来源：http://dali.0kj1m.cn/Article/details/gtnptgpnxt.html

JS:   this.name = "x";
来源：http://dali.cheryme.top/Article/details/gtnvbsqxjd.html

TS:   name: string = "x";
来源：http://dali.yonumen.top/Article/details/gtkdyjyzlc.html

Java: private String name;
来源：http://dali.guannengcc.top/Article/details/gtszubfrjm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xziqi.cn/Article/details/gtpfaohwwp.html

Ruby: @name = "x"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuuluhrah.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gtblyfndjd.html

[G04] 定义方法
来源：http://dali.shuidangran.top/Article/details/gtkhrndxpd.html

Py:   def greet(self): return self.name
来源：http://dali.jqgufenzy.top/Article/details/gtvshbtege.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqzrotvou.html

JS:   greet() { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gtkzrzyejy.html

TS:   greet(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtdzfwdukf.html

Java: String greet() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gtenqxiamt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gtocgiipyb.html

Ruby: def greet; @name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwfnocybf.html

C#:   public string Greet() => Name;
来源：http://dali.0kj1m.cn/Article/details/gtefhlsndl.html

[G05] 继承
来源：http://dali.shanyushiyangtech.top/Article/details/gtuhsvsqox.html

Py:   class Admin(User): pass
来源：http://dali.yueranfly.top/Article/details/gtdqdanutu.html

PHP:  class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gtqgdwosso.html

JS:   class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gtysyoowqd.html

TS:   class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gtvhgnlqjw.html

Java: class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gtwtrhcgco.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj20258888.top/Article/details/gtuzlynzib.html

Ruby: class Admin < User; end
来源：http://dali.andypj.xyz/Article/details/gtzqbyrkan.html

C#:   class Admin : User {}
来源：http://dali.snrcjt.cn/Article/details/gtkaocggam.html

[G06] 重写方法
来源：http://dali.c1oappe.top/Article/details/gtgndubzky.html

Py:   def greet(self): return "admin"
来源：http://dali.nwbrower.top/Article/details/gtpkjzsaaq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtvrmnehfj.html

JS:   greet() { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gttgflagxc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtcjmxjqux.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gtwbkzajzo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cqqwz.cn/Article/details/gtzsidxwft.html

Ruby: def greet; "admin"; end
来源：http://dali.mhx1999.top/Article/details/gtoiyttmye.html

C#:   public override string Greet() => "admin";
来源：http://dali.hfpthk.cn/Article/details/gtsvjlzkzq.html

[G07] 调用父类方法
来源：http://dali.cashguo.top/Article/details/gteflxrwzp.html

Py:   super().greet()
来源：http://dali.hfpthk.cn/Article/details/gtvpjmfqiq.html

PHP:  parent::greet();
来源：http://dali.redwolf501.top/Article/details/gtbwrhwrtd.html

JS:   super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtlbsylgkz.html

TS:   super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtuofadxcb.html

Java: super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjnhufept.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jqgufenzy.top/Article/details/gtdeevzxnb.html

Ruby: super
来源：http://dali.zhixingplan.top/Article/details/gtnwwcrgkw.html

C#:   base.Greet();
来源：http://dali.yuxming.cn/Article/details/gtuyluzded.html

[G08] 静态方法与属性
来源：http://dali.shuidangran.top/Article/details/gtkkrpjbce.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shanyushiyangtech.top/Article/details/gtqrddxqqd.html

PHP:  public static function f() {}
来源：http://dali.sysykeji.top/Article/details/gteffqdvkx.html

JS:   static f() {}
来源：http://dali.yj20258888.top/Article/details/gtribphrhr.html

TS:   static f(): void {}
来源：http://dali.jiagoushi.top/Article/details/gtoctsogyt.html

Java: static void f() {}
来源：http://dali.redwolf501.top/Article/details/gtqrokkboq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xziqi.cn/Article/details/gttvxjudpk.html

Ruby: def self.f; end
来源：http://dali.svipenyu.cn/Article/details/gtteppafdh.html

C#:   public static void F() {}
来源：http://dali.chenzaomai.com/Article/details/gtfaglojme.html

[G09] 接口 / 抽象类
来源：http://dali.ywan-chungtsiang.top/Article/details/gtonhpepib.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.daxiang520.top/Article/details/gtpflichfz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tian-w.cn/Article/details/gtdwqjtzdh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hnxiangtu.top/Article/details/gtmrrnbark.html

TS:   interface Shape { area(): number; }
来源：http://dali.shzxlz.cn/Article/details/gtsufnxoeg.html

Java: interface Shape { double area(); }
来源：http://dali.meibo888.top/Article/details/gtoxlooeno.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenzaomai.com/Article/details/gtemwiiboa.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.daxiang520.top/Article/details/gthutxdntz.html

C#:   interface IShape { double Area(); }
来源：http://dali.fzhhl.top/Article/details/gtkifezgpg.html

[G10] 访问控制
来源：http://dali.hfpthk.cn/Article/details/gthporgsjg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xylfe.cn/Article/details/gtnqclrdhk.html

PHP:  public / protected / private
来源：http://dali.gzhubu.top/Article/details/gtgfpvnetk.html

JS:   #private 字段；其余公开
来源：http://dali.c1oappe.top/Article/details/gtrenbfinc.html

TS:   public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gtrzjfwaoq.html

Java: public / protected / private / 默认包级
来源：http://dali.kuanghao11.cn/Article/details/gtcuayqosk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.iojbl.cn/Article/details/gtksebuxer.html

Ruby: public / protected / private
来源：http://dali.nanxuanxn.top/Article/details/gtvsowioyo.html

C#:   public / protected / private / internal
来源：http://dali.jlsjyb.cn/Article/details/gtudioepkc.html

[G11] getter / setter
来源：http://dali.snrcjt.cn/Article/details/gtxcbirhfo.html

Py:   @property 与 @x.setter
来源：http://dali.ydzc1.top/Article/details/gtycwgmghs.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gtzcnsryta.html

JS:   get name() { return this._name; }
来源：http://dali.aibaodan.cn/Article/details/gtalfhodyl.html

TS:   get name(): string { return this._name; }
来源：http://dali.jlsjyb.cn/Article/details/gtmacfjipq.html

Java: public String getName() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtthoirjzl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gtlvfmdonk.html

Ruby: attr_accessor :name
来源：http://dali.shanyushiyangtech.top/Article/details/gtxlsuebdd.html

C#:   public string Name { get; set; }
来源：http://dali.feifeiyinyue.top/Article/details/gtwyhaiaxr.html

[G12] 对象转字符串
来源：http://dali.cheryme.top/Article/details/gtinmtcnci.html

Py:   def __str__(self): return self.name
来源：http://dali.pengpengdd.cyou/Article/details/gtkflhgabk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gtkdjgqdan.html

JS:   toString() { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gtxasbafir.html

TS:   toString(): string { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtjgyysper.html

Java: @Override public String toString() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtiehfzaya.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinqigfzy.top/Article/details/gtdbkvlaad.html

Ruby: def to_s; @name; end
来源：http://dali.svipenyu.cn/Article/details/gtuasjkdgs.html

C#:   public override string ToString() => Name;
来源：http://dali.jianghu66.top/Article/details/gtfvevnivo.html

[G13] 判断对象类型
来源：http://dali.vqdsnc.cn/Article/details/gtftuhkbgx.html

Py:   isinstance(u, User)
来源：http://dali.pengpengdd.cyou/Article/details/gtzpegikhb.html

PHP:  $u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtoduobumk.html

JS:   u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gtioatcnwl.html

TS:   u instanceof User
来源：http://dali.yueranfly.top/Article/details/gtpyzibxfr.html

Java: u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gtjggkvtrq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tian-w.cn/Article/details/gtimnuqkve.html

Ruby: u.is_a?(User)
来源：http://dali.jyoumei.cn/Article/details/gtahmdlzfo.html

C#:   u is User
来源：http://dali.hysaishi.cn/Article/details/gtvysocfvi.html

[G14] 数据类 / record
来源：http://dali.zhaomingkeji.xyz/Article/details/gtamuzopls.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dashuyun.cn/Article/details/gtkrycwnly.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.iojbl.cn/Article/details/gtltzjyehi.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhongyouzk.top/Article/details/gtnjpcwebi.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj20258.top/Article/details/gtozhhkkat.html

Java: record User(String name, int age) {}
来源：http://dali.fengsongda.top/Article/details/gtnxmfezhf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.daxiang520.top/Article/details/gttkhwjsty.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinghuilouyu.cn/Article/details/gtytbzqmdy.html

C#:   record User(string Name, int Age);
来源：http://dali.zhiwuduotai.top/Article/details/gtzeppvhll.html

[G15] 枚举
来源：http://dali.ybcxt.top/Article/details/gtjbutsdzs.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xinyue.icu/Article/details/gtsrlzoqwf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gaohongyu789.top/Article/details/gtcjmzzwzd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.daria6918.cn/Article/details/gtzcylquxl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daria6918.cn/Article/details/gthkfblbij.html

Java: enum Color { RED, GREEN }
来源：http://dali.sweek.top/Article/details/gtpbetjlod.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gaohongyu789.top/Article/details/gtyosexion.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqeuczmwh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.smart0.xyz/Article/details/gtzklplbrw.html

[G16] 对象转数组 / 字典
来源：http://dali.tian-w.cn/Article/details/gtmxhovmtb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.vqdsnc.cn/Article/details/gthygsldmf.html

PHP:  get_object_vars($obj);
来源：http://dali.cqqwz.cn/Article/details/gtwdhbfvro.html

JS:   Object.entries(obj)
来源：http://dali.snrcjt.cn/Article/details/gtyzdbybir.html

TS:   Object.entries(obj)
来源：http://dali.ehwqpu.com/Article/details/gtjwuvrzpz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.quarkkingdee.top/Article/details/gtznkyynty.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shanyushiyangtech.top/Article/details/gtlumfssyx.html

Ruby: obj.instance_variables
来源：http://dali.yj20258.top/Article/details/gtjfoauqbx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhengqikj.top/Article/details/gtgfxbrjtm.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtijpbkcsi.html


<!-- 参考信息 -->