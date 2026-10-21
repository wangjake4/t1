代发 wailian999

PHP:  number_format(1234567);
来源：http://dali.svipenyu.cn/Article/details/gtixpizbws.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yvedp.cn/Article/details/gtebchkyqk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cdnleiting.top/Article/details/gtwwvhtips.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jqgufenzy.top/Article/details/gtwhmrfpvj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sysykeji.top/Article/details/gtxovbhjln.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gtikznjake.html

C#:   1234567.ToString("N0")
来源：http://dali.pengpengdd.cyou/Article/details/gtypfkwhhq.html

[E17] 首字母大写
来源：http://dali.shuidangran.top/Article/details/gtqivpsvre.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hammf.cn/Article/details/gtagxgkxts.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jyoumei.cn/Article/details/gtrfemgylb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.havefunace.top/Article/details/gtfvmzrifl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gotoacloud.top/Article/details/gtuazzplic.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yueranfly.top/Article/details/gtamylnazu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tanke756.top/Article/details/gtlzpbnlcd.html

Ruby: s.capitalize
来源：http://dali.jyoumei.cn/Article/details/gtkjmxbwem.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yueranfly.top/Article/details/gtjfaovuzf.html

[E18] 模板占位符替换
来源：http://dali.snrcjt.cn/Article/details/gtrrreghnu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yanxiufei.cn/Article/details/gtitpjayyu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.guowangkeji.top/Article/details/gtfszsdaai.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gtqszqkhvw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gtrrpeeelr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hnqzz.top/Article/details/gtraujgbjw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gtnpsmtihs.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhongyouzk.top/Article/details/gtstpqushd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yangfankeji.com/Article/details/gtcdbuvpbc.html

[E19] 多行文本按行拆分
来源：http://dali.c1oappe.top/Article/details/gtlkrgqhhd.html

Py:   s.splitlines()
来源：http://dali.vqdsnc.cn/Article/details/gtgxvonxbn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.guowangkeji.top/Article/details/gtbuccbagf.html

JS:   s.split(/\r?\n/)
来源：http://dali.c1oappe.top/Article/details/gtrvnazjjh.html

TS:   s.split(/\r?\n/)
来源：http://dali.nanxuanxn.top/Article/details/gtrgltriju.html

Java: s.lines().toList()
来源：http://dali.yonumen.top/Article/details/gtgsgtvffd.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj202588.top/Article/details/gtyelzcikp.html

Ruby: s.lines
来源：http://dali.yuxming.cn/Article/details/gthiqodhdx.html

C#:   s.Split('\n')
来源：http://dali.zhixingplan.top/Article/details/gtvrvrubhl.html

[E20] 判断字符串是否为空
来源：http://dali.jinghuilouyu.cn/Article/details/gtjbiqapoo.html

Py:   if not s:
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrnthiugk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ydzc1.top/Article/details/gtpwxlnfnk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhiwuduotai.top/Article/details/gteuisqukl.html

TS:   if (s === "") {}
来源：http://dali.nwbrower.top/Article/details/gtexrtglmr.html

Java: if (s.isEmpty()) {}
来源：http://dali.yonumen.top/Article/details/gtcbiapsae.html

Go:   if s == "" {}
来源：http://dali.ybcxt.top/Article/details/gtuztxkrlv.html

Ruby: if s.empty?
来源：http://dali.tianlin.xyz/Article/details/gtndmwsezk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.havefunace.top/Article/details/gtyhewvuoq.html

[E21] 超长截断加省略号
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwlgzpig.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jqgufenzy.top/Article/details/gtdfscgxns.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gtsflbiqwi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtduxuaztc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gtcjjxhjdy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.redwolf501.top/Article/details/gtnvwuxuzx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinghuilouyu.cn/Article/details/gtwnjwjlgg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ydzc1.top/Article/details/gtlbyixrig.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtdldpmpur.html

[E22] 字节长度与字符长度
来源：http://dali.ybcxt.top/Article/details/gtnerwrbqb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.c1oappe.top/Article/details/gthpycqkan.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gtxpcpbltl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenzaomai.com/Article/details/gtbjzjtisd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gtmlfgmdjr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ydzc1.top/Article/details/gtxsjxrvhq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gotoacloud.top/Article/details/gtvcgbynkb.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gtrablmbvk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.pycfn.com/Article/details/gtnzlennsn.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtvrcvqbmw.html

