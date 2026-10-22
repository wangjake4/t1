代发 wailian999

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cdnleiting.top/Article/details/gt2kbuvzlzn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cheryme.top/Article/details/gt2xcuchrlu.html

Ruby: s.capitalize
来源：http://dali.quarkkingdee.top/Article/details/gt2bneprfkp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cucudq.cn/Article/details/gt2wnnbdrda.html

[E18] 模板占位符替换
来源：http://dali.yonumen.top/Article/details/gt2qymgkuut.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.guannengcc.top/Article/details/gt2zcbtzwke.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xziqi.cn/Article/details/gt2boutdgji.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.daxiang520.top/Article/details/gt2cszwrgtr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vvrturrg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hnqzz.top/Article/details/gt2nuenndia.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jianghu66.top/Article/details/gt2doolkzrf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xylfe.cn/Article/details/gt2uamdhvgl.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.svipenyu.cn/Article/details/gt2msloywzg.html

[E19] 多行文本按行拆分
来源：http://dali.sysykeji.top/Article/details/gt2keayhecg.html

Py:   s.splitlines()
来源：http://dali.daria6918.cn/Article/details/gt2myuxyahe.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xsdanmsn.html

JS:   s.split(/\r?\n/)
来源：http://dali.yvedp.cn/Article/details/gt2wvswjyni.html

TS:   s.split(/\r?\n/)
来源：http://dali.cheryme.top/Article/details/gt2grxhcvrv.html

Java: s.lines().toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2izhxblsn.html

Go:   strings.Split(s, "\n")
来源：http://dali.havefunace.top/Article/details/gt2bybqbljq.html

Ruby: s.lines
来源：http://dali.zhoulong.xyz/Article/details/gt2ahukgpti.html

C#:   s.Split('\n')
来源：http://dali.ybcxt.top/Article/details/gt2hghkcwid.html

[E20] 判断字符串是否为空
来源：http://dali.pycfn.com/Article/details/gt2ucccmaze.html

Py:   if not s:
来源：http://dali.ybcxt.top/Article/details/gt2avixqowf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinqigufen.top/Article/details/gt2ffapuisk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xziqi.cn/Article/details/gt2wfvcetfk.html

TS:   if (s === "") {}
来源：http://dali.9152youxi.cn/Article/details/gt2bnkwvqwu.html

Java: if (s.isEmpty()) {}
来源：http://dali.smart0.xyz/Article/details/gt2wdlombpt.html

Go:   if s == "" {}
来源：http://dali.aibaodan.cn/Article/details/gt2wvzrbusk.html

Ruby: if s.empty?
来源：http://dali.jinqigufen.top/Article/details/gt2kglofvej.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2ylbaywvh.html

[E21] 超长截断加省略号
来源：http://dali.c1oappe.top/Article/details/gt2stptxcpu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.meibo888.top/Article/details/gt2zrvrfdhj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gt2owuonjlp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gt2gtvpqbih.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gt2ldluqast.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gt2sdkkdflf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yanxiufei.cn/Article/details/gt2yzwejbbo.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.guannengcc.top/Article/details/gt2xtixtdtv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gt2gtqygpza.html

[E22] 字节长度与字符长度
来源：http://dali.jyoumei.cn/Article/details/gt2iyixsjpr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.iojbl.cn/Article/details/gt2doterxuh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sweek.top/Article/details/gt2dgllkjop.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tianlin.xyz/Article/details/gt2ojidnjkz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gt2qtwnbpag.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.tian-w.cn/Article/details/gt2mnbtzbdc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xuanzx.com/Article/details/gt2buefwghs.html

Ruby: s.bytesize;  s.length
来源：http://dali.gzhubu.top/Article/details/gt2ygpxgxtv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhixingplan.top/Article/details/gt2dkcmteox.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2mpimmgvu.html

F. 文件与目录
来源：http://dali.sweek.top/Article/details/gt2yqfxdyds.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2ddsnkhmj.html

[F01] 读取整个文件
来源：http://dali.xylfe.cn/Article/details/gt2vqnkxkqe.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.vqdsnc.cn/Article/details/gt2lbkxzhdr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2bjksmkby.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.vqdsnc.cn/Article/details/gt2mnxtflmi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.bjfxy.top/Article/details/gt2tmcamebg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gt2hkokyvsr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gotoacloud.top/Article/details/gt2zzuoqvjs.html

