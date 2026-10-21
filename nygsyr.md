代发 wailian999

TS:   s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gtjvxcdyag.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtmdszgcng.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tanke756.top/Article/details/gtwrgwefeb.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.meibo888.top/Article/details/gtherkrfxc.html

C#:   s.Replace("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtzybkchie.html

[E07] 按分隔符拆分
来源：http://dali.zhixingplan.top/Article/details/gtdzfadmug.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gzhubu.top/Article/details/gtspfznhwf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtoneibtlp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gtwvaoiyxr.html

TS:   s.split(",")
来源：http://dali.jyoumei.cn/Article/details/gtroisvvbo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shangyingyoupin.top/Article/details/gtuzivooej.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xylfe.cn/Article/details/gtpjglhbnj.html

Ruby: s.split(",");  s.split
来源：http://dali.gaohongyu789.top/Article/details/gtkvuffsty.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.gogol.net.cn/Article/details/gtjkjmyzrn.html

[E08] 数组按分隔符合并
来源：http://dali.yj20258888.top/Article/details/gtedykocqk.html

Py:   ",".join(items)
来源：http://dali.sufxvd.cn/Article/details/gteogokdiv.html

PHP:  implode(",", $items);
来源：http://dali.yj202588.top/Article/details/gtvpxsnzuu.html

JS:   items.join(",")
来源：http://dali.daxiang520.top/Article/details/gtbcxghdkr.html

TS:   items.join(",")
来源：http://dali.ehwqpu.com/Article/details/gtjqdeavac.html

Java: String.join(",", items)
来源：http://dali.cheryme.top/Article/details/gtvfmdfome.html

Go:   strings.Join(items, ",")
来源：http://dali.jyoumei.cn/Article/details/gtcatnvjuq.html

Ruby: items.join(",")
来源：http://dali.xuetiantiany.cn/Article/details/gtetgbapkg.html

C#:   string.Join(",", items)
来源：http://dali.jqgufenzy.top/Article/details/gtnzhnitsr.html

[E09] 去除所有空白字符
来源：http://dali.sxryk.cn/Article/details/gtcnnzzcvd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sweek.top/Article/details/gtcwbjyiqp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtkvrtjpox.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yuanzhike.top/Article/details/gtytycnheb.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.smart0.xyz/Article/details/gtnmutwjtl.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.fzhhl.top/Article/details/gtzitfalgp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.birdmap.top/Article/details/gtmvqlflov.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yvedp.cn/Article/details/gtfrqssgrv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.dianchejie.cn/Article/details/gtiewrjhes.html

[E10] 左侧补零 / 定长填充
来源：http://dali.feifeiyinyue.top/Article/details/gtmxjbomoq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.fengsongda.top/Article/details/gtloalnyhx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.tanke756.top/Article/details/gtzppikrsl.html

JS:   "7".padStart(3, "0")
来源：http://dali.svipenyu.cn/Article/details/gtnfvcxiaf.html

