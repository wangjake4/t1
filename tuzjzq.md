代发 wailian999

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.redwolf501.top/Article/details/gtrmcxlcvs.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gotoacloud.top/Article/details/gtxwufaksj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cucudq.cn/Article/details/gtdxamgjmy.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj20258888.top/Article/details/gtivdyeefh.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xziqi.cn/Article/details/gtcoqagpnl.html

[E15] HTML 转义 / 反转义
来源：http://dali.cqqwz.cn/Article/details/gtzwwidltx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cdnleiting.top/Article/details/gtlpbvrhdm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.iojbl.cn/Article/details/gtfsfjzbsc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtxkdwkkfx.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.aizwys.cn/Article/details/gtqexwejol.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhongyouzk.top/Article/details/gtnztxpxzw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.dashuyun.cn/Article/details/gtieftpvqf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmoycbdbf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.bjfxy.top/Article/details/gtuohykhkj.html

[E16] 数字千分位
来源：http://dali.jqgfzy.top/Article/details/gtarlhboko.html

Py:   f"{1234567:,}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtxttdpqef.html

PHP:  number_format(1234567);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtolyssbun.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gogol.net.cn/Article/details/gttldehbek.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.dianchejie.cn/Article/details/gtxgdkbxun.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmaxaixoz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ybcxt.top/Article/details/gtwtwdinut.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hywenlv.cn/Article/details/gtkzznqtix.html

C#:   1234567.ToString("N0")
来源：http://dali.zhixingplan.top/Article/details/gtjebngbcf.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gthvzfetnh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.quarkkingdee.top/Article/details/gtpgkdsetl.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.tianlin.xyz/Article/details/gtocllcemc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtejopxkwr.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnqzz.top/Article/details/gtoamgiqlo.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jiagoushi.top/Article/details/gtygqpzpdn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yongpay.top/Article/details/gtcyxvvhze.html

Ruby: s.capitalize
来源：http://dali.sweek.top/Article/details/gtimmepvdz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.bjfxy.top/Article/details/gtcqkyqlgz.html

[E18] 模板占位符替换
来源：http://dali.kuanghao11.cn/Article/details/gtmvgxacec.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hammf.cn/Article/details/gtrlffdruf.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ppjwa.cn/Article/details/gtucmmnonh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.nwbrower.top/Article/details/gtasmznflt.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yongpay.top/Article/details/gtcsvuiwio.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jqgfzy.top/Article/details/gtskrqkmnm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gtieiwxely.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.0kj1m.cn/Article/details/gtrwwulmza.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jlsjyb.cn/Article/details/gtqajycqhm.html

[E19] 多行文本按行拆分
来源：http://dali.zhixingplan.top/Article/details/gtduzuocmv.html

Py:   s.splitlines()
来源：http://dali.yuanzhike.top/Article/details/gtoyuygxoe.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gzhubu.top/Article/details/gtzqceqizo.html

JS:   s.split(/\r?\n/)
来源：http://dali.cucudq.cn/Article/details/gtgqbntmbs.html

TS:   s.split(/\r?\n/)
来源：http://dali.shangyingyoupin.top/Article/details/gtsemysmup.html

Java: s.lines().toList()
来源：http://dali.tanke756.top/Article/details/gtfdzckppn.html

Go:   strings.Split(s, "\n")
来源：http://dali.cqqwz.cn/Article/details/gtgdijhbal.html

Ruby: s.lines
来源：http://dali.jqgfzy.top/Article/details/gtesiylhpu.html

C#:   s.Split('\n')
来源：http://dali.shzxlz.cn/Article/details/gtdapiqroa.html

[E20] 判断字符串是否为空
来源：http://dali.yangfankeji.com/Article/details/gtnpiazgmb.html

Py:   if not s:
来源：http://dali.jlsjyb.cn/Article/details/gtoxqtwpht.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yuanzhike.top/Article/details/gtvdbkssse.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtuhjwoksc.html

TS:   if (s === "") {}
来源：http://dali.yonumen.top/Article/details/gtfeqazslq.html

Java: if (s.isEmpty()) {}
来源：http://dali.jqgfzy.top/Article/details/gtsfaaahck.html

Go:   if s == "" {}
来源：http://dali.pycfn.com/Article/details/gthpljaeyy.html

