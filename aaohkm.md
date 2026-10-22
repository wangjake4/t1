代发 wailian999

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhengqikj.top/Article/details/gt2bazbtfnw.html

[E15] HTML 转义 / 反转义
来源：http://dali.yangfankeji.com/Article/details/gt2ukcddoor.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.mhx1999.top/Article/details/gt2lrfjujuw.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yuxming.cn/Article/details/gt2rostmxoe.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2pearqmyw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.iojbl.cn/Article/details/gt2glpuirlx.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.dianchejie.cn/Article/details/gt2bjswkckc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.dashuyun.cn/Article/details/gt2bqanwmvt.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bdfyypgf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.fengsongda.top/Article/details/gt2rybfizeh.html

[E16] 数字千分位
来源：http://dali.jqgfzy.top/Article/details/gt2zuhsvftt.html

Py:   f"{1234567:,}"
来源：http://dali.yj20258888.top/Article/details/gt2uqjyyaih.html

PHP:  number_format(1234567);
来源：http://dali.daria6918.cn/Article/details/gt2qrrrgrvf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tian-w.cn/Article/details/gt2ppkdctpy.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jyoumei.cn/Article/details/gt2ijbedous.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.guannengcc.top/Article/details/gt2raxpnmat.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.aibaodan.cn/Article/details/gt2tanncqts.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hftexasd.html

C#:   1234567.ToString("N0")
来源：http://dali.daxiang520.top/Article/details/gt2rvxlqzzk.html

[E17] 首字母大写
来源：http://dali.jqgfzy.top/Article/details/gt2rvogmveq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yonumen.top/Article/details/gt2qydwyfcd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jqgufenzy.top/Article/details/gt2fhvofllo.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2egvnfxfe.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xoquvyye.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jiagoushi.top/Article/details/gt2ecakudlx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xuanzx.com/Article/details/gt2vniqjjos.html

Ruby: s.capitalize
来源：http://dali.snrcjt.cn/Article/details/gt2dahfiwig.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ydzc1.top/Article/details/gt2ykzsqspq.html

[E18] 模板占位符替换
来源：http://dali.jinqigufen.top/Article/details/gt2ixnjcfqb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xinyue.icu/Article/details/gt2rshgscpe.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.havefunace.top/Article/details/gt2qqmkdjki.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cashguo.top/Article/details/gt2qdgqjxkh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gt2lzfoetwe.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gt2taqudend.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jupnfrne.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xinyue.icu/Article/details/gt2bxbzqdzp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinqigufen.top/Article/details/gt2higaiyzt.html

[E19] 多行文本按行拆分
来源：http://dali.jianghu66.top/Article/details/gt2zrtlmsro.html

Py:   s.splitlines()
来源：http://dali.jinqigufen.top/Article/details/gt2qanseemm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ymfnjdha.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ykaeyhwq.html

TS:   s.split(/\r?\n/)
来源：http://dali.vqdsnc.cn/Article/details/gt2kiwndudi.html

Java: s.lines().toList()
来源：http://dali.fzhhl.top/Article/details/gt2amoasjcg.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinqigfzy.top/Article/details/gt2dgxpzszm.html

Ruby: s.lines
来源：http://dali.ydzc1.top/Article/details/gt2uthnlkgp.html

C#:   s.Split('\n')
来源：http://dali.yj20258.top/Article/details/gt2mlyoeoyn.html

[E20] 判断字符串是否为空
来源：http://dali.c1oappe.top/Article/details/gt2jndyrdel.html

Py:   if not s:
来源：http://dali.nanxinkj.top/Article/details/gt2mptypuph.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.quarkkingdee.top/Article/details/gt2iracarao.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ehwqpu.com/Article/details/gt2imlfvetj.html

TS:   if (s === "") {}
来源：http://dali.yj20258888.top/Article/details/gt2yqxgubgi.html

Java: if (s.isEmpty()) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wtjenkds.html

Go:   if s == "" {}
来源：http://dali.ydzc1.top/Article/details/gt2fgmhfpqr.html

Ruby: if s.empty?
来源：http://dali.zhoulong.xyz/Article/details/gt2zsxqbubs.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.dashuyun.cn/Article/details/gt2pnpdoktn.html

