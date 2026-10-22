代发 wailian999

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yangfankeji.com/Article/details/gtzkhnammj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenlongwang.top/Article/details/gtsxwbiron.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hongshengwenyu.top/Article/details/gtfmfpcupz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hysaishi.cn/Article/details/gtgczgixit.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhixingplan.top/Article/details/gtnskapurd.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yuxming.cn/Article/details/gttrasgbam.html

[E16] 数字千分位
来源：http://dali.hnqzz.top/Article/details/gtzyzlbohg.html

Py:   f"{1234567:,}"
来源：http://dali.hywenlv.cn/Article/details/gtfsjoxdej.html

PHP:  number_format(1234567);
来源：http://dali.jianghu66.top/Article/details/gtopfkhugm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gtixfmirzw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenlongwang.top/Article/details/gtkdmhvyix.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinqigufen.top/Article/details/gtjhmydqyi.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cdnleiting.top/Article/details/gteenozfwp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinqigfzy.top/Article/details/gtglynrqvx.html

C#:   1234567.ToString("N0")
来源：http://dali.nwbrower.top/Article/details/gtctqortvn.html

[E17] 首字母大写
来源：http://dali.shangyingyoupin.top/Article/details/gtrlwlogqg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinghuilouyu.cn/Article/details/gtkpfpnpqa.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtwxmbpfbs.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.316326.xyz/Article/details/gtzjxsudui.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xylfe.cn/Article/details/gtjohayfkk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.mhx1999.top/Article/details/gtyxfukvnk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cucudq.cn/Article/details/gtorkqliff.html

Ruby: s.capitalize
来源：http://dali.zhoulong.xyz/Article/details/gtxofqyndz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmsjcbntb.html

[E18] 模板占位符替换
来源：http://dali.gotoacloud.top/Article/details/gtbifieslq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.daxiang520.top/Article/details/gtovxloeee.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.dianchejie.cn/Article/details/gterrkanxy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gtomkqezzo.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tian-w.cn/Article/details/gtfxdylhes.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gtsmyheazf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nwbrower.top/Article/details/gtmxscbnlq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yongpay.top/Article/details/gtzdnevyxy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtnhdldgqz.html

[E19] 多行文本按行拆分
来源：http://dali.cheryme.top/Article/details/gtcslqbhbx.html

Py:   s.splitlines()
来源：http://dali.sysykeji.top/Article/details/gtaarboqye.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.wangdashe.top/Article/details/gtymvjyivh.html

JS:   s.split(/\r?\n/)
来源：http://dali.svipenyu.cn/Article/details/gtneuuerth.html

TS:   s.split(/\r?\n/)
来源：http://dali.xylfe.cn/Article/details/gtmoilfmpu.html

Java: s.lines().toList()
来源：http://dali.yongpay.top/Article/details/gtkdcjlsns.html

Go:   strings.Split(s, "\n")
来源：http://dali.xziqi.cn/Article/details/gtjwbwrepq.html

Ruby: s.lines
来源：http://dali.xuanzx.com/Article/details/gtkppvtunx.html

C#:   s.Split('\n')
来源：http://dali.sweek.top/Article/details/gtfeifvziy.html

[E20] 判断字符串是否为空
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxjietjjb.html

Py:   if not s:
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqkewyliy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cdnleiting.top/Article/details/gtoiqqqngi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zycfv.cn/Article/details/gtgzpurxgj.html

TS:   if (s === "") {}
来源：http://dali.jinqigfzy.top/Article/details/gtovqhdxzp.html

Java: if (s.isEmpty()) {}
来源：http://dali.jqgufenzy.top/Article/details/gthdeauiat.html

Go:   if s == "" {}
来源：http://dali.hysaishi.cn/Article/details/gtqrqargwt.html

Ruby: if s.empty?
来源：http://dali.pycfn.com/Article/details/gtyqefsaoa.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jqgufenzy.top/Article/details/gtzhitnevw.html

[E21] 超长截断加省略号
来源：http://dali.redwolf501.top/Article/details/gtwrozqyjk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jyoumei.cn/Article/details/gtavthtqrl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gttzidoecp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtypcmdswt.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gtsdkvnuxq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtjbjikrvs.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.tanke756.top/Article/details/gtroyhlafk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.tian-w.cn/Article/details/gtumjrnemf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yj202588.top/Article/details/gthmhhymii.html

