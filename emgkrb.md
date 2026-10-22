代发 wailian999

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hongshengwenyu.top/Article/details/gt2yjbiygia.html

[E11] 反转字符串
来源：http://dali.zhixingplan.top/Article/details/gt2rcwrycfi.html

Py:   s[::-1]
来源：http://dali.9152youxi.cn/Article/details/gt2qxuovktm.html

PHP:  strrev($s);
来源：http://dali.meibo888.top/Article/details/gt2ikdwfmku.html

JS:   [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gt2wtbqvkqc.html

TS:   [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gt2gzdtgzag.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eivearps.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.fzhhl.top/Article/details/gt2hqmuihiv.html

Ruby: s.reverse
来源：http://dali.redwolf501.top/Article/details/gt2iwjorlvf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xuanzx.com/Article/details/gt2kkmwgnhe.html

[E12] 统计某字符出现次数
来源：http://dali.ivvv.top/Article/details/gt2gbdaoflw.html

Py:   s.count("a")
来源：http://dali.cheryme.top/Article/details/gt2howarhja.html

PHP:  substr_count($s, "a");
来源：http://dali.aibaodan.cn/Article/details/gt2vxbyemuj.html

JS:   s.split("a").length - 1
来源：http://dali.wangdashe.top/Article/details/gt2zeroaltj.html

TS:   s.split("a").length - 1
来源：http://dali.9152youxi.cn/Article/details/gt2hjjpgnxh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jtvdflix.html

Go:   strings.Count(s, "a")
来源：http://dali.cashguo.top/Article/details/gt2wqvinjzu.html

Ruby: s.count("a")
来源：http://dali.xylfe.cn/Article/details/gt2bavvxdxr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj20258.top/Article/details/gt2awgejgar.html

[E13] 逐字符遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2czvdmoim.html

Py:   for ch in s: print(ch)
来源：http://dali.cheryme.top/Article/details/gt2pnldlbxy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhongyouzk.top/Article/details/gt2sscscyln.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuxming.cn/Article/details/gt2pgsjzoaa.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gt2gdlirzgi.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vjovjcki.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gogol.net.cn/Article/details/gt2iaciagbg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenlongwang.top/Article/details/gt2vgvlnjms.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shuidangran.top/Article/details/gt2whhkgeuj.html

[E14] URL 编码与 Base64
来源：http://dali.316326.xyz/Article/details/gt2azgqgecg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.wangdashe.top/Article/details/gt2vdqfrnhp.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yonumen.top/Article/details/gt2hsexadog.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zdqjudy.top/Article/details/gt2hkbinmrg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yj20258888.top/Article/details/gt2iihzpazy.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gotoacloud.top/Article/details/gt2aoawgboa.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kvqaeoxq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yongpay.top/Article/details/gt2yzacsepv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj20258.top/Article/details/gt2locrbmhc.html

[E15] HTML 转义 / 反转义
来源：http://dali.xuanzx.com/Article/details/gt2ngjzqnlr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2eibyxphy.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.c1oappe.top/Article/details/gt2shfrolgl.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zmhqefmg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cashguo.top/Article/details/gt2hsvanmie.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sysykeji.top/Article/details/gt2plppgylz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xuanzx.com/Article/details/gt2xwgjjqvz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rustfurf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tianlin.xyz/Article/details/gt2vldgkvyj.html

[E16] 数字千分位
来源：http://dali.hywenlv.cn/Article/details/gt2ipwmfpbw.html

Py:   f"{1234567:,}"
来源：http://dali.zhixingplan.top/Article/details/gt2mdlxfszr.html

PHP:  number_format(1234567);
来源：http://dali.yj20258.top/Article/details/gt2eidhgoau.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tanke756.top/Article/details/gt2mdrdwgzx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangdashe.top/Article/details/gt2yuidgrsd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.sweek.top/Article/details/gt2txklgcxd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.gzhubu.top/Article/details/gt2irwyyrkz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpbowcu.html

C#:   1234567.ToString("N0")
来源：http://dali.yuanzhike.top/Article/details/gt2sakhagtp.html

[E17] 首字母大写
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bxowdmth.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.aizwys.cn/Article/details/gt2yvkkoskv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jewnrllc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ptbiwfkd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hgsyilbw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.fzhhl.top/Article/details/gt2ntyfczhg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tianlin.xyz/Article/details/gt2mjkqvgxu.html

Ruby: s.capitalize
来源：http://dali.mhx1999.top/Article/details/gt2tdfohcwe.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ppjwa.cn/Article/details/gt2fbkldidw.html

[E18] 模板占位符替换
来源：http://dali.aibaodan.cn/Article/details/gt2pyfodpat.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.nanxuanxn.top/Article/details/gt2eugzjhpj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.316326.xyz/Article/details/gt2reqryybt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gt2ffssxtag.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gt2qohcbdiv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gt2gklrwzsi.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gt2rwzxyjis.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2rirlbxpv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yj20258.top/Article/details/gt2istfvotj.html

[E19] 多行文本按行拆分
来源：http://dali.vqdsnc.cn/Article/details/gt2zodjrpxx.html

Py:   s.splitlines()
来源：http://dali.redwolf501.top/Article/details/gt2swzcwdit.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.aibaodan.cn/Article/details/gt2qrsgywkm.html

JS:   s.split(/\r?\n/)
来源：http://dali.jiagoushi.top/Article/details/gt2ukgjoute.html

TS:   s.split(/\r?\n/)
来源：http://dali.tian-w.cn/Article/details/gt2yhcgkvhj.html

Java: s.lines().toList()
来源：http://dali.cashguo.top/Article/details/gt2ruhxlujq.html

Go:   strings.Split(s, "\n")
来源：http://dali.aibaodan.cn/Article/details/gt2flqvywem.html

Ruby: s.lines
来源：http://dali.zdqjudy.top/Article/details/gt2fjdwblzr.html

C#:   s.Split('\n')
来源：http://dali.bjfxy.top/Article/details/gt2ayrilpkz.html

[E20] 判断字符串是否为空
来源：http://dali.gogol.net.cn/Article/details/gt2xbffftsn.html

Py:   if not s:
来源：http://dali.wangdashe.top/Article/details/gt2cyzsccuz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.guowangkeji.top/Article/details/gt2jezwvcna.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2yaocafme.html

TS:   if (s === "") {}
来源：http://dali.xinyue.icu/Article/details/gt2vascngkf.html

Java: if (s.isEmpty()) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uodzqnjy.html

Go:   if s == "" {}
来源：http://dali.ppjwa.cn/Article/details/gt2wnjbuscw.html

Ruby: if s.empty?
来源：http://dali.cheryme.top/Article/details/gt2uzmltwck.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shuidangran.top/Article/details/gt2xenupyom.html

[E21] 超长截断加省略号
来源：http://dali.316326.xyz/Article/details/gt2sacxjdae.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.redwolf501.top/Article/details/gt2srvvlcvd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gt2rxbyttbb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gt2nxzzoihy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xziqi.cn/Article/details/gt2rlcsjvpi.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gt2alxsvnut.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gaohongyu789.top/Article/details/gt2oaxdlume.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qejukivt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gt2cfctfofm.html

[E22] 字节长度与字符长度
来源：http://dali.vqdsnc.cn/Article/details/gt2grlaehce.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ehwqpu.com/Article/details/gt2reapeacm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gt2ctzcrkre.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gt2atarriku.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cucudq.cn/Article/details/gt2ectwwdxs.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.aizwys.cn/Article/details/gt2gquqkina.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jyoumei.cn/Article/details/gt2gkrrswde.html

Ruby: s.bytesize;  s.length
来源：http://dali.yuxming.cn/Article/details/gt2dgavyrva.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.feifeiyinyue.top/Article/details/gt2kplqwkvi.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2sljxbkib.html

F. 文件与目录
来源：http://dali.hammf.cn/Article/details/gt2hhbsogst.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2drbtndhp.html

[F01] 读取整个文件
来源：http://dali.xziqi.cn/Article/details/gt2fqquqsup.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.9152youxi.cn/Article/details/gt2ebwsdixm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2tdsrzauu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sxryk.cn/Article/details/gt2dgvfspeh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinqigfzy.top/Article/details/gt2jrtxaowr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gt2rldvchzm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.smart0.xyz/Article/details/gt2solopyke.html

Ruby: File.read("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2chufgwyp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2vtfxoujc.html

[F02] 逐行读取文件
来源：http://dali.sufxvd.cn/Article/details/gt2dcwqtynb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.vqdsnc.cn/Article/details/gt2vhsyrvtk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.c1oappe.top/Article/details/gt2wckffaxa.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gzhubu.top/Article/details/gt2eziwlabp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenzaomai.com/Article/details/gt2gwzffznl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shuidangran.top/Article/details/gt2foylxrpv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.pycfn.com/Article/details/gt2qxnaamtc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ydzc1.top/Article/details/gt2felqfbob.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zdqjudy.top/Article/details/gt2sffaicxn.html

[F03] 写入文件（覆盖）
来源：http://dali.jyoumei.cn/Article/details/gt2tgmjxptb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cucudq.cn/Article/details/gt2ibnrhkjv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sweek.top/Article/details/gt2dsvzzcbh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gt2hrcneshh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.meibo888.top/Article/details/gt2uqzrsifs.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ydzc1.top/Article/details/gt2gljcyoea.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hnxiangtu.top/Article/details/gt2zigyaznl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gaohongyu789.top/Article/details/gt2tglqvwcc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.fzhhl.top/Article/details/gt2hvfhcrwc.html

[F04] 追加写入文件
来源：http://dali.meibo888.top/Article/details/gt2guyrmxri.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oxojohyi.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.0kj1m.cn/Article/details/gt2gypkjmpu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fengsongda.top/Article/details/gt2zpjrcvdn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhixingplan.top/Article/details/gt2kgnazcpa.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.smart0.xyz/Article/details/gt2bzpmhjxd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.svipenyu.cn/Article/details/gt2opelecpi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.guannengcc.top/Article/details/gt2chcexwxa.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nanxuanxn.top/Article/details/gt2ktdjnvwu.html

[F05] 判断文件或目录是否存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fofizoor.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ppjwa.cn/Article/details/gt2blzhulkv.html

PHP:  file_exists("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2nxlfjojl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2ywtgdmft.html

TS:   fs.existsSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2bdhjamde.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gt2agcxornv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ofngiefs.html

Ruby: File.exist?("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nytovqjy.html

C#:   File.Exists("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2sekozlbq.html

[F06] 删除文件
来源：http://dali.tanke756.top/Article/details/gt2ngrcauoz.html

Py:   os.remove("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2fiijwfej.html

PHP:  unlink("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2lqslozqk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2wqftddee.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2inbdnqui.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gt2xlimnaun.html

Go:   os.Remove("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2aimucmgl.html

Ruby: File.delete("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2vnaqusez.html

C#:   File.Delete("a.txt");
来源：http://dali.guannengcc.top/Article/details/gt2prrkrogt.html

[F07] 创建目录（含多级）
来源：http://dali.hnxiangtu.top/Article/details/gt2kosghejn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zycfv.cn/Article/details/gt2cswbkssx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yonumen.top/Article/details/gt2nmkctipk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.vqdsnc.cn/Article/details/gt2svrfgyar.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxinkj.top/Article/details/gt2vzxnhtkm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sxryk.cn/Article/details/gt2bswotdfw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tanke756.top/Article/details/gt2cgybisho.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hongshengwenyu.top/Article/details/gt2wduokckr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.bjfxy.top/Article/details/gt2bnfvmclc.html

[F08] 遍历目录
来源：http://dali.haohaochexian.top/Article/details/gt2amzznzib.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.316326.xyz/Article/details/gt2sfonrzxv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.guowangkeji.top/Article/details/gt2rriffnwc.html

JS:   fs.readdirSync("dir")
来源：http://dali.mhx1999.top/Article/details/gt2lablxuic.html

TS:   fs.readdirSync("dir")
来源：http://dali.jianghu66.top/Article/details/gt2ygnrskoo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.aibaodan.cn/Article/details/gt2rwdfuvyy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xylfe.cn/Article/details/gt2ugjgxozi.html

Ruby: Dir.children("dir")
来源：http://dali.yj202588.top/Article/details/gt2utmzstkp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.wangdashe.top/Article/details/gt2olandcke.html

[F09] 获取文件大小
来源：http://dali.zhongyouzk.top/Article/details/gt2fzdzitwj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2zypvsbsi.html

PHP:  filesize("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2gvrqexlt.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hnxiangtu.top/Article/details/gt2oblloqga.html

TS:   fs.statSync("a.txt").size
来源：http://dali.dashuyun.cn/Article/details/gt2adrgrhdc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gt2sgkplgdo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xylfe.cn/Article/details/gt2ndmthkgj.html

Ruby: File.size("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2okkieigf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sufxvd.cn/Article/details/gt2yirmirrs.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tanke756.top/Article/details/gt2htwcmmwc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wbjajwgw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2tzehczzv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2hqmlrvvz.html

TS:   path.extname("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2pjyabkfr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.mhx1999.top/Article/details/gt2xssbeoih.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gt2nkcsroat.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2vgrzbfyk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2oonhfyvu.html

[F11] 复制与移动文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2imqpomvm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gt2xebjjoqw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2sigectjp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gt2rxcgbdin.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2rhjsuifv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hysaishi.cn/Article/details/gt2dbicdozm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.nanxuanxn.top/Article/details/gt2hmbieons.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2lxraayih.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cqqwz.cn/Article/details/gt2sqfsrtfu.html

[F12] CSV 读写
来源：http://dali.hnxiangtu.top/Article/details/gt2anyclqpq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhongyouzk.top/Article/details/gt2sffgdgfv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.quarkkingdee.top/Article/details/gt2xphoyboy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shzxlz.cn/Article/details/gt2ryubmelr.html

TS:   // 同上
来源：http://dali.daxiang520.top/Article/details/gt2vhcdewiz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.dashuyun.cn/Article/details/gt2smvncqah.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.aizwys.cn/Article/details/gt2snkpopsc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.kuanghao11.cn/Article/details/gt2cmmwkzax.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.c1oappe.top/Article/details/gt2nlarzhyu.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2xpqvaqdq.html

G. 面向对象
来源：http://dali.jlsjyb.cn/Article/details/gt2gupohdrn.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ocuvfunw.html

[G01] 定义类
来源：http://dali.wangdashe.top/Article/details/gt2ensqljpk.html

Py:   class User: pass
来源：http://dali.iojbl.cn/Article/details/gt2hjaepvto.html

PHP:  class User {}
来源：http://dali.aibaodan.cn/Article/details/gt2kxekoxhp.html

JS:   class User {}
来源：http://dali.tian-w.cn/Article/details/gt2pqeinqxm.html

TS:   class User { name: string = ""; }
来源：http://dali.fzhhl.top/Article/details/gt2efelfizy.html

Java: class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2rqeasnfn.html

Go:   type User struct { Name string }
来源：http://dali.cashguo.top/Article/details/gt2byvzookt.html

Ruby: class User; end
来源：http://dali.ivvv.top/Article/details/gt2mvkupjeu.html

C#:   class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2yrukxbaw.html

[G02] 构造函数
来源：http://dali.hfpthk.cn/Article/details/gt2hfciigwr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xuetiantiany.cn/Article/details/gt2ibvhdydp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.nwbrower.top/Article/details/gt2pkfxvcbw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cheryme.top/Article/details/gt2swsmxmyp.html

TS:   constructor(public name: string) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2wombklox.html

Java: User(String name) { this.name = name; }
来源：http://dali.mhx1999.top/Article/details/gt2gsafofqa.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yvedp.cn/Article/details/gt2makzqyci.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yvedp.cn/Article/details/gt2awcwqaol.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gzhubu.top/Article/details/gt2vkemtqcn.html

[G03] 实例属性
来源：http://dali.nwbrower.top/Article/details/gt2mywdoetc.html

Py:   self.name = "x"
来源：http://dali.iojbl.cn/Article/details/gt2patqpozi.html

PHP:  public string $name = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tnwrpdxr.html

JS:   this.name = "x";
来源：http://dali.hysaishi.cn/Article/details/gt2msqudbiq.html

TS:   name: string = "x";
来源：http://dali.cdnleiting.top/Article/details/gt2wepjjgcp.html

Java: private String name;
来源：http://dali.ehwqpu.com/Article/details/gt2vterxmnv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhixingplan.top/Article/details/gt2rtbxtkwa.html

Ruby: @name = "x"
来源：http://dali.yuxming.cn/Article/details/gt2thkxzpgr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nanxuanxn.top/Article/details/gt2cpswgncd.html

[G04] 定义方法
来源：http://dali.mhx1999.top/Article/details/gt2veahaxig.html

Py:   def greet(self): return self.name
来源：http://dali.zhengqikj.top/Article/details/gt2waazdggp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gt2mmiswslo.html

JS:   greet() { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gt2psoxuykg.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gt2fdhafqlq.html

Java: String greet() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gt2wdzibghj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.havefunace.top/Article/details/gt2mtpobvqz.html

Ruby: def greet; @name; end
来源：http://dali.chenlongwang.top/Article/details/gt2ywtmxwwz.html

C#:   public string Greet() => Name;
来源：http://dali.zhengqikj.top/Article/details/gt2yvzutjnn.html

[G05] 继承
来源：http://dali.nanxuanxn.top/Article/details/gt2fmicdple.html

Py:   class Admin(User): pass
来源：http://dali.gzhubu.top/Article/details/gt2adqmzvfc.html

PHP:  class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gt2cksgegbk.html

JS:   class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gt2yxlrzyfl.html

TS:   class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2znltjfll.html

Java: class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gt2cxljrkzh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sufxvd.cn/Article/details/gt2hjacqyil.html

Ruby: class Admin < User; end
来源：http://dali.zhongyouzk.top/Article/details/gt2jkektdtq.html

C#:   class Admin : User {}
来源：http://dali.jqgufenzy.top/Article/details/gt2pbzbztdi.html

[G06] 重写方法
来源：http://dali.vqdsnc.cn/Article/details/gt2snavfhfb.html

Py:   def greet(self): return "admin"
来源：http://dali.gotoacloud.top/Article/details/gt2jbhkvwip.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvnzkrc.html

JS:   greet() { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gt2npdksvsx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gt2slkgckaa.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gt2hsprlmnk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rrmycfdb.html

Ruby: def greet; "admin"; end
来源：http://dali.pycfn.com/Article/details/gt2cxjhxhdd.html

C#:   public override string Greet() => "admin";
来源：http://dali.hfpthk.cn/Article/details/gt2nszmlmwe.html

[G07] 调用父类方法
来源：http://dali.yueranfly.top/Article/details/gt2lvimsgoj.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2knyfzbwx.html

PHP:  parent::greet();
来源：http://dali.sweek.top/Article/details/gt2kudmfpjy.html

JS:   super.greet();
来源：http://dali.redwolf501.top/Article/details/gt2ewrtrlir.html

TS:   super.greet();
来源：http://dali.hnqzz.top/Article/details/gt2qckwlkhc.html

Java: super.greet();
来源：http://dali.xinyue.icu/Article/details/gt2losvxzml.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj20258888.top/Article/details/gt2ftqpmtck.html

Ruby: super
来源：http://dali.shzxlz.cn/Article/details/gt2kwfftmml.html

C#:   base.Greet();
来源：http://dali.hnxiangtu.top/Article/details/gt2aoduehzd.html

[G08] 静态方法与属性
来源：http://dali.yj20258.top/Article/details/gt2dbedzhzl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hnqzz.top/Article/details/gt2tbhhgigg.html

PHP:  public static function f() {}
来源：http://dali.cashguo.top/Article/details/gt2ohvdjjvs.html

JS:   static f() {}
来源：http://dali.yongpay.top/Article/details/gt2angwacpo.html

TS:   static f(): void {}
来源：http://dali.sysykeji.top/Article/details/gt2pqkukksk.html

Java: static void f() {}
来源：http://dali.ehwqpu.com/Article/details/gt2ouwzlulp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.dashuyun.cn/Article/details/gt2yfsrfuzl.html

Ruby: def self.f; end
来源：http://dali.9152youxi.cn/Article/details/gt2poiercqf.html

C#:   public static void F() {}
来源：http://dali.ehwqpu.com/Article/details/gt2ozwzxdoc.html

[G09] 接口 / 抽象类
来源：http://dali.aibaodan.cn/Article/details/gt2hnurtxnu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ehwqpu.com/Article/details/gt2bmvicbth.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinqigufen.top/Article/details/gt2czmfqehd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shuidangran.top/Article/details/gt2zvhtwjvz.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhengqikj.top/Article/details/gt2tgiloxxm.html


<!-- 参考信息 -->