F. 文件与目录
来源：http://dali.mhx1999.top/Article/details/gtdzeeffwv.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtrwswhzry.html

[F01] 读取整个文件
来源：http://dali.gogol.net.cn/Article/details/gtqyssqxjk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.dianchejie.cn/Article/details/gtasnfgiml.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtlscyegda.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xuanzx.com/Article/details/gtubazzkps.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttfztlksu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gtnuxumxta.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ydzc1.top/Article/details/gtxiidotnz.html

Ruby: File.read("a.txt")
来源：http://dali.ivvv.top/Article/details/gtbdthlxad.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xinyue.icu/Article/details/gttzfrfmrc.html

[F02] 逐行读取文件
来源：http://dali.xuanzx.com/Article/details/gtqdpmwqys.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yongpay.top/Article/details/gtxgmbjjue.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtddtdlbzu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.quarkkingdee.top/Article/details/gteuccspxu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.mhx1999.top/Article/details/gtbcvokcze.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj202588.top/Article/details/gtwglbipqa.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinqigfzy.top/Article/details/gtlgciikcg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yonumen.top/Article/details/gtavtzapgf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yongpay.top/Article/details/gtuqeefmyt.html

[F03] 写入文件（覆盖）
来源：http://dali.aibaodan.cn/Article/details/gtfiudwdun.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cucudq.cn/Article/details/gtgssdkuvq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tanke756.top/Article/details/gtrjmvgkcc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yonumen.top/Article/details/gtrwcscsrh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yongpay.top/Article/details/gtyebsqega.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jlsjyb.cn/Article/details/gtjahkxjzk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ivvv.top/Article/details/gtrsiehrpc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.316326.xyz/Article/details/gtfwcmcfez.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yongpay.top/Article/details/gtisuqijjt.html

[F04] 追加写入文件
来源：http://dali.yj20258.top/Article/details/gtmwtkdcdh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yj202588.top/Article/details/gtmvjufeuy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.daria6918.cn/Article/details/gtaseorjgz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jyoumei.cn/Article/details/gtlehpjsef.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtdatezyzg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ivvv.top/Article/details/gtdqktgjot.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xylfe.cn/Article/details/gtqljnbsfj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenzaomai.com/Article/details/gtckfbsklj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xylfe.cn/Article/details/gtljbqlhue.html

[F05] 判断文件或目录是否存在
来源：http://dali.jqgfzy.top/Article/details/gtuwcdhxeu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hfpthk.cn/Article/details/gtuhfimonn.html

