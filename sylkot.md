代发 wailian999

PHP:  implode(",", $items);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxcbgrcje.html

JS:   items.join(",")
来源：http://dali.hywenlv.cn/Article/details/gtbqlbdrgk.html

TS:   items.join(",")
来源：http://dali.yj20258.top/Article/details/gtqamfwabx.html

Java: String.join(",", items)
来源：http://dali.fzhhl.top/Article/details/gtdxfracxa.html

Go:   strings.Join(items, ",")
来源：http://dali.yuxming.cn/Article/details/gtpatkzvno.html

Ruby: items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gtuwwmqaza.html

C#:   string.Join(",", items)
来源：http://dali.zhongyouzk.top/Article/details/gtancjfcrc.html

[E09] 去除所有空白字符
来源：http://dali.jqgfzy.top/Article/details/gtpnfwxlcw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.daxiang520.top/Article/details/gtqdadgbqn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinqigufen.top/Article/details/gtipoecaho.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gogol.net.cn/Article/details/gtfewoqjhg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.haohaochexian.top/Article/details/gtowdkvbfu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shangyingyoupin.top/Article/details/gtcszcvayt.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.tianlin.xyz/Article/details/gthalgorpb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gogol.net.cn/Article/details/gtwlspjvwj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cdnleiting.top/Article/details/gtjbzaxdno.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrpupzloa.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tian-w.cn/Article/details/gtahzxgotk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.andypj.xyz/Article/details/gtsabwxbrj.html

