代发 wailian999

PHP:  number_format(1234567);
来源：http://dali.jqgufenzy.top/Article/details/gtublyqabo.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jianghu66.top/Article/details/gthwdgkvkj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhiwuduotai.top/Article/details/gtrtotlvhl.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.nwbrower.top/Article/details/gtyokipijs.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.redwolf501.top/Article/details/gtpmjcmksx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.daria6918.cn/Article/details/gtibixnwvs.html

C#:   1234567.ToString("N0")
来源：http://dali.svipenyu.cn/Article/details/gtwapkejwy.html

[E17] 首字母大写
来源：http://dali.yuanzhike.top/Article/details/gtjaqkjzuh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.9152youxi.cn/Article/details/gthfaxzggn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.dashuyun.cn/Article/details/gtugorsxnp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daxiang520.top/Article/details/gtgvxbvazv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zycfv.cn/Article/details/gtvkhqjkfa.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.tianlin.xyz/Article/details/gtsbwmvpaf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.aizwys.cn/Article/details/gtuiipafid.html

Ruby: s.capitalize
来源：http://dali.nwbrower.top/Article/details/gtmpevpjir.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.redwolf501.top/Article/details/gtqafdvtqd.html

[E18] 模板占位符替换
来源：http://dali.feifeiyinyue.top/Article/details/gtnjwgdwrl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xziqi.cn/Article/details/gtzswasjug.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hysaishi.cn/Article/details/gtlhnwtpps.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cucudq.cn/Article/details/gtghnuojbh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gtikeibwho.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtexgpvdny.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yueranfly.top/Article/details/gtacpmocrn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jlsjyb.cn/Article/details/gtxwddkghi.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtyszmrrpl.html

[E19] 多行文本按行拆分
来源：http://dali.sxryk.cn/Article/details/gtfwhnmpiy.html

Py:   s.splitlines()
来源：http://dali.jinqigufen.top/Article/details/gtvdcrivnp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hysaishi.cn/Article/details/gtfghcmzbl.html

JS:   s.split(/\r?\n/)
来源：http://dali.jianghu66.top/Article/details/gtmogaqgzf.html

TS:   s.split(/\r?\n/)
来源：http://dali.hfpthk.cn/Article/details/gtguejobuv.html

Java: s.lines().toList()
来源：http://dali.dianchejie.cn/Article/details/gtbdbpghxv.html

Go:   strings.Split(s, "\n")
来源：http://dali.vqdsnc.cn/Article/details/gtzmcfjkza.html

Ruby: s.lines
来源：http://dali.sweek.top/Article/details/gtywkpfest.html

C#:   s.Split('\n')
来源：http://dali.shanyushiyangtech.top/Article/details/gtlggeeogk.html

[E20] 判断字符串是否为空
来源：http://dali.fzhhl.top/Article/details/gtjwjmmyhe.html

Py:   if not s:
来源：http://dali.nanxuanxn.top/Article/details/gtalzyvkru.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.redwolf501.top/Article/details/gtteogbhvr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hywenlv.cn/Article/details/gtmtgbmfwm.html

TS:   if (s === "") {}
来源：http://dali.bjfxy.top/Article/details/gtgkifktkk.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgcpvpixt.html

Go:   if s == "" {}
来源：http://dali.havefunace.top/Article/details/gtpoogmaxa.html

Ruby: if s.empty?
来源：http://dali.yuanzhike.top/Article/details/gtgvssiiyt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.guowangkeji.top/Article/details/gtrufuxrfm.html

[E21] 超长截断加省略号
来源：http://dali.pycfn.com/Article/details/gtcpcjxbzt.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shzxlz.cn/Article/details/gtnlwcxmtv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gtdyyvtbrk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtdcktqnot.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtogjqnjsi.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtltqxeqpf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hfpthk.cn/Article/details/gteesgyntu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtdhmyfjho.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.havefunace.top/Article/details/gtvlfpwzcr.html

[E22] 字节长度与字符长度
来源：http://dali.guowangkeji.top/Article/details/gtcwcpldni.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sysykeji.top/Article/details/gtdnumnbka.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yongpay.top/Article/details/gtqgeqqxyy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xziqi.cn/Article/details/gtwiycmozh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gthmbfypju.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.aibaodan.cn/Article/details/gttjizdybr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhongyouzk.top/Article/details/gtfdorprzq.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfswisfcu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hongshengwenyu.top/Article/details/gtibhovhbp.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtaasyvknn.html

