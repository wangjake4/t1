代发 wailian999

[E14] URL 编码与 Base64
来源：http://dali.tianlin.xyz/Article/details/gtsxxqubnx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shuidangran.top/Article/details/gtvnftiebq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zdqjudy.top/Article/details/gtxplesbpv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xziqi.cn/Article/details/gtprdaslcr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.fzhhl.top/Article/details/gtacjisgff.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.wangdashe.top/Article/details/gtlfqvukiq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.9152youxi.cn/Article/details/gteufzcypb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.fzhhl.top/Article/details/gtqlhdrysg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.c1oappe.top/Article/details/gtstwfctou.html

[E15] HTML 转义 / 反转义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtluusmyyk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hysaishi.cn/Article/details/gtlfojicfi.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.pycfn.com/Article/details/gtnglxlguw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ivvv.top/Article/details/gtnbfmixom.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yonumen.top/Article/details/gtatgpgvxs.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.aibaodan.cn/Article/details/gtnialzmay.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.daria6918.cn/Article/details/gtvaqedwzz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zdqjudy.top/Article/details/gtuxnkkgpn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.guowangkeji.top/Article/details/gtkqyvbugb.html

[E16] 数字千分位
来源：http://dali.ydzc1.top/Article/details/gtegkywdml.html

Py:   f"{1234567:,}"
来源：http://dali.fzhhl.top/Article/details/gtiuxsosdw.html

PHP:  number_format(1234567);
来源：http://dali.yanxiufei.cn/Article/details/gtcbejvcah.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hywenlv.cn/Article/details/gtlmkcyxam.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.guannengcc.top/Article/details/gtbmxrbjiz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cqqwz.cn/Article/details/gtgkqfoccu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sysykeji.top/Article/details/gtkraozilc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yvedp.cn/Article/details/gtfjlryael.html

C#:   1234567.ToString("N0")
来源：http://dali.chenlongwang.top/Article/details/gtznfwgbwb.html

[E17] 首字母大写
来源：http://dali.yongpay.top/Article/details/gtnvsijjzs.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.nwbrower.top/Article/details/gtboslmpfg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.bjfxy.top/Article/details/gtvrpggvbu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigufen.top/Article/details/gtffjjzyke.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cqqwz.cn/Article/details/gttoalvnkz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jiagoushi.top/Article/details/gtoppahsgo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.nanxinkj.top/Article/details/gttpfyfvei.html

Ruby: s.capitalize
来源：http://dali.birdmap.top/Article/details/gtvvpgjybe.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtefgudlxw.html

[E18] 模板占位符替换
来源：http://dali.sysykeji.top/Article/details/gtnohbcrln.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhiwuduotai.top/Article/details/gtswjlaewa.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.snrcjt.cn/Article/details/gtxfmdsqjl.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cashguo.top/Article/details/gtaigyemzs.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gtxpedmmvy.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gtmrangjky.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gtcjfwvwxx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.fengsongda.top/Article/details/gtrvogvweo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.tianlin.xyz/Article/details/gtceaifdca.html

[E19] 多行文本按行拆分
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzunaxrfb.html

Py:   s.splitlines()
来源：http://dali.ybcxt.top/Article/details/gtfwbhyzrg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtrsklickq.html

JS:   s.split(/\r?\n/)
来源：http://dali.hnqzz.top/Article/details/gttyysdqie.html

TS:   s.split(/\r?\n/)
来源：http://dali.yueranfly.top/Article/details/gtifihsecq.html

Java: s.lines().toList()
来源：http://dali.aizwys.cn/Article/details/gtdazulxxp.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gtkrdspslg.html

Ruby: s.lines
来源：http://dali.yongpay.top/Article/details/gtagmxtifl.html

C#:   s.Split('\n')
来源：http://dali.ivvv.top/Article/details/gthvcmevio.html

[E20] 判断字符串是否为空
来源：http://dali.gaohongyu789.top/Article/details/gtswetpdbn.html

Py:   if not s:
来源：http://dali.kuanghao11.cn/Article/details/gtyngxkxvi.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhongyouzk.top/Article/details/gtezxggxka.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.316326.xyz/Article/details/gtsfhsnndq.html

