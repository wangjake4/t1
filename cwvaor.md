代发 wailian999

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinqigufen.top/Article/details/gtyllhnjlo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gzhubu.top/Article/details/gtywrdasdg.html

[E16] 数字千分位
来源：http://dali.316326.xyz/Article/details/gtiukktnnv.html

Py:   f"{1234567:,}"
来源：http://dali.daxiang520.top/Article/details/gtdnyakqiv.html

PHP:  number_format(1234567);
来源：http://dali.redwolf501.top/Article/details/gtiqtdwqmk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlrqwthrw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tanke756.top/Article/details/gtrxetxwid.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.fzhhl.top/Article/details/gtjlvgxifx.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tianlin.xyz/Article/details/gtekgjgcso.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gtbynmtkvl.html

C#:   1234567.ToString("N0")
来源：http://dali.yuanzhike.top/Article/details/gtzedhwgpj.html

[E17] 首字母大写
来源：http://dali.jinqigufen.top/Article/details/gtymwrnuio.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.316326.xyz/Article/details/gtvxdhseeq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtdbdhxnah.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.bjfxy.top/Article/details/gtmgvgrsfs.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.meibo888.top/Article/details/gtaayxfzyk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.daria6918.cn/Article/details/gtspenwlyg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.dashuyun.cn/Article/details/gtekwstntt.html

Ruby: s.capitalize
来源：http://dali.wangdashe.top/Article/details/gtmunlbxln.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.chenjidiqi.icu/Article/details/gtikcznusc.html

[E18] 模板占位符替换
来源：http://dali.chenjidiqi.icu/Article/details/gtmyvpuojy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhiwuduotai.top/Article/details/gtovnfppwg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.aizwys.cn/Article/details/gtedkwjzby.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.fengsongda.top/Article/details/gtzmvnrjjd.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.pycfn.com/Article/details/gtmkeuzahl.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gtkbgtydsf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gtusxwlceu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yuanzhike.top/Article/details/gtxdotlwqj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shzxlz.cn/Article/details/gtekcrlcrw.html

[E19] 多行文本按行拆分
来源：http://dali.hnqzz.top/Article/details/gtgtzhgoxp.html

Py:   s.splitlines()
来源：http://dali.xuanzx.com/Article/details/gthlqscbic.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtrqleglzm.html

JS:   s.split(/\r?\n/)
来源：http://dali.chenlongwang.top/Article/details/gtikakcahv.html

TS:   s.split(/\r?\n/)
来源：http://dali.yueranfly.top/Article/details/gtgsspbhhc.html

Java: s.lines().toList()
来源：http://dali.redwolf501.top/Article/details/gtesnxkzox.html

Go:   strings.Split(s, "\n")
来源：http://dali.pengpengdd.cyou/Article/details/gtsehgitnv.html

Ruby: s.lines
来源：http://dali.sysykeji.top/Article/details/gtrhaqlifc.html

C#:   s.Split('\n')
来源：http://dali.hammf.cn/Article/details/gtsipuyhbb.html

[E20] 判断字符串是否为空
来源：http://dali.yj202588.top/Article/details/gtsxoxpgrf.html

Py:   if not s:
来源：http://dali.cashguo.top/Article/details/gtfjtdayyo.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.c1oappe.top/Article/details/gtqyezwqnc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gtarukkclh.html

TS:   if (s === "") {}
来源：http://dali.yj20258888.top/Article/details/gtroorjmdk.html

Java: if (s.isEmpty()) {}
来源：http://dali.redwolf501.top/Article/details/gtmslipcuy.html

Go:   if s == "" {}
来源：http://dali.nwbrower.top/Article/details/gtyfpsuifr.html

Ruby: if s.empty?
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbgqqhvhy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yj20258888.top/Article/details/gtslraudqk.html

[E21] 超长截断加省略号
来源：http://dali.316326.xyz/Article/details/gtpglaqvde.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xylfe.cn/Article/details/gtcytamtse.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gtqfmkwaku.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtfabhdude.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtynsgydhx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gtkfkdwiqx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xinyue.icu/Article/details/gtzmordoty.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfnkccvr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtsgachdog.html

