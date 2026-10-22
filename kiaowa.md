代发 wailian999

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gtezabdxie.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.c1oappe.top/Article/details/gtsjgosaqj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gtewgbuknd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.pengpengdd.cyou/Article/details/gtgjlftkkw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.chenjidiqi.icu/Article/details/gtjcczknuv.html

[E19] 多行文本按行拆分
来源：http://dali.dashuyun.cn/Article/details/gtktrdltij.html

Py:   s.splitlines()
来源：http://dali.snrcjt.cn/Article/details/gtxbnfopxs.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.sweek.top/Article/details/gtwslwdzbt.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhengqikj.top/Article/details/gtszraznhk.html

TS:   s.split(/\r?\n/)
来源：http://dali.ybcxt.top/Article/details/gtodcrifoq.html

Java: s.lines().toList()
来源：http://dali.cucudq.cn/Article/details/gtqylnkeep.html

Go:   strings.Split(s, "\n")
来源：http://dali.jlsjyb.cn/Article/details/gthvtcxvyo.html

Ruby: s.lines
来源：http://dali.zdqjudy.top/Article/details/gtjsuhcamx.html

C#:   s.Split('\n')
来源：http://dali.iojbl.cn/Article/details/gtvmprtnbg.html

[E20] 判断字符串是否为空
来源：http://dali.guannengcc.top/Article/details/gthmudzhht.html

Py:   if not s:
来源：http://dali.smart0.xyz/Article/details/gtpuiyzdca.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xinyue.icu/Article/details/gthaeqhhfw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.aizwys.cn/Article/details/gtaxosixyk.html

TS:   if (s === "") {}
来源：http://dali.tian-w.cn/Article/details/gtlrsknrjk.html

Java: if (s.isEmpty()) {}
来源：http://dali.shzxlz.cn/Article/details/gtpbvjifug.html

Go:   if s == "" {}
来源：http://dali.ppjwa.cn/Article/details/gtstpsqkwi.html

Ruby: if s.empty?
来源：http://dali.dianchejie.cn/Article/details/gthqkwbjbq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.aibaodan.cn/Article/details/gtcxyechsz.html

[E21] 超长截断加省略号
来源：http://dali.jyoumei.cn/Article/details/gtmskbnzqb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tianlin.xyz/Article/details/gtlhjuelqe.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gthxbpgpwa.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gthgaidkhz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtvrzzttwv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtaftvbtaw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.quarkkingdee.top/Article/details/gtritfkxjd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtouoxwwpu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yj20258.top/Article/details/gtuktzmziw.html

[E22] 字节长度与字符长度
来源：http://dali.yueranfly.top/Article/details/gtloxfwmoo.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.chenlongwang.top/Article/details/gtxhajgmmd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gtuexegwtq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sysykeji.top/Article/details/gtpzoqmwci.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigufen.top/Article/details/gtfopnqgpz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hnqzz.top/Article/details/gtkebutmzw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhongyouzk.top/Article/details/gtqhnzpkwl.html

Ruby: s.bytesize;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtiaaungmz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.haohaochexian.top/Article/details/gtfyzzlwuw.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtyejrmegl.html

F. 文件与目录
来源：http://dali.kuanghao11.cn/Article/details/gtgptjyjkk.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtcustlauw.html

[F01] 读取整个文件
来源：http://dali.ivvv.top/Article/details/gtrgmsevmc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtztviunff.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtifirlfgr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ybcxt.top/Article/details/gtqfemcwpa.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yuxming.cn/Article/details/gtbdgbmjyw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gtmwasqvzp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.iojbl.cn/Article/details/gtfznwbmhi.html

Ruby: File.read("a.txt")
来源：http://dali.sweek.top/Article/details/gtipcgaevm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ivvv.top/Article/details/gtjqsocths.html

[F02] 逐行读取文件
来源：http://dali.xylfe.cn/Article/details/gttdewqbbg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.andypj.xyz/Article/details/gttnqcdezt.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zdqjudy.top/Article/details/gtzxkqzmsr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yvedp.cn/Article/details/gtubcdcqoj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxruenguu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.dianchejie.cn/Article/details/gtalujvvkf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yanxiufei.cn/Article/details/gtjjutddrm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.c1oappe.top/Article/details/gtytavxdqy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xylfe.cn/Article/details/gtcledglbj.html

