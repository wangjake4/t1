代发 wailian999

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.quarkkingdee.top/Article/details/gtekfwolyq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtcootrmrl.html

[E16] 数字千分位
来源：http://dali.yvedp.cn/Article/details/gttubycxww.html

Py:   f"{1234567:,}"
来源：http://dali.cucudq.cn/Article/details/gtkyhqkgja.html

PHP:  number_format(1234567);
来源：http://dali.daria6918.cn/Article/details/gtrishwhzv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.0kj1m.cn/Article/details/gtwycldhnn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuanzhike.top/Article/details/gtnqxbsbty.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.bjfxy.top/Article/details/gtqkutxrip.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhoulong.xyz/Article/details/gtcwiwivvo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.nanxinkj.top/Article/details/gtwutabtpw.html

C#:   1234567.ToString("N0")
来源：http://dali.aizwys.cn/Article/details/gtkquowdrt.html

[E17] 首字母大写
来源：http://dali.dianchejie.cn/Article/details/gthwcxezdw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hywenlv.cn/Article/details/gtszdnhans.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shzxlz.cn/Article/details/gtifqgsbcr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigfzy.top/Article/details/gtyhenvifv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hywenlv.cn/Article/details/gtvjlxjtdm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cheryme.top/Article/details/gtmdqlbaux.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.daxiang520.top/Article/details/gtqeorhwkf.html

Ruby: s.capitalize
来源：http://dali.zhengqikj.top/Article/details/gtvvsunzmg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.fengsongda.top/Article/details/gtbhvbcfii.html

[E18] 模板占位符替换
来源：http://dali.aizwys.cn/Article/details/gtrqdcdihs.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gogol.net.cn/Article/details/gtesuxhttm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.nwbrower.top/Article/details/gtcgzoipup.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.meibo888.top/Article/details/gtesiwwgvg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ivvv.top/Article/details/gtoredhcrr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.fengsongda.top/Article/details/gtbnbzhlyr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.fengsongda.top/Article/details/gtycxlqirw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yueranfly.top/Article/details/gtqulxpjrh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsbckkfla.html

[E19] 多行文本按行拆分
来源：http://dali.cheryme.top/Article/details/gtagscnuix.html

Py:   s.splitlines()
来源：http://dali.aibaodan.cn/Article/details/gtgigrnmoo.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.nanxinkj.top/Article/details/gtmoattyuq.html

JS:   s.split(/\r?\n/)
来源：http://dali.yj20258.top/Article/details/gtqnlsahqd.html

TS:   s.split(/\r?\n/)
来源：http://dali.ppjwa.cn/Article/details/gtriskfsme.html

Java: s.lines().toList()
来源：http://dali.gotoacloud.top/Article/details/gtkzntthwj.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtcpfgrilr.html

Ruby: s.lines
来源：http://dali.zhoulong.xyz/Article/details/gtjbdwvpbx.html

C#:   s.Split('\n')
来源：http://dali.wangshuangyany.cn/Article/details/gtqcbokzks.html

[E20] 判断字符串是否为空
来源：http://dali.ehwqpu.com/Article/details/gthpygrrxc.html

Py:   if not s:
来源：http://dali.havefunace.top/Article/details/gtnwafhtqe.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.pengpengdd.cyou/Article/details/gtbwxaptso.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtmdjihahi.html

TS:   if (s === "") {}
来源：http://dali.meibo888.top/Article/details/gtkixtkufm.html

Java: if (s.isEmpty()) {}
来源：http://dali.wangdashe.top/Article/details/gticdfuktg.html

Go:   if s == "" {}
来源：http://dali.nwbrower.top/Article/details/gtlepzixrq.html

Ruby: if s.empty?
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbudcfijx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nwbrower.top/Article/details/gtgpokzwfi.html

[E21] 超长截断加省略号
来源：http://dali.xziqi.cn/Article/details/gtskzcpqiq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gotoacloud.top/Article/details/gtvjacqnka.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gtyvyzjcqp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtjgvhdwgt.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtkuttagdj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gtqkamqiku.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shanyushiyangtech.top/Article/details/gtqpzlfzuu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtgucoonep.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtuijwpzuf.html

