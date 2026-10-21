代发 wailian999

Go:   strings.Count(s, "a")
来源：http://dali.hammf.cn/Article/details/gtvtinwuuo.html

Ruby: s.count("a")
来源：http://dali.jyoumei.cn/Article/details/gtwokaveou.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yanxiufei.cn/Article/details/gtoskbgvpb.html

[E13] 逐字符遍历
来源：http://dali.dianchejie.cn/Article/details/gtevqdsxwq.html

Py:   for ch in s: print(ch)
来源：http://dali.cucudq.cn/Article/details/gtjrofzned.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.dashuyun.cn/Article/details/gtphpxtkjy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aibaodan.cn/Article/details/gtcnowaioh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gtndrcczdy.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gtuzrjltpy.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jianghu66.top/Article/details/gtskawdmld.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hammf.cn/Article/details/gtnhhanzpg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shuidangran.top/Article/details/gtzoxvhtmv.html

[E14] URL 编码与 Base64
来源：http://dali.ivvv.top/Article/details/gtmfbqyirv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ppjwa.cn/Article/details/gtamaqzwhj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.c1oappe.top/Article/details/gtopluxvkq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shuidangran.top/Article/details/gtirlgjqmx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hywenlv.cn/Article/details/gtvwsvhvey.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.snrcjt.cn/Article/details/gtjlztawjt.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.chenlongwang.top/Article/details/gtoncjekwo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.andypj.xyz/Article/details/gtdiemcrxj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yvedp.cn/Article/details/gtwtwnlnip.html

[E15] HTML 转义 / 反转义
来源：http://dali.yuanzhike.top/Article/details/gtmfrsifcs.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shuidangran.top/Article/details/gtpmjytiwi.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jqgufenzy.top/Article/details/gtdcbmwdxe.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sxryk.cn/Article/details/gttfmqnzbx.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ydzc1.top/Article/details/gthhtwcpdg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hnqzz.top/Article/details/gtmrwnpcjh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.9152youxi.cn/Article/details/gtiaxpctrg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.mhx1999.top/Article/details/gtbccthzsx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtenfhoruc.html

[E16] 数字千分位
来源：http://dali.tanke756.top/Article/details/gtrohtynpz.html

Py:   f"{1234567:,}"
来源：http://dali.shuidangran.top/Article/details/gtuwgquswq.html

PHP:  number_format(1234567);
来源：http://dali.zhixingplan.top/Article/details/gtllppchhc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jlsjyb.cn/Article/details/gtbccgldlw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jyoumei.cn/Article/details/gtyvxxryvy.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.snrcjt.cn/Article/details/gtliiitvvl.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hnxiangtu.top/Article/details/gtixkebkan.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gthzzvtosz.html

C#:   1234567.ToString("N0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlukzosqz.html

[E17] 首字母大写
来源：http://dali.kuanghao11.cn/Article/details/gtbdxelihy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtavbpddzp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sweek.top/Article/details/gtktffpkrk.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xinyue.icu/Article/details/gtbwjhxeyu.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nwbrower.top/Article/details/gtrflfjuhw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yanxiufei.cn/Article/details/gtoeqgmfka.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sufxvd.cn/Article/details/gttimpdpvq.html

Ruby: s.capitalize
来源：http://dali.sweek.top/Article/details/gtywhrkbza.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ehwqpu.com/Article/details/gtjcgptius.html

[E18] 模板占位符替换
来源：http://dali.gotoacloud.top/Article/details/gtionfmutv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.svipenyu.cn/Article/details/gttqvibria.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.aibaodan.cn/Article/details/gtgtzmorbb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gtjfvgllak.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gtjzptsboi.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gtpjebhyca.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.bjfxy.top/Article/details/gtxcxonmbn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj202588.top/Article/details/gtaxtxfcmq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.kuanghao11.cn/Article/details/gtbdvjoyar.html

[E19] 多行文本按行拆分
来源：http://dali.fengsongda.top/Article/details/gtockhosrp.html

Py:   s.splitlines()
来源：http://dali.0kj1m.cn/Article/details/gtiebdrkdt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtnhihnayl.html

JS:   s.split(/\r?\n/)
来源：http://dali.guannengcc.top/Article/details/gtkdpxhzyb.html