[F03] 写入文件（覆盖）
来源：http://dali.9152youxi.cn/Article/details/gtrticguse.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cdnleiting.top/Article/details/gtymrkprpu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hnqzz.top/Article/details/gtjnijocjh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nwbrower.top/Article/details/gtozpujhsy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gtxejxfcgq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.wangdashe.top/Article/details/gtysgzfkav.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hnqzz.top/Article/details/gtfcoueyzb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ivvv.top/Article/details/gtwxoimmhj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gthzgehjwd.html

[F04] 追加写入文件
来源：http://dali.yonumen.top/Article/details/gtpcpmgpbg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.fengsongda.top/Article/details/gtuuplljgx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hnxiangtu.top/Article/details/gtotluwzbl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtqrdcggif.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hysaishi.cn/Article/details/gtafaeyqyp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.fengsongda.top/Article/details/gteyyxnpun.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.quarkkingdee.top/Article/details/gtbrnnxuox.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tian-w.cn/Article/details/gthjlhzmjv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nwbrower.top/Article/details/gtanftdhmy.html

[F05] 判断文件或目录是否存在
来源：http://dali.fengsongda.top/Article/details/gtdczoisqp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.aibaodan.cn/Article/details/gtsnbruqjq.html

PHP:  file_exists("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtusyuibvj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtmekkeoye.html

TS:   fs.existsSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtqhvgomvj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqgrfwrka.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yuanzhike.top/Article/details/gtncawzgno.html

Ruby: File.exist?("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtoowgeohp.html

C#:   File.Exists("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtwjjlsezb.html

[F06] 删除文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtehnllbnj.html

Py:   os.remove("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtdiddbnlm.html

PHP:  unlink("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtgzgaqlcz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtnsumnnia.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtizzkjsup.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtngottqmw.html

Go:   os.Remove("a.txt")
来源：http://dali.havefunace.top/Article/details/gtsdowxrtq.html

Ruby: File.delete("a.txt")
来源：http://dali.birdmap.top/Article/details/gtfquijqvd.html

C#:   File.Delete("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtnczdfsdb.html

[F07] 创建目录（含多级）
来源：http://dali.c1oappe.top/Article/details/gtgxbjpfha.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrspgphtp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.andypj.xyz/Article/details/gtidoahnyi.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fzhhl.top/Article/details/gteonsjiyh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ivvv.top/Article/details/gtdjestrmc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cheryme.top/Article/details/gtacykentn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.havefunace.top/Article/details/gturxmewyv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shuidangran.top/Article/details/gtoapoiozp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.0kj1m.cn/Article/details/gtbzbjdqzv.html

[F08] 遍历目录
来源：http://dali.kuanghao11.cn/Article/details/gtnlmhrros.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.andypj.xyz/Article/details/gtzhzcycwi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.chenjidiqi.icu/Article/details/gtqhquofyt.html

JS:   fs.readdirSync("dir")
来源：http://dali.mhx1999.top/Article/details/gtgnakawch.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtafsjkour.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.316326.xyz/Article/details/gtxjeomfhf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.0kj1m.cn/Article/details/gtnoctddji.html

Ruby: Dir.children("dir")
来源：http://dali.svipenyu.cn/Article/details/gtgtulxanv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cheryme.top/Article/details/gtyqtupndj.html

[F09] 获取文件大小
来源：http://dali.sufxvd.cn/Article/details/gtrkznsfui.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtbuwfiqzu.html

PHP:  filesize("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtzsilyyui.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yonumen.top/Article/details/gtyeuaadza.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenzaomai.com/Article/details/gtgqwcmekr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gtljnenjaq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.316326.xyz/Article/details/gttrtyhnvu.html

Ruby: File.size("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtnvgdxdsq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.aibaodan.cn/Article/details/gtbgepsljp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sufxvd.cn/Article/details/gtyuawyddg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtbzmpvzlt.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtomrnavoe.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtanfgwwec.html

TS:   path.extname("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtogtvuiqt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj202588.top/Article/details/gtlvzmsrlp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtqlcnxvgy.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtiktelbdj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtxpihqmvx.html

[F11] 复制与移动文件
来源：http://dali.yvedp.cn/Article/details/gtoffljnea.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtrqngmydr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtgojokpub.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtlgriuxif.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtxoevkjfq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cucudq.cn/Article/details/gtbabjiyoy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhongyouzk.top/Article/details/gtjeydjrsi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtdtnnvegm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sufxvd.cn/Article/details/gtdhxcfwum.html

[F12] CSV 读写
来源：http://dali.chenjidiqi.icu/Article/details/gtwkcxttcz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hammf.cn/Article/details/gtirgrdvhc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cucudq.cn/Article/details/gtdmumixrc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yangfankeji.com/Article/details/gtiehsvewn.html

TS:   // 同上
来源：http://dali.aizwys.cn/Article/details/gtbfgfxtlb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hongshengwenyu.top/Article/details/gtibnbhiza.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.kuanghao11.cn/Article/details/gtdtmkxanb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shuidangran.top/Article/details/gtmxpeclpe.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zycfv.cn/Article/details/gtffaobakm.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtluyexgmb.html

G. 面向对象
来源：http://dali.kuanghao11.cn/Article/details/gtdrqnbwjo.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtfzloqinw.html

[G01] 定义类
来源：http://dali.yvedp.cn/Article/details/gtaxrucfgv.html

Py:   class User: pass
来源：http://dali.zhoulong.xyz/Article/details/gtnpryunqk.html

PHP:  class User {}
来源：http://dali.fzhhl.top/Article/details/gtoxciumen.html

JS:   class User {}
来源：http://dali.zhongyouzk.top/Article/details/gtsskllggw.html

TS:   class User { name: string = ""; }
来源：http://dali.guannengcc.top/Article/details/gtjjifknxm.html

Java: class User {}
来源：http://dali.zdqjudy.top/Article/details/gteksysfdk.html

Go:   type User struct { Name string }
来源：http://dali.xinyue.icu/Article/details/gtytgprjuo.html

Ruby: class User; end
来源：http://dali.sysykeji.top/Article/details/gtkezmfguq.html

C#:   class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gthzbqicll.html

[G02] 构造函数
来源：http://dali.nanxuanxn.top/Article/details/gtkfeagqpt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj20258888.top/Article/details/gtvztohobt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jlsjyb.cn/Article/details/gtqqkfyqrk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gtdnylkinf.html

TS:   constructor(public name: string) {}
来源：http://dali.haohaochexian.top/Article/details/gttycfmrwv.html

Java: User(String name) { this.name = name; }
来源：http://dali.c1oappe.top/Article/details/gtlubawwuw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yuanzhike.top/Article/details/gtfpwatslh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.smart0.xyz/Article/details/gtwfuvoimy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ppjwa.cn/Article/details/gtntzmmfwh.html

[G03] 实例属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyemajjjd.html

Py:   self.name = "x"
来源：http://dali.yonumen.top/Article/details/gtyaorzmrs.html

PHP:  public string $name = "x";
来源：http://dali.hywenlv.cn/Article/details/gtzojstbtl.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gtkgpcmozh.html

TS:   name: string = "x";
来源：http://dali.yuanzhike.top/Article/details/gtgctmlpfl.html

Java: private String name;
来源：http://dali.tian-w.cn/Article/details/gtpftfgenr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.snrcjt.cn/Article/details/gtdzqfyhsy.html

Ruby: @name = "x"
来源：http://dali.nwbrower.top/Article/details/gtujjzxodo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtabjcpwxl.html

[G04] 定义方法
来源：http://dali.haohaochexian.top/Article/details/gtbtopezrt.html

Py:   def greet(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gtbquaswkq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gthcihabxu.html

JS:   greet() { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtpelsvosc.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtykictbjx.html

Java: String greet() { return name; }
来源：http://dali.cheryme.top/Article/details/gtcyhycmvq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gtmciayxbk.html

Ruby: def greet; @name; end
来源：http://dali.zhiwuduotai.top/Article/details/gteqfvyuhv.html

C#:   public string Greet() => Name;
来源：http://dali.yonumen.top/Article/details/gtovqvcagq.html

[G05] 继承
来源：http://dali.316326.xyz/Article/details/gtnmidqoyn.html

Py:   class Admin(User): pass
来源：http://dali.wangdashe.top/Article/details/gteycstfun.html

PHP:  class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtpahtyjwm.html

JS:   class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtyoxfweda.html

TS:   class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gteomjlpwg.html

Java: class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gtkgwfnvuz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinqigfzy.top/Article/details/gtrhqknyhu.html

Ruby: class Admin < User; end
来源：http://dali.nanxinkj.top/Article/details/gtglrhyeoq.html

C#:   class Admin : User {}
来源：http://dali.jyoumei.cn/Article/details/gtjuqucgkm.html

[G06] 重写方法
来源：http://dali.shuidangran.top/Article/details/gtsflnzkkt.html

Py:   def greet(self): return "admin"
来源：http://dali.ppjwa.cn/Article/details/gtdlmadimf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtiquogyap.html

JS:   greet() { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtonbrkvtk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtumotdesf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtwxwqbfbn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xylfe.cn/Article/details/gtkvjdjkld.html

Ruby: def greet; "admin"; end
来源：http://dali.nwbrower.top/Article/details/gtgcyjvwwb.html

C#:   public override string Greet() => "admin";
来源：http://dali.hfpthk.cn/Article/details/gtavaimpgr.html

[G07] 调用父类方法
来源：http://dali.sysykeji.top/Article/details/gthumdyxvr.html

Py:   super().greet()
来源：http://dali.gaohongyu789.top/Article/details/gtoazojwcg.html

PHP:  parent::greet();
来源：http://dali.nanxuanxn.top/Article/details/gttkegqlwm.html

JS:   super.greet();
来源：http://dali.yj202588.top/Article/details/gtlcrcnqno.html

TS:   super.greet();
来源：http://dali.cqqwz.cn/Article/details/gtnerkznhz.html

Java: super.greet();
来源：http://dali.cdnleiting.top/Article/details/gtbrsnqakg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.daria6918.cn/Article/details/gtjrakxxmr.html

Ruby: super
来源：http://dali.xuetiantiany.cn/Article/details/gtfrgusxhl.html

C#:   base.Greet();
来源：http://dali.haohaochexian.top/Article/details/gthclnmzpi.html

[G08] 静态方法与属性
来源：http://dali.shuidangran.top/Article/details/gtakhpbdjz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.mhx1999.top/Article/details/gtsrskfsan.html

PHP:  public static function f() {}
来源：http://dali.zhongyouzk.top/Article/details/gthjouchre.html

JS:   static f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gtvasuoprg.html

TS:   static f(): void {}
来源：http://dali.tianlin.xyz/Article/details/gtdwqgaxov.html

Java: static void f() {}
来源：http://dali.yj20258.top/Article/details/gtnvtvljxl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ppjwa.cn/Article/details/gtawqetxrw.html

Ruby: def self.f; end
来源：http://dali.shangyingyoupin.top/Article/details/gtymcqmeqw.html

C#:   public static void F() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtobwfqlwi.html

[G09] 接口 / 抽象类
来源：http://dali.pengpengdd.cyou/Article/details/gtqhakiulc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shzxlz.cn/Article/details/gtbvgzxfvm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xuetiantiany.cn/Article/details/gtqddxfuoi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.smart0.xyz/Article/details/gtmgjaepko.html

TS:   interface Shape { area(): number; }
来源：http://dali.zycfv.cn/Article/details/gtaenslxck.html

Java: interface Shape { double area(); }
来源：http://dali.dashuyun.cn/Article/details/gtkxenljfa.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.mhx1999.top/Article/details/gtlgutnhtx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj202588.top/Article/details/gtymqzldbz.html

C#:   interface IShape { double Area(); }
来源：http://dali.jianghu66.top/Article/details/gtzwhwtvop.html

[G10] 访问控制
来源：http://dali.meibo888.top/Article/details/gtvivpjvzw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tian-w.cn/Article/details/gtdksqeybj.html

PHP:  public / protected / private
来源：http://dali.cucudq.cn/Article/details/gtmkxvqwbs.html

JS:   #private 字段；其余公开
来源：http://dali.yj20258888.top/Article/details/gtwcwacfha.html

TS:   public / protected / private
来源：http://dali.hnqzz.top/Article/details/gtfqknnesp.html

Java: public / protected / private / 默认包级
来源：http://dali.andypj.xyz/Article/details/gtwenecjde.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hfpthk.cn/Article/details/gtpgadjvtf.html

Ruby: public / protected / private
来源：http://dali.zycfv.cn/Article/details/gtvyqlpajc.html

C#:   public / protected / private / internal
来源：http://dali.nanxuanxn.top/Article/details/gtmmkxduoh.html

[G11] getter / setter
来源：http://dali.gogol.net.cn/Article/details/gthrqryefp.html

Py:   @property 与 @x.setter
来源：http://dali.dashuyun.cn/Article/details/gtzxwsxiyh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtvyfxinso.html

JS:   get name() { return this._name; }
来源：http://dali.yongpay.top/Article/details/gtgkwtwcam.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinqigufen.top/Article/details/gtxbnclhjk.html

Java: public String getName() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtdxdggwxq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gtcvmqkgbx.html

Ruby: attr_accessor :name
来源：http://dali.yueranfly.top/Article/details/gtgfztgneu.html

C#:   public string Name { get; set; }
来源：http://dali.ybcxt.top/Article/details/gtnkfqcunl.html

[G12] 对象转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtgutjgbyk.html

Py:   def __str__(self): return self.name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdfbhjntl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gtgsudaffa.html

JS:   toString() { return this.name; }
来源：http://dali.yj20258.top/Article/details/gtfhdxpthk.html

TS:   toString(): string { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gtzruwlspo.html

Java: @Override public String toString() { return name; }
来源：http://dali.daxiang520.top/Article/details/gtxzbldhoa.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gtngwxstzu.html

Ruby: def to_s; @name; end
来源：http://dali.vqdsnc.cn/Article/details/gtggfghrsz.html

C#:   public override string ToString() => Name;
来源：http://dali.ehwqpu.com/Article/details/gtsxxrzksb.html

[G13] 判断对象类型
来源：http://dali.cheryme.top/Article/details/gtrqpkttgt.html

Py:   isinstance(u, User)
来源：http://dali.svipenyu.cn/Article/details/gtgaakaeds.html

PHP:  $u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtzrzlzjdt.html

JS:   u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtvalkdigg.html

TS:   u instanceof User
来源：http://dali.ivvv.top/Article/details/gtqbqfojeh.html

Java: u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtmualdiay.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ydzc1.top/Article/details/gtfndifnck.html

Ruby: u.is_a?(User)
来源：http://dali.jqgfzy.top/Article/details/gtfdgckxuy.html

C#:   u is User
来源：http://dali.guannengcc.top/Article/details/gtdrxxspew.html

[G14] 数据类 / record
来源：http://dali.shangyingyoupin.top/Article/details/gtdmsalyfv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dashuyun.cn/Article/details/gtqfoagnyy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nanxuanxn.top/Article/details/gthlbcsdez.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yongpay.top/Article/details/gtaqpyydkg.html

TS:   type User = { name: string; age: number };
来源：http://dali.aibaodan.cn/Article/details/gtkgggmwya.html

Java: record User(String name, int age) {}
来源：http://dali.hammf.cn/Article/details/gtvgdhbfxm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.bjfxy.top/Article/details/gtdqdmmbla.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zycfv.cn/Article/details/gtpnfzkujd.html

C#:   record User(string Name, int Age);
来源：http://dali.shangyingyoupin.top/Article/details/gtopojudlw.html

[G15] 枚举
来源：http://dali.nwbrower.top/Article/details/gtajtmtclm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yuanzhike.top/Article/details/gtesgzhqtx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.svipenyu.cn/Article/details/gtgtdwoxqm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zdqjudy.top/Article/details/gtnjxojlio.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guowangkeji.top/Article/details/gtooovqvtu.html

Java: enum Color { RED, GREEN }
来源：http://dali.cucudq.cn/Article/details/gtatjkegjb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenjidiqi.icu/Article/details/gtkxkiqhji.html

Ruby: Color = %i[red green].freeze
来源：http://dali.smart0.xyz/Article/details/gtsbnknmzu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.birdmap.top/Article/details/gtgfmpfjgt.html

[G16] 对象转数组 / 字典
来源：http://dali.daxiang520.top/Article/details/gtdpyjjkay.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhixingplan.top/Article/details/gtitzhrcob.html

PHP:  get_object_vars($obj);
来源：http://dali.shangyingyoupin.top/Article/details/gtsrkbpaab.html

JS:   Object.entries(obj)
来源：http://dali.nanxuanxn.top/Article/details/gthqvtswot.html

TS:   Object.entries(obj)
来源：http://dali.zdqjudy.top/Article/details/gtmoiskjyk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenlongwang.top/Article/details/gtmascbjac.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cdnleiting.top/Article/details/gtprlkqhbd.html

Ruby: obj.instance_variables
来源：http://dali.cashguo.top/Article/details/gteyangwdx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gtdkasjjjp.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtifgvbqzg.html


<!-- 参考信息 -->