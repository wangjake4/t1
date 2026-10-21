代发 wailian999

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gtnqjhukem.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gtvrundsht.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xziqi.cn/Article/details/gtqtzcgdwu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhengqikj.top/Article/details/gtztcagimv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yanxiufei.cn/Article/details/gtqceqcxkn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhixingplan.top/Article/details/gtmkfivywr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sysykeji.top/Article/details/gtuvmoisfw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zycfv.cn/Article/details/gtioubkivq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yj20258888.top/Article/details/gtfewvppdr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jinqigufen.top/Article/details/gtkxjmtktz.html

[E16] 数字千分位
来源：http://dali.iojbl.cn/Article/details/gtdmshuzwn.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gtpneyvqmc.html

PHP:  number_format(1234567);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwyzhoci.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhengqikj.top/Article/details/gtptgwbbdc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.daria6918.cn/Article/details/gtndslwcto.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhongyouzk.top/Article/details/gtpfjcqenf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.havefunace.top/Article/details/gtbcvgjadr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.wangdashe.top/Article/details/gtfzkbkzjk.html

C#:   1234567.ToString("N0")
来源：http://dali.ivvv.top/Article/details/gtpiqkichr.html

[E17] 首字母大写
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmkwgbgbj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jlsjyb.cn/Article/details/gtwsgbejrd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xziqi.cn/Article/details/gthgahmbkd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigufen.top/Article/details/gtajsfozkf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gtybdnmxyl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.tanke756.top/Article/details/gtgkptyglb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xuanzx.com/Article/details/gtvmrqkbyk.html

Ruby: s.capitalize
来源：http://dali.ivvv.top/Article/details/gtwisitwwx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj202588.top/Article/details/gtxownzwta.html

[E18] 模板占位符替换
来源：http://dali.havefunace.top/Article/details/gtntfkmhft.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hysaishi.cn/Article/details/gtmkyclikd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hysaishi.cn/Article/details/gtiaooyxwx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ivvv.top/Article/details/gtzcclsitg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gtvatpublj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gteomtfoyo.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tian-w.cn/Article/details/gtnmcbargd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.wangshuangyany.cn/Article/details/gthzvihuxr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.aibaodan.cn/Article/details/gtysyrmerw.html

[E19] 多行文本按行拆分
来源：http://dali.wangshuangyany.cn/Article/details/gtphkfkcgv.html

Py:   s.splitlines()
来源：http://dali.mhx1999.top/Article/details/gtrrrzrjkl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yvedp.cn/Article/details/gtoqliqwbo.html

JS:   s.split(/\r?\n/)
来源：http://dali.gotoacloud.top/Article/details/gtzracmumf.html

TS:   s.split(/\r?\n/)
来源：http://dali.gotoacloud.top/Article/details/gtpzrjpyex.html

Java: s.lines().toList()
来源：http://dali.yj20258.top/Article/details/gtbdzihwgv.html

Go:   strings.Split(s, "\n")
来源：http://dali.aizwys.cn/Article/details/gtqjvdnebp.html

Ruby: s.lines
来源：http://dali.tanke756.top/Article/details/gtogunerfm.html

C#:   s.Split('\n')
来源：http://dali.hnxiangtu.top/Article/details/gtbuzluopw.html

[E20] 判断字符串是否为空
来源：http://dali.hnqzz.top/Article/details/gtpvuixeqw.html

Py:   if not s:
来源：http://dali.ehwqpu.com/Article/details/gtdzdrtsjk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xinyue.icu/Article/details/gtibxpzlxg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cqqwz.cn/Article/details/gtnbooxngr.html

TS:   if (s === "") {}
来源：http://dali.shzxlz.cn/Article/details/gtmyrjqntj.html

Java: if (s.isEmpty()) {}
来源：http://dali.jqgfzy.top/Article/details/gtbwgejvxm.html

Go:   if s == "" {}
来源：http://dali.meibo888.top/Article/details/gtenybpsbn.html

Ruby: if s.empty?
来源：http://dali.kuanghao11.cn/Article/details/gttqtrkloq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yuxming.cn/Article/details/gtnaqatvle.html