[E22] 字节长度与字符长度
来源：http://dali.wangdashe.top/Article/details/gtxlgnlugd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cqqwz.cn/Article/details/gttlycvkkj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gtvqfkqtrv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gturwfmnqn.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nwbrower.top/Article/details/gtqnejogzi.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jyoumei.cn/Article/details/gtyvtfvjbp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cqqwz.cn/Article/details/gtwmqtgpfa.html

Ruby: s.bytesize;  s.length
来源：http://dali.ydzc1.top/Article/details/gteszdxkmc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj20258888.top/Article/details/gtuskigeyd.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtpmvekwdq.html

F. 文件与目录
来源：http://dali.hfpthk.cn/Article/details/gtinzpjidn.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtksqpmlyj.html

[F01] 读取整个文件
来源：http://dali.yangfankeji.com/Article/details/gtvpbtbdon.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.meibo888.top/Article/details/gtzryrwjfa.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtrfhfagtp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yanxiufei.cn/Article/details/gtqhexmklu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.0kj1m.cn/Article/details/gtifmhwimu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gtkvdcmohh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.fzhhl.top/Article/details/gtyjwhhexi.html

Ruby: File.read("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtitajytph.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gthcnzpgrd.html

[F02] 逐行读取文件
来源：http://dali.smart0.xyz/Article/details/gtvqtrcmgv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdekxjxtp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj20258888.top/Article/details/gtlqkjdkve.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tanke756.top/Article/details/gtpxsoposm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guannengcc.top/Article/details/gtohhopxzf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cheryme.top/Article/details/gtlmvhzawh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zycfv.cn/Article/details/gtiijpknps.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yvedp.cn/Article/details/gtxacdxeqe.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yangfankeji.com/Article/details/gtepjeldcc.html

[F03] 写入文件（覆盖）
来源：http://dali.tian-w.cn/Article/details/gtmgfmlxqy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ehwqpu.com/Article/details/gtiodppurk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ybcxt.top/Article/details/gtywkxnnvc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.mhx1999.top/Article/details/gthdxjrdkg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ybcxt.top/Article/details/gtseferjwp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xuanzx.com/Article/details/gtidzinyci.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.0kj1m.cn/Article/details/gtkgtawvqg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tanke756.top/Article/details/gtjrpjdrbl.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhengqikj.top/Article/details/gtqrrjnswj.html

[F04] 追加写入文件
来源：http://dali.hysaishi.cn/Article/details/gtaoufveeu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.bjfxy.top/Article/details/gtzfoiuoaj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gttnfvgmgd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.c1oappe.top/Article/details/gtyqcoyawe.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbmjtswnm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.birdmap.top/Article/details/gtsxsexxzi.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.andypj.xyz/Article/details/gtrnawmlmr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ppjwa.cn/Article/details/gtxyzeefsw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.quarkkingdee.top/Article/details/gtfvlhftbu.html

[F05] 判断文件或目录是否存在
来源：http://dali.yonumen.top/Article/details/gtvinnzvbr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ywan-chungtsiang.top/Article/details/gthvmpoddi.html

PHP:  file_exists("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtgywuqyxl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpaowauyz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gtzhvpjkhh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gtgcmgnhit.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sysykeji.top/Article/details/gtqwrttkaj.html

Ruby: File.exist?("a.txt")
来源：http://dali.zycfv.cn/Article/details/gturfecwzj.html

C#:   File.Exists("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtcovrvjyw.html

[F06] 删除文件
来源：http://dali.cashguo.top/Article/details/gtaqsoqkqq.html

Py:   os.remove("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtknkizgkd.html

PHP:  unlink("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtjrjazfgn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtmhdhubmn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gtwqfqmcit.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtrmhhhlca.html

Go:   os.Remove("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbhifxflx.html

Ruby: File.delete("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtlysuudkk.html

C#:   File.Delete("a.txt");
来源：http://dali.hammf.cn/Article/details/gthtpsathr.html

[F07] 创建目录（含多级）
来源：http://dali.xylfe.cn/Article/details/gtcyrmxztb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqgmlpzxe.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhengqikj.top/Article/details/gtkrpgzkax.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hammf.cn/Article/details/gtjndjocvu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hywenlv.cn/Article/details/gtgmilyaqr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.havefunace.top/Article/details/gtrujarono.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.bjfxy.top/Article/details/gtisjqaomi.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.9152youxi.cn/Article/details/gtrhgcmgic.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yj202588.top/Article/details/gtpydqfdsn.html

[F08] 遍历目录
来源：http://dali.zhengqikj.top/Article/details/gttnsuwyul.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hfpthk.cn/Article/details/gtmfmzubap.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yongpay.top/Article/details/gtybyvvfvn.html

JS:   fs.readdirSync("dir")
来源：http://dali.kuanghao11.cn/Article/details/gtrpmgaaqd.html

TS:   fs.readdirSync("dir")
来源：http://dali.shzxlz.cn/Article/details/gtvfcxfdrj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.andypj.xyz/Article/details/gtyjuxfdti.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.dianchejie.cn/Article/details/gtbxblhvry.html

Ruby: Dir.children("dir")
来源：http://dali.hfpthk.cn/Article/details/gtiokwdkmu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.bjfxy.top/Article/details/gtfmqebdgz.html

[F09] 获取文件大小
来源：http://dali.yvedp.cn/Article/details/gtzipqjbkv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtkogtklww.html

PHP:  filesize("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtlvigoujb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.quarkkingdee.top/Article/details/gtsixkymbu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cashguo.top/Article/details/gtzdmcetjw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gttmjwnrss.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ybcxt.top/Article/details/gtyubukhyr.html

Ruby: File.size("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtwljiofvh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinghuilouyu.cn/Article/details/gtkvcqrhhb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yonumen.top/Article/details/gtcejexrlg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtdifcfonl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtayxwskos.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtfnhhsrwu.html

TS:   path.extname("a.txt")
来源：http://dali.c1oappe.top/Article/details/gttgjazqep.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhongyouzk.top/Article/details/gtpjzbpeyx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtagptjsku.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtreknxszo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtextxaukp.html

[F11] 复制与移动文件
来源：http://dali.sysykeji.top/Article/details/gtktahjlmh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtvqqslhro.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.pycfn.com/Article/details/gtqbbfbnbw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gthlkfexzu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gtogcoomui.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hnqzz.top/Article/details/gtqmeoknct.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yangfankeji.com/Article/details/gtwnzvicqu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gttwbxkzmq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cucudq.cn/Article/details/gtbrqfnkzj.html

[F12] CSV 读写
来源：http://dali.jinqigufen.top/Article/details/gtgmkbzrzj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gtxdsdrbur.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.bjfxy.top/Article/details/gtukmhlurj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinqigfzy.top/Article/details/gttewxqoct.html

TS:   // 同上
来源：http://dali.dashuyun.cn/Article/details/gtgdboiark.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tanke756.top/Article/details/gtvmkyccxz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.chenjidiqi.icu/Article/details/gtgkbmjpba.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yuxming.cn/Article/details/gtxivcbxmd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.vqdsnc.cn/Article/details/gtpfazccps.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtkidscyjm.html

G. 面向对象
来源：http://dali.ydzc1.top/Article/details/gtlrkmgepm.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtlwukbmhe.html

[G01] 定义类
来源：http://dali.iojbl.cn/Article/details/gtcxivewtn.html

Py:   class User: pass
来源：http://dali.snrcjt.cn/Article/details/gtwtzeeujg.html

PHP:  class User {}
来源：http://dali.aizwys.cn/Article/details/gteecgoddl.html

JS:   class User {}
来源：http://dali.dashuyun.cn/Article/details/gtqhtmwgjw.html

TS:   class User { name: string = ""; }
来源：http://dali.gogol.net.cn/Article/details/gtesowjdpg.html

Java: class User {}
来源：http://dali.birdmap.top/Article/details/gtdkszrmnn.html

Go:   type User struct { Name string }
来源：http://dali.snrcjt.cn/Article/details/gtbrclodnx.html

Ruby: class User; end
来源：http://dali.ivvv.top/Article/details/gttpcrsiry.html

C#:   class User {}
来源：http://dali.gaohongyu789.top/Article/details/gtfrwbpdwm.html

[G02] 构造函数
来源：http://dali.yvedp.cn/Article/details/gtgcampsyo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.redwolf501.top/Article/details/gtpyaugvjp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.andypj.xyz/Article/details/gttfmkybai.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hysaishi.cn/Article/details/gtfxhcnodn.html

TS:   constructor(public name: string) {}
来源：http://dali.jqgfzy.top/Article/details/gtlkjkjtaz.html

Java: User(String name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gtibniygca.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttmygbmho.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.wangdashe.top/Article/details/gtkpignhar.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gogol.net.cn/Article/details/gtiqmlbdtz.html

[G03] 实例属性
来源：http://dali.gotoacloud.top/Article/details/gtpsxbhpyl.html

Py:   self.name = "x"
来源：http://dali.jinghuilouyu.cn/Article/details/gtxrztxhmv.html

PHP:  public string $name = "x";
来源：http://dali.fengsongda.top/Article/details/gtzurihdwe.html

JS:   this.name = "x";
来源：http://dali.jqgufenzy.top/Article/details/gtljabdmim.html

TS:   name: string = "x";
来源：http://dali.jianghu66.top/Article/details/gtwimipgnb.html

Java: private String name;
来源：http://dali.smart0.xyz/Article/details/gtnnstaqds.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.redwolf501.top/Article/details/gtcqgbttbw.html

Ruby: @name = "x"
来源：http://dali.fzhhl.top/Article/details/gtalzlhdrs.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.aizwys.cn/Article/details/gthvznrrzs.html

[G04] 定义方法
来源：http://dali.9152youxi.cn/Article/details/gtepnepamo.html

Py:   def greet(self): return self.name
来源：http://dali.sxryk.cn/Article/details/gtbmqtdnsq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gtowexflmp.html

JS:   greet() { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gtvonitqyf.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuogunsap.html

Java: String greet() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gtthzbwxwr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzqekqdtp.html

Ruby: def greet; @name; end
来源：http://dali.tanke756.top/Article/details/gtrdgbjims.html

C#:   public string Greet() => Name;
来源：http://dali.aizwys.cn/Article/details/gtjggqdsav.html

[G05] 继承
来源：http://dali.aibaodan.cn/Article/details/gtqmevenxn.html

Py:   class Admin(User): pass
来源：http://dali.chenjidiqi.icu/Article/details/gtoistmsqx.html

PHP:  class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gtonjnvxzx.html

JS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtjkwwiwlt.html

TS:   class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gtujbyijhq.html

Java: class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtmloydwhj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jlsjyb.cn/Article/details/gtuxesfjao.html

Ruby: class Admin < User; end
来源：http://dali.xylfe.cn/Article/details/gtskjnurye.html

C#:   class Admin : User {}
来源：http://dali.hysaishi.cn/Article/details/gttbimxnog.html

[G06] 重写方法
来源：http://dali.yanxiufei.cn/Article/details/gtncdpmked.html

Py:   def greet(self): return "admin"
来源：http://dali.bjfxy.top/Article/details/gthcsisjbk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gtpqnrbgwz.html

JS:   greet() { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gtrkksowjz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gtyvmexkjo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtgozchavh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shangyingyoupin.top/Article/details/gtzixtggvn.html

Ruby: def greet; "admin"; end
来源：http://dali.gaohongyu789.top/Article/details/gttikaujsj.html

C#:   public override string Greet() => "admin";
来源：http://dali.birdmap.top/Article/details/gtdglqpamg.html

[G07] 调用父类方法
来源：http://dali.dianchejie.cn/Article/details/gtzazvuzso.html

Py:   super().greet()
来源：http://dali.sweek.top/Article/details/gtyghiveri.html

PHP:  parent::greet();
来源：http://dali.shuidangran.top/Article/details/gtaopezfrl.html

JS:   super.greet();
来源：http://dali.xuanzx.com/Article/details/gtvjyzifmk.html

TS:   super.greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtpezlsnqo.html

Java: super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gtwkouckcc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hnxiangtu.top/Article/details/gtxgqdniue.html

Ruby: super
来源：http://dali.cucudq.cn/Article/details/gtxgmokrbb.html

C#:   base.Greet();
来源：http://dali.fengsongda.top/Article/details/gtityowvft.html

[G08] 静态方法与属性
来源：http://dali.gzhubu.top/Article/details/gtmbpsyyku.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqkkhgrad.html

PHP:  public static function f() {}
来源：http://dali.aibaodan.cn/Article/details/gtcauyoltu.html

JS:   static f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtocdyyary.html

TS:   static f(): void {}
来源：http://dali.jqgfzy.top/Article/details/gtdogwstoy.html

Java: static void f() {}
来源：http://dali.hysaishi.cn/Article/details/gtfqetjyuy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.aizwys.cn/Article/details/gtgjbmwkcl.html

Ruby: def self.f; end
来源：http://dali.ydzc1.top/Article/details/gtfqtqyapn.html

C#:   public static void F() {}
来源：http://dali.cqqwz.cn/Article/details/gtxaulvwii.html

[G09] 接口 / 抽象类
来源：http://dali.andypj.xyz/Article/details/gtenapgvel.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.andypj.xyz/Article/details/gtbpwxoksh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sysykeji.top/Article/details/gtciziedrp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinyuanbaomall.cn/Article/details/gthluykixi.html

TS:   interface Shape { area(): number; }
来源：http://dali.hongshengwenyu.top/Article/details/gtthcucrrp.html

Java: interface Shape { double area(); }
来源：http://dali.fzhhl.top/Article/details/gtufndvzue.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yanxiufei.cn/Article/details/gtecfrsogg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.svipenyu.cn/Article/details/gtwqrlyfwg.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtwweffemj.html

[G10] 访问控制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsnlmbcjk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.dianchejie.cn/Article/details/gtzimqnvpp.html

PHP:  public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gtbkzwhfmw.html

JS:   #private 字段；其余公开
来源：http://dali.jinqigfzy.top/Article/details/gteddubsdu.html

TS:   public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gthlljewzl.html

Java: public / protected / private / 默认包级
来源：http://dali.havefunace.top/Article/details/gtxsgxrbbu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sweek.top/Article/details/gtektvvyqx.html

Ruby: public / protected / private
来源：http://dali.havefunace.top/Article/details/gtptigqdyq.html

C#:   public / protected / private / internal
来源：http://dali.yj20258.top/Article/details/gtcealgqvx.html

[G11] getter / setter
来源：http://dali.shzxlz.cn/Article/details/gtpymsgrlp.html

Py:   @property 与 @x.setter
来源：http://dali.jinqigufen.top/Article/details/gtehphphrb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtrthivuzf.html

JS:   get name() { return this._name; }
来源：http://dali.kuanghao11.cn/Article/details/gtwkevscvb.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhoulong.xyz/Article/details/gtatdlkcsk.html

Java: public String getName() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtuopfsnof.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtydtljxsy.html

Ruby: attr_accessor :name
来源：http://dali.jinqigufen.top/Article/details/gtamsokxov.html

C#:   public string Name { get; set; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtycwebshd.html

[G12] 对象转字符串
来源：http://dali.dianchejie.cn/Article/details/gtrjzroqco.html

Py:   def __str__(self): return self.name
来源：http://dali.quarkkingdee.top/Article/details/gtsuwtvwkf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.vqdsnc.cn/Article/details/gtrkdqtkgl.html

JS:   toString() { return this.name; }
来源：http://dali.sweek.top/Article/details/gtzdetdmlo.html

TS:   toString(): string { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gtvvwzssxd.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtjawxagvg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gtibvqyxfd.html

Ruby: def to_s; @name; end
来源：http://dali.birdmap.top/Article/details/gtotanslkb.html

C#:   public override string ToString() => Name;
来源：http://dali.meibo888.top/Article/details/gtptgbfzpi.html

[G13] 判断对象类型
来源：http://dali.bjfxy.top/Article/details/gtwtnjwqnt.html

Py:   isinstance(u, User)
来源：http://dali.ppjwa.cn/Article/details/gtofngogih.html

PHP:  $u instanceof User
来源：http://dali.ydzc1.top/Article/details/gtdsnemhsv.html

JS:   u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gtgahjaeoa.html

TS:   u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtekhfnhwp.html

Java: u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtbdbymuuj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sxryk.cn/Article/details/gtoqddyghf.html

Ruby: u.is_a?(User)
来源：http://dali.wangdashe.top/Article/details/gtymvdutab.html

C#:   u is User
来源：http://dali.9152youxi.cn/Article/details/gtxfqoagrp.html

[G14] 数据类 / record
来源：http://dali.0kj1m.cn/Article/details/gtyzpcmjtw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gzhubu.top/Article/details/gtxyctvlds.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nwbrower.top/Article/details/gtnmezvplw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.smart0.xyz/Article/details/gtdsmqgtxa.html


<!-- 参考信息 -->