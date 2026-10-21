代发 wailian999

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.chenzaomai.com/Article/details/gtuizcangu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhongyouzk.top/Article/details/gtodtisbpz.html

C#:   1234567.ToString("N0")
来源：http://dali.jinqigufen.top/Article/details/gtmliuwilu.html

[E17] 首字母大写
来源：http://dali.sxryk.cn/Article/details/gtynekouzp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shuidangran.top/Article/details/gtwvprvdll.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.kuanghao11.cn/Article/details/gthxtmtqhw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yonumen.top/Article/details/gtumopwcmb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shuidangran.top/Article/details/gtclozddjl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jqgufenzy.top/Article/details/gtymifxvgz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.havefunace.top/Article/details/gtchglvtxb.html

Ruby: s.capitalize
来源：http://dali.iojbl.cn/Article/details/gtheuaatym.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sysykeji.top/Article/details/gthlkauvcv.html

[E18] 模板占位符替换
来源：http://dali.zhoulong.xyz/Article/details/gtjxnlcrmb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hnqzz.top/Article/details/gtgaifxpkp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shuidangran.top/Article/details/gtrdniicat.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gtomzmdxky.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gtvpbdncna.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gtdwcapzof.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gtiyzzqtnj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cheryme.top/Article/details/gtnyficrnj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.tianlin.xyz/Article/details/gtzlywoeqo.html

[E19] 多行文本按行拆分
来源：http://dali.yuxming.cn/Article/details/gttxfvyuco.html

Py:   s.splitlines()
来源：http://dali.xylfe.cn/Article/details/gtqlpkjebl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtsyinpiqz.html

JS:   s.split(/\r?\n/)
来源：http://dali.pengpengdd.cyou/Article/details/gtewtemvon.html

TS:   s.split(/\r?\n/)
来源：http://dali.jyoumei.cn/Article/details/gtimrfhves.html

Java: s.lines().toList()
来源：http://dali.0kj1m.cn/Article/details/gtagcdxsqo.html

Go:   strings.Split(s, "\n")
来源：http://dali.gogol.net.cn/Article/details/gtjbkypnks.html

Ruby: s.lines
来源：http://dali.zhengqikj.top/Article/details/gtvpfdbsxq.html

C#:   s.Split('\n')
来源：http://dali.mhx1999.top/Article/details/gtgbjkvzop.html

[E20] 判断字符串是否为空
来源：http://dali.gotoacloud.top/Article/details/gtsyuemvut.html

Py:   if not s:
来源：http://dali.yonumen.top/Article/details/gthgzisrff.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xziqi.cn/Article/details/gtewqwalsy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenzaomai.com/Article/details/gtjkkhrfax.html

TS:   if (s === "") {}
来源：http://dali.guowangkeji.top/Article/details/gtmawdapxg.html

Java: if (s.isEmpty()) {}
来源：http://dali.xziqi.cn/Article/details/gtlfqoyujy.html

Go:   if s == "" {}
来源：http://dali.xuetiantiany.cn/Article/details/gtlgfkgaxq.html

Ruby: if s.empty?
来源：http://dali.tanke756.top/Article/details/gtgjfyhiku.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.daxiang520.top/Article/details/gtpbfwmeay.html

[E21] 超长截断加省略号
来源：http://dali.dashuyun.cn/Article/details/gtqqoekhpv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xylfe.cn/Article/details/gtymwoiwrv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gtouofmgzg.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gtxusyceiz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtzkriwmhu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiizmdgcz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.snrcjt.cn/Article/details/gtgqokagbv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hammf.cn/Article/details/gtuvaalygo.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gtezcxeohl.html

[E22] 字节长度与字符长度
来源：http://dali.chenlongwang.top/Article/details/gtbgkcwfrh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.mhx1999.top/Article/details/gtaxoktide.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gtbujxzyqw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gtzngxwchh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.smart0.xyz/Article/details/gtqoevdjxy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcfphyxee.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xylfe.cn/Article/details/gtiowuqzno.html

Ruby: s.bytesize;  s.length
来源：http://dali.yonumen.top/Article/details/gtyohpchqd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shuidangran.top/Article/details/gtaqvmuvwl.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtkpbwqhch.html

