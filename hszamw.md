代发 wailian999

PHP:  implode(",", $items);
来源：http://dali.gotoacloud.top/Article/details/gtuckuimwu.html

JS:   items.join(",")
来源：http://dali.iojbl.cn/Article/details/gtdyezpiok.html

TS:   items.join(",")
来源：http://dali.aizwys.cn/Article/details/gtzkprjury.html

Java: String.join(",", items)
来源：http://dali.jianghu66.top/Article/details/gtmjrqaiqt.html

Go:   strings.Join(items, ",")
来源：http://dali.bjfxy.top/Article/details/gtsoghvaxs.html

Ruby: items.join(",")
来源：http://dali.guannengcc.top/Article/details/gtmilcnfyk.html

C#:   string.Join(",", items)
来源：http://dali.meibo888.top/Article/details/gthcqmxnxg.html

[E09] 去除所有空白字符
来源：http://dali.shuidangran.top/Article/details/gtfdzjwnoh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.birdmap.top/Article/details/gtsmykbpab.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ydzc1.top/Article/details/gtwttrpvcd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jyoumei.cn/Article/details/gttivcqesw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hnqzz.top/Article/details/gtlfjlrklf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.redwolf501.top/Article/details/gtrjrzlzin.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinqigfzy.top/Article/details/gtqoinzbwg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yj202588.top/Article/details/gtjoyajqzd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yangfankeji.com/Article/details/gtzffwwvmz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yueranfly.top/Article/details/gtghjjhydv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jqgfzy.top/Article/details/gtpumuukgg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jyoumei.cn/Article/details/gtiwbhzcfv.html

JS:   "7".padStart(3, "0")
来源：http://dali.xziqi.cn/Article/details/gttzawdbzu.html

TS:   "7".padStart(3, "0")
来源：http://dali.vqdsnc.cn/Article/details/gtyobrzbll.html

Java: String.format("%03d", 7)
来源：http://dali.yj20258.top/Article/details/gtvteuurbo.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gtmqttdrtd.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.mhx1999.top/Article/details/gtgwaygywj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tian-w.cn/Article/details/gtrpjobegn.html

[E11] 反转字符串
来源：http://dali.shuidangran.top/Article/details/gtwwceprpd.html

Py:   s[::-1]
来源：http://dali.bjfxy.top/Article/details/gtxhsleunj.html

PHP:  strrev($s);
来源：http://dali.hysaishi.cn/Article/details/gtesxxenxv.html