[E22] 字节长度与字符长度
来源：http://dali.pengpengdd.cyou/Article/details/gtvbqzqqxt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtevmnkqjq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqbqotnm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guowangkeji.top/Article/details/gtevmfkkxz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigufen.top/Article/details/gtyiqpwetc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinghuilouyu.cn/Article/details/gtrumierjm.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.havefunace.top/Article/details/gtjuovnbmi.html

Ruby: s.bytesize;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gtakezlema.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.guowangkeji.top/Article/details/gtznypfnea.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gticfaxpxb.html

F. 文件与目录
来源：http://dali.sufxvd.cn/Article/details/gtvmvfdpzm.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gttszmdaim.html

[F01] 读取整个文件
来源：http://dali.ivvv.top/Article/details/gtbsexjjui.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.daria6918.cn/Article/details/gtjgemjkqy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtzgalyxed.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.daria6918.cn/Article/details/gtruqwgpsn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tanke756.top/Article/details/gtglrkdasa.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtccvqdccz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.wangshuangyany.cn/Article/details/gtprdhdbqr.html

Ruby: File.read("a.txt")
来源：http://dali.cheryme.top/Article/details/gtoerpisko.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtjfjbwvzd.html

[F02] 逐行读取文件
来源：http://dali.sufxvd.cn/Article/details/gtkypeprmb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.aibaodan.cn/Article/details/gtoflrmczm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ydzc1.top/Article/details/gtlfxtnwio.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtajejhmld.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ivvv.top/Article/details/gtpizndacf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.smart0.xyz/Article/details/gtobuwzodm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.haohaochexian.top/Article/details/gtqoekfjlu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtytcjkole.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.pengpengdd.cyou/Article/details/gtanmsjydd.html

[F03] 写入文件（覆盖）
来源：http://dali.wangshuangyany.cn/Article/details/gttexpvabp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj20258.top/Article/details/gtvarnbszv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xylfe.cn/Article/details/gtukhsltor.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tian-w.cn/Article/details/gtcfgltkzz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gtefjeadez.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gthmtwrmxd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.wangshuangyany.cn/Article/details/gtagqacnwm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yuxming.cn/Article/details/gtltfmzavo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ivvv.top/Article/details/gtbpuxmjkz.html

[F04] 追加写入文件
来源：http://dali.shuidangran.top/Article/details/gtcorhvgxy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwqyuitmb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.iojbl.cn/Article/details/gtkvjgajyp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tianlin.xyz/Article/details/gtrexvwxha.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hywenlv.cn/Article/details/gtymjfoxac.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hfpthk.cn/Article/details/gtpbkqvspc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ydzc1.top/Article/details/gtazaavlzq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.dianchejie.cn/Article/details/gtihxkjcpw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shangyingyoupin.top/Article/details/gtglmqnpcw.html

[F05] 判断文件或目录是否存在
来源：http://dali.gaohongyu789.top/Article/details/gtasanuepl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ydzc1.top/Article/details/gtnbhqwxdf.html