PHP:  file_exists("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtzsewfgmf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtdhpylsul.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtcmkvntsi.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gtdctwkylu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.birdmap.top/Article/details/gtdvcbaopa.html

Ruby: File.exist?("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpxcszdnr.html

C#:   File.Exists("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtzqlvdxpq.html

[F06] 删除文件
来源：http://dali.yueranfly.top/Article/details/gtjolxrytu.html

Py:   os.remove("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtlodjfgoe.html

PHP:  unlink("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtkhipqers.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtgnhfecjr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtbxgmfvyi.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtwpyhlpiw.html

Go:   os.Remove("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtzuzclcte.html

Ruby: File.delete("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtvxsykbgc.html

C#:   File.Delete("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtpxyqjyqa.html

[F07] 创建目录（含多级）
来源：http://dali.cqqwz.cn/Article/details/gtsukhtmpt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hnqzz.top/Article/details/gtkhrqyxak.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xuanzx.com/Article/details/gtxarteupn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cashguo.top/Article/details/gtarohfoug.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnlrdaclb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.wangdashe.top/Article/details/gtpzlyftwq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yj202588.top/Article/details/gtdseasoqk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hammf.cn/Article/details/gtzubtjawu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gotoacloud.top/Article/details/gtjlvxddvc.html

[F08] 遍历目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyyokniwd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.redwolf501.top/Article/details/gtejjgashb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdxqkfmze.html

JS:   fs.readdirSync("dir")
来源：http://dali.aibaodan.cn/Article/details/gtwdydlojo.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgfzy.top/Article/details/gtepcxtspe.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.aibaodan.cn/Article/details/gtbfprjlnq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinqigufen.top/Article/details/gtuhawuzdk.html

Ruby: Dir.children("dir")
来源：http://dali.jyoumei.cn/Article/details/gtyqwrgplw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.dianchejie.cn/Article/details/gtktfnxzzk.html

[F09] 获取文件大小
来源：http://dali.zdqjudy.top/Article/details/gtkqgkcdvx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtzbkdbaxa.html

PHP:  filesize("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtdgbntxcf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.wangshuangyany.cn/Article/details/gtojlgjunl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.kuanghao11.cn/Article/details/gtqtkaovea.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gtnunlwjbc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.smart0.xyz/Article/details/gtqzgvaywf.html

Ruby: File.size("a.txt")
来源：http://dali.meibo888.top/Article/details/gtucekgfxl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.iojbl.cn/Article/details/gtysqiydzk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj202588.top/Article/details/gtjedjojxd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtmbzsyvrl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtbmwoonib.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtkobqyynu.html

TS:   path.extname("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtpzcixtil.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nwbrower.top/Article/details/gthtnrqbxu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtbosvpskz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtxbznypnw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtqtqpazre.html

[F11] 复制与移动文件
来源：http://dali.gotoacloud.top/Article/details/gtcqyyakst.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gtjlfubkus.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cheryme.top/Article/details/gtcsmhabld.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtcvdwpeth.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtxwijydrd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gtjrsfxxcb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.redwolf501.top/Article/details/gtiycqwtbv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtsqnjiaxu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhengqikj.top/Article/details/gtkevpehjc.html

[F12] CSV 读写
来源：http://dali.gogol.net.cn/Article/details/gtkwgwuibr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sweek.top/Article/details/gtiatjkmqb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nanxinkj.top/Article/details/gtohzfuzwo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhongyouzk.top/Article/details/gtyvxlsipj.html

TS:   // 同上
来源：http://dali.zhixingplan.top/Article/details/gtxbjxdqvt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jqgufenzy.top/Article/details/gtznjadxyy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.vqdsnc.cn/Article/details/gtaqbiullb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinqigfzy.top/Article/details/gtkulxlffl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sufxvd.cn/Article/details/gtgfqjpxwa.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtpjadqnra.html

G. 面向对象
来源：http://dali.hongshengwenyu.top/Article/details/gtegikdjyx.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtsigywcsk.html

[G01] 定义类
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrbbjewlz.html

Py:   class User: pass
来源：http://dali.yueranfly.top/Article/details/gthuviause.html

PHP:  class User {}
来源：http://dali.0kj1m.cn/Article/details/gtqtxxkkhu.html

JS:   class User {}
来源：http://dali.zdqjudy.top/Article/details/gtloghehdc.html

TS:   class User { name: string = ""; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiscsjunw.html

Java: class User {}
来源：http://dali.hysaishi.cn/Article/details/gtxpwwaxty.html

Go:   type User struct { Name string }
来源：http://dali.chenlongwang.top/Article/details/gtqgwwwsfi.html

Ruby: class User; end
来源：http://dali.jyoumei.cn/Article/details/gtbvkmddly.html

C#:   class User {}
来源：http://dali.bjfxy.top/Article/details/gtilukvptt.html

[G02] 构造函数
来源：http://dali.0kj1m.cn/Article/details/gteiiqflgm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj202588.top/Article/details/gtwwviuely.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xuetiantiany.cn/Article/details/gthwkaovow.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhixingplan.top/Article/details/gtwozpeggj.html

TS:   constructor(public name: string) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gthzgftvll.html

Java: User(String name) { this.name = name; }
来源：http://dali.shuidangran.top/Article/details/gtpsvdiojs.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xinyue.icu/Article/details/gtesisqqku.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hywenlv.cn/Article/details/gtryfaajra.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xylfe.cn/Article/details/gtefacmnqw.html

[G03] 实例属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gtobtfcgqu.html

Py:   self.name = "x"
来源：http://dali.yj20258888.top/Article/details/gtfvpxdsfp.html

PHP:  public string $name = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuntddxhl.html

JS:   this.name = "x";
来源：http://dali.jinqigufen.top/Article/details/gtmoqvayjs.html

TS:   name: string = "x";
来源：http://dali.yuanzhike.top/Article/details/gtistwymsn.html

Java: private String name;
来源：http://dali.jyoumei.cn/Article/details/gtvlvpggmh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yuanzhike.top/Article/details/gtomcxyjqe.html

Ruby: @name = "x"
来源：http://dali.daxiang520.top/Article/details/gtqdcxtabn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cucudq.cn/Article/details/gtguvchxcn.html

[G04] 定义方法
来源：http://dali.tian-w.cn/Article/details/gtddnlrwxj.html

Py:   def greet(self): return self.name
来源：http://dali.tanke756.top/Article/details/gtzlbegxfi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gtiizbpije.html

JS:   greet() { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gtrefkcpvv.html

TS:   greet(): string { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgcdnxyxi.html

Java: String greet() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gteloywtxu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gttwdlbivc.html

Ruby: def greet; @name; end
来源：http://dali.kuanghao11.cn/Article/details/gtohhxaoau.html

C#:   public string Greet() => Name;
来源：http://dali.hfpthk.cn/Article/details/gtqngqhtar.html

[G05] 继承
来源：http://dali.xinyue.icu/Article/details/gtfeytnwtj.html

Py:   class Admin(User): pass
来源：http://dali.meibo888.top/Article/details/gttdbxnrwp.html

PHP:  class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtvpxltpmr.html

JS:   class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtctizolld.html

TS:   class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtoruoherk.html

Java: class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtpdzniuar.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinqigfzy.top/Article/details/gtilpnrszv.html

Ruby: class Admin < User; end
来源：http://dali.tanke756.top/Article/details/gteujecqsx.html

C#:   class Admin : User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtjdzdmgeb.html

[G06] 重写方法
来源：http://dali.hfpthk.cn/Article/details/gtxqnubtdt.html

Py:   def greet(self): return "admin"
来源：http://dali.nanxuanxn.top/Article/details/gtgkdgcvkw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gtunjpmqzy.html

JS:   greet() { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gtpgkbgshc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gtiryjeoaj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gtwlgyqyed.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.vqdsnc.cn/Article/details/gtvpbsqkam.html

Ruby: def greet; "admin"; end
来源：http://dali.sysykeji.top/Article/details/gtvjjijegp.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinyuanbaomall.cn/Article/details/gttcyorxfp.html

[G07] 调用父类方法
来源：http://dali.iojbl.cn/Article/details/gtsvkvvfhe.html

Py:   super().greet()
来源：http://dali.shuidangran.top/Article/details/gtjhjlgjeo.html

PHP:  parent::greet();
来源：http://dali.nanxinkj.top/Article/details/gtgifoekpn.html

JS:   super.greet();
来源：http://dali.mhx1999.top/Article/details/gtfdnlmlcq.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gtibfnhuzl.html

Java: super.greet();
来源：http://dali.redwolf501.top/Article/details/gtnyuexchd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.pycfn.com/Article/details/gtggnubozq.html

Ruby: super
来源：http://dali.xuanzx.com/Article/details/gtvanwvnxc.html

C#:   base.Greet();
来源：http://dali.gotoacloud.top/Article/details/gtdokktjnm.html

[G08] 静态方法与属性
来源：http://dali.guannengcc.top/Article/details/gtpchdijpc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cheryme.top/Article/details/gtussvnvbr.html

PHP:  public static function f() {}
来源：http://dali.cucudq.cn/Article/details/gtirjsqwcs.html

JS:   static f() {}
来源：http://dali.gotoacloud.top/Article/details/gtdozgtpzp.html

TS:   static f(): void {}
来源：http://dali.feifeiyinyue.top/Article/details/gteeldzwru.html

Java: static void f() {}
来源：http://dali.ydzc1.top/Article/details/gtpawfgrwf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hongshengwenyu.top/Article/details/gtbhyhcqtv.html

Ruby: def self.f; end
来源：http://dali.yueranfly.top/Article/details/gtdwggvhqx.html

C#:   public static void F() {}
来源：http://dali.wangshuangyany.cn/Article/details/gtwihznytp.html

[G09] 接口 / 抽象类
来源：http://dali.9152youxi.cn/Article/details/gtmztncjkv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nwbrower.top/Article/details/gtiaxernim.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jiagoushi.top/Article/details/gtncbwrgfl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ivvv.top/Article/details/gtvjbxuvjb.html

TS:   interface Shape { area(): number; }
来源：http://dali.hnxiangtu.top/Article/details/gtrehcbehe.html

Java: interface Shape { double area(); }
来源：http://dali.yj202588.top/Article/details/gtpirfiwxh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nwbrower.top/Article/details/gtpwbencdj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cdnleiting.top/Article/details/gtcjwarpra.html

C#:   interface IShape { double Area(); }
来源：http://dali.hnqzz.top/Article/details/gtkalplnmu.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gtqvdyzcsr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xinyue.icu/Article/details/gtpgvurvrq.html

PHP:  public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gtyiofxlaf.html

JS:   #private 字段；其余公开
来源：http://dali.zdqjudy.top/Article/details/gtruirazdm.html

TS:   public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gtechapnwi.html

Java: public / protected / private / 默认包级
来源：http://dali.nanxinkj.top/Article/details/gtzvirgern.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.birdmap.top/Article/details/gtkfbatojo.html

Ruby: public / protected / private
来源：http://dali.gzhubu.top/Article/details/gtjdjkbsij.html

C#:   public / protected / private / internal
来源：http://dali.cashguo.top/Article/details/gtpybynafd.html

[G11] getter / setter
来源：http://dali.svipenyu.cn/Article/details/gtgyraixcy.html

Py:   @property 与 @x.setter
来源：http://dali.vqdsnc.cn/Article/details/gtosadoawa.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gtcvhjguin.html

JS:   get name() { return this._name; }
来源：http://dali.andypj.xyz/Article/details/gtogpinwsy.html

TS:   get name(): string { return this._name; }
来源：http://dali.9152youxi.cn/Article/details/gtaqfgqazf.html

Java: public String getName() { return name; }
来源：http://dali.mhx1999.top/Article/details/gtpjhkmsit.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gtdpcjitic.html

Ruby: attr_accessor :name
来源：http://dali.cheryme.top/Article/details/gtifewdecg.html

C#:   public string Name { get; set; }
来源：http://dali.hammf.cn/Article/details/gtinonjewf.html

[G12] 对象转字符串
来源：http://dali.yangfankeji.com/Article/details/gtprrtyerg.html

Py:   def __str__(self): return self.name
来源：http://dali.zycfv.cn/Article/details/gtxnuemvco.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.vqdsnc.cn/Article/details/gtkxjpeduq.html

JS:   toString() { return this.name; }
来源：http://dali.tanke756.top/Article/details/gtouusclek.html

TS:   toString(): string { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gtykojneou.html

Java: @Override public String toString() { return name; }
来源：http://dali.smart0.xyz/Article/details/gtcdgtntpo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gtsiuyjxgz.html

Ruby: def to_s; @name; end
来源：http://dali.nwbrower.top/Article/details/gthutfvijh.html

C#:   public override string ToString() => Name;
来源：http://dali.xylfe.cn/Article/details/gtpzikmeqh.html

[G13] 判断对象类型
来源：http://dali.svipenyu.cn/Article/details/gtpxbmecvb.html

Py:   isinstance(u, User)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsyngqnut.html

PHP:  $u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gtxdyvrgon.html

JS:   u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtlotdlguw.html

TS:   u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gtbahapbzt.html

Java: u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gttgoxcuyg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jqgfzy.top/Article/details/gtekyvgatl.html

Ruby: u.is_a?(User)
来源：http://dali.sxryk.cn/Article/details/gthbagtxwa.html

C#:   u is User
来源：http://dali.jyoumei.cn/Article/details/gtlwkujtiv.html

[G14] 数据类 / record
来源：http://dali.hammf.cn/Article/details/gtmqkjsumc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.bjfxy.top/Article/details/gtsqocoqye.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hywenlv.cn/Article/details/gtxfcpssnm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.pengpengdd.cyou/Article/details/gtbxnbjrmc.html

TS:   type User = { name: string; age: number };
来源：http://dali.havefunace.top/Article/details/gtnwqwttor.html

Java: record User(String name, int age) {}
来源：http://dali.hysaishi.cn/Article/details/gtmmkdtnho.html

Go:   type User struct { Name string; Age int }
来源：http://dali.iojbl.cn/Article/details/gtoewhhamk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yangfankeji.com/Article/details/gtnplmqgib.html


<!-- 参考信息 -->