代发 wailian999

JS:   [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqmtoyahg.html

TS:   [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtjbggzlek.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmyjzqlwa.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.c1oappe.top/Article/details/gtiholaujv.html

Ruby: s.reverse
来源：http://dali.zhongyouzk.top/Article/details/gtpfyscrij.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ydzc1.top/Article/details/gtladcuxde.html

[E12] 统计某字符出现次数
来源：http://dali.jinqigfzy.top/Article/details/gtptopmhye.html

Py:   s.count("a")
来源：http://dali.wangshuangyany.cn/Article/details/gtojdrxehn.html

PHP:  substr_count($s, "a");
来源：http://dali.daxiang520.top/Article/details/gtumdstlga.html

JS:   s.split("a").length - 1
来源：http://dali.yj20258.top/Article/details/gttzsuiacj.html

TS:   s.split("a").length - 1
来源：http://dali.zhoulong.xyz/Article/details/gtxlycpwqq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.meibo888.top/Article/details/gtnkpwnwug.html

Go:   strings.Count(s, "a")
来源：http://dali.chenzaomai.com/Article/details/gttmwujscb.html

Ruby: s.count("a")
来源：http://dali.nwbrower.top/Article/details/gtgzzfblvj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinqigfzy.top/Article/details/gtsbshukir.html

[E13] 逐字符遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtgaxzanyv.html

Py:   for ch in s: print(ch)
来源：http://dali.zhiwuduotai.top/Article/details/gtkatsqrxe.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yuanzhike.top/Article/details/gtyxdgkptu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xinyue.icu/Article/details/gtxbfzqgzj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhengqikj.top/Article/details/gtthudybwo.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yonumen.top/Article/details/gtjpfrmize.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yonumen.top/Article/details/gtzksuydzx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.9152youxi.cn/Article/details/gtoqkqiwak.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dianchejie.cn/Article/details/gtoawzjhcm.html

[E14] URL 编码与 Base64
来源：http://dali.haohaochexian.top/Article/details/gtxedcgtrv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.redwolf501.top/Article/details/gtoddcdfze.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xylfe.cn/Article/details/gtgtgecocf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cqqwz.cn/Article/details/gtilvegkum.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yuxming.cn/Article/details/gtkehmgtpb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gtmaahrybe.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hnqzz.top/Article/details/gtuwexbgzv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xuanzx.com/Article/details/gtxvposmzi.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.daria6918.cn/Article/details/gtjevzevbz.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenlongwang.top/Article/details/gtkovyxbjs.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.haohaochexian.top/Article/details/gtzciotpsl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yvedp.cn/Article/details/gtyzhaiiag.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.pycfn.com/Article/details/gtwhpxnloj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoxsbtvvd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.nwbrower.top/Article/details/gtkwpwxsvr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.aizwys.cn/Article/details/gttalkjoni.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shuidangran.top/Article/details/gtjaneyqid.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtbamewagk.html

[E16] 数字千分位
来源：http://dali.zhongyouzk.top/Article/details/gtqfqzexnw.html

Py:   f"{1234567:,}"
来源：http://dali.shangyingyoupin.top/Article/details/gtbwosobje.html

PHP:  number_format(1234567);
来源：http://dali.zycfv.cn/Article/details/gtchsuaeho.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.9152youxi.cn/Article/details/gtazqxqmde.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sxryk.cn/Article/details/gtpwrsrhmx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.316326.xyz/Article/details/gtkrhphcbz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.daria6918.cn/Article/details/gtphedaajk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jqgufenzy.top/Article/details/gtbphvxrkx.html

C#:   1234567.ToString("N0")
来源：http://dali.zhengqikj.top/Article/details/gtyllqkabx.html

[E17] 首字母大写
来源：http://dali.9152youxi.cn/Article/details/gtllggywui.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.daria6918.cn/Article/details/gtvuyoiogc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yonumen.top/Article/details/gtfjfkzoll.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258888.top/Article/details/gtfccafdvq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdypeimmk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gotoacloud.top/Article/details/gtnvnsilxc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gtwsflciwf.html

Ruby: s.capitalize
来源：http://dali.gotoacloud.top/Article/details/gtkoacpkep.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sysykeji.top/Article/details/gtjmrcbmtg.html

[E18] 模板占位符替换
来源：http://dali.dianchejie.cn/Article/details/gtxdlymche.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xylfe.cn/Article/details/gtwkpjorac.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnxwtryyn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gtxqbztlcg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sweek.top/Article/details/gtoawzmwuo.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gtoqnzsvid.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gtxxpgctsf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jqgufenzy.top/Article/details/gtchueatdp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaupoonqj.html

[E19] 多行文本按行拆分
来源：http://dali.yj20258888.top/Article/details/gtrtyqpxgo.html

Py:   s.splitlines()
来源：http://dali.ybcxt.top/Article/details/gtgonpfwai.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ybcxt.top/Article/details/gtfatgfwgx.html

JS:   s.split(/\r?\n/)
来源：http://dali.nwbrower.top/Article/details/gtfrqtexvd.html

TS:   s.split(/\r?\n/)
来源：http://dali.shangyingyoupin.top/Article/details/gttkntzpdw.html

Java: s.lines().toList()
来源：http://dali.zdqjudy.top/Article/details/gtxunfvkns.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhongyouzk.top/Article/details/gttzpwwdhg.html

Ruby: s.lines
来源：http://dali.gzhubu.top/Article/details/gtgcohzruv.html

C#:   s.Split('\n')
来源：http://dali.316326.xyz/Article/details/gtamxbmslx.html

[E20] 判断字符串是否为空
来源：http://dali.hywenlv.cn/Article/details/gtqaqawsey.html

Py:   if not s:
来源：http://dali.hysaishi.cn/Article/details/gttyqydwyi.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gaohongyu789.top/Article/details/gtjjlceuny.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgfpixsqp.html

TS:   if (s === "") {}
来源：http://dali.gotoacloud.top/Article/details/gtpipiiqqk.html

Java: if (s.isEmpty()) {}
来源：http://dali.ivvv.top/Article/details/gttdybhnum.html

Go:   if s == "" {}
来源：http://dali.nanxuanxn.top/Article/details/gtlrzskaoe.html

Ruby: if s.empty?
来源：http://dali.svipenyu.cn/Article/details/gtiwfhhwqh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenlongwang.top/Article/details/gtdoglnocy.html

[E21] 超长截断加省略号
来源：http://dali.gotoacloud.top/Article/details/gtvfdydeav.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gotoacloud.top/Article/details/gtmgjbxsqw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gtjqxrxfds.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gtazhijjze.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtgtpvgmde.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.fengsongda.top/Article/details/gtsjxqhvut.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hysaishi.cn/Article/details/gtzirukjif.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yonumen.top/Article/details/gtgadltxwf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gtnxplxdxy.html

[E22] 字节长度与字符长度
来源：http://dali.dianchejie.cn/Article/details/gtxtqsymtb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yuxming.cn/Article/details/gtubdrxwgm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gtuyxjepoc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.c1oappe.top/Article/details/gtdmefrudd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gtcidxtwzn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaapfjyuc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hongshengwenyu.top/Article/details/gtprhjtjgm.html

Ruby: s.bytesize;  s.length
来源：http://dali.redwolf501.top/Article/details/gtlrhbsjrf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinghuilouyu.cn/Article/details/gtejketbcn.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gthuthiefn.html

F. 文件与目录
来源：http://dali.jyoumei.cn/Article/details/gtdhpuysxv.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtjzxiwjql.html

[F01] 读取整个文件
来源：http://dali.daxiang520.top/Article/details/gtwfsgdzvc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj20258888.top/Article/details/gtwhmdulle.html

PHP:  file_get_contents("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtxkgrjfcl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.aibaodan.cn/Article/details/gtmqmmprkt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gtljepmgke.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gteecmzkcn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.redwolf501.top/Article/details/gtaavwsfax.html

Ruby: File.read("a.txt")
来源：http://dali.cheryme.top/Article/details/gtblifjwsm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtktvmmtdc.html

[F02] 逐行读取文件
来源：http://dali.sysykeji.top/Article/details/gthvxrcjqo.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.iojbl.cn/Article/details/gtzujvsbnc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sysykeji.top/Article/details/gtelaqqxzz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tanke756.top/Article/details/gtkvitpcox.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtccczqpfi.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nanxinkj.top/Article/details/gtunhaxkju.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.aibaodan.cn/Article/details/gttmmyyvfl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj202588.top/Article/details/gtjqvpxsls.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yanxiufei.cn/Article/details/gtnkehbhad.html

[F03] 写入文件（覆盖）
来源：http://dali.xinyue.icu/Article/details/gtwnyuoxrv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinqigfzy.top/Article/details/gtgbumqeew.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yj202588.top/Article/details/gtqhgxkznl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.havefunace.top/Article/details/gtnlomhwex.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guannengcc.top/Article/details/gtfembsmgq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gtcomamhvt.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yonumen.top/Article/details/gtuburokfp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jianghu66.top/Article/details/gtsrbamxic.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yueranfly.top/Article/details/gteboprmfs.html

[F04] 追加写入文件
来源：http://dali.svipenyu.cn/Article/details/gtdgevdcqx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.kuanghao11.cn/Article/details/gtsavrztrb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tanke756.top/Article/details/gtggnxgtrh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.meibo888.top/Article/details/gtqzmdgqxh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.havefunace.top/Article/details/gtunxjvktv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlmdcgpea.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdoftymla.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cucudq.cn/Article/details/gtdufvrvjx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yuanzhike.top/Article/details/gtlacuknce.html

[F05] 判断文件或目录是否存在
来源：http://dali.tanke756.top/Article/details/gtfcagujny.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.quarkkingdee.top/Article/details/gtyyucnday.html

PHP:  file_exists("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtjlkrpmat.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gthauszgee.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtniaasmae.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gtlcaypajl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.kuanghao11.cn/Article/details/gtzxqsthrt.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtcqltcqzi.html

C#:   File.Exists("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtrfvddokn.html

[F06] 删除文件
来源：http://dali.sufxvd.cn/Article/details/gtmvboosab.html

Py:   os.remove("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gthswnbwys.html

PHP:  unlink("a.txt");
来源：http://dali.meibo888.top/Article/details/gtjlnnnqiz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtsqjejrcn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtjlrvdjuh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gtpnwdmghc.html

Go:   os.Remove("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtzxqwgbqp.html

Ruby: File.delete("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtbwgsizco.html

C#:   File.Delete("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtcuczkdak.html

[F07] 创建目录（含多级）
来源：http://dali.yongpay.top/Article/details/gtvwuypozc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.guannengcc.top/Article/details/gtkclwlydl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ppjwa.cn/Article/details/gtqrikrivl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ybcxt.top/Article/details/gtqwbvqpcv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yueranfly.top/Article/details/gtzjlrvixf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.vqdsnc.cn/Article/details/gtijduqijc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jqgufenzy.top/Article/details/gtvbspknni.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cashguo.top/Article/details/gtxahxhncg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shuidangran.top/Article/details/gtkbrlvyfj.html

[F08] 遍历目录
来源：http://dali.cashguo.top/Article/details/gtvkbnftbe.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shangyingyoupin.top/Article/details/gtsxjevutq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.mhx1999.top/Article/details/gtxnfwckjw.html

JS:   fs.readdirSync("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtaukofjeb.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenlongwang.top/Article/details/gtmoydabak.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.birdmap.top/Article/details/gtguhhpift.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gtetoosnlu.html

Ruby: Dir.children("dir")
来源：http://dali.shuidangran.top/Article/details/gtidupqjre.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cdnleiting.top/Article/details/gtyioffsww.html

[F09] 获取文件大小
来源：http://dali.nanxuanxn.top/Article/details/gtqwzkmipp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtfozohbes.html

PHP:  filesize("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtgnohvftf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhongyouzk.top/Article/details/gtsqwwdzeo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shzxlz.cn/Article/details/gtlqowzzdd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gtopcyqqyc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tanke756.top/Article/details/gtvmkpbirx.html

Ruby: File.size("a.txt")
来源：http://dali.tanke756.top/Article/details/gtxmnvqbda.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.vqdsnc.cn/Article/details/gtdkbxapqd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.pengpengdd.cyou/Article/details/gtgtwaamab.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtlkvvcplk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.mhx1999.top/Article/details/gtbfkiesmk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtqgozpjgd.html

TS:   path.extname("a.txt")
来源：http://dali.ivvv.top/Article/details/gtguerkbdk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj20258.top/Article/details/gttvnqpxrq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gtrmvciqfh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtfjwfxkws.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtmfhtmtju.html

[F11] 复制与移动文件
来源：http://dali.gogol.net.cn/Article/details/gtnabevqqw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtzykitogk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsbaidnxr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gteamflwom.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gtdshjdnid.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.vqdsnc.cn/Article/details/gtllinsmdc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ehwqpu.com/Article/details/gtqwnieenw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtslowsiyw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tian-w.cn/Article/details/gtvbpdukru.html

[F12] CSV 读写
来源：http://dali.redwolf501.top/Article/details/gtzrwrzupy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jqgufenzy.top/Article/details/gtkyebdjhq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gaohongyu789.top/Article/details/gtkvftecaj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.daxiang520.top/Article/details/gtkosesclw.html

TS:   // 同上
来源：http://dali.jyoumei.cn/Article/details/gtmxabqdng.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.316326.xyz/Article/details/gtogavaxwo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cqqwz.cn/Article/details/gtuhgkiuxe.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.vqdsnc.cn/Article/details/gtanxsuozo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gzhubu.top/Article/details/gtuokfxsjl.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtzdwwampm.html

G. 面向对象
来源：http://dali.yonumen.top/Article/details/gtujdoeilb.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtpbrbslep.html

[G01] 定义类
来源：http://dali.nwbrower.top/Article/details/gtyanlorhr.html

Py:   class User: pass
来源：http://dali.zhixingplan.top/Article/details/gtairlkjsm.html

PHP:  class User {}
来源：http://dali.yonumen.top/Article/details/gtczyrdbmh.html

JS:   class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtohimsdch.html

TS:   class User { name: string = ""; }
来源：http://dali.feifeiyinyue.top/Article/details/gtvfvxrlnn.html

Java: class User {}
来源：http://dali.yuxming.cn/Article/details/gtazakufea.html

Go:   type User struct { Name string }
来源：http://dali.wangshuangyany.cn/Article/details/gtzdreftzf.html

Ruby: class User; end
来源：http://dali.cucudq.cn/Article/details/gtfjvpotaa.html

C#:   class User {}
来源：http://dali.hywenlv.cn/Article/details/gtnxdrdnek.html

[G02] 构造函数
来源：http://dali.0kj1m.cn/Article/details/gtgnlcyeku.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.iojbl.cn/Article/details/gtqqcqflwk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.redwolf501.top/Article/details/gtfyoohexy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.redwolf501.top/Article/details/gtfsuznhqz.html

TS:   constructor(public name: string) {}
来源：http://dali.kuanghao11.cn/Article/details/gthvkehqpf.html

Java: User(String name) { this.name = name; }
来源：http://dali.xziqi.cn/Article/details/gtamigneus.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gogol.net.cn/Article/details/gteasokkjm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xinyue.icu/Article/details/gtgxmzajmh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gaohongyu789.top/Article/details/gtantcktlr.html

[G03] 实例属性
来源：http://dali.xuanzx.com/Article/details/gtzmzzvmmm.html

Py:   self.name = "x"
来源：http://dali.fengsongda.top/Article/details/gtaplfjgyn.html

PHP:  public string $name = "x";
来源：http://dali.xziqi.cn/Article/details/gthksfephm.html

JS:   this.name = "x";
来源：http://dali.fengsongda.top/Article/details/gtqisqqykh.html

TS:   name: string = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtgszbubxo.html

Java: private String name;
来源：http://dali.yanxiufei.cn/Article/details/gtuyvbdylr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenlongwang.top/Article/details/gtmtjwpmha.html

Ruby: @name = "x"
来源：http://dali.sysykeji.top/Article/details/gtkdbioptr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tanke756.top/Article/details/gtehfixkzq.html

[G04] 定义方法
来源：http://dali.cqqwz.cn/Article/details/gtrgnlhchl.html

Py:   def greet(self): return self.name
来源：http://dali.redwolf501.top/Article/details/gtdlkqvnqs.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gtqptqbvvv.html

JS:   greet() { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gtwfvjjkcf.html

TS:   greet(): string { return this.name; }
来源：http://dali.yongpay.top/Article/details/gteiuyrbwl.html

Java: String greet() { return name; }
来源：http://dali.bjfxy.top/Article/details/gttbbycxqg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gtyfslvoyy.html

Ruby: def greet; @name; end
来源：http://dali.gaohongyu789.top/Article/details/gtwxtxqfpg.html

C#:   public string Greet() => Name;
来源：http://dali.cashguo.top/Article/details/gtszjimcmp.html

[G05] 继承
来源：http://dali.pycfn.com/Article/details/gtbatcomyu.html

Py:   class Admin(User): pass
来源：http://dali.shzxlz.cn/Article/details/gturswrrdy.html

PHP:  class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gtheraydum.html

JS:   class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gtuwfepcse.html

TS:   class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gthajeqnbu.html

Java: class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gtidhfbvgm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hfpthk.cn/Article/details/gtszbygeae.html

Ruby: class Admin < User; end
来源：http://dali.vqdsnc.cn/Article/details/gthmzohbag.html

C#:   class Admin : User {}
来源：http://dali.daria6918.cn/Article/details/gtysztbjkg.html

[G06] 重写方法
来源：http://dali.tian-w.cn/Article/details/gtssewkpkv.html

Py:   def greet(self): return "admin"
来源：http://dali.chenjidiqi.icu/Article/details/gtwrtokzzc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gtikkmeuqa.html

JS:   greet() { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtdbyxajfn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gtwbjexrgz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtcuoccxla.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tian-w.cn/Article/details/gtwoxahvam.html

Ruby: def greet; "admin"; end
来源：http://dali.svipenyu.cn/Article/details/gtsluxalgp.html

C#:   public override string Greet() => "admin";
来源：http://dali.yonumen.top/Article/details/gtlykyilcy.html

[G07] 调用父类方法
来源：http://dali.jiagoushi.top/Article/details/gtvppfmahm.html

Py:   super().greet()
来源：http://dali.zhiwuduotai.top/Article/details/gtcwznthdo.html

PHP:  parent::greet();
来源：http://dali.jlsjyb.cn/Article/details/gtoohtfpkj.html

JS:   super.greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtywebdzox.html

TS:   super.greet();
来源：http://dali.316326.xyz/Article/details/gtbystcwhv.html

Java: super.greet();
来源：http://dali.yj202588.top/Article/details/gtmoiagqsp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhongyouzk.top/Article/details/gtldftwjcp.html

Ruby: super
来源：http://dali.meibo888.top/Article/details/gtjumowvds.html

C#:   base.Greet();
来源：http://dali.jlsjyb.cn/Article/details/gtciexmaub.html

[G08] 静态方法与属性
来源：http://dali.snrcjt.cn/Article/details/gtzbxfsjbh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shuidangran.top/Article/details/gtgsagbugk.html

PHP:  public static function f() {}
来源：http://dali.cheryme.top/Article/details/gtdbhhfskk.html

JS:   static f() {}
来源：http://dali.jinqigufen.top/Article/details/gteuejusgj.html

TS:   static f(): void {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyeafhmwi.html

Java: static void f() {}
来源：http://dali.yueranfly.top/Article/details/gtvbfceiwh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jqgufenzy.top/Article/details/gtbnaoxkgw.html

Ruby: def self.f; end
来源：http://dali.zhengqikj.top/Article/details/gtlhdsiwyd.html

C#:   public static void F() {}
来源：http://dali.cashguo.top/Article/details/gtoehqzque.html

[G09] 接口 / 抽象类
来源：http://dali.nanxinkj.top/Article/details/gtnlbsqwtl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.iojbl.cn/Article/details/gtgrvtvuax.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.aibaodan.cn/Article/details/gtymxklhwk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jqgufenzy.top/Article/details/gtbpjnovvj.html

TS:   interface Shape { area(): number; }
来源：http://dali.0kj1m.cn/Article/details/gtldvlwfur.html

Java: interface Shape { double area(); }
来源：http://dali.9152youxi.cn/Article/details/gteliqrues.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sysykeji.top/Article/details/gtraloncjo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvzvfmclj.html

C#:   interface IShape { double Area(); }
来源：http://dali.gotoacloud.top/Article/details/gtbjcbusom.html


<!-- 参考信息 -->