TS:   s.split(/\r?\n/)
来源：http://dali.cheryme.top/Article/details/gtxjtwmkxh.html

Java: s.lines().toList()
来源：http://dali.gaohongyu789.top/Article/details/gtwoyrhhhl.html

Go:   strings.Split(s, "\n")
来源：http://dali.ppjwa.cn/Article/details/gtbeaxfvnu.html

Ruby: s.lines
来源：http://dali.daria6918.cn/Article/details/gtbsgvzaig.html

C#:   s.Split('\n')
来源：http://dali.aizwys.cn/Article/details/gtexfbdouk.html

[E20] 判断字符串是否为空
来源：http://dali.zhiwuduotai.top/Article/details/gtbjvnaymk.html

Py:   if not s:
来源：http://dali.hnqzz.top/Article/details/gtfkpmghix.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.iojbl.cn/Article/details/gtvdmjhenq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.meibo888.top/Article/details/gtbzrtqifi.html

TS:   if (s === "") {}
来源：http://dali.c1oappe.top/Article/details/gtuainurgl.html

Java: if (s.isEmpty()) {}
来源：http://dali.quarkkingdee.top/Article/details/gtozpbtjfn.html

Go:   if s == "" {}
来源：http://dali.yuxming.cn/Article/details/gtmnslcupp.html

Ruby: if s.empty?
来源：http://dali.sysykeji.top/Article/details/gtvoluxzrr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shuidangran.top/Article/details/gtsxrlkhqf.html

[E21] 超长截断加省略号
来源：http://dali.tanke756.top/Article/details/gtaxlndufo.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xylfe.cn/Article/details/gtkxqizavq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnsrxljii.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtybjkoyde.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gtpnbudagf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gtzholqhnu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.guowangkeji.top/Article/details/gtzxixbsbr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtpkqzylwd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtmxgybfzk.html

[E22] 字节长度与字符长度
来源：http://dali.hywenlv.cn/Article/details/gtryfddosg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgqcpmbcl.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gtzerpjgby.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yangfankeji.com/Article/details/gtydjooqfl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenlongwang.top/Article/details/gtkyocfpds.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shzxlz.cn/Article/details/gtmljdltir.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jiagoushi.top/Article/details/gtlqhamvwq.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gtyoliwbqd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hnqzz.top/Article/details/gtmkeogcsu.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkvhxdobf.html

F. 文件与目录
来源：http://dali.chenzaomai.com/Article/details/gtnrbsiudq.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtibqqdmrz.html

[F01] 读取整个文件
来源：http://dali.9152youxi.cn/Article/details/gtcesvhgcj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.dashuyun.cn/Article/details/gtsnjpchot.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yonumen.top/Article/details/gtnmkufugv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.guannengcc.top/Article/details/gtfhwpgioy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.sysykeji.top/Article/details/gtdeniakuq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gtnjsqarsn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.iojbl.cn/Article/details/gtenqgcbyc.html

