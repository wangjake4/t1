代发 wailian999

TS:   "7".padStart(3, "0")
来源：http://dali.yvedp.cn/Article/details/gtbvihbbkh.html

Java: String.format("%03d", 7)
来源：http://dali.svipenyu.cn/Article/details/gtedkzjnzi.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gtzitrgvur.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hysaishi.cn/Article/details/gtunsitnpf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jqgufenzy.top/Article/details/gtjeugaksf.html

[E11] 反转字符串
来源：http://dali.cdnleiting.top/Article/details/gtdxhlxenp.html

Py:   s[::-1]
来源：http://dali.andypj.xyz/Article/details/gtvnoijevz.html

PHP:  strrev($s);
来源：http://dali.havefunace.top/Article/details/gtsyejxmix.html

JS:   [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gtrfjscysf.html

TS:   [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gtqhiacixr.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xylfe.cn/Article/details/gtaxlcodor.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jiagoushi.top/Article/details/gtngzgwjpv.html

Ruby: s.reverse
来源：http://dali.hywenlv.cn/Article/details/gtrewiccgf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.c1oappe.top/Article/details/gtlweuiajr.html

[E12] 统计某字符出现次数
来源：http://dali.mhx1999.top/Article/details/gtztdomnqq.html

Py:   s.count("a")
来源：http://dali.nanxinkj.top/Article/details/gtqroibntq.html

PHP:  substr_count($s, "a");
来源：http://dali.bjfxy.top/Article/details/gtsqzljdle.html

JS:   s.split("a").length - 1
来源：http://dali.hywenlv.cn/Article/details/gtjcksnggl.html

TS:   s.split("a").length - 1
来源：http://dali.zhengqikj.top/Article/details/gtjazwaetd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jqgfzy.top/Article/details/gtbicuuunb.html

Go:   strings.Count(s, "a")
来源：http://dali.hfpthk.cn/Article/details/gtyatczfra.html

Ruby: s.count("a")
来源：http://dali.ehwqpu.com/Article/details/gtoakystrm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xziqi.cn/Article/details/gtkcjtximi.html

[E13] 逐字符遍历
来源：http://dali.yuanzhike.top/Article/details/gtqpowxpzm.html

Py:   for ch in s: print(ch)
来源：http://dali.ehwqpu.com/Article/details/gtctltxwpk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.havefunace.top/Article/details/gtdvgietcs.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.meibo888.top/Article/details/gtxsbbafgk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.snrcjt.cn/Article/details/gtjwdmxzsd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmkchleak.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zycfv.cn/Article/details/gtglbsgxvi.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.haohaochexian.top/Article/details/gtcclvfnuv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yj20258888.top/Article/details/gtkpptkpfw.html

[E14] URL 编码与 Base64
来源：http://dali.hnqzz.top/Article/details/gtzpmikqmy.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.guannengcc.top/Article/details/gtniclnwya.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cdnleiting.top/Article/details/gtcztyahar.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.haohaochexian.top/Article/details/gtigowcins.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlchorprl.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gogol.net.cn/Article/details/gtuvmyjymd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sweek.top/Article/details/gtzwjhazhw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.tian-w.cn/Article/details/gtcmglxfdc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.snrcjt.cn/Article/details/gtjfxoqzdx.html

[E15] HTML 转义 / 反转义
来源：http://dali.yj202588.top/Article/details/gtibooejgl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzjbsmuar.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.bjfxy.top/Article/details/gtlnrxkdal.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hnxiangtu.top/Article/details/gtqsxtahnc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sxryk.cn/Article/details/gtvooktkpf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ehwqpu.com/Article/details/gtrhtbaxhf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnwjawvrh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.guowangkeji.top/Article/details/gtavoialva.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.wangdashe.top/Article/details/gtyhiijmhn.html

[E16] 数字千分位
来源：http://dali.fzhhl.top/Article/details/gtxmrjvbyx.html

Py:   f"{1234567:,}"
来源：http://dali.ehwqpu.com/Article/details/gtfhbftxkq.html

PHP:  number_format(1234567);
来源：http://dali.guannengcc.top/Article/details/gtmkbjxpso.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.fzhhl.top/Article/details/gtigineuit.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jyoumei.cn/Article/details/gtvpyjhnyz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.fengsongda.top/Article/details/gtcjugseyl.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tanke756.top/Article/details/gtbbzvhera.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.wangshuangyany.cn/Article/details/gtptvflepp.html

C#:   1234567.ToString("N0")
来源：http://dali.hywenlv.cn/Article/details/gtlqjzcuwz.html

[E17] 首字母大写
来源：http://dali.ppjwa.cn/Article/details/gtiehggpgb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gzhubu.top/Article/details/gtivenbfbx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.fzhhl.top/Article/details/gtbzelscud.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuanzx.com/Article/details/gtgglorvqk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tian-w.cn/Article/details/gttyintngg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gaohongyu789.top/Article/details/gtbbbtpjuy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yonumen.top/Article/details/gtscaqykcy.html

Ruby: s.capitalize
来源：http://dali.meibo888.top/Article/details/gtckqtdrhr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cashguo.top/Article/details/gtonsxwscp.html

[E18] 模板占位符替换
来源：http://dali.ehwqpu.com/Article/details/gtpnsmhpos.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cdnleiting.top/Article/details/gthtxaqhai.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jiagoushi.top/Article/details/gtztjvorng.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gtrhqdzhei.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj202588.top/Article/details/gtrgweuubq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gtndfvqpds.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgyryubsf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tian-w.cn/Article/details/gtafguytbm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ppjwa.cn/Article/details/gtmmbrfhrl.html

[E19] 多行文本按行拆分
来源：http://dali.snrcjt.cn/Article/details/gtgbpyazsy.html

Py:   s.splitlines()
来源：http://dali.gotoacloud.top/Article/details/gtwhwaoiwt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yongpay.top/Article/details/gtersxqvjw.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinqigufen.top/Article/details/gtckbiewom.html

TS:   s.split(/\r?\n/)
来源：http://dali.cdnleiting.top/Article/details/gtjoszkfqk.html

Java: s.lines().toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtxefhotiz.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj20258.top/Article/details/gtztuafajo.html

Ruby: s.lines
来源：http://dali.yuxming.cn/Article/details/gtsytbykdf.html

C#:   s.Split('\n')
来源：http://dali.wangdashe.top/Article/details/gtchwkyxny.html

[E20] 判断字符串是否为空
来源：http://dali.nanxinkj.top/Article/details/gtwzykzxgp.html

Py:   if not s:
来源：http://dali.meibo888.top/Article/details/gtingtnoyg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hammf.cn/Article/details/gtmsdopayu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gotoacloud.top/Article/details/gthyprdubi.html

TS:   if (s === "") {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtixrfcibe.html

Java: if (s.isEmpty()) {}
来源：http://dali.andypj.xyz/Article/details/gtwjzipspv.html

Go:   if s == "" {}
来源：http://dali.chenzaomai.com/Article/details/gtgkgcspvv.html

Ruby: if s.empty?
来源：http://dali.havefunace.top/Article/details/gtwzuiacie.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ydzc1.top/Article/details/gtwyxapzfq.html

[E21] 超长截断加省略号
来源：http://dali.hnqzz.top/Article/details/gtwlfxyvmo.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.kuanghao11.cn/Article/details/gtggbhgsug.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gtkrueifba.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gtfwhmxoko.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xinyue.icu/Article/details/gtasdelmvp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtcghbvefq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jqgfzy.top/Article/details/gtbqxsxwkr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvdktowix.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gthfuimjkv.html

[E22] 字节长度与字符长度
来源：http://dali.xinyue.icu/Article/details/gtkoxgitbm.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.meibo888.top/Article/details/gtbhbtihmg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gtjepvsito.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sufxvd.cn/Article/details/gtafprdgzs.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xziqi.cn/Article/details/gtlkahghrd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.snrcjt.cn/Article/details/gtkaduwalo.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hammf.cn/Article/details/gtolelfgiv.html

Ruby: s.bytesize;  s.length
来源：http://dali.jqgufenzy.top/Article/details/gtqgywrofu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yuanzhike.top/Article/details/gtcyxmqkxf.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtiwtguxyy.html

F. 文件与目录
来源：http://dali.yuanzhike.top/Article/details/gtkmqtvpci.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtpfcymwyb.html

[F01] 读取整个文件
来源：http://dali.shangyingyoupin.top/Article/details/gtjuopmcvi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xuanzx.com/Article/details/gtesdbtqlb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtxpcolaix.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhoulong.xyz/Article/details/gtmxqiqbgt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gtrhhelmry.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gtndqgiqvs.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yj20258888.top/Article/details/gtoekwrboh.html

Ruby: File.read("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtvsoboqdf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtjrsbrbvk.html

[F02] 逐行读取文件
来源：http://dali.shangyingyoupin.top/Article/details/gtciuwmlvm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ivvv.top/Article/details/gtscwbpqgn.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ydzc1.top/Article/details/gtbjgbiepo.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ehwqpu.com/Article/details/gthswszrmk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cashguo.top/Article/details/gtulpubxyv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.guannengcc.top/Article/details/gtxmfdxhsx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.0kj1m.cn/Article/details/gtitdamcwg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.chenzaomai.com/Article/details/gtisykzfmb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.pengpengdd.cyou/Article/details/gtvxojfmek.html

[F03] 写入文件（覆盖）
来源：http://dali.pycfn.com/Article/details/gtecgjewlc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.kuanghao11.cn/Article/details/gtglugcpfp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jianghu66.top/Article/details/gtdyootlww.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gtwkbwzzbl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.kuanghao11.cn/Article/details/gtytubzwah.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhengqikj.top/Article/details/gtebgmtwcx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.andypj.xyz/Article/details/gtoelcnrbv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hywenlv.cn/Article/details/gtxoiehshc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.pycfn.com/Article/details/gtgalcuwxf.html

[F04] 追加写入文件
来源：http://dali.yanxiufei.cn/Article/details/gtkyhnjsuy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jiagoushi.top/Article/details/gtfvmsqqwm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.guowangkeji.top/Article/details/gtkbpmikaw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gotoacloud.top/Article/details/gtoshpgivi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gogol.net.cn/Article/details/gtqzsmuncg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zdqjudy.top/Article/details/gtcobflcck.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sxryk.cn/Article/details/gtcbbuzrqn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xuanzx.com/Article/details/gtmnlmhbal.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinqigfzy.top/Article/details/gtfmznlprx.html

[F05] 判断文件或目录是否存在
来源：http://dali.hfpthk.cn/Article/details/gtansjzjwm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.dashuyun.cn/Article/details/gtezenezql.html

PHP:  file_exists("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlrfsicgf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtqcgqwkxp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtebwyydzd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtsuwpwigi.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yanxiufei.cn/Article/details/gtjjqgrtvg.html

Ruby: File.exist?("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtdizjfxey.html

C#:   File.Exists("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtumqhjbak.html

[F06] 删除文件
来源：http://dali.wangshuangyany.cn/Article/details/gtsgcvgiqk.html

Py:   os.remove("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtonxdlwco.html

PHP:  unlink("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtgbmogjlz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gtgvxlrwjs.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtkqzfyjiy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gtpgyufvcv.html

Go:   os.Remove("a.txt")
来源：http://dali.sweek.top/Article/details/gtvsndnrdn.html

Ruby: File.delete("a.txt")
来源：http://dali.birdmap.top/Article/details/gtxtxxpeir.html

C#:   File.Delete("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gttgenwlws.html

[F07] 创建目录（含多级）
来源：http://dali.zhixingplan.top/Article/details/gtixfuiqbj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.chenlongwang.top/Article/details/gteydynswb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hywenlv.cn/Article/details/gtgqqxruxa.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.0kj1m.cn/Article/details/gtajzfqwcd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.kuanghao11.cn/Article/details/gtntwrgfno.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.wangshuangyany.cn/Article/details/gtfeallroc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zycfv.cn/Article/details/gtupmgwufe.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj20258.top/Article/details/gtdpnilohc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hammf.cn/Article/details/gtvbhhpezl.html

[F08] 遍历目录
来源：http://dali.chenzaomai.com/Article/details/gthehdwguc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenlongwang.top/Article/details/gteqsxvwns.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yueranfly.top/Article/details/gtsiwpttnm.html

JS:   fs.readdirSync("dir")
来源：http://dali.shuidangran.top/Article/details/gtalbtjbsf.html

TS:   fs.readdirSync("dir")
来源：http://dali.haohaochexian.top/Article/details/gtczgkmugt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yonumen.top/Article/details/gtymrwddny.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhixingplan.top/Article/details/gtaiuykfwn.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gthebuqnwc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jiagoushi.top/Article/details/gtrkmbygmw.html

[F09] 获取文件大小
来源：http://dali.redwolf501.top/Article/details/gtwndrhglq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cashguo.top/Article/details/gtltqmzkwt.html

PHP:  filesize("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtoxwttfbm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.kuanghao11.cn/Article/details/gtopwjfnda.html

TS:   fs.statSync("a.txt").size
来源：http://dali.dashuyun.cn/Article/details/gtgcfeoyum.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gtocrihdzv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinqigfzy.top/Article/details/gtzahgvrpz.html

Ruby: File.size("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtmleprjaw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hysaishi.cn/Article/details/gtebzomtus.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.mhx1999.top/Article/details/gttsaqvved.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtjukdwkgv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.aizwys.cn/Article/details/gtssddyrwm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtqhqvjtys.html

TS:   path.extname("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtllauihgy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhengqikj.top/Article/details/gtnxexexij.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtujnkcohf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtonhwbkly.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtjszpzfzi.html

[F11] 复制与移动文件
来源：http://dali.ivvv.top/Article/details/gtcsazlgpv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtlzybsyax.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sysykeji.top/Article/details/gtslafnyey.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtzhlsigoj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gtapzfigsg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.iojbl.cn/Article/details/gtlfumqyle.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj202588.top/Article/details/gtflynqqyb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtmcrlosrd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zdqjudy.top/Article/details/gtazxkqpoz.html

[F12] CSV 读写
来源：http://dali.jinqigufen.top/Article/details/gtcwdlhnmd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gotoacloud.top/Article/details/gtlrxklkpn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenzaomai.com/Article/details/gtyhvswnrq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yvedp.cn/Article/details/gtmrfrzcmy.html

TS:   // 同上
来源：http://dali.feifeiyinyue.top/Article/details/gtyxuqrcsi.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.meibo888.top/Article/details/gtnkcehzyx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.wangshuangyany.cn/Article/details/gtolmiknmn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hnxiangtu.top/Article/details/gtiaqfclej.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhoulong.xyz/Article/details/gtepqevkct.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtdbibozdx.html

G. 面向对象
来源：http://dali.yuxming.cn/Article/details/gtwxiquwcz.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtymcrdjls.html

[G01] 定义类
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvxuippsk.html

Py:   class User: pass
来源：http://dali.nanxinkj.top/Article/details/gtylmilwqc.html

PHP:  class User {}
来源：http://dali.chenlongwang.top/Article/details/gtjtsrbsgc.html

JS:   class User {}
来源：http://dali.jinqigufen.top/Article/details/gtmnvzgfqd.html

TS:   class User { name: string = ""; }
来源：http://dali.zhoulong.xyz/Article/details/gtcmekyfji.html

Java: class User {}
来源：http://dali.yj202588.top/Article/details/gthjyyhbry.html

Go:   type User struct { Name string }
来源：http://dali.snrcjt.cn/Article/details/gtqqipuegl.html

Ruby: class User; end
来源：http://dali.zhixingplan.top/Article/details/gtrgsikelj.html

C#:   class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtyjpcpjcv.html

[G02] 构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjfugaqey.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yueranfly.top/Article/details/gtxxlirvjb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yuanzhike.top/Article/details/gttrlcrhhb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hywenlv.cn/Article/details/gtrqvclexw.html

TS:   constructor(public name: string) {}
来源：http://dali.haohaochexian.top/Article/details/gtotpunajt.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gtzacauqld.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xziqi.cn/Article/details/gtrurhyszy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shangyingyoupin.top/Article/details/gthqojektu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cucudq.cn/Article/details/gtbfsjhbqm.html

[G03] 实例属性
来源：http://dali.aibaodan.cn/Article/details/gtkbqkjchl.html

Py:   self.name = "x"
来源：http://dali.nanxinkj.top/Article/details/gtjljqquzz.html

PHP:  public string $name = "x";
来源：http://dali.birdmap.top/Article/details/gtxiykohci.html

JS:   this.name = "x";
来源：http://dali.tianlin.xyz/Article/details/gtknwwfhuv.html

TS:   name: string = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gthuopfiix.html

Java: private String name;
来源：http://dali.tianlin.xyz/Article/details/gtacpgiqlc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jlsjyb.cn/Article/details/gtsaxlieij.html

Ruby: @name = "x"
来源：http://dali.daxiang520.top/Article/details/gturnwtixr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jiagoushi.top/Article/details/gtlwwudcrc.html

[G04] 定义方法
来源：http://dali.daria6918.cn/Article/details/gtioqrdugf.html

Py:   def greet(self): return self.name
来源：http://dali.aibaodan.cn/Article/details/gtsdpcfdgb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gtsmduaxwo.html

JS:   greet() { return this.name; }
来源：http://dali.cashguo.top/Article/details/gtlacpkcve.html

TS:   greet(): string { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gtgdyelzsd.html

Java: String greet() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtpklszifs.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.havefunace.top/Article/details/gtalbajfto.html

Ruby: def greet; @name; end
来源：http://dali.kuanghao11.cn/Article/details/gtlonvefdy.html

C#:   public string Greet() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdjsfvsqt.html

[G05] 继承
来源：http://dali.zhoulong.xyz/Article/details/gtywtcxdrz.html

Py:   class Admin(User): pass
来源：http://dali.haohaochexian.top/Article/details/gtlggrbsig.html

PHP:  class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gtrtindbla.html

JS:   class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxokjmhra.html

TS:   class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtkuvgbcwu.html

Java: class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gtnbzewfqt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hnxiangtu.top/Article/details/gtdzgozoiy.html

Ruby: class Admin < User; end
来源：http://dali.birdmap.top/Article/details/gtafcdsaxz.html

C#:   class Admin : User {}
来源：http://dali.gaohongyu789.top/Article/details/gtpfuissds.html

[G06] 重写方法
来源：http://dali.nanxuanxn.top/Article/details/gtoycywpsf.html

Py:   def greet(self): return "admin"
来源：http://dali.jqgufenzy.top/Article/details/gtmzzypyvw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtprxioqos.html

JS:   greet() { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtebehaqgi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gtvjjtdrjs.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gtxgpzaqfu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.birdmap.top/Article/details/gteuowcasp.html

Ruby: def greet; "admin"; end
来源：http://dali.yangfankeji.com/Article/details/gtexcbsxos.html

C#:   public override string Greet() => "admin";
来源：http://dali.wangshuangyany.cn/Article/details/gtcxifoggi.html

[G07] 调用父类方法
来源：http://dali.vqdsnc.cn/Article/details/gtvsgqixbg.html

Py:   super().greet()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtetwbphip.html

PHP:  parent::greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbdvxmzzb.html

JS:   super.greet();
来源：http://dali.aizwys.cn/Article/details/gtsnsazrlq.html

TS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gtwvofjrvl.html

Java: super.greet();
来源：http://dali.xylfe.cn/Article/details/gtiaibacky.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hongshengwenyu.top/Article/details/gtqgbpcvqo.html

Ruby: super
来源：http://dali.yonumen.top/Article/details/gtkbxmlwma.html

C#:   base.Greet();
来源：http://dali.shzxlz.cn/Article/details/gtwshdzyvy.html

[G08] 静态方法与属性
来源：http://dali.hnqzz.top/Article/details/gtmazdszul.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jianghu66.top/Article/details/gtumqoabsv.html

PHP:  public static function f() {}
来源：http://dali.gotoacloud.top/Article/details/gtydnrvjdn.html

JS:   static f() {}
来源：http://dali.fzhhl.top/Article/details/gtcylpefrz.html

TS:   static f(): void {}
来源：http://dali.shangyingyoupin.top/Article/details/gttuhbltij.html

Java: static void f() {}
来源：http://dali.shuidangran.top/Article/details/gtxyuyijlw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sysykeji.top/Article/details/gtilwxhqww.html

Ruby: def self.f; end
来源：http://dali.yangfankeji.com/Article/details/gtvbzjllux.html

C#:   public static void F() {}
来源：http://dali.xylfe.cn/Article/details/gtmnxxgahc.html

[G09] 接口 / 抽象类
来源：http://dali.aibaodan.cn/Article/details/gtukpwkzjt.html


<!-- 参考信息 -->