[E21] 超长截断加省略号
来源：http://dali.chenlongwang.top/Article/details/gt2bvkcgvlz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.birdmap.top/Article/details/gt2dubpbgxy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gt2wviloohr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gt2oxiabpjr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gt2yvxlpwoz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gt2vxpgncxb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xylfe.cn/Article/details/gt2qamqrhdg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yonumen.top/Article/details/gt2freiqnnr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gt2plwtittb.html

[E22] 字节长度与字符长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2miempwuw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sufxvd.cn/Article/details/gt2xyzloypt.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gt2ztomconi.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yangfankeji.com/Article/details/gt2xiawnlcy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gotoacloud.top/Article/details/gt2moshupyw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zycfv.cn/Article/details/gt2pvcbojnw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.kuanghao11.cn/Article/details/gt2fxacmlpq.html

Ruby: s.bytesize;  s.length
来源：http://dali.hnxiangtu.top/Article/details/gt2grmktahz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tanke756.top/Article/details/gt2oaayqdqw.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2kjzidzkn.html

F. 文件与目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xeevowsj.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2bxwpxlqv.html

[F01] 读取整个文件
来源：http://dali.daxiang520.top/Article/details/gt2wneeaicr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shzxlz.cn/Article/details/gt2lylmuoiz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tkvxlntw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.snrcjt.cn/Article/details/gt2jwqwsqkx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gt2lregoijs.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2brbzljiq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cheryme.top/Article/details/gt2fizrmdyk.html