Ruby: File.read("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtghcydvwv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtobvtkvsr.html

[F02] 逐行读取文件
来源：http://dali.jianghu66.top/Article/details/gtcvkalezc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.svipenyu.cn/Article/details/gtuqreknkm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.havefunace.top/Article/details/gtfcndfvlb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgfzy.top/Article/details/gtmuhenqlm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.haohaochexian.top/Article/details/gtawuwltje.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tian-w.cn/Article/details/gtzxpnqwng.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrdvrnahx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jianghu66.top/Article/details/gtcrylxtqx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zdqjudy.top/Article/details/gthwaqjxxp.html

[F03] 写入文件（覆盖）
来源：http://dali.pycfn.com/Article/details/gtfwlxmsga.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.vqdsnc.cn/Article/details/gtnhdwtxhd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zdqjudy.top/Article/details/gtqfvbvwfj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.vqdsnc.cn/Article/details/gtuhnjkhqt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbmjlyerj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenlongwang.top/Article/details/gtflucxdfc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.guannengcc.top/Article/details/gtzpyvpcfn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sweek.top/Article/details/gthdysollw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gtzycvdpgl.html

[F04] 追加写入文件
来源：http://dali.redwolf501.top/Article/details/gtdutvnwmz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ppjwa.cn/Article/details/gtnaslnazo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yj20258888.top/Article/details/gtdlueuwan.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hywenlv.cn/Article/details/gtgairzdyj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gogol.net.cn/Article/details/gtyngierrv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenzaomai.com/Article/details/gtaunbjidx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtwgxcaneh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhoulong.xyz/Article/details/gtugdxkzuy.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shuidangran.top/Article/details/gtaozjaqpx.html

[F05] 判断文件或目录是否存在
来源：http://dali.tanke756.top/Article/details/gtvfgogwgc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tanke756.top/Article/details/gtcfgnlkdu.html

PHP:  file_exists("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtzqtnukpp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtwvlfazid.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpqisarcc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvslxyxoc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tian-w.cn/Article/details/gtzhjpnaof.html

Ruby: File.exist?("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtayjcvbvx.html

C#:   File.Exists("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtthbzehrz.html

[F06] 删除文件
来源：http://dali.9152youxi.cn/Article/details/gtyyxgvupw.html

Py:   os.remove("a.txt")
来源：http://dali.cheryme.top/Article/details/gtzzxrbkgv.html

PHP:  unlink("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gthanfsrng.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtfadvmeus.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtvrqlljdp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gtcgcqcznk.html

Go:   os.Remove("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtweltnwhv.html

Ruby: File.delete("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtqlyjialk.html

C#:   File.Delete("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtfdwwfigo.html

[F07] 创建目录（含多级）
来源：http://dali.nanxuanxn.top/Article/details/gtpumtighy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zdqjudy.top/Article/details/gtfacdzzmi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ybcxt.top/Article/details/gtbvpvmocu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtudepfbev.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pengpengdd.cyou/Article/details/gtxxujnspw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.chenlongwang.top/Article/details/gtillzzmkp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tianlin.xyz/Article/details/gtpksdqdqm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.daria6918.cn/Article/details/gtdxcjhpnt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hysaishi.cn/Article/details/gttakqjmsv.html

[F08] 遍历目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gtufyudaov.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cashguo.top/Article/details/gtbkhganof.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj20258888.top/Article/details/gtbkixgqju.html

JS:   fs.readdirSync("dir")
来源：http://dali.yuxming.cn/Article/details/gtihxoupfd.html

TS:   fs.readdirSync("dir")
来源：http://dali.yvedp.cn/Article/details/gtlbauqnug.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.aizwys.cn/Article/details/gtrktninix.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpjtvgzjl.html

Ruby: Dir.children("dir")
来源：http://dali.haohaochexian.top/Article/details/gtjcpmctzp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.redwolf501.top/Article/details/gtisadzfmt.html

[F09] 获取文件大小
来源：http://dali.wangshuangyany.cn/Article/details/gtkajyqlxx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.316326.xyz/Article/details/gthxuutdyn.html

PHP:  filesize("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtzqzphwxt.html

JS:   fs.statSync("a.txt").size
来源：http://dali.kuanghao11.cn/Article/details/gtjjjzkird.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwhdwompc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaokcfibh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zdqjudy.top/Article/details/gtywajbpsk.html

Ruby: File.size("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtzgnmffdb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.dianchejie.cn/Article/details/gtgkoxkpii.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yanxiufei.cn/Article/details/gtowondums.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gthbnpiyep.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.andypj.xyz/Article/details/gtchbflhsi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtvzjbthgw.html

TS:   path.extname("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtbtsstcnq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.meibo888.top/Article/details/gtcydeeudy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtvjzljryl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtreamlnyy.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gtuabgyllv.html

[F11] 复制与移动文件
来源：http://dali.daria6918.cn/Article/details/gtymbemqri.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmyhegiv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yj20258888.top/Article/details/gtfbpnzwgn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gttilzxudp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gthwjqpcjx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xziqi.cn/Article/details/gtsmrbphqt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.aizwys.cn/Article/details/gtfzrhkfzi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtbdqczkpi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tianlin.xyz/Article/details/gtyssgyfms.html

[F12] CSV 读写
来源：http://dali.cqqwz.cn/Article/details/gtwahczsgf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jqgfzy.top/Article/details/gtxdkresgn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.mhx1999.top/Article/details/gtesdpwmaj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.guowangkeji.top/Article/details/gtfwhlktra.html

TS:   // 同上
来源：http://dali.cashguo.top/Article/details/gthshoqsjz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cdnleiting.top/Article/details/gtebivjhpk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yongpay.top/Article/details/gtlujbxgpj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cucudq.cn/Article/details/gttosiycrt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hnqzz.top/Article/details/gtcvulwuxk.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtoxqmfhht.html

G. 面向对象
来源：http://dali.feifeiyinyue.top/Article/details/gtvzfvaxkk.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtcajztqtv.html

[G01] 定义类
来源：http://dali.tian-w.cn/Article/details/gtxkcujazb.html

Py:   class User: pass
来源：http://dali.svipenyu.cn/Article/details/gtanoggnqv.html

PHP:  class User {}
来源：http://dali.yj20258888.top/Article/details/gtwgjlumfc.html

JS:   class User {}
来源：http://dali.yj202588.top/Article/details/gtpwprctyx.html

TS:   class User { name: string = ""; }
来源：http://dali.hnxiangtu.top/Article/details/gtwlydjlrz.html

Java: class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbuhfjfxo.html

Go:   type User struct { Name string }
来源：http://dali.shuidangran.top/Article/details/gtyawfxhic.html

Ruby: class User; end
来源：http://dali.xinyue.icu/Article/details/gtcxdewhjv.html

C#:   class User {}
来源：http://dali.yangfankeji.com/Article/details/gtyhpzfhen.html

[G02] 构造函数
来源：http://dali.yuanzhike.top/Article/details/gttzjykwhe.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cucudq.cn/Article/details/gthyzqbzod.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtorgwgjkf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yueranfly.top/Article/details/gtnkafwgqj.html

TS:   constructor(public name: string) {}
来源：http://dali.jqgfzy.top/Article/details/gtmddswgnx.html

Java: User(String name) { this.name = name; }
来源：http://dali.gogol.net.cn/Article/details/gtdfkvumzu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.daria6918.cn/Article/details/gtxhtqxpgp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.meibo888.top/Article/details/gtwlprrgwq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.guannengcc.top/Article/details/gtnitdfoix.html

[G03] 实例属性
来源：http://dali.chenzaomai.com/Article/details/gtrumtozfj.html

Py:   self.name = "x"
来源：http://dali.yj20258888.top/Article/details/gtinrziqxi.html

PHP:  public string $name = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvyxggwho.html

JS:   this.name = "x";
来源：http://dali.meibo888.top/Article/details/gtzdxlqihw.html

TS:   name: string = "x";
来源：http://dali.yonumen.top/Article/details/gtczmetojd.html

Java: private String name;
来源：http://dali.zhongyouzk.top/Article/details/gtdkcugfki.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj202588.top/Article/details/gtkugfagtb.html

Ruby: @name = "x"
来源：http://dali.yvedp.cn/Article/details/gtekqfogyi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.svipenyu.cn/Article/details/gtwkalsjuk.html

[G04] 定义方法
来源：http://dali.yueranfly.top/Article/details/gtcuefwksi.html

Py:   def greet(self): return self.name
来源：http://dali.zhoulong.xyz/Article/details/gtuckzxazc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gtpiggremq.html

JS:   greet() { return this.name; }
来源：http://dali.meibo888.top/Article/details/gtgkaoklpm.html

TS:   greet(): string { return this.name; }
来源：http://dali.tanke756.top/Article/details/gtdjdirbnh.html

Java: String greet() { return name; }
来源：http://dali.xziqi.cn/Article/details/gtbiwtlnlw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gtmybwlwvv.html

Ruby: def greet; @name; end
来源：http://dali.zhengqikj.top/Article/details/gtyojofurw.html

C#:   public string Greet() => Name;
来源：http://dali.aibaodan.cn/Article/details/gtvwscjqhf.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gtjyvvpekh.html

Py:   class Admin(User): pass
来源：http://dali.yj20258888.top/Article/details/gtkibnhpms.html

PHP:  class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gttvkjzpkr.html

JS:   class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gtwlgserod.html

TS:   class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtnhznwrqi.html

Java: class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gtnkuziyrr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sweek.top/Article/details/gtqquhsvmp.html

Ruby: class Admin < User; end
来源：http://dali.havefunace.top/Article/details/gtokolciwm.html

C#:   class Admin : User {}
来源：http://dali.guannengcc.top/Article/details/gtarjrmaih.html

[G06] 重写方法
来源：http://dali.tianlin.xyz/Article/details/gthvncrlbd.html

Py:   def greet(self): return "admin"
来源：http://dali.chenjidiqi.icu/Article/details/gtbboxamiq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gtfzuiunvh.html

JS:   greet() { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gtgfvntvhk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtbhdqsmhp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtlwzlrcjh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.0kj1m.cn/Article/details/gtbhfhkicr.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigfzy.top/Article/details/gtivrctmzi.html

C#:   public override string Greet() => "admin";
来源：http://dali.jyoumei.cn/Article/details/gtvtfgfyfr.html

[G07] 调用父类方法
来源：http://dali.daria6918.cn/Article/details/gtqypxysud.html

Py:   super().greet()
来源：http://dali.cucudq.cn/Article/details/gtzywdznbe.html

PHP:  parent::greet();
来源：http://dali.vqdsnc.cn/Article/details/gtsliqpjux.html

JS:   super.greet();
来源：http://dali.sufxvd.cn/Article/details/gtroiwsdfn.html

TS:   super.greet();
来源：http://dali.cheryme.top/Article/details/gtyykpczlv.html

Java: super.greet();
来源：http://dali.chenlongwang.top/Article/details/gtflgqfqzr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xylfe.cn/Article/details/gtotshlnjl.html

Ruby: super
来源：http://dali.mhx1999.top/Article/details/gtgqpfcxew.html

C#:   base.Greet();
来源：http://dali.ehwqpu.com/Article/details/gtledxivqi.html

[G08] 静态方法与属性
来源：http://dali.yj20258888.top/Article/details/gtlmgdgfyp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hywenlv.cn/Article/details/gtzjetplro.html

PHP:  public static function f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gtjdjdvfbe.html

JS:   static f() {}
来源：http://dali.hammf.cn/Article/details/gtgyuuwcax.html

TS:   static f(): void {}
来源：http://dali.chenlongwang.top/Article/details/gtanthnwjc.html

Java: static void f() {}
来源：http://dali.kuanghao11.cn/Article/details/gttcjqhyul.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cqqwz.cn/Article/details/gtghbliblu.html

Ruby: def self.f; end
来源：http://dali.c1oappe.top/Article/details/gtzkjtuyho.html

C#:   public static void F() {}
来源：http://dali.xuetiantiany.cn/Article/details/gtbfibixoi.html

[G09] 接口 / 抽象类
来源：http://dali.jiagoushi.top/Article/details/gtdeaddnjg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sysykeji.top/Article/details/gtcjnjojvj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.pycfn.com/Article/details/gtzymspbjx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hywenlv.cn/Article/details/gtuvxymtmm.html

TS:   interface Shape { area(): number; }
来源：http://dali.hammf.cn/Article/details/gtjajbiupg.html

Java: interface Shape { double area(); }
来源：http://dali.yuanzhike.top/Article/details/gtuvsmpnru.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gtxzddbxyj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sxryk.cn/Article/details/gtftpcgcsx.html

C#:   interface IShape { double Area(); }
来源：http://dali.vqdsnc.cn/Article/details/gthbmbgyrd.html

[G10] 访问控制
来源：http://dali.yuanzhike.top/Article/details/gtfzrvfhbu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nwbrower.top/Article/details/gtjseouxlh.html

PHP:  public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gtbglawerq.html

JS:   #private 字段；其余公开
来源：http://dali.svipenyu.cn/Article/details/gtsczaonef.html

TS:   public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gtyqqbpctm.html

Java: public / protected / private / 默认包级
来源：http://dali.daria6918.cn/Article/details/gtfjnauntr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.pycfn.com/Article/details/gtavtpubku.html

Ruby: public / protected / private
来源：http://dali.daria6918.cn/Article/details/gtxkbxlngb.html

C#:   public / protected / private / internal
来源：http://dali.shanyushiyangtech.top/Article/details/gtekmihgtl.html

[G11] getter / setter
来源：http://dali.wangdashe.top/Article/details/gtulcochiv.html

Py:   @property 与 @x.setter
来源：http://dali.haohaochexian.top/Article/details/gtzurqpxjy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gtpvwitavr.html


<!-- 参考信息 -->