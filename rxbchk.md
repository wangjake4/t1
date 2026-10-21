代发 wailian999

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhongyouzk.top/Article/details/gtpsrzaycp.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.guannengcc.top/Article/details/gtxhwxoojf.html

[E16] 数字千分位
来源：http://dali.xziqi.cn/Article/details/gtlapxcxqh.html

Py:   f"{1234567:,}"
来源：http://dali.vqdsnc.cn/Article/details/gtdrccibcv.html

PHP:  number_format(1234567);
来源：http://dali.xziqi.cn/Article/details/gtgvtnyogj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuxming.cn/Article/details/gtdeoqzdnt.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.meibo888.top/Article/details/gtdcecnvlv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.316326.xyz/Article/details/gttalugpgf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yanxiufei.cn/Article/details/gtrtpngeqp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cheryme.top/Article/details/gttrgxhnti.html

C#:   1234567.ToString("N0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwfabqogd.html

[E17] 首字母大写
来源：http://dali.yueranfly.top/Article/details/gtlbifwxql.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtakcxqrcp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.haohaochexian.top/Article/details/gtvmmzujwx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnqzz.top/Article/details/gtrlfcswzt.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvienzklf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hywenlv.cn/Article/details/gtackagfvk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.aizwys.cn/Article/details/gthpgicczl.html

Ruby: s.capitalize
来源：http://dali.yvedp.cn/Article/details/gtpktkgblm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.tian-w.cn/Article/details/gtzvhgwdra.html

[E18] 模板占位符替换
来源：http://dali.pycfn.com/Article/details/gtfgzghvgh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.snrcjt.cn/Article/details/gtypvozrcw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.daria6918.cn/Article/details/gttgwtmzeu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gtrtevhbrq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gtneeganrs.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gtdurjitem.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gtpwrpqmzr.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hnqzz.top/Article/details/gtfatneuij.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.haohaochexian.top/Article/details/gtsnwlhcxl.html

[E19] 多行文本按行拆分
来源：http://dali.aibaodan.cn/Article/details/gtubmhpjwe.html

Py:   s.splitlines()
来源：http://dali.wangshuangyany.cn/Article/details/gttsihtcwf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xylfe.cn/Article/details/gttdbutppz.html

JS:   s.split(/\r?\n/)
来源：http://dali.316326.xyz/Article/details/gticupdpbi.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gtetwlrlrz.html

Java: s.lines().toList()
来源：http://dali.yj20258888.top/Article/details/gtwdzmzfjv.html

Go:   strings.Split(s, "\n")
来源：http://dali.xuanzx.com/Article/details/gtzbvdomku.html

Ruby: s.lines
来源：http://dali.hywenlv.cn/Article/details/gtqhphkmlu.html

C#:   s.Split('\n')
来源：http://dali.yongpay.top/Article/details/gtuoujkoih.html

[E20] 判断字符串是否为空
来源：http://dali.jiagoushi.top/Article/details/gtaimjyzca.html

Py:   if not s:
来源：http://dali.wangdashe.top/Article/details/gtjccjkebl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shuidangran.top/Article/details/gtubljimgh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cashguo.top/Article/details/gtmqocoonb.html

TS:   if (s === "") {}
来源：http://dali.vqdsnc.cn/Article/details/gtguklellx.html

Java: if (s.isEmpty()) {}
来源：http://dali.havefunace.top/Article/details/gtrwnkoeof.html

Go:   if s == "" {}
来源：http://dali.redwolf501.top/Article/details/gtoyhvneys.html

Ruby: if s.empty?
来源：http://dali.gaohongyu789.top/Article/details/gthxwkqulb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zdqjudy.top/Article/details/gtjgjcgnwd.html

[E21] 超长截断加省略号
来源：http://dali.snrcjt.cn/Article/details/gtapqalpgc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinqigufen.top/Article/details/gtakpvdhkk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gtwnumgjss.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtbbsbwuio.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gtlebdpimt.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gtypbwpgge.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.quarkkingdee.top/Article/details/gtibvdswkf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gthxbdqape.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sxryk.cn/Article/details/gtcdiyrruv.html

[E22] 字节长度与字符长度
来源：http://dali.ehwqpu.com/Article/details/gteidtvigg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtzwwdhhgn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gtwakbmcxp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuanzhike.top/Article/details/gtknzptqqz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gtxxmtkhta.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jqgufenzy.top/Article/details/gttvcvqtzq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.smart0.xyz/Article/details/gtymawyrae.html

