代发 wailian999

Go:   strings.Join(items, ",")
来源：http://dali.jinqigufen.top/Article/details/gtlzopwrlj.html

Ruby: items.join(",")
来源：http://dali.chenzaomai.com/Article/details/gtzmdrnxoh.html

C#:   string.Join(",", items)
来源：http://dali.316326.xyz/Article/details/gthxkrpsud.html

[E09] 去除所有空白字符
来源：http://dali.xziqi.cn/Article/details/gtklcbnegm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinqigfzy.top/Article/details/gtyvsoysrw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ybcxt.top/Article/details/gtzceideeq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcqcgxfbo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.meibo888.top/Article/details/gtrffstwte.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.dashuyun.cn/Article/details/gtqdnvtvyv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zycfv.cn/Article/details/gtwlbwgjdi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yj20258888.top/Article/details/gtlkeaijdn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jyoumei.cn/Article/details/gttpqlmomc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ehwqpu.com/Article/details/gtnelbapcd.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hnxiangtu.top/Article/details/gtnarogbqi.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.smart0.xyz/Article/details/gtakcufvcs.html

JS:   "7".padStart(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gtplaopqps.html

TS:   "7".padStart(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gtcjouwajy.html

Java: String.format("%03d", 7)
来源：http://dali.cqqwz.cn/Article/details/gtwncvgbjm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gtkhmvixzh.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ydzc1.top/Article/details/gtbjhqjwjn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shanyushiyangtech.top/Article/details/gtmsagijfz.html

[E11] 反转字符串
来源：http://dali.meibo888.top/Article/details/gtqwdvqhcd.html

Py:   s[::-1]
来源：http://dali.xziqi.cn/Article/details/gttrmmqnxr.html

PHP:  strrev($s);
来源：http://dali.yuxming.cn/Article/details/gtabludrxs.html

JS:   [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gtpjpfkedk.html

TS:   [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gtwnggrvwj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj202588.top/Article/details/gtjuoihjuq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.wangdashe.top/Article/details/gtwjxkicnc.html

Ruby: s.reverse
来源：http://dali.havefunace.top/Article/details/gtdnolxvlc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jyoumei.cn/Article/details/gtgbtyowxx.html

[E12] 统计某字符出现次数
来源：http://dali.jyoumei.cn/Article/details/gtcgjaoiph.html

Py:   s.count("a")
来源：http://dali.guowangkeji.top/Article/details/gteuvjjhpq.html

PHP:  substr_count($s, "a");
来源：http://dali.jqgufenzy.top/Article/details/gtgcrgzkgu.html

JS:   s.split("a").length - 1
来源：http://dali.birdmap.top/Article/details/gtomlxihrv.html

TS:   s.split("a").length - 1
来源：http://dali.nanxuanxn.top/Article/details/gtayvgmccm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xinyue.icu/Article/details/gtsrpvpzzl.html

Go:   strings.Count(s, "a")
来源：http://dali.yj202588.top/Article/details/gtelrcgobz.html

Ruby: s.count("a")
来源：http://dali.aizwys.cn/Article/details/gtvkfprueq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhengqikj.top/Article/details/gthdhxfdsb.html

[E13] 逐字符遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtsbpzbcbd.html

Py:   for ch in s: print(ch)
来源：http://dali.vqdsnc.cn/Article/details/gtwjrchtld.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shangyingyoupin.top/Article/details/gtyoxjnpsq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cheryme.top/Article/details/gtbhxucwxz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtrazdqwsr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hammf.cn/Article/details/gttezjlsqx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shuidangran.top/Article/details/gtpnqyfhgr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.guannengcc.top/Article/details/gtazbmupfx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yangfankeji.com/Article/details/gtvtntcofo.html

[E14] URL 编码与 Base64
来源：http://dali.hywenlv.cn/Article/details/gtjvyyydse.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.nanxinkj.top/Article/details/gtzstfxpbi.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhengqikj.top/Article/details/gtnvigqhmp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.nwbrower.top/Article/details/gtsrmlqowh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhixingplan.top/Article/details/gtwbextgro.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbdqjlnrm.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sweek.top/Article/details/gtexqlyqpp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sweek.top/Article/details/gtktquooro.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yangfankeji.com/Article/details/gtxddurcfe.html

[E15] HTML 转义 / 反转义
来源：http://dali.fzhhl.top/Article/details/gtuubgjwir.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gzhubu.top/Article/details/gtwwdermgu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cheryme.top/Article/details/gtglfdrueu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.dianchejie.cn/Article/details/gtrxdhmebp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cashguo.top/Article/details/gtiifrzsil.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jiagoushi.top/Article/details/gtaoqvltix.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xziqi.cn/Article/details/gtelejnwgu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwezybuw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.daria6918.cn/Article/details/gtwclehfly.html

[E16] 数字千分位
来源：http://dali.yvedp.cn/Article/details/gtxeuwkznb.html

Py:   f"{1234567:,}"
来源：http://dali.hongshengwenyu.top/Article/details/gtrybbfhgb.html

PHP:  number_format(1234567);
来源：http://dali.tian-w.cn/Article/details/gthejgwthi.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhongyouzk.top/Article/details/gtsseasgxg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jyoumei.cn/Article/details/gtagoeomwo.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hammf.cn/Article/details/gtfvlygmqs.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.guowangkeji.top/Article/details/gtrkfmmsrq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ppjwa.cn/Article/details/gteutbrpad.html

C#:   1234567.ToString("N0")
来源：http://dali.jyoumei.cn/Article/details/gtwyornsgh.html

[E17] 首字母大写
来源：http://dali.fengsongda.top/Article/details/gtkmetzpdr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yj20258.top/Article/details/gtnxwfavqx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yuanzhike.top/Article/details/gtystioohw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwkumldvb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dashuyun.cn/Article/details/gtwktarxfp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hnqzz.top/Article/details/gtzbbfmylh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.quarkkingdee.top/Article/details/gtyzuuffhm.html

Ruby: s.capitalize
来源：http://dali.xuanzx.com/Article/details/gtskdmclez.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yueranfly.top/Article/details/gtewcpekxy.html

[E18] 模板占位符替换
来源：http://dali.cheryme.top/Article/details/gtqisbdktr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xylfe.cn/Article/details/gtmlrvwhgd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.bjfxy.top/Article/details/gteijnebma.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gtjnvtajmx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gtmdbxrbwa.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yj20258.top/Article/details/gtwxmwsvrp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xinyue.icu/Article/details/gtcafnizli.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xziqi.cn/Article/details/gtwejtbizr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.redwolf501.top/Article/details/gtdopfrhzl.html

[E19] 多行文本按行拆分
来源：http://dali.jinqigufen.top/Article/details/gtfqfvtmnp.html

Py:   s.splitlines()
来源：http://dali.aibaodan.cn/Article/details/gtnrpwjtla.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrwlzubli.html

JS:   s.split(/\r?\n/)
来源：http://dali.fengsongda.top/Article/details/gttkdmvhfw.html

TS:   s.split(/\r?\n/)
来源：http://dali.sxryk.cn/Article/details/gtqamvxmcx.html

Java: s.lines().toList()
来源：http://dali.smart0.xyz/Article/details/gtdauhhkqb.html

Go:   strings.Split(s, "\n")
来源：http://dali.yangfankeji.com/Article/details/gtmwypkfjl.html

Ruby: s.lines
来源：http://dali.svipenyu.cn/Article/details/gtdolyqckv.html

C#:   s.Split('\n')
来源：http://dali.xylfe.cn/Article/details/gtyyszfeej.html

[E20] 判断字符串是否为空
来源：http://dali.svipenyu.cn/Article/details/gthhyloelt.html

Py:   if not s:
来源：http://dali.pycfn.com/Article/details/gtwooosazu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.aibaodan.cn/Article/details/gtxzaocaxm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.guowangkeji.top/Article/details/gtrglubewe.html

TS:   if (s === "") {}
来源：http://dali.jinqigufen.top/Article/details/gtpojqzzte.html

Java: if (s.isEmpty()) {}
来源：http://dali.yvedp.cn/Article/details/gtonwlfeid.html

Go:   if s == "" {}
来源：http://dali.wangdashe.top/Article/details/gtxmaomkkj.html

Ruby: if s.empty?
来源：http://dali.chenjidiqi.icu/Article/details/gtdowpveor.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenzaomai.com/Article/details/gtsvzhndla.html

[E21] 超长截断加省略号
来源：http://dali.316326.xyz/Article/details/gtjrgqevoj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hongshengwenyu.top/Article/details/gtobrmnzdd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gtkrhnivkj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtxqtuqfmu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yongpay.top/Article/details/gtpsrnfmup.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtsjwbghnk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hongshengwenyu.top/Article/details/gtcrerpkgx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtaoopdgtr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gtlnatkoyr.html

[E22] 字节长度与字符长度
来源：http://dali.shuidangran.top/Article/details/gtqopggxyn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrtbgwqtt.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgqdyavhq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fzhhl.top/Article/details/gttdhtowpi.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gtkvlsrxlb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ppjwa.cn/Article/details/gthktyltsb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhixingplan.top/Article/details/gtmdjwjgmu.html

Ruby: s.bytesize;  s.length
来源：http://dali.yuxming.cn/Article/details/gtrxruhwfo.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ybcxt.top/Article/details/gtyjhzadez.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtcmvguwct.html

F. 文件与目录
来源：http://dali.dianchejie.cn/Article/details/gtfwsippzi.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtickipbqt.html

[F01] 读取整个文件
来源：http://dali.feifeiyinyue.top/Article/details/gtmfehmwbl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.andypj.xyz/Article/details/gtabnzqsqr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtuctzykcq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ppjwa.cn/Article/details/gtosmyaail.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gtieizuspl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gtiemcoxcx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.meibo888.top/Article/details/gttctnkjon.html

Ruby: File.read("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtalqhzudt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqioeirnq.html

[F02] 逐行读取文件
来源：http://dali.smart0.xyz/Article/details/gtylmxdcjk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.feifeiyinyue.top/Article/details/gtijqahldi.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhixingplan.top/Article/details/gtcehehbby.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangdashe.top/Article/details/gtiwhmryta.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dianchejie.cn/Article/details/gtahrjvmzv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnihyppkr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinqigfzy.top/Article/details/gtkrmibkxw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nanxinkj.top/Article/details/gtdgfrqvkn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthbjumwsq.html

[F03] 写入文件（覆盖）
来源：http://dali.yanxiufei.cn/Article/details/gteuwauekb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.meibo888.top/Article/details/gtefdglfgv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.0kj1m.cn/Article/details/gtjtoxssmy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gtznhziqnk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxxeijskc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.svipenyu.cn/Article/details/gtyhwgtphl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.meibo888.top/Article/details/gtaczcshoz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gteijuqamt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtejhwclia.html

[F04] 追加写入文件
来源：http://dali.sysykeji.top/Article/details/gtzevvutxs.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.birdmap.top/Article/details/gtgjraxrhs.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jqgfzy.top/Article/details/gttefanayu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nwbrower.top/Article/details/gtgjjgwbie.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhongyouzk.top/Article/details/gtxlqkxzhc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.snrcjt.cn/Article/details/gtotcpocta.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.chenzaomai.com/Article/details/gtbsdqavpw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtynnpbkyh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.guannengcc.top/Article/details/gtovvpjosk.html

[F05] 判断文件或目录是否存在
来源：http://dali.meibo888.top/Article/details/gtczcthkvd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hysaishi.cn/Article/details/gtseofaavb.html

PHP:  file_exists("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtmubxgapp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtjhhdxojf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtwrdsemlk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gttnrqrkjq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.mhx1999.top/Article/details/gtyrtjklnz.html

Ruby: File.exist?("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtfzjvlbfu.html

C#:   File.Exists("a.txt")
来源：http://dali.cashguo.top/Article/details/gtbwsqusos.html

[F06] 删除文件
来源：http://dali.316326.xyz/Article/details/gtopqvjaws.html

Py:   os.remove("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gthesygejl.html

PHP:  unlink("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtprkwcngo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtuxuazlgo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtjznkkqux.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gtasujxgsp.html

Go:   os.Remove("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtqxfkuvyu.html

Ruby: File.delete("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtalbxxsum.html

C#:   File.Delete("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtfwxulglp.html

[F07] 创建目录（含多级）
来源：http://dali.yj202588.top/Article/details/gtuyqhxoif.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sufxvd.cn/Article/details/gtvoxdhytj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvnupbuye.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gteqpqpold.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gotoacloud.top/Article/details/gtqdvoaeig.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hfpthk.cn/Article/details/gtibivdedx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.guannengcc.top/Article/details/gtpubxpaii.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xylfe.cn/Article/details/gtgtkiajrf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.guowangkeji.top/Article/details/gtsyqhwfcy.html

[F08] 遍历目录
来源：http://dali.yvedp.cn/Article/details/gtjmlvbbnc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gtlxkwioaw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbjuzgdrz.html

JS:   fs.readdirSync("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gtxbgqsswi.html

TS:   fs.readdirSync("dir")
来源：http://dali.yuanzhike.top/Article/details/gtohhttbti.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenlongwang.top/Article/details/gtllhqyujf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinqigufen.top/Article/details/gtaheykuvf.html

Ruby: Dir.children("dir")
来源：http://dali.hywenlv.cn/Article/details/gtzfshlruj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj20258888.top/Article/details/gtykhqpxmi.html

[F09] 获取文件大小
来源：http://dali.xziqi.cn/Article/details/gtgrqeienm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtguniymnp.html

PHP:  filesize("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtplssgywd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.vqdsnc.cn/Article/details/gtxdnbvmcu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yangfankeji.com/Article/details/gtorndpaha.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gtcizgfghy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinqigufen.top/Article/details/gtiriigncg.html

Ruby: File.size("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtvcwsibnd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.quarkkingdee.top/Article/details/gtijmeyicb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jqgfzy.top/Article/details/gtdxlkjtbh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtyzedgazj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shuidangran.top/Article/details/gtolkfaffp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtimaumqnb.html

TS:   path.extname("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gttcbodgqj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.feifeiyinyue.top/Article/details/gtdpexpbqx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtththikdv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtjitfevyu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtexrrjlts.html

[F11] 复制与移动文件
来源：http://dali.sweek.top/Article/details/gtcanppylz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgzpvaniq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtdazqikfy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gtxrybhkyb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtfqgcyyvk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenjidiqi.icu/Article/details/gtcgefvcpi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.daria6918.cn/Article/details/gtesusdwtk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gtuniffwxy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xziqi.cn/Article/details/gtaxzqjdaz.html

[F12] CSV 读写
来源：http://dali.sufxvd.cn/Article/details/gteeoymdaj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhongyouzk.top/Article/details/gtameunsjt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zdqjudy.top/Article/details/gtcjvaoysr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hammf.cn/Article/details/gtdmkvrhgz.html

TS:   // 同上
来源：http://dali.gaohongyu789.top/Article/details/gtyyjohxon.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.haohaochexian.top/Article/details/gtnkvxezed.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gtpfgxxxqv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jianghu66.top/Article/details/gtpnektczj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.guowangkeji.top/Article/details/gtgmwyxulj.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtisbxbdqj.html

G. 面向对象
来源：http://dali.smart0.xyz/Article/details/gttnlbyzve.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtgnnuqmsn.html

[G01] 定义类
来源：http://dali.jinqigfzy.top/Article/details/gtevvugxep.html

Py:   class User: pass
来源：http://dali.wangdashe.top/Article/details/gtvatacybz.html

PHP:  class User {}
来源：http://dali.jiagoushi.top/Article/details/gtgcallrhq.html

JS:   class User {}
来源：http://dali.cucudq.cn/Article/details/gtbcefhqgg.html

TS:   class User { name: string = ""; }
来源：http://dali.gaohongyu789.top/Article/details/gtnlbkqnms.html

Java: class User {}
来源：http://dali.ybcxt.top/Article/details/gtkhxtwqzq.html

Go:   type User struct { Name string }
来源：http://dali.havefunace.top/Article/details/gtrjqkzqro.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gttpkprhsl.html

C#:   class User {}
来源：http://dali.redwolf501.top/Article/details/gtvmdatusz.html

[G02] 构造函数
来源：http://dali.fzhhl.top/Article/details/gtwwfboipl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.aibaodan.cn/Article/details/gtfytscryl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxzkhpps.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.redwolf501.top/Article/details/gtfyafgmqf.html

TS:   constructor(public name: string) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtvicjmlmt.html

Java: User(String name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gthtmaztbg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sxryk.cn/Article/details/gtpmwpfpxx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.quarkkingdee.top/Article/details/gtkwksmgdv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.haohaochexian.top/Article/details/gtnaoytvxp.html

[G03] 实例属性
来源：http://dali.guannengcc.top/Article/details/gtdsbrtpga.html

Py:   self.name = "x"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrflupivc.html

PHP:  public string $name = "x";
来源：http://dali.meibo888.top/Article/details/gthsrksdat.html

JS:   this.name = "x";
来源：http://dali.xziqi.cn/Article/details/gtaxjsvedy.html

TS:   name: string = "x";
来源：http://dali.jiagoushi.top/Article/details/gtmczcejdt.html

Java: private String name;
来源：http://dali.yj20258888.top/Article/details/gtdmgcbzfw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.mhx1999.top/Article/details/gtluabqaze.html

Ruby: @name = "x"
来源：http://dali.hammf.cn/Article/details/gtvoyaanbo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jqgufenzy.top/Article/details/gtkmelruds.html

[G04] 定义方法
来源：http://dali.316326.xyz/Article/details/gtcfasdixp.html

Py:   def greet(self): return self.name
来源：http://dali.tianlin.xyz/Article/details/gtbckkmifc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gtnwnrlhpg.html

JS:   greet() { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gthuznohqc.html

TS:   greet(): string { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gtsgzlxjkh.html

Java: String greet() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtqsdrdcom.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gtqbahtaup.html

Ruby: def greet; @name; end
来源：http://dali.tian-w.cn/Article/details/gteuqgzusi.html

C#:   public string Greet() => Name;
来源：http://dali.chenjidiqi.icu/Article/details/gtxfnefzny.html

[G05] 继承
来源：http://dali.shanyushiyangkeji.top/Article/details/gtthtrzylv.html

Py:   class Admin(User): pass
来源：http://dali.chenjidiqi.icu/Article/details/gttqzhyqaf.html

PHP:  class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gtxvpgrxrz.html

JS:   class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gtsvkdhexe.html

TS:   class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gtuakijncg.html

Java: class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gtsawfldns.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.fzhhl.top/Article/details/gtvtjwskrg.html

Ruby: class Admin < User; end
来源：http://dali.nwbrower.top/Article/details/gtggqwacgn.html

C#:   class Admin : User {}
来源：http://dali.jqgufenzy.top/Article/details/gtwcyplyik.html

[G06] 重写方法
来源：http://dali.0kj1m.cn/Article/details/gtszmsagvv.html

Py:   def greet(self): return "admin"
来源：http://dali.jianghu66.top/Article/details/gtsysvfgdd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtemyshvyd.html

JS:   greet() { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gtvfjxjplv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gtferwfcfc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtwzqdnvsv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtscrzwdrl.html

Ruby: def greet; "admin"; end
来源：http://dali.yuanzhike.top/Article/details/gtxmkpiokh.html

C#:   public override string Greet() => "admin";
来源：http://dali.ivvv.top/Article/details/gtoqmchyqo.html

[G07] 调用父类方法
来源：http://dali.ehwqpu.com/Article/details/gtcgpdjglh.html

Py:   super().greet()
来源：http://dali.jinqigufen.top/Article/details/gtoaaoladi.html

PHP:  parent::greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxikkiqnz.html


<!-- 参考信息 -->