F. 文件与目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmjsacpfl.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtaonyuxfq.html

[F01] 读取整个文件
来源：http://dali.guowangkeji.top/Article/details/gtfwgfqnqw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jqgfzy.top/Article/details/gtjwwzmcny.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtlwmmyric.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sweek.top/Article/details/gtsroxwefw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gtwtdtoswo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gtqeajweyp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nanxinkj.top/Article/details/gtzqexnbsd.html

Ruby: File.read("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtsjxtqidl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtczjvcces.html

[F02] 逐行读取文件
来源：http://dali.sysykeji.top/Article/details/gtgbaqesyt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhengqikj.top/Article/details/gtsbmwckyv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhiwuduotai.top/Article/details/gtnyvegszm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtugxewbie.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxuanxn.top/Article/details/gthkgbtlie.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.quarkkingdee.top/Article/details/gtopxyihzh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzgtripox.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinghuilouyu.cn/Article/details/gtnlvzvmvl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yangfankeji.com/Article/details/gtgevlckxh.html

[F03] 写入文件（覆盖）
来源：http://dali.gotoacloud.top/Article/details/gtgkchgscu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yonumen.top/Article/details/gtfvuozzln.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.daxiang520.top/Article/details/gtjiktaiba.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.vqdsnc.cn/Article/details/gttbqkaoyr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gtkpfzpeix.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcrfwekdc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.meibo888.top/Article/details/gtrcnyxfih.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.smart0.xyz/Article/details/gtlntmytkl.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gotoacloud.top/Article/details/gttzaibesd.html

[F04] 追加写入文件
来源：http://dali.fengsongda.top/Article/details/gtrplfvuub.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.aibaodan.cn/Article/details/gteynfcaqr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.pycfn.com/Article/details/gttvzbvwmf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yvedp.cn/Article/details/gtgjyfwbgz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ydzc1.top/Article/details/gtirpyqooe.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xuanzx.com/Article/details/gtkgukrokm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sweek.top/Article/details/gtaoyytymk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj202588.top/Article/details/gtoadwkytu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjiodgugw.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinqigufen.top/Article/details/gtacjhzdsk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrvpqwmbi.html

PHP:  file_exists("a.txt");
来源：http://dali.guannengcc.top/Article/details/gteewjwonw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdjwmvyxp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtzdvmiinh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gtkgbzvmpi.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.svipenyu.cn/Article/details/gtspirzpsm.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj20258.top/Article/details/gtgqzhdhtt.html

C#:   File.Exists("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtdamrxjen.html

[F06] 删除文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtzoqhocbi.html

Py:   os.remove("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjozvcwqt.html

PHP:  unlink("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtuztodmzg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtkkthvxra.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtzqqbrqhx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gtvhmjlwst.html

Go:   os.Remove("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtufjpxevp.html

Ruby: File.delete("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtrkcylped.html

C#:   File.Delete("a.txt");
来源：http://dali.yj202588.top/Article/details/gtnnbbofuo.html

[F07] 创建目录（含多级）
来源：http://dali.nanxinkj.top/Article/details/gtpsnxbegd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hnxiangtu.top/Article/details/gtvrnemovx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinqigfzy.top/Article/details/gtmdsehhoa.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ybcxt.top/Article/details/gtiudrdraj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hammf.cn/Article/details/gtlfhffwdo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hywenlv.cn/Article/details/gtivzshufw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcdnupgaa.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yuanzhike.top/Article/details/gtrfazoacv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xinyue.icu/Article/details/gtejrpupmp.html

[F08] 遍历目录
来源：http://dali.jqgfzy.top/Article/details/gtodccrtjg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinqigufen.top/Article/details/gtwpccjrvk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gtglojgxgs.html

JS:   fs.readdirSync("dir")
来源：http://dali.ppjwa.cn/Article/details/gtdcafgfqr.html

TS:   fs.readdirSync("dir")
来源：http://dali.guannengcc.top/Article/details/gtjbhcrvqx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj20258888.top/Article/details/gtwrbrkuon.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.tian-w.cn/Article/details/gteiqrgeng.html

Ruby: Dir.children("dir")
来源：http://dali.nwbrower.top/Article/details/gtqwxgidgm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.dashuyun.cn/Article/details/gttsambbzt.html

[F09] 获取文件大小
来源：http://dali.chenjidiqi.icu/Article/details/gtfqlekhth.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtguhtandj.html

PHP:  filesize("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtzpeoahwh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.wangdashe.top/Article/details/gtxfrcuqhq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.havefunace.top/Article/details/gtyrkmoqnz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gtaytfkpgz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj202588.top/Article/details/gtebarthnw.html

Ruby: File.size("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtddsnnfef.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.haohaochexian.top/Article/details/gtcodmmytl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhixingplan.top/Article/details/gthpuvyvah.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfbvuonuq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtnlbkswqw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtwxqtbsfi.html

TS:   path.extname("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtpuqtepbk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.wangshuangyany.cn/Article/details/gtktbycgrn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gttsmhxdrb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtutrurvqx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtxicjfehp.html

[F11] 复制与移动文件
来源：http://dali.ivvv.top/Article/details/gthiqexmez.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtvrogorro.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yvedp.cn/Article/details/gtrjpakqxj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtyxpmblpg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gtuciaaoji.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenzaomai.com/Article/details/gtkqwupnhr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhongyouzk.top/Article/details/gtqxqttqty.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gthiziandn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.smart0.xyz/Article/details/gtrcayhqgu.html

[F12] CSV 读写
来源：http://dali.yj20258888.top/Article/details/gtahjslvsy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shangyingyoupin.top/Article/details/gtlhbqcrwl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.quarkkingdee.top/Article/details/gterojocgy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrethdehp.html

TS:   // 同上
来源：http://dali.ivvv.top/Article/details/gtahgmtanr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xuetiantiany.cn/Article/details/gtfuachvgg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tanke756.top/Article/details/gtjvdletpb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xinyue.icu/Article/details/gtgxbssivg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.iojbl.cn/Article/details/gtagalgsmc.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtrmezafue.html

G. 面向对象
来源：http://dali.cdnleiting.top/Article/details/gtlgtgigef.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtcnheokif.html

[G01] 定义类
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwqkkjtpf.html

Py:   class User: pass
来源：http://dali.quarkkingdee.top/Article/details/gthqmufxym.html

PHP:  class User {}
来源：http://dali.iojbl.cn/Article/details/gtunkjjtmy.html

JS:   class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtupqsrzbp.html

TS:   class User { name: string = ""; }
来源：http://dali.fzhhl.top/Article/details/gtqhaniphh.html

Java: class User {}
来源：http://dali.dianchejie.cn/Article/details/gtsbmgetcc.html

Go:   type User struct { Name string }
来源：http://dali.chenlongwang.top/Article/details/gtkikddcgu.html

Ruby: class User; end
来源：http://dali.aizwys.cn/Article/details/gtjqejrzrv.html

C#:   class User {}
来源：http://dali.gzhubu.top/Article/details/gtrpdrnhms.html

[G02] 构造函数
来源：http://dali.kuanghao11.cn/Article/details/gtrcuesywl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.svipenyu.cn/Article/details/gtlwxendkt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.iojbl.cn/Article/details/gtzujdpvje.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.dashuyun.cn/Article/details/gtqhmjmbbv.html

TS:   constructor(public name: string) {}
来源：http://dali.sxryk.cn/Article/details/gteczvobha.html

Java: User(String name) { this.name = name; }
来源：http://dali.zycfv.cn/Article/details/gtqmuigqak.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrsucgbbe.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.svipenyu.cn/Article/details/gtzzumqrrn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gotoacloud.top/Article/details/gtudsozgqm.html

[G03] 实例属性
来源：http://dali.ehwqpu.com/Article/details/gtsmhpqalj.html

Py:   self.name = "x"
来源：http://dali.fzhhl.top/Article/details/gtytjinxac.html

PHP:  public string $name = "x";
来源：http://dali.tian-w.cn/Article/details/gtxmxjemsc.html

JS:   this.name = "x";
来源：http://dali.yueranfly.top/Article/details/gtzqfvlwmg.html

TS:   name: string = "x";
来源：http://dali.nwbrower.top/Article/details/gtrrxfnspd.html

Java: private String name;
来源：http://dali.feifeiyinyue.top/Article/details/gttawyqgmx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hywenlv.cn/Article/details/gtwbymoyws.html

Ruby: @name = "x"
来源：http://dali.vqdsnc.cn/Article/details/gtrjhchrpk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtjoxwknfo.html

[G04] 定义方法
来源：http://dali.gogol.net.cn/Article/details/gtqmtkbvcn.html

Py:   def greet(self): return self.name
来源：http://dali.smart0.xyz/Article/details/gtkzustqqk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gtugonkmge.html

JS:   greet() { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gtdruaiila.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gtdddjfljn.html

Java: String greet() { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtdoinaprg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gtfpmytqka.html

Ruby: def greet; @name; end
来源：http://dali.yvedp.cn/Article/details/gtdzttctrc.html

C#:   public string Greet() => Name;
来源：http://dali.andypj.xyz/Article/details/gtbpditvyp.html

[G05] 继承
来源：http://dali.hfpthk.cn/Article/details/gtwxgrdbxa.html

Py:   class Admin(User): pass
来源：http://dali.zycfv.cn/Article/details/gtehvpmjok.html

PHP:  class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gtotyxktqi.html

JS:   class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gtzoyazdah.html

TS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtwoaemhks.html

Java: class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gtivvnmgpr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jqgfzy.top/Article/details/gttuncwddl.html

Ruby: class Admin < User; end
来源：http://dali.jyoumei.cn/Article/details/gtymcizhhf.html

C#:   class Admin : User {}
来源：http://dali.yuanzhike.top/Article/details/gtipflrmsu.html

[G06] 重写方法
来源：http://dali.iojbl.cn/Article/details/gtpgouyimt.html

Py:   def greet(self): return "admin"
来源：http://dali.xinyue.icu/Article/details/gtwflfadmr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthbcuxjnq.html

JS:   greet() { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gtrcdgrpyw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gtmjinfodp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gtrabgefbi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ppjwa.cn/Article/details/gtheeujcnj.html

Ruby: def greet; "admin"; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcavjyirj.html

C#:   public override string Greet() => "admin";
来源：http://dali.c1oappe.top/Article/details/gtfkdjpgky.html

[G07] 调用父类方法
来源：http://dali.c1oappe.top/Article/details/gtxfgnflbj.html

Py:   super().greet()
来源：http://dali.yj20258888.top/Article/details/gtypaqrqoq.html

PHP:  parent::greet();
来源：http://dali.dashuyun.cn/Article/details/gtnswvrxnp.html

JS:   super.greet();
来源：http://dali.zhoulong.xyz/Article/details/gtyxgynkpu.html

TS:   super.greet();
来源：http://dali.yvedp.cn/Article/details/gtfvhiupxa.html

Java: super.greet();
来源：http://dali.ehwqpu.com/Article/details/gtesvyflwe.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.wangdashe.top/Article/details/gtbyutveeb.html

Ruby: super
来源：http://dali.shanyushiyangtech.top/Article/details/gthwfszbli.html

C#:   base.Greet();
来源：http://dali.daria6918.cn/Article/details/gtxzwhqhdx.html

[G08] 静态方法与属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjmwygtvu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhoulong.xyz/Article/details/gtrywngwbr.html

PHP:  public static function f() {}
来源：http://dali.meibo888.top/Article/details/gtvibjklgh.html

JS:   static f() {}
来源：http://dali.0kj1m.cn/Article/details/gtlxvxwhxo.html

TS:   static f(): void {}
来源：http://dali.hnqzz.top/Article/details/gtaayboifx.html

Java: static void f() {}
来源：http://dali.nwbrower.top/Article/details/gtimyrpkta.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.bjfxy.top/Article/details/gtefkarwor.html

Ruby: def self.f; end
来源：http://dali.tanke756.top/Article/details/gtxdkoayav.html

C#:   public static void F() {}
来源：http://dali.vqdsnc.cn/Article/details/gtenrjcahw.html

[G09] 接口 / 抽象类
来源：http://dali.yueranfly.top/Article/details/gtszhqdspg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hongshengwenyu.top/Article/details/gtvaherizj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.feifeiyinyue.top/Article/details/gtqdugrtjh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.mhx1999.top/Article/details/gtevoteimg.html

TS:   interface Shape { area(): number; }
来源：http://dali.hywenlv.cn/Article/details/gtcivmewvz.html

Java: interface Shape { double area(); }
来源：http://dali.hysaishi.cn/Article/details/gtdqbdjtbn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yangfankeji.com/Article/details/gtfvhcufod.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvhcvfpuv.html

C#:   interface IShape { double Area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtizkodxsw.html

[G10] 访问控制
来源：http://dali.zhongyouzk.top/Article/details/gtxqfodgms.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gotoacloud.top/Article/details/gtiqlkhhju.html

PHP:  public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnzgmtixq.html

JS:   #private 字段；其余公开
来源：http://dali.jinyuanbaomall.cn/Article/details/gttxudbrdb.html

TS:   public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gtmilmloms.html

Java: public / protected / private / 默认包级
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxxcawqre.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shanyushiyangtech.top/Article/details/gttptuwpfq.html

Ruby: public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gteejplkkt.html

C#:   public / protected / private / internal
来源：http://dali.jinghuilouyu.cn/Article/details/gtiicrzpdx.html

[G11] getter / setter
来源：http://dali.gotoacloud.top/Article/details/gtivkmzwre.html

Py:   @property 与 @x.setter
来源：http://dali.wangshuangyany.cn/Article/details/gtbmhttpdm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ivvv.top/Article/details/gtkdyweyds.html

JS:   get name() { return this._name; }
来源：http://dali.nanxinkj.top/Article/details/gthhgbgqmp.html

TS:   get name(): string { return this._name; }
来源：http://dali.aizwys.cn/Article/details/gtujhbzolo.html

Java: public String getName() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtabmysrgp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gttoeskkfj.html

Ruby: attr_accessor :name
来源：http://dali.xinyue.icu/Article/details/gtduumdbcj.html

C#:   public string Name { get; set; }
来源：http://dali.havefunace.top/Article/details/gtkambemoz.html

[G12] 对象转字符串
来源：http://dali.yvedp.cn/Article/details/gthbqskjkv.html

Py:   def __str__(self): return self.name
来源：http://dali.wangshuangyany.cn/Article/details/gtyxfbidrm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gtduroqqez.html

JS:   toString() { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtglbkabyr.html

TS:   toString(): string { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gtvyajmfsy.html

Java: @Override public String toString() { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gtluiqbivz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gttrwcqplj.html

Ruby: def to_s; @name; end
来源：http://dali.xuetiantiany.cn/Article/details/gtwjwlnnla.html

C#:   public override string ToString() => Name;
来源：http://dali.snrcjt.cn/Article/details/gtmftqcdro.html

[G13] 判断对象类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnxxldqfy.html

Py:   isinstance(u, User)
来源：http://dali.wangshuangyany.cn/Article/details/gtdougpwhd.html

PHP:  $u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtmsgcygnb.html

JS:   u instanceof User
来源：http://dali.yj202588.top/Article/details/gtwcttwdcy.html

TS:   u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gtzorqrluq.html

Java: u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gtmkhlkfww.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gtlelunrnq.html

Ruby: u.is_a?(User)
来源：http://dali.bjfxy.top/Article/details/gtvqjuapni.html

C#:   u is User
来源：http://dali.daria6918.cn/Article/details/gtuugpcuxq.html

[G14] 数据类 / record
来源：http://dali.hfpthk.cn/Article/details/gtqntlwmca.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zycfv.cn/Article/details/gttyfyofya.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jianghu66.top/Article/details/gtgsrljjme.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gotoacloud.top/Article/details/gtnqdbsfiy.html

TS:   type User = { name: string; age: number };
来源：http://dali.sufxvd.cn/Article/details/gtupankgls.html

Java: record User(String name, int age) {}
来源：http://dali.c1oappe.top/Article/details/gtdxncurpm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenzaomai.com/Article/details/gtzdjzypfq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yanxiufei.cn/Article/details/gtuxmmieve.html

C#:   record User(string Name, int Age);
来源：http://dali.ehwqpu.com/Article/details/gtkcftztmg.html

[G15] 枚举
来源：http://dali.yangfankeji.com/Article/details/gtluogkdfj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttvbrzzsy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.316326.xyz/Article/details/gtupylklbv.html


<!-- 参考信息 -->