F. 文件与目录
来源：http://dali.chenlongwang.top/Article/details/gtffopytad.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtxspwwpnp.html

[F01] 读取整个文件
来源：http://dali.jqgfzy.top/Article/details/gtfmbkxnwd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tian-w.cn/Article/details/gtngymmikh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gttvoiahku.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinqigufen.top/Article/details/gtoadryfov.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gtsabfvplz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gtwbhonsqz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xinyue.icu/Article/details/gtchveqcmg.html

Ruby: File.read("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtgqejlxdd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtdblunprt.html

[F02] 逐行读取文件
来源：http://dali.pengpengdd.cyou/Article/details/gtfojmiiks.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzmhuuieq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xziqi.cn/Article/details/gthwnywlum.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.iojbl.cn/Article/details/gthlgddkfc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnqzz.top/Article/details/gthddsobzw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hfpthk.cn/Article/details/gtrbpevmor.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yueranfly.top/Article/details/gtecxbsnws.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gogol.net.cn/Article/details/gttcuavxnh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinqigufen.top/Article/details/gtfvsbqpyh.html

[F03] 写入文件（覆盖）
来源：http://dali.yongpay.top/Article/details/gtksvzgnip.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jlsjyb.cn/Article/details/gtioqhhxct.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gttdspcjoy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aizwys.cn/Article/details/gtsvoedsoz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gtefwoqiep.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zycfv.cn/Article/details/gtrixgyiuy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.fengsongda.top/Article/details/gtygamjlfd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jlsjyb.cn/Article/details/gthbwbszhb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xylfe.cn/Article/details/gtaqxexnmc.html

[F04] 追加写入文件
来源：http://dali.yueranfly.top/Article/details/gtrslqhfzu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yuanzhike.top/Article/details/gtkvqqpima.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yuxming.cn/Article/details/gtcwxdeiyo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.bjfxy.top/Article/details/gtnrfidhap.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.c1oappe.top/Article/details/gtokdjukie.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hfpthk.cn/Article/details/gtivmcbyyg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jyoumei.cn/Article/details/gthioyszcy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yuanzhike.top/Article/details/gtnqhmrast.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ydzc1.top/Article/details/gthwuqxiss.html

[F05] 判断文件或目录是否存在
来源：http://dali.bjfxy.top/Article/details/gtcszbgnrk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.daxiang520.top/Article/details/gtdgswljlj.html

PHP:  file_exists("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtbezisjdj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gttdsyfziy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtiumovmon.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gtyazjygmb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.daria6918.cn/Article/details/gtvsnqxwjb.html

Ruby: File.exist?("a.txt")
来源：http://dali.316326.xyz/Article/details/gtommmnprr.html

C#:   File.Exists("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtzbsotyro.html

[F06] 删除文件
来源：http://dali.yj20258888.top/Article/details/gtzzdgbztf.html

Py:   os.remove("a.txt")
来源：http://dali.sweek.top/Article/details/gtgoykvaha.html

PHP:  unlink("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtfwngpmbj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtofmqoitx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtawnigudc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gtjmjffxdq.html

Go:   os.Remove("a.txt")
来源：http://dali.yj202588.top/Article/details/gtlddtmbhr.html

Ruby: File.delete("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtettleuor.html

C#:   File.Delete("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtdpcdgzuf.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gtfnbkqqyy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hnxiangtu.top/Article/details/gtqfxmhaeg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj20258.top/Article/details/gtkmftciwa.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuxming.cn/Article/details/gtydksjisa.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gtbesohdly.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.dashuyun.cn/Article/details/gtdamdfgiw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.9152youxi.cn/Article/details/gtubudcxzd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yvedp.cn/Article/details/gtwgsleapb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.birdmap.top/Article/details/gteubflzfx.html

[F08] 遍历目录
来源：http://dali.tianlin.xyz/Article/details/gtlvspurdm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenlongwang.top/Article/details/gteoclukzu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cdnleiting.top/Article/details/gtfambsagj.html

JS:   fs.readdirSync("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtdrxlycqd.html

TS:   fs.readdirSync("dir")
来源：http://dali.zdqjudy.top/Article/details/gtgcklvysx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj202588.top/Article/details/gthikaalce.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gotoacloud.top/Article/details/gtaszpdwwx.html

Ruby: Dir.children("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkhthxvts.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gotoacloud.top/Article/details/gtwclownid.html

[F09] 获取文件大小
来源：http://dali.snrcjt.cn/Article/details/gtjyoipfza.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtfzrurjcj.html

PHP:  filesize("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtyrtkmmaq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hywenlv.cn/Article/details/gtezdyfqmf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbzujcsmc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtjhrcxrop.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xuetiantiany.cn/Article/details/gtsfrxuqoh.html

Ruby: File.size("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtghnizoeh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yanxiufei.cn/Article/details/gtbefveqzh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpowztsvt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtlolpvqco.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yueranfly.top/Article/details/gtnlvzqieq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtfuwggxlg.html

TS:   path.extname("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtdoakuofx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shanyushiyangtech.top/Article/details/gtlxzscmrc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gttwbofpgj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtyoiqnfbp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gtqkvmmjph.html

[F11] 复制与移动文件
来源：http://dali.tianlin.xyz/Article/details/gtfrnkllzt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtxfchlpkm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ppjwa.cn/Article/details/gtfglxqsgb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gtipbpfjgr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gtyggipcbq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gteuybkoad.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hfpthk.cn/Article/details/gtazggvwpb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtkkeajapr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.meibo888.top/Article/details/gtdfazcblh.html

[F12] CSV 读写
来源：http://dali.zhiwuduotai.top/Article/details/gtvqgrnldt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cqqwz.cn/Article/details/gtupscziho.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinghuilouyu.cn/Article/details/gtunpsavil.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.feifeiyinyue.top/Article/details/gtkyodejle.html

TS:   // 同上
来源：http://dali.gzhubu.top/Article/details/gtghoimaoe.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nanxuanxn.top/Article/details/gtqwerzwzf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.mhx1999.top/Article/details/gthvofrqho.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yangfankeji.com/Article/details/gtnggjwkpl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sweek.top/Article/details/gtevoczcfo.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtygsqrzrr.html

G. 面向对象
来源：http://dali.nanxuanxn.top/Article/details/gtygurmgym.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtvnhnyval.html

[G01] 定义类
来源：http://dali.cashguo.top/Article/details/gtwpnunsrv.html

Py:   class User: pass
来源：http://dali.hnxiangtu.top/Article/details/gtgcgdrsdv.html

PHP:  class User {}
来源：http://dali.gaohongyu789.top/Article/details/gtgzumjyyn.html

JS:   class User {}
来源：http://dali.daxiang520.top/Article/details/gtzhakeswn.html

TS:   class User { name: string = ""; }
来源：http://dali.gaohongyu789.top/Article/details/gtvabnvcph.html

Java: class User {}
来源：http://dali.andypj.xyz/Article/details/gtoancscsc.html

Go:   type User struct { Name string }
来源：http://dali.zhiwuduotai.top/Article/details/gtakzpoqsn.html

Ruby: class User; end
来源：http://dali.cqqwz.cn/Article/details/gtrmysdnan.html

C#:   class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqygpyjll.html

[G02] 构造函数
来源：http://dali.hnqzz.top/Article/details/gtnokverwn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.guannengcc.top/Article/details/gtbeqibzam.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.0kj1m.cn/Article/details/gtkyfqdbpj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhixingplan.top/Article/details/gtoiqucoqb.html

TS:   constructor(public name: string) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlfeulyxn.html

Java: User(String name) { this.name = name; }
来源：http://dali.andypj.xyz/Article/details/gtxkurlcev.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gogol.net.cn/Article/details/gtdgdxlhfw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.pycfn.com/Article/details/gtpdjexjrb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cheryme.top/Article/details/gtaycfplwx.html

[G03] 实例属性
来源：http://dali.ybcxt.top/Article/details/gtafylepjo.html

Py:   self.name = "x"
来源：http://dali.c1oappe.top/Article/details/gtznnqwpnz.html

PHP:  public string $name = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gtpswryuvk.html

JS:   this.name = "x";
来源：http://dali.hysaishi.cn/Article/details/gtpzpytice.html

TS:   name: string = "x";
来源：http://dali.dianchejie.cn/Article/details/gtnxiegcsc.html

Java: private String name;
来源：http://dali.jinqigufen.top/Article/details/gtenwlqaju.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.feifeiyinyue.top/Article/details/gttbvaqitx.html

Ruby: @name = "x"
来源：http://dali.smart0.xyz/Article/details/gtdqrbchhd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gtjsmftrac.html

[G04] 定义方法
来源：http://dali.yanxiufei.cn/Article/details/gtkrfgajjh.html

Py:   def greet(self): return self.name
来源：http://dali.jyoumei.cn/Article/details/gtcrlbfabw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gtxrmqvxcv.html

JS:   greet() { return this.name; }
来源：http://dali.tanke756.top/Article/details/gtqwhxcmtu.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gtlckybahi.html

Java: String greet() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttndkyyow.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gtsdawvhis.html

Ruby: def greet; @name; end
来源：http://dali.xuanzx.com/Article/details/gtsjitihsx.html

C#:   public string Greet() => Name;
来源：http://dali.nwbrower.top/Article/details/gtzwazllvh.html

[G05] 继承
来源：http://dali.yj202588.top/Article/details/gtznftugrg.html

Py:   class Admin(User): pass
来源：http://dali.chenlongwang.top/Article/details/gtcpmelqmq.html

PHP:  class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gtofmtsqft.html

JS:   class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtsnshfbjk.html

TS:   class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtsasgcvjy.html

Java: class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtaheirjhv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cdnleiting.top/Article/details/gtvkethaag.html

Ruby: class Admin < User; end
来源：http://dali.hongshengwenyu.top/Article/details/gtzemlqziv.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gtxefwziko.html

[G06] 重写方法
来源：http://dali.cqqwz.cn/Article/details/gtkwghwgxo.html

Py:   def greet(self): return "admin"
来源：http://dali.guowangkeji.top/Article/details/gthpezntie.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gtfvwghedd.html

JS:   greet() { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gtxlajltzd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmdkciqhl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gtppcjtzwx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xinyue.icu/Article/details/gtblklkxre.html

Ruby: def greet; "admin"; end
来源：http://dali.ppjwa.cn/Article/details/gtumbxmzbr.html

C#:   public override string Greet() => "admin";
来源：http://dali.fengsongda.top/Article/details/gtmrsixvun.html

[G07] 调用父类方法
来源：http://dali.snrcjt.cn/Article/details/gtzjelmeqh.html

Py:   super().greet()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbjhfirlc.html

PHP:  parent::greet();
来源：http://dali.hysaishi.cn/Article/details/gtwlxmyszc.html

JS:   super.greet();
来源：http://dali.redwolf501.top/Article/details/gtiqgnvuwr.html

TS:   super.greet();
来源：http://dali.birdmap.top/Article/details/gticbfdcwx.html

Java: super.greet();
来源：http://dali.svipenyu.cn/Article/details/gtywueosat.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.meibo888.top/Article/details/gtjlobqrcf.html

Ruby: super
来源：http://dali.iojbl.cn/Article/details/gtyvtpmasz.html

C#:   base.Greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgwmnplzw.html

[G08] 静态方法与属性
来源：http://dali.316326.xyz/Article/details/gtimzrvoju.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xylfe.cn/Article/details/gtfnfcyjal.html

PHP:  public static function f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmonzfyxn.html

JS:   static f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtnnbwkzei.html

TS:   static f(): void {}
来源：http://dali.fzhhl.top/Article/details/gtaxlawnlk.html

Java: static void f() {}
来源：http://dali.daxiang520.top/Article/details/gtoovfhund.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hnqzz.top/Article/details/gtpwnlkuip.html

Ruby: def self.f; end
来源：http://dali.jinqigufen.top/Article/details/gtgvyblyga.html

C#:   public static void F() {}
来源：http://dali.sweek.top/Article/details/gtcwjxguup.html

[G09] 接口 / 抽象类
来源：http://dali.zhaomingkeji.xyz/Article/details/gtldancpro.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.feifeiyinyue.top/Article/details/gtkecnleba.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guannengcc.top/Article/details/gtngtlukbn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yanxiufei.cn/Article/details/gtjsyebmjb.html

TS:   interface Shape { area(): number; }
来源：http://dali.zycfv.cn/Article/details/gtkfdxlufv.html

Java: interface Shape { double area(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtefoejglt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nanxuanxn.top/Article/details/gtrjyrdiil.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhongyouzk.top/Article/details/gtxxxlqetf.html

C#:   interface IShape { double Area(); }
来源：http://dali.jlsjyb.cn/Article/details/gttzuuzbem.html

[G10] 访问控制
来源：http://dali.havefunace.top/Article/details/gtucabejfc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.bjfxy.top/Article/details/gtpqfzeths.html

PHP:  public / protected / private
来源：http://dali.shzxlz.cn/Article/details/gtuaekjcqd.html

JS:   #private 字段；其余公开
来源：http://dali.vqdsnc.cn/Article/details/gtmkdhisam.html

TS:   public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gtitwnsttv.html

Java: public / protected / private / 默认包级
来源：http://dali.hnxiangtu.top/Article/details/gtkkxqxbyb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.iojbl.cn/Article/details/gtiqglbjgr.html

Ruby: public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gtvupsfzub.html

C#:   public / protected / private / internal
来源：http://dali.kuanghao11.cn/Article/details/gtmkrqixcp.html

[G11] getter / setter
来源：http://dali.9152youxi.cn/Article/details/gtexjtgwcx.html

Py:   @property 与 @x.setter
来源：http://dali.xylfe.cn/Article/details/gthejorymn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gtlunwchbq.html

JS:   get name() { return this._name; }
来源：http://dali.ivvv.top/Article/details/gthcjopkfx.html

TS:   get name(): string { return this._name; }
来源：http://dali.kuanghao11.cn/Article/details/gtmpshriaz.html

Java: public String getName() { return name; }
来源：http://dali.havefunace.top/Article/details/gtyjzopuss.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gtkyalibnf.html

Ruby: attr_accessor :name
来源：http://dali.shuidangran.top/Article/details/gtyczymhxt.html

C#:   public string Name { get; set; }
来源：http://dali.xziqi.cn/Article/details/gtlhdqwrsx.html

[G12] 对象转字符串
来源：http://dali.shzxlz.cn/Article/details/gtrwqwubws.html

Py:   def __str__(self): return self.name
来源：http://dali.gotoacloud.top/Article/details/gtpnjbnpui.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gtinikfyli.html

JS:   toString() { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gtcooosmcg.html

TS:   toString(): string { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gtasukdkep.html

Java: @Override public String toString() { return name; }
来源：http://dali.cheryme.top/Article/details/gtjusqnljc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gtgoytdctw.html

Ruby: def to_s; @name; end
来源：http://dali.yonumen.top/Article/details/gtoecyumxc.html

C#:   public override string ToString() => Name;
来源：http://dali.aizwys.cn/Article/details/gtyfvfyspy.html

[G13] 判断对象类型
来源：http://dali.ydzc1.top/Article/details/gtqpuwfhwt.html

Py:   isinstance(u, User)
来源：http://dali.hnqzz.top/Article/details/gtwbrtvfxa.html

PHP:  $u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gtbnfljvty.html

JS:   u instanceof User
来源：http://dali.sxryk.cn/Article/details/gtjfqkgwws.html

TS:   u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtqqcngkcb.html

Java: u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gtwsaskcaa.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.dashuyun.cn/Article/details/gtjbinyznc.html

Ruby: u.is_a?(User)
来源：http://dali.chenzaomai.com/Article/details/gtacixofpt.html

C#:   u is User
来源：http://dali.pycfn.com/Article/details/gtgemnmwkt.html

[G14] 数据类 / record
来源：http://dali.ydzc1.top/Article/details/gtflqvazsi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yvedp.cn/Article/details/gtrakskaxz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ehwqpu.com/Article/details/gtutkyahzs.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.bjfxy.top/Article/details/gticcrhfdi.html

TS:   type User = { name: string; age: number };
来源：http://dali.fzhhl.top/Article/details/gtgrwqfgkg.html

Java: record User(String name, int age) {}
来源：http://dali.shuidangran.top/Article/details/gtzgjpytzd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ehwqpu.com/Article/details/gtcwdvwdqa.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.nanxinkj.top/Article/details/gtctkfjung.html


<!-- 参考信息 -->