JS:   [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gtdbowawvs.html

TS:   [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gtrnggwnbj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.snrcjt.cn/Article/details/gtfrpbzxqf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.tanke756.top/Article/details/gtgtnmiabz.html

Ruby: s.reverse
来源：http://dali.guannengcc.top/Article/details/gtqgtuxerq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hongshengwenyu.top/Article/details/gtnzkwznsd.html

[E12] 统计某字符出现次数
来源：http://dali.jianghu66.top/Article/details/gtjzeszzrr.html

Py:   s.count("a")
来源：http://dali.hammf.cn/Article/details/gtftjbdmvt.html

PHP:  substr_count($s, "a");
来源：http://dali.c1oappe.top/Article/details/gtfitoaqhk.html

JS:   s.split("a").length - 1
来源：http://dali.yj20258.top/Article/details/gtlpvynrvi.html

TS:   s.split("a").length - 1
来源：http://dali.wangshuangyany.cn/Article/details/gtflqtjggt.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gttbqzukpv.html

Go:   strings.Count(s, "a")
来源：http://dali.hywenlv.cn/Article/details/gtajlbdcfv.html

Ruby: s.count("a")
来源：http://dali.9152youxi.cn/Article/details/gtlcrlhoiv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hfpthk.cn/Article/details/gtpkgfbzgd.html

[E13] 逐字符遍历
来源：http://dali.redwolf501.top/Article/details/gtsujjkniy.html

Py:   for ch in s: print(ch)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtibyraevt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.haohaochexian.top/Article/details/gttaphnejv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xylfe.cn/Article/details/gtkhgtkrxf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.birdmap.top/Article/details/gtekddpszp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.daxiang520.top/Article/details/gtxjwsaxgq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hammf.cn/Article/details/gtxesfxxbq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yongpay.top/Article/details/gtuajhnhmf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shuidangran.top/Article/details/gtumgobhwc.html

[E14] URL 编码与 Base64
来源：http://dali.nanxuanxn.top/Article/details/gteiqetfgu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.guannengcc.top/Article/details/gthzjulyyi.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.tian-w.cn/Article/details/gtavwwjbmo.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbrceuovf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.snrcjt.cn/Article/details/gtzamshiio.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhiwuduotai.top/Article/details/gthjgbadeb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.wangshuangyany.cn/Article/details/gtsekwmlah.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xuanzx.com/Article/details/gtckydupnx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.c1oappe.top/Article/details/gtccvvfuxe.html

[E15] HTML 转义 / 反转义
来源：http://dali.gotoacloud.top/Article/details/gtomhklesg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cashguo.top/Article/details/gtqvqqajes.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yj20258.top/Article/details/gtdvhbjepf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jqgfzy.top/Article/details/gtgxgtainy.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sxryk.cn/Article/details/gtpmmaqbch.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cucudq.cn/Article/details/gthcwhzwkm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yueranfly.top/Article/details/gtcsxnldta.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shuidangran.top/Article/details/gthltallsf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.iojbl.cn/Article/details/gtisswtspi.html

[E16] 数字千分位
来源：http://dali.hysaishi.cn/Article/details/gttzsyeyor.html

Py:   f"{1234567:,}"
来源：http://dali.chenjidiqi.icu/Article/details/gtkvthxktv.html

PHP:  number_format(1234567);
来源：http://dali.jiagoushi.top/Article/details/gtwmxpknss.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ppjwa.cn/Article/details/gtdkfimfwn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.haohaochexian.top/Article/details/gtnpoawksk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.wangshuangyany.cn/Article/details/gthgxdfjkt.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.9152youxi.cn/Article/details/gtejzzicvr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.dianchejie.cn/Article/details/gtmdmgaxdu.html

C#:   1234567.ToString("N0")
来源：http://dali.xinyue.icu/Article/details/gtqkmmrffj.html

[E17] 首字母大写
来源：http://dali.jinqigfzy.top/Article/details/gtewnqmyuq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.iojbl.cn/Article/details/gtwauyqsrd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gzhubu.top/Article/details/gtxyphlahr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.meibo888.top/Article/details/gtmmsukell.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.andypj.xyz/Article/details/gtyyczcwmw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.quarkkingdee.top/Article/details/gtkdnusjiy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.316326.xyz/Article/details/gtmxfgsdcx.html

Ruby: s.capitalize
来源：http://dali.chenzaomai.com/Article/details/gtmplsvdfa.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yongpay.top/Article/details/gtlbgikggh.html

[E18] 模板占位符替换
来源：http://dali.pengpengdd.cyou/Article/details/gtjpjxyxgv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hnqzz.top/Article/details/gtzzqapkoc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jqgfzy.top/Article/details/gtygjlkmes.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gthpvbllpg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gtcgisxqou.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.meibo888.top/Article/details/gtscxmsmdg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gtdqgkqsmg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.fzhhl.top/Article/details/gtievqtftc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zycfv.cn/Article/details/gtqeccccwp.html

[E19] 多行文本按行拆分
来源：http://dali.gotoacloud.top/Article/details/gtexmabmlv.html

Py:   s.splitlines()
来源：http://dali.sweek.top/Article/details/gtyypkymka.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ybcxt.top/Article/details/gtsixafaxx.html

JS:   s.split(/\r?\n/)
来源：http://dali.yvedp.cn/Article/details/gtvcskbdhz.html

TS:   s.split(/\r?\n/)
来源：http://dali.meibo888.top/Article/details/gtzufryvri.html

Java: s.lines().toList()
来源：http://dali.hysaishi.cn/Article/details/gtgnywsfem.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhiwuduotai.top/Article/details/gtvysuomla.html

Ruby: s.lines
来源：http://dali.ppjwa.cn/Article/details/gthhyklrzw.html

C#:   s.Split('\n')
来源：http://dali.gzhubu.top/Article/details/gtfisffrry.html

[E20] 判断字符串是否为空
来源：http://dali.feifeiyinyue.top/Article/details/gtsgbkblfw.html

Py:   if not s:
来源：http://dali.shzxlz.cn/Article/details/gtkfsnmipq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.birdmap.top/Article/details/gtdtoeqppa.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ydzc1.top/Article/details/gtlkxwybgu.html

TS:   if (s === "") {}
来源：http://dali.zhongyouzk.top/Article/details/gthlmtoyuh.html

Java: if (s.isEmpty()) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtyjhblwfk.html

Go:   if s == "" {}
来源：http://dali.ydzc1.top/Article/details/gtvqvlbzim.html

Ruby: if s.empty?
来源：http://dali.shzxlz.cn/Article/details/gtkywkfkvb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkiyscmwx.html

[E21] 超长截断加省略号
来源：http://dali.nanxinkj.top/Article/details/gtybekpjlf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.quarkkingdee.top/Article/details/gtoxubieok.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gtltqdnpqo.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gtszrikcux.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtcvtvfvoz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtjsbenrrc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.daxiang520.top/Article/details/gtyeakkwqq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yueranfly.top/Article/details/gtcsvivayy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ydzc1.top/Article/details/gthqotbbhw.html

[E22] 字节长度与字符长度
来源：http://dali.hammf.cn/Article/details/gtvsswwgqb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.fengsongda.top/Article/details/gtrnrlxrfk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinqigufen.top/Article/details/gtgkqxgfhv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yueranfly.top/Article/details/gtktdkoteb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258888.top/Article/details/gtmzfyiklc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.snrcjt.cn/Article/details/gtpoxcsbea.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gtjwbcxuur.html

Ruby: s.bytesize;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gtsqlnqtcg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jiagoushi.top/Article/details/gtpypkqiuc.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gttbbksrse.html

F. 文件与目录
来源：http://dali.xinyue.icu/Article/details/gtaazxmcff.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtlbyvjsbx.html

[F01] 读取整个文件
来源：http://dali.cqqwz.cn/Article/details/gtmfiobjeq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.quarkkingdee.top/Article/details/gtaqskitem.html

PHP:  file_get_contents("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtdkmjxixw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yj20258888.top/Article/details/gtkbznliqh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gtcgtxuzio.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtimmjpsys.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ybcxt.top/Article/details/gtydenzrtm.html

Ruby: File.read("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtvycwhpcj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtbedcxond.html

[F02] 逐行读取文件
来源：http://dali.jianghu66.top/Article/details/gtavzdinpt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.kuanghao11.cn/Article/details/gtctkvrlyj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cheryme.top/Article/details/gtpthlyqnk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnqzz.top/Article/details/gthtmrbmkq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gotoacloud.top/Article/details/gtaazgkejm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.iojbl.cn/Article/details/gtiarwjlcr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.nanxuanxn.top/Article/details/gtjocirghr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.tian-w.cn/Article/details/gtdqglsrtq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.daxiang520.top/Article/details/gtcixuqjqu.html

[F03] 写入文件（覆盖）
来源：http://dali.svipenyu.cn/Article/details/gtfzwohkgd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.guannengcc.top/Article/details/gtbwlikljl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xuanzx.com/Article/details/gtbudgbyhi.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuanzx.com/Article/details/gtzebuwvxd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhixingplan.top/Article/details/gtqjhfwlwe.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.pengpengdd.cyou/Article/details/gtkitzmjtr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.9152youxi.cn/Article/details/gtdnsbsjpe.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hnqzz.top/Article/details/gtyvurqrwg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenjidiqi.icu/Article/details/gtnwgpwpmz.html

[F04] 追加写入文件
来源：http://dali.xinyue.icu/Article/details/gtctbiioid.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.fzhhl.top/Article/details/gtrmhriito.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yvedp.cn/Article/details/gthiqdanqj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnqzz.top/Article/details/gtbqcfmykd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ivvv.top/Article/details/gtaqkoiflt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.haohaochexian.top/Article/details/gtnntmvfst.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yongpay.top/Article/details/gtmkgvfdkd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.meibo888.top/Article/details/gtcfubixqs.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhongyouzk.top/Article/details/gtkvlgfetm.html

[F05] 判断文件或目录是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtpwleycko.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhiwuduotai.top/Article/details/gtekgxzkum.html

PHP:  file_exists("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtdqjqrosj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtdabtuinw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtzsrmddqa.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtwdwqekzz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcsshdmpl.html

Ruby: File.exist?("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtmzwxdkwf.html

C#:   File.Exists("a.txt")
来源：http://dali.ydzc1.top/Article/details/gthekjsgsi.html

[F06] 删除文件
来源：http://dali.yvedp.cn/Article/details/gtttvhraua.html

Py:   os.remove("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gttpuyjxhy.html

PHP:  unlink("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtnznbvlbn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtkamowofm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gtywbevszf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gtawyjzfjy.html

Go:   os.Remove("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtvswyfwdr.html

Ruby: File.delete("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtcqewvjco.html

C#:   File.Delete("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtpqlxrvvx.html

[F07] 创建目录（含多级）
来源：http://dali.hywenlv.cn/Article/details/gtxwmbxrup.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj20258888.top/Article/details/gtueaavwev.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sysykeji.top/Article/details/gtwbpioafx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gzhubu.top/Article/details/gtvltdhhfc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinghuilouyu.cn/Article/details/gtrpnhtqqj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sufxvd.cn/Article/details/gtrfpxmjhd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ydzc1.top/Article/details/gtflzisjix.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hysaishi.cn/Article/details/gtfcumavjn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yj202588.top/Article/details/gtemjpjfot.html

[F08] 遍历目录
来源：http://dali.redwolf501.top/Article/details/gtbqeblufn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yueranfly.top/Article/details/gtebpshvgd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.bjfxy.top/Article/details/gtquzfgrej.html

JS:   fs.readdirSync("dir")
来源：http://dali.snrcjt.cn/Article/details/gtuwuccwid.html

TS:   fs.readdirSync("dir")
来源：http://dali.sufxvd.cn/Article/details/gtofrcicsl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.smart0.xyz/Article/details/gtbbnmisec.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.wangdashe.top/Article/details/gtgskjewrc.html

Ruby: Dir.children("dir")
来源：http://dali.zhengqikj.top/Article/details/gteaqxdlwp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yonumen.top/Article/details/gtmdwgmqjs.html

[F09] 获取文件大小
来源：http://dali.xuanzx.com/Article/details/gtexkvjxyb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtqkgrxnen.html

PHP:  filesize("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtosddruxv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ppjwa.cn/Article/details/gtbfxaiiei.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sysykeji.top/Article/details/gtttfzxvbu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gtdgtqxgms.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.mhx1999.top/Article/details/gthvrlggpb.html

Ruby: File.size("a.txt")
来源：http://dali.tanke756.top/Article/details/gtpxcfvkrx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.tian-w.cn/Article/details/gtjmaknvzg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nanxuanxn.top/Article/details/gttmpdmihv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtlrqcnsbq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cashguo.top/Article/details/gtmbscwcie.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gthvevamvl.html

TS:   path.extname("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtyjirxczw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jyoumei.cn/Article/details/gtriozivwo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtgzrkzdda.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtigbtjzpq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtosoznglk.html

[F11] 复制与移动文件
来源：http://dali.redwolf501.top/Article/details/gtfbcdvshh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gtvxeuzphp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yvedp.cn/Article/details/gtcltgwwze.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gtaoiztymo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtibhnywud.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.meibo888.top/Article/details/gtkecamrdy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhiwuduotai.top/Article/details/gtzpuixkqt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtjlyodoyb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.haohaochexian.top/Article/details/gtxsrmvgvv.html

[F12] CSV 读写
来源：http://dali.birdmap.top/Article/details/gtdwvkehok.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ivvv.top/Article/details/gtvljovqjv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.andypj.xyz/Article/details/gthygjczjb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tianlin.xyz/Article/details/gtmokugszk.html

TS:   // 同上
来源：http://dali.xylfe.cn/Article/details/gtqryfywsb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinqigufen.top/Article/details/gtwweourrl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjyydtfvp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.wangshuangyany.cn/Article/details/gthixfciua.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gotoacloud.top/Article/details/gtdzkqtopn.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtjcwxmojx.html

G. 面向对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxordfwtb.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtiejmusbb.html

[G01] 定义类
来源：http://dali.dashuyun.cn/Article/details/gtsabgzekl.html

Py:   class User: pass
来源：http://dali.jinghuilouyu.cn/Article/details/gtdygigvbe.html

PHP:  class User {}
来源：http://dali.cdnleiting.top/Article/details/gtoqrtzrhs.html

JS:   class User {}
来源：http://dali.nanxinkj.top/Article/details/gtgxzdagir.html

TS:   class User { name: string = ""; }
来源：http://dali.yvedp.cn/Article/details/gtfkblyiom.html

Java: class User {}
来源：http://dali.pycfn.com/Article/details/gtzfgkodje.html

Go:   type User struct { Name string }
来源：http://dali.ehwqpu.com/Article/details/gtlzkjbhcu.html

Ruby: class User; end
来源：http://dali.zhiwuduotai.top/Article/details/gtpkyjnhgd.html

C#:   class User {}
来源：http://dali.hnqzz.top/Article/details/gtspsnmibc.html

[G02] 构造函数
来源：http://dali.xuanzx.com/Article/details/gtdbvwhsab.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shanyushiyangtech.top/Article/details/gtczvlrsly.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtluwbxztn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hnxiangtu.top/Article/details/gtqmnofipd.html

TS:   constructor(public name: string) {}
来源：http://dali.nanxinkj.top/Article/details/gtcgsmtdva.html

Java: User(String name) { this.name = name; }
来源：http://dali.cdnleiting.top/Article/details/gtpcchcwvm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.dianchejie.cn/Article/details/gtbjnuyfnk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yueranfly.top/Article/details/gtckoipkhp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ivvv.top/Article/details/gtrgnodlca.html

[G03] 实例属性
来源：http://dali.yj20258888.top/Article/details/gtwxhflbyb.html

Py:   self.name = "x"
来源：http://dali.daxiang520.top/Article/details/gtgvdmfjgn.html

PHP:  public string $name = "x";
来源：http://dali.tian-w.cn/Article/details/gtymdbxbqj.html

JS:   this.name = "x";
来源：http://dali.yj20258888.top/Article/details/gtpstaviek.html

TS:   name: string = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gthcyzsoic.html

Java: private String name;
来源：http://dali.birdmap.top/Article/details/gtwgxshxlf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.fzhhl.top/Article/details/gtkiclojbo.html

Ruby: @name = "x"
来源：http://dali.bjfxy.top/Article/details/gtgttosxqu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.haohaochexian.top/Article/details/gtvdanbmcr.html

[G04] 定义方法
来源：http://dali.yvedp.cn/Article/details/gtgztkpngd.html

Py:   def greet(self): return self.name
来源：http://dali.ehwqpu.com/Article/details/gtchayavsy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjadyejjt.html

JS:   greet() { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtsomdfzes.html

TS:   greet(): string { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtyqqhbezw.html

Java: String greet() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gthulzchhl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gtdajbgdes.html

Ruby: def greet; @name; end
来源：http://dali.xuetiantiany.cn/Article/details/gtzhzearam.html

C#:   public string Greet() => Name;
来源：http://dali.shangyingyoupin.top/Article/details/gtlraiswbj.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gtjwzwzjcr.html

Py:   class Admin(User): pass
来源：http://dali.wangdashe.top/Article/details/gtumtvuzmj.html

PHP:  class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gtatyxejmk.html

JS:   class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gtvrkpmfek.html

TS:   class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gtveukcjxg.html

Java: class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gtngswtktb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.fzhhl.top/Article/details/gtdcuimasw.html

Ruby: class Admin < User; end
来源：http://dali.zhoulong.xyz/Article/details/gtutxhkvfv.html

C#:   class Admin : User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtrxkjmjob.html

[G06] 重写方法
来源：http://dali.ydzc1.top/Article/details/gtvpwnijqv.html

Py:   def greet(self): return "admin"
来源：http://dali.fengsongda.top/Article/details/gtylxxwqel.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtseslfeun.html

JS:   greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtrrqxlqes.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gtmbivofpt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gtbnmdcqyz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyvpkurqg.html

Ruby: def greet; "admin"; end
来源：http://dali.yuxming.cn/Article/details/gtdqmebjda.html


<!-- 参考信息 -->