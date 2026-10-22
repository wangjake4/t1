代发 wailian999

TS:   "7".padStart(3, "0")
来源：http://dali.cashguo.top/Article/details/gt2ulogmteg.html

Java: String.format("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gt2nrgpbrlj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gt2vcmuuwge.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2llmtovca.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jqgufenzy.top/Article/details/gt2xddfhavl.html

[E11] 反转字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2lredputt.html

Py:   s[::-1]
来源：http://dali.yuanzhike.top/Article/details/gt2ynekixhw.html

PHP:  strrev($s);
来源：http://dali.yueranfly.top/Article/details/gt2eekabmgn.html

JS:   [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gt2ipufeqdn.html

TS:   [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gt2mahotorr.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.smart0.xyz/Article/details/gt2okrsfvlh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xziqi.cn/Article/details/gt2wwjiuywj.html

Ruby: s.reverse
来源：http://dali.nanxinkj.top/Article/details/gt2nnnwlioo.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jlsjyb.cn/Article/details/gt2mtddbows.html

[E12] 统计某字符出现次数
来源：http://dali.birdmap.top/Article/details/gt2rhmbbxba.html

Py:   s.count("a")
来源：http://dali.yj202588.top/Article/details/gt2delnjacj.html

PHP:  substr_count($s, "a");
来源：http://dali.jinqigufen.top/Article/details/gt2gmfyscmu.html

JS:   s.split("a").length - 1
来源：http://dali.yueranfly.top/Article/details/gt2ffvqabsd.html

TS:   s.split("a").length - 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fppplctz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gogol.net.cn/Article/details/gt2pwbqvsnu.html

Go:   strings.Count(s, "a")
来源：http://dali.hysaishi.cn/Article/details/gt2wacegoeg.html

Ruby: s.count("a")
来源：http://dali.ybcxt.top/Article/details/gt2nbabbkag.html

C#:   s.Count(c => c == 'a')
来源：http://dali.9152youxi.cn/Article/details/gt2yfaythfa.html

[E13] 逐字符遍历
来源：http://dali.ehwqpu.com/Article/details/gt2chuqvlmb.html

Py:   for ch in s: print(ch)
来源：http://dali.tianlin.xyz/Article/details/gt2igmjwoaw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.daria6918.cn/Article/details/gt2iiepwyrz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gt2xxlwcgaq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shuidangran.top/Article/details/gt2jrmmvpdm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.iojbl.cn/Article/details/gt2fpenfjcv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2usckezgx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.andypj.xyz/Article/details/gt2rdrleryt.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cashguo.top/Article/details/gt2fkjxndvm.html

[E14] URL 编码与 Base64
来源：http://dali.zhengqikj.top/Article/details/gt2xctbrxgv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yvedp.cn/Article/details/gt2odkxxpii.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hysaishi.cn/Article/details/gt2knwqecfc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fjxovavt.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.fengsongda.top/Article/details/gt2pcfmaihf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ydzc1.top/Article/details/gt2bcphckuq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.snrcjt.cn/Article/details/gt2dofaqdsp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nanxuanxn.top/Article/details/gt2ipfmsgdf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yuanzhike.top/Article/details/gt2zdhsuacw.html

[E15] HTML 转义 / 反转义
来源：http://dali.andypj.xyz/Article/details/gt2qrhrqysf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhengqikj.top/Article/details/gt2monsgfyu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tjevusok.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xylfe.cn/Article/details/gt2minvrvkr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.bjfxy.top/Article/details/gt2yiqzknml.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2olratcov.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.wangdashe.top/Article/details/gt2ivrxrkzf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.andypj.xyz/Article/details/gt2cjrzcbrx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2ggfjuble.html

[E16] 数字千分位
来源：http://dali.redwolf501.top/Article/details/gt2fmnoyncu.html

Py:   f"{1234567:,}"
来源：http://dali.ydzc1.top/Article/details/gt2kiniylbb.html

PHP:  number_format(1234567);
来源：http://dali.gotoacloud.top/Article/details/gt2iiljaign.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dtlemcuq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenzaomai.com/Article/details/gt2sibtevgf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.iojbl.cn/Article/details/gt2jiklqpnh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yueranfly.top/Article/details/gt2cfmuccyb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hywenlv.cn/Article/details/gt2oyyodmdu.html

C#:   1234567.ToString("N0")
来源：http://dali.hywenlv.cn/Article/details/gt2uhrvqtsl.html

[E17] 首字母大写
来源：http://dali.pengpengdd.cyou/Article/details/gt2dhgqgsqk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sweek.top/Article/details/gt2eiacofut.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hywenlv.cn/Article/details/gt2glcdpnwc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2bjnzvsya.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258.top/Article/details/gt2axvyuacx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.bjfxy.top/Article/details/gt2mcqiefwo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hfpthk.cn/Article/details/gt2lbgbsnqi.html

Ruby: s.capitalize
来源：http://dali.chenjidiqi.icu/Article/details/gt2xqbdxyas.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ykrpqfrc.html

[E18] 模板占位符替换
来源：http://dali.nanxuanxn.top/Article/details/gt2urqecenh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cucudq.cn/Article/details/gt2cjjkpuig.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ffsnlekr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.c1oappe.top/Article/details/gt2ejwohgii.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gt2ocjoaowe.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gt2rhlrclda.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.havefunace.top/Article/details/gt2zcrbapiu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jqgfzy.top/Article/details/gt2byfjyoms.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yonumen.top/Article/details/gt2qebxduam.html

[E19] 多行文本按行拆分
来源：http://dali.mhx1999.top/Article/details/gt2eydcengr.html

Py:   s.splitlines()
来源：http://dali.yj202588.top/Article/details/gt2fxrpaxvg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nafvpmrd.html

JS:   s.split(/\r?\n/)
来源：http://dali.yangfankeji.com/Article/details/gt2zyrkrobu.html

TS:   s.split(/\r?\n/)
来源：http://dali.yuanzhike.top/Article/details/gt2pmxhqjns.html

Java: s.lines().toList()
来源：http://dali.0kj1m.cn/Article/details/gt2ldjvpbnv.html

Go:   strings.Split(s, "\n")
来源：http://dali.hnxiangtu.top/Article/details/gt2xidbbadt.html

Ruby: s.lines
来源：http://dali.meibo888.top/Article/details/gt2qpdhizux.html

C#:   s.Split('\n')
来源：http://dali.ehwqpu.com/Article/details/gt2cledorii.html

[E20] 判断字符串是否为空
来源：http://dali.yongpay.top/Article/details/gt2npiuwrjz.html

Py:   if not s:
来源：http://dali.shangyingyoupin.top/Article/details/gt2xexzrnzn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zdqjudy.top/Article/details/gt2jioucccd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xylfe.cn/Article/details/gt2qfefmzyd.html

TS:   if (s === "") {}
来源：http://dali.yj20258.top/Article/details/gt2qtlrynrl.html

Java: if (s.isEmpty()) {}
来源：http://dali.jiagoushi.top/Article/details/gt2pofgtafw.html

Go:   if s == "" {}
来源：http://dali.xuanzx.com/Article/details/gt2mvfszvwa.html

Ruby: if s.empty?
来源：http://dali.bjfxy.top/Article/details/gt2uvlyjati.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yvedp.cn/Article/details/gt2hlrpzlta.html

[E21] 超长截断加省略号
来源：http://dali.chenzaomai.com/Article/details/gt2ingzgzvj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinqigfzy.top/Article/details/gt2dtwyqafz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gt2aunyrhve.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gt2plkzikyg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gt2tyqzmqoe.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gt2ednmlxja.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.nanxinkj.top/Article/details/gt2kfzwjefk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gt2gyujtvpj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gt2eubxsmyt.html

[E22] 字节长度与字符长度
来源：http://dali.jlsjyb.cn/Article/details/gt2pybbljkv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wnnylxpj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gt2slndffvy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.svipenyu.cn/Article/details/gt2uclmoxaf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.bjfxy.top/Article/details/gt2hxypqqzz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhixingplan.top/Article/details/gt2axvustod.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhoulong.xyz/Article/details/gt2wihjtnrv.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhiwuduotai.top/Article/details/gt2tqqsxnpa.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinqigufen.top/Article/details/gt2wbublrca.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2fqlvmldw.html

F. 文件与目录
来源：http://dali.iojbl.cn/Article/details/gt2rkqclcru.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2spyrrhbp.html

[F01] 读取整个文件
来源：http://dali.yangfankeji.com/Article/details/gt2azobhdzu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jlsjyb.cn/Article/details/gt2pswysize.html

PHP:  file_get_contents("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2oczxfpdk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhixingplan.top/Article/details/gt2pkvdsvoq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yuxming.cn/Article/details/gt2atctfapm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gt2bqammtsm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sxbkfszc.html

Ruby: File.read("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2xiowabub.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2onslbpwq.html

[F02] 逐行读取文件
来源：http://dali.guannengcc.top/Article/details/gt2yfttxbdv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jlsjyb.cn/Article/details/gt2droaxbnn.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cheryme.top/Article/details/gt2enxboxtr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.iojbl.cn/Article/details/gt2wxevyous.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cashguo.top/Article/details/gt2autlclrb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.vqdsnc.cn/Article/details/gt2xrhtrbbg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cqqwz.cn/Article/details/gt2arsppdlm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.vqdsnc.cn/Article/details/gt2oowwxvfj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.chenlongwang.top/Article/details/gt2xtrovzak.html

[F03] 写入文件（覆盖）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jseuryas.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.svipenyu.cn/Article/details/gt2zocyxheh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.birdmap.top/Article/details/gt2thllyhiz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gt2smcpptnh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gzhubu.top/Article/details/gt2hooonhom.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xylfe.cn/Article/details/gt2mktxatrp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.andypj.xyz/Article/details/gt2otoeexyg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tian-w.cn/Article/details/gt2zavlxvvo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.pengpengdd.cyou/Article/details/gt2fcniozkx.html

[F04] 追加写入文件
来源：http://dali.0kj1m.cn/Article/details/gt2betiktjc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.tanke756.top/Article/details/gt2tbntgccm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhiwuduotai.top/Article/details/gt2pixxsynn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gt2xrtwjoyr.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.meibo888.top/Article/details/gt2xedgmqon.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.fzhhl.top/Article/details/gt2yhrzfpzl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhengqikj.top/Article/details/gt2sluiyarl.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhongyouzk.top/Article/details/gt2zcdcglll.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ivvv.top/Article/details/gt2ewxgdeyw.html

[F05] 判断文件或目录是否存在
来源：http://dali.wangdashe.top/Article/details/gt2vwnulppa.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sysykeji.top/Article/details/gt2euopsooc.html

PHP:  file_exists("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2wmpxceln.html

JS:   fs.existsSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2znmdoapj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2arvqsfei.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gt2hrybkewq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hywenlv.cn/Article/details/gt2oeirvpmv.html

Ruby: File.exist?("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2qrahbnnt.html

C#:   File.Exists("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2elhsczfn.html

[F06] 删除文件
来源：http://dali.wangdashe.top/Article/details/gt2oztewyzs.html

Py:   os.remove("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2eeijgynn.html

PHP:  unlink("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2snuxhbje.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2pbuewhrv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pwizwxkc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gt2obbenymi.html

Go:   os.Remove("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ujptmqqm.html

Ruby: File.delete("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2ikfuykyd.html

C#:   File.Delete("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2alwihmqc.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxlaajh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xinyue.icu/Article/details/gt2kiewmemu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.316326.xyz/Article/details/gt2xnmezbih.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shuidangran.top/Article/details/gt2xjfgdfiv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mzplbqzh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhixingplan.top/Article/details/gt2ljgvevod.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jianghu66.top/Article/details/gt2tpwhtncy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yuxming.cn/Article/details/gt2cjhdtjsg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sxryk.cn/Article/details/gt2mzzezgbj.html

[F08] 遍历目录
来源：http://dali.hammf.cn/Article/details/gt2fbabtxgp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xuanzx.com/Article/details/gt2qbtfswum.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xinyue.icu/Article/details/gt2bdrbjled.html

JS:   fs.readdirSync("dir")
来源：http://dali.dashuyun.cn/Article/details/gt2ggnaivff.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhongyouzk.top/Article/details/gt2ioewmtyi.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jqgufenzy.top/Article/details/gt2bzunjeez.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jqgfzy.top/Article/details/gt2fuxfvlbr.html

Ruby: Dir.children("dir")
来源：http://dali.yvedp.cn/Article/details/gt2czqpbdqp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ilqglfna.html

[F09] 获取文件大小
来源：http://dali.dashuyun.cn/Article/details/gt2fcdytyzl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2hlblezng.html

PHP:  filesize("a.txt");
来源：http://dali.guannengcc.top/Article/details/gt2yobbsxqi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ydzc1.top/Article/details/gt2ctappyhu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ghufisqn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2peojbtjg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.pengpengdd.cyou/Article/details/gt2nicmkvoy.html

Ruby: File.size("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2jvatpyuf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.0kj1m.cn/Article/details/gt2ltrxgorb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yvedp.cn/Article/details/gt2tfgbsfqb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2fyzkklhe.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2dtigigxy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2mfloacpl.html

TS:   path.extname("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2pnilvnrb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenjidiqi.icu/Article/details/gt2wnxzjzei.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2chufleub.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2wdrddgki.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2fhnzvshl.html

[F11] 复制与移动文件
来源：http://dali.zycfv.cn/Article/details/gt2cmhpnrbk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gt2trwwpbxn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2jfnsteje.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ovqgyfal.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gt2ybctaphz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.meibo888.top/Article/details/gt2bqytside.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tanke756.top/Article/details/gt2dykhsgmb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2yilqkrru.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jqgufenzy.top/Article/details/gt2zzscavmf.html

[F12] CSV 读写
来源：http://dali.yj202588.top/Article/details/gt2vsbpnqhh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tanke756.top/Article/details/gt2konxhbdk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jlsjyb.cn/Article/details/gt2kcphrenu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uosqbayx.html

TS:   // 同上
来源：http://dali.zdqjudy.top/Article/details/gt2grgadwdd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.havefunace.top/Article/details/gt2qthqhasu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhoulong.xyz/Article/details/gt2vsandulc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.quarkkingdee.top/Article/details/gt2tjoqaxra.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zdqjudy.top/Article/details/gt2kfafxblp.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2ajfwcsoy.html

G. 面向对象
来源：http://dali.jlsjyb.cn/Article/details/gt2bazpmdee.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2qogtwedm.html

[G01] 定义类
来源：http://dali.yangfankeji.com/Article/details/gt2vcqebedm.html

Py:   class User: pass
来源：http://dali.zdqjudy.top/Article/details/gt2awkywpnr.html

PHP:  class User {}
来源：http://dali.pycfn.com/Article/details/gt2kkthkrza.html

JS:   class User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2dfpplvmj.html

TS:   class User { name: string = ""; }
来源：http://dali.aibaodan.cn/Article/details/gt2jglvyinu.html

Java: class User {}
来源：http://dali.tianlin.xyz/Article/details/gt2jztrlsnl.html

Go:   type User struct { Name string }
来源：http://dali.wangdashe.top/Article/details/gt2rccizzht.html

Ruby: class User; end
来源：http://dali.tanke756.top/Article/details/gt2tzacolmx.html

C#:   class User {}
来源：http://dali.yonumen.top/Article/details/gt2adogcnzb.html

[G02] 构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bdwswwkl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yangfankeji.com/Article/details/gt2ljumejxg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2ndmcahsd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2igcuihkg.html

TS:   constructor(public name: string) {}
来源：http://dali.ybcxt.top/Article/details/gt2ybeokndh.html

Java: User(String name) { this.name = name; }
来源：http://dali.hammf.cn/Article/details/gt2dgcwqozl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxecspka.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cdnleiting.top/Article/details/gt2juwrrcvm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sufxvd.cn/Article/details/gt2dlvyfncy.html

[G03] 实例属性
来源：http://dali.chenzaomai.com/Article/details/gt2rixrrauf.html

Py:   self.name = "x"
来源：http://dali.yueranfly.top/Article/details/gt2dwzqhatk.html

PHP:  public string $name = "x";
来源：http://dali.fzhhl.top/Article/details/gt2crumamxr.html

JS:   this.name = "x";
来源：http://dali.yueranfly.top/Article/details/gt2dvfnfucu.html

TS:   name: string = "x";
来源：http://dali.tianlin.xyz/Article/details/gt2xplaasgo.html

Java: private String name;
来源：http://dali.birdmap.top/Article/details/gt2vprndrcz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nexssefu.html

Ruby: @name = "x"
来源：http://dali.jqgufenzy.top/Article/details/gt2hyrkhyqx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.aibaodan.cn/Article/details/gt2mrqguale.html

[G04] 定义方法
来源：http://dali.sysykeji.top/Article/details/gt2iabkulqe.html

Py:   def greet(self): return self.name
来源：http://dali.daxiang520.top/Article/details/gt2quzurhgq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2cgjbsldx.html

JS:   greet() { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gt2wrfypqvn.html

TS:   greet(): string { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2ileigzyu.html

Java: String greet() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gt2icignecp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hysaishi.cn/Article/details/gt2uthhvxiq.html

Ruby: def greet; @name; end
来源：http://dali.cdnleiting.top/Article/details/gt2cabwijou.html

C#:   public string Greet() => Name;
来源：http://dali.jyoumei.cn/Article/details/gt2thfqkcpv.html

[G05] 继承
来源：http://dali.gogol.net.cn/Article/details/gt2hukmyevi.html

Py:   class Admin(User): pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ilvqnnlm.html

PHP:  class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gt2ohyftehc.html

JS:   class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gt2fjmdwusr.html

TS:   class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vkptxpgd.html

Java: class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gt2ctwzsrga.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jqgfzy.top/Article/details/gt2desacrzf.html

Ruby: class Admin < User; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ksbzrzlb.html

C#:   class Admin : User {}
来源：http://dali.yj20258.top/Article/details/gt2fhdnysgm.html

[G06] 重写方法
来源：http://dali.jinqigfzy.top/Article/details/gt2rgivscar.html

Py:   def greet(self): return "admin"
来源：http://dali.hfpthk.cn/Article/details/gt2rbofhpdh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gt2nneuclev.html

JS:   greet() { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gt2tkfwkgjp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2zyjltbdg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gt2jdeblfrn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinqigufen.top/Article/details/gt2ddoppxtt.html

Ruby: def greet; "admin"; end
来源：http://dali.yj202588.top/Article/details/gt2usaangas.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aeveumhl.html

[G07] 调用父类方法
来源：http://dali.sysykeji.top/Article/details/gt2grgttwdo.html

Py:   super().greet()
来源：http://dali.chenlongwang.top/Article/details/gt2sjtjfprs.html

PHP:  parent::greet();
来源：http://dali.0kj1m.cn/Article/details/gt2dchyirfw.html

JS:   super.greet();
来源：http://dali.iojbl.cn/Article/details/gt2jkswxgwa.html

TS:   super.greet();
来源：http://dali.gotoacloud.top/Article/details/gt2sehkoumk.html

Java: super.greet();
来源：http://dali.jiagoushi.top/Article/details/gt2ovdmaobp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rrvuiwfm.html

Ruby: super
来源：http://dali.yangfankeji.com/Article/details/gt2ajdxxnrm.html

C#:   base.Greet();
来源：http://dali.jqgfzy.top/Article/details/gt2zezeqqyo.html

[G08] 静态方法与属性
来源：http://dali.yuanzhike.top/Article/details/gt2gselmibp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.fzhhl.top/Article/details/gt2knlqomfe.html

PHP:  public static function f() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vswrcexb.html

JS:   static f() {}
来源：http://dali.ydzc1.top/Article/details/gt2ylqpwpoz.html

TS:   static f(): void {}
来源：http://dali.redwolf501.top/Article/details/gt2ibwhcziz.html

Java: static void f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2bblcdvlw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hywenlv.cn/Article/details/gt2myqzztky.html

Ruby: def self.f; end
来源：http://dali.zhongyouzk.top/Article/details/gt2hvfxttcy.html

C#:   public static void F() {}
来源：http://dali.gzhubu.top/Article/details/gt2opqumleh.html

[G09] 接口 / 抽象类
来源：http://dali.ybcxt.top/Article/details/gt2rqgiksvm.html


<!-- 参考信息 -->