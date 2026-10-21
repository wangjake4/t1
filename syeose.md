代发 wailian999

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.aibaodan.cn/Article/details/gtzhzomyaf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sxryk.cn/Article/details/gtcacdcmvn.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jqgufenzy.top/Article/details/gtgfshugyz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.dianchejie.cn/Article/details/gtvrkziksp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yuxming.cn/Article/details/gtbwxgfykg.html

[E15] HTML 转义 / 反转义
来源：http://dali.svipenyu.cn/Article/details/gtvtbfxyzf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhongyouzk.top/Article/details/gtmwngbgcn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.guannengcc.top/Article/details/gtjznakyfd.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jqgfzy.top/Article/details/gtvoktqshv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinqigfzy.top/Article/details/gtnvnwstan.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hysaishi.cn/Article/details/gtwvolhsrk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gaohongyu789.top/Article/details/gtmzrpisug.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtaaaxnfnz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jinqigfzy.top/Article/details/gtdbqesaeb.html

[E16] 数字千分位
来源：http://dali.yj20258888.top/Article/details/gtpldirxux.html

Py:   f"{1234567:,}"
来源：http://dali.ydzc1.top/Article/details/gticruggpv.html

PHP:  number_format(1234567);
来源：http://dali.zhongyouzk.top/Article/details/gtwmiizamr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jiagoushi.top/Article/details/gteluvniyw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhixingplan.top/Article/details/gtvbkwdlop.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhengqikj.top/Article/details/gtevqqfduy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.quarkkingdee.top/Article/details/gtgeabivuz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.nanxinkj.top/Article/details/gtbkhhbrmz.html

C#:   1234567.ToString("N0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwfrxcbpz.html

[E17] 首字母大写
来源：http://dali.jinghuilouyu.cn/Article/details/gteaacycem.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.0kj1m.cn/Article/details/gtkixaqurz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.guowangkeji.top/Article/details/gthukoyisb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gotoacloud.top/Article/details/gtdslvhhbq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigfzy.top/Article/details/gtkiwppifv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yueranfly.top/Article/details/gtvhqnvtpk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gtofynwxjv.html

Ruby: s.capitalize
来源：http://dali.hongshengwenyu.top/Article/details/gtzzfrhknl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj202588.top/Article/details/gtetuaguzx.html

[E18] 模板占位符替换
来源：http://dali.aibaodan.cn/Article/details/gtgbcupsbc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jianghu66.top/Article/details/gtxbearpxa.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.guannengcc.top/Article/details/gtqvlrbdty.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gtdeqkxftj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gtvqlzcnnn.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gtysswhjii.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.c1oappe.top/Article/details/gtidmxllpp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.fengsongda.top/Article/details/gtlslgmojg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhiwuduotai.top/Article/details/gtimubusxw.html

[E19] 多行文本按行拆分
来源：http://dali.chenzaomai.com/Article/details/gttmwicayq.html

Py:   s.splitlines()
来源：http://dali.guowangkeji.top/Article/details/gtvpitnofw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zycfv.cn/Article/details/gtmjnstqnq.html

JS:   s.split(/\r?\n/)
来源：http://dali.yueranfly.top/Article/details/gtudhasjog.html

TS:   s.split(/\r?\n/)
来源：http://dali.meibo888.top/Article/details/gtqgpcvcsv.html

Java: s.lines().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtehkcxcgy.html

Go:   strings.Split(s, "\n")
来源：http://dali.nwbrower.top/Article/details/gtlffnetcv.html

Ruby: s.lines
来源：http://dali.hnxiangtu.top/Article/details/gtfddcpfzd.html

C#:   s.Split('\n')
来源：http://dali.shanyushiyangtech.top/Article/details/gtgdievtnu.html

[E20] 判断字符串是否为空
来源：http://dali.sufxvd.cn/Article/details/gtaorkisub.html

Py:   if not s:
来源：http://dali.nwbrower.top/Article/details/gtbzcrdfhi.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cdnleiting.top/Article/details/gtoowxvvtq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xuanzx.com/Article/details/gtyuglgkzq.html

TS:   if (s === "") {}
来源：http://dali.xylfe.cn/Article/details/gtxgegqixq.html

Java: if (s.isEmpty()) {}
来源：http://dali.hysaishi.cn/Article/details/gtawhqvzlw.html