TS:   "7".padStart(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gtirqzbnmg.html

Java: String.format("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gtskdwligc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xziqi.cn/Article/details/gtldfmfhqx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gtrbvsqccm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdnoylued.html

[E11] 反转字符串
来源：http://dali.pycfn.com/Article/details/gtwjqwmmge.html

Py:   s[::-1]
来源：http://dali.wangdashe.top/Article/details/gtdumiysmc.html

PHP:  strrev($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtesoujnhq.html

JS:   [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gttsmyaieo.html

TS:   [...s].reverse().join("")
来源：http://dali.iojbl.cn/Article/details/gtgaiqblmv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.dianchejie.cn/Article/details/gtbhlpynic.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.havefunace.top/Article/details/gtoriksucz.html

Ruby: s.reverse
来源：http://dali.pengpengdd.cyou/Article/details/gtbpabbiti.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ybcxt.top/Article/details/gtfqmasmkw.html

[E12] 统计某字符出现次数
来源：http://dali.zhoulong.xyz/Article/details/gttaqugxpe.html

Py:   s.count("a")
来源：http://dali.cheryme.top/Article/details/gtzkqizthd.html

PHP:  substr_count($s, "a");
来源：http://dali.gaohongyu789.top/Article/details/gtqbvpqdot.html

JS:   s.split("a").length - 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdpgaiszf.html

TS:   s.split("a").length - 1
来源：http://dali.iojbl.cn/Article/details/gtjdvugafl.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.dianchejie.cn/Article/details/gtqtbfgrqc.html

Go:   strings.Count(s, "a")
来源：http://dali.quarkkingdee.top/Article/details/gtssdqijbq.html

Ruby: s.count("a")
来源：http://dali.jlsjyb.cn/Article/details/gtblfewyjn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhoulong.xyz/Article/details/gtxrzbnufa.html

[E13] 逐字符遍历
来源：http://dali.yongpay.top/Article/details/gtleivtpef.html

Py:   for ch in s: print(ch)
来源：http://dali.yj20258888.top/Article/details/gtpwkrwski.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnkmlngjg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dianchejie.cn/Article/details/gtnrfbbnke.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tanke756.top/Article/details/gtbdnrnbxl.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuywlewsj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhoulong.xyz/Article/details/gtrizlcvsz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenjidiqi.icu/Article/details/gtdtrxewwm.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gtnejgdmqs.html

[E14] URL 编码与 Base64
来源：http://dali.hysaishi.cn/Article/details/gttxgezeei.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiatdqkaj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yonumen.top/Article/details/gtvrfneikm.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.pengpengdd.cyou/Article/details/gthiykhopt.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.c1oappe.top/Article/details/gtbldwhhkg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.vqdsnc.cn/Article/details/gtalxmrmxm.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinqigufen.top/Article/details/gtrrrearsb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj202588.top/Article/details/gtgayrbgcd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.nanxinkj.top/Article/details/gtvghixthf.html

[E15] HTML 转义 / 反转义
来源：http://dali.yueranfly.top/Article/details/gtrbmnijpk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhoulong.xyz/Article/details/gtthjcfaoh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gaohongyu789.top/Article/details/gtttcfpbyi.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hnqzz.top/Article/details/gtuuczaunv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gtqueheggu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenzaomai.com/Article/details/gtqcbsqcts.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ppjwa.cn/Article/details/gtujxwvhjx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yj20258.top/Article/details/gtxvtetfxd.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cqqwz.cn/Article/details/gtwsreyhiw.html

[E16] 数字千分位
来源：http://dali.shzxlz.cn/Article/details/gtaxtyyaku.html

Py:   f"{1234567:,}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtipvmwfmk.html

PHP:  number_format(1234567);
来源：http://dali.gaohongyu789.top/Article/details/gtsiqdlxjh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jiagoushi.top/Article/details/gtcvdmduaj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthwpeqhpe.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.guannengcc.top/Article/details/gtmjxiyuqs.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.redwolf501.top/Article/details/gtoklrxfyd.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yangfankeji.com/Article/details/gtstqktgtp.html

C#:   1234567.ToString("N0")
来源：http://dali.mhx1999.top/Article/details/gtllaymyto.html

[E17] 首字母大写
来源：http://dali.shanyushiyangkeji.top/Article/details/gtljidhamg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sufxvd.cn/Article/details/gttdbebxrn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.fengsongda.top/Article/details/gtqwzdyylm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fzhhl.top/Article/details/gtyqqkytqn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.haohaochexian.top/Article/details/gthczlgrqo.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.dianchejie.cn/Article/details/gtovstvaal.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.fzhhl.top/Article/details/gtmxisocsf.html

Ruby: s.capitalize
来源：http://dali.jinyuanbaomall.cn/Article/details/gtciqxadcu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jianghu66.top/Article/details/gtjaqntmmr.html

[E18] 模板占位符替换
来源：http://dali.gogol.net.cn/Article/details/gtniogqpul.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.birdmap.top/Article/details/gtyzceswjs.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinqigfzy.top/Article/details/gtodlmfeau.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gtkevcmysk.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gtfutpilbl.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtokclatjg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sysykeji.top/Article/details/gtazvsjuxr.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj202588.top/Article/details/gtypmzltkn.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhixingplan.top/Article/details/gtrwjizmqf.html

[E19] 多行文本按行拆分
来源：http://dali.yuxming.cn/Article/details/gtpsblzjar.html

Py:   s.splitlines()
来源：http://dali.sysykeji.top/Article/details/gtsbfmoepu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.sxryk.cn/Article/details/gtidzlfqkr.html

JS:   s.split(/\r?\n/)
来源：http://dali.redwolf501.top/Article/details/gtjxfrvuey.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhoulong.xyz/Article/details/gtpmvspian.html

Java: s.lines().toList()
来源：http://dali.yj20258.top/Article/details/gtzonjlwat.html

Go:   strings.Split(s, "\n")
来源：http://dali.pengpengdd.cyou/Article/details/gtmkxokfkn.html

Ruby: s.lines
来源：http://dali.sysykeji.top/Article/details/gteqizwqjc.html

C#:   s.Split('\n')
来源：http://dali.jqgfzy.top/Article/details/gtfvvlcvyl.html

[E20] 判断字符串是否为空
来源：http://dali.hongshengwenyu.top/Article/details/gtnakigizc.html

Py:   if not s:
来源：http://dali.wangshuangyany.cn/Article/details/gtevowlsok.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.c1oappe.top/Article/details/gtgukypiyd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ivvv.top/Article/details/gtvkskamaz.html

TS:   if (s === "") {}
来源：http://dali.iojbl.cn/Article/details/gtoyqbcleb.html

Java: if (s.isEmpty()) {}
来源：http://dali.hfpthk.cn/Article/details/gthidcaqao.html

Go:   if s == "" {}
来源：http://dali.shzxlz.cn/Article/details/gtulmkucdy.html

Ruby: if s.empty?
来源：http://dali.tian-w.cn/Article/details/gtowjnejss.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.fzhhl.top/Article/details/gtltazqoui.html

[E21] 超长截断加省略号
来源：http://dali.hongshengwenyu.top/Article/details/gtgnxcwaid.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shuidangran.top/Article/details/gtgotpdpvj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gtpomcwfst.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtjwwfdhdz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gtpkwkvtbm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sxryk.cn/Article/details/gtrrsnheie.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jyoumei.cn/Article/details/gtqwqoydca.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gtukotfuhh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.havefunace.top/Article/details/gtpmriuaur.html

[E22] 字节长度与字符长度
来源：http://dali.chenjidiqi.icu/Article/details/gtvvgcjeaw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ydzc1.top/Article/details/gtwwbbdlqw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gthhsjgyec.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shuidangran.top/Article/details/gtzzclskdz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.smart0.xyz/Article/details/gtfduaqcra.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gaohongyu789.top/Article/details/gtzqvzlzuy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhiwuduotai.top/Article/details/gtnioyotqy.html

Ruby: s.bytesize;  s.length
来源：http://dali.sysykeji.top/Article/details/gtryccbtfj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.wangdashe.top/Article/details/gtthszphcr.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtjoehprvo.html

F. 文件与目录
来源：http://dali.shuidangran.top/Article/details/gtzliuteuv.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtmlsmjnhb.html

[F01] 读取整个文件
来源：http://dali.shangyingyoupin.top/Article/details/gtkedjwgzf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cdnleiting.top/Article/details/gtcsshsheu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtqjltyndw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.guannengcc.top/Article/details/gtdsbtsgmv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shuidangran.top/Article/details/gtfzshnyud.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gtvqtqsqgu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cashguo.top/Article/details/gtpujhapih.html

Ruby: File.read("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtydvrarpz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gttsnnqphf.html

[F02] 逐行读取文件
来源：http://dali.316326.xyz/Article/details/gtbogywwvu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nanxinkj.top/Article/details/gttopoeilb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zdqjudy.top/Article/details/gtcpczvlqx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gtwuoesypk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yangfankeji.com/Article/details/gtagxzcwsx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinqigfzy.top/Article/details/gturiiwnar.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tianlin.xyz/Article/details/gtnbixkhzn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jyoumei.cn/Article/details/gtukjkqhad.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.316326.xyz/Article/details/gtavqbuvrw.html

[F03] 写入文件（覆盖）
来源：http://dali.xylfe.cn/Article/details/gtfftoaprt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sufxvd.cn/Article/details/gteqknbvrs.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.havefunace.top/Article/details/gtnwwsezrm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.kuanghao11.cn/Article/details/gtxlwqxrvp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcznqsheb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hnxiangtu.top/Article/details/gtyxjtlidp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xinyue.icu/Article/details/gtwwgecbpv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yuanzhike.top/Article/details/gtrtpwkngc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yvedp.cn/Article/details/gtylaallst.html

[F04] 追加写入文件
来源：http://dali.meibo888.top/Article/details/gtogfuxkln.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.guowangkeji.top/Article/details/gtlhdhzbve.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.c1oappe.top/Article/details/gtvpqynlgt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yvedp.cn/Article/details/gtibrbrwlk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxinkj.top/Article/details/gtarxrxmwd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttzgrzyne.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtivpdataj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sxryk.cn/Article/details/gtvsvjqzmt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.vqdsnc.cn/Article/details/gtvcjvhcvh.html

[F05] 判断文件或目录是否存在
来源：http://dali.nanxuanxn.top/Article/details/gtatfdacre.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sysykeji.top/Article/details/gtouslapdu.html

PHP:  file_exists("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtkblusils.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtwqgtrxkb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtegvaulvw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gtiazgeubx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyyipqium.html

Ruby: File.exist?("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtnhhxylyk.html

C#:   File.Exists("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtltqnbhfz.html

[F06] 删除文件
来源：http://dali.zycfv.cn/Article/details/gtpuefdzsl.html

Py:   os.remove("a.txt")
来源：http://dali.yj20258.top/Article/details/gtvnzvriop.html

PHP:  unlink("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtzrtfapnc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gtejnwjwkw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtrrbrvlwb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gtwkmxhjax.html

Go:   os.Remove("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtlgakkgkg.html

Ruby: File.delete("a.txt")
来源：http://dali.cashguo.top/Article/details/gtqgpdugjk.html

C#:   File.Delete("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtjbrvppoj.html

[F07] 创建目录（含多级）
来源：http://dali.316326.xyz/Article/details/gtzppoxeyu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinqigfzy.top/Article/details/gtexsgygvz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.guowangkeji.top/Article/details/gtwtxqpjsc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dianchejie.cn/Article/details/gtfwhdixxc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhixingplan.top/Article/details/gtzocawved.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hnxiangtu.top/Article/details/gtdqdrqmkv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.nwbrower.top/Article/details/gthqfaafvd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.pengpengdd.cyou/Article/details/gtabismeof.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jqgfzy.top/Article/details/gtrpupfqkw.html

[F08] 遍历目录
来源：http://dali.ybcxt.top/Article/details/gtwfcoanft.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.vqdsnc.cn/Article/details/gtqrkklgwa.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhongyouzk.top/Article/details/gtjrtnaryy.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtoaaqevda.html

TS:   fs.readdirSync("dir")
来源：http://dali.hfpthk.cn/Article/details/gtacbxrpqs.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttfqpocem.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ivvv.top/Article/details/gtfphpipjq.html

Ruby: Dir.children("dir")
来源：http://dali.guowangkeji.top/Article/details/gtmzkshyet.html

C#:   Directory.GetFiles("dir")
来源：http://dali.kuanghao11.cn/Article/details/gtrcxvepcp.html

[F09] 获取文件大小
来源：http://dali.hfpthk.cn/Article/details/gtfwpsyzsn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtnqwecbzc.html

PHP:  filesize("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtejsilatm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtldgfwrkx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nanxinkj.top/Article/details/gtszzjkreh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gtzutcmcig.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xuanzx.com/Article/details/gtomfovngx.html

Ruby: File.size("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtgvsoehnt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ybcxt.top/Article/details/gtixjquqbx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinqigfzy.top/Article/details/gtcaspcjgq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtqplmvpqy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.meibo888.top/Article/details/gtqhfltgfj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtxurwrpuq.html

TS:   path.extname("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtxzsryyip.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj202588.top/Article/details/gtjiutlbir.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtlwjhbvnh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtwxknousw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtpptwtovw.html

[F11] 复制与移动文件
来源：http://dali.andypj.xyz/Article/details/gtiommtycc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gtktovzarz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sysykeji.top/Article/details/gtndrkfyry.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtctrjseew.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gtmuvwikgo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yonumen.top/Article/details/gtmqtbzysb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinqigufen.top/Article/details/gtghkakwol.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gttqhjgqhq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cucudq.cn/Article/details/gtuabbsmft.html

[F12] CSV 读写
来源：http://dali.316326.xyz/Article/details/gtouotdtnf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nanxuanxn.top/Article/details/gtppeeufik.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nwbrower.top/Article/details/gtghezevte.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cucudq.cn/Article/details/gtrnopnyho.html

TS:   // 同上
来源：http://dali.cdnleiting.top/Article/details/gthawubwvc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ppjwa.cn/Article/details/gtdzvwpttk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.svipenyu.cn/Article/details/gtjezqiqmb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.fengsongda.top/Article/details/gtwgqcvknr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xinyue.icu/Article/details/gtwmkaynoi.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtymsxullw.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gtireuivus.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtiklkdite.html

[G01] 定义类
来源：http://dali.daria6918.cn/Article/details/gtvswctynb.html

Py:   class User: pass
来源：http://dali.zhongyouzk.top/Article/details/gttutomivr.html

PHP:  class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gttqewubut.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gtfzbjcebj.html

TS:   class User { name: string = ""; }
来源：http://dali.jinqigfzy.top/Article/details/gtvejkwshn.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gtoallbxqq.html

Go:   type User struct { Name string }
来源：http://dali.sufxvd.cn/Article/details/gtytbdnqrb.html

Ruby: class User; end
来源：http://dali.gaohongyu789.top/Article/details/gtnhgddvtc.html

C#:   class User {}
来源：http://dali.hnxiangtu.top/Article/details/gtsevqvdhy.html

[G02] 构造函数
来源：http://dali.fengsongda.top/Article/details/gtuaxjlkjx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.meibo888.top/Article/details/gtqqayxuke.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.bjfxy.top/Article/details/gttzzmunew.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shzxlz.cn/Article/details/gtqyzxdowp.html

TS:   constructor(public name: string) {}
来源：http://dali.yj20258.top/Article/details/gtpywjgfkj.html

Java: User(String name) { this.name = name; }
来源：http://dali.yueranfly.top/Article/details/gtgmzofcay.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yongpay.top/Article/details/gtzjvnckvd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.0kj1m.cn/Article/details/gtpbhombth.html

C#:   public User(string name) { Name = name; }
来源：http://dali.smart0.xyz/Article/details/gtisayyjub.html

[G03] 实例属性
来源：http://dali.jiagoushi.top/Article/details/gtwuobozfq.html

Py:   self.name = "x"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiodlmzue.html

PHP:  public string $name = "x";
来源：http://dali.c1oappe.top/Article/details/gtdxlfxnem.html

JS:   this.name = "x";
来源：http://dali.hysaishi.cn/Article/details/gtvbmdeeam.html

TS:   name: string = "x";
来源：http://dali.quarkkingdee.top/Article/details/gtiotacwyv.html

Java: private String name;
来源：http://dali.chenlongwang.top/Article/details/gtqvhrpnqd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yuxming.cn/Article/details/gtlwglrfvu.html

Ruby: @name = "x"
来源：http://dali.cashguo.top/Article/details/gtkqznaulz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjbgnxiuz.html

[G04] 定义方法
来源：http://dali.nwbrower.top/Article/details/gtagudvvld.html

Py:   def greet(self): return self.name
来源：http://dali.feifeiyinyue.top/Article/details/gthgdksqgn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gtwiydibtl.html

JS:   greet() { return this.name; }
来源：http://dali.cheryme.top/Article/details/gtqogpszwc.html

TS:   greet(): string { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtyywgihzo.html

Java: String greet() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtzlvlrtzg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gtsrvzvidh.html

Ruby: def greet; @name; end
来源：http://dali.gogol.net.cn/Article/details/gtetsxkykh.html

C#:   public string Greet() => Name;
来源：http://dali.jianghu66.top/Article/details/gtxpvbzsxb.html

[G05] 继承
来源：http://dali.yongpay.top/Article/details/gtyorodbso.html


<!-- 参考信息 -->