Ruby: if s.empty?
来源：http://dali.yonumen.top/Article/details/gttxnkjwbw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yj202588.top/Article/details/gtgwpkcrcj.html

[E21] 超长截断加省略号
来源：http://dali.havefunace.top/Article/details/gtedbkrunz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cqqwz.cn/Article/details/gtlqxvrcba.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gtdpuiajbp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fengsongda.top/Article/details/gtzwnlzloc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gtlcuahmjf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtjhnsusnm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinqigufen.top/Article/details/gtoukyijli.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtusmyotno.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtsoqhqjui.html

[E22] 字节长度与字符长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwstsecq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gthxwtwgij.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gtdimkaijt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.bjfxy.top/Article/details/gtfocgjryx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dashuyun.cn/Article/details/gtxlmsghay.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.fengsongda.top/Article/details/gtrxibzeux.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvlilvsey.html

Ruby: s.bytesize;  s.length
来源：http://dali.aizwys.cn/Article/details/gtenolospf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ivvv.top/Article/details/gtpnwsmuyb.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gttrzdlkks.html

F. 文件与目录
来源：http://dali.jiagoushi.top/Article/details/gtqmwyhcie.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtdiujgvqq.html

[F01] 读取整个文件
来源：http://dali.redwolf501.top/Article/details/gtzbgecuhg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zycfv.cn/Article/details/gtogfhspfg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtsgdzhzzz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.0kj1m.cn/Article/details/gtmbehpekn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shanyushiyangtech.top/Article/details/gttgxkfrbs.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gtjgqhadmi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nanxinkj.top/Article/details/gtkgfutdef.html