Go:   if s == "" {}
来源：http://dali.zhengqikj.top/Article/details/gtqfdpmnmf.html

Ruby: if s.empty?
来源：http://dali.iojbl.cn/Article/details/gtvokmncan.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jiagoushi.top/Article/details/gtenzyhzfb.html

[E21] 超长截断加省略号
来源：http://dali.yuxming.cn/Article/details/gthpmjfqka.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.meibo888.top/Article/details/gtzitvshzz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gtonswwmaf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gttmhbcbsj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtegjsmydz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtzbcriphd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhiwuduotai.top/Article/details/gtldqghvis.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gtflpfzois.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtdznghdux.html

[E22] 字节长度与字符长度
来源：http://dali.0kj1m.cn/Article/details/gtjlehqowl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yuanzhike.top/Article/details/gtaoyreebs.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gtzpzuqfgb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gtgigtapcf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnxiangtu.top/Article/details/gtcuchqcxm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hfpthk.cn/Article/details/gthdacjwse.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.mhx1999.top/Article/details/gtybyxtlah.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gtsvvrddpj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sysykeji.top/Article/details/gtbbyfupys.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtwztkbcwi.html

F. 文件与目录
来源：http://dali.zhongyouzk.top/Article/details/gtvgnpkxac.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gttqvnctwo.html

[F01] 读取整个文件
来源：http://dali.gaohongyu789.top/Article/details/gteggswtmh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.mhx1999.top/Article/details/gtohfryogb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtdzvxpttb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.birdmap.top/Article/details/gtazaxjtlr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gtqzzulnwt.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gttjtjfcgq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.316326.xyz/Article/details/gtckkihhlx.html