[E21] 超长截断加省略号
来源：http://dali.zhixingplan.top/Article/details/gtancdpmkv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xinyue.icu/Article/details/gtllfpdszi.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gtlrhnxdjg.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xinyue.icu/Article/details/gtppmrlqhk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gtsrlvctjn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gtkopphezf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.9152youxi.cn/Article/details/gtzyzyjnjt.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj20258.top/Article/details/gtppvkmbok.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xinyue.icu/Article/details/gtienufiir.html

[E22] 字节长度与字符长度
来源：http://dali.jiagoushi.top/Article/details/gtukhjydtp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hfpthk.cn/Article/details/gtvhxuwdrj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cheryme.top/Article/details/gtgccajpen.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.9152youxi.cn/Article/details/gtyurirgzm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sufxvd.cn/Article/details/gtldrtpfei.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.haohaochexian.top/Article/details/gtobiaqwsk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.quarkkingdee.top/Article/details/gttgyyjjwe.html

Ruby: s.bytesize;  s.length
来源：http://dali.yuanzhike.top/Article/details/gttwhyytmp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jiagoushi.top/Article/details/gttydvsrmx.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtslgbdlwm.html

F. 文件与目录
来源：http://dali.yj20258.top/Article/details/gttuismcsg.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtyfkotwqo.html

[F01] 读取整个文件
来源：http://dali.dianchejie.cn/Article/details/gtdncwipan.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.feifeiyinyue.top/Article/details/gtfatejoru.html

