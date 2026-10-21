代发 wailian999

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.chenzaomai.com/Article/details/gtylkkwdcu.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gogol.net.cn/Article/details/gtwvcpcrjd.html

[E16] 数字千分位
来源：http://dali.xuanzx.com/Article/details/gtedrzjurl.html

Py:   f"{1234567:,}"
来源：http://dali.zdqjudy.top/Article/details/gtvjsxxmrh.html

PHP:  number_format(1234567);
来源：http://dali.yvedp.cn/Article/details/gtsobqstgz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ydzc1.top/Article/details/gtuyqxxvwg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tanke756.top/Article/details/gtlbmnklpv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ehwqpu.com/Article/details/gtgjurulnd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnqiaqjac.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sysykeji.top/Article/details/gtanovsbde.html

C#:   1234567.ToString("N0")
来源：http://dali.cashguo.top/Article/details/gthpckfoop.html

[E17] 首字母大写
来源：http://dali.gzhubu.top/Article/details/gtkchwzaqb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbvyrsqyt.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.fengsongda.top/Article/details/gtlktgdvbl.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yanxiufei.cn/Article/details/gtcfmcbaax.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ydzc1.top/Article/details/gtwopqmvil.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.316326.xyz/Article/details/gtiracebvo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhixingplan.top/Article/details/gtsypgfuuo.html

Ruby: s.capitalize
来源：http://dali.jinqigfzy.top/Article/details/gtunzlrvvm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shanyushiyangtech.top/Article/details/gtyygqajdf.html

[E18] 模板占位符替换
来源：http://dali.guannengcc.top/Article/details/gtqfnnkwfs.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhixingplan.top/Article/details/gtlmulfewt.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj202588.top/Article/details/gtrbziubjm.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yonumen.top/Article/details/gtzxwhuelr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj202588.top/Article/details/gtmvhzekps.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gtpqwusxsp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjbajeyuf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ppjwa.cn/Article/details/gtswpffuji.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.fzhhl.top/Article/details/gtqhgwjyqt.html

[E19] 多行文本按行拆分
来源：http://dali.hongshengwenyu.top/Article/details/gthakhvzzw.html

Py:   s.splitlines()
来源：http://dali.c1oappe.top/Article/details/gtdbxqfbqf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cqqwz.cn/Article/details/gtajlrgvlh.html

JS:   s.split(/\r?\n/)
来源：http://dali.gzhubu.top/Article/details/gtdnrrrcfi.html

TS:   s.split(/\r?\n/)
来源：http://dali.jiagoushi.top/Article/details/gtxoawsrse.html

Java: s.lines().toList()
来源：http://dali.dianchejie.cn/Article/details/gtnoxyapbk.html

Go:   strings.Split(s, "\n")
来源：http://dali.wangdashe.top/Article/details/gtmntnlsgu.html

Ruby: s.lines
来源：http://dali.pengpengdd.cyou/Article/details/gtbnemmbao.html

C#:   s.Split('\n')
来源：http://dali.vqdsnc.cn/Article/details/gtycorgzgi.html

[E20] 判断字符串是否为空
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjdygmwrs.html

Py:   if not s:
来源：http://dali.yj20258888.top/Article/details/gtrysvfvtk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gtfgvcxavq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenzaomai.com/Article/details/gtbodbqjws.html

TS:   if (s === "") {}
来源：http://dali.smart0.xyz/Article/details/gtjjenpqun.html

Java: if (s.isEmpty()) {}
来源：http://dali.meibo888.top/Article/details/gttgrleyhw.html

Go:   if s == "" {}
来源：http://dali.yvedp.cn/Article/details/gtgfzfhezu.html

Ruby: if s.empty?
来源：http://dali.tanke756.top/Article/details/gtklfndaem.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yangfankeji.com/Article/details/gtvjvfefdp.html

[E21] 超长截断加省略号
来源：http://dali.fengsongda.top/Article/details/gtoxzhwbzh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tianlin.xyz/Article/details/gtqjltxoki.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gtomtjjqdr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gteqgomraj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gtibtabkfl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtlkrqljtz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gotoacloud.top/Article/details/gtntadxxav.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gtnqzkskuq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtylyheapx.html