JS:   "7".padStart(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gtpztwsana.html

TS:   "7".padStart(3, "0")
来源：http://dali.316326.xyz/Article/details/gtikeqlxxq.html

Java: String.format("%03d", 7)
来源：http://dali.tianlin.xyz/Article/details/gtpecpcegd.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gaohongyu789.top/Article/details/gticnbotcd.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtozrhjqab.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhengqikj.top/Article/details/gthhlcidyu.html

[E11] 反转字符串
来源：http://dali.dianchejie.cn/Article/details/gtraxvurtt.html

Py:   s[::-1]
来源：http://dali.yuxming.cn/Article/details/gtnwvnhaqr.html

PHP:  strrev($s);
来源：http://dali.nanxuanxn.top/Article/details/gtqteopzef.html

JS:   [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtdxkgcfkd.html

TS:   [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gtkvijpiqj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hammf.cn/Article/details/gtygrthnsj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hongshengwenyu.top/Article/details/gtcdakyvhv.html

Ruby: s.reverse
来源：http://dali.zhengqikj.top/Article/details/gtacthqswd.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.svipenyu.cn/Article/details/gtokwcesfj.html

[E12] 统计某字符出现次数
来源：http://dali.nanxinkj.top/Article/details/gthvahyryx.html

Py:   s.count("a")
来源：http://dali.quarkkingdee.top/Article/details/gtwjhsdpzb.html

PHP:  substr_count($s, "a");
来源：http://dali.haohaochexian.top/Article/details/gtdwowdihd.html

JS:   s.split("a").length - 1
来源：http://dali.yongpay.top/Article/details/gtgyrsbxan.html

TS:   s.split("a").length - 1
来源：http://dali.cdnleiting.top/Article/details/gtewxevyms.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cucudq.cn/Article/details/gtufoyewfl.html

Go:   strings.Count(s, "a")
来源：http://dali.shangyingyoupin.top/Article/details/gtvgwaxbuh.html

Ruby: s.count("a")
来源：http://dali.cdnleiting.top/Article/details/gtdjlwghxu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.chenzaomai.com/Article/details/gtrcytxgcl.html

[E13] 逐字符遍历
来源：http://dali.xziqi.cn/Article/details/gtyesnmpna.html

Py:   for ch in s: print(ch)
来源：http://dali.jianghu66.top/Article/details/gtuubveype.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvmgheovf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuhkrnctk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ivvv.top/Article/details/gtserfazed.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.aibaodan.cn/Article/details/gtidizogxy.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ydzc1.top/Article/details/gtcuutvmvd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cheryme.top/Article/details/gtdnfunucp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yvedp.cn/Article/details/gtxekeeiyh.html

[E14] URL 编码与 Base64
来源：http://dali.jinghuilouyu.cn/Article/details/gttetieync.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hnxiangtu.top/Article/details/gtzkuqpkli.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.daxiang520.top/Article/details/gtjehawfom.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhongyouzk.top/Article/details/gthjxxvqef.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sysykeji.top/Article/details/gtcbthjayy.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpyndkjzp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shangyingyoupin.top/Article/details/gtyqqbvpag.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sufxvd.cn/Article/details/gtktzlegdx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinqigfzy.top/Article/details/gtxrwmoqab.html

[E15] HTML 转义 / 反转义
来源：http://dali.quarkkingdee.top/Article/details/gtdlfvhswr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.tian-w.cn/Article/details/gttwvvpejl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.dashuyun.cn/Article/details/gtcbqsqoce.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyvcwcbya.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhoulong.xyz/Article/details/gtikqzpkjs.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hnxiangtu.top/Article/details/gteogfhewn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.quarkkingdee.top/Article/details/gtiabulqic.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jlsjyb.cn/Article/details/gtrtriwhyj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtwoxkjjuf.html

[E16] 数字千分位
来源：http://dali.zhongyouzk.top/Article/details/gtupjrthaj.html

Py:   f"{1234567:,}"
来源：http://dali.xinyue.icu/Article/details/gtwyuvufzq.html

PHP:  number_format(1234567);
来源：http://dali.iojbl.cn/Article/details/gtgxghwifb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yonumen.top/Article/details/gtturavoyp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.pengpengdd.cyou/Article/details/gtltsvllpt.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yanxiufei.cn/Article/details/gtddmssyje.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tianlin.xyz/Article/details/gtqingauiz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.316326.xyz/Article/details/gtojgdumvb.html

C#:   1234567.ToString("N0")
来源：http://dali.ehwqpu.com/Article/details/gtmzewnkxi.html

[E17] 首字母大写
来源：http://dali.pengpengdd.cyou/Article/details/gtacyaypjy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sweek.top/Article/details/gtsoqsuybp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sxryk.cn/Article/details/gtnicrsszx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gzhubu.top/Article/details/gtzjrgzdgj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuanzx.com/Article/details/gteagesmzc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwjxmbygn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.0kj1m.cn/Article/details/gtgqzknkso.html

Ruby: s.capitalize
来源：http://dali.zhoulong.xyz/Article/details/gttqoaxgww.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.fengsongda.top/Article/details/gtiqoqseku.html

[E18] 模板占位符替换
来源：http://dali.cheryme.top/Article/details/gtkaqfhtkz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.bjfxy.top/Article/details/gtbvmnzhtc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hywenlv.cn/Article/details/gtxcqqjkdr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gtmdszkyni.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gtsnnfdmcs.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gtjjkdtlrx.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jianghu66.top/Article/details/gtqdgmdkvt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj20258.top/Article/details/gtkqjgbxup.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsnxxknxp.html

[E19] 多行文本按行拆分
来源：http://dali.ybcxt.top/Article/details/gthjmlolub.html

Py:   s.splitlines()
来源：http://dali.yj20258888.top/Article/details/gthuyuhbmp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtpnwxhabc.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinqigufen.top/Article/details/gttutmoawy.html

TS:   s.split(/\r?\n/)
来源：http://dali.cdnleiting.top/Article/details/gtjfpgsywk.html

Java: s.lines().toList()
来源：http://dali.meibo888.top/Article/details/gtpcuwxxkr.html

Go:   strings.Split(s, "\n")
来源：http://dali.yongpay.top/Article/details/gtquefqoyg.html

Ruby: s.lines
来源：http://dali.aizwys.cn/Article/details/gtyfuiyafi.html

C#:   s.Split('\n')
来源：http://dali.yuanzhike.top/Article/details/gtlhdmxuzt.html

[E20] 判断字符串是否为空
来源：http://dali.ybcxt.top/Article/details/gtkujexoel.html

Py:   if not s:
来源：http://dali.nwbrower.top/Article/details/gtjpzbbfjk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.mhx1999.top/Article/details/gtxrlmsagr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhoulong.xyz/Article/details/gtjjgyjyit.html

TS:   if (s === "") {}
来源：http://dali.ydzc1.top/Article/details/gtsscvlqwq.html

Java: if (s.isEmpty()) {}
来源：http://dali.0kj1m.cn/Article/details/gtzxwpfwgw.html

Go:   if s == "" {}
来源：http://dali.sufxvd.cn/Article/details/gtzevybonq.html

Ruby: if s.empty?
来源：http://dali.tanke756.top/Article/details/gtfoziqlah.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.dianchejie.cn/Article/details/gtkcfqwhxd.html

[E21] 超长截断加省略号
来源：http://dali.shzxlz.cn/Article/details/gtkahelpdv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yuanzhike.top/Article/details/gtameenecq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.havefunace.top/Article/details/gtggbxcmme.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gtmlbwicjv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gtuwlphltf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nwbrower.top/Article/details/gtbhpyxkig.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ehwqpu.com/Article/details/gtvjugdcxc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gtxuifwqxy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbzeqwuwr.html

[E22] 字节长度与字符长度
来源：http://dali.shuidangran.top/Article/details/gtopywaxsj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.aizwys.cn/Article/details/gtmidggwou.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gtjbjblfuu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.mhx1999.top/Article/details/gtbhakqego.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpeuofcal.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhixingplan.top/Article/details/gtrtdbalcl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cashguo.top/Article/details/gtfxjzfdyn.html

Ruby: s.bytesize;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gtamygdljk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.guannengcc.top/Article/details/gtazzisuaq.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtnvsemexe.html

F. 文件与目录
来源：http://dali.feifeiyinyue.top/Article/details/gtrxhjfiuq.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtwfxaifnv.html

[F01] 读取整个文件
来源：http://dali.ydzc1.top/Article/details/gtrtfelxkw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj20258.top/Article/details/gtbnearxtu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtmpgwhujd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.c1oappe.top/Article/details/gtfdfpccdw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gttrpzhisl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gtzzrjyoxh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhaomingkeji.xyz/Article/details/gtovuwjtmf.html

Ruby: File.read("a.txt")
来源：http://dali.tanke756.top/Article/details/gtnkvtwyrc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtfsjbkhgt.html

[F02] 逐行读取文件
来源：http://dali.sxryk.cn/Article/details/gtxnypwafq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.iojbl.cn/Article/details/gtxbhapleu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hnxiangtu.top/Article/details/gtxktblcxc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jyoumei.cn/Article/details/gtbcxbwqjd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.vqdsnc.cn/Article/details/gtupmensuv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.kuanghao11.cn/Article/details/gtbrshnbwq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yuanzhike.top/Article/details/gtjqjbygyg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.pycfn.com/Article/details/gtvwauqdos.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xziqi.cn/Article/details/gtsvzjkgtg.html

[F03] 写入文件（覆盖）
来源：http://dali.jinqigfzy.top/Article/details/gtswwdbgwp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xuanzx.com/Article/details/gtjxdothfc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.andypj.xyz/Article/details/gtrkanwrno.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gtjspaxtfp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guannengcc.top/Article/details/gtfqqdcgxa.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.feifeiyinyue.top/Article/details/gtootywael.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenjidiqi.icu/Article/details/gtoqgjvvtq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yj202588.top/Article/details/gtnjphexom.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.redwolf501.top/Article/details/gtzcjrajbm.html

[F04] 追加写入文件
来源：http://dali.pycfn.com/Article/details/gtjvmckdrp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.mhx1999.top/Article/details/gtijcpfnip.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cdnleiting.top/Article/details/gtxrgpkfub.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yonumen.top/Article/details/gtczszsgfg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guowangkeji.top/Article/details/gtscxjvodt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zdqjudy.top/Article/details/gttfudryii.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.havefunace.top/Article/details/gtvlssaxsz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cqqwz.cn/Article/details/gtgxytofij.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.fzhhl.top/Article/details/gtiywzqbyv.html

[F05] 判断文件或目录是否存在
来源：http://dali.haohaochexian.top/Article/details/gtknlyagpm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hywenlv.cn/Article/details/gtxtvgjrlg.html

PHP:  file_exists("a.txt");
来源：http://dali.cheryme.top/Article/details/gttzyhfzpe.html

JS:   fs.existsSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gtdfjzjfwt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtrhlsiwsn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gtsrkpspbl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhongyouzk.top/Article/details/gtgvuveema.html

Ruby: File.exist?("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlxzcdvog.html

C#:   File.Exists("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtzgygzdxl.html

[F06] 删除文件
来源：http://dali.fzhhl.top/Article/details/gtrnqnfimi.html

Py:   os.remove("a.txt")
来源：http://dali.sweek.top/Article/details/gtczpdfhyo.html

PHP:  unlink("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtyoueeydx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtnesagovt.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtflceizdr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gtqieacmnf.html

Go:   os.Remove("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gthohvbmbh.html

Ruby: File.delete("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtfrioobpz.html

C#:   File.Delete("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtcbtpxjls.html

[F07] 创建目录（含多级）
来源：http://dali.dashuyun.cn/Article/details/gtmsyfxijz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.andypj.xyz/Article/details/gtydfvpevo.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.tian-w.cn/Article/details/gtbolrkoym.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuxming.cn/Article/details/gtdyaahped.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gaohongyu789.top/Article/details/gtctvkrepj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.aibaodan.cn/Article/details/gtdubwwrhc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhoulong.xyz/Article/details/gtvtphtmum.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hfpthk.cn/Article/details/gtdwhewngv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yuanzhike.top/Article/details/gtcytatcyf.html

[F08] 遍历目录
来源：http://dali.xziqi.cn/Article/details/gtxmaewwjn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sxryk.cn/Article/details/gtluloonnd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shangyingyoupin.top/Article/details/gtpnxwzehy.html

JS:   fs.readdirSync("dir")
来源：http://dali.jqgfzy.top/Article/details/gttdvavzry.html

TS:   fs.readdirSync("dir")
来源：http://dali.hfpthk.cn/Article/details/gtbenltlge.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cashguo.top/Article/details/gtbdewcdrt.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.svipenyu.cn/Article/details/gtkpyhirvw.html

Ruby: Dir.children("dir")
来源：http://dali.fzhhl.top/Article/details/gtpjntwkba.html

C#:   Directory.GetFiles("dir")
来源：http://dali.meibo888.top/Article/details/gtmhiupofq.html

[F09] 获取文件大小
来源：http://dali.pycfn.com/Article/details/gtuncpbwcr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtpmynvwqw.html

PHP:  filesize("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtohdecxaw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.wangdashe.top/Article/details/gtbrofowvv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zycfv.cn/Article/details/gteqlfmgdy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gtuuucfgxd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xylfe.cn/Article/details/gtyjwhuttn.html

Ruby: File.size("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtvlratacs.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.vqdsnc.cn/Article/details/gtvzoontzs.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hongshengwenyu.top/Article/details/gtcljtolkx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtgwrbzzvo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwhseplgl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtwcempzzr.html

TS:   path.extname("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtkkdpiies.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yonumen.top/Article/details/gtgrzpgyxm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtxfqjxopw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gteuglcqce.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtiawwaruo.html

[F11] 复制与移动文件
来源：http://dali.andypj.xyz/Article/details/gtkpebntkt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gtimudbgnc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.pycfn.com/Article/details/gtakhtcpzd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtorlugxjp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gttkwlqyuz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmlzomdpv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yanxiufei.cn/Article/details/gtwdxzpotr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtwjhxfinl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.aizwys.cn/Article/details/gtzhaxawjx.html

[F12] CSV 读写
来源：http://dali.tanke756.top/Article/details/gtkcypzzue.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.bjfxy.top/Article/details/gthxxhlcvx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ydzc1.top/Article/details/gtwgxcxbfd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jlsjyb.cn/Article/details/gtasqbjnup.html

TS:   // 同上
来源：http://dali.hysaishi.cn/Article/details/gtnavuhntd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tianlin.xyz/Article/details/gtqgwpcost.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.redwolf501.top/Article/details/gtsxpzoeoc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.dashuyun.cn/Article/details/gtfypkumie.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tanke756.top/Article/details/gtfkpcaztg.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtgjpjumuc.html

G. 面向对象
来源：http://dali.zhengqikj.top/Article/details/gtmljjanis.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtpaupmkbh.html

[G01] 定义类
来源：http://dali.316326.xyz/Article/details/gtajozlxhq.html

Py:   class User: pass
来源：http://dali.shanyushiyangtech.top/Article/details/gtqfuqupom.html

PHP:  class User {}
来源：http://dali.316326.xyz/Article/details/gtzqsgbfmy.html

JS:   class User {}
来源：http://dali.zhoulong.xyz/Article/details/gtinmqekon.html

TS:   class User { name: string = ""; }
来源：http://dali.jinqigfzy.top/Article/details/gtvrzohzbs.html

Java: class User {}
来源：http://dali.guannengcc.top/Article/details/gtrswgtild.html

Go:   type User struct { Name string }
来源：http://dali.xuetiantiany.cn/Article/details/gtrainpayb.html

Ruby: class User; end
来源：http://dali.jiagoushi.top/Article/details/gtqudtdnpw.html

C#:   class User {}
来源：http://dali.ydzc1.top/Article/details/gtcbffosot.html

[G02] 构造函数
来源：http://dali.svipenyu.cn/Article/details/gtomkeunzk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hfpthk.cn/Article/details/gtnfvjqxcc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrirwskgw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xinyue.icu/Article/details/gthmecarbx.html

TS:   constructor(public name: string) {}
来源：http://dali.meibo888.top/Article/details/gtzeufaved.html

Java: User(String name) { this.name = name; }
来源：http://dali.birdmap.top/Article/details/gtdihxgguo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.tanke756.top/Article/details/gtusfxhhfi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sxryk.cn/Article/details/gtrnrizsvr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.c1oappe.top/Article/details/gtjokzbieq.html

[G03] 实例属性
来源：http://dali.daxiang520.top/Article/details/gtaeolfgnq.html

Py:   self.name = "x"
来源：http://dali.sweek.top/Article/details/gtvqrhkcwu.html

PHP:  public string $name = "x";
来源：http://dali.fengsongda.top/Article/details/gtxizpjkcg.html

JS:   this.name = "x";
来源：http://dali.c1oappe.top/Article/details/gtqxiwargy.html

TS:   name: string = "x";
来源：http://dali.yonumen.top/Article/details/gtuzzwdblt.html

Java: private String name;
来源：http://dali.guowangkeji.top/Article/details/gtlidnuxtd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhixingplan.top/Article/details/gtheqtiole.html

Ruby: @name = "x"
来源：http://dali.gzhubu.top/Article/details/gtmmvvzjqw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shuidangran.top/Article/details/gtcizbcgyn.html

[G04] 定义方法
来源：http://dali.ehwqpu.com/Article/details/gtmivicbxj.html

Py:   def greet(self): return self.name
来源：http://dali.xylfe.cn/Article/details/gtxgwtgpzf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gtxrftvqjo.html

JS:   greet() { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gtpipvwklj.html

TS:   greet(): string { return this.name; }
来源：http://dali.cheryme.top/Article/details/gtpdpvfbdo.html

Java: String greet() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gtajjgzshc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gtxfogfiqn.html

Ruby: def greet; @name; end
来源：http://dali.nwbrower.top/Article/details/gtywqikhcg.html

C#:   public string Greet() => Name;
来源：http://dali.aibaodan.cn/Article/details/gtymqnrkkt.html

[G05] 继承
来源：http://dali.jinqigfzy.top/Article/details/gtmxaimqgp.html

Py:   class Admin(User): pass
来源：http://dali.gaohongyu789.top/Article/details/gtvjwhlsif.html

PHP:  class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gtgcjcoczs.html

JS:   class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gttckghpfq.html

TS:   class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gtngdwwxid.html

Java: class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtjxnmrjsh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hfpthk.cn/Article/details/gtoszhilqk.html

Ruby: class Admin < User; end
来源：http://dali.aizwys.cn/Article/details/gtbolrjtbe.html

C#:   class Admin : User {}
来源：http://dali.ydzc1.top/Article/details/gtgnagxbtb.html

[G06] 重写方法
来源：http://dali.haohaochexian.top/Article/details/gtzoridwbt.html

Py:   def greet(self): return "admin"
来源：http://dali.jiagoushi.top/Article/details/gtozgrlrbr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gtqlwfyfsm.html

JS:   greet() { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gtzpqkmmca.html

TS:   greet(): string { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gtkibkjbut.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gtrjwuyajr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sxryk.cn/Article/details/gtpgcplhqy.html

Ruby: def greet; "admin"; end
来源：http://dali.nwbrower.top/Article/details/gtqugneyop.html


<!-- 参考信息 -->