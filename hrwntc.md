代发 wailian999

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.tianlin.xyz/Article/details/gtoxzyzvuc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xziqi.cn/Article/details/gtbwypeniv.html

[E16] 数字千分位
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzfeghhto.html

Py:   f"{1234567:,}"
来源：http://dali.aibaodan.cn/Article/details/gtaqdjreov.html

PHP:  number_format(1234567);
来源：http://dali.c1oappe.top/Article/details/gtalagltbs.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.svipenyu.cn/Article/details/gtycuqmsmb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.dashuyun.cn/Article/details/gtdukzbfso.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.tianlin.xyz/Article/details/gtsznoavzs.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.guannengcc.top/Article/details/gtenqdncdc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zycfv.cn/Article/details/gtgjxxsxzb.html

C#:   1234567.ToString("N0")
来源：http://dali.jiagoushi.top/Article/details/gtnavqenmd.html

[E17] 首字母大写
来源：http://dali.ivvv.top/Article/details/gttskttmhl.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.smart0.xyz/Article/details/gtaiggbmfc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yj20258.top/Article/details/gtyrvomhov.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenlongwang.top/Article/details/gtanaohaoc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gtwapcaebt.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xziqi.cn/Article/details/gtmasssvzu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.redwolf501.top/Article/details/gtoyvcdlkw.html

Ruby: s.capitalize
来源：http://dali.meibo888.top/Article/details/gtihcrxbjp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.dashuyun.cn/Article/details/gtihcxdziy.html

[E18] 模板占位符替换
来源：http://dali.guowangkeji.top/Article/details/gtqgtrdies.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.andypj.xyz/Article/details/gthbaqmmbr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.nanxinkj.top/Article/details/gtjhqvines.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gtwrjzmpfu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnndienxc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cheryme.top/Article/details/gtgrsuayll.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.havefunace.top/Article/details/gtlfjyojgy.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.chenjidiqi.icu/Article/details/gtdibxjjvq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.pycfn.com/Article/details/gtvpplivpq.html

[E19] 多行文本按行拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gtvftgijna.html

Py:   s.splitlines()
来源：http://dali.tian-w.cn/Article/details/gtqedmmopu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ppjwa.cn/Article/details/gtojexdnxv.html

JS:   s.split(/\r?\n/)
来源：http://dali.kuanghao11.cn/Article/details/gtbtdafvee.html

TS:   s.split(/\r?\n/)
来源：http://dali.yangfankeji.com/Article/details/gtcvvyhcnh.html

Java: s.lines().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlbfzupda.html

Go:   strings.Split(s, "\n")
来源：http://dali.jianghu66.top/Article/details/gtjxuctwvl.html

Ruby: s.lines
来源：http://dali.ehwqpu.com/Article/details/gtzftfujyj.html

C#:   s.Split('\n')
来源：http://dali.zhongyouzk.top/Article/details/gtzgwcjqfa.html

[E20] 判断字符串是否为空
来源：http://dali.aizwys.cn/Article/details/gtdfwxcfaq.html

Py:   if not s:
来源：http://dali.jianghu66.top/Article/details/gtaecznyau.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.mhx1999.top/Article/details/gtplisyzhy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenlongwang.top/Article/details/gtxbwvqewy.html

TS:   if (s === "") {}
来源：http://dali.shuidangran.top/Article/details/gtsqvwixne.html

Java: if (s.isEmpty()) {}
来源：http://dali.tanke756.top/Article/details/gtuolxsvfs.html

Go:   if s == "" {}
来源：http://dali.jlsjyb.cn/Article/details/gtsxptyepw.html

Ruby: if s.empty?
来源：http://dali.316326.xyz/Article/details/gthsuknfuu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gotoacloud.top/Article/details/gtrobqdvlz.html

[E21] 超长截断加省略号
来源：http://dali.yuxming.cn/Article/details/gtjulblzfc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj202588.top/Article/details/gtxaqrqlnt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrpcjbvlm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gtcoqjyulo.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtlehmoqll.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtvibunitw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.aibaodan.cn/Article/details/gtophttdye.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gtcxfcagbo.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtzfahensc.html