TS:   if (s === "") {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtvvhrhshc.html

Java: if (s.isEmpty()) {}
来源：http://dali.kuanghao11.cn/Article/details/gtrmgeilih.html

Go:   if s == "" {}
来源：http://dali.yongpay.top/Article/details/gtmwyuzusu.html

Ruby: if s.empty?
来源：http://dali.cqqwz.cn/Article/details/gtxssyhehl.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.haohaochexian.top/Article/details/gtxxrjnxjf.html

[E21] 超长截断加省略号
来源：http://dali.fengsongda.top/Article/details/gtagviguhd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yvedp.cn/Article/details/gtmaializj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gtlahabibi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gtkhwdjveb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sweek.top/Article/details/gtqdpxwqte.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtgogvbnne.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zdqjudy.top/Article/details/gtgmtyubph.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yueranfly.top/Article/details/gtpbyyusww.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtahimkaql.html

[E22] 字节长度与字符长度
来源：http://dali.kuanghao11.cn/Article/details/gtpxzggovq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yangfankeji.com/Article/details/gtfdroxohc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gtsprftywb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnxiangtu.top/Article/details/gthojwyaxy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guannengcc.top/Article/details/gtyudyyemc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.dianchejie.cn/Article/details/gtuqvbxvip.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ehwqpu.com/Article/details/gtjlfuqokf.html

Ruby: s.bytesize;  s.length
来源：http://dali.jiagoushi.top/Article/details/gtwzmwaiux.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.redwolf501.top/Article/details/gthxxzdaxd.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gttyudvdce.html

F. 文件与目录
来源：http://dali.mhx1999.top/Article/details/gtekhtdzrc.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtnrvzhquy.html

[F01] 读取整个文件
来源：http://dali.shangyingyoupin.top/Article/details/gtydflnzam.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhongyouzk.top/Article/details/gtvbsltsmn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtnekqhuet.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhongyouzk.top/Article/details/gtrtfbouaz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gtklhzmqid.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gtbnpdlgdn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenlongwang.top/Article/details/gtlkjfqgem.html

Ruby: File.read("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gttjkbpmlx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtezaolitr.html

[F02] 逐行读取文件
来源：http://dali.0kj1m.cn/Article/details/gthnraqgdt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.redwolf501.top/Article/details/gthylbqfpm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.vqdsnc.cn/Article/details/gtjvbhihrk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sysykeji.top/Article/details/gtbmvilono.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hfpthk.cn/Article/details/gtfrkmrerg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhixingplan.top/Article/details/gtnearotba.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzcvspysq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xziqi.cn/Article/details/gtmjhvdhcq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinqigufen.top/Article/details/gtbmymscwm.html

[F03] 写入文件（覆盖）
来源：http://dali.jinqigufen.top/Article/details/gtamkftysr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hnxiangtu.top/Article/details/gtiqziaump.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.aibaodan.cn/Article/details/gtvmfyqzyl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gtiljpbrdn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.pycfn.com/Article/details/gtdjcaqpcb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhengqikj.top/Article/details/gtoxldsqtp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sufxvd.cn/Article/details/gtmdixggpk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.havefunace.top/Article/details/gtxszolepu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwtxjpuso.html

[F04] 追加写入文件
来源：http://dali.xylfe.cn/Article/details/gtmhuzltzp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hnxiangtu.top/Article/details/gthcracmjw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yj20258888.top/Article/details/gtburaqdtc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangdashe.top/Article/details/gtwlqwkhzz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnxiangtu.top/Article/details/gtmwqrcelb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.mhx1999.top/Article/details/gtxbkycike.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.svipenyu.cn/Article/details/gtsuqzdudz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sysykeji.top/Article/details/gtrxmizioj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.quarkkingdee.top/Article/details/gtlihopgfb.html

[F05] 判断文件或目录是否存在
来源：http://dali.cqqwz.cn/Article/details/gtqamjnnlk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ehwqpu.com/Article/details/gtsybzdlal.html

PHP:  file_exists("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtdadrftul.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtgamkpbif.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtyokogans.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtcnagfnaw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjcajbomo.html

Ruby: File.exist?("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtrqdkbrpn.html

C#:   File.Exists("a.txt")
来源：http://dali.pycfn.com/Article/details/gtjjmscltp.html

[F06] 删除文件
来源：http://dali.cucudq.cn/Article/details/gtpqpmqpiv.html

Py:   os.remove("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtqddyhwzg.html

PHP:  unlink("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtuwngesss.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtkyblzgok.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtjpuzfmyd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtfgcqwnyy.html

Go:   os.Remove("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtvzjeqxux.html

Ruby: File.delete("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtjubqhrzn.html

C#:   File.Delete("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkoouvqek.html

[F07] 创建目录（含多级）
来源：http://dali.jianghu66.top/Article/details/gtritbfeih.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gaohongyu789.top/Article/details/gtpbilcwkb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.aibaodan.cn/Article/details/gtvctzykqc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.0kj1m.cn/Article/details/gtkkkkukxx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cdnleiting.top/Article/details/gtakpaqkmg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.chenzaomai.com/Article/details/gtrqvxefds.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yangfankeji.com/Article/details/gtwcuqxrxb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zycfv.cn/Article/details/gtrkgzqxnf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hfpthk.cn/Article/details/gtmslyovqb.html

[F08] 遍历目录
来源：http://dali.dashuyun.cn/Article/details/gtoetzbqil.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.9152youxi.cn/Article/details/gtwxxkmcve.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yuanzhike.top/Article/details/gtngecwcye.html

JS:   fs.readdirSync("dir")
来源：http://dali.ppjwa.cn/Article/details/gtacmutvgj.html

TS:   fs.readdirSync("dir")
来源：http://dali.dianchejie.cn/Article/details/gtpvfivijv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gtmgrtaous.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtvyaywvlw.html

Ruby: Dir.children("dir")
来源：http://dali.andypj.xyz/Article/details/gthmkoyczg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinqigufen.top/Article/details/gtzdzuuryw.html

[F09] 获取文件大小
来源：http://dali.9152youxi.cn/Article/details/gtxhwutyns.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtcfupjboy.html

PHP:  filesize("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtnagkmext.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gzhubu.top/Article/details/gtrjubpidj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cqqwz.cn/Article/details/gtphzxqjco.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gteivsnrdc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.guannengcc.top/Article/details/gtltyzdoqh.html

Ruby: File.size("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtnxwwnond.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhiwuduotai.top/Article/details/gtrrgpkian.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.wangshuangyany.cn/Article/details/gtnaamrnix.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtihnkkyas.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrekwukyi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gthwbobnvb.html

TS:   path.extname("a.txt")
来源：http://dali.meibo888.top/Article/details/gtmpaliyti.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhengqikj.top/Article/details/gtquusulua.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtfkuofepk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtolxkdjvv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtrdbohhoy.html

[F11] 复制与移动文件
来源：http://dali.fzhhl.top/Article/details/gtgrqjajbv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gtsrppbdpu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtrbaidttg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtgvmchfon.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gttltoiptj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ppjwa.cn/Article/details/gtoumnqfms.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.bjfxy.top/Article/details/gtdmwoveop.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gtgdnejqlx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ybcxt.top/Article/details/gtdbosifhn.html

[F12] CSV 读写
来源：http://dali.shanyushiyangkeji.top/Article/details/gtebnvficl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthjmhqbgv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhengqikj.top/Article/details/gtfqxaytwx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hnxiangtu.top/Article/details/gtnbthvkui.html

TS:   // 同上
来源：http://dali.mhx1999.top/Article/details/gtazwxisve.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sysykeji.top/Article/details/gttpgzlico.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcrimcuqr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.tianlin.xyz/Article/details/gtbalkjyws.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinqigfzy.top/Article/details/gtxluhatkp.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gttanbqoij.html

G. 面向对象
来源：http://dali.yonumen.top/Article/details/gtvfoqpvfr.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtbylsxtmg.html

[G01] 定义类
来源：http://dali.jqgfzy.top/Article/details/gtrktcfcfy.html

Py:   class User: pass
来源：http://dali.chenzaomai.com/Article/details/gtjgckhyoh.html

PHP:  class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtjsiuoyoz.html

JS:   class User {}
来源：http://dali.svipenyu.cn/Article/details/gtnrqbzopv.html

TS:   class User { name: string = ""; }
来源：http://dali.zycfv.cn/Article/details/gtgiuwcamg.html

Java: class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtyszjnzjf.html

Go:   type User struct { Name string }
来源：http://dali.cheryme.top/Article/details/gtfyjgvloo.html

Ruby: class User; end
来源：http://dali.zhiwuduotai.top/Article/details/gtnmhoobcj.html

C#:   class User {}
来源：http://dali.shzxlz.cn/Article/details/gtftiowhtn.html

[G02] 构造函数
来源：http://dali.jinqigufen.top/Article/details/gtiwevjqwm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.havefunace.top/Article/details/gtveeoeekh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtfzakrsdw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tianlin.xyz/Article/details/gtxorxdxch.html

TS:   constructor(public name: string) {}
来源：http://dali.jianghu66.top/Article/details/gtilsntmjq.html

Java: User(String name) { this.name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthnraergn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.chenjidiqi.icu/Article/details/gtiqwupvlu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gotoacloud.top/Article/details/gtfvmfyedn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.dianchejie.cn/Article/details/gtmmqjntlq.html

[G03] 实例属性
来源：http://dali.pengpengdd.cyou/Article/details/gtaftxepzh.html

Py:   self.name = "x"
来源：http://dali.yvedp.cn/Article/details/gtdbbnkymy.html

PHP:  public string $name = "x";
来源：http://dali.xuanzx.com/Article/details/gtrtnrwusn.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gtosbdtbrf.html

TS:   name: string = "x";
来源：http://dali.hywenlv.cn/Article/details/gtdxtkbnto.html

Java: private String name;
来源：http://dali.daxiang520.top/Article/details/gtuqpdbcre.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tian-w.cn/Article/details/gtyskfedjz.html

Ruby: @name = "x"
来源：http://dali.cheryme.top/Article/details/gtrprpuhjm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yanxiufei.cn/Article/details/gtxvpyyyvn.html

[G04] 定义方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxidetyql.html

Py:   def greet(self): return self.name
来源：http://dali.pycfn.com/Article/details/gtmjwmmtmc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shzxlz.cn/Article/details/gtdtgaumbj.html

JS:   greet() { return this.name; }
来源：http://dali.sweek.top/Article/details/gtotarstml.html

TS:   greet(): string { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gtacadpadn.html

Java: String greet() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gttiyddwlj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.feifeiyinyue.top/Article/details/gtamopfqrk.html

Ruby: def greet; @name; end
来源：http://dali.aizwys.cn/Article/details/gtjzkbmyod.html

C#:   public string Greet() => Name;
来源：http://dali.mhx1999.top/Article/details/gtxcekmoeq.html

[G05] 继承
来源：http://dali.snrcjt.cn/Article/details/gtqqusqand.html

Py:   class Admin(User): pass
来源：http://dali.redwolf501.top/Article/details/gtipwyyofv.html

PHP:  class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gtqugelijg.html

JS:   class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gthjspszlu.html

TS:   class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gtqdrfijjv.html

Java: class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtlhktyxam.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shangyingyoupin.top/Article/details/gtoxtwyhbq.html

Ruby: class Admin < User; end
来源：http://dali.yangfankeji.com/Article/details/gtptljahbs.html

C#:   class Admin : User {}
来源：http://dali.yueranfly.top/Article/details/gtacuayxey.html

[G06] 重写方法
来源：http://dali.mhx1999.top/Article/details/gtkwckzdhe.html

Py:   def greet(self): return "admin"
来源：http://dali.aibaodan.cn/Article/details/gtevqmtxkv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gtfwgzidwt.html

JS:   greet() { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvcjpffho.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtfgbwwbri.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gtakhqrzof.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.pycfn.com/Article/details/gtmcubbzxv.html

Ruby: def greet; "admin"; end
来源：http://dali.cashguo.top/Article/details/gtzfirzcyq.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhoulong.xyz/Article/details/gtsunvwewz.html

[G07] 调用父类方法
来源：http://dali.ivvv.top/Article/details/gtkdydiazn.html

Py:   super().greet()
来源：http://dali.jlsjyb.cn/Article/details/gtzswreexz.html

PHP:  parent::greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gttslssgzy.html

JS:   super.greet();
来源：http://dali.fzhhl.top/Article/details/gtzpaxqsph.html

TS:   super.greet();
来源：http://dali.redwolf501.top/Article/details/gtdeoivzwc.html

Java: super.greet();
来源：http://dali.fengsongda.top/Article/details/gtsffglffl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj202588.top/Article/details/gtorampyhe.html

Ruby: super
来源：http://dali.tanke756.top/Article/details/gtduzdwzhl.html

C#:   base.Greet();
来源：http://dali.jinqigufen.top/Article/details/gtiskloeez.html

[G08] 静态方法与属性
来源：http://dali.cdnleiting.top/Article/details/gtpcfrkviy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hnqzz.top/Article/details/gtlfkjqwux.html

PHP:  public static function f() {}
来源：http://dali.aibaodan.cn/Article/details/gtdxyeintk.html

JS:   static f() {}
来源：http://dali.cdnleiting.top/Article/details/gtavpuqkec.html

TS:   static f(): void {}
来源：http://dali.birdmap.top/Article/details/gttzklfjym.html

Java: static void f() {}
来源：http://dali.ppjwa.cn/Article/details/gtbipbsoso.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenzaomai.com/Article/details/gtekawcseq.html

Ruby: def self.f; end
来源：http://dali.wangdashe.top/Article/details/gteqrpjnns.html

C#:   public static void F() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gthzrcibbi.html

[G09] 接口 / 抽象类
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmftxugbm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.birdmap.top/Article/details/gtwgquwqpa.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.0kj1m.cn/Article/details/gtjfsdabiv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ybcxt.top/Article/details/gtklqqqsul.html

TS:   interface Shape { area(): number; }
来源：http://dali.meibo888.top/Article/details/gtkzeokszw.html

Java: interface Shape { double area(); }
来源：http://dali.haohaochexian.top/Article/details/gtpiyinuvy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shzxlz.cn/Article/details/gtefjoemiv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gtvcsmmwpn.html

C#:   interface IShape { double Area(); }
来源：http://dali.tianlin.xyz/Article/details/gttvvmamon.html

[G10] 访问控制
来源：http://dali.sysykeji.top/Article/details/gtucmimhcx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.c1oappe.top/Article/details/gtwsaysssv.html

PHP:  public / protected / private
来源：http://dali.xinyue.icu/Article/details/gtnokiqeat.html

JS:   #private 字段；其余公开
来源：http://dali.nanxinkj.top/Article/details/gtphwtwxmy.html

TS:   public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gttxfmaakv.html

Java: public / protected / private / 默认包级
来源：http://dali.shuidangran.top/Article/details/gtgfyxjpet.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj202588.top/Article/details/gtddmeoizf.html

Ruby: public / protected / private
来源：http://dali.sxryk.cn/Article/details/gtcigerqej.html

C#:   public / protected / private / internal
来源：http://dali.jyoumei.cn/Article/details/gtgevzsytp.html

[G11] getter / setter
来源：http://dali.316326.xyz/Article/details/gtkxjpcuqp.html

Py:   @property 与 @x.setter
来源：http://dali.ivvv.top/Article/details/gtnqndclsv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gtlohfwrlb.html

JS:   get name() { return this._name; }
来源：http://dali.sweek.top/Article/details/gtjryhggtw.html

TS:   get name(): string { return this._name; }
来源：http://dali.cucudq.cn/Article/details/gtcmcgsbfl.html

Java: public String getName() { return name; }
来源：http://dali.cashguo.top/Article/details/gtboxaxkeg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gtxsjsajbl.html

Ruby: attr_accessor :name
来源：http://dali.bjfxy.top/Article/details/gttkeoijrr.html

C#:   public string Name { get; set; }
来源：http://dali.316326.xyz/Article/details/gtcpwwqbgk.html

[G12] 对象转字符串
来源：http://dali.ppjwa.cn/Article/details/gtksaecila.html

Py:   def __str__(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gturywimzk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gtiitnganx.html

JS:   toString() { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtvqnqwgva.html

TS:   toString(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtcmdewrzn.html

Java: @Override public String toString() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtwfyawzrs.html


<!-- 参考信息 -->