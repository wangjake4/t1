代发 wailian999

[E18] 模板占位符替换
来源：http://dali.zhongyouzk.top/Article/details/gt2adebcbhl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yanxiufei.cn/Article/details/gt2lexveihh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbuovghh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ppjwa.cn/Article/details/gt2nobsqtgg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gt2bmwktzms.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gt2jhblkmym.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mxqmyvrg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yueranfly.top/Article/details/gt2xteaaafw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.svipenyu.cn/Article/details/gt2pwopshrb.html

[E19] 多行文本按行拆分
来源：http://dali.zhongyouzk.top/Article/details/gt2trnaplqx.html

Py:   s.splitlines()
来源：http://dali.snrcjt.cn/Article/details/gt2soczcugw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shzxlz.cn/Article/details/gt2mnzbhzcq.html

JS:   s.split(/\r?\n/)
来源：http://dali.9152youxi.cn/Article/details/gt2optxngss.html

TS:   s.split(/\r?\n/)
来源：http://dali.meibo888.top/Article/details/gt2foiofnjx.html

Java: s.lines().toList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2xwkzpgfq.html

Go:   strings.Split(s, "\n")
来源：http://dali.wangdashe.top/Article/details/gt2kzjrijwy.html

Ruby: s.lines
来源：http://dali.ydzc1.top/Article/details/gt2htsavcjd.html

C#:   s.Split('\n')
来源：http://dali.9152youxi.cn/Article/details/gt2ximndxtz.html

[E20] 判断字符串是否为空
来源：http://dali.kuanghao11.cn/Article/details/gt2gahbnqkg.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2ponvpddx.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sweek.top/Article/details/gt2tlgfxdsq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.bjfxy.top/Article/details/gt2trmaqclx.html

TS:   if (s === "") {}
来源：http://dali.ehwqpu.com/Article/details/gt2opsemuah.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yxqgfqwf.html

Go:   if s == "" {}
来源：http://dali.nwbrower.top/Article/details/gt2rwgbwmyb.html

Ruby: if s.empty?
来源：http://dali.smart0.xyz/Article/details/gt2mllurppo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2almwsymj.html

[E21] 超长截断加省略号
来源：http://dali.jianghu66.top/Article/details/gt2mwchilgf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hywenlv.cn/Article/details/gt2xduorfha.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gt2npmumzyr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gt2zhdgfrzw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gt2enpbpsij.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ybcxt.top/Article/details/gt2woxdbiom.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jiagoushi.top/Article/details/gt2qfpfrtjp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sysykeji.top/Article/details/gt2lrggkejp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gt2uecsfyof.html

[E22] 字节长度与字符长度
来源：http://dali.nanxinkj.top/Article/details/gt2wstcmsrj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.mhx1999.top/Article/details/gt2sxuauoyk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gt2qlkdqxbd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gt2ylpxfmiv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sufxvd.cn/Article/details/gt2wubbmoxz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhengqikj.top/Article/details/gt2kagkwhnc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.daxiang520.top/Article/details/gt2allhdlky.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gt2vayqytfx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gzhubu.top/Article/details/gt2yorhldab.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2lilkxoda.html

F. 文件与目录
来源：http://dali.wangdashe.top/Article/details/gt2vdbjtgkq.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2gzortxgi.html

[F01] 读取整个文件
来源：http://dali.jyoumei.cn/Article/details/gt2ahbwhbfc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.andypj.xyz/Article/details/gt2dkdftllk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gzhubu.top/Article/details/gt2mehexojc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hnxiangtu.top/Article/details/gt2mdufjvxn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gt2egfjmlsw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tssvhftf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.guannengcc.top/Article/details/gt2nbzvigsa.html