Ruby: s.bytesize;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpvhqlokj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhoulong.xyz/Article/details/gtkqhriyld.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtpacatkkr.html

F. 文件与目录
来源：http://dali.ivvv.top/Article/details/gtecpkbilr.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtdhvmdmrb.html

[F01] 读取整个文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtspxkofvf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hammf.cn/Article/details/gtsdwjaoqx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtmjbzqdfl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.redwolf501.top/Article/details/gtmfxzabiu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yonumen.top/Article/details/gtgwxzbtdk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gttcpgskyr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.0kj1m.cn/Article/details/gtqwezpvze.html

Ruby: File.read("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtaazhgazr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ivvv.top/Article/details/gtqupaqfgo.html

[F02] 逐行读取文件
来源：http://dali.hongshengwenyu.top/Article/details/gtpotisskc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinghuilouyu.cn/Article/details/gtsxnqjslk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ybcxt.top/Article/details/gtvpzgrhkq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.iojbl.cn/Article/details/gtgwyektlq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jianghu66.top/Article/details/gtkergmolz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yvedp.cn/Article/details/gtcvphocuh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hywenlv.cn/Article/details/gtodxsphvt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinqigufen.top/Article/details/gturlqauun.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.chenlongwang.top/Article/details/gttbdptazg.html

[F03] 写入文件（覆盖）
来源：http://dali.redwolf501.top/Article/details/gtjfabunpn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.daxiang520.top/Article/details/gtlbbqpssy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gaohongyu789.top/Article/details/gtifreomqx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenjidiqi.icu/Article/details/gtnjmwxihe.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gtwmpmqpyj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhengqikj.top/Article/details/gtpcsimwpv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hammf.cn/Article/details/gtwaychklu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sufxvd.cn/Article/details/gtjkmfwuln.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhongyouzk.top/Article/details/gtnrouwxyr.html

[F04] 追加写入文件
来源：http://dali.jlsjyb.cn/Article/details/gttfktkrme.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.kuanghao11.cn/Article/details/gtqtupacwf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhiwuduotai.top/Article/details/gtcklpqdcb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuxming.cn/Article/details/gtauvaisbx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cqqwz.cn/Article/details/gtfzkttvqy.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nanxinkj.top/Article/details/gtursmcxff.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.chenlongwang.top/Article/details/gtbhopsdrr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ydzc1.top/Article/details/gtwutgzxoj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.redwolf501.top/Article/details/gtehrewozl.html

[F05] 判断文件或目录是否存在
来源：http://dali.jyoumei.cn/Article/details/gtghbdjyrm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.daxiang520.top/Article/details/gtyvrskuol.html

PHP:  file_exists("a.txt");
来源：http://dali.cashguo.top/Article/details/gtzytbqwsw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtlksaxlqw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtadelugjr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gtvmgcrwod.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.kuanghao11.cn/Article/details/gtzjivtukf.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj20258.top/Article/details/gtvdvvdtld.html

C#:   File.Exists("a.txt")
来源：http://dali.ydzc1.top/Article/details/gttuotyiqx.html

[F06] 删除文件
来源：http://dali.daria6918.cn/Article/details/gtpihjnaln.html

Py:   os.remove("a.txt")
来源：http://dali.sweek.top/Article/details/gtynioywem.html

PHP:  unlink("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtfxehvmfy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtebtyjuzq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtvlxpqbvm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gthxujkhhj.html

Go:   os.Remove("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtzltyifpw.html

Ruby: File.delete("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtntjloxni.html

C#:   File.Delete("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtpgngfdhu.html

[F07] 创建目录（含多级）
来源：http://dali.cashguo.top/Article/details/gtbdmcqfxk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sxryk.cn/Article/details/gtgqxenbql.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shangyingyoupin.top/Article/details/gtnuahjbso.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tian-w.cn/Article/details/gtlhldhtee.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuanzhike.top/Article/details/gtcijytdpn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jianghu66.top/Article/details/gtwgkpoilc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlnwtufxi.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gtzqgltsfo.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.fengsongda.top/Article/details/gthauicreo.html

[F08] 遍历目录
来源：http://dali.wangdashe.top/Article/details/gttafwnvkx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xuanzx.com/Article/details/gtnuayjcul.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yongpay.top/Article/details/gtdaaasevs.html

JS:   fs.readdirSync("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtckvkzoem.html

TS:   fs.readdirSync("dir")
来源：http://dali.hnqzz.top/Article/details/gthwkbtmla.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hywenlv.cn/Article/details/gtytxlbjyl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtjvvraqxr.html

Ruby: Dir.children("dir")
来源：http://dali.mhx1999.top/Article/details/gtohaazpip.html

C#:   Directory.GetFiles("dir")
来源：http://dali.dianchejie.cn/Article/details/gtyzlqljhs.html

[F09] 获取文件大小
来源：http://dali.yonumen.top/Article/details/gthtkvlbkj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gteouppbmh.html

PHP:  filesize("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtcspiafsi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jqgufenzy.top/Article/details/gtkkvwnvsf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.havefunace.top/Article/details/gtevopmiql.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gtbcjzqpmf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yueranfly.top/Article/details/gtpwpjdmty.html

Ruby: File.size("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtjrizluns.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.pycfn.com/Article/details/gtcfdffpcp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jianghu66.top/Article/details/gtpqlmuybo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtgddhjyyr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtcbaltggi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtcjgzoadl.html

TS:   path.extname("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtlznhhaky.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cqqwz.cn/Article/details/gtdhrkhgpu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtcdiooucj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtreslwlkq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtrpkvqenk.html

[F11] 复制与移动文件
来源：http://dali.shangyingyoupin.top/Article/details/gtinbycodm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gtzmvsgezr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hammf.cn/Article/details/gtieovgbbm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtjeilycft.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtuidfqmwi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.wangdashe.top/Article/details/gtklzhnioy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gtfmhesdbc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gttrnijksf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jqgfzy.top/Article/details/gtvpovsees.html

[F12] CSV 读写
来源：http://dali.tianlin.xyz/Article/details/gttenbacoc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gogol.net.cn/Article/details/gtqngjekjp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.wangdashe.top/Article/details/gtobygjpkv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hywenlv.cn/Article/details/gtucvihbby.html

TS:   // 同上
来源：http://dali.yonumen.top/Article/details/gtwtwalzax.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nwbrower.top/Article/details/gtmoyoczla.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sweek.top/Article/details/gtgsfrmtdx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.smart0.xyz/Article/details/gtlhnyluft.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xuanzx.com/Article/details/gtaxwbtfsy.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtbplgbtow.html

G. 面向对象
来源：http://dali.aizwys.cn/Article/details/gtmcwrmcjr.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtfkhrtcwd.html

[G01] 定义类
来源：http://dali.svipenyu.cn/Article/details/gtjxlthejv.html

Py:   class User: pass
来源：http://dali.jinqigfzy.top/Article/details/gttkmzqzye.html

PHP:  class User {}
来源：http://dali.dashuyun.cn/Article/details/gtgwkrydgr.html

JS:   class User {}
来源：http://dali.yj20258.top/Article/details/gtyzzrhupm.html

TS:   class User { name: string = ""; }
来源：http://dali.cqqwz.cn/Article/details/gtbalculom.html

Java: class User {}
来源：http://dali.aibaodan.cn/Article/details/gtzeujzzcd.html

Go:   type User struct { Name string }
来源：http://dali.iojbl.cn/Article/details/gtfyecosgt.html

Ruby: class User; end
来源：http://dali.sufxvd.cn/Article/details/gtigioomwf.html

C#:   class User {}
来源：http://dali.zhoulong.xyz/Article/details/gtuopzitbf.html

[G02] 构造函数
来源：http://dali.tianlin.xyz/Article/details/gtrzjynlym.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jlsjyb.cn/Article/details/gtcxdaxofo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jyoumei.cn/Article/details/gtlxzzzyrc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.birdmap.top/Article/details/gtjsgsjxji.html

TS:   constructor(public name: string) {}
来源：http://dali.yanxiufei.cn/Article/details/gtosgbtehx.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenlongwang.top/Article/details/gtrqosjhtu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jiagoushi.top/Article/details/gtjrbtxhyq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jqgufenzy.top/Article/details/gtveegkmya.html

C#:   public User(string name) { Name = name; }
来源：http://dali.fengsongda.top/Article/details/gtvudfdnsm.html

[G03] 实例属性
来源：http://dali.birdmap.top/Article/details/gtgpnnjlqh.html

Py:   self.name = "x"
来源：http://dali.yj20258888.top/Article/details/gtscpjdrvi.html

PHP:  public string $name = "x";
来源：http://dali.sweek.top/Article/details/gtqbrrwcyu.html

JS:   this.name = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gtrcjtbttg.html

TS:   name: string = "x";
来源：http://dali.aizwys.cn/Article/details/gtzvobmzal.html

Java: private String name;
来源：http://dali.xziqi.cn/Article/details/gtprolnxxu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gaohongyu789.top/Article/details/gtcyifvacb.html

Ruby: @name = "x"
来源：http://dali.bjfxy.top/Article/details/gtexlaedfq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xylfe.cn/Article/details/gttnwekiok.html

[G04] 定义方法
来源：http://dali.zhoulong.xyz/Article/details/gtmybjgirs.html

Py:   def greet(self): return self.name
来源：http://dali.mhx1999.top/Article/details/gtxgvydyga.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yueranfly.top/Article/details/gtskubsowm.html

JS:   greet() { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gtdftanjig.html

TS:   greet(): string { return this.name; }
来源：http://dali.ivvv.top/Article/details/gtfrahxtpr.html

Java: String greet() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbdjovxxp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gtgtdaxtgq.html

Ruby: def greet; @name; end
来源：http://dali.jlsjyb.cn/Article/details/gtbzmwljfu.html

C#:   public string Greet() => Name;
来源：http://dali.zhoulong.xyz/Article/details/gtjdghzzht.html

[G05] 继承
来源：http://dali.pycfn.com/Article/details/gtkjufpgcr.html

Py:   class Admin(User): pass
来源：http://dali.meibo888.top/Article/details/gtogvknxti.html

PHP:  class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gttzyqehmk.html

JS:   class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtmnusqpjf.html

TS:   class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdgyoqzdz.html

Java: class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gtgevabdgt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhengqikj.top/Article/details/gtlwielsjz.html

Ruby: class Admin < User; end
来源：http://dali.yvedp.cn/Article/details/gttffifxuc.html

C#:   class Admin : User {}
来源：http://dali.yuanzhike.top/Article/details/gtozfjveni.html

[G06] 重写方法
来源：http://dali.xuanzx.com/Article/details/gtyluqszrv.html

Py:   def greet(self): return "admin"
来源：http://dali.sweek.top/Article/details/gtqhoozewm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gttvzgcqmw.html

JS:   greet() { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gtzgbosngq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbebnykah.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtcgpudbis.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.birdmap.top/Article/details/gtwhbqniuo.html

Ruby: def greet; "admin"; end
来源：http://dali.wangshuangyany.cn/Article/details/gtdidumvnd.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhixingplan.top/Article/details/gtuohpiyle.html

[G07] 调用父类方法
来源：http://dali.gaohongyu789.top/Article/details/gtcusawquw.html

Py:   super().greet()
来源：http://dali.xuanzx.com/Article/details/gtznaslyif.html

PHP:  parent::greet();
来源：http://dali.vqdsnc.cn/Article/details/gtnwdkclii.html

JS:   super.greet();
来源：http://dali.0kj1m.cn/Article/details/gtxnqqpysv.html

TS:   super.greet();
来源：http://dali.cucudq.cn/Article/details/gtkqccdpli.html

Java: super.greet();
来源：http://dali.sxryk.cn/Article/details/gtdfxrfvoo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtopzojbag.html

Ruby: super
来源：http://dali.ehwqpu.com/Article/details/gtliukhhoz.html

C#:   base.Greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrmmmsyhl.html

[G08] 静态方法与属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrjnwcpwx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yanxiufei.cn/Article/details/gtirwekibp.html

PHP:  public static function f() {}
来源：http://dali.meibo888.top/Article/details/gtcubrdegv.html

JS:   static f() {}
来源：http://dali.hnxiangtu.top/Article/details/gtwmzkynpk.html

TS:   static f(): void {}
来源：http://dali.daria6918.cn/Article/details/gtpsoohzwk.html

Java: static void f() {}
来源：http://dali.hammf.cn/Article/details/gtwpquyifo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj20258888.top/Article/details/gtdczgcrzn.html

Ruby: def self.f; end
来源：http://dali.wangdashe.top/Article/details/gtrcxwtjed.html

C#:   public static void F() {}
来源：http://dali.iojbl.cn/Article/details/gtqlylvqfy.html

[G09] 接口 / 抽象类
来源：http://dali.shangyingyoupin.top/Article/details/gtarujeqpg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj202588.top/Article/details/gtfpggwdma.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtivvvlnkr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gogol.net.cn/Article/details/gtoffkgupz.html

TS:   interface Shape { area(): number; }
来源：http://dali.cdnleiting.top/Article/details/gtxjqzygjk.html

Java: interface Shape { double area(); }
来源：http://dali.jianghu66.top/Article/details/gtlczkwuuv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cheryme.top/Article/details/gtgfqfbkdd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hnxiangtu.top/Article/details/gthrrkcodh.html

C#:   interface IShape { double Area(); }
来源：http://dali.andypj.xyz/Article/details/gtgzoobfzl.html

[G10] 访问控制
来源：http://dali.yanxiufei.cn/Article/details/gtiprghlps.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hammf.cn/Article/details/gtoaslhmsm.html

PHP:  public / protected / private
来源：http://dali.zycfv.cn/Article/details/gtxxhvteet.html

JS:   #private 字段；其余公开
来源：http://dali.cheryme.top/Article/details/gtrgqaxyum.html

TS:   public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gtljxvktwh.html

Java: public / protected / private / 默认包级
来源：http://dali.yongpay.top/Article/details/gtngylvvui.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.pycfn.com/Article/details/gttssxuxyo.html

Ruby: public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gtnzoyqwzw.html

C#:   public / protected / private / internal
来源：http://dali.jinqigufen.top/Article/details/gtjgqvuhwj.html

[G11] getter / setter
来源：http://dali.hysaishi.cn/Article/details/gtzyctwzvz.html

Py:   @property 与 @x.setter
来源：http://dali.haohaochexian.top/Article/details/gtfrzdftvo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gtxbhgllhq.html

JS:   get name() { return this._name; }
来源：http://dali.zhixingplan.top/Article/details/gtcdkahkkv.html

TS:   get name(): string { return this._name; }
来源：http://dali.nwbrower.top/Article/details/gtiuexeprt.html

Java: public String getName() { return name; }
来源：http://dali.gzhubu.top/Article/details/gtszspouyi.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gteqdoratz.html

Ruby: attr_accessor :name
来源：http://dali.zhixingplan.top/Article/details/gtkpzjocrd.html

C#:   public string Name { get; set; }
来源：http://dali.zhengqikj.top/Article/details/gtbemlbrcv.html

[G12] 对象转字符串
来源：http://dali.yanxiufei.cn/Article/details/gtieuksjwk.html

Py:   def __str__(self): return self.name
来源：http://dali.hfpthk.cn/Article/details/gtmkzncmhh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gtctmqfyqh.html

JS:   toString() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gteflmxdav.html

TS:   toString(): string { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtxmajaqdt.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhixingplan.top/Article/details/gtuotoawkw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gtsuizqbwx.html

Ruby: def to_s; @name; end
来源：http://dali.ydzc1.top/Article/details/gtobpzjrpm.html

C#:   public override string ToString() => Name;
来源：http://dali.aizwys.cn/Article/details/gtaojdbmiz.html

[G13] 判断对象类型
来源：http://dali.pengpengdd.cyou/Article/details/gtyfevezcu.html

Py:   isinstance(u, User)
来源：http://dali.guannengcc.top/Article/details/gtxipptzvb.html

PHP:  $u instanceof User
来源：http://dali.sysykeji.top/Article/details/gtecijdybb.html

JS:   u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtlfbirrmh.html

TS:   u instanceof User
来源：http://dali.sxryk.cn/Article/details/gtjsnhvzlj.html

Java: u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtoigekhfs.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sufxvd.cn/Article/details/gthaiipwcd.html

Ruby: u.is_a?(User)
来源：http://dali.pycfn.com/Article/details/gtasfirrch.html

C#:   u is User
来源：http://dali.xziqi.cn/Article/details/gtsznpifrg.html

[G14] 数据类 / record
来源：http://dali.chenzaomai.com/Article/details/gtqycgtzts.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jyoumei.cn/Article/details/gttimbvjcu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.dashuyun.cn/Article/details/gtaavqoqgc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.guannengcc.top/Article/details/gtrpemlizi.html


<!-- 参考信息 -->