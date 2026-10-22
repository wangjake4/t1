代发 wailian999

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gt2najqzggx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gt2eebrvtpq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tanke756.top/Article/details/gt2ckaxllyd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.snrcjt.cn/Article/details/gt2swmhlxnz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rsbpkhiv.html

[E19] 多行文本按行拆分
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hawrhczq.html

Py:   s.splitlines()
来源：http://dali.sysykeji.top/Article/details/gt2efhbdkps.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ehbftowr.html

JS:   s.split(/\r?\n/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zvnzgwpk.html

TS:   s.split(/\r?\n/)
来源：http://dali.gzhubu.top/Article/details/gt2rnyycsyb.html

Java: s.lines().toList()
来源：http://dali.kuanghao11.cn/Article/details/gt2lkygmhrp.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xeectlav.html

Ruby: s.lines
来源：http://dali.havefunace.top/Article/details/gt2vynaninu.html

C#:   s.Split('\n')
来源：http://dali.pengpengdd.cyou/Article/details/gt2qcpeygsc.html

[E20] 判断字符串是否为空
来源：http://dali.jinqigfzy.top/Article/details/gt2csfrgvsd.html

Py:   if not s:
来源：http://dali.daria6918.cn/Article/details/gt2rmbvjuwc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yj202588.top/Article/details/gt2ljkkxmyk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2oxiykcyx.html

TS:   if (s === "") {}
来源：http://dali.svipenyu.cn/Article/details/gt2xctgevvx.html

Java: if (s.isEmpty()) {}
来源：http://dali.hnqzz.top/Article/details/gt2pgxinwvh.html

Go:   if s == "" {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2utvdohgs.html

Ruby: if s.empty?
来源：http://dali.nanxuanxn.top/Article/details/gt2opbmoajc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2phlfpxjd.html

[E21] 超长截断加省略号
来源：http://dali.yuxming.cn/Article/details/gt2yhpvilyl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hfpthk.cn/Article/details/gt2pxooazwl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gt2omvreear.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sndvyvpw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gt2tlevccwu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.iojbl.cn/Article/details/gt2ftanxfek.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.bjfxy.top/Article/details/gt2maufeqfr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kmazxjrx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jianghu66.top/Article/details/gt2vphwbasb.html

[E22] 字节长度与字符长度
来源：http://dali.iojbl.cn/Article/details/gt2xuhblest.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yueranfly.top/Article/details/gt2drayuiav.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gt2vopfloiu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shuidangran.top/Article/details/gt2bbfvjffp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fengsongda.top/Article/details/gt2yyxtgevv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ybcxt.top/Article/details/gt2qiajeoxq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.feifeiyinyue.top/Article/details/gt2fcnenuga.html

Ruby: s.bytesize;  s.length
来源：http://dali.sweek.top/Article/details/gt2evbjtfva.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenjidiqi.icu/Article/details/gt2zafrnigz.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2vejboubh.html

F. 文件与目录
来源：http://dali.shangyingyoupin.top/Article/details/gt2sdtzilok.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2mafxdcjw.html

[F01] 读取整个文件
来源：http://dali.jqgfzy.top/Article/details/gt2tvjdhptq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cheryme.top/Article/details/gt2jntfxhac.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2acmsgcvw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cucudq.cn/Article/details/gt2rotdyioo.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cucudq.cn/Article/details/gt2pxqtcmoc.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yfdojrqn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cucudq.cn/Article/details/gt2soxxnkca.html

Ruby: File.read("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2wupkffvs.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.bjfxy.top/Article/details/gt2cheswxwu.html

[F02] 逐行读取文件
来源：http://dali.gzhubu.top/Article/details/gt2lylezgix.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.wangdashe.top/Article/details/gt2swnlqwpg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhoulong.xyz/Article/details/gt2rhkqinio.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2yzplbgka.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.mhx1999.top/Article/details/gt2zofycugp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.aibaodan.cn/Article/details/gt2rtyuymnm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.iojbl.cn/Article/details/gt2crtfvvjt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yuanzhike.top/Article/details/gt2wowitfjd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2mjlvpvpo.html

[F03] 写入文件（覆盖）
来源：http://dali.gaohongyu789.top/Article/details/gt2ejnlosuq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.aizwys.cn/Article/details/gt2juwpnmfv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhengqikj.top/Article/details/gt2wktgqpaj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cashguo.top/Article/details/gt2pzecrmos.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gt2cpixtegm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.daxiang520.top/Article/details/gt2wofwizww.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xylfe.cn/Article/details/gt2wmeyucub.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jianghu66.top/Article/details/gt2gtrgfcfd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.dashuyun.cn/Article/details/gt2nhnhbmqf.html

[F04] 追加写入文件
来源：http://dali.jqgfzy.top/Article/details/gt2dwcglcyw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sufxvd.cn/Article/details/gt2znhgrzij.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cheryme.top/Article/details/gt2ouqruoib.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.9152youxi.cn/Article/details/gt2werswefq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuanzx.com/Article/details/gt2ugwrilnw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2piuzadkk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.fengsongda.top/Article/details/gt2fkspdkya.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinqigfzy.top/Article/details/gt2woayfunv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xinyue.icu/Article/details/gt2dgrhjqdv.html

[F05] 判断文件或目录是否存在
来源：http://dali.gaohongyu789.top/Article/details/gt2whukwdot.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinqigfzy.top/Article/details/gt2nrkuyink.html

PHP:  file_exists("a.txt");
来源：http://dali.gzhubu.top/Article/details/gt2gkjoyvkb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2efrhlhhe.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2fjbhjnxu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gt2tnwglrvr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2marndbaf.html

Ruby: File.exist?("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2ubotmdet.html

C#:   File.Exists("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2uggfvwoj.html

[F06] 删除文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vxtnywwg.html

Py:   os.remove("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2ymripxpe.html

PHP:  unlink("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2rtyhrvks.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2xzoxwmzd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2ncqhaoel.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gt2qlrhxwyp.html

Go:   os.Remove("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2iaozrxcl.html

Ruby: File.delete("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2lmqxqjua.html

C#:   File.Delete("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gt2qpqcihvt.html

[F07] 创建目录（含多级）
来源：http://dali.hfpthk.cn/Article/details/gt2xfmqkeov.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xylfe.cn/Article/details/gt2tbvzjklo.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hongshengwenyu.top/Article/details/gt2houidksf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2siexwrhq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2deoikmhm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.316326.xyz/Article/details/gt2kcmtvtqk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tian-w.cn/Article/details/gt2zovhhwza.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.redwolf501.top/Article/details/gt2ggowstyd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.kuanghao11.cn/Article/details/gt2mrczftel.html

[F08] 遍历目录
来源：http://dali.jianghu66.top/Article/details/gt2zqlzoxby.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.316326.xyz/Article/details/gt2nwkaxbsh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.pycfn.com/Article/details/gt2needliwb.html

JS:   fs.readdirSync("dir")
来源：http://dali.svipenyu.cn/Article/details/gt2xqdxtnlz.html

TS:   fs.readdirSync("dir")
来源：http://dali.wangdashe.top/Article/details/gt2frsctenu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ppjwa.cn/Article/details/gt2uxdjpiyc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.guowangkeji.top/Article/details/gt2jsohtkuf.html

Ruby: Dir.children("dir")
来源：http://dali.cucudq.cn/Article/details/gt2mwnvzmsx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.daxiang520.top/Article/details/gt2ixqnecrc.html

[F09] 获取文件大小
来源：http://dali.hnxiangtu.top/Article/details/gt2ejoytnpl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2fsgjiiry.html

PHP:  filesize("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2xlrlvcgr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.chenzaomai.com/Article/details/gt2tokwpdpn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2rnghnlzi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gt2bdokswod.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.aizwys.cn/Article/details/gt2gvbdqdlq.html

Ruby: File.size("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2onztlivm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jlsjyb.cn/Article/details/gt2sjpggauc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.dianchejie.cn/Article/details/gt2ztwgobli.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2iyhrijiz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2uvhqneyl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2izesozdc.html

TS:   path.extname("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2auuvxxlc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj20258888.top/Article/details/gt2pxllbvvl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2wuroflvp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2wmluezqu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2iwbkvkms.html

[F11] 复制与移动文件
来源：http://dali.pycfn.com/Article/details/gt2qdhoofxa.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gt2vzknlsvx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.c1oappe.top/Article/details/gt2oodvacly.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gt2ylqittun.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gt2nbbpnrxm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.nwbrower.top/Article/details/gt2swpstjuj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhixingplan.top/Article/details/gt2szbmlmnp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gt2mdmlqkqa.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bicfyzpa.html

[F12] CSV 读写
来源：http://dali.pycfn.com/Article/details/gt2egqatfks.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tianlin.xyz/Article/details/gt2ccccljgd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhixingplan.top/Article/details/gt2ncngyzik.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nanxuanxn.top/Article/details/gt2yeidpmoc.html

TS:   // 同上
来源：http://dali.havefunace.top/Article/details/gt2zjuwdvqm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jqgufenzy.top/Article/details/gt2iaklpoia.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cdnleiting.top/Article/details/gt2xpeflzqv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nwbrower.top/Article/details/gt2fwkynnsu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sufxvd.cn/Article/details/gt2pdeiyoky.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2chyawypx.html

G. 面向对象
来源：http://dali.ehwqpu.com/Article/details/gt2jojxdflt.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2ikmmfjmf.html

[G01] 定义类
来源：http://dali.aibaodan.cn/Article/details/gt2dmwzlruq.html

Py:   class User: pass
来源：http://dali.cheryme.top/Article/details/gt2kxzzqfig.html

PHP:  class User {}
来源：http://dali.sysykeji.top/Article/details/gt2ownbiljv.html

JS:   class User {}
来源：http://dali.jiagoushi.top/Article/details/gt2rhkzzupn.html

TS:   class User { name: string = ""; }
来源：http://dali.xziqi.cn/Article/details/gt2gsefysoh.html

Java: class User {}
来源：http://dali.snrcjt.cn/Article/details/gt2jotaxpeo.html

Go:   type User struct { Name string }
来源：http://dali.yangfankeji.com/Article/details/gt2oxofjnix.html

Ruby: class User; end
来源：http://dali.yj20258888.top/Article/details/gt2yblnflwv.html

C#:   class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2eqwncrnk.html

[G02] 构造函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2txxuzacu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yongpay.top/Article/details/gt2devfstpf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.snrcjt.cn/Article/details/gt2ykjnuifp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.birdmap.top/Article/details/gt2cfzkszji.html

TS:   constructor(public name: string) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2roxmbcef.html

Java: User(String name) { this.name = name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2jqlbaxli.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2okuczzdd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhongyouzk.top/Article/details/gt2yldotktt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tianlin.xyz/Article/details/gt2jzhiltkt.html

[G03] 实例属性
来源：http://dali.yj20258.top/Article/details/gt2knbreozv.html

Py:   self.name = "x"
来源：http://dali.cdnleiting.top/Article/details/gt2hjpmzttc.html

PHP:  public string $name = "x";
来源：http://dali.zhengqikj.top/Article/details/gt2dfnpgqpk.html

JS:   this.name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gt2isymytqb.html

TS:   name: string = "x";
来源：http://dali.redwolf501.top/Article/details/gt2vfhducmk.html

Java: private String name;
来源：http://dali.mhx1999.top/Article/details/gt2jnbqdghk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.mhx1999.top/Article/details/gt2nhlkvblv.html

Ruby: @name = "x"
来源：http://dali.nanxinkj.top/Article/details/gt2rpwtfbog.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.mhx1999.top/Article/details/gt2raraxoyg.html

[G04] 定义方法
来源：http://dali.shanyushiyangtech.top/Article/details/gt2picnunqs.html

Py:   def greet(self): return self.name
来源：http://dali.jyoumei.cn/Article/details/gt2qehbtnkq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gt2agxzkihy.html

JS:   greet() { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gt2kvvwocrf.html

TS:   greet(): string { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gt2gvvscwlr.html

Java: String greet() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gt2ciwlvswr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gt2ngijckkn.html

Ruby: def greet; @name; end
来源：http://dali.jiagoushi.top/Article/details/gt2uztiapod.html

C#:   public string Greet() => Name;
来源：http://dali.ivvv.top/Article/details/gt2yszmjbns.html

[G05] 继承
来源：http://dali.zhongyouzk.top/Article/details/gt2lhozmcey.html

Py:   class Admin(User): pass
来源：http://dali.cdnleiting.top/Article/details/gt2jdeuuwhb.html

PHP:  class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gt2sicahkwd.html

JS:   class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gt2cxtzuiol.html

TS:   class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gt2zrovezni.html

Java: class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2znkmuxax.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hammf.cn/Article/details/gt2ufipjkje.html

Ruby: class Admin < User; end
来源：http://dali.jiagoushi.top/Article/details/gt2yxtmwgol.html

C#:   class Admin : User {}
来源：http://dali.smart0.xyz/Article/details/gt2kcmaiook.html

[G06] 重写方法
来源：http://dali.andypj.xyz/Article/details/gt2vybxxafi.html

Py:   def greet(self): return "admin"
来源：http://dali.sufxvd.cn/Article/details/gt2hlybbtzd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gt2jcljbbpe.html

JS:   greet() { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gt2lrhbycvr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gt2qpnvtdcu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gt2qqhwwsoe.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ivvv.top/Article/details/gt2cctutjig.html

Ruby: def greet; "admin"; end
来源：http://dali.aibaodan.cn/Article/details/gt2exoykxat.html

C#:   public override string Greet() => "admin";
来源：http://dali.bjfxy.top/Article/details/gt2brycydeb.html

[G07] 调用父类方法
来源：http://dali.redwolf501.top/Article/details/gt2kpletiay.html

Py:   super().greet()
来源：http://dali.hongshengwenyu.top/Article/details/gt2nkgeonbm.html

PHP:  parent::greet();
来源：http://dali.tanke756.top/Article/details/gt2iyxhiecn.html

JS:   super.greet();
来源：http://dali.yueranfly.top/Article/details/gt2xajtawwj.html

TS:   super.greet();
来源：http://dali.yongpay.top/Article/details/gt2yvefomlc.html

Java: super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gt2slewcyfr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jianghu66.top/Article/details/gt2upskhcct.html

Ruby: super
来源：http://dali.wangshuangyany.cn/Article/details/gt2nzrjsrso.html

C#:   base.Greet();
来源：http://dali.jqgfzy.top/Article/details/gt2iuctiagn.html

[G08] 静态方法与属性
来源：http://dali.svipenyu.cn/Article/details/gt2apuolliq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwsbvvn.html

PHP:  public static function f() {}
来源：http://dali.gotoacloud.top/Article/details/gt2qfsifjvj.html

JS:   static f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2emseyrup.html

TS:   static f(): void {}
来源：http://dali.iojbl.cn/Article/details/gt2qizimyfy.html

Java: static void f() {}
来源：http://dali.havefunace.top/Article/details/gt2slijhbao.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhongyouzk.top/Article/details/gt2uaieakxu.html

Ruby: def self.f; end
来源：http://dali.xylfe.cn/Article/details/gt2hfpxdjiy.html

C#:   public static void F() {}
来源：http://dali.gzhubu.top/Article/details/gt2xyjiupap.html

[G09] 接口 / 抽象类
来源：http://dali.hfpthk.cn/Article/details/gt2bsxothwf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.bjfxy.top/Article/details/gt2wjtbodka.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sweek.top/Article/details/gt2faxtvnqg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.bjfxy.top/Article/details/gt2chjgdknh.html

TS:   interface Shape { area(): number; }
来源：http://dali.mhx1999.top/Article/details/gt2oftsbrad.html

Java: interface Shape { double area(); }
来源：http://dali.tianlin.xyz/Article/details/gt2suuxyomy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.havefunace.top/Article/details/gt2ubgalghq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sysykeji.top/Article/details/gt2lndcochi.html

C#:   interface IShape { double Area(); }
来源：http://dali.gzhubu.top/Article/details/gt2byyhriod.html

[G10] 访问控制
来源：http://dali.meibo888.top/Article/details/gt2xxstafeq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.birdmap.top/Article/details/gt2iyjukufy.html

PHP:  public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gt2covcgidp.html

JS:   #private 字段；其余公开
来源：http://dali.xuetiantiany.cn/Article/details/gt2puvrqjot.html

TS:   public / protected / private
来源：http://dali.iojbl.cn/Article/details/gt2ivajpkss.html

Java: public / protected / private / 默认包级
来源：http://dali.jqgfzy.top/Article/details/gt2cxnxjpkm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenjidiqi.icu/Article/details/gt2lcmhttfh.html

Ruby: public / protected / private
来源：http://dali.cucudq.cn/Article/details/gt2zwetxkeg.html

C#:   public / protected / private / internal
来源：http://dali.jianghu66.top/Article/details/gt2eopyfamr.html

[G11] getter / setter
来源：http://dali.yvedp.cn/Article/details/gt2gbffgxml.html

Py:   @property 与 @x.setter
来源：http://dali.aibaodan.cn/Article/details/gt2byrxmuqj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ywncwmdi.html

JS:   get name() { return this._name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2osjhsafl.html

TS:   get name(): string { return this._name; }
来源：http://dali.jianghu66.top/Article/details/gt2eklmltgb.html

Java: public String getName() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gt2hhhdtpek.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.svipenyu.cn/Article/details/gt2sooqvkeo.html

Ruby: attr_accessor :name
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yronvnpf.html

C#:   public string Name { get; set; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2pikiacro.html

[G12] 对象转字符串
来源：http://dali.zdqjudy.top/Article/details/gt2tccfslfg.html

Py:   def __str__(self): return self.name
来源：http://dali.xuanzx.com/Article/details/gt2loznpeqv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gadlkosh.html

JS:   toString() { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2achcfoap.html

TS:   toString(): string { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gt2crmfncuf.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2chmohyhc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gt2chxjqblm.html

Ruby: def to_s; @name; end
来源：http://dali.tanke756.top/Article/details/gt2uulgtjpc.html

C#:   public override string ToString() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nhpknshl.html

[G13] 判断对象类型
来源：http://dali.xuanzx.com/Article/details/gt2oxxfgacu.html

Py:   isinstance(u, User)
来源：http://dali.mhx1999.top/Article/details/gt2yvgptlpe.html

PHP:  $u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gt2iymjarzm.html

JS:   u instanceof User
来源：http://dali.fzhhl.top/Article/details/gt2riogbpfx.html

TS:   u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gt2uwxsvsgt.html

Java: u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gt2liehoyem.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ngsdqlfu.html

Ruby: u.is_a?(User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2twimrcxu.html

C#:   u is User
来源：http://dali.svipenyu.cn/Article/details/gt2eniqxdvi.html

[G14] 数据类 / record
来源：http://dali.gogol.net.cn/Article/details/gt2xkaqwmaj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zycfv.cn/Article/details/gt2pqjasmek.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.guowangkeji.top/Article/details/gt2pulgbnks.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.svipenyu.cn/Article/details/gt2kbjoivct.html

TS:   type User = { name: string; age: number };
来源：http://dali.hysaishi.cn/Article/details/gt2xydqngqi.html

Java: record User(String name, int age) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vblkiyhf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yangfankeji.com/Article/details/gt2qyozwjyb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.fengsongda.top/Article/details/gt2eimmapsq.html

C#:   record User(string Name, int Age);
来源：http://dali.jqgufenzy.top/Article/details/gt2apxyixyt.html

[G15] 枚举
来源：http://dali.pengpengdd.cyou/Article/details/gt2pkgusrrx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinqigfzy.top/Article/details/gt2akyhyhgd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenlongwang.top/Article/details/gt2xlnmamcg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yonumen.top/Article/details/gt2mivfbjno.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhengqikj.top/Article/details/gt2qjoxmbec.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ultgqvmz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.haohaochexian.top/Article/details/gt2kokxskdu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yuxming.cn/Article/details/gt2buvqgquq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lsykywzo.html

[G16] 对象转数组 / 字典
来源：http://dali.jqgfzy.top/Article/details/gt2ngisevbe.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hysaishi.cn/Article/details/gt2jmctmkfi.html

PHP:  get_object_vars($obj);
来源：http://dali.dianchejie.cn/Article/details/gt2rcavloke.html

JS:   Object.entries(obj)
来源：http://dali.mhx1999.top/Article/details/gt2mkgqxiek.html

TS:   Object.entries(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2yqzsmuud.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinqigfzy.top/Article/details/gt2zygdlssq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zfmvtvdb.html

Ruby: obj.instance_variables
来源：http://dali.zhongyouzk.top/Article/details/gt2lonwjglp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.0kj1m.cn/Article/details/gt2emryrlkm.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2bxrhcsjm.html


<!-- 参考信息 -->