Ruby: File.read("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2zbhvooht.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sweek.top/Article/details/gt2gpegyuaf.html

[F02] 逐行读取文件
来源：http://dali.hammf.cn/Article/details/gt2iujrwwsd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.svipenyu.cn/Article/details/gt2yzrwjmwb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.andypj.xyz/Article/details/gt2jcfykkil.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daxiang520.top/Article/details/gt2qevmhbzz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.0kj1m.cn/Article/details/gt2hyqonagj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cashguo.top/Article/details/gt2psbbjwvv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.guowangkeji.top/Article/details/gt2nlxwttcn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2fobjyhhk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.9152youxi.cn/Article/details/gt2phzayirp.html

[F03] 写入文件（覆盖）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bvntvamf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.iojbl.cn/Article/details/gt2lzxtmydt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shzxlz.cn/Article/details/gt2medepjpf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ydmwdmql.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gt2oiptfhnl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.guannengcc.top/Article/details/gt2uhaqefyd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.0kj1m.cn/Article/details/gt2odipvwbv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.svipenyu.cn/Article/details/gt2gacyxlxk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shangyingyoupin.top/Article/details/gt2rtjcporq.html

[F04] 追加写入文件
来源：http://dali.jinqigufen.top/Article/details/gt2jtrejrbc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhixingplan.top/Article/details/gt2axiqwejl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xuetiantiany.cn/Article/details/gt2cnwrwmth.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.havefunace.top/Article/details/gt2xulfaucr.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hysaishi.cn/Article/details/gt2xcnvlpcc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhoulong.xyz/Article/details/gt2vsoptuxm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj20258888.top/Article/details/gt2zxzaqoiu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sufxvd.cn/Article/details/gt2dgxcftjf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cheryme.top/Article/details/gt2umfekfrn.html

[F05] 判断文件或目录是否存在
来源：http://dali.gogol.net.cn/Article/details/gt2bpkihxlw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gaohongyu789.top/Article/details/gt2sypxzwzp.html

PHP:  file_exists("a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2bmbskbla.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2uhppiqsq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2zhajflei.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gt2dcctccux.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yanxiufei.cn/Article/details/gt2iasrwvhy.html

Ruby: File.exist?("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2eoyggxgz.html

C#:   File.Exists("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2igxwodbk.html

[F06] 删除文件
来源：http://dali.andypj.xyz/Article/details/gt2uhfmwckj.html

Py:   os.remove("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2kmjpalel.html

PHP:  unlink("a.txt");
来源：http://dali.guannengcc.top/Article/details/gt2nytyawfo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2xdgdntau.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2rwstmqcg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gt2lmlnvxhx.html

Go:   os.Remove("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2fyqcvvff.html

Ruby: File.delete("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sqtxhpmb.html

C#:   File.Delete("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gt2jheybmlc.html

[F07] 创建目录（含多级）
来源：http://dali.andypj.xyz/Article/details/gt2dvjdoavl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.wangdashe.top/Article/details/gt2dkyuswvl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jlsjyb.cn/Article/details/gt2staawxpq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jlsjyb.cn/Article/details/gt2kzmnifah.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cqqwz.cn/Article/details/gt2orbyclhr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.andypj.xyz/Article/details/gt2lhnbsckv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xuanzx.com/Article/details/gt2isznlnqw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jianghu66.top/Article/details/gt2bhbsydwc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hysaishi.cn/Article/details/gt2ewypougz.html

[F08] 遍历目录
来源：http://dali.nwbrower.top/Article/details/gt2zdwbiokb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.0kj1m.cn/Article/details/gt2cbibnbko.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.guannengcc.top/Article/details/gt2zmwzvrns.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yyddgkau.html

TS:   fs.readdirSync("dir")
来源：http://dali.cdnleiting.top/Article/details/gt2rtmqbuvc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hnxiangtu.top/Article/details/gt2vpojdeip.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.9152youxi.cn/Article/details/gt2hzytnjhu.html

Ruby: Dir.children("dir")
来源：http://dali.9152youxi.cn/Article/details/gt2yaspbcyh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gt2nsjzlyzd.html

[F09] 获取文件大小
来源：http://dali.andypj.xyz/Article/details/gt2tcrzentm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2lxmckrbw.html

PHP:  filesize("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2kwgntlmn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.chenzaomai.com/Article/details/gt2xxnccjnq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhoulong.xyz/Article/details/gt2cqldctmn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gt2ilztpmuo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinqigufen.top/Article/details/gt2kpfgbqdw.html

Ruby: File.size("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2hlsosgxk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shuidangran.top/Article/details/gt2epizxczz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ntyhgequ.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2xzdowgnj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2ezzmisah.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2utfnefyz.html

TS:   path.extname("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2txpqncga.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shuidangran.top/Article/details/gt2yrutzlpn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2ufkbgjvb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2pakegmea.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xyqctrqt.html

[F11] 复制与移动文件
来源：http://dali.9152youxi.cn/Article/details/gt2hkkvjxll.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gt2zzmafbbn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gt2onahzvqg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2xsuiisot.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2rmjbfboj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cbosysla.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jlsjyb.cn/Article/details/gt2ghhpszbb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gt2qgeyjevx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yueranfly.top/Article/details/gt2cjzfuhmh.html

[F12] CSV 读写
来源：http://dali.9152youxi.cn/Article/details/gt2bcwpxbwn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.guowangkeji.top/Article/details/gt2vcrcczvj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2igsbycgf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yanxiufei.cn/Article/details/gt2pquoszqn.html

TS:   // 同上
来源：http://dali.quarkkingdee.top/Article/details/gt2osrgejad.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jlsjyb.cn/Article/details/gt2jhsbovzk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hjmpdqzd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gzhubu.top/Article/details/gt2fqcpozes.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xuetiantiany.cn/Article/details/gt2fznksjab.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2uqhudvae.html

G. 面向对象
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rqcqcvvi.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2nherlght.html

[G01] 定义类
来源：http://dali.cucudq.cn/Article/details/gt2cmfhdvps.html

Py:   class User: pass
来源：http://dali.yuanzhike.top/Article/details/gt2htnovmxb.html

PHP:  class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2dabbijfn.html

JS:   class User {}
来源：http://dali.hysaishi.cn/Article/details/gt2yfdrzedd.html

TS:   class User { name: string = ""; }
来源：http://dali.yangfankeji.com/Article/details/gt2yyjewxul.html

Java: class User {}
来源：http://dali.haohaochexian.top/Article/details/gt2ufioarvr.html

Go:   type User struct { Name string }
来源：http://dali.yonumen.top/Article/details/gt2qoflpndh.html

Ruby: class User; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2aiikcomg.html

C#:   class User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2voaoebnw.html

[G02] 构造函数
来源：http://dali.meibo888.top/Article/details/gt2khcuyexi.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hammf.cn/Article/details/gt2rymkvpwk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rvvxdbwh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2heeupcwy.html

TS:   constructor(public name: string) {}
来源：http://dali.snrcjt.cn/Article/details/gt2snoqahrm.html

Java: User(String name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2bteijnkz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yvedp.cn/Article/details/gt2pplbznlq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sweek.top/Article/details/gt2gskpuvrd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.316326.xyz/Article/details/gt2nijlgsvk.html

[G03] 实例属性
来源：http://dali.zhiwuduotai.top/Article/details/gt2mvcskfsx.html

Py:   self.name = "x"
来源：http://dali.hongshengwenyu.top/Article/details/gt2ribznqpl.html

PHP:  public string $name = "x";
来源：http://dali.gzhubu.top/Article/details/gt2bwhlocgc.html

JS:   this.name = "x";
来源：http://dali.shuidangran.top/Article/details/gt2uxrfisob.html

TS:   name: string = "x";
来源：http://dali.hammf.cn/Article/details/gt2xvbzzafc.html

Java: private String name;
来源：http://dali.smart0.xyz/Article/details/gt2egfddzkm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yvedp.cn/Article/details/gt2wfpefhbd.html

Ruby: @name = "x"
来源：http://dali.iojbl.cn/Article/details/gt2jnyrwujk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hysaishi.cn/Article/details/gt2vqmpjtah.html

[G04] 定义方法
来源：http://dali.shuidangran.top/Article/details/gt2slveouwl.html

Py:   def greet(self): return self.name
来源：http://dali.wangshuangyany.cn/Article/details/gt2mjaocekf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gt2eykacuxm.html

JS:   greet() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gt2kzedhnjd.html

TS:   greet(): string { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2ddfzoaeg.html

Java: String greet() { return name; }
来源：http://dali.zhixingplan.top/Article/details/gt2qdefodal.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gt2rdlhgryo.html

Ruby: def greet; @name; end
来源：http://dali.hywenlv.cn/Article/details/gt2dlqmkyby.html

C#:   public string Greet() => Name;
来源：http://dali.zhoulong.xyz/Article/details/gt2epesxtdp.html

[G05] 继承
来源：http://dali.smart0.xyz/Article/details/gt2lmvhcltj.html

Py:   class Admin(User): pass
来源：http://dali.smart0.xyz/Article/details/gt2fmajhfcx.html

PHP:  class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gt2pvnhuvey.html

JS:   class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wopmuhng.html

TS:   class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gt2eqocynxd.html

Java: class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gt2tuffxlxk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj20258.top/Article/details/gt2xrtvctqi.html

Ruby: class Admin < User; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wjvdnphn.html

C#:   class Admin : User {}
来源：http://dali.chenzaomai.com/Article/details/gt2pvuluola.html

[G06] 重写方法
来源：http://dali.ivvv.top/Article/details/gt2mkncapmh.html

Py:   def greet(self): return "admin"
来源：http://dali.cucudq.cn/Article/details/gt2hsdsskma.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gt2nwlmbmvv.html

JS:   greet() { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gt2ghafqlsn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gt2yclcizqe.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gt2hqbqdzni.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinqigufen.top/Article/details/gt2ijomqdtu.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigfzy.top/Article/details/gt2fsmokxee.html

C#:   public override string Greet() => "admin";
来源：http://dali.fengsongda.top/Article/details/gt2ndemteoo.html

[G07] 调用父类方法
来源：http://dali.xylfe.cn/Article/details/gt2icohwkcq.html

Py:   super().greet()
来源：http://dali.shzxlz.cn/Article/details/gt2pmnnragu.html

PHP:  parent::greet();
来源：http://dali.xinyue.icu/Article/details/gt2mpdujsih.html

JS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gt2ifpwuyqv.html

TS:   super.greet();
来源：http://dali.pycfn.com/Article/details/gt2paafnjai.html

Java: super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vgharrue.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.guowangkeji.top/Article/details/gt2dvcfufea.html

Ruby: super
来源：http://dali.xinyue.icu/Article/details/gt2yrabhfft.html

C#:   base.Greet();
来源：http://dali.chenjidiqi.icu/Article/details/gt2qxwwryaa.html

[G08] 静态方法与属性
来源：http://dali.ydzc1.top/Article/details/gt2jovzoelj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gogol.net.cn/Article/details/gt2ncqyplzx.html

PHP:  public static function f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2hxaolfos.html

JS:   static f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2owitxiio.html

TS:   static f(): void {}
来源：http://dali.daxiang520.top/Article/details/gt2lkyaqnsn.html

Java: static void f() {}
来源：http://dali.tanke756.top/Article/details/gt2pqeprknz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.guowangkeji.top/Article/details/gt2eifdouwo.html

Ruby: def self.f; end
来源：http://dali.zhoulong.xyz/Article/details/gt2wajdmtlg.html

C#:   public static void F() {}
来源：http://dali.hysaishi.cn/Article/details/gt2chkljqfr.html

[G09] 接口 / 抽象类
来源：http://dali.dashuyun.cn/Article/details/gt2mtktirrt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gzhubu.top/Article/details/gt2fcvznhix.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ybcxt.top/Article/details/gt2eabdxbnt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinqigufen.top/Article/details/gt2uidoygba.html

TS:   interface Shape { area(): number; }
来源：http://dali.shzxlz.cn/Article/details/gt2wdxizgvy.html

Java: interface Shape { double area(); }
来源：http://dali.dashuyun.cn/Article/details/gt2dbywoavm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cheryme.top/Article/details/gt2zffjfqgj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jyoumei.cn/Article/details/gt2iihrbhsk.html

C#:   interface IShape { double Area(); }
来源：http://dali.ppjwa.cn/Article/details/gt2wyisrzns.html

[G10] 访问控制
来源：http://dali.ehwqpu.com/Article/details/gt2qcfbgoqs.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ydzc1.top/Article/details/gt2ghdgmxrh.html

PHP:  public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zhuqlrbh.html

JS:   #private 字段；其余公开
来源：http://dali.guannengcc.top/Article/details/gt2vvyalilm.html

TS:   public / protected / private
来源：http://dali.yj20258.top/Article/details/gt2clxzvntb.html

Java: public / protected / private / 默认包级
来源：http://dali.zhoulong.xyz/Article/details/gt2eormckse.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.iojbl.cn/Article/details/gt2phszjlvz.html

Ruby: public / protected / private
来源：http://dali.aizwys.cn/Article/details/gt2qzkpehhd.html

C#:   public / protected / private / internal
来源：http://dali.vqdsnc.cn/Article/details/gt2supztpzi.html

[G11] getter / setter
来源：http://dali.ehwqpu.com/Article/details/gt2erzzapem.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2hemzbhyh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2uvbyckxs.html

JS:   get name() { return this._name; }
来源：http://dali.zhixingplan.top/Article/details/gt2bgpfeblh.html

TS:   get name(): string { return this._name; }
来源：http://dali.jyoumei.cn/Article/details/gt2mqkxtgcy.html

Java: public String getName() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2szsurdof.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.iojbl.cn/Article/details/gt2sduygvbk.html

Ruby: attr_accessor :name
来源：http://dali.yj20258888.top/Article/details/gt2hkgudcyc.html

C#:   public string Name { get; set; }
来源：http://dali.redwolf501.top/Article/details/gt2guxloxhi.html

[G12] 对象转字符串
来源：http://dali.yonumen.top/Article/details/gt2swddtnsa.html

Py:   def __str__(self): return self.name
来源：http://dali.yj202588.top/Article/details/gt2euezxkfw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gt2qmvhijhr.html

JS:   toString() { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gt2cfmhpkgs.html

TS:   toString(): string { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gt2oymnyner.html

Java: @Override public String toString() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gt2wizxnnba.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gt2bylivhqq.html

Ruby: def to_s; @name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wtlvntgw.html

C#:   public override string ToString() => Name;
来源：http://dali.shangyingyoupin.top/Article/details/gt2besyjgbl.html

[G13] 判断对象类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xrrarmwv.html

Py:   isinstance(u, User)
来源：http://dali.316326.xyz/Article/details/gt2okmchqcp.html

PHP:  $u instanceof User
来源：http://dali.tian-w.cn/Article/details/gt2cocaxrqv.html

JS:   u instanceof User
来源：http://dali.yj202588.top/Article/details/gt2kvdesrii.html

TS:   u instanceof User
来源：http://dali.sxryk.cn/Article/details/gt2fnjwbmjo.html


<!-- 参考信息 -->