Ruby: File.read("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2ioxbuokf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2bilzlbzx.html

[F02] 逐行读取文件
来源：http://dali.gotoacloud.top/Article/details/gt2tgbiaxxb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gotoacloud.top/Article/details/gt2vrkyskpz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ivvv.top/Article/details/gt2bklrhmve.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nwbrower.top/Article/details/gt2yymjppkt.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2musahjjk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.wangdashe.top/Article/details/gt2kccjjsyz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qjjaixcf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.havefunace.top/Article/details/gt2uiqqyxus.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2kmjftqre.html

[F03] 写入文件（覆盖）
来源：http://dali.xinyue.icu/Article/details/gt2wspcoftj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tianlin.xyz/Article/details/gt2qshwabwx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jyoumei.cn/Article/details/gt2helxguwr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258888.top/Article/details/gt2ngjayawz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.mhx1999.top/Article/details/gt2xbytolii.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cheryme.top/Article/details/gt2bnouyyfw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xuanzx.com/Article/details/gt2cqlsytau.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.9152youxi.cn/Article/details/gt2hdlclbab.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.dashuyun.cn/Article/details/gt2weguomzz.html

[F04] 追加写入文件
来源：http://dali.zhongyouzk.top/Article/details/gt2bncufsoa.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sxryk.cn/Article/details/gt2jgywryss.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.chenjidiqi.icu/Article/details/gt2mxptnsjn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jianghu66.top/Article/details/gt2ifigewlc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.mhx1999.top/Article/details/gt2rygwwmwq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hywenlv.cn/Article/details/gt2uzixckqn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xuanzx.com/Article/details/gt2ccbgrcar.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.guannengcc.top/Article/details/gt2hhlyvwzd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2retxwsos.html

[F05] 判断文件或目录是否存在
来源：http://dali.gotoacloud.top/Article/details/gt2zgbkjrtk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ixijjicd.html

PHP:  file_exists("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2snyerala.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2zvfxhzpp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2ihrjrxag.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gt2lyzhrlsl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yueranfly.top/Article/details/gt2vduyeurp.html

Ruby: File.exist?("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2zovxyvfr.html

C#:   File.Exists("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2zdktqpws.html

[F06] 删除文件
来源：http://dali.9152youxi.cn/Article/details/gt2koroozlm.html

Py:   os.remove("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2nudtxasr.html

PHP:  unlink("a.txt");
来源：http://dali.ybcxt.top/Article/details/gt2zlnaudah.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2upbzgwfv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2uyeexxpr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hhyonswj.html

Go:   os.Remove("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2psklhjdk.html

Ruby: File.delete("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2iizzncks.html

C#:   File.Delete("a.txt");
来源：http://dali.birdmap.top/Article/details/gt2pwrwsuya.html

[F07] 创建目录（含多级）
来源：http://dali.fengsongda.top/Article/details/gt2eqylqnlk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cashguo.top/Article/details/gt2amnnlhrf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.9152youxi.cn/Article/details/gt2rwsjhmou.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dfdosaol.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shuidangran.top/Article/details/gt2mblenbuk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yanxiufei.cn/Article/details/gt2ktucfxkk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.wangdashe.top/Article/details/gt2tglhewru.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhixingplan.top/Article/details/gt2wopbzmxr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xziqi.cn/Article/details/gt2syrokcol.html

[F08] 遍历目录
来源：http://dali.fzhhl.top/Article/details/gt2stmoilni.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinqigufen.top/Article/details/gt2opccamwx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ehwqpu.com/Article/details/gt2ogbknazs.html

JS:   fs.readdirSync("dir")
来源：http://dali.guannengcc.top/Article/details/gt2xifbripr.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenlongwang.top/Article/details/gt2meqdaefd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sysykeji.top/Article/details/gt2fdsnmfhd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.kuanghao11.cn/Article/details/gt2yyjbfjsk.html

Ruby: Dir.children("dir")
来源：http://dali.mhx1999.top/Article/details/gt2ryvndlhd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hammf.cn/Article/details/gt2jplcgxyv.html

[F09] 获取文件大小
来源：http://dali.vqdsnc.cn/Article/details/gt2zxvndiiw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2aojazcyo.html

PHP:  filesize("a.txt");
来源：http://dali.gzhubu.top/Article/details/gt2kkotyyaa.html

JS:   fs.statSync("a.txt").size
来源：http://dali.svipenyu.cn/Article/details/gt2zsmowpnd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yuanzhike.top/Article/details/gt2ozifldkx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gt2bfpbvvsf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.havefunace.top/Article/details/gt2npbikhsu.html

Ruby: File.size("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2wpspboiv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gotoacloud.top/Article/details/gt2eassktly.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.316326.xyz/Article/details/gt2crzgymzj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2qhmicgak.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cheryme.top/Article/details/gt2apkdvjes.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2qlmwumhj.html

TS:   path.extname("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2uvyvvhqd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hysaishi.cn/Article/details/gt2kilwqmwt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hyuleara.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2oimujbwb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2nakmjcja.html

[F11] 复制与移动文件
来源：http://dali.birdmap.top/Article/details/gt2rnunfnfg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2wvlbkjmo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2rvhujeyc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2jaggxney.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gt2kamlpwnm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ybcxt.top/Article/details/gt2zqstvgwb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yonumen.top/Article/details/gt2evqsrnpb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eyfvovqn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cheryme.top/Article/details/gt2sgwfppao.html

[F12] CSV 读写
来源：http://dali.yj202588.top/Article/details/gt2ixiglxik.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gaohongyu789.top/Article/details/gt2hicxrumd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hnqzz.top/Article/details/gt2mkohhnhc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hammf.cn/Article/details/gt2qyibldcc.html

TS:   // 同上
来源：http://dali.yuanzhike.top/Article/details/gt2avpanlsd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yonumen.top/Article/details/gt2xmeewowi.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ydzc1.top/Article/details/gt2pksgptgx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sxryk.cn/Article/details/gt2wfclkvul.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gogol.net.cn/Article/details/gt2biwcrewn.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2xsfuooel.html

G. 面向对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dlgiodit.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2tdeqcemy.html

[G01] 定义类
来源：http://dali.aizwys.cn/Article/details/gt2tgzmtldc.html

Py:   class User: pass
来源：http://dali.sufxvd.cn/Article/details/gt2pxvggoac.html

PHP:  class User {}
来源：http://dali.yj20258.top/Article/details/gt2orrtjjjf.html

JS:   class User {}
来源：http://dali.ydzc1.top/Article/details/gt2uygfjwem.html

TS:   class User { name: string = ""; }
来源：http://dali.haohaochexian.top/Article/details/gt2aztsmwhl.html

Java: class User {}
来源：http://dali.zhengqikj.top/Article/details/gt2uhmpqlnb.html

Go:   type User struct { Name string }
来源：http://dali.aizwys.cn/Article/details/gt2jdficnfu.html

Ruby: class User; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2rtoeduma.html

C#:   class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kthoxmgl.html

[G02] 构造函数
来源：http://dali.hnqzz.top/Article/details/gt2juxmfvwp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yuxming.cn/Article/details/gt2hcrmrwhg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.redwolf501.top/Article/details/gt2fppqpjfw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.mhx1999.top/Article/details/gt2wxamfaap.html

TS:   constructor(public name: string) {}
来源：http://dali.haohaochexian.top/Article/details/gt2nmiskywu.html

Java: User(String name) { this.name = name; }
来源：http://dali.ehwqpu.com/Article/details/gt2rchiizdt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.chenlongwang.top/Article/details/gt2enzeeyzj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hnxiangtu.top/Article/details/gt2uqrouquw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2wsswczem.html

[G03] 实例属性
来源：http://dali.jinghuilouyu.cn/Article/details/gt2calbazro.html

Py:   self.name = "x"
来源：http://dali.sysykeji.top/Article/details/gt2ylgxddkf.html

PHP:  public string $name = "x";
来源：http://dali.cashguo.top/Article/details/gt2mcetfjhr.html

JS:   this.name = "x";
来源：http://dali.shzxlz.cn/Article/details/gt2qgxxlyek.html

TS:   name: string = "x";
来源：http://dali.ydzc1.top/Article/details/gt2fwembotj.html

Java: private String name;
来源：http://dali.hysaishi.cn/Article/details/gt2bnccfubq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sufxvd.cn/Article/details/gt2mcrlvddc.html

Ruby: @name = "x"
来源：http://dali.yanxiufei.cn/Article/details/gt2bgweukud.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.wangdashe.top/Article/details/gt2glqkjdoy.html

[G04] 定义方法
来源：http://dali.hnxiangtu.top/Article/details/gt2lmhljeso.html

Py:   def greet(self): return self.name
来源：http://dali.kuanghao11.cn/Article/details/gt2hpfegdtm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uiutxnok.html

JS:   greet() { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2zhiuypjl.html

TS:   greet(): string { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gt2ofevldqx.html

Java: String greet() { return name; }
来源：http://dali.xuanzx.com/Article/details/gt2ufwwffbc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gt2yhmboqpo.html

Ruby: def greet; @name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tmxxwajw.html

C#:   public string Greet() => Name;
来源：http://dali.nanxuanxn.top/Article/details/gt2ekjjrznw.html

[G05] 继承
来源：http://dali.aizwys.cn/Article/details/gt2iqhfaixx.html

Py:   class Admin(User): pass
来源：http://dali.chenzaomai.com/Article/details/gt2prkurwli.html

PHP:  class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gt2hqxlykzd.html

JS:   class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gt2tozrmnkg.html

TS:   class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gt2pnbqqcek.html

Java: class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xglymacn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.daria6918.cn/Article/details/gt2cgavfosw.html

Ruby: class Admin < User; end
来源：http://dali.ivvv.top/Article/details/gt2axuyzsrj.html

C#:   class Admin : User {}
来源：http://dali.cashguo.top/Article/details/gt2nwshmall.html

[G06] 重写方法
来源：http://dali.shangyingyoupin.top/Article/details/gt2gtxqffeh.html

Py:   def greet(self): return "admin"
来源：http://dali.zhixingplan.top/Article/details/gt2cerfzkxp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gt2cxxoophy.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkcfnddx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sgcybwgn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gt2ormbzrgu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jqgfzy.top/Article/details/gt2gulvapuj.html

Ruby: def greet; "admin"; end
来源：http://dali.nwbrower.top/Article/details/gt2zysmqahr.html

C#:   public override string Greet() => "admin";
来源：http://dali.xuanzx.com/Article/details/gt2kyjyxwfm.html

[G07] 调用父类方法
来源：http://dali.meibo888.top/Article/details/gt2owsamyqd.html

Py:   super().greet()
来源：http://dali.yj20258888.top/Article/details/gt2qqolcmpo.html

PHP:  parent::greet();
来源：http://dali.tianlin.xyz/Article/details/gt2uhifleux.html

JS:   super.greet();
来源：http://dali.mhx1999.top/Article/details/gt2kdhnykli.html

TS:   super.greet();
来源：http://dali.sysykeji.top/Article/details/gt2pikhrrau.html

Java: super.greet();
来源：http://dali.xinyue.icu/Article/details/gt2btqdklbt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj20258.top/Article/details/gt2xhusgirn.html

Ruby: super
来源：http://dali.ivvv.top/Article/details/gt2mmngsvdn.html

C#:   base.Greet();
来源：http://dali.haohaochexian.top/Article/details/gt2ggkwelyx.html

[G08] 静态方法与属性
来源：http://dali.aizwys.cn/Article/details/gt2qqfetdbv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hysaishi.cn/Article/details/gt2rcpghnhr.html

PHP:  public static function f() {}
来源：http://dali.hywenlv.cn/Article/details/gt2iqmzljty.html

JS:   static f() {}
来源：http://dali.hammf.cn/Article/details/gt2oaxrxyea.html

TS:   static f(): void {}
来源：http://dali.iojbl.cn/Article/details/gt2oblnfrbh.html

Java: static void f() {}
来源：http://dali.dashuyun.cn/Article/details/gt2lucyqybl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gzhubu.top/Article/details/gt2atuclhww.html

Ruby: def self.f; end
来源：http://dali.nanxinkj.top/Article/details/gt2uwdhsapp.html

C#:   public static void F() {}
来源：http://dali.shuidangran.top/Article/details/gt2nmmmxyfl.html

[G09] 接口 / 抽象类
来源：http://dali.kuanghao11.cn/Article/details/gt2eyrfznfw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.wangdashe.top/Article/details/gt2zqlkcagw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xzcjpbcl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zdqjudy.top/Article/details/gt2yzyutsvf.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtetgvmc.html

Java: interface Shape { double area(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2qudvzitg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.pengpengdd.cyou/Article/details/gt2tmhoitwr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yueranfly.top/Article/details/gt2cljquaxb.html

C#:   interface IShape { double Area(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2zbzncipt.html

[G10] 访问控制
来源：http://dali.ivvv.top/Article/details/gt2mjklikxp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj20258888.top/Article/details/gt2vvriukjd.html

PHP:  public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gt2ibzvkqkd.html

JS:   #private 字段；其余公开
来源：http://dali.jiagoushi.top/Article/details/gt2acmjbpju.html

TS:   public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gt2ezzzabyx.html

Java: public / protected / private / 默认包级
来源：http://dali.jianghu66.top/Article/details/gt2iqjunbpc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tianlin.xyz/Article/details/gt2ajgwwngy.html

Ruby: public / protected / private
来源：http://dali.hammf.cn/Article/details/gt2xcbhajzd.html

C#:   public / protected / private / internal
来源：http://dali.yuanzhike.top/Article/details/gt2wdecenwh.html

[G11] getter / setter
来源：http://dali.cqqwz.cn/Article/details/gt2tkomnmli.html

Py:   @property 与 @x.setter
来源：http://dali.redwolf501.top/Article/details/gt2bfgkvxdz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gt2btukbihl.html

JS:   get name() { return this._name; }
来源：http://dali.hfpthk.cn/Article/details/gt2fjzbqftm.html

TS:   get name(): string { return this._name; }
来源：http://dali.bjfxy.top/Article/details/gt2dfbdbhrl.html

Java: public String getName() { return name; }
来源：http://dali.sweek.top/Article/details/gt2qbfswgje.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.0kj1m.cn/Article/details/gt2wvnfekde.html

Ruby: attr_accessor :name
来源：http://dali.ybcxt.top/Article/details/gt2pegffdff.html

C#:   public string Name { get; set; }
来源：http://dali.c1oappe.top/Article/details/gt2yzkgewxz.html

[G12] 对象转字符串
来源：http://dali.jqgfzy.top/Article/details/gt2ufyottlw.html

Py:   def __str__(self): return self.name
来源：http://dali.aibaodan.cn/Article/details/gt2zgraryiy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gt2pqhgbdnr.html

JS:   toString() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gt2jnclnjbt.html

TS:   toString(): string { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2orytgcmz.html

Java: @Override public String toString() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qjlmtmay.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gt2rxsuoolo.html

Ruby: def to_s; @name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vpvztksf.html

C#:   public override string ToString() => Name;
来源：http://dali.guowangkeji.top/Article/details/gt2migncjvs.html

[G13] 判断对象类型
来源：http://dali.9152youxi.cn/Article/details/gt2awpsxvos.html

Py:   isinstance(u, User)
来源：http://dali.gotoacloud.top/Article/details/gt2vyjigjub.html

PHP:  $u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gt2xbakelcm.html

JS:   u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gt2lwuttrte.html

TS:   u instanceof User
来源：http://dali.yonumen.top/Article/details/gt2hdjemcpm.html

Java: u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gt2spcaeqyi.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.daria6918.cn/Article/details/gt2voweeetk.html

Ruby: u.is_a?(User)
来源：http://dali.svipenyu.cn/Article/details/gt2ouwarkcm.html

C#:   u is User
来源：http://dali.ehwqpu.com/Article/details/gt2mnseixms.html

[G14] 数据类 / record
来源：http://dali.svipenyu.cn/Article/details/gt2vuglmgwg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.0kj1m.cn/Article/details/gt2mbbaixnk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.fengsongda.top/Article/details/gt2bqbqezev.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hysaishi.cn/Article/details/gt2tmstadoj.html

TS:   type User = { name: string; age: number };
来源：http://dali.shuidangran.top/Article/details/gt2ldqizbde.html

Java: record User(String name, int age) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2exttsjlh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hfpthk.cn/Article/details/gt2lqtvxviv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jyoumei.cn/Article/details/gt2axnakegj.html

C#:   record User(string Name, int Age);
来源：http://dali.aizwys.cn/Article/details/gt2hmllcaao.html

[G15] 枚举
来源：http://dali.redwolf501.top/Article/details/gt2wzdshkcm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yueranfly.top/Article/details/gt2zfxnaqnz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nanxinkj.top/Article/details/gt2iwllxwhm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shangyingyoupin.top/Article/details/gt2pyhlltik.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hfpthk.cn/Article/details/gt2wyrahmqk.html

Java: enum Color { RED, GREEN }
来源：http://dali.haohaochexian.top/Article/details/gt2zagxokdt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2prwhiwpr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.dashuyun.cn/Article/details/gt2ohzcvcee.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.birdmap.top/Article/details/gt2sohmtvyn.html

[G16] 对象转数组 / 字典
来源：http://dali.xuanzx.com/Article/details/gt2mocxlloa.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.fengsongda.top/Article/details/gt2ddngrtjq.html


<!-- 参考信息 -->