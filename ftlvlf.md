代发 wailian999

PHP:  number_format(1234567);
来源：http://dali.dianchejie.cn/Article/details/gtkugvhvtt.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangdashe.top/Article/details/gtamdrihxd.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj202588.top/Article/details/gtbngybjgc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yuanzhike.top/Article/details/gttfkcfvez.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.mhx1999.top/Article/details/gtkhdqskhr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzkitunyd.html

C#:   1234567.ToString("N0")
来源：http://dali.yuanzhike.top/Article/details/gtxsvidski.html

[E17] 首字母大写
来源：http://dali.cucudq.cn/Article/details/gtcjblwvgj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hysaishi.cn/Article/details/gtxhmslhza.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shzxlz.cn/Article/details/gtwzvipsan.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigufen.top/Article/details/gtqkioysxo.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnxiangtu.top/Article/details/gtspcnekvy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.mhx1999.top/Article/details/gtjdisokvi.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tanke756.top/Article/details/gtjbfefagn.html

Ruby: s.capitalize
来源：http://dali.hnxiangtu.top/Article/details/gtrhapctti.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ppjwa.cn/Article/details/gtpytntkfo.html

[E18] 模板占位符替换
来源：http://dali.ppjwa.cn/Article/details/gtjvniklnw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yangfankeji.com/Article/details/gtyrirxozf.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jyoumei.cn/Article/details/gtscbdoymq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.fengsongda.top/Article/details/gtycnfzalu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cheryme.top/Article/details/gteiimffss.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gtcgxofpda.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gttllnglze.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ybcxt.top/Article/details/gtusjblgeq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.aizwys.cn/Article/details/gtfbxvvdzu.html

[E19] 多行文本按行拆分
来源：http://dali.yj20258.top/Article/details/gtqqucyaeo.html

Py:   s.splitlines()
来源：http://dali.yongpay.top/Article/details/gtofipiism.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.sysykeji.top/Article/details/gtfeoyuwrh.html

JS:   s.split(/\r?\n/)
来源：http://dali.andypj.xyz/Article/details/gtwbfrvttm.html

TS:   s.split(/\r?\n/)
来源：http://dali.ydzc1.top/Article/details/gtuiygpesa.html

Java: s.lines().toList()
来源：http://dali.hysaishi.cn/Article/details/gtoiyhsgnj.html

Go:   strings.Split(s, "\n")
来源：http://dali.hnqzz.top/Article/details/gtwcvullgd.html

Ruby: s.lines
来源：http://dali.jqgufenzy.top/Article/details/gtnhegrzwo.html

C#:   s.Split('\n')
来源：http://dali.quarkkingdee.top/Article/details/gtamokmhac.html

[E20] 判断字符串是否为空
来源：http://dali.yj202588.top/Article/details/gtwubpzkps.html

Py:   if not s:
来源：http://dali.gotoacloud.top/Article/details/gtfumguinq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hammf.cn/Article/details/gtooorcsgv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hywenlv.cn/Article/details/gtchnajbsh.html

TS:   if (s === "") {}
来源：http://dali.yvedp.cn/Article/details/gtbrlvljtd.html

Java: if (s.isEmpty()) {}
来源：http://dali.gotoacloud.top/Article/details/gtoiomjvaa.html

Go:   if s == "" {}
来源：http://dali.svipenyu.cn/Article/details/gtkmpcophf.html

Ruby: if s.empty?
来源：http://dali.jqgufenzy.top/Article/details/gtlyssjwmu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenlongwang.top/Article/details/gtodfqyyku.html

[E21] 超长截断加省略号
来源：http://dali.chenzaomai.com/Article/details/gtgxrntgva.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yueranfly.top/Article/details/gtqicvwvjy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gtmexzqapk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtcivzvxex.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sxryk.cn/Article/details/gtbaysmhuz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtaeouzoye.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.feifeiyinyue.top/Article/details/gtnkaevlvj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtwracbgaz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtizicgcpp.html

[E22] 字节长度与字符长度
来源：http://dali.hnxiangtu.top/Article/details/gtmmuzcqjj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nanxinkj.top/Article/details/gtvpgwaezz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gtivspwfvn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hywenlv.cn/Article/details/gtddibrybs.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cdnleiting.top/Article/details/gtsfgbawbm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sufxvd.cn/Article/details/gtlsuknoep.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.316326.xyz/Article/details/gtbrytcimp.html