PHP:  file_get_contents("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtijpzvpkb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ivvv.top/Article/details/gtawlxwcsi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.316326.xyz/Article/details/gtetigrmxf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gttjxeipqd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hongshengwenyu.top/Article/details/gtlrtdmwtc.html

Ruby: File.read("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtniekllvq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtgnikhjpx.html

[F02] 逐行读取文件
来源：http://dali.ehwqpu.com/Article/details/gtgquynlxc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xuetiantiany.cn/Article/details/gtuebjuaie.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhiwuduotai.top/Article/details/gtgsnhjhzf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgdumkbvo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jianghu66.top/Article/details/gtktrysmsa.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhengqikj.top/Article/details/gtpaqittsa.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.daria6918.cn/Article/details/gtpwkigmir.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jianghu66.top/Article/details/gtiwxlvtcs.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yangfankeji.com/Article/details/gtasbeoide.html

[F03] 写入文件（覆盖）
来源：http://dali.dianchejie.cn/Article/details/gtdajmaldv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hammf.cn/Article/details/gtnfnooqwn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shangyingyoupin.top/Article/details/gthuauicsi.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gtishziigl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yueranfly.top/Article/details/gtlwxwszid.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenzaomai.com/Article/details/gtrhlmhqso.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.kuanghao11.cn/Article/details/gttazpuodd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jlsjyb.cn/Article/details/gtiqjgdkgy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yonumen.top/Article/details/gtvpxbmwpq.html

[F04] 追加写入文件
来源：http://dali.zhixingplan.top/Article/details/gtohmxvupc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtryosajwr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shzxlz.cn/Article/details/gtefmsgats.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.andypj.xyz/Article/details/gtqrohjspi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.mhx1999.top/Article/details/gtgdirelno.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.fengsongda.top/Article/details/gtrmjisbtn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zycfv.cn/Article/details/gtegvtvuel.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hnxiangtu.top/Article/details/gtkmymhcuk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ybcxt.top/Article/details/gtdmpasqrs.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj20258.top/Article/details/gtfpohvfoi.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaofovezg.html

PHP:  file_exists("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtozrtnump.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gthzchcwtg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtqcuiieyq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gtohtwaxnq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.svipenyu.cn/Article/details/gthglguqpj.html

Ruby: File.exist?("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtpvgahdrg.html

C#:   File.Exists("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtplaacvhr.html

[F06] 删除文件
来源：http://dali.yj20258888.top/Article/details/gtfhzypwdw.html

Py:   os.remove("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtnwkxjhaw.html

PHP:  unlink("a.txt");
来源：http://dali.yonumen.top/Article/details/gttoaorivg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gttnyitcfm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gttaqxgnty.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtzoxeghos.html

Go:   os.Remove("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtvoeozqof.html

Ruby: File.delete("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtseeyicsk.html

C#:   File.Delete("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtvutzqrba.html

[F07] 创建目录（含多级）
来源：http://dali.yonumen.top/Article/details/gteqldfyqw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tanke756.top/Article/details/gtimrwmnbv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.aizwys.cn/Article/details/gtvnegatgy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.0kj1m.cn/Article/details/gtqdlundwy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hfpthk.cn/Article/details/gttaxjeoet.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cashguo.top/Article/details/gtsrsbvchi.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.guowangkeji.top/Article/details/gtgzvduwnh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xylfe.cn/Article/details/gtculzfhdl.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tian-w.cn/Article/details/gtvqbsmtee.html

[F08] 遍历目录
来源：http://dali.fengsongda.top/Article/details/gthigpxvbv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cucudq.cn/Article/details/gteuxkdsoc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shuidangran.top/Article/details/gtbzhlpbqp.html

JS:   fs.readdirSync("dir")
来源：http://dali.hfpthk.cn/Article/details/gtaxgisplo.html

TS:   fs.readdirSync("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtlqhmlsmt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yvedp.cn/Article/details/gtctnjtxjw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.9152youxi.cn/Article/details/gtcmuwnuco.html

Ruby: Dir.children("dir")
来源：http://dali.ydzc1.top/Article/details/gtbjfimwrm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.aibaodan.cn/Article/details/gtxfaihyqu.html

[F09] 获取文件大小
来源：http://dali.andypj.xyz/Article/details/gtnlpzhxei.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtlriubknt.html

PHP:  filesize("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtormbwddg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cucudq.cn/Article/details/gtlcdlpqav.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xylfe.cn/Article/details/gtcehmvnie.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gtixxdzqrm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.iojbl.cn/Article/details/gtxvaaeupc.html

Ruby: File.size("a.txt")
来源：http://dali.yj202588.top/Article/details/gtvdthownh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ydzc1.top/Article/details/gtjqbvfzut.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinqigufen.top/Article/details/gtsfeqkhsp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtmuovvtie.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cucudq.cn/Article/details/gtrrvgrnca.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtyvglklec.html

TS:   path.extname("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtfbwfcjkv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhongyouzk.top/Article/details/gteulvkiqz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtpjgpcxvx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtteatvntj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtdxocgzsh.html

[F11] 复制与移动文件
来源：http://dali.quarkkingdee.top/Article/details/gtslhtchyf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtfszupdqb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gogol.net.cn/Article/details/gtckjsmrok.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gthckqtuwp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gtuxptyfai.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinqigfzy.top/Article/details/gttblnxjpb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yuanzhike.top/Article/details/gtramnxhwq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gtowlysino.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhongyouzk.top/Article/details/gtgsqxscnb.html

[F12] CSV 读写
来源：http://dali.jinghuilouyu.cn/Article/details/gtcevbjxeb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tian-w.cn/Article/details/gthvikoyeg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cdnleiting.top/Article/details/gttfdsptfp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xinyue.icu/Article/details/gtwulylccg.html

TS:   // 同上
来源：http://dali.haohaochexian.top/Article/details/gtqhgcbsna.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.haohaochexian.top/Article/details/gtlbhcxstd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvenywjyt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.meibo888.top/Article/details/gtiubiofxz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.kuanghao11.cn/Article/details/gtldpkjdbl.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtmuqekimf.html

G. 面向对象
来源：http://dali.smart0.xyz/Article/details/gtkmjrngft.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtitfthkwk.html

[G01] 定义类
来源：http://dali.yonumen.top/Article/details/gtlfizdbvo.html

Py:   class User: pass
来源：http://dali.jinqigufen.top/Article/details/gtcbifikut.html

PHP:  class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtdxeyqyts.html

JS:   class User {}
来源：http://dali.andypj.xyz/Article/details/gtgsctxuma.html

TS:   class User { name: string = ""; }
来源：http://dali.andypj.xyz/Article/details/gtgovlqjeb.html

Java: class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtyetafojf.html

Go:   type User struct { Name string }
来源：http://dali.tian-w.cn/Article/details/gteftsserl.html

Ruby: class User; end
来源：http://dali.fzhhl.top/Article/details/gtxlvjbuqe.html

C#:   class User {}
来源：http://dali.0kj1m.cn/Article/details/gtjiyfjegp.html

[G02] 构造函数
来源：http://dali.shuidangran.top/Article/details/gtcldrcbup.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tanke756.top/Article/details/gtjmfqxbpe.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhoulong.xyz/Article/details/gtyjwlbzam.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtojidcmtn.html

TS:   constructor(public name: string) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtpfdpfxnv.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenlongwang.top/Article/details/gtifadzizy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinqigfzy.top/Article/details/gtzqpshwoh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinqigfzy.top/Article/details/gtseurqzkw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tian-w.cn/Article/details/gtxxpxxmen.html

[G03] 实例属性
来源：http://dali.yanxiufei.cn/Article/details/gtpeimnfhs.html

Py:   self.name = "x"
来源：http://dali.yvedp.cn/Article/details/gtuvihmxsr.html

PHP:  public string $name = "x";
来源：http://dali.aizwys.cn/Article/details/gtrbxxapzs.html

JS:   this.name = "x";
来源：http://dali.gotoacloud.top/Article/details/gtkmesntut.html

TS:   name: string = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtosppcgab.html

Java: private String name;
来源：http://dali.tian-w.cn/Article/details/gtggdtmfos.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hnqzz.top/Article/details/gtqjrxkudr.html

Ruby: @name = "x"
来源：http://dali.svipenyu.cn/Article/details/gtgcotaoem.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.aibaodan.cn/Article/details/gtvzkdxsho.html

[G04] 定义方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxofjtdox.html

Py:   def greet(self): return self.name
来源：http://dali.feifeiyinyue.top/Article/details/gtvfjxsqak.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpebfhktm.html

JS:   greet() { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gtgfbpbiyg.html

TS:   greet(): string { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gtefbrasjn.html

Java: String greet() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtwmcovwvw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gtgebtcbct.html

Ruby: def greet; @name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcjovmsxw.html

C#:   public string Greet() => Name;
来源：http://dali.xziqi.cn/Article/details/gtduermgbp.html

[G05] 继承
来源：http://dali.jiagoushi.top/Article/details/gtluszatzw.html

Py:   class Admin(User): pass
来源：http://dali.birdmap.top/Article/details/gtyopsdcpm.html

PHP:  class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gtbcpdyaii.html

JS:   class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtfuwakyqx.html

TS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtoqwfhlgo.html

Java: class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtwlztmrws.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.dashuyun.cn/Article/details/gtltrnntpy.html

Ruby: class Admin < User; end
来源：http://dali.birdmap.top/Article/details/gtqhmmpast.html

C#:   class Admin : User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtczrleuiq.html

[G06] 重写方法
来源：http://dali.chenzaomai.com/Article/details/gtmhelevme.html

Py:   def greet(self): return "admin"
来源：http://dali.redwolf501.top/Article/details/gtxqadaoka.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtnrkghwjm.html

JS:   greet() { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gtlhtaksrl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtfdrmrjll.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gtguobrrvd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hnqzz.top/Article/details/gthtqondby.html

Ruby: def greet; "admin"; end
来源：http://dali.shangyingyoupin.top/Article/details/gtjmippzrp.html

C#:   public override string Greet() => "admin";
来源：http://dali.dianchejie.cn/Article/details/gtuahohkgs.html

[G07] 调用父类方法
来源：http://dali.fengsongda.top/Article/details/gtwbgpsgvh.html

Py:   super().greet()
来源：http://dali.jinqigufen.top/Article/details/gtwemuilmx.html

PHP:  parent::greet();
来源：http://dali.cheryme.top/Article/details/gthqdhbaxh.html

JS:   super.greet();
来源：http://dali.chenlongwang.top/Article/details/gtvdvalggy.html

TS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gtawbwuurb.html

Java: super.greet();
来源：http://dali.jqgfzy.top/Article/details/gtxwzjgjpw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cqqwz.cn/Article/details/gtumjonbuv.html

Ruby: super
来源：http://dali.316326.xyz/Article/details/gtvawtkcbt.html

C#:   base.Greet();
来源：http://dali.gaohongyu789.top/Article/details/gtjuiooxys.html

[G08] 静态方法与属性
来源：http://dali.jlsjyb.cn/Article/details/gteyyztwfc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.aibaodan.cn/Article/details/gtihjwxaxb.html

PHP:  public static function f() {}
来源：http://dali.zycfv.cn/Article/details/gtfbkwzxbn.html

JS:   static f() {}
来源：http://dali.xuanzx.com/Article/details/gtbdnipjnz.html

TS:   static f(): void {}
来源：http://dali.bjfxy.top/Article/details/gtdmxiksyz.html

Java: static void f() {}
来源：http://dali.meibo888.top/Article/details/gtwgliuuxf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.smart0.xyz/Article/details/gtrhsnvctt.html

Ruby: def self.f; end
来源：http://dali.xylfe.cn/Article/details/gtltifumkb.html

C#:   public static void F() {}
来源：http://dali.vqdsnc.cn/Article/details/gtuswubxvb.html

[G09] 接口 / 抽象类
来源：http://dali.nwbrower.top/Article/details/gtsggrchac.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbgonsvfs.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.smart0.xyz/Article/details/gtaxeoelqy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.pycfn.com/Article/details/gtreulceiw.html

TS:   interface Shape { area(): number; }
来源：http://dali.zdqjudy.top/Article/details/gtxkgmsgvc.html

Java: interface Shape { double area(); }
来源：http://dali.ehwqpu.com/Article/details/gtckylgkqq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtydxznmoq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hnxiangtu.top/Article/details/gtgsbhqtxn.html

C#:   interface IShape { double Area(); }
来源：http://dali.yanxiufei.cn/Article/details/gtbhtbibwj.html

[G10] 访问控制
来源：http://dali.iojbl.cn/Article/details/gttazrgpqh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hnqzz.top/Article/details/gtushcamfy.html

PHP:  public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gttgojnfta.html

JS:   #private 字段；其余公开
来源：http://dali.feifeiyinyue.top/Article/details/gtzomzbopo.html

TS:   public / protected / private
来源：http://dali.havefunace.top/Article/details/gtzjsiooac.html

Java: public / protected / private / 默认包级
来源：http://dali.gzhubu.top/Article/details/gtdjrayzvj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinqigufen.top/Article/details/gtfwjjwalw.html

Ruby: public / protected / private
来源：http://dali.jianghu66.top/Article/details/gtcswlhlod.html

C#:   public / protected / private / internal
来源：http://dali.andypj.xyz/Article/details/gtggsrrwlm.html

[G11] getter / setter
来源：http://dali.xuanzx.com/Article/details/gtysikuoca.html

Py:   @property 与 @x.setter
来源：http://dali.aibaodan.cn/Article/details/gttggwctgl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gtkqmgiivl.html

JS:   get name() { return this._name; }
来源：http://dali.cucudq.cn/Article/details/gtiqlratry.html

TS:   get name(): string { return this._name; }
来源：http://dali.yvedp.cn/Article/details/gtwhkgffol.html

Java: public String getName() { return name; }
来源：http://dali.sweek.top/Article/details/gtoxcbgvax.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gtmyoiognd.html

Ruby: attr_accessor :name
来源：http://dali.yj20258888.top/Article/details/gtcxhcuuxo.html

C#:   public string Name { get; set; }
来源：http://dali.meibo888.top/Article/details/gtrkhjuszo.html

[G12] 对象转字符串
来源：http://dali.meibo888.top/Article/details/gtksbzpjpv.html

Py:   def __str__(self): return self.name
来源：http://dali.chenzaomai.com/Article/details/gtdrrphbux.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gtaiymywjk.html

JS:   toString() { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gtyckdvkbm.html

TS:   toString(): string { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gtiuwmfkxj.html

Java: @Override public String toString() { return name; }
来源：http://dali.yueranfly.top/Article/details/gttrpvvupt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gtzhhavkqh.html

Ruby: def to_s; @name; end
来源：http://dali.cashguo.top/Article/details/gtxaxtdyvh.html

C#:   public override string ToString() => Name;
来源：http://dali.hnqzz.top/Article/details/gtqvkonplc.html

[G13] 判断对象类型
来源：http://dali.zhixingplan.top/Article/details/gtlfumsmzm.html

Py:   isinstance(u, User)
来源：http://dali.xinyue.icu/Article/details/gtpwmfxuan.html

PHP:  $u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkuvvofyo.html

JS:   u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtcmgczjes.html

TS:   u instanceof User
来源：http://dali.316326.xyz/Article/details/gtzcrsuupc.html


<!-- 参考信息 -->