PHP:  file_exists("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtcokztwxq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtmegzhnxu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtuwzlnraf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gtqyfytuxv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yueranfly.top/Article/details/gtwtqlrfre.html

Ruby: File.exist?("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtqqdebxjb.html

C#:   File.Exists("a.txt")
来源：http://dali.xziqi.cn/Article/details/gthkrqvmej.html

[F06] 删除文件
来源：http://dali.hnqzz.top/Article/details/gtyqnvffba.html

Py:   os.remove("a.txt")
来源：http://dali.birdmap.top/Article/details/gtpuskjwat.html

PHP:  unlink("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtqlbfgwhs.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtvbucploq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtmujtzjjj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtdgwcbwxh.html

Go:   os.Remove("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtwcushhiu.html

Ruby: File.delete("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtkninkytx.html

C#:   File.Delete("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtfoaevxcp.html

[F07] 创建目录（含多级）
来源：http://dali.yj202588.top/Article/details/gtxlzcbwpj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xuetiantiany.cn/Article/details/gtyfykvksl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.guowangkeji.top/Article/details/gtytscujlo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cheryme.top/Article/details/gtwmkmokep.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuxming.cn/Article/details/gtfdmgtrrq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ydzc1.top/Article/details/gtmudbnfih.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrwpgfkpl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.meibo888.top/Article/details/gtquwigdms.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cashguo.top/Article/details/gtfumitqag.html

[F08] 遍历目录
来源：http://dali.zdqjudy.top/Article/details/gtyjuhqfan.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gtykfglksh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.kuanghao11.cn/Article/details/gtpsvvylrv.html

JS:   fs.readdirSync("dir")
来源：http://dali.hysaishi.cn/Article/details/gtrnththvi.html

TS:   fs.readdirSync("dir")
来源：http://dali.nanxuanxn.top/Article/details/gtwgimjgfc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.havefunace.top/Article/details/gtludfaplb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jianghu66.top/Article/details/gteavohiwv.html

Ruby: Dir.children("dir")
来源：http://dali.fzhhl.top/Article/details/gtygytkckt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yanxiufei.cn/Article/details/gthdnnwsiw.html

[F09] 获取文件大小
来源：http://dali.meibo888.top/Article/details/gtcorqwyng.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtctoiiayn.html

PHP:  filesize("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtrvshyoxd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yueranfly.top/Article/details/gtqsszsosa.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hfpthk.cn/Article/details/gtsswskufl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gtzsizzyix.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj20258888.top/Article/details/gtivakrnpp.html

Ruby: File.size("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtxvkyxspa.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmaiermyg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gzhubu.top/Article/details/gtnjzexacf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvjdzkjhj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtwlobozes.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gthqyrsizi.html

TS:   path.extname("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtmwfrehkz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.fengsongda.top/Article/details/gtmpknntop.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxnxmcvjc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvwzlumgt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtulhanoxj.html

[F11] 复制与移动文件
来源：http://dali.jianghu66.top/Article/details/gtxcjbhrua.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtfzockejg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.c1oappe.top/Article/details/gthoukrqcg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtmshgcqtg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gthkwfmchb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yanxiufei.cn/Article/details/gtjzeomwzc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yvedp.cn/Article/details/gtaaqstern.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gtlgfoense.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yangfankeji.com/Article/details/gtiqlyulxc.html

[F12] CSV 读写
来源：http://dali.gogol.net.cn/Article/details/gtldpssjrh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zycfv.cn/Article/details/gtppywmtwq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ivvv.top/Article/details/gtqaryuclz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sxryk.cn/Article/details/gtyvizlkzf.html

TS:   // 同上
来源：http://dali.zhaomingkeji.xyz/Article/details/gtellaaggz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.quarkkingdee.top/Article/details/gtgkjcmhre.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.c1oappe.top/Article/details/gtizflwxyr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gtwaiayhqe.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj20258.top/Article/details/gtfapkvrju.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtewayvcxt.html

G. 面向对象
来源：http://dali.yvedp.cn/Article/details/gtigrjkrqs.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtwqyrtcoy.html

[G01] 定义类
来源：http://dali.chenzaomai.com/Article/details/gtgfztvqpz.html

Py:   class User: pass
来源：http://dali.fengsongda.top/Article/details/gtxlyhonco.html

PHP:  class User {}
来源：http://dali.xylfe.cn/Article/details/gtqfwstulz.html

JS:   class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtlviqvwbq.html

TS:   class User { name: string = ""; }
来源：http://dali.shuidangran.top/Article/details/gtvronvvkx.html

Java: class User {}
来源：http://dali.zdqjudy.top/Article/details/gtfvygpugy.html

Go:   type User struct { Name string }
来源：http://dali.nanxinkj.top/Article/details/gtblmgsrop.html

Ruby: class User; end
来源：http://dali.daxiang520.top/Article/details/gtekqerxit.html

C#:   class User {}
来源：http://dali.havefunace.top/Article/details/gtyklsmerv.html

[G02] 构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtqqojmtnz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ybcxt.top/Article/details/gtyyvivwbl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jianghu66.top/Article/details/gtiikhkhrb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtpginyvit.html

TS:   constructor(public name: string) {}
来源：http://dali.zycfv.cn/Article/details/gtxrhsvlkw.html

Java: User(String name) { this.name = name; }
来源：http://dali.xylfe.cn/Article/details/gtmbxedkwm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shuidangran.top/Article/details/gtsfqovlvf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yonumen.top/Article/details/gtslfciypl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.mhx1999.top/Article/details/gtekmwyfti.html

[G03] 实例属性
来源：http://dali.zhongyouzk.top/Article/details/gtljdfmiox.html

Py:   self.name = "x"
来源：http://dali.0kj1m.cn/Article/details/gtozlupttt.html

PHP:  public string $name = "x";
来源：http://dali.sysykeji.top/Article/details/gtnohowccp.html

JS:   this.name = "x";
来源：http://dali.nwbrower.top/Article/details/gtajpitjuf.html

TS:   name: string = "x";
来源：http://dali.zhongyouzk.top/Article/details/gtpornjnae.html

Java: private String name;
来源：http://dali.nanxuanxn.top/Article/details/gtprsiqyql.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.0kj1m.cn/Article/details/gtxspjbsyt.html

Ruby: @name = "x"
来源：http://dali.jinqigufen.top/Article/details/gtgptqkxmb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtlxxqmati.html

[G04] 定义方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtffshfcuf.html

Py:   def greet(self): return self.name
来源：http://dali.fengsongda.top/Article/details/gtbjknsjpo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gtwmcfscjr.html

JS:   greet() { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gtnwnihkhg.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqljudbty.html

Java: String greet() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtklqdbsvx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gtupolrufd.html

Ruby: def greet; @name; end
来源：http://dali.jlsjyb.cn/Article/details/gtnlkcidmn.html

C#:   public string Greet() => Name;
来源：http://dali.iojbl.cn/Article/details/gtlwfrbzfu.html

[G05] 继承
来源：http://dali.redwolf501.top/Article/details/gtalcvmnsw.html

Py:   class Admin(User): pass
来源：http://dali.tian-w.cn/Article/details/gtlifaktbe.html

PHP:  class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gtbovxhyza.html

JS:   class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtwfqfexzl.html

TS:   class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gtuvgljntl.html

Java: class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gttzajffvx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sxryk.cn/Article/details/gtzxyovraj.html

Ruby: class Admin < User; end
来源：http://dali.hammf.cn/Article/details/gtitkrdonq.html

C#:   class Admin : User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlhheivwk.html

[G06] 重写方法
来源：http://dali.meibo888.top/Article/details/gtxivysupb.html

Py:   def greet(self): return "admin"
来源：http://dali.tianlin.xyz/Article/details/gtahloawoy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gtxqzvwgqc.html

JS:   greet() { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtfaozrqdh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtuxfowplq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gtlnkhqwtw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.daria6918.cn/Article/details/gtgvgorxgi.html

Ruby: def greet; "admin"; end
来源：http://dali.sweek.top/Article/details/gtkmfudxqb.html

C#:   public override string Greet() => "admin";
来源：http://dali.cheryme.top/Article/details/gtsrxrhjfl.html

[G07] 调用父类方法
来源：http://dali.guannengcc.top/Article/details/gtwscvimra.html

Py:   super().greet()
来源：http://dali.hfpthk.cn/Article/details/gtyczsuglz.html

PHP:  parent::greet();
来源：http://dali.jyoumei.cn/Article/details/gtxtgfqauw.html

JS:   super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtqzmuunzw.html

TS:   super.greet();
来源：http://dali.0kj1m.cn/Article/details/gtortjslxr.html

Java: super.greet();
来源：http://dali.hammf.cn/Article/details/gtotfjzofl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbxkledmi.html

Ruby: super
来源：http://dali.jinqigfzy.top/Article/details/gtyuriqnfu.html

C#:   base.Greet();
来源：http://dali.hywenlv.cn/Article/details/gtgvukzcxs.html

[G08] 静态方法与属性
来源：http://dali.hnqzz.top/Article/details/gtrlwkqofw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.fengsongda.top/Article/details/gtcmlpyflo.html

PHP:  public static function f() {}
来源：http://dali.guowangkeji.top/Article/details/gtmnhhjqgm.html

JS:   static f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gtxccxcidg.html

TS:   static f(): void {}
来源：http://dali.ybcxt.top/Article/details/gttevqguex.html

Java: static void f() {}
来源：http://dali.hnqzz.top/Article/details/gtgpskzieg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hywenlv.cn/Article/details/gtgkqkxcwq.html

Ruby: def self.f; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvznhoske.html

C#:   public static void F() {}
来源：http://dali.smart0.xyz/Article/details/gthgsvpmpw.html

[G09] 接口 / 抽象类
来源：http://dali.ybcxt.top/Article/details/gtgfbdjqsr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.pengpengdd.cyou/Article/details/gtkuferhlf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yanxiufei.cn/Article/details/gtmdyofrto.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xziqi.cn/Article/details/gtqwpmioij.html

TS:   interface Shape { area(): number; }
来源：http://dali.ydzc1.top/Article/details/gtiibajoex.html

Java: interface Shape { double area(); }
来源：http://dali.daxiang520.top/Article/details/gtygvukyfk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cheryme.top/Article/details/gtebzvxiop.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xinyue.icu/Article/details/gtraaopdpw.html

C#:   interface IShape { double Area(); }
来源：http://dali.yvedp.cn/Article/details/gtuffjbhmj.html

[G10] 访问控制
来源：http://dali.yueranfly.top/Article/details/gtvlmnqshw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hnqzz.top/Article/details/gtjbgrcmvw.html

PHP:  public / protected / private
来源：http://dali.jqgufenzy.top/Article/details/gtrtmfspws.html

JS:   #private 字段；其余公开
来源：http://dali.birdmap.top/Article/details/gtjfmfhbkm.html

TS:   public / protected / private
来源：http://dali.yj20258888.top/Article/details/gtsebimcwo.html

Java: public / protected / private / 默认包级
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbexstwef.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.svipenyu.cn/Article/details/gtwfppxaql.html

Ruby: public / protected / private
来源：http://dali.gaohongyu789.top/Article/details/gtifwdpamh.html

C#:   public / protected / private / internal
来源：http://dali.nanxinkj.top/Article/details/gtrsbwzgof.html

[G11] getter / setter
来源：http://dali.gogol.net.cn/Article/details/gtwfhmyrgx.html

Py:   @property 与 @x.setter
来源：http://dali.c1oappe.top/Article/details/gtyrkgtatl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gtiiyhctou.html

JS:   get name() { return this._name; }
来源：http://dali.c1oappe.top/Article/details/gtslbwloxh.html

TS:   get name(): string { return this._name; }
来源：http://dali.daxiang520.top/Article/details/gtsoctksdl.html

Java: public String getName() { return name; }
来源：http://dali.yj20258888.top/Article/details/gtraaxoczm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gtkbduzget.html

Ruby: attr_accessor :name
来源：http://dali.daria6918.cn/Article/details/gtvyhtjlmy.html

C#:   public string Name { get; set; }
来源：http://dali.yj202588.top/Article/details/gtbxvshvqc.html

[G12] 对象转字符串
来源：http://dali.0kj1m.cn/Article/details/gtrjwgoplz.html

Py:   def __str__(self): return self.name
来源：http://dali.zhongyouzk.top/Article/details/gtafqcxemg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gtnionpzuo.html

JS:   toString() { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtcqoyfmkc.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtrqjagcvb.html

Java: @Override public String toString() { return name; }
来源：http://dali.cashguo.top/Article/details/gteprszfgw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gtdqlttobp.html

Ruby: def to_s; @name; end
来源：http://dali.wangshuangyany.cn/Article/details/gtgjhorvep.html

C#:   public override string ToString() => Name;
来源：http://dali.pengpengdd.cyou/Article/details/gtucrgimuw.html

[G13] 判断对象类型
来源：http://dali.meibo888.top/Article/details/gtuvqxtphc.html

Py:   isinstance(u, User)
来源：http://dali.pycfn.com/Article/details/gtomzqvgph.html

PHP:  $u instanceof User
来源：http://dali.birdmap.top/Article/details/gtdfwtmzwu.html

JS:   u instanceof User
来源：http://dali.mhx1999.top/Article/details/gtidkhwxyr.html

TS:   u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtxzflcwny.html

Java: u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gtggwmosty.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yuxming.cn/Article/details/gtuyqvixaz.html

Ruby: u.is_a?(User)
来源：http://dali.smart0.xyz/Article/details/gtokdnpspc.html

C#:   u is User
来源：http://dali.gaohongyu789.top/Article/details/gtorbtcnzo.html


<!-- 参考信息 -->