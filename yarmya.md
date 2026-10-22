代发 wailian999

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jlsjyb.cn/Article/details/gtglrqyiav.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.fengsongda.top/Article/details/gtfvjfhmmm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jyoumei.cn/Article/details/gtncjqjgei.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.daria6918.cn/Article/details/gtgrtvyhwx.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hfpthk.cn/Article/details/gtxhpiiidt.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.tanke756.top/Article/details/gtcpurbwig.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xziqi.cn/Article/details/gtugejmayn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jiagoushi.top/Article/details/gtpkppihrg.html

[E10] 左侧补零 / 定长填充
来源：http://dali.316326.xyz/Article/details/gtnyjarsmy.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gthjpiayfx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.birdmap.top/Article/details/gtmtmspkuz.html

JS:   "7".padStart(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gtqhitlqst.html

TS:   "7".padStart(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gtjfskcdet.html

Java: String.format("%03d", 7)
来源：http://dali.shangyingyoupin.top/Article/details/gtfwepfmam.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gtifmycssv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.c1oappe.top/Article/details/gttscvjmmy.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tianlin.xyz/Article/details/gtqkokueqr.html

[E11] 反转字符串
来源：http://dali.xuanzx.com/Article/details/gtfllmcfgf.html

Py:   s[::-1]
来源：http://dali.316326.xyz/Article/details/gtojjmjhvp.html

PHP:  strrev($s);
来源：http://dali.0kj1m.cn/Article/details/gtlpnofknb.html

JS:   [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gtlshykduo.html

TS:   [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gtecloorkr.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.mhx1999.top/Article/details/gtsxrrxabs.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrpgmgvzz.html

Ruby: s.reverse
来源：http://dali.guannengcc.top/Article/details/gtwtpthrek.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.fengsongda.top/Article/details/gtebnzcadl.html

[E12] 统计某字符出现次数
来源：http://dali.bjfxy.top/Article/details/gtepxmnzsq.html

Py:   s.count("a")
来源：http://dali.xuanzx.com/Article/details/gtwmcyusiw.html

PHP:  substr_count($s, "a");
来源：http://dali.yangfankeji.com/Article/details/gtcrtezmvo.html

JS:   s.split("a").length - 1
来源：http://dali.316326.xyz/Article/details/gtigpwtxfd.html

TS:   s.split("a").length - 1
来源：http://dali.cheryme.top/Article/details/gtylibiboz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cdnleiting.top/Article/details/gtjliybvry.html

Go:   strings.Count(s, "a")
来源：http://dali.ybcxt.top/Article/details/gtnrqfzilv.html

Ruby: s.count("a")
来源：http://dali.cheryme.top/Article/details/gtxzqevhjx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.meibo888.top/Article/details/gtpvurhyah.html

[E13] 逐字符遍历
来源：http://dali.guannengcc.top/Article/details/gtxnfanxfe.html

Py:   for ch in s: print(ch)
来源：http://dali.zycfv.cn/Article/details/gtcwdjwdhg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj20258.top/Article/details/gtpbvfuaco.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gttackatul.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ppjwa.cn/Article/details/gtfeqsbdop.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgjmpciip.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.dashuyun.cn/Article/details/gtowhrfgvz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.kuanghao11.cn/Article/details/gtcmdpnmyd.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gtiggipkpz.html

[E14] URL 编码与 Base64
来源：http://dali.zhoulong.xyz/Article/details/gtrrimfutm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gtozjlgrhx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shangyingyoupin.top/Article/details/gteppssbfk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.snrcjt.cn/Article/details/gtnbeoqand.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sweek.top/Article/details/gtogtxcrbq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.birdmap.top/Article/details/gtuetlbmlj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hfpthk.cn/Article/details/gtscjedjae.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shzxlz.cn/Article/details/gtfplfszjr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.iojbl.cn/Article/details/gtjiqnxpyn.html

[E15] HTML 转义 / 反转义
来源：http://dali.hysaishi.cn/Article/details/gtptyhpioc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sufxvd.cn/Article/details/gtmoscuyph.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gtvumdxbrc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.fengsongda.top/Article/details/gtdekjoktu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.0kj1m.cn/Article/details/gttaroqoqo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.andypj.xyz/Article/details/gtqagyhxnb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gtlcnfxqms.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cashguo.top/Article/details/gtrgfzwgno.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.havefunace.top/Article/details/gtyccbddaf.html

[E16] 数字千分位
来源：http://dali.ppjwa.cn/Article/details/gtretwcsst.html

Py:   f"{1234567:,}"
来源：http://dali.yanxiufei.cn/Article/details/gteyecjkxr.html

PHP:  number_format(1234567);
来源：http://dali.hfpthk.cn/Article/details/gtrtyztezk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtswsabnuy.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnxiangtu.top/Article/details/gtuwxqwwua.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.dianchejie.cn/Article/details/gtnybwmocy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.gogol.net.cn/Article/details/gtriugaton.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zycfv.cn/Article/details/gtknihdoox.html

C#:   1234567.ToString("N0")
来源：http://dali.xylfe.cn/Article/details/gtrrfiqfif.html

[E17] 首字母大写
来源：http://dali.jqgfzy.top/Article/details/gtxwdoxyyo.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hongshengwenyu.top/Article/details/gtqgjstjxw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.havefunace.top/Article/details/gtnteekosr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.quarkkingdee.top/Article/details/gtekhlmjno.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.mhx1999.top/Article/details/gteagfikre.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.nwbrower.top/Article/details/gtuvoidzhx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hysaishi.cn/Article/details/gtxlulmimt.html

Ruby: s.capitalize
来源：http://dali.feifeiyinyue.top/Article/details/gtzqntedik.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.dianchejie.cn/Article/details/gtmoxtfxhg.html

[E18] 模板占位符替换
来源：http://dali.pycfn.com/Article/details/gtgnnnyapj.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sysykeji.top/Article/details/gtsjedybvu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenzaomai.com/Article/details/gtsttdykvh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gthqxjtdgu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ppjwa.cn/Article/details/gtcjgzmfux.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hammf.cn/Article/details/gtfouykihf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sxryk.cn/Article/details/gtdzqpdgwu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sysykeji.top/Article/details/gtzxdecpvi.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.0kj1m.cn/Article/details/gtaxpmtcvj.html

[E19] 多行文本按行拆分
来源：http://dali.xinyue.icu/Article/details/gtafxknfpl.html

Py:   s.splitlines()
来源：http://dali.xuanzx.com/Article/details/gtuijbuwej.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.wangdashe.top/Article/details/gttugfbjnz.html

JS:   s.split(/\r?\n/)
来源：http://dali.cheryme.top/Article/details/gtevzwnqbp.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnbsuxvjv.html

Java: s.lines().toList()
来源：http://dali.haohaochexian.top/Article/details/gtosvzolff.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gtebuvksgt.html

Ruby: s.lines
来源：http://dali.jlsjyb.cn/Article/details/gtprdhmgkg.html

C#:   s.Split('\n')
来源：http://dali.cucudq.cn/Article/details/gtolscwcso.html

[E20] 判断字符串是否为空
来源：http://dali.sxryk.cn/Article/details/gtmubuyucv.html

Py:   if not s:
来源：http://dali.yvedp.cn/Article/details/gtjncyxcmc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ppjwa.cn/Article/details/gtymbiqlmw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhongyouzk.top/Article/details/gtdeyduslx.html

TS:   if (s === "") {}
来源：http://dali.dianchejie.cn/Article/details/gtahrsugtc.html

Java: if (s.isEmpty()) {}
来源：http://dali.tian-w.cn/Article/details/gtpgzldzcb.html

Go:   if s == "" {}
来源：http://dali.pycfn.com/Article/details/gtoxkknvct.html

Ruby: if s.empty?
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmbaxtbed.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nanxuanxn.top/Article/details/gtdddjzzhl.html

[E21] 超长截断加省略号
来源：http://dali.chenzaomai.com/Article/details/gtiepeshuu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xuetiantiany.cn/Article/details/gtntqmnzvx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yj20258.top/Article/details/gtnphuvtza.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gtgnbyqlbl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gteetbylkr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sweek.top/Article/details/gtluuhtgsu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shzxlz.cn/Article/details/gtevyayygd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.aizwys.cn/Article/details/gttivynhpf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtivoadnua.html

[E22] 字节长度与字符长度
来源：http://dali.cdnleiting.top/Article/details/gtrglnoepj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtgygmulux.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gttznuiifb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gttrhumnga.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aibaodan.cn/Article/details/gtcwujzyba.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinqigufen.top/Article/details/gtlwjfcrrl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.316326.xyz/Article/details/gtudxkybzl.html

Ruby: s.bytesize;  s.length
来源：http://dali.jiagoushi.top/Article/details/gtczkmqphk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfvulbdny.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtzlkssbtd.html

F. 文件与目录
来源：http://dali.jqgufenzy.top/Article/details/gtnloebglo.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtvhagydzp.html

[F01] 读取整个文件
来源：http://dali.shzxlz.cn/Article/details/gtxsfmxodc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jiagoushi.top/Article/details/gtgkuwhstm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtaqesnbdk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shangyingyoupin.top/Article/details/gttxtksdnd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.birdmap.top/Article/details/gthjbbqxgp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gtvwbxehft.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenlongwang.top/Article/details/gtdblrkhwy.html

Ruby: File.read("a.txt")
来源：http://dali.havefunace.top/Article/details/gtubuhakfi.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtpxdppbfy.html

[F02] 逐行读取文件
来源：http://dali.wangdashe.top/Article/details/gtjdtqfxnj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nanxinkj.top/Article/details/gtcnqzidld.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shzxlz.cn/Article/details/gtuezaltnq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xylfe.cn/Article/details/gttpcpgevk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gotoacloud.top/Article/details/gtgseibftc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinqigfzy.top/Article/details/gtttklciug.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hywenlv.cn/Article/details/gtksbjlafk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.meibo888.top/Article/details/gtzaesswrl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.316326.xyz/Article/details/gtsecfyptu.html

[F03] 写入文件（覆盖）
来源：http://dali.hnqzz.top/Article/details/gtdwmizzwl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtraolhmhp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.bjfxy.top/Article/details/gtawdhbsqn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gttoaqqftl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.redwolf501.top/Article/details/gtmicueyte.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cdnleiting.top/Article/details/gtvyljzrff.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.quarkkingdee.top/Article/details/gtbqwjblbr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.guowangkeji.top/Article/details/gtnpsicirn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenjidiqi.icu/Article/details/gtecgtrrow.html

[F04] 追加写入文件
来源：http://dali.aibaodan.cn/Article/details/gtaxxoymay.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.iojbl.cn/Article/details/gtqjmugptr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yongpay.top/Article/details/gtwhbvsxxo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fzhhl.top/Article/details/gtawgyslpn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jyoumei.cn/Article/details/gtszoiqmdh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hysaishi.cn/Article/details/gthotzytlc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yuxming.cn/Article/details/gtebvsgvvj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkwjgtdhd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hysaishi.cn/Article/details/gtduesuhsz.html

[F05] 判断文件或目录是否存在
来源：http://dali.shangyingyoupin.top/Article/details/gtudpmoifo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.c1oappe.top/Article/details/gtqkszgsdv.html

PHP:  file_exists("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtjamhoyid.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtaokuswhm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtafiroteb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gttwoioarz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.mhx1999.top/Article/details/gtnjjuwdyz.html

Ruby: File.exist?("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gttqdxihnn.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtcxykuwba.html

[F06] 删除文件
来源：http://dali.andypj.xyz/Article/details/gtwwevlegq.html

Py:   os.remove("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtsdpnqtby.html

PHP:  unlink("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtdmtuqjwx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gthnhvqawr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtwpugekta.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gtbgcxebeh.html

Go:   os.Remove("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtjnpqzjrq.html

Ruby: File.delete("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtvdjgmaht.html

C#:   File.Delete("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtadkubxlu.html

[F07] 创建目录（含多级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsdfospep.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hnxiangtu.top/Article/details/gtgkoazymt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenjidiqi.icu/Article/details/gtbacbivis.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenlongwang.top/Article/details/gtpaftslze.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuanzx.com/Article/details/gthlwgjjbe.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xinyue.icu/Article/details/gtmlajnxoe.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.guannengcc.top/Article/details/gtpdworqfi.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xziqi.cn/Article/details/gtvvmteflh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gtjqpanadk.html

[F08] 遍历目录
来源：http://dali.guowangkeji.top/Article/details/gturlavakm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.vqdsnc.cn/Article/details/gtkvhvksgn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hywenlv.cn/Article/details/gtakupvnad.html

JS:   fs.readdirSync("dir")
来源：http://dali.redwolf501.top/Article/details/gtjerzxfvo.html

TS:   fs.readdirSync("dir")
来源：http://dali.mhx1999.top/Article/details/gtmkeloeyj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhiwuduotai.top/Article/details/gtegksfwgl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtxutqwvdh.html

Ruby: Dir.children("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtenvysihw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtlvplreob.html

[F09] 获取文件大小
来源：http://dali.quarkkingdee.top/Article/details/gtzvujbvmc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtgjtftajt.html

PHP:  filesize("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtozipgsjx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sweek.top/Article/details/gtkoraetvr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.haohaochexian.top/Article/details/gteswoefda.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gtrtkusoww.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.quarkkingdee.top/Article/details/gtoxpfbxjq.html

Ruby: File.size("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtmrbszulv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sysykeji.top/Article/details/gtocifugjf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tanke756.top/Article/details/gtxwmsqecb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtfawtrqnv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtigrojeoa.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gthznxvvoq.html

TS:   path.extname("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwwcjmrql.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hammf.cn/Article/details/gtqnyxywlw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtdsuomsbn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtxabkcaeb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtadffyall.html

[F11] 复制与移动文件
来源：http://dali.jlsjyb.cn/Article/details/gtabtmslht.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtieyceetr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tianlin.xyz/Article/details/gtkimrdgyp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gttpasmmgr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfpihuvw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hysaishi.cn/Article/details/gtfkvvatvl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.fengsongda.top/Article/details/gtmuprftvl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtfujifjfn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xylfe.cn/Article/details/gtrfqpimnp.html

[F12] CSV 读写
来源：http://dali.ybcxt.top/Article/details/gtacdsazua.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.mhx1999.top/Article/details/gtdofvkjrm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gotoacloud.top/Article/details/gtajslzbch.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ybcxt.top/Article/details/gtbizrnuqk.html

TS:   // 同上
来源：http://dali.chenzaomai.com/Article/details/gthlzpgwdr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tian-w.cn/Article/details/gthynofqvx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gotoacloud.top/Article/details/gthkpfymxp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sufxvd.cn/Article/details/gttoaqfivq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhongyouzk.top/Article/details/gtgrktbmyx.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtctjeyvmi.html

G. 面向对象
来源：http://dali.havefunace.top/Article/details/gtfblzabgh.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtcjheqfxt.html

[G01] 定义类
来源：http://dali.xinyue.icu/Article/details/gtdcgcqifj.html

Py:   class User: pass
来源：http://dali.chenjidiqi.icu/Article/details/gtlraqlgbp.html

PHP:  class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjaxukbzc.html

JS:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gtkmuhgkri.html

TS:   class User { name: string = ""; }
来源：http://dali.chenzaomai.com/Article/details/gtnedfuwlg.html

Java: class User {}
来源：http://dali.daxiang520.top/Article/details/gtpxcumekt.html

Go:   type User struct { Name string }
来源：http://dali.yonumen.top/Article/details/gtbxodozal.html

Ruby: class User; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaxdlsihd.html

C#:   class User {}
来源：http://dali.cucudq.cn/Article/details/gtwzmleryo.html

[G02] 构造函数
来源：http://dali.vqdsnc.cn/Article/details/gtgelpsyhb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsfkjqsht.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.guannengcc.top/Article/details/gtzkzzdqgp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gtfufpewkp.html

TS:   constructor(public name: string) {}
来源：http://dali.dianchejie.cn/Article/details/gtqbivfjgh.html

Java: User(String name) { this.name = name; }
来源：http://dali.snrcjt.cn/Article/details/gtfbegcqts.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yj20258.top/Article/details/gtqahofcfj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.svipenyu.cn/Article/details/gtcydptbpk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zycfv.cn/Article/details/gtfwnbbfpc.html

[G03] 实例属性
来源：http://dali.nanxuanxn.top/Article/details/gtjrvngedq.html

Py:   self.name = "x"
来源：http://dali.iojbl.cn/Article/details/gtdtwuvuta.html

PHP:  public string $name = "x";
来源：http://dali.iojbl.cn/Article/details/gtpwtbrphh.html

JS:   this.name = "x";
来源：http://dali.xziqi.cn/Article/details/gtrzbxumej.html

TS:   name: string = "x";
来源：http://dali.jiagoushi.top/Article/details/gtxllopcsp.html

Java: private String name;
来源：http://dali.316326.xyz/Article/details/gtcnexorfq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinyuanbaomall.cn/Article/details/gtimwtakar.html

Ruby: @name = "x"
来源：http://dali.ivvv.top/Article/details/gtlwxqrrbb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.mhx1999.top/Article/details/gtzjhbijmq.html

[G04] 定义方法
来源：http://dali.jianghu66.top/Article/details/gtldezwcfz.html

Py:   def greet(self): return self.name
来源：http://dali.shuidangran.top/Article/details/gtmhqpcnim.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gtqqkituws.html

JS:   greet() { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gtdtgctkff.html

TS:   greet(): string { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gtlnirtjkj.html

Java: String greet() { return name; }
来源：http://dali.yj202588.top/Article/details/gtrfiaqihe.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gtmrtwcbnn.html

Ruby: def greet; @name; end
来源：http://dali.snrcjt.cn/Article/details/gtprserecj.html

C#:   public string Greet() => Name;
来源：http://dali.nanxinkj.top/Article/details/gtorapconh.html

[G05] 继承
来源：http://dali.nanxuanxn.top/Article/details/gtitgsjqwb.html

Py:   class Admin(User): pass
来源：http://dali.jlsjyb.cn/Article/details/gtdeexbdig.html

PHP:  class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gtcopzitjq.html

JS:   class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gthjiygwrj.html

TS:   class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gtlcbqpaxj.html

Java: class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gtfrrcgtyq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xziqi.cn/Article/details/gtnhinshcf.html

Ruby: class Admin < User; end
来源：http://dali.nwbrower.top/Article/details/gtoqatdviw.html

C#:   class Admin : User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtxjyqczbb.html

[G06] 重写方法
来源：http://dali.bjfxy.top/Article/details/gtwgmcqija.html

Py:   def greet(self): return "admin"
来源：http://dali.shzxlz.cn/Article/details/gtvxrggtle.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtbprahvmd.html

JS:   greet() { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gtnvfyyntn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtovvxszpr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gtevayuwaa.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj20258888.top/Article/details/gtrewciigi.html

Ruby: def greet; "admin"; end
来源：http://dali.smart0.xyz/Article/details/gtouewisxt.html

C#:   public override string Greet() => "admin";
来源：http://dali.yuxming.cn/Article/details/gtpbtojgee.html

[G07] 调用父类方法
来源：http://dali.xziqi.cn/Article/details/gtefrbdzdx.html

Py:   super().greet()
来源：http://dali.9152youxi.cn/Article/details/gturagtdug.html

PHP:  parent::greet();
来源：http://dali.jinqigufen.top/Article/details/gtowjboofj.html

JS:   super.greet();
来源：http://dali.chenzaomai.com/Article/details/gtreslqput.html

TS:   super.greet();
来源：http://dali.jinqigfzy.top/Article/details/gtvdtrqrnd.html

Java: super.greet();
来源：http://dali.svipenyu.cn/Article/details/gtfkgzquch.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hysaishi.cn/Article/details/gtkhxoowyo.html


<!-- 参考信息 -->