Ruby: File.read("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtmfcqcobo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtlivltotl.html

[F02] 逐行读取文件
来源：http://dali.gotoacloud.top/Article/details/gtijfolwll.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.9152youxi.cn/Article/details/gtsjkqgwxj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jyoumei.cn/Article/details/gtsnfdagfx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yanxiufei.cn/Article/details/gtszlsclky.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258.top/Article/details/gtoksyqwic.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shuidangran.top/Article/details/gtbxyfgjus.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.dianchejie.cn/Article/details/gtuzqaztgt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yongpay.top/Article/details/gtnwbdumpu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nwbrower.top/Article/details/gtduamshgt.html

[F03] 写入文件（覆盖）
来源：http://dali.jqgfzy.top/Article/details/gtwgybfomx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hongshengwenyu.top/Article/details/gtoysezsyd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tanke756.top/Article/details/gtuqyrlvbg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fengsongda.top/Article/details/gtvicdxvuw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cashguo.top/Article/details/gtqkpzrwoa.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hywenlv.cn/Article/details/gttpjazmts.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gogol.net.cn/Article/details/gtamhstnti.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zdqjudy.top/Article/details/gtkhvefywo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ppjwa.cn/Article/details/gtcqnqcvwn.html

[F04] 追加写入文件
来源：http://dali.cheryme.top/Article/details/gtmkevkjnk.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sxryk.cn/Article/details/gtgjtpwiiz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cashguo.top/Article/details/gtaiutifjw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.quarkkingdee.top/Article/details/gtpamwqvlg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtisrjpkam.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.havefunace.top/Article/details/gtsiksnnfu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cucudq.cn/Article/details/gtkffdgfay.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hysaishi.cn/Article/details/gtmscrndev.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ybcxt.top/Article/details/gtiqxgjlab.html

[F05] 判断文件或目录是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtlejigbpb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tian-w.cn/Article/details/gtepmgrpkm.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtzvfjemjl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtngkejopr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sweek.top/Article/details/gtrjlkjbka.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gttjoivdrs.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yvedp.cn/Article/details/gtmmmbhkio.html

Ruby: File.exist?("a.txt")
来源：http://dali.316326.xyz/Article/details/gthnquzzgr.html

C#:   File.Exists("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgpkqkhtx.html

[F06] 删除文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtieyhvkax.html

Py:   os.remove("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtkfgvccyy.html

PHP:  unlink("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gthvalhhqu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gthigvfpqr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtggtxaeow.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gtnqlvybyq.html

Go:   os.Remove("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtlrmzegop.html

Ruby: File.delete("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtupugstfj.html

C#:   File.Delete("a.txt");
来源：http://dali.hammf.cn/Article/details/gtprffhfzp.html

[F07] 创建目录（含多级）
来源：http://dali.hongshengwenyu.top/Article/details/gtvdfmipzc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj20258888.top/Article/details/gtbtkohdtu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj202588.top/Article/details/gtqnhvluro.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yvedp.cn/Article/details/gttkzwmkff.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pycfn.com/Article/details/gtmzksgmir.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yanxiufei.cn/Article/details/gtddxrtcmw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hysaishi.cn/Article/details/gtqpjgkkzi.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenjidiqi.icu/Article/details/gtiplclfdp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.redwolf501.top/Article/details/gtgfewuexe.html

[F08] 遍历目录
来源：http://dali.zycfv.cn/Article/details/gtipvpxevz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.fzhhl.top/Article/details/gttloudqkh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.redwolf501.top/Article/details/gtmkgmxziw.html

JS:   fs.readdirSync("dir")
来源：http://dali.yueranfly.top/Article/details/gtrqcwqtfx.html

TS:   fs.readdirSync("dir")
来源：http://dali.sysykeji.top/Article/details/gtgdjuuvau.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hysaishi.cn/Article/details/gtitqdflts.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nwbrower.top/Article/details/gtaexophlj.html

Ruby: Dir.children("dir")
来源：http://dali.guannengcc.top/Article/details/gtbwtinqtg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtolawlang.html

[F09] 获取文件大小
来源：http://dali.nanxinkj.top/Article/details/gtvsgquvzm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtdmmrhnzx.html

PHP:  filesize("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtbcxlnoes.html

JS:   fs.statSync("a.txt").size
来源：http://dali.havefunace.top/Article/details/gtfvykfytx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yangfankeji.com/Article/details/gtqvwzvcvr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gtbptszjic.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yanxiufei.cn/Article/details/gtccipanjw.html

Ruby: File.size("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtcpieqjhb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shzxlz.cn/Article/details/gtmfiuzrmn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhengqikj.top/Article/details/gtxjhjnakc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gtfbyqkwzf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtpacurmpp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtappcsipa.html

TS:   path.extname("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtfuqlasrp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shanyushiyangtech.top/Article/details/gtthojosqm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gtrdxmmbtv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gtimeqjgqq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtpsrzyafv.html

[F11] 复制与移动文件
来源：http://dali.aizwys.cn/Article/details/gtnyniffxg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gtkdheengx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.aizwys.cn/Article/details/gtyitjbyxs.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtanvgddwg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gtkytzjmzg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yonumen.top/Article/details/gtxsurqmxt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.316326.xyz/Article/details/gtpoovephw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gtsebyeexn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhoulong.xyz/Article/details/gtpjaioguv.html

[F12] CSV 读写
来源：http://dali.zhixingplan.top/Article/details/gthqbzdtnz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.guannengcc.top/Article/details/gtzpuartfa.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenlongwang.top/Article/details/gtbbflasnt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.quarkkingdee.top/Article/details/gtwcmzqlpa.html

TS:   // 同上
来源：http://dali.yonumen.top/Article/details/gtqpeewfeu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.daxiang520.top/Article/details/gtvojnelpa.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnvvfjfoa.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenjidiqi.icu/Article/details/gtunackumr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ehwqpu.com/Article/details/gtnfuerpca.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gthtgukwlj.html

G. 面向对象
来源：http://dali.hammf.cn/Article/details/gtxzwntusg.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtwczqhikv.html

[G01] 定义类
来源：http://dali.snrcjt.cn/Article/details/gtsvndbfja.html

Py:   class User: pass
来源：http://dali.sweek.top/Article/details/gtkfkeaykt.html

PHP:  class User {}
来源：http://dali.andypj.xyz/Article/details/gtsckrusug.html

JS:   class User {}
来源：http://dali.gotoacloud.top/Article/details/gtkgjdhokj.html

TS:   class User { name: string = ""; }
来源：http://dali.wangshuangyany.cn/Article/details/gtsnbktrch.html

Java: class User {}
来源：http://dali.316326.xyz/Article/details/gtadhsdzym.html

Go:   type User struct { Name string }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrlourvba.html

Ruby: class User; end
来源：http://dali.chenlongwang.top/Article/details/gtdxxwopfc.html

C#:   class User {}
来源：http://dali.jyoumei.cn/Article/details/gtcaqrfhqx.html

[G02] 构造函数
来源：http://dali.xylfe.cn/Article/details/gtbeaibxtd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sufxvd.cn/Article/details/gtboyonmdz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.smart0.xyz/Article/details/gtorugsfao.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinqigufen.top/Article/details/gtfnntliyd.html

TS:   constructor(public name: string) {}
来源：http://dali.meibo888.top/Article/details/gtmnwwgffy.html

Java: User(String name) { this.name = name; }
来源：http://dali.sweek.top/Article/details/gtzuckvgnh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.quarkkingdee.top/Article/details/gtldjjjyls.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jqgufenzy.top/Article/details/gtuarifdkx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zdqjudy.top/Article/details/gtcpclxlox.html

[G03] 实例属性
来源：http://dali.redwolf501.top/Article/details/gtczysglbn.html

Py:   self.name = "x"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuzfzyaxn.html

PHP:  public string $name = "x";
来源：http://dali.ydzc1.top/Article/details/gtwretitnc.html

JS:   this.name = "x";
来源：http://dali.fzhhl.top/Article/details/gtvdmblkjt.html

TS:   name: string = "x";
来源：http://dali.dashuyun.cn/Article/details/gtvjdebmvt.html

Java: private String name;
来源：http://dali.aizwys.cn/Article/details/gtpuhlpgbv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.quarkkingdee.top/Article/details/gtacoxswms.html

Ruby: @name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gtowjlunbm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hysaishi.cn/Article/details/gtugknofgv.html

[G04] 定义方法
来源：http://dali.sweek.top/Article/details/gtmeocrpxx.html

Py:   def greet(self): return self.name
来源：http://dali.hnxiangtu.top/Article/details/gtxlytyzkf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gthklbamsu.html

JS:   greet() { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkaucxzha.html

TS:   greet(): string { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gtepmupxza.html

Java: String greet() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtsjiaqznx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gtftzaggjn.html

Ruby: def greet; @name; end
来源：http://dali.cqqwz.cn/Article/details/gtofilmcco.html

C#:   public string Greet() => Name;
来源：http://dali.pengpengdd.cyou/Article/details/gtxatvqaqs.html

[G05] 继承
来源：http://dali.dashuyun.cn/Article/details/gtdrchkyov.html

Py:   class Admin(User): pass
来源：http://dali.vqdsnc.cn/Article/details/gtqvlfixqi.html

PHP:  class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gtrbkjzmlk.html

JS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtauskupba.html

TS:   class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gtmzvyeceq.html

Java: class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtetwsrqlz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shangyingyoupin.top/Article/details/gtuehafejz.html

Ruby: class Admin < User; end
来源：http://dali.sufxvd.cn/Article/details/gtihpsmhjx.html

C#:   class Admin : User {}
来源：http://dali.hnqzz.top/Article/details/gtxzfxaegu.html

[G06] 重写方法
来源：http://dali.hammf.cn/Article/details/gtxxuzrvfo.html

Py:   def greet(self): return "admin"
来源：http://dali.haohaochexian.top/Article/details/gtteocljlr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gteyrtxqif.html

JS:   greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtjvhgwpxn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gtplwvrdlj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtjffghclc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.andypj.xyz/Article/details/gteebezdzn.html

Ruby: def greet; "admin"; end
来源：http://dali.nwbrower.top/Article/details/gttuiuueyq.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhixingplan.top/Article/details/gtkcfvdcum.html

[G07] 调用父类方法
来源：http://dali.xziqi.cn/Article/details/gtuaxjbohw.html

Py:   super().greet()
来源：http://dali.hammf.cn/Article/details/gtjfysohvp.html

PHP:  parent::greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtnoppvdpg.html

JS:   super.greet();
来源：http://dali.jiagoushi.top/Article/details/gtetfgkvtv.html

TS:   super.greet();
来源：http://dali.aizwys.cn/Article/details/gtqkhhvpck.html

Java: super.greet();
来源：http://dali.tanke756.top/Article/details/gtkqcgodwh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.wangdashe.top/Article/details/gtmaodmjak.html

Ruby: super
来源：http://dali.xuetiantiany.cn/Article/details/gtbaapynbp.html

C#:   base.Greet();
来源：http://dali.yanxiufei.cn/Article/details/gtsgeaifrn.html

[G08] 静态方法与属性
来源：http://dali.meibo888.top/Article/details/gtbmtmesyk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xinyue.icu/Article/details/gtznkvzunu.html

PHP:  public static function f() {}
来源：http://dali.shzxlz.cn/Article/details/gtepjkrumo.html

JS:   static f() {}
来源：http://dali.yueranfly.top/Article/details/gtfgjbjatj.html

TS:   static f(): void {}
来源：http://dali.xziqi.cn/Article/details/gtymffvdmw.html

Java: static void f() {}
来源：http://dali.hysaishi.cn/Article/details/gtbngbwleu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xuanzx.com/Article/details/gthqarvzuk.html

Ruby: def self.f; end
来源：http://dali.gzhubu.top/Article/details/gtdcqymdxb.html

C#:   public static void F() {}
来源：http://dali.iojbl.cn/Article/details/gtgrsjgbnu.html

[G09] 接口 / 抽象类
来源：http://dali.daxiang520.top/Article/details/gtzttgleio.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gaohongyu789.top/Article/details/gtqvostmlq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.9152youxi.cn/Article/details/gtxkewgpga.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sxryk.cn/Article/details/gtycojlypr.html

TS:   interface Shape { area(): number; }
来源：http://dali.zdqjudy.top/Article/details/gtgyuschgq.html

Java: interface Shape { double area(); }
来源：http://dali.hysaishi.cn/Article/details/gthnsyqpuq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.haohaochexian.top/Article/details/gttsujbapa.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.snrcjt.cn/Article/details/gtjlqqtlsx.html

C#:   interface IShape { double Area(); }
来源：http://dali.gogol.net.cn/Article/details/gtqyfytidx.html

[G10] 访问控制
来源：http://dali.tian-w.cn/Article/details/gttbcydwwy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yangfankeji.com/Article/details/gtgjbryzhn.html

PHP:  public / protected / private
来源：http://dali.fengsongda.top/Article/details/gtpmnvovoy.html

JS:   #private 字段；其余公开
来源：http://dali.c1oappe.top/Article/details/gtuohntana.html

TS:   public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gtjuvhmcti.html

Java: public / protected / private / 默认包级
来源：http://dali.ehwqpu.com/Article/details/gtmbrdbrrv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenjidiqi.icu/Article/details/gtvtulbmnj.html

Ruby: public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gtcvgvsgaw.html

C#:   public / protected / private / internal
来源：http://dali.guowangkeji.top/Article/details/gtkorjqgjw.html

[G11] getter / setter
来源：http://dali.yanxiufei.cn/Article/details/gtmvvwkxey.html

Py:   @property 与 @x.setter
来源：http://dali.nanxinkj.top/Article/details/gtdqgqjlpf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gtredeacts.html

JS:   get name() { return this._name; }
来源：http://dali.dashuyun.cn/Article/details/gtbolrbikl.html

TS:   get name(): string { return this._name; }
来源：http://dali.pycfn.com/Article/details/gtvmreitcy.html

Java: public String getName() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtaygoufss.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gtdcyaeyua.html

Ruby: attr_accessor :name
来源：http://dali.jianghu66.top/Article/details/gthofzwqjy.html

C#:   public string Name { get; set; }
来源：http://dali.wangshuangyany.cn/Article/details/gthqmvflgj.html

[G12] 对象转字符串
来源：http://dali.yj20258.top/Article/details/gtnassfzqs.html

Py:   def __str__(self): return self.name
来源：http://dali.jinqigufen.top/Article/details/gtguexhxjg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gtrzndkjwb.html

JS:   toString() { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtsueevtfk.html

TS:   toString(): string { return this.name; }
来源：http://dali.tanke756.top/Article/details/gtcqgockqa.html

Java: @Override public String toString() { return name; }
来源：http://dali.c1oappe.top/Article/details/gtxspexlqd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gtrsgxqcmp.html

Ruby: def to_s; @name; end
来源：http://dali.guannengcc.top/Article/details/gtjapskxdq.html

C#:   public override string ToString() => Name;
来源：http://dali.zhixingplan.top/Article/details/gtovtazvod.html

[G13] 判断对象类型
来源：http://dali.cqqwz.cn/Article/details/gtlgwqtddi.html


<!-- 参考信息 -->