[E22] 字节长度与字符长度
来源：http://dali.quarkkingdee.top/Article/details/gtccaaddkf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.mhx1999.top/Article/details/gtrqgkarzf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gtblwwpfzs.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shuidangran.top/Article/details/gtridibozc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yonumen.top/Article/details/gtvqmtpznd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cucudq.cn/Article/details/gtoemcgnvy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinqigufen.top/Article/details/gtgekogiyo.html

Ruby: s.bytesize;  s.length
来源：http://dali.gogol.net.cn/Article/details/gttayfrpda.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shanyushiyangtech.top/Article/details/gtikbkwyak.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtlreubynl.html

F. 文件与目录
来源：http://dali.nanxuanxn.top/Article/details/gtlwsljqur.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtwebzzetj.html

[F01] 读取整个文件
来源：http://dali.nwbrower.top/Article/details/gtpzhclvai.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.316326.xyz/Article/details/gtnpchaurc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtpzgrpnzt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gtdazludic.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.haohaochexian.top/Article/details/gtlhwbugpm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gtwsilukox.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shangyingyoupin.top/Article/details/gtpfvfoumw.html

Ruby: File.read("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtctzypazo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtkanhvobo.html

[F02] 逐行读取文件
来源：http://dali.shangyingyoupin.top/Article/details/gtrcqzmuzp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xuanzx.com/Article/details/gtipkgizsm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.wangdashe.top/Article/details/gtnrrclgie.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aizwys.cn/Article/details/gtmtcuucej.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shzxlz.cn/Article/details/gtdgunxtrw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.chenlongwang.top/Article/details/gtedbmzquo.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gtadipnfqz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ivvv.top/Article/details/gttyknemmq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.fzhhl.top/Article/details/gtqvdqpobr.html

[F03] 写入文件（覆盖）
来源：http://dali.zhoulong.xyz/Article/details/gtpedpxumk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.meibo888.top/Article/details/gtfgvkkrjp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jqgfzy.top/Article/details/gtfapyoqlh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gttclvhggc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gtyxkpowlw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.wangdashe.top/Article/details/gtnushmeet.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ybcxt.top/Article/details/gtrhacafzm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tanke756.top/Article/details/gtoyiaavtv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gogol.net.cn/Article/details/gtrcbhrast.html

[F04] 追加写入文件
来源：http://dali.yanxiufei.cn/Article/details/gthjsmzlmr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gogol.net.cn/Article/details/gtgsqjpgwt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.vqdsnc.cn/Article/details/gtjtnsbjrm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gttnnzthrq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258.top/Article/details/gtqgqxygsx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.0kj1m.cn/Article/details/gtivghpwog.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sweek.top/Article/details/gtdzwxuxni.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinqigfzy.top/Article/details/gtftepwbir.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xziqi.cn/Article/details/gtyfhgessx.html

[F05] 判断文件或目录是否存在
来源：http://dali.smart0.xyz/Article/details/gtndtvdrec.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ivvv.top/Article/details/gtywelquyw.html

PHP:  file_exists("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtzglwsyui.html

JS:   fs.existsSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtazxktwrf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtsshkoarx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gtdmorqgmg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcrzjgmqy.html

Ruby: File.exist?("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtiqjvnsjq.html

C#:   File.Exists("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtgfkhenat.html

[F06] 删除文件
来源：http://dali.fzhhl.top/Article/details/gtzcgecagc.html

Py:   os.remove("a.txt")
来源：http://dali.sweek.top/Article/details/gtggjpnitd.html

PHP:  unlink("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtqjvrsdkh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtmvfszacl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtyaiqqdto.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gtgrnkglgx.html

Go:   os.Remove("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtnoyjsqyo.html

Ruby: File.delete("a.txt")
来源：http://dali.zycfv.cn/Article/details/gttvzczyak.html

C#:   File.Delete("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtyobqszlx.html

[F07] 创建目录（含多级）
来源：http://dali.aizwys.cn/Article/details/gtyecgbgmg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gotoacloud.top/Article/details/gtakgvcioc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.pycfn.com/Article/details/gttohndleo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhengqikj.top/Article/details/gtjgjdkoqc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.birdmap.top/Article/details/gtstpduugs.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shzxlz.cn/Article/details/gtdljyhzga.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jqgufenzy.top/Article/details/gtbtnnfmfq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jiagoushi.top/Article/details/gtlzwdivlz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yuxming.cn/Article/details/gtbdazedru.html

[F08] 遍历目录
来源：http://dali.zhoulong.xyz/Article/details/gtxdaaohaf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sxryk.cn/Article/details/gtpuwhklwr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ivvv.top/Article/details/gtlkjqqfet.html

JS:   fs.readdirSync("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtcacxoqof.html

TS:   fs.readdirSync("dir")
来源：http://dali.nwbrower.top/Article/details/gtoltimaka.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nanxinkj.top/Article/details/gtdgejblkl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenzaomai.com/Article/details/gtzeubszih.html

Ruby: Dir.children("dir")
来源：http://dali.gotoacloud.top/Article/details/gtfogoyucz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.c1oappe.top/Article/details/gtjutyfjgb.html

[F09] 获取文件大小
来源：http://dali.shanyushiyangtech.top/Article/details/gtpfiqtszh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtfowpoxrj.html

PHP:  filesize("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtjjyfjetz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.aizwys.cn/Article/details/gtahqftcmg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.bjfxy.top/Article/details/gtjkohgerj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gtvindsmnk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jqgfzy.top/Article/details/gtwptjztxs.html

Ruby: File.size("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtmtvhtydw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtejpevuxp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tian-w.cn/Article/details/gtdcgwwaox.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtvjnzhsxb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.meibo888.top/Article/details/gtuwdzwxgm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtlvqrhftv.html

TS:   path.extname("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gteywevjaw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xinyue.icu/Article/details/gtfwlxmugo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtihalnrzi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtsofpeqpt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtdeyjzurn.html

[F11] 复制与移动文件
来源：http://dali.snrcjt.cn/Article/details/gtpiomgend.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtnmbcvuag.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jyoumei.cn/Article/details/gticqfzzul.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gtrikrmpuq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtmwfzmvbf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xuanzx.com/Article/details/gtncfivget.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinqigufen.top/Article/details/gtkneipcjt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gtxtrcbjun.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yuanzhike.top/Article/details/gtpnrbgptn.html

[F12] CSV 读写
来源：http://dali.fengsongda.top/Article/details/gtzsshaage.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.meibo888.top/Article/details/gtomdbbdtj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhongyouzk.top/Article/details/gtfggqhhpl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.feifeiyinyue.top/Article/details/gtdwsxsukh.html

TS:   // 同上
来源：http://dali.zhixingplan.top/Article/details/gtxfongfhs.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gogol.net.cn/Article/details/gtzasgtbag.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hywenlv.cn/Article/details/gttdufyhlr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenjidiqi.icu/Article/details/gttcgbviul.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yvedp.cn/Article/details/gtxfmsmtsk.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtwdbvlmww.html

G. 面向对象
来源：http://dali.zhengqikj.top/Article/details/gthqzjqnbh.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtwahemyjt.html

[G01] 定义类
来源：http://dali.sufxvd.cn/Article/details/gtirpvovea.html

Py:   class User: pass
来源：http://dali.kuanghao11.cn/Article/details/gtzhxsagqt.html

PHP:  class User {}
来源：http://dali.sxryk.cn/Article/details/gtxuckdkjh.html

JS:   class User {}
来源：http://dali.ppjwa.cn/Article/details/gtqxfnpcra.html

TS:   class User { name: string = ""; }
来源：http://dali.yj20258.top/Article/details/gtomeaelvt.html

Java: class User {}
来源：http://dali.redwolf501.top/Article/details/gthsqmupfk.html

Go:   type User struct { Name string }
来源：http://dali.bjfxy.top/Article/details/gtzqomqjqw.html

Ruby: class User; end
来源：http://dali.wangdashe.top/Article/details/gtlgznsgyd.html

C#:   class User {}
来源：http://dali.svipenyu.cn/Article/details/gtqjswtjsl.html

[G02] 构造函数
来源：http://dali.vqdsnc.cn/Article/details/gtjrdhowtf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xinyue.icu/Article/details/gtypofqyys.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yvedp.cn/Article/details/gtlbsozgui.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.mhx1999.top/Article/details/gtippwwfei.html

TS:   constructor(public name: string) {}
来源：http://dali.yangfankeji.com/Article/details/gtpqfqrbrd.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiwrogvdk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.tanke756.top/Article/details/gthgehcmom.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.andypj.xyz/Article/details/gtayevbkvl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.fzhhl.top/Article/details/gtrudemfpa.html

[G03] 实例属性
来源：http://dali.bjfxy.top/Article/details/gtpzfkexxq.html

Py:   self.name = "x"
来源：http://dali.iojbl.cn/Article/details/gtstrgwios.html

PHP:  public string $name = "x";
来源：http://dali.gzhubu.top/Article/details/gtwtmxnmvn.html

JS:   this.name = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtajspufnk.html

TS:   name: string = "x";
来源：http://dali.hysaishi.cn/Article/details/gtywenkdqw.html

Java: private String name;
来源：http://dali.sysykeji.top/Article/details/gtqbeltuhi.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jlsjyb.cn/Article/details/gtojdiipvb.html

Ruby: @name = "x"
来源：http://dali.feifeiyinyue.top/Article/details/gtxkixzfap.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtjynekrvn.html

[G04] 定义方法
来源：http://dali.pycfn.com/Article/details/gtnnmglqzf.html

Py:   def greet(self): return self.name
来源：http://dali.xziqi.cn/Article/details/gtsxefnjlo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtldvvkedi.html

JS:   greet() { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtznvsolwc.html

TS:   greet(): string { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtligqoika.html

Java: String greet() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtbgpomvvk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gtumvlsrun.html

Ruby: def greet; @name; end
来源：http://dali.ppjwa.cn/Article/details/gtzhumnezh.html

C#:   public string Greet() => Name;
来源：http://dali.cqqwz.cn/Article/details/gtmnxlnzic.html

[G05] 继承
来源：http://dali.ydzc1.top/Article/details/gtjiqklusn.html

Py:   class Admin(User): pass
来源：http://dali.ehwqpu.com/Article/details/gtrblzxrnq.html

PHP:  class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtfxxafidr.html

JS:   class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtjumvnzhy.html

TS:   class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gtyyuyyfvs.html

Java: class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtrdiemuvs.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cucudq.cn/Article/details/gtnsechfwe.html

Ruby: class Admin < User; end
来源：http://dali.daria6918.cn/Article/details/gtfkgxxylp.html

C#:   class Admin : User {}
来源：http://dali.yonumen.top/Article/details/gtuwjairlj.html

[G06] 重写方法
来源：http://dali.gotoacloud.top/Article/details/gtiprnorzo.html

Py:   def greet(self): return "admin"
来源：http://dali.shanyushiyangtech.top/Article/details/gtvamyjmuv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gteabllaad.html

JS:   greet() { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gtvgzqvzns.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gtpjdglzgg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gtincafrkr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hysaishi.cn/Article/details/gtcvqmsszu.html

Ruby: def greet; "admin"; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttfusjsvo.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhixingplan.top/Article/details/gtijwizolx.html

[G07] 调用父类方法
来源：http://dali.tanke756.top/Article/details/gtotxjgjth.html

Py:   super().greet()
来源：http://dali.hysaishi.cn/Article/details/gtowlsvava.html

PHP:  parent::greet();
来源：http://dali.fzhhl.top/Article/details/gtsvwgcrqr.html

JS:   super.greet();
来源：http://dali.pycfn.com/Article/details/gtqmzjglgo.html

TS:   super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gttmxjeoxl.html

Java: super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gttcenqmgu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hongshengwenyu.top/Article/details/gtgtmgdhbh.html

Ruby: super
来源：http://dali.jinqigufen.top/Article/details/gtbrdifobb.html

C#:   base.Greet();
来源：http://dali.hywenlv.cn/Article/details/gtqodvvtdf.html

[G08] 静态方法与属性
来源：http://dali.wangdashe.top/Article/details/gtjcevwacs.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yueranfly.top/Article/details/gtzlvrgeti.html

PHP:  public static function f() {}
来源：http://dali.fengsongda.top/Article/details/gtzdqhzxnh.html

JS:   static f() {}
来源：http://dali.yongpay.top/Article/details/gtrnbbjcav.html

TS:   static f(): void {}
来源：http://dali.ydzc1.top/Article/details/gtcfizucef.html

Java: static void f() {}
来源：http://dali.zdqjudy.top/Article/details/gtdejlekxd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.haohaochexian.top/Article/details/gtqpnhdjwg.html

Ruby: def self.f; end
来源：http://dali.aizwys.cn/Article/details/gtheuwjmzk.html

C#:   public static void F() {}
来源：http://dali.mhx1999.top/Article/details/gtmgruzgwm.html

[G09] 接口 / 抽象类
来源：http://dali.gogol.net.cn/Article/details/gtqvacegeo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhiwuduotai.top/Article/details/gtbewcyolk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.redwolf501.top/Article/details/gtsxbobakd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hywenlv.cn/Article/details/gtjaprbotw.html

TS:   interface Shape { area(): number; }
来源：http://dali.hnqzz.top/Article/details/gtzdoartxi.html

Java: interface Shape { double area(); }
来源：http://dali.xziqi.cn/Article/details/gtxrrirwcq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenlongwang.top/Article/details/gtzacouigm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.redwolf501.top/Article/details/gtwghzwmhr.html

C#:   interface IShape { double Area(); }
来源：http://dali.ydzc1.top/Article/details/gtdruvccyq.html

[G10] 访问控制
来源：http://dali.yuanzhike.top/Article/details/gtekeqyzrz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xziqi.cn/Article/details/gthehrvkte.html

PHP:  public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gtxgqzjjgd.html

JS:   #private 字段；其余公开
来源：http://dali.hfpthk.cn/Article/details/gtoyytxkdt.html

TS:   public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gteueertfx.html

Java: public / protected / private / 默认包级
来源：http://dali.jiagoushi.top/Article/details/gtqczhwpcv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hongshengwenyu.top/Article/details/gtqvagabxi.html

Ruby: public / protected / private
来源：http://dali.hnqzz.top/Article/details/gtcdyqhdht.html

C#:   public / protected / private / internal
来源：http://dali.xylfe.cn/Article/details/gtffisllpr.html

[G11] getter / setter
来源：http://dali.chenjidiqi.icu/Article/details/gtxgvzveuu.html

Py:   @property 与 @x.setter
来源：http://dali.redwolf501.top/Article/details/gtlptkwfdx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gtpbiygeka.html

JS:   get name() { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gtmfepfsnw.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gtqzxzpncg.html

Java: public String getName() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtlksgkhdh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gtscypzbua.html

Ruby: attr_accessor :name
来源：http://dali.zhongyouzk.top/Article/details/gtkbiszuit.html

C#:   public string Name { get; set; }
来源：http://dali.gzhubu.top/Article/details/gttuergdaw.html

[G12] 对象转字符串
来源：http://dali.sufxvd.cn/Article/details/gtygeccfap.html

Py:   def __str__(self): return self.name
来源：http://dali.316326.xyz/Article/details/gtblacqsnd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gtxbllgrxc.html

JS:   toString() { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gtpltvgvgj.html

TS:   toString(): string { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtcgoqzjwn.html

Java: @Override public String toString() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gtmbhrseqh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gtnrnxautp.html

Ruby: def to_s; @name; end
来源：http://dali.guowangkeji.top/Article/details/gtrgcchtzi.html

C#:   public override string ToString() => Name;
来源：http://dali.chenlongwang.top/Article/details/gtlrxgardt.html

[G13] 判断对象类型
来源：http://dali.cdnleiting.top/Article/details/gtgsndzahu.html

Py:   isinstance(u, User)
来源：http://dali.hnxiangtu.top/Article/details/gtgifrvebg.html

PHP:  $u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtwtiaegrg.html

JS:   u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtaulvsvbi.html

TS:   u instanceof User
来源：http://dali.pycfn.com/Article/details/gtueenrzvb.html

Java: u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gtxwjgrtlr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.pycfn.com/Article/details/gtzcpsubqe.html

Ruby: u.is_a?(User)
来源：http://dali.hysaishi.cn/Article/details/gtpjcldwyh.html

C#:   u is User
来源：http://dali.yj202588.top/Article/details/gtxtihrkwc.html

[G14] 数据类 / record
来源：http://dali.jyoumei.cn/Article/details/gtwwklnbdo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.snrcjt.cn/Article/details/gtbejucbxw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.feifeiyinyue.top/Article/details/gtktimyxly.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.andypj.xyz/Article/details/gtkwlosycv.html


<!-- 参考信息 -->