Ruby: s.bytesize;  s.length
来源：http://dali.xylfe.cn/Article/details/gtqxnkpnft.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hywenlv.cn/Article/details/gtwfeywvnq.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtknyrponf.html

F. 文件与目录
来源：http://dali.hongshengwenyu.top/Article/details/gtepvvkhrj.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gttzdltxud.html

[F01] 读取整个文件
来源：http://dali.zhixingplan.top/Article/details/gtmajbkbfg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.bjfxy.top/Article/details/gtezdzbizq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtcozeymen.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hywenlv.cn/Article/details/gtgqjlgvib.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yvedp.cn/Article/details/gtywjpfgml.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gtgtcodmxm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.svipenyu.cn/Article/details/gtjmlxvqgs.html

Ruby: File.read("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtehgoushx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtlqtsndel.html

[F02] 逐行读取文件
来源：http://dali.tian-w.cn/Article/details/gtbgnsbnqw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shzxlz.cn/Article/details/gthaikfqjs.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gotoacloud.top/Article/details/gthvbhbasl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiavmlnxe.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hysaishi.cn/Article/details/gtvacwjome.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cqqwz.cn/Article/details/gtgaxnlwsh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinqigufen.top/Article/details/gtarajcfek.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.0kj1m.cn/Article/details/gthpsodslq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xuanzx.com/Article/details/gtjdhocjnt.html

[F03] 写入文件（覆盖）
来源：http://dali.hywenlv.cn/Article/details/gtsquvkxgm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shuidangran.top/Article/details/gtgplbikgi.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinqigfzy.top/Article/details/gtnedoftyk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shuidangran.top/Article/details/gtrwbqgmtw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj202588.top/Article/details/gtsijjsmki.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.pycfn.com/Article/details/gtcdrgmpix.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpusvgswv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.bjfxy.top/Article/details/gtyihtnbbh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yueranfly.top/Article/details/gtxfltrqox.html

[F04] 追加写入文件
来源：http://dali.aibaodan.cn/Article/details/gthenvxwms.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.dianchejie.cn/Article/details/gtzlhbgqhb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jqgfzy.top/Article/details/gttiwozkgo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuanzhike.top/Article/details/gtidlscgdm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.c1oappe.top/Article/details/gtiqqqbdkl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhiwuduotai.top/Article/details/gteduegvue.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.c1oappe.top/Article/details/gthfhqzmps.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jiagoushi.top/Article/details/gtgjprbvrc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nwbrower.top/Article/details/gtmxqncyrx.html

[F05] 判断文件或目录是否存在
来源：http://dali.sysykeji.top/Article/details/gtavlqykdm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhoulong.xyz/Article/details/gtpdmsxozv.html

PHP:  file_exists("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtbxivuynn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtpwrsppuh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gtwrryqliu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gtumkjnytz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yj20258.top/Article/details/gtubyxzvtu.html

Ruby: File.exist?("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtxmzhbsuy.html

C#:   File.Exists("a.txt")
来源：http://dali.tian-w.cn/Article/details/gthdcztkob.html

[F06] 删除文件
来源：http://dali.ybcxt.top/Article/details/gtxpaqtosu.html

Py:   os.remove("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthbyyiqvz.html

PHP:  unlink("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtedoktbab.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gttpvnqmua.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtctnghheu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gtzsnmkoyw.html

Go:   os.Remove("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtspiuvzlt.html

Ruby: File.delete("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtvgaiihzo.html

C#:   File.Delete("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gttemjhzpn.html

[F07] 创建目录（含多级）
来源：http://dali.zhengqikj.top/Article/details/gtnbxbeypq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhiwuduotai.top/Article/details/gteqrpzlqo.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj20258888.top/Article/details/gtixtrcank.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sufxvd.cn/Article/details/gtmtxruzmz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yueranfly.top/Article/details/gtjytmivth.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yongpay.top/Article/details/gtbzeatljw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.vqdsnc.cn/Article/details/gtcsbuvgkh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sweek.top/Article/details/gtwaumkktk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cheryme.top/Article/details/gtmaumtjoe.html

[F08] 遍历目录
来源：http://dali.fengsongda.top/Article/details/gtzsgqgkaw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhixingplan.top/Article/details/gtlknuhifw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.c1oappe.top/Article/details/gtgyrfkzlx.html

JS:   fs.readdirSync("dir")
来源：http://dali.yongpay.top/Article/details/gtpcmtgygv.html

TS:   fs.readdirSync("dir")
来源：http://dali.daxiang520.top/Article/details/gtoqwtfrjv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenlongwang.top/Article/details/gtfuvrquht.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtnxyryzxd.html

Ruby: Dir.children("dir")
来源：http://dali.dashuyun.cn/Article/details/gtfukxrqnb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hysaishi.cn/Article/details/gtpwwnjfaj.html

[F09] 获取文件大小
来源：http://dali.xinyue.icu/Article/details/gtyruaeseg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cheryme.top/Article/details/gtlaceyodj.html

PHP:  filesize("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtyzhomzqk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.aibaodan.cn/Article/details/gtodwuvbhs.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xziqi.cn/Article/details/gtaffuiaee.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gtgvhzhrlw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.smart0.xyz/Article/details/gtqrickxmx.html

Ruby: File.size("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtyxczmjph.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gtmnwurkhm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cashguo.top/Article/details/gtjfmzaoyt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtrjrpfshn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtqyuvnfck.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjafdlpsz.html

TS:   path.extname("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtofnnlkat.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.redwolf501.top/Article/details/gtspbivbkf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtnfcnttjl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtpsxcaerc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtvhxrlajk.html

[F11] 复制与移动文件
来源：http://dali.tianlin.xyz/Article/details/gtpdqitsdx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gtoplhjqno.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.redwolf501.top/Article/details/gtjazvkvkp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtrmramnxo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gtifscfwzu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tianlin.xyz/Article/details/gtpwycynsd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zycfv.cn/Article/details/gtebpcjyfq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gtebyqdsxy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.pycfn.com/Article/details/gtktdsbzgx.html

[F12] CSV 读写
来源：http://dali.jlsjyb.cn/Article/details/gtxrfsibug.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ybcxt.top/Article/details/gtamoihwrm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenzaomai.com/Article/details/gtcrgoitwk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yueranfly.top/Article/details/gtbololnrk.html

TS:   // 同上
来源：http://dali.andypj.xyz/Article/details/gttqzewgpm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jqgfzy.top/Article/details/gtcfeqlyao.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gzhubu.top/Article/details/gttcpclngz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.birdmap.top/Article/details/gtohlsmhjs.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yuxming.cn/Article/details/gtstzxwuow.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gthpallchl.html

G. 面向对象
来源：http://dali.hysaishi.cn/Article/details/gttetnwemj.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gttzhbykyi.html

[G01] 定义类
来源：http://dali.aibaodan.cn/Article/details/gtraygttms.html

Py:   class User: pass
来源：http://dali.daxiang520.top/Article/details/gtyecfqbxz.html

PHP:  class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtedxykuui.html

JS:   class User {}
来源：http://dali.jinqigufen.top/Article/details/gthnllcqyr.html

TS:   class User { name: string = ""; }
来源：http://dali.jinqigufen.top/Article/details/gtfoyejhvs.html

Java: class User {}
来源：http://dali.hywenlv.cn/Article/details/gtvrgaxzyx.html

Go:   type User struct { Name string }
来源：http://dali.shangyingyoupin.top/Article/details/gtwfowukts.html

Ruby: class User; end
来源：http://dali.wangdashe.top/Article/details/gtedyfkwwx.html

C#:   class User {}
来源：http://dali.yongpay.top/Article/details/gtmueblite.html

[G02] 构造函数
来源：http://dali.haohaochexian.top/Article/details/gtlyzgmtbo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.dashuyun.cn/Article/details/gtdmxhytzk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.mhx1999.top/Article/details/gtholrkspk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tanke756.top/Article/details/gtwtovmufm.html

TS:   constructor(public name: string) {}
来源：http://dali.gzhubu.top/Article/details/gtlbnfprgn.html

Java: User(String name) { this.name = name; }
来源：http://dali.nwbrower.top/Article/details/gtxrmvbyjo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gaohongyu789.top/Article/details/gtvqjbjapu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenzaomai.com/Article/details/gtzqznoypw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnayqdodd.html

[G03] 实例属性
来源：http://dali.ehwqpu.com/Article/details/gtztjyrxbp.html

Py:   self.name = "x"
来源：http://dali.316326.xyz/Article/details/gtoisrffyw.html

PHP:  public string $name = "x";
来源：http://dali.yj20258888.top/Article/details/gtlmgclfbn.html

JS:   this.name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtgetwuspk.html

TS:   name: string = "x";
来源：http://dali.redwolf501.top/Article/details/gtvvyvmtbz.html

Java: private String name;
来源：http://dali.guowangkeji.top/Article/details/gteqspykcr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yangfankeji.com/Article/details/gtoqkphbwj.html

Ruby: @name = "x"
来源：http://dali.yvedp.cn/Article/details/gtwwksddds.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jqgfzy.top/Article/details/gtgysclxil.html

[G04] 定义方法
来源：http://dali.sufxvd.cn/Article/details/gtrkcefryq.html

Py:   def greet(self): return self.name
来源：http://dali.fengsongda.top/Article/details/gtpvufmhgt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtmcsmhoqa.html

JS:   greet() { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtjridqxkc.html

TS:   greet(): string { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtvruxsitg.html

Java: String greet() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtfqwvggph.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gtahomlizi.html

Ruby: def greet; @name; end
来源：http://dali.chenlongwang.top/Article/details/gtyfxhbofl.html

C#:   public string Greet() => Name;
来源：http://dali.iojbl.cn/Article/details/gtayfcuaug.html

[G05] 继承
来源：http://dali.daxiang520.top/Article/details/gtyjpcinjb.html

Py:   class Admin(User): pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvdtlajdb.html

PHP:  class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gtqkixhhlf.html

JS:   class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtgbdcfjdk.html

TS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtvmtzvabt.html

Java: class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtgaklgqxd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.vqdsnc.cn/Article/details/gtlqulrewb.html

Ruby: class Admin < User; end
来源：http://dali.zhongyouzk.top/Article/details/gtekyexckj.html

C#:   class Admin : User {}
来源：http://dali.hammf.cn/Article/details/gtuukcanlh.html

[G06] 重写方法
来源：http://dali.gogol.net.cn/Article/details/gtkmbwtzou.html

Py:   def greet(self): return "admin"
来源：http://dali.dianchejie.cn/Article/details/gtdljjdczj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtuwqyugth.html

JS:   greet() { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gttnkyjwep.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtxreubjcm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gtcjwqimku.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenjidiqi.icu/Article/details/gtcykjlgzc.html

Ruby: def greet; "admin"; end
来源：http://dali.yuanzhike.top/Article/details/gtcxawkvar.html

C#:   public override string Greet() => "admin";
来源：http://dali.yueranfly.top/Article/details/gtcynyzxzy.html

[G07] 调用父类方法
来源：http://dali.zhiwuduotai.top/Article/details/gtivfagvjd.html

Py:   super().greet()
来源：http://dali.jiagoushi.top/Article/details/gtpfweswjq.html

PHP:  parent::greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtsyrbhbbn.html

JS:   super.greet();
来源：http://dali.pycfn.com/Article/details/gtzutzocif.html

TS:   super.greet();
来源：http://dali.smart0.xyz/Article/details/gtsvkxcher.html

Java: super.greet();
来源：http://dali.ehwqpu.com/Article/details/gthqtbmwsi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhiwuduotai.top/Article/details/gtnrpxzono.html

Ruby: super
来源：http://dali.hnqzz.top/Article/details/gtihqvhmrt.html

C#:   base.Greet();
来源：http://dali.jlsjyb.cn/Article/details/gtzjtxnehy.html

[G08] 静态方法与属性
来源：http://dali.nanxuanxn.top/Article/details/gtsaccjmey.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jiagoushi.top/Article/details/gtfdggvtrc.html

PHP:  public static function f() {}
来源：http://dali.9152youxi.cn/Article/details/gtmekyzvxn.html

JS:   static f() {}
来源：http://dali.sufxvd.cn/Article/details/gtsbswjyyy.html

TS:   static f(): void {}
来源：http://dali.cucudq.cn/Article/details/gtlgiohepd.html

Java: static void f() {}
来源：http://dali.yvedp.cn/Article/details/gtskivmvie.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nwbrower.top/Article/details/gtxwduzoqg.html

Ruby: def self.f; end
来源：http://dali.zhixingplan.top/Article/details/gtkuwfuodv.html

C#:   public static void F() {}
来源：http://dali.shzxlz.cn/Article/details/gtbxoadlrz.html

[G09] 接口 / 抽象类
来源：http://dali.gotoacloud.top/Article/details/gtvuopmeoz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmwizpjq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnbymdqid.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cucudq.cn/Article/details/gtlrwxhlgv.html

TS:   interface Shape { area(): number; }
来源：http://dali.shzxlz.cn/Article/details/gthnnmsbms.html

Java: interface Shape { double area(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnrpjnuic.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xuanzx.com/Article/details/gtwuxvytha.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xuanzx.com/Article/details/gtzhxaxfdk.html

C#:   interface IShape { double Area(); }
来源：http://dali.jqgfzy.top/Article/details/gtbvelovtr.html

[G10] 访问控制
来源：http://dali.kuanghao11.cn/Article/details/gtelpcarvt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hnqzz.top/Article/details/gthapfpmie.html

PHP:  public / protected / private
来源：http://dali.fzhhl.top/Article/details/gtywxwzxmy.html

JS:   #private 字段；其余公开
来源：http://dali.hysaishi.cn/Article/details/gtfwmdhuxl.html

TS:   public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gtjjleahgy.html

Java: public / protected / private / 默认包级
来源：http://dali.chenlongwang.top/Article/details/gtclhziutc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgfbmjyvx.html

Ruby: public / protected / private
来源：http://dali.cucudq.cn/Article/details/gtpdorxrkl.html

C#:   public / protected / private / internal
来源：http://dali.fengsongda.top/Article/details/gtrfxhptln.html

[G11] getter / setter
来源：http://dali.yvedp.cn/Article/details/gtvrixxulj.html

Py:   @property 与 @x.setter
来源：http://dali.havefunace.top/Article/details/gtmgvrvkmo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gtxqsklvjn.html

JS:   get name() { return this._name; }
来源：http://dali.yangfankeji.com/Article/details/gtcaabdvnc.html

TS:   get name(): string { return this._name; }
来源：http://dali.xziqi.cn/Article/details/gtlcummrlu.html

Java: public String getName() { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gteycnkidy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gtgwtmpwya.html

Ruby: attr_accessor :name
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkyimbji.html

C#:   public string Name { get; set; }
来源：http://dali.jyoumei.cn/Article/details/gtmckwnmlh.html

[G12] 对象转字符串
来源：http://dali.iojbl.cn/Article/details/gtrxwlsjrl.html

Py:   def __str__(self): return self.name
来源：http://dali.nwbrower.top/Article/details/gtbkqpwero.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gteeyskxeq.html

JS:   toString() { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtwvwgbtsy.html

TS:   toString(): string { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtilpvbkki.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlwntfdfr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gtuddtiqmk.html

Ruby: def to_s; @name; end
来源：http://dali.daria6918.cn/Article/details/gtewdavmjh.html

C#:   public override string ToString() => Name;
来源：http://dali.zhongyouzk.top/Article/details/gtxzsouooq.html

[G13] 判断对象类型
来源：http://dali.0kj1m.cn/Article/details/gthqhiylup.html

Py:   isinstance(u, User)
来源：http://dali.9152youxi.cn/Article/details/gthrheritm.html

PHP:  $u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gtgygnewrk.html

JS:   u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gtohmkjfyz.html

TS:   u instanceof User
来源：http://dali.yonumen.top/Article/details/gtrjlwkovo.html

Java: u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gtrwoqkjwy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sufxvd.cn/Article/details/gttwftrkqi.html

Ruby: u.is_a?(User)
来源：http://dali.shangyingyoupin.top/Article/details/gthrwwsbcy.html

C#:   u is User
来源：http://dali.jlsjyb.cn/Article/details/gtqolungym.html

[G14] 数据类 / record
来源：http://dali.pycfn.com/Article/details/gtzivtjqkc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.kuanghao11.cn/Article/details/gtoveehcqf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xuetiantiany.cn/Article/details/gtlxhmmran.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ivvv.top/Article/details/gtecrczmsn.html

TS:   type User = { name: string; age: number };
来源：http://dali.shuidangran.top/Article/details/gttnjbgwkb.html

Java: record User(String name, int age) {}
来源：http://dali.guannengcc.top/Article/details/gtivvqydmm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.redwolf501.top/Article/details/gtyqfpyzlo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ivvv.top/Article/details/gtsldonvdx.html


<!-- 参考信息 -->