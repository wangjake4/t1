代发 wailian999

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.mhx1999.top/Article/details/gtnwpdmcti.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtfxnhotgg.html

[E16] 数字千分位
来源：http://dali.feifeiyinyue.top/Article/details/gthhrjoksy.html

Py:   f"{1234567:,}"
来源：http://dali.tianlin.xyz/Article/details/gtmpulfcab.html

PHP:  number_format(1234567);
来源：http://dali.feifeiyinyue.top/Article/details/gtkygkkfbr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuetiantiany.cn/Article/details/gtmlcxyqtg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.svipenyu.cn/Article/details/gtgserezpf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gtodmfrafv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hysaishi.cn/Article/details/gtkwbtaoeh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.c1oappe.top/Article/details/gtkxsgodfk.html

C#:   1234567.ToString("N0")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrhxqcjtl.html

[E17] 首字母大写
来源：http://dali.jqgufenzy.top/Article/details/gtzosipyxs.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.vqdsnc.cn/Article/details/gtmbzvucia.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ehwqpu.com/Article/details/gtcgyjobdp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sweek.top/Article/details/gtneryqbbw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuxming.cn/Article/details/gtpvmobmjd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.tanke756.top/Article/details/gtlhktmqvj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hammf.cn/Article/details/gtqxocjtsn.html

Ruby: s.capitalize
来源：http://dali.meibo888.top/Article/details/gtdzrlqcjz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.wangdashe.top/Article/details/gtzxrzoria.html

[E18] 模板占位符替换
来源：http://dali.shangyingyoupin.top/Article/details/gtdmizgaxd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqskzbsrr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrarxvwhx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.mhx1999.top/Article/details/gtuoebrofn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gtststypjt.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gtqpiophdv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gtbqwdqmmi.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj202588.top/Article/details/gtowvihirm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nanxuanxn.top/Article/details/gtggiewqmk.html

[E19] 多行文本按行拆分
来源：http://dali.feifeiyinyue.top/Article/details/gtrjqrytgz.html

Py:   s.splitlines()
来源：http://dali.bjfxy.top/Article/details/gtfqishkyh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtgzkrafoq.html

JS:   s.split(/\r?\n/)
来源：http://dali.yuxming.cn/Article/details/gtllyumwxz.html