[E22] 字节长度与字符长度
来源：http://dali.yuanzhike.top/Article/details/gtmgxvuzkd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shzxlz.cn/Article/details/gthbbjawvr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gtgxnqewrr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pengpengdd.cyou/Article/details/gtohegyxut.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jiagoushi.top/Article/details/gtvgvlljmk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyktntvcn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xinyue.icu/Article/details/gtxjcyyteu.html

Ruby: s.bytesize;  s.length
来源：http://dali.yvedp.cn/Article/details/gtqpmwespw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.pycfn.com/Article/details/gtjhdkjmto.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gthmdkkrmq.html

F. 文件与目录
来源：http://dali.pengpengdd.cyou/Article/details/gtzyogmubg.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtjorakqri.html

[F01] 读取整个文件
来源：http://dali.shzxlz.cn/Article/details/gtjeomlkmm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cqqwz.cn/Article/details/gtbnfxvolb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtwgdzszbu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.316326.xyz/Article/details/gttmovxjjm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gtpydylacc.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gtueiuecpe.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenzaomai.com/Article/details/gtsmunbsqc.html

Ruby: File.read("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtkfgnaaxr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtujvwgkyz.html

[F02] 逐行读取文件
来源：http://dali.yj202588.top/Article/details/gtyzgmkphx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hnqzz.top/Article/details/gtucstjhzg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xuanzx.com/Article/details/gtkxsidbwd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fzhhl.top/Article/details/gtennfhyzp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tianlin.xyz/Article/details/gttdbbtsnm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.fzhhl.top/Article/details/gtvuypgxdm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yanxiufei.cn/Article/details/gthpxzvpbs.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhoulong.xyz/Article/details/gtukgdwqzb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cheryme.top/Article/details/gtuwrjobav.html

[F03] 写入文件（覆盖）
来源：http://dali.hongshengwenyu.top/Article/details/gtxocdffav.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvwyrmqvn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.pengpengdd.cyou/Article/details/gtxmbyulje.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gttrwrfcss.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xziqi.cn/Article/details/gttzfrzssc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sufxvd.cn/Article/details/gtxqkveyct.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhengqikj.top/Article/details/gtqttwahlp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaybokjmo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gaohongyu789.top/Article/details/gtovarokho.html

[F04] 追加写入文件
来源：http://dali.316326.xyz/Article/details/gttbergfln.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.svipenyu.cn/Article/details/gtsukmveas.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zycfv.cn/Article/details/gtlhvdqrxf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangdashe.top/Article/details/gtqkhpxnag.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hysaishi.cn/Article/details/gttwnefrdx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlgbuzubw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hfpthk.cn/Article/details/gtcocbetjh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.wangdashe.top/Article/details/gtwvtlsvee.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.daria6918.cn/Article/details/gtxlkugfjw.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhoulong.xyz/Article/details/gtiagaezut.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.mhx1999.top/Article/details/gtmlptgkuk.html

PHP:  file_exists("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtctegjlvx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gtfoethipu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtbitxscza.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gtdmszefgg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.guowangkeji.top/Article/details/gtluvuthtb.html

Ruby: File.exist?("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtxwxsdroc.html

C#:   File.Exists("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtgjrtgtvc.html

[F06] 删除文件
来源：http://dali.bjfxy.top/Article/details/gtxysxxhhc.html

Py:   os.remove("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtdivxnobk.html

PHP:  unlink("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtfmxxrwza.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtvqckawvv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtolszhido.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gtbrpgttbw.html

Go:   os.Remove("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtehadwebz.html

Ruby: File.delete("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtpjfkapab.html

C#:   File.Delete("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtfmkxofjx.html

[F07] 创建目录（含多级）
来源：http://dali.yvedp.cn/Article/details/gtilunwfjr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jiagoushi.top/Article/details/gtyrjykqry.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shzxlz.cn/Article/details/gtpyfycdms.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jlsjyb.cn/Article/details/gtdbybqnpe.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhoulong.xyz/Article/details/gtwzxctdne.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhiwuduotai.top/Article/details/gtltxsukwy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ydzc1.top/Article/details/gtkejnlycr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.dashuyun.cn/Article/details/gtumuyqzlt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hongshengwenyu.top/Article/details/gtcjmszmks.html

[F08] 遍历目录
来源：http://dali.havefunace.top/Article/details/gtznxpmanz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.guannengcc.top/Article/details/gtnklahlud.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.0kj1m.cn/Article/details/gtowomyhue.html

JS:   fs.readdirSync("dir")
来源：http://dali.dashuyun.cn/Article/details/gtgbbhmzyr.html

TS:   fs.readdirSync("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtxxnbaash.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.daxiang520.top/Article/details/gtjvntgmur.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrgszgtgk.html

Ruby: Dir.children("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gtkqkemigy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jianghu66.top/Article/details/gtdvgnlxao.html

[F09] 获取文件大小
来源：http://dali.nanxinkj.top/Article/details/gtxhzsbgbz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtwhvhabjr.html

PHP:  filesize("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtxarxopfw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ivvv.top/Article/details/gtyorvlsrf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenjidiqi.icu/Article/details/gtuhxmxwuu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gtxqnmieyi.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.c1oappe.top/Article/details/gtyjzttcxw.html

Ruby: File.size("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtbabshyau.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xuanzx.com/Article/details/gtugfrxhur.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinghuilouyu.cn/Article/details/gtcprvhwlp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttsdzkzpy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtuascypmx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtzkvplftd.html

TS:   path.extname("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtmbqebhfc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hnxiangtu.top/Article/details/gtueyqetyv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gticxmscze.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtbveprtxb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gttnivwenn.html

[F11] 复制与移动文件
来源：http://dali.cqqwz.cn/Article/details/gtuwlicraq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvidxzxyn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yj202588.top/Article/details/gtngurlpaw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gtrhlqgdqn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtuzdvwuii.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cucudq.cn/Article/details/gtkqirnahe.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.wangdashe.top/Article/details/gtuibdondx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gtaagvajmi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtidremvxp.html

[F12] CSV 读写
来源：http://dali.havefunace.top/Article/details/gtlutpemkr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cheryme.top/Article/details/gtjwqxevmc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.316326.xyz/Article/details/gtqaqefdpb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hnxiangtu.top/Article/details/gtafbukneq.html

TS:   // 同上
来源：http://dali.nanxinkj.top/Article/details/gtsbcuxnbj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.daria6918.cn/Article/details/gtjqxdemhf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zycfv.cn/Article/details/gtnhortqvt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxdxxszfr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hywenlv.cn/Article/details/gtrtwjyvyw.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtrvwoagxb.html

G. 面向对象
来源：http://dali.hammf.cn/Article/details/gtuvpcucrv.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtbpdtaswp.html

[G01] 定义类
来源：http://dali.shanyushiyangkeji.top/Article/details/gtamvlomxr.html

Py:   class User: pass
来源：http://dali.shanyushiyangtech.top/Article/details/gtvkseuxqo.html

PHP:  class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtfutzcsau.html

JS:   class User {}
来源：http://dali.smart0.xyz/Article/details/gtfqwnxfvm.html

TS:   class User { name: string = ""; }
来源：http://dali.yuanzhike.top/Article/details/gtunegkqni.html

Java: class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtuuymxony.html

Go:   type User struct { Name string }
来源：http://dali.birdmap.top/Article/details/gtgdujokch.html

Ruby: class User; end
来源：http://dali.xylfe.cn/Article/details/gtxyxkwtjo.html

C#:   class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gthmdkdpvm.html

[G02] 构造函数
来源：http://dali.tanke756.top/Article/details/gtylsneavo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yueranfly.top/Article/details/gtojweskbu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.vqdsnc.cn/Article/details/gtfpgcmbhz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinqigufen.top/Article/details/gtritfbhnf.html

TS:   constructor(public name: string) {}
来源：http://dali.sufxvd.cn/Article/details/gthvuhgmbs.html

Java: User(String name) { this.name = name; }
来源：http://dali.yuanzhike.top/Article/details/gtgrmwjtic.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sysykeji.top/Article/details/gtzgkbqfdg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgpcuuaxr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnhmlbjzh.html

[G03] 实例属性
来源：http://dali.aizwys.cn/Article/details/gtnqpzsslt.html

Py:   self.name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gtyfzvzaif.html

PHP:  public string $name = "x";
来源：http://dali.jiagoushi.top/Article/details/gtxtsucgfh.html

JS:   this.name = "x";
来源：http://dali.sweek.top/Article/details/gttdfsdhyo.html

TS:   name: string = "x";
来源：http://dali.tianlin.xyz/Article/details/gtdscrtwoy.html

Java: private String name;
来源：http://dali.yuanzhike.top/Article/details/gtysoiguqf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gotoacloud.top/Article/details/gtozbjzuiw.html

Ruby: @name = "x"
来源：http://dali.birdmap.top/Article/details/gttkrcntji.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shuidangran.top/Article/details/gtvcdemnxz.html

[G04] 定义方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbrzslmeg.html

Py:   def greet(self): return self.name
来源：http://dali.sxryk.cn/Article/details/gtlkfyuqiz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gtbworwhpr.html

JS:   greet() { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gtnpzvtjji.html

TS:   greet(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtbojalyjz.html

Java: String greet() { return name; }
来源：http://dali.yonumen.top/Article/details/gttohrgtry.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gtwzanxtcb.html

Ruby: def greet; @name; end
来源：http://dali.aizwys.cn/Article/details/gtmolyooey.html

C#:   public string Greet() => Name;
来源：http://dali.pycfn.com/Article/details/gtqovnjnzn.html

[G05] 继承
来源：http://dali.pengpengdd.cyou/Article/details/gtmnwjzwxd.html

Py:   class Admin(User): pass
来源：http://dali.ivvv.top/Article/details/gtbqfboipw.html

PHP:  class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gtszfutfpk.html

JS:   class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gtmnnqqjrf.html

TS:   class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gtjxbzfaxl.html

Java: class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gteebcslwu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hfpthk.cn/Article/details/gtyoszlwnv.html

Ruby: class Admin < User; end
来源：http://dali.9152youxi.cn/Article/details/gtulsfvuaa.html

C#:   class Admin : User {}
来源：http://dali.mhx1999.top/Article/details/gtqvzjbqev.html

[G06] 重写方法
来源：http://dali.yuanzhike.top/Article/details/gtgvqkstfw.html

Py:   def greet(self): return "admin"
来源：http://dali.jyoumei.cn/Article/details/gtxkiglvqm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtolmwoqvw.html

JS:   greet() { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gtgjgzwpft.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtlxevlqbz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtebyyfjht.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinqigufen.top/Article/details/gtfidxiyjq.html

Ruby: def greet; "admin"; end
来源：http://dali.zhixingplan.top/Article/details/gtyjwdltyi.html

C#:   public override string Greet() => "admin";
来源：http://dali.cdnleiting.top/Article/details/gtbwkcwjzp.html

[G07] 调用父类方法
来源：http://dali.xziqi.cn/Article/details/gtdyuquket.html

Py:   super().greet()
来源：http://dali.shzxlz.cn/Article/details/gtblooyxzf.html

PHP:  parent::greet();
来源：http://dali.sufxvd.cn/Article/details/gtlcaltpti.html

JS:   super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gtlockckpg.html

TS:   super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtsmcavwjz.html

Java: super.greet();
来源：http://dali.jlsjyb.cn/Article/details/gtrxmtuwvw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xinyue.icu/Article/details/gtbixfjstu.html

Ruby: super
来源：http://dali.meibo888.top/Article/details/gtgdgnhwma.html

C#:   base.Greet();
来源：http://dali.hammf.cn/Article/details/gtkwxxssiw.html

[G08] 静态方法与属性
来源：http://dali.meibo888.top/Article/details/gtfkukznxq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenlongwang.top/Article/details/gtbfnfiavz.html

PHP:  public static function f() {}
来源：http://dali.tian-w.cn/Article/details/gtluflvgtk.html

JS:   static f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtfuhmepum.html

TS:   static f(): void {}
来源：http://dali.xinyue.icu/Article/details/gtzinyzzpi.html

Java: static void f() {}
来源：http://dali.iojbl.cn/Article/details/gtfqlcwacg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nwbrower.top/Article/details/gtlqicwmex.html

Ruby: def self.f; end
来源：http://dali.tanke756.top/Article/details/gtlynvexof.html

C#:   public static void F() {}
来源：http://dali.yj202588.top/Article/details/gthvkajamx.html

[G09] 接口 / 抽象类
来源：http://dali.jqgufenzy.top/Article/details/gtzvlcorcy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.kuanghao11.cn/Article/details/gtdxkarehm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sxryk.cn/Article/details/gtowvztgcj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.pycfn.com/Article/details/gtovkhenqx.html

TS:   interface Shape { area(): number; }
来源：http://dali.yangfankeji.com/Article/details/gtqzgpgrru.html

Java: interface Shape { double area(); }
来源：http://dali.jiagoushi.top/Article/details/gtlnhvrcgw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cashguo.top/Article/details/gtsufdhdxr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hnqzz.top/Article/details/gtigaqvwqi.html

C#:   interface IShape { double Area(); }
来源：http://dali.yuanzhike.top/Article/details/gtywfjqdmf.html

[G10] 访问控制
来源：http://dali.svipenyu.cn/Article/details/gtfmgvvfty.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hysaishi.cn/Article/details/gtewogcpue.html

PHP:  public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gthczwpane.html

JS:   #private 字段；其余公开
来源：http://dali.xuanzx.com/Article/details/gtlkfdzroj.html

TS:   public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gtbjxojqpv.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigfzy.top/Article/details/gtxpgxjexj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cqqwz.cn/Article/details/gtmckzdcus.html

Ruby: public / protected / private
来源：http://dali.yvedp.cn/Article/details/gtwjwwvboj.html

C#:   public / protected / private / internal
来源：http://dali.ydzc1.top/Article/details/gtiznrrlga.html

[G11] getter / setter
来源：http://dali.xziqi.cn/Article/details/gtmmaoxtrd.html

Py:   @property 与 @x.setter
来源：http://dali.cheryme.top/Article/details/gtxvovkrbe.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gtskpgwycg.html

JS:   get name() { return this._name; }
来源：http://dali.dashuyun.cn/Article/details/gthsroqizc.html

TS:   get name(): string { return this._name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtorbkanul.html

Java: public String getName() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtyzvgvmnn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gtftzegipj.html

Ruby: attr_accessor :name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfwbxcegg.html

C#:   public string Name { get; set; }
来源：http://dali.wangdashe.top/Article/details/gtefdrchnr.html

[G12] 对象转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtursptiql.html

Py:   def __str__(self): return self.name
来源：http://dali.zhoulong.xyz/Article/details/gtrjvqelbx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gtxcwiuivu.html

JS:   toString() { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gtfeycsnue.html

TS:   toString(): string { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnwoxzmhj.html

Java: @Override public String toString() { return name; }
来源：http://dali.tian-w.cn/Article/details/gtfuvgbdvo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gtgnyvodof.html

Ruby: def to_s; @name; end
来源：http://dali.cdnleiting.top/Article/details/gtjjombefe.html

C#:   public override string ToString() => Name;
来源：http://dali.dashuyun.cn/Article/details/gtkaokiqoc.html

[G13] 判断对象类型
来源：http://dali.yanxiufei.cn/Article/details/gtlijenzsv.html

Py:   isinstance(u, User)
来源：http://dali.birdmap.top/Article/details/gtrhwicpyw.html

PHP:  $u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gttzvqytqz.html

JS:   u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gtbehoqyin.html

TS:   u instanceof User
来源：http://dali.pycfn.com/Article/details/gtejsxvmlq.html

Java: u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtxbrmqeuc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.daxiang520.top/Article/details/gtzsbelcic.html

Ruby: u.is_a?(User)
来源：http://dali.snrcjt.cn/Article/details/gtqafctgjd.html

C#:   u is User
来源：http://dali.316326.xyz/Article/details/gtzscgwcuq.html

[G14] 数据类 / record
来源：http://dali.sweek.top/Article/details/gttvkhfnnw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jyoumei.cn/Article/details/gtzlklrhew.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cdnleiting.top/Article/details/gtvaejawqf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hnqzz.top/Article/details/gtauhzzpod.html


<!-- 参考信息 -->