Ruby: File.read("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtdzqeyviz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtnebcvsro.html

[F02] 逐行读取文件
来源：http://dali.quarkkingdee.top/Article/details/gtlqsdmpzz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxufgrsla.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zdqjudy.top/Article/details/gtlntzghzp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.iojbl.cn/Article/details/gthnlytbyh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.quarkkingdee.top/Article/details/gtimhpvycd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tanke756.top/Article/details/gtlexizphg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gzhubu.top/Article/details/gtpmfqxmcj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ehwqpu.com/Article/details/gtfoissdaz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.aizwys.cn/Article/details/gtptapzcjc.html

[F03] 写入文件（覆盖）
来源：http://dali.cucudq.cn/Article/details/gtgzxxfbdu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.svipenyu.cn/Article/details/gtlkqoufer.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gogol.net.cn/Article/details/gtdpgzcylv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.iojbl.cn/Article/details/gtdqegqlew.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gtfzkwulle.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ybcxt.top/Article/details/gtnkrktirb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhengqikj.top/Article/details/gtfldfcayr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zdqjudy.top/Article/details/gtxfwxdiud.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgsnfssmd.html

[F04] 追加写入文件
来源：http://dali.bjfxy.top/Article/details/gtsmplrzjz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ydzc1.top/Article/details/gtniittyoi.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.pycfn.com/Article/details/gthdhzodpz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.quarkkingdee.top/Article/details/gtdecyyshy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.9152youxi.cn/Article/details/gtjxreknbp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.birdmap.top/Article/details/gtvhkeyvsn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cheryme.top/Article/details/gtzbenjsdx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.aibaodan.cn/Article/details/gtbwpvjjsa.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.smart0.xyz/Article/details/gtroxxkddl.html

[F05] 判断文件或目录是否存在
来源：http://dali.meibo888.top/Article/details/gtspiwckqf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shzxlz.cn/Article/details/gtiwgblsrf.html

PHP:  file_exists("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtbopihmdu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtzpurkdqz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtstzetvbf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gtfazbnbat.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ehwqpu.com/Article/details/gtwvhmzmqi.html

Ruby: File.exist?("a.txt")
来源：http://dali.fengsongda.top/Article/details/gteywrfwut.html

C#:   File.Exists("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtwlxojssw.html

[F06] 删除文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtivrrstza.html

Py:   os.remove("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gthonwujyd.html

PHP:  unlink("a.txt");
来源：http://dali.sweek.top/Article/details/gtjulkcahh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtuktnlpjn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtoruthuub.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gthrcxhmre.html

Go:   os.Remove("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtbmdzgpib.html

Ruby: File.delete("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtydryosim.html

C#:   File.Delete("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtuijjljul.html

[F07] 创建目录（含多级）
来源：http://dali.gogol.net.cn/Article/details/gtenhgkmfo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.andypj.xyz/Article/details/gtxmjxfacf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gtnddvakny.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.316326.xyz/Article/details/gtuvboxebv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenjidiqi.icu/Article/details/gtyekhoqpf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ppjwa.cn/Article/details/gtnxzzrvas.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.9152youxi.cn/Article/details/gtknlnyztc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.haohaochexian.top/Article/details/gtlzaagdpj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhongyouzk.top/Article/details/gtkibkznmi.html

[F08] 遍历目录
来源：http://dali.hnqzz.top/Article/details/gthsmpihug.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jiagoushi.top/Article/details/gtsycekini.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.dianchejie.cn/Article/details/gtwdupirpw.html

JS:   fs.readdirSync("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtbmiqrzka.html

TS:   fs.readdirSync("dir")
来源：http://dali.cucudq.cn/Article/details/gtpayupsqd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xylfe.cn/Article/details/gthctvirdg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nwbrower.top/Article/details/gtjzsooicr.html

Ruby: Dir.children("dir")
来源：http://dali.daxiang520.top/Article/details/gtogtyitwk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.fengsongda.top/Article/details/gtjkgicouf.html

[F09] 获取文件大小
来源：http://dali.feifeiyinyue.top/Article/details/gtnaxsxjvx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtwudzfmtn.html

PHP:  filesize("a.txt");
来源：http://dali.tanke756.top/Article/details/gtbkgswiuw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hnqzz.top/Article/details/gtqtdkvwlz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhoulong.xyz/Article/details/gtwvnafwmd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gtflqfywmk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gaohongyu789.top/Article/details/gtqermpxmn.html

Ruby: File.size("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtliyjejgc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.quarkkingdee.top/Article/details/gtscnjkgli.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jqgfzy.top/Article/details/gtddxzvcfb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtwowrjzdy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xziqi.cn/Article/details/gtkjgsedqj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtvcgrntxn.html

TS:   path.extname("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gttpefvcjm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jyoumei.cn/Article/details/gtvfuhtwqj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtuzqsuspc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gthsliaudn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtsghvwlgy.html

[F11] 复制与移动文件
来源：http://dali.yuanzhike.top/Article/details/gtavehqvza.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtheblkkmu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xinyue.icu/Article/details/gtrrdvtlco.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gtoexvlnkt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtnuksmcqe.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ehwqpu.com/Article/details/gteoxkmyla.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj20258888.top/Article/details/gtiagihuhy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gtrxapzwkw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj202588.top/Article/details/gtpefgyvwr.html

[F12] CSV 读写
来源：http://dali.jyoumei.cn/Article/details/gthxwjgnai.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.bjfxy.top/Article/details/gtfjinuntw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ehwqpu.com/Article/details/gtsppesabf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xylfe.cn/Article/details/gtojzkqxvk.html

TS:   // 同上
来源：http://dali.jianghu66.top/Article/details/gtxezyhnkl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.andypj.xyz/Article/details/gtkstglqet.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.feifeiyinyue.top/Article/details/gtsgzquyli.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.dashuyun.cn/Article/details/gtsyjzmwia.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cucudq.cn/Article/details/gtpflwjkec.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtdnzliqei.html

G. 面向对象
来源：http://dali.jqgfzy.top/Article/details/gtmukzszfn.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtycmelcoa.html

[G01] 定义类
来源：http://dali.pengpengdd.cyou/Article/details/gtvecumynk.html

Py:   class User: pass
来源：http://dali.yj20258.top/Article/details/gthonypvbv.html

PHP:  class User {}
来源：http://dali.cdnleiting.top/Article/details/gtzznpgtjq.html

JS:   class User {}
来源：http://dali.nanxuanxn.top/Article/details/gtmmcjtcxm.html

TS:   class User { name: string = ""; }
来源：http://dali.316326.xyz/Article/details/gtanmntmqw.html

Java: class User {}
来源：http://dali.nanxinkj.top/Article/details/gtojnpprsc.html

Go:   type User struct { Name string }
来源：http://dali.vqdsnc.cn/Article/details/gtxcezhmrq.html

Ruby: class User; end
来源：http://dali.aibaodan.cn/Article/details/gtnwckoezt.html

C#:   class User {}
来源：http://dali.jqgufenzy.top/Article/details/gtdvbkmept.html

[G02] 构造函数
来源：http://dali.hywenlv.cn/Article/details/gtlijunpdy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jqgfzy.top/Article/details/gtsiycjbfe.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yongpay.top/Article/details/gtfcahbmfv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sxryk.cn/Article/details/gtikyoipkn.html

TS:   constructor(public name: string) {}
来源：http://dali.fengsongda.top/Article/details/gtuemtzbuj.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gthnstboqe.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nanxuanxn.top/Article/details/gtdhbbeszp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ehwqpu.com/Article/details/gtfwguafdg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ydzc1.top/Article/details/gtvzhzbkmw.html

[G03] 实例属性
来源：http://dali.tianlin.xyz/Article/details/gtakdnnfok.html

Py:   self.name = "x"
来源：http://dali.nwbrower.top/Article/details/gtpyhbbbsc.html

PHP:  public string $name = "x";
来源：http://dali.ivvv.top/Article/details/gthlycvbhr.html

JS:   this.name = "x";
来源：http://dali.hfpthk.cn/Article/details/gthdldnuee.html

TS:   name: string = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdndqgqoz.html

Java: private String name;
来源：http://dali.zhengqikj.top/Article/details/gtdvdnygtz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.fzhhl.top/Article/details/gtxqhxyhvv.html

Ruby: @name = "x"
来源：http://dali.jinghuilouyu.cn/Article/details/gtollybbqi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzosstscw.html

[G04] 定义方法
来源：http://dali.yanxiufei.cn/Article/details/gtrpnyvrjp.html

Py:   def greet(self): return self.name
来源：http://dali.smart0.xyz/Article/details/gtnuxdcxth.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gtzrmpubgc.html

JS:   greet() { return this.name; }
来源：http://dali.meibo888.top/Article/details/gtuzojzace.html

TS:   greet(): string { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gtlewmswum.html

Java: String greet() { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdfybeyti.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gtuefkmmeg.html

Ruby: def greet; @name; end
来源：http://dali.daria6918.cn/Article/details/gttwvppcjj.html

C#:   public string Greet() => Name;
来源：http://dali.zhiwuduotai.top/Article/details/gtnzvoidsw.html

[G05] 继承
来源：http://dali.zhaomingkeji.xyz/Article/details/gtykoozccf.html

Py:   class Admin(User): pass
来源：http://dali.ivvv.top/Article/details/gtkksvexno.html

PHP:  class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtxgtrqkmn.html

JS:   class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtoakrjbmb.html

TS:   class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gthjianmxo.html

Java: class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gtsfwtieqw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.andypj.xyz/Article/details/gtdhacioye.html

Ruby: class Admin < User; end
来源：http://dali.fzhhl.top/Article/details/gttztbhqsj.html

C#:   class Admin : User {}
来源：http://dali.gzhubu.top/Article/details/gttxyjxndg.html

[G06] 重写方法
来源：http://dali.haohaochexian.top/Article/details/gtcnfcfabx.html

Py:   def greet(self): return "admin"
来源：http://dali.fengsongda.top/Article/details/gtmdwnrnau.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gtyglafflc.html

JS:   greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtigmmydcm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtbbjpezwj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gtkevlkusl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xuetiantiany.cn/Article/details/gtzmtpoabj.html

Ruby: def greet; "admin"; end
来源：http://dali.guannengcc.top/Article/details/gtymlguant.html

C#:   public override string Greet() => "admin";
来源：http://dali.guowangkeji.top/Article/details/gtqmqshwmg.html

[G07] 调用父类方法
来源：http://dali.zdqjudy.top/Article/details/gtwxvaiqsd.html

Py:   super().greet()
来源：http://dali.gotoacloud.top/Article/details/gtjxbblyyi.html

PHP:  parent::greet();
来源：http://dali.yuxming.cn/Article/details/gtrongpsav.html

JS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gtlekequwv.html

TS:   super.greet();
来源：http://dali.fzhhl.top/Article/details/gtqlhbbrzh.html

Java: super.greet();
来源：http://dali.yuxming.cn/Article/details/gtjghqgsfy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.birdmap.top/Article/details/gtrtvyrqex.html

Ruby: super
来源：http://dali.jiagoushi.top/Article/details/gtsrgqvhaa.html

C#:   base.Greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtbjkkjzpa.html

[G08] 静态方法与属性
来源：http://dali.yangfankeji.com/Article/details/gtwlvvgvov.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenzaomai.com/Article/details/gtxbmsjjsf.html

PHP:  public static function f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gtalzfqven.html

JS:   static f() {}
来源：http://dali.tian-w.cn/Article/details/gttgvfcncg.html

TS:   static f(): void {}
来源：http://dali.sweek.top/Article/details/gtaofpdcji.html

Java: static void f() {}
来源：http://dali.birdmap.top/Article/details/gtbktlfaib.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ivvv.top/Article/details/gtmkzxwqtn.html

Ruby: def self.f; end
来源：http://dali.snrcjt.cn/Article/details/gtjbwjchys.html

C#:   public static void F() {}
来源：http://dali.pycfn.com/Article/details/gtwzufbqba.html

[G09] 接口 / 抽象类
来源：http://dali.sufxvd.cn/Article/details/gtzhaufhkz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.daria6918.cn/Article/details/gtzbhveirf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xylfe.cn/Article/details/gtmayfevxc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xylfe.cn/Article/details/gtitegbisf.html

TS:   interface Shape { area(): number; }
来源：http://dali.havefunace.top/Article/details/gtmeoazfok.html

Java: interface Shape { double area(); }
来源：http://dali.redwolf501.top/Article/details/gthwsytctj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jqgfzy.top/Article/details/gtskinavaf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.c1oappe.top/Article/details/gthnpjxlvt.html

C#:   interface IShape { double Area(); }
来源：http://dali.gogol.net.cn/Article/details/gtkwnqbszi.html

[G10] 访问控制
来源：http://dali.cqqwz.cn/Article/details/gthggogamq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.pycfn.com/Article/details/gtvhkyyxid.html

PHP:  public / protected / private
来源：http://dali.andypj.xyz/Article/details/gtyojebcfw.html

JS:   #private 字段；其余公开
来源：http://dali.yanxiufei.cn/Article/details/gtompjoykc.html

TS:   public / protected / private
来源：http://dali.tian-w.cn/Article/details/gtmebwvibu.html

Java: public / protected / private / 默认包级
来源：http://dali.chenzaomai.com/Article/details/gtxksvfupf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gzhubu.top/Article/details/gtelidinqy.html

Ruby: public / protected / private
来源：http://dali.iojbl.cn/Article/details/gtojbhotbh.html

C#:   public / protected / private / internal
来源：http://dali.wangdashe.top/Article/details/gtntbaktsh.html

[G11] getter / setter
来源：http://dali.wangdashe.top/Article/details/gtlsvlhgbz.html

Py:   @property 与 @x.setter
来源：http://dali.yj202588.top/Article/details/gtgnsftssx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gtpxlldamk.html

JS:   get name() { return this._name; }
来源：http://dali.xziqi.cn/Article/details/gtcdproiwc.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhixingplan.top/Article/details/gtbgwfnntl.html

Java: public String getName() { return name; }
来源：http://dali.shuidangran.top/Article/details/gtnwcboumm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gtopkqevbb.html

Ruby: attr_accessor :name
来源：http://dali.tian-w.cn/Article/details/gtpovrquwp.html

C#:   public string Name { get; set; }
来源：http://dali.wangshuangyany.cn/Article/details/gtesfzqdhb.html

[G12] 对象转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtjquohgdw.html

Py:   def __str__(self): return self.name
来源：http://dali.jqgufenzy.top/Article/details/gtnjcsffsv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gtpvtwvldu.html

JS:   toString() { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtfguaevmn.html

TS:   toString(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtskqqzirk.html

Java: @Override public String toString() { return name; }
来源：http://dali.yuxming.cn/Article/details/gtgqdexadv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gtckveaumd.html

Ruby: def to_s; @name; end
来源：http://dali.shzxlz.cn/Article/details/gtripwioqs.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258888.top/Article/details/gtzezmfzkl.html

[G13] 判断对象类型
来源：http://dali.zhengqikj.top/Article/details/gtpktunval.html


<!-- 参考信息 -->