Ruby: File.read("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2zamkfygq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2qvyfloaq.html

[F02] 逐行读取文件
来源：http://dali.sufxvd.cn/Article/details/gt2mdazqfpa.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sufxvd.cn/Article/details/gt2wygbilyj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xuanzx.com/Article/details/gt2cziyflkj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2cuptgfae.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2lqhjdjcb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hnqzz.top/Article/details/gt2volvzgsv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gogol.net.cn/Article/details/gt2rwidfrvl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kdmdcpzd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sysykeji.top/Article/details/gt2gdxulbjz.html

[F03] 写入文件（覆盖）
来源：http://dali.zhongyouzk.top/Article/details/gt2pouuyxnb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.daxiang520.top/Article/details/gt2segcmgup.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gogol.net.cn/Article/details/gt2zqzvcooe.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gt2yyjsrfqt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ybcxt.top/Article/details/gt2pcaxdact.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xinyue.icu/Article/details/gt2sciuntrq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.aibaodan.cn/Article/details/gt2wdiefxog.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenlongwang.top/Article/details/gt2eqbfjxxn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.guannengcc.top/Article/details/gt2hughaoae.html

[F04] 追加写入文件
来源：http://dali.jinqigfzy.top/Article/details/gt2klyscknh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.mhx1999.top/Article/details/gt2yepxhxsd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cdnleiting.top/Article/details/gt2nqvhyxky.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tanke756.top/Article/details/gt2zuctvicc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258.top/Article/details/gt2fofotjyh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2muasstzf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.aizwys.cn/Article/details/gt2ryrxfmse.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nanxuanxn.top/Article/details/gt2oohhfnkc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.mhx1999.top/Article/details/gt2srmlvdpr.html

[F05] 判断文件或目录是否存在
来源：http://dali.gogol.net.cn/Article/details/gt2bckkynqj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.guannengcc.top/Article/details/gt2tjujmbwn.html

PHP:  file_exists("a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2leruveou.html

JS:   fs.existsSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2ueiwxoil.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2ygdiniph.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gt2jeglumhl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.0kj1m.cn/Article/details/gt2ymseojbh.html

Ruby: File.exist?("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2dahaerrr.html

C#:   File.Exists("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2nkdkyciw.html

[F06] 删除文件
来源：http://dali.vqdsnc.cn/Article/details/gt2edpcmctx.html

Py:   os.remove("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2xrqleeaf.html

PHP:  unlink("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gt2egqyozrw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fedrpgfk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2bedcgxji.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gt2olqltysv.html

Go:   os.Remove("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2kyevkkon.html

Ruby: File.delete("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2argocapm.html

C#:   File.Delete("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2ddffgidd.html

[F07] 创建目录（含多级）
来源：http://dali.zdqjudy.top/Article/details/gt2vsudcefh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.pycfn.com/Article/details/gt2vektnyyx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.aizwys.cn/Article/details/gt2lypvphuq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwvxttz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yueranfly.top/Article/details/gt2ncvmbgck.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.chenlongwang.top/Article/details/gt2xdtcyxvc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.birdmap.top/Article/details/gt2wbetzinr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sysykeji.top/Article/details/gt2qkkocbnm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.svipenyu.cn/Article/details/gt2uakjbuvj.html

[F08] 遍历目录
来源：http://dali.cdnleiting.top/Article/details/gt2jicyucpu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ofktazxo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ehwqpu.com/Article/details/gt2xcspvhev.html

JS:   fs.readdirSync("dir")
来源：http://dali.guannengcc.top/Article/details/gt2kusvaawq.html

TS:   fs.readdirSync("dir")
来源：http://dali.xziqi.cn/Article/details/gt2jewhlscj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.havefunace.top/Article/details/gt2bkqxcita.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bigwzktn.html

Ruby: Dir.children("dir")
来源：http://dali.dianchejie.cn/Article/details/gt2btczlocd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.haohaochexian.top/Article/details/gt2hpxksaco.html

[F09] 获取文件大小
来源：http://dali.andypj.xyz/Article/details/gt2nqdwicyx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2fwojzogh.html

PHP:  filesize("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gt2snfyuwmy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.wangshuangyany.cn/Article/details/gt2hptradiy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhengqikj.top/Article/details/gt2vdjxtueg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gt2ysbjuhja.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.aizwys.cn/Article/details/gt2yvwtytbf.html

Ruby: File.size("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2uthqhdpr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.wangdashe.top/Article/details/gt2wpjjleyi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gogol.net.cn/Article/details/gt2bfpgocig.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2dirghcgo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2zajksotb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2ptemfxat.html

TS:   path.extname("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2nztjgsph.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fieivtxc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2wvveajbb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2addutrsf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2aclwrjfl.html

[F11] 复制与移动文件
来源：http://dali.ehwqpu.com/Article/details/gt2jciqomlj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2dbitalat.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2bjhbdzfy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2ziemagnt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2cvjxyvfb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xziqi.cn/Article/details/gt2nnoqhosf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shangyingyoupin.top/Article/details/gt2lpbumrdn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2cihunaek.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yonumen.top/Article/details/gt2cilojvcd.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2kyeiznzq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.svipenyu.cn/Article/details/gt2xvbbmtra.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bhghfcjv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ybcxt.top/Article/details/gt2bbhkjdwi.html

TS:   // 同上
来源：http://dali.yuanzhike.top/Article/details/gt2aysltjdw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cucudq.cn/Article/details/gt2litopgru.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhongyouzk.top/Article/details/gt2hnhncnfe.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ksltupbt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yangfankeji.com/Article/details/gt2odcjsppb.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2efzriude.html

G. 面向对象
来源：http://dali.mhx1999.top/Article/details/gt2xnxrfcpp.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2oxtfrqzq.html

[G01] 定义类
来源：http://dali.jiagoushi.top/Article/details/gt2ndttzlni.html

Py:   class User: pass
来源：http://dali.316326.xyz/Article/details/gt2qsbzykux.html

PHP:  class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2kzllcovo.html

JS:   class User {}
来源：http://dali.hfpthk.cn/Article/details/gt2lnwgdhum.html

TS:   class User { name: string = ""; }
来源：http://dali.fzhhl.top/Article/details/gt2pllmkklq.html

Java: class User {}
来源：http://dali.svipenyu.cn/Article/details/gt2mbekleru.html

Go:   type User struct { Name string }
来源：http://dali.sxryk.cn/Article/details/gt2hkxudqca.html

Ruby: class User; end
来源：http://dali.chenlongwang.top/Article/details/gt2gfiqffuj.html

C#:   class User {}
来源：http://dali.daxiang520.top/Article/details/gt2pjbghkye.html

[G02] 构造函数
来源：http://dali.hammf.cn/Article/details/gt2samrwkqc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenzaomai.com/Article/details/gt2hnqphaqb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj20258.top/Article/details/gt2gslfcalq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.fzhhl.top/Article/details/gt2kelxsgdb.html

TS:   constructor(public name: string) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vzdpqmjo.html

Java: User(String name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gt2vqpbldpj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xuetiantiany.cn/Article/details/gt2wuvmuypn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.daxiang520.top/Article/details/gt2nttvlxzv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.dianchejie.cn/Article/details/gt2ndmeuzgh.html

[G03] 实例属性
来源：http://dali.svipenyu.cn/Article/details/gt2zjuvqdbb.html

Py:   self.name = "x"
来源：http://dali.yanxiufei.cn/Article/details/gt2whnuemxm.html

PHP:  public string $name = "x";
来源：http://dali.jqgfzy.top/Article/details/gt2srfzhwnb.html

JS:   this.name = "x";
来源：http://dali.kuanghao11.cn/Article/details/gt2btkjilte.html

TS:   name: string = "x";
来源：http://dali.shuidangran.top/Article/details/gt2swtjriex.html

Java: private String name;
来源：http://dali.yueranfly.top/Article/details/gt2ubzwfbja.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.dianchejie.cn/Article/details/gt2tsycphgd.html

Ruby: @name = "x"
来源：http://dali.cdnleiting.top/Article/details/gt2vwbkrozw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xziqi.cn/Article/details/gt2prddsgks.html

[G04] 定义方法
来源：http://dali.fengsongda.top/Article/details/gt2ycdhygvd.html

Py:   def greet(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gt2wcwolmly.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gt2oixbnpis.html

JS:   greet() { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gt2lqmiipmt.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fzutfyfj.html

Java: String greet() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gt2wqugxxsn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gt2uwzgdkbl.html

Ruby: def greet; @name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xxjlmzbz.html

C#:   public string Greet() => Name;
来源：http://dali.cheryme.top/Article/details/gt2wpkibxtb.html

[G05] 继承
来源：http://dali.ivvv.top/Article/details/gt2awikzzaj.html

Py:   class Admin(User): pass
来源：http://dali.sufxvd.cn/Article/details/gt2uovpussb.html

PHP:  class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gt2hapwvwug.html

JS:   class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gt2lnmeoots.html

TS:   class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2bchyvcjs.html

Java: class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gt2bfdmueka.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.aibaodan.cn/Article/details/gt2iughuiro.html

Ruby: class Admin < User; end
来源：http://dali.fzhhl.top/Article/details/gt2xchzcpgx.html

C#:   class Admin : User {}
来源：http://dali.yangfankeji.com/Article/details/gt2cvtqddjb.html

[G06] 重写方法
来源：http://dali.daxiang520.top/Article/details/gt2bjqbdqit.html

Py:   def greet(self): return "admin"
来源：http://dali.shuidangran.top/Article/details/gt2qjozuhke.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2hswakizb.html

JS:   greet() { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2ttrllyao.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gt2aaaepvxw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gt2zhsgshcr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xylfe.cn/Article/details/gt2vatlvdlp.html

Ruby: def greet; "admin"; end
来源：http://dali.yj20258888.top/Article/details/gt2zqujelpu.html

C#:   public override string Greet() => "admin";
来源：http://dali.hnxiangtu.top/Article/details/gt2prrhbfdl.html

[G07] 调用父类方法
来源：http://dali.sxryk.cn/Article/details/gt2bukbnwuk.html

Py:   super().greet()
来源：http://dali.aibaodan.cn/Article/details/gt2dlzztuug.html

PHP:  parent::greet();
来源：http://dali.ivvv.top/Article/details/gt2nsgutnqq.html

JS:   super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gt2lhstdjkq.html

TS:   super.greet();
来源：http://dali.yj20258.top/Article/details/gt2fhxfqarb.html

Java: super.greet();
来源：http://dali.bjfxy.top/Article/details/gt2qjsbyhac.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.smart0.xyz/Article/details/gt2kxnffdnn.html

Ruby: super
来源：http://dali.chenlongwang.top/Article/details/gt2eufhvgpg.html

C#:   base.Greet();
来源：http://dali.yj20258.top/Article/details/gt2bdbpemfj.html

[G08] 静态方法与属性
来源：http://dali.shuidangran.top/Article/details/gt2hiqloetz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenjidiqi.icu/Article/details/gt2yzcrzmfb.html

PHP:  public static function f() {}
来源：http://dali.zhengqikj.top/Article/details/gt2eklincnf.html

JS:   static f() {}
来源：http://dali.nwbrower.top/Article/details/gt2gokuwsmy.html

TS:   static f(): void {}
来源：http://dali.zhoulong.xyz/Article/details/gt2zrnihwre.html

Java: static void f() {}
来源：http://dali.yueranfly.top/Article/details/gt2efcqglqd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yvedp.cn/Article/details/gt2doysxhtx.html

Ruby: def self.f; end
来源：http://dali.nanxuanxn.top/Article/details/gt2guquztjf.html

C#:   public static void F() {}
来源：http://dali.shuidangran.top/Article/details/gt2kzjmohad.html

[G09] 接口 / 抽象类
来源：http://dali.birdmap.top/Article/details/gt2lyrkpazo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.andypj.xyz/Article/details/gt2lstjkbdh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cqqwz.cn/Article/details/gt2acaqucqo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ydzc1.top/Article/details/gt2rceiojhh.html

TS:   interface Shape { area(): number; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2piuhovmz.html

Java: interface Shape { double area(); }
来源：http://dali.fengsongda.top/Article/details/gt2wvjdiibr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhixingplan.top/Article/details/gt2ynmlljkf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj202588.top/Article/details/gt2hviocwdz.html

C#:   interface IShape { double Area(); }
来源：http://dali.bjfxy.top/Article/details/gt2iorocuhu.html

[G10] 访问控制
来源：http://dali.hammf.cn/Article/details/gt2orilzaof.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yonumen.top/Article/details/gt2swxhlyqv.html

PHP:  public / protected / private
来源：http://dali.ivvv.top/Article/details/gt2weftcaiq.html

JS:   #private 字段；其余公开
来源：http://dali.zycfv.cn/Article/details/gt2uxyeiyjo.html

TS:   public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gt2ikxqddfv.html

Java: public / protected / private / 默认包级
来源：http://dali.yj20258888.top/Article/details/gt2nwtlwhyc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jlsjyb.cn/Article/details/gt2jyifeztc.html

Ruby: public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gt2fdcghqjh.html

C#:   public / protected / private / internal
来源：http://dali.jqgufenzy.top/Article/details/gt2tjidacwp.html

[G11] getter / setter
来源：http://dali.feifeiyinyue.top/Article/details/gt2dcboblnz.html

Py:   @property 与 @x.setter
来源：http://dali.shuidangran.top/Article/details/gt2mhnhkcgt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gt2wqjmrppl.html

JS:   get name() { return this._name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2yiwcfaje.html

TS:   get name(): string { return this._name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2hddgjbyj.html

Java: public String getName() { return name; }
来源：http://dali.zycfv.cn/Article/details/gt2wqezsttw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hfpthk.cn/Article/details/gt2mrpmeghs.html

Ruby: attr_accessor :name
来源：http://dali.jianghu66.top/Article/details/gt2cdthtkct.html

C#:   public string Name { get; set; }
来源：http://dali.yanxiufei.cn/Article/details/gt2zxvoxlhq.html

[G12] 对象转字符串
来源：http://dali.fengsongda.top/Article/details/gt2hxjmzuit.html

Py:   def __str__(self): return self.name
来源：http://dali.nanxuanxn.top/Article/details/gt2xlavpxmw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gt2yvazoeaj.html

JS:   toString() { return this.name; }
来源：http://dali.cheryme.top/Article/details/gt2cqyldqoh.html

TS:   toString(): string { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gt2nmoxcruo.html

Java: @Override public String toString() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dxnuifde.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gt2raizypkx.html

Ruby: def to_s; @name; end
来源：http://dali.fzhhl.top/Article/details/gt2nsfutmsb.html

C#:   public override string ToString() => Name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ufndwsqn.html

[G13] 判断对象类型
来源：http://dali.yj20258.top/Article/details/gt2mhegisgc.html

Py:   isinstance(u, User)
来源：http://dali.zycfv.cn/Article/details/gt2qpwzwfzi.html

PHP:  $u instanceof User
来源：http://dali.xylfe.cn/Article/details/gt2voqknpib.html

JS:   u instanceof User
来源：http://dali.xinyue.icu/Article/details/gt2tfmlpjov.html

TS:   u instanceof User
来源：http://dali.ydzc1.top/Article/details/gt2zwqlfjal.html

Java: u instanceof User
来源：http://dali.yonumen.top/Article/details/gt2kspsemak.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cheryme.top/Article/details/gt2rblmmocb.html

Ruby: u.is_a?(User)
来源：http://dali.sysykeji.top/Article/details/gt2ferkcpxq.html

C#:   u is User
来源：http://dali.chenjidiqi.icu/Article/details/gt2ldfdworp.html

[G14] 数据类 / record
来源：http://dali.guowangkeji.top/Article/details/gt2slneseup.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.daxiang520.top/Article/details/gt2cvioiban.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yj20258.top/Article/details/gt2vdijejfv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yuanzhike.top/Article/details/gt2iiycpmgc.html

TS:   type User = { name: string; age: number };
来源：http://dali.sxryk.cn/Article/details/gt2xbkamjpi.html

Java: record User(String name, int age) {}
来源：http://dali.jianghu66.top/Article/details/gt2yvdiwvhg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dlysqtcm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.snrcjt.cn/Article/details/gt2nngnzdhk.html

C#:   record User(string Name, int Age);
来源：http://dali.iojbl.cn/Article/details/gt2thcejanj.html

[G15] 枚举
来源：http://dali.quarkkingdee.top/Article/details/gt2yqezlpcw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zycfv.cn/Article/details/gt2omnjpryc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.snrcjt.cn/Article/details/gt2bnindrsn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gaohongyu789.top/Article/details/gt2nnkjheiy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xziqi.cn/Article/details/gt2spwhgtrr.html

Java: enum Color { RED, GREEN }
来源：http://dali.daria6918.cn/Article/details/gt2mgirngkz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.aizwys.cn/Article/details/gt2crmkpmbc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hywenlv.cn/Article/details/gt2qwmrijyc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2krxusomz.html

[G16] 对象转数组 / 字典
来源：http://dali.guowangkeji.top/Article/details/gt2zvzeicvt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tanke756.top/Article/details/gt2yktvczdv.html

PHP:  get_object_vars($obj);
来源：http://dali.zhoulong.xyz/Article/details/gt2lccbdgdt.html

JS:   Object.entries(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2odprxnnj.html

TS:   Object.entries(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2aszmgyrd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shzxlz.cn/Article/details/gt2cncesrjk.html


<!-- 参考信息 -->