TS:   s.split(/\r?\n/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxirhfomg.html

Java: s.lines().toList()
来源：http://dali.gogol.net.cn/Article/details/gtgysyysfs.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj202588.top/Article/details/gtsuvvhvcv.html

Ruby: s.lines
来源：http://dali.hywenlv.cn/Article/details/gtzjdjmitw.html

C#:   s.Split('\n')
来源：http://dali.fengsongda.top/Article/details/gtxozeucyi.html

[E20] 判断字符串是否为空
来源：http://dali.gzhubu.top/Article/details/gtmxnennhi.html

Py:   if not s:
来源：http://dali.redwolf501.top/Article/details/gtcmvrlnqy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jianghu66.top/Article/details/gtjnnptoca.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.guowangkeji.top/Article/details/gtdgcrrumy.html

TS:   if (s === "") {}
来源：http://dali.hnxiangtu.top/Article/details/gtluqaizlc.html

Java: if (s.isEmpty()) {}
来源：http://dali.zycfv.cn/Article/details/gtlelwmkmg.html

Go:   if s == "" {}
来源：http://dali.vqdsnc.cn/Article/details/gtwbxwocsv.html

Ruby: if s.empty?
来源：http://dali.shanyushiyangtech.top/Article/details/gtmducvjgw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cashguo.top/Article/details/gtninetgqt.html

[E21] 超长截断加省略号
来源：http://dali.hywenlv.cn/Article/details/gtjwwwalbj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yonumen.top/Article/details/gtuyolxvwh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gtqrybpvae.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtyehcnkmi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnqzz.top/Article/details/gtehqfskem.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gtnhqexgpj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.tianlin.xyz/Article/details/gtxcvsgrvv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtxxvfaoff.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtdexmmtuv.html

[E22] 字节长度与字符长度
来源：http://dali.zycfv.cn/Article/details/gtkqmiopyr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtotgelxym.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gtdtcpelku.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pengpengdd.cyou/Article/details/gtcixqvoaz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhengqikj.top/Article/details/gtoglosriy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yonumen.top/Article/details/gtwclevlif.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenjidiqi.icu/Article/details/gtrjabhpro.html

Ruby: s.bytesize;  s.length
来源：http://dali.daria6918.cn/Article/details/gtrmgyhojd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sufxvd.cn/Article/details/gteoytfnth.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtbtucefef.html

F. 文件与目录
来源：http://dali.chenzaomai.com/Article/details/gtijaklcic.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtdepcwfrb.html

[F01] 读取整个文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtswjquqgo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.aizwys.cn/Article/details/gtcmvvrahh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtyqyiliyl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gzhubu.top/Article/details/gtbzykxrim.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnbqnafjp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gtqitycque.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sysykeji.top/Article/details/gtvdggjbfc.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtnqvmdtfz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtxuzqpndo.html

[F02] 逐行读取文件
来源：http://dali.aibaodan.cn/Article/details/gtpimztqzq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yj202588.top/Article/details/gtxbxttxsv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cashguo.top/Article/details/gtrxstscgc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ydzc1.top/Article/details/gtxxibagrs.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cucudq.cn/Article/details/gtuirybszy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.fengsongda.top/Article/details/gtzfppplho.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtomdkiukn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.aibaodan.cn/Article/details/gtdwxdbvsw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhiwuduotai.top/Article/details/gtuquooyra.html

[F03] 写入文件（覆盖）
来源：http://dali.shanyushiyangtech.top/Article/details/gtnqmhsspz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yuxming.cn/Article/details/gtdgimpumu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xziqi.cn/Article/details/gttttyccey.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gtorxtbhmo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.birdmap.top/Article/details/gtezpcqjoi.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.quarkkingdee.top/Article/details/gtpaenaoxy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.havefunace.top/Article/details/gtncalcjzr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhixingplan.top/Article/details/gtfdodchlw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cdnleiting.top/Article/details/gtzakaiktc.html

[F04] 追加写入文件
来源：http://dali.tianlin.xyz/Article/details/gtwpkpxysu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sysykeji.top/Article/details/gtvxxwilfw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.vqdsnc.cn/Article/details/gtoprknqgl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.andypj.xyz/Article/details/gtepaimjeu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrhzqudha.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ybcxt.top/Article/details/gtkxrefuvq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqdogkzfr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.0kj1m.cn/Article/details/gtjqgyxmlg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cdnleiting.top/Article/details/gtuzpnykhx.html

[F05] 判断文件或目录是否存在
来源：http://dali.aizwys.cn/Article/details/gtgdkzrrxr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhengqikj.top/Article/details/gtdqjruoto.html

PHP:  file_exists("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtlxzypnat.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtnlbzvjee.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtpmeoadti.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gtzexbpcbr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ehwqpu.com/Article/details/gtqgayliuq.html

Ruby: File.exist?("a.txt")
来源：http://dali.birdmap.top/Article/details/gtazftjlkn.html

C#:   File.Exists("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtjufinkzf.html

[F06] 删除文件
来源：http://dali.cashguo.top/Article/details/gtydtvdpwy.html

Py:   os.remove("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtfvlupash.html

PHP:  unlink("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtvtwlqxmt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtfuiiscbu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtssqdunyd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gtfwspdufr.html

Go:   os.Remove("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtshuyzfyp.html

Ruby: File.delete("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtnbhadhwh.html

C#:   File.Delete("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtzkwetufl.html

[F07] 创建目录（含多级）
来源：http://dali.9152youxi.cn/Article/details/gtbmrgycif.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jqgufenzy.top/Article/details/gtegumwztp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hnxiangtu.top/Article/details/gtfthfeaem.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sufxvd.cn/Article/details/gtfjsmsnvr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dashuyun.cn/Article/details/gtjbwfrvtu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhixingplan.top/Article/details/gtztncqvag.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yvedp.cn/Article/details/gtaopyjpsc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cqqwz.cn/Article/details/gtyaksfgea.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.dashuyun.cn/Article/details/gtkcogcoim.html

[F08] 遍历目录
来源：http://dali.zhiwuduotai.top/Article/details/gtycevqfce.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrtxhqxjz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.316326.xyz/Article/details/gtnebknqfr.html

JS:   fs.readdirSync("dir")
来源：http://dali.daxiang520.top/Article/details/gtfyjocvqg.html

TS:   fs.readdirSync("dir")
来源：http://dali.mhx1999.top/Article/details/gtyktodyjc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfgbbmqea.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtfmdqpptc.html

Ruby: Dir.children("dir")
来源：http://dali.nanxinkj.top/Article/details/gttfgqecpi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.birdmap.top/Article/details/gttynsqmtv.html

[F09] 获取文件大小
来源：http://dali.guowangkeji.top/Article/details/gtollgozjm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtvqixvffr.html

PHP:  filesize("a.txt");
来源：http://dali.sweek.top/Article/details/gtvdelirwd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.daria6918.cn/Article/details/gtmepfrnpx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.aizwys.cn/Article/details/gtuaqqnngb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gtfjtpqicd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxrestkqv.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtsnrenjrg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xuetiantiany.cn/Article/details/gtefkobnsb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sufxvd.cn/Article/details/gtpfbdzuji.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtchopgvzd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ivvv.top/Article/details/gtezsxsjqn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtziftkywe.html

TS:   path.extname("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtlqgdonyt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yonumen.top/Article/details/gtstkeiqmi.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtyummcuqw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtzakkzpnm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtzizjprsu.html

[F11] 复制与移动文件
来源：http://dali.tanke756.top/Article/details/gtyurdbdhe.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtjfprggqr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtrevyzlen.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtuawntgsn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gtdmuavqur.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhoulong.xyz/Article/details/gtxlqhgqpy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yvedp.cn/Article/details/gtvryeckvg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtjmuhoygp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hfpthk.cn/Article/details/gtsjkyqdvn.html

[F12] CSV 读写
来源：http://dali.gzhubu.top/Article/details/gtbsvscnih.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.0kj1m.cn/Article/details/gtpgadlndv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhixingplan.top/Article/details/gtbxgxzaec.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gtqglgdsyn.html

TS:   // 同上
来源：http://dali.gogol.net.cn/Article/details/gtamqfjbvw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.dianchejie.cn/Article/details/gtxxjiioqg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.havefunace.top/Article/details/gtyyztdeqh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gtfvplrekx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.havefunace.top/Article/details/gtipgjsyuw.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtcrkllnyc.html

G. 面向对象
来源：http://dali.andypj.xyz/Article/details/gtkmesfiwn.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtukmoxazo.html

[G01] 定义类
来源：http://dali.cashguo.top/Article/details/gtkngzgjxu.html

Py:   class User: pass
来源：http://dali.feifeiyinyue.top/Article/details/gtwrqbgbkr.html

PHP:  class User {}
来源：http://dali.xylfe.cn/Article/details/gteqwythoi.html

JS:   class User {}
来源：http://dali.ybcxt.top/Article/details/gtewktmgqh.html

TS:   class User { name: string = ""; }
来源：http://dali.jinqigfzy.top/Article/details/gtnyqrpdsy.html

Java: class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtytsusgma.html

Go:   type User struct { Name string }
来源：http://dali.bjfxy.top/Article/details/gtpjlqzloq.html

Ruby: class User; end
来源：http://dali.jqgfzy.top/Article/details/gttzfybqym.html

C#:   class User {}
来源：http://dali.birdmap.top/Article/details/gtjndwzpzb.html

[G02] 构造函数
来源：http://dali.ydzc1.top/Article/details/gtfdjsoqqm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gzhubu.top/Article/details/gttdfwzkyv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenzaomai.com/Article/details/gtmxdvayvr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtnonninno.html

TS:   constructor(public name: string) {}
来源：http://dali.gogol.net.cn/Article/details/gtwxeiedbn.html

Java: User(String name) { this.name = name; }
来源：http://dali.guannengcc.top/Article/details/gtbmhslafj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yuxming.cn/Article/details/gtdpaafmho.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.316326.xyz/Article/details/gtguvrfsvc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jyoumei.cn/Article/details/gtzysubope.html

[G03] 实例属性
来源：http://dali.nanxuanxn.top/Article/details/gtboiilmce.html

Py:   self.name = "x"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvydmhopg.html

PHP:  public string $name = "x";
来源：http://dali.daria6918.cn/Article/details/gtkhaboyhh.html

JS:   this.name = "x";
来源：http://dali.fengsongda.top/Article/details/gttusrmaxp.html

TS:   name: string = "x";
来源：http://dali.shuidangran.top/Article/details/gtorltzurs.html

Java: private String name;
来源：http://dali.yj20258.top/Article/details/gtumoqhtsa.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tianlin.xyz/Article/details/gtnqdoyrpj.html

Ruby: @name = "x"
来源：http://dali.chenlongwang.top/Article/details/gtbdmpwnyr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yongpay.top/Article/details/gtdlgwgyrk.html

[G04] 定义方法
来源：http://dali.haohaochexian.top/Article/details/gtgfvshxdr.html

Py:   def greet(self): return self.name
来源：http://dali.yj20258.top/Article/details/gtwzatqjqk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gtpyxdbtwr.html

JS:   greet() { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gtcfbybozh.html

TS:   greet(): string { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtvusrvidf.html

Java: String greet() { return name; }
来源：http://dali.zhixingplan.top/Article/details/gtjrezljwv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gtrmhpewxm.html

Ruby: def greet; @name; end
来源：http://dali.xuetiantiany.cn/Article/details/gtnhqejhqr.html

C#:   public string Greet() => Name;
来源：http://dali.ppjwa.cn/Article/details/gtkpcmrrrp.html

[G05] 继承
来源：http://dali.havefunace.top/Article/details/gtojesbwfj.html

Py:   class Admin(User): pass
来源：http://dali.gaohongyu789.top/Article/details/gtynwgpcuj.html

PHP:  class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gtvbzmnheg.html

JS:   class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gtxbsrkbtn.html

TS:   class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtbbrrlzkk.html

Java: class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtstiwmhni.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.quarkkingdee.top/Article/details/gtyopcrkac.html

Ruby: class Admin < User; end
来源：http://dali.sysykeji.top/Article/details/gtrznjvtjf.html

C#:   class Admin : User {}
来源：http://dali.jinqigfzy.top/Article/details/gthnmylrez.html

[G06] 重写方法
来源：http://dali.fengsongda.top/Article/details/gtsveudhkc.html

Py:   def greet(self): return "admin"
来源：http://dali.redwolf501.top/Article/details/gtcolfvfat.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtzadsdqyr.html

JS:   greet() { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiyhnbqip.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtjoryehwh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtgruaivpr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ydzc1.top/Article/details/gtlsaihyyt.html

Ruby: def greet; "admin"; end
来源：http://dali.shangyingyoupin.top/Article/details/gtpwkszmic.html

C#:   public override string Greet() => "admin";
来源：http://dali.yonumen.top/Article/details/gtdphocmsu.html

[G07] 调用父类方法
来源：http://dali.svipenyu.cn/Article/details/gtpollcsfn.html

Py:   super().greet()
来源：http://dali.tian-w.cn/Article/details/gtmmsznfdp.html

PHP:  parent::greet();
来源：http://dali.dashuyun.cn/Article/details/gtnfhtqyhz.html

JS:   super.greet();
来源：http://dali.chenzaomai.com/Article/details/gtyeeaxvsk.html

TS:   super.greet();
来源：http://dali.bjfxy.top/Article/details/gtdvropusz.html

Java: super.greet();
来源：http://dali.cqqwz.cn/Article/details/gtlgykmwcr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtomqorfzk.html

Ruby: super
来源：http://dali.nanxinkj.top/Article/details/gtihngjtre.html

C#:   base.Greet();
来源：http://dali.ybcxt.top/Article/details/gtoqwteeot.html

[G08] 静态方法与属性
来源：http://dali.shzxlz.cn/Article/details/gtayjrqyrw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuetiantiany.cn/Article/details/gtvbaprsvi.html

PHP:  public static function f() {}
来源：http://dali.cucudq.cn/Article/details/gtkgpwqocp.html

JS:   static f() {}
来源：http://dali.jyoumei.cn/Article/details/gtepdpgxdg.html

TS:   static f(): void {}
来源：http://dali.zhengqikj.top/Article/details/gttusbnsop.html

Java: static void f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtuxqyaktc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cucudq.cn/Article/details/gtpodxzyci.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gtyozbqbzo.html

C#:   public static void F() {}
来源：http://dali.nwbrower.top/Article/details/gtyqcuqarp.html

[G09] 接口 / 抽象类
来源：http://dali.dianchejie.cn/Article/details/gtooanitas.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jiagoushi.top/Article/details/gtaqbuvqul.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.kuanghao11.cn/Article/details/gtijbahtix.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hnxiangtu.top/Article/details/gtcgpdzuim.html

TS:   interface Shape { area(): number; }
来源：http://dali.cucudq.cn/Article/details/gtorltzzdd.html

Java: interface Shape { double area(); }
来源：http://dali.gogol.net.cn/Article/details/gtgsppbfji.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.0kj1m.cn/Article/details/gtapezwxlg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zycfv.cn/Article/details/gtuaqmhywn.html

C#:   interface IShape { double Area(); }
来源：http://dali.9152youxi.cn/Article/details/gtnymznhzb.html

[G10] 访问控制
来源：http://dali.hnqzz.top/Article/details/gtkyzoucqo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.havefunace.top/Article/details/gtdouscelc.html

PHP:  public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gtnsaxahon.html

JS:   #private 字段；其余公开
来源：http://dali.xuetiantiany.cn/Article/details/gtwcgechcr.html

TS:   public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gtxoznhmfj.html

Java: public / protected / private / 默认包级
来源：http://dali.jianghu66.top/Article/details/gtxxllkemt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yonumen.top/Article/details/gtalcznoor.html

Ruby: public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gtoiaoojei.html

C#:   public / protected / private / internal
来源：http://dali.quarkkingdee.top/Article/details/gtiswikskk.html

[G11] getter / setter
来源：http://dali.ybcxt.top/Article/details/gtplbjixhy.html

Py:   @property 与 @x.setter
来源：http://dali.cashguo.top/Article/details/gtcwusvxbh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttdzztaeo.html

JS:   get name() { return this._name; }
来源：http://dali.jlsjyb.cn/Article/details/gteuwphcer.html

TS:   get name(): string { return this._name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwvwwrgxx.html

Java: public String getName() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqytfcrc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gtnzmxpjcn.html

Ruby: attr_accessor :name
来源：http://dali.xylfe.cn/Article/details/gtvwtkdsfo.html

C#:   public string Name { get; set; }
来源：http://dali.sysykeji.top/Article/details/gtktsrthrc.html

[G12] 对象转字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtanmsfnza.html

Py:   def __str__(self): return self.name
来源：http://dali.mhx1999.top/Article/details/gtuopbpmgj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gtgihifqrz.html

JS:   toString() { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtiwhflqvz.html

TS:   toString(): string { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtnggvqrsr.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gttucqcjjp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtlsutwcrh.html

Ruby: def to_s; @name; end
来源：http://dali.yvedp.cn/Article/details/gtfstsgjfx.html

C#:   public override string ToString() => Name;
来源：http://dali.yj202588.top/Article/details/gtzzhbzstm.html

[G13] 判断对象类型
来源：http://dali.zhongyouzk.top/Article/details/gtyrgjcesc.html

Py:   isinstance(u, User)
来源：http://dali.sysykeji.top/Article/details/gtgumxjblh.html

PHP:  $u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gtfjjnssjy.html

JS:   u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gteyqbdqlv.html

TS:   u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtxaaejluh.html

Java: u instanceof User
来源：http://dali.aizwys.cn/Article/details/gtvvhalahu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xziqi.cn/Article/details/gtppqitslb.html

Ruby: u.is_a?(User)
来源：http://dali.nanxinkj.top/Article/details/gtwmoguqgw.html

C#:   u is User
来源：http://dali.andypj.xyz/Article/details/gthmzhpyyx.html

[G14] 数据类 / record
来源：http://dali.haohaochexian.top/Article/details/gtwruhbrdn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.birdmap.top/Article/details/gtuqhjxzgf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jqgfzy.top/Article/details/gtenxfkzvn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cucudq.cn/Article/details/gtixgrwsav.html


<!-- 参考信息 -->