[E22] 字节长度与字符长度
来源：http://dali.c1oappe.top/Article/details/gtjzxmbhnr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ybcxt.top/Article/details/gtefbxeizn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gtvqinwyfj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dianchejie.cn/Article/details/gtojldkijw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yangfankeji.com/Article/details/gtstxkwmvh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sxryk.cn/Article/details/gtzqeybrlh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hnxiangtu.top/Article/details/gtustwdawk.html

Ruby: s.bytesize;  s.length
来源：http://dali.chenlongwang.top/Article/details/gtliifhtnt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.wangshuangyany.cn/Article/details/gtveatubgo.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtsfjjfytl.html

F. 文件与目录
来源：http://dali.jianghu66.top/Article/details/gtpiapsllc.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtkepsajxu.html

[F01] 读取整个文件
来源：http://dali.daxiang520.top/Article/details/gtzkowknmj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cqqwz.cn/Article/details/gtchszlffn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtzhzmxbiy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jqgufenzy.top/Article/details/gtojhwgohn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtgwyituxy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gtmmmboraj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cashguo.top/Article/details/gtolicgqwn.html

Ruby: File.read("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtwraxvuay.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbnpqisje.html

[F02] 逐行读取文件
来源：http://dali.gaohongyu789.top/Article/details/gtgjsprfzn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.birdmap.top/Article/details/gtjwojqqrk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.smart0.xyz/Article/details/gtvwuxiwtg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sysykeji.top/Article/details/gtcrflteju.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.birdmap.top/Article/details/gtcwvzfsqq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sxryk.cn/Article/details/gtbbfrpodl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cashguo.top/Article/details/gtlfbahmgp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hywenlv.cn/Article/details/gtdjdcohuc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yonumen.top/Article/details/gtqvkhlkmw.html

[F03] 写入文件（覆盖）
来源：http://dali.yj20258.top/Article/details/gtmomubuig.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.dashuyun.cn/Article/details/gtsztqxrhm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nanxinkj.top/Article/details/gthrsjkdcg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cheryme.top/Article/details/gtmpaagtxs.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dianchejie.cn/Article/details/gtxopsuvjo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yuxming.cn/Article/details/gttsordmzb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhoulong.xyz/Article/details/gtqmuutfld.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.fengsongda.top/Article/details/gtfpemyaqc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.mhx1999.top/Article/details/gtirzzpfby.html

[F04] 追加写入文件
来源：http://dali.pycfn.com/Article/details/gtjytpgjcy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xylfe.cn/Article/details/gtjqfslqpl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjsfhgxfh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.iojbl.cn/Article/details/gtlzcjuvib.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtmwxblijb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gogol.net.cn/Article/details/gtnkdnggho.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yueranfly.top/Article/details/gtmxmnsrfb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.guannengcc.top/Article/details/gtoycbuiyj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.quarkkingdee.top/Article/details/gtgkznyntv.html

[F05] 判断文件或目录是否存在
来源：http://dali.haohaochexian.top/Article/details/gtfvortwuh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinqigfzy.top/Article/details/gtwfzrrpqv.html

PHP:  file_exists("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtezjeaeqb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtnaeaogaa.html

TS:   fs.existsSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtrdgobxsz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gtkbnuinwq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zdqjudy.top/Article/details/gtvadfybio.html

Ruby: File.exist?("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtbminnyht.html

C#:   File.Exists("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtgvcjnmkw.html

[F06] 删除文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlhcuzxvv.html

Py:   os.remove("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtstjnnkre.html

PHP:  unlink("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtmoopuwvy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtdxbovhsp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtoynjrxrj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gtyajjzdaz.html

Go:   os.Remove("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtptiqvefx.html

Ruby: File.delete("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrmkvacsm.html

C#:   File.Delete("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtsaoxutix.html

[F07] 创建目录（含多级）
来源：http://dali.havefunace.top/Article/details/gttpzscepw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.pengpengdd.cyou/Article/details/gtabxrpxut.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxytsasjw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangshuangyany.cn/Article/details/gthbunxqky.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.316326.xyz/Article/details/gtoqprnvsl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ydzc1.top/Article/details/gtxlfhgzlo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.nwbrower.top/Article/details/gtgyooxpob.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sufxvd.cn/Article/details/gtesnudqoe.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shanyushiyangtech.top/Article/details/gtgxgplldm.html

[F08] 遍历目录
来源：http://dali.cheryme.top/Article/details/gtpxdledwx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jyoumei.cn/Article/details/gtdtcrkyhk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.chenzaomai.com/Article/details/gtpsjctuwn.html

JS:   fs.readdirSync("dir")
来源：http://dali.daria6918.cn/Article/details/gtqighmalj.html

TS:   fs.readdirSync("dir")
来源：http://dali.hammf.cn/Article/details/gtidpwwfmh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yonumen.top/Article/details/gtesleopst.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sysykeji.top/Article/details/gtybtayttg.html

Ruby: Dir.children("dir")
来源：http://dali.jiagoushi.top/Article/details/gtlheobuiu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.svipenyu.cn/Article/details/gtnhohjlsi.html

[F09] 获取文件大小
来源：http://dali.xinyue.icu/Article/details/gtzscyvwvh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtmlfwmngs.html

PHP:  filesize("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtvnxdyniz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zycfv.cn/Article/details/gtmnlyajjy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jqgfzy.top/Article/details/gtvdvediee.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gttkwghbwg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhiwuduotai.top/Article/details/gtrcfvhmzb.html

Ruby: File.size("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtscstzriv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gotoacloud.top/Article/details/gtrlwsgxnr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nwbrower.top/Article/details/gtuipvikps.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtmqfvumbm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tanke756.top/Article/details/gtxbftqlua.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtnzfgikxl.html

TS:   path.extname("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtohuyeyow.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.dashuyun.cn/Article/details/gtjrxwzbsm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtjbpuqcic.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtqmfnmawv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtfbogjiwr.html

[F11] 复制与移动文件
来源：http://dali.cheryme.top/Article/details/gtlhuavqdv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtcgwjdpbl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtarhwbtiw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtuclphbif.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gthjmompwt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.dianchejie.cn/Article/details/gtyrbxfila.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hnxiangtu.top/Article/details/gtrlvatjkc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gtegfzzdvz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.9152youxi.cn/Article/details/gtelanricc.html

[F12] CSV 读写
来源：http://dali.zycfv.cn/Article/details/gtelmedkhy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jlsjyb.cn/Article/details/gtvgaroqwe.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nanxuanxn.top/Article/details/gtklfnkqhy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj20258888.top/Article/details/gtljqeldeb.html

TS:   // 同上
来源：http://dali.ppjwa.cn/Article/details/gtyisrxxfd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenzaomai.com/Article/details/gtmqphbtkb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tianlin.xyz/Article/details/gtmncfcxyc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cdnleiting.top/Article/details/gtpehlmxuj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sxryk.cn/Article/details/gtnlffizar.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtcfrnzbft.html

G. 面向对象
来源：http://dali.yongpay.top/Article/details/gtzmwjawdu.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtcbeesysv.html

[G01] 定义类
来源：http://dali.meibo888.top/Article/details/gtqyhnyjft.html

Py:   class User: pass
来源：http://dali.jqgfzy.top/Article/details/gtjdvkbokn.html

PHP:  class User {}
来源：http://dali.sysykeji.top/Article/details/gtidqadpvd.html

JS:   class User {}
来源：http://dali.jiagoushi.top/Article/details/gtbymruchh.html

TS:   class User { name: string = ""; }
来源：http://dali.zycfv.cn/Article/details/gtembosfjp.html

Java: class User {}
来源：http://dali.hammf.cn/Article/details/gtajcjhvji.html

Go:   type User struct { Name string }
来源：http://dali.shangyingyoupin.top/Article/details/gtdlijllkb.html

Ruby: class User; end
来源：http://dali.yanxiufei.cn/Article/details/gthdskujfx.html

C#:   class User {}
来源：http://dali.guowangkeji.top/Article/details/gtzjokvmxn.html

[G02] 构造函数
来源：http://dali.yj20258888.top/Article/details/gtlzvpmtrt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xuanzx.com/Article/details/gtzftfmkzs.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.daxiang520.top/Article/details/gtsdpktqwu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.0kj1m.cn/Article/details/gtjxnxwdpa.html

TS:   constructor(public name: string) {}
来源：http://dali.dashuyun.cn/Article/details/gtmrmdhzbp.html

Java: User(String name) { this.name = name; }
来源：http://dali.xziqi.cn/Article/details/gtvvmftmqs.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.andypj.xyz/Article/details/gtaipmoixq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.aibaodan.cn/Article/details/gtpbkenkng.html

C#:   public User(string name) { Name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gthhspueln.html

[G03] 实例属性
来源：http://dali.zycfv.cn/Article/details/gtqwvdanmy.html

Py:   self.name = "x"
来源：http://dali.xylfe.cn/Article/details/gtdsckrmeq.html

PHP:  public string $name = "x";
来源：http://dali.0kj1m.cn/Article/details/gtaixtpust.html

JS:   this.name = "x";
来源：http://dali.cucudq.cn/Article/details/gtncofpptp.html

TS:   name: string = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gtvgyjioon.html

Java: private String name;
来源：http://dali.cdnleiting.top/Article/details/gtmkdnzzjq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cheryme.top/Article/details/gtuvtruzec.html

Ruby: @name = "x"
来源：http://dali.jiagoushi.top/Article/details/gthkqegant.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sufxvd.cn/Article/details/gteogeyqft.html

[G04] 定义方法
来源：http://dali.zhongyouzk.top/Article/details/gtlwfbfkcd.html

Py:   def greet(self): return self.name
来源：http://dali.fengsongda.top/Article/details/gtdomxniya.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jianghu66.top/Article/details/gtmjowpwpj.html

JS:   greet() { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtwgfdturg.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmskkxlfe.html

Java: String greet() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtymenwppg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gtchvpxxrh.html

Ruby: def greet; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gttlszruyj.html

C#:   public string Greet() => Name;
来源：http://dali.hysaishi.cn/Article/details/gttucbhgup.html

[G05] 继承
来源：http://dali.dashuyun.cn/Article/details/gtorvpcqpp.html

Py:   class Admin(User): pass
来源：http://dali.tianlin.xyz/Article/details/gtxpqfgipg.html

PHP:  class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtbhhmugsl.html

JS:   class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtoitcrbpc.html

TS:   class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtgmzlcdzc.html

Java: class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtzbutzwsa.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ehwqpu.com/Article/details/gthlghqbla.html

Ruby: class Admin < User; end
来源：http://dali.gaohongyu789.top/Article/details/gtqshjfyfn.html

C#:   class Admin : User {}
来源：http://dali.mhx1999.top/Article/details/gtoyknchzf.html

[G06] 重写方法
来源：http://dali.zhoulong.xyz/Article/details/gtbqklhrez.html

Py:   def greet(self): return "admin"
来源：http://dali.chenzaomai.com/Article/details/gtispkqjqu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gttdhpfjty.html

JS:   greet() { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gthtvecxqx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gtzocgqyxb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwslgfwww.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gotoacloud.top/Article/details/gtsgyekzse.html

Ruby: def greet; "admin"; end
来源：http://dali.ehwqpu.com/Article/details/gtvflxdset.html

C#:   public override string Greet() => "admin";
来源：http://dali.hongshengwenyu.top/Article/details/gtomobhosv.html

[G07] 调用父类方法
来源：http://dali.nanxuanxn.top/Article/details/gtszrlmzky.html

Py:   super().greet()
来源：http://dali.ppjwa.cn/Article/details/gtvwwnoevk.html

PHP:  parent::greet();
来源：http://dali.sysykeji.top/Article/details/gtudyusvvj.html

JS:   super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtiaxnpvdu.html

TS:   super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtttnzyzhn.html

Java: super.greet();
来源：http://dali.shuidangran.top/Article/details/gtvookfzpk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ehwqpu.com/Article/details/gtyzhtnram.html

Ruby: super
来源：http://dali.iojbl.cn/Article/details/gtpdnxvoxc.html

C#:   base.Greet();
来源：http://dali.pycfn.com/Article/details/gtgvlabatg.html

[G08] 静态方法与属性
来源：http://dali.hammf.cn/Article/details/gtzwaryzot.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangdashe.top/Article/details/gtnmsnsrfo.html

PHP:  public static function f() {}
来源：http://dali.jyoumei.cn/Article/details/gtnnhwflou.html

JS:   static f() {}
来源：http://dali.ehwqpu.com/Article/details/gtzzcavlwh.html

TS:   static f(): void {}
来源：http://dali.nwbrower.top/Article/details/gtkzpkdsgr.html

Java: static void f() {}
来源：http://dali.hysaishi.cn/Article/details/gtzmuodxgr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.316326.xyz/Article/details/gtdlsgcygd.html

Ruby: def self.f; end
来源：http://dali.havefunace.top/Article/details/gtmnzokcoj.html

C#:   public static void F() {}
来源：http://dali.yj20258888.top/Article/details/gtcyaxzfkb.html

[G09] 接口 / 抽象类
来源：http://dali.yonumen.top/Article/details/gtfbnokngs.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jianghu66.top/Article/details/gtzolqdzhg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhongyouzk.top/Article/details/gtkcdzljly.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sweek.top/Article/details/gtqwplcjvj.html

TS:   interface Shape { area(): number; }
来源：http://dali.yangfankeji.com/Article/details/gtkxlnlalw.html

Java: interface Shape { double area(); }
来源：http://dali.0kj1m.cn/Article/details/gtwrhycozb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shzxlz.cn/Article/details/gtflnaidwb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tianlin.xyz/Article/details/gtqfxmxlvk.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhoulong.xyz/Article/details/gtodcojqyb.html

[G10] 访问控制
来源：http://dali.ybcxt.top/Article/details/gtbtdovuko.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.meibo888.top/Article/details/gtffbkbncg.html

PHP:  public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gtdtniyskx.html

JS:   #private 字段；其余公开
来源：http://dali.vqdsnc.cn/Article/details/gtwnypdupe.html

TS:   public / protected / private
来源：http://dali.pycfn.com/Article/details/gtexitpjmk.html

Java: public / protected / private / 默认包级
来源：http://dali.tanke756.top/Article/details/gtbxvcdoly.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.quarkkingdee.top/Article/details/gtbhabyoiw.html

Ruby: public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gtpevutrij.html

C#:   public / protected / private / internal
来源：http://dali.jianghu66.top/Article/details/gtposmxjsl.html

[G11] getter / setter
来源：http://dali.pycfn.com/Article/details/gtbljaeqpr.html

Py:   @property 与 @x.setter
来源：http://dali.cdnleiting.top/Article/details/gtbytfxzhr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtvioscisr.html

JS:   get name() { return this._name; }
来源：http://dali.tanke756.top/Article/details/gtrcniukto.html

TS:   get name(): string { return this._name; }
来源：http://dali.ydzc1.top/Article/details/gtaurrnmyl.html

Java: public String getName() { return name; }
来源：http://dali.yvedp.cn/Article/details/gtgsvgmzhx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gtqgdkubct.html

Ruby: attr_accessor :name
来源：http://dali.ppjwa.cn/Article/details/gtqyozxgxh.html

C#:   public string Name { get; set; }
来源：http://dali.zhoulong.xyz/Article/details/gtmqiyntpz.html

[G12] 对象转字符串
来源：http://dali.zycfv.cn/Article/details/gtzttgovba.html

Py:   def __str__(self): return self.name
来源：http://dali.xylfe.cn/Article/details/gtnilhwefw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gtvyywrnhq.html

JS:   toString() { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtevawxyel.html

TS:   toString(): string { return this.name; }
来源：http://dali.meibo888.top/Article/details/gtetiljfnh.html

Java: @Override public String toString() { return name; }
来源：http://dali.meibo888.top/Article/details/gtclhntatz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tanke756.top/Article/details/gtfvnivcdk.html

Ruby: def to_s; @name; end
来源：http://dali.xylfe.cn/Article/details/gtsljnfljh.html

C#:   public override string ToString() => Name;
来源：http://dali.fengsongda.top/Article/details/gtcrrudrgr.html

[G13] 判断对象类型
来源：http://dali.daxiang520.top/Article/details/gtaxiovhme.html

Py:   isinstance(u, User)
来源：http://dali.yanxiufei.cn/Article/details/gtoxbvbuey.html

PHP:  $u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtkcsjoygn.html

JS:   u instanceof User
来源：http://dali.havefunace.top/Article/details/gtfgrvblwe.html

TS:   u instanceof User
来源：http://dali.xylfe.cn/Article/details/gtdiwnremm.html

Java: u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gterunbgqc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.fzhhl.top/Article/details/gtaafygqzv.html

Ruby: u.is_a?(User)
来源：http://dali.316326.xyz/Article/details/gtlyehulhg.html

C#:   u is User
来源：http://dali.snrcjt.cn/Article/details/gtbundbsqh.html

[G14] 数据类 / record
来源：http://dali.hfpthk.cn/Article/details/gtavttzyjw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shuidangran.top/Article/details/gtqswxmgxt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.vqdsnc.cn/Article/details/gtbezthzor.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gaohongyu789.top/Article/details/gtqrxjbats.html


<!-- 参考信息 -->